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
