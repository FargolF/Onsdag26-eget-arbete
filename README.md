# Onsdag 26/11 

## Välkomna till denna veckas repository! 

I denna repository ska vi gå igenom det som vi har lärt oss under senaste föreläsningar/LAB! 

# Blink 
Exempel på programmering kan var `BlinkProgrammeringen`, där en LED-Lampan börjar lysa i blinkande form. Man kan bestämma förhållanden mellan tid på och tid av, det vill säga hur snabbt LED-Lampan ska släckas och sättas på.

![Blink png](https://github.com/user-attachments/assets/8036ab70-99cc-4932-ba02-fb3b25be0755)


# Mikroprocessor? 
![computer-microprocessor-icon-on-white-260nw-2678923811 jpg](https://github.com/user-attachments/assets/13c6f7e3-9c54-4f9c-aa92-2917a10b1261)

En **Mikroprocessor** anses vara en dators miniatyriserad centralprocessor`(CPU)`, som beffiner sig på ett enda chip. 
Den får instruktioner och utför de genom olika operationer. Man kan även säga att det är datorns **hjärna**! 

Under tisdagens föreläsning och LAB fick vi jobba med **Arduino IDE** och **Plusivo**. 

# Arduino IDE
<img width="200" height="108" alt="Arduino_Logo_Registered svg" src="https://github.com/user-attachments/assets/390e35e5-188a-40de-b71d-fbcc864b500a" />

Platformen där man kan enkelt programmera interaktiva elektroniska objekt. Man skriver sin kod `(skiss)`, och kan enkelt pusha den till sin Plusivo! Platformen är väldigt populär för utbildningssyfte, då användningen är mycket enkelt. 


# Plusivo


Ett varumärke där man kan enkelt testa sig för programmering av elektroniska kompotenter. 

# Kod

```CPP

void setup() {

  // initialize digital pin LED_BUILTIN as an output.
  
  pinMode(LED_BUILTIN, OUTPUT);
}


// the loop function runs over and over again forever

void loop() {

  digitalWrite(LED_BUILTIN, HIGH);  // turn the LED on (HIGH is the voltage level)


  delay(500);                      // wait for a second
  
  digitalWrite(LED_BUILTIN, LOW);   // turn the LED off by making the voltage LOW


  delay(500);                      // wait for a second

