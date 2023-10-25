<div style="background-color: black; position: relative;">
  <div style="
    color: darkgrey;   padding: 0; 
    list-style: none; 
    display: table;
    padding-left: 12px;"
  >
    <li><a href="#">LOGO</a></li>

    <div class="floating-projects-about" >
      <li><a href="#">Projects, </a></li>

      <li><a href="#">About</a></li>
    </div>
    <!-- 
    <li><a href="#">Portfolio</a></li>
    <li><a href="#">Blog</a></li>
    <li><a href="#">Contact</a></li> -->
  </div>
</div>

<style>


.floating-projects-about {
  position: absolute; 
  right: 300px; 
  left: auto;
}

  
@media screen and (max-width: 768px) {
  .floating-projects-about {
    position: static;  
    margin-left: 36px;
  }

}

  /* body,html {
  margin: 0;
  font: bold 14px/1.4 'Open Sans', arial, sans-serif;
  background: #000;
} */
ul { 
  /* margin: 150px auto 0;  */
  padding: 0; 
  list-style: none; 
  display: table;
  width: 600px;
  /* text-align: center; */
}
li { 
  display: table-cell; 
  position: relative; 
  padding: 15px 0;
  padding-right: 0;
}
a {
  /* color: black; */
  color: #fff;
  text-transform: uppercase;
  text-decoration: none;
  letter-spacing: 0.15em;
  
  display: inline-block;
  padding: 15px 20px;
  padding-right: 2px;
  padding-left: 2px;
  position: relative;
}
a:after {    
  background: none repeat scroll 0 0 transparent;
  bottom: 0;
  content: "";
  display: block;
  height: 2px;
  left: 50%;
  position: absolute;
  background: #fff;
  transition: width 0.3s ease 0s, left 0.3s ease 0s;
  width: 0;
}
a:hover:after { 
  width: 100%; 
  left: 0; 
}
@media screen and (max-height: 300px) {
	ul {
		margin-top: 40px;
	}
}

</style>