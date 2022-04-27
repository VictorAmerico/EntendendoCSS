# Entendendo o CSS
Acompanhamento de estudos sobre CSS

# Primeiro contato
Conceitos Básicos

## HTML (1)
~~~html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Estudo do Css</title>
</head>
<body>
    <header>
        <h1>Titulo</h1>
        <p class="t1">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Aliquid neque explicabo cumque accusantium ullam saepe dicta
            veniam dolorum possimus placeat repudiandae eaque dignissimos
            harum quasi consequatur, voluptates sit id corrupti?</p>
        <p class="t2">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Aliquid neque explicabo cumque accusantium ullam saepe dicta
            veniam dolorum possimus placeat repudiandae eaque dignissimos
            harum quasi consequatur, voluptates sit id corrupti?</p>
        <p class="t3">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Aliquid neque explicabo cumque accusantium ullam saepe dicta
            veniam dolorum possimus placeat repudiandae eaque dignissimos
            harum quasi consequatur, voluptates sit id corrupti?</p>
        <p class="t4">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Aliquid neque explicabo cumque accusantium ullam saepe dicta
            veniam dolorum possimus placeat repudiandae eaque dignissimos
            harum quasi consequatur, voluptates sit id corrupti?</p>
        <p class="t5">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Aliquid neque explicabo cumque accusantium ullam saepe dicta
            veniam dolorum possimus placeat repudiandae eaque dignissimos
            harum quasi consequatur, voluptates sit id corrupti?</p>

            <h1 id="f1">Formatação de texto</h1>
            <h2 class="f2">Formatação2</h2>
            <p class="f3">subtitulo</p>
            <p class="f4">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Aliquid neque explicabo cumque accusantium ullam saepe dicta
                veniam dolorum possimus placeat repudiandae eaque dignissimos
                harum quasi consequatur, voluptates sit id corrupti?</p>
            
            <ul class="u1">
                <div>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</div>
                <div>Aliquid neque explicabo cumque accusantium ullam saepe dicta</div>
                <div>veniam dolorum possimus placeat repudiandae eaque dignissimos</div>
                <div>harum quasi consequatur, voluptates sit id corrupti?</div>
            </ul>
    </header>
</body>
</html>
~~~
## CSS (1)
~~~css
/*
Margin, Border, Padding, Content
*/
h1,h2,p{
    text-align: center;
    font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

ul{
    list-style-type: square ;
}
.t1{
    background-color: rgb(255, 217, 0);
    padding: 10px;
    border: 5px solid #000;
    margin: 5px;
}

.t2{
    background-color: black;
    color: white;
    /*
    padding-top: 15px;
    padding-right: 10px;
    padding-left: 5px;
    padding-left: 0;
    */
    padding: 15px 10px 5px 0;
    border: 5px solid rgb(255, 0, 0);
    margin: 5px;
}

.t3{
    border: 3px solid blue;
    border-top: 2px dotted green;
    border-right: 4px dashed pink;
}

.t4{
    border-top: 3px dotted blue;
    border-right: 4px solid green;
    border-bottom: 1px dotted rgb(255, 51, 85);
    border-left: 4px dashed cyan;
}

.t5{
    border: 3px solid #505050;
    /*
    border-width: 3px;
    border-color: #505050;
    border-style: solid;
    */
}

#f1{
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    color: green;
}

.f2{
    font-family: Verdana, Arial;
}

.f3{
    font-style: italic;
    /*
    text-transform: uppercase;
    text-transform: lowercase;
    */
    text-transform: capitalize;
}

.f4{
    text-decoration: underline;
    /*
    text-decoration: overline;
    text-decoration: line-through;
    */
}

.u1{
    margin: 4px;
    border: 15px 10px 5px 0 solid #000;
    text-align: center;
}
~~~
