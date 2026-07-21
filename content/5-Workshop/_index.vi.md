---
title: "Workshop"
date: 2026-07-21
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

# Hướng dẫn triển khai HMN Bakery

Chào mừng bạn đến với tài liệu hướng dẫn triển khai dự án **HMN Bakery — Website Đặt Bánh Trực Tuyến**.

> 🚀 **Bản Demo:** https://d1babxppbit8as.cloudfront.net/
>
> 🔑 **Tài khoản Admin để kiểm thử:**
> * **Email:** `hoaik4d5@gmail.com`
> * **Mật khẩu:** `123abcd`

## Video minh họa

<iframe width="100%" height="500" src="https://www.youtube.com/embed/E0BoPDcxsTQ" title="Trình phát video YouTube" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Trong workshop này, chúng ta sẽ từng bước triển khai toàn bộ hệ thống **Backend Serverless** bằng **AWS SAM (Serverless Application Model)**, thiết lập dữ liệu ban đầu và kết nối với **Frontend ReactJS**.

Hệ thống được xây dựng trên các dịch vụ của AWS, bao gồm:

- **Amazon API Gateway** – Cung cấp các REST API cho hệ thống.
- **AWS Lambda** – Xử lý các chức năng nghiệp vụ bằng Node.js.
- **Amazon DynamoDB** – Cơ sở dữ liệu NoSQL lưu trữ dữ liệu.
- **Amazon Cognito** – Xác thực và quản lý người dùng.
- **Amazon S3** – Lưu trữ tài nguyên và triển khai Frontend.
- **Amazon SNS / SES** – Gửi thông báo và email.

---

## Nội dung thực hành

1. **[Tổng quan kiến trúc và API](5.1-Overview/)**  
   Tìm hiểu kiến trúc hệ thống và các API được sử dụng.

2. **[Chuẩn bị môi trường](5.2-Prerequisite/)**  
   Cài đặt và cấu hình các công cụ cần thiết như AWS CLI, AWS SAM CLI và Node.js.

3. **[Triển khai Backend bằng AWS SAM](5.3-Deploy/)**  
   Triển khai toàn bộ hạ tầng và dịch vụ Backend lên AWS chỉ với một lệnh.

4. **[Cấu hình sau khi triển khai](5.4-PostDeploy/)**  
   Khởi tạo dữ liệu mẫu và tạo tài khoản quản trị (Admin).

5. **[Kết nối Frontend ReactJS](5.5-Frontend/)**  
   Cấu hình Frontend để kết nối với Backend đã triển khai.

6. **[Dọn dẹp tài nguyên](5.6-Cleanup/)**  
   Xóa các tài nguyên AWS sau khi hoàn thành thực hành nhằm tránh phát sinh chi phí không cần thiết.