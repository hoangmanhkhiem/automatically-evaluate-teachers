# Công cụ đánh giá giảng viên tự động

## Description

Công cụ này được viết bằng ngôn ngữ Python

Mục đích viết ra công cụ này để giảm thời gian đánh giá giảng viên cho những ai lười.

## Install

Python :  https://www.python.org/downloads/

Chromedriver: https://googlechromelabs.github.io/chrome-for-testing/

## Setup

```
I. Clone the repository:
> git clone https://github.com/hoangmanhkhiem/automatically-evaluate-teachers.git

Chọn 1 trong 2 phương án
2a. Phương án 1: Chạy file Exe

Sau đó không cần quan tâm các dòng bên dưới

2b. Phương án 2: Setup nếu exe lỗi

1. Change into the project directory:
> cd automatically-evaluate-teachers

2. Create a virtual environment:
> py -m venv venv

3. Activate the virtual environment:
> source venv/bin/activate (Linux)
> venv\Scripts\activate (Windows)

4. Install dependencies:
> pip install -r requirements.txt
```
## Run
```
python run.py
```

## Run2

1. Activate the virtual environment (venv là tên môi trường mẫu nếu bạn trước đó cài môi trường như bước setup thì copy làm theo còn không thì phải thay venv về tên môi trường trước đó bạn đã setup):
> source venv/bin/activate (Linux)
> 
> venv\Scripts\activate (Windows)

5. run

> python run.py

### 

- Nhập mail

- Nhập pass

- Nhập đường link bài đánh giá

Lấy đường link bài đánh giá bằng cách truy cập: 
https://sis.utc.edu.vn/survey/overview.php
Sau đó chọn bài vào copy đường link

## License

This script is licensed under the [MIT License](https://opensource.org/license/mit/).
