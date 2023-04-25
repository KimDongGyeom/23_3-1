# 팀 프로젝트 ERD-요구사항

## 유저 user[id, email, pwd, nickname, role] 
1. 유저는 여행을 생성한다
2. 유저는 여러개의 여행을 가질 수 있다.

## 여행 travel[id, startDay, clear, planID]
1. 여행은 여러개의 플랜과 목적지로 이루어져있다.

## 플랜 plan[id, title, tag, start, end, city, destination, img, userId]
1. 플랜은 일별 정보 {누가[userId], 언제[start, end], 어디[city, destination] .. 등의 정보를 가진다}
2. 플랜은 여행에 소속된다

## destination 목적지
1. 장소에 대한 정보를 가진다
2. 목적지는 plan에 소속된다
