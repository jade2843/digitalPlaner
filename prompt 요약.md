#제목
# 1. prompt와 맥락에 대한 이해

### 

1.1 생성 AI와 Context

...

- 🤖prompt : "Context란 무엇인가?"  
    
    ![](https://adsloader.bitbucket.io/doc/study/5/images/context_1.png)
    
- prompt 결과:
    

"Context(컨텍스트)"는 어떤 사건, 상황, 문장 또는 단어 등이 포함된 주변 환경이나 배경을 나타냅니다. 이는 해당 요소를 이해하거나 해석하는 데 필요한 정보를 제공하는데 중요한 역할을 합니다. 맥락이 없는 정보는 종종 혼돈을 야기할 수 있습니다. 이는 언어, 문화, 기술 등 여러 측면에서 발생할 수 있는데, 각각의 경우에 맥락은 중요한 의미를 지닙니다.

예를 들어, 단어 "바람"은 맥락에 따라 다르게 해석될 수 있습니다. 날씨와 관련된 문맥에서는 공기의 움직임을 나타내지만, 대화에서는 소문이나 감정의 움직임을 나타낼 수 있습니다.

컴퓨터과학 분야에서도 "컨텍스트"는 중요한 개념입니다. 예를 들어, 프로그래밍 언어에서 변수나 함수의 의미는 사용된 컨텍스트에 따라 달라질 수 있습니다. 함수의 인자나 변수의 스코프 등이 이에 해당합니다.

맥락은 의사소통과 이해에 있어서 핵심적인 개념이며, 상황에 맞게 정보를 해석하고 사용하는 데 도움을 줍니다.

### 

1.2 생성 AI를 바라보는 개발자 시각:

> 생성AI는 AI 과학자의 이론을 가지고 “개발자가 프로그래밍하며 만든 것”이다.

![](https://adsloader.bitbucket.io/doc/study/5/images/context_3.png)

[프롬프트는 대화가 아니라 명령]이다. 개발자에게 프롬프트라는 단어가 익숙한 이유는 "명령"이라는 의미로 사용되는 단어이기 때문이다. 우리가 흔하게 접하는 DOS 창(터미널) 역시 "명령 프롬프트" 창으로 불린다.

![](https://adsloader.bitbucket.io/doc/study/5/images/prompt_0.jpg)

```kotlin

0. 범위(scope)를 만든다. -> " ..에서"
1. 데이터부터 정의한다. 
2. 명령을 순차적으로 기술한다. 
3. 나온 결과는 답이 아니라 방법일 뿐이다.

```

결론:

```javascript
▪ 생성 AI는 “사람대신 사용하는 그럭저럭한 Assitant” 
▪ 내 자신이 하나의 기업으로 활동하는데 도움을 주는 도구 
▪ 문해력이 있다면 → 시간을 벌어주고(생성결과물 검증가능) 
▪ 문해력이 없다면 → 시간을 낭비하는 것(생성결과물 가치를 알 수 없음)
```

# 

2. 간단한 맥락 예제

[#TODO](https://adsloader.bitbucket.io/#TODO)

### 

2.1 Ask AI: ChatGPT, Bard, Bing

```javascript
1. 사람이 3명이 있다.
2. 의사, 부산거주 70대 노인, 검찰
3. "밥먹었어요?"라는 말을 했다. 
4. 3명은 각각 어떤 식으로 사고하는가?
```

ChatGPT:  

![](https://adsloader.bitbucket.io/doc/study/5/images/context_6.png)

Bard:  

![](https://adsloader.bitbucket.io/doc/study/5/images/context_4.png)

Bing:  

![](https://adsloader.bitbucket.io/doc/study/5/images/context_5.png)

생각하기🔔:  
인간의 언어로 제한된 맥락을 제공하고 프롬프트를 작성할 경우, 얼마나 근사치의 생성물을 가져올 수 있을까?

### 

2.2 Ask AI: ChatGPT, Bard, Bing

[#TODO](https://adsloader.bitbucket.io/#TODO)

```javascript
a4 크기의 종이와 빨간색 싸인펜, 파란색 볼펜, 검은색 연필이 있습니다.
파란색으로 1부터 10까지 최상단의 위치에 1줄로 표기합니다.
그 다음 줄에 빨간색으로 55라는 숫자를 씁니다.
연필로 빨간색의 숫자값과 +100을 한 결과를 [빨간색결과]에 저장하고 그 값을 최하단 중앙에 표기합니다.
[빨간색결과]에 -100을 표기하고 아래에 파란색으로 같은 값을 표기해주세요
```

ChatGPT:

Bard:

Bing:

참고용 자료:  
[되도록 나중에 보기: ✂ 자력갱생으로 해결 못할 경우, 참고자료 ✂](https://github.com/VintageAppMaker/AIForJavascript/blob/main/doc/1/1.context/Context_thinking_1.md#context%ED%98%95%EC%8B%9D%EC%9C%BC%EB%A1%9C-%EC%82%AC%EA%B3%A0%ED%95%98%EA%B8%B0-1)

### 

2.3 Ask AI: ChatGPT, Bard, Bing

HTML과 Javascript를 만드는 예제이다. 그러므로 결과물을 테스트 해볼 수 있어야 한다.  
아래의 사이트로 이동하여 간단한 사용법을 배운 후, 진행한다.

[jsfiddle](https://jsfiddle.net/)

[#TODO](https://adsloader.bitbucket.io/#TODO)

```javascript
javascript에서 
1. 파란색으로 1부터 10까지 최상단의 위치에 1줄로 출력합니다.
2. 그 다음 줄에 빨간색으로 55라는 숫자를 출력합니다.
3. 빨간색의 숫자값과 +100을 한 결과를 다음줄 중앙에 표기합니다.
소스코드를 만들어주세요
```

위의 프롬프트를 각 생성 AI에서 실행해본다. 그리고 결과물을 [jsfiddle](https://jsfiddle.net/)에서 테스트 해본다.

ChatGPT:

Bard:

Bing:

참고용 자료:

[되도록 나중에 보기: ✂ 자력갱생으로 해결 못할 경우, 참고자료 ✂](https://github.com/VintageAppMaker/AIForJavascript/blob/main/doc/1/1.context/Context_thinking_2.md)

### 

2.4 Ask AI: ChatGPT, Bard, Bing

HTML과 Javascript를 만드는 예제이다. 그러므로 결과물을 테스트 해볼 수 있어야 한다.  
아래의 사이트로 이동하여 간단한 사용법을 배운 후, 진행한다.

[jsfiddle](https://jsfiddle.net/)

[#TODO](https://adsloader.bitbucket.io/#TODO)

```javascript
1. 5개의 숫자값을 넣는 공간(배열)을 만들고 이름을 "성적리스트"라고 정의합니다. 
  그리고 모두 0으로 채워넣습니다.
2. 숫자값이 100점이면 첫번째 공간에 +1을 합니다. 
3. 숫자값이 99에서 80사이라면 두번째 공간에 +1을 합니다. 
4. 숫자값이 79에서 70사이라면 세번째 공간에 +1을 합니다. 
5. 숫자값이 69에서 60사이라면 네번쨰 공간에 +1을 합니다. 
6. 숫자값이 59이하라면 다섯번째 공간에 +1을 합니다.

이런 로직으로 javascript 함수를 만들어주고 이름을 score_count라고 정의해주세요
```

위의 프롬프트를 각 생성 AI에서 실행해본다. 그리고 결과물을 [jsfiddle](https://jsfiddle.net/)에서 테스트 해본다.

ChatGPT:

Bard:

Bing:

참고용 자료:

[되도록 나중에 보기: ✂ 자력갱생으로 해결 못할 경우, 참고자료 ✂](https://github.com/VintageAppMaker/AIForJavascript/blob/main/doc/1/1.context/Context_thinking_3.md)

[#TODO](https://adsloader.bitbucket.io/#TODO)  
위의 함수가 원하는 결과를 만들었다면, 그 다음 프롬프트로 다음을 실행한다.

```javascript
score_count를 이용하여 [100, 70, 100, 90, 10]의 결과값을 출력해줘
```

ChatGPT:

Bard:

Bing:

# 

3. 의사코드( pseudocode )의 이해

ChatGPT에게 프롬프트를 던지며 학습을 해본다.

![](https://adsloader.bitbucket.io/doc/study/5/images/psu_1.png)

### 

Person:

- 의사코드 튜토리얼을 만들어줘

### 

ChatGPT:

- 물론입니다! 의사코드를 사용하여 간단한 예제를 풀어보는 튜토리얼을 만들어보겠습니다. 의사코드는 일련의 작업을 설명하는 고수준의 가상 코드로, 실제 프로그래밍 언어의 문법을 사용하지 않고 알고리즘을 기술하는 방법입니다.

이 튜토리얼에서는 의사코드로 세 개의 숫자를 더하는 간단한 알고리즘을 만들어보겠습니다. 시작해 볼까요?

**의사코드 튜토리얼: 숫자 더하기**

1. 세 개의 숫자를 입력받습니다.
2. 입력받은 세 개의 숫자를 더합니다.
3. 결과를 출력합니다.

이제 위의 의사코드를 실제 프로그래밍 언어로 변환하지 않고 알고리즘을 실행하는 방법을 알아보겠습니다.

**의사코드:**

```

1. 숫자1을 입력받는다.
2. 숫자2를 입력받는다.
3. 숫자3을 입력받는다.
4. 합계 = 숫자1 + 숫자2 + 숫자3
5. 합계를 출력한다.

```

이제 이 의사코드를 텍스트 편집기나 노트북 등에 작성하고, 각 단계를 순서대로 실행해보세요. 예를 들어, 첫 번째 단계에서는 사용자로부터 숫자1을 입력받는 작업을 수행하고, 두 번째 단계에서는 숫자2를 입력받는 작업을 수행합니다. 세 번째 단계에서는 숫자3을 입력받고, 네 번째 단계에서는 입력받은 세 숫자를 더하는 작업을 수행합니다. 마지막으로, 다섯 번째 단계에서는 계산된 합계를 출력합니다.

이렇게 하면 의사코드를 사용하여 알고리즘을 실행할 수 있습니다. 의사코드는 프로그램을 작성하기 전에 알고리즘을 설계하고 검증하는 데 유용한 도구입니다. 실제 프로그래밍 언어로 의사코드를 변환하여 구현할 수 있으며, 팀 협업 시에도 알고리즘의 이해를 돕는 데 사용될 수 있습니다.

의사코드는 프로그래밍 언어에 종속되지 않으므로, 여러분이 편리하게 사용할 수 있는 방법으로 의사코드를 작성해보세요. 이를 통해 알고리즘을 논리적으로 설계하고 이해하는 데 도움이 될 것입니다.

### 

Person:

- 의사코드로 더하기 함수를 만들고 값을 넣어 실행하는 예제를 만들어줘

### 

ChatGPT:

- 물론입니다! 의사코드로 더하기 함수를 만들고 값을 넣어 실행하는 예제를 제공해드리겠습니다. 다음은 의사코드로 작성된 더하기 함수입니다.

**의사코드:**

```python

함수 더하기(숫자1, 숫자2):
    합계 = 숫자1 + 숫자2
    반환 합계

```

위의 의사코드는 "더하기"라는 함수를 정의하고 있습니다. 이 함수는 두 개의 숫자를 입력받아 합계를 계산하고, 그 결과를 반환합니다.

이제 이 의사코드를 기반으로 값을 넣어 실행해보겠습니다.

**의사코드 실행 예제:**

```python

숫자1 = 3
숫자2 = 5
결과 = 더하기(숫자1, 숫자2)
결과를 출력한다.

```

위 예제에서는 `숫자1`에 3을, `숫자2`에 5를 대입한 후 `더하기` 함수를 호출합니다. 그 결과로 반환된 값을 `결과` 변수에 저장하고, 이를 출력합니다.

실제 프로그래밍 언어로 이를 구현할 때는 의사코드를 해당 언어의 문법에 맞게 변환해야 합니다. 예를 들어, Python에서는 다음과 같이 의사코드를 구현할 수 있습니다.

**Python 예제:**

```python

def 더하기(숫자1, 숫자2):
    합계 = 숫자1 + 숫자2
    return 합계

숫자1 = 3
숫자2 = 5
결과 = 더하기(숫자1, 숫자2)
print(결과)

```

이렇게 하면 Python 프로그램으로 더하기 함수를 구현하고 값을 넣어 실행한 예제를 확인할 수 있습니다.

의사코드는 프로그래밍 언어와는 달리 구체적인 문법이 없으므로 여러분이 사용하는 언어에 맞게 의사코드를 변환하여 구현할 수 있습니다.

[#TODO](https://adsloader.bitbucket.io/#TODO)  
위의 예제를 복사해 아래의 온라인 컴파일러에서 실행해본다.  
[https://www.online-python.com/](https://www.online-python.com/)

# 

4. 의사코드 형식으로 prompt 만들기

### 

4.1 Ask AI: ChatGPT, Bard, Bing

[#TODO](https://adsloader.bitbucket.io/#TODO)

```javascript

1. 함수 max(num1, num2) 정의
2. 결과값 = num1, num2에서 가장 큰 값
3. 결과값을 리턴

시작:
1. 결과 = max(3, 5)  # max 함수에 3과 5를 입력
2. 결과값 출력

위의 pseudocode의 결과값을 보여주세요
```

ChatGPT:

Bard:

Bing:

참고용 자료:

[되도록 나중에 보기: ✂ 자력갱생으로 해결 못할 경우, 참고자료 ✂](https://github.com/VintageAppMaker/AIForJavascript/blob/main/doc/1/1.context/Context_thinking_5.md)

### 

4.2 Ask AI: ChatGPT, Bard, Bing

[#TODO](https://adsloader.bitbucket.io/#TODO)

```javascript

1. 함수 max(num1, num2) 정의
2. 결과값 = num1, num2에서 가장 큰 값
3. 결과값을 리턴

시작:
1. 결과 = max(3, 5)  # max 함수에 3과 5를 입력
2. 결과값 출력
위의 pseudocode에서 
max 함수가 num1, num2 대신 
연속되는 숫자열중 가장 큰 값을 반환하도록
수정해주세요
```

ChatGPT:

Bard:

Bing:

참고용 자료:

[되도록 나중에 보기: ✂ 자력갱생으로 해결 못할 경우, 참고자료 ✂](https://github.com/VintageAppMaker/AIForJavascript/blob/main/doc/1/1.context/Context_thinking_6.md)

### 

4.3 Ask AI: ChatGPT, Bard, Bing

[#TODO](https://adsloader.bitbucket.io/#TODO)

```javascript


제목: 1인기업 평소습관 - 회전율과 BEP  

취지의 글(주제):
	주제에 대해 간략히 쓴다. 

	사업에서 0순위는 생존이고 매입과 매출이다. 
	이를 본능적으로 파악하기 위해서 평소에 관심을 가지고
	주위를 둘러보는 것이 중요하다. 

	"매입, 매출"의 중요성을 간략히 설명한다. 
	회전율과 BEP를 자영업자와 일반인이 이해가능하도록 정의한다. 

평생의 습관(예제):
	"매입, 매출"을 기준으로 평소의 습관을 설명한다. 
	일상에서 만나는 음식점과 가계들을 "매입, 매출" 습관으로 해석하다. 
	스토리텔링으로 예제를 설명한다

글쓰기 시작:

	취지의 글("1인기업에서 매입매출")을 쓴다. 
	평생의 습관("점심에간 국수집의 생존가능성")을 쓴다. 

	긍정의 글로 마무리한다. 

-------

위의 pseudo code 대로  스토리텔링 형식의 글을 만들어줘

```

ChatGPT:

Bard:

Bing:

참고용 자료:

[되도록 나중에 보기: ✂ 자력갱생으로 해결 못할 경우, 참고자료 ✂](https://github.com/VintageAppMaker/AIForJavascript/blob/main/doc/1/1.context/context_writing.md)

# 

5. Context 형식으로 prompt 만들기 정리

생성AI는 대부분 할루시네이션을 발생시킨다. 할루시네이션(Hallucination)은 인공지능(AI)이 맥락과 관련 없거나 사실이 아닌 내용을 마치 옳은 답처럼 내놓는 현상을 말한다. **생성AI는 말 그대로 생성을 할 뿐이지 진위여부를 판별하거나 추론**을 하지 못한다.

```
Context를 만들기 위해 순차적으로 쓴다 
1. 데이터부터 정의한다. 
2. 이전 프롬프트가 만든 Context를 기반으로 기술한다. 
3. 나온 결과는 답이 아니라 방법일 뿐이다. 

방법과 방법의 Thread(실타래로 이해)를 관리해야 한다. 긴 문장으로 1번에 써야 한다 명령이 되어야 한다. 대화가 되는 순간 오류가 발생한다.
```

결국, 프롬프트 자체가 중요한 것이 아니다.

1. 맥락을 만드는 프롬프트 구성력
2. 결과를 이해할 수 있는 문해력

이 필요하게 된다. 결론적으로 Prompt Engineering은 개발자 사고방식의 문맥구성 능력과 "프롬프트 결과에 대한 도메인 문해력"이 존재해야 한다. 쉽게 말해 "전문가"들에게 필요한 도구이며 문해력이 없는 일반인들에게는 노코드 툴보다 활용성이 떨어지는 도구이다.

![](https://adsloader.bitbucket.io/doc/study/5/images/prompt_ex_1.png)

- [핵개인 - 전문가의 분야가 공유되는 시대](https://www.youtube.com/watch?v=N_I51A0suKg)

# 

6. Missions

아래의 미션에서 나온 HTML을 [jsfiddle](https://jsfiddle.net/)에서 테스트 한다.

### 

6.1 Ask AI: ChatGPT, Bard, Bing

[#TODO](https://adsloader.bitbucket.io/#TODO)

```javascript

HTML과 Javascript  
    기능:  
    2023.12.31을 기준으로 현재시간을 뺀 남은 시간을 표시한다  
    화면:  
    중앙에 디지털 시계를 표시한다.  
    디지털 시계는 남은 시간을 표시한다.

디지털 시계화면 상세:  
글자크기: 32pt  
그림자 : True  
글자색: 붉은색

소스를 만들어줘

```

[#TODO](https://adsloader.bitbucket.io/#TODO)

```javascript
1을 누르면 고양이 그림을 다음주소에서 가져와 보여주고(https://cdn.pixabay.com/photo/2015/11/16/14/43/cat-1045782_1280.jpg), 
2를 누르면  강아지 그림을 다음주소에서 가져오는 (https://cdn.pixabay.com/photo/2016/12/13/05/15/puppy-1903313_1280.jpg) HTML 소스를 만들어줘
```

[#TODO](https://adsloader.bitbucket.io/#TODO)

- 놀라운 검색력

```javascript
HTML 페이지에서 버튼이 개 있다.

[시작], [멈춤]
[시작]을 누르면

https://vgmsite.com/soundtracks/samurai-aces-arcade/cmqeaknx/01_Player%20Select.mp3

플레이한다.

[멈춤]을 누르면 음악을 멈춘다.

소스를 만들어줘

```

[#TODO](https://adsloader.bitbucket.io/#TODO)

```javascript

1. 1 페이지의 HTML을 만든다. 
2. 첫번째는 회사명 
3. 두번째는 회사소개 
4. 세번째는 제품소개 
5. 네번째는 회사위치(지도)와 연락처(메일) 

를 보여주는 반응형 웹페이지를 만들어줘
```