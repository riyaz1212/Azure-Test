# Azure-Test
https://hub.docker.com/r/mindofpsyche/flask-rest-api

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bookmark Manager</title>
    <link rel="stylesheet" href="styles.css">
    <div id="main">
        <h1>Bookmarks</h1>
        <div id="box">
        <div id="primary">
            <h2>Primary</h2>
            <ul>
                <li><a href="https://www.w3schools.com" target="_blank">W3Schools.com</a></li>
                <li><a href="https://www.youtube.com" target="_blank">Youtube.com</a></li>
                <li><a href="https://www.facebook.com" target="_blank">Facebook</a></li>
                <li><a href="https://www.quora.com" target="_blank">Quora</a></li>
                <li><a href="https://www.github.com" target="_blank">Github</a></li>

            </ul>
        </div>

        <div id="secondary">
            <h2>Secondary</h2>
            <ul>
                <li><a href="https://www.youtube.com" target="_blank">Youtube.com</a></li>
                <li><a href="https://www.facebook.com" target="_blank">Facebook</a></li>
            </ul>
        </div>
    </div>

    </div>
    
</head>
<body>
    
</body>
</html>

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: gilroy;
}
html, body{
    height: 100%;
    width: 100%;
}
#main{
    
    height: 100%;
    width: 100%;
}

#main h1{
    font-size: 80px;
    margin: 10px;
    text-align: center;
    border:2px solid black ;
    background-color: azure;

}
#box{
    
    padding: 20px;
    height:70%;
    line-height: 30px;
    display: flex;
    align-items: center;
}

#primary{
    
    border: 2px solid black;
    
    height: 60%;
    width: 50%;
    margin: 20px;
    padding-left: 225px;
    padding-top: 10px;
    
}

#secondary{
    
    border: 2px solid black;
    height: 60%;
    width: 50%;
    padding-top: 10px;
    padding-left: 225px;
    margin: 20px;
    
}
