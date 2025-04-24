🛡️ Bộ Sưu Tập Nuclei Template – Thực hành Kiểm thử Bảo mật với Metasploitable 2
📘 Giới thiệu
Chào bạn!
Đây là bộ sưu tập Nuclei Template do mình — một sinh viên đam mê an toàn thông tin — tự xây dựng trong quá trình học và thực hành kiểm thử bảo mật.

Các template này được thiết kế chủ yếu để kiểm tra Metasploitable 2, một hệ thống intentionally vulnerable được sử dụng rộng rãi trong huấn luyện và nghiên cứu bảo mật. Mục tiêu chính của dự án là học tập, rèn luyện kỹ năng phát hiện lỗ hổng, và hiểu sâu hơn về cách hoạt động của các dịch vụ dễ bị tấn công.

🌟 Tính năng nổi bật
Phù hợp với môi trường học tập: Tập trung vào Metasploitable 2 — hệ thống lab quen thuộc với sinh viên ngành an toàn thông tin.

Đa dạng mục tiêu: Bao gồm kiểm tra các dịch vụ như FTP, SSH, Telnet, HTTP, MySQL, v.v.

Cú pháp rõ ràng – dễ mở rộng: Phù hợp cho người mới học Nuclei, dễ đọc và sửa đổi theo nhu cầu thực hành.

Mục đích giáo dục: Cam kết sử dụng hợp pháp, không áp dụng cho hệ thống sản xuất ngoài quyền kiểm soát.

🛠️ Hướng dẫn sử dụng
📦 Yêu cầu
Nuclei: Cài đặt công cụ từ ProjectDiscovery.

Máy ảo Metasploitable 2: Chạy trên VirtualBox/VMware.

Quyền truy cập vào môi trường lab cá nhân.

▶️ Thực hiện quét
# Tải project về máy
git clone https://github.com/ten_nguoi_dung/ten_kho_luu_tru.git

# Kiểm thử với Nuclei
nuclei -t ./ten_kho_luu_tru -u http://<ip-metasploitable>
⚠️ Lưu ý quan trọng
Chỉ sử dụng trong môi trường được phép như Metasploitable hoặc lab cá nhân.

Không chịu trách nhiệm nếu bị lạm dụng: Đây là project học tập, không nên dùng vào mục đích tấn công.

Nên đọc kỹ template trước khi chạy để hiểu rõ hành vi của từng lệnh.

🎓 Lời kết
Dự án này được tạo ra với tinh thần học hỏi, hy vọng sẽ giúp các bạn sinh viên khác có thêm nguồn tài liệu để luyện tập kỹ năng kiểm thử bảo mật.
Mọi góp ý hoặc chia sẻ đều rất được hoan nghênh!
