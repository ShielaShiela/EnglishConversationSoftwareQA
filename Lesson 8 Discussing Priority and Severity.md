# 🧪 Discussing Priority & Severity in QA  
# 🧪 在軟體測試中討論 Priority（優先順序）與 Severity（嚴重程度）

---

## 🎯 Learning Objectives 學習目標

By the end of this lesson, students will be able to:

- Explain the difference between **Priority** and **Severity**  
  解釋 Priority 與 Severity 的差別  
- Describe software bugs clearly  
  清楚描述軟體錯誤  
- Discuss urgency professionally in meetings  
  在會議中專業討論錯誤急迫性  
- Practice QA-related conversational English  
  練習 QA 相關英語口說  

---

# 🔥 Severity vs Priority  
# 🔥 Severity 與 Priority 的差別

| Term | Definition | 中文說明 |
|------|------------|----------|
| **Severity** | How serious the bug is technically | 技術上錯誤的嚴重程度 |
| **Priority** | How urgent the bug needs to be fixed | 修復的急迫性 |

## 💡 Key Concept 重點觀念

A bug can be:

- High severity but low priority（嚴重但不急）
- Low severity but high priority（不嚴重但很急）

---

# 🚨 High Priority Bug Examples  
# 🚨 高優先順序錯誤範例

## Example 1 – Payment Failure  
### 範例一：付款失敗

- Users cannot complete credit card payment.  
  使用者無法完成信用卡付款  
- Severity: Critical  
- Priority: High  
- Business Impact: Revenue loss  

---

## Example 2 – Login Not Working  
### 範例二：登入失敗

- Users cannot log in after update.  
  更新後使用者無法登入  
- Severity: Critical  
- Priority: High  
- Business Impact: All users locked out  

---

## Example 3 – Homepage Typo  
### 範例三：首頁拼字錯誤

- “Welcom” instead of “Welcome”  
- Severity: Low  
- Priority: Medium (or High during campaign)  

---

# 📖 Scenario Practice  
# 📖 情境練習

## E-commerce Release Day  
## 電商系統上線日

QA found:

1. Login failure（登入失敗）
2. Coupon not applied（折扣券無法使用）
3. Product image misaligned（圖片位置跑掉）
4. Admin dashboard crash（後台當機）

### Discussion Questions 討論問題

- Which bug is most severe?  
- Which bug should be fixed first?  
- Can we release with these bugs?  

---

# 🎭 Dialogue Practice  
# 🎭 會議對話練習

### Sample Meeting Conversation 會議對話範例

**QA:**  
I found a critical issue in the checkout module.  
我在結帳模組發現一個關鍵問題。

**PM:**  
How severe is it?  
嚴重程度如何？

**QA:**  
It blocks users from completing payment. The severity is critical.  
這會阻止使用者完成付款，因此嚴重程度是關鍵。

**Developer:**  
Is it reproducible?  
可以重現嗎？

**QA:**  
Yes, it happens every time using Visa.  
是的，每次使用 Visa 都會發生。

**PM:**  
Let’s prioritize this immediately.  
我們要立即處理這個問題。

---

# 🗣 Speaking Practice Questions  
# 🗣 口說練習問題

1. What is the difference between severity and priority?  
2. Who decides priority in your company?  
3. Can priority change over time?  
4. How would you explain a critical bug in English?  

---

# 🧾 Mock Jira Bug Tickets  
# 🧾 Jira 模擬錯誤單範例

---

## 🐞 BUG-101: Payment Failure on Checkout

### Basic Information 基本資訊

- Issue Type: Bug  
- Project: E-Commerce Web App  
- Reporter: QA Team  
- Assignee: Backend Developer  
- Priority: High  
- Severity: Critical  
- Status: Open  
- Environment: Production  

### Description 描述

Users cannot complete checkout when selecting Visa as payment method.  
使用 Visa 付款時無法完成結帳。

### Steps to Reproduce 重現步驟

1. Add product to cart  
2. Proceed to checkout  
3. Select Visa  
4. Click "Confirm Payment"

### Expected Result 預期結果

Payment should be processed successfully.

### Actual Result 實際結果

Error message: "Transaction Failed"

### Business Impact 商業影響

Revenue loss and customer dissatisfaction.

---

## 🐞 BUG-102: Coupon Code Not Applied

### Basic Information 基本資訊

- Issue Type: Bug  
- Priority: High  
- Severity: Major  
- Status: Open  
- Environment: Production  

### Description 描述

The coupon code "NEWYEAR20" does not apply discount.  
折扣碼無法套用。

### Steps to Reproduce 重現步驟

1. Add product to cart  
2. Enter coupon code  
3. Click apply  

### Expected Result 預期結果

20% discount applied.

### Actual Result 實際結果

No discount applied.

### Business Impact 商業影響

Marketing campaign affected.

---

## 🐞 BUG-103: Homepage Typo

### Basic Information 基本資訊

- Issue Type: Bug  
- Priority: Medium  
- Severity: Low  
- Status: Open  
- Environment: Production  

### Description 描述

The banner displays "Welcom" instead of "Welcome."  
首頁橫幅拼字錯誤。

### Business Impact 商業影響

Brand image affected.

---

## 🐞 BUG-104: Admin Dashboard Crash

### Basic Information 基本資訊

- Issue Type: Bug  
- Priority: High  
- Severity: Critical  
- Status: Open  
- Environment: Staging & Production  

### Steps to Reproduce 重現步驟

1. Login as Admin  
2. Navigate to Reports  
3. Click Export (CSV)  

### Expected Result 預期結果

Report downloads successfully.

### Actual Result 實際結果

System crashes.

### Business Impact 商業影響

Internal operations blocked.

---

# 🎯 Homework 作業

Write your own bug ticket including:

- Summary  
- Severity  
- Priority  
- Steps to reproduce  
- Expected vs Actual result  
- Business impact  
