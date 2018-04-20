0006802
# <프로그래머를 위한 선형대수> (2017) 리뷰

<Linear Algebra for Programmer> | 히라오카 카즈유키, 호리 겐 지음 | 길벗출판사 </br>
책을 읽으며 배운 내용을 정리하였습니다. 

#### 책 관련 링크
=======
Linear Algebra for Programmer </br>
히라오카 카즈유키, 호리 겐 지음 | 길벗출판사 </br>

책을 읽으며 배운 내용을 정리하였습니다. 


### 책 관련 링크
예제 소스 코드 다운 경로 : www.github.com/gilbutITbook/006802

### 0. 들어가며 
</br>
저는 프로그래머는 아니고, 문과생으로 데이터 과학을 공부하기 위해 이제 막 선형대수를 시작한 학생입니다. 이 책에서는 Ruby를 활용해 선형 사상 애니메이션 그려볼 수 있게 자료를 제공하고 있습니다. 하지만 이 책을 보며 Ruby나 Gnuplot을 처음알게 된 제가 책에 나온대로 따라해서 애니메이션을 그려보는 환경을 만들긴 쉽지 않았습니다. </br>
</br>
책에 나와있는 대로 Ruby와 Gnuplot을 모두 설치하고, 코드를 실행해보았지만 계속 오류가 나서 결국 저자들이 제공하는 애니메이션을 확인하는 것은 포기했습니다(OTL) </br> 
</br>
대신, GeoGebra(https://www.geogebra.org/m/pDU4peV5)에서 제공하는 Linear Transformation 애니메이션을 참고하였습니다. </br>




### 1. 용어 정리
처음 선형대수를 배울 때 영어로 배워서 그런지, 번역된 용어가 익숙하지 않았습니다 (가령, "선형 사상"이 "Linear Mapping"이라던가...). 책에서는 처음 용어가 나올 때 영문명을 함께 제공하고 있지 않아 관련 내용을 구글에 검색해보려면, 우선 용어의 영문명을 찾은 다음에 관련 내용을 찾아야 하는 번거로움이 있었습니다. 더불어 한자식 표현보다는 영문명이 직관적으로 잘 이해되는 경우도 있어 아래와 같이 각 장에 등장하는 용어의 영문명을 정리하였습니다. </br>


#### 1장 
##### 1.1 벡터와 공간
사상(mapping)
전치(transpose)
행렬식(determinant)
종벡터(column vector)
횡벡터(row vector)
위치 벡터(position, position vector)
벡터 공간(vector space)
내적(inner product)
외적(outer product)
정칙 행렬(regular matrix)
랭크(rank)
고유값(eigenvalue)


##### 1.2. 행렬과 사상
선형 사상(linear mapping)
선형 변환(linear transformation)
