# sass 사용거의 안함. scss를 사용한다.  scss-->샤스라고 읽음

![image](https://github.com/understanding963852/sass/assets/60366769/1817c33d-2d69-43fd-8cc3-7c141c0a4712)


# scss 컴파일

![image](https://github.com/understanding963852/sass/assets/60366769/c555dd17-9130-4f49-877b-00f0077ace3d)

# css 위치변경
![image](https://github.com/understanding963852/sass/assets/60366769/14e35178-6cae-4918-9f33-1814977e3281)

# savaPath:null이면 scss파일과 같은위치에 style.css가 생긴다
![image](https://github.com/understanding963852/sass/assets/60366769/da95b41f-4e36-45c1-a5cd-028f85e77fac)

# ~은 style.scss를 의미, /는 style.scss가있는 폴더
![image](https://github.com/understanding963852/sass/assets/60366769/0cf04327-21e3-4995-ae2b-473069cb02c8)

# scss파일이 있는 폴더의 상위요소에 생성
![image](https://github.com/understanding963852/sass/assets/60366769/6aa860b7-7b4e-43f4-a96b-8f2c422fb617)

# 주석처리 방법
#  //주석처리방법은 css로 컴파일되지 않는다
#  /*  */주석처리방법은 css로 컴파일되어 나타남
![image](https://github.com/understanding963852/sass/assets/60366769/08be5031-4a6c-42bb-b0ee-711d42737545)

# 변수만들기 --> $로 시작함,(영문, 숫자, - , _)만 사용할수 있음. 숫자로 시작할수 없음.
![image](https://github.com/understanding963852/sass/assets/60366769/fc7da532-5e88-44d0-adb8-b79d0bb66b8a)

# Partials(파샬)
  -- 관련된것끼리 묶어서 분리/ 소스에 반복되는 부분들을 분리 분산시켜서 모듈화 시키는 기능
  
  * Partials의 파밍명은 _로 시작하며
  * 불러들일때는 @import '파일명',   이때 파일명에 _는 포함시키지 않고, 확장명도 포함시키지 않는다.
  
  💠  Scss는 _로 시작하는 파일은 컴파일하지 않는다.
  
  ![image](https://github.com/understanding963852/sass/assets/60366769/e5e45fd1-c9a3-41cd-9d6e-c4c598ce8ad9)
  
  # @import -- 변수가 중복될때는 아래의 것이 적용된다. 
  
  ![image](https://github.com/understanding963852/sass/assets/60366769/611e8060-de4c-410f-8fb8-fbe56eb20e26)

  
  # @use  --> 변수이름이 같을때 에러발생, @use를 사용할때는 앞에 파일명을 추가해서 파일명.변수명
  ![image](https://github.com/understanding963852/sass/assets/60366769/f2b971fc-5241-4929-868d-34d411615bf1)

# as 뒤에 별명을 붙여서 사용할수 있다.
![image](https://github.com/understanding963852/sass/assets/60366769/3d2a6231-a0ae-4cdc-9476-f3f06c4c39a4)

 # @forward 는 파샬을 묶어줌  style.scss에서는 _index.scss를 호출하여 사용함
![image](https://github.com/understanding963852/sass/assets/60366769/a21e4ddb-e47a-4ac7-96ca-b73c72c0db57)

# *(와일드카드)를 붗이면 이름을 생략할 수 있다.
![image](https://github.com/dddd1215/sass/assets/129017020/1960b8cd-0d51-4564-a204-2ac415394b49)

