# teenager-phone-usage-analysis

# 📱 青少年手機使用與成癮分析

## 專案簡介
本專案分析青少年手機使用行為與成癮情況，探索使用時間、睡眠、學業表現、焦慮程度等變數之間的關聯。

## 資料來源
- 檔案名稱：`teen_phone_addiction_dataset.csv`
- 資料包含 **12 個欄位**：
  - Age, Daily_Usage_Hours, Sleep_Hours, Academic_Performance, Exercise_Hours, Anxiety_Level, Time_on_Social_Media, Time_on_Gaming, Time_on_Education, Phone_Usage_Purpose, Weekend_Usage_Hours, Addiction_Level

## 使用技術
- **Python**（Pandas, Matplotlib, Seaborn）
- **SQLite**（資料存儲與查詢）
- **Jupyter Notebook**（數據處理與可視化）

## 分析內容
1. 成癮等級與平均每日使用時間及睡眠時間的關係
2. 不同手機用途與學業表現的差異
3. 每日使用時間與睡眠時間的散點圖
4. 遊戲時間與學業表現的相關性
5. 社交媒體使用時間與焦慮程度的關聯

## 部分分析結論
1. 成癮等級最高的族群每日使用時間最長且睡眠最少，顯示高度成癮與睡眠不足可能相關。
2. 以學習為主要手機用途的學生，平均學業表現最佳；以遊戲為主要用途者學業表現最低。
3. 社交媒體使用時間與焦慮程度可能存在正向關聯。

## 專案檔案結構
📂 teen-phone-usage-analysis
├── teen_phone_addiction_dataset.csv # 原始資料
├── teen_phone_addiction_dataset_cleaned_advanced.csv # 清理後資料
├── smartphone addiction.ipynb # Jupyter Notebook 分析
