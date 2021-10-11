# route-gg-yaml
루트지지 운영에 필요한 yaml 파일 목록 입니다.

- 프론트와 백엔드는 3개의 파드를 가지고 있는 Deployment로 구성했습니다.
- 위 Deployment의 각 파드들은 로드 발란서 서비스를 등록했습니다.
- DB pod는 ClusterIP를 통해 고정아이피로 하여 각 모듈이 DB 찾을수 있도록 하였습니다.
- route-gg-yaml에 yaml 파일을 github에 저장했습니다.
