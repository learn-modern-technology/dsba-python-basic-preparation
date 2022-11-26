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

## **Joining NumPy Arrays - Examples**  
    - There are three stack function that we can use for joining arrays  
        a. vstack()  
        b. hstack()  
        c. column_stack()  
    - Examples of vstack()  
    ```  Python
    import numpy as np
    n1 = np.array([10,12,14,16,18,20])
    n2 = np.array([100,200,300,400,500])
    final = np.vtack((n1,n2))
    print(final)
    ```

    - Examples of vstack()  
    ```  Python
    import numpy as np
    n1 = np.array([10,12,14,16,18,20])
    n2 = np.array([100,200,300,400,500,600])
    final = np.htack((n1,n2))
    print(final)
    ```

    - Examples of column_stack()  
    ```  Python
    import numpy as np
    n1 = np.array([10,12,14,16,18,20])
    n2 = np.array([100,200,300,400,500,600])
    final = np.column_stack((n1,n2))
    print(final)
    ```


