# Machine Learning Homework - Exoplanet Exploration


Tools / Technologies used: Python, SVM (Machine Learning Model), and Random forest 

Summary


Random Forest is better than SVM.

SVM

                     Before CV                     After CV
Training Data Score: 0.843410261300782            0.8743086019454511
Testing Data Score: 0.8421052631578947            0.8718535469107551

                 precision    recall  f1-score   support

     CANDIDATE       0.84      0.61      0.71       422
     CONFIRMED       0.71      0.87      0.78       450
FALSE POSITIVE       0.98      1.00      0.99       876

      accuracy                           0.87      1748
     macro avg       0.84      0.83      0.83      1748
  weighted avg       0.88      0.87      0.87      1748


  Random Forest

  
                 Before CV	                          After CV
Training Score	0.9956131985504482                     1.0
Testing Score	0.8947368421052632                     0.9016018306636155

                  precision    recall  f1-score   support

     CANDIDATE       0.83      0.76      0.80       422
     CONFIRMED       0.81      0.85      0.83       450
FALSE POSITIVE       0.98      1.00      0.99       876

      accuracy                           0.90      1748
     macro avg       0.87      0.87      0.87      1748
  weighted avg       0.90      0.90      0.90      1748


