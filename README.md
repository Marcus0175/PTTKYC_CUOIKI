## 📋 Yêu cầu hệ thống

- Node.js 14.x hoặc cao hơn
- MongoDB 4.x hoặc cao hơn
- NPM hoặc Yarn

## ⚙️ Cài đặt và chạy

### 1. Clone repository
```bash
git clone [repository-url]
cd gym-management-system
```

### 2. Cài đặt Backend
```bash
cd backend
npm install
```

### 3. Cấu hình Backend
Tạo file `.env` trong thư mục `backend`:
```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/gym-management
JWT_SECRET=your_jwt_secret_key
```

### 4. Khởi động MongoDB
Đảm bảo MongoDB đang chạy trên máy local hoặc cấu hình MongoDB Atlas.

### 5. Chạy Backend
```bash
cd backend
npm run dev
```

### 6. Cài đặt Frontend
```bash
cd frontend
npm install
```

### 7. Chạy Frontend
```bash
cd frontend
npm start
```

## 🔍 Sử dụng tài khoản có sẵn sau khi chạy
### Test flow Admin:
Tài khoản / Mật khẩu : `Manager / 111222`

### Test flow Receptionist:
Tài khoản / Mật khẩu : `letan1 / 111222`


### Test flow Trainer:
Tài khoản / Mật khẩu : `vanbhlv / 111222`


### Test flow Customer:
Tài khoản / Mật khẩu : `nguyenvana / 111222`


