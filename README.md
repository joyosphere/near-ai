# near-ai

## 요구사항

- Python 3.9 이상 3.12 미만 버전 지원
- Poetry (Python 패키지 관리자)

## Poetry 설치 및 설정

Poetry가 설치되어 있지 않은 경우, 아래 명령어로 설치할 수 있습니다:

```bash
curl -sSL https://install.python-poetry.org | python3 -
```

Poetry 설치 후, 환경 변수 설정이 필요할 수 있습니다. 아래 명령어를 실행하여 PATH에 Poetry를 추가합니다:

```bash
export PATH="/Users/$USER/.local/bin:$PATH"
```

## 프로젝트 설치 및 실행

1. 프로젝트 클론:
```bash
git clone git@github.com:joyosphere/near-ai.git
cd near-ai
```

2. Poetry를 사용하여 의존성 설치:
```bash
poetry install
```

3. Poetry 가상환경 활성화:
```bash
poetry shell
```

4. 프로젝트 실행:
```bash

```

## 개발 환경 설정

Poetry를 사용하여 개발 환경을 설정할 때 유용한 명령어들:

- 새로운 패키지 설치: `poetry add package-name`
- 개발 의존성으로 패키지 설치: `poetry add --dev package-name`
- 의존성 업데이트: `poetry update`
- 가상환경 정보 확인: `poetry env info`
- 의존성 목록 확인: `poetry show`
