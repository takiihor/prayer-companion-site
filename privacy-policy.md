---

layout: default
title: Privacy Policy
---

# 隱私政策 / Privacy Policy

## 中文（繁體）

**生效日期：2026-06-10**

本隱私政策說明「禱告同行 / Prayer Companion」（下稱「本應用程式」）如何收集、使用、儲存與刪除你的資料。發行者為 Taki Hor。

### 1. 我們收集哪些資料

**未登入使用時**

* 你的禱告內容、選擇的情緒標籤與草稿，**只儲存在你裝置本機**（AsyncStorage），不會上傳。

**登入（建立帳戶）後**

* **帳戶資料**：電郵地址；以及由電郵自動產生的顯示名稱。若你使用「使用 Apple 登入」，我們只會收到 Apple 提供給本應用程式的匿名 Apple 用戶識別碼與電郵（你可選擇讓 Apple 隱藏實際電郵）；若你使用「使用 Google 登入」，我們會收到你的 Google 帳戶電郵。
* **禱告資料**：你的禱告文字、選擇的標籤、系統偵測的情緒、AI 回應、收藏的經文、每日操練、以及你對回應的「有/沒有幫助」回饋。
* **牧養記憶（預設關閉）**：只有在你於「設定」中主動開啟時，本應用程式才會把你近期禱告整理成簡短摘要，以便讓日後的回應更貼近你的處境。你可以隨時在「設定」中檢視、刪除這些摘要，或整項關閉。
* **用量記錄**：每次 AI 請求的 token 用量（用於成本與濫用控制）。刪除帳戶後，這些記錄會與你的身分**去連結（匿名化）**。

我們**不收集**：位置、健康資料、財務資料、相片、通訊錄，也**不使用**第三方廣告或行為追蹤 SDK。

### 2. 你的禱告如何被處理（重要）

當你送出禱告時，禱告文字會經由我們的後端（Supabase Edge Function）傳送至**第三方 AI 服務「DeepSeek」**，以生成經文建議與牧養回應。傳送僅在伺服器端進行，目的僅限於產生你的回應。我們**不會**將你的禱告內容出售或用於廣告或模型訓練。

在送出前，本應用程式會在你的裝置上與伺服器端進行**危機關鍵字偵測**（例如自傷、暴力字眼），以便顯示危機求助資訊。這項偵測用於你的安全，不會用於其他用途。

### 3. 本應用程式的限制（重要）

本應用程式提供基於聖經的禱告陪伴，**不是**以下服務的替代品：

* 牧師、教會輔導、或屬靈導師
* 心理治療師、臨床輔導員、或精神科醫生
* 緊急危機服務或緊急醫療服務

若你或身邊的人有立即的安全風險，請撥打當地緊急服務（香港：999、台灣：119、中國：120）或危機熱線。本應用程式的回應基於聖經，不提供醫療或專業診斷意見。

### 4. 資料儲存與保留

* 登入用戶的資料儲存在 **Supabase**（我們的後端服務供應商）。
* 你可以隨時刪除個別禱告、收藏與記憶摘要。
* 資料會保留至你刪除它、或刪除帳戶為止。

### 5. 刪除你的資料 / 帳戶

* 在「設定 → 本機資料 → 清除本機資料」可清除裝置上的草稿、紀錄與收藏。
* 在「設定 → 帳戶 → 刪除帳戶」可**永久刪除你的帳戶及所有同步到雲端的資料**（禱告、回應、收藏、操練、回饋、記憶摘要）。此動作無法復原；用量記錄會被匿名化。

### 6. 安全

所有與後端的通訊都使用 HTTPS 加密傳輸。資料庫以列級安全（Row Level Security）限制，確保每位用戶只能存取自己的資料。

### 7. 兒童

本應用程式並非以 13 歲以下兒童為對象，我們不會在知情下收集其個人資料。

### 8. 第三方服務（子處理者）

* **Supabase** — 帳戶驗證、資料庫與後端託管。
* **DeepSeek** — 生成 AI 回應所需的語言模型處理。
* **Apple（Sign in with Apple）** — 僅在 iOS 上以 Apple 帳戶登入時使用。Apple 不會因此收到你的禱告內容。
* **Google（Sign in with Google）** — 僅在以 Google 帳戶登入時使用。Google 不會因此收到你的禱告內容。

### 9. 你的權利

你可以隨時存取、更正或刪除你的資料（透過應用程式內的功能），或就隱私問題聯絡我們。

### 10. 政策更新

我們可能更新本政策；重大變更會在此頁面更新生效日期。

### 11. 聯絡我們

如有任何隱私相關問題，請電郵：[takii.hor@gmail.com](mailto:takii.hor@gmail.com)

---

## English

**Effective date: 2026-06-10**

This Privacy Policy explains how "禱告同行 / Prayer Companion" (the "App"), published by Taki Hor, collects, uses, stores, and deletes your information.

### 1. What we collect

**When used without signing in**

* Your prayer text, selected emotion tags, and drafts are stored **only on your device** (AsyncStorage) and are not uploaded.

**When signed in (with an account)**

* **Account data:** your email address, and a display name auto-derived from your email. If you sign in with Apple, we receive only the anonymous Apple user identifier and the email Apple provides (you may choose to have Apple hide your real email). If you sign in with Google, we receive your Google account email.
* **Prayer data:** your prayer text, selected tags, detected emotions, AI responses, saved verses, daily tasks, and your "helpful / not helpful" feedback on responses.
* **Pastoral memory (off by default):** only if you explicitly enable it in Settings, the App summarizes your recent prayers into short notes to make future responses more contextually relevant. You can view, delete, or disable this feature in Settings at any time.
* **Usage records:** token usage per AI request (for cost and abuse control). When you delete your account, these records are **de-linked from your identity (anonymized).**

We do **not** collect location, health, financial data, photos, or contacts, and we use **no** third-party advertising or behavioral tracking SDKs.

### 2. How your prayers are processed (important)

When you submit a prayer, the prayer text is sent through our backend (a Supabase Edge Function) to a **third-party AI service, "DeepSeek,"** to generate Scripture suggestions and a pastoral response. This happens server-side only and solely to produce your response. We do **not** sell your prayers or use them for advertising or model training.

Before submission, the App performs **crisis keyword detection** (e.g., self-harm or violence terms) on your device and on the server, so it can show you support resources. This is used for your safety only and for no other purpose.

### 3. Limitations of this App (important)

This App provides Bible-based prayer companionship. It is **not** a replacement for:

* Pastors, church counselors, or spiritual directors
* Licensed therapists, clinical counselors, or psychiatrists
* Emergency or crisis services

If you or someone nearby is in immediate danger, contact your local emergency services (e.g., 911, 999, 112) or a crisis helpline. In the US, you can call or text **988** (Suicide and Crisis Lifeline). In the UK, call **116 123** (Samaritans). The App's responses are Scripture-based and do not constitute medical or professional advice.

### 4. Storage and retention

* Signed-in users' data is stored with **Supabase**, our backend provider.
* You can delete individual prayers, saved verses, and memory notes at any time.
* Data is retained until you delete it or delete your account.

### 5. Deleting your data / account

* **Settings → Local data → Clear local data** removes drafts, prayer history, and saved verses on the device.
* **Settings → Account → Delete account** **permanently deletes your account and all cloud-synced data** (prayers, responses, saved verses, tasks, feedback, memory notes). This cannot be undone; usage records are anonymized.

### 6. Security

All communication with the backend uses HTTPS encryption in transit. The database uses Row Level Security so each user can access only their own data.

### 7. Children

The App is not directed to children under 13, and we do not knowingly collect their personal information.

### 8. Third-party services (sub-processors)

* **Supabase** — authentication, database, and backend hosting.
* **DeepSeek** — language-model processing to generate AI responses.
* **Apple (Sign in with Apple)** — used only when signing in with an Apple account on iOS. Apple does not receive your prayer content.
* **Google (Sign in with Google)** — used only when signing in with a Google account. Google does not receive your prayer content.

### 9. Your rights

You may access, correct, or delete your data at any time (via in-app features), or contact us with privacy questions.

### 10. Changes to this policy

We may update this policy; material changes will be reflected by updating the effective date on this page.

### 11. Contact

For any privacy questions, email: [takii.hor@gmail.com](mailto:takii.hor@gmail.com)
