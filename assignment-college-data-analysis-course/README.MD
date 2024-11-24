# Data Analysis Assignment
> This for exercising data visualization skills

## Questions

### 1. Bitcoin Prices
Here is a list of Bitcoin prices recorded at the end of each week (Sunday) in 2018 and 2019.
Create a visualization that allows you to answer the question:
In which year did bitcoin holders have more profits?

```python 
prices = [14292.2, 12858.9, 11467.5, 9241.1, 8559.6, 11073.5, 9704.3,
          11402.3, 8762.0, 7874.9, 8547.4, 6938.2, 6905.7, 8004.4,
          8923.1, 9352.4, 9853.5, 8459.5, 8245.1, 7361.3, 7646.6,
          7515.8, 6505.8, 6167.3, 6398.9, 6765.5, 6254.8, 7408.7,
          8234.1, 7014.3, 6231.6, 6379.1, 6734.8, 7189.6, 6184.3,
          6519.0, 6729.6, 6603.9, 6596.3, 6321.7, 6572.2, 6494.2,
          6386.2, 6427.1, 5621.8, 3920.4, 4196.2, 3430.4, 3228.7,
          3964.4, 3706.8, 3785.4, 3597.2, 3677.8, 3570.9, 3502.5,
          3661.4, 3616.8, 4120.4, 3823.1, 3944.3, 4006.4, 4002.5,
          4111.8, 5046.2, 5051.8, 5290.2, 5265.9, 5830.9, 7190.3,
          7262.6, 8027.4, 8545.7, 7901.4, 8812.5, 10721.7, 11906.5,
          11268.0, 11364.9, 10826.7, 9492.1, 10815.7, 11314.5, 10218.1,
          10131.0, 9594.4, 10461.1, 10337.3, 9993.0, 8208.5, 8127.3,
          8304.4, 7957.3, 9230.6, 9300.6, 8804.5, 8497.3, 7324.1,
          7546.6, 7510.9, 7080.8, 7156.2, 7321.5, 7376.8] 
```

### 2. CPU Usage
The following data is the average hourly CPU usage for a worker’s computer over the course of a week. Each row of data represents a day of the week starting with Monday. Each column of data represents an hour of the day starting with 0 to midnight.
Use data visualization to answer the following questions:
- What time does the worker typically eat lunch?
- Does the worker work on weekends?
- What day of the week does the worker start working on their computer in the evening?

```python
cpu_usage = [[2, 2, 4, 2, 4, 1, 1, 4, 4, 12, 22, 23, 45, 9, 33, 56, 23, 40, 21, 6, 6, 2, 2, 3],
             [1, 2, 3, 2, 3, 2, 3, 2, 7, 22, 45, 44, 33, 9, 23, 19, 33, 56, 12, 2, 3, 1, 2, 2],
             [2, 3, 1, 2, 4, 4, 2, 2, 1, 2, 5, 31, 54, 7, 6, 34, 68, 34, 49, 6, 6, 2, 2, 3],
             [1, 2, 3, 2, 4, 1, 2, 4, 1, 17, 24, 18, 41, 3, 44, 42, 12, 36, 41, 2, 2, 4, 2, 4],
             [4, 1, 2, 2, 3, 2, 5, 1, 2, 12, 33, 27, 43, 8, 38, 53, 29, 45, 39, 3, 1, 1, 3, 4],
             [2, 3, 1, 2, 2, 5, 2, 8, 4, 2, 3, 1, 5, 1, 2, 3, 2, 6, 1, 2, 2, 1, 4, 3],
             [1, 2, 3, 1, 1, 3, 4, 2, 3, 1, 2, 2, 5, 3, 2, 1, 4, 2, 45, 26, 33, 2, 2, 1]]
```