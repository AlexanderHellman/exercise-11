# exercise-11
# Övnings repo 
*detta repo är för en övning i github*

# Sample Mermaid diagrams, for more details edittttt:
https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams



```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```



```mermaid
sequenceDiagram;
participant Alice;
participant Bob;
Alice->>John: Hello John, how are you?;
loop Healthcheck;
	John->>John: Fight against hypochondria;
end;
Note right of John: Rational thoughts <br/>prevail!;
John-->>Alice: Great!;
John->>Bob: How about you?;
Bob-->>John: Jolly good!;
```
	
	
	
```mermaid
classDiagram
class01 <|-- AveryLongClass : Cool
class03 *-- Class04
class05 o-- Class06
class07 .. Class08
class09 --> C2 : Where am i?
class09 --* C3
class09 --|> Class07
class07 : equals()
class07 : Object[] elementData
class01 : size()
class01 : int chimp
class01 : int gorilla
class08 <--> C2: Cool label
```


```mermaid
gitGraph
commit
commit
branch develop
commit
commit
commit
checkout main
commit
commit
```


