# ARDUINO 第二篇
第一篇的延伸訓練</p>
同時閃爍4顆LED</p>
程式如下:</p>
void setup()</p>
{</p>
  // put your setup code here, to run once:</p>
    pinMode(2,OUTPUT);</p>
    pinMode(3,OUTPUT);</p>
    pinMode(4,OUTPUT);</p>
    pinMode(5,OUTPUT);</p>
}</p>
</p>
void loop() {</p>
  // put your main code here, to run repeatedly:</p>
  digitalWrite(2,HIGH);</p>
  digitalWrite(3,HIGH);</p>
  digitalWrite(4,HIGH);</p>
  digitalWrite(5,HIGH);</p>
  delay(300);</p>
  digitalWrite(2,LOW);</p>
  digitalWrite(3,LOW);</p>
  digitalWrite(4,LOW);</p>
  digitalWrite(5,LOW);</p>
  delay(300);</p>
}</p>

--------------------------------------------------------------------------


