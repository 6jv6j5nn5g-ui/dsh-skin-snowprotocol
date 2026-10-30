# 霜雪协议 · DSH Web 过场

给 DeepSeek Harness Web GUI 加一段冷启动过场：打开界面时先播一段霜雪协议动画，播完落到正常的工作界面。

## 装

```bash
dsh plugin --profile <你的profile> add github:6jv6j5nn5g-ui/dsh-skin-snowprotocol
```

装完重启一次 DSH（它是启动时注入的，不走 HMR）。

## 它做了什么

- 启动时全屏播放一段过场：霜雪下落、文字逐行浮现
- 播完自动进入工作界面，不打断任何操作
- 纯客户端实现，不改宿主代码

## 兼容

- DSH `0.2.1-rc.3` 实测可用
- 纯客户端插件

## 想要自己的过场

可以接定制：文字、节奏、画面都可以改。联系方式见仓库主页。

## License

MIT
