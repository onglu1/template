# STL  
## Bitset  
```cpp
//定义 
bitset<4> bitset1;　　//无参构造，长度为４，默认每一位为０
bitset<8> bitset2(12);　　//长度为８，二进制保存，前面用０补充
string s = "100101";
bitset<10> bitset3(s);　　//长度为10，前面用０补充
char s2[] = "10101";
bitset<13> bitset4(s2);　　//长度为13，前面用０补充
cout << bitset1 << endl;　　//0000
cout << bitset2 << endl;　　//00001100
cout << bitset3 << endl;　　//0000100101
cout << bitset4 << endl;　　//0000000010101

//操作  
foo.count();//popcount
foo.size();
foo.any();foo.none();//是否存在1,是否不存在1
foo.all();//是否全为1
foo.set();foo.reset();//全部置1,全部置0
foo.to_string();foo.to_ulong();foo.to_ullong();
```
