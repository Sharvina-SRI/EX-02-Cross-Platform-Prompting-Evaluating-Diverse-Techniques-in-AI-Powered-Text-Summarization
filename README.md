# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

### 1. Zero-shot Prompt

#### Prompt:
```
"Summarize the following article on 'The Basics of Blockchain Technology' in 4–5 sentences for undergraduate students."
``` 
#### ChatGPT:
Accuracy: Covers most key points; minor technical simplifications.

Coherence: Logical and readable.

Simplicity: Easy to understand.

Speed: Very fast.

User Experience: Smooth, direct, minimal editing required.

#### Gemini:
Accuracy: Misses some technical details.

Coherence: Adequate but slightly disjointed.

Simplicity: Clear but may oversimplify.

Speed: Fast.

User Experience: Easy to use, but may need manual edits.

### 2. Few-shot Prompt

#### Prompt:
```
"Here are two examples of summaries for technical articles:
Example 1:
‘Quantum computing uses principles of quantum mechanics to perform calculations faster than classical computers. It is still experimental but promises breakthroughs in cryptography and complex problem-solving.’

Example 2:
‘Artificial Intelligence involves creating machines that can learn and make decisions. It is widely used in industries such as healthcare, finance, and transportation to automate tasks and improve efficiency.’
Now summarize the following blockchain article for undergraduate students."
```
#### ChatGPT:
Accuracy: High; captures key concepts well.

Coherence: Excellent logical flow.

Simplicity: Very beginner-friendly.

Speed: Slightly slower than zero-shot but acceptable.

User Experience: Very good; output aligns with examples.

#### Gemini:
Accuracy: Improved compared to zero-shot but slightly less detailed.

Coherence: Better flow than zero-shot.

Simplicity: Understandable.

Speed: Fast.

User Experience: Good; may require minor edits.

### 3. Chain-of-Thought Prompt

#### Prompt:
```
"Explain the key points of this blockchain article step by step, then provide a simple 4-sentence summary for undergraduate students."
```
#### ChatGPT:
Accuracy: Very high; detailed reasoning ensures correctness.

Coherence: Excellent stepwise explanation leading to summary.

Simplicity: Summary is understandable but slightly condensed from reasoning.

Speed: Slower due to stepwise reasoning.

User Experience: Good; clear insight into the reasoning process.

#### Gemini:
Accuracy: Reasoning included but less thorough.

Coherence: Adequate but summary may feel abrupt.

Simplicity: Summary simple but may omit nuances.

Speed: Faster than ChatGPT for reasoning, less detailed.

User Experience: Decent; less intuitive than ChatGPT.

### 4. Role-based Prompt

#### Prompt:
```
"Act as an expert educator and summarize this blockchain article for undergraduate students, highlighting key concepts in a clear and simple way."
```

#### ChatGPT:
Accuracy: Excellent; all main points captured.

Coherence: Very logical and smooth.

Simplicity: Beginner-friendly and engaging.

Speed: Slightly slower than zero-shot but well worth it.

User Experience: Outstanding; feels tailored and professional.

#### Gemini:
Accuracy: Good but slightly less detailed.

Coherence: Reasonable; formal tone may feel less engaging.

Simplicity: Simple but not as approachable.

Speed: Fast.

User Experience: Good but not as polished as ChatGPT.

## Algorithm (Methodology)

Prepare the 500-word article on blockchain.

Select platforms: ChatGPT, Gemini.

Define prompting techniques: Zero-shot, Few-shot, Chain-of-Thought, Role-based.

Design custom prompts for each technique (as above).

Input article + prompt into the AI platform.

Record outputs and evaluate: Accuracy, Coherence, Simplicity, Speed, User Experience.

Compare results to determine best combination.

## Result

Best Overall: ChatGPT with Role-based or Few-shot prompting - Accurate, coherent, simple, and engaging.

Secondary Option: Gemini with Few-shot prompting - Fast and simple but less detailed.

Chain-of-Thought: Useful for deeper understanding, slower but more thorough in ChatGPT.

Zero-shot: Fast but less accurate and detailed on both platforms.

