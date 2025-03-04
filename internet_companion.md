# My experience finding a good Internet Companion

If you’re like me and have started relying more on large language models (LLMs) rather than traditional search engines for your daily internet needs, you’ve probably noticed how much the landscape keeps changing. One day, **ChatGPT-4o** seems like the best option; the next, it’s **Gemini 2** or **Grok**, while **Claude** quietly remains a solid choice in the background. It feels like there’s always something new to try, and the competition between these models is pushing the boundaries of what they can do.

But I’ve realized that it’s not just about how powerful a model is. Sometimes, a slightly less advanced model can feel better to use if it’s part of a well-thought-out product. For example, for a long time, I preferred **Claude** over **ChatGPT**. Even though ChatGPT was technically more capable, Claude felt like it was designed with a better user experience in mind, and that made all the difference for me.

This shift in how I think about LLMs has been part of a larger journey—one where I’ve been experimenting with tools, setups, and workflows to find what works best for me. Along the way, I’ve learned a lot about how these models interact with search engines, how companies are integrating them into their ecosystems, and how to make them work together in a way that feels seamless. Let me share what I’ve discovered.
## The Role of Search in LLMs: Grounding for Better Results

One major shift I’ve noticed is how critical **grounding** has become for LLMs. Grounding refers to the practice of connecting an LLM to real-time (search) tools to provide up-to-date information and reduce hallucinations (when the model confidently generates incorrect or fabricated information). Almost every major provider now incorporates search as a tool for their models. Some let you control how search is used, while others handle it entirely in the background.

This integration of search has made assistants more dynamic, but it also introduces new challenges. For example, **Google’s Gemini** leverages its connection to Google’s vast ecosystem of services and search capabilities. **Grok**, on the other hand, pulls live information from trending discussions. **ChatGPT** has integrated Bing search and is even building its own search index.

While this sounds great in theory, it also brings up a fundamental issue: **garbage in, garbage out**. If the search engine feeding the LLM prioritizes low-quality or biased results, the model’s responses will reflect that. Different search engines have different priorities, SEO tactics can skew results, and each model processes search results in its own way. This variability can make the experience inconsistent and, at times, frustrating.

That’s why I’ve come to appreciate products like **Perplexity**, which focus on creating a seamless collaboration between search and LLMs. Perplexity doesn’t just bolt search onto an LLM—it’s designed to make the two work together coherently. However, even Perplexity relies on a limited set of models and search engines, which can feel restrictive.

## My Ideal Setup: Kagi + LLMs

After experimenting with various tools, I’ve landed on a setup that gives me the flexibility and control I’ve been looking for: **Kagi**. For those unfamiliar, Kagi is a paid search engine that builds its own search index, actively fighting against SEO manipulation and ad-driven prioritization. What really sets it apart is a feature called **Lenses**, which allows you to customize how the search engine behaves.

With Lenses, I can fine-tune my search experience in ways that demonstrate over and over how bad of a user experience search engines have become (despite better and better engines) . Here's how I fune-tune my search experience:

- I can **downvote certain types of results** to tweak future searches.
- I can create a Lens that includes only specific websites, like academic journals or coding resources, and use it when I need highly targeted results.
- I can exclude websites I find unhelpful (goodbye, Pinterest and low-quality SEO articles!) or reduce their priority.

Now, here’s where it gets even better: **Kagi Assistant**. This tool combines Kagi’s powerful search capabilities with a choice of nearly all the popular LLMs, including **Claude 3.7**, **ChatGPT-4.0**, **o3-mini**, **DeepSeek**, **Llama**, **Gemini**, **Mistral**, and more. For $25 a month, I get to choose which model I want to use, customize how it responds, and pair it with my tailored search setup or a specific Lens for grounding.

### How I Use Kagi Assistant

The flexibility of Kagi Assistant has completely transformed how I interact with LLMs. Here are a few examples of how I’ve set it up:

1. **Idea Sparring Assistant**  
    For brainstorming and exploring ideas, I created an assistant grounded in data from **Product Hunt**, **Crunchbase**, **GitHub**, and a few other curated websites. It ignores Reddit opinions (unless I specifically ask for them) and uses reasoning-focused models like **o3-mini** or **DeepSeek**. These models take a bit more time to respond but provide thoughtful, comprehensive insights.
    
2. **Coding Assistant**  
    My coding assistant is grounded in **GitHub**, **Stack Overflow**, and a few niche programming resources tailored to my needs. I’ve found **Claude 3.5** to be particularly strong for coding tasks, so that’s the model I use here. For more complicated generation, i switch to **Claude 3.7**
    
3. **General Use Assistant**  
    For everyday questions, I stick with my regular Kagi search as the grounding source and switch between models like **ChatGPT-4o** or **Claude 3.5** depending on the task. The ability to switch models mid-conversation is a game-changer.
    
4. **Quick Answers**  
    For simple, quick questions that don’t require up-to-date information, I use the blazing-fast **Mistral** model with search turned off. It’s perfect for those moments when speed matters more than depth. (like asking what is the capital of Madagascar, or who wrote book XYZ)
    

### Why Kagi Works for Me

Kagi’s team is constantly adding new models and even maintains its own leaderboard to evaluate them. This leaderboard feels more tailored to real-world use cases compared to the more gamed public leaderboards like LMSYS. While the web app isn’t as feature-rich as tools like Claude or ChatGPT (it doesn’t have artifacts or project management features), it does support file attachments and voice commands, which have been enough for my needs.

The combination of Kagi’s customizable search and the ability to choose and switch between LLMs makes it the most versatile and satisfying setup I’ve found. It’s not perfect, but it’s close enough to feel like the future of how I interact with the internet.

If you’re exploring ways to make LLMs work better for you, I highly recommend giving Kagi a try. It’s a reminder that sometimes, the best solutions aren’t about having the most powerful tools—they’re about having the right tools, working together in the right way.

P.S. Kagi is also using Crystal programming language to power lot of their work. So that is super cool as well :) 
