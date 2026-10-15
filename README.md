# 코덱스 리셋 예보

ChatGPT·Codex 사용량 100% 리셋이 언제 올지 예보하는 한 페이지짜리 사이트입니다.

- 리셋 기록은 [Codex Resets](https://codex-resets.com) 공개 API(`/api/v1/resets`)에서 페이지를 열 때마다 새로 받아옵니다. API를 쓸 수 없을 때는 `index.html` 안에 저장된 기록으로 표시합니다.
- 원본 데이터는 OpenAI Codex 팀 Tibo([@thsottiaux](https://x.com/thsottiaux))의 X 게시물입니다.
- 예보는 최근 리셋에 더 큰 비중(반감기 30일)을 두고 리셋 간격을 로그정규 분포로 맞춘 결과입니다. OpenAI 공식 일정이 아닙니다.

Data from <a href="https://codex-resets.com">Codex Resets</a>
