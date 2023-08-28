<nav>
    <ul>
        <div class="container">
            <li><a href="/"><img src="\Images\Night school studios logo.jpg" class="logo-img" alt="Night School Stuios Logo"></a></li>
                <div class="text">
                    <li><a href="/games">Games</a></li>
                <div class="border"></div>
                </div>
                <div class="text">
                    <li><a href="/about"> About</a></li>
                <div class="border"></div>
            </div>
            <div class="icons">
                <li><a><i class="fa-brands fa-instagram"></i></a> </li>
                <li><a><i class="fa-brands fa-twitter"></i></a></li>
                <li><a><i class="fa-brands fa-youtube"></i></a></li>
                <li><a><i class="fa-brands fa-facebook"></i></a></li>
                <li><a><i class="fa-brands fa-tiktok"></i></a></li>
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
	justify-content: center;
	text-decoration: none;
	list-style-type: none;
	margin: 0;
	padding: 0;
	overflow: hidden;
}
nav li a {
    font-size: 30px; 
	color: white    ;
	text-decoration: none;
	font-family: 'Cinzel', serif;
    transition: color ease-in 0.35s;
}
nav li a:hover {
    color: blue;
    cursor: pointer;
}
nav li a img {
    padding-left: 7%;
    width: 200px;
    display: flex;
    overflow: hidden;
    border-radius: 25px
}
nav li a img:hover {
    opacity: 0.7;
}
.icons {
    display: inline-flex;
}
i {
    color: gray;
}
i:hover {
    color: white;
}
/*Css For underline hover*/
/*Container that holds the content*/
 .container{
  display:grid;
  grid-template-columns:repeat(4, 1fr);
  width: 100%;
  border: white 2px thick;
}
/*styling for the underline*/
.border{
  height:2px;
  width:0;
  background:red;
  transition: width .2s linear;
}
/*Positioning the text*/
.text {
    height: 1%; 
    padding: 1%;
}
/*width of the underline*/
.container div:hover .border{
  width:12%;
}

</style>