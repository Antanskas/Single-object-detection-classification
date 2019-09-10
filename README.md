# Object_classification+localization

* ### Idea ![](https://github.com/Antanskas/Single-object-detection-classification/blob/master/repository_images/idea.png)
  * Classify and localize 7 dog breeds using resnet  + regression heads ![dog img](https://github.com/Antanskas/Single-object-detection-classification/blob/master/repository_images/dog.png)


* ### Environment ![colab img](https://github.com/Antanskas/Object_classification-localization/blob/master/repository_images/colab.png)
  * Google colaboratory GPU 

* ### Dataset ![books img](https://github.com/Antanskas/Single-object-detection-classification/blob/master/repository_images/books.png)
  * Chose 7 common dog breeds from Stanford Dogs Dataset. Training on 1193 images 

* ### Training ![](https://github.com/Antanskas/Single-object-detection-classification/blob/master/repository_images/graph.png)
  * Classification part was inspired by ResNet architecture principles and for localization only changed last resnet layers to regression layers to predict x1, y1, x2, y2 boundary boxes corners coordinates. Training notebook named _train.ipynb_, testing notebook - _test.ipynb_

   * Classification head training accuracy during 300 epochs on Google colab GPU  
![classification training accuracy img](https://github.com/Antanskas/Object_classification-localization/blob/master/models/ResNet50_300/ResNet50_300_acc.png)
   * Classification head training loss during 300 epochs on Google colab GPU  
![classification training loss img](https://github.com/Antanskas/Object_classification-localization/blob/master/models/ResNet50_300/ResNet50_300_loss.png)

  * Regression head training accuracy during 15 epochs on Google colab GPU  
![regression training accuracy img](https://github.com/Antanskas/Object_classification-localization/blob/master/models/Regression/regression_15_acc.png)
  * Regression head training loss during 15 epochs on Google colab GPU  
![regression training loss img](https://github.com/Antanskas/Object_classification-localization/blob/master/models/Regression/regression_15_loss.png)

* ### Results
- - -
![Image 1](https://github.com/Antanskas/Object_classification-localization/blob/master/outputs/output_1.PNG)  
- - -
![Image 2](https://github.com/Antanskas/Object_classification-localization/blob/master/outputs/output_2.PNG) 
- - -
![Image 3](https://github.com/Antanskas/Object_classification-localization/blob/master/outputs/output_3.PNG)   
- - -
![Image 4](https://github.com/Antanskas/Object_classification-localization/blob/master/outputs/output_4.PNG)   
- - -
![Image 5](https://github.com/Antanskas/Object_classification-localization/blob/master/outputs/output_5.PNG)  
- - -
![Image 6](https://github.com/Antanskas/Object_classification-localization/blob/master/outputs/output_6.PNG) 
- - -
![Image 7](https://github.com/Antanskas/Object_classification-localization/blob/master/outputs/output_7.PNG)
- - -
