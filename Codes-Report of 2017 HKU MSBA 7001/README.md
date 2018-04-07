# 美日货币对走势预测——基于3种基础机器学习方法
# Rate Prediction of USDJPY based on 3 basic machine learning methods

This proect is about the use of 3 Basic Machine Learning Methods for forex prediction on USDJPY.
The main effort is contributed before the model training part, which means the data clearning and merging part.
The part shows how to scrap and acquire data from different data sources and clean,aggregate and marge them together without causing a data leakage, which is fatal to your models' performances.
Most of the resources in the codes are not valid or effective at this moment. For example, the Google data acquired with pandas-datareader is not available because of policy change from Google, and the cftc data can be more easily acquired using quandl, I used scrapping way just for a higher score.
One breakout thinking in the research is to set a "thresh" concept when labeling the data.
A modificated version of the model has been used by Cloudhandstrading Co. Ltd in Beijing for the Option Strategy part of its Weekly Report to CME.
If you have any questions, suggestions or find anything wrong in the reports or codes. Please don't hesitate to let me know.

这个项目是有关使用3种基础机器学习方法进行外汇预测的。
最主要的部分其实是模型训练之前的数据清洗和整合部分。
这一部分展示了我如何从不同数据来源取得数据，并且清洗，归结，整合数据。并且在这一过程中如何尽力避免数据泄露，保证最终的模型训练的准确性。
需要注意的是，这个代码中大部分数据源已经失效或数据采集方式不高效。比如：pandas-datareader的google数据由于google方面政策变动问题已经失效；quandl取cftc数据会是一个更高效的方式，在这里我只是为了使用爬虫加分。
我认为研究中的一个突破是我设定了一个thresh参数来进行训练及测试用label的构建。
这个研究的一个修改版目前正在被“北京云核变量教育咨询有限公司”使用，作为其每周为CME撰写的外汇周报中期权策略的来源。
若您对研究报告、代码或外汇周报有任何疑问、建议或指教，请随时联系我。
