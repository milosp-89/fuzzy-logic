# Implementation of a fuzzy logic membership function

About:
- In the realm of fuzzy logic, the application of a fuzzy logic membership function is foundational
  to the process of modeling uncertainty and imprecision within a system. At its core, a membership
  function serves as a bridge between crisp, precise input values and the fuzzy, ambiguous boundaries of a fuzzy set.
  This mathematical function assigns membership degrees to elements within the universe of discourse,
  indicating the degree to which each element belongs to the fuzzy set under consideration.

Main sources and documentation:
- https://pypi.org/project/scikit-fuzzy/
- https://github.com/scikit-fuzzy/scikit-fuzzy
- https://scikit-fuzzy.github.io/scikit-fuzzy/overview.html

Additional sources (theory):
- https://www.youtube.com/watch?v=__0nZuG4sTw&t=781s
- https://www.youtube.com/watch?v=CBTEVFphv-E

Main module and pip installation:
- scikit-fuzzy==0.4.2

Other modules used:
- pandas for dataframe manipulation
- numpy for additional dataframe manipulations
- warnings to avoid unnecessary warning messages
- matplotlib for visualization of graphs
- multiprocessing (will be included in some point) for
  dealing with performance over the time

Environment setup (used for this project):
- Python version: 3.8.18
- Anaconda version: 23.5.2
- Jupyter Notebook version: 7.0.8

Next Steps:
- Refine parameters, variables, and functions, both for input and output (fine-tuning)
- Implement parallelism using multiprocessing to leverage all CPU cores, aiming to accelerate the code execution.
  The current runtime is approximately 4.0 minutes, however, with the addition of more rules and a growing dataset,
  implementation becomes necessary to maintain performance over time

# Status setup (dummy dataset example):
![status](https://github.com/milosp-89/fuzzy-logic/assets/155644532/0be989c8-7797-4daf-b825-157f4f75f9d6)

# Trend setup (dummy dataset example):
![trend](https://github.com/milosp-89/fuzzy-logic/assets/155644532/a2b01a54-628d-40a0-be44-0f2653c336cf)

# Peak setup (dummy dataset example):
![peak](https://github.com/milosp-89/fuzzy-logic/assets/155644532/c4ba6267-a7a5-4cb8-9aae-0fa20a71e468)

# Output setup (dummy dataset example):
![output](https://github.com/milosp-89/fuzzy-logic/assets/155644532/652dc8c5-e342-4ad7-9120-b01bdcb926b2)

# Output value after applying function rule (dummy dataset example):
![output_value_rule](https://github.com/milosp-89/fuzzy-logic/assets/155644532/a67c63f7-b83e-42da-bc45-d51efe16990f)

# Input file before implementation (dummy dataset example):
![input_file](https://github.com/milosp-89/fuzzy-logic/assets/155644532/8d4d8791-fe45-4447-815f-83bf28639503)

# Output file after implementation (dummy dataset example):
![output_file](https://github.com/milosp-89/fuzzy-logic/assets/155644532/736918f7-7684-4901-a854-fe1cd5673b63)
