# ESP32 Wifi to Bluetooth Duplo Train Controll
Using an ESP32 to controll the bluetooth Duplo Train  

## Steps  
- Find the Bluetooth MAC address of your duplo train (power on train when not paired, and use for example BLE scanner on your android phone)
- Copy the code, and add your own bluetooth mac address
- Install the code on your ESP32 (use an ESP32 having bluetooth)
- After installing the code, startup the ESP32, and start-up your train  
- They should pair instantly  
- Add the ESP32 to your HA install and see all the sensors/buttons

![image](https://github.com/kippesikgithub/esp_bt_duplo/assets/100353268/064db0e9-4a1e-4772-8adc-b1e6c5698cda)

![image](https://github.com/kippesikgithub/esp_bt_duplo/assets/100353268/67f050a0-9a4d-4b69-8bd4-c310f7bf178b)

Source code: https://community.home-assistant.io/t/lego-duplo-train-control-with-esphome/637816
