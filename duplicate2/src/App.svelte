<script>
import heroDesktop from './assets/hero-desktop.jpg'
import circle from './assets/circle.png'
</script>

<main>
    <img id="circle" src={circle} alt="a circle">
    <div class="circle2"></div>
    <h1>BASE<br>APPAREL</h1>
    <h2><section name="pinkSection" id="pinkSection">WE'RE</section><br>COMING<br>SOON</h2>
    <p>Hello Fellow Shoppers! We're currently building our new<br> fashion store. Add your email below to stay up-to date with<br> announcements and our launch deals.</p>
    <input id="email" name="email" type="text" required>
    <button id="button">></button><br>
    <label for="button"> Please Provide a valid email.</label>

<img id="hero" src={heroDesktop} alt="A woman smiling">
</main>

<style>
   
 

    * {
        font-family: 'Josefin Sans', serif;
        
    }
    main{
        width:100%;
         /*background: linear-gradient(135deg, hsl(0, 80%, 86%), hsl(0, 74%, 74%));
         linear-gradient(135deg, hsl(0, 0%, 100%), hsl(0, 100%, 98%));
         */}
#circle{
    display:flex;
    justify-content: center;
}
.circle2{
    border: 4px solid rgb(246, 181, 187);
	border-radius: 50%;
	width: 29px;
	height: 29px;
} 
  #hero {
/* position:relative;
display:flex;
justify-content: flex-end; */
position:absolute;
    top:0;
    right:0px;
max-width: 42%;
min-width: 42%;
 /* 1440 610 */ 
height: 100vh;

}
h1 {
    margin-left: 208px;
    margin-top:66px;
    font-size: 26px;
    font-family: "Josefin Sans";
    
}
h2{
    font-family: 'Josefin Sans', serif;
font-size: 100px;
margin-left:169px;
}
#pinkSection{
  color:  rgb(201,157,158);
  padding:0px;
  display:contents;
  margin: 0px;
   }
p {
    color:rgb(201,157,158);
   font-weight:300;
   font-size: 20px;
   margin-left: 168px;
 /*  display: flex;
   justify-content: center;
   overflow-wrap: break-word; */
}
input[type=text] {
    
    column-gap: 50px;
    margin-left: 165px;
    border: 2px solid rgb(225,109,109);
    border-radius: 25px;
    width:30%;
    height: 57px;
    font-size: 20px;
    
}
button{
    
    background-color: rgb(250,206,207);
    color: white;
    border:none;
    border-radius: 25px;
    font-size: 30px;
    z-index: 2;
    width:8%;
    height:57px;
    font-weight: bold;
}
label{
    color:red;
    margin-left: 198px;
    
}

</style>

