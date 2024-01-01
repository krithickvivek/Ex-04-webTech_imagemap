# Ex-06-Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
## Step 1
Use the image tag to upload the required photo by source.
## Step 2
Create a map, By using the shape attribute to select a particular place to show the information
## Step 3
By using the coords attribute we can select a particular area we needed ,Then using the href the website is called to show the details.


# Code:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>IMAGE_MAP_AROUND_ME</title>
    </head>
    <body align="center">
        <h1 ALIGN="center">IMAGE_MAP_AROUND_ME</h1>
        <P><b><big>You can click on Malles Alankar, Vels Global School, Adayar River Check Dam, 
            IPS Colony and IDPL Global
            to read more about the topic:</big></b></P>
    
        <hr>
        <hr>
        <style>
            h1{
                align-items:left;
                background-color: rgb(235, 255, 12);
            }
            hr{
                width: 10;
            }
    </style>
        <img src="https://res.cloudinary.com/dlseemi4e/image/upload/v1700392192/kimage_lqhtcl.jpg" 
        alt="Workplace" usemap="#workmap" width="1000" height="700">
        <map name="workmap">
            <area shape="circle" coords="616,86,62" alt="Vels Global School" href="school.html">
            <area shape="rect" coords="459,87,563,153" alt="Adayar Dam" href="dam.htm">
            <area shape="circle" coords="494,227,73" alt="IPS Colony"  href="colony.html" >
            <area shape="rect"  coords="796,206,887,305" alt="FLATS"  href="flat.html" >
            <area shape="circle"  coords="251,87,40" alt="IDPL Ground" href="ground.html">
        </map>
        <hr>
        <hr>
    </body>
</html>
```

# Output:
![out](<Screenshot 2023-11-19 175203.png>)

# Result:
The program is executed sucessfully.

