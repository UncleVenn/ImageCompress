<!--
 * @Author: 张文Uncle
 * @Email: 861182774@qq.com
 * @Date: 2019-09-29 14:00:48
 * @LastEditors: 张文Uncle
 * @LastEditTime: 2019-09-29 14:00:48
 * @Descripttion: 
 -->
# ImageCompress
图片压缩,支持动态图片

```
require "ImageCompress.php";
(new ImageCompress('图片路径','压缩等级 默认0.5(0-1)'))->compressImg('压缩后的文件名,尾缀名可加可不加,该项为空则不保存压缩结果,直接输出');
```
