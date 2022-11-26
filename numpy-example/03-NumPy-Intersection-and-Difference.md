# **Two Important Python Library used for Data Science**
- **What is Python Library?**
    - Python library is collection of function and methods that allows us to perform many actions without writing our own code
    - Numerical Computing - NumPy
    - For Visualization - matplotlib, Searnborn, plotlead
    - For Data Manipulation - pandas
    - For Machine Learning Algorithms - Scikit-learn
    - Deep Learning Framework - TensorFlows and Keras

## **NumPy - Numerical Python**
- It is the core library for numeric and scientific computing
- It consists of multi-dimensional array objects and a collection of routines for processing those arrays.

## **Numpy Intersection & Difference**
    - There are 2 functions that help us to find the Intersection and Different elements in NumPy Array.  
        a. intersect1d
        b. setdiff1d
    - Examples for intersect1d
        ``` Python
        import numpy as np
        n1=np.array([10,20,30,40,50,60])
        n2=np.array([50,60,70,80,90])
        intersect = np.intersect1d(n1,n2)
        print(intersect)
        ```

    - Examples for setdiff1d
        ``` Python
        import numpy as np
        n1=np.array([10,20,30,40,50,60])
        n2=np.array([50,60,70,80,90])
        n1minusn2 = np.setdiff1d(n1,n2)
        print(n1minusn2)
        ```
    - Examples for setdiff1d
        ``` Python
        import numpy as np
        n1=np.array([10,20,30,40,50,60])
        n2=np.array([50,60,70,80,90])
        n2minusn1 = np.setdiff1d(n1,n2)
        print(n2minusn1)
        ```