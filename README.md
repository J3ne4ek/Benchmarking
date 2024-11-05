### Questions:

**Competitive landscape**

1. What advantages do JetBrains products have over free alternatives like VS Code?
   [link with possible answer](https://www.reddit.com/r/Python/comments/10jkbcc/what_are_the_benefits_of_pycharm_over_vs_code/?rdt=32912)
2. How do code completion tools impact developer productivity and the competitive landscape?
   [link with possible answer](https://github.blog/news-insights/research/survey-reveals-ais-impact-on-the-developer-experience/)
   

**Competitive pricing**

1. What discounts or promotions does JetBrains provide for students and educators? [sourse](https://www.jetbrains.com/lp/leaflets-gdc/students/)

**Trend analysis**

1. Which programming languages are currently trending in the software development market? [source](https://www.tiobe.com/tiobe-index/)
2. How has the rise of cloud-based development environments affected JetBrains' offerings?

### LLMs for evaluation:

1. ChatGPT, gpt-3.5 (https://chatgpt.com/)
2. Mistral Large2  ([https://chat.mistral.ai](https://chat.mistral.ai/))
3. Gemini 1.5 flash (https://gemini.google.com/app)
4. DeepSeek ([https://chat.deepseek.com](https://chat.deepseek.com/))
5.  YandexGPT 4 Pro RC (https://ya.ru/ai/gpt-4)

### Evaluation criteria:

Truthfulness:

    0 — At least one primary claim is inaccurate, unsupported, or can be disputed by reputable web evidence.
    
    1 — Primary claims are accurate, but at least one secondary claim is inaccurate, unsupported, or can be disputed by reputable web evidence.
    
    2 — All claims are accurate and can be verified by reputable web evidence.

Content Relevance

    0 — Response contains a significant amount of unnecessary content that is repetitive, unhelpful, or irrelevant. 
    
    1 — Response is generally relevant to the prompt but contains a small portion of unnecessary content that is repetitive, unhelpful, or irrelevant
    
    2 — Response contains only necessary content. Every sentence is clearly helpful  and not repetitive.


Content Completeness

    0 — The response gives enough information with sufficient detail to completely addresses the prompt.

    1 — There is some relevant information that is missing the response, reducing its helpfulness or 
    
    2 — Too much content is missing to fulfill the user’s request in a meaningful way. 


### Evaluation

#### ChatGPT

| Question | Truthfulness | Content Relevance | Content Completeness |
|----------|--------------|-------------------|----------------------|
| Q1       | 2            | 2                 | 2                    |
| Q2       | 2            | 2                 | 2                    |
| Q3       | 2            | 2                 | 2                    |
| Q4       | 1            | 2                 | 2                    |
| Q5       | 2            | 1                 | 2                    |
| Overall  | 1.8          | 1.8               | 2                    |

**Strengths** Good and detailed answers, attached a link to student promotions

**Weaknesses** Sometimes it adds unnecessary information, making it harder to read.

**Recommendations** Add the ability to look at the sources used for the answers, links to the products it describes, and at the end offer the user something else to ask

#### Mistral

| Question | Truthfulness | Content Relevance | Content Completeness |
|----------|--------------|-------------------|----------------------|
| Q1       | 2            | 2                 | 2                    |
| Q5       | 2            | 2                 | 2                    |
| Q2       | 2            | 2                 | 1                    |
| Q3       | 1            | 1                 | 2                    |
| Q4       | 2            | 2                 | 2                    |
| Overall  | 1.8          | 1.8               | 1.8                  |

**Strengths** The model gives good detailed answers that are well formatted, but sometimes there is too much information

**Weaknesses** Doesn't always provide the most up-to-date information, didn't provide links to resources that I used, for example, to check student promotions

**Recommendations** Add a reference to the sources so that the user can use them in the future.

####  Gemini

| Question | Truthfulness | Content Relevance | Content Completeness |
|----------|--------------|-------------------|----------------------|
| Q1       | 2            | 2                 | 2                    |
| Q2       | 2            | 2                 | 2                    |
| Q3       | 2            | 2                 | 2                    |
| Q4       | 1            | 2                 | 2                    |
| Q5       | 2            | 2                 | 1                    |
| Overall  | 1.8          | 2                 | 1.8                  |

**Strengths** The model has good information about different internet sources, there is no unnecessary information in the comments, so it is easy to find

**Weaknesses** Sometimes the formatting is not as convenient as other models, in the list of popular languages, she did not mention the existence of different ratings and gave a specific one

**Recommendations** The model already gives good answers, but could add additional questions at the end to clarify the information.

#### DeepSeek

| Question | Truthfulness | Content Relevance | Content Completeness |
|----------|--------------|-------------------|----------------------|
| Q1       | 2            | 2                 | 2                    |
| Q2       | 2            | 2                 | 2                    |
| Q3       | 2            | 1                 | 2                    |
| Q4       | 1            | 1                 | 2                    |
| Q5       | 2            | 2                 | 2                    |
| Overall  | 1.8          | 1.6               | 2                    |

**Strengths** The model uses resources very well, and also shows which ones she used to answer, sends links to the necessary sites, very good information

**Weaknesses** Sometimes adds unnecessary information to the answer, very long answers, for example, the number of popular languages could be reduced

**Recommendations** To make the user experience more convenient, the answer should include only the most important information, and at the end the model can ask if there is anything else to add.

#### YandexGPT 4 Pro RC

| Question | Truthfulness | Content Relevance | Content Completeness |
|----------|--------------|-------------------|----------------------|
| Q1       | 2            | 2                 | 1                    |
| Q2       | 2            | 2                 | 0                    |
| Q3       | 0            | 2                 | 2                    |
| Q4       | 1            | 2                 | 0                    |
| Q5       | 2            | 2                 | 2                    |
| Overall  | 1.4          | 2                 | 1                    |

**Strengths** Writes fairly compact answers without unnecessary fluff, making it easy to find the information you need

**Weaknesses** Doesn't know how to use internet sources, or talk about them. Instead, writes an incorrect/inaccurate answer or a very vague one, as in the case of cloud offers from jetbreins

**Recommendations** It is possible to add tools that allow you to google information or an honest option that there is no exact information if they ask about relevant information, such as JetBrains offers for students
    

### Conclusion
In this report, a comparison of 5 large LLMs was made, which have a chat in the public domain. All models cope well with the tasks, as they are cloud-based and have large sizes. It is worth answering that the answers of the models are very similar to each other, but some add more specifics. The worst model was from Yandex, as it is clear that it does not have the ability to search for the most relevant information. The other models are all good, but I would highlight the DeepSeek model, whose answers seemed to me the most relevant