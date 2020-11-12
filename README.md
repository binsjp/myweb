<html>
    <head>

        <title>binsjp</title> <!-- 주소창 이름-->
  <meta charset="UTF-8">
       
       
        <link rel="stylesheet" href="https://www.w3schools.com/html/styles.css"> <!-- css사용. -->
       
        
       <!--link rel="stylesheet" href="styles.css"-->
        <style>
             
           
             
             h1 {
                color: floralwhite;
                 font-family: monospace;
                 font-size: 200%;
                  text-align: center;
                 
             }
             
              h2 {
         
                 font-family: cursive;
                 font-size: 200%;
             }
             
              h3 {
                 color: darkblue;
                 font-family: fantasy;
                 font-size: 100%;
                   text-align: center;
             }
             
              p {
                 color: ghostwhite;
                 font-family: monospace;
                 font-size: 100%;
                border: 1px solid darkblue; 
       padding-top: 5px; padding-bottom: 5px; padding-left: 5px; padding-right: 5px;
                margin-top: 10px; margin-right: 10px; margin-left: 5px; 
                   text-align: center;
                
                 
             } <!--보더는 테두리, 패딩은 보더 안쪽 크기, 마진은 보더 바깥 크기-->
             
             menu {
  display: block;
  list-style-type: disc;
  margin-top: 1em;
  margin-bottom: 1em;
  margin-left: 0;
  margin-right: 0;
  padding-left: 50px;
}
        
        </style>
    </head>
    <body style="background-color: cornflowerblue; color:white">

        <h1 style= "font-size: 30px"> &#10024; Willkommen &#10024; 환영합니다 &#10024; Welcome &#10024;</h1>
        
            <p style="font-size: 18; font-family:monospace">Resin-Accessoires made by <b>binsjp</b>© </p>
            <p><img src="keyring_1.jpg" alt="sso" style="width:200px;height:200px;">
           <img src="shaker_4.png" alt="shakers" style="width:200px;height:200px;">
    
                <img src="work.png" alt="uv" style="width:200px;height:200px;"></p>

       
        <h3 style="color:floralwhite;">&#129505;Menu&#129505;</h3>
        
        
          <a href="Shakers.html">
              <p><input type="button" value="Shakers" onclick="
        document.querySelector('body').style.backgroundColor='blue';
                document.querySelector('body').style.color='white'";></p></a>
                                                              
       
       <a href="Keyring.html">
         <p> <input type="button" value="Keyrings" onclick="
        document.querySelector('body').style.backgroundColor='blue';
                document.querySelector('body').style.color='white'";></p>
           <!--p style="color:cadetblue; font-size:16; font-family:monospace">Keyrings</p></a--> <!-- paragraph p 줄바꿈 자동임. 꾸며주기-->
         
        
           <a href="Nametags.html">
               <p><input type="button" value="Nametags" onclick="
        document.querySelector('body').style.backgroundColor='blue';
                document.querySelector('body').style.color='white'";></p>
               <!--p style="color:darkseagreen; font-size:16; font-family:monospace">Nametags</p></a-->
            
        
        <a href="Earrings.html">
            <p><input type="button" value="Earrings" onclick="
        document.querySelector('body').style.backgroundColor='blue';
                      document.querySelector('body').style.color='white'";></p></a>
               
               
            
            
        <!--p style="color:cadetblue; font-size:16; font-family: monospace">Earrings</p></a--><!-- anker, hypertext-referens-->
      <br><br><br>
            
           <hr style="color: aliceblue"><!-- 줄긋기-->
     
            <h3>Copyright Seunghee</h3>
               
           
        <p id="demo"></p>
            <script>
            var d= new Date("2020/11/12");
            document.getElementById("demo").innerHTML=d;
            </script>
        <br>
        <h1>header1</h1>
        
        <br>
        <h2>header2</h2>
        <br>
        <h3>header3</h3>
         <br>
        <h4 style="color:blue; ">header4</h4>
         <br>
        <h5>header5</h5>
         <br>
        <h6>header6</h6>
        <br>
        
        <ol> <!--순서list-->
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

<ul><!--순서x-->
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
        
  <br>
        <menu type="context" id="mymenu">
  <menuitem label="Refresh" onclick="window.location.reload();" icon="ico_reload.png">
  </menuitem>
  <menu label="Share on...">
    <menuitem label="Twitter" icon="ico_twitter.png"
    onclick="window.open('//twitter.com/intent/tweet?text='+window.location.href);">
    </menuitem>
    <menuitem label="Facebook" icon="ico_facebook.png"
    onclick="window.open('//facebook.com/sharer/sharer.php?u='+window.location.href);">
    </menuitem>
  </menu>
  <menuitem label="Email This Page"
  onclick="window.location='mailto:?body='+window.location.href;"></menuitem>
</menu>
        
    </body>
    
</html>
