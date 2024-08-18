# Blog

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link href='https://fonts.googleapis.com/css?family=Rubik' rel='stylesheet'>
  <style>
    @media only screen and (max-width: 600px) {
      #d1{
      height:auto;
      width:300px;
      flex-shrink:0;
      flex-basis:100px;
      overflow-y: auto;
      scrollbar-width: none;
      background-color: #A2CA71;
      border-top-right-radius: 15px;
      border-bottom-right-radius: 15px;
    }
    #d2{
      flex-grow:1;
      height:auto;
      margin:0px 10px 0px 10px;
      flex-shrink:0;
      flex-basis:200px;
      overflow-y:scroll;
      scrollbar-width: none;
      background-color: #F6E96B;
      border-radius:15px;
    }
    #d2 article{
      margin-bottom:20px;
      font-size:10px;
      line-height:27px;
    }
    #d2 h1{
      font-size:20px;
      text-align: center;
      margin:30px;
      letter-spacing:1px;
    }
    #i button{
      width:80%;
      height:20px;
      margin-left:10%;
      margin-right:10%;
      margin-bottom:5%;
      margin-top:5%;
      background-color: inherit;
      border:none;
      font-size:10px;
    }
    #d2 div{
      margin:10px;
    }
    #n{
      display:flex;
      align-items:center;
      justify-content: space-between;
      background-color: #387F39;
      height:40px;
    }
    #t{
      margin-left:10px;
      color:white;
      font-size:20px;
    }
    #b{
      margin-right:10px;
      background-color: inherit;
      color:white;
      border:none;
      font-size:10px;
    }
    }
    *{
      margin:0px;
      font-family:'rubik';
    }
    nav{
      display:flex;
      align-items:center;
      justify-content: space-between;
      background-color: #387F39;
      height:70px;
    }
    nav h1{
      margin-left:20px;
      color:white;
      font-size:30px;
    }
    nav button{
      margin-right:20px;
      background-color: inherit;
      color:white;
      border:none;
      font-size:17px;
    }
    nav button:hover{
      border-bottom:3px solid white;
      border-image: linear-gradient(to right, #2fbfcc 0%, #d5be3a 100%) 1;
    }
    .main{
      display:flex;
      height:600px;
      width:auto;
      margin-top:35px;
    }
    footer{
      display:flex;
      align-items: center;
      justify-content: center;
      margin-top:35px;
      height:40px;
      background-color: #BEDC74;
    }
    .sidebar{
      height:auto;
      width:300px;
      flex-shrink:0;
      flex-basis:100px;
      overflow-y: auto;
      scrollbar-width: none;
      background-color: #A2CA71;
      border-top-right-radius: 15px;
      border-bottom-right-radius: 15px;
    }
    .content{
      flex-grow:1;
      height:auto;
      margin:0px 50px 0px 50px;
      flex-shrink:0;
      flex-basis:200px;
      overflow-y:scroll;
      scrollbar-width: none;
      background-color: #F6E96B;
      border-radius:15px;
    }
    .item button{
      width:80%;
      height:30px;
      margin-left:10%;
      margin-right:10%;
      margin-bottom:5%;
      margin-top:5%;
      background-color: inherit;
      border:none;
      font-size:15px;
    }
    .item button:hover{
      border-bottom:3px solid black;
    }
    .content article{
      margin-bottom:20px;
      font-size:18px;
      line-height:27px;
    }
    .content h1{
      font-size:30px;
      text-align: center;
      margin:30px;
      letter-spacing:2px;
    }
    .content::-webkit-scrollbar-track{
      size:5px;
    }
    .content div{
      margin:50px;
    }
  </style>
</head>
<body>
  <header>
    <nav class="n">
      <h1 id="t">Blog Title</h1>
      <div>
        <button id="b">HOME</button>
        <button id="b">ABOUT</button>
        <button id="b">SERVICES</button>
        <button id="b">CONTACT</button>
      </div>
    </nav>
  </header>
  <section class="main">
    <div id="d1" class="sidebar">
      <div id="i" class="item"><button id="b1" onclick="checkb1()">Blog-1</button></div>
      <div id="i" class="item"><button id="b2" onclick="checkb2()" >Blog-2</button></div>
      <div id="i" class="item"><button id="b3" onclick="checkb3()" >Blog-3</button></div>
      <div id="i" class="item"><button id="b4" onclick="checkb4()" >Blog-4</button></div>
      <div id="i" class="item"><button id="b5" onclick="checkb5()" >Blog-5</button></div>
      <div id="i" class="item"><button id="b6" onclick="checkb6()" >Blog-6</button></div>
      <div id="i" class="item"><button id="b7" onclick="checkb7()" >Blog-7</button></div>
      <div id="i" class="item"><button id="b8" onclick="checkb8()" >Blog-8</button></div>
      <div id="i" class="item"><button id="b9" onclick="checkb9()" >Blog-9</button></div>
      <div id="i" class="item"><button id="b10" onclick="checkb10()" >Blog-10</button></div>
      <div id="i" class="item"><button id="b11" onclick="checkb11()" >Blog-11</button></div>
      <div id="i" class="item"><button id="b12" onclick="checkb12()" >Blog-12</button></div>
      <div id="i" class="item"><button id="b13" onclick="checkb13()" >Blog-13</button></div>
    </div>
    <div id="d2" class="content">
      <div>
      <h1 id="demo">BLOG-1:</h1>
      <article>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi ipsum eos expedita odio architecto molestias quisquam porro eligendi autem? Quibusdam mollitia non maxime veritatis quaerat. Repellendus sunt at distinctio accusantium adipisci quaerat quae, deserunt atque sed repudiandae quia doloremque deleniti fugit neque! Eveniet nemo, sint nihil voluptas ducimus distinctio in!</article>
      <article>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolorum et quisquam, vero doloribus fugit, earum laborum ullam qui cumque repellendus facilis temporibus. Delectus laudantium reprehenderit sapiente quasi tenetur praesentium maxime, voluptates reiciendis, cum sint tempora? Placeat ab incidunt quidem, consequuntur dolore dolorem voluptatibus inventore possimus ducimus pariatur, laudantium dolor omnis officiis commodi minus enim! Facere voluptatem eius, exercitationem ratione eligendi, minima, explicabo dicta hic ut iure sequi? Aliquam doloremque tenetur hic cupiditate natus fugiat excepturi pariatur dolores facilis earum accusamus, molestiae aspernatur, rerum quidem? Aliquid iste recusandae reprehenderit vel cupiditate ab ipsum, fugiat quae libero pariatur corporis nemo aut eum?</article>
      <article>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi ipsum eos expedita odio architecto molestias quisquam porro eligendi autem? Quibusdam mollitia non maxime veritatis quaerat. Repellendus sunt at distinctio accusantium adipisci quaerat quae, deserunt atque sed repudiandae quia doloremque deleniti fugit neque! Eveniet nemo, sint nihil voluptas ducimus distinctio in!</article>
      <article>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quibusdam omnis recusandae consequatur iusto! Id, delectus eius! Fugit, sequi? Cupiditate voluptatum cumque dolorem quod perspiciatis consequuntur doloribus suscipit ipsa, magnam eos molestias explicabo, veritatis doloremque! Impedit, perspiciatis quisquam. Voluptate quasi commodi cum sunt. Illum alias rem necessitatibus nesciunt in dolorum nam nisi blanditiis, aut, sed eum quo eveniet repellat? Inventore labore odit praesentium! Esse, nesciunt quas! A architecto, fugiat facilis saepe eaque fugit, natus accusamus adipisci quasi rem excepturi, amet labore quod expedita officiis ab! Repudiandae voluptas molestias vel molestiae, eos sint rerum nulla cum, qui velit eveniet incidunt aliquam quas!</article>
      <article>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi ipsum eos expedita odio architecto molestias quisquam porro eligendi autem? Quibusdam mollitia non maxime veritatis quaerat. Repellendus sunt at distinctio accusantium adipisci quaerat quae, deserunt atque sed repudiandae quia doloremque deleniti fugit neque! Eveniet nemo, sint nihil voluptas ducimus distinctio in!</article>
      <article>Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus numquam saepe sit nobis nulla odio! Ut ab magnam animi rerum. Placeat nostrum praesentium veniam velit consequatur. Esse laudantium nulla quibusdam, vel ullam architecto ad eum tempora, optio facilis voluptatem, excepturi dolor quisquam incidunt voluptate perferendis quaerat eveniet. Molestias nisi cumque rem corrupti obcaecati reiciendis illo unde labore est quae? Cupiditate, ad accusantium amet quaerat molestiae iusto similique dicta laborum dolore error. Laborum accusantium expedita nulla ipsum, adipisci perspiciatis ullam cum dignissimos incidunt sapiente nihil consequatur sint illo deserunt voluptas error. Vitae placeat porro aliquam dolore accusantium corporis molestiae delectus excepturi.</article>
      <article>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi ipsum eos expedita odio architecto molestias quisquam porro eligendi autem? Quibusdam mollitia non maxime veritatis quaerat. Repellendus sunt at distinctio accusantium adipisci quaerat quae, deserunt atque sed repudiandae quia doloremque deleniti fugit neque! Eveniet nemo, sint nihil voluptas ducimus distinctio in!</article>
    </div>
    </div>
  </section>
  <footer>
    <p>All copyrights are reserved to Likitha</p>
  </footer>
  <script>
    function checkb1(){
      document.getElementById('demo').innerHTML='BLOG-1:';
    }
    function checkb2(){
      document.getElementById('demo').innerHTML='BLOG-2:';
    }
    function checkb3(){
      document.getElementById('demo').innerHTML='BLOG-3:';
    }
    function checkb4(){
      document.getElementById('demo').innerHTML='BLOG-4:';
    }
    function checkb5(){
      document.getElementById('demo').innerHTML='BLOG-5:';
    }
    function checkb6(){
      document.getElementById('demo').innerHTML='BLOG-6:';
    }
    function checkb7(){
      document.getElementById('demo').innerHTML='BLOG-7:';
    }
    function checkb8(){
      document.getElementById('demo').innerHTML='BLOG-8:';
    }
    function checkb9(){
      document.getElementById('demo').innerHTML='BLOG-9:';
    }
    function checkb10(){
      document.getElementById('demo').innerHTML='BLOG-10:';
    }
    function checkb11(){
      document.getElementById('demo').innerHTML='BLOG-11:';
    }
    function checkb12(){
      document.getElementById('demo').innerHTML='BLOG-12:';
    }
    function checkb13(){
      document.getElementById('demo').innerHTML='BLOG-13:';
    }
  </script>
</body>
</html>
