# cicd

## Components

다음과 같은 파일들이 존재합니다.

- index.html
- Dockerfile
- deployment.yaml
- workflows/main.yaml

### index.html

컨테이너 안에 들어가는 contents입니다. 예시에서는 nginx를 사용하기 때문에 간단한 html 페이지를 사용합니다.

### Dockerfile

배포할 컨테이너를 빌드하는 빌드 스크립트입니다.


### deployment.yaml

배포하는 Kubernetes manifest 파일입니다. 예시에서는 `Deployment`와 `Service`를 이용하여 nginx를 배포합니다.


### .github/workflows/main.yaml

전체 CI/CD를 수행하는 workflow 스크립트입니다.
