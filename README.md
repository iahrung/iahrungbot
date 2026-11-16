# Iahrungbot 🌿 ⚡

> *Trợ lý thông minh sinh ra từ đại ngàn, làm chủ mọi hệ thống năng lượng và IoT.* Từ trạm sạc xe điện đến các tấm pin mặt trời giữa vùng cao nguyên, Iahrungbot chính là "bộ não" bền bỉ vận hành vạn vật.

---

## 🌐 Tầm nhìn

Iahrungbot không chỉ là một trợ lý ảo thông thường; nó là một **tác nhân hệ điều hành biên (Edge OS Agent)** chuyên biệt cho hạ tầng phân tán. Được thiết kế để bám sát thực địa, Iahrungbot kết nối liền mạch giữa phần cứng công nghiệp, cảm biến nông nghiệp, năng lượng tái tạo và ý định của con người.

Mục tiêu của chúng tôi rất thực tế: **Tự chủ và bền bỉ ở mọi địa hình.** Chúng tôi hoạt động ngay tại những nơi khắc nghiệt nhất — từ các tủ điều khiển năng lượng mặt trời ngoài trời, trạm sạc xe điện thông minh, hệ thống giám sát nông nghiệp đến các trung tâm điều khiển cục bộ không cần internet (chế độ 4G offline).

---

## ⚡ Kiến trúc cốt lõi

Iahrungbot được xây dựng bằng **ngôn ngữ Go** kết hợp với **Python** để đạt hiệu năng tối ưu, tiêu thụ tài nguyên cực thấp và độ ổn định vĩnh cửu. Nó hoạt động như một tiến trình nhẹ (lightweight daemon) chạy trên Linux nhúng (OpenWrt, Ubuntu Core) và các vi điều khiển, mang lại khả năng tự phục hồi và tự chủ hoàn toàn cho hệ thống.

---

## 🚀 Nơi tôi chạy bộ

* **☀️ Hệ thống năng lượng mặt trời:** Giám sát biến tần (Inverter), tối ưu hóa công suất và điều khiển hệ thống Tigo CCA / Modbus RS485.
* **🔌 Trạm sạc xe điện (EV Charging):** Tích hợp phần cứng sạc Grasen, xử lý giao thức chuẩn OCPP low-level và bảo mật WebSocket TLS/SSL.
* **📡 Thiết bị Nhúng & IoT vùng biên:** Raspberry Pi, Orange Pi, các bo mạch vi điều khiển kết nối mô-đun 4G LTE tại vùng sâu vùng xa.
* **🖥️ Máy chủ cục bộ & Cloud:** Vận hành trên các hệ thống máy chủ nội bộ hoặc VPS tối ưu hóa với PM2 và Docker.

---

## 🛠️ Khả năng của hệ thống

Với vai trò là một OS Agent chuyên sâu về phần cứng và IoT, tôi sở hữu các khả năng cốt lõi:

* **Giao diện phần cứng & Công nghiệp:** Tương tác trực tiếp qua cổng Serial, Modbus RTU/RS485, đọc trạng thái nguồn điện, cảm biến môi trường và đo lường điện năng.
* **Hệ thống kỹ năng linh hoạt (Modular Skills):** Các mô-đun kỹ năng độc lập có thể nạp nhanh, chuyển đổi linh hoạt giữa các vai trò (kỹ sư giám sát trạm sạc, chuyên gia năng lượng, điều phối viên dữ liệu).
* **Bộ nhớ cục bộ an toàn:** Lưu trữ dữ liệu ngoại tuyến bền vững, tự động đồng bộ hóa lên đám mây khi có kết nối mạng trở lại, đảm bảo hệ thống không bao giờ mất dữ liệu.
