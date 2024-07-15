<!DOCTYPE html>
<html>
    <head>
        <!-- Font Awesome Icon Library -->
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <style>
            *{
                margin:0;
                padding:0;
                box-sizing:border-box;
            }
            .checked {
            color: orange;
            }
            body {
                width:100%;
                min-height:100vh;
                background-color:#1c1a22; /*raisin black */
                display:flex;
                justify-content:center;
                align-items:center;
                padding:40px 0;
            }
            body > div {
                display:flex;
                justify-content:center;
                gap:30px;
                align-items:center;
                flex-wrap:wrap;
            }
            .success {
                width:250px;
                padding:25px;
                background:#8080805c;
                min-height:250px;
                display:flex;
                flex-direction:column;
                justify-content:center;
                align-items:center;
                font-size:1.3em;
                color:#fff;
                backdrop-filter:blur(4px);
                border-radius:1em;
                box-shadow:5px 5px  #8080805c inset;
                cursor:pointer;
            }
            .success:hover{
                animation:animate .4s linear .2s 5;
            }
            @keyframes animate {
                0% {
                    transform:rotateZ(0);
                }
                25% {
                    transform:rotateZ(4deg);
                }
                50% {
                    transform:rotateZ(0);
                }
                75% {
                    transform:rotateZ(-4deg);
                }
                100% {
                    transform:rotateZ(0);
                }
            }
            @media screen and (max-width:568px) {
                .success {
                    display:grid;
                }
            }
        </style>
    </head>
    <body>

        <div>
            <div class="success">
                <h2>HTML</h2>
                <div>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                </div>
            </div>

            <div class="success">
                <h2>CSS</h2>
                <div>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                </div>
            </div>
            
            <div class="success">
                <h2>JAVASCRIPT</h2>
                <h6>Loading...</h6>
                <div>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star"></span>
                </div>
            </div>

            <div class="success">
                <h2>jQuery</h2>
                <h6>Loading...</h6>
                <div>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star "></span>
                    <span class="fa fa-star"></span>
                </div>
            </div>

            <div class="success">
                <h2>Bootstrap 5</h2>
                <div>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                </div>
            </div>

            <div class="success">
                <h2>PHP</h2>
                <h6>Loading...</h6>
                <div>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star "></span>
                    <span class="fa fa-star "></span>
                </div>
            </div>

            <div class="success">
                <h2>MySQL</h2>
                <h6>Loading...</h6>
                <div>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star "></span>
                    <span class="fa fa-star "></span>
                </div>
            </div>

            <div class="success">
                <h2>DSA(with C Pro.Language)</h2>
                <h6>Loading...</h6>
                <div>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star "></span>
                    <span class="fa fa-star "></span>
                    <span class="fa fa-star "></span>
                </div>
            </div>
        </div>

    </body>
</html>
<!--End the html page here -->
