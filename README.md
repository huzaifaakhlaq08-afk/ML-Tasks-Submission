# ML Project Tasks

## Task 1: Term Deposit Prediction
* Goal: Model banaya jo yeh check karega ke customer bank mein term deposit kholega ya nahi.
* Method: Data par Categorical Encoding lagayi aur Logistic Regression ke sath Random Forest model ko train kiya.
* Result: Random Forest ka result behtareen aaya jiska AUC score 0.94 raha. Duration aur economic factors prediction ke liye sab se important nikle.

## Task 2: Customer Segmentation
* Goal: Mall customers ka data use karke unke income aur spending habits ke mutabik group banana.
* Method: Pehle features ko standard scale kiya, phir K-Means Clustering lagayi aur visualization ke liye PCA use kiya.
* Result: Customers ke 5 alag-alag clusters (groups) successfully banaye jinse unka spending behavior saaf pata chalta hai.

## Task 4: Loan Default Risk Optimization
* Goal: Bank ke nuksaan (financial loss) ko kam se kam karne ke liye decision threshold ko set karna.
* Method: Random Forest model ki probabilities par ek custom business cost apply ki (False Negative cost = $500, False Positive cost = $100).
* Result: Cost minimization curve plot kiya aur woh exact optimal point dhoond nikala jahan bank ka risk sab se kam ho jata hai.
