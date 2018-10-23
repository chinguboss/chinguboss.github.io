---
layout: post
title:  "Assignment3"
date:   2018-10-23
excerpt: "인간컴퓨터상호작용 과제입니다."
---

Human Computer Interaction
Assignment #3


2014190717 권기정 | Human Computer Interaction | 2018.10.23




 
 
##  A.	 Requirements
### 1. Describe the overall objective of the application
<p>
	요즘 대부분의 사진 정렬 프로그램들은 앨범을 만들어 사진을 정렬한다는 기본 기능 말고도 다른 기능을 과도하게 탑재하고 있어서 
  처음 사용하는 사람들은 어떠한 기능이 있는 지 파악하기 힘든 경우가 많다. 특히나 정보 습득 능력이 젊은 층보다 상대적으로 떨어지는 
  중/장년층 사용자들에겐 더욱 그런 경향이 있다. 또한 SNS를 즐기시는 중/장년층 소비자들이 늘어나기 때문에 SNS에 대한 접근성도 
  편리하게 만들고자 한다. 따라서 그러한 중/장년층 사용자들을 위해 배우기 쉽고 직관적으로 사용하기 편한 application을 만들려고 한다.
</p>  

### 2. List major functional requirement
<p>
	<ol>
	<li>앨범의 이름을 정하고, 사진을 넣을 수 있음(앨범 만들기)</li>
	<li>사진을 날짜/장소별로 정렬시킬 수 있음</li>
	<li>사진을 간단하게 편집할 수 있음</li>
	<li>사진을 바로 SNS에 공유할 수 있음</li>
	</ol>
</p> 

### 3. List major UI requirements
<p>
	<ol>
		<li>Functional
			<ul>
        			<li>앨범 만드는 아이콘을 직관적으로 알 수 있음</li>
				<li>앨범 및 사진을 공유하는 아이콘을 직관적으로 알 수 있음</li>
				<li>사진을 클릭하면 사진이 확대되고, 사진의 정보가 같이 나옴</li>
			</ul>
		</li>
		<li>Non-functional
			<ul>
        			<li>눈의 노화가 찾아올 시기이기 때문에 글자와 아이콘의 크기를 크게 한다</li>
		    		<li>눈의 피로도를 덜기 위해 배경 화면의 색깔을 초록색으로 맞춤</li>
      			</ul>
		</li>
	</ol>
</p>

### 4. List other considerations
<p>
	<ul>
        	<li>사용자들이 여행이나 가족들끼리 찍은 사진을 컴퓨터/핸드폰으로 편하게 관리할 수 있게 한다</li>
        	<li>윈도우 환경과 안드로이드/IOS 환경으로 둘 다 사용할 수 있게 한다. 주로 사용하는 플랫폼은 Desktop 환경이지만 모바일과 컴퓨터는 서로 연동되어서 관리된다.</li>
        	<li>50대 이상의 중/장년층을 주 고객 대상으로 한다</li>
	</ul>
</p>
  
## B. User analysis
### 1. Conduct user interviews

<iframe src="https://www.youtube.com/watch?v=g_1YcLa2pd0" frameborder="0" allowfullscreen=""></iframe></br>
<iframe src="https://www.youtube.com/watch?v=0Pcphn_9PLs" frameborder="0" allowfullscreen=""></iframe></br>

### 2. List the major direct user requirements
<p>
  <ul>
	<li>아이콘이 큼직큼직 했으면 좋겠음</li>
	<li>최대한 간단하게 사진을 관리할 수 있으면 좋겠음</li>
	<li>사진 편집이 쉬웠으면 좋겠음</li>
	<li>사진이 자동으로 분류가 되면 좋겠음</li>
  </ul>
</p>

### 3. List the major cognitive/ergonomic requirements
<p>
  <ul>
	<li>눈의 피로를 덜기 위해 배경화면이 초록색임</li>
	<li>중/장년층 사용자들의 노안이 온다는 특성을 고려해 글자 크기를 크게 함</li>
  </ul>
</p>

### 4. Construct 2~3 usage scenarios
<p>
	[Scenario 1]</br>
한 사용자가 스마트폰으로 여행에 가서 사진을 찍는다. 찍은 사진을 가지고 앨범을 만들려고 앨범 만들기 버튼을 클릭한 후 앨범의 이름을 입력하고 만든다. 그 후 앨범의 기타 추가적인 정보(찍은 날짜, 장소 같은 필수적이진 않은 내용들)를 입력한 후 프로그램을 종료한다.
</p>
<p>
[Scenario 2]</br>
	한 사용자가 SNS에 올리기 위해 찍은 사진을 보니 마음에 들지 않아 보정을 하려 한다. 원하는 사진을 선택하여 보정을 한 후 SNS에 공유 버튼을 눌러 사진을 업로드한다.
</p>

### 5. Construct a rough interaction model for 2~3 major tasks
<p>
[Model 1] : 새 앨범 추가</br>
1)	프로그램을 실행시킨다.</br>
2)	새 앨범 추가 아이콘을 클릭한다.</br>
3)	앨범의 이름을 기입하고 확인 버튼을 누른다.</br>
4)	앨범에 들어갈 사진들을 선택한 후 삽입 버튼을 누른다.</br>
5)	앨범의 추가 정보들을 입력하거나, 입력하지 않을 것이라면 건너뛰기 버튼을 누른다.</br>
6)	프로그램을 종료한다.</br>
</p>
</p>
[Model 2] : 사진을 SNS에 올리기</br>
1)	프로그램을 실행시킨다.</br>
2)	SNS에 올리고 싶은 사진을 앨범에서 찾아서 선택한다.</br>
3)	SNS에 공유 버튼을 클릭한다.</br>
4)	올리고 싶은 SNS의 아이콘을 클릭한다.</br>
5)	SNS에 사진에 대한 설명을 쓴다.</br>
6)	업로드 버튼을 누른다.</br>
7)	프로그램을 종료한다.</br>
</p>
