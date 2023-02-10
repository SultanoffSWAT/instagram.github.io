<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Instagram</title>
        <style>
            #cin{
                position:absolute;
                left:870px;
                top:118px;
                text-align: center;
            }
            body{
                background-color: #fafafa;
            }
            #login{
                display:grid;
                align-items: center;
                justify-content: center;
                text-align: center;
                border: 0.1px solid  #ababab;
                width:350px;
                height:323px;
                background-color: white;
            }
            #instagram_logo{
                width: 175px;
                height: 51px;
                margin-top: 46px;
                margin-bottom: 20%;
            }
            #instagram_logo:hover{
                cursor: pointer;
            }
            ::placeholder{
                position: relative;
                left: 7px;
                font-size: 12px;
            }
            input[type="text"]{
                position: relative;
                background-color: red;
                bottom:20px;
                width:268px;
                height:38px;
                background-color: #fafafa;
                border: 0.1px solid #ababab;
                border-radius: 4px;
                font-family: Arial, Helvetica, sans-serif;
                padding-left: 10px;
                font-size:12px;
            }
            input[type="text"]::placeholder{
                font-family: Arial, Helvetica, sans-serif;
                position: relative;
                left:0px;
            }
            input[type="password"]{
                font-family: Arial, Helvetica, sans-serif;
                position:relative;
                bottom:13px;
                width:268px;
                height:38px;
                background-color: #fafafa;
                border: 0.1px solid #ababab;
                border-radius: 4px;
                padding-left: 10px;
                font-size:16px;
            }
            input[type="password"]::placeholder{
                font-family: Arial, Helvetica, sans-serif;
                position: relative;
                left:0px;
            }
            #log_button{
                width:268px;
                height:32px;
                background-color: #65b5fa;
                border-radius: 8px;
                border:none;
                font-family: Arial, Helvetica, sans-serif;
                color: white;
                font-size: 14px;
                font-weight: bold;
                position: relative;
                bottom: 20px;
            }
            #forgot{
                color:#0a3f70;
                text-decoration: none;
                font-size: 13px;
                font-family: Arial, Helvetica, sans-serif;
                position: relative;
                bottom: 16px;
            }
            #forgot:hover{
                cursor:pointer;
            }
            #signup{
                display:grid;
                align-items: center;
                justify-content: center;
                height:63px;
                width: 350px;;
                border: 0.1px solid  #ababab;
                font-family: Arial, Helvetica, sans-serif;
                font-size: 14px;
                margin-top: 10px;
                background-color: white;
            }
            #signup{
                cursor:pointer;
            }
            #getapp{
                font-family: Arial, Helvetica, sans-serif;
                font-size: 14px;
                margin-top: 15px;
                text-align: center;
            }
            #appstore{
                height:40px;
                width: 136px;
            }
            #playmarket{
                margin-left: 4px;
                height:40px;
                width: 134px;
            }
            #phoneimg{
                height: 581px;
                width:410px;
                position: absolute;
                left:450px;
                top:60px;
            }
            #info{
                text-align: center;
                padding-top: 720px;
            }
            .inf{
                text-decoration: none;
                color:  #919191;
                font-family: Arial, Helvetica, sans-serif;
                font-size: 13px;
                font-weight: lighter;
            }
            select{
                border:none;
                background-color: transparent;
                color:  #919191;
                font-family: Arial, Helvetica, sans-serif;
                font-size: 13px;
                -webkit-appearance: none;
            }
            .inf.s:hover{
                text-decoration: underline;
            }
        </style>
    </head>
    <body>
        <div id="cin">
            <div id="login">
                <div>
                    <img id="instagram_logo" src="https://logos-download.com/wp-content/uploads/2016/03/Instagram_Logo_2016.png" alt="instagram">
                </div>
                <div>
                    <input type="text" placeholder="Phone number,username, or email" id="phone">
                </div>
                <div>
                    <input type="password" placeholder="Password" id="password">
                </div>
                <br>
                <div>
                    <input type="submit" value="Log In" id="log_button">
                </div>
                <br>
                <div>
                    <a id="forgot" href="https://www.instagram.com/accounts/password/reset/">Forgot password?</a>
                </div>
            </div>
            <div id="signup">
                <p>Don't have an account? <a href="https://www.instagram.com/accounts/emailsignup/" style="text-decoration:none; color:#0094f6;"><strong>Sign up</strong></a></p>
            </div>
            <p id="getapp">
                Get the app.
            </p>
            <div>
                <a class="logo" href="https://l.instagram.com/?u=https%3A%2F%2Fitunes.apple.com%2Fapp%2Finstagram%2Fid389801252%3Fpt%3D428156%26ct%3Digweb.loginPage.badge%26mt%3D8%26vt%3Dlo&e=AT3vDH0Mc4wQzsa88c7iAOqnypdLwcV_NmsyYoKdNYVScLVEp5-bWjcoeoheUPovjlxa_iGqL_I1N7xbGk-Wqf1zXvou1U6UEtQX7BxzSjceYMy2TCFM8JtCA-J3lLtU08XGM2WEHe-ki3uG5dNKHcKivOXOE5k2BPAwYvD6J-g"><img id="appstore" src="https://static.cdninstagram.com/rsrc.php/v3/yt/r/Yfc020c87j0.png" alt="appstore"></a>
                <a class="logo" href="https://l.instagram.com/?u=https%3A%2F%2Fplay.google.com%2Fstore%2Fapps%2Fdetails%3Fid%3Dcom.instagram.android%26referrer%3Dutm_source%253Dinstagramweb%2526utm_campaign%253DloginPage%2526ig_mid%253D979A5DFD-F382-4CC5-99B5-467816B2D7C5%2526utm_content%253Dlo%2526utm_medium%253Dbadge&e=AT3vDH0Mc4wQzsa88c7iAOqnypdLwcV_NmsyYoKdNYVScLVEp5-bWjcoeoheUPovjlxa_iGqL_I1N7xbGk-Wqf1zXvou1U6UEtQX7BxzSjceYMy2TCFM8JtCA-J3lLtU08XGM2WEHe-ki3uG5dNKHcKivOXOE5k2BPAwYvD6J-g"><img id="playmarket" src="https://static.cdninstagram.com/rsrc.php/v3/yz/r/c5Rp7Ym-Klz.png" alt="playmarket"></a>
            </div>
        </div>
        <img id="phoneimg" src="phone.png" alt="phone">
        <div id="info">
            <p>
                <a class="inf s" href="https://www.instagram.com/">Meta</a>&emsp;
                <a class="inf s" href="https://www.instagram.com/">About</a>&emsp;
                <a class="inf s" href="https://www.instagram.com/">Blog</a>&emsp;
                <a class="inf s" href="https://www.instagram.com/">Jobs</a>&emsp;
                <a class="inf s" href="https://www.instagram.com/">Help</a>&emsp;
                <a class="inf s" href="https://www.instagram.com/">API</a>&emsp;
                <a class="inf" href="https://www.instagram.com/">Privacy</a>&emsp;
                <a class="inf" href="https://www.instagram.com/">Terms</a>&emsp;
                <a class="inf" href="https://www.instagram.com/">Top Accounts</a>&emsp;
                <a class="inf" href="https://www.instagram.com/">Locations</a>&emsp;
                <a class="inf" href="https://www.instagram.com/">Instagram Lite</a>&emsp;
                <a class="inf" href="https://www.instagram.com/">Contact Uploading & Non-Users</a>&emsp;
            </p>
            <div>
                <p class="inf">
                    <select id="lang">
                    <option>English</option>
                    <option>Kazakh</option>
                    <option>Russian</option>
                    <option>Chinese</option>
                    <option>Japanese</option>
                    <option>Arabic</option>
                    <option>Hindi</option>
                    <option>France</option>
                </select>
                © 2023 Instagram from Meta</p>
            </div>
        </div>
    </body>
</html>
