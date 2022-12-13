# Reflux AI
Laryngopharyngeal/gastroesophageal reflux disease personalized machine learning solution.

## Background
"In 2019, there were 783.95 million cases of GERD globally. Between 1990 and 2019, the total number of prevalent cases, incident cases, and YLDs increased by 77.53%, 74.79%, and 77.19%, respectively" (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9122392/).  Laryngopharyngeal Reflux Disease (LPRD) is similar in nature to GERD; however, stomach acid doesn't just go up into the esophagus alone.  Rather, it travels up the esophagus and spills in to the throat or voice box (pharyn/larynx).  A common symptom of GERD is heartburn.  A common symptom of LPRD is difficulty breathing (often misdiagnosed initially as asthma due to similar lung symptoms such as wheezing).

People are often put on protein pump inhibitor medications such as Omeprazole to treat GERD/LPRD.  The side effects are well known and unwanted for long term use.  Diet and lifestyle changes are often wieldy as an alternative to medication, but difficult to plan out and manage effectively.

I personally have suffered from LPRD since 2019 (around the time COVID appeared), and have had multiple episodes that put me in the ER.  I went from being a gym nut to being someone who rarely can get through a workout without having difficulty breathing and feeling a globbus sensation in my throat.  I've been misdiagnosed as asthmatic and have been told all my symptoms stem from anxiety.  Inhalers rarely helped, I had my anxiety under control (albeit took a while because being short of breath for sometimes no reason is scary), and so much more.  One day I took tums for my stomach ache and I immediately was able to breath better.  I investigated this further.  Long story short, in late 2022 I saw my ENT doctor and was diagnosed as having LPRD.  Everything made sense from that day on.  I was put on medication for long-term use, but I was unhappy with this due to the potential side-effects.  I set out to change my diet/lifestyle.  I was fairly active to begin with, so that was easy.  My diet needed considerable work.  Disclaimer: I am not a medical doctor.  That said I do have significant experience with clinical/biomedical data and the power it provides. 

I came up the idea to track my food/drink intake, workout schedule, and how I felt on a day-to-day basis.  I am currently doing this now.  The end goal of this project is to train a machine learning model to tell me what food to eat next based on everything reported thus far at a given time.  I'd then create a system around this ML model to maybe text me when it thinks I'm going to get symptoms, so that I can eat or drink something before the symptoms come on.  This is definitely ambitious, but important to me, and after collecting data on me and getting a working prototype, I hope to expand this project to others with GERD/LPRD.  Let me break down my plan of attack.

## Phase 1
Collect data on me about food/drink intake, working out, and how I feel as well as when symptoms present themselves.  Not too sure what the most optimal data format is right now, so I am recording as much details as possible, and once I see some good features I will clean up the dataset.  This phase will take a while.  Even once done I'll keep recording data on myself.  Need a way to easily record data.

## Phase 2
Train a RNN-variant on the data, and evaluate.  Consider all ways to improve the model and ways to get better or more meaningful data.  This will take a while.

## Phase 3
Build a system around this model to further allow easy recording and alert messaging of somesort.  Not sure how long this will take.  Consider ways to better integrate this system into my daily life.  Maybe an app on my phone would be better.  This will be a lot more straightforward to do.

## Phase 4
Now that I have a working prototype for myself, consider how others may utilize this system.  The biggest challenge for a new user is getting a baseline of data as everyone is different and has a different diet/lifestyle/etc.  This is a very openended challenge.   

## Questions/Recommendations
If you have any questions/recommendations or would like to collaborate, email me at mjw467@drexel.edu
