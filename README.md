FinPulse Waterfall Pro - Professional Financial Waterfall Decomposition | 專業財務瀑布拆解工具

FinPulse Waterfall Pro is a professional-grade financial decomposition engine designed to visualize complex value chains. By leveraging interactive waterfall charts, this tool helps analysts and business owners transform raw income statements into intuitive, layer-by-layer insights from Revenue to Net Income.

FinPulse Waterfall Pro 是一款專為財務結構設計的「價值鏈拆解引擎」。本工具透過互動式瀑布圖技術，將複雜的損益數據轉化為直觀的層級分析，協助使用者精準掌握從營業收入到最終淨利的每一分價值流動。

🚀 核心功能 | Core Features

1. 層級拆解分析 | Hierarchical Decomposition Analysis

Dynamic Waterfall Visualization (動態瀑布圖視覺化): Automatically calculates the bridge between items. Positive values (Income) are highlighted in professional blue, while negative values (Expenses) are in soft red.
自動計算各項目間的銜接位點，收入項以專業藍呈現，支出項以柔和紅標示。

Negative Value Textures (負值警戒紋理): Subtotal items with negative values automatically trigger a high-density red stripe pattern for instant risk identification.
當結算位點（如毛利、淨利）轉為負值時，自動套用高密度細緻紅斜紋，強化經營風險識別。

Vertical Chinese Labeling (優化直式標籤): Native support for Traditional Chinese characters with vertical alignment, maintaining maximum readability in financial charts.
針對繁體中文優化的直式排列邏輯，確保在窄長的財務柱位下仍保有極佳的可讀性。

2. 精準會計邏輯 | Precision Accounting Logic

Automated ROC Tax Engine (營所稅自動引擎): Built-in logic follows Taiwan's Ministry of Finance corporate income tax brackets ($P \le 12w$: Exempt; $12w < P \le 20w$: 50% excess; $P > 20w$: 20% flat).
內建中華民國財政部營所稅級距邏輯，自動判定免稅、減徵與全額徵收區間。

5 Core KPI Monitoring (五大核心指標監測): Real-time calculation of Gross Margin, Expense Ratio, Operating Margin, Effective Tax Rate, and Net Margin.
即時計算並呈現毛利率、費用率、營益率、實質稅率與淨利率，全方位監控經營效率。

Professional Input Formatting (會計格式輸入): Supports thousand separators (e.g., 1,000,000) for an intuitive accounting experience.
輸入框支援自動千位分隔符號格式化，符合專業財務報表製作習慣。

3. 極致互動體驗 | Interaction & UX

Universal Reordering (全平台拖曳排序): Fully optimized for both Desktop (Drag-and-Drop) and iOS/Android (Touch handles) to customize your value chain sequence.
全面支援電腦（滑鼠拖曳）與手機（觸控手柄）操作，靈活調整價值鏈項目順序。

Retina-Quality Export (2x 解析度匯出): Export high-definition PNG reports including the customizable title and dynamic Net Income metrics, optimized for slide presentations.
支援 2x 倍率（Retina 級別）高清圖片匯出，包含可編輯標題與動態淨利數值，專為專業簡報設計。

Adaptive Theme System (自適應主題系統): High-contrast Dark mode and clean Light mode with automatic font color calibration.
提供高品質深色模式與極簡白天模式，字體顏色隨背景自動校準以維持對比度。

📈 數學模型 | Mathematical Concept

營利事業所得稅計算 (ROC Tax Calculation)

$$Tax =
\begin{cases}
0 & \text{if } P \le 120,000 \\
(P - 120,000) \times 0.5 & \text{if } 120,000 \< P \le 200,000 \\
P \times 0.2 & \text{if } P \> 200,000
\end{cases}$$

$P$: Pre-tax Income (課稅所得額)

🛠 技術棧 | Tech Stack

Frontend: React.js 18 (Standalone build)

Styling: Tailwind CSS (Responsive Utility-First)

Charting: Chart.js

Icons: Lucide React

Optimization: Custom Touch-Event listener for iOS Safari compatibility

📖 使用方式 | Getting Started

Github page : https://kasimchang.github.io/FinPulse/ (直接開啟互動網頁)

Edit Value Chain (編輯價值鏈): Click labels to rename or drag handles to reorder. (點擊標籤重新命名，或使用手柄拖曳排序)

Simulate Scenarios (模擬數據): Input Revenue and Expenses to see immediate KPI changes. (輸入營收與支出，即時觀察指標變動)

Export Report (匯出報表): Click "Download PNG" to save a 2x resolution analysis image. (點擊「下載圖片」儲存 2x 高清分析圖表)

✍️ 作者 | Author

kasimchang Precision Pricing Engine Creator GitHub Profile

📜 版權聲明 | Copyright & License

All Rights Reserved. This project is currently not open for licensing. No part of this software may be reproduced, modified, or distributed without written permission from the author.

版權所有，翻印必究。 本專案目前不開放授權使用。未經作者書面許可，請勿擅自轉載、修改、散佈或用於商業用途。
