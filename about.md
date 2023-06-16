---
layout: page
navigation_title: login
permalink: /about/
---
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>로그인 페이지</title>
    <link rel="stylesheet" href="./style.css" type="text/css" media="all" />
    <script src="./login.js" type="text/javascript"></script>
</head>
<style>
    .main_container{
    border: 0px solid;
}
.blog-cover{
  height: 0px;
  }
.login_container{
    width: 380px; 
    height: 520px; 
    margin: auto; 
    border-radius: 3px; 
    box-shadow: 0px 0px 20px #000;
}
.form_container{
    width: 300px;
    margin: auto;
}
.form_title_div{
    margin: auto; 
    text-align: center;
}
.form_title_p{
    font-weight: bold; 
    font-size: 22px; 
    display: inline-block; 
    padding-top: 8px;
}
.form_input{
    width: 98%; 
    height: 30px; 
    border: 1px solid; 
    border-radius: 3px; 
    border-color: gray;
}
.form_item_name{
    color: gray;
}
.form_text_alert{
    height: 20px;
}
.form_text_alert_padding{
    padding-bottom: 10px;
}
.form_submit_button{
    width: 100%; 
    height: 44px; 
    background-color: rgb(83, 154, 236); 
    border: 1px; 
    border-radius: 3px; 
    color: white; 
    font-size: 17px; 
    font-weight: 500;
}
</style>
<body>
    <div id="container" class="main_container">
        <div style="padding: 20px;"></div>
        <div class="login_container">
            <div class="form_container">
                <form name="login_form" action="/cookie" method="get">
                    <div class="form_title_div">
                        <p class="form_title_p">Login</p>
                    </div>
                    <div>
                        <div>
                            <a class="form_item_name">username</a>
                        </div>
                        <div>
                            <input type="text" name="username" placeholder="name" class="form_input"/>
                        </div>
                        <div class="form_text_alert_padding">
                            <div id="alert_username" class="form_text_alert"></div>
                        </div>
                    </div>
                    <div>
                        <div>
                            <a class="form_item_name">Email</a>
                        </div>
                        <div>
                            <input type="text" name="email" placeholder="E-mail" class="form_input"/>
                        </div>
                        <div class="form_text_alert_padding">
                            <div id="alert_email" class="form_text_alert"></div>
                        </div>
                    </div>
                    <div>
                        <div>
                            <a class="form_item_name">Password</a>
                        </div>
                        <div>
                            <input type="password" name="password" placeholder="Enter password" class="form_input" />
                        </div>
                        <div class="form_text_alert_padding">
                            <div id="alert_password" class="form_text_alert"></div>
                        </div>
                    </div>
                    <div>
                        <div>
                            <a class="form_item_name">Confirm Password</a>
                        </div>
                        <div>
                            <input type="password" name="password2" onfocus="" placeholder="Enter password again" class="form_input" />
                        </div>
                        <div class="form_text_alert_padding">
                            <div id="alert_password2" class="form_text_alert"></div>
                        </div>
                    </div>
                    <div style="height: 10px;"></div>
                    <div>
                        <button type="button" class="form_submit_button" onclick="login()">Submit</button>
                    </div>
                </form>
            </div>
        </div>
    </div>
</body>
</html>



