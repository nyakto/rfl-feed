Раздел продажи коммерческой недвижимости
----------------------------------------

```xml
<?xml version="1.0" encoding="utf-8" ?>
<rfl-feed xmlns="http://www.realtymag.ru/rfl">
    <offer internal-id="1083">
        <!--
            объект сделки
            строго ограниченные значения:
            * помещение
        -->
        <property-type>помещение</property-type>
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
            <value>25 000 000</value>
            <!--
                валюта
                строго ограниченные значения:
                * RUR
                * RUB
                * USD
                * EUR
            -->
            <currency>RUR</currency>
            <!--
                цена
                текст
            -->
            <comment>Цена не обсуждается</comment>
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
            оплата за жилищно-коммунальные услуги
            набор строго ограниченных значений:
            * холодное водоснабжение
            * горячее водоснабжение
            * электроэнергию
        -->
        <municipal-payments>
            <for>холодное водоснабжение</for>
            <for>горячее водоснабжение</for>
            <for>электроэнергию</for>
            <!--
                оплата производится по счетчикам
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
            <by-meter>да</by-meter>
            <!--
                фиксированная ставка ЖКУ в месяц
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
            <fixed-rate>нет</fixed-rate>
        </municipal-payments>
        <building-info>
            <!--
                место размещения торгового помещения
                строго ограниченные значения:
                * отдельное капитальное здание
                * отдельное некапитальное здание
                * жилой дом
                * административное здание
                * офисный центр
                * офисно-жилой комплекс
                * офисно-деловой центр
                * офисно-складской комплекс
                * бизнес-центр
                * торговый центр
                * торгово-офисный центр
                * торгово-развлекательный центр
                * многофункциональный комплекс
                * бизнес-парк
                * технопарк
                * бизнес-инкубатор
                * складской комплекс
                * рынок
                * особняк
                * производственное здание
                * имущественный комплекс
                * ОСЗ
            -->
            <type>офисно-деловой центр</type>
            <!--
                этажность здания
                integer
            -->
            <floors>23</floors>
            <!--
                лифт в здании
                строго ограниченные значения:
                * пассажирский
                * пассажирский и грузовой
                * грузовой
                * грузопассажирский
                * несколько пассажирских
                * несколько пассажирских и грузовой
            -->
            <elevator>пассажирский</elevator>
            <!--
                парковка
                строго ограниченные значения:
                * подземная
                * наземная
                * многоуровневая
            -->
            <parking>подземная</parking>
            <!--
                наличие пунктов общепита в здании
                набор строго ограниченных значений:
                * столовая
                * кафе
                * ресторан
                * ресторан быстрого обслуживания
                * продовольственный магазин
            -->
            <food>
                <option>столовая</option>
                <option>кафе</option>
                <option>ресторан</option>
                <option>ресторан быстрого обслуживания</option>
                <option>продовольственный магазин</option>
            </food>
            <security>
                <!--
                    охрана
                    строго ограниченные значения:
                    * служба охраны
                    * вахтер
                    * милиция
                -->
                <type>служба охраны</type>
                <!--
                    видеонаблюдение
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
                <video>да</video>
            </security>
        </building-info>
        <commercial-space-info>
            <area>
                <!--
                    общая площадь
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
                назначение помещения
                набор строго ограниченных значений:
                * помещения свободного назначения
                * ПСН
                * производство
                * кафе
                * ресторан
                * бар
                * сфера услуг
                * гостиница
                * хостел
                * отель
                * автомойка
                * салон красоты
                * парикмахерская

                обязательно должна быть указано хотя бы одно значение!
                максимум можно указать 2 значения!
            -->
            <appropriation>
                <option>ресторан</option>
                <option>бар</option>
            </appropriation>
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
                отделка
                строго ограниченные значения:
                * евроремонт в соответствии с классом здания
                * евроремонт
                * чистовая отделка
                * косметический ремонт
                * требуется капитальный ремонт
                * требуется реконструкция
            -->
            <decoration>евроремонт</decoration>
            <!--
                центральная вентилляция
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
            <central-ventilation>да</central-ventilation>
            <!--
                отопление
                строго ограниченные значения:
                * центральное
                * индивидуальное
            -->
            <heating>центральное</heating>
            <!--
                кондиционирование
                строго ограниченные значения:
                * центральное
                * индивидуальное
            -->
            <air-conditioning>центральное</air-conditioning>
            <!--
                интернет подведен к помещению
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
            <internet>да</internet>
            <!--
                телефон подведен к помещению
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
            <phone>да</phone>
            <!--
                подведенная электрическая мощность (кВт)
                double
            -->
            <power>300</power>
            <!--
                наличие отдельного входа для разгрузки товара
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
            <way-for-unload>да</way-for-unload>
            <!--
                наличие пандуса для разгрузки товара
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
            <pandus-for-unload>нет</pandus-for-unload>
            <!--
                наличие пожарной сигнализации
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
            <fire-alarm>да</fire-alarm>
        </commercial-space-info>
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
