# movie-review-<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Đánh Giá Top Phim Hay Nhất</title>
    <style>
        /* Thiết lập giao diện cơ bản */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f0f2f5;
            color: #333;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: #1a1a1a;
            color: #ffffff;
            text-align: center;
            padding: 2.5rem 0;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .container {
            max-width: 900px;
            margin: 3rem auto;
            padding: 0 20px;
        }

        /* Thiết kế thẻ bài viết (Movie Card) */
        .movie-card {
            display: flex;
            background-color: #ffffff;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            margin-bottom: 2.5rem;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .movie-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
        }

        .movie-image {
            width: 350px;
            height: auto;
            object-fit: cover;
            flex-shrink: 0;
        }

        .movie-info {
            padding: 25px;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .movie-title {
            margin: 0 0 10px 0;
            font-size: 1.8rem;
            color: #e50914; /* Màu đỏ phong cách Netflix */
        }

        .movie-rating {
            font-size: 1.1rem;
            font-weight: bold;
            color: #f39c12; /* Màu vàng ngôi sao */
            margin-bottom: 15px;
        }

        .movie-desc {
            line-height: 1.6;
            color: #555;
            text-align: justify;
        }

        /* Thiết kế cho màn hình nhỏ (Điện thoại) */
        @media (max-width: 768px) {
            .movie-card {
                flex-direction: column;
            }
            .movie-image {
                width: 100%;
                height: 300px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Top Phim Kinh Điển Đáng Xem Nhất</h1>
        <p>Góc review những tác phẩm điện ảnh xuất sắc</p>
    </header>

    <div class="container">
        
        <div class="movie-card">
            <img src="https://placehold.co/400x600/222/fff?text=Skyfall+007" alt="Skyfall" class="movie-image">
            <div class="movie-info">
                <h2 class="movie-title">1. Skyfall (007)</h2>
                <div class="movie-rating">Điểm đánh giá: ⭐⭐⭐⭐⭐ (9/10)</div>
                <p class="movie-desc">
                    Một trong những phần phim xuất sắc nhất của loạt phim James Bond. Đạo diễn Sam Mendes đã mang đến những pha hành động mãn nhãn kết hợp với chiều sâu tâm lý nhân vật. Hình ảnh tuyệt đẹp và ca khúc chủ đề rúng động khiến bộ phim trở thành một kiệt tác hành động không thể bỏ qua.
                </p>
            </div>
        </div>

        <div class="movie-card">
            <img src="https://placehold.co/400x600/34495e/fff?text=Tokyo+Drift" alt="Tokyo Drift" class="movie-image">
            <div class="movie-info">
                <h2 class="movie-title">2. The Fast and the Furious: Tokyo Drift</h2>
                <div class="movie-rating">Điểm đánh giá: ⭐⭐⭐⭐ (8/10)</div>
                <p class="movie-desc">
                    Tách biệt khỏi mạch truyện chính ban đầu, phần phim này đưa người xem hòa mình vào thế giới ngầm của nghệ thuật đua xe drift tại Nhật Bản. Những góc cua khét lẹt, âm nhạc cực cháy và văn hóa JDM đặc trưng đã biến đây thành một tượng đài trong lòng những người đam mê tốc độ.
                </p>
            </div>
        </div>

        <div class="movie-card">
            <img src="https://placehold.co/400x600/4a235a/fff?text=Ghost+in+the+Shell" alt="Ghost in the Shell" class="movie-image">
            <div class="movie-info">
                <h2 class="movie-title">3. Ghost in the Shell</h2>
                <div class="movie-rating">Điểm đánh giá: ⭐⭐⭐⭐⭐ (9.5/10)</div>
                <p class="movie-desc">
                    Tác phẩm kinh điển định hình lại toàn bộ thể loại Cyberpunk. Khai thác sâu sắc về ranh giới giữa con người và máy móc, triết học về linh hồn và sự tồn tại. Với bối cảnh một thế giới tương lai đồ sộ, bộ phim đã truyền cảm hứng cho hàng loạt bom tấn viễn tưởng thế hệ sau.
                </p>
            </div>
        </div>

    </div>

</body>
</html>
