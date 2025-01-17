# Implementation (구현)

[메인으로 돌아가기](https://github.com/kiiimes/algorithm-study)

풀어보면 좋을 문제는 추천 문제에 체크(:heavy_check_mark:) 해놨습니다.

추천 문제 아닌 나머지는 나머지를 난이도 섞었습니다.

시뮬레이션 관련 문제는 시뮬레이션에 있습니다.

(매우 [단순한 구현](https://www.acmicpc.net/problem/1000)는 추가하지 않았습니다.)

<br>

***❗️❗️꼭 문제를 순서대로 안풀어도 됩니다.❗️❗️***

[백준 문제집](https://www.acmicpc.net/workbook/view/6783)
|          순번          |        문제 번호         |        문제 이름         |         난이도          |        은숙         |
| :-----: | :-----: | :-----: | :-----: | :-----: |
| 00 | <a href="https://www.acmicpc.net/problem/21608" target="_blank">21608</a> | <a href="https://www.acmicpc.net/problem/21608" target="_blank">상어 초등학교</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/10.svg"/> |  |
| 01 | <a href="https://www.acmicpc.net/problem/21611" target="_blank">21611</a> | <a href="https://www.acmicpc.net/problem/21611" target="_blank">마법사 상어와 블리자드</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/15.svg"/> |                      |
| 02 | <a href="https://www.acmicpc.net/problem/2753" target="_blank">2753</a> | <a href="https://www.acmicpc.net/problem/2753" target="_blank">윤년</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/2.svg"/> |  |
| 03 |  <a href="https://www.acmicpc.net/problem/1212" target="_blank">1212</a> | <a href="https://www.acmicpc.net/problem/1212" target="_blank">8진수 2진수</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/3.svg"/> |  |
| 04 | <a href="https://www.acmicpc.net/problem/20053" target="_blank">20053</a> | <a href="https://www.acmicpc.net/problem/20053" target="_blank">최소, 최대 2</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/3.svg"/> |✅|
| 05 | <a href="https://www.acmicpc.net/problem/5597" target="_blank">5597</a> | <a href="https://www.acmicpc.net/problem/5597" target="_blank">과제 안 내신 분..?</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/4.svg"/> |✅ |
| 06 | <a href="https://www.acmicpc.net/problem/21918" target="_blank">21918</a> | <a href="https://www.acmicpc.net/problem/21918" target="_blank">전구</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/4.svg"/> | ✅|
| 07 | <a href="https://www.acmicpc.net/problem/20546" target="_blank">20546</a> | <a href="https://www.acmicpc.net/problem/20546" target="_blank">🐜 기적의 매매법 🐜</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/5.svg"/> |  |
| 08 | <a href="https://www.acmicpc.net/problem/14467" target="_blank">14467</a> | <a href="https://www.acmicpc.net/problem/14467" target="_blank">소가 길을 건너간 이유 1</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/6.svg"/> | ✅|
| 09 | <a href="https://www.acmicpc.net/problem/2578" target="_blank">2578</a> | <a href="https://www.acmicpc.net/problem/2578" target="_blank">빙고</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/6.svg"/> | ✅ |
| 10 | <a href="https://www.acmicpc.net/problem/4396" target="_blank">4396</a> | <a href="https://www.acmicpc.net/problem/4396" target="_blank">지뢰 찾기</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/6.svg"/> |✅ |
| 11 | <a href="https://www.acmicpc.net/problem/1913" target="_blank">1913</a> | <a href="https://www.acmicpc.net/problem/1913" target="_blank">달팽이</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/> |✅ |
| 12 | <a href="https://www.acmicpc.net/problem/12933" target="_blank">12933</a> | <a href="https://www.acmicpc.net/problem/12933" target="_blank">오리</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/> | |
| 13 | <a href="https://www.acmicpc.net/problem/1244" target="_blank">1244</a> | <a href="https://www.acmicpc.net/problem/1244" target="_blank">스위치 켜고 끄기</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/> |  |
| 14 | <a href="https://www.acmicpc.net/problem/10994" target="_blank">10994</a> | <a href="https://www.acmicpc.net/problem/10994" target="_blank">별 찍기 - 19</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/> |  |
| 15 | <a href="https://www.acmicpc.net/problem/20436" target="_blank">20436</a> | <a href="https://www.acmicpc.net/problem/20436" target="_blank">ZOAC 3</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/> |  |
| 16 | <a href="https://www.acmicpc.net/problem/20291" target="_blank">20291</a> | <a href="https://www.acmicpc.net/problem/20291" target="_blank">파일 정리</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/> |  ✅|
| 17 | <a href="https://www.acmicpc.net/problem/17413" target="_blank">17413</a> | <a href="https://www.acmicpc.net/problem/17413" target="_blank">단어 뒤집기 2</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/> | ✅ |
| 18 | <a href="https://www.acmicpc.net/problem/22858" target="_blank">22858</a> | <a href="https://www.acmicpc.net/problem/22858" target="_blank">원상 복구 (small)</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/> |                ✅      |
| 19 | <a href="https://www.acmicpc.net/problem/2615" target="_blank">2615</a> | <a href="https://www.acmicpc.net/problem/2615" target="_blank">오목</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/> |                      |
| 20 | <a href="https://www.acmicpc.net/problem/17276" target="_blank">17276</a> | <a href="https://www.acmicpc.net/problem/17276" target="_blank">배열 돌리기</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/> |                      |
| 21 | <a href="https://www.acmicpc.net/problem/16926" target="_blank">16926</a> | <a href="https://www.acmicpc.net/problem/16926" target="_blank">배열 돌리기 1</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/> | |
| 22 | <a href="https://www.acmicpc.net/problem/15787" target="_blank">15787</a> | <a href="https://www.acmicpc.net/problem/15787" target="_blank">기차가 어둠을 헤치고 은하수를</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/> |  |
| 23 | <a href="https://www.acmicpc.net/problem/20207" target="_blank">20207</a> | <a href="https://www.acmicpc.net/problem/20207" target="_blank">달력</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/10.svg"/> |  |
| 24 | <a href="https://www.acmicpc.net/problem/20164" target="_blank">20164</a> | <a href="https://www.acmicpc.net/problem/20164" target="_blank">홀수 홀릭 호석</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/> |                      |
| 25 | <a href="https://www.acmicpc.net/problem/14719" target="_blank">14719</a> | <a href="https://www.acmicpc.net/problem/14719" target="_blank">빗물</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/> | |
| 26 | <a href="https://www.acmicpc.net/problem/16719" target="_blank">16719</a> | <a href="https://www.acmicpc.net/problem/16719" target="_blank">ZOAC</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/> |                      |
| 27 | <a href="https://www.acmicpc.net/problem/22856" target="_blank">22856</a> | <a href="https://www.acmicpc.net/problem/22856" target="_blank">트리 순회</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/> |                      |
| 28 | <a href="https://www.acmicpc.net/problem/22860" target="_blank">22860</a> | <a href="https://www.acmicpc.net/problem/22860" target="_blank">폴더 정리 (small)</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/13.svg"/> |                      |
| 29 | <a href="https://www.acmicpc.net/problem/22859" target="_blank">22859</a> | <a href="https://www.acmicpc.net/problem/22859" target="_blank">HTML 파싱</a> | <img height="25px" width="25px" src="https://static.solved.ac/tier_small/13.svg"/> |                      |
