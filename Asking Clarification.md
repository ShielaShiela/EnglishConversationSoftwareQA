
## Part 5: Role Play Scenarios (10 minutes)
## 角色扮演场景 | 역할극 시나리오

### Scenario 1: Unclear Bug Report
**场景1：不清晰的缺陷报告 | 시나리오 1: 불명확한 버그 리포트**

**Situation:** A developer filed a bug report that says "The button doesn't work properly." You need to ask for more details.

**情境：** 开发人员提交了一份缺陷报告，说"按钮无法正常工作"。你需要询问更多细节。

**상황:** 개발자가 "버튼이 제대로 작동하지 않는다"는 버그 리포트를 제출했습니다. 더 자세한 내용을 물어봐야 합니다.

**Practice asking:**
- Which button specifically?
- What is the expected behavior?
- What actually happens when you click it?
- Can you provide steps to reproduce?

---

### Scenario 2: Ambiguous Requirement
**场景2：模糊的需求 | 시나리오 2: 모호한 요구사항**

**Situation:** The product manager says, "The search feature should be fast and show relevant results."

**情境：** 产品经理说："搜索功能应该快速并显示相关结果。"

**상황:** 제품 관리자가 "검색 기능은 빠르고 관련 결과를 보여줘야 한다"고 말합니다.

**Practice asking:**
- What does "fast" mean? (Under 2 seconds? 1 second?)
- How do we define "relevant"?
- What are the acceptance criteria?

---

### Scenario 3: Technical Explanation
**场景3：技术解释 | 시나리오 3: 기술적 설명**

**Situation:** During a sprint planning meeting, the tech lead explains a complex API integration, but you're not sure about the error handling requirements.

**情境：** 在冲刺计划会议中，技术负责人解释了一个复杂的API集成，但你不确定错误处理的要求。

**상황:** 스프린트 계획 회의에서 기술 리드가 복잡한 API 통합을 설명하는데, 에러 처리 요구사항이 확실하지 않습니다.

**Practice asking:**
- Could you elaborate on the error handling?
- What should happen if the API returns a timeout?
- Just to confirm, should we show a generic error message or specific ones?

---

## Part 6: Dialogue Practice (5 minutes)
## 对话练习 | 대화 연습

### Read and practice this dialogue:

**QA Tester (You):** Hi Sarah, I was reviewing the user story for the password reset feature, and I have a few questions.

**你（QA测试员）：** 嗨，Sarah，我在审查密码重置功能的用户故事，有几个问题想问。

**QA 테스터 (당신):** 안녕하세요 Sarah, 비밀번호 재설정 기능의 사용자 스토리를 검토하고 있는데, 몇 가지 질문이 있어요.

---

**Product Manager:** Sure, what would you like to know?

**产品经理：** 当然，你想知道什么？

**제품 관리자:** 네, 뭐가 궁금하세요?

---

**QA Tester:** The story says the reset link should expire "soon." Could you specify what "soon" means exactly?

**你：** 故事里说重置链接应该"很快"过期。您能具体说明"很快"到底是多久吗？

**QA 테스터:** 스토리에 재설정 링크가 "곧" 만료되어야 한다고 되어 있는데요. "곧"이 정확히 얼마인지 명시해 주시겠어요?

---

**Product Manager:** Good question. It should expire after 24 hours.

**产品经理：** 好问题。应该在24小时后过期。

**제품 관리자:** 좋은 질문이에요. 24시간 후에 만료되어야 해요.

---

**QA Tester:** Got it. And just to confirm, if a user requests multiple reset links, should the old ones become invalid?

**你：** 明白了。再确认一下，如果用户请求多个重置链接，旧的链接应该失效吗？

**QA 테스터:** 알겠습니다. 그리고 확인차 여쭤보는데, 사용자가 여러 개의 재설정 링크를 요청하면, 이전 것들은 무효화되어야 하나요?

---

**Product Manager:** Yes, only the most recent link should work.

**产品经理：** 是的，只有最新的链接应该有效。

**제품 관리자:** 네, 가장 최근 링크만 작동해야 해요.

---

**QA Tester:** Perfect. One more thing—could you elaborate on the error message when someone enters an unregistered email?

**你：** 好的。还有一件事——您能详细说明一下当用户输入未注册的邮箱时显示什么错误消息吗？

**QA 테스터:** 좋아요. 한 가지 더요—등록되지 않은 이메일을 입력했을 때 오류 메시지에 대해 좀 더 설명해 주시겠어요?

---

**Product Manager:** For security reasons, we should show the same message whether the email exists or not: "If this email is registered, you will receive a reset link."

**产品经理：** 出于安全考虑，无论邮箱是否存在，我们都应该显示相同的消息："如果此邮箱已注册，您将收到重置链接。"

**제품 관리자:** 보안상의 이유로, 이메일 존재 여부와 관계없이 같은 메시지를 보여줘야 해요: "이 이메일이 등록되어 있다면, 재설정 링크를 받으실 거예요."

---

**QA Tester:** That makes sense. Thank you for clarifying!

**你：** 这样说得通。谢谢您的澄清！

**QA 테스터:** 이해됐어요. 명확히 해주셔서 감사합니다!

---

## Homework / Self-Study 作业/自学 | 숙제/자습

1. **Write 5 clarification questions** you might ask about a feature you're currently testing.
   - 写出5个你可能会针对当前测试功能提出的澄清问题。
   - 현재 테스트 중인 기능에 대해 물어볼 수 있는 명확한 질문 5개를 작성하세요.

2. **Practice these phrases** in your next meeting and note how people respond.
   - 在下次会议中练习这些短语，并记录人们的反应。
   - 다음 미팅에서 이 표현들을 연습하고 사람들의 반응을 기록하세요.

3. **Record yourself** asking clarification questions and check your pronunciation.
   - 录下自己提出澄清问题的过程，并检查发音。
   - 명확한 질문을 하는 자신의 모습을 녹음하고 발음을 확인하세요.

---

## Quick Reference Card 快速参考卡 | 빠른 참조 카드

| When you... | Say... |
|-------------|--------|
| Don't understand | "Could you clarify...?" |
| Need more details | "Could you elaborate on...?" |
| Want to confirm | "Just to confirm, you mean...?" |
| Need specifics | "Could you be more specific about...?" |
| Missed something | "Sorry, could you repeat that?" |
| Want to verify | "Let me make sure I understand..." |
