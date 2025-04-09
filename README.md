    <head>
        <style>
            @keyframes fade-in {
                0%{opacity: 0;}
                50%{opacity: 50;}
                100%{opacity: 100;}
            }
            :root {
                --border: 3px
            }
            body {
                font-family: Arial, Helvetica, sans-serif;
                background-color: rgb(27, 27, 27);   
            }
            div {
                animation-name: fade-in;
                animation-duration: 2s;
            }
            .hover_text {
                width: 140px;
                height: 1200px;
                background-color: rgb(72, 162, 247);
                background-image: linear-gradient(rgb(72, 162, 247), rgb(49, 101, 150));
                border: solid, var(--border), rgba(41, 87, 131, 0.719);
                transition: width 2s;
                margin-left: auto;
                margin-right: auto;
                border-radius: 4px;
            }
            .hover_text:hover {
                width: 480px
            }
            .header_text {
                height: fit-content;
            }
            h1 {
                font-size: 25px;
                text-shadow: -1px 0 rgb(210, 210, 210), 0 1px rgb(210, 210, 210), 1px 0 rgb(210, 210, 210), 0 -1px rgb(210, 210, 210);
                transition: height 3s;
                background-color: rgb(255, 255, 255);
                text-align: center;
                border: solid, black, var(--border);
                height: 60px;
                border-radius: 4px;
                box-shadow: 4px 4px rgba(58, 58, 58, 0.486);
            }
            p {
                font-size: medium;
                text-align: center;
                background-color: rgb(255, 255, 255);
                border: solid, black, var(--border);
                border-radius: 4px;
                box-shadow: 4px 4px rgba(58, 58, 58, 0.486);
            }
            img {
                width: inherit;
                height: inherit;
                display: block;
                margin-left: auto;
                margin-right: auto;
                object-fit: cover;
            }
            #img_holder {
                background-color: white;
                border: var(--border), solid, black;
                width: 110px;
                height: 110px;
                padding: 5px;
                border-radius: 4px;
                display: block;
                margin-left: auto;
                margin-right: auto;
                transition: height 2s;
                transition: width 2s;
                box-shadow: 4px 4px rgba(58, 58, 58, 0.486);
            }
            a {
                color: blue;
                text-decoration: underline;
            }
            .Navbar {
                list-style: none;
                margin: 0;
                padding: 0;
            }
            li {
                float: left;
                border: var(--border), rgb(255, 255, 255), solid;
                border-radius: 2px;
            }
            li a {
                display: block;
                color: rgb(255, 255, 255);
                text-align: center;
                padding: 5px 5px;
                text-decoration: none;
            }
            li a:hover:not(.active) {
                color: rgb(39, 39, 39);
                background-color: #ffffff;
            }
            .active {
                background-color: #4fa1ff;
            }
        </style>
        <title>Faith's Webpage</title>
        <link rel="icon" type="image/x-icon" href="file:///C:/Users/29-HaqReh/Downloads/LUFFFFYYYY.jpeg">
        <link rel="stylesheet" href="mystyle.css">
    </head>
    <body>
        <ul class="Navbar">
            <strong><li ><a class="active"href="file:///C:/Users/29-HaqReh/OneDrive/Desktop/web%20development/webpages.html/Porfollio/mainpage.html">Main Page</a></strong></li>
            <strong><li><a href="https://discord.gg/HJznCb7WVk">contact</a></strong></li>
            <strong><li><a href="file:///C:/Users/29-HaqReh/OneDrive/Desktop/web%20development/webpages.html/Porfollio/sidepage.html">extra info</a></strong></li>
        </ul>
        <br>
        <br>
        <br>
        <div class="hover_text">
            <h1 class="header_text">Faith's Website</h1>
            <p>Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem </p>
            <br>
            <div class="hitbox_img">
                <div id="img_holder">
                    <img src="https://lh5.googleusercontent.com/ffq1jK5m9OEhlV_irmcmwzhhsv3r_sObg1Z_mo7UQrc5KNN7OGVMgQvRAiYPttorGx0uAYaWoiNej-w9ooQ4ApM">
                </div>
            </div>
            <br>
            <p>Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem</p>
            <div class="resources">
                <p>you can context me via my <a href="https://discord.gg/HJznCb7WVk">discord server</a></p>
                <p><a href="file:///C:/Users/29-HaqReh/OneDrive/Desktop/web%20development/webpages.html/Porfollio/sidepage.html">Test</a></p>
            </div>
            <div>
                <p>Ipsum Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis facilis sequi ducimus culpa libero laudantium quidem reiciendis nemo hic nostrum, sunt eos impedit inventore mollitia, eligendi voluptas exercitationem dolores totam?</p>
        </div>
    </body>
