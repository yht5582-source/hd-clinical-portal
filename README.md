# 血液透析室｜臨床決策與智慧照護入口首頁 (`hd-clinical-portal`)

血液透析室跨專業（醫師、護理師、營養師、行政品管）單頁互動網頁整合入口，串接所有臨床決策工具並內建床邊快算與急症處置導航。

## 線上入口網址（GitHub Pages）
- 入口首頁：`https://yht5582-source.github.io/hd-clinical-portal/`

## 整合子系統清單
1. **醫師端｜透析處方（spKt/V）與每月生化決策引導**：`https://yht5582-source.github.io/hd-clinical-decision-support/`
2. **護理端｜上機前 UFR 安全檢核與血管通路穿刺地圖**：`https://yht5582-source.github.io/hd-nursing-ufr-access/`
3. **營養端｜CKD 與透析專用口服營養品（ONS）精算**：`https://yht5582-source.github.io/ckd-ons-choice/`
4. **內建床邊即時工具**：
   - 超濾率（UFR）、白蛋白矯正血鈣、鈣磷乘積、URR 與 Daugirdas II spKt/V 口袋快算
   - 透析中併發症（IDH、肌肉痙攣、DDS、迴路凝血、空氣栓塞）急救處置 SOP 導航
   - 血漿置換術（TPE）血漿容積（EPV）與置換液比例計算器
   - 健保門診透析品質指標（HD1–HD13，對照健保署公告）、KDOQI/KDIGO 臨床目標與 B/C 肝感染管制分區檢核

## 版本紀錄
- **v1.1（2026-11-14）**：篩選與搜尋可同時作用並顯示件數與無結果提示；新增「行政品管」分類；口袋快算加入輸入檢查、透析後 BUN ≥ 透析前警示、Daugirdas II spKt/V；TPE 計算器改以台灣 FFP 單位（預設 110 mL/U）並修正補鈣劑量敘述；KPI 改列健保署 HD1–HD13 實際閾值（Albumin ≥ 3.5 BCG、URR ≥ 65%、Hb > 8.5、Ca×P < 60）並附來源；DDS 加入重症停機步驟；彈窗支援 Esc、焦點管理與鍵盤操作；加入 service worker 離線快取（`sw.js`）與 favicon。
