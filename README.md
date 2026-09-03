# ATmega32 Embedded Learning Board

<h2 align="center">
  THIẾT KẾ VÀ CHẾ TẠO BO MẠCH LẬP TRÌNH NHÚNG DỰA TRÊN VI ĐIỀU KHIỂN AVR CHO MỤC ĐÍCH GIÁO DỤC
</h2>

<p align="center">
  <b>ATmega32 Embedded Training Board</b>
</p>

---

##  Giới thiệu

Đây là dự án thiết kế và chế tạo **bo mạch học tập lập trình nhúng sử dụng vi điều khiển ATmega32**, được xây dựng nhằm phục vụ việc học tập, thực hành và nghiên cứu các hệ thống nhúng.

Bo mạch tích hợp nhiều ngoại vi phổ biến, giúp sinh viên có thể thực hành lập trình vi điều khiển, giao tiếp với cảm biến, thiết bị hiển thị, bộ nhớ và các chuẩn giao tiếp thông dụng.

Toàn bộ sơ đồ nguyên lý và PCB của bo mạch được thiết kế bằng **KiCad**.

---

##  Mục tiêu

- Thiết kế một bo mạch học tập dựa trên vi điều khiển **ATmega32**.
- Tích hợp các ngoại vi thường sử dụng trong các bài thực hành vi điều khiển.
- Hỗ trợ nhiều chuẩn giao tiếp như UART, I2C, SPI và 1-Wire.
- Thiết kế PCB hoàn chỉnh bằng KiCad.
- Xây dựng nền tảng phần cứng phục vụ các bài thực hành lập trình nhúng.
- Kiểm thử từng chức năng của bo mạch trên phần cứng thực tế.

---

##  Vi điều khiển:  ATmega32

##  Các ngoại vi tích hợp

Bo mạch được thiết kế với các khối chức năng:

| Ngoại vi | Chức năng |
|---|---|
| LCD 16x2 | Hiển thị thông tin |
| LED 7 đoạn 4 số | Hiển thị số |
| LM35 | Đo nhiệt độ |
| DS18B20 | Cảm biến nhiệt độ |
| DS3231 | Đồng hồ thời gian thực |
| Relay | Điều khiển thiết bị |
| Micro SD Card | Lưu trữ dữ liệu |
| LED đơn | Hiển thị trạng thái |
| Button | Nhập tín hiệu số |
| Potentiometer | Tạo tín hiệu analog |
| LDR | Đo cường độ ánh sáng |
| CH340E | Giao tiếp USB-UART |

Các ngoại vi trên được tích hợp nhằm phục vụ nhiều bài thực hành về GPIO, ADC, UART, I2C, SPI, 1-Wire và điều khiển thiết bị.

---

##  Các chuẩn giao tiếp
UART,I2C,SPI,1-Wire

##  Thiết kế bằng KiCad

Project được thiết kế bằng **KiCad 9**.

Các file chính:

```text
ATmega32/
│
├── atmega32.kicad_pro       # KiCad Project
├── atmega32.kicad_sch       # Schematic
├── atmega32.kicad_pcb       # PCB Layout
│
├── aa.kicad_sym             # Custom Symbol Library
│
├── CR1220 SMD.pretty/       # Footprint Library
├── Micro.pretty/            # Footprint Library
├── SN74LVC125APWR.pretty/   # Footprint Library
│
├── fp-lib-table
├── sym-lib-table
└── Logo_hus.png
```

## Hình ảnh sản phẩm trong quá trình làm
Hình ảnh ở trên là bản đầu tiên làm, file ở trên đã sửa sau khi test các chức năng sửa những lỗi cho ra bản hoàn chỉnh nhất. 
