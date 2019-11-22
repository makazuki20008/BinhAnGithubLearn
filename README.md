# BinhAnGithubLearn
học github qua các ví dụ cơ bản, clone, add, push, status, commit, merch, branch,...

Tạo một github project
- Tiêu đề trong readme
- Tạo text trong project rồi update lên
- Tạo project angular
- Tạo project android
- Xóa project

Tạo một github project
- Tạo github project ta vào new repository để thêm vào github một repository
	  Trong phần này thì repository sẽ hiển thị to nhất trong phần readme
	  Trong phần decription sẽ là nội dung nhỏ bên trong của readme
- clone repository về để sử dụng trên client
- .git là một thư mục trong thư mục của project ta clone về, nơi này để mô tả các git và thay đổi
của git
- Thêm file vào .git ta dùng câu lệnh git add
- Cho thay đổi vào file đã lưu trong .git ta dùng git commit -m "Add new text"
- Để xem tình trạng file trong .git ta dùng git status
- Để cập nhật project lên trên github.com ta phải git add file đã thay đổi vào .git và git push 
lên online
- Xóa project trong github ta vào setting vào mục Danger zone rồi xóa đi


Các câu lệnh git:  
git init (tạo ra repository ở local (xuất hiện .git))  
git remote add origin https://github.com/user-name/repository-name (kết nối thư mục local với online)  
git clone (tải thư mục trên online xuống local)  
git branch --- (tạo branch mới)  
git checkout --- (đưa đến branch nào đó)  
git add * (thêm thư mục vào repository ở local)  
git commit (thêm thay đổi vào repository ở local)  
git commit -m "Add new file a KhoaPham.txt" (thêm thay đổi kèm với mô tả vào repository ở local)  
git commit -a -m "Adding ddress"  
git merch --- (hợp nhất các branch lại với nhau)  
git log -- (hiện lịch sử commit trong repository)  
git revert -- (trả thư mục lại như lần commit đã làm mà ta thấy id ở log)  
git status (tình trạng các thư mục đã vào repository hay chưa)  
git push (đưa repository ở local lên online)  
git diff (thông tin commit)  
git show (thông tin commit, cây thư mục, blobs)  
git pull -- (cập nhật hết repository online xuống local)  
