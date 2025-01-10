# Empower Your Everyday: Unlocking the Potential of AI with Fabric

## What is Fabric

[Fabric](https://github.com/danielmiessler/fabric/) is an open-source framework for augmenting humans using AI.

AI is powerful, but it's not easy to integrate this functionality into our lives. In other words, AI doesn't have a capabilities problem—it has an integration problem.
Fabric was created to address this by enabling everyone to granularly apply AI to everyday challenges.

Fabric's philosophy is that `AI isn't a thing; it's a magnifier of a thing. And that thing is human creativity`. Fabric's approach is to break problems into individual pieces and apply AI to them one at a time.

## Why Fabric

Fabric streamlines the process of incorporating AI into life and work. It does this using *Patterns*, which are AI prompt templates formatted in Markdown for maximum readability and editability. This format ensures that both users and AI can easily understand and execute the instructions.

Fabric comes with a large number of Patterns out of the box, but users can create and host their own custom Patterns.

Fabric is available via CLI or a node interface. It works with a variety of models and can create AI-agents.

## Using Fabric

Input can be piped into Fabric:

`echo "Give me a list of ice cream flavors" | fabric -s -p ai`

and Fabric commands can be chained:

`echo "Give me a list of ice cream flavors" | fabric -s -p ai | fabric -p summarize | fabric -s -p write_essay`

## Custom Patterns

Custom patterns can be created. They can also be improved using Fabric's `improve_prompt` Pattern:

`echo "You are an expert in understanding and digesting TED talks, identifying key points mentioned, funny stories, key quotes. You will identify themes, create discussion questions and identify stories." | fabric -sp improve_prompt`

This would result in this output:

```md
**You are an expert in analyzing TED talks. Your task is to:**
1. **Identify Key Points:** Extract and list the main ideas or arguments presented in the TED talk.
2. **Highlight Funny Stories:** Note any humorous anecdotes or stories shared during the talk.
3. **Capture Key Quotes:** Provide direct quotes that encapsulate significant insights or moments from the talk.
4. **Determine Themes:** Analyze and state the overarching themes of the talk.
5. **Create Discussion Questions:** Formulate thought-provoking questions based on the content of the talk that could be used to spark further discussion.
6. **Summarize Stories:** Briefly summarize any stories told during the talk, explaining their relevance to the main message.
**Please present your analysis in a structured format, using bullet points for each section.**
```

## Context

Context refers to additional, pre-created information that can be applied to Patterns to add more context to a given task.

## Agents

Agents aredesigned to execute specific tasks or interact with data. They handle tasks like text summarisation, API integrations, and data processing. Agents use PraisonAI and work with OpenAI and Ollama models. They enhance Fabric's capabilities by enabling focused functionalities without altering its core framework extensively.

## Mills

Mills host and manage Patterns.

## Looms

Looms interact with Mills. They send user input to the mills and retrieve processed output. Looms may be CLI, web interfaces, or other apps interacting with the mill.

## Use Case for Mills and Looms

A company processing large volumes of customer feedback can use a Mill to host Patterns for sentiment analysis and summarization. Employees access these tools using Looms and send data to the Mill for rapid analysis.

## Resources

[Empower Your Everyday: Unlocking the Potential of AI with Fabric](https://www.infralovers.com/blog/2024-06-25-fabric-overview/)
[Fabric](https://github.com/danielmiessler/fabric/)

### Intro videos

While not mentioned in this article, below are some videos which provide an introduction to Fabric. Keep in mind that many of these were recorded when Fabric was Python-based, so some of the instructions may be out-of-date.

[Network Chuck](https://www.youtube.com/watch?v=UbDyjIIGaxQ)
[David Bombal](https://www.youtube.com/watch?v=vF-MQmVxnCs)
[My Own Intro to the Tool](https://www.youtube.com/watch?v=wPEyyigh10g)
[More Fabric YouTube Videos](https://www.youtube.com/results?search_query=fabric+ai)
