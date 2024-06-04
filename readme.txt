Chào mừng bạn đã đến với AI Historian, sau đây sẽ là một số hướng dẫn để bạn có thể tải về và khởi chạy được trang web này

* trong quá trình cài đặt và tải các gói khuyến kích sử dụng trên Command Prompt (CMD) dưới quyền admin

1. Tạo môi trường ảo cho python:
	On Windows, run:
		python -m venv tutorial-env

	-> example:  python -m venv venv

	On MacOS, run:	
		python3 -m venv .env
	
2. khởi chạy Environment:
	On Windows, run:
		tutorial-env\Scripts\activate.bat

	-> example: venv\Scripts\activate.bat

	On Unix or MacOS, run:
		source tutorial-env/bin/activate

   	Nếu gặp lỗi về "Execution Policies", chạy: Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted sẽ cho phép máy có quyền chạy lệnh

3. Nhập các package:
		pip install -r requirements.txt

	Trong quá trình cài đặt của file requirements.txt có thể hơi lâu vì có những thư viện thừa mà tôi chưa thể xác định được
	Nên xin hãy chờ đợi trong ít phút

Nếu bạn tải và cài đặt đến giờ mà chưa gặp vấn đề gì thì xin chúc mừng bạn đặt hoàn thành !

Nếu bạn gặp lỗi về một vài thư viện không thể import được xin hỗ bổ sung nó sau

# --debug: Cập nhật lại ứng dụng mỗi khi có thay đổi
flask --debug run
# Có một số trường hợp sử dụng vscode báo Warning nhưng vẫn có thể khởi chạy chương trình khi gõ lệnh này trên thanh terminal: flask run

4. Đóng gói package:
		pip freeze > requirements.txt

Tham khảo thêm ở: https://docs.python.org/3/tutorial/venv.html
			  và: https://t3h.com.vn/tin-tuc/trien-khai-ung-dung-vi-du-python-flask-bang-heroku


Nếu bạn có thắc mắc hoặc những ý tưởng cải tiến bổ sung gì về trang web,
 gặp vấn đề trong việc tải xuống hoặc khởi chạy web mà chưa chỉnh sửa, xin hãy liên hệ gmail: phamtheants@gmail.com

AI Historian - Xin cảm ơn
