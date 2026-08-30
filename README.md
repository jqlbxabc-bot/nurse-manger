# 高三六科 AI 学习助手：临时公网演示

这是通过 GitHub Actions 和 Cloudflare Quick Tunnel 运行的临时测试环境。

- 每次运行最长约 6 小时，任务结束后网址失效。
- 仓库不包含 `.env`、API Key、数据库或学生上传资料。
- DeepSeek 仅从 GitHub Actions Secret `DEEPSEEK_API_KEY` 读取；没有该 Secret 时只能测试界面与非 AI 流程。
- 临时环境的数据会在任务结束后清空，不应填写真实个人信息。

在 Actions 页面打开 `Temporary public demo` 的最新运行记录，展开 `Publish temporary URL`，即可看到 `trycloudflare.com` 临时网址。

