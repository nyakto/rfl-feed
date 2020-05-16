Раздел продажи гаражей
----------------------

```xml
<?xml version="1.0" encoding="utf-8" ?>
<rfl-feed xmlns="http://www.realtymag.ru/rfl">
    <offer internal-id="1083">
        <!--
            объект сделки
            строго ограниченные значения:
            * гараж
            * бокс капитальный
            * бокс некапитальный
            * металлический гараж
            * машиноместо
            * парковочное место
        -->
        <property-type>гараж</property-type>
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
                должно соответствовать названию населенного пункта на сайте www.realtymag.ru
                (без префикса типа населенного пункта)
            -->
            <locality-name>Изобильный</locality-name>
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
        <remoteness>
            <!--
                удаленность в минутах
                integer
            -->
            <value>5</value>
            <!--
                тип удаленности
                строго ограниченные значения:
                * пешком до метро
                * общественным транспортом
                * электричкой
                * пешком до остановки
            -->
            <type>пешком до метро</type>
        </remoteness>
        <price>
            <!--
                цена
                integer
            -->
            <value>500 000</value>
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
        <video-review>
            <!--
                прямая ссылка на видео с вашим объектом с YouTube, без сокращений и счётчиков переходов
                cсылка должна быть без параметра таймкода, например &t=2s
                текст
            -->
            <youtube-video-review-url>http://youtu.be/iwGFalTRHDA</youtube-video-review-url>     
            <!--
                Возможность показать недвижимость по видео-звонку, например в WhatsApp, Skype, Viber или FaceTime
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
            <online-show>да</online-show>
        </video-review>
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
        <parking-info>
            <!--
                название гаражного комплекса
                текст
            -->
            <name>ГК Машиностроителей</name>
            <!--
                тип гаражного комплекса
                строго ограниченные значения:
                * многоуровневый паркинг
                * гаражный комплекс
                * подземный паркинг
                * ряды отдельных боксов
                * открытая стоянка
            -->
            <type>подземный паркинг</type>
            <!--
                этажность здания
                integer
            -->
            <floors>23</floors>
            <!--
                наличие лифта
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
            <elevator>да</elevator>
            <!--
                наличие видеонаблюдения
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
            <video-security>да</video-security>
            <!--
                наличие автомойки
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
            <cleaning-service>да</cleaning-service>
            <!--
                наличие шиномонтажа
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
            <tire-fitting-service>да</tire-fitting-service>
            <!--
                наличие магазина автозапчастей
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
            <parts-shop>нет</parts-shop>
            <!--
                наличие автосервиса
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
            <service>да</service>
        </parking-info>
        <garage-info>
            <area>
                <!--
                    площадь гаража
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
                этаж
                integer
            -->
            <floor>3</floor>
            <!--
                размер гаража
                текст
            -->
            <size>2.64м x 3м</size>
            <!--
                высота гаража
                текст
            -->
            <height>2,85м</height>
            <!--
                наличие освещения
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
            <illumination>да</illumination>
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
            <water-supply>нет</water-supply>
            <!--
                автоматические ворота
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
            <automatic-doors>нет</automatic-doors>
            <!--
                смотровая яма
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
            <observation-pit>нет</observation-pit>
            <!--
                погреб
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
            <vault>да</vault>
        </garage-info>
        <!--
            дополнительные сведения
            текст
        -->
        <additional-info>дополнительная информация</additional-info>
        <!--
            фото
            url, максимум 50 фоторгафий
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
