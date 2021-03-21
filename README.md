# TruyTimKhoBauSTEM
* Truy Tìm Kho Báu - STEM Trại Toán-Tin. 26/03/2021.
* Ngôn ngữ: C++, SFML.
* Tác giả: Phạm Nhật Quang.

# Ghi chú
* Code chưa được hoàn thiện, cực rối rắm và dài dòng.
* Hiện tại đang được hoàn thiện tới giai đoạn cuối cùng.

# Cách sử dụng
## File nhập
- File "input.inp" được dùng để nhập 2 giá trị, lần lượt là số chìa khóa và thời gian (giây).
- File "input2.inp" được dùng để nhập 4 xâu giá trị, là cách đi của 4 người chơi tương ứng.

## Cách điều hành
### Giai đoạn 1
- Khi chạy/compile, chương trình sẽ hiện ra màn hình ô cờ đã được sinh ra và thời gian từng người chơi.
- Giả sử người 1 nộp kết quả, ta nhấn "U" để dừng đồng hồ người chơi đó, đồng thời nhập kết quả vào dòng thứ nhất file "input2.inp"
- Tương tự, với người 2 thì nhấn "I", người 3 nhấn "O", người 4 nhấn "P".
- Nút "R" được dùng để dừng hết đồng hồ của tất cả người chơi và chuyển chương trình đến giai đoạn tiếp theo.
- Lưu ý: Chỉ nhấn nút "R" khi đã nhập đầy đủ file "input2.inp", để chuyển giai đoạn của chương trình.

### Giai đoạn 2
- Dần dần, kết quả của từng người sẽ được biểu thị trực quan trên màn hình, các thông số sẽ được biểu thị bên cạnh.
- Sau khi biểu thị xong, chương trình sẽ chờ 10 giây trước khi chuyển sang người tiếp theo.
- Sau khi biểu thị tất cả người chơi, hệ thống chuyển sang giai đoạn 3.

### Giai đoạn 3 (Chưa hoàn thiện)
- Màn hình này sẽ hiện ra kết quả tổng của người chơi dựa trên tiêu chí sắp xếp: _Số chìa khóa > Số nước đi > Thời gian_.
- Nhấn "R" hoặc đóng cửa sổ để kết thúc trò chơi.

# Cách cài đặt
## Cài và link đúng MingW-w64 (bản x86_64, posix-seh, 8.1.0).
## Để compile bằng Code::Blocks:
- Tải SFML (bản SEH): https://www.sfml-dev.org/download/sfml/2.5.1/
- Cài SFML vào Code::Blocks: https://www.youtube.com/watch?v=fcZFaiGFIMA/
- Mở file project "lmao2.cbp".
## Để chạy thẳng:
- Chạy file "/bin/Release/lmao2.exe".
- Cầu mong nó sẽ chạy đúng?

