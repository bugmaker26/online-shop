# Hướng dẫn 
# Cách thành viên trong nhóm tham gia xây dựng project
# Bước 1: Nhận quyền truy cập
Chủ repository mời các thành viên vào project bằng quyền Collaborator trên GitHub.
Sau khi nhận được lời mời, thành viên cần:
- đăng nhập GitHub
- chấp nhận lời mời bằng Accept invitation
# Bước 2: Clone project về máy
Sau khi được cấp quyền, thành viên tải project về máy bằng lệnh:
*******************************************************
git clone https://github.com/bugmaker26/online-shop.git
*******************************************************
# Bước 3: Đồng bộ code trước khi làm
Trước khi bắt đầu chỉnh sửa, cần lấy phiên bản mới nhất từ GitHub:
*******************************************************
**git pull origin main**
*******************************************************
# Bước 4: Chỉnh sửa phần được phân công
# Sau khi sửa xong, chạy các lệnh:
*******************************************************
**git add .**

**git commit -m "Mo ta noi dung da sua"**

**git push origin main**
*******************************************************
# 5. Quy tắc
- luôn pull trước khi sửa code
- không nên để nhiều người sửa cùng một file cùng lúc
- commit với nội dung rõ ràng
- push thường xuyên để tránh dồn nhiều thay đổi
- không upload file rác hoặc file cá nhân lên repository
# 6. File không nên đưa lên GitHub
.vscode/ 

.DS_Store

__MACOSX/

._*
