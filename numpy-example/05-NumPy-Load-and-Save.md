# **Two Important Python Library used for Data Science**
- **What is Python Library?**

## **Saving and Loading of NumPy Array**
- Examples for Saving NumPy
        ``` Python
        import numpy as np
        n1=np.array([10,20,30,40,50,60])
        np.save('my_numpy',n1)
        ```

- Examples for Saving NumPy
        ```Python
        import numpy as np
        n2=np.load('my_numpy.npy')
        print(n2)
        ```