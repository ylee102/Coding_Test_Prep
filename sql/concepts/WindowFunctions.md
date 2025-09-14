Window Functions 쓰기 

## 무엇이냐? 
- Group by 는 한 행을 그룹으로 묶어줌. (Group by + 집계함수) 
- Window function 은 각행의 개별 정보 (Rank 등) 유지하면서, 그룹내의 데이터를 활용해 계산 수행. 
- 집계 함수가 여러 행을 하나로 압축하지만, 윈도우 함수는 각 행 옆에 계산된 값을 추가해서 이어 붙여줌. 
## 언제 쓰냐 ? 왜 쓰냐? 
- Group by 와 다르게 행정보를 유지할 수 있음 
- Rank 나 Avg, 이전, 이후 행과의 비교등 분석을 가능하다. 
- Join 대체가 가능.  
- Partition by, Order by 등과 같이 사용. 

## 어떻게 쓰냐 ? 
- 윈도우 함수(컬럼명) Over ([Parition by 컬럼1], [Order by 컬럼2])
- Partition by 는 데이터를 어떤 기준으로 나눌 지 정해줌 
- Order by 나눈 그룹내 행들의 순서를 정해줌. LAG 나 RANK 처럼 순서 따질 때 씀. 
