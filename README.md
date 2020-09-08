# ARDUINO 第二篇
同時閃爍4顆LED</p>
可運用for迴圈</p>
程式如下:</p>
```c++

void setup()
{
  for(int i=2;i<6;i++)
    pinMode(i,OUTPUT);
   
}

void loop() 
{
  for(int i=2;i<6;i++)
  digitalWrite(i,HIGH);
  delay(300);

  for(int i=2;i<6;i++)
  digitalWrite(i,LOW); 
  delay(300);
 
}
```
--------------------------------------------------------------------------


