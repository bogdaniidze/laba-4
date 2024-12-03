# laba-4

**Dockerfile**

![image](https://github.com/user-attachments/assets/7abf6cae-9f45-4e2d-925c-655af9da4d5a)

**Docker image (образ)**

![image](https://github.com/user-attachments/assets/85401af5-b95d-419a-88a7-79d57c8d9aa8)


**Создание контейнеров**

![image](https://github.com/user-attachments/assets/eba7c4e5-a1ca-4098-afea-f5de42dbedc8)

**КАРТИНКА**

![image](https://github.com/user-attachments/assets/ff11c5d1-1995-4e01-87bf-2a4443d320b6)





**Создание сети**

```bash 
sudo docker network create myNetwork
 ```

**Подключение контейнеров к этой сети**

```bash
sudo docker network connect myNetwork my-aafire-1
 ```
```bash
sudo docker network connect myNetwork my-aafire-2
```
**ТЕСТ**

```bash
sudo docker exec -it my-aafire-1 ping my-aafire-2
```

![image](https://github.com/user-attachments/assets/f61640b5-ab0a-4378-b9b4-3ced24262050)
