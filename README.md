# Thực hành tạo Repository mới trên GitHub

Repository này ghi lại quy trình tạo một dự án Git mới, kết nối repository trên máy tính với GitHub và đẩy `README.md` lên nhánh `main`.

## Các lệnh Git đã sử dụng

```powershell
git init
git remote add origin https://github.com/Viet0810/github-basics-practice.git
git branch -M main
git add README.md
git commit -m "Add README.md file"
git push -u origin main
```

- `git init`: khởi tạo repository Git trong thư mục hiện tại.
- `git remote add origin <URL>`: thêm repository GitHub làm remote có tên `origin`.
- `git branch -M main`: đổi tên nhánh hiện tại thành `main`.
- `git add README.md`: đưa README vào staging area để chuẩn bị commit.
- `git commit -m "..."`: lưu snapshot các thay đổi đã staging cùng thông điệp mô tả.
- `git push -u origin main`: đẩy nhánh `main` lên remote `origin` và thiết lập upstream cho những lần push sau.

## Một số lệnh thư mục được dùng

```powershell
New-Item -ItemType Directory -Path 'D:\01\github-basics-practice'
Set-Location 'D:\01\github-basics-practice'
```

- `New-Item -ItemType Directory`: tạo thư mục dự án mới trên máy tính.
- `Set-Location`: chuyển Terminal vào thư mục dự án để chạy lệnh Git tại đúng nơi.

## Repository

[https://github.com/Viet0810/github-basics-practice](https://github.com/Viet0810/github-basics-practice)
