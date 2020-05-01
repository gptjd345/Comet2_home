## 김혜성의 첫번째 작업공간입니다.

***

### git bub 시작


1. **원격 저장소 생성**

2. **지역 저장소 생성** */d/git_Comet2_home*

3. **지역 저장소와 원격 저장소 연결**
    - git remote add origin 원격 저장소 주소
    - origin은 원격 저장소를 의미
    - git remote -v  로 연결 확인
    
4. **첫 푸쉬**
    - git push -u origin master
    - -u 옵션은 지역 저장소의 브랜치를 원격 저장소의 master브랜치에 연결하는 것으로 처음 한번만 사용
    
5. **첫 풀**
    - git pull origin master 
    - 원격 저장소의 내용을 지역저장소의 master브랜치로 가져옴
    
6. **git bash 환경설정**
    - **사용할 컬러명 설정**
      - green="\[\033[1;32m\]" //green은 bold처리
      - blue="\[\033[0;34m\]"
      - purple="\[\033[0;35m\]"
      - reset="\[\033[0m\]"
      - white="\[\033[0;37m\]"
    
    - **export PS1="$green\u$green\$(__git_ps1)$white \w $ $green"**
      - $green\u: username을 green으로
      - $green\$(__git_ps1): 체크아웃한 commit의 hash나 기타 git 관련 정보를 녹색(green)으로
      - $white \W $: 현재 디렉터리 위치와 $를 white로
      - $green: 그 이후의 정보는 green으로 변경
    - **export LS_COLORS="di=01;37:fi=01;32"**
      - **디렉토리명**은 흰색으로 **파일명**은 밝은 녹색으로 처리 둘다 **bold**처리


[참고한 사이트](https://medium.com/@violetboralee/windows-%EC%82%AC%EC%9A%A9%EC%9E%90%EB%A5%BC-%EC%9C%84%ED%95%9C-git-bash-%EC%84%A4%EC%A0%95-ac50acb34c46) 
---


      
    
    

