# HTML5-Basic
untuk memanggil code html5,css,java banyak software yang digunakan antara lain `[#Atom]`, `#Bracket`, `#Notepad++`, `#Microsoft Visual Studio Code`. dari **masing-masing** software tersebut memiliki keunggulan masing-masing.

**My Note :** 

```
<!DOCTYPE html>
  <html>
  <head>
      <title>Page Title</title>
   </head>
<body>

    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>

  </body>
</html>
```

> Basic Code for css call :
```
<link rel="stylesheet" type="text/css" href="link your css name">
```
**BOOTSTRAP**
Version V4.3 [Bootstrap](https://getbootstrap.com/)

**HTML ATRIBUT**
* ``<hr>`` 
  * ``<br>``
    * ``<p>``

> ``<hr> garis lurus yang digunakan apabila dalam pemberian batas antara content / isi.``
> ``<br> digunakan apabila ingin melakukan baris baru.``
> ``<p> paragraph/paragraf digunakan apabila ingin melakukan penggantian paragraf baru.``
  
**Text**
* ``<h1>``
  * ``<h2>``
    * ``<h3>``
      * ``<h4>``

**Background Gradient CSS**
```
body{
    background: rgb(121,9,82);
    background: linear-gradient(90deg, rgba(121,9,82,1) 0%, rgba(255,0,84,1) 100%);
}
```

# DIV CLASS BOX
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Pert4 Tugas</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" media="screen" href="main.css">
    <script src="main.js"></script>
    <link rel="stylesheet" href="pert4.css">

    <style>
    .div1{
        padding-top: 100%; 
        border: 1px solid blue;
        background: blue;
        padding: 10px 10px;
        height: 350px;
        width: 350px;
    }
    .div2{
        padding-top: 100px;
        border: 1px solid white;
        background: black;
        padding: 10px 30px;
        height: 250px;
    }
    .div3{
        padding-top: 100px;
        border: 1px solid grey;
        background: grey;
        padding: 10px 30px;
        height: 150px;
    }
    .div4{
        padding-top: 100px;
        border: 1px solid brown;
        background: brown;
        padding: 14px 10px;
    }
    #border{
        color: #fff;
    }
    #margin{
        color: #fff;
    }
    p{
        color: #fff;
        text-align: center;
    }
    #border{
        text-align: center;
    }
    </style>
</head>
<body>
    <div class="div1">
        <p>Margin</p>
        <div class="div2">
            <p id="border">Border</p>
            <div class="div3">
                <p id="padding">Padding</p>
                <div class="div4">
                    <p id="content">content</p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
```
