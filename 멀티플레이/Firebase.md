# Import해주어야 하는것

FirebaseAuth.유니티패키지
>계정인증용으로 사용

우리의 프로젝트를 파베가 인식을 하려면, 
> Firebase가 우리에 대한 식별자를 가지고 있어야함. 동작할 대상의 앱에 대한 식별자를 알고 있어야함.
> 세팅에서 안드로이드로 바꾸어줌

식별자 세팅
> Package name -> 설정 (본인은 com.mineo.firebasestudy 로 변경)

서명 세팅
> 서명을 넣어주어야 파베에서 신뢰할수 있는 앱으로 인식
> Publishing Settings -> KeyStore Manager -> keystore -> Create New -> Anywhere -> 프로젝트 내부에 폴더 생성!-> 패스워드 설정 , Alias설정 및 Alias비번 설정
