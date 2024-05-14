# Plugin ParagonBelica

- [Paragon: Lt.Belica](https://www.unrealengine.com/marketplace/ko/product/paragon-lt-belica) 콘텐츠 전용 플러그인
- LtBelicaPlayerCharacter 블루프린트 캐릭터 에셋에서 `Reset Orientation and Position` 함수를 사용하기 때문에 `XRBase` 플러그인 종속성을 추가하였습니다.

## 설치 방법

### 서브 모듈로 설치하는 방법

1. 메인 프로젝트 `git` 저장소 열기
2. 플러그인 `git` 저장소를 메인 프로젝트 `git` 저장소에 서브 모듈로서 추가
    - git 저장소의 `하위 폴더`에 언리얼 프로젝트가 생성된 경우 `지역 상대 경로`: `언리얼_프로젝트_폴더_이름/Plugins/ParagonBelica`
    - git 저장소의 `루트 폴더`에 언리얼 프로젝트가 생성된 경우 `지역 상대 경로`: `Plugins/ParagonBelica`

### zip 파일로 사용하는 방법

1. `zip` 파일 다운로드
2. 압축 해제 후 루트 폴더 이름을 `ParagonBelica`으로 수정
3. 언리얼 프로젝트 `Plugins` 폴더에 `ParagonBelica` 붙여넣기