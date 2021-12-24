# TruyTimKhoBauSTEM
* Truy Tìm Kho Báu - STEM Trại Toán-Tin. 26/03/2021.
* Ngôn ngữ: C++, SFML.

# Ghi chú
* Mặc dù chương trình đã xong, tuy nhiên code chưa được hoàn thiện và tinh chỉnh.

# Cách sử dụng
## File
- File "input.inp" được dùng để nhập 3 giá trị, lần lượt là số chìa khóa, số hố và thời gian (giây).
- File "input2.inp" được dùng để nhập 4 xâu giá trị, là cách đi của 4 người chơi tương ứng.
- File "lmao2.exe" là chương trình đã biên dịch, "main.cpp" là mã nguồn của chương trình.
- Các thư mục còn lại là những thư mục tài nguyên, chứa hình ảnh sử dụng trong chương trình.

## Cách điều hành
### Giai đoạn 1
- Khi chạy/compile, chương trình sẽ hiện ra màn hình ô cờ đã được sinh ra và thời gian từng người chơi.
- Giả sử người 1 nộp kết quả, ta nhấn "U" để dừng đồng hồ người chơi đó, đồng thời nhập kết quả vào dòng thứ nhất file "input2.inp"
- Tương tự, với người 2 thì nhấn "I", người 3 nhấn "O", người 4 nhấn "P".
- Nút "R" được dùng để dừng hết đồng hồ của tất cả người chơi và chuyển chương trình đến giai đoạn tiếp theo.
- *Lưu ý*: Chỉ nhấn nút "R" khi đã nhập đầy đủ file "input2.inp", để chuyển giai đoạn của chương trình.

### Giai đoạn 2
- Dần dần, kết quả của từng người sẽ được biểu thị trực quan trên màn hình, các thông số sẽ được biểu thị bên cạnh.
- Sau khi biểu thị xong, chương trình sẽ chờ 10 giây trước khi chuyển sang người tiếp theo.
- Sau khi biểu thị tất cả người chơi, hệ thống chuyển sang giai đoạn 3.

### Giai đoạn 3
- Màn hình này sẽ hiện ra kết quả tổng của người chơi dựa trên tiêu chí sắp xếp: _Số chìa khóa > Số nước đi > Thời gian_.
- Nhấn "R" hoặc đóng cửa sổ để kết thúc trò chơi.

# Cách cài đặt (Phức tạp)
## Bắt buộc
* Ở trang GitHub này, nhấn vào nút "Code" -> Chọn "Download ZIP".
* Giải nén file vừa tải. Chương trình nằm trong thư mục vừa giải nén.
- Chạy file "lmao2.exe".
