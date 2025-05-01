#!/bin/bash
# Đảm bảo đã ở đúng thư mục repository
cd /path/to/your/repo || { echo "Không thể vào 
thư mục repo"; exit 1; }
# Thêm file .deb vào Git
git add * || { echo "Không thể thêm file vào 
git"; exit 1; }
# Commit với thông điệp tự động
git commit -m "Cập nhật file .deb mới" || { 
echo "Không thể commit"; exit 1; }
# Đẩy thay đổi lên repository
git push || { echo "Push không thành công"; 
exit 1; }
echo "Quá trình cập nhật và đẩy file lên repo JTIS hoàn tấ
