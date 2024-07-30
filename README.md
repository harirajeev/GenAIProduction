# GenAIProduction
Survey on GenAI Production best practices and everything around it

- [GenAI Production](https://github.com/harirajeev/GenAIProduction/blob/main/GenAIProduction.md)
- [GenAI Security](https://github.com/harirajeev/GenAIProduction/blob/main/GenAISecurity.md)

![image](https://github.com/user-attachments/assets/010d553d-c53d-42e0-bbc4-2e02373964fc)


LLMs can be categorised based on the number of parameters:
- 𝗦𝗺𝗮𝗹𝗹: ≤ 1 billion parameters
- 𝗠𝗲𝗱𝗶𝘂𝗺: 1 to 10 billion parameters
- 𝗟𝗮𝗿𝗴𝗲: 10 to 100 billion parameters
- 𝗩𝗲𝗿𝘆 𝗟𝗮𝗿𝗴𝗲: > 100 billion parameters

## Metrics:  
- Recall: the fraction of the nearest neighbors found by the algorithm.
- Query per second (QPS): the number of queries the algorithm can handle per second. This is crucial for high-traffic applications.
- Build time: the time required to build the index. This metric is important especially if you need to frequently update your index (e.g. because your data changes).
- Index size: the size of the index created by the algorithm, which is crucial for assessing its scalability and storage requirements.

System metrics tell you the state of your overall system. Common metrics are 
- throughput,
- memory usage,
- hardware utilization, and
- service availability/uptime.

Model metrics assess your model’s performance, such as accuracy, toxicity, and hallucination rate.

Common latency metrics include:
- Time to First Token (TTFT): The time it takes for the first token to be generated.
- Time Between Tokens (TBT): The interval between each token generation.
- Tokens Per Second (TPS): The rate at which tokens are generated.
- Time Per Output Token (TPOT): The time it takes to generate each output token.
- Total Latency: The total time required to complete a response.

GenAI adoption usecases:
- [Musings on Building a Generative AI Product (LinkedIn, 2024)](https://www.linkedin.com/blog/engineering/generative-ai/musings-on-building-a-generative-ai-product?_l=en_US)
- [How we built Text-to-SQL at Pinterest (Pinterest, 2024)](https://medium.com/pinterest-engineering/how-we-built-text-to-sql-at-pinterest-30bad30dabff)
- [From idea to reality: Elevating our customer support through generative AI (Vimeo, 2023)](https://medium.com/vimeo-engineering-blog/from-idea-to-reality-elevating-our-customer-support-through-generative-ai-101a2c5ea680)
- [A deep dive into the world’s smartest email AI (Shortwave, 2023)](https://www.shortwave.com/blog/deep-dive-into-worlds-smartest-email-ai/)
- [LLM-powered data classification for data entities at scale (Grab, 2023)](https://engineering.grab.com/llm-powered-data-classification)
- [From Predictive to Generative - How Michelangelo Accelerates Uber’s AI Journey (Uber, 2024)](https://www.uber.com/blog/from-predictive-to-generative-ai/)
