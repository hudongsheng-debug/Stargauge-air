# StarGauge Air 支持
最后更新：2026-11-10

## 联系方式
hudongsheng356@gmail.com
请在邮件主题中写明“StarGauge Air 支持”，并提供应用版本、iPad 型号、iPadOS 版本及复现步骤。请只发送你愿意分享的截图和最小示例；不要发送密码或无关敏感资料。

## 快速开始
- 点击“体验示例”，或从文件导入 FITS 并选择图像 HDU。
- 在“选区”模式点选星点或拖动区域。
- 查看统计与径向曲线，按需保存测量记录。
- 导出测量 CSV、径向 CSV 或带标记 PNG。

## 数据和使用边界
支持未压缩及支持的瓦片压缩二维图像、多图像 HDU；不支持立方体、表格或外层 gzip。FWHM 为二阶矩估计，不是拟合或标定结果；孔径信号不是标定星等。本地记录不包含原始 FITS，重新应用需要匹配的像素指纹与图像/HDU。

## 保存与备份
测量数值、选区、记录名称与用于匹配的图像/HDU 像素指纹保存在应用本地空间，最多 1000 条记录。原始 FITS 不随记录保存。文件指纹用于识别图像，不是个人身份标识，也不会上传。
卸载或删除应用前，请先导出重要资料并保留原始文件。仅卸载应用与删除应用的系统行为可能不同；请按 iPad 的实际选项确认。

## 常见问题

### 为什么记录不能重新应用？
需要重新打开像素指纹匹配的原图及对应 HDU。只保留文件名不足以匹配。

### FWHM 是拟合结果吗？
不是。这里采用高斯等效二阶矩估计；请结合背景、采样和目标形态解释。

### 文件选择器里找不到文件，或云文件无法读取？
先在系统“文件”中确认文件已完整下载、你有访问权限，且格式受本应用支持。重试时优先使用“我的 iPad”中的本地副本。扩展名相同不保证内部数据结构一致。

### 怎样报告问题？
说明你执行的操作、预期结果与实际结果，并提供不含敏感信息的截图。若需要样例，优先构造小型合成文件。没有源文件也可以先报告，我们会根据描述继续沟通。

## 隐私
本应用不要求账户，主要处理在设备本机完成。请阅读同目录的隐私政策，了解本地存储、文件服务和主动支持邮件的处理方式。

---

# StarGauge Air Support
Last updated: 2026-11-10

## Contact
hudongsheng356@gmail.com
Use “StarGauge Air Support” in the subject. Include the app version, iPad model, iPadOS version, and reproduction steps. Send only screenshots and minimal examples you are comfortable sharing. Do not send passwords or unrelated sensitive information.

## Quick start
- Choose Explore Demo or import FITS and select an image HDU.
- In Selection mode, tap a star or drag a region.
- Inspect statistics and radial profiles, and save a measurement record if desired.
- Export measurement CSV, radial-profile CSV, or marked PNG.

## Data and scope
Supports uncompressed and supported tile-compressed 2D images and multiple image HDUs, not cubes, tables, or outer gzip compression. FWHM is a second-moment estimate, not a fitted or calibrated result; aperture signal is not calibrated magnitude. Saved records do not contain the source FITS. Reapplication requires matching pixel identity and image/HDU.

## Saving and backups
Measurements, selections, record names, and image/HDU pixel fingerprints used for matching are stored locally, with up to 1000 records. Source FITS files are not included. Fingerprints identify image data, not a person, and are not uploaded.
Export important work and retain source files before offloading or deleting the app. Offload App and Delete App can have different effects; check the actual system option on your iPad.

## Frequently asked questions

### Why can a saved selection not be reapplied?
Reopen the original image and HDU with matching pixel identity. A matching filename alone is insufficient.

### Is FWHM a fitted result?
No. It is a Gaussian-equivalent second-moment estimate. Interpret it with the background, sampling, and target shape in mind.

### A file is missing from the picker, or a cloud file will not open
In Files, confirm the file is fully downloaded, accessible, and in a supported format. Try a local copy under On My iPad. A matching filename extension does not guarantee a supported internal structure.

### How should I report a problem?
Describe the action, expected result, and actual result, with screenshots free of sensitive information. If an example is needed, prefer a small synthetic file. You may report the problem without a source file first; we can follow up from your description.

## Privacy
No account is required and core processing takes place on your device. Read the privacy policy in this folder for local storage, file services, and voluntary support communications.
