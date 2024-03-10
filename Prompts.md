# Prompts

## **GPT Conversation:** [MT: Weekly md to html](https://chat.openai.com/share/3b5fe4ab-cc55-4ee0-8508-3d9595685215)

**User:**
Given the following example transformation pair: markdown fragment:
```
| 1) **Transformers for Time-Series Data**  | #timeseries #transformers | [Blog](https://medium.com/bearingpoint-data-analytics-ai/transformers-for-time-series-data-3fadff9f07d8) 
| 2) **Bentsen 2022** - Spatio-Temporal Wind Speed Forecasting using Graph Networks and Novel Transformer Architectures | #timeseries #transformers | [Paper](https://arxiv.org/abs/2208.13585) [GitHub](https://github.com/LarsBentsen/FFTransformer.) 
```
and corresponding HTML:
```
<div>
    <p><b>1) Transformers for Time-Series Data</b>
        <span class="hashtag">#timeseries #transformers</span>
        ( <a href="https://medium.com/bearingpoint-data-analytics-ai/transformers-for-time-series-data-3fadff9f07d8">Blog</a> )</p>
    <hr>
</div>

<div>
    <p><b>2) Bentsen 2022</b> - Spatio-Temporal Wind Speed Forecasting using Graph Networks and Novel Transformer Architectures
        <span class="hashtag">#timeseries #transformers</span>
        ( <a href="https://arxiv.org/abs/2208.13585">Paper</a> | <a href="https://github.com/LarsBentsen/FFTransformer.">GitHub</a> ) </p>
    <hr>
</div>
```
Transform the following markdown into HTML fragment:
```
| 9) **ChatGPT Prompt Engineering for Developers** - from DeepLearning.AI by Andrew Ing and Isa Fulford (1 hour) | #course #llm | [Course](https://learn.deeplearning.ai/courses/chatgpt-prompt-eng)
| 10) **Notebooks to Python** - Bridging the Gap: Converting Data Science Notebooks into Production ML Code | #python | [Blog](https://marvelousmlops.substack.com/p/bridging-the-gap-converting-data?utm_source=multiple-personal-recommendations-email&utm_medium=email&triedRedirect=true)

```

**ChatGPT:**
```
<div>
    <p><b>9) ChatGPT Prompt Engineering for Developers</b> - from DeepLearning.AI by Andrew Ing and Isa Fulford (1 hour)
        <span class="hashtag">#course #llm</span>
        ( <a href="https://learn.deeplearning.ai/courses/chatgpt-prompt-eng">Course</a> )</p>
    <hr>
</div>

<div>
    <p><b>10) Notebooks to Python</b> - Bridging the Gap: Converting Data Science Notebooks into Production ML Code
        <span class="hashtag">#python</span>
        ( <a href="https://marvelousmlops.substack.com/p/bridging-the-gap-converting-data?utm_source=multiple-personal-recommendations-email&utm_medium=email&triedRedirect=true">Blog</a> )</p>
    <hr>
</div>
```