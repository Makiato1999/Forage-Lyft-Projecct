# Forage-Lyft-Project
Lyft Back-End Engineering Virtual Experience Program
## Software Architecture
Useful resources
- [Composition in Python](https://realpython.com/inheritance-composition-python/)<br/>Inheritance and Composition: A Python OOP Guide
- [Composition and Aggregation](https://en.wikipedia.org/wiki/Class_diagram#Scope)<br/>Differences between Composition and Aggregation
- [ERD Introduction Video](https://www.youtube.com/watch?v=-CuY5ADwn24)<br/>Primary Key and Foreign Key
- [ERD concepts](https://www.visual-paradigm.com/guide/data-modeling/what-is-entity-relationship-diagram/)<br/>Cardinality
## Refactoring
Software diagram with factory design pattern
- Lyft has provided progress1 diagram(answer):[click here](https://github.com/Makiato1999/Forage-Lyft-Project/blob/main/Software%20Architecture/example.pdf)
- And progress2 answer: [click here](https://github.com/vagabond-systems/forage-lyft-task-2-model-answer)
<br/>
Useful resources
- [Abstract Factory Pattern](https://refactoringguru.cn/design-patterns/abstract-factory)
- RUNOOB.COM
  - [Factory Pattern](https://www.runoob.com/design-pattern/factory-pattern.html)
  - [Abstract Factory Pattern](https://www.runoob.com/design-pattern/abstract-factory-pattern.html)
- static method
  - staticmethod用于修饰类中的方法,使其可以在不创建类实例的情况下调用方法，这样做的好处是执行效率比较高。 当然，也可以像一般的方法一样用实例调用该方法。 该方法一般被称为静态方法。 静态方法不可以引用类中的属性或方法，其参数列表也不需要约定的默认参数self
## Data Munging
Useful resources
- [Convert csv into SQLite table in Python](https://www.alixaprodev.com/2022/03/csv-file-into-sqlite-table-in-python.html)<br/>Create table, Insert
#### Some issues i have encountered
- [how to fix 'sqlite3.OperationalError: no such column'](https://itecnote.com/tecnote/python-sqlite3-operationalerror-no-such-column-but-im-not-asking-for-a-column/)<br/>When i used f string to write SELECT sql, i forgot the ''
