# GitHub 分享操作指南

## 推荐：两个技能放在同一个仓库
GitHub 中用于保存文件的是 Repository（仓库）；Projects 是管理任务的看板。分享技能先建仓库即可。

1. 登录 GitHub，点击右上角“+”→“New repository”。仓库名可用 `gaokao-consultation-skills`；描述可填“高考初访准备与省份年度政策维护 Agent Skills”。需要公开分享选 Public。勾选添加 README，点击 Create repository。
2. 在仓库首页打开 Add file → Upload files。将本次两个技能目录中的 `GitHub源码包.zip` 先解压到临时位置，再把解压得到的两个英文文件夹拖入上传区。不要直接上传 ZIP 代替源文件。预览应看到 `gaokao-first-consult/SKILL.md` 和 `gaokao-policy-library/SKILL.md`。
3. 填写提交说明“添加高考咨询技能与使用文档”，点击 Commit changes。如果是别人的仓库，需有写入权限，或通过 Fork 和 Pull request 提交。
4. 编辑仓库根目录 README，简述两个技能用途，并链接 `gaokao-first-consult/README.md` 和 `gaokao-policy-library/README.md`。也可以分别建立两个仓库，上传各自源码包解压后的文件内容，让 SKILL.md 位于仓库根目录。
5. 打开文件核对中文、目录与链接。复制仓库地址即可分享。下载者可用 Code → Download ZIP，解压后按每个 README 安装。
6. 可选：在 Releases 新建版本，填写实际版本号，上传各自的 GitHub源码包.zip 方便下载。源文件更新后需重新打包，避免附件和源码不一致。

## 发布前还需你决定
- 作者或团队署名、联系渠道及最终仓库名称：尚未提供，无需为了上传填写私人联系方式。
- 授权方式：目前沿用原课程分享说明，没有擅自添加 MIT 等开源许可证。若希望公众可再分发、商用或改编，需由权利人选择许可并添加 LICENSE；公开可见不等于已经授予这些权利。
- 可选增加匿名演示截图与真实试用反馈；本次未伪造运行结果。

不要上传学生信息表、真实案例、账号凭据或私人政策工作库。现有旧 ZIP 和总校验清单仍是原交付版本，不代表本次新增文档；本次请使用新生成的 GitHub源码包。

## 后续更新
在 GitHub 打开目标文件，点击编辑按钮修改后提交。涉及多个文件时再次 Upload files，保持原路径。不要只更新 ZIP 而不更新源码。

官方操作参考：
- [创建仓库](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)
- [上传文件](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
- [许可证说明](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)
