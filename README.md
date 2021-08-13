# GIT TUTORIAL

1.
```sudo apt install git-all```

```git --version```

```git config --global user.email "nhien@gmail.com```

```git config --global user.name "nhienduyvu```

𝗰𝗼𝗻𝗳𝗶𝗴: cấu hình 

2.
```git init```

𝗶𝗻𝗶𝘁𝗶𝗮𝗹𝗶𝘇𝗲𝗱: khởi tạo

```git status```

𝘂𝗻𝘁𝗿𝗮𝗰𝗸𝗲𝗱 𝗳𝗶𝗹𝗲𝘀: tệp không theo dõi

𝗰𝗼𝗺𝗺𝗶𝘁: thao tác ghi lại việc thêm/ thay đổi file hay thư mục vào repository / cam kết (ggdich)

𝗿𝗲𝘀𝗽𝗼𝗻𝘀𝗶𝘁𝗼𝗿𝘆: kho

```git add <file>``` 

```git add . : thêm tất cả các file``` 

```git commit -m " " ``` 

𝗶𝗻𝘀𝗲𝗿𝘁𝗶𝗼𝗻: sự chèn (ggdich) / Nhiên hiểu: sự thêm mới

𝘄𝗼𝗿𝗸𝗶𝗻𝗴 𝘁𝗿𝗲𝗲: cây thư mục hiện hành

```git log```

```𝑐𝑜𝑚𝑚𝑖𝑡 XXXXXXXXXXXXXX
𝐴𝑢𝑡ℎ𝑜𝑟: 𝑛ℎ𝑖𝑒𝑛𝑑𝑢𝑦𝑣𝑢 <𝑛ℎ𝑖𝑒𝑛@𝑔𝑚𝑎𝑖𝑙.𝑐𝑜𝑚>
𝐷𝑎𝑡𝑒:   Time  +0700
    𝑓𝑢𝑐𝑘𝑦𝑜𝑢
```

```git show XXXXXXXXXXXXXX```

𝘮𝘢𝘶 𝘹𝘢𝘯𝘩 𝘭𝘢 𝘯𝘰𝘪 𝘥𝘶𝘯𝘨 𝘮𝘰𝘪 𝘥𝘶𝘰𝘤 𝘵𝘩𝘦𝘮 𝘷𝘢𝘰

```git diff``` (diff viết tắt của different) xem thay đổi

3.
𝘄𝗼𝗿𝗸𝗶𝗻𝗴 𝗱𝗶𝗿𝗲𝗰𝘁𝗼𝗿𝘆: <file_maudo> thư mục làm việc 

𝘀𝘁𝗮𝗴𝗶𝗻𝗴 𝗮𝗿𝗲𝗮: <file_mauxanh> khi commit chỉ file trong staging are mới được commit 

𝗴𝗶𝘁 𝗿𝗲𝘀𝗽𝗼𝗻𝘀𝗶𝘁𝗼𝗿𝘆: lưu những thay đổi của những commit (xem dùng git log)

```gitk```

𝗚𝗨𝗜(𝗴𝗿𝗮𝗽𝗵𝗶𝗰 𝘂𝘀𝗲𝗿 𝗶𝗻𝘁𝗲𝗿𝗳𝗮𝗰𝗲): giao diện người dùng

4.
```git checkout -- <file_name>``` xóa bỏ file chưa lên staging area 

𝗰𝗵𝗲𝗰𝗸𝗼𝘂𝘁: thủ tục thanh toán (ggdich)

```git reset HEAD <file_name>```: xóa những thay đổi hiện tại ở working directory

5.
```git checkout -b <branch_name>``` tạo một branch và chuyển qua branch đó làm việc

```git branch``` xem đang có nhánh nào

```git checkout <branch_name>``` chuyển qua <barnch_name>

```git merge <branch_name>``` hợp nhất <branch_name> vào master (lưu ý: nhớ |git checkout master trước lệnh git merge <branch_name>

```git branch -D <branch_name>``` xóa <branch_name>

𝗯𝗿𝗮𝗻𝗰𝗵: nhánh

𝗺𝗲𝗿𝗴𝗲: hợp nhất

6.
(dùng git log để lấy XXXXXXXX)

```git reset --soft XXXXXXXXX```

```git reset --mixed XXXXXXXX```

```git reset --hard XXXXXXXXX```

7.
```git revert XXXXXXXXXXX``` khác với reset là khi Nhiên thấy một commit Nhiên ghét nó, cách đây vài commit rồi và muốn bỏ nó đi thì dùng git revert / là một lệnh trong git có tác dụng hoàn nguyên lại một số commit nào đó đã tồn tạ

𝗿𝗲𝘃𝗲𝗿𝘁: hoàn nguyên

8.

**gitignore**: liệt kê những file mà Nhiên không mong muốn cho vào git hoặc hiểu nôm na là Git sẽ bỏ qua những file đó đi.
tạo 1 file .gitignore/liệt kê các file không muốn commit

𝗶𝗴𝗻𝗼𝗿𝗲: làm lơ (ggdich)

9.
```git remote add orgin <link>```

```git remote -v``` danh sách các remote repo

```git push -u oringin master```

```git push```

𝗼𝗿𝗶𝗴𝗶𝗻: gốc

10. 
```git config --global credential.helper store```

```git config --global credential.helper "cache --timeout=18000"```

```git ssh / gnome-keyring```

11.
```git clone <link>```

```git pull``` merge tất cả các thay đổi trên remote repository tới thư mục đang chạy trên local, pull command cần được dùg

𝗽𝘂𝗹𝗹: kéo

12.
push a branch

push request

rebase
....
𝑐𝑎𝑝 𝑛ℎ𝑎𝑡 𝑠𝑎𝑢....
