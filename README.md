Realty Feed Language
====================

* Фид проверяется каждые 3 часа запросом с заголовком ```If-Modified-Since``` (который обязательно должен корректно обрабатываться).
* Кажное объявление проходит проверку на соответствие обязательным полям, отсутствию URL в текстовых полях и т.п.
* Допустимо использование пустых полей, они будут игнорироваться.
* Желательно отдавать фид в ```Content-Encoding``` ```gzip``` или ```deflate``` для ускорения его передачи по сети, либо сжимать сформированный файл фида утилитой [gzip].

Структура файла фида:
```xml
<?xml version="1.0" encoding="utf-8" ?>
<rfl-feed xmlns="http://www.realtymag.ru/rfl">
	<offer internal-id="1083">
		<!--
			объект сделки
			допустимые значения зависят от раздела
		-->
		<property-type>квартира</property-type>
		<!--
			тип сделки
			допустимые значения зависят от раздела
		-->
		<offer-type>продажа</offer-type>
		<!--
			дата создания объявления
			дата в формате ISO 8601
		-->
		<creation-date>2013-08-21T15:40:32+04:00</creation-date>
		<!--
			дата последнего обновления объявления
			дата в формате ISO 8601
		-->
		<last-update-date>2013-09-04T07:42:11+04:00</last-update-date>
		<!--
			поля, соответствующие разделу
		-->
		<!--
			контактная информация
		-->
		<contact-info>
            <!--
                статус контактного лица
                строго ограниченные значения: частное лицо, агентство, маклер, инвестор, застройщик, частный риэлтор, собственник
            -->
            <dealer>собственник</dealer>
            <!--
                имя контактного лица
                текст
            -->
            <name>Андрей</name>
            <!--
                телефоны контактного лица
                на данный момент используется только первый телефон
            -->
            <phones>
                <item>+7 (963) 326-12-75</item>
            </phones>
            <!--
                email контактного лица
                текст
            -->
            <email>pupkin@vasily.ru</email>
            <!--
                UIN (ICQ) контактного лица
                текст
            -->
            <uin>32612751</uin>
            <!--
                комментарий по способу связи
                текст
            -->
            <comment>Звонить с 9-00 до 21-00</comment>
        </contact-info>
	</offer>
</rfl-feed>
```

**Внимание!** Указывать *xmlns="http://www.realtymag.ru/rfl"* обязательно, иначе фид не будет распознан!

[gzip]: http://www.gnu.org/software/gzip/manual/gzip.html
