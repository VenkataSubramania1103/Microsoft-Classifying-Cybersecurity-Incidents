Microsoft : Classifying Cybersecurity Incidents with Machine Learning

Enhancing the efficiency of Security Operation Centers (SOCs) by developing a machine learning model that can accurately predict the triage grade of cybersecurity incidents.
Objective is to create a classification model that categorizes incidents as true positive (TP), benign positive (BP), or false positive (FP) based on historical evidence and customer responses

Libraries Used are:
  Numpy, Pandas, Sci-kit learn, Seaborn, Matplotlib, xgboost

Important Features are ['OrgId', 'IncidentId', 'AlertId', 'AlertTitle', 'Day', 'Time', 'Category', 'Hour', 'EntityType', 'IpAddress', 'City', 'Url', 'EvidenceRole', 'ApplicationId', 'Year']

Models used:
  DecisionTreeClassifier, RandomForestClassifier, XGBoostClassifier

Metrics achieved:
Accuracy = 0.925541
Precision = 0.926537
F1 Score = 0.925614
Recall = 0.925682
