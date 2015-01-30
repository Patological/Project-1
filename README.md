# Project-1
Code from Udacity Project 1 - Mug Mock
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Orange Udacity Mug</title>
  <link rel="stylesheet" href="css/bootstrap.min.css"> 
  <link rel="stylesheet" href="css/main.css">
</head>

<body>
  <div class="container">
  
    <div class="row">
      <div class="col-md-12">
        <header>
          <h1>Orange Udacity Mug</h1>
        </header>
      </div>
    </div>
    
    <div class="row">
      <div class="col-md-5">
        <img src="images/mug.png" class="img-responsive" alt="Udacity Mug">
        <div class="section">
          <header>
            <h2>Main Features</h2>
          </header>
          
            <ul>
              <li>Holds your favorite drink</li>
              <li>Energizing color</li>
              <li>Reminds you to learn</li>
            </ul>
        </div>
      </div>
      
      <div class="col-md-7">
        <header>
            <h2>A Good Way to Start a Day</h2>
        </header>
          <article>
            <p>Bacon ipsum dolor sit amet shoulder drumstick spare ribs shank, magna in sirloin. Turducken dolore tempor irure tenderloin pork belly shankle. Excepteur in strip steak pork chop voluptate tongue, hamburger nostrud kevin enim nulla ut cow incididunt. Do pancetta swine hamburger incididunt in excepteur irure pig labore est venison dolor ex adipisicing. Labore capicola veniam, commodo corned beef ut non rump swine pork chop exercitation ball tip ham deserunt.</p>
            <p>Ad tri-tip short loin anim beef ribs eu ball tip velit deserunt frankfurter sunt nisi filet mignon. Pork loin quis ham hock mollit cupidatat. Id ground round chuck jerky meatball laborum frankfurter short loin in biltong t-bone doner ea irure. Culpa ex ut id. Nostrud t-bone bresaola pariatur qui tri-tip pork chop, ribeye irure velit pork et in dolore.</p>
            <p>Bacon in sunt dolor fatback excepteur turkey chuck velit proident frankfurter quis. Nisi shank sirloin sed tenderloin. Magna short ribs kielbasa biltong minim. In esse t- bone est tail kielbasa dolor ullamco tongue mollit sint sirloin chuck venison anim. Short ribs dolore adipisicing, bresaola venison cupidatat short loin turducken biltong leberkas andouille elit ad in occaecat. Ground round pariatur cupidatat ham hock magna tempor ea jowl duis.
            </p>
          </article>
      </div>
    </div>
  </div>

</body>
</html>



* {
    font-family: 'Kalimati', Verdana, sans-serif;
}

* {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    -ms-box-sizing: border-box;
    box-sizing: border-box;
}
* {max-width: 1024px}

.container {
  margin-left: 0px;
  margin-right: 0px;
  padding-left:  15px;
  padding-right: 0px;
}

h1 {
    font-weight: lighter;
    font-size: 48px;
    text-align: center;
}

header {
    font-size: normal;
    color: #666666;
    font-weight: 200;
}    

h2 {
    color: #F07C17;
    margin-top: 0px;
    font-size: 24px;
    font-weight: bold;
    text-align: left;
    margin-bottom: 30px;
}

img {
    width: 100%;
    height: auto;
}
.section {
  box-sizing: content-box;
  border-style: solid;
  border-color: #CCCCCC;
  border-width: 1px;
  margin-top: 40px;
  padding-top: 30px;
  padding-left: 30px;
  padding-bottom: 30px;
  line-height: 2;
  font-size: 16px;
}

ul {
margin-top: 0;
}

.header {
    text-align: center;
    color: #666666;
    font-weight: 200;
}

article {
}

p {
    color: #666666;
    line-height: 2;
    text-align: left;
    font-size: 16px;
}

.row {
    width: 100%;
    margin-bottom: 20px;
    margin-right: 15px;
    margin-left: 15px;
}

.col-md-5 {
    max-width: 41.66%; color: #666666; 
    text-align: left; 
    right: 0px;
}

.col-md-7 {
    max-width: 58.33%; color: #666666; 
    padding-right: 5px;
    left: 3px;
}

.col-md-12 {
    width: 100%;
    text-align: center;
    color: #666666;
    padding-top: 25px;
    margin-left: 2px;
}
