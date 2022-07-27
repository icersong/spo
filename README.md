# spo
Simplistic python object like json

这是一个类似json的简化的文件格式。其目的是用于数据库字段存储一些简单的配置，为了方便手工编辑数据而简化的一种方式。

eg：

````
这是一个string
````

````
12345, 是一个integer    ==> (12345, "是一个integer")
````

````
123.45, 是一个float    ==> (123.45, "是一个float")
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

