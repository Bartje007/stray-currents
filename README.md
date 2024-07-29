//stray currents

//Zwerfstromen Arduino, 

void setup() {
  Serial.begin(9600);
  pinMode(A0, INPUT);
}
  void loop(){
int waarde =0; 

waarde = analogRead(A0);
Serial.println(waarde);
  delay(200);
  
  }

//AO draadje hangen //
