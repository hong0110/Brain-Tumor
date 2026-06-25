# Hệ thống Hỗ trợ Chẩn đoán U não từ ảnh MRI

## Giới thiệu

Hệ thống Hỗ trợ Chẩn đoán U não từ ảnh MRI là ứng dụng web sử dụng trí tuệ nhân tạo nhằm hỗ trợ phát hiện và phân loại khối u não từ ảnh MRI. Hệ thống cho phép người dùng tải ảnh lên, thực hiện dự đoán bằng mô hình Deep Learning và hiển thị kết quả trực quan trên giao diện web.

Đây là dự án học phần được thực hiện theo nhóm, kết hợp giữa phân tích nghiệp vụ, phân tích hệ thống, thiết kế giao diện, phát triển ứng dụng web và tích hợp mô hình AI.

---

## Mục tiêu dự án

- Hỗ trợ phát hiện và phân loại khối u não từ ảnh MRI.
- Tự động hóa quy trình dự đoán bằng mô hình Deep Learning.
- Xây dựng hệ thống web trực quan, dễ sử dụng.
- Quản lý lịch sử dự đoán của người dùng.

---

## Chức năng chính

- Đăng nhập hệ thống.
- Tải ảnh MRI lên hệ thống.
- Dự đoán loại khối u bằng mô hình AI.
- Hiển thị kết quả dự đoán.
- Quản lý lịch sử dự đoán.
- Kiểm tra dữ liệu đầu vào và xử lý lỗi.

---

## Nội dung thực hiện

Dự án được triển khai theo quy trình phát triển phần mềm hoàn chỉnh, bao gồm:

### Business Analysis
- Phân tích bài toán và xác định phạm vi dự án.
- Phân tích yêu cầu chức năng và phi chức năng.
- Xây dựng quy trình xử lý của hệ thống.
- Đề xuất giải pháp hỗ trợ chẩn đoán bằng AI.

### System Analysis & Design
- Thiết kế kiến trúc tổng thể của hệ thống.
- Thiết kế cơ sở dữ liệu.
- Thiết kế luồng xử lý giữa các thành phần.
- Thiết kế giao diện người dùng bằng Figma.

### Artificial Intelligence
- Thu thập và tiền xử lý dữ liệu ảnh MRI.
- Nghiên cứu và đánh giá các mô hình Deep Learning.
- Lựa chọn mô hình ResNet50 để xây dựng hệ thống.
- Huấn luyện, đánh giá và tích hợp mô hình AI.

### Web Development
- Xây dựng ứng dụng Web bằng Django.
- Phát triển giao diện và các chức năng của hệ thống.
- Xây dựng API kết nối giữa giao diện và mô hình AI.
- Quản lý người dùng và lịch sử dự đoán.

### Testing & Evaluation
- Kiểm thử chức năng hệ thống.
- Đánh giá hiệu quả mô hình bằng Accuracy, Precision, Recall và F1-Score.
- Kiểm thử trải nghiệm người dùng và xử lý các trường hợp ngoại lệ.

---

## Công nghệ sử dụng

- Python
- Django
- TensorFlow / Keras
- OpenCV
- MySQL
- HTML, CSS, JavaScript
- Figma
- Git & GitHub

---

## Hướng phát triển

- Nâng cao độ chính xác của mô hình.
- Mở rộng số lượng loại khối u được hỗ trợ.
- Triển khai hệ thống trên nền tảng Cloud.
- Cải thiện trải nghiệm người dùng.

---

## Ghi chú

Đây là dự án được thực hiện với mục đích nghiên cứu và học tập.
