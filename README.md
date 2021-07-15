# trading-behavioral-biases-detector-thai

## Problem
Since the 2020 pandemic, trading has become the new normal for many Thais in both [Stocks](https://www.bangkokpost.com/business/2048747/sharp-rise-in-online-trading-on-stock-market) and [Cryptocurrency](https://www.bangkokpost.com/business/2103539/april-sees-surge-in-retail-cryptocurrency-traders) markets. To illustrate, online accounts trading on the Thai stock market nearly doubled last year (Bangkokpost). However, most of people who opened their account last year have very little or no exprience in trading, let alone skills to survive the dynamic of financial markets. One of the skills inexperienced trader lack most is trading psychology and understanding of themself. Traditional way to optimally learn trading psychology is to write a trading diary and let professional coach review your trade, but most trader don't have access to professional coach.


## Proposed solution
We will create a sentiment analysis web app to read trader's diary in Thai language and classify their trading behavioral biases into 13 common biases discussed in Van K Thrap's classic book, [Trade your way to financial freedom](https://www.amazon.com/Trade-Your-Way-Financial-Freedom/dp/007147871X).


## Initial idea
- Use pretrained multipurpose nlp model from [WangchanBERTa](https://airesearch.in.th/releases/wangchanberta-pre-trained-thai-language-model/) to finetune model
- Collect data from web sracpping or from [project R](https://github.com/quant-hub)'s internal weekly discussion and invite professinal trader to label it.
- Explain output of the model using [Shap](https://github.com/slundberg/shap)
- Publish model to huggerface.
- Deploy as web app using [Streamlit](https://streamlit.io) with the help of Docker compose and Google cloud run.
- Connect with Google speech to text API


## Project plan
- Start after my internship ends (August).
- Will evaluate the possibility of extends this as a senior project.
