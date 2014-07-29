Facebook API
================

1- Facebook API là gì? <br/>
• API - Application Programming Interface – tạm dịch là giao diện 
chương trình ứng dụng. API là một phương tiện để giao tiếp giữa các 
chương trình, là xu hướng trong thế giới lập trình. Không chỉ chỉ có 
Facebook API mà Google, Yahoo, Amazon và các công ty lớn khác 
cũng cung cấp các API riêng, với API này bạn có thể tạo ra các ứng 
dụng bằng cách sử dụng tính năng hoặc dữ liệu hiện có trên máy chủ 
của họ. <br/>
• Facebook API là một nền tảng để xây dựng những ứng dụng cho các 
thành viên của mạng xã hội Facebook. API cho phép các ứng dụng sử 
dụng các kết nối xã hội và các thông tin hồ sơ để làm cho các ứng 
dụng liên quan tới nhau nhiều hơn. API cung cấp những lời gọi để lấy 
thông tin về người sử dụng, nhóm người dùng, bạn bè, thông báo, sự 
kiện và nguồn cấp dữ liệu…Cũng có thể dùng lời gọi API để cập nhật 
và lấy thông tin hồ sơ.<br/>
• API sử dụng giao thức RESTful và các hồi đáp được trả lại dưới dạng 
XML. <br/>

2- Cách thức làm việc Facebook API
• API là nền tảng do Facebook cung cấp cho người viết ứng dụng để dễ 
dàng trong việc tạo ứng dụng và đảm bảo người viết ứng dụng không 
can thiệp quá sâu vào hệ thống của Facebook. API cho phép thực thi 
nền tảng thông qua các phương thức được định nghĩa. Thông qua các 
lời gọi API, người tạo ứng dụng có thể lấy thông tin về user, groups, 
photo,… mà họ cần. <br/>
• Facebook gửi phương thức POST tới máy chủ Facebook API. Nó bao 
gồm một số các thông số yêu cầu như api_key của ứng dụng. 
Session_key của người dùng đưa ra yêu cầu. Bên cạnh đó Facebook 
còn thêm vào tham số fb_sig để thông báo ứng dụng đưa ra yêu cầu. 
Bằng cách này tất cả các lời gọi API sẽ được đảm bảo, Facebook có 
thể xác minh các yêu cầu được gửi từ một ứng dụng đã được chấp 
thuận. Thông tin mà Facebook sẽ trả lại là một tài liệu XML.<br/>

3- Graph API và FQL <br/>
• Graph API : là cách đơn giản nhất để đọc hay viết dữ liệu vào Facebook. Graph API có rất nhiều phiên bản đang được sử dung . Có thể coi như 1 tập hàm viết sẵn giúp bạn thao tác với CSDL của facebook như truy vấn dữ liệu , post bài mới lên facebook hay tải hình ảnh lên …..<br/>
• FQL: là viết tắt của Facebook Query Language tạm dịch là ngôn ngữ truy vấn.<br/>
• Ngôn ngữ truy vấn của Facebook (FQL) là một ngôn ngữ dựa trên ngôn ngữ SQL, được các nhà phát triển Facebook tạo ra để 
giúp người viết ứng dụng truy xuất tới các bảng trong cơ sở dữ liệu bao gồm các bảng : user, friend, group, group_member, 
event, event_member, photo, album, and photo_tag… o Các đối tượng FQL được chấp nhận để gọi một câu truy vấn 
FQL thông qua Graph API. FQL cung cấp một số tính năng nâng cao không có sẵn trong Graph API, bao gồm xử lý nhiều 
câu truy vấn trong 1 lời gọi hàm duy nhất. <br/>

