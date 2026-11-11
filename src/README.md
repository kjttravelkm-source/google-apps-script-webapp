# Apps Script 소스

기존 프로젝트를 별도 로컬 폴더에 `clasp clone-script`로 백업한 뒤, 공개해도 되는지 검토한 전체 소스와 `appsscript.json`을 이 폴더에 넣습니다. 하위 폴더 구조를 그대로 유지하세요. OAuth 파일, 시트 데이터, 비공개 설정은 커밋하지 마세요.

Actions의 **Apps Script upload**에서 `check`는 Google 프로젝트 읽기 권한을 확인합니다. 백업을 마치고 덮어쓰기를 승인한 경우 `backup_confirmed`를 선택하고 `upload`를 실행하세요. `redeploy`는 `APPS_SCRIPT_DEPLOYMENT_ID`로 지정된 기존 버전 배포를 갱신합니다.

수동 업로드를 검증한 뒤 Actions 변수 `APPS_SCRIPT_AUTO_UPLOAD`를 `true`로 설정하면 `main`의 `src/` 변경이 Apps Script 편집기에 자동 업로드됩니다.
