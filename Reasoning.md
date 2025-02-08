DeepSeek
-  [The Illustrated DeepSeek-R1 - Jay Allamar](https://newsletter.languagemodels.co/p/the-illustrated-deepseek-r1)
-  ![image](https://github.com/user-attachments/assets/c6f363b1-79fe-436e-beec-e6d1ca9249e5)

-  There are three special things to highlight in the R1 creation process.
   - 1. Long chains of reasoning SFT Data
     This is a large number of long chain-of-thought reasoning examples (600,000 of them). These are very hard to come by and very expensive to label with humans at this scale. Which is why the process to create them is the second special thing to highlight
     ![image](https://github.com/user-attachments/assets/a542fe3e-e4a1-4b70-8448-b8dde9e97d23)

   - 2. An interim high-quality reasoning LLM (but worse at non-reasoning tasks).
        This data is created by a precursor to R1, an unnamed sibling which specializes in reasoning. This sibling is inspired by a third model called R1-Zero (that we’ll discuss shortly). It is significant not because it’s a great LLM to use, but because creating it required so little labeled data alongside large-scale reinforcement learning resulting in a model that excels at solving reasoning problems. 
The outputs of this unnamed specialist reasoning model can then be used to train a more general model that can also do other, non-reasoning tasks, to the level users expect from an LLM.
      ![image](https://github.com/user-attachments/assets/38d9d26e-f796-4425-a5fa-2a19b3383312)
   - 3- Creating reasoning models with large-scale reinforcement learning (RL)
      -   This happens in two steps:

![image](https://github.com/user-attachments/assets/eedccd65-581b-46b2-8ab7-51b7c24b463f)

      -   3.1 Large-Scale Reasoning-Oriented Reinforcement Learning (R1-Zero)
         -   Here, RL is used to create the interim reasoning model. The model is then used to generate the SFT reasoning examples. 
             But what makes creating this model possible is an earlier experiment creating an earlier model called DeepSeek-R1-Zero.
         -   R1-Zero is special because it is able to excel at reasoning tasks without having a labeled SFT training set. 
             Its training goes directly from a pre-trained base model through a RL training process (no SFT step). 
             It does this so well that it’s competitive with o1.

![image](https://github.com/user-attachments/assets/2dcc9e12-e039-45f5-845a-b9203f442717)




         
