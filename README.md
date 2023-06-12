# Experiment-2
Create a commercial website using HTML & CSS
# Aim:
To create a commercial website using HTML & CSS.

# Algorithm:
1.Start React project,using "create-react-app projectName".

2.To create the folder,go to the folder using "code .".

3.To start the website using localhost,npm start.

4.Edit the components in the folder,for the project.

5.Edit App.js and enter the HTML code in the return and render.


```

```
# HTML CODE:
```html
<!DOCTYPE html>
<head>
    <title>Car-Site</title>
    <link rel="StyleSheet" href="web.css">
</head>
<body>
    <div style="width:1400px;height:830px;background-color:black; text-align: center; padding: 20px;">

        <h2><b>BEST TUNNING</b>
        <pre><a href=" ">home</a></pre>
        <pre><a href=" ">project</a></pre>
        <pre><a href=" ">team</a></pre>
        <pre><a href=" ">contact</a></pre>
        <form><button>Book an Appoinment</button></form>
        </h2>
        <div class="im">
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
        <img src="C:\Users\Deepak\Downloads\benz side view.jpg">
        <h2>TUNNING PERFECTION</h2>

        <b><p>Tuning is an upgrade<br>that unlocks hidden<br>
            potential of your car</p></b>
            <br>
            <h3><p>&#8595;     Explore</h3></p>
        </div>
    </div>
    <div style="width:1400px;height:570px;background-color:black; text-align: center; padding: 20px;">
    <div class="mid">
        <img src="C:\Users\Deepak\Downloads\speedometer.jpeg">
            <h3>WHY DO YOU WANT IT</h3>
            <b><h1>What is Tuning and<br>Why do you Want It?</h1></b>
            <p>Tuning is an upgrade to the software in the vehicle's computer.<br>Custom software is installed that changes many parameters<br>that control the way the engine operates. With proper tuning<br>you can increase both power and fuel economy</p>  
            <div class="i">
            <div class="dx" >
                <img src="C:\Users\Deepak\Downloads\timer.png" style="height: 40px; width:40px;"></img>
                <br>
                <br>
                <br>
                <p style="color: antiquewhite;">A comphrehensive tool<br> for high horsepower <br>builds.</p>
            </div>
            <div class="dy" >
                <img src="C:\Users\Deepak\Downloads\petrol pump.png" style="height: 40px; width:40px;"></img>
                <br>
                <br>
                <br>
                <p style="color: antiquewhite;">With proper tuning you can increase your fuel<br>economy.</p>
            </div>
            </div>
    </div>
    </div>
    <div class="end">
    <div style="width: 725px; float:left; height:515px; background:black;">
        <img src="C:\Users\Deepak\Downloads\front.jpg">
        </div>
        <div style="width: 711px; float:left; height:515px; background:black;">
        <h2>ADVANTAGES</h2>
        <br>
        <br>
        <br>
        <h1>What can I Expect<br/>from Tuning?</h1>



        
        <h3>Through proper modification it is possible to greatly increase<br>the power output of the vehicles while at the same time<br>improving safety and longevity of the engine, drivabilty, and<br>smoothness</h3>

        <div class="dx" >
            <p style="color:red; font-size: 30px;">20-35 hp</p>
            <p style="color: antiquewhite;">roughly increase from a stage 1 tune.</p>
        </div>
        <div class="dy" >
            <p style="color:red;font-size: 30px;">35-40 hp</p>
            <p style="color: antiquewhite;">roughly increase from a stage 2 tune.</p>
        </div>
        
            
    </div>
    </div>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
   

    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    
   
   

    <div class="er">
    <div style="width:1400px;height:80px;background-color:black; text-align: center; padding: 20px;">
        <h2><b>BEST TUNNING</b>
            <pre><a href=" ">home</a></pre>
            <pre><a href=" ">project</a></pre>
            <pre><a href=" ">team</a></pre>
            <pre><a href=" ">contact</a></pre>
            </h2>

    </div>
    </div>

</body>
</html>
```
# CSS CODE:
```css
h2{
    display:flex;
    justify-content:space-between;
    font-family: sans-serif;
    color:orangered;
    font-size: 20px;
}
a{
    display:flex;
    justify-content: space-between;
    color: rgb(255, 255, 255);
    font-size: 15px;
}
button{
    background-color:orangered;
  border:0cqb;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  border-radius: 15px;

}
div {  
    width: auto;  
    text-align: center;  
    border: 3px solid black;  
}
img {  
    max-width: 100%;  
    height: auto;  
    }   
.im h2{
    font-size: 15px;
    color: white;

}
.im p{
    color:white;
    font-size: 25px;
    text-align: left;
    font-family: Arial, Helvetica, sans-serif;
}
.im h3{
    color:white;
    text-align: left;
}
.mid h3{
    color:white;
    text-align: left;
}
.mid h1{
    color:white;
    text-align: left;
    font-size: 45px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.mid p{
    color:white;
    text-align: left;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 15px;
}
.mid img{
    float:right;
    height: 380px;
    width: 850px;
  
}
.dx{
  text-align:center;
  display:block;
  background-color: transparent;
  border: 1px solid transparent;
  margin-right: 10px;
  margin-bottom: 1px;
  float:left;
  left : -5%;
}
.dy{
    width:200px;
  text-align:center;
  display:block;
  background-color: transparent;
  border: 1px solid transparent;
  margin-right: 10px;
  margin-bottom: 1px;
  float:left;
  left : -5%;
}
.dx p{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.dy p{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.end img{
    height:450px;
    width:700px;
    float: left;
}
.end h2{
    color: white;
    float: left;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.end h1{
    color: white;
    text-align: left;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.end h3{
    color: white;
    float: left;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.end dx{
    position: absolute;
    left : 5%;

}
.end dy{
    position: absolute;
    left : 25%;
}
.pp h2{
    display:flex;
    justify-content:space-between;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color:orangered;
    font-size: 20px;
}

.er a{
    display:flex;
    justify-content:center;
    color:white;
    font-size: 15px;
    
}

```
# OUTPUT:
![image](https://github.com/SOMEASVAR/Website/assets/93434149/f284099f-ae4f-41a7-974d-c0cdc42662d4)
![image](https://github.com/SOMEASVAR/Website/assets/93434149/504ec771-e536-4923-a58f-d8f891bdb08b)
![image](https://github.com/SOMEASVAR/Website/assets/93434149/e79ce252-2227-4a7b-a64b-5e59759a59a3)
# GITHUB LINK:
```
https://github.com/SOMEASVAR/Website.git
```
# RESULT:
Thus to create a commercial website using HTML & CSS is created successfully.
