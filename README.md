# DataAnalyst

데이터 분석 프로젝트를 위한 리포지토리입니다.

## 프로젝트 설명

이 프로젝트는 데이터 분석 작업을 위한 환경을 제공합니다.

## 필수 요구사항

- Python 3.9 이상
- pip3 (Python 패키지 관리자)

## 설치 및 실행

### 1. 리포지토리 클론
```bash
git clone https://github.com/jun789-lee/DataAnalyst.git
cd DataAnalyst
```

### 2. 가상 환경 생성 (권장)
```bash
# 가상 환경 생성
python3 -m venv .venv

# 가상 환경 활성화
source .venv/bin/activate  # macOS/Linux
# 또는
.venv\Scripts\activate  # Windows
```

### 3. Python 패키지 설치
```bash
# 가상 환경이 활성화된 상태에서 실행
pip install -r requirements.txt
```

### 4. Jupyter 커널 등록
```bash
# Jupyter가 가상 환경의 패키지를 인식할 수 있도록 커널 등록
python -m ipykernel install --user --name=dataanalyst --display-name="Python (DataAnalyst)"
```

### 5. Jupyter Notebook 실행
```bash
jupyter notebook
# 또는
jupyter lab
```

**중요**: Jupyter 노트북을 열면 오른쪽 상단에서 **"Python (DataAnalyst)"** 커널을 선택하세요!

### 가상 환경 비활성화
작업을 마친 후:
```bash
deactivate
```

## 포함된 라이브러리

- **pandas**: 데이터 조작 및 분석
- **numpy**: 수치 계산
- **matplotlib**: 데이터 시각화
- **jupyter**: 인터랙티브 노트북 환경

## 기여 방법

1. 이 리포지토리를 포크합니다
2. 새로운 브랜치를 생성합니다 (`git checkout -b feature/AmazingFeature`)
3. 변경사항을 커밋합니다 (`git commit -m 'Add some AmazingFeature'`)
4. 브랜치에 푸시합니다 (`git push origin feature/AmazingFeature`)
5. Pull Request를 생성합니다

## 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다.

