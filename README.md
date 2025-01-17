# Advent of Code Solutions
This repository contains (almost) all of my solutions to Advent of Code through the years.

The first year I participated in Advent of code was 2017 but I only got a couple of days back then.
In 2018 I was able to get a bit further but 2019 was the first year I actually got all the way to
the end (and got points on the global leaderboard). Back then I used C++ but in 2020 I changed
primarily to Python to make writing the code faster as I hadn't had enough practice during the year.

| Year          | :star: | Points | Rank | Main language |
| :------------ | -----: | -----: | ---: | :------------ |
| [2015](/2015) |     41 |      - |    - | _Python_      |
| [2016](/2016) |     20 |      - |    - | _Python_      |
| [2017](/2017) |      8 |      - |    - | _Rust_        |
| [2018](/2018) |     28 |      - |    - | _C++_         |
| [2019](/2019) |     50 |     57 |  551 | _C++_         |
| [2020](/2020) |     50 |     10 |  803 | _Python_      |
| [2021](/2021) |     50 |    178 |  286 | _Python_      |
| [2022](/2022) |     50 |     33 |  772 | _Python_      |
| [2023](/2023) |     50 |     12 | 1015 | _Python_      |
| [2024](/2024) |     40 |     26 |  845 | _Python_      |
|               |        |        |      |               |
| **Total**     |    387 |    316 | 1358 |               |


## Python template
In 2021 I decided that I finally need to start building myself a framework to help read the input,
run the example cases as tests, measure the execution time, and most importantly :sparkles: look
pretty :sparkles:.

![a screenshot of what my python template prints to the terminal](output-example.png)


## Inputs (private submodule)
### File tree
```
inputs/
|-- 2015/
|   |-- 01.txt
|   |-- ...
|   `-- 25.txt
|-- .../
`-- 2023/
    |-- 01/
    |   |-- 0.txt
    |   |-- ...
    |   `-- input.txt
    |-- .../
    `-- 25/
        `-- ...
```

### Test data (n.txt)
```
input line 1
input line 2
input line 3
...
input line n


part 1 answer or - to skip

part 2 answer or - to skip
```