# Metal-Furnace-Challenge
My solution of Metal Furnace Challenge Predict The Grade Of An Alloy 

**Manufacturing of any alloy is not a simple process. Many complicated factors are involved in the making of a perfect alloy, from the temperature at which various metals are melted to the presence of impurities to the cooling temperature set to cool down the alloy. Very minor changes in any of these factors can affect the quality or grade of the alloy produced.**

<img src="https://www.machinehack.com/wp-content/uploads/2020/04/MetalFurnace-01-1536x864.jpg" width=700 height=400>

Given are 28 distinguishing factors in the manufacturing of an alloy, your objective as a data scientist is to build a Machine Learning model that can predict the grade of the product using these factors.

You are provided with 28 anonymized factors (f0 to f27) that influence the making of a perfect alloy that is to be used for various applications based on the grade/quality of the obtained product.

**Data Description**  
The unzipped folder will have the following files.

- Train.csv – 620 observations.
- Test.csv – 266 observations.
- Sample Submission – Sample format for the submission.
- Target Variable: grade


**My Approach**:

1. On EDA f9 feature had only one unique value, 'f9' feature was removed.
2. Transforming the test feature values into train feaures, as there was a linear relation between the feature values.
3. Xgb model trained on 80% of the train data and validation on 20% of the data.

**Public rank**: 10  
**Private rank**: 1



