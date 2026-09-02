# 三款旗艦 SoC 報導原始文章網址對照清單（Snapdragon 8 Elite Gen 5 / Dimensity 9500 / Exynos 2600）

## TL;DR
- 20 個來源中，絕大多數都找到了確切的原始文章/資料庫網址；少數（GSMArena「SoC 規格資料庫頁面」、Jon Peddie Research 的 Exynos 2600 專文、Notebookcheck Dimensity 9500 專屬資料庫頁）經查證並不存在或無法確認確切 ID，均已明確標示「查無此確切連結」並提供替代方案。
- 最可靠、可直接引用的一手來源包含：MediaTek 官方新聞稿、TechInsights 拆解報告、TrendForce（引 The Bell）量產新聞、Counterpoint、Mark Vena（Medium 引 Siegfried Chang）、SamMobile、TechPowerUp、GameGPU、Android Addicts 原始實測。
- 引用時請注意：多數「跑分資料庫」頁數據會隨時間更新（須註記擷取日期）；Exynos 2600 部分早期跑分屬洩漏且真偽存疑；少數頁面（Android Authority、部分資料庫頁）搜尋結果未顯示明確發佈日期，建議發佈前開啟確認。

## Key Findings（逐一對照）

**1. Counterpoint Research — 三款 SoC 製程與規格分析**
- URL: https://counterpointresearch.com/en/insights/qualcomm-snapdragon-8-elite-gen-5-redefines-mobile-performance-and-ai-efficiency
- 標題:「Qualcomm Snapdragon 8 Elite Gen 5: Redefines Mobile Performance and AI Efficiency」
- 核心內容：比較 Snapdragon 8 Elite Gen 5（TSMC 3nm、第三代 Oryon、新 Adreno GPU、更快 Hexagon NPU）、Dimensity 9500（強化 APU、優化 LLM/多模態）與 Samsung 重返旗艦戰局的 Exynos，聚焦 AI 導向架構與每瓦效能。

**2. Jon Peddie Research — GPU 架構分析**
- Snapdragon 8 Elite Gen 5：https://www.jonpeddie.com/news/qualcomm-snapdragon-8-elite-gen-5/ 標題「Qualcomm Snapdragon 8 Elite Gen 5」。內容涵蓋第三代 Oryon（Arm v9、對齊 PC 產線）、TSMC N3P、prime 核達 4.6GHz、Adreno GPU 針對 UE5/DX12/Vulkan 1.4 重新設計、18MB HPM 快取。
- Dimensity 9500：https://www.jonpeddie.com/techwatch/dimensity-9500-goes-big-on-cores-big-on-ai/ 標題「Dimensity 9500 goes big on cores, big on AI」（由子代理查得，發佈日期未顯示，建議點開再次確認）。
- Exynos 2600：**查無此確切連結，建議改引用類似主題的替代來源**。Jon Peddie 網站似無 Exynos 2600／Xclipse 960 GPU 專文；替代可用 TechInsights 拆解（見第 7 項）或 SamMobile 的 Xclipse 960 RDNA4 架構報導（見第 14 項）。

**3. Android Central — Snapdragon 8 Elite Gen 5 發表報導**
- 主發表報導 URL: https://www.androidcentral.com/phones/qualcomm/snapdragon-8-elite-gen-5-launch
- 標題:「The new Snapdragon 8 Elite Gen 5 promises smarter, more proactive AI and better video recording」
- 核心內容：3nm、雙 prime 核 4.6GHz、六效能核最高 3.62GHz、CPU 效能+20%、支援 APV 編碼、agentic AI。
- 補充（同站相關）：完整整理頁 https://www.androidcentral.com/phones/qualcomm/qualcomm-snapdragon-8-elite-gen-5 （提及採 TSMC「3NP」節點）；發表前預告頁 https://www.androidcentral.com/phones/qualcomm/qualcomm-confirms-snapdragon-8-elite-gen-5 （確認 9/23 Snapdragon Summit 揭曉）。

**4. GSMArena — 規格資料庫頁面 + Galaxy S26 續航實測**
- 續航實測對比報導 URL: https://www.gsmarena.com/exynos_2600equipped_galaxy_s26_disappoints_in_battery_test_-news-72176.php 標題「Exynos 2600-equipped Galaxy S26 disappoints in battery test」。引用 Android Addicts 實測：兩機同為 4,300mAh／12GB／512GB、同一 5G 網路關 Wi-Fi；Exynos 版撐 6h48m，Snapdragon 版再多撐 2h38m（約長 39%）。
- Dimensity 9500 發表新聞：https://www.gsmarena.com/mediatek_announces_dimensity_9500_flagship_chipset-news-69618.php （Prasad，2025-09-22）。
- **SoC「規格資料庫頁面」：查無此確切連結，建議改引用替代來源**。GSMArena 並無針對 SoC 的獨立「規格資料庫」頁，其晶片內容以帶日期的新聞文章形式呈現。建議 SoC 規格庫改用第 12（91mobiles）、13（nanoreview）或第 6（Notebookcheck）項所列頁面。

**5. MediaTek 官方新聞稿 — Dimensity 9500 規格發布**
- URL: https://www.mediatek.com/press-room/mediatek-dimensity-9500-unleashes-best-in-class-performance-ai-experiences-and-power-efficiency-for-the-next-generation-of-mobile-devices
- 標題:「MediaTek Dimensity 9500 Unleashes Best-in-Class Performance, AI Experiences, and Power Efficiency for the Next Generation of Mobile Devices」（HSINCHU, Taiwan – Sept. 22, 2025）
- 核心內容：第三代 All Big Core（4.21GHz C1-Ultra + 三 premium + 四 performance）、四通道 UFS 4.1、Arm G1-Ultra GPU、NPU 990（Generative AI Engine 2.0）。

**6. Notebookcheck — 跑分資料庫 + CPU 功耗實測（引 Geekerwan）+ 續航對比**
- CPU/GPU 早期跑分報導 URL: https://www.notebookcheck.net/MediaTek-Dimensity-9500-vs-Snapdragon-8-Elite-Gen-5-Early-CPU-and-GPU-benchmarks-indicate-a-win-for-Qualcomm.1126321.0.html 標題「MediaTek Dimensity 9500 vs Snapdragon 8 Elite Gen 5: Early CPU and GPU benchmarks indicate a win for Qualcomm」。引 Xiaobai's Tech Reviews 逐字數據：Snapdragon 8 Elite Gen 5「single-core score of 3,831 and a multi-core score of 12,459 on Geekbench 6」，Dimensity 9500「scores 3,635 and 10,941」；GPU 3DMark Wild Life Extreme 8,492 vs 8,251。
- CPU 功耗/能效實測（引用 Geekerwan 數據）URL: https://www.notebookcheck.net/Qualcomm-Snapdragon-8-Elite-Gen-5-vs-Dimensity-9500-and-Apple-A19-Pro-in-efficiency-analysis.1123883.0.html 標題「Qualcomm Snapdragon 8 Elite Gen 5 vs Dimensity 9500 and Apple A19 Pro in efficiency analysis」。逐字：「the Snapdragon 8 Gen 5 Elite consumes around 19 watts of power at full CPU load, compared to the 12 watts of the Apple A19 Pro or the 17 watts of the Snapdragon 8 Elite」（GPU 端 3DMark Steel Nomad Light 約 12W）。
- Galaxy S26 續航對比報導 URL: https://www.notebookcheck.net/Samsung-Galaxy-S26-with-Exynos-2600-fails-in-battery-test-compared-to-Snapdragon.1261969.0.html 標題「Samsung Galaxy S26 with Exynos 2600 fails in battery test compared to Snapdragon」。
- 規格資料庫頁面：
  - Exynos 2600：https://www.notebookcheck.net/Samsung-Exynos-2600-Processor-Benchmarks-and-Specs.1270874.0.html
  - Snapdragon 8 Elite Gen 5：https://www.notebookcheck.net/Qualcomm-Snapdragon-8-Elite-Gen-5-Processor-Benchmarks-and-Specs.1123169.0.html （子代理查得，建議確認）
  - Dimensity 9500 專屬資料庫頁：**查無此確切連結（子代理無法確認頁面 ID）**，建議改用上方 CPU/GPU 對比報導，或其 GPU 資料庫頁 https://www.notebookcheck.net/Arm-Mali-G1-Ultra-MC12-Benchmarks-and-Specs.1157800.0.html （子代理查得，建議確認）。

**7. TechInsights — Exynos 2600 拆解（確認 Samsung SF2 製程）**
- URL: https://www.techinsights.com/blog/samsung-exynos-2600-2nm-sf2-process-analysis
- 標題:「Samsung Exynos 2600 (2nm SF2) Process Analysis」
- 核心內容：自 Galaxy S26+ 5G 取出 Exynos 2600 晶粒，經拆解與顯微分析確認採 Samsung 2nm SF2 GAA（MBCFET 多橋通道）製程，為 Samsung 第二款 GAA 行動處理器、首款 2nm。
- 補充：概述文 https://www.techinsights.com/blog/samsung-exynos-2600-brings-2nm-smartphones ；Floorplan 分析 https://www.techinsights.com/blog/samsung-exynos-2600-2nm-sf2-floorplan-analysis ；Dimensity 9500 相關 https://www.techinsights.com/blog/dimensity-9500-debuts-arm-c1-cores-and-dual-npu （確認 Dimensity 9500 採 TSMC N3P、30 億電晶體）。

**8. TrendForce — 引 The Bell 的 SF2 良率與 Exynos 2600 量產時程（2025-09-30 發布）**
- URL: https://www.trendforce.com/news/2025/09/30/news-samsung-reportedly-starts-exynos-2600-mass-production-yield-estimated-to-reach-50/
- 標題:「[News] Samsung Reportedly Starts Exynos 2600 Mass Production, Yield Estimated to Reach 50%」
- 核心內容（引 The Bell 逐字）：「The SF2 process yield climbed from around 30% in Q1 to an estimated 50%... The 'fab out'... is expected between late October and early November.」（良率由 Q1 約 30% 升至約 50%，9 月投片，預計 10 月底至 11 月初 fab-out）。

**9. Android Authority — Exynos 2600 / Dimensity 9500 架構評析 + GPU 穩定度實測**
- Dimensity 9500 首發實測（含 GPU 穩定度）URL: https://www.androidauthority.com/first-dimensity-9500-phone-benchmarked-3606500/ 標題「I benchmarked the first Dimensity 9500 phone (Update: Re-tested)」，vivo X300 Pro 穩定度約 54%、峰值 45.1°C。
- Exynos 2600 發表/架構：https://www.androidauthority.com/samsung-exynos-2600-announced-3626595/ 標題「Samsung announces Exynos 2600: World's first 2nm smartphone chip...」（子代理查得，建議點開確認）。
- Xclipse/AMD RDNA 架構與 GPU 穩定度分析：https://www.androidauthority.com/samsung-exynos-amd-analysis-3656892/ 標題「Samsung bet big on AMD for Exynos...」（子代理查得，建議確認）。

**10. TechPowerUp — Geekbench Browser 排行（引 Geekerwan 的 Xclipse 960 OpenCL 數據）**
- URL: https://www.techpowerup.com/345515/samsungs-exynos-2600-tops-android-gpu-performance-charts-in-early-geekbench-6-tests
- 標題:「Samsung's Exynos 2600 Tops Android GPU Performance Charts in Early Geekbench 6 Tests」
- 核心內容：Xclipse 960 於 Geekbench 6 OpenCL 得 24,964 分，登 Geekbench Browser Android 榜首，勝 Honor Magic8 Pro 的 Snapdragon 8 Elite Gen 5（23,634）逾 1,000 分；同站 Geekerwan 遊戲功耗文可參 https://www.techpowerup.com/341353/early-benchmarks-reveal-impressive-snapdragon-8-elite-gen-5-gaming-performance 。

**11. Beebom — 零售機 Geekbench/AnTuTu 實測 + CPU 節流測試**
- Snapdragon 8 Elite Gen 5：https://gadgets.beebom.com/guides/snapdragon-8-elite-gen-5-benchmark-specs 標題「Snapdragon 8 Elite Gen 5: Benchmarks and Specs」。iQOO 15 實測 AnTuTu v11 3,740,686、Geekbench 3,588/10,207，並含 CPU Throttling 測試。
- Exynos 2600：https://gadgets.beebom.com/guides/samsung-exynos-2600-benchmark-specs 標題「Samsung Exynos 2600: Benchmarks and Specs」。
- 光追對比報導：https://gadgets.beebom.com/news/samsung-exynos-2600-outperforms-snapdragon-8-elite-gen-5-and-dimensity-9500-in-ray-tracing-benchmarks 。

**12. 91mobiles — 三款 SoC 跑分資料庫頁面**
- Snapdragon 8 Elite Gen 5：https://www.91mobiles.com/processor/qualcomm-snapdragon-8-elite-gen-5-pdp （AnTuTu 4,033,382）
- Dimensity 9500：https://www.91mobiles.com/processor/mediatek-dimensity-9500-pdp
- Exynos 2600：https://www.91mobiles.com/processor/samsung-exynos-2600-pdp （AnTuTu 3,113,347）

**13. nanoreview — 三款 SoC 跑分資料庫頁面**
- Snapdragon 8 Elite Gen 5：https://nanoreview.net/en/soc/qualcomm-snapdragon-8-elite-2
- Dimensity 9500：https://nanoreview.net/en/soc/mediatek-dimensity-9500
- Exynos 2600：https://nanoreview.net/en/soc/samsung-exynos-2600
- 注意：Snapdragon 8 Elite Gen 5 的 slug 為 `qualcomm-snapdragon-8-elite-2`（非 gen-5），勿與 Dimensity 9500s 等變體頁面混淆。

**14. SamMobile — Xclipse 960 採 AMD RDNA 4 + Basemark 光追**
- RDNA4 架構報導 URL: https://www.sammobile.com/news/exynos-2600-first-mobile-chip-amd-rdna4-gpu/ 標題「Exynos 2600 is the first Exynos to use AMD's RDNA4 GPU technology!」（引 The Elec，Xclipse 960 採 RDNA4 衍生 MGFX4、8 WGP/16 CU、980MHz）。
- Basemark 光追報導 URL: https://www.sammobile.com/news/exynos-2600s-gpu-outperforms-rivals-ahead-galaxy-s26-launch/ 標題「Exynos 2600's GPU outperforms rivals ahead of Galaxy S26 launch」（GPU Score In Vitro 1.0 Mobile Raytracing 8,321 分居首，勝 Adreno 840 與 Mali-G1 Ultra）。

**15. Mark Vena — 引 Siegfried Chang（MediaTek 產品行銷資深總監）談話**
- URL: https://markvena.medium.com/mediateks-new-dimensity-9500-a-bold-flagship-play-in-a-market-defined-by-apple-and-qualcomm-f2cea9a3a432
- 標題:「MediaTek's New Dimensity 9500: A Bold Flagship Play in a Market Defined by Apple and Qualcomm」（Medium）
- 核心內容（引 Chang 逐字）：CPU「For the single core, compared to our last generation, we upgrade around 32%. And for the power consumption, we have even lower... around 37%.」；NPU「we almost doubled performance with a new architecture... and we can reach up to 100 TOPS NPU, which is the most powerful.」

**16. PhoneArena — Exynos 2600 早期跑分真偽爭議**
- URL: https://www.phonearena.com/news/the-exynos-2600-ap-reportedly-benchmarks-near-apple-m5-levels_id175429
- 標題:「It's hard to believe, but the Exynos 2600 AP reportedly benchmarks at Apple M5 levels」
- 核心內容：@lafaiel 於 X 貼出 Exynos 2600 單核 4,217、多核 13,482，但 Geekbench 官方資料庫查無該結果，PhoneArena 明確質疑可能已被移除、造假或測試未曾發生。
- 補充（同站相關爭議報導）：https://www.phonearena.com/news/Alleged-Galaxy-S26-Ultra-benchmark-scores-dispel-a-fantasy_id177238 （引 Ice Universe，反駁 Exynos 超越 Snapdragon 的說法）。

**17. comparigon — Exynos 2600 AnTuTu 子項跑分資料庫頁面**
- URL: https://comparigon.com/mobilesocs/exynos-2600
- 標題:「Exynos 2600 Specs Review」
- 核心內容：AnTuTu v11 總分 3,161,830，子項分拆 CPU 1,060,612 / GPU 1,200,578 / Memory 409,429 / UX 491,211。

**18. GameGPU — Snapdragon 8 Elite Gen 5 遊戲功耗模擬實測**
- URL: https://en.gamegpu.com/news/igry/snapdragon-8-elite-gen-5-tyanet-aaa-igry-no-stradaet-ot-energopotrebleniya
- 標題:「Snapdragon 8 Elite Gen 5 handles AAA games, but suffers from power consumption」
- 核心內容：以模擬跑 Cyberpunk 2077、RDR2、RE Requiem 達 80–90 FPS。逐字：「Initially, peak power consumption was reported to be around 50 watts, but it was later clarified that the data was incorrect. The actual value is approximately 24 W」（原報約 50W 為誤讀，實際峰值約 24W；WccfTech 補充 RE Requiem 為 24.1W 而非 48.3W，係 GameHub 讀數加倍所致）。

**19. Android Addicts — Galaxy S26 Exynos vs Snapdragon 續航原始實測**
- URL: https://www.androidaddicts.online/2026/04/25/galaxy-s26-day-in-the-life-battery-drain-test-exynos-vs-snapdragon/
- 標題:「Galaxy S26 Day in the Life Battery Drain Test (Exynos vs Snapdragon)」（2026-04-25）
- 核心內容：原始「一日使用」續航實測（此為續作；GSMArena/SamMobile 早前引用的原始 6h48m vs 9h26m 測試對應同頻道 YouTube 影片 youtu.be/zQI7PBQDs_Q）。此頁為 Android Addicts 官網原始貼文，內含各階段實測與相關影片連結。

**20. CpuTronic — Dimensity 9500 採 TSMC N3P 製程確認**
- URL: https://cputronic.com/soc/mediatek-dimensity-9500
- 標題:「MediaTek Dimensity 9500: Detailed Specifications and Benchmark Ratings」
- 核心內容：明載採 TSMC 3nm N3P 節點、1×C1-Ultra + 3×C1-Premium + 4×C1-Pro（Armv9.3）、最高 16MB L3、Arm Mali-G1 Ultra（MC12）、LPDDR5X 至 10,667 MT/s、UFS 4.1。

## Recommendations
- **一手引用優先**：官方新聞稿（第 5 項 MediaTek）、拆解機構（第 7 項 TechInsights）、供應鏈新聞（第 8 項 TrendForce 引 The Bell）、原始實測（第 19 項 Android Addicts、第 18 項 GameGPU、以及經 TechPowerUp/Notebookcheck 轉述的 Geekerwan 功耗數據）。這些屬最高可信度，可作為主要引用。
- **對於三項「查無確切連結」**：(a) GSMArena SoC 規格庫——改用 91mobiles/nanoreview/Notebookcheck 規格庫頁；(b) Notebookcheck Dimensity 9500 資料庫頁——改用其 CPU/GPU 對比報導或 Mali-G1 Ultra GPU 頁；(c) Jon Peddie Exynos 2600 專文——改用 TechInsights 或 SamMobile 的 Xclipse 960 架構報導。切勿自行拼湊或臆測 URL。
- **發佈前建議逐一開啟驗證**：由子代理查得但我未親自逐一開啟的連結（Jon Peddie Dimensity 9500、Android Authority Exynos 2600 相關兩篇、Notebookcheck Snapdragon/Mali 資料庫頁）。若判準：頁面能正常開啟且標題與內容相符即可採用；若 404 或內容不符，改用同項所列已確認之替代連結。

## Caveats
- 多數 SoC「跑分資料庫」頁面（91mobiles、nanoreview、comparigon、Notebookcheck、CpuTronic）數據會隨版本與新機加入而更新，引用時務必註明擷取日期。
- Exynos 2600 部分早期跑分屬洩漏且真偽存疑（見第 16 項；亦有 Notebookcheck「CPU downgrades」與 PhoneArena「dispel a fantasy」等後續報導），引用該類數字時應明確標明爭議與未經官方證實。
- 發佈日期：部分資料庫頁與 Android Authority 文章於搜尋結果未顯示明確日期，需開啟頁面確認；本清單中未標日期者即屬此類。
- 續航「壓力測試」（第 4、19 項）屬單一 YouTuber 的高強度情境，非日常使用代表值，且部分評論指出歐版與美/加版數據機頻段聚合支援差異可能放大差距，引用時宜補充此背景。