## Readme File 
****
*This is the readme file of the sdsc3002 Assignment2*   
**Name:** *Du Junye* &emsp; &emsp; &emsp; &emsp;&emsp; **SID:** *56641800*



![image-20220523020227389](D:\OneDrive - City University of Hong Kong - Student\SemB 课程资料\sdsc3002\3002assignment2\Core_number_calculation_in_graph\image-20220523020227389.png)

**Python Verison and Package version:**  

+ Python 3.9.7
****


<h2> Class Structure</h2>  

****
> ### **Graph Variables:**    
>> **Graph.graph**: *defaultdict*, records the neighbours of a specified node  
>> **Graph.degree**: *defaultdict*, records the degree of a specified node  
>> **Graph.answer**: *dict*, records the core number of a specified node  

> ### **Member Function:**
>> **addedge**:  add an edge between two vertices  
>> **initialdegree**:  calculate every node's degree according to the graph  
>> **movenode**:  remove the node in the graph  
>> **Kscore**:  calculate the core number of each node and store it into the answer

**Conclusion:**  *The running time of the code in my test is around 6.46s*

**Note:** *The testing result may differ from the real value due to the performance of computers.*