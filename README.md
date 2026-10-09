# Y다운로더 업데이트 공지

Y다운로더 전용 공개 공지 저장소입니다. 앱 소스·설치파일·로그·인증정보는 보관하지 않습니다. 다른 앱의 공지와 분리하여 관리합니다.

## 조회 주소

- 일반 배포: https://raw.githubusercontent.com/codeyellow34-ux/YDownloader-Updates/main/latest.json
- 테스트: https://raw.githubusercontent.com/codeyellow34-ux/YDownloader-Updates/main/test.json

0.1.13 설치본은 위 주소를 사용합니다. 업데이트 페이지는 현재 제작자 https://x.com/yno_dev 로 연결됩니다.

## 공지 관리

- 현재 두 파일은 `active: false`이며 실제 업데이트 공지를 띄우지 않습니다.
- 일반 파일은 `channel: stable`, `releaseId: yd-` 접두사, 테스트 파일은 `channel: test`, `releaseId: test-` 접두사를 사용합니다.
- `productId`는 `gif-downloader-y`, `schema`는 `1`, 버전은 숫자 3개(예: `0.1.13`)를 사용합니다.
- 설치파일 전달 후 별도 사용자 승인 시에만 해당 버전·공지 식별자·간결한 `patchNotes`를 맞춰 `active: true`로 변경합니다.
- 일반 공지에 테스트 버전을 게시하지 않습니다. JSON으로 앱의 이동 링크를 변경하지 않습니다.

## 공개 파일 허용 목록

- `latest.json`
- `test.json`
- `README.md`
