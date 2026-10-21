# GPT代充 / ChatGPT Plus 国内充值指南（2026 年 10 月更新）

这是一份面向中文用户的 ChatGPT 付费会员说明：Plus、Pro 100 / 200 / 500 的官方美元价和区别，国内为什么直接付不了款，"代充（订阅代付）"怎么挑，以及付款被拒、付了钱还显示免费版、续费失败、被扣两次钱等问题的排查，报错部分按 OpenAI 官方帮助中心逐条整理并附官方链接。作者：瑶瑶ai训练师；更新于 2026-10-17。本仓库是非官方整理，与 OpenAI 没有隶属关系，文中品牌名仅用于说明。

**直接回答：** ChatGPT 官网只接受支持地区发行的银行卡等付款方式，国内银行卡、支付宝直接付不了。没有海外卡的人，常见做法是"代充"（订阅代付）：由卖家替你付款，把官方 Plus / Pro 订阅开到你自己的账号上。

**怎么选代充：** 看 6 点：价格正常、不要密码、到账时间说得清、失败怎么退、掉订阅管不管、售后找得到人。判断方法见下文。

**官方价格：** Free $0、Go $8/月、Plus $20/月、Pro 分 $100 / $200 / $500 三档，都只能按月付（2026-10-17 核对自 OpenAI 官方定价页和帮助中心，见下表）。

## 目录

- [使用前先读：关于地区](#使用前先读关于地区)
- [ChatGPT 官方价格表](#chatgpt-官方价格表2026-10-17-核对)
- [Plus 和 Pro 怎么选](#plus-和-pro-怎么选)
- [为什么国内开通 ChatGPT Plus 很难](#为什么国内开通-chatgpt-plus-很难)
- [几种开通方式对比](#几种开通方式对比)
- [怎么选代充的 6 个判断点](#怎么选代充的-6-个判断点)
- [报错 / 常见问题大全](#报错--常见问题大全)
- [降低被封风险的习惯](#降低被封风险的习惯)
- [常见问题](#常见问题)
- [国内开通参考](#国内开通参考)
- [更多教程](#更多教程)
- [关于本仓库和作者](#关于本仓库和作者)
- [参考资料](#参考资料)

## 使用前先读：关于地区

OpenAI 官方公布了支持的国家和地区列表（[Supported countries and territories](https://platform.openai.com/docs/supported-countries)），2026-10-17 查看：中国大陆、香港、澳门都不在列表中（台湾在列表中）。页面写明，在列表之外的地区访问或提供访问服务，账号可能被封禁或停用。本仓库只整理官方的价格、订阅和报错说明，不提供绕过地区限制或支付限制的方法；请在符合 OpenAI 使用条款的前提下使用。

## ChatGPT 官方价格表（2026-10-17 核对）

| 档位 | 官方价（美元） | 说明 |
|---|---|---|
| Free | $0 | 体验用，额度最少 |
| Go | $8/月 | 轻度使用；官方页面注明可能含广告 |
| Plus | $20/月 | 大多数每天用的人；Codex 额度按每 5 小时估算 |
| Pro 100 | $100/月 | Pro 三档里最低一档，不含 Ultrafast |
| Pro 200 | $200/月 | 用量高于 Pro 100，不含 Ultrafast |
| Pro 500 | $500/月 | 三档里用量最高，含 GPT-6 Astra / GPT-6.1 Sol 的 Ultrafast |
| Business / Enterprise | 定价页未直接标价，按每人每月计费；Enterprise 联系销售 | 团队、企业 |

来源：[OpenAI 定价页](https://openai.com/chatgpt/pricing/)（Free、Go、Plus 价格，Pro 显示"From $100"和"3 档用量供选择"）、[About ChatGPT Pro tiers](https://help.openai.com/en/articles/9793128-about-chatgpt-pro-tiers)（Pro 三档的价格和区别）、[What is ChatGPT Plus?](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)（Plus $20/月，按月计费）。价格和权益会变，以官方页面为准。

几点说明（都来自上面的官方页面）：

- Plus 和 Pro 只能按月付，官方写明不提供年付，也不能一次预付多个月。
- Pro 200 现在可以重新订阅，价格不变，但新订阅的用量额度比以前低。2026-09-22 到 09-29（太平洋时间上午 10 点）期间有有效 Pro 200 订阅的老用户，旧额度保留到 2026-10-29，之后也按新额度算。
- 会员和 API 分开计费，开了会员不等于有 API 额度。
- Codex：Plus 的额度按每 5 小时估算，Pro 目前没有 5 小时限制，两者都可能另有每周限制；额度用完可以另外买 credits，价格按套餐不同（[Codex 定价页](https://developers.openai.com/codex/pricing)）。

## Plus 和 Pro 怎么选

- 第一次开会员：先买 **Plus**。日常问答、写作、偶尔写代码够用。
- Plus 一周里好几天碰到上限，或者每天用 Codex 写几个小时代码：**Pro 100**。
- 几乎全天写代码、做研究：**Pro 200**；需要 Ultrafast 或者额度要求很高：**Pro 500**。
- 官方对三档只写"用量高低"，没有给倍数；网上说的"5X / 10X / 25X"是第三方说法，以官方为准。

更细的对比见 [ChatGPT Plus 和 Pro 有什么区别](https://kw.yaoyao.chat/guide/plus-vs-pro.html) 和 [ChatGPT Pro 100 / 200 / 500 怎么选](https://kw.yaoyao.chat/guide/chatgpt-pro.html)。

## 为什么国内开通 ChatGPT Plus 很难

- OpenAI 官方不面向中国大陆提供服务（见上面的地区说明），使用时要保持网络环境稳定。
- 官网结算一般只接受支持地区发行的银行卡，支付宝、银联卡付不了；国内发行的双币卡也经常被拒（card declined）。
- 账单地址和卡信息对不上、同一张卡反复尝试，会让付款越来越难通过。

## 几种开通方式对比

| 方式 | 优点 | 缺点 |
|---|---|---|
| 自己用海外卡订阅 | 官方价，自己掌控 | 国内的卡基本付不了，被拒很常见 |
| 虚拟信用卡 | 按官方价付款 | 开卡费、手续费、汇率差，经常被拒，平台有跑路风险 |
| 外区 Apple ID + 礼品卡 | 不用信用卡 | 要外区账号，步骤多，订阅由 App Store 管理 |
| 合租 / 拼车 | 单价低 | 通常违反服务条款，聊天记录不私密，额度被分走，容易被风控 |
| 代充（订阅代付） | 支付宝下单，不用自己的卡 | 要挑靠谱的卖家 |

## 怎么选代充的 6 个判断点

代充的本质是"别人替你付款，把订阅开到你自己的账号上"。各家页面看着差不多，真正的差别在这 6 件事。逐项判断方法见 [ChatGPT Plus 代充怎么选](https://kw.yaoyao.chat/guide/daichong-duibi.html)。

1. **价格是否正常。** 官方 Plus 是 $20/月，代充价是平台自己的定价，一般会比官方美元价折算后高一些（包含海外付款渠道成本和售后）。远低于官方美元价折算的（几十块一个月）要问清为什么，常见是退款单、漏洞单，订阅过几天会被收回。看清"起"字，服务费、发票费是否另算。
2. **要不要账号密码。** 不需要。靠谱的自助开通只让你复制一段登录信息，不要密码，不要转发手机或邮箱验证码，不要装软件或插件。要密码、要验证码、要关两步验证的，换一家。
3. **多久到账。** 问清是自助还是人工，页面上的到账时间有没有说明统计口径。只写"秒到"却不说明怎么统计的，只能当宣传语看。
4. **失败怎么退。** 付款前问清失败后钱或卡密怎么处理：自动退回还是要申请，重试有没有次数限制。
5. **掉订阅管不管。** 问清质保覆盖多久、掉了怎么处理（补开、补时长还是退款），要求对方用文字回复。
6. **售后找谁。** 有没有能联系到的真人、有没有订单查询入口、平台背后是谁、域名能不能在别处核实。

## 报错 / 常见问题大全

每条按"现象 → 原因 → 怎么处理"写，处理办法来自 OpenAI 官方帮助中心，并附官方链接；官方没写到的地方注明"以官方说明为准"。

### 1. 付款时提示"请核对账单信息后重试"（英文界面类似 Your card was declined）

- **现象：** 在 chatgpt.com 升级 Plus / Pro，填完卡点付款，页面提示"请核对账单信息后重试"，或者英文提示卡被拒。
- **原因：** 这是付款被拒后的统一提示。官方列出的常见原因：卡号、有效期、账单地址填错或和发卡行登记的不一致；银行出于安全原因拦截，或余额不足；你本人或发卡行所在地不在 OpenAI 支持地区（官方原话：如果任一方在支持地区之外，付款可能被拒）。官方页面没有逐字解释这条中文提示，以官方说明为准。
- **怎么处理：** 按官方建议：①核对卡号、有效期、账单地址，账单地址填发卡行登记的真实地址（见 [ChatGPT 订阅账单地址怎么填](https://kw.yaoyao.chat/guide/zhangdan-dizhi.html)）；②清除浏览器缓存和 Cookie 后再试一次；③联系银行，确认是否被拦截、余额是否足够；④确认你和发卡行都在支持地区；⑤都不行，用帮助中心右下角的聊天窗口联系 OpenAI 支持。不要短时间内反复点付款，连续被拒会更难通过。
- **官方出处：** [Why did my ChatGPT Plus or ChatGPT Pro renewal transaction fail?](https://help.openai.com/en/articles/7242622-why-did-my-chatgpt-plus-or-chatgpt-pro-renewal-transaction-fail)、[Supported countries and territories](https://platform.openai.com/docs/supported-countries)

### 2. 卡被拒（card declined）、国内银行卡 / 支付宝付不了

- **现象：** 国内发行的信用卡、借记卡、双币卡被拒；付款页没有支付宝等国内付款选项。
- **原因：** 官方定价页写明 Go / Plus / Pro / Business 接受主流信用卡；结算以支持地区为前提，国内发行的银联卡、支付宝不在范围内，双币卡也经常因为发卡行所在地被拒。
- **怎么处理：** 换支持地区发行的卡，或者改用代充（由卖家付款，会员开到你自己的账号）。更多情况见 [ChatGPT 充值银行卡不能用怎么办](https://kw.yaoyao.chat/guide/yinhangka.html) 和 [ChatGPT 可以用支付宝吗](https://kw.yaoyao.chat/guide/chatgpt-zhifubao.html)。
- **官方出处：** [OpenAI 定价页 FAQ](https://openai.com/chatgpt/pricing/)、[续费失败说明](https://help.openai.com/en/articles/7242622-why-did-my-chatgpt-plus-or-chatgpt-pro-renewal-transaction-fail)

### 3. 已有订阅，想升级到 Pro 或换档位，找不到入口 / 提示账号已有订阅

- **现象：** 账号已经是 Plus，想换成 Pro，或者 Pro 100 想换 Pro 200，页面没有想要的选项；在代充平台提交时提示"该账号已有订阅或近期付款记录"。
- **原因：** ChatGPT 的订阅由购买渠道管理：网页（chatgpt.com）、Apple App Store、Google Play 各自独立。官方说明：换方案要用现有账号，在 **Settings → My Plan** 查看当前订阅和可以切换的方案；在 App Store / Google Play 订阅的，网页上管不了，要先在对应商店处理。同一个账号在两个渠道各订一份，会重复扣费。代充平台的"已有订阅"类提示，一般是因为账号当前已有生效订阅或刚付过款，通道不会重复开通。
- **怎么处理：** 网页订阅：Settings → My Plan 看可用的升级 / 切换；App 内订阅：先在 App Store / Google Play 管理。降级或取消在当前账期结束时生效，期间可以撤回。
- **官方出处：** [About ChatGPT Pro tiers](https://help.openai.com/en/articles/9793128-about-chatgpt-pro-tiers)、[How do I avoid being charged twice](https://help.openai.com/en/articles/20001043-how-do-i-avoid-being-charged-twice-if-i-subscribe-to-chatgpt-on-ios-android-and-the-web)

### 4. Plus 到期了 / 续费扣款失败，账号变回免费版

- **现象：** 到了续费日没扣成功，收到付款失败邮件，账号变回 Free。
- **原因：** 官方说明续费偶尔会因为安全措施或支付方式本身的问题失败，常见是银行拦截、卡过期或余额不足、浏览器缓存干扰、你或发卡行不在支持地区。取消订阅或续费失败后，付费功能用到当前账期结束，之后回到免费版。
- **怎么处理：** 自己绑卡的：按官方建议清缓存、核对卡信息和账单地址、联系银行，然后在 Settings → Billing 重新订阅；代充开通的：不走你的银行卡，到期前重新下单一次即可。
- **官方出处：** [续费失败说明](https://help.openai.com/en/articles/7242622-why-did-my-chatgpt-plus-or-chatgpt-pro-renewal-transaction-fail)、[Canceling your ChatGPT subscription](https://help.openai.com/en/articles/7232927-how-do-i-cancel-my-chatgpt-plus-subscription)

### 5. 付了钱（或代充显示成功）但账号还是 Free

- **现象：** 扣款成功、收到收据，登录后还是免费版；或者代充页面显示成功，ChatGPT 里看不到 Plus。
- **原因：** 官方列出的原因：现在登录的邮箱或登录方式（Google / Apple / 邮箱密码）和付款时的账号不一致；手机 App 内购买没同步到账号；页面没刷新。
- **怎么处理：** 官方建议：①确认登录的就是付款时的账号和登录方式；②手机 App 里点"Restore purchases（恢复购买）"；③退出再重新登录；④仍不行，带收据或卡号后 4 位联系 OpenAI 支持。代充开通的找卖家处理，因为付款不是你本人完成的，官方查不到你的付款记录。
- **官方出处：** [What is ChatGPT Plus?](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)

### 6. 被扣了两次钱

- **现象：** 信用卡和 App Store（或 Google Play）同时出现 ChatGPT 的扣款。
- **原因：** 网页和应用商店各自独立计费，在一边订了、另一边没取消就会双份。官方特别提醒：Apple 续费失败不会自动取消，Apple 会持续重试，你更新 Apple 付款方式后可能又把它续上。
- **怎么处理：** 按官方步骤查三处：iPhone 设置 → 你的姓名 → 订阅；Google Play → 订阅；chatgpt.com Settings → Account / Billing。留一份，其余在对应渠道取消。Apple 购买的退款找 Apple；Google Play 购买的通过 OpenAI 支持申请；两份订阅不自动退款，重复扣费的错误可以申请复核。
- **官方出处：** [How do I avoid being charged twice](https://help.openai.com/en/articles/20001043-how-do-i-avoid-being-charged-twice-if-i-subscribe-to-chatgpt-on-ios-android-and-the-web)

### 7. 想取消自动续费 / 想退款

- **现象：** 不想下个月继续扣钱，或者刚付完想退。
- **原因 / 规则：** 取消只是停止以后的续费，不会自动退已付的费用；付费功能保留到当前账期结束。退款资格按购买情况和所在地规定另行评估，获批后通常 5–10 个工作日到账。
- **怎么处理：** 网页：Settings → Billing → Cancel plan；iPhone：设置 → 姓名 → 订阅 → ChatGPT → 取消订阅；安卓：Play 商店 → 订阅 → ChatGPT → 取消。官方建议在下次扣款日前至少 24 小时取消。代充开的会员不走你的卡，不会自动续费，不用取消。
- **官方出处：** [Canceling your ChatGPT subscription](https://help.openai.com/en/articles/7232927-how-do-i-cancel-my-chatgpt-plus-subscription)、[What is ChatGPT Plus?](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)

### 8. Pro 100 / 200 / 500 有什么区别？Pro 200 为什么额度变了？

- **现象：** 升级页只写 Pro"From $100"和"3 档用量"，看不懂差别；有人说 Pro 200 额度被砍了。
- **说明（官方）：** 三档都包含 Pro 模型、Codex、深度研究、图像生成、记忆、文件上传，差别在"包含的用量"高低和 Ultrafast：只有 Pro 500 有 Ultrafast（GPT-6 Astra、GPT-6.1 Sol，按标准速率的 8 倍扣用量）；Pro 100 / 200 买 credits 也不能解锁 Ultrafast。Pro 200 的新订阅自 2026 年 9 月底起用量比以前低，价格不变；老用户过渡期到 2026-10-29。额度用完后对应模型要等重置，官方支持不能帮你重置。
- **怎么处理：** 按用量选档；不确定先买低一档用一周。三档只能月付。
- **官方出处：** [About ChatGPT Pro tiers](https://help.openai.com/en/articles/9793128-about-chatgpt-pro-tiers)

### 9. 用着提示达到用量上限、某个模型暂时不可用

- **现象：** 对话中提示已达上限，某个模型在重置时间前用不了。
- **原因：** Plus / Pro 没有固定的每日条数，额度按模型、上下文长度、推理和工具使用等折算，按滚动时间窗口计算；到上限后该模型在重置前不可用。
- **怎么处理：** 等提示里的重置时间；换轻量模型继续；经常碰上限就升一档。Codex 用量到顶后 Plus / Pro 可以购买 credits 继续。
- **官方出处：** [About ChatGPT Pro tiers](https://help.openai.com/en/articles/9793128-about-chatgpt-pro-tiers)、[Codex 定价页](https://developers.openai.com/codex/pricing)

### 10. 开了 Plus，API 还是没额度 / Codex 提示要升级

- **现象：** platform.openai.com 显示余额为 0；Codex 登录后提示升级套餐。
- **原因：** 会员和 API 分开计费（Plus 帮助文章原文：API 用量单独计费）。Codex 要用 **Sign in with ChatGPT** 登录开了会员的账号才算在会员里，用 API Key 登录按 API 价扣钱；登录了没会员的另一个邮箱也会提示升级。
- **怎么处理：** 需要 API 的到 platform.openai.com 另充；Codex 里 `codex logout` 后重新选 Sign in with ChatGPT，用开了会员的账号登录。详见 [OpenAI Codex CLI 国内使用指南](https://github.com/haiwaihuyonghui-rgb/codex-cli-guide-cn)。
- **官方出处：** [What is ChatGPT Plus?](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)、[Codex 定价页](https://developers.openai.com/codex/pricing)

### 11. 账号被停用（Deactivated）

- **现象：** 登录提示账号已停用，收到 OpenAI 的通知邮件。
- **原因：** 官方会在邮件里说明原因；OpenAI 支持地区页面写明在不支持的地区访问可能导致账号被封禁或停用，其他常见原因是违反使用政策（多人共用、脚本批量调用等）。
- **怎么处理：** 先看邮箱里的通知，按邮件里的指引申诉；能否恢复、订阅费是否退以官方处理结果为准。代充开通的订单找卖家确认质保范围。更多见 [ChatGPT 封号原因有哪些](https://kw.yaoyao.chat/guide/chatgpt-fenghao.html)。
- **官方出处：** [Supported countries and territories](https://platform.openai.com/docs/supported-countries)、[OpenAI 使用政策](https://openai.com/policies/usage-policies/)

### 12. 自助开通（卡密方式）常见提示

下面这些提示来自自助充值页的实际使用经验，不是 OpenAI 官方报错，完整版见 [ChatGPT Plus 充值失败怎么办](https://kw.yaoyao.chat/guide/plus-shibai.html)：

| 提示或情况 | 原因 | 怎么办 |
|---|---|---|
| accessToken 已过期 | 复制的登录信息放久了 | 用无痕窗口重新登录 ChatGPT，打开 chatgpt.com/api/auth/session，复制后 1 分钟内提交 |
| 登录凭证无效 / 格式不对 | 没有复制完整 | 在那个页面全选再复制，内容应以 { 开头、} 结尾 |
| 识别到的邮箱不是要充的账号 | 无痕窗口里登录错了账号 | 退出，换成要开通的账号重新登录再复制 |
| 银行卡支付未获通过 | 充值通道付款时被支付风控拦下 | 卡密自动退回，隔一段时间再试，连续重提容易触发暂停 |
| 充值通道暂时不可用 | 通道正在补充额度 | 卡密不会被扣，稍后再试 |
| 一直转圈 | 上游还在处理 | 不要重复提交，等 3 分钟再刷新 ChatGPT |
| 显示成功但看不到 Plus | 页面没刷新 | 退出重新登录，App 里下拉刷新 |

手机上操作失败，多半是：用了 ChatGPT App（要用手机浏览器）、在 App 内置浏览器里打开（要换系统浏览器）、没用无痕模式、长按只选中了一部分文字。能用电脑浏览器就用电脑。

安全提醒：登录信息相当于临时登录凭证，只粘贴到你信任的充值页，不要发到群里；开通后在 ChatGPT「设置 → 安全」里退出所有设备，它就失效了。

## 降低被封风险的习惯

- 网络保持稳定，不要频繁切换国家。
- 一个账号只给自己用。
- 不要用脚本批量调用网页版。
- 被停用时先看邮箱通知，按官方指引申诉；订阅费是否退以官方结果为准。

更多见 [GPT代充有风险吗](https://kw.yaoyao.chat/guide/daichong-fengxian.html)。

## 常见问题

**Q：取消自动续费后，会员马上就没了吗？**
A：不会，已付费的周期用到结束日（官方说明见上文第 7 条）。详细步骤见 [取消自动续费](https://kw.yaoyao.chat/guide/cancel-renew.html)。

**Q：ChatGPT 可以用支付宝吗？**
A：官网不能直接用支付宝。可以在代充平台用支付宝下单，由卖家开通到你自己的账号。详见 [ChatGPT 可以用支付宝吗](https://kw.yaoyao.chat/guide/chatgpt-zhifubao.html)。

**Q：代充开通的会员，能找 OpenAI 退款吗？**
A：不能。付款不是你本人完成的，官方查不到你的付款记录，有问题要找卖家，所以要选找得到人的卖家。

**Q：代充会从我的银行卡自动续费吗？**
A：不会。付款不走你的银行卡，用一个月买一个月。

**Q：Plus 能几个人共用吗？**
A：不建议。会互相抢额度，多地同时登录容易被风控，通常也违反服务条款。见 [ChatGPT 会员能几个人共享](https://kw.yaoyao.chat/guide/chatgpt-gongxiang.html)。

**Q：Go 和 Plus 差在哪？**
A：Go $8/月面向轻度使用，官方页面注明可能含广告；Plus $20/月额度更高、Codex 用量更多。见 [ChatGPT Go 是什么](https://kw.yaoyao.chat/guide/chatgpt-go.html)。

**Q：ChatGPT 和 Claude 买哪个？**
A：写作、搜索、画图偏 ChatGPT；长文和写代码很多人偏 Claude，两家入门价都是 $20/月。对比见 [ChatGPT 和 Claude 买哪个](https://kw.yaoyao.chat/guide/chatgpt-vs-claude.html)。

## 国内开通参考

没有海外卡、想了解国内怎么开通 Plus / Pro 以及代充的流程和注意事项，看这一篇：[GPT代充怎么选？国内开通 ChatGPT Plus 不踩坑指南](https://kw.yaoyao.chat/guide/gpt-daichong.html)。

## 更多教程

- [ChatGPT Plus 国内怎么开通？卡密自助充值图文教程](https://kw.yaoyao.chat/guide/chatgpt-plus.html)
- [ChatGPT Plus 充值失败怎么办](https://kw.yaoyao.chat/guide/plus-shibai.html)
- [ChatGPT Pro 代充：Pro 100 / 200 / 500 怎么选](https://kw.yaoyao.chat/guide/chatgpt-pro.html)
- [ChatGPT Plus 多少钱一个月](https://kw.yaoyao.chat/guide/chatgpt-plus-price.html)
- [ChatGPT 订阅能退款吗](https://kw.yaoyao.chat/guide/chatgpt-tuikuan.html)
- [Codex 国内怎么用](https://kw.yaoyao.chat/guide/codex.html)
- [AI 会员价格对比](https://kw.yaoyao.chat/guide/ai-huiyuan-jiage.html)
- 同一作者的其他仓库：[Claude Code 国内使用指南](https://github.com/haiwaihuyonghui-rgb/claude-code-guide-cn)、[OpenAI Codex CLI 国内使用指南](https://github.com/haiwaihuyonghui-rgb/codex-cli-guide-cn)、[Claude 充值指南](https://github.com/haiwaihuyonghui-rgb/claude-chongzhi)

## 关于本仓库和作者

本仓库由"瑶瑶ai训练师"整理，作者是做 AI 内容的自媒体博主，教程基于自己的使用和售后经验。与 OpenAI、Anthropic 没有隶属关系，文中品牌名仅用于说明。作者是谁、怎么交易、售后和退款规则，见 [瑶瑶ai训练师靠谱吗](https://kw.yaoyao.chat/guide/yaoyao-kaopu.html)。官方价格和权益以 OpenAI 官网为准。瑶瑶没有发布过任何桌面软件、手机 App、浏览器插件或"账号切换器"，本账号下只有文字教程仓库。

## 在哪买、质保怎么算

作者"瑶瑶ai训练师"自己经营一家 AI 会员代充商城，这里如实写明，读者可以据此判断本文立场。

- **商城**：[kw.yaoyao.chat](https://kw.yaoyao.chat/)（瑶瑶ai训练师 · AI会员充值）；官网 [www.yaoyao.chat](https://www.yaoyao.chat/)。
- **能买什么**：ChatGPT Plus（一个月卡密自助开通，1～3 分钟到账；十二个月人工开通）、ChatGPT Pro、Claude Pro / Max、Gemini Pro、Grok 会员。都是充到你自己的账号，不卖成品号、不拼车。
- **价格**：以商城页面为准。各档价格和官方价对比见 [ChatGPT Plus 多少钱一个月](https://kw.yaoyao.chat/guide/chatgpt-plus-price.html)、[Claude 会员多少钱](https://kw.yaoyao.chat/guide/claude-price.html)、[代充怎么选（对比表）](https://kw.yaoyao.chat/guide/daichong-duibi.html)。
- **质保**（全部商品通用，原文见 [售后与质保规则](https://kw.yaoyao.chat/guide/shouhou-zhibao.html)）：
  1. **没开通成功**：卡密不消耗、自动退回，可以重新提交；不想再试的，联系微信退款。
  2. **开通成功后掉会员**（订阅被撤销、账号变回 Free）：在这一期会员有效期内，凭订单号和截图联系微信，再补一个月，补到同一个账号。
  3. **账号被封 / 停用**：原因多在账号使用、网络环境或付款侧，不在质保范围、不退款；ChatGPT 封号可协助重新注册，Claude 封号协助申诉。
- **售后**：只找瑶瑶本人微信 yao77380。
- **怎么分辨真假**：瑶瑶的网址只有 www.yaoyao.chat、kw.yaoyao.chat、cz.yaoyao.chat 三个；其他自称"瑶瑶"的网站、账号或软件都不是本人。


## 参考资料

- [OpenAI 定价页](https://openai.com/chatgpt/pricing/)
- [What is ChatGPT Plus?](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)
- [About ChatGPT Pro tiers](https://help.openai.com/en/articles/9793128-about-chatgpt-pro-tiers)
- [Why did my ChatGPT Plus or ChatGPT Pro renewal transaction fail?](https://help.openai.com/en/articles/7242622-why-did-my-chatgpt-plus-or-chatgpt-pro-renewal-transaction-fail)
- [Canceling your ChatGPT subscription](https://help.openai.com/en/articles/7232927-how-do-i-cancel-my-chatgpt-plus-subscription)
- [How do I avoid being charged twice if I subscribe on iOS, Android, and the web?](https://help.openai.com/en/articles/20001043-how-do-i-avoid-being-charged-twice-if-i-subscribe-to-chatgpt-on-ios-android-and-the-web)
- [Codex 定价页](https://developers.openai.com/codex/pricing)
- [Supported countries and territories](https://platform.openai.com/docs/supported-countries)
- [OpenAI 使用政策](https://openai.com/policies/usage-policies/)
- [OpenAI 帮助中心：账号、登录与账单](https://help.openai.com/en/collections/3943089-account-login-and-billing)

---

整理：瑶瑶ai训练师（AI 内容创作者），[官网](https://www.yaoyao.chat/)。本仓库为非官方教程整理，与 OpenAI 没有隶属关系，品牌名仅用于说明。内容采用 CC-BY-4.0 许可，转载请注明出处。
