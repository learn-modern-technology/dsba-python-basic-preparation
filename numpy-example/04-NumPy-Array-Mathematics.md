# **Two Important Python Library used for Data Science**
- **What is Python Library?**

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
    - Examples for basic math function
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

