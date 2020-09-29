The data represents Android apps that are
labeled as benign or malicious. The goal is to build models that can identify
malicious apps (or malware), so that they can be prevented from entering the
market. Two sets of apps are provided. These datasets are csv
files(AndroidAppsTrain.csv and AndroidAppsTest.csv). Each app
in the train and test files is represented using 471 binary (0/1) features, which
denote the presence/absence of various permissions, intent actions, discriminative APIs,
obfuscation signatures, and native code signatures. For simplicity
sake, we assume that the names of the features are f0, f2, · · · , f470. The
last column of an instance/app (f471) corresponds to the class label y, which
takes values 0 (benign) or 1 (malware).
