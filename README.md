# Artist_Recognition
An AI model designed to figure out the name of the artist given his/her painting.

The model uses VGG19 as it's base model and an art dataset found on Kaggle.  
During training, the model achieves over 70% accuracy, however in testing the accuracy is 55%. While not as high as one might hope, considering there are over 40 artists in the database, many with relatively simillar painting styles, the accuracy is well over baseline.  
However, further work on the model is needed. The difference between the testing an training accuracy shows clear signs of overfitting. While the dataset is certianly a big part of the reason, surely the model could be better fine tuned to achieve greater testing performance, something I look forward to doing in the future.  

## Running the code
The code was written in Google Colab. Therefore I suggest opening it there (you can do so through github) and running the cells in order.
