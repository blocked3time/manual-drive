![image](https://github.com/user-attachments/assets/eeabb0d0-bc1c-4a8a-923c-cbd601c9e491)# manual-drive

opencv 와 다이나믹셀을 이용한 모터 제어 시스템

![image](https://github.com/user-attachments/assets/59235a89-b270-4397-ac28-9e863fca7136)


w,s,a,d,space 로 조작 가능하며 각 전진,후진,좌회전,우회전,정지이다.

opencv 라이브러리를 통해 카메라에서 받은 영상을 영상을 jetson에 저장한다.(약 30프레임)

gstreamer를 통해 jetson에서 pc로 영상을 전송하여 실시간 제어가 가능하다.
