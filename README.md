# Toke_auth
## 1. Run server
npm init -y

npm install express

node app.js

![Run server](/public/results/server.png)

# 2. Test Postman

### a. Go to profile
Chưa đăng kí, chưa đăng nhập thì bị từ chối quyền xem profile

![Profile Fail](/public/results/profile_fail.png)

Nên cần phải đăng kí trước

### b. Register

![Register](/public/results/register.png)

Trên MongoDB

![User In MongoDB](/public/results/user_register_mongodb.png)

### c. Login

![Login](/public/results/login.png)

Kiểm tra lại profile sau khi login (Vẫn thất bại)

![Profile No Token](/public/results/profile_no_token.png)

Sau khi nhập khóa token vào (xem profile thành công)

![Profile - Token](/public/results/profile_token.png)

Thay đổi token hết hạn sau 120s

![Change - Token](/public/results/change_token1.png)

Tạo người dùng mới 

![Register](/public/results/new_user.png)

Đăng nhập

![Login](/public/results/login1.png)

Xem profile với token

![Profile - Token](/public/results/profile_token1.png)

Sau 120s kiểm tra lại

![Profile No Token](/public/results/profile_no_token1.png)

