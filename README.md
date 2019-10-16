# knigh_rider_buttin
int switchState = 0;
void setup() {
 pinMode (3,OUTPUT);
 pinMode (4,OUTPUT);
 pinMode(5,OUTPUT); 
 pinMode(2,INPUT);
  
  

}

void loop() {
  switchState = digitalRead(2);
  if (switchState == LOW) {
  digitalWrite (4,LOW);
  digitalWrite (3,LOW);
  digitalWrite (5,LOW);
  digitalWrite (7,LOW);
  digitalWrite (6,LOW);
  }
  else{
digitalWrite (4,HIGH);
digitalWrite (3,HIGH);
digitalWrite (5,HIGH);
digitalWrite (7,HIGH);
digitalWrite (6,HIGH);
  }
}
