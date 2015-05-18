# zipCode (우편번호 검색)
공공데이터 Open API 를 사용한 새우편번호 검색

Screen shot :
![Screen shot](http://applusform.github.io/newZipCode/screenshot.png)

### 인증키 발급
https://www.data.go.kr 에서 오픈API - 새우편번호 지번주소 조회 서비스의 [SERVICE KEY]를 발급 받아야 합니다. 

### !! 주의 !!
* 우정사업본부에서 제공하는 새우편번호 데이터가 아직 완전하지 않아 오동작할 수 있습니다.
  1. 구의1동 처럼 숫자가 있는 경우 현재 동작하지 않습니다.
  2. 세종시는 동작하지 않습니다.

### 실행하는 방법
1. MOML Application Viewer를 설치한 후 실행합니다. ( [Google Play Store](https://play.google.com/store/apps/details?id=org.mospi.momlappviewer), [Xcode Project](https://github.com/applusform/MOMLAppViewer_iOS), [Android Studio Project](https://github.com/applusform/MOMLAppViewer_Android_Studio) )
2. 주소 입력창에 **applusform.github.io/newZipCode** 를 입력합니다.

### 빌드하는 방법 ( .apk, .ipa )
1. http://ApplusForm.com 사이트의 **[Get Agate]** 메뉴에서 **MOML API Demo Peoject** 를 다운로드 받습니다.
2. **moml** 폴더의 모든 파일들을 이 프로젝트의 파일로 교체합니다.
3. 빌드하고 실행합니다.

