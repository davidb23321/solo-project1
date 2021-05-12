// C++ code
//
void setup()
{
  pinMode(7, OUTPUT);
}

void loop()
{
  tone(7, 261, 200);
  	delay(900);
   tone(7, 293, 200);
  	delay(400);
   tone(7, 329, 100);
  	delay(1200);
   tone(7, 392, 200);
  	delay(1200);
   tone(7, 440, 200);
  	delay(1200);
}
