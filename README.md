# ARDUINO 第二篇
同時閃爍4顆LED</p>
可運用for迴圈</p>
程式如下:</p>
void setup()</p>
{</p>
  for(int i=2;i<6;i++)</p>
    pinMode(i,OUTPUT);</p>
   </p>
}</p>

void loop() </p>
{</p>
  for(int i=2;i<6;i++)</p>
  digitalWrite(i,HIGH);</p>
  delay(300);</p>
</p>
  for(int i=2;i<6;i++)</p>
  digitalWrite(i,LOW); </p>
  delay(300);</p>
 
}</p>

--------------------------------------------------------------------------


