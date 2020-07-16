<script src="https://unpkg.com/typewriter-effect@latest/dist/core.js"></script>

<div id="typewriter">
  
  const instance = new Typewriter('#typewriter', {
      loop: true
  });

  instance.typeString("Hi!")
      .pauseFor(1000)
      .deleteAll()
      .typeString('I am Ronan.')
      .pauseFor(1000)
      .deleteChars(15)
      .typeString('an aspiring<br>Software Developer.')
      .pauseFor(1000)
      .deleteChars(29)
      .typeString('currently learning<br>Your-Skill.')
      .pauseFor(1000)
      .deleteAll()
      .typeString('Check out my work at<br>github.com/your-username')
      .pauseFor(1000)
      .deleteAll()
      .start();

</div>

#typewriter {
    position: absolute;
    font-size: 60px;
    font-family: 'B612', sans-serif;
    font-weight: 700;
    width: 800px;
    margin: 350px 250px;
}
