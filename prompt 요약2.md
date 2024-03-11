## 핵심 요약

**1. 프롬프트와 맥락에 대한 이해**

* 프롬프트는 명령이며, 개발자가 AI에게 명령을 내리는 방식입니다.
* 맥락은 프롬프트를 이해하는데 중요한 역할을 합니다.
* 개발자는 맥락을 정의하고 명령을 순차적으로 작성해야 합니다.
* 생성된 결과는 답이 아니라 방법이며, 개발자가 결과를 해석해야 합니다.

**2. 의사코드**

* 의사코드는 실제 프로그래밍 언어를 사용하지 않고 알고리즘을 기술하는 방법입니다.
* 의사코드는 알고리즘을 설계하고 검증하는데 유용합니다.
* 개발자는 의사코드를 실제 프로그래밍 언어로 변환하여 구현할 수 있습니다.

**3. Context 형식으로 prompt 만들기**

* 생성 AI는 맥락과 관련 없거나 사실이 아닌 내용을 만들어낼 수 있습니다.
* 개발자는 맥락을 명확하게 정의하고 프롬프트를 작성해야 합니다.
* 개발자는 결과를 이해하고 해석할 수 있는 문해력이 필요합니다.

**4. Missions**

* HTML 코드를 사용하여 다양한 기능을 구현하는 예시입니다.
* 개발자는 HTML 코드를 학습하여 웹 페이지를 만들고 디자인할 수 있습니다.

**참고**

* HTML 코드는 웹 페이지를 만들기 위한 마크업 언어입니다.
* HTML 코드는 태그와 속성으로 구성됩니다.
* HTML 코드는 웹 개발 분야에서 활용됩니다.

**요약**

* 프롬프트, 맥락, 의사코드, Context 형식으로 prompt 만들기, Missions 등 다양한 개념을 다룹니다.
* 개발자는 생성 AI를 효과적으로 활용하기 위해 관련 개념을 이해하고 적용할 수 있어야 합니다.

**HTML 코드 예시**

* **현재 시간 표시**

```html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>현재 시간 표시</title>
</head>
<body>
    <h1 id="clock"></h1>
    <script>
        function updateTime() {
            let now = new Date();
            let hours = now.getHours();
            let minutes = now.getMinutes();
            let seconds = now.getSeconds();
            
            let clockText = `${hours}:${minutes}:${seconds}`;
            
            document.getElementById("clock").textContent = clockText;
        }
        
        setInterval(updateTime, 1000);
    </script>
</body>
</html>
```

* **고양이/강아지 그림 표시**

```html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>고양이/강아지 그림 표시</title>
</head>
<body>
    <button id="cat-button">고양이</button>
    <button id="dog-button">강아지</button>
    <img id="image" src="">
    <script>
        const catImage = "https://cdn.pixabay.com/photo/2015/11/16/14/43/cat-1045782_1280.jpg";
        const dogImage = "https://cdn.pixabay.com/photo/2016/12/13/05/15/puppy-1903313_1280.jpg";
        
        document.getElementById("cat-button").addEventListener("click", () => {
            document.getElementById("image").src = catImage;
        });
        
        document.getElementById("dog-button").addEventListener("click", () => {
            document.getElementById("image").src = dogImage;
        });
    </script>
</body>
</html>
```

* **음악 재생/멈춤**

```html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">