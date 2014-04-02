Раздел продажи дач
------------------

```xml
<?xml version="1.0" encoding="utf-8" ?>
<rfl-feed xmlns="http://www.realtymag.ru/rfl">
	<offer internal-id="1083">
		<!--
			объект сделки
			строго ограниченные значения:
			* дача
			* садовый домик
			* дачный домик
			* дачный дом
			* летний домик
		-->
		<property-type>дача</property-type>
		<!--
			тип сделки
			строго ограниченные значения:
			* продажа
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
		<!-- информация о месторасположении -->
		<location-info>
			<!--
				страна
				строго ограниченные значения:
				* Россия
			-->
			<country>Россия</country>
			<!--
				регион
				должен соответствовать регионам на сайте www.realtymag.ru
				для Москвы - Москва
				для Санкт-Петербурга - Санкт-Петербург
			-->
			<region>Ставропольский край</region>
			<!--
				административный район
				текст
			-->
			<district>Изобильненский район</district>
			<!--
				название населенного пункта
				должно соответствовать названию населенного пункта на сайте www.realtymag.ru (без префикса типа населенного пункта)
			-->
			<locality-name>Изобильный</locality-name>
			<!--
				район города
				текст
			-->
			<sub-locality-name>РЭО</sub-locality-name>
			<!--
				направление
				текст
			-->
			<direction>Волоколамское</direction>
			<!--
				шоссе
				текст
			-->
			<highway>Рижское</highway>
			<!--
				название ближайшего населенного пункта
				текст
			-->
			<nearby-locality-name>Солнечнодольск</nearby-locality-name>
			<!--
				адрес
				текст
			-->
			<address>п. Майский, снт Дружба, ул. 8 марта, д. 13</address>
			<!--
				широта
				double
			-->
			<latitude>55.724799</latitude>
			<!--
				долгота
				double
			-->
			<longitude>37.633095</longitude>
		</location-info>
		<price>
			<!--
				цена
				integer
			-->
			<value>2 500 000</value>
			<!--
				валюта
				строго ограниченные значения:
				* RUR
				* RUB
				* USD
				* EUR
			-->
			<currency>RUR</currency>
		</price>
		<!--
			класс недвижимости
			строго ограниченные значения:
			* эконом-класс
			* бизнес-класс
			* премиум
		-->
		<offer-class>эконом-класс</offer-class>
		<!--
			срочная сделка
			строго ограниченные значения:
			* да
			* нет
			* true
			* false
			* 1
			* 0
			* +
			* -
		-->
		<urgent-deal>нет</urgent-deal>
		<!--
			готовность объекта
			строго ограниченные значения:
			* на стадии закладки
			* незавершенное строительство
			* готов к проживанию
			* готов под чистовую отделку
			* используется для проживания
		-->
		<ready-state>готов к проживанию</ready-state>
		<!--
			торг уместен
			строго ограниченные значения:
			* да
			* нет
			* true
			* false
			* 1
			* 0
			* +
			* -
		-->
		<haggling-allowed>да</haggling-allowed>
		<!--
			рассрочка платежа
			строго ограниченные значения:
			* да
			* нет
			* true
			* false
			* 1
			* 0
			* +
			* -
		-->
		<credit>нет</credit>
		<!--
			возможен подъезд в зимнее время
			строго ограниченные значения:
			* да
			* нет
			* true
			* false
			* 1
			* 0
			* +
			* -
		-->
		<accessible-in-winter>да</accessible-in-winter>
		<house-info>
			<area>
				<!--
					площадь дома
					double
				-->
				<value>43,2</value>
				<!--
					единицы измерения
					строго ограниченные значения:
					* кв.м
				-->
				<unit>кв.м</unit>
			</area>
			<!--
				этажность дома
				integer
			-->
			<floors>2</floors>
			<!--
				количество комнат
				integer
			-->
			<rooms-count>5</rooms-count>
			<!--
				фундамент
				текст
			-->
			<foundation>ленточный монолитный</foundation>
			<!--
				материал стен
				текст
			-->
			<walls-material>малые бетонные блоки</walls-material>
			<!--
				кровля
				текст
			-->
			<roof-material>профнастил</roof-material>
			<!--
				перекрытия
				текст
			-->
			<blocking-material>монолит бетон</blocking-material>
			<!--
				ограждение
				строго ограниченные значения:
				* нет
				* металлический забор
				* кирпичный забор
				* деревянный забор
				* сетка
			-->
			<barrier>металлический забор</barrier>
			<!--
				наличие электроснабжения
				строго ограниченные значения:
				* да
				* нет
				* true
				* false
				* 1
				* 0
				* +
				* -
			-->
			<energy-supply>да</energy-supply>
			<!--
				наличие водоснабжения
				строго ограниченные значения:
				* да
				* нет
				* true
				* false
				* 1
				* 0
				* +
				* -
			-->
			<water-supply>да</water-supply>
			<!--
				наличие отопления
				строго ограниченные значения:
				* да
				* нет
				* true
				* false
				* 1
				* 0
				* +
				* -
			-->
			<heat-supply>да</heat-supply>
			<!--
				наличие гаоснабжения
				строго ограниченные значения:
				* да
				* нет
				* true
				* false
				* 1
				* 0
				* +
				* -
			-->
			<gas-supply>да</gas-supply>
			<!--
				наличие канализации
				строго ограниченные значения:
				* да
				* нет
				* true
				* false
				* 1
				* 0
				* +
				* -
			-->
			<sewerage>да</sewerage>
			<!--
				вывоз мусора
				строго ограниченные значения:
				* да
				* нет
				* true
				* false
				* 1
				* 0
				* +
				* -
			-->
			<garbage-disposal>нет</garbage-disposal>
			<!--
				наличие гаража
				строго ограниченные значения:
				* да
				* нет
				* true
				* false
				* 1
				* 0
				* +
				* -
			-->
			<garage>да</garage>
			<!--
				наличие телефона
				строго ограниченные значения:
				* да
				* нет
				* true
				* false
				* 1
				* 0
				* +
				* -
			-->
			<phone>нет</phone>
		</house-info>
		<lot-info>
			<area>
				<!--
					общая площадь участка
					integer
				-->
				<value>8</value>
				<!--
					единицы измерения
					строго ограниченные значения:
					* сотка
				-->
				<unit>сотка</unit>
			</area>
			<!--
				баня
				строго ограниченные значения:
				* да
				* нет
				* true
				* false
				* 1
				* 0
				* +
				* -
			-->
			<bath-house>да</bath-house>
			<!--
				дополнительные строения на участке
				текст
			-->
			<additional-buildings>теплица</additional-buildings>
		</lot-info>
		<infrastructure-info>
			<!--
				наличие объектов торговли
				строго ограниченные значения:
				* да
				* нет
				* true
				* false
				* 1
				* 0
				* +
				* -
			-->
			<store-units>да</store-units>
			<!--
				наличие развлекательных комплексов
				строго ограниченные значения:
				* да
				* нет
				* true
				* false
				* 1
				* 0
				* +
				* -
			-->
			<entertainment-units>нет</entertainment-units>
			<!--
				наличие спортивных сооружений
				строго ограниченные значения:
				* да
				* нет
				* true
				* false
				* 1
				* 0
				* +
				* -
			-->
			<sport-units>нет</sport-units>
			<!--
				орана
				строго ограниченные значения:
				* да
				* нет
				* true
				* false
				* 1
				* 0
				* +
				* -
			-->
			<security>да</security>
			<!--
				описание инфраструктуры
				текст
			-->
			<description></description>
		</infrastructure-info>
		<!--
			дополнительные сведения
			текст
		-->
		<additional-info>дополнительная информация</additional-info>
		<!--
			фото
			url, максимум 7 фоторгафий
		-->
		<photo>
			<item>http://www.realtymag.ru/img/notice/kvartira/prodazha/0001.jpg</item>
			<item>http://www.realtymag.ru/img/notice/kvartira/prodazha/0002.jpg</item>
			<item>http://www.realtymag.ru/img/notice/kvartira/prodazha/0003.jpg</item>
			<item>http://www.realtymag.ru/img/notice/kvartira/prodazha/0004.jpg</item>
			<item>http://www.realtymag.ru/img/notice/kvartira/prodazha/0005.jpg</item>
			<item>http://www.realtymag.ru/img/notice/kvartira/prodazha/0006.jpg</item>
			<item>http://www.realtymag.ru/img/notice/kvartira/prodazha/0007.jpg</item>
		</photo>
		<contact-info>
			<!--
				статус контактного лица
				строго ограниченные значения:
				* частное лицо
				* агентство
				* маклер
				* инвестор
				* застройщик
				* частный риэлтор
				* собственник
			-->
			<dealer>собственник</dealer>
			<!--
				имя контактного лица
				текст
			-->
			<name>Станислав</name>
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
