# OrchestratorAccessTokenGen
Platform Orchestrator에서 REST API 사용하기 위한 Access Token 생성하기 

# 준비사항 
1. PlatformLoginCredential 이름의 Credential 만들고 본인의 메일계정과 비번을 기록한다. ( 이 계정이 platform.uipath.com 에 로그인하는 계정임)
2. Chrome Plugin을 설치한다. 

# 실행 결과 
성공적으로 AccessToken 생성시 해당 프로젝트 폴더에 rest_api_token.json 파일이 생성되며, 여기에 필요한 access_token이 있음. 
이 access_token을 API 호출시 header에 설정해주면 됨. 

