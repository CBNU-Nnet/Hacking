## 포너블 기초 커리큘럼

1. C언어 기초 

   - 문자열 

   * 배열 
   * 포인터 
   * 등.... 

2. BOF 핸드북 (bof_handbook.pdf) 

3. assembly 문서 (asm.pdf) 

4. 달고나 문서 (buffer_overflow_foundation_pub.pdf) 

5. 샤의 공간 문서

6. LoB (Lord of Bufferoverflow)

-------------

2번 먼저 한 후 3번 4번 5번 병행

## 과제

- C언어 기초 
- 리눅스 기본 명령어
- bof 핸드북 병행

기한 : 4월 10일 까지 

* bof 핸드북 
* assembly 문서 
* bof 기초 강좌 
* gdb 사용법 익히기
* 달고나 문서 틈틈히

기한 : 4월 3일 까지 

------------

- 각종 문서 읽으면서 gdb사용법/디버깅 방법 숙지
- 스택구조 파악
- LoB 1번 삽질 (풀면 더 좋음)

기한 : 4월 8일까지

------

- LoB 다 풀기
  - 라이트업

기한 :  5월 8일 까지

--------

- pwnable.kr 회원가입
- pwnable.kr fd
- pwnable.kr bof

기한 : 5월 22일 까지

----

## 문서

* BOF 기초 강좌 모음 

  - https://www.hackerschool.org/HS_Boards/data/Lib_system/dotri.txt

  * <https://www.hackerschool.org/HS_Boards/data/Lib_system/lamagra.txt>

* 블랙펄 문서

  * 우리집에 GDB 있는데… 메모리 보고갈래?
    * https://bpsecblog.wordpress.com/2016/03/08/gdb_memory_1/
    * <https://bpsecblog.wordpress.com/2016/04/04/gdb_memory_2/>
    * <https://bpsecblog.wordpress.com/2016/05/20/gdb_memory_3/>

* 샤의 공간

  * [기초](https://shayete.tistory.com/entry/1-%EC%8B%9C%EC%8A%A4%ED%85%9C-%ED%95%B4%ED%82%B9%EC%9D%B4%EB%9E%80-linux-%EA%B8%B0%EC%B4%88%EB%AA%85%EB%A0%B9%EC%96%B4-vim-%EB%AA%85%EB%A0%B9%EC%96%B4-%EC%82%AC%EC%9A%A9%EB%B2%95 )
  * [gdb명령어](<https://shayete.tistory.com/entry/2-Stack-Corruption-gdb-%EB%AA%85%EB%A0%B9%EC%96%B4?category=857069>)
  * [어셈 및 핸드레이](<https://shayete.tistory.com/entry/3-%ED%95%B8%EB%93%9C%EB%A0%88%EC%9D%B4-%EA%B8%B0%EB%B3%B8-%EC%96%B4%EC%85%88%EB%B8%94%EB%A6%AC-%EB%AA%85%EB%A0%B9%EC%96%B4?category=857069>)
  * [RTL](<https://shayete.tistory.com/entry/4-Return-to-Library-RTL?category=857069>)

- LoB (Lord of Bufferoverflow)
  - <https://www.hackerschool.org/HS_Boards/zboard.php?id=HS_Notice&no=1170881885>
  - [Lob Tips (풀기 전 알아야 할 것들)](<https://intadd.tistory.com/106>)
  - [기초에 심하게 충실한 LoB 풀이](<https://conchiholic.github.io/wargame/lob/2018/08/02/LOB_1_1.html>)
  - 쉘코드
    - "\x31\xc0\x50\xba\x2e\x2e\x72\x67\x81\xc2\x01\x01\x01\x01\x52\xb9\x2e\x62\x69\x6e\x83\xc1\x01\x51\x89\xe3\x50\x53\x89\xe1\x89\xc2\xb0\x0b\xcd\x80"
- 함수 프롤로그 & 에필로그 & 스택프레임 & 호출규약
  - http://woosunbi.tistory.com/attachment/cfile10.uf@2513A04B56EE7B9A248C70.pdf
  - <https://shotgh.tistory.com/33>
  - <https://phaphaya.tistory.com/25>
  - <https://harin-luna.tistory.com/entry/%ED%95%A8%EC%88%98-%ED%94%84%EB%A1%A4%EB%A1%9C%EA%B7%B8Prolog-%EC%97%90%ED%95%84%EB%A1%9C%EA%B7%B8Epilog>
  - <https://wlgns595919.tistory.com/5>
- 메모리 보호기법 정리
  - <https://bpsecblog.wordpress.com/memory_protect_linux/>

## 환경 세팅

**포너블 문제 풀이 환경 세팅**

- ubuntu 16.04 서버 64비트
  - vm / 클라우드 / 개인서버 / 동아리 서버 등 아무거나 편한 걸로
- python2 + pwntools
  - pip install pwntools
  - <https://github.com/Gallopsled/pwntools>
- xshell + lrzsz
  - sz와 rz를 쓰면 xshell 을 통해 파일을 자유롭게 업로드/다운로드 할 수 있음.
  - 설치 : apt update && apt install lrzsz

---

## 방학 때 할 것들

- rop 연습 (대회 문제 풀기)
   - ropasaurusrex 풀기
   - angry doraemon
 - pwnable.kr
   - fd, bof
   - horcruxes
   - simple login
   - brain fuck
   - md5 calc
   - echo1
   - ascii easy
   - toodler's bottle 5개 이상 풀기

- root-me.org
  - system crack 문제 순차적으로 쭉 풀면됨