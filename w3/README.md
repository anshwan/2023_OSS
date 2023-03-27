# 2023_OSS   
## 2023 OSS 수업   
### 3주차 git   

### 이미지   
![한국항공대학교 로고](./kauimg.png)   

### 링크 
[LMS](https://lms.kau.ac.kr/)

### Progit 링크   
[Progit](https://git-scm.com/book/ko/v2)   

### 주요 git 명령어   
* add : 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용
   * 예) git add
* commit 
* branch
* merge
* status
* log
   * 예) git log --oneline -- decorate --graph --all 
<hr/>

### 2주차 숙제
```bash
#!/bin/bash

NAME=안승환
STUDENT_ID=2020125038
FILE_PATH=$(find /home/kau2 -name 'w2_homework.txt' 2> /dev/null)
LINE_NUMBER=$(wc -l $FILE_PATH | awk '{print$1}')
LAST_LINE=$(tail -n 1 $FILE_PATH)


echo "----------"
echo -e "name : \n$NAME\n"
echo "----------"
echo -e "student id : \n$STUDENT_ID"
echo "__________"
echo -e "\nfile path : \n$FILE_PATH\n"
echo "----------"
echo -e "line number : \n$LINE_NUMBER\n"
echo "----------"
echo -e "last line : \n$LAST_LINE\n"
```

## 마크다운

### 목록

#### 번호있는 목록 : 내림차순 정렬
1. 첫번째
2. 세번째
3. 두번째

#### 번호없는 목록 : *,-,+
+ 첫번째   
+ 세번째   
+ 두번째 
<hr/>

- 빨강   
   - 녹색   
      - 파랑   

### 강조

*single asterisks*    
_single underscores_    
**double asterisks**    
__double underscores__    
~~cancelline~~

