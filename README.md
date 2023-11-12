# Ex.06 Book Front Cover Page Design
## Date: 12/11/2023

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
## cover.html
```html

<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:rgba(255, 255, 255, 0.562);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(got.jpg);
            background-size: cover;
        }
        .insight{
            color: rgba(255, 255, 255, 0.359);

        }
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgba(255, 255, 255, 0.359);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'times new roman', times new roman, times new roman;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }
        .id {
            width:400px;
            position: relative;
            top:180px;   
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: rgba(255, 255, 255, 0.359);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgba(255, 255, 255, 0.879);">
            </div>
            <div class="booktitle">
                <h1>GAME OF THRONES</h1></div>
            <div class="subtitle">
                Game of Thrones is roughly based on the storylines of the A Song of Ice and Fire book series by George R. R. Martin, set in the fictional Seven Kingdoms of Westeros and the continent of Essos
            </div>
            <div class="mypic">
                <img src="myphoto.jpeg" width="130" height="155" alt="">
            </div>
            <div class="id">
                <hr style="color: rgba(255, 255, 255, 0.476);">
            </div>
            <div class="author">
               <p><b>MUGILAN</b></p>
            </div>
            <div class="ed">
                <b>FIRST SEASON</b>
            </div>
        </div>
    </body>
</html>
```

## OUTPUT:

![web ex 6 1](https://github.com/Mugilan212/cover/assets/144508901/0f5e3023-4327-4715-9a4f-024b05d317fb)


![web ex 6](https://github.com/Mugilan212/cover/assets/144508901/21bb9e17-ce11-4feb-aec0-4371166a3c87)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
