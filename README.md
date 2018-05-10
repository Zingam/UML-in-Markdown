How to Use UML Diagrams in GitHub Markdown Documents
====

[comment]: # ( Taken from: https://stackoverflow.com/a/32771815/1474291 )

![Class Diagram](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/Zingam/Markdown-Document-UML-Use-Test/master/UML/Instance.puml)

The Project Structure
----

```
 |
 +-- UML
 |    |
 |    +-- Instance.puml
 |         ...    
 |
 +-- README.md
      ...
        
```

The Source
----

* [UML/Instance.puml][1]

[1]: https://github.com/Zingam/UML-in-Markdown/blob/master/UML/Instance.puml

```
Instance <|-- VulkanRootObject

class Instance {
    -- Contructors & destructors --
    - Instance()
    
    -- Public methods --
    + Initialize() : bool
}
```

The Link
----

1. PlantUML's proxy:
    * http://www.plantuml.com/plantuml/proxy?src=
2. Document's GitHub raw URL:
    * https://raw.githubusercontent.com/Zingam/Markdown-Document-UML-Use-Test/master/UML/Instance.puml
3. Combined URL (combine the PlantUML's proxy URL and the document's GitHub raw URL):
    * http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/Zingam/Markdown-Document-UML-Use-Test/master/UML/Instance.puml

The Markdown
----

```
![Class Diagram](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/Zingam/Markdown-Document-UML-Use-Test/master/UML/Instance.puml)
```

The Diagram
----

![Class Diagram](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/Zingam/Markdown-Document-UML-Use-Test/master/UML/Instance.puml)
