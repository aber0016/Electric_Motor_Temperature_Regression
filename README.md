# Rotor_Temperature_Regression

This project seeks to design a model with appropriate feature engineering, that estimates one target temperature rotor temperature ("pm") in a causal manner. In order to maintain real-time capability, model sizes should be as small as possible, while retain a high level of prediction accuracy, as temperature estimation in production will be deployed on best-cost hardware of traction drives in an automotive environment, where lean computation and lightweight implementation is key and crucial.

The main purpose of the data set's recording is to be able to model the rotor temperatures of a permanent magnet synchronous motor (PMSM) in real-time. Due to the intricate structure of an electric traction drive, direct measurement with thermal sensors is not possible for rotor temperatures, and even in case of the stator temperatures, sensor outage or even just deterioration can't be administered properly without redundant modeling. In addition, precise thermal modeling gets more and more important with the rising relevance of functional safety. The available features to model the target can be seen below.

![alt text](https://github.com/aber0016/Rotor_Temperature_Regression/blob/main/rec_2.png?raw=true)
