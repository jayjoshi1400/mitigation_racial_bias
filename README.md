# Mitigating Racial Bias in Criminal Justice: Code Black

MLH NC State Hackathon Project (Feb 2 - Feb 3, 2024)

By Rishabh Kala, Jay Joshi, [Teddy Xinyuan Chen](https://teddysc.me), and Lixing Zheng.

- [Mitigating Racial Bias in Criminal Justice: Code Black](#mitigating-racial-bias-in-criminal-justice-code-black)
  - [Demo](#demo)
  - [Inspiration](#inspiration)
  - [What it does](#what-it-does)
  - [How we built it](#how-we-built-it)
  - [Challenges we ran into](#challenges-we-ran-into)
  - [Accomplishments that we're proud of](#accomplishments-that-were-proud-of)
  - [What we learned](#what-we-learned)
  - [What's next for Mitigating Racial Bias in Criminal Justice: Code Black](#whats-next-for-mitigating-racial-bias-in-criminal-justice-code-black)


## Demo

https://hack-ncsu.teddysc.me

## Inspiration

Our team researched about the bias existing in the criminal justice systemte and wanted to help in mitigating it, Therefore, we decided to go for systemmatic analysis and mitigation bias against black in the society, esp. in the criminal justice system and around machine learning models. That's why we made this, to visually show the racial bias in the models when it comes to predicting recividism rate between black and the general population with some ways to mitigate it.

## What it does

We wanted to show that such a bias existed and ways in which we can mitigate it. For this, we decided to  analyze a dataset which showcased the results of a 2 year follow-up study on individuals to find out if the predicted recidivism rate was actually correct. The results did show a bad accuracy in general but moreover the results that indicated a racial bias and we tried to visually showcase it. Then we decided to use existing classifier algorithms such as Naive Bayes, Decision Tree, Random Forest and Logistic Regression, to actually classify the data along with the new follow-up results, in an effort to mitigate the exisgting bias and we achieved accuracies much better than the previous model. We then converted the data which we had into a graphical format and represented it. 

## How we built it

We searched for a dataset with relevant data and then looked into precprocessing this data. We used PCA for feature selection and then applied the right machine learning classification models to it. After that, we graphically represented this data, such that, it is easier to interpret. Front end: a carousel page for showing figures visualizing the models' results. Built with Next.js and Tailwind CSS, hosted on Cloudflare.

## Challenges we ran into

The biggest challenge which we ran into was finding and interpreting the right dataset. We needed a credible and reliable dataset for this project and this proved to be quite challenging in the beginning, but collectively, we were able to find the right fit. Moreover, we had to also select the right machine learning models for this project and that was challenging but again teamwork came to the rescue and we were able to pick the right ones.

Next.js's buggy documentation also cost us a lot of time.

## Accomplishments that we're proud of

We discovered that the current system used to predict recividism might be flawed and biased. We leveraged data driven techniques to make more accurate prediction on recividism and hence, seeing to it that the bias that these systems have was eliminated.


## What we learned

We learned how to leverage technology for social good and promote equality. Moreover, we learned a lot about the use of machine learning model and data visualization.

## What's next for Mitigating Racial Bias in Criminal Justice: Code Black

We can work with more recent data as well as leverage more cutting edge models in order to eliminate this bias even further. We can also make the website more interactive with the functionality to run and test different models in the background. 
