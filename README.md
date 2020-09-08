# ARDUINO 第二篇
第一篇的延伸訓練</p>
同時閃爍4顆LED</p>
程式如下:</p>
void setup()</p>
{</p>
  // put your setup code here, to run once:</p>
  for(int i=2;i<6;i++)</p>
    pinMode(i,OUTPUT);</p>
   </p>
}</p>

void loop() {</p>
  // put your main code here, to run repeatedly:</p>
  for(int i=2;i<6;i++)</p>
  digitalWrite(i,HIGH);</p>
  delay(300);</p>
</p>
  for(int i=2;i<6;i++)</p>
  digitalWrite(i,LOW); </p>
  delay(300);</p>
 
}</p>

--------------------------------------------------------------------------


