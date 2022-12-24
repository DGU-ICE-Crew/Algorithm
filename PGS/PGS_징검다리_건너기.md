# PGS 징검다리 건너기
- 221224
## 코드
- 현철 : [PGS 불량 사용자](https://github.com/moonn6pence/PS_solutions/blob/master/programmers/%EC%A7%95%EA%B2%80%EB%8B%A4%EB%A6%AC%20%EA%B1%B4%EB%84%88%EA%B8%B0.cpp)
- 용태 : [PGS 불량 사용자](https://github.com/smc2315/algorithm/blob/main/PGS/%EC%A7%95%EA%B2%80%EB%8B%A4%EB%A6%AC%20%EA%B1%B4%EB%84%88%EA%B8%B0.cpp)
- 상준 : []()
- 진원 : []()
- 원석 : []()
## 핵심
- 방법이 여러가지임
  - union-find + 우선순위 큐
  - sliding window + multiset
  - 이분탐색
- 이분탐색 떠올리는 방법(관점 전환)
- logN으로 최대, 최소 구할 때 multiset 활용
## 사고흐름1 - 이분탐색 방식
1. 징거다리의 크기가 아닌 사람 수 기준으로 관점을 전환
2. 이분탐색하면서 연속적으로 건널 수 있는지 없는지 체크하면서 mid 조절
## 사고흐름2 - 우선순위 큐 + union-find
1. 작은 징검다리 순서대로 0이 되므로 우선순위 큐 사용
2. 우선순위 큐에서 pop된 돌들이 연속적으로 k개 모이면 못 건너므로 union-find 사용해서 카운트
