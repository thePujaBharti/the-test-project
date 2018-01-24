# the-test-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>CSS Buttons</title>
    <style>
        body{
            font-family: "Ubuntu", Tahoma, "Helvetica Neue", Helvetica, Arial, sans-serif;
        }
        .button{
            background-color: green;
            color: white;
            border: none;
            text-decoration: none;
            cursor: pointer;
            padding: 10px 16px;
            display:inline;
            border-radius: 5px;
            height: 40px;
            font-size: 15px;
        }
        .button:hover{
            background-color: darkgreen;
            cursor: pointer;
        }

        .button-outline{
            border: 2px solid green;
            background-color: white;
            text-decoration: none;
            color: black;
            border-radius: 5px;
            padding: 10px 16px;
            height: 40px;
            font-size: 15px;
        }

        .button-outline:hover{
            background-color: green;
            color: white;
        }

        .btn{
            color: white;
            border: none;
            text-decoration: none;
            cursor: pointer;
            padding: 10px 16px;
            display:inline;
            border-radius: 5px;
            height: 40px;
            font-siz.e: 15px;
        }

        .primary{
            background-color: blue;
        }

        .primary:hover{
            background-color: darkblue;
        }

        .secondary{
            background-color: gray;
        }

        .secondary:hover{
            background-color: darkgray;
        }

        .warning{
            background-color: darkorange;
        }

        .warning:hover{
            background-color: orange;
        }

        .danger{
            background-color: red;
        }

        .danger:hover{
            background-color: darkred;
        }
    </style>
</head>
<body>

<button>Default Button</button>
<a href="#" class="button">Link</a>
<button class="button">Button</button>
<input class="button" type="button" value="Input">


<hr>
<button>Default Button</button>
<a href="#" class="button-outline">Link</a>
<button class="button-outline">Button</button>
<input class="button-outline" type="button" value="Input">

<hr>

<button>Default Button</button>
<button class="btn primary">Primary</button>
<button class="btn secondary">Secondary</button>
<button class="btn button">Success</button>
<button class="btn warning">Warning</button>
<button class="btn danger">Danger</button>



</body>
</html>
