- [1. git config](#1-git-config)
- [2. git init](#2-git-init)
- [3. git add](#3-git-add)
- [4. git clone](#4-git-clone)
- [5. git commit](#5-git-commit)
- [6. git status](#6-git-status)
- [7. git push](#7-git-push)
- [8. git checkout](#8-git-checkout)
- [9. git remote](#9-git-remote)
- [10. git branch](#10-git-branch)
- [11. git pull](#11-git-pull)
- [12. git merge](#12-git-merge)
- [13. git log](#13-git-log)
- [14. git diff](#14-git-diff)
# 1. git config
Một trong những lệnh config được dùng nhiều nhất. Dùng để đặt cấu hình riêng cho người dùng. Còn nhiều config khác mà bạn có thể xem thêm
```
git config --global user.name <username>
git config --global user.email <mailaddress>
```
# 2. git init
Tạo một repo mới trên máy của bạn
```
git init
```

# 3. git add
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

# 4. git clone
Sao chép 1 repo trên server về máy
```
git clone <Đường dẫn đến repo trên server>
```

# 5. git commit
Xác nhận và lưu những thay đổi của project
```
git commit -m "<Ghi chú commit>"
```

# 6. git status
Hiển thị trạng thái của project như: thêm, xoá, sửa file...
```
git status
```

# 7. git push
Cập nhật những thay đổi của project và gửi lên server
```
git push origin <Tên nhánh>
```

# 8. git checkout
Tạo một nhánh mới và chuyển qua nhánh đó (từ master)
```
git checkout -b <Tên nhánh>
```
Chuyển nhánh
```
git checkout <Tên nhánh>
```

# 9. git remote
Xem danh sách remote
```
git remote -v
```
Kết nối repo của bạn đến máy chủ remote
```
git remote add origin <Đường dẫn đến repo trên server>
```
Đổi tên remote
```
git remote rename <Tên remote cũ> <Tên remote mới> 
```

# 10. git branch
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

# 11. git pull
Lấy source mới nhất trên server về và tiến hành trộn
```
git pull
```

# 12. git merge
Để trộn một nhánh vào nhánh đang hoạt động
```
git merge <Tên nhánh>
```

# 13. git log
Hiển thị danh sách cách commit trên 1 nhánh và các thông tin của nó
```
git log
```
# 14. git diff
Xem xung đột với tệp cơ sở
```
git diff --base
```
Xem xung đột với nhánh được trộn trước khi trộn
```
git diff
```