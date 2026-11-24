
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A Little Something for My Batman 🦇</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  background: #090609;
  color: white;
  font-family: Georgia, serif;
  text-align: center;
}

section {
  min-height: 100vh;
  padding: 65px 22px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.first {
  background: radial-gradient(circle, #42101f, #090609 75%);
}

h1 {
  color: #ff739b;
  font-size: 35px;
}

h2 {
  color: #ff9bb7;
}

p {
  font-size: 17px;
  line-height: 1.9;
  max-width: 500px;
}

button {
  background: #e82d60;
  color: white;
  border: none;
  border-radius: 30px;
  padding: 15px 25px;
  font-size: 16px;
  margin-top: 20px;
}

.card {
  border: 1px solid #a83c60;
  border-radius: 20px;
  padding: 25px;
  max-width: 450px;
  background: #1a1018;
}

</style>
</head>

<body>

<section class="first">
  <h1>A LITTLE SOMETHING</h1>
  <h1>FOR MY BATMAN 🦇</h1>
  <p>
    Hey, Batman! ❤️<br>
    You guessed it right...
    but you still don't know what's waiting for you!
  </p>

  <button onclick="document.getElementById('surprise').scrollIntoView({behavior:'smooth'})">
    Open Your Surprise ♡
  </button>
</section>

<section id="surprise">
  <div class="card">
    <h2>HEY, YOU! 🎀</h2>
    <p>
      So, someone finally came to collect their gift!
      Well, here it is.
      A little corner of the internet,
      specially made for you.
    </p>
    <h2>🦇 ❤️ 🐈‍⬛</h2>
  </div>
</section>

<section>
  <h1>TO BE CONTINUED...</h1>
  <p>Your Catwoman has more surprises waiting. ♡</p>
</section>

</body>
</html>

