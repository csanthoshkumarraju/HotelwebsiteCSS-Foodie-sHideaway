# HotelwebsiteCSS-Foodie-sHideaway
/*  * is selecting all html code */
/*  * is selecting all html code */
*
{
  padding:0;
  margin:0;
  box-sizing: border-box
}
html {
  font-size:61.5%
}
body {
  font-family: "inter" sans-serif;
  line-height:1;
  font-weight:600;
  color:#555;
}
/* .hero is class. classes , ids are used to design specified fields or parts in pages */
.hero-section{
  background-color: #e98b38;
  padding: 5rem 0;
  
}
.hero {
  max-width:80rem;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 9.6rem;
}

.heading {
  font_size: 100px;
  font-weight:100px;
  line-height: 1.05;
  color: #333;
  letter-spacing: -0.5px;
  margin-bottom: 3.2rem;
  margin-left: 3.2rem;

  
}
.Description {
  font_size: 2rem;
  line-height: 1.2;
  margin-bottom: 4rem;
  margin-left: 3.2rem;
}
.button:link, .button:visited {
  display: inline-block;
  background-color: #343434;
  color: #F9F6EE;
  text-decoration: none;
  font-size: 1.5rem;
  padding: 1rem 2rem;
  border-radius: 15px;
  transition: all 1s;
  margin-right: 1.6rem;
  margin-left: 3.7rem;
}
.button:hover, 
.button:active {
  background-color:#F9F6EE;
  color: #343434;
  box-shadow: 0 0 0 4px #007FFF;
}

.hero-pic {
  width :100%;
  border-radius: 20px;
  padding: 10px;
}
.Served {
  float: left;
  width: 33.33%;
  padding: 5px;
}
.Human::after {
  content: "";
  clear: both;
  display: table;
}


