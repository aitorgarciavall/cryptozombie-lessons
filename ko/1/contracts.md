---
title: "컨트렉트"
actions: ['정답 확인하기', '힌트 보기']
material: 
  editor:
    language: sol
    startingCode: |
      pragma solidity //1. 여기에 솔리디티 버전 적기

      //2. 여기에 컨트렉트 생성
    answer: > 
      pragma solidity ^0.4.19;


      contract ZombieFactory {

      }
---

완전 기초부터 시작하기:

솔리디티 코드는 **컨트렉트** 안에 싸여 있지. `컨트렉트`는 이더리움 애플리케이션의 기초 건축 블록으로, 모든 변수와 함수는 어느 한 컨트렉트에 속하게 마련이지. 컨트렉트는 자네의 모든 프로젝트의 시작 지점이라고 할 수 있지. 

비어 있는 `HelloWorld` 컨트렉트는 다음과 같네:

```
contract HelloWorld {

}
```

## Version Pragma

모든 솔리디티 소스 코드는 "version pragma"로 시작해야 하는데, 이는 해당 코드가 이용해야 하는 솔리디티 버전을 선언하는 것이지. 이를 통해 이후에 출시될 컴파일러 버전이 잠재적으로 코드를 깨뜨리는 변화를 가져올 수 있다는 문제를 예방하고자 하는 거지.

선언은 다음과 같이 하면 되네: `pragma solidity ^0.4.19;` (이 코스 집필 시 최신 버전이 0.4.19임).

종합하자면 컨트렉트 초기 뼈대는 다음과 같네. 새로운 프로젝트를 시작할 때마다 이 뼈대를 제일 먼저 작성해야 하지:

```
pragma solidity ^0.4.19;

contract HelloWorld {

}
```

# 직접 해보기

우리의 좀비 군대 생성을 시작하기 위해 `ZombieFactory`라는 기본 컨트렉트를 생성해 보세!

1. 우측 박스에 우리 컨트렉트가 솔리디티 버전 `0.4.19`를 쓸 수 있도록 설정한다. 

2. `ZombieFactory`라는 빈 컨트렉트를 생성한다.

다 마쳤으면 아래 "정답 확인하기"를 클릭하게. 막히는 부분이 있으면 "힌트 보기"를 클릭할 수도 있네. 