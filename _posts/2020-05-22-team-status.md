---
layout: post
title: "Team Status(팀 진행사항)"
date:   2020-05-22 21:50:40 +0200
description : Team Status until now
---

# Team Status<br>

### 5/6 : 팀원 첫 회의, 팀원들의 사용가능언어 공유, OSS Project 탐색 시작
- 팀 배정 후 첫 회의를 시작하였습니다.
- OSS Project를 검색하기 전, 팀원들의 사용가능 프로그램언어를 미리 파악하여, OSS Project 선정과정에서 난이도 조절을 할 수 있도록 하였습니다.
- 5명 모두 c언어를 다룰 수 있어, 먼저 c언어 위주의 프로젝트를 우선으로 탐색하기로 하였고, 파이썬 중심의 프로젝트도 겸해서 탐색하는 것으로 하였습니다.

### 5/9 : 개인별 선정한 OSS Project 공유, 팀 OSS project 선정(Python Games, Minecraft)
- 개인별 선정한 OSS project 공유 및 팀 OSS project 선정을 위한 회의를 진행하였습니다.
- 팀원들이 비교적 쉽게 프로젝트에 기여할 수 있고, 활용도가 높은 프로젝트를 우선으로 하여 선정하였습니다.
- 하지만, 여전히 난이도가 높은 프로젝트라고 판단하여, 일부는 파이썬 언어를 다루지 못하지만, 본 팀이 시도할만 한 좋은 프로젝트가 많은 파이썬 중심 프로젝트로 다시 한번 탐색하기로 하였습니다.

### 5/13 : 팀 OSS project 최종 선정 및 기여 방식 회의
- 파이썬 중심 OSS 프로젝트 탐색 후 선정을 위한 회의를 진행하였습니다.
- 영어를 base로 진행한 word cloud 프로젝트를 한글로도 가능할 수 있도록 기여할 수 있다고 판단, word cloud 프로젝트를 팀 OSS project로 선정하였습니다.
- 혹시나, word cloud 프로젝트에서 더이상 기여할 만한 아이디어가 나오지 않을 경우, Python Games 프로젝트를 추가 기여 프로젝트로 선정하였습니다.
- word cloud 프로젝트에 기여할 만한 부분을 issue, pull-request를 통해 검색하여 더 만들어보기로 하였습니다.

### 5/15 : 해당 OSS project의 기여 방식 회의, 팀 정적 페이지 생성
- word cloud 프로젝트에서 본 팀원들이 기여할 수 있는 방식에 대한 회의를 진행하였습니다.
- 해당 패키지를 한글 font로 진행할 경우, 정상적으로 작동되지만, 단어별이 아닌 띄어쓰기별로 구분하여 작동하는 사실을 인지하였습니다.
- 이는 영어 NLP와 한글 NLP에 큰 차이가 있다는 결론을 도출하였고, 영어 NLP를 활용하고 있는 해당 프로젝트에 한글 NLP를 내재하여야 한다는 결론을 도출하였습니다.
- 대표적인 한글 NLP 패키지인 [konlpy][konlpy] 를 활용하여 tokenization을 진행한 후, word cloud 패키지를 적용하는 방법으로 기여하기로 하였습니다.
- 추가로 wordcloud 본 repository에서 나온 issue들을 면밀히 관찰하여, 팀이 기여할 수 있는 부분을 더 검색하기로 하였습니다.
- 팀 정적 페이지를 생성하여, 주차별로 팀원이 돌아가면서 관리하기로 하였습니다.

### 5/20 : 팀원 역할 배정
- 팀원별 역할을 배정하기 위해 회의를 진행하였습니다.
- 크게 이미 정한 기여방법인 '한글NLP패키지 사용하여 한글버전 만들기'를 포함하여, 'issue 검색 및 해결방안 고안', '정적페이지 관리 및 한글 예제 사용' 등의 프로젝트로 구분하여, 개인별 두 가지 이상씩 소속되어 역할 수행하는 것으로 하였습니다.
 
### 5/21~5/24 : 개인별 활동 진행
- readme, wiki, 정적페이지 관리 및 수정, 추가 진행
- issue 탐색 후 해당 issue에 대한 해결방안에 대하여 팀 [repository][repository]에서 토론 진행
- 미완성 korean version의 wordcloud 코드 commit

[konlpy]: https://github.com/konlpy/konlpy
[repository]: https://github.com/20-1-SKKU-OSS/2020-1-OSS-5/issues/2

