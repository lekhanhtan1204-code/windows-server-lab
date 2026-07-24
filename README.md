# Bài thực hành Quản trị Windows Server

Repository lưu trữ báo cáo, hình ảnh và script trong quá trình thực hành quản trị mạng trên Windows Server.

## Nội dung thực hành

- Cài đặt Windows Server và Windows Client trên VMware.
- Cấu hình địa chỉ IPv4 tĩnh.
- Cài đặt Active Directory Domain Services.
- Nâng cấp Windows Server thành Domain Controller.
- Tạo và quản lý Domain, Organizational Unit, User và Group.
- Cho máy Windows Client tham gia Domain.
- Cấu hình DNS Server.
- Cấu hình DHCP Server và cấp phát địa chỉ IP.
- Tạo, liên kết và kiểm tra Group Policy Object.
- Áp dụng chính sách cho người dùng và máy tính.
- Kiểm tra GPO bằng `gpupdate` và `gpresult`.
- Phân quyền đăng nhập và truy cập tài nguyên.

## Bài thực hành Group Policy

Các chính sách được thử nghiệm có thể gồm:

1. Chặn Control Panel.
2. Chặn Command Prompt.
3. Chặn Registry Editor.
4. Chặn Task Manager.
5. Chặn Settings.
6. Ẩn ổ đĩa.
7. Chặn truy cập ổ đĩa.
8. Chặn USB lưu trữ.
9. Đặt hình nền Desktop.
10. Không cho thay đổi hình nền.
11. Tắt màn hình khóa.
12. Cấu hình độ dài mật khẩu.
13. Cấu hình độ phức tạp mật khẩu.
14. Cấu hình thời hạn mật khẩu.
15. Khóa tài khoản khi nhập sai mật khẩu.
16. Chặn người dùng đăng nhập cục bộ.
17. Chặn đăng nhập qua Remote Desktop.
18. Hiển thị thông báo trước khi đăng nhập.
19. Tắt Windows Installer.
20. Chặn cài đặt phần mềm.
21. Chặn chạy ứng dụng được chỉ định.
22. Chỉ cho chạy ứng dụng được chỉ định.
23. Xóa biểu tượng Recycle Bin.
24. Ẩn biểu tượng Network.
25. Chặn thay đổi cấu hình mạng.
26. Tắt AutoPlay.
27. Chặn truy cập Taskbar Settings.
28. Chặn thay đổi ngày giờ.
29. Chuyển hướng thư mục người dùng.
30. Triển khai phần mềm bằng Group Policy.

## Cấu trúc repository

```text
windows-server-lab/
├── Bao-cao/
├── Hinh-anh/
│   ├── Active-Directory/
│   ├── DNS-DHCP/
│   └── Group-Policy/
├── Scripts/
├── .gitignore
└── README.md
```

## Công nghệ sử dụng

- Windows Server
- Windows 10/11 Client
- Active Directory Domain Services
- DNS và DHCP
- Group Policy Management
- PowerShell
- VMware Workstation

## Lưu ý

Repository không lưu file máy ảo, file ISO, snapshot hoặc file cài đặt dung lượng lớn. Những file này có thể tạo hoặc cài đặt lại và không phù hợp để đưa lên GitHub.

