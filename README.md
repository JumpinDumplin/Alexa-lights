# Alexa-lights
Control dumb lights using Alexa

Uses an ESP-8266 to talk to the Sinric API, and controls appliances connected to the ESP via a relay module.

### API Initialisation
- Make an account awith [Sinric](https://sinric.com)
- Add an alexa device with device-type "Light"
- Copy device ID and API key from the dashboard and place it in the main code 
 
### ESP connections
- Connect IN pin of relay module to pin D2 (GPIO4)
- Connect the wires from the light to the relay 
- Connect 5V power supply for the ESP

