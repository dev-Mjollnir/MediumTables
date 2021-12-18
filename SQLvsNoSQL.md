| **SQL**| **NoSQL**|
|---------------------------|---------------------------|
|SQL databases are only vertically scalable. This means that you can increase the load on a single server by increasing things like RAM, CPU or SSD.|NoSQL databases are horizontally and vertically scalable. This means that you handle more traffic by sharding, or adding more servers in your NoSQL database.|
|SQL databases are table-based.|NoSQL databases are either key-value pairs, document-based, graph databases or wide-column stores. This makes relational SQL databases a better option for applications that require multi-row transactions.|
|SQL databases follow ACID properties (Atomicity, Consistency, Isolation and Durability).|NoSQL database follows the Brewers CAP theorem (Consistency, Availability and Partition tolerance).|
|SQL databases have fixed or static or predefined schema.|NoSQL databases have dynamic schema.|
|SQL databases are not suited for hierarchical data storage.|NoSQL databases are best suited for hierarchical data storage.|
|Data is distributed across multiple tables| Data is typically merged and nested in a few collections|
|Limitations for lots of (thousand) read & write queries per second. |Great performance for mass (simple) read & write queries.|
|Structured data can be stored in tables| Using JSON data un-structured data can be stored.|
