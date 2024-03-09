# arceos 工作空间

**本工作空间配合 vscode 使用**

## 使用方法

- 将本项目下载到本地
- 在本项目中下载任何课程需要的代码，下一节会给出常用代码的仓库地址
- 用 vscode 打开本项目
- 安装本项目的推荐插件
- 修改 `.devcontainer/devcontainer.json`
    - `workspaceFolder`: 使其指向需要修改代码的文件夹, 路径中的前缀 `/workspaces/arceos_ws/` 不要动，这个是 vscode 另一个变量控制的
    - `containerEnv`: 指向你的代理，如果代理开在本机，则 ip 应该给 Docker 虚拟网卡的地址，一般来说是 `172.17.0.1`
- `ctrl - shift - p` 打开命令面板
- 搜索并使用 `Dev Containers: Rebuild and Reopen in Container`
- 进入容器后不用再安装项目推荐插件，那些插件是给本地安装的，不是给容器的

## 常用仓库地址

- arceos: https://github.com/rcore-os/arceos.git
- redis: https://github.com/redis/redis.git
- Starry: https://github.com/ZhiyuanSue/Starry_redis_homework.git