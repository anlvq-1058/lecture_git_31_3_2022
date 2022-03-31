- commit 
  + -m: tạo ra một commit mới 
  + --aemnd: gộp lại commit

- Nhiều commit
  + chủ quan: sử dụng commit -m nhiều lần
  + khách quan: vô tình sử dụng commit -m
  + checkout từ một nhánh khác 

    VD: tạo form - tạo controller, save DB - thêm validates
            ok              ok                    x
            c1              c2                    x
  chapter 3
    -> đẩy code lên trên github
    checkout -> chapter 4
      -> commit chapter 3 + commit chapter 4
- Gộp commit
  - rebase: git rebase -i HEAD~n (n=2)
    - squash 
    - fixup  
  - fix conflict

  - reset option commit-id 
          + --soft 
          + --hard
          + x
  - git commit --amend
