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
> 터미널 -> keystore 폴더로 이동 -> keytool -list -v -alias (alias이름) -keystore 이름.keystore 입력 

**여기서 오류가 생겼다. 자바 런타임이 없어서 에러가 뜬것이다. https://www.lainyzine.com/ko/article/how-to-install-java-runtime-environment-on-macos/ 여기에 나오는 방법을 통해 설치를 하고 실행을 하였더니 실행이 되었다**

SHA1: 82:C3:D4:1F:59:97:C4:37:F5:66:50:9A:0B:84:7E:6F:59:B2:F4:98
-> 디지털 지문 추가
