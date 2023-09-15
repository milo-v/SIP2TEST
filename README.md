# SIP2TEST

SIP2TEST là server xử lý dữ liệu đầu ra/ vào từ thiết bị sử dụng giao thức SIP2 ([Docs](https://developers.exlibrisgroup.com/wp-content/uploads/2020/01/3M-Standard-Interchange-Protocol-Version-2.00.pdf)). 

Thiết bị được giả lập qua công cụ [SIP Testing Tool](https://clcohio.org/sip-testing-tool/)


## Installation

1. Clone repo.

```bash
git clone https://github.com/nna2k2/SIP2TEST.git
```

2. Cài đặt docker. Build image và chạy container.
```bash
docker-compose up -d
```

3. Cài đặt [SIP Testing Tool](https://clcohio.org/sip-testing-tool/)


## Usage

1. Sau khi chạy container, truy cập http://localhost:8080.

2. Nhập IP và port sau đó nhấn Start để chạy Server.

3. Vào SIP Testing Tool, nhập IP và port tương ứng sau đó nhấn Connect. 

4. Sau khi kết nối thành công với thiết bị SIP Testing Tool, tuỳ chọn các chức năng và thông báo sẽ được hiển thị ở phần Logs bên server. 

5. Để tắt server nhấn Stop.



