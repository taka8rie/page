### Setter -> 用于给所有的实例变量赋值，通过Setter这种方式来处理数据，能实现数据的封装。（任何有值可以被运用到的地方，可以使用xxx.getter来获取该类型的值）
#### setter可以检查参数，并给出相对应的判断(比如抛出异常)
Public void setHeight(int ht){
			if(ht>9)
		  height=ht;}

### 数据隐藏
* 将实例变量标记为private (private in size)
* 将getters与setters标记为public 
```
public void setSize(int s){
if(s>const){ // const为某一数值。
size=s;}
}
```


			
			
