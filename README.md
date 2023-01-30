Places Around Me
AIM:
To develop a website to display details about the places around my house.

Design Steps:
Step 1: Create a Django project abd app.

Step 2: create the html and css files based on your place in the image.

Step 3: Define new function in views file.

Step 4: Import views files and define the paths in urls file.

Step 5: Run the server
Code:

map.html
```

<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Puzhal</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>dharani p (22009065)</b></font>
</h3>
<center>
<img src="/static/images/location.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/ghs.html" title="Govt. Higher Secondary School">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/rto.html" title="RTO Office">
<area shape="circle" coords="400,350,50" href="/static/html/vk.html" title="Puzhal Lake">
<area shape="circle" coords="400,200,75" href="/static/html/bus.html" title="Hi-Tech Bus Stand">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/park.html" title="Eco-Park">
</map>
</center>
</body>
</html>
```
park.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Eco-Park</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Puzhal</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Eco-Park</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
A very nice park near puzhal bus stand. It is located surrounding the puzhal Lake. 
Very superb calm place in puzhal. Best for walking. Nice playing place for kids.
Well maintained with jogging track. Source of ground water.
Good place play with children.  In Banyan Tree lot of parrot stay like house. 
Good sound and Air. Lake view park looks awesome.
Very nice place at puzhal.
Simple and relax with play area.
</font>
</p>
</body>
</html>
```
rto.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>RTO Office</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Ariyalur - Cement City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>RTO Office</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
RTO office or the Regional Transport Office is a government body specifically established to oversee all transport-related operations in the country. RTOs are located throughout the country in each state and union territory. RTOs are responsible for enforcing the rules as laid down by the Motor Vehicle Act of 1988.
The department also maintains a database of all the vehicles operating in the country as well as issues licenses for drivers. Besides, the RTO office also collects road taxes, supervises pollution checks, and ensures the enforcement of all road transportation rules. If you own or drive a vehicle in India, you will need to visit the RTO to get your vehicle registered, obtain a driver’s license or renew your driver’s license, etc.
RTOs are also responsible for improving road and vehicle safety, especially to avoid accidents and other road fatalities.
</b>
</font>
</p>
</body>
</html>
```
bus.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Bus Stand</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Puzhal</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Hi-Tech Bus Stand</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
Puzhal is an administrative district, one of the 38 districts in the 
state of Tamil Nadu in India. The district headquarters is located at puzhal. 
The district encompasses an area of 1,949.31 km². Gangaikonda Cholapuram, 
built by King Rajendra Cholan of Chola Empire, is a UNESCO World Heritage site 
situated in this district. The district is also known for its rich prehistoric 
fossils. Many fossils of gigantic molluscs and jawed fishes, at least one 
fossilized dinosaur egg, and several fragmentary fossils of sauropod and theropod 
dinosaurs have been discovered here. An on-site museum is being set up at 
Keelapazhur to preserve and conserve fossils. Ariyalur is noted for its cement
 industries and Jayankondam has huge reserves of lignite.
</b>
</font>
</p>
</body>
</html>
```
ghs.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Govt. High. Sec. School</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Puzhal</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Government Higher Secondary School</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The main objectives of puzhal Government Higher Secondary School are 
<ul>
<li>To impart proper and qualified training to teachers and give them an attractive salary and incentives so that they are not tempted to quit and look elsewhere for jobs.</li>
<li>To provide financial aids and grants wisely and judiciously.</li>
<li>To Frame of syllabus and curriculum.</li>
<li>To set aims and objectives of education.</li>
</ul>
</font>
</p>
</body>
</html>
```
vk.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Washerman’s Lake</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><Puzhal</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Puzhal Lake</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The uses of Puzhal Lake in puzhal are 
<ol type="1">
<li>Lake is used for rain water harvesting.</li>
<li>It is used for drinking.</li>
<li>Pisculture.</li>
<li>For bathing, washing clothes etc.</li>
</ol>
</font>
</p>
</body>
</html>
```
Output:![2023-01-30 (1)](https://user-images.githubusercontent.com/119407159/215508427-e43cafe3-c43e-43dd-abdc-7f65e48dd9ff.png)


![2023-01-30 (5)](https://user-images.githubusercontent.com/119407159/215508724-78db794b-13f5-4363-bc75-0f54e59b0773.png)

![2023-01-30 (6)](https://user-images.githubusercontent.com/119407159/215508748-2b9fd249-ab9a-4b4b-9692-ddd351f0e49b.png)


![2023-01-30 (2)](https://user-images.githubusercontent.com/119407159/215508640-8a47ab95-9ae8-45f8-80eb-2d55f0b1a348.png)


![2023-01-30 (3)](https://user-images.githubusercontent.com/119407159/215508654-b632bf1a-7738-4e3f-bf5b-151931dfa276.png)
![2023-01-30 (4)](https://user-images.githubusercontent.com/119407159/215508703-525b217f-4833-473a-8d8e-eaa29382e44f.png)


validator

![2023-01-30 (7)](https://user-images.githubusercontent.com/119407159/215508773-bf803ab4-a4c7-49e6-9bab-bb782700c07e.png)

result :
The experiment was executed successfully.
