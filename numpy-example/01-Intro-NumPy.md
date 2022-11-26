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

## **Some Basics of NumPy - Examples**
    - Single-Dimensional Array  
        - Example 1:  
        ``` Python
        ## Single-Dimensional Array
        import numpy as np
        n1 = np.array([10,20,30,40,50])
        print(n1)
        ```

    - Multi-Dimensional Array  
        - Example 2:  
        ``` Python
        ## Multi-Dimensioanl Array
        import numpy as np
        n2 = np.array([[10,20,30,40],[40,30,20,10]])
        print(n2)
        ```

    - Initialize Numpy Arrays with Zeros  
        - Example 3:  
        ``` Python
        ## Initialize Numpy Arrays with Zeros
        import numpy as np
        n3 = np.zeros((1,2))
        print(n3)
        ```

        - Example 4:  
        ``` Python
        ## Initialize Numpy Arrays with Zeros
        import numpy as np
        n4 = np.zeros((5,5))
        print(n4)
        ```
    - Initializing Numpy Array with same number  
        - Example 5:  
        ``` Python
        ## Initializing Numpy Array with same number
        ## This method can be used to initialize the Array with ZERO Value as well.
        import numpy as np
        n5 = np.full((2,6),29)
        print(n5)
        ```
    - Initializing Numpy Array within a range  
        - Example 6:  
        ``` Python
        ## Initializing Numpy Array within a range
        import numpy as np
        n6 = np.arange(10,20)   ## 20 in exclusive
        print(n6)
        ```
        - Example 7: 
        ``` Python
        ## Initializing Numpy Array within a range using the step
        import numpy as np
        n7 = np.arange(10,50,5)   ## 5 is skip value
        print(n7)
        ```
    - Initializing NumPy Array with random numbers  
        - Example 8:
        ``` Python
        import numpy as np
        n8 = np.random.randint(1,100,5)  ## To get 5 random integers from 1 to 100
        print(n8)
        ```
    - Checking and Changin the shape of NumPy Array  
        - Example 9:
        ``` Python
        ## Multi-Dimensioanl Array
        import numpy as np
        n9 = np.array([[10,20,30,40],[40,30,20,10]])
        print(n9)
        print(n9.shape)
        #n9.shape = (3,2)## cannot reshape array of size 8 into shape (3,2)
        #print(n9)
        #print(n9.shape)
        n9.shape = (4,2)
        print(n9)
        print(n9.shape)
        ```
