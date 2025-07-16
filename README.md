# Economic Interconnectedness

This repository contains the scripts, data, and outputs from an ongiong project to perform large scale network analysis on bilateral trade flows and international financial position and their economic significance. 

Using data from the Inaternational Monetary Fund (IMF)'s [International Trade in Goods (by partner country) (IMTS)](https://data.imf.org/en/datasets/IMF.STA:IMTS), [Direct Investment Positions by Counterpart Economy (formerly CDIS)](https://data.imf.org/en/datasets/IMF.STA:DIP) and [Portfolio Investment Positions by Counterpart Economy (formerly CPIS)](https://data.imf.org/en/datasets/IMF.STA:PIP), as well as the Bank of International Settlements (BIS)'s [Location Banking Statistics (LBS)](https://data.bis.org/topics/LBS) we construct a composite index of systemic interconnectedness using 16 centrality based metrics, weigthed after filtering through a Principal Component Analysis (PAC). Afterwards we perform a cross-country time series panel Vector Autoregression (VAR) to evaluate for links of trade and financial interconnectedness on macroeconomic performance.

The model's acripts, it's analytical pipeline, and outputs are all done using mostly [R](https://www.r-project.org/), with R Markdown for drafting a reproducible research document and Overleaf for formatting a submiteable document.

## Version history

### 1.0

##### XX-XXX-202X

Intitial release
