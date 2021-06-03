# ToBinary
마인크래프트 BE 전용 애드온으로, 모든 엔티티의 점수를 이진법화 합니다.

## 명령어
- `/function bin.setup` : 함수 실행에 필요한 스코어보드를 생성합니다.
- `/function bin.printMyScore` : 나의 점수를 출력합니다. (나에게만 보임)
- `/function bin.printMyScoreAll` : 나의 점수를 출력합니다. (모두에게 보임)

## 스코어보드 목록
- `bin` : 계산할 대상이 포함된 스코어보드입니다.
- `binBit<number>` : 결과값의 `<number>`자리입니다.
  
### 스코어보드 저장 방식
![저장방식](https://user-images.githubusercontent.com/84027019/120663384-ef28e180-c4c4-11eb-92fd-01d948c08ab2.png)
  
## 태그 목록
해당 애드온을 이용한 커맨드 작업에 도움이 되기 위한 태그들입니다.

### 부호태그
- `isPlus` : 입력된 값이 양수 또는 0이면 붙여집니다.
- `isMinus` : 입력된 값이 음수이면 붙여집니다.
- `hasOne<number>` : `<number>`자리가 1이면 붙여집니다.
  
## 사용 방법
1. 마인크래프트 월드내에서 `/function bin.setup`을 입력합니다.
2. `bin` 스코어보드에 자신이 원하는 점수를 입력하면 이진법으로 계산이 됩니다.
커맨드 예시: `/scoreboard players @s bin 23`
3. 값 출력은 위의 명령어를 참고해주세요. (actionbar로 출력됩니다.)
