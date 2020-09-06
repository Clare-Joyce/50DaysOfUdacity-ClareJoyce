# Day 44
**Intro Machine Learning**
* Feature scaling
* Comparing features with different scales.
* When feature scaling is critical and when it is unnecessary.
* MinMaxScaler in Sklearn
* Feature Scaling mini project with Enron dataset.

**One:**
```ruby
def featureScaling(arr):
    x_min = min(arr)
    x_max = max(arr)
    rs_arr = []
    for x in arr:
        rs_arr.append((float(x)-x_min)/(x_max - x_min))

    return rs_arr

# tests of your feature scaler--line below is input data
data = [115, 140, 175]
print featureScaling(data)
```
**Two:**
```ruby
def featureScaling(arr):
    x_min = min(arr)
    x_max = max(arr)
    rs_arr = [((float(x)-x_min)/(x_max - x_min)) for x in arr]

    return rs_arr

# tests of your feature scaler--line below is input data
data = [115, 140, 175]
print featureScaling(data)
```
