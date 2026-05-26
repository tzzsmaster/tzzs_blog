# 【AI编程】 模型订阅渠道、费用与体验
____tz_zs

首选 `claude opus` 模型，从 `Claude Opus 4.6` 到 `Claude Opus 4.7`，opus 仍是现在的最优解。
其次 GPT 模型。

>2026-05-18 补充：现如今，大多数模型在多数日常编码任务中感受不到明显差距，差距主要出现在需要深度理解业务背景做权衡决策的场景。

## 一、GitHub Copilot
购买方式：港卡

可以通过 `Copilot` 灵活选用 `claude、gpt、gemini` 等的最新模型。如果之前有注册，因为他可以港卡直接支付，会是不错的选择。不用担心 `claude` 封号，也不需要找额外的渠道避开银行卡限制。
不过，最近有调整，之前没有注册过的，暂时可能没法注册新账号。
>自 2026 年 4 月 20 日起，`Copilot Pro`、`Copilot Pro+` 和`学生`计划的新用户注册将暂时停止。
>自 2026 年 4 月 22 日起，`GitHub 免费版`和 `GitHub 团队版`计划的组织用户将暂时停止自助注册 Copilot Business。

使用方式：`VS Code` + `Copilot 插件`
### 订阅计划 Copilot Pro
- 10美元一个月，第一月免费试用。
- 在直到 4 月底的时候，Pro 订阅可以使用 `Claude Opus 4.6`（ `Claude Opus 4.7` 出现之前）。现在已经只包含最高到 `Claude Sonnet 4.6` 和 `GPT-5.4`。
- 包含 300 次高级请求。
### 订阅计划 Copilot Pro+
4月底，我将订阅升级到了 `Copilot Pro+`。

- 39 美元一个月。
- 支持到最新的 `Claude Opus 4.7` 和 `GPT-5.5` 模型。  
- 高级请求次数 1500 次。

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/30a2b81debfe4ab1969f2e89696121a0.png)

### 消耗情况和节约token要点  
然而，消耗量巨大，如上图 `Claude Opus 4.7` 的积分是 15x，意味着是 `Claude Sonnet 4.6` 1x 的 15 倍的消耗量。
5月以来，仅4个工作日，就几乎消耗光了，如下图。

而且公告中，6月以后，将改为按量计费，可能很难控制成本，需要注意控制消耗：

>自 2026 年 6 月 1 日起，GitHub 将把 Copilot 的计费方式从基于请求的计费方式改为基于使用量的计费方式。

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/4faf4d06d74f4d1c9c70eb745fe4110f.png)

因为当前是按照次数计分，在使用模型时，可以尽量将问题集中处理和安排，不要简单的问答，一次 `Claude Opus 4.7` 消耗 15 的请求次数。
另外，不是所有地方都要用 `Claude Opus 4.7`，一般的开发中，使用 `Claude Sonnet 4.6` 也完全能够胜任，额度也完全够用。

## 二、GPT + Codex
购买方式：  
通过咸鱼购买 Apple 美区充值卡 → 充值 Apple ID → 在 iOS App 内购买 ChatGPT 会员  

- `Codex`+`GPT-5.5` 模型
- `Codex Plus` 订阅，20美元一个月。

Codex 在 Windows 上暂时没有自己的 IDE，如果需要，只能通过插件在其他 IDE 中使用。  

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/d622d8cd3ea444e49e44a9402395f8da.png)

使用方式：`VS Code`+`Codex插件`  
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/51eb2091392c48f59d7af876b2fa4a79.png)  
使用方式：`Cursor`+`Codex插件`  
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/a87f7acad60843bb9ba65d55aee60a54.png)  
### VS Code + Codex插件  
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/ddcb88b15b794a4baf34e106dc5fd5ec.png)  

- 体验上更接近 IDE 方式。
- GPT-5.5 模型是靠谱的。
- GPT 的胆子比 Claude 系列的大，改动更加大刀阔斧。

## 三、Cursor

购买方式：内地支付宝可行  
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/f906ddf542b14a1f8b366a7dd02931e3.png)  
使用方式：`Cursor` + `GPT / Claude / Gemini`  

注意，`Opus 4.7` 模型不对某些地区开放 `Model not available`。如遇到，可以通过开启代理的 `Tun` 模式解决。如下： 
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/c8bd34fd200941a0aad2b850dea8041e.png)  
地区限制，模型不可用（Model not available）：  
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/f749dbf6655c4805ae943b247be4bf84.png)  
代理开启 `TUN` 和 `全局`：  
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/f7142df7cbc34fc8bc5f747d800f4a47.png)  
### 订阅计划 Pro  
- `Cursor Pro` 订阅，20美元一个月
- 同时能切 `GPT / Claude / Gemini`

#### 消耗情况和节约token要点  
查看token消耗：https://cursor.com/cn/dashboard/usage  
一次调用消耗了 1300+ 万的 token，额度 20%。  
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/16420d7d9c474053baa756f9b1a61e8f.png)  
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/0b616281f4d5491993c6b56e19f92ac9.png)  
emmmm 用不起了，半天时间，用了近 4000 万 token。  
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/7cf56ea10c194e3c9b5c1749bf99ce96.png)  
总额消耗到 6100+ 万 token，显示 100%，自动切换到了免费模型 `Composer 2.5` 。  

### 订阅计划 Cursor Pro+
切换到 `Cursor Pro+` 计划。

- `Cursor Pro+` 订阅，60美元一个月
- 直接升级订阅计划，原 `Cursor Pro` 订阅自动进行了部分退款：refunded (17.37 USD)  
- 升级订阅计划后，额度进行了重置，即原 `Cursor Pro` 订阅时消耗 token 的累计数量清零了，重新开始计算。

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/fbcc9320c32a4879a441cb48493e2b0d.png)

### 20260520 补充
[邀请的链接，可以省10美元 https://cursor.com/referral?code=PAOMBITXI7CO](https://cursor.com/referral?code=PAOMBITXI7CO)  

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/9684b53fc55c4161891322e1ee7f7154.png)


