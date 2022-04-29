---
title: 友链
comments: false
date: 2021-02-19 22:10:17
---

# 好盆友滴友链！

<!-- more -->

<div id="qexo-friends"></div>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/qexo-static@1.1.3/hexo/friends/friends.css"/>
<script src="https://cdn.jsdelivr.net/npm/qexo-static@1.1.3/hexo/friends/friends.js"></script>
<script>loadQexoFriends("qexo-friends", "https://admin.imfmkli.top")</script>

网站要求：
要开启https，开启强制https
博客存活一个月以上
不允许色情，暴力，等违法的内容的博客加入友链

名字:鸽子博客
链接:[https://blog.imfmkli.top](https://blog.imfmkli.top)
简介:咕咕咕
图片:[https://alpha-q3.sourcegcdn.com/2022/03/30/NAGqZhi7.jpg](https://alpha-q3.sourcegcdn.com/2022/03/30/NAGqZhi7.jpg)

自助添加友链：（需要审核）

<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

<script>
    var i = 1;
    $(document).ready(function(){
      $("button").click(function(){
        var webname = document.getElementById("firstname").value;
        var weburl = document.getElementById("lastname").value;
        var image = document.getElementById("image").value;
        var miaoshu = document.getElementById("miaoshu").value;
        if (i>1) {
          alert("提交过一次拉！");
          return false;
        };
        i++;
        $.post("https://admin.imfmkli.top/pub/ask_friend/",
        {
          name:webname,
          url:weburl,
          image:image,
          description:miaoshu,
        },
        function(data,status){
          alert("已提交\n返回的数据：" + data + "\n状态：" + status);
        });
      });
    });
</script>

<div class="mdui-container">
    <div class="mdui-textfield">
      <label class="mdui-textfield-label">站站名字</label>
      <input class="mdui-textfield-input" type="text" id="firstname"/>
    </div>
    <div class="mdui-textfield">
      <label class="mdui-textfield-label">链接</label>
      <input class="mdui-textfield-input" type="text" id="lastname"/>
    </div>
    <div class="mdui-textfield">
      <label class="mdui-textfield-label">图片链接</label>
      <input class="mdui-textfield-input" type="text" id="image"/>
    </div>
    <div class="mdui-textfield">
      <label class="mdui-textfield-label">描述</label>
      <input class="mdui-textfield-input" type="text" id="miaoshu"/>
    </div>
    <button class="mdui-btn mdui-btn-raised mdui-ripple mdui-color-red">添加（不要重复提交）</button>
  </div>

---

已审核名单：
1.

---

