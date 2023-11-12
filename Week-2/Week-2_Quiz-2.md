**1. True or False.** Because of the knowledge cut-off, an LLM cannot answer questions about today's news. But with RAG to supply it articles from the news, it would be able to.
- [x] True
- [ ] False

**2.** You want to build an application to answer questions based on information found in your emails. Which of the following is the most appropriate technique?
- [ ] Fine-tuning an LLM on your emails, whereby we take a pre-trained LLM and further train it on your emails.
- [x] RAG, where the LLM is provided additional context based on retrieving emails relevant to your question.
- [ ] Prompting (without RAG), where we iteratively refine the prompt until the LLM gets the answers right.
- [ ] Pretraining an LLM on your emails.

**3.** What does the idea of using an LLM as a reasoning engine refer to?
- [x] This refers to the idea of using an LLM not as a source of information, but to process information (wherein we provide it the context it needs, through techniques like RAG).
- [ ] The idea of using an LLM to play games (like chess) that require complex reasoning, but having its output moves in the game.
- [ ] Reasoning engine is another term for RAG.
- [ ] This refers to pretraining an LLM on a lot of text so that it acquires general reasoning capabilities.

**4. True or False.** By making trusted sources of information available to an LLM via RAG, we can reduce the risk of hallucination.
- [x] True, because RAG allows the LLM to reason through accurate information retrieved from a trusted source to arrive at the correct answer.
- [ ] False, because the LLM has learned from a lot of text from the internet (perhaps>100 billion words) to hallucinate, so adding one more short piece of text to the prompt as in RAG won't make any meaningful difference.
- [ ] True, because the LLM is now restricted to outputting paragraphs of text exactly as written in the provided document, which we trust.
- [ ] False, because giving the LLM more information only confuses the LLM more and causes it to be more likely to hallucinate.

**5.** An ecommerce company is building a software application to route emails to the right department (Apparel, Electronics, Home Appliances, etc.) It wants to do so with a small, 1 billion parameter model, and needs high accuracy. Which of these is an appropriate technique?
- [ ] Pretrain a 1 billion parameter model on around 1,000 examples of emails and the appropriate department.
- [ ] Pretrain a 1 billion parameter model on around 1 billion examples of emails and the appropriate department.
- [ ] Fine-tune a 1 billion parameter model on around 1 billion examples of emails and the appropriate department.
- [x] Fine-tune a 1 billion parameter model on around 1,000 examples of emails and the appropriate department.
