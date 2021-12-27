---
marp: true
title: Workshop Ichiba
description: Software Development Process
theme: uncover
paginate: true
_paginate: false
---

<!-- backgroundImage: "linear-gradient(to bottom, #67b8e3, #0288d1)" -->

<style>
   section.h3__left h3 {
  text-align: left;
}

section.p__left p {
   text-align: left
}

section.h5__left h5 {
   text-align: left
}
</style>

# <!--fit--> Software Development Process

Quy trình làm việc dự án phần mềm

<style>a { color: black; }</style>

<!-- This is presenter note. You can write down notes through HTML comment. -->

---

![Marp bg 60%](https://raw.githubusercontent.com/mramra3004/md-presentation/master/assets/kindpng_4730562.png)

---
<!-- _class: h3__left -->
#### <!--fit--> Nội dung được đề cập
   ### 1. Thực trạng của lập trình viên
   ### 2. Quy trình phát triển phần mềm
   ### 3. WFH của lập trình viên

---
<!-- _class: p__left -->

##### <!--fit--> Thực trạng của lập trình viên

- Trước đó code chạy bình thường nhưng sang máy khác thì lại không có chạy được:
  + Do chạy được kiểm thử qua 1, 2 trường hợp.
  + Do cấu hình môi trường chưa đúng.
*=> Thiết đặt môi trường làm việc chưa được thống nhất*
---
##### <!--fit--> Thực trạng của lập trình viên
- Code cho chạy tính năng chính đã, thêm comments sau, hay viết tài liệu sau:
  + Có một sự thật là không mấy lập trình viên mặn mà với việc viết comments hay tài liệu bởi vì khi họ thay đổi code họ lại phải thêm việc đi cập nhật lại các comments và tài liệu liên quan trước đó.
  + Việc chính của họ là code, việc viết tài liệu và comments giải thích tài liệu cho một ai đó thường được coi không phải việc của họ
  *=> Việc người mới tiếp nhận công việc cũ quá khó*
---

##### <!--fit--> Thực trạng của lập trình viên

- Nó không phải trách nhiệm của tôi:
  + Cái này là của anh A viết ra nó!, Đây không phải là lỗi phần chức năng của tôi! Cái này do kiến trúc hạ tầng! Vấn đề này của team khác! Nhưng tự mình hiểu rằng có một phần trách nhiệm của mình.
  + Tuy nhiên, thật sự rằng ai cũng khó lòng chấp nhận được lỗi lầm và cái tôi luôn đẩy lên cao. Cứ đá bóng đi trước đã, tính sau
  *=> Phải giao trách nhiệm và quyền hạn cho mỗi thành viên*
---

##### <!--fit--> Thực trạng của lập trình viên
- Tôi không biết về nghiệp vụ hay chức năng này:
   + Chuyên môn hóa nghiệp vụ mỗi thành viên trong team đúng là làm cho mỗi thành viên trở nên cô lập, họ chỉ nắm nghiệp vụ của riêng họ và hoàn thành việc của họ là đúng.
  *=> Phải có tài liệu về các nghiệp vụ, buổi trao đổi giữa các team để thống nhất nghiệp vụ*
---

##### <!--fit--> Thực trạng của lập trình viên
- Tôi không có khả năng diễn thuyết, thuyết trình, demo:
   + Có một số trường hợp dự án phải thuyết trình cho khách hàng hay demo sản phẩm. Thường BA hay QC sẽ làm việc này vì họ nắm rõ flow và các use case tổng quát hơn lập trình viên thật.
   + Những chức năng mà mình làm ra thì phải hiểu rõ hơn ai hết.
  *=> Trau dồi kỹ năng mềm có các buổi seminar để anh em có thể nâng cao kiến thức*
---

##### <!--fit--> Thực trạng của lập trình viên
-  Sắp xong rồi, cuối ngày hôm nay là xong:
   + Có những vấn đề lập trình viên chưa chắc chắn hay chưa biết cách giải quyết như thế nào, nhưng để an ủi sếp và đồng nghiệp họ hứa lươn rằng, sắp xong rồi anh, cuối ngày có cho chị test
  *=> Nên làm việc có kế hoạch log work từng ngày để mọi người trong team có thể nắm được*
---

##### <!--fit--> Thực trạng của lập trình viên
-  Đây chỉ là giải pháp tạm thời:
   + Hiện tại chưa có giải pháp nào tốt hơn tại thời điểm này. Tôi sẽ cải thiệt optimize, refactor sau. Yên tâm đi, tạm thời vậy đã.
   + Đúng là có những thời điểm không kịp deadline bạn sẽ phải chữa cháy tạm thời, nhưng cố gắng trình bày với sếp để họ biết trước để chuẩn bị kế hoạch và phương án sau này.
  *=> Người đứng đầu nên tạo cảm hứng để anh em có thể bày phương án tốt hơn*
---

##### <!--fit--> Thực trạng của lập trình viên
-  Nó không phải là bug, anh chị làm gì đó sai thôi:
   + Một câu chữa cháy không thể nào hợp lý hơn. Đôi khi tưởng chừng như bạn đúng ở các trường hợp và tiền điều kiện để chạy chức năng đó, nhưng đâu ai cấm người dùng vọc phá và đảo lộn thứ tự các bước đâu.
  *=> Nên viết mô tả task đúng từ câu chuyện của khách hàng*
---

![bg right 60%](https://raw.githubusercontent.com/mramra3004/md-presentation/master/assets/103020.png)
##### <!--fit--> Giải quyết vấn đề
---

<!-- _class: h5__left -->
##### <!--fit--> Quy trình phát triển phần mềm
##### 1. Câu chuyện của khách hàng (Customer Story)
---
##### <!--fit--> Thành phần cơ bản của khi viết tài liệu
- Tổng quan hệ thống (nên vẽ bằng plant uml)
- Cấu trúc các thư mục code, solution code
- Các thuật toán mà phải tuỳ biến theo nghiệp vụ
- Các cấu hình cơ bản (appsettings.json,...)
- Các API, View,... có tác động với nghiệp vụ như thế nào để mọi người dễ sửa chữa, tìm kiếm nhanh.
---
![bg right 60%](https://icongr.am/octicons/mark-github.svg)
##### <!--fit--> Thực hành
---
![bg 40% opacity blur](https://avatars.githubusercontent.com/u/34239991?v=4)

### Created by MRAMRA ([@mramra3004](https://github.com/mramra3004))

https://github.com/mramra3004/md-presentation
