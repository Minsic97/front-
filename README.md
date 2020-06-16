# front- 쇼핑몰 css

* {
  box-sizing: border-box;
}



.carousel-item {
  width: 100%;
  height: 600px;
  text-align: center;
}

/* background image 사진 설정*/

.carousel-item.item1 {
  background-image: url("../images/logo1.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
}

.carousel-item.item2 {
 background-image: url("../images/logo2.jpg");
 background-repeat: no-repeat;
 background-size: cover;
 background-position: center center;
}

.carousel-item.item3 {
  background-image: url("../images/logo3.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
}

/* background 밑에 h1 글 */

.info h1{
  font-family: serif sans-serif;
  font-size: 18px;
  text-align: center;
  margin-top: 30px;
  margin-bottom: 30px;
}

/* background image 안에 사진 */

.helper {
  display: inline-block;
  vertical-align: middle;
  height: 100%;
}

.intro {
  display: inline-block;
  vertical-align: middle;
}

.intro h2 {
  margin-top: 0;
  font-size: 35px;
  font-weight: 300px;
  color: white;
}

.intro h3 {
  font-size: 35px;
  font-weight: 300px;
  color: white;
  margin-top: 5px;
  margin-bottom: 30px;
}

.intro a {
  font-size: 20px;
  color: white;
  background-color: black;
  padding: 10px 20px;
}

/* body 그림 밑에 글 css*/


.span2{
    text-decoration: line-through;
    color: gray;
}

.container2{
  width: 1050px;
  margin-left: auto;
  margin-right: auto;
}

#img1{
  width: 300px;
  text-align: center;
}

.row{
  float: left;
  margin: 0 10px;
}

.info3 p{
  font-size: 13px;
  color: black;
  text-align: center;
  margin-bottom: 5px;
}

.info3 h3 {
  font-size: 16px;
  color: black;
  margin-top: 10px;
  text-align: center;
}



.info5 {
  font-size: 12px;
  background-color: hotpink;
  color: white;
  font-weight: 200px;
}

.info6 {
  font-size: 12px;
  background-color: red;
  color: white;
  font-weight: 200px;
  margin-right: 3px;
}
