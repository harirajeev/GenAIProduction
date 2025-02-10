DeepSeek
- [DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning - Paper](https://arxiv.org/abs/2501.12948)
-  [The Illustrated DeepSeek-R1 - Jay Allamar](https://newsletter.languagemodels.co/p/the-illustrated-deepseek-r1)

 ![image](https://github.com/user-attachments/assets/48fcb97a-e9d3-4def-bc58-737868c567b7)


- [Understanding Reasoning LLMs - Sebastian Raschka](https://www.linkedin.com/pulse/understanding-reasoning-llms-sebastian-raschka-phd-1tshc/?trackingId=IUjZ42GWSOmZmtdNX5lBRw%3D%3D)
         
  - DeepSeek did not release a single R1 reasoning model but instead introduced three distinct variants: DeepSeek-R1-Zero, DeepSeek-R1, and DeepSeek-R1-Distill.
   ![image](https://github.com/user-attachments/assets/3a917d7a-97ba-4951-be0e-b42b53ee29fe)
  - (1) DeepSeek-R1-Zero: This model is based on the 671B pre-trained DeepSeek-V3 base model released in December 2024. The research team trained it using reinforcement learning (RL) with two types of rewards. This approach is referred to as "cold start" training because it did not include a supervised fine-tuning (SFT) step, which is typically part of reinforcement learning with human feedback (RLHF).
  - (2) DeepSeek-R1: This is DeepSeek's flagship reasoning model, built upon DeepSeek-R1-Zero. The team further refined it with additional SFT stages and further RL training, improving upon the "cold-started" R1-Zero model.
  - (3) DeepSeek-R1-Distill*: Using the SFT data generated in the previous steps, the DeepSeek team fine-tuned Qwen and Llama models to enhance their reasoning abilities. While not distillation in the traditional sense, this process involved training smaller models (Llama 8B and 70B, and Qwen 1.5B–30B) on outputs from the larger DeepSeek-R1 671B model.
