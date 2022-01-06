# ioBroker.ventilation
ioBroker adapter for ventilation systems like Blauberg, RL, Oxxify

![image](https://user-images.githubusercontent.com/24653087/148353802-c1d22fde-37fa-42f5-8cc6-fa1ca1699c9d.png)


v0.001 = node file to activate as system service which connects to the ventilation system via UDP and translates it to MQTT
status, fan_level, mode (ventilation, regeneration) is supported


UDP communication following this description:
[BDA_Anschluss_SmartHome_RV_V2.pdf](https://github.com/madjack84/ioBroker.ventilation/files/7820469/BDA_Anschluss_SmartHome_RV_V2.pdf)
