
对LLM在SQL生成中可能失败原因的假设：

1.LLM容易混淆多层嵌套的数学运算（如 ROUND(A/B*C, N)），导致括号闭合错误；

2.在复杂的表达式或者函数调用中，LLM可能错误的引用字段名或参数顺序；
