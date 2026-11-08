# bark-icons

[Bark](https://github.com/Finb/Bark) 推送通知用的图标，512×512 PNG、透明背景，供 `icon` 参数直接引用。

## 图标

| 文件 | 尺寸 | 直链 |
|---|---|---|
| `sms.png` | 512×512 | https://raw.githubusercontent.com/strange2000/bark-icons/main/sms.png |
| `sms-512.png` | 512×512（与 `sms.png` 同一文件） | https://raw.githubusercontent.com/strange2000/bark-icons/main/sms-512.png |
| `message-ios-512.png` | 512×512 | https://raw.githubusercontent.com/strange2000/bark-icons/main/message-ios-512.png |

## 用法

Bark 的 `icon` 参数接受一个图片 URL，直接把它拼在推送地址后面：

```text
https://api.day.app/<你的key>/推送内容?icon=https://raw.githubusercontent.com/strange2000/bark-icons/main/sms.png
```

在 Bark App 里也可以：`设置 → 应用图标` 填上面任一 URL。

## 国内访问不稳时

`raw.githubusercontent.com` 在部分网络下会超时，换 jsDelivr 镜像即可（同一仓库同一文件）：

```text
https://cdn.jsdelivr.net/gh/strange2000/bark-icons@main/sms.png
```

## 许可

MIT，见 [LICENSE](LICENSE)。图标可以随便用、随便改。
