# 油猴脚本：本地开发环境-自动登录iLabPower账号

### 目的
在iLabPower系统中，接口权限校验主要依赖于已登录账号的用户信息，该信息被临时保存于cookie中。此脚本可自动读取UC系统当前账号注册的cookie，并将其写入本地开发页面，避免了开发者手动复制粘贴的过程。

### 使用步骤
#### 情况一：未登录任何账号
1. 打开UC系统，登录账号，系统自动跳转至用户中心页面。
2. 刷新该用户中心页面。
3. 打开本地开发页面。

#### 情况二：已登录某一账号
1. 打开UC系统，或刷新当前UC系统页面。
2. 打开本地开发页面。
