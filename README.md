# sass 사용 거의 안함. scss사용한다. scss --> 샤스라고 읽음

![image](https://github.com/dddd1215/sass/assets/129017020/07713713-16a0-43c7-ba3e-c2a3afd693eb)


# scss 컴파일

![image](https://github.com/dddd1215/sass/assets/129017020/c41c84f6-128f-4375-a774-e42268d01d1a)


# css 위치 변경

![image](https://github.com/dddd1215/sass/assets/129017020/e22423f6-df0a-46c3-85ab-8430a1d22795)
# savePath:null이면 scss파일과 같은 위치에 style.css가 생긴다.

![image](https://github.com/dddd1215/sass/assets/129017020/896e920d-84f1-4120-bb84-1690d05e3d87)
# ~은style.scss를 의미, /는 style.scss가 있는 폴더
![image](https://github.com/dddd1215/sass/assets/129017020/e6048fcb-5782-4fc4-8838-4dcbc50e4c5a)

# scss 폴더의 상위요소에 생셩
![image](https://github.com/dddd1215/sass/assets/129017020/390638a3-0893-47ae-aaea-65c900f9ec74)

#주석처리방법
# //주석처리 방법은 css로 컴파일되지 않는다
#/**/주석처리 방법은 css로 컴파일 되어 나타난다

# 변수 만들기 --> $로 시작함,(영문,숫자,-,_)만 사용할 수 있음. 숫자로 시작할 수 없음

# partials(파샬)
--관련된 것 끼리 묶어서 분리/소스에 반복되는 부분들을 분리 분산 시켜서 모듈화 시키는 기능

* partials의 파밍명은_로 시작하며
* 불러들일때는 @import '파일명' 이때 파일명에 _는 포함시키지 않고, 확장명도 포함시키지 않는다.

Scss는 _로 시작하는 파일은 컴파일하지 않는다.
