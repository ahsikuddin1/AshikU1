<!DOCTYPE html>
</html>
<head>
  <link href="/normalize.css" rel="stylesheet">
  <style>
    header {
      text-align: center;
      background-size: cover;
      color: Pink;
    }
    a {
      color: red;
    }
    h1 {
      font-size: 60px;
    }
    img {
      margin: 50px 0px 0px 0px;
      border: 7px solid white;
      border-radius: 20px;
    }
    ul {
      padding: 10px;
      background: green;
    }
    li {
      display: inline;
      padding: 0px 10px 0px 10px;
    }
    article {
      max-width: 400px;
      padding: 3px;
      margin: 0 auto;
    }
    @media (max-width: 400px) {
      h1 {
        font-size: 28px;
        padding: 8px;
      }
      li {
        padding: 5px;
        display: block;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://i.imgur.com/fdsm34K.jpg">
    <h1>Ahsik's Personal Website</h1>
    <ul>
      <li><a href="#">About Me</a></li>
      <li><a href="#">Contact Info</a></li>
    </ul>
  </header>
  <article>
    <h2>About Me</h2>
    <p> My Name is Ahsik Uddin and I recently graduated with a BBA in Business Managment from Brooklyn College. However, my real passion is in the technology field.Ever since I was 8, it was my job in the house to set up computers and software. </p>
    <button>Like</button>
  </article>
  <article>
    <h2>Contact info </h2>
    <p> My email address is Ahsikuddin1@gmail.com .</p>
    <button>Like</button>
  </article>
  <script>
    $("button").on("click", function() {
      alert("Clicked!");
    });
