#LAB 5 - Lecture Note   
###202434610 박세하   

---

1. Standard Output : 보이게 되는 screen. 부등호 기호인 > 를 통해 파일에 아웃풋을 저장 할 수 있다. 
  - ex) words.txt > sorted_words.txt : words.txt에 명령어를 입력 한 결과를 sorted_words.txt에 저장
  - 커맨드 cat 을 통해 지정 파일로 아웃풋이 저장됨.
  - 기호 >> 를 통해 명령어의 결과를 파일에 추가함.

   
2. Standard Input : 키보드로 입력. 기호 < 를 통해 파일의 내용을 명령어로 사용하게 됨.
  - ex) sort < word.txt : word.txt 의 내용을 sort 명령어를 사용하여 정렬함.

   
3. | (pipelines) : 명령어를 단계별로 적용 할 수 있는 기호. 나가기 키는 q.   

   
4. Expansion : 특정한 명령어에서 특정한 의미로 확장 되는 것.   
ex) echo (다음 올 텍스트를 그대로 출력함.)     
* : 현재 디렉토리의 모든 파일 출력   
~ : 홈 디렉토리 출력   
\ : 긴 명령어로 인한 줄바꿈 기능

   
5. Permissions : -rwxrwxrwx = owner(소유자) / group(속한 그룹) / others(나머지 사용자)   
  - -기호 : 파일 종류, -은 일반폴더, d는 디렉토리
  - 첫 rwx : 파일 소유자의 읽기 - 쓰기 - 수행 권한
  - 두번째 rwx : group owner의 읽기 - 쓰기 - 수행 권한
  - 세번째 rwx : 모든 유저의 읽기 - 쓰기 - 수행 권한
  - 뒤따라 출력되는 단어 2개는 각각 owner,group

   
6. chmod : 권한 바꾸는 명령어 ex) chmod-숫자-파일      
  - 777 : 모든 범위에게 모든 권한
  - 755 : 소유자 모든권한, 나머지는 쓰기 권한 X
  - 700 : 소유자 모든권한, 나머지 모든 권한 X
  - 666 : 모든 유저는 읽기,쓰기 권한 X
  - 644 : 소유자 읽기 쓰기, 나머지 읽기만
  - 600 : 소유자 읽기 쓰기, 나머지 모든 권한 X

     
7. Superuser : 시스템 관리자 권한을 모두 가진 유저
  - sudo 라는 키워드 입력 후 사용하고자 하는 커맨드 입력

   
8. Text Editors : CLI는 키보드로만, GUI는 마우스도 같이 사용 가능
  - vi,vim (CLI) : 가장 많이 사용
  - nano (CLI) : 사용자 편의성
  - gedit(GUI) : 대표적인 GUI 텍스트 에디터
  - kwrite(GUI) : GUI 텍스트 에디터

   
9. Shell Script : 미리 입력할 명령어 저장해놓고 Text Editor를 통해 실행 ex) sh + (스크립트 파일)      

   
10. History : 지금까지 입력한 명령어를 보여줌.   

   
11. wget : 인터넷 서버에서 원하는 파일을 다운로드 할 때 사용됨. ex) wget (다운받고자 하는 파일의 링크)   

   
12. curl : 인터넷에서 원하는 파일 다운로드 or 업로드 할 때 사용됨. ex) curl -0 (다운받고자 하는 파일의 링크)   

   
13. grep(Global Regular Expression Print) : 파일에서 특정어를 검색할 때 사용하는 명령어. ex) grep + (찾는 단어) + (텍스트 파일)   
- -i : 대소문자 구별 하지 않고 검색
- -v : 선택한 단어가 없는 텍스트 파일을 찾음.
- -n : 찾은 단어의 라인까지 출력
- -r : 찾은 디렉토리 뿐만 아니라 하위 디렉토리까지 검색   
   
- [abc] : [] 안에 있는 문자를 찾음
- ^ : 라인의 첫번째
- $ : 라인의 마지막

---

궁금한 사항이 있으면 chatGPT 적극 활용하기!


