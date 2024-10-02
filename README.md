<html>
    <head>
        <meta charset="utf-8">
        <title>linker</title>
    </head>                   
        <div class="h1">LINKER<sup>v<span id="v"></span></sup></div>
    <hr>
    <span id="nta"></span>    
    <div id="message">
        <label>username:
        <input id="name" type="text" placeholder="alaways needed."><br><br>
        password:
        <input id='password' type='password' placeholder="needed if its an acount.">
        </label>
        <br>
        <button id="button" type="button">enter</button>
        </div><br>
        <div style="overflow:auto; height: 500px;">
        <div class="h2">News</div>
        <h3>For new members:</h3>
        <p>You can get a higher rating if you do spectacular things or you get a new award.</p>
<script>
      function add(){
          var myWindow = window.open("https://arc-conte.github.io/linker.app/", "", "width=800,height=500");
      }
      let width = screen.width;
      let height = screen.height;
      if(height!==500&&width!==800){
          document.getElementById("nta").innerHTML='<button id="tla" onclick="add();">Try The Linker App</button><br><br>';
      }
  var button = document.getElementById("button");
  document.getElementById("v").textContent="1.0.2";
  var onButtonClick = function() {
    var cpass =["cpc","ModSquad","tech"];
    var apass =["ARCoder","code","sci"];
    var mpass =["painthon","slc","chem"];
    var password = document.getElementById("password").value;
    var name = document.getElementById("name").value;
    var greeting="<div id='window'>reload and type in a new linker<sup id='red'>code</sup></div>";
    var other = "<div class='a'><div class='h2'>news</div><p></p><div>";      
    if(name===apass[0] && password===apass[1] || name===apass[2] && password===apass[1]){
        greeting ="<div id='window'>Your LINKER<sup id='red'>Code</sup> was succesful.</div><div class='arc'><br><svg style='width:94px; height: 71px; border-radius:5px'><rect x='2' y='18' fill='rgb(16, 133, 0)' width='92' height='50'></rect><text font-size='25' font-family='Cursive' x='4' y='51'>ARC</text><text fill='red' font-size='25' font-family='Cursive' x='36' y='50'>C</text>         <text transform='rotate(-7 20,40)' font-family='Verdana' x='56' y='43'>oder</text>            <text transform='rotate(8 25,40)' font-family='Verdana' x='64' y='54'>👨🏻‍💻</text>  <text fill='red' transform='rotate(-7 20,40)' font-family='Verdana' x='54' y='42'>oder</text></svg> <label><select><option>bages:</option><option>gold member 🥇</option><option>coder 10💻  </option></select></label><br><br> Welcome, A.R.C.</div><span id='note'>are you geting the new verison</span>";
    }else if(name==="tsc" && password==="ttt" || name==="lab" && password==="ttt"){
        greeting="<div id='window'>Your LINKER<sup id='red'>Code</sup> was succesful.</div><div class='tsc'><br><svg style='width:94px; height: 71px; border-radius:5px'>  <rect x='2' y='18' fill='rgb(16, 133, 0)' width='92' height='50'></rect>            <text font-size='25' font-family='Cursive' x='3' y='51'>TSC</text>            <text fill='red' font-size='25' font-family='Cursive' x='36' y='50'>C</text>            <text transform='rotate(-7 20,40)' font-family='Verdana' x='52' y='43'>at</text>            <text fill='red' transform='rotate(-7 20,40)' font-family='Verdana' x='51' y='42'>at</text>            <text transform='rotate(-8 41,40)' font-family='Verdana' x='69' y='43'>😻</text>            <text transform='rotate(24 41,40)' font-family='Verdana' x='57' y='50'>😺</text>        </svg> rating: <img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><label><select><option>bages:</option><option>join linker 🖥 </option></select></label><br><br> Welcome, T.S.C.</div>";        
    }else if(name===cpass[0] && password===cpass[1] || name===cpass[2] && password===cpass[1]){
        greeting="<div id='window'>Your LINKER<sup id='red'>Code</sup> was succesful.</div><div class='cpc'>C.P.C.<br><img class='icon-cpc' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/avatars/robot_male_2.png'> rating: <img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><label><select><option>bages:</option><option>join linker 🖥 </option></select></label><br><br> Welcome, C.P.C.</div>";
    }else if(name===mpass[0] && password===mpass[1] || name===mpass[2] && password===mpass[1]){
        greeting="<div id='window'>Your LINKER<sup id='red'>Code</sup> was succesful.</div><div class='painthon'>painthon<br><img class='icon-painthon' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/avatars/robot_male_2.png'> rating: <img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><label><select><option>bages:</option><option>join linker 🖥 </option></select></label><br><br> Welcome, painthon<br><ul>Fun Things<li>memfist kity pack<li>christmas pack<li>tescora park</ul></div>";
    }else if(name==="cpc"){
        greeting="<div class='page'><div class='h2'>C.P.C.</div><ul>skills:<li>coding(pjs)<li>trains</ul><h3>entery 1</h3><p>your text here</p><h3>entery 2</h3><p>your text here</p></div>";
    }else if(name==="arc"){
        greeting="<div class='page'><div class='h2'>A.R.C.</div><ul>skills:<li>coding(html, java, pjs, jQuery)<li>light show master<li>electronics</ul><h3>Show and tell</h3><p></p><h3>entery 2</h3><p>your text here</p><h3>entery 3</h3><p>your text here</p></div>";           
    }else if(name==="cards"){
            greeting="<div id='id-card'><h3>A.R.C.</h3><p>coding</p></div>";
    }else{
    }      
    document.getElementById("message").innerHTML = greeting;
  };
  button.addEventListener("click", onButtonClick);
  </script>
 <body>
        search the ARCoder web: <input id="address"> <button onClick="look()">search</button>
        <div id="page"></div>
        <script>
            function savera (){
                localStorage.setItem('ARCoder.org', document.getElementById('s').value);
            }
            localStorage.setItem('gobble.anti', "0");
            function saverc (){
                localStorage.setItem('gobble.anti', document.getElementById('s').value);
            }
            function look (){
                var page = document.getElementById("address").value;
                if(page==="gobble.anti"){
                    document.getElementById("page").innerHTML=localStorage.getItem("gobble.anti");
                }else if(page==="ARCoder.org/91413"){
                    document.getElementById("page").innerHTML="<textarea id='s' value="+localStorage.getItem('ARCoder.org')+"></textarea><button onclick='savera()'>save</button>";                    
                }else if(page==="ARCoder.org"){
                    document.getElementById("page").innerHTML=localStorage.getItem("ARCoder.org");
                }else if(page==="gobble.anti/6711"){
                    document.getElementById("page").innerHTML="<textarea id='s' value="+localStorage.getItem('gobble.anti')+"></textarea><button onclick='saverc()'>save</button>";                    
                }
            };
        </script>
