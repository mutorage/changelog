# changelog
change log for mutorage

## clog 2020.12.29
  * [Backend_API] YTM - Backend간 통신 프로토콜을 HTTPS에서 HTTP/2 over TLS로 변경
  * [Backend_API] YTM - Backend간 통신데이터 압축 적용 (gzip, br, deflate)
  * [Backend_API] YTM - Backend간 preconnect적용

## clog 2021.01.04
  * [Backend_API] 앨범 또는 노래가 합작품(아티스트가 두명 이상)일경우 오류가 발생하는 문제 수정
  * [Backend_API] 아티스트의 구독자수가 비공개일때 발생하는 오류 수정

## clog 2021.01.07
  * [Backend_API] 소스코드 전체 리펙토링, YTM-API전체를 모듈화
  * [Desktop-Web] 데스크톱 앱 디자인 및 개발 방향 수립, 모의 구현(추후 재 작성 필요)

## clog 2021.02.04
  * [Desktop-Web] 클로즈 베타 서비스 시작

## clog 2021.02.14
  * [Desktop-Web] 코드 리펙토링

## clog 2021.02.27
  * [Backend_API] API를 요청할때마다 clickTracking정보를 전송하는 기능을 삭제함.(YTM-CTP가 하는 일을 명확히 알게됨.)
