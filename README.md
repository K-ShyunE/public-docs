# 공개 문서 저장소

여러 앱의 개인정보처리방침, 이용약관, 지원 문서 및 오픈소스 고지를 한 곳에서 공개하기 위한 GitHub Pages 저장소입니다.

## 디렉터리 구조

```text
docs/
├── index.html
├── assets/
│   └── common.css
└── apps/
    └── ai-usage-tracker/
        ├── index.html
        └── privacy-policy/
            └── index.html
```

새 앱을 추가할 때는 `docs/apps/<app-slug>/` 아래에 앱 안내 페이지와 필요한 문서를 배치합니다. 한 번 외부 서비스에 등록한 문서 URL은 변경하지 않습니다.

## 새 저장소에 올리는 방법

1. GitHub에 `public-docs`라는 공개 저장소를 생성합니다.
2. 이 디렉터리 안의 파일을 새 저장소 루트에 복사합니다.
3. `main` 브랜치에 커밋하고 푸시합니다.
4. 저장소의 `Settings > Pages`로 이동합니다.
5. `Build and deployment`의 Source를 `Deploy from a branch`로 선택합니다.
6. Branch는 `main`, Folder는 `/docs`를 선택하고 저장합니다.
7. 배포가 끝나면 아래 주소를 로그인하지 않은 브라우저에서 확인합니다.

```text
https://k-shyune.github.io/public-docs/
https://k-shyune.github.io/public-docs/apps/ai-usage-tracker/privacy-policy/
```

## 운영 원칙

- 이 저장소에는 외부 공개가 가능한 자료만 저장합니다.
- API 키, 인증 토큰, 사용자 데이터 및 내부 운영 문서는 저장하지 않습니다.
- 개인정보처리방침에는 시행일과 최종 수정일을 표시합니다.
- 앱의 데이터 처리 방식이 변경되면 코드 배포 전에 관련 문서도 함께 갱신합니다.
- 삭제하거나 이동한 문서의 기존 URL은 가능한 한 리디렉션으로 유지합니다.

