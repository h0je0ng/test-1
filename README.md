# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6

#### 내용추가하기!!!


### 가로줄넣기  : - 또는 *를 3개이상 넣으면 됨


------
******


## 텍스트 줄바꿈을 할때는 엔터를 2번 눌러야 됨
줄바꿈 

해요 

이렇게


## 순서목록
1.Git

2.main

3.push

4.pull

5.협업하기

순서는 바뀌어도 상관이 없어요/ 순서대로 출력돼

## 순서없는 목록은 +,-,*를 붙여 나열 
- Git

    * main

      - origin

          + push

              * pull
         
탭을 누르면 여러 단계 가능 

## 1.굵게 : 텍스트 앞 뒤로 **또는 __로 감싸기 (_2개)
## 2.기울임체 : 텍스트 앞 뒤로 * 또는 _로 감싸기(_1개)
## 3.굵은 기울임체 :  텍스트 앞뒤로 *** 또는 ____로 감싸기(_3개)
## 4.취소선 : 텍스트 앞 뒤로 ~~로 감싸기

**깃허브**는 __원격 저장소__ 를 제공하는 서비스 입니다. 
***버전관리***와 협업기능을 주로 사용할 수 있습니다. ~~ㅎㅎ~~

## ① 소스코드를 삽입할때는 백틱(')

한줄짜리 소스코드는 `void sum(x,y) {retyrn x+y;}` 이렇게 쓰면 됩니다 

## ② 여러 줄 코드를 삽입 할때는 소스코드 앞 뒤에 ```작성

```java
int sum(int x, int y){
  int result = x + y;
  return result;
}
```

## 링크표시

1. <주소>: 링크주소가 그대로 화면에 표시됨
2. [텍스트].<주소>: 링크 텍스트만 나타나고 텍스트를 클릭하면 주소로 이동
3. [텍스트].<주소,"부가설명"> : 링크텍스트 위에 커서를 올리면 부가 설명이 말풍선으로 표시됨

<https://www.naver.com>

[네이버].<https://www.naver.com>

[네이버].<https://www.naver.com,"클릭하면 네이버로 이동합니다">

## 이미지업로드 : 해당레파지토리에 이미지를 업로드 한뒤 ![설명메세지](./파일명)

![하와이](./하와이_.jpg)
