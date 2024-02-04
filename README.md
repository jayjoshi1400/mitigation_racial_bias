# Mitigating Racial Bias in Criminal Justice: Code Black

By ... [Teddy Xinyuan Chen](https://teddysc.me) ...

## Inspiration

I (Teddy) attended a Black History Month event focused on `soul foods` on campus and was inspired to make more people learn a little bit more about black culture. Our team researched about the bias existing in the criminal justice systemte and wanted to help in mitigating it, Therefore, we decided to go for systemmatic analysis and mitigation bias against black in the society, esp. in the criminal justice system and around machine learning models. That's why we made this, to visually show the racial bias in the models when it comes to predicting recividism rate between black and the general population with some ways to mitigate it.

## What it does

We wanted to show that such a bias existed and ways in which we can mitigate it. For this, we decided to  analyze a dataset which showcased the results of a 2 year follow-up study on individuals to find out if the predicted recidivism rate was actually correct. The results did show a bad accuracy in general but moreover the results that indicated a racial bias and we tried to visually showcase it. Then we decided to use existing classifier algorithms such as Naive Bayes, Decision Tree, Random Forest and Logistic Regression, to actually classify the data along with the new follow-up results, in an effort to mitigate the exisgting bias and we achieved accuracies much better than the previous model. We then converted the data which we had into a graphical format and represented it. 

## How we built it

We searched for a dataset with relevant data and then looked into precprocessing this data. We used PCA for feature selection and then applied the right machine learning classification models to it. After that, we graphically represented this data, such that, it is easier to interpret.

Front end: a carousel page for showing figures visualizing the models' results. Built with Next.js and Tailwind CSS, hosted on Cloudflare.

## Challenges we ran into

The biggest challenge which we ran into was finding and interpreting the right dataset. We needed a credible and reliable dataset for this project and this proved to be quite challenging in the beginning, but collectively, we were able to find the right fit. Moreover, we had to also select the right machine learning models for this project and that was challenging but again teamwork came to the rescue and we were able to pick the right ones.

Next.js's buggy documentation also cost us a lot of time.

## Accomplishments that we're proud of



## What we learned



## What's next for Mitigating Racial Bias in Criminal Justice: Code Black
