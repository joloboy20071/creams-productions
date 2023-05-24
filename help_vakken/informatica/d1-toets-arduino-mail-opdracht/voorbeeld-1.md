---
description: laat een rood lampje knipperen met een interval van 1 seconde
---

# voorbeeld 1

```cpp
const int led = 2;//denifneer op welke pin de led is aangesloten
void setup()
{
  pinMode(led, OUTPUT);//zet de led op output
}

void loop()
{
  digitalWrite(led, HIGH);//aan
  delay(1000);// wacht 1 seconde
  digitalWrite(led, LOW);//uit
  delay(1000);//wacht 1 seconde
}
```

{% file src="../../../.gitbook/assets/voorbeeld1.txt" %}
