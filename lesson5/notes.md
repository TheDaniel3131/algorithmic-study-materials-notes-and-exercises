# Lesson 5

## Algorithm Analysis & Asymptotic Growth Rate
### Algo Analysis 
- A Step-By-Step Process.
- Can written in Many Ways.
- Obtain best or optimum solutions from analyzing algorithms.
- Expected to work fast based on input size. If input size is small, algo will be fine.
- How to analyze validty of an algo? (to understand how algo works)
  - Order of Growth: Change in behavior by using Input Size increases (high) values for analysis. In some cases, it may or may not be work well due to algo's speed or efficency (Involves Time Complexity). 

## Best Case, Worst Case, Average Case
- Best Case: C<sub>best(n)</sub> = 1  
- Worst Case: C<sub>worst(n)</sub> = n
- Average Case: C<sub>average(n)<sub/> = (n + 1) / 2 // n
  ![image](https://github.com/TheDaniel3131/algorithmic-study-materials-notes-and-exercises/assets/71692327/b746f504-53d4-4b91-93a4-d6385c478e47)
  - Probability (p) of Successful Search: p / n
  - Probability of Unsuccessful Search: 1-p / n

  - Successful Search: 1(n + 1) / 2 + n(1 - 1) => (n + 1) / 2
  - Unsucessful Search: 0(n + 1) / 2 + n(1 - 0) => n
 
## Rules 
### Primitive Operations (Takes Unit Time)
- Assignment (Assign)
- Calculations
- Indexing
- Calling/Return

![image](https://github.com/TheDaniel3131/algorithmic-study-materials-notes-and-exercises/assets/71692327/322eda63-9cfe-4a99-8fd9-c2273d31cd56)

### Example of Worst Case Time Algo
![image](https://github.com/TheDaniel3131/algorithmic-study-materials-notes-and-exercises/assets/71692327/97c74f42-cbe1-4170-8ab5-691ed3d4696d)
![image](https://github.com/TheDaniel3131/algorithmic-study-materials-notes-and-exercises/assets/71692327/ad72ef67-5580-4d15-9a84-63153113c0c4)

### Graphs
- Time become larger quadrically.
![image](https://github.com/TheDaniel3131/algorithmic-study-materials-notes-and-exercises/assets/71692327/25d04e42-462e-482f-b3af-28235e3f7274)

### Drawbacks in counting primitive operations
- Concern about Linear In Time & Quadratic In Time
- Implementation details are insignificant
- Concern only the order of growth.

### Tool to analyze running time of an algo
![image](https://github.com/TheDaniel3131/algorithmic-study-materials-notes-and-exercises/assets/71692327/c9a2d4d6-b9bd-4db5-a8ea-0ea501a3ea88)

### Operations of Order of Growth
![image](https://github.com/TheDaniel3131/algorithmic-study-materials-notes-and-exercises/assets/71692327/63b6c1a1-2b21-48c4-b4a9-0ef10032b752)

