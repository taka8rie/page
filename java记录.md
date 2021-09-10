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

### 关于reference variable。
类似于c或者c++的指针，将对象的地址存在stack里边，对象其实是存在heap里边。这样能够减少stack的内存占用，防止stack overflow。
（在座的各位都有车，把车停在停车库，而不是把车停在教室）
			
### every single byte in your memory has an address,like array
each byte has 8 bites.int has 4 bytes
```
int arr[3];
arr[0]=3; //int 3 ->(24个0，00000011） arr's address =first byte in (int 3) equal 0000 0000 ,transform to  hexadecimal not binary. //需要修正
```


