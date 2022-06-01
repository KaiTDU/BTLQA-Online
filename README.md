# BTLQA-Online
## Đề tài Hệ thống hỏi đáp online 
*Mô hình sử dụng Web service (Backend: SpringBoot, Frontend: Vuejs) <br>
*Các tool, framework,ngôn ngữ, lib sử dụng (Docker, mysql, springboot, vuejs, java, javascript, css, bootstrap4, npm)

### Mô tả hệ thống hoạt động trên Vscode:
- Sau khi gitclone phần BE (https://github.com/KaiTDU/QA-be): git clone https://github.com/KaiTDU/QA-be  <br>
  +) Khởi tạo database theo file application.properties và chạy mysql <br>
  +) Cài đặt một số lib: mvn install <br>
  +) Chạy: mvn spring-boot:run <br>
  +) Test API: Postman <br>
- Sau khi gitclone phần FE (https://github.com/KaiTDU/QA-fe): git clone https://github.com/KaiTDU/QA-fe <br>
  +) Cài đặt: npm install <br>
  +) Chạy: npm run dev <br>

#### Công việc thành viên trong nhóm thực hiện:
Lê Đại Thắng - B19DCCN657 (nhóm trưởng) <br>
Đào Ngọc Huy - B19DCCN305 <br>
Database: thiết kế và phân tích đề tài (mysql + docker): (Thắng) <br>
Backend: <br>
   -Khởi tạo structure + Authentication, Authorziration (JWT) : (Thắng) <br>
	 -Blog: +) Model: (Huy) <br>
	 	      +) Controller: Lấy danh sách blog, tạo, sửa, xóa (Thắng) <br>
	 -Answer:  +) Model:  (Huy) <br>
	 	         +) Controller: Lấy danh sách answer, tạo, sửa, xóa (Thắng) <br>
	 -Admin:+) Model: (Thắng) <br> 
          +) Controller: Lấy danh sách user, question và thống kê (Thắng) <br>
  
Frontend: - Khởi tạo structure: (Thắng)
	  - Route: +) Login : (Huy) <br>
	           +) Register: (Huy) <br>
	           +) Dashbroad: (Thắng) <br>
	           +) Admin: (Thắng) <br>
