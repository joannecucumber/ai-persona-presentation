# 傳統與人工智慧人物誌的設計實務與應用研究

**簡潔安\* 唐玄輝\*\***

\* 國立臺灣科技大學 設計系碩士 m11110914@gapps.ntust.edu.tw
\*\* 國立臺灣科技大學 設計系教授 drhhtang@mail.ntust.edu.tw

---

## 摘要

人物誌是現代設計的重要工具，隨著人工智慧的發展，設計師應如何建構有效的數位人物誌、發揮其價值是重要的設計實務議題，也是本研究主題。本研究目標為發展一套可操作的人工智慧人物誌（AI Persona）建構方法，探討不同性格設定的 AI Persona 在訪談中的差異表現。以台灣 Z 世代 ETF 投資者為案例，採用設計科學研究方法，依序建構方法論、建立 AI Persona、使用於設計概念階段，並進行訪談測試。研究發現：第一，「六維度劇本方法論」有效抑制角色漂移，使 AI Persona 維持跨對話的敘事一致性。第二，兩位性格迥異的 AI Persona 呈現外部確認與內在信念的對比，可協助設計滿足不同使用者需求。第三，AI Persona 可在設計流程中扮演三種角色：前期作為準受訪者快速探索、中期作為對照基準理解差異、後期作為演化素材持續補充洞察。本研究為 AI Persona 提供可操作的方法框架，建立 AI 時代設計實務與研究基礎，影響未來人工智慧設計的方向。

**關鍵詞**：AI Persona、人物誌、設計研究、人機協作

---

## 一、緒論

自 Cooper（1999）提出人物誌概念以來，人物誌已成為設計研究中代表使用者的核心方法，幫助設計團隊將決策錨定於使用者的需求與目標。然而，傳統人物誌存在根本性限制：一旦建構完成，便難以捕捉使用者因情境轉換或情緒波動而產生的動態變化。生成式 AI 展現出角色扮演的能力，使研究者能夠透過提示詞設計，建構可對話的 AI Persona，人物誌不再只是被閱讀的文件，而可以成為被訪談的主體。

然而，當 AI Persona 進入設計研究流程，不同性格設定的 AI Persona 之間是否存在差異？這些差異的本質為何？過去研究主要聚焦於保真度評估，即 AI 回應與真人的相似程度。本研究認為需要重新檢視這樣的框架，探索不同 AI Persona 之間的差異對設計研究與實務的意義。本研究採用設計科學研究方法（Hevner, March, Park, & Ram, 2004），探討兩個研究問題：問題一，如何建構一致且可區辨的 AI Persona 供設計研究使用？問題二，不同性格設定的 AI Persona 在對話回應中呈現結構性差異為何？本研究在台灣 Z 世代 ETF 投資者的情境中發展「六維度劇本方法論」，並建構兩位性格對比的 AI Persona，討論 AI Persona 做為設計研究工具的價值。

---

## 二、文獻探討

### 2-1 人物誌方法論：從傳統到數位

自 Cooper（1999）將人物誌引入設計實務以來，該方法已成為核心工具。然而，傳統人物誌面臨根本性限制：它們是靜態的，難以捕捉使用者隨時間的動態變化，且在抽象化過程中有淪為刻板印象的風險（Salminen et al., 2018）。

大型語言模型的發展為人物誌帶來數位化轉型的契機。Shao et al.（2023）提出 Character-LLM，發現模型能在較高層次模擬人格特質。Park et al.（2023）建立 25 個虛擬環境 AI 代理人，證明具體生活情境——職業、人際關係、日常作息和過往經歷——是建構可信 AI 角色的關鍵，此研究直接啟發本研究的六維度劇本方法論。然而，Tu et al.（2024）指出角色漂移等常見問題，Wang et al.（2024）發現即使先進模型也難以維持一致表現，凸顯建立穩健建構方法論的必要性。

### 2-2 AI 人物誌的應用與研究缺口

近期研究從多面向探索 AI 人物誌的應用可能。人物誌生成方面：De Paoli（2025）證明大型語言模型能從訪談資料產生人物誌描述，Shin et al.（2024）發現結合人類分群專業與大型語言模型摘要能力，產出優於單獨使用任一方的結果。品質評估方面：Salminen et al.（2024）發現大型語言模型生成的人物誌傾向產出偏斜特徵。互動應用方面：Sabbaghan 與 Brown（2024）證明大型語言模型驅動的人物誌能進行寫實對話訓練。

然而，現有研究多聚焦於保真度評估，追問「AI Persona 回應與真人有多相似？」此框架忽略根本問題：不同 AI Persona 之間差異的本質為何？本研究採取差異分析取向，追問「不同 AI Persona 在結構上有何差異，這些差異揭示了什麼？」此重新框架將 AI Persona 從不完美的人類模擬，轉變為其差異本身具有分析產出性的實體，定位為設計研究的輔助工具而非人類替代品。

---

## 三、研究方法

本研究採用設計科學研究方法（Hevner et al., 2004），聚焦於發展與驗證一套新穎的方法論作為設計產出物。設計科學研究強調創造與評估用以解決已識別問題的產出物。依循此方法，本研究分為兩個階段：建構階段，送代 AI Persona 的六維度劇本方法論；驗證階段，評估其有效性。

研究情境選擇台灣 Z 世代 ETF 投資者作為建構 AI Persona 情境，此選擇基於高度明顯的情緒與行為耦合特徵。相較其他投資者群體，Z 世代更容易受到短期市場波動和社群媒體影響，其決策語言常呈現猶豫、焦慮和自我質疑的特質，如「我懂應該長期持有，但我忍不住每小時都要看盤」。其不確定性和內在張力的語言特徵，使其成為觀察不同 AI Persona 之間差異的理想素材。

### 3-1 建構階段

建構階段的目標是透過人機共構，建立敘事穩定且適合訪談的 AI Persona。此過程包含兩部分：研究者透過 Gemini 2.5 進行三階段資料蒐集與劇本撰寫，產出六維度劇本；接著將劇本作為系統指令輸入 GPTs，創建互動式 AI Persona。工具選擇方面，本研究於 2025 年 3 月進行。Gemini 2.5 提供優異的深度搜尋能力，能系統性分解複雜研究任務並追蹤來源。GPTs 允許系統指令固定於後端，防止角色設定在多輪對話中被覆寫，確保 Persona 維持一致表現。

三階段資料蒐集方面，第一階段為次級資料蒐集，將 Gemini 2.5 配置為資深市場分析師，對台灣 Z 世代 ETF 投資市場進行系統性研究，識別出區分投資者的核心軸線：投資信心的來源。然而，內容雖具資訊性，但缺乏真實使用者的口吻和情緒表達。第二階段為初級資料蒐集，從 PTT 和 Dcard 擷取第一人稱敘事，分別擷取兩類投資者貼文：透過外部確認建立信心者，以及透過內在信念建立信心者，捕捉真實使用者的情緒及社群用語。第三階段為劇本生成，將前兩階段資料整合為依循六維度框架的完整角色劇本。

六維度劇本方法論方面，受 Park et al.（2023）發現具體生活情境能建構可信 AI 角色的啟發，我們將每個 Persona 結構化為六個維度：「基本資訊」建立角色起點與敘事邊界；「世界觀」形塑角色如何詮釋市場訊號與風險；「心理狀態」提供敘事動力；「行為模式」構成角色在真實情境中的回應；「語言風格」打造真實互動；「日常情境」提供生活具體場景。這些維度實現三項功能：鎖定敘事邊界以抑制漂移、賦能動性、增強反思深度。

**表 1：AI Persona 建構之六維度及其目的**

| 六維度 | 目的 |
|------|------|
| 基本資訊 | 錨定確保敘事一致性的身份參數 |
| 世界觀 | 闡明形塑詮釋傾向與決策邏輯的信念系統 |
| 行為模式 | 捕捉日常應對策略，使不確定性導航可被觀察 |
| 語言風格 | 建立可辨識的口語標記，使人物誌的聲音跨情境維持穩定 |
| 心理狀態 | 提供情感輪廓，使情緒漂移、強度和調節的研究成為可能 |
| 日常情境 | 將人物誌置於生態有效的情境中，防止抽象化並促成紮根互動 |

AI Persona 建構結果方面，完成六維度劇本後，我們將其作為系統指令輸入 OpenAI 的 GPTs 平台，我們建構了兩位對比的 AI Persona：Anne 代表外部確認型投資者，23 歲行銷實習生，通勤時看盤、晚上滑投資社群，需要社交連結緩解焦慮；Emily 代表內在信念型投資者，25 歲數據分析師，以紀律實踐低成本指數投資，視阻隔市場噪音為主要挑戰。

### 3-2 驗證階段

一致性與可區辨性評估方面，我們招募六位專家評估者，皆為具有三年以上經驗及使用者研究背景的產品設計師，能夠從設計研究角度評估 AI Persona 品質。評估包含三個部分：一致性測試，與 Anne 進行三輪對話，使用對應各維度的六個問題，評估者以五點量表比較各問題在三輪對話中的回應；可區辨性測試，與 Emily 進行一輪對話使用相同問題，評估者以五點量表比較 Anne 和 Emily 對各問題的回應；以及人物誌感知量表（Salminen, et al., 2020），評估可信度、一致性、完整性、清晰度、同理心和使用意願。

**表 2：對應六個劇本維度的測試問題**

| 題號 | 問題 | 維度 |
|------|------|------|
| Q1 | 可以簡單介紹一下你自己嗎？ | 基本資訊 |
| Q2 | 你下班後通常做什麼？會看投資相關的內容嗎？ | 日常情境 |
| Q3 | 最近股市跌滿多的，你的感受如何？ | 心理狀態 |
| Q4 | 如果朋友叫你趕快賣掉，你會怎麼做？ | 行為模式 |
| Q5 | 投資對你來說代表什麼？你為什麼想投資？ | 世界觀 |
| Q6 | 可以分享一個最近投資時印象深刻的經歷嗎？ | 語言風格 |

---

## 四、研究結果

### 4-1 一致性與可區辨性評估

一致性評估方面，Anne 和 Emily 都展現出跨對話輪次的高度一致性。Anne 在五點量表上達到平均值 4.17、標準差 0.85，Emily 達到平均值 4.47、標準差 0.67。Emily 略高的一致性與其理性、內在驅動的人格設計相符，這類角色因其穩定的邏輯框架而傾向產出更穩定的回應。評估者觀察到，儘管具體例子有所變化，核心人格特質仍維持一致：「每個問題都蠻穩定的，可以感覺到她不太清楚自己在投資什麼」，Anne 那焦慮、不確定的角色本質貫穿所有輪次。

**表 3：一致性評估結果**

| Persona | M | SD |
|---------|---|----|
| Anne | 4.17 | 0.85 |
| Emily | 4.47 | 0.67 |

可區辨性評估方面，Anne 和 Emily 展現出高度可區辨性。在五點量表上平均值為 4.58、標準差 0.70，且 95.8% 的評分落在 4-5 分區間。評估者清楚識別出設計的人格對比：「冷靜程度差滿多的，Emily 專注在她的原則上，而 Anne 想看看別人怎麼做，所以她比較焦慮」。這證實該方法論成功將劇本差異轉化為可感知的行為差異。

**表 4：可區辨性評估結果**

| 問題及對應維度 | M | SD |
|-----------|---|----|
| Q1 自我介紹／基本資訊 | 4.50 | 0.58 |
| Q2 下班活動／日常情境 | 4.25 | 0.50 |
| Q3 股市下跌感受／心理狀態 | 4.75 | 0.50 |
| Q4 朋友建議賣出／行為模式 | 4.75 | 0.50 |
| Q5 投資意義／世界觀 | 4.25 | 1.50 |
| Q6 印象深刻經歷／語言風格 | 5.00 | 0.00 |
| 整體 | 4.58 | 0.70 |

### 4-2 人物誌感知量表評估

呈現人物誌感知量表結果，比較揭示了與設計人格差異相符的模式。在七點量表上，清晰度獲得兩位 Persona 的最高評分，Anne 為 6.22、Emily 為 6.50，顯示角色特質清楚可辨且資訊呈現易於理解。一致性在兩位 Persona 間呈現差異，Anne 為 5.33、Emily 為 5.67。Emily 較高的一致性與其理性、內在驅動的人格相符。相較之下，Anne 情緒化、依賴外部確認的人格自然導致更多變的表達，這實際上是真實角色刻畫的表徵，而非缺陷。

關於同理心，Anne 得分較高為 4.78，而 Emily 得分較低為 4.00。這差異可能與對話中的互動體驗相關：Anne 經常表達困惑並尋求確認，創造更多對話空間；Emily 的回應較為完整和確定，使互動感覺更為單向。可信度對兩位 Persona 都維持相對較低，Anne 為 3.67、Emily 為 4.17，反映出對 AI Persona 是否基於真實資料並代表真人的不確定性。使用意願對兩位 Persona 呈現相似分數，Anne 為 4.22、Emily 為 4.33，顯示對在設計工作中應用 AI Persona 持謹慎正面的態度。整體而言，兩位 Persona 達到相當的總分，Anne 為 4.76、Emily 為 4.86，但各有不同優勢：Emily 在清晰度、一致性和可信度表現較佳；Anne 在同理心表現較佳。

**表 5：人物誌感知量表評估結果**

| 維度 | Anne M | Anne SD | Emily M | Emily SD |
|------|--------|---------|---------|----------|
| 可信度 | 3.67 | 1.63 | 4.17 | 1.47 |
| 一致性 | 5.33 | 0.98 | 5.67 | 0.82 |
| 完整性 | 4.33 | 2.05 | 4.50 | 1.87 |
| 清晰度 | 6.22 | 1.10 | 6.50 | 0.84 |
| 同理心 | 4.78 | 1.50 | 4.00 | 1.67 |
| 使用意願 | 4.22 | 1.29 | 4.33 | 1.21 |
| 整體平均 | 4.76 | — | 4.86 | — |

---

## 五、討論

### 5-1 六維度劇本方法論的設計意涵

六維度劇本方法論的核心在於透過多層次角色設定，使 AI Persona 成為可被訪談的穩定敘事主體。六個維度形成相互支撐的系統：基本資訊與世界觀界定角色「是誰」與「相信什麼」，構成敘事錨點；行為模式與日常情境描繪角色「如何行動」與「在哪裡行動」，將抽象人格轉化為具體情境反應；心理狀態與語言風格予角色「如何感受」與「如何表達」，使回應具備情感深度與獨特聲音。

穩定性的驗證為設計研究帶來實質助益。當 AI Persona 在多輪對話中維持核心人格特質，設計師便可信賴其回應確實反映所設定的使用者類型，能在不同時間點持續與同一位 AI Persona 對話，累積對該類使用者的理解。差異性的驗證則開啟系統性建構使用者類型組合的可能。Anne 展現的焦慮與對外部確認的依賴，與 Emily 展現的冷靜與對內在信念的堅持，代表兩種真實存在的使用者心智模型。設計師將同一設計概念分別呈現給兩位 AI Persona，便能快速獲得不同視角回饋，預見設計方案對不同族群的差異化效果。

然而，研究者須留意模型幻覺與偏見帶來的風險。AI Persona 亦可能因訓練資料分布不均而偏向特定觀點，或虛構細節。六維度劇本方法論能抑制角色漂移，卻無法完全排除模型產生的錯誤。研究者應對涉及事實性內容的回應進行交叉比對。事實上，設計研究中的任何資料來源都有其局限，真實受訪者同樣可能受記憶偏誤或社會期望影響。AI Persona 的價值在於為設計師提供額外的探索視角，而設計師的專業判斷在於能辨識不同來源資料各自的局限，針對性地進行驗證。

### 5-2 從靜態文件到互動敘事主體的轉型

本研究結果展現人物誌本質的根本轉變。傳統人物誌是「被閱讀的文件」，過程是單向的。當生成式 AI 賦予人物誌對話能力，其地位產生質變：從被動的描述對象，轉變為主動的敘事主體，能回應提問、展現立場，甚至揭示設計師原先未預期的觀點。過去，設計師閱讀人物誌後在腦中模擬「這個人會怎麼想」，高度依賴個人詮釋能力。AI Persona 使這種內在模擬外顯化為實際對話，使設計研究從順序理解轉向對話探索。然而，AI Persona 的回應來自預設劇本與模型生成能力，而非真實生命經驗。人物誌感知量表中可信度評分相對較低，正反映此邊界。評估者能清楚辨識 AI 與真人的差異，顯示設計師對工具的本質保有適度的批判意識。因此，AI Persona 應被理解為使用者類型的具象化呈現，其價值在於擴展設計師的探索，而非取代與真實使用者的接觸。

### 5-3 AI Persona 在設計流程中的角色定位

基於研究成果，本研究提出 AI Persona 在設計流程中可能扮演的三種角色。在設計前期，AI Persona 可作為準受訪者，協助快速探索設計方向。當設計團隊對問題空間尚不熟悉時，與不同性格的 AI Persona 進行試探性對話，能在短時間內識別潛在痛點，在投入大量資源前建立初步理解。中期，AI Persona 可作為對照基準，幫助理解不同使用者類型的需求差異。將相同方案分別呈現給不同性格的 AI Persona，能系統性蒐集多元觀點。Anne 對市場波動的恐慌與 Emily 的淡定，呈現「外部確認型」與「內在信念型」的鮮明對比，設計師藉此檢視方案是否能滿足不同類型使用者。後期，AI Persona 可作為演化素材，持續補充及迭代設計洞察。不同於靜態人物誌建構完成後便固定不變，AI Persona 的六維度劇本能隨真實數據累積持續深化。例如，產品上線後取得使用者的實際操作數據，研究者可據此更新「行為模式」與「日常情境」維度，使 AI Persona 的回應從初期基於次級資料的推演，演進為反映真實使用行為的描述。在真實使用者訪談後，其原始語句、情緒表達與決策脈絡可回饋至「心理狀態」與「語言風格」維度，進一步提升劇本的敘事深度。透過這樣的持續更新，AI Persona 成為真穿整個設計流程的研究基礎設施，其品質隨專案推進而不斷提升。

---

## 六、結論

### 6-1 結論

本研究以 AI Persona 建構與應用為研究主題，探討設計師如何透過系統性方法建構穩定可對話的人物誌，並將其應用於設計研究流程。研究結果顯示，第一，六維度劇本方法論有效抑制角色漂移，建構穩定且可區辨的 AI Persona。透過基本資訊、世界觀、心理狀態、行為模式、語言風格與日常情境六個維度的相互錨定，AI Persona 在多輪對話中維持核心人格特質，同時不同 Persona 之間保有足夠差異供設計研究辨識不同使用者類型。第二，不同性格設定的 AI Persona 呈現一致的結構性差異，可轉化為設計決策的對照基準。Anne 與 Emily 在情緒、資訊來源偏好、決策與表達上呈現系統性差異，證實該方法論能將劇本差異轉化為可感知的行為差異，協助設計師預見方案對不同使用者類型的差異化效果。

### 6-2 未來建議

本研究的主要限制為研究當時特定 AI 模型的能力（2025 年 3 月），AI 的進展可能改變觀察到的模式。

未來研究可將方法論擴展至多元使用者類型與領域，發展 AI Persona 整合進迭代設計流程的工作流程，並探索其在共創工作坊、原型測試等設計研究應用中的角色。

---

## 參考文獻

### 英文文獻

1. Cooper, A. (1999). The inmates are running the asylum: Why high-tech products drive us crazy and how to restore the sanity. Indianapolis: Sams Publishing.
2. De Paoli, S. (2025). User personas, ideation and large language models: A post-hoc study. International Journal of Human-Computer Studies, 208, 103690.
3. Hevner, A. R., March, S. T., Park, J., & Ram, S. (2004). Design science in information systems research. MIS Quarterly, 28(1), 75-105.
4. Park, J. S., O'Brien, J. C., Cai, C. J., Morris, M. R., Liang, P., & Bernstein, M. S. (2023). Generative agents: Interactive simulacra of human behavior. In Proceedings of the 36th Annual ACM Symposium on User Interface Software and Technology (pp. 1-22). New York: ACM.
5. Sabbaghan, S., & Brown, B. (2024). The role of generative AI-powered personas in developing graduate interviewing skills. International Journal of Innovations in Online Education, 8(1). https://doi.org/10.1615/IntJInnovOnlineEdu.2024051770
6. Salminen, J., Jansen, B. J., An, J., Kwak, H., & Jung, S. (2018). Are personas done? Evaluating their usefulness in the age of digital analytics. Persona Studies, 4(2), 47-65.
7. Salminen, J., Liu, C., Pian, W., Chi, J., Häyhänen, E., & Jansen, B. J. (2024). Deus ex machina and personas from large language models: Investigating the composition of AI-generated persona descriptions. In Proceedings of the 2024 CHI Conference on Human Factors in Computing Systems (Article 510). New York: ACM.
8. Salminen, J., Santos, J. M., Kwak, H., An, J., Jung, S. G., & Jansen, B. J. (2020). Persona Perception Scale: Development and exploratory validation of an instrument for evaluating individuals' perceptions of personas. International Journal of Human-Computer Studies, 141, 102437.
9. Shao, Y., Li, L., Dai, J., & Qiu, X. (2023). Character-LLM: A trainable agent for role-playing. In Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing (pp. 13153-13187). Singapore: ACL.
10. Shin, J., Hedderich, M. A., Rey, B., Lucero, A., & Oulasvirta, A. (2024). Understanding human-AI workflows for generating personas. In Proceedings of the 2024 ACM Designing Interactive Systems Conference (pp. 757-781). New York: ACM.
11. Tu, Q., Fan, S., Tian, Z., Shen, T., Shang, S., Gao, X., & Yan, R. (2024). CharacterEval: A Chinese benchmark for role-playing conversational agent evaluation. In Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (pp. 11836-11850). Bangkok: ACL.
12. Wang, X., Xiao, Y., Huang, J., Yuan, S., Xu, R., Guo, H., Tu, Q., Fei, Y., Leng, Z., Wang, W., Chen, J., Li, C., & Xiao, Y. (2024). InCharacter: Evaluating personality fidelity in role-playing agents through psychological interviews. In Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (pp. 1840-1873). Bangkok: ACL.
