            <!DOCTYPE html>
            <html lang="en">

            <head>
              <meta charset="UTF-8">
              <meta name="viewport" content="width=device-width, initial-scale=1.0">
              <meta http-equiv="X-UA-Compatible" content="ie=edge">
              <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Oswald:wght@200..700&display=swap">
              <link rel="preconnect" href="https://fonts.googleapis.com">
              <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
              <link href="https://fonts.googleapis.com/css2?family=Alegreya:ital,wght@0,400..900;1,400..900&display=swap" rel="stylesheet">
              <title>Form For Class 11</title>
              <style>
                * {
                  font-family: Oswald;
                  margin: 0%;
                  padding: 0%;
                }

                .photo {
                  width: 50%;
                }

                h1 {
                  text-align: center;
                  font-size: 3em;
                  background-color: whitesmoke;
                  margin: 15px 15px;
                  border: 2px solid #DFDFDF;
                  border-radius: 20px;

                }

                .text-1 {
                  background-color: whitesmoke;
                  margin: 15px 15px;
                  border: 2px solid #DFDFDF;
                  border-radius: 5px;
                  text-align: center;
                }

                .text-2 {
                  margin: 15px 15px;
                  border: 2px solid #DFDFDF;
                  border-radius: 5px;
                  background-color: whitesmoke;
                  text-align: center;
                }

                .text-3 {
                  text-align: center;
                  margin: 15px 15px;
                  border-radius: 5px;
                  border: 2px solid #DFDFDF;
                  background-color: whitesmoke;
                  color: orangered;
                  font-weight: bolder;
                }

                .main {
                  margin: 0px 10px;
                  margin: 15px 15px;
                  border-radius: 10px;
                  border: 2px solid #5E5E5E;
                  padding: 5px 10px 10px 5px;
                  background: linear-gradient(45deg, #FFED00, #FF3600E3);
                  font-weight: bold;
                  font-family: none;
                  font-family: Alegreya;
                }

                .input {
                  width: 100%;
                }

                .padding {
                  letter-spacing: 10px;
                  padding: 5px 10px 5px 10px;
                }

                .last {
                  text-align: center;
                  font-weight: bolder;
                  font-family: Alegreya;
                }

                .btn {
                  text-align: center;
                  margin: ;
                  width: 80%;
                  padding: 0% 35% 0% 35%;
                  background: linear-gradient(45deg, #00CFFF, #6E00FF);
                  border: none;
                  color: #00FFB0;
                  font-size: 25px;
                  border-left: 2px solid #FF00B0;
                  border-right: 2px solid #FF6E00;
                  border-top: 2px solid #F200FF;
                  border-bottom: 2px solid #00FF0D;
                  width: 0%;
                  padding: 0%;
                  padding: 0px 5em;
                  margin: 0% 10px;
                }

                :hover .btn {
                  color: #FF0096;
                  s
                }

                .apl {
                  font-weight: bolder;
                  font-size: 5em;
                }

                .Bill {
                  text-align: center;
                  padding: 10px 5em;
                }

                .animation {
                  background-color: #7DFF00;
                  padding: 20px 20px;
                  text-align: center;
                  animation: Rahul 5s infinite;
                }

                @keyframes Rahul {
                  0% {
                    transform: scale(1);
                  }

                  50% {
                    transform: scale(1.1);
                    color: #0080ff;
                  }

                  100% {
                    transform: scale(1);
                  }
                }
              </style>
            </head>

            <body>
              <div class="1st">
                <h1>RAHULER SWAPNO FOR CLASS 11 & CLASS 12</h1>
                <br>

                <div class="animation">
                  <h1>Rahul Sharma</h1>
                </div>
                <p class="text-1">Enter Your Name, Class, Roll, Section, Imei Number Properly......</p>
                <hr>
                <p class="text-2">The name and photo associated with your Google account will be recorded when you upload files and submit this form. Your email is not part of your response.</p>
                <hr>
                <p class="text-3">*INDICATE REQUIRED QUESTIONS</p>
                <hr><br>
              </div>

              <!--Main Text Start-->
              <p class="main">Name: <input class="input" type="Name " name="" id="" placeholder="Enter Your Name "></p>
              <br>
              <p class="main">
                11 &nbsp;<input class="padding" type="radio" name="Class" id="11">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                12 &nbsp;<input class="padding" type="radio" name="Class" id="12"></p><br>

              <p class="main">Roll: <input class="input" type="tel" name="Roll" id="Roll" placeholder="Enter Your Roll Number"></p>
              <br>
              <p class="main">Arts <input type="radio" name="Stream" id="Arts">
                Commerce <input type="radio" name="Stream" id="Commerce">
                Science <input type="radio" name="Stream" id="Science">

              </p>
              <br>
              <p class="main">Registration Number <input type="number" name="" id="" placeholder="Your Answer "></p><br>
              <p class="main">IMEI NUMBER.1 <input class="input" type="details.1" name="" id="" placeholder="Your Answer"></p><br>
              <p class="main">IMEI NUMBER.2 <input class="input" type="details.2" name="" id="" placeholder="Your Answer"></p><br>
              <p class="last">
                Upload PDF/ PHOTO of BILL / CASH MEMO purchased in your name and sign in full upon this.(Under 1MB)
              </p>
              <input class="Bill" type="file" name="Bill" id="Bill">
              <input class="btn" type="button" class="apl" value="Submit"><br><br>
            </body>

            </html>
