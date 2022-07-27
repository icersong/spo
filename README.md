# spo
Simplistic python object like json

这是一个简化的python object文本存储格式，类似json，但是又进一步简化书写，更方便手工编辑。其目的是用于数据库字段存储一些简单的配置，有时候需要手工编写。

eg：

````
这是一个string   ==> "这是一个string"
````

````
"12345"   ==> "12345"
````

````
12345    ==> 12345
````

````
123.45    ==> 123.45
````

````
这,是,一个,tuple,like,python   ==> ("这","是","一个","tuple","like","python")
````

````
(这,是,一个,tuple,like,python)    ==> ("这","是","一个","tuple","like","python")
````

````
[这,是,一个,list,like,python]   ==> ["这","是","一个","list","like","python"]
````

````
{这,是,一个,set,like,python}   ==> {"这","是","一个","set","like","python"}
````

````
{这是一个: dict like python}  ==> {"这是一个": "dict like python"}
````

````
{这,是,一个:dict,like,python}  ==> {("这","是","一个"):"dict,like,python"}
````

