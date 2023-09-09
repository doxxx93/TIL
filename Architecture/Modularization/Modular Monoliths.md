2023-09-10 03:37
Status: #Idea
Tags:

# Modular Monoliths

[GOTO 2018, Simon Brown - Modular Monoliths](https://youtu.be/5OjqD-ow8GE)

모듈형 모놀리스는 코드를 모듈 개념으로 구조화하는 아키텍처이다.

전통적인 모놀리식 아키텍처와 모듈화된 아키텍처 사이에 존재하는 아키텍처이다.

다음과 같은 특징과 장점을 갖는다.

1. 모듈화: 어플리케이션은 여러 모듈로 나뉘어져있으며, 각 모듈은 특정 기능 또는 역할을 수행한다. 코드의 유지보수와 확장을 용이하게 한다.
2. 단일 코드베이스: 하나의 코드베이스를 유지한다. 모듈간의 의존성을 관리하기 쉽게 만든다.
3. 단일 배포 단위

마이크로서비스 아키텍처로의 전환을 고려하는 중간 단계로서의 대안으로 고려되기도 한다.

## 종류

내가 아는 모듈러 모놀리식 아키텍처를 구현하는 방식에는 다음과 같은 3가지가 있다.

- [Gradle Multi-Project Builds](https://docs.gradle.org/current/userguide/intro_multi_project_builds.html) - 그레이들 멀티 프로젝트 - 멀티 모듈

- [스프링 모듈리스](https://spring.io/projects/spring-modulith) - 단일 스프링 컨테이너에서 논리적 모듈을 구성

- 다중 스프링 컨테이너 - [박용권님의 우아한 모노리스](https://github.com/arawn/building-modular-monoliths-using-spring)

---

# References
