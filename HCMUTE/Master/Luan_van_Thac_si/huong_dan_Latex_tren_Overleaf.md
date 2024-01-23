Hướng dẫn viết thesis dùng latex online với Overleaf
B1: tạo tài khoản overleaf
	- Truy cập link: https://www.overleaf.com/login 
	- chọn Log in through your institution
	- Sinh viên tạo tài khoản bằng địa chỉ email trường 
	- Trường hợp khác: tạo tài khoản với email của google.
	- Đăng nhập thành công vào overleaf
	- Chú ý email kích hoạt (xác minh) tài khoản được gửi vào địa chỉ email đã đăng ký.
B2: tại trang overleaf
	- menu bên trái dùng quản lý các project (project có thể là paper, book, hoặc thesis)
	- chọn All Projects để xem các project đã và đang tham gia
	- chọn New Project > 1 manu mới hiện ra cho phép tạo mới project
		- Từ mẫu latex có sẵn (example project)
		- Mẫu từ github (Import from Github)
		- Mẫu mới hoàn toàn (Blank Project)
		- Mẫu có sẵn của Overleaf
		Trong trường hợp này, chọn Upload Projects (up project từ ổ đĩa máy tính)
	- Chọn hoặc kéo thả file hcmute_thesis.zip chứa mẫu viết luận văn trường hcmute. 
B3: giao diện sẽ có 3 phần:
	- Phần 1 (bên trái) là menu hiển thị danh sách các file đi kèm
	- Phần 2 (bên phải) là nội dung thesis trình bày sau khi biên dịch và hiển thị
	- Phần 3 (giữa) nội dung viết trên latex.
	thesis.tex - file latex chính, bao gồm trang bìa, lời cảm ơn, lời cam đoan, ... chapter1 (nội dung chương 1), chapter 2 (nội dung chương 2)...
	chapter1.tex - file latex chứa nội dung chương 1
	chapter2.tex - file latex chứa nội dung chương 2
	<< có thể tạo thêm các file .tex cho nội dung các chương >> bằng cách thực hiện như sau
		- tạo file mới .tex tên là chapter3 bên menu bên trái
		- trong file thesis.tex, phần nội dung, thêm chương 3 bằng dòng code \input{chapter3.tex} bên dưới \input{chapter2.tex}
	- tìm file refs.bib để thêm vào các tài liệu tham khảo 