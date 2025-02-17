# 如何部署
1. 克隆本仓库
2. 拉取主题
```bash
git submodule init
git submodule update
```

3. 常用命令
```bash
brew upgrade hugo                      // 更新 hugo
git submodule update --remote --merge  // 更新主题
hugo server                            // 本地预览
hugo                                   // 编译
```