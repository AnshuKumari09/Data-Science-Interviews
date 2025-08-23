⚡ Problem

Maan lo tumhe ek dataset mila hai jisme:

Kuch missing values hain

Kuch categorical columns (jaise City = Delhi, Mumbai, Chennai) hain

Kuch numerical columns (jaise Age, Salary) hain

Aur last me tumhe ML model train karna hai.

Agar tum ye saare steps manually karoge, toh process kuch aisa hoga:

Missing values fill karna (imputation)

Categorical data ko encode karna (OneHot / Ordinal Encoding)

Numerical data ko scale karna (StandardScaler / MinMaxScaler)

Model ko fit karna

Har step ke baad tumhe alag-alag transformations apply karne padenge. Matlab code messy aur error-prone ho jayega.

💡 Yaha aati hai Pipeline

Pipeline ek tarah ka data processing + model training ka conveyor belt hai.
Tum ek baar sequence define kar do, fir data automatically step-by-step process hota hai.
✅ Fayde of Pipeline

Cleaner Code → Saare steps ek jagah likhe hote hain

Reproducibility → Har baar wahi sequence chalega, galti kam hogi

Cross Validation Easy → cross_val_score(pipeline, X, y) direct kaam karta hai

Avoid Data Leakage → Train-test split ke baad transformations sirf train pe learn hote hain, test pe directly apply hote hain (bahut important hai)
