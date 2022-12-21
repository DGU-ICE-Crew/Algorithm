# PGS 불량사용자
- 221221
## 코드
- 현철 : [현철 풀이](https://github.com/moonn6pence/PS_solutions/blob/master/programmers/%EB%B6%88%EB%9F%89%20%EC%82%AC%EC%9A%A9%EC%9E%90.cpp)
- 용태 : []()
- 상준 : [상준 풀이](https://github.com/sangjun0412/codingTest_base/blob/main/(kakao)%EB%B6%88%EB%9F%89%20%EC%82%AC%EC%9A%A9%EC%9E%90%20.py)
- 진원 : []()
- 원석 : []()
## 핵심
- 백트래킹으로 계산 시에 중복 카운트 제거
## 사고흐름
1. 문자열 처리하므로 정규식 활용가능
2. 카운트인데 모든 경우를 세야하므로 백트래킹이다
3. 백트래킹 진행 도중에 중복을 제거해야하므로, 기록해둘 무언가가 필요함.->비트마스크 or 리스트, 셋 등등