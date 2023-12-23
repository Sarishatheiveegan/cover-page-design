# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone into the repository named cover-page-design and create a django admin interface.
### Step 2:
Write HTML and CSS code for designing book cover page and excute them
## Code:
```
<!DOCTYPE html>
<html>
    <head>
        <title>
            Front cover page
        </title>
        <style>
            .bookpage{
                height:700px;
                width:500px;
                margin-left:35%;
                background-image: url(book cover.jpeg);
                padding:10px;
                background-size: cover;
            }
            .hr1{
                width:200px

            }
            .booktitle{
                margin-top: 30px;
                color:white;
                padding:5px;
                font-size: xx-large;
            }
            .subtitle{
                color:white;
                font-size: large;
            }
            .mypic{
                position: relative;
                top:90px;
                left:390px;
                height: 80px;
                width: 90px;
            }
            .hr2{
                padding-top: 130px;
            
            }
            *{
                color: white;
            }
            .ed{
                position:relative;
                top: 110px;
            }
            .author{
                font-family: 'Trebuchet MS';
                font-size: large;
            }
            .pb{
                position: relative;
                left:420px;
                top:-40px;
                font-size: x-large;
            }
        </style>
        <body>
            <div class="bookpage">
            <div style="color:white">INSIGHT </div>
            <div class="hr1"><hr ></div>
            <div class="booktitle"><h1>ARTIFICAL INTELLIGENCE WITH CSS</h1></div>
            <div class="subtitle">Develop future-proof responsive websites<br>using latest HTML5 and CSS</div>
            <div class="mypic"><img src=Re-3537.jpeg" height="140px" ></div>
            <div class="ed">SPECIAL EDITION</div>
            <div class="hr2"><hr ></div>
            <div class="author"> sarisha</div>
            <div class="pb"> <h2>SEC</h2></div>
        </div>
        </body>
    </head>
</html>
```

## Output:
 ![output](https://github.com/Sarishatheiveegan/cover-page-design/assets/144979465/56dc624f-43bb-43cb-b6ee-2f775c56def0)


## Result:
Thus the program executed successfully
