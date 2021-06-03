# ToBinary
마인크래프트 BE 전용 애드온으로,
모든 엔티티의 점수를 이진법화 합니다.

## 명령어
`function bin.setup` : 필요한 스코어보드를 생성합니다.
`function bin.printMyScore` : 나의 점수를 출력합니다. (나에게만 보임)
`function bin.printMyScoreAll` : 나의 점수를 출력합니다. (모두에게 보임)

## 스코어보드 목록
`binIn` : 점수를 입력하는 스코어보드입니다.
`binBit<number>` : 결과값의 <number>번째자리입니다.
  
## 사용 방법
`binIn` 스코어보드에 자신이 원하는 점수를 입력하면 이진법으로 계산이 됩니다.
커맨드 예시: `/scoreboard players @s binIn 23`

***단, 위에서 말했듯, 엔티티만 적용됩니다***
