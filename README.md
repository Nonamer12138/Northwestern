# -- Deep learning
python train.py source.csv cpu epoch_number batch_number

*The column scorePercentage_pre of result/student_knowledge.csv is the prediction value*

python predict.py 

# -- Statist Model

python build_knowledge_dataset.py ../data/wholedata.csv

python statistic_training_complete.py ../data/wholedata.csv ../result ../model
python statistic_training_complete.py ../data/new_data.csv ../result ../model ../new_model

python statistic_prediction.py ../model ../data/prediction_set.csv