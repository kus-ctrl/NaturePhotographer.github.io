# NaturePhotographer.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nature Portfolio</title>
    <style>
        body { background: #0b0c10; color: #66fcf1; font-family: 'Segoe UI', sans-serif; text-align: center; }
        header { padding: 50px; }
        h1 { font-size: 3rem; letter-spacing: 5px; }
        .gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; padding: 20px; }
        .gallery img { width: 100%; border-radius: 10px; transition: 0.3s; filter: grayscale(50%); }
        .gallery img:hover { filter: grayscale(0%); transform: scale(1.05); cursor: pointer; }
    </style>
</head>
<body>
    <header>
        <h1>MY NATURE PHOTOGRAPHY</h1>
        <p>Capturing the slick details of the natural world.</p>
    </header>
    <div class="gallery">
        <img src="photo1.jpg" alt="Nature Photo 1">
        <img src="photo2.jpg" alt="Nature Photo 2">
    </div>
</body>
</html>
