

<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Salbabida of Hope</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap');

  body { 
    font-family: 'Great Vibes', cursive; 
    line-height: 1.8; 
    background: linear-gradient(135deg, #fdfbfb, #ebedee), url('https://www.transparenttextures.com/patterns/paper-fibers.png');
    background-size: cover;
    padding: 5%; 
    margin: 0;
    color: #2c3e50;
    text-shadow: 1px 1px 2px rgba(255,255,255,0.6);
  }
  h1 { 
    text-align: center; 
    color: #34495e; 
    font-size: 2.5em; 
    margin-bottom: 20px;
  }
  p { 
    font-size: 1.4em; 
    text-align: center; 
  }
  .link { 
    color: #6c5ce7; 
    cursor: pointer; 
    text-decoration: underline; 
    transition: color 0.3s ease;
  }
  .link:hover {
    color: #d63031;
  }
  .hidden { 
    display: none; 
    margin: 15px auto; 
    padding: 15px; 
    background: rgba(255,255,255,0.8); 
    border-left: 4px solid #6c5ce7; 
    max-width: 700px; 
    border-radius: 8px;
    font-size: 1.2em;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  }
  @media (max-width: 600px) {
    body { padding: 15px; }
    h1 { font-size: 2em; }
    p { font-size: 1.2em; }
  }
</style>
<script>
  function toggle(id) {
    var x = document.getElementById(id);
    if (x.style.display === "none" || x.style.display === "") {
      x.style.display = "block";
    } else {
      x.style.display = "none";
    }
  }
</script>
</head>
<body>

<h1>Salbabida of Hope</h1>

<p>In a world where <span class="link" onclick="toggle('hope')">hope</span> seems dim and far,<br>
A grain of <span class="link" onclick="toggle('kindness')">kindness</span> shines like a star,<br>
<strong>Salbabida</strong> — a <span class="link" onclick="toggle('lifeline')">lifeline</span> thrown,<br>
In waters deep, where <span class="link" onclick="toggle('dreams')">dreams</span> are sown.</p>

<div id="hope" class="hidden">Hope is the belief that tomorrow can be better, even when the present is stormy.</div>
<div id="kindness" class="hidden">Kindness, like a life ring, keeps the soul afloat when the waves of hardship rise.</div>
<div id="lifeline" class="hidden">A lifeline is not just a rope — it’s an act of saving someone when they cannot save themselves.</div>
<div id="dreams" class="hidden">Dreams give us direction, like a lighthouse guiding a lost ship.</div>

<p><span class="link" onclick="toggle('efren')">Efren’s heart</span>, a beacon bright,<br>
Sharing <span class="link" onclick="toggle('lessons')">lessons</span> by day and night,<br>
With every <span class="link" onclick="toggle('child')">child</span>, he casts a line,<br>
To guide them forth, their <span class="link" onclick="toggle('spirits')">spirits</span> shine.</p>

<div id="efren" class="hidden">Efren Peñaflorida is a Filipino teacher who started the "Pushcart Classroom" to teach street children.</div>
<div id="lessons" class="hidden">Lessons are not only from books, but from experiences, interactions, and the challenges we face along the way.</div>
<div id="child" class="hidden">Each child has the potential to rise above their struggles with the right guidance.</div>
<div id="spirits" class="hidden">A shining spirit inspires others to keep going despite the storms of life.</div>

</body>
</html>
