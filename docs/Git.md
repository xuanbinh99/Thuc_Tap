# **Tìm hiểu về  Git**

![](https://github.com/satthuno999/Git-Github/tree/master/images/logogit.png )

## Mục lục
[1. Lịch sử của Git.](#lichsugit)

[2. Git là gì?](#gitlagi)

[3. Phân biệt **Git** với **Github**.](#phanbietgit)

[4. Công dụng và cách hoạt động của Git.](sdgit)

[5. **Repository** là gì?](#repolagi)

[6. File Readme và vị trí file trong **Repo**?](#filereadme)

---

<a name="lichsugit">

## 1. Lịch sử của Git.

+ Được phát triển bởi **Linus Torvalds** vào năm 2005, ban đầu dành cho việc phát triển nhân **Linux**. Hiện nay, **Git** trở thành một trong các phần mềm quản lý mã nguồn phổ biến nhất. **Git** là phần mềm mã nguồn mở được phân phối theo giấy phép công cộng **GPL2**. 

<a name="gitlagi">

## 2. Git là gì? 
+ **Git** là tên gọi của một **Hệ thống quản lý phiên bản phân tán** (Distributed Version Control System – **DVCS**).
+ **DVCS** là hệ thống giúp mỗi máy tính có thể lưu trữ nhiều phiên bản khác nhau của một mã nguồn được *clone* từ kho chứa nguồn *repository*.

<a name="phanbietgit" >

## 3. Phân biệt **Git** với **Github**.
+ **Git** là tên gọi của một mô hình hệ thống còn **Github** là một dịch vụ máy chủ hoạt động theo mô hình hệ thống Git
+ Mỗi máy tính có thể *clone* mã nguồn từ một *repository* thì **Github** là nơi lưu chữ các kho chứa mã nguồn *repo* kia.

<a name="sdgit">

## 4. Công dụng và cách hoạt động của Git.
+ Mỗi lần ta thay đổi mã nguồn trên máy tính ta có thể ủy thác ( *commit* ) và đẩy lên kho chứa mã nguồn đó, từ máy tính khác ta dễ dàng *clone* những thay đổi mới nhất kia.
+ Ngoài ra ta sẽ dễ dàng khôi phục những thay đổi của mã nguồn mà không cần lưu lại mã nguồn trước khi sửa.

![](https://github.com/satthuno999/Git-Github/tree/master/images/sdgit.png "Work Tree")

+ Trong công việc:
    - Quản lý code và lịch sử thay đổi
    - Làm việc nhóm 
    - Sắp xếp công việc tốt hơn
    - Linh hoạt khi quản lý nhiều task
    - Tự tin hơn khi thử nghiệm ý tưởng mới
+ Hoạt động cơ bản của Git

![](https://github.com/satthuno999/Git-Github/tree/master/images/hdgit.png "Cách hoạt động của Git")

- Giả sử từ *Repository* chính trong **Github** ta có thể làm việc với nhiều máy tính khác nhau khi được ủy quyền.
- Một số Lệnh cơ bản trên Git:

    - `Clone` (bản sao): Tạo bản sao mã nguồn từ **Repo** về máy.

    - `Pull` (kéo): Cập nhật những thay đổi từ **Repo**, những file không thay đổi sẽ không dùng tới.

    - `Push` (đẩy): Khi chỉnh sửa mã nguồn từ máy thực hiện lệnh *push* ta sẽ đẩy những thay đổi đó lên **Repo** trên **Github**.

<a name="repolagi">

## 5. **Repository** là gì?
+ **Repository** (Nhà kho): Là nơi chứa dữ liệu/cơ sở dữ liệu, những thông tin cần thiết để duy trì, quản lý, sửa đổi và các lịch sử của dự án
+ Có 2 loại cấu trúc chính :
    - **Object** store chứa dữ liệu nguyên bản, các file log ghi chép quá trình sửa đổi, tên người tạo file và các thông tin khác
    - **Index** là file nhị phân động và tạm thời miêu tả cấu trúc thư mục của toàn bộ **Repo** và trạng thái của dự án được thể hiện thông qua commit và tree tại một thời điểm nào đó trong lịch sử phát triển, nó không chứa nội dung file mà chỉ dùng để tìm kiếm.

<a name="filereadme">

## 6. File Readme và vị trí file trong **Repo**?
+ File **Readme** là một tệp văn bản chứa các thông tin chủ chốt, nội dung chính của **Reposity** đó.
+ Vị trí của file ở cuối cùng của **Repo** mục đích để khi truy cập vào **Github** file *Readme* sẽ được hiển thị ngay lên màn hình, giúp người xem biết **Repo** này có những nội dung gì và thuận tiện truy cập tìm kiếm.
---