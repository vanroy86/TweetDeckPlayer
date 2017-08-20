# 트윗덱 플레이어
Copyright (c) 2016-2017 Sokcuri, Dalgona, Gaeulbyul and other contributors  
http://github.com/sokcuri/TweetDeckPlayer

> 최신 릴리즈는 [트윗덱 플레이어 릴리즈 페이지](https://github.com/sokcuri/TweetDeckPlayer/releases)에서 다운로드할 수 있습니다.  
> 버전 확인 및 업데이트 이력은 [ChangeLog.md](ChangeLog.md) 파일을 확인하거나 릴리즈 페이지를 참고하세요.

> 사용 중 문의사항 또는 이슈가 있다면 [트윗덱 플레이어 이슈 페이지](https://github.com/sokcuri/TweetDeckPlayer/issues)를 방문하세요.

---

트윗덱 플레이어는 [Electron](http://electron.atom.io/) 기반 데스크톱 웹앱으로, 기존 트윗덱보다 더 많은 부가 기능과 퍼포먼스를 제공합니다. 
웹 브라우저와 독립적인 세션을 유지하기 때문에 각각 다른 아이디로 트윗덱을 로그인할 수 있습니다.


추가 기능
----------
- 커스터마이징
  - 마음(하트) 대신 관심글(별)로 바꾸기
  - 텍스트 폰트 글씨체/글씨크기 변경
    - 폰트를 여러개 지정하려면 arial, NanumGothic과 같이 입력합니다.
  - 컬럼 너비 커스터마이징
  - 프로필 이미지 원형 표시

- 이미지 저장 부가 기능
  - 이미지를 끌어서 바탕화면에 저장
  - 이미지를 원본(orig) 사이즈로 다운받기
  - 마음을 누르면 이미지 바로 저장
    (MAC은 alt, 윈도우 또는 리눅스는 ctrl를 누르고 마음을 찍으면 저정하지 않습니다)

- 트윗 관련 부가기능
  - 엔터 키로 트윗하기
  - 빠른 리트윗
    - Shift 키를 누르고 클릭하면 이전과 같은 리트윗 박스가 뜹니다
  - 정규식 트윗 필터
  - 알림 없는 인용

- 퍼포먼스 향상
  - 키보드로 트윗 선택시 애니메이션 최소화

- n시간마다 자동 새로고침 기능
  - 지정된 시간마다 자동으로 새로고침해 트윗덱의 메모리 폭주를 방지

- 기타 편의기능
  - unlink.is 주소 자동 변환
  - 내부 브라우저로 페이지 띄우기
    - shift 키를 누르고 링크를 클릭하면 외부 브라우저로 띄웁니다
  - 단축키 `Ctrl+<0-9>`를 통한 손쉬운 기본 계정 전환
  - 웹 브라우저와 독립된 세션 제공

* unlink.is, 정규식 트윗 필터 기능은 페이지를 한번 새로고침해야 적용됩니다. 
* 페이지 새로고침은 아무곳에 우클릭 후 reload 메뉴를 누르시거나 alt를 누르고 View의 Reload 메뉴를 눌러주세요.

사용법
------
- **설정창 여는 법**
 - 트윗덱 플레이어 화면에서 alt를 누르고 File의 Setting 메뉴로 들어가세요.
 - 트윗덱 설정 아이콘에 마우스를 대고 우클릭한 후 Setting 메뉴를 클릭하세요.

- **데이터 폴더**
 - 트윗덱 플레이어는 각 폴더당 한개의 창을 띄울 수 있습니다. 여러 곳에 각각의 실행파일을 복사하고 실행하면 각각 다른 계정으로 로그인이 가능합니다.
 - Mac의 경우 app 파일이 위치한 폴더 안에 app 파일과 동일한 이름의 폴더가 생성되며, 생성된 폴더 안의 data 폴더에 데이터가 저장됩니다.
 - 윈도우의 경우 exe 파일이 위치한 폴더의 data 폴더 안에 데이터가 저장됩니다.

최소 사양
--------
- Window : 32/64bit
 - **윈도우 비스타 이상** - 크로미움 및 Electron의 윈도우 XP 지원 종료로 인해 비스타, 윈도우 7 이상에서만 실행이 가능합니다.
- Mac : 64bit
- Linux : 32/64bit

문서 파일
--------
* [README.md](README.md) - 지금 보고 계신 이 파일입니다!
* [ChangeLog.md](ChangeLog.md) - 트윗덱 플레이어 업데이트 및 변경사항을 확인할 수 있습니다.
* [Installation.md](Installation.md) - 패키지 또는 쉘을 통한 수동 설치 방법에 대해서 알아봅니다.
* [LICENSE.md](LICENSE.md) - 트윗덱, 트윗덱 플레이어 및 라이브러리의 라이센스를 고지합니다.