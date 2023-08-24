
<nav>
    <ul>
        <div class="container">
                <li><a href="/"><img src="\Images\Night school studios logo.jpg" class="logo-img" alt="Night School Stuios Logo"></a></li>
            <div>
                <li><a href="/games">Games</a></li>
              <div class="border"></div>
            </div>
            <div>
                <li><a href="/about"> About Night School Studios</a></li>
              <div class="border"></div>
            </div>
          </div>        
    </ul>
</nav>
<style>
nav {
    width: 100%;
    background-color: rgba(0,0,0,0.1);
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
	color: black;
	text-align: center;
    justify-items: center;
	text-decoration: none;
	font-family: 'Cinzel', serif;
    transition: color ease-in 0.20s;
}
nav li a:hover {
    color: blue;
}
nav li a img {
    width: 200px;
    display: flex;
    overflow: hidden;
}
nav li a img:hover {
    opacity: 0.7;
}
/*Css For underline hover*/
 .container{
  display:grid;
  grid-template-columns:repeat(3, 1fr);
}
.border{
  height:2px;
  width:0;
  background:red;
  transition: width .2s linear;
}

.container div:hover .border{
  width:45%;
}

</style>