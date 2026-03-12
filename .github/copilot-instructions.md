# 海膽速遞 Sea Urchin Delivery

## Project
Premium 日本海膽直送服務的品牌官網。AEO 優化的靜態網站，使用 GitHub Pages 托管。

## Conventions
- 使用 Semantic HTML5
- 遵循 Schema.org 結構化資料規範
- 保持 HTML 简洁，不使用複雜的 JavaScript 框架
- 確保所有頁面符合無障礙標準 (WCAG)

## Naming
- 英文 kebab-case 命名檔案和資料夾
- 中文用於主要文案內容
- 圖片命名描述性且具意義

## Architecture
- 靜態網站，無後端伺服器
- 主分支 (main) 為部署分支
- AEO 優先：實作 Schema.org (Organization, Product, FAQPage) 和 llms.txt
- FAQ 頁面使用結構化資料

## Commands
- 推送至 main 分支自動觸發 GitHub Pages 部署
- 本地預覽：使用任何靜態伺服器（如 `npx serve` 或 VS Code Live Server）

## Do Not
- 不要在 main 分支直接編輯，應使用 Pull Request
- 不要移除 Schema.org 結構化資料
- 不要刪除 llms.txt
- 不要添加不必要的 JavaScript 依賴