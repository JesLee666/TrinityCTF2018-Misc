双重二维码噩梦。
1. zip里面是二维码的四个部分，需要拼拼图。
2. 扫码可以得到一个百度盘下载地址，是一个巨大的二维码。
3. 二维码扫出来是一个很长很长的base64.
4. 如果你直接解码就错了。因为我说过，base64解码之前一定要看一下是不是三的倍数。否则就悲剧了哟。补完=号再试一试？
PS. 我说过base64是把短的变成长的，每次加密长度增加33.3%.所以解码到长度足够短吧。
不要放弃，扫他一百遍（其实只加密了10此左右）