# Coding_Test_Prep
Coding_Test_Prep
Repository to prepare for coding test 
포괄적인 커밋 메시지 규칙

[유형]은 커밋의 목적을 한눈에 알 수 있게 해줍니다.

(영역)은 커밋이 적용된 프로젝트의 특정 부분을 나타냅니다.

간단한 설명은 커밋이 무엇을 했는지 요약합니다.

커밋 유형 (Type) 문자 그대로 커밋이 어떤 변경 사항을 담고 있는지 알려줍니다. 다음과 같은 유형들을 활용해 보세요.
feat: 새로운 기능 추가 (예: feat(dp): 새로운 동적 계획법 문제 풀이 추가)

fix: 버그 수정 (예: fix(sql): 203번 문제 쿼리 오류 수정)

docs: 문서 수정 (예: docs(concepts): JOIN 개념 정리 파일 업데이트)

style: 코드 포맷팅, 세미콜론 누락 등 (예: style(python): PEP8 규칙에 따라 코드 포맷팅)

refactor: 코드 리팩토링 (예: refactor(hash): 해시 충돌 방지 로직 개선)

test: 테스트 코드 추가 또는 수정 (예: test(bfs): BFS 테스트 케이스 추가)

chore: 빌드 시스템 변경, 라이브러리 업데이트 등 (예: chore(git): 커밋 템플릿 추가)

영역 (Scope) 커밋이 영향을 미치는 범위를 지정합니다. 폴더 이름이나 알고리즘 유형을 사용하면 좋습니다.
SQL: sql, join, window-function

알고리즘: dfs, bfs, dp, greedy, sort

자료구조: array, stack, queue, hash-table

폴더: concepts, leetcode, programmers

메시지 본문 (Body) 필수는 아니지만, 복잡한 변경 사항을 설명할 때 유용합니다. 첫 번째 줄에 한 칸 띄고 상세 내용을 작성합니다.
feat(dp): 2차원 배열 동적 계획법 문제 풀이 추가

O(N^2) 시간 복잡도를 가지는 풀이법 작성
Memoization 기법을 활용하여 성능 최적화 커밋 메시지 작성 예시 feat(sql): LeetCode 175번 LEFT JOIN 풀이 추가
fix(algorithm): 242번 문제 파이썬 솔루션 로직 오류 수정

docs(concepts): 윈도우 함수 개념 설명 보강

refactor(bfs): 큐(queue) 구현을 deque로 변경