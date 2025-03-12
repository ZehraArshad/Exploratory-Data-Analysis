# What is an outlier?

- Below is the best representation of outliers
<br/>

![image](https://github.com/user-attachments/assets/53c6ea2a-65f4-4169-991c-49e9d99730f2)

- Outlier is a value very different from the patter
- It is not necessary that it is always an error
- gender = [0,0,0,1,1,0, ..... 999] - Here **999** is an outlier and an error
- age = [18, 16, 15, ...,45] here **45** is not an outlier because there is some aged 45 in the data
- sometimes, we remove these outliers, sometimes we don't, depends on the **Domain Knowledge**
- But it can affect the mean alot, so use medians

## How to deal with?

- Make box plots
- Identify distribution
- Go to [dist](https://github.com/ZehraArshad/Python_For_DA)
- Use either IQR, Zscore depending on the dist
- Either remove the outlier, keep them or Winsorization or log transformations
