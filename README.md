<h1>Hanbaek_Python_Study</h1>
실습환경: Google Colab
<br>
<h2>Python 학습 요약</h2>
<table style="width: 642px;" border="1">
<tbody>
<tr>
<td style="width: 82.4688px;">범주</td>
<td style="width: 542.531px;">세부내용</td>
</tr>
<tr>
<td style="width: 82.4688px;">자료형</td>
<td style="width: 542.531px;">기본자료형(숫자, 문자), list, tuple, dictionary, set, boolean</td>
</tr>
<tr>
<td style="width: 82.4688px;">제어문</td>
<td style="width: 542.531px;">if문, if-else문, if-elif문, while문, for문, range(시작,끝,간격)</td>
</tr>
<tr>
<td style="width: 82.4688px;">함수</td>
<td style="width: 542.531px;">지역변수, 전역변수, return, parameter</td>
</tr>
<tr>
<td style="width: 82.4688px;">클래스</td>
<td style="width: 542.531px;">생성자, 상속, 오버라이드, 인스턴스 변수, 접근 제어, 정적 메서드, 클래스 메서드</td>
</tr>
<tr>
<td style="width: 82.4688px;">그외</td>
<td style="width: 542.531px;">예외처리, 파일조작(txt,csv)</td>
</tr>
<tr>
<td style="width: 82.4688px;">OpenCv</td>
<td style="width: 542.531px;">이미지 크기조절, 보간법(선형, 쌍선형), 필터, 상하대칭, 좌우대칭, 회전, 자유회전, 평탄화, 윤곽선추출, 흑백, 회색조, HSV</td>
</tr>
<tr>
<td style="width: 82.4688px;">알고리즘</td>
<td style="width: 542.531px;">maxheap tree, 이진탐색트리, 허프만코드, Dijkastra, Floyd-Warshell</td>
</tr>
</tbody>
</table>

<h2>Python 실습 파일 목록</h2>
<table border="1" width="1177">
<tbody>
<tr>
<td width="350">파일명</td>
<td width="827">내용</td>
</tr>
<tr>
<td>0404 실습.ipynb</td>
<td>코랩 환경 설정, True/False,None,list,tuple,set 연습</td>
</tr>
<tr>
<td>Ex0414실습.ipynb</td>
<td>파이썬 기본문법, 내부변수, 전역변수, 함수 선언,&nbsp;</td>
</tr>
<tr>
<td>ex0418.ipynb</td>
<td>list의 slicing opreration, 오름차순, 내림차순 정렬 구현, 평균, 분산, 표준편차 계산</td>
</tr>
<tr>
<td>ex0419.ipynb</td>
<td>지역변수, 전역변수, 학년별 성적 관리하는 클래스, 메소드 구현</td>
</tr>
<tr>
<td>ex0425.ipynb</td>
<td>랜덤모듈, txt읽기, 쓰기, 다양한 함수 연습</td>
</tr>
<tr>
<td>Ex0426.ipynb</td>
<td>csv 읽기(csv모듈 필요), 쓰기, 인코딩, sys모듈(try-except, assert, sys.exc_inf()), 인스턴스 객체 생성, self 파라미터</td>
</tr>
<tr>
<td>ex0502.ipynb</td>
<td>csv 입출력 연습, csv.reader(), csv.writer(), .write, .writerow()</td>
</tr>
<tr>
<td>과제0503 개량.ipynb</td>
<td>입력받은 정수2개의 범위에서 입력받은 n개만큼 추출해 각 행마다 csv로 저장하는 과제</td>
</tr>
<tr>
<td>과제 0503 클래스화.ipynb</td>
<td>사용했던 함수들을 클래스의 메소드로 묶음</td>
</tr>
<tr>
<td>과제 0503 클래스+캡슐화.ipynb</td>
<td>메소드에 인자넣을 필요없이 내부 인자를 가져다 쓰도록 변형</td>
</tr>
<tr>
<td>ex0510.ipynb</td>
<td>클래스로 List 구현 연습</td>
</tr>
<tr>
<td>0516 Set 클래스만들기.ipynb</td>
<td>클래스로 Set 구현 연습</td>
</tr>
<tr>
<td>0516 Stack ADT.ipynb</td>
<td>클래스로 Stack 구현 연습(Last In First Out)</td>
</tr>
<tr>
<td>0516 괄호검사기(스택 응용).ipynb</td>
<td>stack이용해 괄호의 짝( () {} [])이 맞게 입력되었는지 검사</td>
</tr>
<tr>
<td>0516 수식계산_번역 중위-_후위.ipynb</td>
<td>string으로 입력받은 수학식에 들어있는 사칙연산을 괄호도 고려해서 stack으로 연산해서 결과 도출</td>
</tr>
<tr>
<td>0516파이썬 변수 주소저장 .ipynb</td>
<td>파이썬 변수 메모리 저장방식과 주소값 연습</td>
</tr>
<tr>
<td>0517 OpenCV 연습.ipynb</td>
<td>OpenCv 모듈 연습, 이미지파일 열기, 크기 1/2, 2배, n배, 상하반전, 좌우반전, 원점대칭 반전, 90도회전</td>
</tr>
<tr>
<td>0518 OPEN CV Interpolation 연습.ipynb</td>
<td>OpenCv 보간법(Interpolation)연습, INTER_LINEAR, bilinear 보간법 연습</td>
</tr>
<tr>
<td>0518 resize by bilinear.ipynb</td>
<td>OpenCv Bilinear 보간법 이용한 resize 함수 구현</td>
</tr>
<tr>
<td>0518 회색조, RGB분리, RGB-_HSV.ipynb</td>
<td>OpenCv로 이미지 불러와 회색조, RGB채널 분리, HSV변환 연습</td>
</tr>
<tr>
<td>0525 opencv 복습.ipynb</td>
<td>OpenCv복습, Bilinear 보간법 개량</td>
</tr>
<tr>
<td>0525 이미지 상하_좌우 대칭, 90도 회전.ipynb</td>
<td>OpenCv 상하대칭, 좌우대칭, 직각회전 함수화</td>
</tr>
<tr>
<td>0525 회색조이미지 히스토그램, 평탄화.ipynb</td>
<td>OpenCv 회색조, 이미지 색 분포 히스토그램(0~255), 평탄화 연습</td>
</tr>
<tr>
<td>0607 그림 임의의 각도로 회전.ipynb</td>
<td>OpenCv 입력받은 값으로 이미지 회전 구현 연습</td>
</tr>
<tr>
<td>0607 그림에 평균필터, 가우시안필터.ipynb</td>
<td>OpenCv 3x3필터 평탄화, 윤곽선 추출, 가우시안 필터 구현 연습</td>
</tr>
<tr>
<td>0621 maxheap tree.ipynb</td>
<td>maxheap 자료구조 구현 연습</td>
</tr>
<tr>
<td>0621 Morse Code by Tree.ipynb</td>
<td>자료구조 노드 구현한 클래스 이용해 모르스 부호 변환기, 해석기 구현 연습</td>
</tr>
<tr>
<td>0627 이진탐색트리.ipynb</td>
<td>이진탐색 트리 알고리즘 구현 연습(후위, 순환)</td>
</tr>
<tr>
<td>0627 힙 응용한 허프만 코드.ipynb</td>
<td>허프만 코드 알고리즘 구현 연습(최소힙을 산출해 데이터 압축하는데 사용)</td>
</tr>
<tr>
<td>0704 Dijkstra 알고리즘.ipynb</td>
<td>Dijkstra 알고리즘 구현 연습(하나의 점에서 모든 점까지의 최단거리 산출)</td>
</tr>
<tr>
<td>0704 Floyd-Warshell 알고리즘.ipynb</td>
<td>Floyd-Warshell 알고리즘 구현 연습(모든 노드 간 최단 경로를 구하는 알고리즘)</td>
</tr>
<tr>
<td>Class 연산자 오버로딩 연습.ipynb</td>
<td>클래스 이용해 사칙연산(+,-,*,/)과 and, or, xor, &lt;, &gt;, &lt;=, &gt;=, !=등의 연산자 구현 연습</td>
</tr>
<tr>
<td>Colab-Github연동.ipynb</td>
<td>colab에 있는 파일을 github repository에 자동 업로드 시키는거 연습</td>
</tr>
<tr>
<td>ex0613 괄호검사 복습.ipynb</td>
<td>stack이용한 괄호검사기 개량</td>
</tr>
<tr>
<td>ex0613 미로탐색(넓이탐색 by queue).ipynb</td>
<td>넓이 탐색 알고리즘을 이용한 미로 탐색 구현 연습</td>
</tr>
<tr>
<td>ex0613 원형큐 구현.ipynb</td>
<td>자료구조 원형 큐 구현 연습(삭제, 삽입 위치 순환 변경), 큐(First In First Out)</td>
</tr>
<tr>
<td>ex0614 덱(Deque).ipynb</td>
<td>자료구조 덱 구현 연습(FIFO+LIFO)</td>
</tr>
<tr>
<td>ex0614 연결된 리스트(노드이용).ipynb</td>
<td>자료구조 Linked_list 노드 이용해 구현</td>
</tr>
<tr>
<td>ex0614 연결된 스택(노드이용).ipynb</td>
<td>자료구조 Linked_stack 노드 이용해 구현</td>
</tr>
<tr>
<td>ex0614 전략적 미로탐색 by 우선순위 큐.ipynb</td>
<td>우선순위 큐 이용해 전략적 탐색 알고리즘 이용한 미로 탐색 구현 연습</td>
</tr>
<tr>
<td>ex_opencv_imread.ipynb</td>
<td>OpenCv 기본 사용법 예제</td>
</tr>
<tr>
<td>Math,Random,List,Tuple,Dic,Set.ipynb</td>
<td>Math 모듈, Random모듈, List, Tuple, Dic, Set에 있는 내장 함수와 메소드 사용 연습</td>
</tr>
<tr>
<td>라인편집기-0511.ipynb</td>
<td>txt파일을 읽어와 입력받은 행에 라인을 삽입, 삭제, 수정할수 있는 클래스 구현</td>
</tr>
<tr>
<td>미로탐색(스택응용).ipynb</td>
<td>리스트로 구현한 스택 클래스 이용해 미로 탐색, 탐색위치를 출력해 보여주는 클래스도 같이 구현</td>
</tr>
<tr>
<td>미로탐색 다듬기.ipynb</td>
<td>탐색위치를 실시간으로 보여주는 클래스 출력 형식 다듬음</td>
</tr>
<tr>
<td>성적분석 작업중.ipynb</td>
<td>ex0419에서 하던 반별 성적 관리 시스템을 csv파일로 연동해 저장하는 코드 구현 연습</td>
</tr>
<tr>
<td>성적분석 정리.ipynb</td>
<td>반별 성적 관리 시스템을 클래스로 정리</td>
</tr>
<tr>
<td>성적분석 개량.ipynb</td>
<td>클래스로 정리한 메소드들을 보다 쉽게 인자 전달 받도록 개량</td>
</tr>
<tr>
<td>성적분석 제출본.ipynb</td>
<td>성적관리 결과인 평균, 표준편차등을 보다 알기 쉽게 그래프등으로 출력하는 기능도 추가</td>
</tr>
<tr>
<td>임의의 데이터 통계.ipynb</td>
<td>직접 구현해본 임의의 데이터 통계 구하는 코드</td>
</tr>
<tr>
<td>임의의 데이터 통계 구하기(교수님 예시).ipynb</td>
<td>교수님이 주신 임의의 데이터 통계구하기 예제 코드</td>
</tr>
<tr>
<td>임의의_데이터_통계_구하기(주석추가함).ipynb</td>
<td>예제를 하나씩 실행시켜보며 주석 추가</td>
</tr>
<tr>
<td>클래스_동작.ipynb</td>
<td>클래스 특성 연습, 인스턴스 객체 생성해 보기</td>
</tr>
<tr>
<td>클래스_임의의_데이터_통계_구하기.ipynb</td>
<td>임의의 데이터 통계 구하기 코드를 클래스화 시킴</td>
</tr>
</tbody>
</table>
