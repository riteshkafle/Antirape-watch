# Antirape-watch 

Anti-rape System is an IoT based project whose central idea is to provide security for people facing sexual harassment. The model is a wearable technology (anti-rape watch) that is used to defend the harassment.  This model is designed to advocate harassment without harming the victim with high accuracy. When an individual feels unsafe, one can click the button on the watch to send alerts to the nearest police station with the location coordinates. Once the button is pressed, the rescue team is there to assist the victim. That is why it is highly efficient, accurate & easy to use. 

![anti rape watch](https://user-images.githubusercontent.com/85400895/134727278-11fad52f-76ee-4e46-a96e-dd816b0242d4.png)

                              Working Mechanism 

There will be two systems watch and server. The watch consists of arduino, GSM module ,GPS sensor ,transmitter. When a button is pressed, the signals get triggered and GPS sensor generates the location in the form of latitude and longitude. The values of latitude and longitude are stored in two different variables. The sample message is created saying "I am in danger. Please rescue me ." The link is also created using latitude and longitude variables that redirect to Google maps url. Then the message is sent to the local authorities phone number which will be set by the programmer during watch construction.

In addition there will be a local server which can be kept to local police station. The server consists of receiver ,LCD display panel and a buffer. The LCD panel will also display the same message with location of victim. The beeping sound will be produced in the server to make sure that police should be ready to rescue the victim .

Transmission of signal between watch and server will be in the form of electromagnetic waves that travels serially.

The message can be sent to the police personal number of station number anywhere in the world but the transmission between watch and the server should be within the range of 1 km in omni-direction.

The watch is rechargeable. The charger is given to victim. The watch works well more than 8 hours once it is fully charged.The server box can work on both AC as well as DC.

![server box](https://user-images.githubusercontent.com/85400895/134727566-8a235942-b1bf-48c2-8d00-49f87c57feaa.png) 
![working mechanism](https://user-images.githubusercontent.com/85400895/134757652-d54fcf91-58fd-464b-b378-867c8ae8589f.JPG)


                                Components Used 

Arduino Nano,
RF Module 433 MHz, 
Two Channel Relay Module, 
NEO-6M GPS Module,
Arduino Uno R3 Board (ATmega328),
16*2 LCD Module &
Buzzer 

![station components](https://user-images.githubusercontent.com/85400895/134757822-ebe29ba1-ce28-46c9-9849-63364eea9aef.JPG)


                             Circuit Connection: 
![circuit diagram](https://user-images.githubusercontent.com/85400895/134733227-1ff95c27-ce35-4cf8-a927-2f6301dd6053.JPG)


                         


