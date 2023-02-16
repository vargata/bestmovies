<!Doctype html>
<html lang="en">
	<head>
		<title>My portfolio</title>
		<link rel="icon" type="image/x-icon" href="img/tv.png">
		<link rel="stylesheet" href="css/master.css">
		<link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.7.0/styles/default.min.css">
		<script src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.7.0/highlight.min.js"></script>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	</head>
	<body>

		<canvas id="background" ></canvas>
		
		<div class="content_container">
			<h1>Example database project to show the use of subqueries</h1>
		
<pre><code class="language-sql">
SELECT 	r.mov_title AS "The movie",
	r.mov_year AS "released in",
        actor.act_fname AS "starred",
        actor.act_lname AS "by",
        movie_cast.role AS "in the role of",
        r.rev_stars AS "got stars (out of 10)"
FROM
	(SELECT m.mov_id, m.mov_title, m.mov_year, m.rev_stars FROM
        (SELECT movie.mov_id, movie.mov_title, movie.mov_year, rating.rev_stars FROM movie
		INNER JOIN rating
         	ON rating.mov_id = movie.mov_id
         	WHERE mov_year BETWEEN 1980 AND 2000) AS m
        WHERE m.rev_stars > 8) AS r
INNER JOIN movie_cast ON r.mov_id = movie_cast.mov_id
INNER JOIN actor ON actor.act_id = movie_cast.act_id
ORDER BY r.mov_year;

</code></pre>
		
    		<img src="img/movie-database.png" />
    		<img src="img/best_movies.png" />
		</div>
		
		<script src="js/matrix.js"></script>
		<script type="text/javascript">hljs.highlightAll();</script>
	</body>
</html>