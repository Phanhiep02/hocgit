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

# github

- git remote and add origin {repo url}
- git push origin {branch name}
- git clone {repo url}
- git fetch origin
- git checkout -b {branch name} origin/{branch name}

- git push
- git push -u origin {branch name} đẩy nhánh lên git

-- tạo nhánh từ trên git xong lấy về

1. git fetch origin
2. tên tạo , file ở github
   2.1 git checkout -b staging origin/staging

- muốn merge từ github thì tạo Pull request
- khi tạo và thay đổi xong ở trên github thành công thì sau đó sẽ kéo về code ở máy tính
- dùng git pull

# xử lí conflict

- cố tình để conflict

1. git checkout master
2. git pull origin {brand name conflict}
3. check thủ công
4. git add . , git commit , git push
