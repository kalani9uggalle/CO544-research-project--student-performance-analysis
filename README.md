
To compile the models with .model extension use weka software.

There was 12 attributes(with performance) at the beginning.some attributes were removed with the results of correlation of attributes.
These remaining attributes were trained with the six classifiers.
The trained models are included in following folders.
>>with percentage split(train:80%)-> "model_with4_attributes_split" folder
>>with 5 fold cross validation -> "model_with4_attributes_cross_validation folder

Next,using learner based feature selection algorithm some other attributes are further removed.
These remaining attributes were trained with the six classifiers.
The trained models are included in following folders.
>>with 5 fold cross validation and percentage split -> "Final_Attributes_Trainig" folder

The models developed before mid evaluation are included in "mid" folder.
