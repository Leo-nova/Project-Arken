# 🤝 貢獻指南 Contributing

首先，謝謝你願意花時間關注這個小專案。  
這裡大部分都是我跟 AI 一起協作拚湊出來的東西，  
所以如果你想要幫忙、補充，當然非常歡迎。  

---

## 📌 你可以怎麼幫？
- **開 Issue**：發現 bug、文檔有錯字，或有趣的新想法，請直接開 Issue。  
- **提 PR**：如果你動手修好了，直接送 PR 就行。  
- **分享心得**：其實就算只是在 Discussions 留下一句「好玩」或「幹這也行」，我也會覺得很開心。  

---

## 📂 資料夾與命名規範
為了保持整個 repo 的乾淨與一致性，請遵循以下規則：  
- 資料夾名稱一律用 **小寫加 dash**（例如：`test-finance`, `test-healthcare`）。  
- 英文測試報告放在 `/En/`，繁體中文測試報告放在 `/zhTW/`。  
- 每個測試資料夾必須包含 `README.md`，用來摘要結果與結論。  
- 如果想塞一些「奇怪人格」，建議送去 `back-alley/`，那邊就是放怪東西的地方。  

---

## ⚠️ 注意事項
- 這個框架是實驗性質，不保證穩定。  
- Commit 訊息不用太嚴肅，但請盡量讓人看得懂。  
- **所有測試都僅供研究與教育用途，完全不構成專業建議。**  

---

## 💡 最後
不要把這裡想得太嚴肅。  
就像我的早期作品一樣，  
**這專案本來就該帶點實驗性、隨興，還有一點笑點。**

**部分架構設計的靈感來自 [@onestardao](https://github.com/onestardao) 的作品 [WFGY](https://github.com/onestardao/WFGY)，在此特別感謝。** 

---

🛠 維護說明：.gitattributes

本專案使用 `.gitattributes`檔案來標準化文字檔的格式，
例如：統一的換行符號、UTF-8 編碼（支援繁體中文文件）、以及正確處理二進位檔案。

如果你日後有更新或修改 `.gitattributes`，
請執行以下指令一次，以重新套用整個 repo 的規則：

```bash
git rm --cached -r .
git reset --hard
git add --renormalize .
git commit -m "Apply .gitattributes normalization"
