# Lesson 4 Conversational English for Software QA: Bug Reports

## 课程概述 | 수업 개요 | Lesson Overview

**Duration:** 50 minutes  
**Level:** Intermediate  
**Topic:** Writing and Discussing Bug Reports in Software QA

---

## Part 1: Warm-up (5 minutes)

### Quick Discussion Questions

1. Have you ever reported a bug or problem with software?
2. What makes a good bug report?
3. What information do you think developers need to fix bugs?

---

## Part 2: Key Vocabulary (10 minutes)

### Essential Bug Report Terms

| English | 中文 (简体) | 한국어 |
|---------|------------|--------|
| Bug / Defect | 缺陷 / 错误 | 버그 / 결함 |
| Severity | 严重程度 | 심각도 |
| Priority | 优先级 | 우선순위 |
| Steps to reproduce | 重现步骤 | 재현 단계 |
| Expected result | 预期结果 | 예상 결과 |
| Actual result | 实际结果 | 실제 결과 |
| Environment | 环境 | 환경 |
| Crash | 崩溃 | 충돌 |
| Screenshot | 截图 | 스크린샷 |
| Workaround | 临时解决方案 | 임시 해결책 |
| Reproduce / Reproducible | 重现 / 可重现的 | 재현하다 / 재현 가능한 |
| Intermittent | 间歇性的 | 간헐적인 |
| Regression | 回归缺陷 | 회귀 결함 |
| Log file | 日志文件 | 로그 파일 |

### Severity Levels

| English | 中文 (简体) | 한국어 | Description |
|---------|------------|--------|-------------|
| Critical | 严重 | 치명적 | System crash, data loss | 系统崩溃，数据丢失 | 시스템 충돌, 데이터 손실 |
| High | 高 | 높음 | Major feature not working | 主要功能无法使用 | 주요 기능 작동 안 함 |
| Medium | 中 | 중간 | Minor feature issue | 次要功能问题 | 부차적 기능 문제 |
| Low | 低 | 낮음 | Cosmetic issue, typo | 外观问题，拼写错误 | 외관 문제, 오타 |

---

## Part 3: Dialogue Practice (15 minutes)

### Dialogue 1: Reporting a Bug to Your Team Lead

**QA Tester (Min-jun):** Hey Sarah, I found a critical bug in the checkout process.  
**QA测试员（民俊）：** 嘿，莎拉，我在结账流程中发现了一个严重的缺陷。  
**QA 테스터 (민준):** 안녕하세요 Sarah, 결제 프로세스에서 치명적인 버그를 발견했습니다.

**Team Lead (Sarah):** Oh no, what's happening?  
**团队负责人（莎拉）：** 哦不，发生了什么？  
**팀 리더 (Sarah):** 오, 무슨 일이죠?

**Min-jun:** When users click "Complete Purchase," the page freezes and nothing happens. I can reproduce it 100% of the time.  
**民俊：** 当用户点击"完成购买"时，页面会卡住，什么也不会发生。我可以百分之百重现这个问题。  
**민준:** 사용자가 "구매 완료"를 클릭하면 페이지가 멈추고 아무 일도 일어나지 않습니다. 100% 재현 가능합니다.

**Sarah:** That's definitely critical. Did you check the console for any error messages?  
**莎拉：** 这确实很严重。你检查控制台有没有错误消息吗？  
**Sarah:** 그건 확실히 치명적이네요. 콘솔에서 오류 메시지를 확인했나요?

**Min-jun:** Yes, there's a JavaScript error. I've attached the screenshot and log file to the bug ticket.  
**民俊：** 是的，有一个JavaScript错误。我已经把截图和日志文件附加到了缺陷工单上。  
**민준:** 네, JavaScript 오류가 있습니다. 버그 티켓에 스크린샷과 로그 파일을 첨부했습니다.

**Sarah:** Perfect. What's the ticket number? I'll escalate this to the dev team immediately.  
**莎拉：** 完美。工单号是多少？我会立即将此问题上报给开发团队。  
**Sarah:** 완벽합니다. 티켓 번호가 뭔가요? 바로 개발팀에 에스컬레이션하겠습니다.

**Min-jun:** It's BUG-1247. I also tested on different browsers - same issue on all of them.  
**民俊：** 是BUG-1247。我还在不同的浏览器上测试了，所有浏览器都有同样的问题。  
**민준:** BUG-1247입니다. 다른 브라우저에서도 테스트했는데, 모두 동일한 문제입니다.

---

### Dialogue 2: Developer Asking for More Information

**Developer (Li Wei):** Hi Alex, I'm looking at BUG-1305 about the login timeout. Can you provide more details?  
**开发人员（李伟）：** 嗨，亚历克斯，我正在查看关于登录超时的BUG-1305。你能提供更多细节吗？  
**개발자 (Li Wei):** 안녕하세요 Alex, 로그인 타임아웃에 관한 BUG-1305를 보고 있습니다. 더 자세한 정보를 주실 수 있나요?

**QA Tester (Alex):** Sure! What information do you need?  
**QA测试员（亚历克斯）：** 当然！你需要什么信息？  
**QA 테스터 (Alex):** 물론이죠! 어떤 정보가 필요하신가요?

**Li Wei:** Can you tell me the exact steps to reproduce this bug? I'm not seeing the timeout on my end.  
**李伟：** 你能告诉我重现这个缺陷的确切步骤吗？我这边没有看到超时。  
**Li Wei:** 이 버그를 재현하는 정확한 단계를 알려주실 수 있나요? 제 쪽에서는 타임아웃이 안 보입니다.

**Alex:** Let me walk you through it. First, clear your browser cache. Then go to the login page and wait exactly 15 minutes without doing anything.  
**亚历克斯：** 让我详细说明一下。首先，清除浏览器缓存。然后进入登录页面，什么都不做，等待整整15分钟。  
**Alex:** 자세히 설명해 드리겠습니다. 먼저 브라우저 캐시를 지우세요. 그런 다음 로그인 페이지로 가서 아무것도 하지 않고 정확히 15분을 기다리세요.

**Li Wei:** Okay, and then what happens?  
**李伟：** 好的，然后会发生什么？  
**Li Wei:** 알겠습니다, 그러면 어떻게 되나요?

**Alex:** After 15 minutes, if you try to enter credentials and click login, you get an error message saying "Session expired" but the session should still be active.  
**亚历克斯：** 15分钟后，如果你尝试输入凭据并点击登录，会得到一个错误消息说"会话已过期"，但会话应该仍然是活动的。  
**Alex:** 15분 후에 자격 증명을 입력하고 로그인을 클릭하면 "세션 만료" 오류 메시지가 나타나지만 세션은 여전히 활성 상태여야 합니다.

**Li Wei:** Got it! What browser and OS are you testing on?  
**李伟：** 明白了！你在什么浏览器和操作系统上测试的？  
**Li Wei:** 알겠습니다! 어떤 브라우저와 OS에서 테스트하셨나요?

**Alex:** Chrome version 120 on Windows 11. I also tested on Firefox and saw the same behavior.  
**亚历克斯：** Windows 11上的Chrome 120版本。我还在Firefox上测试了，看到了相同的行为。  
**Alex:** Windows 11의 Chrome 버전 120입니다. Firefox에서도 테스트했는데 동일한 현상이 나타났습니다.

**Li Wei:** Perfect, that helps a lot. I'll investigate and update the ticket once I find the root cause.  
**李伟：** 完美，这很有帮助。我会调查并在找到根本原因后更新工单。  
**Li Wei:** 완벽합니다, 큰 도움이 됩니다. 근본 원인을 찾으면 티켓을 업데이트하겠습니다.

---

## Part 4: Useful Phrases (5 minutes)

### Reporting Bugs

| English | 中文 (简体) | 한국어 |
|---------|------------|--------|
| I found a bug in... | 我在...中发现了一个缺陷 | ...에서 버그를 발견했습니다 |
| This issue occurs when... | 这个问题发生在... | 이 문제는 ...할 때 발생합니다 |
| I can reproduce this consistently | 我可以持续重现这个问题 | 이것을 지속적으로 재현할 수 있습니다 |
| The expected behavior is... | 预期的行为是... | 예상되는 동작은... |
| Instead, what happens is... | 相反，实际发生的是... | 대신 일어나는 일은... |
| This is blocking our testing | 这阻碍了我们的测试 | 이것이 테스트를 막고 있습니다 |

### Asking for Clarification

| English | 中文 (简体) | 한국어 |
|---------|------------|--------|
| Can you provide more details? | 你能提供更多细节吗？ | 더 자세한 정보를 제공해 주실 수 있나요? |
| What are the steps to reproduce? | 重现步骤是什么？ | 재현 단계가 무엇인가요? |
| Is this happening on all devices? | 这在所有设备上都发生吗？ | 이것이 모든 기기에서 발생하나요? |
| Can you share a screenshot? | 你能分享一个截图吗？ | 스크린샷을 공유해 주실 수 있나요? |
| What version are you testing? | 你在测试什么版本？ | 어떤 버전을 테스트하고 계신가요? |

---

## Part 5: Role Play Activity (15 minutes)

### Scenario 1: Critical Bug Report
**角色扮演1：严重缺陷报告 | 역할극 1: 치명적 버그 보고**

**Student A (QA Tester):** You discovered that users cannot upload profile pictures. The upload button doesn't respond when clicked. This is a high-priority bug.

**学生A（QA测试员）：** 你发现用户无法上传个人资料图片。点击上传按钮时没有响应。这是一个高优先级缺陷。

**학생 A (QA 테스터):** 사용자가 프로필 사진을 업로드할 수 없다는 것을 발견했습니다. 업로드 버튼을 클릭해도 반응이 없습니다. 이것은 높은 우선순위 버그입니다.

**Student B (Team Lead):** Ask questions about:
- Which browsers were tested
- Can they reproduce it every time
- Any error messages in the console
- What file types they tried to upload

**学生B（团队负责人）：** 询问以下问题：
- 测试了哪些浏览器
- 他们能否每次都重现
- 控制台中有任何错误消息吗
- 他们尝试上传了什么文件类型

**학생 B (팀 리더):** 다음에 대해 질문하세요:
- 어떤 브라우저를 테스트했는지
- 매번 재현할 수 있는지
- 콘솔에 오류 메시지가 있는지
- 어떤 파일 유형을 업로드하려고 했는지

---

### Scenario 2: Following Up on a Bug
**角色扮演2：跟进缺陷 | 역할극 2: 버그 후속 조치**

**Student A (Developer):** You're working on BUG-982 about slow page loading. You need more information from the QA tester about network conditions and specific pages affected.

**学生A（开发人员）：** 你正在处理关于页面加载缓慢的BUG-982。你需要QA测试员提供更多关于网络条件和受影响的具体页面的信息。

**학생 A (개발자):** 페이지 로딩 속도 저하에 관한 BUG-982를 작업하고 있습니다. QA 테스터로부터 네트워크 상태와 영향받는 특정 페이지에 대한 더 많은 정보가 필요합니다.

**Student B (QA Tester):** Provide detailed information:
- You tested on a standard WiFi connection
- The homepage loads slowly (8+ seconds)
- Other pages load normally
- This started after the latest deployment

**学生B（QA测试员）：** 提供详细信息：
- 你在标准WiFi连接上测试
- 主页加载缓慢（8秒以上）
- 其他页面正常加载
- 这是在最新部署后开始的

**학생 B (QA 테스터):** 상세 정보 제공:
- 표준 WiFi 연결에서 테스트했습니다
- 홈페이지 로딩이 느립니다 (8초 이상)
- 다른 페이지는 정상적으로 로드됩니다
- 최신 배포 후 시작되었습니다

---

## Part 6: Writing Practice - Bug Report Template

### Complete Bug Report Structure
**完整的缺陷报告结构 | 완전한 버그 보고서 구조**

```
Title: [Short, clear description]
标题：[简短、清晰的描述]
제목: [짧고 명확한 설명]

Environment:
环境：
환경:
- OS: Windows 11 / macOS 13 / etc.
- Browser: Chrome 120 / Firefox 115 / etc.
- App Version: 2.5.3

Severity: Critical / High / Medium / Low
严重程度：严重/高/中/低
심각도: 치명적 / 높음 / 중간 / 낮음

Steps to Reproduce:
重现步骤：
재현 단계:
1. [First step]
2. [Second step]
3. [Third step]

Expected Result:
预期结果：
예상 결과:
[What should happen]
[应该发生什么]
[무엇이 발생해야 하는지]

Actual Result:
实际结果：
실제 결과:
[What actually happens]
[实际发生了什么]
[실제로 무엇이 발생하는지]

Additional Information:
附加信息：
추가 정보:
- Screenshots attached
- Log files attached
- Reproducible: Yes/No
- Frequency: Always / Sometimes / Rarely
```

---

## Homework / 作业 / 숙제

1. Write a complete bug report in English for a bug you've encountered (real or imagined)
   用英语写一份完整的缺陷报告，关于你遇到过的缺陷（真实的或想象的）
   실제 또는 가상의 버그에 대한 완전한 버그 보고서를 영어로 작성하세요

2. Practice the dialogues with a classmate
   与同学练习对话
   동료와 대화를 연습하세요

3. Research 5 more QA-related terms and create bilingual flashcards
   研究5个更多的QA相关术语并创建双语抽认卡
   QA 관련 용어 5개를 더 조사하고 이중 언어 플래시 카드를 만드세요

---

## Teacher Notes / 教师备注 / 교사 노트

- Encourage students to use the vocabulary naturally in sentences
- For role plays, allow 2-3 minutes preparation time
- Monitor pronunciation of technical terms like "reproducible" and "intermittent"
- Adapt scenarios based on students' actual work experience
- Consider bringing real bug report examples to show

---

**课程结束 | 수업 종료 | End of Lesson**
