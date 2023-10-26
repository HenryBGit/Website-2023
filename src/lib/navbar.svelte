<nav>
    <ul>
        <a href="/"><img src="\Images\Night school studios logo.jpg" class="logo-img" alt="Night School Stuios Logo"></a>
        <div class="container">
                <div class="text">
                    <li>
                        <a href="/games"> Games
                            <div class="border"></div>
                        </a>                        
                    </li>
                    <li>
                        <a href="/about"> About
                            <div class="border"></div>
                        </a>                        
                    </li>
                    <li>
                        <a href="/api"> Api Stuff
                            <div class="border"></div>
                        </a>                        
                    </li>
                    <!-- Social Media icons and links -->
                    <div class="icons">
                        <li><a href="https://www.instagram.com/nightschoolstudio/"><i class="fa-brands fa-instagram"></i></a> </li>
                        <li><a href="https://twitter.com/nightschoolers"><i class="fa-brands fa-twitter"></i></a></li>
                        <li><a href="https://www.youtube.com/c/NightSchoolStudio"><i class="fa-brands fa-youtube"></i></a></li>
                        <li><a href="https://www.facebook.com/nightschoolstudio"><i class="fa-brands fa-facebook"></i></a></li>
                        <li><a href="https://www.tiktok.com/@nightschoolstudio"><i class="fa-brands fa-tiktok"></i></a></li>
                    </div>
            </div>
        </div>   
    </ul>
</nav>
<style>
nav {
    width: 100%;
    overflow: hidden;
}
nav ul {
    display: flex;
	text-decoration: none;
	list-style-type: none;
	margin: 0;
	overflow: hidden;
}
nav li a {
    font-size: 25px; 
	color: white;
	text-decoration: none;
	font-family: 'Cinzel', serif;
}
nav a img {
    padding-top: 3%;
    padding-left: 7%;
    width: 200px;
    display: flex;
    overflow: hidden;
    justify-content: right;
    padding: 0;
}
nav a img:hover {
    opacity: 0.7;
}

/*positioning the icons*/
.icons {
    display: inline-flex;
    justify-content: right;
    gap:7px;
    align-items: center;
    overflow: hidden;
    margin:none;
}
/*Social media icons styling*/
i {
    color: gray;
}
i:hover {
    color: white;
    transition: color 0.5s ease-out;
    cursor: pointer;
}

/*Css For underline hover*/
/*Container that holds the content*/
 .container{
  display:grid;
  grid-template-columns:1fr;
  width: 75%;
}
/*styling for the underline*/
.border{
  height:2px;
  width:0;
  background:red;
  transition: width .3s linear;
}
/*Positioning the text*/
.text {
    display:inline-flex;
    gap: 10px;
    align-items: center;
    justify-content: right;
}
/*width of the underline*/
.text a:hover .border{
  width:65%;
}

</style>