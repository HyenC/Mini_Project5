# 신용카드 연체 예측 AI      
* [멋쟁이 사자처럼] Mini_Project5
* [DACON 링크] https://dacon.io/competitions/official/235713/overview/description      
* * *
### DATASET
- index `int64`
- gender: 성별 `object`
- car: 차량 소유 여부 `object`
- reality: 부동산 소유 여부 `object`
- child_num: 자녀 수 `int64`
- income_total: 연간 소득 `float64`
- income_type: 소득 분류 `object`     
['Commercial associate', 'Working', 'State servant', 'Pensioner', 'Student']
- edu_type: 교육 수준 `object`      
['Higher education' ,'Secondary / secondary special', 'Incomplete higher', 'Lower secondary', 'Academic degree']
- family_type: 결혼 여부 `object`     
['Married', 'Civil marriage', 'Separated', 'Single / not married', 'Widow']

- house_type: 생활 방식 `object`      
['Municipal apartment', 'House / apartment', 'With parents', 'Co-op apartment', 
'Rented apartment', 'Office apartment']
- DAYS_BIRTH: 출생일 `int64`      
데이터 수집 당시 (0)부터 역으로 셈, 즉, -1은 데이터 수집일 하루 전에 태어났음을 의미
- DAYS_EMPLOYED: 업무 시작일 `int64`      
데이터 수집 당시 (0)부터 역으로 셈, 즉, -1은 데이터 수집일 하루 전부터 일을 시작함을 의미양수 값은 고용되지 않은 상태를 의미함
- FLAG_MOBIL: 핸드폰 소유 여부 `int64`
- work_phone: 업무용 전화 소유 여부 `int64`
- phone: 전화 소유 여부 `int64`
- email: 이메일 소유 여부 `int64`
- occyp_type: 직업 유형 `object`
- family_size: 가족 규모 `float64`
- begin_month: 신용카드 발급 월 `float64`      
데이터 수집 당시 (0)부터 역으로 셈, 즉, -1은 데이터 수집일 한 달 전에 신용카드를 발급함을 의미
- **credit: 사용자의 신용카드 대금 연체를 기준으로 한 신용도 `float64`**      
=> 낮을 수록 높은 신용의 신용카드 사용자를 의미함
* * *
