# Ex.04 Images as Hyperlinks
## DATE: 16/04/2024
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
  
## CODE
```
<html
     <head>
        <title>GOMATHY Ex04 Agri..</title>
    </head>
        <body bgcolor="#d5eed3">
<h1 style ="font-family:elephant;color:#43086b;text-decoration-line:underline ; text-align:center;";>Ex.04 Images as Hyperlinks</h1>

<h2 style="font-family:elephant;color:rgb(230, 37, 117);">Sugarcane</h2>
<a href=" https://www.bing.com/ck/a?!&&p=b18fe348f5b020f4JmltdHM9MTcxMzEzOTIwMCZpZ3VpZD0wZTM0MTBhZC02YzE5LTY3ZTItMzZiYS0wNGIxNmRjYjY2NzUmaW5zaWQ9NTUwOA&ptn=3&ver=2&hsh=3&fclid=0e3410ad-6c19-67e2-36ba-04b16dcb6675&psq=sugarcane&u=a1aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvU3VnYXJjYW5l&ntb=1">
<img src="e:\images\sgcane.jpg" width="200"  border size="2" height="200"></a><br>

<h2 style="font-family:elephant;color:rgb(17, 140, 58);">Sesame</h2>
<A HREF="https://www.bing.com/ck/a?!&&p=11e2244b4d4d4304JmltdHM9MTcxMzEzOTIwMCZpZ3VpZD0wZTM0MTBhZC02YzE5LTY3ZTItMzZiYS0wNGIxNmRjYjY2NzUmaW5zaWQ9NTU2MA&ptn=3&ver=2&hsh=3&fclid=0e3410ad-6c19-67e2-36ba-04b16dcb6675&psq=SESAME&u=a1aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvU2VzYW1l&ntb=1">
 <IMG SRC="e:\images\SESAME.jpg"  width="200" border size="2"  height="200"></A><br><br>

<h2 style="font-family:elephant;color:#dc6013;">Combined harvester</h2>
<a href="https://www.bing.com/ck/a?!&&p=47a0648a3de2f96aJmltdHM9MTcxMzEzOTIwMCZpZ3VpZD0wZTM0MTBhZC02YzE5LTY3ZTItMzZiYS0wNGIxNmRjYjY2NzUmaW5zaWQ9NTU0MA&ptn=3&ver=2&hsh=3&fclid=0e3410ad-6c19-67e2-36ba-04b16dcb6675&psq=harvester&u=a1aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvQ29tYmluZV9oYXJ2ZXN0ZXI&ntb=1">
<img src="e:\images\harvester.webp" width="200"  border size="2" height="200"><br><br></a>

<h2 style="font-family:elephant;color:#aa1a1a;">Tractor</h2>
<a href="https://www.bing.com/ck/a?!&&p=620fc08918dd8928JmltdHM9MTcxMzEzOTIwMCZpZ3VpZD0wZTM0MTBhZC02YzE5LTY3ZTItMzZiYS0wNGIxNmRjYjY2NzUmaW5zaWQ9NTQ5NA&ptn=3&ver=2&hsh=3&fclid=0e3410ad-6c19-67e2-36ba-04b16dcb6675&psq=tractor&u=a1aHR0cHM6Ly93d3cuY3JvcHNyZXZpZXcuY29tL3doYXQtYXJlLXRyYWN0b3JzLXVzZWQtZm9yLw&ntb=1">
    <img src="e:\images\tractor.jpg" width="200"  border size="2" height="200"><br><br></a>

<h2 style="font-family:elephant;color:rgb(174, 23, 201);">Fertilizer</h2> 
<a href="https://www.bing.com/ck/a?!&&p=f6c7e2f4552af867JmltdHM9MTcxMzEzOTIwMCZpZ3VpZD0wZTM0MTBhZC02YzE5LTY3ZTItMzZiYS0wNGIxNmRjYjY2NzUmaW5zaWQ9NTMwNQ&ptn=3&ver=2&hsh=3&fclid=0e3410ad-6c19-67e2-36ba-04b16dcb6675&psq=fertilizer&u=a1aHR0cHM6Ly9ieWp1cy5jb20vYmlvbG9neS9mZXJ0aWxpemVycy8&ntb=1">
<img src="e:\images\ferti.jpg"width="200" height="200" border size="2"><br><br></a>

<h2 style="font-family:elephant;color:#107218;"> Organic fertilizer</h2> 
<a href="https://www.bing.com/ck/a?!&&p=d489aac698460702JmltdHM9MTcxMzIyNTYwMCZpZ3VpZD0wZTM0MTBhZC02YzE5LTY3ZTItMzZiYS0wNGIxNmRjYjY2NzUmaW5zaWQ9NTI1Ng&ptn=3&ver=2&hsh=3&fclid=0e3410ad-6c19-67e2-36ba-04b16dcb6675&psq=organic+fertilizer+for+plants&u=a1aHR0cHM6Ly93d3cuZXBpY2dhcmRlbmluZy5jb20vb3JnYW5pYy1mZXJ0aWxpemVycy8&ntb=1">
<img src="e:\images\orgferti.jpg"width="200" height="200" border size="2"><br><br></a>

</body>
    
</html>
```

## OUTPUT

<img width="950" alt="sct1" src="https://github.com/GOMATHY1719/Ex04/assets/165985023/8ccaae93-2708-4a4d-b183-ad9895c1f97c">


<img width="959" alt="sct2" src="https://github.com/GOMATHY1719/Ex04/assets/165985023/d5274cc7-3748-42c1-bfc5-1e79a6b28661">


<img width="951" alt="sct3" src="https://github.com/GOMATHY1719/Ex04/assets/165985023/a84f30e6-f82d-41e0-8526-e98558effa6d">



## RESULT
 Images as hyperlinks is implemented successfully.
