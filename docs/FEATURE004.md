## 📝 기능 목록
1. 입력 값에 대한 예외처리
> - 입력된 문자열의 길이 체크 : 1 이상, 1,000 이하

2. 문자열 word가 매개변수로 주어질 때, 입력받은 문자열을 청개구리 사전을 참고해 반대로 변환하여 return.
> - 입력받은 문자열을 List로 분리하는 함수 제작
> - 청개구리 사전 중, 알파벳 대문자 : 알파벳 대문자 A ~ Z를 Key로 하고, 역순으로 알파벳 대문자 Z ~ A를 Value로 하는 사전용 Map 생성하는 함수 제작
> - 청개구리 사전 중, 알파벳 소문자 : 알파벳 소문자 a ~ z를 Key로 하고, 역순으로 알파벳 소문자 z~ a를 Value로 하는 사전용 Map 생성하는 함수 제작
> - 알파벳 여부 및 알파벳 대소문자 판단은 정규식 이용
> - 입력받은 문자열을 청개구리 사전을 참고해 반대로 변환하기. 단, 스페이스(공백) 및 알파벳이 아닌 문자는 바로 결과를 담을 StringBuffer에 추가한다.