## Design
1. config plugin, like GPTs  action (openapi schema + authentication).
2. wrap API to `javascript` function,  then using [function-calling](https://platform.openai.com/docs/guides/function-calling)`
![image](https://github.com/user-attachments/assets/b7cfc13b-e9e8-46c0-bee5-4fa71e51bfff)


## Plugins

| Name | Authentication | Description |
| ---- | --- | ----------------------------- |
| [Dalle3](./plugins/dalle) | bearer | openai's dall-e image generator|
| [ArxivSearch](./plugins/arxivsearch) | - | Run Arxiv search and get the article information |
| [DuckDuckGoLiteSearch](./plugins/duckduckgolite) | - | a search engine |
| [Webpilot](./plugins/webpilot) | custom | from: https://www.webpilot.ai |

