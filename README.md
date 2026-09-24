---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: 37b90b68a17e7de0e96915fb7616a823_eb64b4bbb81511f1aea4525400393706
    ReservedCode1: 66VqJdM6lxqlgEG/VvOE+fGhqwkM5vJdv+eRumYH30I1Z55FNwZmoTRjiZ8DfodpgKNhBAAleYm+eQPV5GGvJKmeGZiX1NiaGJ3eo1sLyLWZuQgkT6dJ1/I94M4UrzlljfV3n1yz4FAMVZvt7bCxE+vALiIK4pMEaffZLU/ItAI4XE97SLpv95zFJGc=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: 37b90b68a17e7de0e96915fb7616a823_eb64b4bbb81511f1aea4525400393706
    ReservedCode2: 66VqJdM6lxqlgEG/VvOE+fGhqwkM5vJdv+eRumYH30I1Z55FNwZmoTRjiZ8DfodpgKNhBAAleYm+eQPV5GGvJKmeGZiX1NiaGJ3eo1sLyLWZuQgkT6dJ1/I94M4UrzlljfV3n1yz4FAMVZvt7bCxE+vALiIK4pMEaffZLU/ItAI4XE97SLpv95zFJGc=
---

# EVASafe

一个完全离线的安卓本地密码管理器 —— 密码只存在你自己的手机里。

---

## 这是什么

EVASafe 用来集中存放那些零散又重要的东西：账号密码、银行卡密码、PIN 码、各种卡片密码。

它的核心只有一句话：**不联网、不上传、不做云同步**。所有数据都留在设备本地，外面加两道锁 —— PIN 码和指纹。

## 核心特性

| 特性 | 说明 |
| --- | --- |
| 完全离线 | 不联网、无云同步，数据只存在本机 |
| 双重解锁 | PIN 码 + 指纹，指纹解锁优先级最高 |
| 失败保护 | 指纹连续失败 3 次后冷却 30 秒，期间只能用 PIN 码 |
| 加密备份 | 导出为 `.holesafe` 加密文件，恢复时需输入备份密码 |
| 两种导入 | 支持「合并导入」和「覆盖导入」 |
| Excel 导出 | 可导出为 `.xlsx` 表格，方便查看和编辑（明文，请注意保管） |
| 外观自定义 | 深色 / 浅色模式，主题色可选 |

## 快速上手

1. 安装后首次打开，设置 PIN 码
2. 开始录入密码条目，比如「我的建行储蓄卡」
3. 到设置里开启指纹解锁，以后抬手就能进
4. 定期做一次备份导出，把 `.holesafe` 文件放到安全的地方

> 请务必记住 PIN 码 —— 忘记 PIN 码将无法解锁。

## 备份与恢复

**导出备份**

1. 设置一个用于加密备份文件的密码
2. 经过加密后导出为 `.holesafe` 文件
3. 妥善保存这个文件

**恢复备份**

1. 选择导入方式：合并导入 / 覆盖导入
2. 输入导出时设置的加密密码
3. 等待恢复完成

> 特别注意：覆盖导入会清除现有所有密码，操作前请先确认已有备份。

> 仅支持导入由 EVASafe 导出的 `.holesafe` 加密文件；解密失败时请检查密码是否正确。

## 关于「不联网」

EVASafe 的设计理念很简单：**只有把密码彻底与互联网隔绝，才是真的安全**。

不做云同步、不上传任何账号数据，也不依赖服务器在线。你可以在手机的应用权限里查看它的权限情况。

为什么不做云同步？因为一旦上传云端，谁也无法保证云服务器是否安全 —— 存在自己手机里，最踏实。

## 版本更新

由于应用本身不联网，版本更新需要你自行到更新发布页查看是否有新版本。

## 使用建议

- 首次使用就把 PIN 码设好，并立刻开启指纹解锁
- 每隔一段时间导出一份加密备份，多存几个地方
- 导出的 `.holesafe` 文件和它的备份密码，请分开保管
- Excel 导出是明文文件，方便归类和编辑，但不要随手乱放

## 注意事项

- 忘记 PIN 码将无法解锁，也没有后门可以找回
- 备份文件与 Excel 文件一旦泄露，其中的密码就等于泄露，请自行妥善保管
- 本应用为个人自用工具，使用前请自行评估风险

---

## 反馈

有想法、发现问题，欢迎到 [@EvanTop](https://github.com/evantop) 的仓库提 Issue。
*（内容由AI生成，仅供参考）*
