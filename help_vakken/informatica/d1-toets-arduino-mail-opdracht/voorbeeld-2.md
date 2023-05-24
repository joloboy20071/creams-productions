---
description: >-
  een buzzer 7 keer laaten piepen voor een kwart seconde en dan een rood lampje
  aan laten gaan voor 2 seconde
---

# voorbeeld 2

```cpp
const int buzzer = 3; //define buzzer
const int rood = 2 //define het rode lampje
void setup()
{
  pinMode(buzzer, OUTPUT);//zet ze bijde op output
  pinMode(rood, OUTPUT);
}

void loop()
{
  for (int i=0;i<7; i++){// een for loop die 7 keer iets doet
      tone(buzzer, 2500, 250);//toon 
      delay(250);// een kwart seconde wachten
      noTone(buzzer);//stop de buzzer
      delay(250);// een kwart seconde wachten
  }
  digitalWrite(rood,HIGH);//lampje aan 
  delay(2000);// wacht 2 seconde
  digitalWrite(rood, LOW);//lampje uit
}

```

{% file src="../../../.gitbook/assets/voorbeeld2.txt" %}
