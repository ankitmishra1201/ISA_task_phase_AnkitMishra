#LOGISTIC REGRESSION


Regression deals with a predictive modelling technique. It shows the relation between independent also known as predictive variable or dependent or target value. Logistic regression comes int ouse when output is of categorical format such as yes/no , 1 or 0,true or false, high or low. As in linear regression we get output values over a large range but for the categorical output it should be between 1 and 0, hence the linear regression curve is to be clipped between 1 and o which is performed using logistic regression , for this we use a sigmoid function.

<img width="233" alt="Screenshot 2021-08-31 at 14 57 44" src="https://user-images.githubusercontent.com/75842497/131478646-3e27de16-650b-4bac-a574-0398c3e8cbe6.png">


concept of threshold: This is used to decide whether the output value(betwwen o and 1) rounds off to give the output as 0(low) or 1(high). The output values between threshold value(0.5) and 1 is rounded to 1 and the value below threshold and is rounded to 0.

concept of log likelihood: Using the concept of linear regression:

<img width="288" alt="Screenshot 2021-08-31 at 14 58 41" src="https://user-images.githubusercontent.com/75842497/131478597-93b2f6c7-b417-4130-8e20-e1a3d56fa40f.png">


putting the above value in sigmoid equation:


Now , by taking inspiration from Bernaulli's traits, we find the log likelyhood function and differentiating it to find the gradient ascent update equation. Hence the likelihood is defined as :

<img width="269" alt="Screenshot 2021-08-31 at 15 00 13" src="https://user-images.githubusercontent.com/75842497/131478793-926b7555-ff93-45f7-a2c7-9e54798cc184.png">


log likelihood becomes:

<img width="423" alt="Screenshot 2021-08-31 at 15 01 13" src="https://user-images.githubusercontent.com/75842497/131478945-7b27509e-1aeb-4a3b-bb59-c12d3a6fdebe.png">


differenciating it:

<img width="289" alt="Screenshot 2021-08-31 at 15 02 00" src="https://user-images.githubusercontent.com/75842497/131479067-93d635b7-3f8b-4073-adcb-41e235290111.png">


The gradient ascent update equation becomes:

<img width="172" alt="Screenshot 2021-08-31 at 15 02 59" src="https://user-images.githubusercontent.com/75842497/131479193-810f5bfc-6c3f-4254-b57e-95e3c9d37df1.png">

