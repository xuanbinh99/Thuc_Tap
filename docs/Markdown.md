# **Tìm hiểu về ngôn ngữ Markdown**

## Mục lục

[1.Markdown là gì](#khainiem)

[2.Lợi ích của Markdown](#loiich)

[3.Cách viết ngôn ngữ Markdown](#hdvietmd)


---

<a name="khainiem">

##  1. Markdown là gì?</a>
* **Markdown** là ngôn ngữ đánh dấu văn bản được tạo ra bởi *John Gruber* năm 2004. 
* Tệp tin có đuôi là .md
* **Markdown** sử dụng cú pháp khá đơn giản và dễ hiểu để đánh dấu văn bản và văn bản được viết bằng Markdown sẽ có thể được chuyển đổi sang *HTML*. Ngược lại các văn bản được viết bằng *HTML* cũng có thể được chuyển đổi sang Markdown.

<a name="loiich">

## 2. Lợi ích của ngôn ngữ Markdown.</a>
* Không cần giỏi lập trình
* Dễ dàng chuyển đổi giữa HTML với Markdown
* Là các plugin cho một số hệ thống quản lý nộ dung như Github, reddit, SourceForge

<a name="hdvietmd">

## 3. Cách viết ngôn ngữ Markdown </a>
###  **Những cách viết tiêu đề:**

``` 
# H1
## H2
### H3
```
sẽ hiển thị là:
># H1
>## H2
>### H3

ví dụ khác để viết tiêu đề:
 ```
Tiêu đề 1
=========
 Thêu đề 2
---------
```
 kết quả hiển thị:

>Tiêu đề 1
>=========
>Tiêu đề 2
>---------

### **Cách nhấn mạnh, đánh dấu , inline code**

+ Để in nghiêng ta dùng ` *từ cần in nghiêng* ` ta sẽ được *từ cần in nghiêng*.
+ In đậm ta dùng `**từ cần in đậm**` ta được **từ cần in đậm**.
+ Để thêm nhấn mạnh ta có thể gạch ngang chữ bằng cách `~Từ gạch~` sẽ được~~Từ gạch~~.
+ Để viết `inline code` ta dùng cú pháp  
```
`inline code`
```
+ Để highlight block code, bạn viết:
```
    ```php

    echo ("highlight code");

    ```
```
ta sẽ được kết quả:
```php

echo ("highlight code");

```

+ Tạo một trích dẫn ta dùng ký tự >

    ví dụ: >Nội dung văn bản

    ta được

    >Nội dung văn bản

### **Cách viết một bảng**

```
| dòng | cột 1 | cột 2 | Cột 3 |
| ----- |-----|------|-----|
|dòng 1 | 1 | 2 | 3 |
|Dòng 2 | 4 | 5 | 6 |
```

ta sẽ được bảng :

| dòng | cột 1 | cột 2 | Cột 3 |
| ----- |-----|------|-----|
|dòng 1 | 1 | 2 | 3 |
|Dòng 2 | 4 | 5 | 6 |

### **Chèn link và ảnh**

* **Chèn link**
    +   ``` 
        [Link FACEBOOK](http://fb.com/xuanbinh.vu.6464)
        ```
        ta được:

        [Link FACEBOOK](http://fb.com/xuanbinh.vu.6464)

    + Hoặc 
        ``` 
        [Link FACEBOOK][FB]
        [Link GOOGLE][GG]
        ...
        ...
        [FB]: http://fb.com/xuanbinh.vu.6464
        [GG]: http://google.com/
        ```

        ta được:

        [Link FACEBOOK][FB]

        [Link GOOGLE][GG]

        [FB]: http://fb.com/xuanbinh.vu.6464 "Facebook Bình đẹp trai"

        [GG]: http://google.com/ "Google"

    + Ta cũng có thể để link trực tiếp: http://fb.com/xuanbinh.vu.6464

* **Chèn ảnh**
    + Tương tự ta cũng có các cách chèn ảnh
        ``` 
        ![Tên ảnh](link ảnh "phần mô tả khi trỏ chuột vào ảnh.")

        ví dụ:

        ![Avatar Facebook](https://scontent.fhan5-7.fna.fbcdn.net/v/t1.0-9/48422330_593868904388446_1488964414475337728_n.jpg?_nc_cat=103&_nc_oc=AQlOZyxwshBBYL2rtXgdHvMB-6grkcgAXGgQOg_ggTxbL_I5-EhjEdl-sutAZI9vi1M&_nc_ht=scontent.fhan5-7.fna&oh=d707920adbe88babda41a9f6ae7bd743&oe=5D3B70B5 "Mô tả ảnh")

        ta được:
        ```
        ![Avatar Facebook](https://scontent.fhan5-7.fna.fbcdn.net/v/t1.0-9/48422330_593868904388446_1488964414475337728_n.jpg?_nc_cat=103&_nc_oc=AQlOZyxwshBBYL2rtXgdHvMB-6grkcgAXGgQOg_ggTxbL_I5-EhjEdl-sutAZI9vi1M&_nc_ht=scontent.fhan5-7.fna&oh=d707920adbe88babda41a9f6ae7bd743&oe=5D3B70B5 "Mô tả ảnh")


## **4. Kết luận**

Markdown quả thật rất tuyệt đối với giới lập trình và phát triển phần mềm. Hi vọng bài viết này có thể trở thành một bản ghi nhớ hữu ích cho bạn, và hi vọng bạn sẽ không bao giờ phải bỏ tay ra khỏi bàn phím để sờ đến chuột khi viết bài nữa.