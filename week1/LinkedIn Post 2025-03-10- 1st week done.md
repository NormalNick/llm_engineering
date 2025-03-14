:celebrate: I completed week 1 of @Ed Donner's LLM Engineering course on @Udemy? https://www.udemy.com/course/llm-engineering-master-ai-and-large-language-models

This learning seems simple, but I feel like I'm starting to unlock new methods and tools to solve a wider range of problems!

What did I learn?

- **How to setup Jupyter Lab** on my laptop - I used python venv because I'm comfortable with it
- **How to call OpenAI APIs**, and how system prompts are different than user prompts.
- **How to call local LLMs** on my laptop with the power of Ollama http://ollama.com/ - I even used DeepSeek locally!
- LLMs will produce different outputs with the same question. What I think is referred to as "non-deterministic".
- **How to 'program' with LLMs instead of code** to return json
- **LLMs terms & history**: a bit about how LLMs count tokens - check out OpenAI's tokenizer https://platform.openai.com/tokenizer
- **LLM pricing**: tokens are the primary measure, rates differ at input vs output time - check out Vellum's LLM leaderboard https://platform.openai.com/tokenizer
- **How little LLMs cost** to run for small tasks. I used only $0.02 of OpenAI's API's this past week. I suspect this becomes a concern at scale; I can track my costs on https://platform.openai.com/settings/organization/usage

Week 1 projects

- Created a Technical Q&A assistant that can answer technical questions.
- Leveraged both OpenAI's GTP-4omini and Local LLMs llama and deepseek.
- Changed the system_prompt to change the tone & personality of the answers. (I used ChatGPT to create this prompt)
- I went the extra step and used ipywidgets to create a simple User Interface in Jupyter Lab. 
