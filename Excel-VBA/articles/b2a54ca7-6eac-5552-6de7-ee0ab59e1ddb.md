
# MajorUnitScale Property

Returns or sets the major unit scale value for the category axis when the CategoryType property is set to xlTimeScale. Read/write XlTimeUnit .



|XlTimeUnit can be one of these XlTimeUnit constants.|
| **xlDays**|
| **xlMonths**|
| **xlYears**|

 _expression_. **MajorUnitScale**

 _expression_ Required. An expression that returns one of the objects in the Applies To list.

## Example

This example sets the category axis to use a time scale and sets the major and minor units.


```vb
With myChart.Axes(xlCategory) 
 .CategoryType = xlTimeScale 
 .MajorUnit = 5 
 .MajorUnitScale = xlDays 
 .MinorUnit = 1 
 .MinorUnitScale = xlDays 
End With
```

