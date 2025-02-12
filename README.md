<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>음악 아카이브</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin: 0; padding: 0; background-color: #f9f9f9; }
        header { background: #333; color: white; padding: 20px; font-size: 24px; }
        section { padding: 20px; }
        .works { display: flex; flex-direction: column; align-items: center; }
        .work { background: white; margin: 10px; padding: 15px; width: 80%; max-width: 600px; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        footer { background: #333; color: white; padding: 10px; position: absolute; bottom: 0; width: 100%; }
    </style>
</head>
<body>
    <header>음악 아카이브</header>
    <section>
        <h2>작품 소개</h2>
        <div class="works">
            <div class="work">
                <h3>작품 제목 1</h3>
                <p>작품 설명 텍스트</p>
                <audio controls>
                    <source src="music1.mp3" type="audio/mp3">
                    브라우저가 오디오 태그를 지원하지 않습니다.
                </audio>
            </div>
            <div class="work">
                <h3>작품 제목 2</h3>
                <p>작품 설명 텍스트</p>
                <audio controls>
                    <source src="music2.mp3" type="audio/mp3">
                    브라우저가 오디오 태그를 지원하지 않습니다.
                </audio>
            </div>
        </div>
    </section>
    <footer>문의: example@email.com</footer>
</body>
</html>
# creative_sunyong
