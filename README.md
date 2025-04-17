# K58_KMT
đề 12 : quản lý đồ án sinh viên(dành cho giảng viên hướng dẫn)  : mssv K225480106032 - Nguyễn trung Kiên - Đồ án phân tích thiết kế hệ thống 
# yêu cầu 
tuần 1: 
lập dàn ý cho đồ án : quản lý quá trình làm đồ án của các sinh viên 
dàn ý đồ án của em gồm 6 chương:

MỤC LỤC	

LỜI CAM ĐOAN	

DANH MỤC	

CÁC TỪ VIẾT TẮT	

DANH MỤC CÁC BẢNG VÀ HÌNH VẼ, ĐỒ THỊ	

LỜI NÓI ĐẦU	9

CHƯƠNG 1. KHẢO SÁT HỆ THỐNG

1.1. Thực trạng của hệ thống	

1.1.1. Giới thiệu chung về trường đại học kĩ thuật công nghiệp

1.1.2 Sơ đồ tổ chức quản lý đồ án	

1.1.3 Hoạt động của hệ thống hiện tại	

1.2. yêu cầu của hệ thống mới	

1.2.1 Những vấn đề cần tháo gỡ trong quản lý đồ án

1.2.2 Tin học hóa trong công tác quản lý

1.2.3 Yêu cầu phát sinh hệ thống mới	

CHƯƠNG 2. PHÂN TÍCH HỆ THỐNG	

2.1. Phân tích thông tin vào ra của hệ thống	

2.1.1 Thông tin vào hệ thống thông tin	

2.1.2 Thông tin ra của hệ thống thông tin	

Hệ thống xử lý thông tin	

2.2.	Phân tích hệ thống	

2.2.1.	Biểu đồ usecase

2.2.2.	Biểu đồ lớp	

2.2.3.	Biểu đồ trạng thái	

2.2.4.	Biểu đồ hoạt động

CHƯƠNG 3. THIẾT KẾ HỆ THỐNG	

3.1. Thiết kế cơ sở dữ liệu

3.1.2. Mô tả chi tiết cơ sở dữ liệu	

3.1.3. Sơ đồ thực thể liên kết	

3.2. Thiết kế hệ thống phần mềm

CHƯƠNG 4. CÀI ĐẶT CHƯƠNG TRÌNH	

4.1. Giới thiệu chung về ngôn ngữ sql sever

4.2. Kiểm thử chương trình	

CHƯƠNG 5. NHẬN XÉT VÀ ĐÁNH GIÁ VỀ HỆ THỐNG

5.1. Những kết quả đã đạt được	

5.2. Hướng phát triển của đề tài
KẾT LUẬN	

TÀI LIỆU THAM KHẢO	


## TUẦN 2 ĐƯA RA DANH SÁCH CÁC BẢNG DỮ LIỆU + CÁC TRƯỜNG VỚI KIỂU DỮ LIỆU PHÙ HỢP, PK, FK, CK HỢP LÝ => DEADLINE: 23H59 11.4.2024

BẢNG SINH VIÊN 
MSSV LÀ KHÓA CHÍNH (PK)
![image](https://github.com/user-attachments/assets/54611e78-7bc2-40bf-8db7-43dde48433cd)

BẢNG GIẢNG VIÊN 
MÃ GIẢNG VIÊN LÀ KHÓA CHÍNH (PK)
![image](https://github.com/user-attachments/assets/3ec778ab-6788-4f50-9a05-158d7faed67e)

BẢNG QUẢN TRỊ VIÊN 
MÃ QUẢN TRỊ VIÊN LÀ KHÓA CHÍNH 
![image](https://github.com/user-attachments/assets/900ca8fc-4345-4fdf-b63a-867269271b6e)

BẢNG ĐỀ TÀI 
MÃ ĐỀ TÀI LÀ KHÓA CHÍNH 
KHÓA NGOẠI : MSSV===> SINH VIÊN(MSSV)   MÃ GV===>GIẢNG VIÊN(MÃ GV)
![image](https://github.com/user-attachments/assets/4920b397-7a6d-461e-ba61-4806663a8167)

BẢNG PHẢN HỒI 
MÃ PHẢN HỒI LÀ KHÓA CHÍNH 
KHÓA PHỤ: MA_BAO-CAO===> NOPBAOCAO(MA_BAO_CAO)  MA_GV===>GIANGVIEN(MA_GV)
![image](https://github.com/user-attachments/assets/0085c528-3c5e-4709-b062-612a70778850)

BẢNG NỘP BÁO CÁO 
MÃ BÁO CÁO LÀ KHÓA CHÍNH 
KHÓA NGOẠI: MA_DE_TAI===>DETAI(MA_DE_TAI)
![image](https://github.com/user-attachments/assets/1b656152-c918-4ae7-9ef1-d50436259098)

BẢNG CHẤM ĐIỂM 
MA_CHAM_DIEM LÀ KHÓA CHÍNH 
KHÓA PHỤ: MA_BAO-CAO===> NOPBAOCAO(MA_BAO_CAO)
![image](https://github.com/user-attachments/assets/54d6ff5f-bcba-4f16-a479-97156cd2577d)

BẢNG MỐC THỜI GIAN
MA_MOC LÀ KHÓA CHÍNH 
KHÔNG CÓ KHÓA NGOẠI 
![image](https://github.com/user-attachments/assets/7ea908dd-d55c-4771-a921-59159aed304a)

BẢNG BÁO CÁO THỐNG KÊ
MA_BAO_CAO LÀ KHÓA CHÍNH 
KHÔNG CÓ KHÓA NGOẠI 
![image](https://github.com/user-attachments/assets/48079afb-940d-4bdc-bc97-a60ba26870e1)


KHÓA RÀNG BUỘC 

BẢNG ĐỀ TÀI
KHÓA RÀNG BUỘC TRẠNG THÁI 
![image](https://github.com/user-attachments/assets/713f641b-613f-4aa4-a0b9-5ae2f7196e24)

BẢNG CHẤM ĐIỂM
KHÓA RÀNG BUỘC ĐIỂM
![image](https://github.com/user-attachments/assets/631a54de-c585-4b60-b6bc-f2d75973d05b)

## TUẦN 3:  VỚI MỖI CHỨC NĂNG CỦA HỆ THỐNG => ĐƯA RA CÁC SQL PHÙ HỢP ĐỂ CÓ DỮ LIỆU (ĐỦ DỮ LIỆU CHO APP GIẢ TƯỞNG XỬ LÝ ĐƯỢC) => DEADLINE: 23H59 18.4.2024

BẢNG DIAGRAM 
![image](https://github.com/user-attachments/assets/29b21369-ca1c-4ec1-be33-ce08ebf81bec)

NHẬP THÔNG TIN QUẢN TRỊ VIÊN
![image](https://github.com/user-attachments/assets/c2600a13-6cf9-4d75-9b78-5695d6e8e97f)

NHẬP THÔNG TIN GIẢNG VIÊN 
![image](https://github.com/user-attachments/assets/3a345a08-4904-4432-bc95-e1b192271401)

NHẬP THÔNG TIN SINH VIÊN
![image](https://github.com/user-attachments/assets/f0eaf3fb-2943-4198-b651-267483508fc8)

NHẬP THÔNG TIN ĐỀ TÀI 
![image](https://github.com/user-attachments/assets/dd5352aa-bfac-4381-98dc-e23131b55ebb)

NHẬP THÔNG TIN MỐC THỜI GIAN 
![image](https://github.com/user-attachments/assets/052e0ab4-0f8d-478b-9cad-b7625b36810c)

NHẬP THÔNG TIN BÁO CÁO 
![image](https://github.com/user-attachments/assets/9f98c1b6-025f-4df9-bfbd-7ff702a71f83)

NHẬP THÔNG TIN ĐIỂM
![image](https://github.com/user-attachments/assets/0176edb6-b411-4585-ae32-15b0fd133045)

NHẬP THÔNG TIN THỐNG KÊ
![image](https://github.com/user-attachments/assets/512bb43a-3c0e-4270-bd04-fbb074635356)

NHẬP THÔNG TIN PHẢN HỒI
![image](https://github.com/user-attachments/assets/5b96b004-c8e0-4316-bc2b-7fb182c6191d)

SHOW THÔNG TIN
BÁO CÁO 
![image](https://github.com/user-attachments/assets/44cfc300-1715-47bd-9f77-64990c4ab964)

đề tài 
![image](https://github.com/user-attachments/assets/079a8942-1e31-43b7-a047-00ed571f76cc)

điểm
![image](https://github.com/user-attachments/assets/d3c82e60-278c-4e22-9309-24fd8cfdf4f3)

giảng viên 
![image](https://github.com/user-attachments/assets/ced3d266-0074-4ba5-8c84-bf658f4b9b42)

phản hồi 
![image](https://github.com/user-attachments/assets/cec8f325-e76b-4cfd-91eb-7a5fd2c1ede7)

admin
![image](https://github.com/user-attachments/assets/f5256fb5-8837-487a-bf03-2382b296ffd0)

sinh viên 
![image](https://github.com/user-attachments/assets/d09c0a54-5f94-4b1b-8746-91c617aaf9c4)

thời gian
![image](https://github.com/user-attachments/assets/54ca061f-9abc-479c-a3fc-9c0ae055ba35)

thống kê
![image](https://github.com/user-attachments/assets/d109fbcb-17f2-47b0-841c-1539695faf11)





















    



