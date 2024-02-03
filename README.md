
<html lang="en">
    <head>
        <link rel="stylesheet" href="./style/css/styles.css">
        
    </head> 
    <body>
        <div class="container">
            <div >
                <h1 class = "header_text">Will You Be My Valentines</h1>
            </div>
            <div class="gif_container">
                <img src="https://media.giphy.com/media/LnKonfpQ44fNvuGLkA/giphy.gif" alt="Cute animated illustration">
            </div>
            <div class = "buttons">
                <button class="btn" id="noButton" onmouseover="moveButton()">No</button>
                <script>
                    function nextPage() {
                        window.location.href = "yes.html";
                    }
                    
                    function moveButton() {
                        var x = Math.random() * (window.innerWidth - document.getElementById('noButton').offsetWidth);
                        var y = Math.random() * (window.innerHeight - document.getElementById('noButton').offsetHeight);
                        document.getElementById('noButton').style.left = `${x}px`;
                        document.getElementById('noButton').style.top = `${y}px`;
                    }
                </script> 
            </div>
        </div>
       
    </body> 
</html>

<html>
<head>
  <title>My Page</title>
</head>
<body>
  <button onclick="showNewPage()">Yes</button>
  <div id="newPageContent" style="display: none;">
   
<html lang="en">
    <head>
        <link rel="stylesheet" href="./style/css/yes_styles.css">
        
    </head> 
    <body>
        <div class="container">
            <div >
                <h1 class = "header_text">Yippie!!! </h1>
            </div>
            <div class="gif_container">
                <img src="https://i.pinimg.com/originals/ca/cd/fb/cacdfbfcbb04a05af340446db3d5cb4d.gif" alt="Cute animated illustration">
            </div>
            <p class = "text"> Cant Wait Until Valentines Babe</p>
        </div>
       
    </body> 
</html>
    <h1>LOVE YOU BABE</h1>
    <p>Happy Valentine's Day when it comes babe!!!! You make my heart skip a beat, and every moment with you is a cherished gift. Grateful for the love we share</p>
  </div>

  <script>
    function showNewPage() {
      document.getElementById("newPageContent").style.display = "block";
    }
  </script>
</body>
