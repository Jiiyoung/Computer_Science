# Library & Framework

## Library
공통적으로 반복되어 사용되는 기능이나 특정 기능들을 모듈화한 것<br>
프로그램 기능 수행을 위해 활용 가능한 도구의 집합<br>
오로지 의도와 목적성만 존재<br>

## Framework
프레임워크는 뼈대&기반구조가 이미 완성되어 있고 규칙이 존재하는 개발환경을 뜻함<br>

### 사용하는 이유?
프로그램 개발에 투입되는 개발자들이 늘어남에 따라 다양성 또한 늘어나 전체 시스템의 통일성/일관성이 부족<br>
이를 해결하기 위해 개발자의 자유를 제한하는 대신 일정한 테두리 안에서 일관되고 유지보수를 쉽게 할 수 있는 환경인 프레임워크를 도입<br>

### 특징
1. 특정 개념들의 추상화를 제공하는 여러 클래스나 컴포넌트로 구성
2. 개발 편의성의 증가로 시간 단축에 용이
3. 컴포넌트 재사용 가능
4. 오류의 폭 감소
5. 일정부분 코드 품질 보장
6. 유지보수에 용이


### 단점
1. 프레임워크 의존도가 높아지면 개발 능력 저하
2. 개발자의 자유도 저하


## Library와 Framework의 차이
**애플리케이션의 Flow(흐름)을 누가 가지고 있느냐**의 차이<br>
Library는 환경 제한 없이 필요한 기능을 원할 때 가져와서 **능동적으로** 사용하면 된다.<br>
사용자가 애플리케이션 흐름을 직접 제어 가능<br>
<br>
Framework는 전체적인 흐름을 자체적으로 가지고 있어 개발자는 그 안에서 필요한 코드를 작성하면 된다.<br>
애플리케이션 코드는 프레임워크가 짜놓은 틀에서 **수동적으로** 동작해야 한다.<br>
프레임워크에는 분명한 **제어의 역전** 개념이 적용되어 있어야 한다.<br>

#### 간단히 정리하면, 프레임워크는 하나의 집(house)을 의미하고 라이브러리는 필요 시 집에 가져올 수 있는 가구(furniture)들을 의미