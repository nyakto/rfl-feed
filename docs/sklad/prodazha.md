Раздел продажи склада
---------------------

```xml
<?xml version="1.0" encoding="utf-8" ?>
<rfl-feed xmlns="http://www.realtymag.ru/rfl">
	<offer internal-id="1083">
		<!--
			объект сделки
			строго ограниченные значения: склад
		-->
		<property-type>склад</property-type>
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
				адрес
				текст
			-->
			<address>ул. Красноармейская, д. 5</address>
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
			<!--
				станция метро
				должна соответствовать названию станции метро для заданного города на сайте www.realtymag.ru
			-->
			<metro>Авиамоторная</metro>
		</location-info>
		<price>
			<!--
				цена
				integer
			-->
			<value>2 500 0000</value>
			<!--
				валюта
				строго ограниченные значения: RUR, RUB, USD, EUR
			-->
			<currency>RUR</currency>
			<!--
				цена
				текст
			-->
			<comment>Цена не обсуждается</comment>
		</price>
		<building-info>
			<!--
				место размещения торгового помещения
				строго ограниченные значения: отдельное капитальное здание, отдельное некапитальное здание, жилой дом, административное здание, торговый центр, торгово-развлекательный центр, офисный центр, рынок, многофункциональный комплекс, торгово-офисный центр, бинес-центр, складской комплекс, ОСЗ
			-->
			<type>складской комплекс</type>
			<!--
				этажность здания
				integer
			-->
			<floors>23</floors>
			<!--
				лифт в здании
				строго ограниченные значения: пассажирский, грузовой, пассажирский и грузовой, грузопассажирский, несколько пассажирских, несколько пассажирских и грузовой
			-->
			<elevator>пассажирский</elevator>
		</building-info>
		<storage-facility-info>
			<!--
				тип складского помещения
				строго ограниченные значения: капитальное, ангарного типа, открытая площадка
			-->
			<type>ангарного типа</type>
			<!--
				категория складского помещения
				строго ограниченные значения: отапливаемый, неотапливаемый, открытая площадка, холодильник
			-->
			<category>неотапливаемый</category>
			<area>
				<!--
					общая площадь
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
				этаж
				integer
			-->
			<floor>3</floor>
			<!--
				высота потолков
				double
			-->
			<ceiling-height>3</ceiling-height>
			<!--
				тип пола
				текст
			-->
			<floor-type>наливной</floor-type>
			<!--
				нагрузка на пол
				текст
			-->
			<floor-capacity>обычная</floor-capacity>
			<!--
				центральная вентилляция
				строго ограниченные значения: да, нет, true, false, 1, 0, +, -
			-->
			<central-ventilation>да</central-ventilation>
			<!--
				отопление
				строго ограниченные значения: центральное, индивидуальное
			-->
			<heating>центральное</heating>
			<!--
				кондиционирование
				строго ограниченные значения: центральное, индивидуальное
			-->
			<air-conditioning>центральное</air-conditioning>
			<!--
				подведенная электрическая мощность (кВт)
				double
			-->
			<power>300</power>
			<!--
				наличие санузла
				строго ограниченные значения: да, нет, true, false, 1, 0, +, -
			-->
			<sannode>нет</sannode>
			<!--
				горячее водоснабжение
				строго ограниченные значения: да, нет, true, false, 1, 0, +, -
			-->
			<hot-water-supply>да</hot-water-supply>
			<!--
				холодное водоснабжение
				строго ограниченные значения: да, нет, true, false, 1, 0, +, -
			-->
			<cold-water-supply>да</cold-water-supply>
			<!--
				наличие автоматических ворот докового типа
				строго ограниченные значения: да, нет, true, false, 1, 0, +, -
			-->
			<large-automatic-gates>да</large-automatic-gates>
			<!--
				наличие погрузочно-разгрузочных площадок регулируемой высоты
				строго ограниченные значения: да, нет, true, false, 1, 0, +, -
			-->
			<tipping-site-with-adjustable-height>нет</tipping-site-with-adjustable-height>
			<!--
				место для разгрузки большегрузных автомобилей
				строго ограниченные значения: да, нет, true, false, 1, 0, +, -
			-->
			<tipping-site-for-trucks>да</tipping-site-for-trucks>
			<!--
				наличие железнодорожной ветки
				строго ограниченные значения: да, нет, true, false, 1, 0, +, -
			-->
			<railroad-way-access>да</railroad-way-access>
			<!--
				наличие пандуса для разгрузки товара
				строго ограниченные значения: да, нет, true, false, 1, 0, +, -
			-->
			<pandus-for-unload>нет</pandus-for-unload>
			<!--
				наличие пожарной сигнализации
				строго ограниченные значения: да, нет, true, false, 1, 0, +, -
			-->
			<fire-alarm>да</fire-alarm>
		</storage-facility-info>
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