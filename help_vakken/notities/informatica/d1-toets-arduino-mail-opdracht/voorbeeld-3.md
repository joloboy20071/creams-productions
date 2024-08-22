---
description: >-
  je hebt een temperatuur sensor die meet de temperatuur in de ruimte als deze
  boven de 80 graden komt zetten we een fentilator aan.
---

# voorbeeld 3

```cpp
int sensor = A5;// sensor pin
const int fan = 11;
const int temp = 80;// temperatuur limiet
int sensorwaarde;

void setup(){
  pinMode(fan, OUTPUT);// zet fan op OUTPUT
}

void loop()
{
  sensorwaarde = analogRead(sensor);// lees de analoge waarde
  if (sensorwaarde>temp){
	digitalWrite(fan,HIGH);// fan aan
    }
  else{
	digitalWrite(fan,LOW);// fan uit
  }
}
```

{% file src="../../../.gitbook/assets/voorbeeld3.txt" %}
