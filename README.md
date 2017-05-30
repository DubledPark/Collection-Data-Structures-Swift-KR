# Collection Data Structures Swift - KR
Collection Data 스위프트 구조를 소개합니다.좋은 글이라 생각되어 번역합니다. 핵심적인 부분을 제외하고는 번역을 제외하고 의역했습니다. 본문은 [여기](https://www.raywenderlich.com/123100/collection-data-structures-swift-2)를 참고해주세요.

##Introduction
많은 데이터를 처리하는 어플리케이션을 만들고 있을 때를 생각해보세요. 언제 데이터를 넣고 어떻게 그 많은 데이터를 효율적으로 핸들링을 하실 건가요? 
많은 데이터를 처리 할 경우에는 `Array`, `Dictionarys`, `Sets` 에 대한 근본적인 개념을 알고 있는게 중요합니다. 이 `collection data structures` 에 명확한 개념을 가질 경우 처리 속도는 어마어마하게 빨라 질 것 입니다.
#####듀토리얼의 순서는 다음과 같습니다.
1. 데이터 구조에 대해 개념을 가지고, `Big-O`표기법에 대해 배워봅니다.
2. 여러가지 자료구조들에 대해 숙지합니다.
3. 데이터 구조들의 퍼포먼스를 비교해봅니다.
4. 추가의 팁으로 다른 구조들을 조금 더 알아봅니다.

##Getting Started
###What is `Big-O` Notation?

Big-O 표현법은 정확하게 자료를 연산 할 때 시간 그래프를 표현 할 수 있는 방법입니다.
- `O(1)`: 제일 이상적인 퍼포먼스를 보여주는 그래프입니다. 연상의 횟수만큼 실행되는 경우입니다.
-  `O(log n)`: 좋은 퍼포먼스를 보여주는 그래프입니다. 데이터 구조에 있는 아이템만큼 점차적으로 연산의 횟수가 늘어나는 그래프입니다.
-  `O(n)`: 중간 단계의 퍼포먼스를 보여주는 그래프입니다. 데이터 구조랑 연산횟수가 일차함수를 그리며 증가합니다. 
- `O(n (log n))`: 연산횟수가 데이터 구조에 있는 아이템 * 데이터구조 아이템 수만큼 처리합니다. 낮은 단계의 퍼포먼스를 보여주는 그래프입니다.
- `O(n²) `: 데이터구조에 있느나이템수의 제곱만큼 늘어납니다. 여기서 부턴 성능이 매우 떨어지고, 추천하지 않습니다.
- `O(2^n)`: 2의 데이터 구조의 갯수만큼 증가합니다. 매우 나쁜 퍼포먼스를 보여줍니다.
- `O(n!)`: 최악의 케이스입니다. 이렇게 코딩이 될 경우에는 답이 없습니다.

(그래프 추가)



