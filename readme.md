## Readme File  
****
*This is the readme file of the sdsc3002 Assignment2-greedy algorithm of core number calculation in graph* 


![image-20220523020227389](https://user-images.githubusercontent.com/76908071/169709471-502b2a50-3083-4805-b8af-c16aba45cc4b.png)


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
