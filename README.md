# DSPy_data_generation
Data generation with Dspy by using context

## Introduction
In this experiment, DSPY was utilized to automatically generate question and answer (QA) pairs from a given context, with a focus on processing Lithuanian language queries. The goal of the experiment was to explore the efficiency and accuracy of the DSPY framework in generating relevant QA pairs based on the provided context, while also addressing the challenge of working with a less widely used language. Lithuanian is not a primary language in most training models, making it a less common target for AI models. The experiment used the Gemma 2 27B Q4 model and aimed to assess how sensitive the generation process is to the choice of model. Additionally, the model was run locally with Ollama, further increasing the complexity of the experiment due to the language's unique characteristics.

## Conclusion
The experiment demonstrated that DSPY, when paired with the Gemma 2 27B Q4 model, can effectively generate question and answer pairs from a given context. However, the results underscored that the information module's performance is highly sensitive to the specific model used. This indicates that model selection plays a crucial role in determining the quality and relevance of the generated QA pairs. 

The experiment also faced the challenge of processing Lithuanian, a language spoken by a small population and not widely supported in natural language processing tools. Despite these challenges, the model performed reasonably well in generating accurate QA pairs in Lithuanian. Further investigation into optimizing the choice of model and refining the information retrieval process can improve the overall performance of the system.

## Key Highlights
- **Model Used**: Gemma 2 27B Q4
- **Language**: Lithuanian (a smaller, less supported language)
- **Challenge**: Working with a language that is not widely used in AI training
- **Framework**: DSPY
- **Execution**: Model was run locally with Ollama

## Future Directions
- Further experimentation with different models to optimize QA pair generation.
- Refining the process of information retrieval, especially when handling less common languages like Lithuanian.

## Generated data
- Generated data can be found at: https://huggingface.co/datasets/ArturG9/Lithuanian_Context_QA
