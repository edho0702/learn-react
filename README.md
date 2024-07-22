# 리액트 프로그래밍

멋사 프론트엔드 스쿨 10기 리액트 프로그래밍 학습 저장소# learn-react


- 과제 세팅

- 과제 마크업

- 과제 마크업 이미지 텍스트 추가

- 과제 폰트 추가

- 과제 스타일링

## html
```
<!DOCTYPE html>
<html lang="ko-KR">

    <head>
        <meta charset="UTF-8" />
        <meta
            name="viewport"
            content="width=device-width, initial-scale=1.0"
        />
        <title>디자인 핸드오프</title>
        <link
            rel="stylesheet"
            href="./src/styles/main.css"
        />
    </head>

    <ul>
        <li>
            <img
                src="src/assets/img/Architecture (1).png"
                alt=""
            />
            <span>History of Architecture</span>
        </li>
        <li>
            <img
                src="src/assets/img/Architecture (2).png"
                alt=""
            />
            <span>Building design</span>
        </li>
        <li>
            <img
                src="src/assets/img/Architecture (3).png"
                alt=""
            />
            <span>Graphics</span>
        </li>
        <li>
            <img
                src="src/assets/img/Architecture (4).png"
                alt=""
            />
            <span>Climatology</span>
        </li>
    </ul>

    <body>

    </body>

</html>
```

## css
```
@import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');

ul {
    display: flex;
    flex-direction: column;
    min-width: 13.75rem;
    max-width: 40rem;
    list-style: none;
    padding-inline: 0;
    margin: auto;
    margin-block: 0;
}

li {
    font-family: pretendard;
    display: flex;
    align-items: center;
    gap: 1.25rem;
    padding: 0.75rem;
    background-color: #141415;
    color: #fff
}
```
