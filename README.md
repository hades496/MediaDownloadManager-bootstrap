# MediaDownloadManager Bootstrap

GitHub 仓库认证已调整为 gh 优先：安装脚本会先尝试 `gh auth status` / `gh auth login` / `gh auth setup-git`，仅在 `gh` 不可用或认证失败时回退为手动输入 Token；若当前环境没有交互终端，请预先设置 `GITHUB_TOKEN` 环境变量。

发布时，将本目录中的文件直接上传到公开仓库根目录即可。
