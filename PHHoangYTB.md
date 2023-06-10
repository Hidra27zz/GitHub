# NHỮNG ĐIỀU CẦN LÀM

---
Tìm hiểu sơ về Version Control, Git & Github
Cài đặt Git trên máy

Cơ bản: tạo Github Repository & Clone
Pull & Push

Nâng cao: Branch, Merge
Conflict Resolving, Pull Request

# SOURCE CONTROL/ VERSION CONTROL LÀ GÌ?

---

- Hệ thống giúp lưu trữ mọi thay đổi của source code
- Hỗ trợ nhiều người làm việc cùng lúc
- Xem đứa nào thay đổi code (Rất tiện tìm thằng đổ lỗi)
- Revert các thay đổi, đưa code về version cũ hơn, không lo mất code

# Git là gì ?

---

- Ra đời năm 2005
- Tác giả Lunus Torvald, hỗ trợ viết Lunix kernel
- Toàn bộ code và history được lưu trữ trên máy người dùng
- 3 khái niệm quan trọng: repo, commit, branch

# GitHub là gì ?

---

- Dịch vụ lưu trữ Git Repository lớn nhất Vịnh Bắc Bộ
- Biểu tượng con bạch tuộc thần thánh trong phim hentai
- Code chung chạ với mọi ae trên thế giới
- Thêm một số tính năng cho git.

# các lệnh cơ bản

- git init: tạo ra một repo trên máy
- git clone: lấy từ trên mạng về
- git pull: đồng bộ từ trên mạng về máy

- git add and git add .: thêm nó vào repo
- git commit:
- git push : đồng bộ nó từ máy lên mạng

- git log
- git log --decorate --graph --oneline

![d38b4f4b-b4df-4677-9ef0-db86f3d37e95](https://github.com/Nan27Hid/GitHup/assets/135946173/2971d646-b1f6-49c5-88d8-a65115d4ef6b)

- bạn muốn commit file change to github bạn cần chắc chắn là file ban đầu của bạn ko bị ai sửa trên github
- trường hợp file của bạn ko bị sửa:
  - bạn chỉ cần:
    - git add . 
    - git commit -m "message"
    - git push

- trường hợp file bạn có thay đổi 
  - bạn cần:
    - git pull
    - git add . 
    - git commit -m ""
    - git push


#add hình và chạy được trên GitHub
---
- tạo issue trong repo
- thả file hình cần vào ô trong issue
- lấy link và pass vào file code trên github or file code chính của bạn 
- nếu bạn sửa trên github bạn cần pull về code chính của bạn
- nếu bạn sửa trong code chính bạn cần push lên github.

#Nâng cao (Branch, Merge)

##CÁC LỆNH CƠ BẢN
---
cơ bản
  - git branch
  - git checkout
  - git merge

nâng cao
  - git rebase
  - git cherry - pick

![7d050654-0ea2-4d4d-b3ad-4c8c4fc748ed](https://github.com/Nan27Hid/GitHup/assets/135946173/a6426c9c-6d59-4459-932a-0d39276ebd30)


- ở các công ty thì người ta sẽ tạo thêm một cái Pull Request
#PULL REQUEST LÀ GÌ
---
- là cái làm hiển thị các thay đổi của code, khi các bạn làm gì thì khi đọc cái pull request thì người ta biết được là bạn đã thay đổi những gì trong code, nó giúp gôm lại, và người ta sẽ review cái code đó khi mà cái code đó oke thì người ta mới accept cái pull request. tức là người ta mới merge cái thay đổi đó vào cái branch master.
- đơn giản chỉ là: ê code nè, merge giùm đi
- giúp commit ngắn gọn hơn
- hỗ trợ code review, ngăn code ẩu


Các bước để add branch:
---
- git branch ten_branch
- git branch
- git checkout ten_branch
- git branch 
or có thể sd: git checkout -b ten_branch  (cái này vừa tạo branch vừa checkout)

- tạo code mới trong Vscode
- thêm nó vào branch mới
