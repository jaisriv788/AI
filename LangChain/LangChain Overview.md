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

### Types Of Memory
1. **Conversation Buffer Memory** - It stores a transcript of recent messages. Great for short chats but can grow large quickly.
2. **Conversation Buffer Window Memory** - This only keeps the last **N** interactions to avoid excessive token usage.
3. **Summarize Based Memory** - It periodically summarizes older chat segments to keep a condensed memory fragment that can be used as the state for the next prompt.
4. **Custom Memory** - For advance usage, user can store specialized state in a custom memory. For e.g. the user preference or key facts about them. 

## Agents
- Agents are more than model or anything they not only behave as chatbots but they can also perform predefined task for which they have been created.
- Agents also called as AI Agents have the capability of NLU(Natural Language Understanding) capabilities and according to it they can also generate the response.
- They also have the reasoning capabilities so that they can perform some tasks so that they should not behave as chatbots.
- They also have the accessibility to the tools that the agent require so to perform the operation.
- e.g. Their is an agent who has the access to the weather API and the ticket booking platform API or something then he can perform action on the weather API and also book the tickets for the user also.

> This was the overview as we will have a detailed section for each of components separately with individual section for them.