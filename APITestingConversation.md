# ESL Dialogue: API Testing Using Postman
## 软件测试英语对话 | 소프트웨어 테스팅 영어 대화

---

### Scene: Two QA engineers discussing API testing during a team meeting
**场景：两位QA工程师在团队会议中讨论API测试**
**장면: 두 명의 QA 엔지니어가 팀 미팅에서 API 테스팅을 논의하고 있다**

---

**Alex:** Hey Sarah, have you started testing the new user authentication API?

**Alex:** 嘿，Sarah，你开始测试新的用户认证API了吗？

**Alex:** 이봐 Sarah, 새로운 사용자 인증 API 테스트 시작했어?

---

**Sarah:** Yes, I've been using Postman to send requests. I created a new collection for all the authentication endpoints.

**Sarah:** 是的，我一直在用Postman发送请求。我为所有认证端点创建了一个新的集合。

**Sarah:** 응, Postman으로 요청을 보내고 있어. 모든 인증 엔드포인트를 위한 새 컬렉션을 만들었어.

---

**Alex:** That's great. Did you set up environment variables for the base URL?

**Alex:** 太好了。你为基础URL设置环境变量了吗？

**Alex:** 좋아. 기본 URL에 대한 환경 변수는 설정했어?

---

**Sarah:** Of course. I have separate environments for development, staging, and production. It makes switching between servers much easier.

**Sarah:** 当然。我为开发、预发布和生产环境分别设置了不同的环境。这样在服务器之间切换就容易多了。

**Sarah:** 물론이지. 개발, 스테이징, 프로덕션 환경을 따로 만들어뒀어. 서버 간 전환이 훨씬 쉬워졌어.

---

**Alex:** What status code did you get for the login endpoint?

**Alex:** 登录端点返回了什么状态码？

**Alex:** 로그인 엔드포인트에서 어떤 상태 코드를 받았어?

---

**Sarah:** For valid credentials, I received a 200 OK with a JSON response containing the access token. But when I tested with wrong passwords, it correctly returned a 401 Unauthorized.

**Sarah:** 对于有效的凭据，我收到了200 OK，JSON响应中包含访问令牌。但当我用错误密码测试时，它正确地返回了401未授权。

**Sarah:** 유효한 자격 증명으로는 액세스 토큰이 포함된 JSON 응답과 함께 200 OK를 받았어. 그런데 잘못된 비밀번호로 테스트했을 때는 401 Unauthorized가 정확히 반환됐어.

---

**Alex:** Did you write any test scripts in the Tests tab?

**Alex:** 你在Tests标签页里写了测试脚本吗？

**Alex:** Tests 탭에 테스트 스크립트 작성했어?

---

**Sarah:** Yes, I added assertions to verify the response time is under 500 milliseconds and that the token field exists in the response body.

**Sarah:** 是的，我添加了断言来验证响应时间在500毫秒以内，以及响应体中存在token字段。

**Sarah:** 응, 응답 시간이 500밀리초 이내인지, 그리고 응답 본문에 토큰 필드가 존재하는지 검증하는 어설션을 추가했어.

---

**Alex:** Perfect. Can you show me how you handle the bearer token for authenticated requests?

**Alex:** 太好了。你能演示一下如何处理需要认证的请求的bearer token吗？

**Alex:** 완벽해. 인증된 요청에 대한 bearer 토큰을 어떻게 처리하는지 보여줄 수 있어?

---

**Sarah:** Sure. In the pre-request script, I extract the token from the login response and store it as a collection variable. Then in the Authorization tab, I select "Bearer Token" and reference that variable.

**Sarah:** 当然。在预请求脚本中，我从登录响应中提取token并将其存储为集合变量。然后在Authorization标签页中，我选择"Bearer Token"并引用那个变量。

**Sarah:** 물론이지. pre-request 스크립트에서 로그인 응답에서 토큰을 추출해서 컬렉션 변수로 저장해. 그런 다음 Authorization 탭에서 "Bearer Token"을 선택하고 그 변수를 참조해.

---

**Alex:** That's a smart approach. Have you encountered any bugs so far?

**Alex:** 这是个聪明的方法。到目前为止你发现任何bug了吗？

**Alex:** 영리한 방법이네. 지금까지 버그를 발견했어?

---

**Sarah:** Actually, yes. I found that the API doesn't validate the email format properly. It accepts strings without the @ symbol, which should trigger a 400 Bad Request.

**Sarah:** 实际上，是的。我发现API没有正确验证邮箱格式。它接受没有@符号的字符串，这应该触发400错误请求。

**Sarah:** 사실, 응. API가 이메일 형식을 제대로 검증하지 않는 걸 발견했어. @ 기호가 없는 문자열도 받아들이는데, 이건 400 Bad Request를 반환해야 해.

---

**Alex:** Good catch! Did you log it in the bug tracking system?

**Alex:** 发现得好！你在缺陷跟踪系统里记录了吗？

**Alex:** 잘 찾았어! 버그 추적 시스템에 기록했어?

---

**Sarah:** Yes, I attached the Postman request and response as evidence. I also exported the collection so the developer can reproduce the issue easily.

**Sarah:** 是的，我附上了Postman的请求和响应作为证据。我还导出了集合，这样开发人员可以轻松重现这个问题。

**Sarah:** 응, Postman 요청과 응답을 증거로 첨부했어. 컬렉션도 내보내서 개발자가 문제를 쉽게 재현할 수 있게 했어.

---

## Key Vocabulary | 重要词汇 | 주요 어휘

| English | 中文 | 한국어 |
|---------|------|--------|
| API endpoint | API端点 | API 엔드포인트 |
| HTTP request | HTTP请求 | HTTP 요청 |
| Status code | 状态码 | 상태 코드 |
| Environment variable | 环境变量 | 환경 변수 |
| Access token | 访问令牌 | 액세스 토큰 |
| Assertion | 断言 | 어설션 |
| Response body | 响应体 | 응답 본문 |
| Pre-request script | 预请求脚本 | pre-request 스크립트 |
| Collection | 集合 | 컬렉션 |
| Bearer token | 持有者令牌 | bearer 토큰 |
| Bug tracking | 缺陷跟踪 | 버그 추적 |
| Reproduce | 重现 | 재현하다 |

---

## Practice Questions | 练习问题 | 연습 문제

1. What tool are they using for API testing?
   他们用什么工具进行API测试？
   그들은 API 테스팅에 어떤 도구를 사용하고 있나요?

2. What status code indicates successful authentication?
   什么状态码表示认证成功？
   인증 성공을 나타내는 상태 코드는 무엇인가요?

3. What bug did Sarah find in the API?
   Sarah发现了什么bug？
   Sarah가 API에서 어떤 버그를 발견했나요?

4. How does Sarah handle the bearer token between requests?
   Sarah如何在请求之间处理bearer token？
   Sarah는 요청 간에 bearer 토큰을 어떻게 처리하나요?

---

## Speaking Practice Prompts | 口语练习 | 말하기 연습

*Try explaining these concepts to a partner:*

1. Describe how to create a new request in Postman.
2. Explain the difference between GET and POST methods.
3. Tell your partner about a bug you found during API testing.
4. Describe your testing workflow using Postman.
