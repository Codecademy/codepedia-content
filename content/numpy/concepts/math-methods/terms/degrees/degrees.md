---
Title: '.degrees()'
Description: 'Converts radians to degrees.'
Subjects:
  - 'Computer Science'
  - 'Data Science'
Tags:
  - 'Arrays'
  - 'Functions'
  - 'NumPy'
CatalogContent:
  - 'learn-python-3'
  - 'paths/computer-science'
---

In NumPy, the **`.degrees()`** function converts an angle measure from radians to degrees.

## Syntax

```pseudo
numpy.degrees(x)

numpy.degrees([x, x, x])
```

- `x`: The number or array of numbers in radians that must be converted.

## Example 1

```py
# Importing the 'numpy' library as 'np'
import numpy as np

# Convert a single number from radians to degrees
radNum = 4
result = np.degrees(radNum)
print(result)
```

The output of the above code is shown below:

```shell
229.1831180523293
```


## Example 2

```py
# Importing the 'numpy' library as 'np'
import numpy as np

# Convert an array of numbers from radians to degrees
radArray = [ 2, 4, 5, 8]
result = np.degrees(radArray)
print(result)
```

The output of the above code is shown below:

```shell
[114.59155903 229.18311805 286.47889757 458.3662361 ]
```



## Codebyte Example

In this codebyte example, the `.degree()` method converts

```codebyte/python
import numpy as np

radArray = [ 1, 32, 100]
result = np.degrees(radArray)
print(result)
```