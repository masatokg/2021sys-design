```uml
@startuml
お客様 -> ホール係 : 注文
ホール係 -> 厨房 : 席番号と料理
厨房 -> ホール係: 完成した料理
ホール係 -> お客様 : 注文した料理
"Bob()" -> "This is very\nlong" as Long
' You can also declare:
' "Bob()" -> Long as "This is very\nlong"
Long --> "Bob()" : ok
@enduml
```
