DELUXE GARAGE CASH BILL V1.2 — GitHub 更新说明

修改：
1) Cash Bill A4 中删除 REMARK 区块，VEHICLE DETAILS 不再显示 Remark
2) 左上 DELUXE GARAGE Logo 放大
3) 右上 CASH BILL 改为白底黑字和橙色细节，不再使用汽车照片背景
4) App 底部五个菜单改为白底深色字、橙色图标与选中状态

其余功能：保留旧 Cash Bill 保存、历史记录、PDF、打印、分享、签名/盖章、商品库、客户及多页打印。
数据兼容：沿用原来的 localStorage 键 deluxe_garage_invoice_v1，不会主动清空历史资料。

更新方式：
1. 建议先在当前 V1.1 的 Settings 导出 JSON 备份。
2. ZIP 解压，上传里面的 index.html、sw.js、manifest.json、logo.jpg、logo-tight.jpg、footer-strip.jpg、header-car.jpg、icon-180.png、icon-192.png、icon-512.png 到现有 DeluxeGarage GitHub 仓库根目录，覆盖同名文件。
3. GitHub Pages 发布后，通过 Safari 打开网址并刷新。若旧界面暂时还在，关闭重新打开，耐心等缓存更新。
4. 不必删除 iPhone 主屏幕 App；不要清除 Safari 网站数据，以免本地 Cash Bill 资料丢失。

注意：请在 iPhone 上实际测试导出 PDF / 打印与单据保存。
