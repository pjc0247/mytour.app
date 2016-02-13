RegionHeader
====
리스트 화면에서 각 지역이 어떤 이름, 어떤 모습으로 표시될지를 지정합니다.

```json
{
    "title" : "TITLE",
    
    "offsetX" : "100px",
    "offsetY" : "100px",
    
    "titleColor" : "red",
    
    "fadeColor" : "red",
    "fadeDistance" : "100px",
    "fadeSpread" : "100px",
    
    "radius" : "10px"
}
```

Properties
----
* __title__ : 리스트 화면에 보여질 타이틀 값입니다.
* offsetX : `title`이 표시될 X 위치입니다. 설정하지 않으면 중앙으로 표시됩니다.
* offsetY : `title`이 표시될 Y 위치입니다. 설정하지 않으면 하단에 표시됩니다.
* radius : 외각선을 둥글게 표시할 정도입니다. 설정하지 않으면 각진 모양으로 표시됩니다.