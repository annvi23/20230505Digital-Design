void setup() {
  Serial.begin(9600);
}

void loop() {
  int sensorVal = analogRead(A0);
  Serial.println(sensorVal);
  if(sensorVal < 30) sensorVal = 30;
  if(sensorVal > 140) sensorVal = 140;
  analogWrite(9, map(sensorVal,30,140,0,255));
  delay(1);
}
