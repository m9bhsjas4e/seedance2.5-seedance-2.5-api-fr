# Seedance 2.5 Guide API（seedance-2.5 / seedance2.5）

<p align="center">
  <img src="hero.jpg" width="820" alt="Seedance 2.5 sample">
</p>

> À l'usage, rechargement dès 1 $, endpoint compatible OpenAI. **480P-input $0.0576; 480P $0.0961; 720P-input $0.1296**

**[模型页](https://go.apimart.ai/k-56bbc9) · [实时价格](https://go.apimart.ai/k-52310a) · [获取 API Key](https://go.apimart.ai/k-f489bf)**

## Tarifs（快照 2026-09-24）

| 档位 | 单价 |
| --- | --- |
| `480P-input` | $0.0576 |
| `480P` | $0.0961 |
| `720P-input` | $0.1296 |
| `default` | $0.216 |

按量计费、**$1 起充**，无订阅、无免费额度；每次任务响应返回 `cost` / `credits_cost`。

## 调用示例

```bash
curl --request POST --url https://api.apimart.ai/v1/videos/generations \
  --header "Authorization: Bearer $APIMART_API_KEY" --header 'Content-Type: application/json' \
  --data '{"model":"seedance-2.5","prompt":"海边悬崖的现代别墅，黄昏","size":"16:9","n":1}'
```

## 披露

Ce dépôt documente l'accès via APIMart, passerelle tierce.
