Раздел продажи земельных участков
---------------------------------

```xml
<?xml version="1.0" encoding="utf-8" ?>
<rfl-feed xmlns="http://www.realtymag.ru/rfl">
	<offer internal-id="1086">
		<!--
			объект сделки
			строго ограниченные значения: земельный участок
		-->
		<property-type>квартира</property-type>
		<!--
			тип сделки
			строго ограниченные значения: продажа
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
				строго ограниченные значения: Россия
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
				строго ограниченные значения: RUR, RUB, USD, EUR
			-->
			<currency>RUR</currency>
		</price>
		<!--
			имеется свидетельство о собственности
			строго ограниченные значения: да, нет, true, false, 1, 0, +, -
		-->
		<ownership-confirmed>да</ownership-confirmed>
		<buildings-info>
			<area>
				<!--
					площадь строений на участке
					double
				-->
				<value>43,2</value>
				<!--
					единицы измерения
					строго ограниченные значения: кв.м
				-->
				<unit>кв.м</unit>
			</area>
			<!--
				характер строений на участке
				строго ограниченные значения: капитальные, некапитальные
			-->
			<type>капитальные</type>
		</buildings-info>
		<lot-info>
			<area>
				<!--
					общая площадь участка
					integer
				-->
				<value>8</value>
				<!--
					единицы измерения
					строго ограниченные значения: сотка, га
				-->
				<unit>сотка</unit>
			</area>
			<!--
				кадастровый номер участка
				текст
			-->
			<registration-number>50:16:0102014:2</registration-number>
			<!--
				назначение земельного участка
				строго ограниченные значения: ИЖС, коммерческое строительство, жилищное строительство, садоводчество, огородничество, сельхозназначение, бизнес-цели
			-->
			<appropriation>ИЖС</appropriation>
			<!--
				категория земельного участка
				строго ограниченные значения: с/х назначения, поселений, промышленности, особо охраняемых территорий, лесного фонда, водного фонда, прочие
			-->
			<category>поселений</category>
			<!--
				рельеф земельного участка
				строго ограниченные значения: равнинный, небольшой уклон, холмистый, горный, смешанный, прибрежная полоса
			-->
			<relief>равнинный</relief>
			<!--
				наличие лена на земельном участке
				строго ограниченные значения: на всем участке, частичное наличие, нет
			-->
			<forest>нет</forest>
			<!--
				газоснабжение подведено к участку
				строго ограниченные значения: да, нет, true, false, 1, 0, +, -
			-->
			<gas-supply>да</gas-supply>
			<!--
				электроснабжение подведено к участку
				строго ограниченные значения: да, нет, true, false, 1, 0, +, -
			-->
			<energy-supply>да</energy-supply>
			<!--
				наличие водоснабжения
				строго ограниченные значения: да, нет, true, false, 1, 0, +, -
			-->
			<water-supply>да</water-supply>
			<!--
				канализация
				строго ограниченные значения: центральная, индивидуальная
			-->
			<sewerage>индивидуальная</sewerage>
		</lot-info>
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
				строго ограниченные значения: частное лицо, агентство, маклер, инвестор, застройщик, частный риэлтор, собственник
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