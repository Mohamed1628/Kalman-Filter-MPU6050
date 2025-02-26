# KalmanFilterMPU6050
This program uses an ESP32 to host a web server that displays readings from an MPU-6050 accelerometer and gyroscope sensor. The sensor orientation is also visualized using a rectangular prism on the web page. The gyroscope sensor readings (pitch and roll at least) are filtered using a Kalman filter. This program uses Visual Studio Code and the extension PlatformIO.

<p align="center">
  <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWg4Z3J6OXJ6dWN5bjJpbGhvMTg1MXhtcGJiaGRrb21oM2dzMTdsaCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ZfgviCJI3zNZ9dE2i1/giphy.gif"><br>
  Folder structure in VS Code after building.
</p>

<iframe src="https://giphy.com/embed/ZfgviCJI3zNZ9dE2i1" width="480" height="269" style="" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/ZfgviCJI3zNZ9dE2i1">via GIPHY</a></p>

## Project Structure
This project is using PlatformIO with the Arduino framework in Visual Studio Code. PlatformIO is just a extra set of tools to make it easier to build a project.

```
Kalman-Filter-MPU6050
  ├───.pio
  ├───.vscode
  ├───data
  │        index.html
  │        script.js
  │        style.css
  ├───include
  ├───lib
  │    └───KalmanFilter
  │            KalmanFilter.cpp
  │            KalmanFilter.h
  ├───src
  │        ESP32_MPU_6050_Web_Server.cpp
  │
  └───test
  │   platformio.ini
```

<p align="center">
  <img src="https://github.com/user-attachments/assets/b5f7d076-f044-4ed2-8564-c85cd385ab7b"><br>
  Folder structure in VS Code after building.
</p>
