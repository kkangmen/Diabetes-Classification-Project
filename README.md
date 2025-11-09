# Diabetes-Classification-Project
기학기 팀플용

# 1. 다른 동료가 수정된 파일을 dev에 통합 시켰으면, 내 구글드라이브에 갖고온다.
!git checkout dev
!git pull origin dev

# 2. 작업을 하기 전에, 방금 최신화한 dev의 내용을 내 브랜치로 먼저 merge를 한다.
!git checkout kangmin-dev
!git merge dev

# 3. github의 내 브랜치로 작업물을 올린다.
!git add diabetes.ipynb
!git commit -m "message"
!git push origin kangmin-dev
