# INF-1: Infrastructure TW Hbaek

1. 결정 추적을 위해 네이밍 정리

2. 필히 기록해야하는 시간

Date: 2022-04-27

## Status

1. 상태값

신청

## Context

1. 목표는 무엇인가?  해결해야하는 문제는 무엇인가? 결정기록은 이러한 상황에 대한 요약을 제공해야 한다.
그렇게 하면 결정의 근거와 기록의 업데이트가 필요한 이유를 이해할 수 있다.

2. 결정을 내릴수 있는 선택지가 없다면 좋은 결정이 아니다. 좋은 결정 기록은 선택지가 무엇인지 이해하는데 도움이 되어야 한다. 이는 결정이 내려진 시점의 상황과 '선택공간'을 이해하는데 도움이 된다.



## Decision
1. 결정의 핵심은 선택이다. 모든 결정 기록은 선택한 사항을 문서화 해야한다.
2. 결정에는 그에 따른 결과가 있으며 중요한 내용은 결정기록에 문서화되어야 한다. 장단점은 무엇인가? 우리의 선택은 우리가 일하는 방식이나 내려야 할 다른 결정에 어떤 영향을 미치는가?

## Consequences
결과
No human operator infrastructure changes will be allowed. We'll need to invest in specialized tools and a language to treat infrastructure changes as code. Making changes will take longer than if we were to use a console or CLI. 테스트 분기
