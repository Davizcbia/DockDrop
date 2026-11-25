# DockDrop

[简体中文](#简体中文) · [English](#english)

## 简体中文

DockDrop 是 DockOver 的文件和文字互传工具。Windows 端显示配对光泡和备用二维码，手机使用浏览器连接。完成首次配对后，可以记住设备并在之后重新连接。Windows 仍会在接收前显示确认。

## Windows 11 x64

1. 下载并解压 `DockDrop-Windows-Portable-0.1.0.zip`，运行 `DockDrop.exe`。
2. 用手机浏览器扫描光泡或备用二维码，在手机上选择发送或接收。
3. 在 Windows 设置窗口中调整接收目录、管理已配对手机和资源管理器入口。

电脑需要 Microsoft Edge WebView2 Runtime。简体和繁体中文由 Windows 或 DockOver 的语言设置启用。

[下载 0.1.0](https://github.com/Davizcbia/DockDrop/releases/tag/0.1.0) · [手机扫码页](https://davizcbia.github.io/dockdrop-scan/bubble/) · [共享源码](https://github.com/Davizcbia/DockOver/tree/1.1.0/dockui/src/pairing)

Release 另含 PC 局域网互传和临时 Wi-Fi 浏览器收发预览，实体设备兼容性仍在验证中。

## English

DockDrop transfers files and text between Windows and a phone. Scan the pairing bubble or backup QR code in your phone browser. You can remember the phone after the first pairing and reconnect later. Windows asks before accepting an incoming transfer.

1. Extract the Windows 11 x64 package and run `DockDrop.exe`. Microsoft Edge WebView2 Runtime is required.
2. Open the scanner on your phone and scan the bubble or QR code. Choose Send or Receive.
3. Open DockDrop Settings to choose the destination folder, manage remembered phones, or add the File Explorer menu entry.

The release also includes PC LAN transfer and temporary Wi-Fi browser transfer previews. Physical-device compatibility is still being tested.

[Download 0.1.0](https://github.com/Davizcbia/DockDrop/releases/tag/0.1.0) · [Phone scanner](https://davizcbia.github.io/dockdrop-scan/bubble/) · [Shared source](https://github.com/Davizcbia/DockOver/tree/1.1.0/dockui/src/pairing)

## 功能截图 / Screenshots

| 光泡配对 / Pairing bubble | 手机文字收发 / Phone text transfer |
| --- | --- |
| ![光泡配对 / Pairing bubble](screenshots/pairing.jpg) | ![手机文字收发 / Phone text transfer](screenshots/phone-text-transfer.jpg) |
| **PC 收件请求 / PC receive request** | **实际接收进度 / Transfer progress** |
| ![收件确认](screenshots/receive-request.jpg) | ![接收进度](screenshots/receiving.jpg) |
| **接收完成 / Transfer complete** | **DockOver 桌面暂存 / Desktop staging** |
| ![接收完成 / Transfer complete](screenshots/receive-complete.jpg) | ![暂存小组件](screenshots/desktop-staging-widget.jpg) |
