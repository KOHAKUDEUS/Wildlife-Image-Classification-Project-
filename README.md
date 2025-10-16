# Wildlife-Image-Classification-Project

Dự án này là một chuỗi các notebook Jupyter được thiết kế để hướng dẫn bạn xây dựng một hệ thống phân loại hình ảnh động vật hoang dã từ cơ bản đến nâng cao, sử dụng các nguyên tắc của học sâu (deep learning) và thư viện PyTorch.

## Nội dung chính
### 1. 011-image-as-data.ipynb
Notebook này giới thiệu các bước chuẩn bị dữ liệu hình ảnh cho mô hình học sâu. Bạn sẽ tìm hiểu cách tải, xử lý và biến đổi hình ảnh từ các định dạng khác nhau thành các tensor PyTorch. Notebook cũng đề cập đến cách giải quyết các vấn đề thường gặp như kích thước và chế độ màu sắc (RGB, grayscale) không đồng nhất trong tập dữ liệu.

### 2. 012-fix-my-code.ipynb
Trong notebook này, chúng ta sẽ tập trung vào kỹ năng gỡ lỗi cần thiết khi làm việc với PyTorch. Bạn sẽ được thực hành tìm và sửa các lỗi trong đoạn mã, từ đó hiểu rõ hơn về cách đọc thông báo lỗi và đưa ra giải pháp hiệu quả.

### 3. 013-binary-classification.ipynb
Notebook này đi sâu vào việc xây dựng một mô hình phân loại nhị phân (binary classification). Bạn sẽ học cách chuẩn bị dữ liệu cho bài toán hai lớp (ví dụ: "có động vật hoang dã" và "không có"), xây dựng một mạng nơ-ron đơn giản, và huấn luyện mô hình để phân biệt giữa hai loại. Các khái niệm như hàm mất mát (loss function) và độ chính xác (accuracy) cũng được giới thiệu.

### 4. 014-multiclass-classification.ipynb 
Tiếp nối từ bài học trước, notebook này mở rộng kiến thức về mô hình phân loại đa lớp (multiclass classification). Bạn sẽ học cách điều chỉnh mô hình để xử lý nhiều hơn hai lớp động vật (ví dụ: gấu, sói, hươu), cách tổ chức dữ liệu và sử dụng các hàm kích hoạt (activation function) cũng như hàm mất mát phù hợp cho bài toán này.

Để chạy các notebook này, bạn cần cài đặt các thư viện cần thiết, bao gồm **PyTorch** và **Pillow**.

```bash
pip install torch torchvision pillow
