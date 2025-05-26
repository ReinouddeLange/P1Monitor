# P1Monitor

Uitleg: https://www.ztatz.nl/p1-monitor/ <br>
De slimme meter heeft een P1 poort/aansluiting waar elke 10 seconden de laatste waarden uit te lezen zijn. De Raspberry Pi heeft een serieel naar USB kabeltje dat op de P1 poort van de slimme meter is aangesloten. De ztatz software laat de statistieken op een webpagina zien.

<img width="600" alt="P1Monitor_Principe" src="https://github.com/user-attachments/assets/f83bdf05-4668-4e2b-ae2e-24cd84a69c58" />

## Webpagina

<img width="600" alt="Scherm­afbeelding 2025-05-24 om 4 32 37 PM" src="https://github.com/user-attachments/assets/e1a2725d-789c-4d37-9f3b-a2018270464b" />
<p>

## Aansluiting
  
<img width="300" alt="Slimme meter" src="https://github.com/user-attachments/assets/30548e35-1241-44dc-bba1-512c8fb3eae9" />
<img width="300" alt="Slimme meter P1 aansluiting" src="https://github.com/user-attachments/assets/3e6eab73-ae7c-44f1-8a09-5e595781d2b6" />
<p>

<img width="600" alt="Raspberry Pi aansluiting" src="https://github.com/user-attachments/assets/b4f0d40d-0b3b-4ea2-a0a7-072f08790e72" />

### P1 instellingen

| seriële instellingen |  |
| --- | --- |
| baudrate | 115200 |
| byte size | 8 bits |
| parity | geen |
| stopbits | 1 stop bit | 
| device | /dev/ttyUSB0 |



## openweathermap.org api key
Om de weersinformatie te laten zien op de webpagina is een API key nodig. <br>
https://home.openweathermap.org/api_keys <br>
