# ChatGPT4-Adversarial-Turing-Test
A simple Turing-Test experiment demonstrating ChatGPT4's ability to learn from itself in an adversarial manner at inference time.

## Introduction
Inspired by [this paper](https://arxiv.org/abs/2309.04658#:~:text=Exploring%20Large%20Language%20Models%20for%20Communication%20Games%3A%20An%20Empirical%20Study%20on%20Werewolf,-Yuzhuang%20Xu%2C%20Shuo&text=Communication%20games%2C%20which%20we%20refer,social%20science%2C%20and%20artificial%20intelligence.) that lets 7 `gpt-3.5-turbo-0301` models play **Werewolf**, I wonder whether a ChatGPT model can learn from the judgement and analysis given by another instance of it in an adversarial manner. So I set up this **simplified Turing Test** to let one **ChatGPT4** chat thread answer a given question and another ChatGPT4 chat thread to judge, and guide them to learn from the other's reasoning if one makes a mistake. This experiment demonstrate to some extent ChatGPT4's adversarial self-learning ability. It also shows the power of prompt engineering for LLMs and a potential engineer pipeline to self-improve answers in some situations.

## Set-up

## Summary of result

## Conclusion

## Appendix: Complete Chat history
Here are the raw chat history using OpenAI sharing feature
1. [Chat history with the ChatGPT4 judge](https://chat.openai.com/share/be347d5f-fa7a-4667-aa88-fb3717022934)
2. [Chat history with the ChatGPT4 participant](https://chat.openai.com/share/30c27f72-0d23-4b65-97fe-57d3c30fd27d)

Here are the chat organized by time. <br><br> 

| Time Step (odd steps are my prompts) | ChatGPT4 Participant   | ChatGPT4 Judge |
| ------------------------------------ | --------------------------- | --------------------------- |
|     1     | Do you know Turing test?      | Do you know Turing test?       |
|     2     | Yes, I'm familiar with the Turing Test. It's a measure of a machine's ability to exhibit intelligent behavior indistinguishable from that of a human. Proposed by the British mathematician and computer scientist Alan Turing in 1950, the test involves a human evaluator who engages in natural language conversations with both a human and a machine designed to generate human-like responses. If the evaluator cannot reliably distinguish between the machine and the human based on their responses, the machine is said to have passed the test. <br><br> The Turing Test has been a foundational concept in the philosophy of artificial intelligence and has spurred numerous debates about the nature of intelligence, consciousness, and the potential of machines to emulate human thought processes. However, it's worth noting that passing the Turing Test does not necessarily mean a machine possesses consciousness or true understanding; it simply means the machine can mimic human-like conversational behavior convincingly.   | Yes, I'm familiar with the Turing Test. The Turing Test is a measure of a machine's ability to exhibit intelligent behavior indistinguishable from that of a human. It was proposed by the British mathematician and computer scientist Alan Turing in 1950 in his paper "Computing Machinery and Intelligence." <br><br> In the Turing Test, a human evaluator interacts with an unseen interlocutor, which can be either a human or a machine. The evaluator's task is to determine which one they are conversing with based on the conversation. If the evaluator cannot reliably distinguish the machine from the human, the machine is said to have passed the test.  <br><br>  It's worth noting that the Turing Test is not a definitive measure of all aspects of human intelligence or consciousness. Instead, it's a test of a machine's ability to mimic human-like conversational behavior. Over the years, there have been criticisms and variations of the test, but it remains a foundational concept in the philosophy of artificial intelligence.        |
|     3     | Do you know Turing test?      | Do you know Turing test?       |