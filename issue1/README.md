jara和jara有同名的类，sameclassmodule不同的pom，会使用不同的jar

├─jara
│  │  pom.xml
│  ├─src
│      ├─main
│      │  ├─java
│      │  │  └─com
│      │  │      └─nmj
│      │  │          └─common
│      │  │                  SameClass.java
│      │  │
│      │  └─resources
│      └─test
│          └─java
│
├─jarb
│  │  pom.xml
│  │
│  ├─src
│      ├─main
│      │  ├─java
│      │  │  └─com
│      │  │      └─nmj
│      │  │          └─common
│      │  │                  SameClass.java
│      │  │
│      │  └─resources
│      └─test
│          └─java
│
└─sameclass
    │  pom.xml
    └─sameclassmodule
        │  pom.xml
        │
        ├─src
            ├─main
            │  ├─java
            │  │  └─com
            │  │      └─nmj
            │  │          └─sameclass
            │  │                  EntryPoint.java
            │  │
            │  └─resources
            └─test
                └─java