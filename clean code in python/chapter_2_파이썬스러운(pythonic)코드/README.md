# Chapter_2 : 파이썬스러운(pythonic) 코드

- 인덱스와 슬라이스
slice의 시작 인덱스는 포함, 끝 인덱스는 제외하고 선택한 구간의 값을 가져온다는 것에 유의.

slice의 (시작, 중지, 간격) 중 하나를 지정하지 않은 경우 None으로 간주됨.

튜플, 문자열, 리스트의 특정 요소를 가져오려고 한다면 for 루프를 돌며 수작업으로 요소를 선택하지 말고 이와 같은 방법을 사용하는 것이 좋다.
