# book-my-show
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Book My Show</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #f84464;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        nav ul {
            padding: 0;
            list-style: none;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .search-bar {
            text-align: center;
            margin: 20px 0;
        }
        .search-bar input {
            width: 50%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .search-bar button {
            padding: 10px 20px;
            background-color: #f84464;
            border: none;
            color: white;
            cursor: pointer;
            border-radius: 5px;
        }
        .movie-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
            margin-top: 30px;
        }
        .movie-item {
            background-color: white;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .movie-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 5px;
        }
        .movie-item h3 {
            text-align: center;
            margin: 10px 0;
        }
        .movie-item p {
            text-align: center;
            font-size: 0.9em;
            color: #666;
        }
        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Book My Show</h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">Events</a></li>
                    <li><a href="#">My Bookings</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="search-bar">
        <input type="text" placeholder="Search for movies, events, or venues...">
        <button>Search</button>
    </div>

    <div class="container">
        <h2>Now Showing</h2>
        <div class="movie-grid">
            <!-- Movie 1 -->
            <div class="movie-item">
                <img src="https://via.placeholder.com/200x300" alt="Movie 1">
                <h3>Movie Title 1</h3>
                <p>Genre | Duration | Rating</p>
            </div>
            <!-- Movie 2 -->
            <div class="movie-item">
                <img src="https://via.placeholder.com/200x300" alt="Movie 2">
                <h3>Movie Title 2</h3>
                <p>Genre | Duration | Rating</p>
            </div>
            <!-- Movie 3 -->
            <div class="movie-item">
                <img src="https://via.placeholder.com/200x300" alt="Movie 3">
                <h3>Movie Title 3</h3>
                <p>Genre | Duration | Rating</p>
            </div>
            <!-- Movie 4 -->
            <div class="movie-item">
                <img src="https://via.placeholder.com/200x300" alt="Movie 4">
                <h3>Movie Title 4</h3>
                <p>Genre | Duration | Rating</p>
            </div>
        </div>
    </div>

    <footer>
        <p>© 2024 Book My Show. All rights reserved.</p>
    </footer>
</body>
</html>
