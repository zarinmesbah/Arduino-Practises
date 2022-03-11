# Arduino-Practises


// C++ code
//
void setup()
{
  Serial.begin(9600);
  pinMode(9, OUTPUT);
}

void loop()
{  
  Serial.println("ON");
  digitalWrite(9, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(9, LOW);
  Serial.println("OFF"); 
  delay(1000); // Wait for 1000 millisecond(s)
}
