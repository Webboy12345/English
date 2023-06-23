
<html lang="en">

  <head>

    <title>Document</title>

    <style>

      #cont {

        width: 100%;

        height: 150px;

        text-align: center;

        top: 0;

        color: beige;

        font-size: 90px;

        background-color: rgb(228, 89, 112);

      }

      #name1 {

        text-align: center;

        color: rgb(225, 225, 170);

        overflow-x: hidden;

        width: 100%;

        height: 22px;

        word-spacing: 55px;

        animation: move-left-to-right 10s linear infinite;

      }

      @keyframes move-left-to-right {

        0% {

          transform: translateX(-100%);

        }

        100% {

          transform: translateX(5%);

        }

      }

      #cont1 {

        width: 100%;

        height: 500px;

        background-color: pink;

        align-items: center;

      }

      body {

        font-family: Arial, sans-serif;

        background-color: #f1f1f1;

      }

      .container {

        margin-top: 5%;

        background-color: white;

        border: 1px solid beige;

        border-radius: 5px;

        padding: 20px;

        width: 400px;

        margin: 0 auto;

      }

      h1 {

        text-align: center;

        color: #555;

      }

      input[type="text"],

      input[type="password"] {

        width: 100%;

        padding: 12px 20px;

        margin: 8px 0;

        display: inline-block;

        border: 1px solid #ccc;

        border-radius: 4px;

        box-sizing: border-box;

      }

      button {

        background-color: rgb(260, 100, 130);

        color: #fff;

        padding: 14px 20px;

        margin: 8px 0;

        border: none;

        border-radius: 4px;

        cursor: pointer;

        width: 100%;

      }

      button:hover {

        background-color: rgb(228, 89, 112);

      }

      .cancelbtn {

        width: auto;

        padding: 10px 18px;

        background-color: #f44336;

      }

      .imgcontainer {

        text-align: center;

        margin: 24px 0 12px 0;

        margin-bottom: -1%;

      }

      img.avatar {

        width: 30%;

        border-radius: 50%;

      }

      .container label {

        color: #555;

      }

      .container span {

        float: right;

        padding-top: 16px;

      }

      .clearfix::after {

        content: "";

        clear: both;

        display: table;

      }

      @media screen and (max-width: 300px) {

        .cancelbtn,

        .signupbtn {

          width: 100%;

        }

      }

      input {

        text-transform: uppercase;

      }

    </style>

  </head>

  <body style="padding: 0; margin: 0; overflow: hidden">

    <div id="cont"><div id="name">ᴇɴɢʟɪꜱʜ</div></div>

    <div id="name1">

      ᴇɴɢʟɪꜱʜ ᴇɴɢʟɪꜱʜ ᴇɴɢʟɪꜱʜ ᴇɴɢʟɪꜱʜ ᴇɴɢʟɪꜱʜ ᴇɴɢʟɪꜱʜ ᴇɴɢʟɪꜱʜ ᴇɴɢʟɪꜱʜ ᴇɴɢʟɪꜱʜ

      ᴇɴɢʟɪꜱʜ ᴇɴɢʟɪꜱʜ ᴇɴɢʟɪꜱʜ ᴇɴɢʟɪꜱʜ ᴇɴɢʟɪꜱʜ ᴇɴɢʟɪꜱʜ

    </div>

    <div id="cont1">

      <div class="container" style="position: relative; top: 10%">

        <h1 style="margin-bottom: -20px">Login</h1>

        <form action="/action_page.php">

          <div class="imgcontainer">

            <img

              src="https://yt3.googleusercontent.com/ytc/AL5GRJUuk5ax2E847tIjvvFZVlM-rp_VdX46lkNo70aaoQ=s900-c-k-c0x00ffffff-no-rj"

              alt="Avatar"

              class="avatar"

            />

          </div>

          <div class="clearfix">

            <label for="username"><b>Roll Number</b></label>

            <input id="inp"

              type="text"

              maxlength="10"

              placeholder="Enter Roll Number"

              name="username"

              required

            />

          </div>

          <div class="clearfix">

            <button type="submit">Login</button>

            <button onclick=document.getElementById('inp').value="" type="button" class="cancelbtn" id="butt">Cancel</button>

          </div>

        </form>

      </div>

    </div>

  </body>

  <script>

  document.getGetElementById('butt').onclick() = {

       

  }

  </script>

</html>
