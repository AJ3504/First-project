# 맛잘알 녀석들 [오날엔]

스파르타코딩클럽 6기_React / 23.05.08 ~ 23.05.12 / first project

## 팀원

| 팀원   | 스택         | 팀원구분 | 깃허브                                      | 
| ------ | ------------ | -------- | ------------------------------------------- | 
| 이지은 | `프론트엔드` | `팀장`   | [JellyBear97](https://github.com/JellyBear97)     | 
| 김선아 | `프론트엔드` | 팀원     | [sunny-kim111111](https://github.com/sunny-kim111111) |      
| 박지혜 | `프론트엔드` | 팀원     | [jeehyeeee](https://github.com/jeehyeeee) |         |
| 이다혜 | `프론트엔드`     | 팀원     | [leejoys-lab](https://github.com/leejoys-lab)     | 
| 이안진 | `프론트엔드`     | 팀원     | [AJ3504](https://github.com/AJ3504)     | 

## 목차

-   [1. 프로젝트 소개](#1-프로젝트-소개)
-   [2. 프로젝트 시연 영상](#2-프로젝트-시연-영상)
-   [3. 프로젝트 주소](#3-프로젝트-주소)
-   [4. 프로젝트 S.A](#4-프로젝트-sa)
-   [5. 기술스택](#5-기술스택)
-   [6. 사용한 라이브러리](#6-사용한-라이브러리)
-   [7. API Table](#7-api-table)
-   [8. 구현기능](#8-구현-기능)

## 1. 프로젝트 소개

[오날엔]은 ‘오늘의 날씨엔?’의 줄임말로, 오늘의 날씨(맑음/흐림/비옴/눈옴)에 따라 음식을 추천해주는 웹사이트입니다.

로그인을 하고 ‘음식 추천하기’ 폼을 작성하면, 카테고리별로 포스팅됩니다.

포스팅된 글은 날씨별/음식 종류별로 확인할 수 있습니다.

## 2. 프로젝트 시연 영상

[유튜브 링크](https://www.youtube.com/watch?v=1D28YUxfV14)

## 3. 프로젝트 주소

[배포 일시 중지]

## 4. 프로젝트 S.A
* 초안
https://docs.google.com/presentation/d/13UxMs-f0XtIC67JiRo-EThHj2hmAyObDc222OMGFfOw/edit?usp=sharing
* 최종
['오날엔' notion](https://www.notion.so/d9abce7c5aa648058b12e02fcec8d163?pvs=4)

## 5. 기술스택
  * Javascript
  * html/css
  * Python
  * MongoDB

## 6. 사용한 라이브러리
  * JQuery
  * Bootstrap
  * Flask
  * Bs4
  * Pymongo
  * MongoDB

## 7. API Table

| Number | Method | URL                                   | Description     | Request                                                      | Response                                                     |
| ------ | ------ | ------------------------------------- | --------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1      | `POST` | /api/sign_in                          | 회원가입          | {id, pw} | | 
| 2      | `POST` | /api/login                            | 로그인           | {id, pw}  | |                                
| 3      | `GET`  | /api/login                            | 로그인 정보 조회    |                   |                                                              
| 4      | `GET`  | /api/foodlist                             | 게시물 전체목록 조회          |                       |                                                              
| 5      | `GET`  | /api/cate-{weather}-all                         | 날씨 카테고리별 목록 조회   |                     |
| 6      | `GET`  | /api//cate-{weather}-foodtype                          | 날씨+foodtype 카테고리별 목록 조회  |  | 
| 7      | `POST` | /api/foodlist                            | 게시물 작성   | {body: formData}
{weather, foodtype, menu, img, comment} |
| 8      | `GET`  | /api/categories                       | 게시물 조회 | {p_id} || 
| 9      | `PUT`  | /api/post?category_id=카테고리 아이디 | 게시물 수정      |  {body: formData}
{p_id, weather, foodtype, menu, img, comment}                       ||
| 10     | `DELETE`| /api/post?category_id=카테고리 아이디 | 게시물 삭제      | {p_id}             | |
| 11     | `POST` | /api/post?category_id=카테고리 아이디 | 댓글 등록      | {body: formData}
{p_id, name, comment}                                 | |
| 12     | `GET`  | /api/post?category_id=카테고리 아이디 | 댓글 조회      | {p_id, c_id}   |  |
| 12     | `DELETE`  | /api/post?category_id=카테고리 아이디 | 댓글 삭제      | {p_id, c_id}   |  |

## 8. 구현 기능

### 1) 로그인 화면


### 2) 홈 화면

### 3) 게시글 입력 FORM

### 4) 게시글 모달창

