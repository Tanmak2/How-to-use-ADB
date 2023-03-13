# ADB 사용법
```
1. 환경변수 설정
  가. Android Studio 실행 -> File 탭 -> Settings 클릭
      또는 Android Studio 실행 -> Ctrl+Alt+S
  나. Appearance & Behaviour -> System Settings -> Android SDK 클릭 -> Android SDK Location 경로 복사
  다. 윈도우키 + R -> 실행창에 sysdm.cpl 실행
  라. 고급탭 -> 환경 변수 클릭
  마. 시스템 변수 -> 변수명 Path 클릭 -> 편집 클릭
  바. 새로 만들기 -> {Android SDK 경로}\platform-tools 입력 -> 확인
```
```
2. ADB로 디버깅 하기
  가. 윈도우키 + R -> cmd 실행
  나. Unity로 만든 앱을 테스트용 스마트폰에 설치
      ※ Unity로 만든 앱이 아니여도 가능, Unity에서 Debug.Log("내용")을 확인가능
  다. 테스트용 스마트폰에서 앱 실행
  라. cmd창에서 adb logcat -s Unity 입력
  마. Unity로 만든 앱에서 나오는 로그 확인가능
      ※ 어디서 어떤 오류인지도 확인가능 ex) NullReferenceException, MissingMethodException 등등
```
