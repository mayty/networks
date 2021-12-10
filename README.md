
![network topology](1.4.png)

<details>
    <summary>1 вариант</summary>
    <details>
        <summary>1. Сколько может быть vlan?</summary>
        2^12
    </details>
    <details>
        <summary>2. Назовите 3 режима port-security</summary>
        Protect, restrict, shutdown
    </details>
    <details>
        <summary>3. Настроить обозначенный порт на работы</summary>
        (вроде транк просто настроить и м. б. создать vlan-ы) (int Fa0/1; switchport mode trunk; switchport trunk allowed vlan 20, 10, 2)
    </details>
    <details>
        <summary>4. 3 технологии резервирования каналов (?для серверов)</summary>
        AFT, SFT, NFT only
    </details>
    <details>
        <summary>5. Назвать частоту работы dialup</summary>
        0-4kHz
    </details>
    <details>
        <summary>6. 3 технологии вида NBMA</summary>
        FR, ATM and xDSL
    </details>
    <details>
        <summary>7. Что содержится в заголовке  ячейки ATM</summary>
        VPI (Virtual Path Identifier), VCI (Virtual Channel Identifier)
    </details>
    <details>
        <summary>8. Структура домена ISDN</summary>

![ISDN structure](1.8.png)
    </details>
    <details>
        <summary>9. Что делает  ADSL сплиттер?</summary>
        разделение диапазона частот
    </details>
    <details>
        <summary>10. store-forward как работает?</summary>
        коммутатор получает пакет полностью перед его ретрансляцией; анализируется адрес назначения и проверяется контрольная сумма
    </details>
    <details>
        <summary>11. High-end производители активных сетевых устройств 3 шт</summary>
        Cisco, Intel, HP
    </details>
    <details>
        <summary>12. wifi стандарты, которые совместимы с 802.11b</summary>
        точно 802.11g, неточно: 802.11n и 802.11ad
    </details>
</details>

<details>
    <summary>2 вариант</summary>
    <details>
        <summary>1. Аналог 802.1Q</summary>
        3COM VLT, Cisco ISL, Cisco VTP
    </details>
    <details>
        <summary>2. Виды STP, применимые к топологии на доске</summary>
        PVST+ и возможно что-то еще
    </details>
    <details>
        <summary>3. Сконфигурировать порт свича 1</summary>
    </details>
    <details>
        <summary>4. Приведите пример использования связи порта при агрегации каналов</summary>
    </details>
    <details>
        <summary>5. 2 типа виртуальных цепей</summary>
        PVCs, SVCs
    </details>
    <details>
        <summary>6. нарисовать структуру домена ADSL</summary>

![ADSL structure](2.6.png)
    </details>
    <details>
        <summary>7. Скорость DS0</summary>
        64Кбит/c
    </details>
    <details>
        <summary>8. Пример адреса ATM</summary>
    </details>
    <details>
        <summary>9. Метод Cut Through</summary>
        Cut Through -- без промежуточной буферизации -- коммутатор не ожидает получения пакета целиком; анализируется лишь адрес назначения
    </details>
    <details>
        <summary>10. Количество непересекающихся каналов в 802.11b</summary>
        3
    </details>
    <details>
        <summary>11. </summary>
    </details>
    <details>
        <summary>12. Что входит в состав телекоммуникационного оборудования?</summary>
        связное оборудование, телевизионное и сетевое
    </details>
</details>

<details>
    <summary>3 вариант</summary>
    <details>
        <summary>1. Масштабируемые vlan</summary>
        Private VLAN
    </details>
    <details>
        <summary>2. Настроить классическую маршрутизацию</summary>
    </details>
    <details>
        <summary>3. Bridge ID</summary>
        Bridge Priority (2 байта) Bridge Address (6 байт) (802.1D)
    </details>
    <details>
        <summary>4. Пример подинтерфейса на Linux</summary>
        eth0.10
    </details>
    <details>
        <summary>5. ADSL расшифровка</summary>
        Asymmetric Digital Subscriber Loop
    </details>
    <details>
        <summary>6. Какие протоколы устанавливают соответствие между виртуальными цепями и IP-адресами</summary>
        В случае с SVCs без ATM-адресов не обойтись. А вот в случае с PVCs обычно используют «напрашивающуюся» специфическую особенность NBMA-топологий, которая заключается в том, что IP-адреса можно связывать не с ATM-адресами, а с PVCs. При этом так же возможны два варианта связывания: статическое, то есть «вручную», и динамическое -- с помощью особого варианта протокола ARP под названием InARP (Inverse ARP)
    </details>
    <details>
        <summary>7. Т1</summary>
        T1 = DS1 + <1DS0, 1,544 Mbit/s
    </details>
    <details>
        <summary>8. Офисные АТС на английском</summary>
        IP PBX
    </details>
    <details>
        <summary>9. Тип модуляции в 802.11a</summary>
        OFDM
    </details>
    <details>
        <summary>10. SERDES - что это такое?</summary>
        Пара функциональных блоков, используются для преобразования данных между последовательным и параллельным интерфейсами в обоих направлениях
    </details>
    <details>
        <summary>11. Пример L2-L3 технологий</summary>
        коммутатор и маршрутизатор?
    </details>
    <details>
        <summary>12. Индикаторы LED на NIC</summary>
        link LED, speed LED и activity LED
    </details>
</details>

<details>
    <summary>4 вариант</summary>
    <details>
        <summary>1. Настроить  link aggregation по топологии</summary>
    </details>
    <details>
        <summary>2. Назвать 3 СПЕЦИАЛИЗИРОВАННЫХ vlan</summary>
        native, private, provided, ?mangament
    </details>
    <details>
        <summary>3. Какие роли у портов у корневого моста STP?</summary>
        designated
    </details>
    <details>
        <summary>4. Состав заголовка 802.1q</summary>
        tpid, up, cfi, vid
    </details>
    <details>
        <summary>5. Из чего состоит E1?</summary>
        ds1 +2ds0
    </details>
    <details>
        <summary>6. LANE - расшифровка</summary>
        LAN Emulation
    </details>
    <details>
        <summary>7. Состав заголовка 802.11b</summary>
        Signal, Service, Length, CRC
    </details>
    <details>
        <summary>8. Модуляция ADSL</summary>
        DMT
    </details>
    <details>
        <summary>9. К какому телекоммуникационному оборудованию относится стационарный телефон</summary>
        связное оборудование
    </details>
    <details>
        <summary>10. Нарисовать пример стека коммутаторов</summary>

![routers stack](4.10.png)
    </details>
    <details>
        <summary>11. Что такое slip</summary>
        проскальзывание
    </details>
    <details>
        <summary>12. 3 различия l2 и l3 коммутаторов</summary>
        l3 коммутаторы работают с пакетами и виртуальными l3 интерфейсами + ?
    </details>
</details>

<details>
    <summary>5 вариант</summary>
    <details>
        <summary>1. 3 протокола агрегирования</summary>
        LACP, PaGP, SLA
    </details>
    <details>
        <summary>2. Что такое native-vlan?</summary>
        предназначен для передачи нетегированного трафика
    </details>
    <details>
        <summary>3. Конфигурация Router-on-stick</summary>
    </details>
    <details>
        <summary>4. При каких условиях данный порт(отметил на топологии) будет root?</summary>
    </details>
    <details>
        <summary>5. Статистическое мультиплексирование в WAN</summary>
        При статистическом (statistical) мультиплексировании соотношение количеств тайм-слотов цифровых каналов в смешанном потоке соответствует востребованности этих цифровых каналов
    </details>
    <details>
        <summary>6. 2 вида интерфейса ATM</summary>
        UNI, NNI
    </details>
    <details>
        <summary>7. Нарисовать point-to-multipoint FR</summary>

![point-to-multipoint FR](5.7.png)
    </details>
    <details>
        <summary>8. Расшифровать SNAP</summary>
        Subnetwork Access Protocol
    </details>
    <details>
        <summary>9. Что такое MSDU?</summary>
        MAC service data unit (MSDU, e.g. an Ethernet frame)
    </details>
    <details>
        <summary>10. К какому типу телеком. оборудования относится коммутатор, записанный посредством PoE?</summary>
    </details>
    <details>
        <summary>11. Что такое mediaconverter</summary>
        осуществляют преобразование СрПД
    </details>
    <details>
        <summary>12. backplane на маршрутизаторе</summary>
        пакеты проходят через связывающую все порты общую высокоскоростную шину
    </details>
</details>

<details>
    <summary>6 вариант</summary>
    <details>
        <summary>1. Protect port security описать</summary>
    </details>
    <details>
        <summary>2. Настроить ivr(on stick)</summary>
    </details>
    <details>
        <summary>3. При каких условиях порты designated</summary>
    </details>
    <details>
        <summary>4. Технологии используемые для кластеризации маршрутизаторов </summary>
        HSRP, GLBP, VRRP, IRDP
    </details>
    <details>
        <summary>5. Скорость e3</summary>
        34,368 Mbit/s
    </details>
    <details>
        <summary>6. Модуляции xdsl</summary>
        CAP, TCPAM, DMT, QAM
    </details>
    <details>
        <summary>7. Isdn схема</summary>
    </details>
    <details>
        <summary>8. CPE расшифровать</summary>
        Customer Premises Equipment
    </details>
    <details>
        <summary>9. Области частот в wifi</summary>
        2.4 и 5 ггц
    </details>
    <details>
        <summary>10. </summary>
    </details>
    <details>
        <summary>11. Определение силового оборудования</summary>
        Под силовым оборудованием принято понимать технические средства для обеспечения телекоммуникационного оборудования питающим напряжением
    </details>
    <details>
        <summary>12. Для чего ПЗУ на сетевом адаптере</summary>
        ПЗУ для хранения настроек по умолчанию (обычно подключается по шине I2C)
    </details>
</details>

![Another topology](7.2.png)

<details>
    <summary>7 вариант</summary>
    <details>
        <summary>1. Pf</summary>
        port VLAN identifier
    </details>
    <details>
        <summary>2. Обозначить root порты на топологии</summary>
        те, которые находятся на L2 коммутаторах и обращены к L3
    </details>
    <details>
        <summary>3. На топологии настроить порт *(жёлтая) для доступа с admin Обозн * как fa0/1, а admin VLAN как vlan 20</summary>
        <p>interface fa0/1</p>
        <p>switchport mode trunk</p>
        <p>switchport trunk allowed 10,20</p>
        <p>P.S. Некоторые ещё адрес vlan'а на коммутатор прописывали, но я не делала, потому что задание было настроить только порт</p>
    </details>
    <details>
        <summary>4. Port mirroring</summary>
        дублирование входящих и исходящих кадров одного порта на другом
    </details>
    <details>
        <summary>5. Самый медленный интерфейс ISDN</summary>
        BRI (Basic rate interface): 2B+1D 128 kbit/s
    </details>
    <details>
        <summary>6. DLCI</summary>
        Data-Link Connection Identifier - для идентификации VCs в пределах физ. каналов -> таблица коммутации (аналогично, как VPI/VCI в ATM)
    </details>
    <details>
        <summary>7. Написать таблицу АТМ коммутации, состоящую из одной строки</summary>

![ATM table](7.7.png)
    </details>
    <details>
        <summary>8. Устройства с провайдерской стороны POTS</summary>
        Внутренний либо внешний, аналоговый либо цифровой модемный пул
    </details>
    <details>
        <summary>9. Область частот 802.11а</summary>
        5 GHz
    </details>
    <details>
        <summary>10. Поддержка какого протокола обеспечивает ipv6 мультикаст</summary>
        IPv6 MLD
    </details>
    <details>
        <summary>11. 3 гибридные топологии маршрутизатор и коммутаторов</summary>
        Маршрутизирующие коммутаторы, коммутирующие маршрутизаторы, коммутаторы потоков
    </details>
    <details>
        <summary>12. 3 любых блока структурной схемы сетевого адаптера</summary>

![ATM table](7.12.png)
    </details>
</details>

<details>
    <summary>8 вариант</summary>
    <details>
        <summary>1. Что такое learning при коммутации</summary>
    </details>
    <details>
        <summary>2. Дорисовать любую (или все возможные?) комбинации состояний портов при STP (схема)</summary>
    </details>
    <details>
        <summary>3. Настроить IVR</summary>
    </details>
    <details>
        <summary>4. 3 любых критерия по классификации VLAN</summary>
    </details>
    <details>
        <summary>5. Типы сигнализации в WAN</summary>
        CCS, CAS
    </details>
    <details>
        <summary>6. Frame Relay, пример строки коммутации из таблицы</summary>
    </details>
    <details>
        <summary>7. ADSL - расшифровать букву А и что значит</summary>
        Asymmetric
    </details>
    <details>
        <summary>8. Основной стандарт Dial-Up</summary>
        V.92
    </details>
    <details>
        <summary>9. Протокол для поддержки IPv4 multicast в СПД</summary>
        IPv4 IGMP
    </details>
    <details>
        <summary>10. PPDU - это (может BPDU?)</summary>
    </details>
    <details>
        <summary>11. BALUN - это</summary>
        BALUN -- BALance-UNbalance -- двунаправленный преобразователь из коаксиального кабеля в витую пару и наоборот
    </details>
    <details>
        <summary>12. CAM-таблица, для чего нужна</summary>
        в таблице хранится соответствие MAC-адресов и портов
    </details>
</details>

<details>
    <summary>9 вариант</summary>
    <details>
        <summary>1. 3 недостатка vlan</summary>
    </details>
    <details>
        <summary>2. Ivr classic на ближайшем к роутеру коммутаторе</summary>
    </details>
    <details>
        <summary>3. Обозначить любую возможную комбинацию designated портов</summary>
    </details>
    <details>
        <summary>4. Cisco протокол совместимый с HSRP</summary>
    </details>
    <details>
        <summary>5. Что такое STM-64</summary>
    </details>
    <details>
        <summary>6. Что такое сигнализация в WAN</summary>
    </details>
    <details>
        <summary>7. Нарисовать Adsl сплитер</summary>
    </details>
    <details>
        <summary>8. Виды виртуальных цепей, поддерживаемые ATM</summary>
    </details>
    <details>
        <summary>9. 3 технические характеристики 802.11n</summary>
    </details>
    <details>
        <summary>10. Для чего в сетевых интерфейсах нужен Errprom</summary>
    </details>
    <details>
        <summary>11. Пример мультикаст групп используемой актианым сетевым оборудованием</summary>
    </details>
    <details>
        <summary>12. 3 производителя комплектующих для Ethernet сетевых адаптеров</summary>
    </details>
</details>

<details>
    <summary>10 вариант</summary>
    <details>
        <summary>1. Назовите три любых достоинства кластеров в маршрутизаторе</summary>
    </details>
    <details>
        <summary>2. На топологии обозначить designated порты</summary>
    </details>
    <details>
        <summary>3. На топологии настроить конфигурацию</summary>
    </details>
    <details>
        <summary>4. Конфигурирование виланов в линукс</summary>
    </details>
    <details>
        <summary>5. Что такое DSLAM</summary>
    </details>
    <details>
        <summary>6. Скорость цифрового потока Е3</summary>
    </details>
    <details>
        <summary>7. 3 отличия любых последовательности сетевых интерфейсов от ethernet интерфейсов</summary>
    </details>
    <details>
        <summary>8. Расшифровать LMI</summary>
    </details>
    <details>
        <summary>9. Для чего нужны несущие при модуляции</summary>
    </details>
    <details>
        <summary>10. Факторы влияющие на производительность сетевого адаптера (“узкие места”)</summary>
    </details>
    <details>
        <summary>11. Что такое коммутатор</summary>
    </details>
    <details>
        <summary>12. что такое децибел(dB)</summary>
    </details>
</details>
