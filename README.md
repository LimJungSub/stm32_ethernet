## 관련 공부 자료 모음

원노트에 기록하였다.

# MQTT_pub, MQTT_sub

![다이어그램w5500](https://github.com/user-attachments/assets/58f9dd2c-6f98-4217-a5fb-67dd75e621fc)

![diagram-export-2025 -3 -24 -오전-10_39_14](https://github.com/user-attachments/assets/f54fe647-457a-47ed-96e9-c951d1b9dca1)

W5500은 TCP/IP 스택이 하드웨어에 내장되어 있으며, SPI 인터페이스를 통해 제어됨.

따라서 WIZnet사에서 제공하는 소켓 API를 사용하여 네트워크 계층을 직접 구현해야 했다.

### 네트워크 환경은 Static Host Configuration으로 구성했다.

추후 DHCP를 구성하는 방법을 공부하여 DHCP방식으로 네트워크에 참여하도록 한다.
