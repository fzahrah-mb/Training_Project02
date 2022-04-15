# Feed Forward Neural Network for Diamond Price Prediction
_Using a Feed Forward Neural Network (Deep Learning) model to predict the price of a diamond_

## Description

- The model utilises the [Diamonds Data Set from Kaggle][df1] to predict the price of a certain given diamond
- In a summary, the data set are required from a snapshot of Tiffany & Co's pricelist from 2017.
- A Feed Forward Neural Network is used for the project because of the relatively high number of the data, approximately 54,000 data.

## Methodology
#### The project can be divided into several sections:
- Data Acquisition
- Data Preprocessing
- Data Features & Label Definition
- Data Scaling
- Model Creation
- Model Training
- Model Prediction

## Results
- The training was set to run for 20 epochs. However, Early Stopping has occured the 17th epoch.
- Model evaluation was done after model training and the results are:
    - Test loss = 467303.47
    - Test accuracy = 467303.47
    - Test MAE = 324.13

## License
Copyright (c) [2022] [Fatimah Zahrah binti Mohd Badry]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
MIT

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [df1]: <https://www.kaggle.com/datasets/shivam2503/diamonds>