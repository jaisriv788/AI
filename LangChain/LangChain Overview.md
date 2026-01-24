## About
- LangChain is a open-source framework for developing application powered by LLMs.
- LangChain components -
  1. Models
  2. Prompts
  3. Chains
  4. Memory
  5. Indexes
  6. Agents

## Models
- In LangChain, models are the core interface through which user interacts with AI models.

![[ModelsExample.excalidraw|600]]

- The problems mentioned in the figure above was solved by LLMs.
- As LLMs were trained on the whole internet data with billions of parameters so new problem emerged and that was their size and cost to host them as a single LLM can be of size greater than 100GB.
- Now this problem of size and cost were resolved by the LLM APIs.

### Types Of Models
1. Language Model
2. Embedding Model

![[ModelsFLow.excalidraw|700]]

## Prompts
- These are the input to LLMs for which LLM generates result and small amount of change in prompt can lead to a totally different result.

## Chains
- With the help of chains we can build the pipelines.
- Chains prove us the power of making a models output as the next models input also.

## Indexes
- It connects your application to external knowledge. Such as PDF, Website or database.
- Indexes have majorly four components - 
  1. Document Loader.
  2. Text Splitter.
  3. Vector Storage.
  4. Retrievers.

## Memory
- LLM API calls are stateless that means that it does not have any reference to the last chat, message or the answer it has provided for that particular prompt. So the requirement of the memory came into picture. 