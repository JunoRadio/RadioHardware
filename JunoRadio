#include <LiquidCrystal.h>
#include <GoogleTone.h>
char valores;
char lat;
char lon;

 #define BUZ 6
//Define os pinos que serão utilizados para ligação ao display
LiquidCrystal lcd(12, 11, 5, 4, 3, 2);

char caracter; // Enviado pelo aplicativo
void setup() {
  lcd.begin(16, 2);
  Serial.begin(9600);
  pinMode(BUZ, OUTPUT);
  lcd.clear();

  //Posiciona o cursor na coluna 3, linha 0;
  lcd.setCursor(3, 0);
  //Envia o texto entre aspas para o LCD
  lcd.print("JUNO");
  lcd.setCursor(3, 1);
  lcd.print("ON RADIO");
}

void dis(){
    lcd.clear();

  //Posiciona o cursor na coluna 3, linha 0;
  lcd.setCursor(3, 0);
  //Envia o texto entre aspas para o LCD
  lcd.print("JUNO");
  lcd.setCursor(3, 1);
  lcd.print("ON RADIO");
}
void buzzer(){
  
  digitalWrite(BUZ, HIGH);
  delay(100);
  digitalWrite(BUZ, LOW);
  delay(50); 
  digitalWrite(BUZ, HIGH);
  delay(100);
  digitalWrite(BUZ, LOW);
  delay(50); 
  digitalWrite(BUZ, HIGH);
  delay(100);
  digitalWrite(BUZ, LOW);
  delay(50); 
  digitalWrite(BUZ, HIGH);
  delay(100);
  digitalWrite(BUZ, LOW);
  delay(50); 
  digitalWrite(BUZ, HIGH);
  delay(100);
  digitalWrite(BUZ, LOW);
  delay(50); 
  digitalWrite(BUZ, HIGH);
  delay(100);
  digitalWrite(BUZ, LOW);
  delay(50); 
  digitalWrite(BUZ, HIGH);
  delay(100);
  digitalWrite(BUZ, LOW);
  delay(50); 
  digitalWrite(BUZ, HIGH);
  delay(100);
  digitalWrite(BUZ, LOW);
  delay(50); 
  digitalWrite(BUZ, HIGH);
  delay(100);
  digitalWrite(BUZ, LOW);
  delay(50); 
  digitalWrite(BUZ, HIGH);
  delay(100);
  digitalWrite(BUZ, LOW);
  delay(50); 
  digitalWrite(BUZ, HIGH);
  delay(100);
  digitalWrite(BUZ, LOW);
  delay(50); 
  digitalWrite(BUZ, HIGH);
  delay(100);
  digitalWrite(BUZ, LOW);
  delay(50); 
}
void loop() {

  caracter = Serial.read();
   valores = substr(caracter, 0, 4);
   lat = substr(caracter, 4, 10);
   lon = substr(caracter, 10, 20);
  if (caracter == 'L') { // L = String SE A STRING TEM O VALOR CORRETO, PRINTA A LAT/LONG
    buzzer();
    lcd.setCursor(0, 0);
  //Envia o texto entre aspas para o LCD
  lcd.print("LAT: " . lat);
  lcd.setCursor(0, 1);
  lcd.print("LON: " . lon); 
  delay(10000);
  dis();
  }

    
}
