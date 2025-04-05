# 🎮 全球电子游戏销售分析  
**基于16,598条游戏销售数据的市场洞察 | Python/SQL/Tableau**  
 

---

## 📌 项目概述  
**目标**：分析全球电子游戏销售数据，挖掘畅销游戏特征、市场分布规律与行业趋势，为游戏开发与发行策略提供数据支持。  
**关键成果**：  
- 识别动作类（Action）和体育类（Sports）为最畅销游戏类型，合计占比超30%；  
- 发现北美市场贡献近50%销售额，日本市场RPG类占比35%；  
- 揭示任天堂（Nintendo）为市场份额最高发行商（占比17%）。  

---

## 🛠️ 技术栈  
- **数据分析**：Python (Pandas, Matplotlib, Seaborn)  
- **数据查询**：SQL (分组聚合、多条件筛选)  
- **可视化**：Plotly, Tableau  

---

## 📂 数据来源  
Kaggle公开数据集：[Video Game Sales](https://www.kaggle.com/gregorut/videogamesales)  
- **数据量**：16,598条记录，11个字段  
- **关键字段**：  
  - `Global_Sales`（全球销售额）  
  - `Genre`（游戏类型）  
  - `Platform`（发行平台）  
  - `Publisher`（发行商）  

---

## 🔍 分析流程  
```mermaid
graph LR
A[数据清洗] --> B[多维分析]
B --> C[可视化洞察]
C --> D[业务策略]
