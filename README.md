# Kubernetes Website Static Resource

**English** | [简体中文](README-zh.md)

1. This repository stores the build artifacts of https://github.com/xuxiaowei-com-cn/kubernetes-website
    - Due to certain limitations, the build artifacts of Kubernetes 1.19 and earlier are stored at
      https://github.com/xuxiaoweicom/kubernetes-website-static
2. It is used to deploy Pages on Cloudflare
3. Each Kubernetes Website branch stores only the latest build result, with no history, to keep the repository from
   growing too large
4. The size of each branch is available at: https://xuxiaowei.io/t/1320
5. Do not clone this repository. If you need it, clone only the code of the specified branch

```shell
git clone -b static/release-1.24/public https://github.com/xuxiaowei-com-cn/kubernetes-website-static
```
