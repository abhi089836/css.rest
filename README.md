@import url('https://fonts.googleapis.com/css2?family=Cedarville+Cursive&display=swap');
*{
  margin:0px;
  padding:0px;
  text-decoration:none;
  list-style:border-box;
  font-family:Verdana;
  max-width:1500px;
  overflow:hidden;
}
div-main{
  position:absolute;
  display:flex;
  align-items:center;
  justify-content:space-around;
  width:100%;
  height:10vh;
  background:color:transparent;

}
div-nav1 a{
  color:black;
  font-size:13px;
  padding-right:20px;
  transition:all 0.3s;
}
div-nav1 a:hover{
  color:blue;
}
div-nav2 div-user a{
  color:black;
}
div1 h2{
  padding:200px;
}
div-nav2{
  display:flex;
  align-items:center;
  font-size:13px;
}
div-search{
  border-bottom:2px solid gray;
  padding-bottom:10px;
  margin-right:20px;
}
div-search input{
  width:150px;
  outline:none;
  border:none;
  background-color:transparent;
}
div-search input::placeholder{
  color:black;
}
div-user{
  margin-left:20px;
  padding-bottom:10px;
  cursor:pointer;
  color:black;
}
/*.......Section 1.......*/
div-section1{
  display:flex;
  align-items:center;
  justify-content:space-between;
}
div-section1 div-image img{
  width:50vw;
  max-width:700px;
  margin-right:-5vw;
  margin-top:80px;
}
div-content{
  width:50vw;
  padding:7%;
}
div-content h1{
  color:rgb(57,33,55);
  font-size:55px;
  margin-bottom:15px;
  font-family:Camberia,Cochin,Georgia,Times New Roman,Sans-Serif;
}
div-content p{
  color:rgb(109,97,110);
  margin-bottom:30px;
}
div-content a-btn{
  background-color:rgb(239,122,30);
  color:white;
  display:inline-flex;
  align-items:center;
  padding:20px 30px;
  border-radius:50px;
  transition:all 0.5s;
  cursor:pointer;
}
div-content a-btn i{
  margin-left:20px++;
  font-size:20px;
}
div-content a-btn:hover{
  background-color:rgb(239,121,30,0.712);
  transform:translateX(20px);
}
/*.....Section 2.....*/
div-section2{
  display:flex;
  align-items:center;
  justify-content:space-between;
  padding:0 5%;
}
div-section2 div-image2 img{
  width:40vw;
  max-width:600px;
}
div-section2 div-content2{
  max-width:40vw;
}
div-section2 h2{
  font-family:Cedarville Cursive;
  font-size:30px;
  color:rgb(300,40,22);
}
div-section2 div-content2 h1{
  color:rgb(57,33,73);
  font-size:45px;
  margin-bottom:15px;
  font-family:Camberia,Cochin, Georgia,Times,Times New Roman,Sans-Serif;
}
div-section2 div-content2 p{
  color:rgb(109,97,110);
  margin-bottom:30px;
  font-size:15px;
  line-height:25px;
}
/*.......Section 3.......*/
div-section3{
  padding:7% 5%;
  text-align:center;
}
div-section3 h1{
  font-family:Camberia,Cochin,Georgia,Times New Roman,Times,Sans-Serif;
  font-size:45px;
}
div-section3 div-cardBox{
  padding:70px 0;
  display:flex;
  align-items:center;
  justify-content:space-between;
}
div-card{
  width:270px;
  padding:40px,20px;
  border-radius:15px;
  box-shadow:0 0 40px rgb(254,253,209,0.6);
  cursor:pointer;
  transition:all 0.3s;
  
}
div-card:hover{
  box-shadow:0 0 100px rgb(239,122,30);
  transform:scale(1.02);
}
div-card img{
  width:150px;
  height:150px;
  margin-bottom:45px;
}
div-card h4, div-card p, div-card span{
  text-align:left;
  margin-bottom:15px;
  display:block;
}
div-card p{
  font-size:13px;
  display:-webkit-box;
  -webkit-box-orient:vertical;
  -webkit-line-clamp:2;
  overflow:hidden;
  text-overflow:ellipsis;
}
div-card span{
  color:rgb(241,147,73);
  font-weight:700;
}
/*.....Section 4....*/

div-content4 a-btn{
  background-color:rgb(239,122,30);
  color:white;
  display:inline-flex;
  align-items:center;
  padding:20px 30px;
  border-radius:50px;
  transition:all 0.5s;
  cursor:pointer;
}
div-content4 a-btn i{
  margin-left:20px++;
  font-size:20px;
}
div-content4 a-btn:hover{
  background-color:rgb(239,121,30,0.712);
  transform:translateX(20px);
}
div-section4{
  display:flex;
  align-items:center;
  justify-content:space-between;
}
div-section4 div-image4 img{
  width:40vw;
  max-width:700px;
  margin-top:-50px;
}
div-section4 div-content4{
  width:50vw;
  padding:7%;
}
div-section4 div-content4 h1{
  color:rgb(57,33,55);
  font-size:55px;
  margin-bottom:15px;
  font-family: Camberia;
}
div-section4 div-content4 p{
  color:rgb(109,97,110);
  margin-bottom:30px;
}
div-section4 div-content4 h2{
  font-family: Cedarville Cursive;
  font-size:30px;
  color:rgb(241,147,73);
}
/*....Section 5....*/
div-section5{
  padding:5% 10%;
  margin:10% 0;
}
div-newsletter{
  background-color:rgb(56,42,51);
  border-radius:20px;
  min-height:200px;
  width:100%;
  display:flex;
  align-items:center;
  justify-content:space-around;
}
div-newsletter img{
  width:30vw;
  max-width:450px;
}
div-newsletter div-content5{
  width:30vw;
}
div-newsletter div-content5 h1{
  color:white;
  font-size:40px;
  margin-bottom:40px;
  width:80%;
  font-family: Cedarville Cursive;
}
div-newsletter h2{
   font-family: Cedarville Cursive;
   font-size:30px;
   color:rgb(241,147,73);
}
div-newsletter div-subscribe{
  padding:10px;
  background-color:white;
  border-radius:40px;
  display:flex;
  align-items:center;
  justify-content:space-between;
}
div-newsletter div-subscribe input{
  font-size:15px;
  outline:none;
  border:none;
  width:70%;
  padding:10px;
}
div-newsletter div-subscribe button{
  background-color:rgb(239,122,30);
  border:none;
  color:white;
  border-radius:20px;
  font-size:15px;
  padding:10px 20px;
  cursor:pointer;
}
/*.... Section 6....*/
div-section6{
 padding:0% 10%;
 display:flex;
 justify-content:space-between;
}
div-section6 h2{
  width:200px;
}
div-section6 div3{
  max-width:200px;
}
div-section6 ul li:first-child{
  font-weight:700;
}
div-section6 li, div-section6 p{
  padding:10px 0;
}
div-section6 p, div-section6 a{
  color:gray;
  font-size:14px;
  line-height:22px;
}
div-section6 a:hover{
  color:rgb(239,122,30);
}
/*.... Footer ....*/
div-footer{
  text-align:center;
  padding:1.5% 0;
  margin-top:7%;
  font-size:14px;
  background-color:rgb(239,121,30,0.3);
}







