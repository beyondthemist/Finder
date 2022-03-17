# Finder
## 무슨 프로그램인가?
주어진 root directory의 모든 하위 경로에 존재하는 압축파일을 찾아낸다.  
  
  
## 왜 만들었는가?
1. 본인은 정보보호병(CERT)으로 군 복무를 수행했음
2. 주요 업무 중 하나가 외부에서 들여온 저장매체를 검사하는 것이었음
3. 당시 백신이 압축파일을 제대로 검사하지 못 해 압축파일은 따로 빼내서 압축을 풀고 검사해야 했음
4. 대체로 입축파일도 너무 많았고, 가끔 디렉토리 구조가 너무 복잡한 경우도 있었음
5. 4.와 같은 이유로 손으로 찾으면서 파일이 누락되는 경우 발생했음.
위와 같은 애로사항이 동기가 되어 만들었다.
  
  
## 압축파일을 완벽하게 찾아내는가?
압축파일 확장명 종류를 검색해서 나온 것들을 최대한 포함한 것이므로 정말 모든 압축파일을 다 찾아낸다고 확정할 수는 없다.  
  
  
## 완벽한 프로그램인가?
상용 프로그램이 아닌데다가, 당시 속해있던 부서에서 '우리끼리 쓰는' 목적으로 만든 것이므로 사용자의 실수에 대한 처리나 UI 등이 다소 불편하다.  
애초에 GUI는 없이 만들었다가, 만드는 김에 해보자 싶어서 만들어봤다.  
사실 JavaFX로 만들고 싶었으나 Scene Builder도 없는데다가 익숙치 않은 탓에 그나마 익숙한 Swing으로 만들었다.  
다만 이 프로그램을 6개월 정도 쓰다가 전역했는데, 문제 있다는 얘기는 들은 게 없다.
  
  
## 한국인이고, 군 복무 중에 쓰려고 만든 것인데 왜 주석은 전부 영어인가?
당시 이 프로그램을 만든 PC는 군 인트라넷 PC였고, 코딩하기에 적절한 폰트는 한글을 지원하지 않았다.  
군 인트라넷 PC 특성 상 내가 원하는 폰트(개인적으로 D2Coding 선호)를 다운받을 수 없었고,  
그렇다고 주석을 안 쓸 수는 없어서 영어로 주석을 써놨다.  
참고로 본인은 수능 영어 5등급이다.
