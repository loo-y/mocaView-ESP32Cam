# mocaView-ESP32Cam

ESP32 Cam 开发板 Camera WebServer
<br>
实现自动抓拍并上传至远端服务器


## 如何安装
1. 下载 [Arduino IDE](https://www.arduino.cc/en/software)
<br><br>
2. 添加 附加开发板管理器地址:  (多地址以逗号分隔)
<br>
```https://dl.espressif.com/dl/package_esp32_index.json,https://www.arducam.com/downloads/esp32_uno_psram/package_ArduCAM_ESP32_PSRAM_index.json```
<br>
<img width="800" alt="image" src="https://github.com/loo-y/mocaView-ESP32Cam/assets/2792566/08f9110f-eef7-4478-9125-e7df820d5854">
<br>
<br>
3. 安装开发板。```Tools``` -> ```Board``` -> ```Board Manager```
<br>
<img width="800" alt="image" src="https://github.com/loo-y/mocaView-ESP32Cam/assets/2792566/97c4cf87-0622-4af3-9f82-df0482c2e54a">
<br>
<br>
4. 搜索 ```ArduuCAM ESP32S Boards``` 并安装
<br>
<img width="800" alt="image" src="https://github.com/loo-y/mocaView-ESP32Cam/assets/2792566/152ca863-dd72-49d3-b8d9-ec8237dad6a3">
<br>
<br>
5. git clone 当前项目到本地并在  ```Arduino IDE``` 中打开
<br>
<br>
6. 修改代码中的配置项，注意注释中的提示
<br>
<img width="800" alt="image" src="https://github.com/loo-y/mocaView-ESP32Cam/assets/2792566/f43e3081-a7a3-450a-bbfa-e7c428e33a8e">
<br>
<br>
7. 连接 ESP32Cam 到电脑。
<br>
<br>
8. 选择正确的 Board, Port, Partition Scheme。
<br>
<img width="800" alt="image" src="https://github.com/loo-y/mocaView-ESP32Cam/assets/2792566/e0c6c989-d00e-4c5a-afc2-5ef8a641e2e4">
<br>
<br>
9. 点击 Upload 进行编译并写入开发板
<br>
<img width="800" alt="image" src="https://github.com/loo-y/mocaView-ESP32Cam/assets/2792566/86527ae7-c6f5-4254-afe0-9bb00e456b22">
