# Wildlife-Image-Classification-Project

Dự án này là một chuỗi các notebook Jupyter được thiết kế để hướng dẫn bạn xây dựng một hệ thống phân loại hình ảnh động vật hoang dã từ cơ bản đến nâng cao, sử dụng các nguyên tắc của học sâu (deep learning) và thư viện PyTorch.

Kho lưu trữ này chứa các notebook Jupyter từ khóa học **AI Lab: Deep Learning for Computer Vision** của [WorldQuant University](https://www.wqu.edu/). Dự án tập trung vào việc khám phá hình ảnh như dữ liệu, xây dựng và huấn luyện mô hình phân loại nhị phân và đa lớp sử dụng PyTorch. Các notebook minh họa cách xử lý dữ liệu hình ảnh, xây dựng mạng nơ-ron tích chập (CNN) và đánh giá mô hình.

## Mục Tiêu

- Hiểu cách biểu diễn hình ảnh dưới dạng dữ liệu số (tensor) và khám phá đặc trưng của chúng.
- Xây dựng và huấn luyện mô hình phân loại nhị phân (binary classification) cho hình ảnh.
- Xây dựng và huấn luyện mô hình phân loại đa lớp (multiclass classification) cho hình ảnh.
- Sử dụng các công cụ như PyTorch để xử lý dữ liệu, huấn luyện và đánh giá mô hình.

## Bộ Dữ Liệu

- **Nguồn**: Bộ dữ liệu bao gồm hình ảnh động vật (ví dụ: antelope, grizzly), được tổ chức theo thư mục cho phân loại nhị phân (hai lớp) và đa lớp (nhiều lớp).
- **Vị trí**: Dữ liệu lưu trong các thư mục như `data_p1/train`, được chia theo lớp (ví dụ: antelope, grizzly).
- **Tiền xử lý**: Hình ảnh được tải bằng PIL, chuyển đổi thành tensor, thay đổi kích thước và chuẩn hóa. Xử lý các chế độ hình ảnh khác nhau (grayscale, RGB) và tính toán giá trị trung bình kênh màu.
- **Đặc trưng**: Hình ảnh có kích thước khác nhau, giá trị pixel từ 0-1 sau khi chuyển thành tensor.

## Cấu Trúc Kho Lưu Trữ

| Notebook | Mô Tả |
|----------|-------|
| `011-image-as-data.ipynb` | Khám phá hình ảnh như dữ liệu: Tải, hiển thị, chuyển đổi thành tensor, phân tích kích thước, chế độ và giá trị trung bình kênh màu. |
| `013-binary-classification.ipynb` | Xây dựng và huấn luyện mô hình phân loại nhị phân sử dụng CNN với PyTorch, đánh giá bằng độ chính xác và ma trận nhầm lẫn. |
| `014-multiclass-classification.ipynb` | Xây dựng và huấn luyện mô hình phân loại đa lớp, sử dụng các thư viện như Torchvision cho dữ liệu và mô hình. |
