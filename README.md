# Git101

## LOG IN
git config --global user.name "juho-creator"</br>
git config --global user.email "juhokim2018@gmail.com"
</br></br></br></br>




## SET UP
git remote add origin https://github.com/juho-creator/AlgoTrading.git</br>
git fetch
</br></br></br></br>




## UPDATING REPO
git init</br>
git add . </br>
git status</br>
git commit -m "Updated"</br>
git remote add origin  https://github.com/juho-creator/AlgoTrading.git</br>
git push -u origin main
</br></br></br></br>





## DOWNLOADING REPO
1st : git clone https://github.com/juho-creator/AlgoTrading.git</br>
2nd : git pull
</br></br></br></br>




## BRANCHES
1. Switching Branch</br>
git checkout -b {branch name}</br>

2. Pushing to branch</br>
git push -u origin {branch name}		</br>


3. Deleting branches</br>
git push origin --delete main 
</br></br></br></br>


# Git Flow 
![image](https://github.com/juho-creator/git101/assets/72856990/f97ddfbb-6387-4f37-bea0-ecdbe068352d)

**메인 브렌치**
- Master (제품으로 배포가능)
- Develop (개발자들이 개발하는 브랜치)
</br></br>


**보조 브랜치**
- feature : 기능 구현 ( Develop ---> Develop)
- release :  QA (Develop ---> Develop  & Master)
- hotfix : 빠른 버그 수정 ( Master --> Develop & Master)

--no-ff : merge를 할때 사용함
</br></br>


# Reference
[**렉스의 Git 브랜칭 전략**
](https://www.youtube.com/watch?v=wtsr5keXUyE)
