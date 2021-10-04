# 十六 VLOOKUP函数和绝对参照设定
## 1.VLOOKUP函数使用
1.1 语法VLOOKUP (lookup_value, table_array, col_index_num, [range_lookup]) 
> lookup_value（必需参数）,要查找的值。 要查找的值必须列于在参数参数中指定的单元格table_array列中
>> 例如，如果表数组跨单元格 B2：D7，则lookup_value必须列B
>>
>>Lookup_value可以是值，也可以是单元格引用

> Table_array（必需参数）,VLOOKUP 在其中搜索 lookup_value 和返回值的单元格区域。 可以使用命名区域或表，并且可以在参数中使用名称，而不是单元格引用
>> 单元格区域的第一列必须包含lookup_value。单元格区域还需要包含要查找的返回值

> col_index_num（必需参数）,对于包含(的列，列号table_array)从1开始 

> range_lookup（可选参数）一个逻辑值，该值指定希望VLOOKUP查找近似匹配还是精确匹配：
>>近似匹配-1/TRUE假定表中的第一列按数字或字母顺序排序,然后搜索最接近的值。这是未指定值时的默认方法。例如，=VLOOKUP (90，A1：B100，2，TRUE) 
>>
>>完全匹配-0/FALSE将搜索第一列中的确切值。例如，=VLOOKUP ("Smith"，A1：B100，2，FALSE) 。




1.2 VLOOKUP使用“L”型动线，搜索关键字需要在第一列
> 单元格区域的第一列必须包含lookup_value

# 2.绝对参照设置
> 选中区域，按F4锁定


