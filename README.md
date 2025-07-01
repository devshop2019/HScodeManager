# HScodeManager

## Sử dụng repository này để

* Đối với Kit phát triển, mạch nạp ---> Test nạp code (debug nếu có) được

* Đối với cảm biến, module chức năng, màn hình... ---> Test hoạt động được

## Hướng dẫn sử dụng HScode

(Ví dụ: Bạn muốn test cảm biến với **mã HS1939-BNO055_BMP280**)

Sau khi mở Arduino IDE, tiến hành làm theo các bước sau:

* B1: Vào mục File -> Preferences
![HDSD001](/images/1.png)
* B2: Tại mục "Sketchbook location:", hãy trỏ đến thư mục có tên cùng mã
![HDSD002](/images/2.png)
* B3: Vào mục File -> Sketchbook -> examples để chọn code mẫu
![HDSD003](/images/3.png)
* B4: Vào Tools, mục "Board" chọn "Arduino UNO", mục "Port" chọn "COMx" (x tùy máy, miễn đúng là của board UNO)
![HDSD004](/images/4.png)
* B5: Nạp code (Chắc chắn thành công nếu như làm đúng các bước trên)
![HDSD005](/images/5.png)
* B6: Tắt nguồn, đấu dây (Wiring)
![HDSD006](/images/6.png)
* B7: Cập điện UNO, xem KQ
![HDSD007](/images/7.png)

<video width="640" height="360" controls>
  <source src="images/KQ0001.mp4" type="video/mp4">
</video>