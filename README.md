# GenAIProduction
Survey on GenAI Production best practices and everything around it

- [GenAI Production](https://github.com/harirajeev/GenAIProduction/blob/main/GenAIProduction.md)

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
