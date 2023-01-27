<div align="center">
  <img src="https://s2.loli.net/2022/06/16/opBDE8Swad5rU3n.png" width="180" height="180" alt="NoneBotPluginLogo">
  <br>
  <p><img src="https://s2.loli.net/2022/06/16/xsVUGRrkbn1ljTD.png" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">

# nonebot_plugin_easy_group_manager
✨女生自用 99 新简易群管✨

</div>

### 📣 前言

女生自用 99 新简易群管，管理员设置新方案，BOT 不再必须为群主才能设置管理员。

## ⭐ 安装
    1.pip install nonebot-plugin-easy-group-manager
    2.nb plugin install nonebot-plugin-easy-group-manager
    3.Download zip

## 🛠️ 配置

| 配置       | 类型 | 示例          | 默认 | 说明                                                               |
| ---------- | --- | ------------- | ---- | ----------------------------------------------------------------- |
| admin_mode | int | admin_model=1 | 1    | 1 为调用 API，BOT 不需要为群主；2 为使用 Nonebot 框架，BOT 必须为群主 |
| skey       | str | skey="xxx"    | None | 获取看下文                                                         |
| pskey      | str | pskey="xxx"   | None | 获取看下文                                                         |

## 🎉 指令

| 指令                              | 权限                              | 说明                                |
| --------------------------------- | --------------------------------- | ---------------------------------- |
| 设置管理员 + @somebody             | SUPERUSER/GROUP_OWNER             | 设置一个管理员                      |
| 取消管理员 + @somebody             | SUPERUSER/GROUP_OWNER             | 取消一个管理员                      |
| 禁言/口球  + @somebody + 阿拉伯数字 | SUPERUSER/GROUP_OWNER/GROUP_ADMIN | 禁言某人，单位分钟，需要 BOT 为管理员 |
| 解禁 + @somebody                  | SUPERUSER/GROUP_OWNER/GROUP_ADMIN  | 解除某人禁言，需要 BOT 为管理员      |
| 移出 + @somebody                  | SUPERUSER/GROUP_OWNER/GROUP_ADMIN  | 移出某人，需要 BOT 为管理员          |
| 移出并拉黑 + @somebody             | SUPERUSER/GROUP_OWNER/GROUP_ADMIN | 移出并拉黑，需要 BOT 为管理员         |

## ⚠️ 获取 skey 和 pskey

1、访问 [https://qun.qq.com/](https://qun.qq.com/), 并使用**群主** QQ 号登录。

2、按 F12 并切换到 网络(Network) 视图。

![image.png](https://s2.loli.net/2023/01/26/a4lLFwDbJjPmfSE.png)

**skey=** 和 **p_skey=** 后面的内容(**不包括**后面的分号)即为需要的 skey 和 pskey。

## ✨ FUTURE

- [ ] 分群设置不同的 skey 和 pskey
