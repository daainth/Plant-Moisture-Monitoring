# Plant-Moisture-Monitoring
A personal project which I use to further develop my skills with a Computer Engineering background. The main goal of this project is to create a remote plant monitoring system that will help me maintain the lives of my plants. 

Goals
- Develop a wireless system to connect via some low power method
- Utilize a database to store telemetry and historical data
- Some UI via a website that will instantly tell me the moisture status for the plants

Long Terms Goals(Maybes)
- Data visualization on the website
- Machine learning integration
- A mobile application


Hardware
- ESP32 (ESP-IDF)
- Potential
  - https://www.dfrobot.com/product-2918.html
  - https://www.dfrobot.com/product-1385.html
 
Software
- MQTT broker: Mosquitto
- FastAPI
- Postgres
- Pydantic
- TimescaleDB

General
- Docker Compose: mosquitto + backend + db + dashboard
- Add CI/CD with GitHub Actions (lint/test/build, build container images)
- OTA flow for ESP-IDF
