This project is just a demo how to use git
//git init
//git status
//git add
//git commit : đóng gói những thằng màu xanh (object or hộp) có dán nhãn
Ex: git commit -m 'Add README file'

//git log (xem các commit)
//git show (xem một commit - có key)
//git diff 	//different: xem noi dung cua file modifile
-- ấn "q" để thoát ra chế độ xem different

// working directory: thư mục làm việc
// staging area: - git add thì các file vào khu này. chỉ có các file này được phép commit
// git repository :- sau khi commit các file sẽ được lưu vào khu này (lưu những thay đổi của các commit)

//gitk : xem giao diện dạng cửu sổ (giống //git show)

//git checkout :- xóa bỏ một file chưa lên staging area
//git reset	: xóa bỏ một file đã lên staging area
-- chuyển một file từ staging -> directory
-- xóa những thay đổi hiện tại ở working directory

//git checkout - b <branch> (branching) // vừa tạo branch vừa checkout
//git checkout <branch>		// chuyển tới branch
//git merge
- branch: tạo một nhánh mới
- merge: ghép nhiều nhánh
- công dụng khi có những chức năng mới (ex: tạo trang mới) tạo ra một branch để chạy, nếu đã chạy ổn thì merge lại. Để đảm bảo master luôn là tốt nhất
- checkout: chuyển sang nhánh đó làm việc

