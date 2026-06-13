# 醫學系課程地圖單一 HTML 版

這個版本已將 HTML、CSS 與 JavaScript 全部整合在 `index.html`，可直接上傳到 GitHub Pages 或一般網頁空間使用。

## 使用方式

1. 上傳 `index.html`。
2. 若使用 GitHub Pages，請將 `index.html` 放在 repository 根目錄。
3. 到 GitHub repository 的 `Settings` → `Pages`。
4. Source 選擇 `Deploy from a branch`。
5. Branch 選擇 `main` 與 `/root`。

## 修改課程內容

課程資料位於 `index.html` 的 `courses` 陣列中。每門課包含以下欄位：

```js
{
  year: '一年級',
  semester: '上',
  name: '普通生物學',
  domain: '基礎科學',
  competency: '基礎醫學知識、終身學習',
  prerequisite: '高中生物',
  note: '銜接細胞生物學與生理學'
}
```

只要替換或增減陣列中的資料，網頁表格與篩選選單會自動更新。
