<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>深海遗梦·千禧年新闻门户</title>
    <style>
        /* 完全复古风格：宋体，无圆角，无渐变，紧凑行距，老式数码感 */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            background: #8C8C8C;
            font-family: '宋体', 'SimSun', 'Times New Roman', serif;
            font-size: 13px;
            line-height: 1.3;
            color: #222;
            padding: 20px;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            background: #F5F0E7;
            border: 1px solid #AAA;
            box-shadow: 0 0 6px rgba(0,0,0,0.1);
        }
        .top-nav {
            background: #E0D6C8;
            padding: 6px 12px;
            border-bottom: 2px solid #BBAA99;
            font-size: 12px;
        }
        .top-nav ul {
            list-style: none;
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
            margin: 0;
        }
        .top-nav li { display: inline; white-space: nowrap; }
        .top-nav a { color: #003366; text-decoration: none; }
        .top-nav a:hover { text-decoration: underline; color: #CC0000; }
        .row { display: flex; background: #FFFFFF; }
        .left-sidebar {
            width: 220px;
            background: #FCF7E8;
            border-right: 2px solid #CC3333;
            padding: 12px 10px;
            font-size: 12px;
        }
        .right-main {
            flex: 1;
            background: #FFFFFF;
            padding: 12px 18px;
        }
        .block-title {
            font-size: 18px;
            font-weight: bold;
            color: #CC0000;
            border-bottom: 1px solid #CC0000;
            margin: 10px 0 12px 0;
            padding-bottom: 2px;
        }
        .block-title-small {
            font-size: 16px;
            font-weight: bold;
            color: #CC0000;
            border-left: 4px solid #CC0000;
            padding-left: 8px;
            margin: 12px 0 10px 0;
        }
        .news-item {
            margin-bottom: 12px;
            padding-left: 14px;
            position: relative;
        }
        .news-item:before {
            content: "●";
            color: black;
            font-size: 11px;
            position: absolute;
            left: 0;
            top: 0;
        }
        .news-title a { color: #0000CC; text-decoration: underline; }
        .news-meta { font-size: 11px; color: #555; }
        /* 缩略图样式 - 统一显示“图片已丢失” */
        .thumb {
            border: 1px solid #CCCCAA;
            background: #F0ECD8;
            display: inline-block;
            padding: 3px;
            margin: 5px 8px 5px 0;
            font-size: 11px;
            text-align: center;
            float: left;
        }
        .thumb-square, .thumb-landscape, .thumb-portrait {
            width: 80px;
            height: 80px;
            background: #D6CFB0;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: '宋体', monospace;
            color: #886644;
        }
        /* 统一所有缩略图尺寸为小方块，显示“图片已丢失” */
        .thumb-landscape { width: 80px; height: 80px; }
        .thumb-portrait { width: 80px; height: 80px; }
        .thumb-square { width: 80px; height: 80px; }
        .clearfix::after { content: ""; clear: both; display: table; }
        /* 广告网格 */
        .ad-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 15px 0;
        }
        /* 广告方块样式：统一显示“链接已丢失” */
        .ad-linklost {
            width: 85px;
            height: 85px;
            background: white;
            border: 1px solid #AA9F7E;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: '宋体', 'SimSun', serif;
            font-size: 13px;
            color: #CC0000;
            text-align: center;
            cursor: default;
        }
        .reply-item {
            margin-bottom: 12px;
            padding-left: 14px;
            position: relative;
            border-bottom: 1px dotted #E0D6C8;
            padding-bottom: 6px;
        }
        .reply-item:before { content: "○"; color: #666; position: absolute; left: 0; top: 0; font-size: 11px; }
        .reply-author { font-weight: bold; color: #336699; }
        .sidebar-footer { margin-top: 25px; padding-top: 12px; border-top: 1px dashed #CC9966; font-size: 11px; }
        .icon-row { display: flex; gap: 8px; margin: 8px 0; }
        .func-icon { background: #E0D6C8; padding: 3px 8px; font-size: 11px; display: inline-block; border: 1px solid #AA9F7E; }
        hr { border: none; border-top: 1px dotted #CCCCAA; }
        a { text-decoration: none; }
        ul, li { list-style: none; }
    </style>
</head>
<body>
<div class="container">
    <div class="top-nav">
        <ul>
            <li><a href="#">首 页</a></li><li><a href="#">新 闻</a></li><li><a href="#">娱 乐</a></li>
            <li><a href="#">体 育</a></li><li><a href="#">论 坛</a></li><li><a href="#">博 客</a></li>
            <li><a href="#">相 册</a></li><li><a href="#">留 言</a></li><li><a href="#">邮 箱</a></li>
            <li><a href="#">聊天室</a></li><li><a href="#">下载中心</a></li><li><a href="#">同学录</a></li>
            <li><a href="#">在线音乐</a></li>
        </ul>
    </div>

<div class="row">
        <div class="left-sidebar">
            <div style="margin-bottom: 15px; text-align: right; font-size: 11px;">
                <a href="#" style="color:#333;">登录</a> | <a href="#" style="color:#333;">注册</a>
            </div>
            <div class="block-title-small">📢 热门广告</div>
            <div class="ad-grid">
                <div class="ad-linklost">链接已丢失</div>
                <div class="ad-linklost">链接已丢失</div>
                <div class="ad-linklost">链接已丢失</div>
                <div class="ad-linklost">链接已丢失</div>
                <div class="ad-linklost">链接已丢失</div>
            </div>
            <div class="block-title-small">🔗 友情链</div>
            <ul style="margin-left: 12px;">
                <li>▶ <a href="#">小雨的贴吧 (建设中)</a></li>
                <li>▶ <a href="#">2009互联网档案馆</a></li>
                <li>▶ <a href="#">无名小站</a></li>
                <li>▶ <a href="#">奇摩家族</a></li>
            </ul>
            <div class="sidebar-footer">
                <div style="font-weight: bold;">📞 客服专线</div>
                <div>0800-123-456</div>
                <div>📠 传真: (02) 8765-4321</div>
                <div class="icon-row">
                    <span class="func-icon">✉️ 写信</span>
                    <span class="func-icon">🖨️ 打印</span>
                    <span class="func-icon">🔍 搜索</span>
                    <span class="func-icon">⭐ 收藏</span>
                </div>
                <div>© 梦之论坛 旧时光</div>
            </div>
        </div>
<div class="right-main">
            <div style="text-align: center; margin: 5px 0 10px;">
                <h2 style="font-size: 28px; font-family:'宋体';">✦ 梦之论坛 ✦</h2>
                <div style="font-size: 12px; color: #666;">—— 那些想说却不敢说的秘密 ——</div>
            </div>
            <div class="block-title">▍ 求助 / 寻人启事</div>
            <div class="news-item">
                <div class="news-title"><a href="#">【求助】还有人在用这个论坛吗？我想找一个小学同学</a></div>
                <div class="news-meta">深海旅人 | 发表于 2009-03-21 22:14 | 点击: 143</div>
            </div>
            <div class="clearfix">
                <div class="thumb thumb-landscape" style="float:left; margin-right: 12px;">
                    <div>图片已丢失</div>
                </div>
                <div style="font-size:13px; line-height:1.4;">
                    今天回老家，居然还能登上这个论坛。<br>
                    突然很想找一个人，小学时候在贴吧认识的网友，她叫 <strong>“雨水”</strong>。<br>
                    我们一起玩过一个叫《地狱之躯》的小游戏。<br>
                    后来就失联了。<br>
                    如果你认识她，或者你就是她，请私信我。
                </div>
</div>
            <div class="thumb thumb-portrait" style="float:right; margin: 8px 0 8px 12px;">
                <div>图片已丢失</div>
            </div>
            <div style="margin-top: 12px;">
                这是她当年给我的贴吧链接： <a href="#" style="color:#0000CC; text-decoration:underline;">【小雨の秘密基地】（以后会做）</a><br>
                <span style="font-size:11px; color:#886644;">※ 链接还没做好，以后会指向一个真实的贴吧页面。</span><br><br>
                不知道她现在过得好不好…… ☹
            </div>
            <div class="thumb thumb-square" style="float:left; margin: 10px 12px 5px 0;">
                <div>图片已丢失</div>
            </div>
            <div class="clearfix"></div>
            <div class="block-title" style="margin-top: 20px;">▍ 网友回复</div>
            <div class="reply-item"><span class="reply-author">过路云</span> <span class="news-meta">2009-03-22 09:13</span><div class="reply-content">这个论坛好古老了，居然真有人。</div></div>
            <div class="reply-item"><span class="reply-author">北方的狼</span> <span class="news-meta">2009-03-22 14:02</span><div class="reply-content">在网上找一个人不就是大海捞针吗？</div></div>
            <div class="reply-item"><span class="reply-author">向日葵</span> <span class="news-meta">2009-03-23 00:17</span><div class="reply-content">加油哦 ☹</div></div>
            <div class="reply-item"><span class="reply-author">罪</span> <span class="news-meta">2009-03-23 00:17</span><div class="reply-content">加油啊</div></div>
            <div class="reply-item"><span class="reply-author">匿名</span> <span class="news-meta">2009-03-23 19:40</span><div class="reply-content">顶</div></div>
            <div class="thumb thumb-landscape" style="margin: 15px 10px 5px 0; float: left;">
                <div>图片已丢失</div>
            </div>
            <div style="clear:both;"></div>
            <div style="font-size: 11px; text-align: center; border-top: 1px solid #DDCCAA; margin-top: 20px; padding-top: 10px;">
                ☆ 本论坛建于2005年 ☆ 最佳分辨率1024*768 ☆<br>
                © 梦之论坛 讨论那些想说却不敢说的秘密
            </div>
        </div>
    </div>
</div>
</body>
</html>
