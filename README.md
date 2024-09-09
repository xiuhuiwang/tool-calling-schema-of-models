# tool-calling-schema-of-models
A collection of tool calling request and response schema of the main models for comparison.

# Tool Calling Doc Link

[Claude](https://docs.anthropic.com/en/docs/build-with-claude/tool-use#tool-use-examples)

[Google Gemini](https://ai.google.dev/gemini-api/docs/function-calling)
- [Accepted schema of Gemini](https://ai.google.dev/api/caching#schema)
- Mote that even the Gemini replies with a functionCall field, the finishReason is still "STOP", that means we cannot tell if we have reached final answer by the finishReason. [Gemini finishReasoon List](https://ai.google.dev/api/generate-content#finishreason)

[OpenAI](https://platform.openai.com/docs/api-reference/chat) - Click the "Function" tag on the right

[Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/function-calling) - looks the same with OpenAI

[Amazon Bedrock Converse API](https://docs.aws.amazon.com/bedrock/latest/userguide/tool-use-inference-call.html)