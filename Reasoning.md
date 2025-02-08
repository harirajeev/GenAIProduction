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

