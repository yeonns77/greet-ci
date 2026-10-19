# greet-ci

인사말을 출력하는 Python 프로그램입니다.

## 설치 및 동기화

```bash
uv lock
```

## 실행

```bash
uv run --locked python greet.py Hee
# 출력: Hello, Hee!

uv run --locked python greet.py
# 출력: Hello, world!
```

## 테스트 및 정적 분석

```bash
uv run --locked pytest -q greet.py
uv run --locked black --check greet.py
uv run --locked flake8 greet.py
uv run --locked mypy greet.py
```

## 패키지 빌드

```bash
uv build
```
