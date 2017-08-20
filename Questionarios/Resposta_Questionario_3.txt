1.
	 (a) char a = 0x01;
	 (b) char a = 0x03;
	 (c) char a = 0xfb;
	 (d) char a = 0xf3;
	 (e) char a = a^0x80;
	 (f) char a = a^0xf0;
	     a = a|0x0f;

2. 
#define LED RED_LED
#define LED2 GREEN_LED
  
void setup() {                
  
  pinMode(LED, OUTPUT); 
  pinMode(LED2, OUTPUT);     
}


void loop() {
  digitalWrite(LED, HIGH);   
  delay(250); 
  digitalWrite(LED2, HIGH);    
  delay(250); 
  digitalWrite(LED, LOW);    
  delay(250);               
  digitalWrite(LED2, LOW);   
  delay(250); 
}


4. 
#define LED RED_LED
#define LED2 GREEN_LED
  
void setup() {                
  
  pinMode(LED, OUTPUT); 
  pinMode(LED2, OUTPUT);     
}


void loop() {
  digitalWrite(LED, HIGH);   
  digitalWrite(LED2, HIGH);    
  delay(250); 
  digitalWrite(LED, LOW);                   
  digitalWrite(LED2, LOW);   
  delay(250); 
}