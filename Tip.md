git reset HEAD~2
git add .
git commit -m "code api update me"
git push -f
  
  git checkout develop
	git pull origin develop
	git checkout branch_hien_tai
	git rebase develop
	trong quá trình rebase thì có thể có conflict, sửa từng file rồi
	git add .
	git rebase --continue
	// hiện ra sửa, lưu lại thì gõ :wq còn ko lưu thì :q, muốn sửa thì nhấn i
	
	Cho đến khi hiển thị message success
	git push -f origin branch_hien_tai
	
//====lần tới muốn sửa mà muốn giữ 1 commit

	git reset HEAD~1
	git add .
	git commit --amend --no-edit
	git push -f origin <branch_name>
	
	
	git push -u origin feature/hung.ha-api-get-list-picture
