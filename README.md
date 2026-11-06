# super-duper-palm-tree
a little rag project

# Context

***2026-11-05***

Hello! I was recently laid off from Netflix (about 3 weeks ago, on Oct 15, 2026) and I figured I'd spend the time working a few new ML projects for fun! In school, I had the opportunity to get a bit of exposure to machine learning and artificial intelligence (this was 2016-2018), and if I dig back far enough I did a really neat machine translation group project. 

However, as I entered the workforce, I found machine learning in practice to often live very far away from the day-to-day of business decisions. In that first job, I spent months on a clustering project that was put into production for reporting, but I was always confused about what impact it would actually have on the business - it didn't feel like I was using what I learned to do anything impactful.

So I left that first job and dove into Data Analyst, Data Scientist, and Analytics Engineer roles over the past 8 years, all of them in positions where I worked directly with product managers, designers, finance and strategy, and other decision-makers to provide visibility and insights that can shape the business decisions that were made day-to-day. It was really fulfilling! 

Now, almost 8 years later, though I understand the incredible value that production machine learning brings to areas like fraud detection, search, and personalization, I still think that while ML can do a lot of great things, it fundamentally cannot save a business that doesn't have a clear product strategy - to be fair, neither can data analytics, but I do think clear measurement and visibility into data is table-stakes in order to make informed business decisions.

I'm really thankful for the experience I've gained over the past 8 years in this area, and I definitely have much more to learn. However, especially over the past 4 years as I've matured in my ability to produce insights useful to the business, I've found that I now have an interest in building my understanding of how ML works in practice today, which I'm definitely lacking in.

So I've decided to use this time off to work on a few ML projects for fun - starting with this one!

I will be attempting to build a local RAG search tool / chatbot from scratch, to understand the principles of how it works. Also compared to 8 years ago LLMs should make this much easier, I hope. So here we go!

# Embedding Models
There are a variety of pre-trained machine learning models that can be downloaded and run locally on your machine. For this project, we'll use the industry-standard `sentence-transformers` library, which is made available by Hugging Face.

*Install the library*

```
pip install sentence-transformers
```

### More about sentence-transformers: a digression


### Other pre-trained embedding models: another digression


### Appendix: uv for project management
I'll be honest, I haven't coded for fun in a while.