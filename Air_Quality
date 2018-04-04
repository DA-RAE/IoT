void setup()
{
  Serial.begin(9600);
  pinMode(6,OUTPUT); //red led
  pinMode(8,OUTPUT); //white led
}

void loop()
{  
  int sensorvalue=analogRead(A0);
  delay(500);
  Serial.print("Air Quality=");
  Serial.println(sensorvalue);
  
  if(sensorvalue>300)
  {
    digitalWrite(6,HIGH); //red led on
    digitalWrite(8,LOW); //white led off
  }
  else
  {
    digitalWrite(6,LOW); //red led off
    digitalWrite(8,HIGH); //white led on
  } 
  delay(500);  
}
