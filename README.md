# D3-scale
This is an angular application with D3 library to different types of graph scale.D3 Scales provide a convenient solution to this. They map our data values to values that would be better represented in visualizations.D3 provide different types of method to show different charts.
this application include 
1. scale Linear
2. scale Time
3. scale Log
4. scale Band

# Project Setup
1. git clone project
2. npm install
3. ng serve

# Create svg
first create svg and then add scale 
![image](https://user-images.githubusercontent.com/25982054/124364337-7d2bef80-dc5e-11eb-903f-d75f90a15bcf.png)

![image](https://user-images.githubusercontent.com/25982054/124364290-23c3c080-dc5e-11eb-99c0-2a97b0272bc7.png)

# Scale Linear
 1. To craete linear scale you need **d3.scaleLinear()** 
 set the scale domain, here domain start with **0** to **100** but if you want negative scale then start domain with **negative value** to **positive value**
 
 ![image](https://user-images.githubusercontent.com/25982054/124363163-54542c00-dc57-11eb-989b-f6e952865e92.png)
 
 
 2. Add scale position axisBottom , axisLeft, axisRight , axisTop
 
 ![image](https://user-images.githubusercontent.com/25982054/124363245-c9276600-dc57-11eb-953b-b944be98bbe0.png)
 
 ## Output
 1. positive scale
 
    ![image](https://user-images.githubusercontent.com/25982054/124363299-0986e400-dc58-11eb-8abb-f9b752d320ef.png)
 2. Negative scale
 
    ![image](https://user-images.githubusercontent.com/25982054/124363411-b6f9f780-dc58-11eb-8a2b-38f2f6a35ac1.png)
   
# Scale Time
1. To craete time scale you need **d3.scaleTime()** 
 set the scale domain, here provite **start Date-time** and **End Date-time**
 
 ![image](https://user-images.githubusercontent.com/25982054/124363603-d180a080-dc59-11eb-9c7e-2bdb202d2b29.png)
 
 2. Add scale position axisBottom , axisLeft, axisRight , axisTop and format the label using **tickFormat**
 
 ![image](https://user-images.githubusercontent.com/25982054/124363617-f6751380-dc59-11eb-88f7-fa6ea246cc8a.png)

 
 ## Output
 ![image](https://user-images.githubusercontent.com/25982054/124363687-67b4c680-dc5a-11eb-977e-d405503ca3d1.png)

# Scale Log
 1. To craete linear scale you need **d3.scaleLog()** 
 set the scale domain, here domain start with **0.1** to **1000**.
 0 and negative value not assign to domain because log(0) or log(-negativeValue) return **NAN**
 
 ![image](https://user-images.githubusercontent.com/25982054/124363956-042b9880-dc5c-11eb-9a76-602af39b85ac.png)
 
 2. To format scale user **d3.format('.0f')**
 
 ![image](https://user-images.githubusercontent.com/25982054/124364028-6edcd400-dc5c-11eb-8b03-ee59312da287.png)

 ## Output
 1. scale without format
 
 ![image](https://user-images.githubusercontent.com/25982054/124364084-d2ff9800-dc5c-11eb-9648-e6844cffcca4.png)

 2. scale with format
 
    ![image](https://user-images.githubusercontent.com/25982054/124364055-af3c5200-dc5c-11eb-83d3-2c28a76c1501.png)
    
# Scale Band
 1. To craete linear scale you need **d3.scaleBand()** 
 
 ![image](https://user-images.githubusercontent.com/25982054/124364256-e65f3300-dc5d-11eb-948e-01c562f96291.png)

 ## Output
 
![image](https://user-images.githubusercontent.com/25982054/124364226-a4ce8800-dc5d-11eb-925c-8c333a300a3e.png)


   
