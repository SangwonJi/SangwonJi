# 👋 Intro

안녕하세요! 지상원입니다. 

제가 가진 분석 역량과 그간 사용한 프로그래밍 언어들을 보여드리기 위해, 데이터 사이언스를 전공하며 진행한 프로젝트들을 정리해 보았습니다. 

<br />

# 📝 Projects
학교생활동안 진행했던 프로젝트들입니다. 

R을 사용했던 프로젝트 부터, Python을 사용한 프로젝트 순서대로 정리했습니다. 

상세한 설명 및 어떤 코드를 바탕으로 진행하였는지는 상세 설명 링크에서 확인 부탁드리겠습니다. 

<br />

## R을 사용한 분석

### 1. 💊 임상 시험 데이터를 사용한 생존률 분석

> 주어진 csv 파일 데이터를 자유롭게 탐색적 데이터 분석(EDA)을 통해 다양한 시각화 방법으로 분석하고,
> 
> 비교할 변수를 직접 선택한 값을 기반으로 데이터셋에 대한 A/B 테스트에 대해 결론을 도출하는 프로젝트였습니다. 
> 
>> Cholangitis Project 
>> - Language : R (ggplot2, dplyr, ggfortify, patchwork)
>> - Skill : 선형 회귀 (Linear Regression), PCA, 변수 선택 (Feature Selection)
>> 
>> [프로젝트 상세 설명(Cholangitis)](https://github.com/SangwonJi/Cholangitis)
>> 
>> [프로젝트 코드 / PDF](https://github.com/SangwonJi/Cholangitis/blob/main/Cholangitis_Project.pdf)

<br />

### 2. 📝 심슨 쇼의 대본 분석

> 심슨 가족 쇼 대본을 제공받고, 텍스트 분석을 수행하였습니다.
> 
> Shiny app을 사용하여 버튼과 그래프를 통해 텍스트를 시각화하고, 이를 통해
> - 가장 많이 사용된 단어를 분석하고,
> - 시즌별로 사용된 단어의 빈도와 검색 기능을 통해 시즌별 사용 횟수를 확인하였으며,
> - 전체적인 단어 사용 트렌드도 파악하였습니다.
> 
> 시각화 도구를 통해 사용자가 좀 더 편하고 간편하게 데이터의 패턴과 트렌드를 직관적으로 볼 수 있게 하였으며,
>
> 데이터 분석 결과를 실시간으로 확인할 수 있게 하였습니다.
>
>> Simpsons Transcript Analysis Project
>> - Language : R
>> - Skill : shinyapps
>>
#### 🕒 로딩 시간 주의
> 앱이 웹사이트 및 그래프를 로드하는 동안 시간이 소요될 수 있습니다. 이 점 양해 부탁드립니다.
>> [프로젝트 웹사이트 링크(Simpsons Transcript Analysis Project)](https://sangwon08017.shinyapps.io/Simpsons_Transcripts_Analysis/)
>>
>> 
>> [프로젝트 코드](https://github.com/SangwonJi/Simpsons-Transcript-Analysis/blob/main/app.R)

<br />

### 3. 📈 투자 시뮬레이션

> 사용자가 다양한 투자 시나리오를 설정하고, 결과를 실시간으로 분석할 수 있는 인터랙티브한 웹 애플리케이션으로,
>
> Shiny app을 활용하여 총 시장 인덱스 펀드에 투자했을 때의 결과를 시뮬레이션하고 시각화 하였습니다. 
> 
> 사용자가 투자 기간, 초기 투자 금액, 연 평균 수익률등을 설정하고, 이러한 변수들이 투자결과에 미치는 영향을 시각화하는 그래프를 바로 확인해볼 수 있게 하였습니다.
>
>> Investment Simulator Project 
>> - Language : R
>> - Skill : shinyapps
>>
#### 🕒 로딩 시간 주의
> 앱이 웹사이트 및 그래프를 로드하는 동안 시간이 소요될 수 있습니다. 이 점 양해 부탁드립니다.
>> [프로젝트 웹사이트 링크(Investment Simulator Project)](https://sangwon08017.shinyapps.io/Hw5-Sangwon-Ji/)
>>
>> [프로젝트 코드](https://github.com/SangwonJi/Investment-Simulator/blob/main/app.R)

<br />

## Python을 사용한 분석 / 개발

###  1. 🌏 세계의 발전과 빈곤 프로젝트 (World Progress and Poverty Project) 

> Gapminder.org의 데이터를 활용하여 세계 인구 성장과 국가별 빈곤률에 초점을 맞추어 세계의 변화와 발전을 분석하는 프로젝트 입니다.
>
> 인구 성장과 빈곤율의 변화를 데이터를 가다듬어, 시각화된 그래프를 통해 나라별 데이터를 한 눈에 보기 좋게 비교하고, 결론을 내렸습니다. 
>
>> World Progress and Poverty Project
>> - Language : python3(NumPy,Matplotlib)
>> - Skill : 게임 메커니즘, 확률 분석, 전략 수립
>>
>> [프로젝트 상세 설명(World Progress and Poverty Project)](https://github.com/SangwonJi/WPP)
>>
>> [프로젝트 코드 / PDF](https://github.com/SangwonJi/WPP/blob/main/project1.ipynb)

<br />

### 2. 📽️ 영화 분류 (Movie Classification) 프로젝트 

> 주어진 영화 대본 테이블에서 특정 단어의 사용 빈도를 통해 영화가 코미디인지 스릴러인지 예측하는 분류 모델을 구축하는 프로젝트입니다.
>
> 자연어 처리 및 기계 학습 기술을 활용하여 텍스트 데이터를 분석하고 예측 모델을 만들었습니다.
>
>> Typing Test Project
>> - Language : python3
>> - Skill : K-neartest neighbors (K-NN) 분류기 구현, 알고리즘 구현, 유클리드 거리 계산
>>
>> [프로젝트 상세 설명(Typing Test Project](https://github.com/SangwonJi/Movie-Classification)
>>
>> [프로젝트 코드 / PDF](https://github.com/SangwonJi/Movie-Classification/blob/main/Classification_Project.ipynb)

<br />

###  3. 🎲 게임 오브 호그(Hog)

> 게임 오브 호그는 턴제 주사위 게임 시뮬레이션 프로젝트입니다. 
>
> 각 턴 마다 굴리는 횟수를 전략적으로 생각하여, 100점을 달성하는 것이 목표인 게임입니다.

>> Game of Hog Project
>> - Language : python3   
>> - Skill : 게임 메커니즘, 확률 분석, 전략 수립
>>
>> [프로젝트 상세 설명(Hog)](https://github.com/SangwonJi/Hog)
>>
>> [프로젝트 코드 / PDF](https://github.com/SangwonJi/Hog/blob/main/hog.pdf)

<br />

### 4. 🐜 개미 대 꿀벌 🐝 (Ants vs. Somebees) 타워 디펜스 게임

> 이 프로젝트에서는 객체지향 프로그래밍을 이용하여 '개미 대 꿀벌 (Ants Vs. SomeBees)'이라는 타워 디펜스 게임을 개발했습니다.
>
> 플레이어는 여왕개미가 되어 꿀벌의 공격으로부터 개미집을 방어하고, 이 과정에서 다양한 유형의 개미를 전략적으로 배치하여 방어 매커니즘을 강화하는 방식으로 게임이 플레이 됩니다.
>
>> Project Ants
>> - Language : python3
>> - Skill : 객체 지향 프로그래밍 (Object-oriented programming (OOP))
>>
>> [프로젝트 상세 설명(Ants)](https://github.com/SangwonJi/Ants)
>>
>> [프로젝트 코드 / PDF](https://github.com/SangwonJi/Ants/blob/main/ants.pdf)

<br />

### 5. ⌨️ 타이핑 테스트 (Typing Test) 프로젝트 

> 타이핑 테스트 프로젝트는 사용자의 타자 속도와 정확도를 측정하는 프로그램입니다
>
> 주어진 문장을 입력하는 시간과 정확도를 분석하여 단어 당 분당 타수(WPM)와 정확도(Accuracy)를 계산합니다.
>
>> Typing Test Project
>> - Language : python3
>> - Skill : 문자열 처리, 알고리즘 설계 및 구현
>>
>> [프로젝트 상세 설명(Typing Test Project)](https://github.com/SangwonJi/Cats)
>>
>> [프로젝트 코드 / PDF](https://github.com/SangwonJi/Cats/blob/main/cats.pdf)

<br />

감사합니다. 

<br />

### 📫 Contact

- 이메일 : allen08017@gmail.com
