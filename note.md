# Terms

repository (repo)
branch(nhánh)
conflict
local
remote

# Commands

- git init
- git status (trạng thái )
- git add (lưu lại folder)
- git reset (quay lại folder vừa lưu)
- git commit -m (note)
- git log --oneline
- git checkout {branch name} để tới nhánh commit đó
- git branch - nhánh mặc định (main)
- git checkout -b tên của branch để tạo nhánh mới

  khi bên nhánh dev có thêm contact mà muốn master cũng có thì dùng merge

- git merge {branch name}
- git branch -d {branch name} - xóa nhánh

- xử lí conflict xong thì git add . , git commit

- git push
- git push -u origin {branch name} đẩy nhánh lên git

-- tạo từ trên git xong lấy về

1. git fetch origin
2. tên tạo , file ở github
   2.1 git checkout -b staging origin/staging
