# Predicting Low Cloud Albedo in Extratopical Cyclones with a Shallow Neural Network 

In previous work, a few key cloud controlling factors (CCFs) were identified to predict the mesoscale morphologies of low clouds in extratropical cyclones (Tong et al., 2025). These CCFs are also found to explain ~31% of the total variance of the cyclone averaged albedo normalized by solar angles (a<sub>n</sub>). In this project, we are interested in testing how much improvement of predictive skill can be obtained after accounting for the nonlinear interactions between the CCFs and low cloud albedo. A shallow multilayer perception (MLP) was applied to both the CCFs and the principal components (PCs) extracted from the CCFs. No significant improvement was found in either case. Partial dependence and sensitivity analyses suggest that most CCFs have a near-linear relationship with albedo, and CCFs that have a nonlinear relationship with albedo are less important in albedo prediction. We conclude that, within a low-dimensional meteorological subspace, albedo variability is primarily governed by approximately linear relationships.

  
  
  
Due to the author's laziness during the holiday season, the figures are referenced in the writeup but not captioned. The author believes, though, that the figures are well labeled and can be understood. One hint: solar angle normalized albedo (a<sub>n</sub> in the writeup) can appear as alb_corr (albedo corrected) or simply y in the figures. 
