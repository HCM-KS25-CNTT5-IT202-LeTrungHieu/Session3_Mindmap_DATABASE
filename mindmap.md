# SQL Data Manipulation

## Kiến thức

### INSERT

- Thêm dữ liệu mới

### UPDATE

- Cập nhật dữ liệu

### DELETE

- Xóa dữ liệu

### SELECT

- Truy xuất dữ liệu

## Mục tiêu

- Lấp đầy hệ thống
- Duy trì chính xác
- Tối ưu tài nguyên
- Hỗ trợ ra quyết định

## Kiến thức chính

### INSERT

- Constraints
- NOT NULL

### UPDATE

- WHERE
- Cẩn thận update toàn bảng
- Nên SELECT trước

### DELETE

- WHERE
- Foreign Key

### SELECT

- Tránh SELECT \*
- Dùng LIMIT

## Usecase

### Thương mại điện tử

#### INSERT

- Thêm khách hàng
- Nhập hàng

#### UPDATE

- Trạng thái đơn hàng
- Giá sản phẩm

#### SELECT

- Email marketing
- Kiểm tra tồn kho

### Vận hành

#### DELETE

- Xóa dữ liệu rác

#### INSERT INTO SELECT

- Backup dữ liệu
- Migrate dữ liệu

### Quản trị rủi ro

#### Soft Delete

- is_deleted
- Khôi phục dữ liệu
- Giữ lịch sử

## Kết luận

- Công cụ vận hành hệ thống dữ liệu
- UPDATE và DELETE cần cẩn thận
