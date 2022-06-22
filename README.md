# EGDataset

Exploration Global Dataset is a dataset provided by a hybrid model to perform malware detection on Android applications. This dataset is based on a hybrid model (static and dynamic analysis) with an exploration approach.

# Purpose
The approach used to obtain this dataset investigates the general application's features. Then this performs some investigations on the several nodes to analyze the global app behavior.Finally, you can read the result obtained after using machine learning analysis on the dataset (Random Forest and SVM algorithms) and a k-folds approach with ten occurrences.

|Algorithms|Accuracy|Precision|Recall|F1_Score|
|---|---|---|---|---|
|Random Forest|0.957|0.957|0.957|0.957|
|SVM|0.945|0.945|0.945|0.945|

# Dataset Population

This dataset is composed by 1072 records (461 benigns and 611 malwares). Benign app are extracted from "ApkPure" web service (https://m.apkpure.com/fr/) and malwares from "VirusShare".

# Features metrics

You could find in this table the list of features include in this dataset.

|Feature|Type|
|---|---|
|Providers number| Extracted|
|Extern attribute| Extracted|	
|Strings Global number	| Extracted|
|Dex number| Extracted|	
|Intern attribute| Extracted|	
|Argument Type number| Extracted|	
|Balise number	| Extracted|
|Call number| Extracted|	
|Special strings number| Extracted|	
|Custom Argument| Calculated|	
|Affectation number| Calculated|	
|Number of sginature permission| Extracted|	
|Number of Dangerous permission| Extracted|	
|Average size of class| Calculated|	
|Services number| Extracted|	
|Android API| Extracted|	
|Receivers Numbers| Extracted|	
|Unicode number| Extracted|	
|URL Number| Extracted|	
|Weighted Method per class| Calculated|	
|Reponse for class| Calculated|	
|Class number	| Extracted|
|Permission number| Extracted|	
|Other Permission number| Extracted|	
|Number of child| Calculated|	
|Other Type String Number| Extracted|	
|System Args| Calculated|


# Availability
This dataset is under an open-source license, but the model's code is unavailable for privacy reasons. However, if you have any questions before using it, you can contact me by e-mail (damien.strullu@gmail.com) or Linkedin (https://www.linkedin.com/in/damienstrullu/).

# Special Thanks

This dataset is obtained due to the participation "VirusShare" (https://virusshare.com/) and "VirusTotal" (https://www.virustotal.com/) to perform some detection on the sample data provided.
