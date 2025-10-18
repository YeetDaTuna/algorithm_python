# Algorithm Practice (Python)

알고리즘 문제 풀이 연습 프로젝트

## 환경 요구사항

- Python 3.x
- IntelliJ IDEA (또는 PyCharm)

## 초기 개발환경 설정

### 1. 저장소 클론

```bash
git clone [저장소 URL]
cd algorithm_python
```

### 2. IntelliJ IDEA에서 프로젝트 열기

1. IntelliJ IDEA 실행
2. **File → Open** 선택
3. `algorithm_python` 폴더 선택

### 3. Python 인터프리터 설정

#### 방법 1: 새 가상환경 생성 (권장)

1. **File → Project Structure** (단축키: `Ctrl+Alt+Shift+S`)
2. 왼쪽에서 **Project** 선택
3. **SDK** 드롭다운에서 **Add SDK → Python SDK** 선택
4. **Virtualenv Environment** 선택
5. **New environment** 선택
   - Location: 프로젝트 폴더 내 `venv` 
   - Base interpreter: 시스템에 설치된 Python 선택
6. **OK** 클릭

#### 방법 2: 기존 Python 사용

1. **File → Project Structure** (단축키: `Ctrl+Alt+Shift+S`)
2. 왼쪽에서 **Project** 선택
3. **SDK** 드롭다운에서 **Add SDK → Python SDK** 선택
4. **System Interpreter** 선택
5. 시스템에 설치된 Python 선택
6. **OK** 클릭

#### 빠른 설정 (우측 하단)

1. 우측 하단의 **Python 인터프리터** 클릭
2. **Add New Interpreter → Add Local Interpreter** 선택
3. 위와 동일하게 설정

### 4. 터미널에서 가상환경 활성화 (선택사항)

가상환경을 만들었다면:

**Windows:**
```bash
venv\Scripts\activate
```

**macOS/Linux:**
```bash
source venv/bin/activate
```

### 5. 의존성 설치 (필요한 경우)

```bash
pip install -r requirements.txt
```

현재는 외부 라이브러리를 사용하지 않으므로 기본 Python만으로 실행 가능합니다.


## .gitignore 설정

가상환경과 IDE 설정 파일은 Git에 포함되지 않습니다:
- `venv/` - Python 가상환경
- `.idea/` - IntelliJ IDEA 설정
- `__pycache__/` - Python 캐시 파일
- `*.pyc` - 컴파일된 Python 파일


