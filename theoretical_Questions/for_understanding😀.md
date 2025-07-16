 Kahani 1: Supervised Learning
Example: Teacher aur Bacche wali kahani
Ek teacher hai jo students ko apple aur orange pehchanna sikhati hai. Teacher unko pehle se labelled examples dikhati hai:
Ye photo apple hai.
Ye photo orange hai.
Bacche bahut saare labelled images dekhte hain. Jab naye fruit ki photo dikhti hai, baccha dekh ke pehchan leta hai: “Ye to apple hai!”
👉 Yahi hai Supervised Learning — labelled data se seekhna.

Technical Example: Spam Email Detection
Hamare paas labelled emails hain: kuch spam, kuch not spam.
Model inko dekhkar seekhta hai aur naye email pe predict karta hai — spam ya nahi.

🎓 💡 Kahani 2: Unsupervised Learning
Example: Party mein Unknown Groups wali kahani
Tum ek badi party mein gayi ho. Tum kisi ko nahi jaanti. Tumne kisi se nahi pucha ki kaun kaun dost hai. Tum bas logon ka behaviour observe karti ho — kaun kis se baat kar raha hai, kaun kaun ek dusre ke paas khada hai.
Dheere dheere tum samajh jaati ho ki:
Ye log ek group hai.
Wo log doosra group hai.
Tumne bina kisi label ke hidden groups dhund liye.
👉 Yahi hai Unsupervised Learning — unlabelled data mein se pattern dhoondna.

Technical Example: Customer Segmentation
Ek shopping site mein logon ke shopping pattern se clusters banana — premium buyers, budget buyers, discount hunters — bina label ke.

🎓 💡 Kahani 3: Semi-Supervised Learning
Example: Class mein Homework wali kahani
Teacher ne tumhe 100 pages ka homework diya hai. Sirf pehle 10 pages ka solution diya hai. Baaki 90 pages tumhe khud karne hain — par tum pehle 10 pages ko dekh ke samajh jaati ho ki kis pattern mein question solve karna hai.
Tum labelled + unlabelled data mix karke kaam karti ho.
👉 Yahi hai Semi-Supervised Learning.

Technical Example: Few labelled images, baaki auto-label
Bahut badi image dataset mein sirf kuch images labelled hain — baaki ko model unlabelled images se bhi pattern seekh ke handle karta hai.

🎓 💡 Kahani 4: Reinforcement Learning
Example: Bachche ka Cycle Seekhna
Ek chhota bachcha cycle chalana seekhta hai. Uske paas koi teacher nahi — bus try karta hai. Jab gira — negative reward mila (chot lagi). Jab seedha chala — positive reward mila (maza aaya!).
Dheere dheere bachcha samajh jaata hai ki kese balance banana hai — trial & error se seekh ke best decision lena.
👉 Yahi hai Reinforcement Learning — reward-mila toh kaam karo, punishment mila toh sudhar lo.

Technical Example: Self Driving Car, AlphaGo, Chess AI
Ek agent environment se interact karta hai — reward/punishment ke basis pe seekhta hai.

2 . Linear Regression ek statistical method hai jo 2 variables ke beech relation nikalta hai, assume karta hai ki woh linear hai (seedha line).

Ek hi variable ho toh Simple Linear Regression
Multiple variables ho toh Multiple Linear Regression.

3. Gradient Descent hai — ek optimization algorithm jo Cost Function ko minimize karta hai.
