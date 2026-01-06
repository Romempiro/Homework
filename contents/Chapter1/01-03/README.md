# 03. 자바 첫 프로그램 만들고 실행하기

## 1. 목표

이 수업의 목표는 다음 한 줄을 **직접 실행해서 화면에 출력**하는 것이다.

```text
Hello, World!
```

이 문장이 정상적으로 출력되면,
- 개발 환경이 정상
- 프로젝트 생성 성공
- 코드 작성 및 실행 성공  
이다.

---

## 2. 새 프로젝트 생성

### 2-1. IntelliJ IDEA 실행

1. IntelliJ IDEA 실행
2. 시작 화면에서 **New Project** 클릭

---

### 2-2. 프로젝트 설정

다음 항목을 **그대로 따라 설정**한다.

- Language: **Java**
- Build System: **Gradle**
- JDK:
  - `Download JDK` 선택
  - 버전: **Java 17** 또는 **Java 21**
- Gradle DSL: **Groovy**
- Project Name: `HelloWorld`
- Location: 원하는 폴더

설정 후 **Create** 클릭

---

## 3. 프로젝트 구조 이해

프로젝트가 생성되면 다음과 같은 구조가 보인다.

```text
HelloWorld
 ├─ src
 │   └─ main
 │       └─ java
 └─ build.gradle
```

중요한 부분만 기억하면 된다.

- **java 폴더**: 우리가 코드를 작성하는 곳
- **build.gradle**: 프로젝트 설정 파일

---

## 4. 패키지 생성

### 4-1. java 폴더에서 패키지 생성

1. `src/main/java` 우클릭
2. `New` → `Package`
3. 패키지 이름 입력

```text
com.example.helloworld
```

4. Enter

---

## 5. Java 클래스 생성

### 5-1. 클래스 생성

1. 방금 만든 패키지 우클릭
2. `New` → `Java Class`
3. 클래스 이름 입력

```text
HelloWorld
```

4. Enter

---

## 6. HelloWorld 코드 작성

생성된 `HelloWorld.java` 파일에  
아래 코드를 **그대로 작성**한다.

```java
package com.example.helloworld;

public class HelloWorld {

    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

---

## 7. 코드 설명 (중요)

학생 기준으로 한 줄씩 설명한다.

```java
public class HelloWorld {
```
- 프로그램의 이름
- 파일 이름과 반드시 같아야 한다

```java
public static void main(String[] args) {
```
- **프로그램이 시작되는 위치**
- Java는 반드시 main 메서드부터 실행된다

```java
System.out.println("Hello, World!");
```
- 화면에 글자를 출력하는 코드
- println → 출력 후 줄 바꿈

---

## 8. 프로그램 실행 방법

### 8-1. 실행 버튼으로 실행

1. 코드 왼쪽에 있는 **초록색 ▶ 버튼 클릭**
2. `Run 'HelloWorld.main()'` 선택

---

### 8-2. 실행 결과 확인

아래쪽 **Run 콘솔 창**에 다음이 출력되면 성공이다.

```text
Hello, World!
```

---

## 9. 실행이 안 될 때 체크 사항

### 9-1. main 메서드가 없는 경우
- `main` 철자 확인
- 중괄호 위치 확인

### 9-2. JDK 설정 문제
- `File → Project Structure`
- Project SDK 확인

---

## 10. 여기까지의 의미

여기까지 성공했다면:

- IntelliJ 설치 완료
- Java 프로젝트 생성 가능
- Java 코드 작성 가능
- 프로그램 실행 가능

즉, **개발 준비 끝**이다.

---

## 11. 정리

- Java 프로그램은 `main`부터 실행
- `System.out.println()`은 출력
- HelloWorld 출력은 모든 언어의 첫 단계
- 이 단계가 이해 안 되면 다음 단계로 가지 않는다


## 다음 강의 
[04. 컴퓨터에서 자료 표현하기](../01-04/README.md)