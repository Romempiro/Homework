# Intellij 설치하기


## 1. IntelliJ IDEA란?

IntelliJ IDEA는 **JetBrains**에서 개발한 통합 개발 환경(IDE)이다.  
주로 **Java, Kotlin, Spring** 개발에 사용된다.

에디션 종류:
- **Community Edition**: 무료, 기본 Java 개발용
- **Ultimate Edition**: 유료, Spring / JPA / 웹 개발 지원

> 학습 목적이라면 **Community Edition**으로 충분하다.

---

## 2. 설치 전 준비 사항

### 2-1. 시스템 요구 사항
- RAM: 최소 8GB 권장
- 저장공간: 최소 2GB 이상
- 운영체제:
  - Windows 10 이상
  - macOS 11 이상
  - Linux (glibc 2.17 이상)

### 2-2. JDK 설치 여부
- 최신 IntelliJ는 **JDK 자동 다운로드 지원**
- 별도 설치 안 해도 됨 (권장)

---

## 3. Windows 설치 방법

### 3-1. 설치 파일 다운로드
1. 웹 브라우저 실행
2. https://www.jetbrains.com/idea 접속
3. **Community Edition** 선택
4. `Download` 클릭

### 3-2. 설치 진행
1. 다운로드한 `ideaIC-xxxx.exe` 실행
2. `Next` 클릭
3. 설치 경로 선택 (기본값 권장)
4. 옵션 선택
   - Create Desktop Shortcut (선택)
   - Add to PATH (선택)
5. `Install` 클릭

### 3-3. 설치 완료
- `Finish` 클릭
- IntelliJ IDEA 실행

---

## 4. macOS 설치 방법

### 4-1. 설치 파일 다운로드
1. https://www.jetbrains.com/idea 접속
2. **Community Edition** 선택
3. macOS 버전 다운로드

### 4-2. 설치 진행
1. 다운로드한 `ideaIC.dmg` 실행
2. IntelliJ IDEA 아이콘을 `Applications` 폴더로 드래그

### 4-3. 실행
- Launchpad 또는 Applications에서 IntelliJ IDEA 실행
- 보안 경고 시 `열기` 선택

---

## 5. Linux 설치 방법 (권장 방식)

### 5-1. JetBrains Toolbox 사용
```bash
sudo snap install intellij-idea-community --classic
```

또는

1. JetBrains Toolbox 다운로드
2. Toolbox 실행
3. IntelliJ IDEA Community 설치

---

## 6. 최초 실행 시 설정

### 6-1. Import Settings
- 처음 설치면 **Do not import settings** 선택

### 6-2. UI 설정
- Theme: Light / Dark 선택
- 기본값 사용 권장

### 6-3. 플러그인
- 기본 플러그인 그대로 사용
- 나중에 필요 시 설치

---

## 7. 새 프로젝트 생성

1. `New Project` 클릭
2. Language: **Java**
3. Build System: **Gradle** 또는 **Maven**
4. JDK: 자동 다운로드 선택
5. `Create` 클릭

---

## 8. 설치 확인 방법

### 8-1. 실행 확인
- IntelliJ IDEA 정상 실행 여부
- 새 프로젝트 생성 가능 여부

### 8-2. JDK 확인
- `File > Project Structure`
- Project SDK 확인

---

## 9. 자주 발생하는 문제

### 9-1. 실행이 안 될 때
- RAM 부족
- 이전 버전 충돌
- 재설치로 해결

### 9-2. 한글 깨짐
- File Encoding UTF-8 확인

---

## 10. 정리

- Community Edition으로 충분
- JDK는 자동 설치 사용
- 기본 설정 유지
- 설치 후 바로 프로젝트 생성해서 테스트



## 3. 다음 강의 
[03. 자바 첫 프로그램 만들고 실행하기](../01-03/README.md)