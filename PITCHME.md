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

![bg right 80%](https://raw.githubusercontent.com/mramra3004/md-presentation/master/assets/103020.png)
##### <!--fit--> Giải quyết vấn đề
---

<!-- _class: h5__left -->
##### <!--fit--> Quy trình phát triển phần mềm
##### 1. Câu chuyện của khách hàng (User Stories)
##### 2. Xây dựng các tính năng từ User Stories
##### 3. Xây dựng sprint
##### 4. Xây dựng task
##### 5. Xây dựng quy tắc của một sprint
---

##### <!--fit--> Câu chuyện của khách hàng (User Stories)
-  User stories là những mô tả ngắn gọn, đơn giản về một feature và được kể từ cách nhìn của nhóm người dùng (user hoặc customer của phần mềm) muốn có feature đó. Một cách điển hình user stories có dạng:
  ```
  Với tư cách là một người thuộc < nhóm user >, tôi muốn < mục tiêu >
  vì < lý do >
  ```
---

##### <!--fit--> Câu chuyện của khách hàng (User Stories)
- Ví dụ về user Stories
  + Một ích lợi của user stories là chúng có thể được viết ra theo những mức độ chi tiết khác nhau. Người ta thậm chí có thể viết chỉ một user story chứa đựng cả một lượng lớn các chức năng. Kiểu user story này được gọi là Epic. Chẳng hạn đây là một ví dụ về epic của một phần mềm để xác thực người dùng:
  ```
  Với tư cách một người dùng, tôi có thể đăng nhập vào hệ thống với quyền
  hạn là admin
  ```
---


##### <!--fit--> Câu chuyện của khách hàng (User Stories)
- Cách thêm chi tiết vào một User story
  + Bằng cách chia nhỏ thành nhiều user story con.
  + Bằng cách thêm các điều kiện cần thỏa mãn.
---

##### <!--fit--> Câu chuyện của khách hàng (User Stories)
- Ví dụ về chi tiết về 1 User Stories
  + *Với tư cách là 1 admin, tôi muốn chọn ra 1 nhóm khách hàng với số lượng mua hàng nhiều nhất trên các sàn thương mại*
  +  Chi tiết được thêm vào user story nói trên nếu chỉ rõ điều kiện cần thỏa mãn là: "Nhóm khách hàng mua hàng của của sàn Yahoo Auction, Mercari, Rakuten"
---

##### <!--fit--> Câu chuyện của khách hàng (User Stories)
- Ai viết user stories:
  + Bất kì ai cũng có thể viết được User Stories, nhưng Product Owner sẽ là người đảm bảo phải có tồn tại một Product backlog gồm các user stories.
---

##### <!--fit--> Xây dựng các tính năng từ User Stories
- Từ các User Stories nên có một buổi các team họp với nhau để xây dựng các tính năng thích hợp
- Thống nhất các tính năng để đảm bảo phục vụ hết User Stories
---


# Xây dựng sprint
- Scrum Master: Scrum Master là người bắt buộc phải tham dự buổi Sprint Planning để đưa ra mục tiêu và kế hoạch để hoàn thành các nhiệm vụ có trong Sprint..
- Product Owner: Product Owner bắt buộc phải tham gia để trả lời câu hỏi *"Chúng ta sẽ làm gì?"* và phải đảm bảo sẵn sàng trả lời các thắc mắc của team IT cũng như các team vận hành khác.
---

### Xây dựng sprint
- Product Owner trình bày cho team IT và team vận hàng hiểu rõ tất cả các hạng mục Product Backlog có khả năng được đưa vào sản xuất trong Sprint này. Vì việc làm mịn các user stories cho nên Product Owner trả lời các thắc mắc của các team trong quá trình phát triển
- Project manager cần lựa chọn các hạng mục trong Product Backlog để phát triền ở sprint này. Số lượng hạng mục được chọn tuỳ thuộc vào nguồn lực mà các team có hoặc có thể dựa vào năng suất làm việc trong quá khứ để ước lượng.
---


### Xây dựng sprint
- Sau khi đã phân tách các hạng mục từ  Product Backlog thành các công việc cụ thể thì sẽ có sprint backlog.
- Sau khi phân tích chi tiết, PM cần điều chỉnh một số hạng mục Product Backlog đã chọn có thể trao đổi với Product Owner để lựa chọn
- Sau khi hoàn thành được sprint backlog thì các team có thể bắt tay ngay vào việc triển khai công việc.
---

### Xây dựng task
- Sau khi đã có từng hạng mục công việc thì developer sẽ là người viết mô tả chi tiết cho các task của mình (vì họ là người thực hiện nên họ sẽ là người viết mô tả cho task)
- Khi hoàn thành mô tả của 1 task thì tester sẽ vào viết các test case trong quá trình phát triển của developer, để khi developer hoàn thành xong công việc thì tester sẽ dựa vào các tester case để test.
---

### Xây dựng task
- Sau khi kết thúc quá trình phát triển thì sẽ có một buổi nghiệm thu task vào cuối sprint
  các team sẽ ngồi lại với nhau để nghiệm thu sau đó PO và PM là những người nghiệm thu sản phẩm và họ sẽ kéo Done task để kết thúc sprint.
- Một sprint được coi là không cháy chi khi hoàn thành được **80% - 95%** task
---

##### <!--fit--> Xây dựng quy quy tắc của một sprint
- Ở mỗi đầu dự án các team nên ngồi lại với nhau để có thể có 1 quy tắc làm việc trong sprint
- Log work ở mỗi ngày cuối làm việc để mỗi ngày PM, PO có thể thấy được quá trình phát triển hàng ngày.
- Mỗi ngày sẽ có một buổi daily meeting để mọi người trong team nắm được tính hình hiện tại công việc và giải quyết các vấn đề còn tồn đọng chưa giải quyết ở ngày hôm trước
  ...
---

##### <!--fit--> WFH của lập trình viên
- Lợi ích của việc WFH:
  + WFH là nhân viên có thể cân bằng chất lượng cuộc sống cũng như công việc một cách dễ dàng hơn. Làm việc trong một không gian thân thuộc và yên tĩnh giúp ta tăng độ tập trung lên đáng kể, thúc đẩy sự sáng tạo và tốc độ hoàn thành công việc. Từ đó, ta có thêm thời gian cho những thói quen và sở thích cá nhân.
---

##### <!--fit--> WFH của lập trình viên
- Lợi ích của việc WFH:
  + WFH sẽ phần nào giúp mỗi người có thể bảo vệ sức khoẻ cho bản thân và gia đình. Vào những ngày thời tiết xấu hay chất lượng môi trường thấp thì chắc chẳng ai muốn đi lại ngoài đường cả. Đặc biệt trong thời kỳ dịch bệnh covid như bây giờ thì đúng là việc bảo vệ sức khỏe của bản thân và gia đình là quan trọng nhất.
---


##### <!--fit--> WFH của lập trình viên
- Lợi ích của việc WFH:
  + WFH giúp nhân viên khi ở nhà có thể tiết kiệm thời gian đi lại, có quyền lựa chọn khung giờ làm việc linh hoạt. Làm việc ở nhà miễn sao công việc được hoàn thành theo yêu cầu và đạt chất lượng cao nhất thì các công ty cũng có thể tiết kiệm được các chi phí liên quan đến cơ sở vật chất khi có những nhân viên làm việc tại văn phòng.
---



##### <!--fit--> WFH của lập trình viên
- Mặt trái của việc WFH:
  + Nếu người quản lý không có quy định rõ ràng về WFH, họ sẽ dễ mất quyền kiểm soát. Làm sao để biết được nhân viên đã cố gắng hết sức nhưng vẫn không đạt kết quả tốt, hay người ta chỉ làm việc qua loa cho xong deadline? Nói thì nói vậy thôi chứ đối với lập trình viên nếu chạy theo mô hình agile thì tiến độ cũng được theo dõi phần nào, anh em chỉ cần quan tâm đến task và deadline sau đó thôi, cũng nhẹ nhàng hơn cho người quản lý.
---

##### <!--fit--> WFH của lập trình viên
- Mặt trái của việc WFH:
  +  Việc giao tiếp giữa nhân viên với lãnh đạo, đồng nghiệp cũng dễ trở nên kém hiệu quả. Dù có bao nhiêu công cụ hỗ trợ thì việc họp trực tuyến vẫn khó đạt hiệu quả như khi thảo luận face-to-face. Chưa kể, chuyện internet yếu, nhiều tạp âm cũng khiến ta mất kha khá thời gian điều chỉnh. Lâu dần, sự giao tiếp sẽ trở nên kém hiệu quả, các cá nhân dần tách biệt và mất đi tiếng nói chung trong công việc.
---


##### <!--fit--> WFH của lập trình viên
- Các để WFH hiệu quả hơn:
  + Daily stand-up time: cái này chắc anh em làm agile hiểu rõ, sáng nào cũng meeting report nhiều cũng thành quen, nhưng trước khi meeting nên check lại những thứ đã đang và sẽ làm cùng với những issue nên mình thường bắt đầu làm việc trước lúc meeting sáng khoảng 30-40 phút.
---

##### <!--fit--> WFH của lập trình viên
- Các để WFH hiệu quả hơn:
  + Dev update proccess: đến 5h30 chiều, ngồi lại một lần nữa để cập nhật cho team về quá trình làm việc cùng những vấn đề gặp phải trong ngày. Từ đó, không chỉ leader nắm bắt được quá trình làm việc của mỗi thành viên mà team cũng có thể giúp nhau giải quyết những khó khăn ngay lập tức.
---


### Created by MRAMRA ([@mramra3004](https://github.com/mramra3004))

https://github.com/mramra3004/md-presentation
