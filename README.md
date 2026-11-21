# CCNA NETGEAR GUI V1.3 — CLI 參數全面檢查版

以 V1.2.1 為基礎，逐一檢查 23 個模組（19 個設定模組、1 個監控模組、3 個知識模組）。

## 修正
- 19 個設定模組增加 20+ 個常見原本固定的設定參數（SSH timeout/retries、STP 模式、Port Security Sticky、DHCP Snooping/DAI Trust、OSPF cost/passive、ACL action/protocol 等）。
- **每個模組均有「進階 GUI：逐條 CLI 指令參數／新增指令」**：所有預設 CLI 行均可逐行修改、移除、增加。基本欄位變更時進階欄位會重置為最新預設，避免不同模式的舊指令殘留。
- 保留手機版、CLI 對照、記憶練習及本機設定紀錄。
- 修正監控模組不應儲存為 running config。

## 重要限制
這是 CLI 教學產生器，並非 Cisco IOS 解析器或真正網路模擬器。進階指令編輯器讓 GUI 不再隱藏固定 CLI 行，但**無法保證任意手動新增指令的語法或 IOS 版本相容性**。部分 CCNA 考點（WLC、JSON、REST、RF、拓樸與協定收斂）仍是知識導覽，不是完整互動模擬。建議用 Packet Tracer / 真實設備驗證。

## GitHub Pages
解壓縮後將 index.html、sw.js、manifest.webmanifest、icon.svg、README.md 上傳至 Repository 根目錄；Settings → Pages → Deploy from a branch → main / (root)。PWA 更新後可嘗試重新整理或清除網站快取。
