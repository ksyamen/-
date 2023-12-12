<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>계절의 변화</title>
    <style>
        /* 이전의 CSS 스타일링은 그대로 유지 */
    </style>
</head>
<body>
    <!-- 각 계절 섹션은 변경 없음 -->

    <!-- 2023 계절의 변화 웹페이지 누를 시 동영상 재생 -->
    <a href="#" onclick="playVideo()">
        <section id="webpage-section">
            <h2>2023 계절의 변화 웹페이지</h2>
            <p>클릭하여 웹페이지 동영상을 재생하세요.</p>
        </section>
    </a>

    <!-- 푸터는 변경 없음 -->

    <!-- 자바스크립트를 통해 동영상 재생 처리 -->
    <script>
        function playVideo() {
            // 동영상 URL을 교체해야 합니다.
            var videoUrl = 'https://www.example.com/your-video.mp4';

            // 새 창을 열어 동영상 재생
            window.open(videoUrl, '_blank');
        }
    </script>
</body>
</html>
