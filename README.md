# TruyTimKhoBauSTEM
* Truy Tìm Kho Báu - STEM Trại Toán-Tin. 26/03/2021.
* Ngôn ngữ: C++, SFML.

# Ghi chú
* Mặc dù chương trình đã xong, tuy nhiên code chưa được hoàn thiện và tinh chỉnh.

# Cách sử dụng
## File nhập
- File "input.inp" được dùng để nhập 3 giá trị, lần lượt là số chìa khóa, số hố và thời gian (giây).
- File "input2.inp" được dùng để nhập 4 xâu giá trị, là cách đi của 4 người chơi tương ứng.

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
* Cài [MingW-w64](https://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win32/Personal%20Builds/mingw-builds/installer/mingw-w64-install.exe/download) (GNU G++, bản x86_64, posix-seh, 8.1.0).
* Thực hiện chạy file "mingw-w64.bat" ở thư mục cài đặt (ví dụ: C:\Program Files\mingw-w64\x86_64-8.1.0-posix-seh-rt_v6-rev0).

## Để compile bằng Code::Blocks:
- Mở file project "lmao2.cbp".
- Tải SFML (bản SEH): [Link tải SFML](https://www.sfml-dev.org/files/SFML-2.5.1-windows-gcc-7.3.0-mingw-64-bit.zip)
- Cài SFML vào Code::Blocks: [Video hướng dẫn](https://www.youtube.com/watch?v=fcZFaiGFIMA/)
- *Lưu ý*: Chỉnh sửa đường dẫn Compiler, Linker lại cho đúng với máy.

## Để chạy thẳng (Chưa thử):
- Chạy file "lmao2.exe".
