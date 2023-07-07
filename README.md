# Psychedelic-Depression Nexus: Predictive Analysis of Patient Outcomes

Depression has been increasing even before COVID-19. As a tool to aid in treatment of this increase,psychedelics have seen a resurrence in recent years due to clinical trials and breakthrough studies. psychedelics have been used the "betterment of well people" , PTSD, etc.

## Question 

**Given patient features and psychedelic drug use, can we create a model to predict depression to enable clinical improvement?**

## Conclusion 

Overall the SVC model has the best performance on the recall(because we want to reduce false negatives) and use MCC score which is a more balanced metric for an unbalanced data.

Test recall: 0.771
MCC: 0.516
![SVC_confusion_matrix](https://user-images.githubusercontent.com/79125303/202750801-e3eb9a03-f02a-4190-9bb9-05f3e61c8f82.png)



