I. GIỚI THIỆU ĐỒ ÁN
● Tên đồ án: Remote PC
● Chức năng: Giám sát từ xa và kiểm soát máy tính khác trong một mạng máy tính:
  1. Thao tác màn hình máy tính
  2. Chụp ảnh màn hình
  3. Duyệt thư mục và tập tin máy tính để gửi/nhận files. ● Môi trường phát triển và công nghệ sử dụng: Phần mềm viết bằng bất kỳ ngônngữ, giao tiếp giữa các máy qua socket thuần của ngôn ngữ lập trình mà bạn chọnvàđượcsử dụng các thư viện hỗ trợ khác để thực hiện các chức năng (không phải cho socket)
II. NỘI DUNG
Kết nối
  ● Server sẽ mở một socket để lắng nghe kết nối
  ● Bên Client, người dùng sẽ nhập địa chỉ IP của Server muốn kết nối. Sau đó, Client sẽtạo một socket để gửi yêu cầu kết nối đến Server. Server sẽ chấp nhận kết nối vàdùngmột socket khác để kết nối với Client.
  ● Sau khi kết nối thành công, Client sẽ thực hiện được các yêu cầu đến Server, baogồm:
    1. Xem màn hình và thao tác được trên đó (giống như bạn remote máy khi dùngphầnmềm Teamview hay UltraViewer) •Chuột •Bàn phím
    2. Chụp ảnh màn hình
    3. Duyệt thư mục và tập tinh máy tính để gửi nhận files như phần File của Teamview

**Video demo:https://youtu.be/NjAx0-MgccA?si=nvXJ5bVx5fuUZ3ZJ
