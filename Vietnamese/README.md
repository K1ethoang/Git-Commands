# 1. Git là gì?
Là phần mềm quản lý mã nguồn phân tán được phát triển bởi Linus Torvalds vào năm 2005, ban đầu dành cho việc phát triển nhân Linux. Hiện nay, Git trở thành một trong các phần mềm quản lý mã nguồn phổ biến nhất. Git là phần mềm mã nguồn mở được phân phối theo giấy phép công cộng GPL2.
Git có khả năng chạy trên nhiều hệ điều hành khác nhau như: Linux, Windows, Mac OSX…

# 2. Các câu lệnh

## 2.1. Cơ bản

### 2.1.1. git config
Một trong những lệnh config được dùng nhiều nhất. Dùng để đặt cấu hình riêng cho người dùng. Còn nhiều config khác mà bạn có thể xem thêm
```
git config --global user.name <username>
git config --global user.email <mailaddress>
```
### 2.1.2. git init
Tạo một repo mới trên máy của bạn
```
git init
```

### 2.1.3. git init
Tạo một repo mới trên máy của bạn
```
git init
```

### 2.1.4. git add
Cập nhật tất cả
```
git add .
```
Cập nhật tất cả các file theo dạng (vd: .c, .cpp, .css...).
```
git add *.<tên đuôi> 
```
Cập nhật file theo tên
```
git add <tên file 1> [<tên file 2> ... <Tên file n>]
```

### 2.1.5. git clone
Sao chép 1 repo trên server về máy
```
git clone /đường-dẫn-đến/repository/
```
hoặc
```
git clone tênusername@địachỉmáychủ:/đường-dẫn-đến/repository
```

### 2.1.6. git commit
Xác nhận và lưu những thay đổi của project
```
git commit -m "<Ghi chú commit>"
```

### 2.1.7. git status
Hiển thị trạng thái của project như: thêm, xoá, sửa file...
```
git status
```

### 2.1.8. git push
Cập nhật những thay đổi của project và gửi lên server
```
git push origin <Tên nhánh>
```

### 2.1.9. git checkout
Tạo một nhánh mới và chuyển qua nhánh đó (từ master)
```
git checkout -b <Tên nhánh>
```
Chuyển nhánh
```
git checkout <Tên nhánh>
```

### 2.1.10. git remote
Xem danh sách remote
```
git remote -v
```
Kết nối repo của bạn đến máy chủ remote
```
git remote add origin <Đường dẫn>
```
Đổi tên remote
```
git remote rename <Tên remote cũ> <Tên remote mới> 
```

### 2.1.11. git branch
Tạo nhánh mới
```
git branch <Tên nhánh>
```
Xoá nhánh
```
git branch -d <Tên nhánh>
```
Kiểm tra nhánh hiện tại
```
git branch
```

### 2.1.12. git pull
Lấy source mới nhất trên server về và tiến hành trộn
```
git pull
```

### 2.1.13. git merge
Để trộn một nhánh vào nhánh đang hoạt động
```
git merge <Tên nhánh>
```

### 2.1.14. git log
Hiển thị danh sách cách commit trên 1 nhánh và các thông tin của nó
```
git log
```
### 2.1.15. git diff
Xem xung đột với tệp cơ sở
```
git diff --base
```
Xem xung đột với nhánh được trộn trước khi trộn
```
git diff
```
