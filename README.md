# 🛡️ Bộ Template Nuclei dành cho Metasploitable 2 – Dự án học tập về An ninh mạng

Xin chào!  
Đây là bộ sưu tập các **template Nuclei** do mình — một sinh viên ngành an toàn thông tin — tự viết trong quá trình học tập và thực hành kiểm thử bảo mật.  
Các template này được thiết kế dành riêng cho **Metasploitable 2**, một máy ảo cố tình chứa nhiều lỗ hổng, rất phù hợp để luyện tập trong môi trường lab an toàn.

> ⚠️ **Lưu ý:** Dự án này chỉ phục vụ mục đích học tập và nghiên cứu hợp pháp.

---

## 🎯 Mục đích dự án

Dự án được thực hiện với mục tiêu:

- Thực hành phát hiện các lỗ hổng phổ biến và lỗi cấu hình sai.
- Làm quen với cách hoạt động của công cụ **Nuclei**.
- Hiểu rõ hơn về phản hồi của các dịch vụ khi bị tấn công thử nghiệm.
- Xây dựng nền tảng kiến thức vững chắc về kiểm thử bảo mật — một cách có trách nhiệm.

---

## 💡 Tính năng nổi bật

- 📌 **Tập trung vào Metasploitable 2**: Bao gồm các dịch vụ như FTP, SSH, Telnet, HTTP, MySQL,...
- 🧩 **Dễ đọc, dễ sửa**: Phù hợp cho sinh viên hoặc người mới học sử dụng Nuclei.
- ⚙️ **Học đi đôi với hành**: Tăng cường kỹ năng kiểm thử thực tế trong môi trường ảo hóa.
- ✅ **An toàn và hợp pháp**: Chỉ nên sử dụng trong hệ thống bạn được quyền truy cập.

---

## 🛠 Yêu cầu

- [Nuclei](https://github.com/projectdiscovery/nuclei) (phiên bản mới nhất)
- Máy ảo **Metasploitable 2** (chạy trên VirtualBox, VMware,…)
- Môi trường lab an toàn, có thể kiểm soát được

---

## 🚀 Cách sử dụng

1. **Tải về kho lưu trữ**:
   ```bash
   git clone https://github.com/ten_nguoi_dung/ten_kho_luu_tru.git
   cd ten_kho_luu_tru
Chạy quét bằng Nuclei:

bash
Copy
Edit
nuclei -t ./ -u http://<ip-cua-metasploitable2>
Thay <ip-cua-metasploitable2> bằng địa chỉ IP thật của máy Metasploitable 2 (ví dụ: 192.168.56.101).

📁 Cấu trúc thư mục
Các template được phân loại theo dịch vụ:

Copy
Edit
├── ftp/
├── http/
├── mysql/
├── ssh/
└── telnet/
Mỗi thư mục chứa các file .yaml mô tả lỗ hổng và phương pháp kiểm thử tương ứng.

⚠️ Cảnh báo pháp lý
Chỉ sử dụng các template này trong môi trường bạn được phép kiểm thử.

Tác giả không chịu trách nhiệm với bất kỳ hành vi lạm dụng hoặc thiệt hại nào gây ra bởi việc sử dụng sai mục đích.

Nên đọc kỹ nội dung từng template trước khi sử dụng để tránh rủi ro.

🙏 Ghi nhận
Cảm ơn đội ngũ ProjectDiscovery vì đã phát triển công cụ Nuclei và chia sẻ mã nguồn mở.

Dự án được truyền cảm hứng từ cộng đồng an ninh mạng và các bạn sinh viên cùng chí hướng.

👨‍🎓 Về tác giả
Mình là sinh viên năm 3 chuyên ngành Mạng máy tính và Truyền thông dữ liệu tại Trường Đại học Công nghệ – ĐHQG Hà Nội.
Dự án này là một phần trong quá trình tự học và thực hành kỹ năng kiểm thử bảo mật.

Nếu bạn cũng đang học, đừng ngần ngại fork dự án, góp ý hoặc kết nối cùng học hỏi nhé!
