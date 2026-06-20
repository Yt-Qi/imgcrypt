# imgcrypt

柒璃制作的本地图片加密 / 解密工具。所有处理均在浏览器本地完成，不会上传图片、密码或处理记录。

## GitHub Pages

主页：

```text
https://yt-qi.github.io/imgcrypt/
```

## 页面入口

| 功能 | 文件 | 访问地址 |
| --- | --- | --- |
| 单张图片解密 | `index.html` | `https://yt-qi.github.io/imgcrypt/` |
| 批量图片加密 | `Image-multiEncrypt_pc-only.html` | `https://yt-qi.github.io/imgcrypt/Image-multiEncrypt_pc-only.html` |
| 批量图片解密 | `Image-multiDncrypt_pc-only.html` | `https://yt-qi.github.io/imgcrypt/Image-multiDncrypt_pc-only.html` |

## 功能说明

- 单张解密页支持读取嵌入密码的加密 PNG 图片。
- 批量加密页支持一次导入多张图片，处理完成后下载包含所有加密图的 zip 压缩包。
- 批量解密页支持一次导入多张加密图片，处理完成后下载包含所有解密图的 zip 压缩包。
- 批量解密时，若图片内嵌密码会自动识别；未嵌入密码的图片使用页面中手动输入的密码。

## 注意事项

- 加密后的图片应保持 PNG 格式。
- 不要压缩、转格式或通过会改写图片内容的软件转发加密图，否则可能无法解密还原。
- 批量工具面向 PC 浏览器使用。
