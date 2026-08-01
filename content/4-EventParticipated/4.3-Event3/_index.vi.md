---
title: "Workshop: Khám phá chuyên sâu chứng chỉ AWS (CLF-C02 & AIF-C01)"
date: 2026-08-01
weight: 1
chapter: false
pre: " <b> 4.3. </b> "
---

# Báo cáo sự kiện: Khám phá chuyên sâu chứng chỉ AWS

### Mục tiêu sự kiện

- Nắm bắt toàn diện về cấu trúc của kỳ thi chứng chỉ AWS Certified Cloud Practitioner (CLF-C02) và AI Practitioner (AIF-C01).
- Hiểu sâu về các khái niệm cốt lõi của AWS Cloud, bao gồm hạ tầng toàn cầu, tính sẵn sàng cao (High Availability) và tính co giãn (Elasticity).
- Tìm hiểu về Khung áp dụng đám mây (AWS CAF), tối ưu hóa tài nguyên (Rightsizing) và bảo mật để thu hẹp khoảng cách giữa việc "Có bằng cấp" (Certified) và "Thực sự đủ năng lực" (Qualified).

### Diễn giả khách mời

Buổi chia sẻ chuyên sâu được dẫn dắt bởi:
- **Anh Danh Hoàng Hiếu Nghị** - Từ cộng đồng AWS Student Builder Group.

### Những điểm nổi bật

#### 1. Tổng quan kỳ thi: Các lĩnh vực và Tỷ trọng
- Cấu trúc chi tiết của bài thi CLF-C02 được chia thành:
  - **Domain 1:** Cloud Concepts - Các khái niệm Đám mây (24%)
  - **Domain 2:** Security and Compliance - Bảo mật và Tuân thủ (30%)
  - **Domain 3:** Cloud Technology and Services - Dịch vụ và Công nghệ Đám mây (34%)
  - **Domain 4:** Billing, Pricing, and Support - Thanh toán, Định giá và Hỗ trợ (12%)

#### 2. Khái niệm Đám mây & Hạ tầng Toàn cầu
- **Hạ tầng toàn cầu (1.1.2):** Cách AWS tổ chức hạ tầng thành các Regions (Khu vực), Availability Zones (Vùng sẵn sàng) và các edge locations. Có 4 tiêu chí quan trọng để chọn Region: độ trễ, chi phí, yêu cầu tuân thủ dữ liệu và tính khả dụng của dịch vụ.
- **Tính sẵn sàng cao, Co giãn và Nhanh nhạy (1.1.3):** 
  - *High Availability:* Chạy dự phòng trên nhiều AZ thông qua Load Balancer để đảm bảo hệ thống không bị "sập".
  - *Elasticity:* Tự động thêm hoặc bớt tài nguyên theo nhu cầu thực tế (Auto-scaling).
  - *Agility:* Tốc độ triển khai tài nguyên cực nhanh, giúp giảm chi phí thử nghiệm ý tưởng mới và đẩy nhanh thời gian ra mắt sản phẩm.

#### 3. Khung áp dụng đám mây AWS (AWS CAF)
- **Hiểu về CAF (1.3.3):** Khám phá 6 khía cạnh đánh giá sự sẵn sàng lên mây (Kinh doanh, con người, quản trị, nền tảng, bảo mật, vận hành).
- **Lợi ích mang lại:** Giảm thiểu rủi ro doanh nghiệp, cải thiện hiệu suất ESG, tăng doanh thu và tối ưu hóa hiệu quả hoạt động.

#### 4. Tối ưu hóa chi phí & Rightsizing
- **Rightsizing (1.4.6):** Là quá trình liên tục điều chỉnh kích thước tài nguyên cho khớp với khối lượng công việc thực tế. Việc sử dụng các công cụ như AWS Compute Optimizer và AWS Cost Explorer giúp tránh lãng phí tài nguyên và tiết kiệm chi phí hiệu quả.

#### 5. Bảo mật và Tuân thủ (Security and Compliance)
- Đi sâu vào Domain 2 (chiếm 30% bài thi), nhấn mạnh Mô hình Trách nhiệm Chung (Shared Responsibility Model) của AWS, quản trị bảo mật đám mây và các khả năng quản lý quyền truy cập.

### Những gì tôi học được

#### Kiến thức chuyên môn
- Phân biệt rõ ràng giữa Region và Availability Zone, cũng như cách các edge locations lưu trữ đệm (cache) nội dung ở gần người dùng cuối hơn.
- Hiểu sâu hơn về các lựa chọn thiết kế kiến trúc như khả năng chịu lỗi và tính co giãn, giúp biến hóa đơn máy chủ cố định hàng tháng thành đường cong chi phí dựa trên mức sử dụng thực tế.

#### Tư duy nghề nghiệp & Thi cử
- **Certified vs. Qualified:** Việc thi đậu chỉ giúp bạn "Certified" (có chứng chỉ), nhưng việc thực sự hiểu các nguyên lý cốt lõi (như tại sao cần có Framework hay cách rightsizing hoạt động trong thực tế) mới là thứ giúp bạn "Qualified" (đủ năng lực) để làm việc trong môi trường thực tế.

### Ứng dụng vào Công việc & Thực tập

- **Kế hoạch ôn thi:** Tôi sẽ xây dựng lộ trình học tập dựa trên 4 Domain, tập trung nhiều thời gian hơn cho Domain 3 (Công nghệ) và Domain 2 (Bảo mật) vì chúng chiếm tỷ trọng lớn nhất.
- **Áp dụng Best Practices:** Tôi dự định sẽ áp dụng nguyên lý "rightsizing" vào các dự án cá nhân trên AWS, liên tục theo dõi CloudWatch metrics để đảm bảo không cấp phát thừa (over-provisioning) cho các máy chủ EC2.

### Trải nghiệm sự kiện

Tham gia buổi Deep Dive này là một cột mốc quan trọng trong hành trình chinh phục chứng chỉ của tôi.

#### Những bài học khai mở
- Trước đây tôi từng nghĩ Cloud Adoption Framework chỉ là những thuật ngữ kinh doanh sáo rỗng. Tuy nhiên, khi được phân tích qua 6 khía cạnh thực tiễn, tôi nhận ra hầu hết các dự án chuyển đổi đám mây thất bại là do các vấn đề về tổ chức/con người chứ không phải do công nghệ.

#### Định hướng rõ ràng hơn
- Bài thuyết trình của anh Hiếu Nghị đã mang đến một lộ trình rõ ràng, đúng trọng tâm để chinh phục kỳ thi CLF-C02. Hiện tại tôi cảm thấy vô cùng tự tin vào phương pháp học tập của mình và có thêm rất nhiều động lực để sớm đạt được chứng chỉ AWS Cloud Practitioner.
#### Event Photos

![Hình ảnh sự kiện](/images/Event/sukien3.png)