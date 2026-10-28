# BÀI LÀM – HACKATHON 01

## - **Mã đề:** 14
## - **Họ tên:**  Bùi Minh Hoàng
## - **Lớp:** HCM_CNTT1
## - **Link repository:** 
## - **Hệ điều hành (Windows/macOS):** Windows

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
pwd 
ls 

mv huong_dan_cham_soc.txt docs/
mv logo_nha_khoa.png media/
cp media/logo_nha_khoa.png backup/
rm temp_226.tmp
..\starter-kit\logs
ls
cd ..\

```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
 Directory: D:\starter-kit\starter-kit


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026   7:45 AM                backup
d-----        10/28/2026   7:48 AM                data
d-----        10/28/2026   8:17 AM                docs
d-----        10/28/2026   8:23 AM                logs
d-----        10/28/2026   8:16 AM                media
d-----        10/28/2026   8:22 AM                nha-khoa-website
-a----        10/28/2026   8:29 AM              0 README.md


    Directory: D:\starter-kit\starter-kit\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           6094 Dieu_Tri_Thang_4.xlsx


    Directory: D:\starter-kit\starter-kit\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM             63 Huong Dan Cham Soc.txt


    Directory: D:\starter-kit\starter-kit\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           1079 Clinic.log
-a----        10/28/2026   8:25 AM            630 daily_report.txt


    Directory: D:\starter-kit\starter-kit\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           5736 Logo Nha Khoa - Copy.PNG


    Directory: D:\starter-kit\starter-kit\nha-khoa-website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
------        10/27/2026   1:32 AM             65 .env
-a----        10/27/2026   1:32 AM           2224 bai_lam.md
-a----        10/28/2026   8:22 AM              0 daily_report.txt
------        10/27/2026   1:32 AM             22 temp_226.tmp


```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
Get-Content Clinic.log | select-string "ERROR" | echo >> daily_report.txt
```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
 2 0 2 6 - 0 4 - 2 8   0 9 : 5 1 : 2 9   [ E R R O R ]   K e t   n o i   h e   t h o n g   h o   s o   t h a t   b a i 
 
 2 0 2 6 - 0 4 - 2 8   1 0 : 0 7 : 2 9   [ E R R O R ]   K h o n g   t i m   t h a y   t r a n g   / b a n g - g i a - d i c h - v u   ( 4 0 4 ) 

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] Heading 1: tên dự án
- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
 Get-Content Clinic.log | select-string "ERROR" | Measure-Object

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text

Count    : 5
Average  :
Sum      :
Maximum  :
Minimum  :
Property :

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/dieu_tri_thang_4.xlsx`, không cần ghi vào đây.
