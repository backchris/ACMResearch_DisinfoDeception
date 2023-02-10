# ACMResearch_DisinfoDeception
Leading 4 undergraduates through a semester-long ML research project on security applications of scaled disinformation distribution on Twitter

Project plan can also be found here:
https://docs.google.com/document/d/1PrVKPqJqnmbhMPXLQA3_EGEC46qQAEQWb3ejo9TvvRo/edit#heading=h.2bgw0c9hhw0q

## Disinfo_Deception
Using Adversarial Attacks to Deceive Political Disinformation Models on Twitter

Spring 2023 ACM research project developed by Christopher Back

## Description

You will attempt to fool machine learning models trained to detect political disinformation on Twitter using adversarial learning. An adversarial attack feeds a model seemingly normal input data (adversarial examples) which is actually designed to deceive the model into outputting an intended mistake. This project aims to identify if political actors can bypass detection systems using adversarial learning to spread misinformation to fool public understanding of social media.

1. You will first design and program a NLP (natural language processing) imitation model using supervised transfer learning to replicate a disinformation detection model that would be found on a platform such as Twitter. This model will be trained using a public Kaggle dataset, and will be used as the victim model. 
2. You will then program an adversarial attack model which will be used to generate adversarial examples using the same Kaggle dataset the victim model was trained on.
3. Then, you will test these adversarial examples and see if it successfully fools the victim detection model. 
4. Afterwards, you will curate your own, separate labeled dataset by scraping real-world Twitter posts. You will feed this dataset into your attack model to generate adversarial examples from a dataset different from the one the victim model was trained on. Then, test the attack to compare its performance in deceiving the victim model with the previous set of attacks.
5. Lastly, prepare a poster presentation with the results to display at the ACM research symposium.
