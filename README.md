<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Góc Học Tập của Thịnh</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --math-color: #e74c3c;
            --physics-color: #f1c40f;
            --literature-color: #9b59b6;
            --bg-color: #ecf0f1;
        }
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
        body { background-color: var(--bg-color); color: #333; padding-top: 70px; }
        nav { background: var(--primary-color); color: white; padding: 1rem; position: fixed; width: 100%; top: 0; z-index: 1000; text-align: center; }
        .container { max-width: 1000px; margin: auto; padding: 20px; }
        h1 { text-align: center; margin-bottom: 30px; color: var(--primary-color); }
        .subject-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; }
        .subject-card { background: white; border-radius: 15px; padding: 20px; box-shadow: 0 5px 15px rgba(0,0,0,0.1); }
        .subject-card h2 { border-bottom: 3px solid; padding-bottom: 10px; margin-bottom: 15px; }
        .math { border-color: var(--math-color); color: var(--math-color); }
        .physics { border-color: var(--physics-color); color: var(--physics-color); }
        .literature { border-color: var(--literature-color); color: var(--literature-color); }
        .note-list { list-style: none; }
        .note-list li { background: #f9f9f9; margin-bottom: 8px; padding: 10px; border-left: 5px solid #ccc; border-radius: 3px; }
        .add-btn { width: 100%; padding: 10px; margin-top: 10px; background: #2ecc71; color: white; border: none; border-radius: 5px; cursor: pointer; }
        footer { text-align: center; padding: 30px; margin-top: 50px; font-size: 0.9rem; color: #7f8c8d; }
    </style>
</head>
<body>
    <nav><h2>📚 TRẠM HỌC TẬP - LỚP 12</h2></nav>
    <div class="container">
        <h1>Lộ trình chinh phục đại học</h1>
        <div class="subject-grid">
            <div class="subject-card">
                <h2 class="math">📐 Toán Học</h2>
                <ul class="note-list">
                    <li><b>Hàm số:</b> Nhớ cực trị hàm bậc 3.</li>
                    <li><b>Nguyên hàm:</b> Bảng công thức trang 122.</li>
                </ul>
                <button class="add-btn">Ghi chú thêm</button>
            </div>
            <div class="subject-card">
                <h2 class="physics">⚡ Vật Lý</h2>
                <ul class="note-list">
                    <li><b>Dao động cơ:</b> x = Acos(ωt + φ).</li>
                    <li><b>Sóng cơ:</b> Giao thoa và sóng dừng.</li>
                </ul>
                <button class="add-btn">Ghi chú thêm</button>
            </div>
            <div class="subject-card">
                <h2 class="literature">📖 Ngữ Văn</h2>
                <ul class="note-list">
                    <li><b>Tây Tiến:</b> Vẻ đẹp bi tráng.</li>
                    <li><b>Việt Bắc:</b> Tình quân dân.</li>
                </ul>
                <button class="add-btn">Ghi chú thêm</button>
            </div>
        </div>
    </div>
    <footer><p>Cố lên Thịnh nhé! 🚀</p></footer>
</body>
</html>
