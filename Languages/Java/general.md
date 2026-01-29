Java:
- Java Memory Model: jmm - что? для чего? зачем? как работает? (happens before, sequetianl consistancy, programm order, CAS)
- виды памяти: heap/stack/cache (для чего нужны, как используются)
- Мусор в Java: GC - что это? как работает на примере нескольких версий? (stages, generations, STW, minor/full gc)

Java Core:
- примитивы/объекты - инициализация, работа с ними
- модификаторы доступа - виды? какие бывают? для чего используются?
- equals/hashcode - зачем? для чего? как? нативная реализация?
- exceptions (иерархия, виды)
- ключевые слова volatile, synchronized, final, finalize, finally, static
- String pool
- виды ссылок
- что такое аннотации и для чего нужны


Java Collections:
-- базовые вещи
-- hashmap (бакеты, linked list, tree set, hashcode)
-- tree (на уровне понимания вставки, балансировки)
-- какие-нибудь concurrent коллекции, типа CopyOnWriteArrayList, ConcurrentHashMap, BlockedQueue

Java Threads:
- thread - что это? за что отвечает? как работает
- runnable vs callable - что за аннотации
- исключения работы потоков
- самые частые ошибки - виды ошибок? обработка?
- коллекции 
- future & completable future - что это? для чего? набить руку на примерах


Java additional:
- Lombok - как он упрощает жизнь на примере генерации объектов, классов и методов через аннотации

Java patterns:
- какие бывают виды - Порождающие, Структурные, Поведенческие
- Основные с собесов ниже (разбор как реализовать, для чего и когда применять)
- Builder
- Factory
- Adapter
- Prototype
- Facade
- Proxy
- Template
- Strategy
- State
- Observer
- Iterator
- CoR (Chain of Resposibility)

Архитектурные паттерны:
- state machine
- two phase commit
- saga
- cqrs
- cdc
- event sourcing
- circut breaker
- rate limiter
- sticky session
- orchestration
- choreography