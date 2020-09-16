<!DOCTYPE HTML>
<html>
    <head>
        <title>A Little Info About Me</title>
        <style>
    body {
        background: rgb(0, 0, 0);
        color: rgb(0, 0, 0);
        padding: 10px;
        font-family: arial;
    }
    #all-contents {
        max-width: 800px;
        margin: auto;
    }

    /* navigation menu */
    nav {
        background: rgb(20, 0, 0);
        margin: 0 auto;
        margin-bottom: 20px;
        display: flex;
        padding: 10px;
    }
    h1 {
        display: flex;
        align-items: center;
        color: white;
        flex: 1;
        margin: 0;
    }
    #nav-ul {
        list-style-image: none;
    }
    .nav-li {
        display: inline-block;
        padding: 0 10px;
    }
    a {
        text-decoration: none;
        color: #fff;
    }

    /* main container area beneath menu */
    main {
        background: rgb(20, 0, 0);
        display: flex;
    }
    .sidebar {
        margin-right: 25px;
        padding: 10px;
    }
    .sidebar-img {
        width: 200px;
    }
    .content {
        flex: 1;
        padding: 15px;
        color: white;
    }
    #interests {
        border: 4px silver ridge;
        padding: 8px;
        color: white;
    }
    h2, h3 {
        margin: 0px;
        color: white;
    }
</style>
    </head>

    <body>
        <! -- All Content Goes Here -->
        <div id="all contents">
            <nav>
                <h1>A Little Info About Me</h1>
                <ul id="nav-ul">
                    <li class="nav-li">
                      <a href="index.html"> Home </a>
                    </li>
                    <li class="nav-li">
                      <a href="portfolio.html"> Portfolio </a>
                    </li>
                </ul>
            </nav>

            <main>
                <! -- Sidebar Section -->
                <div class="sidebar">
                      <img class="sidebar-img"src="https://f0ca2d3c-a490-474d-b1f3-a40d5e21c144.ws-us02.gitpod.io/mini-browser/workspace/SethCulpepper.github.io/Praise%20Team%20Guitar.png">
                </div>

                <! -- Content Section -->
                <div class="content">
                    <h2> Seth Culpepper </h2>
                    <p> Student at LAVCA </p>
                </div>
                <! -- Interests Section -->
                <div id="interests">
                    <h3>Interests</h3>
                    <ul>
                        <li>Playing Guitar</li>
                        <li>Rock Climbing</li>
                        <li>Video Games</li>
                    </ul>
                </div>
                </div>
            </main>
        </div>
    </body>
</html>