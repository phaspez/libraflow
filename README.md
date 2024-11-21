# libraflow - Bài tập lớn CT449

Ứng dụng quản lý thư viện sử dụng MongoDB, Express.js, Vue và Node.js

## Hướng dẫn cài đặt trên máy

### Yêu cầu:

Máy đã cài đặt Node.js, Mongo Compass và database của MongoDB được truy cập tại mongodb://localhost:27017/libraflow

1. Cài đặt tất cả library và package được sử dụng, lần lượt thực hiện lệnh:

```
    npm i
```

trên thư mục `libraflow-fe`, `libraflow-be` và `libraflow-admin`.

2. Tạo tệp tin `.env` lần lượt trên các thư mục với nội dung sau:

```
    JWT_SECRET=*********
```

Với `\libraflow-be\.env`

```
BACKEND_URL=************
VUE_APP_BACKEND_URL=************
VITE_BACKEND_URL=************
```

Với `\libraflow-fe\.env` và `libraflow-admin\.env`

3. Lần lượt chạy server cục bộ

```
    npm run dev
```

Đối với `\libraflow-fe\` và `libraflow-admin\`

```
    npm start
```

Đối với `\libraflow-be\`

Có thể thay lệnh `npm` bằng `yarn` hoặc `pnpm`
