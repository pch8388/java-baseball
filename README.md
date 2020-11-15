# 숫자 야구 게임
## 진행 방법
* 숫자 야구 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 과제를 제출한다.

## 과제 제출 과정
* [과제 제출 방법](https://github.com/next-step/nextstep-docs/tree/master/precourse)

## 요구사항 정의
### 도메인 요구사항
- [x] 문제 출제자는 임의의 3개의 숫자를 선택한다
    - [x] 숫자는 중복 금지
    - [x] 세자리 숫자인지 확인
        - [x] 숫자 형식이 맞는 지 확인
        - [x] 세자리가 맞는 지 확인
- [x] 정답자는 입력받은 3개의 숫자를 제출한다
    - [x] 숫자는 중복 금지
        - [x] 세자리 숫자인지 확인
            - [x] 숫자 형식이 맞는 지 확인
            - [x] 세자리가 맞는 지 확인
- [x] 출제자가 정한 숫자와 입력한 숫자의 일치도 확인
    - [x] 스트라이크 여부 판단
    - [x] 볼 여부 판단
    - [x] 낫싱 여부 판단
- [x] 결과메시지 생성
- [x] 3 스트라이크라면 이번 게임을 종료
### IO 요구사항
- [x] 세자리 숫자의 입력을 받는다
    - [x] 숫자가 아닌 값 포함 여부 확인
    - [x] 세자리의 수가 맞는 지 확인
- [x] 사용자에게 야구게임의 결과를 보여준다
    - [x] 결과 출력
    - [x] 3 스트라이크라면 게임 재진행 여부를 확인
        - [x] 재진행 시 다음 회차의 게임 시작
        - [x] 게임종료시 프로그램 종료
            - [x] 프로그램 종료
            - [x] 종료 메시지 출력
