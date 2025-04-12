# Understanding DeepSeek-R1_ Incentivizing Reasoning Capability in LLMs via  Reinforcement Learning 2501.12948v1

This link is to their github page: [DeepSeek](https://github.com/deepseek-ai/DeepSeek-Math)

DeepSeek-R1-Zero is a first generation reasoning model.
Its is trained via large-scale reinforcement learning (RL) without supervised fine-tuning (SFT) as a preliminary step.
It has reasoning capabilities but has limitations of poor readability and language mixing.

An improved version DeepSeek-R1 incorporates multi-stage training and cold-start data before RL. It's comparable to OpenAI-o1-1217 on reasoning tasks.
Released six models distilled from DeepSeek-R1 based on Qwen and Llama

Post-training requires less resources than pre-training.

Open AI o1 introduced **inference-time** scaling by increasing the length of **Chain-of-Thought** reasoning process.

However **test time scaling** remains a challenge. 

The paper focuses of Reinforcement Learning (RL).

Explore if LLM can develop reasoning capabilities without any supervised data just by RL.

Use DeepSeek-V3-Base and employ GRPO RL framework.




