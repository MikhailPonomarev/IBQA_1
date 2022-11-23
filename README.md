# Введение в тестирование безопасности

## **Wireshark, UDP**
- Sourсe port: 57585
- Destanation port: 1900
![udp](https://user-images.githubusercontent.com/82900581/203582279-9a1241de-034c-4797-9d2c-bd4214dc4aa6.png)

## **Wireshark, DNS**

Обнаруженные флаги протокола DNS:
- 0x0100 Standard query
![dns1](https://user-images.githubusercontent.com/82900581/203585347-656d9130-a3fd-4a72-b3c8-400b5eaa3fe8.png)

- 0x8180 Standard query response, No error
![dns2](https://user-images.githubusercontent.com/82900581/203585396-1f5ed0db-66b2-46dc-ad88-2283c77f2b43.png)

- 0x8183 Standard query response, No such name
![dns3](https://user-images.githubusercontent.com/82900581/203585428-f00d3a1a-fcd7-4054-a632-ed63eaa1ea48.png)
