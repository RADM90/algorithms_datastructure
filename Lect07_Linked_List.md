# 7강: 연결 리스트 (Linked List) (1)

데이터 원소들을 순서를 지어 늘어놓는다는 점에서 선형 배열(Linear Aray)과 비슷하지만, 원소를 늘어놓는 방식이 "번호가 붙여진 칸에 원소들을 채워넣는" 방식이 아닌 "각 원소들을 줄줄이 엮어서" 관리하는 방식이라는 점에서 차이가 있음.

가운데에서 끊어 하나를 삭제하거나, 아니면 가운데를 끊고 그 자리에 다른 원소를 (원소들을) 삽입하는 것이 선형 배열의 경우보다 쉬움 (빠른 처리가 가능)
선형 배열에 비해서 데이터 구조 표현에 소요되는 저장 공간 (메모리) 소요가 큼 (링크 또한 메모리에 저장되어 있어야 하므로, 연결 리스트를 표현하기 위해서는 동일한 데이터 원소들을 담기 위하여 사용하는 메모리 요구량이 많음)

또한 "k 번째의 원소" 를 찾아가는 데에는 선형 배열의 경우보다 시간이 오래 걸림.


 "단방향 연결 리스트 (singly linked list)" 를 추상적 자료 구조로 정의하고, 이 추상적 자료 구조에 가할 수 있는 아래와 같은 연산 구현
- 특정 원소 참조 (k 번째)
- 리스트 순회 (list traversal)
- 길이 얻어내기

