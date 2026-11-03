!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>3 Column Layout</title>
        <style type="text/css">
            header {
                background-color: #eabcf5;
                height:150px;
            }
            footer {
                background-color: #c4f7b3;
                height:150px;
            }
            #container {width:80%; background-color: #f5bcd4; margin: 0 auto; height: 900px;}
            #wrapper {background-color: azure;}
            #content {background-color: antiquewhite; float:left; width: 70%;}
            #maincontent {background-color: aquamarine; height: 900px;width:60%; float:right;}
            #secondarycontent {background-color: aliceblue; height: 1000px;width:40%; float:left;}
            #sidebar {background-color: #f5eabf; height:600px; width: 30%; float:right;}

            
        </style>

    </head>
    <body>
        <div id="container">
            <header>logo</header>
                <div id="wrapper">
                    <div id="content">
                        <div id="maincontent">main content

                        </div>
                        <div id="secondarycontent">secondary content</div>
                    </div>
                    <div id="sidebar">sidebar</div>
                    <footer>footer</footer>
                </div>
        </div>

    </body>
</html>
