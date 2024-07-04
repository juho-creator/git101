# Git101

## LOG IN
git config --global user.name "juho-creator"</br>
git config --global user.email "juhokim2018@gmail.com"
</br></br></br></br>




## SET UP
git remote add origin https://github.com/juho-creator/AlgoTrading.git</br>
git fetch
</br></br></br></br>

## Issuing new token
git remote set-url origin https://youruser:password@github.com/user/repo.git
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
</br></br></br></br>


# CI/CD
![image](https://github.com/juho-creator/git101/assets/72856990/c0668ed5-3bbd-483c-ae9c-65f9ab011e6d)

- **CI (Continuous Integration)** : 여려 명이 코드 하나를 수정하며 지속적으로 관리함 
- **CD (Continuous Deployment)** : 빌드된 코드를 자동으로 재품 릴리스함
![image](https://github.com/juho-creator/git101/assets/72856990/d591228c-8a4d-4f18-be17-d2fb25903a60)
</br></br></br></br>



# Reference
- [**렉스의 Git 브랜칭 전략**
](https://www.youtube.com/watch?v=wtsr5keXUyE)
- [**Explain Git like I'm five**](https://www.youtube.com/watch?v=YFNQwo7iTNc)
- [**Github와 협업**](https://www.youtube.com/watch?v=3doDm--wuJE)
- [**Git 강의**](https://www.youtube.com/watch?v=hFJZwOfme6w&list=PLuHgQVnccGMA8iwZwrGyNXCGy2LAAsTXk&index=2)
- [**CI/CD란?**](https://www.youtube.com/watch?v=sIPU_VkrguI)
- [**Git 브랜치 보는 법**](https://www.youtube.com/watch?v=PHkdwAL6NQY) 

