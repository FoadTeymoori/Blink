سه تا الگوریتم مختلف برای ال ای دی چشمک زن در آردوینو

```cpp

void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
}
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);  
  delay(1000);                     
  digitalWrite(LED_BUILTIN, LOW);   
  delay(1000);                      
}
//////////////////////////////////////2
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);  
  delay(1000);                     
  digitalWrite(13, LOW);   
  delay(1000);                      
}
//////////////////////////////////////3 
int LED = 2;

void setup() {
  pinMode(LED, OUTPUT);
}

void loop() {
  digitalWrite(LED, HIGH);  
  delay(1000);                     
  digitalWrite(LED, LOW);   
  delay(1000);                      
}
```
