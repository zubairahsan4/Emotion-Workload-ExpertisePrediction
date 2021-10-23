# Emotion-Workload-ExpertisePrediction

This model was trained using the average valence*, the average arousal*, the average workload score (adapted NASA TLX without Physical Demand metric) for 16 questions that all participants attempted, and the overall expertise^ on all questions. The model is trained on Ensemble (Bagged Trees) classifier with an accuracy of 71.4%, with weighted precision of 72%, weighted recall of 71.5%, and weighted F-score 71.11%. On the testing set, the model predicted the expertise with an accruacy of 72.73%. 

*The average valence and average arousal were calculated for each participant on all the questions they attempted. The valence and arousal for each question were calculated by a follow-up SAM Test that was presented to the participants after each programming question. 

^Overall expertise was calculated by the percentage of the correct answers that the participants got. Two groups were formed; high performers and low performers.
