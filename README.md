# LearnLangChain
A repo about some of the fundamental in LangChain framework

## Chains

### LLM Chain
- most basic type of chains
- 
### Sequential Chain
- Single input and single ouput, multiple input and multiple output
- combine multiple LLM chains
- very userful when try to put together output from different inputs
### Router Chain
- more complicated task
- determine which chain to use and directs to it
- flexible to user different destination prompts

## Vector storage

### LLM's on Documents
- LLM can only inspect a few thousand words at a time
- Embeddings, semantic vector
- Word vector can be saved to vector db
- stuff (most commonly used, simple), map_reduce, refine, map_rerank

## Evaluation
Datatypes we can use to do the evaluation
- QAGenerateChain to automatically create q and a

## Agent
- tools like "llm-mat", "wikipedia", define your own tools
- CHAT_ZERO_SHOT_REACT_DESCRIPTION
- it would be straightforward to use high-level APIs to implement Agent
- lower level APIs can grant more controls over the generation of response



