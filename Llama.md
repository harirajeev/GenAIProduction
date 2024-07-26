- LLaMA 3
   - Llama System Safety:
   - Models & Inference Guardrails: Llama-Guard-3 8B (multilingual text in)
   - Prompt Guard (direct and indirect prompt injection filtering)
   - Cybersecurity: CyberSec Eval 3, a new benchmark for assessing LLM security risks, introducing tests for prompt injection and code interpreter abuse, revealing unresolved conditioning    issues, proposing the False Refusal Rate (FRR) to measure safety-utility tradeoffs, and providing open-source code for further evaluations.
   - 𝗧𝗵𝗲 𝟴𝗕 𝗮𝗻𝗱 𝟳𝟬𝗕 𝗺𝗼𝗱𝗲𝗹𝘀 𝗮𝗿𝗲 𝗲𝘅𝘁𝗲𝗻𝗱𝗲𝗱 𝘁𝗼 𝟭𝟮𝟴𝗸 𝘁𝗼𝗸𝗲𝗻𝘀 𝗰𝗼𝗻𝘁𝗲𝘅𝘁 𝗹𝗲𝗻𝗴𝘁𝗵.
   - 𝗟𝗹𝗮𝗺𝗮-𝟯.𝟭-𝟰𝟬𝟱𝗕 on par or above GPT-4o on many benchmarks.
   - 𝗔 𝗻𝗲𝘄 𝟰𝟬𝟱𝗕, 𝗽𝗼𝘀𝘀𝗶𝗯𝗹𝘆 𝘁𝗵𝗲 𝘀𝘁𝗿𝗼𝗻𝗴𝗲𝘀𝘁 𝗟𝗟𝗠 𝗲𝘃𝗲𝗿, with 128k context length, 88.6% on MMLU, a crazy 96.8% on GSM8K.
   - You still need 8xH100 to run it with full context length
   - Pretrained on 15T tokens, a more diverse training dataset than Llama-3 to reinforce multilinguality: English, German, French, Italian, Portuguese, Hindi, Spanish, and Thai.
   - License: same as Llama-3, and on top of that it allows using the output data from Llama-3.1 for training other models (distillation)
   -   
 
-   <b>Umar Jamil</b>
   -   [Coding LLaMA 2 from scratch in PyTorch - KV Cache, Grouped Query Attention, Rotary PE, RMSNorm](https://www.youtube.com/watch?v=oM4VmoabDAI)
   -   [GitHub](https://github.com/hkproj/pytorch-llama)
   -   [Pdf](https://github.com/hkproj/pytorch-llama/blob/main/Slides.pdf)
    
-   <b>cameronr wolfe</b>
   -   [LLaMA-2 from the Ground Up](https://cameronrwolfe.substack.com/p/llama-2-from-the-ground-up)
   -   [practical-prompt-engineering-part](https://cameronrwolfe.substack.com/p/practical-prompt-engineering-part)
    
