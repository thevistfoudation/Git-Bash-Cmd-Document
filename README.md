# Git-Bash-Cmd-Document
## Mục Lục
- [I.𝐌Ứ𝐂 ĐỘ 𝐂Ơ 𝐁Ả𝐍](#What)
- [II. 𝐌Ứ𝐂 ĐỘ 𝐓𝐑𝐔𝐍𝐆 𝐁Ì𝐍𝐇](#How)
- [III.𝐌Ứ𝐂 ĐỘ 𝐍Â𝐍𝐆 𝐂𝐀𝐎 ](#When)
<a name="What"></a>
## I.𝐌Ứ𝐂 ĐỘ 𝐂Ơ 𝐁Ả𝐍 
- 𝟏, 𝐠𝐢𝐭 𝐜𝐨𝐧𝐟𝐢𝐠
Git config là câu lệnh mà chúng ta phải thực thi đầu tiên cài đặt git lên máy. Câu lệnh này sẽ giúp các bạn thiết lập tên và email cá nhân của bạn, những thông tin này sẽ đính kèm trong mọi commit của bạn, đều này sẽ rất hữu ích khi chúng ta muốn biết đoạn code nào đó đã được ai triển khai để có thể thảo luận trong trường hợp chúng ta không hiểu rõ đoạn code đấy sử dụng cho mục đích gì.
$ git config --global user.name "Your name"
$ git config --global user.email "Your email"
-  𝟐, 𝐠𝐢𝐭 𝐯𝐞𝐫𝐬𝐢𝐨𝐧
Câu lệnh này dùng để kiểm tra phiên bản git đang sử dụng trên máy.
$ git version
- 𝟑, 𝐠𝐢𝐭 𝐢𝐧𝐢𝐭
Đây là câu lệnh đầu tiên khi chúng ta bắt đầu một dự án mới, câu lệnh này sẽ giúp chúng ta tạo một repository mới, sau đó nó sẽ được sử dụng để lưu trữ và quản lý mã nguồn trong repository này.
$ git init
// Hoặc bạn có thể đặt tên cho repo với lệnh
$ git init <your repository name>
- 𝟒, 𝐠𝐢𝐭 𝐜𝐥𝐨𝐧𝐞
Câu lệnh này giúp download một repository đã tồn tại sẵn trên khô lưu trữu (github, gitlab v.v) về máy.
git clone <your project URL>
-  𝟓, 𝐠𝐢𝐭 𝐚𝐝𝐝
Git add là câu lệnh giúp thêm tất cả các file code mới mới hoặc các file code được chỉnh sửa vào repository.
$ git add your_file_name - Thêm một file( thêm mới hoặc chỉnh sửa) vào staging area
$ git add * - Thêm tất cả các file (thêm mới hoặc chỉnh sửa) vào staging area
-  𝟔, 𝐠𝐢𝐭 𝐜𝐨𝐦𝐦𝐢𝐭
Đây là câu lệnh được sử dụng phổ biến nhất, câu lệnh này giúp lưu các thay đổi ở các file trong vùng staging area xuống repository.
Có thể hiểu git add dùng để thêm thêm các file được thay đổi hoặc thêm mới vào vùng staging area, và chúng sẽ sẵn sàng để commit và sau đó những thay đổi này sẽ được lưu xuống repository.
$ git commit -m “your useful commit message”
- 𝟕, 𝐠𝐢𝐭 𝐬𝐭𝐚𝐭𝐮𝐬
Câu lệnh này cho phép bạn xem tình trạng hiện tại của mã nguồn như có bao nhiêu file được thêm mới hoặc chỉnh sửa.  Những file nào đang nằm trong vùng staging area hoặc đang nằm ngoài staging area.
-  𝟖, 𝐠𝐢𝐭 𝐛𝐫𝐚𝐧𝐜𝐡
Trong một Git repository luôn luôn tồn tại nhiều nhánh riêng biệt dùng để triển khai một tính năng nào đó độc lập với các nhánh khác.
Các lệnh branch các bạn có thể sử dụng:
$ git branch
> Dùng để hiển thị tất cả các branch đang có.
$ git branch
> Dùng để tạo một branch mới.
$ git branch -d <branch_name>
> Xoá branch.
- 𝟗, 𝐠𝐢𝐭 𝐜𝐡𝐞𝐜𝐤𝐨𝐮𝐭
Để di chuyển qua lại giữa các branch, chúng ta có thể sử dụng git checkout để đạt được điều này.
git checkout <branch_name>
Ngoài ra các bạn có thể vừa chuyển qua một branch mới và tiện thể khởi tạo nếu chưa tồn tại với câu lệnh.
$ git checkout -b <your_new_branch_name>
<a name="How"></a>
## II.𝐌Ứ𝐂 ĐỘ 𝐓𝐑𝐔𝐍𝐆 𝐁Ì𝐍𝐇

<a name="When"></a>
## III.𝐌Ứ𝐂 ĐỘ 𝐍Â𝐍𝐆 𝐂𝐀𝐎

