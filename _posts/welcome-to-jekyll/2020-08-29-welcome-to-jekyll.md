---
layout: post
title:  "Git 접속용 SSH Public Key 등록/수정"
date:   2022-07-27 23:10:00 +0700
categories: jekyll update
---

우리 회사는 AWS로 Redmine과 Git서버를 연동하여 사용중이다. 
직원 한 분이 잘 되던 Git에 접속이 안된다고 했다.

SSH Key로 접속하기 때문에 사용하던 키를 새롭게 변경하고자 직원에게 id_rsa Key를 생성해달라고 하고 공개키를 전달받았다. 

전달받은 키를 authorized_key에 등록해야 한다.

서버 ssh에 접속 후 ~/.ssh/authorized_key 파일 내의 직원 key를 교체 해준다. 


Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
