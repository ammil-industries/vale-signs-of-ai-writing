# UTMParameters Test Cases

## Should Flag (True Positives)

Visit https://example.com/article?utm_source=chatgpt.com for more information.

Source: https://site.org?utm_source=openai&ref=ai

Link: https://news.com/story&utm_source=chatgpt.com

Reference: https://docs.example.com?utm_source=openai

## Should NOT Flag (Avoid False Positives)

Visit https://example.com/article?utm_source=newsletter for more.

Source: https://site.org?utm_source=google&ref=search

Normal URL: https://example.com/article

URL with other params: https://site.org?ref=twitter&campaign=social
