#readingfacts.html

<!DOCTYPE html>
<html>
  <head>
    <script src="myscript.js"></script>
    <link rel="stylesheet" href="readingfacts.css">
    <script>
    function openNav() {
  document.getElementById("mySidenav").style.width = "250px";
}
function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
}
  </script>
  </head>
  <body id="back">
    <div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
  <a href="homepage.html">Home</a>
  <a href="#">Find/Near Me</a>
  <a href="addA.html">Add A Library</a>
  <a href="findalibrary.html">What's Trending?</a>
  <a href="#">Why Should You Read?</a>
  <a href="aboutUs.html">About Us</a>
</div>

<span style="font-size:30px;cursor:pointer" onclick="openNav()">&#9776;</span>
</body>
</html>
<h1>READING FACTS!!!</h1>
<img src="https://www.familiesmagazine.com.au/wp-content/uploads/2017/05/Children-reading.jpg" width="1200"  height="600"></img>
  <form id="reading facts" name="reading facts">

  <p><h3>1.IMAGINATION:</h3>
<p>Reading helps your imagination when it comes to creating and thinking.
By reading you are painting those pictures of the story in your mind.
</p>
</p>
<img src="http://opencourtresources.com/ocr/grade3/unitpages/imagination/images/cq_banner_imagination.png" width="600"  height="400"></img>
  <p><h3>2. FOCUS AND CONCENTRATION:</h3>
<p>By sitting still and reading, you are training your body/mind too slow down,
 relax, and focus on what you are reading. This helps you to focus and concentrate on
  other activities because you are used to doing it.
</p>
</p>
<img src="http://ccwkeepaccount.com/wp-content/uploads/2018/07/B_Business_Management_banner_template_01.jpg" width="600"  height="400"></img>
  <p><h3>3. FLUENCY:</h3>
<p>Fluency is defined as the ability to read with speed, accuracy, and expression.
Powerful and effective language. When you read it helps to improve the way you read and speak.
</p>
</p>
<img src="https://1.bp.blogspot.com/-uMii8xKQIEI/WuOLh8ydIEI/AAAAAAAACxo/tDC7FzvnCJMs-xZnknjb3jVA3LPuQWtwQCLcBGAs/s1600/Fluencybanner.png" width="600"  height="400"></img>
  <p><h3>4.INCREASES SELF ESTEEM:</h3>
        <p>With good language skills your are able to be more confident
        within yourself and your ability to communicate with others.
</p>
</p>
<img src="http://www.selfesteemcure.com/images/SEBan_OPTION.jpg" width="600"  height="400"></img>
  <p><h3>5.DISCOVERING NEW THINGS:</h3>
        <p> Reading helps readers to explore new worlds and different
         lives from the comfort of their own home.  You can also discover other languages, culture,
          and places that you have not seen or thought about before.
</p>
</p>
<img src="https://previews.123rf.com/images/epicfail/epicfail1611/epicfail161100231/67874536-thin-line-flat-design-banner-for-discover-web-page-new-solutions-technology-knowledge-and-science-mo.jpg" width="600"  height="400"></img>
  <p><h3>6.KNOWLEDGE:</h3>
       <P>Reading books helps gain knowledge. Books are a rich source of information
       . Reading books on varied subjects imparts information and increases the depth about the subject
       as well. Whenever you read a book, you learn a new information that otherwise would not have known.

 </p>
 </p>
 <img src="https://www.decision-making-solutions.com/images/dkc-banner-image.jpg" width="600"  height="400"></img>

 <p><h3>7. VOCABULARY EXPANSION:</h3>
   <p>The more you read, the more words you gain exposure to,
     and they will inevitably make their way into your everyday vocabulary.

</p>
</p>
 <img src="https://christiandfahey.files.wordpress.com/2012/05/increase-your-vocabulary.png" width="600"  height="400"></img>

<p><h3>8. STRONGER ANALYTICAL THINKING SKILLS:</h3>
  <p>Reading helps your ability to analyze things easily.
     It helps you share your ideas clearly with others.
     For example if you have an opportunity to discuss the book with others,
      you will be able to state your opinions clearly,
      as you have taken the time to really consider all the aspects involved.


</p>
</p>
 <img src="http://emeteducation.org/wp-content/uploads/2014/01/banner2_optimized.jpg" width="600"  height="400"></img>

 <p><h3>9. BETTER WRITING SKILLS:</h3>
   <p>  Reading helps to improve your writing skills. It will help your fluidity, and writing styles.

</p>
</p>
 <img src="http://contentwritingoffice.com/wp-content/uploads/2017/11/ArticleWriting.jpg" width="600"  height="400"></img>
 </body>
</html>



#readingfacts.css

body {
  background: linear-gradient(to top, #679289 0%, #335773 100%);
}
    font-family: "Lato", sans-serif;
}

body {
    font-family: "Lato", sans-serif;
}

p {
  font-size: 25px;
}

h1 {
  font-size: 100px;
}

h3 {
  color: #ee2e31;
}

.sidenav {
    height: 100%;
    width: 0;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    background-color: #071e22;
    overflow-x: hidden;
    transition: 0.5s;
    padding-top: 60px;
}

.sidenav a {
    padding: 8px 8px 8px 32px;
    text-decoration: none;
    font-size: 25px;
    color: #f4c095;
    display: block;
    transition: 0.5s;
    border-bottom: 2px solid #679289;
}

.sidenav a:hover {
    color: #f1f1f1;
}

.sidenav .closebtn {
    position: absolute;
    top: 0;
    right: 25px;
    font-size: 36px;
    margin-right: 50px;
}

@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}


#myscripts.js

function openNav() {
    document.getElementById("mySidenav").style.width = "250px";
}

function closeNav() {
    document.getElementById("mySidenav").style.width = "0";
}
