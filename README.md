
# TABLE FOOD

1. PRIMARY KEY (food_pk)
2. 음식의 이름 (food_name)
3. 그람 별 칼로리 (food_calorie)
4. 단위의 이름 (예: 개, 인분, 횟수...) (food_metricname)
5. 1단위의 그람수 (food_metricgrams)
6. 음식의 대분류 (EX. 구이, 국...) (food_category)
7. 그람 당 탄수화물 (food_carb)
8. 그람 당 지방 (food_fat)
9. 그람 당 단백질 (food_protein)
10. 그람 당 나트륨 (food_sodium)



# TABLE USER
1. PRIMARY KEY (USER_ID)
2. 나이 (USER_AGE)
3. 키 (USER_HEIGHT)
4. 몸무게 (USER_WEIGHT)
5. 성별 (USER_GENDER)
6. 현재 목표 칼로리수 (USER_CAL_GOAL)




# TABLE RECORD
1. PRIMARY KEY (RECORD_ID)
2. 날짜 (RECORD_DATE)
3. 먹은 음식 (RECORD_FOOD_ID)
4. 먹은 양 (RECORD_FOOD_AMOUNT)


# METHOD
1. 사용자 정보 입력 -> DB 입력후 목표 칼로리 계산 -> 모든 정보 저장
2. 목표 칼로리 수정 기능
3. 음식 정보 확인
4. 음식 정보 수정 및 추가
5. 식단 기록 추가 및 수정
6. 기록된 식단 보여주기 (아침/ 점심/ 저녁으로 구별; 먹은 칼로리와 남은 칼로리 표시)
7. 날짜 별 기록 선택
