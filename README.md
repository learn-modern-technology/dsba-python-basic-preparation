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

## **Addition of NumPy Array**
    - Below are mathematics functions that helps us to find the result of the expression.  
        a. sum
        b. sum with axis
        c. Addition, Multiplication, Subtraction and Division
    - Examples for sum
        ``` Python
        import numpy as np
        n1=np.array([10,20,30,40,50,60])
        n2=np.array([50,60,70,80,90,95])
        result_sum = np.sum([n1,n2])
        print("result_sum",result_sum)
        ```

    - Examples for sum with axis 0 
        ``` Python
        import numpy as np
        n1=np.array([10,20,30,40,50,60])
        n2=np.array([50,60,70,80,90,95])
        result_sum_axis0 = np.sum([n1,n2],axis=0)
        print("result_sum_axis0",result_sum_axis0)
        ```

    - Examples for sum with axis 1
       ``` Python
        import numpy as np
        n1=np.array([10,20,30,40,50,60])
        n2=np.array([50,60,70,80,90,95])
        result_sum_axis1 = np.sum([n1,n2],axis=1)
        print("result_sum_axis1",result_sum_axis1)
        ```

    - Examples for Basic Operations
       ``` Python
        import numpy as np
        n1=np.array([10,20,30,40,50,60])
        n2=np.array([50,60,70,80,90,95])
        result_basic_sum = n1 + 1
        result_basic_mul = n2 * 5
        result_basic_sub = n2 - 5
        result_basic_div = n1/10
        print("result_basic_sum",result_basic_sum)
        print("result_basic_mul",result_basic_mul)
        print("result_basic_sub",result_basic_sub)
        print("result_basic_div",result_basic_div)
        ```
    - Examples for basic math function with axis 1
       ``` Python
        import numpy as np
        n2=np.array([50,60,70,80,90,95])
        result_mean = np.mean(n2)
        result_median = np.median(n2)
        result_std = np.std(n2)
        print("result_mean",result_mean)
        print("result_median",result_median)
        print("result_std",result_std)
        ```

## **Saving and Loading of NumPy Array**
- Examples for Saving NumPy
        ``` Python
        import numpy as np
        n1=np.array([10,20,30,40,50,60])
        np.save('my_numpy',n1)
        ```

- Examples for Saving NumPy
        ``` Python
        import numpy as np
        n2=np.load('my_numpy.npy')
        print(n2)
        ```