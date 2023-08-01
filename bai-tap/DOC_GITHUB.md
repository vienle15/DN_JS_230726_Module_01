Mở terminal Ctrl + `
Khởi tạo git $ git init
Thêm các file code đã thay đổi để sẵn sàng commit: $ git add .
Kiểm tra trạng thái của git: $ git status
Commit nội dung đã add: $ git commit -m "<thông tin mô tả>" // ex: $ git commit -m "session 01"
Kết nối tới repo github: $ git remote add origin <link_repo> // EX: $ git remote add origin https://github.com/khoalyRikkei/DN_JS_230726_Module_01.git
Đẩy dữ liệu lên repo: git push --set-upstream origin master
Sau khi đã push thành công. Sau này mỗi lần up code lên chỉ thực hiện 3 bước:
git add .
git commit -m "<noi_dung>"
git push
Clone code
git clone <link_repo>
