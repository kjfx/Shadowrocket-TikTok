# Shadowrocket TikTok配置，iphone tiktok不拔卡教程，ios免拔卡

- Shadowrocket TikTok视频教程：https://youtu.be/p4dYq7xEPbg <br>
电报交流群：https://t.me/kejifx


### 操作步骤<br>
1、下载 Shadowrocket 和 TikTok，需要用美区AppleID下载，下载完先不要打开TikTok。<br>
- 注册美国AppleID教程：https://github.com/kjfx/AppleID<br>

2、打开Shadowrocket → 配置 → default.conf → 编辑配置 → HTTPS解密 → 开启HTTPS解密 → 生成新的CA订书 → 生成新的CA订书 → 安装证书 → 允许 → 打开设置 → 已下载描述文件 → 安装 → 安装 → 安装 → 完成 → 通用 → 关于本机 → 证书信任设置 → 开启信任Shadowrocket证书 → 继续 → 打开Shadowrocket → 关闭 → √ → √ → 配置 → default.conf → 编辑纯文本 → 滚动条拉到最下面 <br>
在最下面粘贴以下代码：

    [URL Rewrite]
    (?<=_region=)CN(?=&) JP 307
    (?<=&mcc_mnc=)4 2 307
    ^(https?:\/\/(tnc|dm)[\w-]+\.\w+\.com\/.+)(\?)(.+) $1$3 302
    (?<=\d\/\?\w{7}_\w{4}=)1[6-9]..(?=.?.?&) 18.4 307

    [MITM]
    hostname = *.tiktokv.com,*.byteoversea.com,*.tik-tokapi.com
    
再点击保存。

3、在Shadowrocket添加节点，开启科学上网。<br>

- Shadowrocket添加节点视频教程：https://youtu.be/2rXuAw_8nac <br>

4、打开TikTok App 即可实现免拔卡看，可以登录，评论。

### 如何更改国家：
默认是日本区，可以更改这行代码中的JP (?<=_region=)CN(?=&) JP 307<br>
美国示例： (?<=_region=)CN(?=&) US 307<br>
英文简写 JP（日本）｜KR（韩国）｜UK（英国）｜US（美国）｜TW（中国台湾）

### IOS看不了TikTok解决方法：
1、下载TikTok 21.1.0版本使用。<br>
2、插上手机卡，不要拔卡，看最新视频教程操作。<br>
教程：https://www.youtube.com/c/%E7%A7%91%E6%8A%80%E5%88%86%E4%BA%AB/search?query=tiktok%20ios<br>
