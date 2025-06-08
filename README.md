# MonadPay
*基于 Deeplinks 的规范，用于在 URL 中编码 Monad 交易请求，以启用支付、NFC 和其他用例。发送、请求和触发加密支付的最简单方法--只需一个链接。*

---

## 🛠 使用案例

MonadPay 支持**链接原生加密支付**。比如`monadpay://send?to=0x123...&amount=10&token=USDC`- 嵌入`到`任何地方。

- **创作者和商家：**在社交媒体、电子邮件、QR 码、NFC 芯片或发票上分享支付链接。
- **DApps 和机器人：**通过 URL 触发链上支付，无需开发钱包用户界面。
- **NFC / Physical UX：**带有 MonadPay 链接的贴纸或芯片可将离线互动转化为即时支付。
- **Telegram / Farcaster / 电子邮件支付：**只需轻点一下，即可打开钱包，进行预先填充的交易。