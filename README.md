# EGDataset

Exploration Global Dataset is a dataset provided by a hybrid model to perform malware detection on Android applications. This dataset is based on a hybrid model (static and dynamic analysis) with an exploration approach.

# Purpose
The approach used to obtain this dataset investigates the general application's features. Then this performs some investigations on the several nodes to analyze the global app behavior.Finally, you can read the result obtained after using machine learning analysis on the dataset (Random Forest and SVM algorithms) and a k-folds approach with ten occurrences.

|Algorithms|Accuracy|Precision|Recall|F1_Score|
|---|---|---|---|---|
|Random Forest|0.957|0.957|0.957|0.957|
|SVM|0.945|0.945|0.945|0.945|

# Article linked to this work

https://github.com/Dam4323/MalwareDetectionExperiment/blob/main/02_-_Hybrid_Detection_Model_for_Android_Malware.pdf

# Dataset Population

This dataset is composed by 1072 records (461 benigns and 611 malwares). Benign app are extracted from "ApkPure" web service (https://m.apkpure.com/fr/) and malwares from "VirusShare".

# Features metrics

You could find in this table the list of features include in this dataset.

|Feature|Type|Phase Extraction|
|---|---|---|
|Providers number| Extracted|Static|
|Extern attribute| Extracted|Dynamic|	
|Strings Global number	| Extracted| Static|
|Dex number| Extracted|Dynamic|	
|Intern attribute| Extracted|Dynamic|	
|Argument Type number| Extracted|Dynamic|	
|Balise number	| Extracted| Static|
|Call number| Extracted| Static|	
|Special strings number| Extracted| Static|	
|Custom Argument| Calculated| Static|	
|Affectation number| Calculated| Static|	
|Number of sginature permission| Extracted| Static|	
|Number of Dangerous permission| Extracted|	Static|
|Average size of class| Calculated| Dynamic|	
|Services number| Extracted|	Static|
|Android API| Extracted| Static|	
|Receivers Numbers| Extracted| Static|	
|Unicode number| Extracted|	Static|
|URL Number| Extracted| Static|
|Weighted Method per class| Calculated| Dynamic|	
|Reponse for class| Calculated|Dynamic|	
|Class number	| Extracted| Static|
|Permission number| Extracted| Static|	
|Other Permission number| Extracted|	Static|
|Number of child| Calculated|	Dynamic|
|Other Type String Number| Extracted| Static|	
|System Args| Calculated| Static|


# Availability
This dataset is under an open-source license, but the model's code is unavailable for privacy reasons. However, if you have any questions before using it, you can contact me by e-mail (damien.strullu@gmail.com) or Linkedin (https://www.linkedin.com/in/damienstrullu/). This dataset is not available for commercial purpose and makes no warranty for such use.

If you use this dataset, thanks to mention this in your work.

# Special Thanks

This dataset is obtained due to the participation of "VirusShare" (https://virusshare.com/) and "VirusTotal" (https://www.virustotal.com/) to perform some detection on the sample data provided.
