## Ứng dụng hỗ trợ khách hàng mua sắm tại trung tâm thương mại

Trong bối cảnh thị trường bán lẻ ngày càng cạnh tranh, việc cung cấp trải nghiệm mua sắm tiện lợi và hiệu quả cho khách hàng là vô cùng quan trọng. Bài toán này nhằm phát triển một ứng dụng hỗ trợ khách hàng mua sắm tại trung tâm thương mại, giúp họ tìm kiếm thông tin về sản phẩm, khuyến mãi, và địa điểm cửa hàng một cách nhanh chóng. Mục tiêu cuối cùng là nâng cao trải nghiệm khách hàng, tăng cường sự hài lòng và thúc đẩy doanh số bán hàng cho các cửa hàng trong trung tâm thương mại.


## Công nghệ sử dụng

- **Budibase**: Phần mềm tự do nguồn mở ít mã
- **BudibaseDB**: Hệ quản trị cơ sở dữ liệu được xây dựng bởi Budibase dựa trên couchDB


## Các chức năng chính

- Tìm kiếm cửa hàng, sản phẩm
- Gửi form thông báo mất/nhặt đồ
- Kiểm tra sản phẩm giảm giá
- Tủ đồ thông minh

## Cấu trúc thư mục
```text
trung-tam-thuong-mai/
    ├── asserts/
    │   ├── image.png
    │   └── ...
    ├── budibase/
    ├── src/
    │   ├── file.tar.gz
    │   └── ...
    ├── LICENSE
    ├── README.md
    └── setup.sh
```


## Cài đặt sử dụng
### Yêu cầu

Để sử dụng ứng dụng, bạn phải cài đặt:
1. [Docker](https://www.docker.com/)
2. [Docker Compose](https://docs.docker.com/compose/)
3. [Node.js](https://nodejs.org/en/)
4. Cài đặt self-hosted Budibase với NPM
```bash
npm install -g @budibase/cli
budi --version  # Kiểm tra phiên bản của budibase
```

### Xây dựng ứng dụng

1. **Khởi động ứng dụng**
```bash
budi hosting --start
```

2. **Truy cập Budibase** <http://localhost:10000>

3. **Build ứng dụng**<br>

![Build Budibase app](./asserts/build-budibase-app.png)

4. **Import ứng dụng**<br>

Để import ứng dụng, sau khi tạo ứng dụng vào `Settings > Export/Import > Import app` rồi kéo thả file tài nguyên vào, sau đó ấn `Update`<br>

![Import application](./asserts/import-app.png)

### Cách cài đặt khác 
1. **Clone project về máy**
```bash
git clone https://github.com/CayDen-AI/trung-tam-thuong-mai.git
```

2. **Cài đặt và khởi chạy**
```bash
sh setup.sh
```

## Tài liệu người dùng

Tài liệu dành cho người sử dụng ứng dụng [Document](./docs/Tài%20liệu%20người%20dùng.odt)

## Liên hệ

- Nguyễn Hải Đăng: 22a1001d0049@students.hou.edu.vn<br>
- Lê Hoàng Phúc: 22a1001d0254@students.hou.edu.vn<br>
- Nguyễn Trần Duy Anh: 24a1001d025@students.hou.edu.vn


## Giấy phép

This project is licensed under the terms of the [Apache 2.0](./LICENSE) license.


## Contributors

- Nguyễn Hải Đăng: [@CayDen_AI](https://github.com/CayDen-AI)
- Lê Hoàng Phúc: [@phucnt2004](https://github.com/phucnt2004)
- Nguyễn Trần Duy Anh: [@Duyanha37](https://github.com/Duyanha37)