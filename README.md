# HScodeManager

## Sử dụng repository này để

* Đối với Kit phát triển, mạch nạp ---> Test nạp code (debug nếu có) được

* Đối với cảm biến, module chức năng, màn hình... ---> Test hoạt động được

## Hướng dẫn sử dụng HScode

(Ví dụ: Bạn muốn test cảm biến với **mã HS1939-BNO055_BMP280**)

Sau khi mở Arduino IDE, tiến hành làm theo các bước sau:

* __B1: Vào mục File -> Preferences__
![HDSD001](/images/1.png)

* __B2: Tại mục "Sketchbook location:", hãy trỏ đến thư mục có tên cùng mã__
![HDSD002](/images/2.png)

* __B3: Vào mục File -> Sketchbook -> examples để chọn code mẫu__
![HDSD003](/images/3.png)

* __B4: Vào Tools, mục "Board" chọn "Arduino UNO", mục "Port" chọn "COMx" (x tùy máy, miễn đúng là của board UNO)__
![HDSD004](/images/4.png)

* __B5: Nạp code (Chắc chắn thành công nếu như làm đúng các bước trên)__
![HDSD005](/images/5.png)

* __B6: Tắt nguồn, đấu dây (Wiring)__
![HDSD006](/images/6.png)

* __B7: Cập điện UNO, xem KQ__
![HDSD007](/images/7.png)

<video width="640" height="360" controls>
  <source src="images/KQ0001.mp4" type="video/mp4">
</video>