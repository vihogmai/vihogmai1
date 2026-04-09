
# vihogmai1
Download và cài đặt SQL Server 2025, phiên bản Developer

Link tải: https://www.microsoft.com/vi-vn/sql-server/sql-server-downloads

Chọn phiên bản SQL Server 2025 Developer

Không chọn Azure (nặng, ko dùng đến), các tính năng mở rộng khác (feature) chọn tất cả

Cài đặt với 2 kiểu login (Mixed Mode): Windows Authentication (nhớ Add Current User) và SQL Server Authentication (username mặc định là sa, chỉ cần nhập mật khẩu 123 , nhớ nhập 2 chỗ: Enter password và Confirm password)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/76b5ed7f-595d-48cf-9b87-052bc4e783aa" />

Cấu hình cho SQL Server làm việc ở cổng động (Dynamic Port), TCP: enable+active yes cho 127.0.0.1, chọn cổng động là 3xxxx với xxxx là 4 số cuối của mã số sv, (nếu cổng này đã mở sẵn trước đó bởi 1 ứng dụng khác thì chọn cổng là 4xxxx hoặc 5xxxx)
Kiểm tra xem service SQL Server có đang running và mở đúng cổng đã chọn hay không?

Sử dụng lệnh trên cmd: netstat -ano | findstr LISTENING để liệt kê các cổng mà máy tính đang mở,

Nếu thấy dòng: TCP 0.0.0.0:xxxxx với xxxxx là cổng đã chọn ở bước 2 là OK

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/4806597e-5a0d-46b5-b97d-881e1ffcab8f" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/339572b4-967c-42b2-99f6-ec363f6abad0" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e96e1b03-acc8-4b55-a643-c0623a5ee1c5" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/61fe00c9-8526-49d7-bfa1-613726a7b197" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/68acce8c-425b-410e-8af9-94ca158d6142" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0ecda88b-f28b-45e2-8948-730d7da508d3" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6907b498-d377-453b-a0f6-f801d1db7d07" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/55dcb758-7e79-47fe-aed0-ca056945ccff" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/62022017-01be-4fff-babf-a701542b6352" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/66efed89-dbed-449d-b7b5-a8fd837a4655" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ba2e2864-6732-4ddc-abec-9f016f55dde9" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0ae03bc0-4986-4db1-8ecf-fbd04f41aeb8" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1ac00869-76a8-479b-9bea-2de1266c9c4a" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/796dae61-ce32-472b-a46d-e4fde7cc50ff" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/73ad7f1f-be2d-4a02-a46c-cf9303648d72" />



