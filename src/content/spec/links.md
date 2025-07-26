# 友情链接

欢迎来到我的友情链接页面，以下是支持和推荐的优秀站点！
---
<style>
  .friend-link-card {
    display: flex;
    align-items: center;
    border: 1px solid #ddd;
    border-radius: 10px;
    width: 360px;
    height: 90px;
    padding: 10px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    overflow: hidden;
    box-sizing: border-box;
    margin-bottom: 20px;
  }
  
  .friend-link-avatar {
    margin-right: 10px;
    flex-shrink: 0;
    display: block;
    position: relative;
    z-index: 10;
  }
  
  .friend-link-avatar img {
    width: 36px;
    height: 36px;
    border-radius: 50%;
    display: block;
    cursor: pointer;
    -webkit-user-select: none;
    user-select: none;
    -webkit-touch-callout: none;
    touch-action: manipulation;
  }
  
  .friend-link-content {
    flex-grow: 1;
    overflow: hidden;
  }
  
  .friend-link-content a {
    text-decoration: none;
    color: #333;
    display: block;
  }
  
  .friend-link-title {
    margin: 0 0 3px 0;
    font-size: 1rem;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }
  
  .friend-link-desc {
    margin: 0;
    font-size: 0.8rem;
    color: #555;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }
</style>

<div class="friend-links-container" style="display: flex; flex-wrap: wrap; gap: 20px 30px;">

  <!-- 第一个卡片 -->
  <div class="friend-link-card">
    <a href="https://blog.094521.xyz/" target="_blank" rel="noopener noreferrer" class="friend-link-avatar">
      <img src="https://pc.094521.xyz/favicon.jpg" alt="ドリームトレイン Blog 的 Logo" style="width: 36px; height: 36px; border-radius: 50%; display: block; cursor: pointer;">
    </a>
    <div class="friend-link-content">
      <a href="https://blog.094521.xyz/" target="_blank" rel="noopener noreferrer">
        <h3 class="friend-link-title">ドリームトレイン Blog</h3>
      </a>
      <p class="friend-link-desc">一个摆烂的年更Blog</p>
    </div>
  </div>

  <!-- 第二个卡片 -->
  <div class="friend-link-card">
    <a href="https://github.com" target="_blank" rel="noopener noreferrer" class="friend-link-avatar">
      <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub 的 Logo" style="width: 36px; height: 36px; border-radius: 50%; display: block; cursor: pointer;">
    </a>
    <div class="friend-link-content">
      <a href="https://github.com" target="_blank" rel="noopener noreferrer">
        <h3 class="friend-link-title">GitHub</h3>
      </a>
      <p class="friend-link-desc">开源项目托管平台。</p>
    </div>
  </div>

  <!-- 第三个卡片 -->
  <div class="friend-link-card">
    <a href="https://stackoverflow.com" target="_blank" rel="noopener noreferrer" class="friend-link-avatar">
      <img src="https://cdn.sstatic.net/Sites/stackoverflow/Img/favicon.ico?v=ec617d71519" alt="Stack Overflow 的 Logo" style="width: 36px; height: 36px; border-radius: 50%; display: block; cursor: pointer;">
    </a>
    <div class="friend-link-content">
      <a href="https://stackoverflow.com" target="_blank" rel="noopener noreferrer">
        <h3 class="friend-link-title">Stack Overflow</h3>
      </a>
      <p class="friend-link-desc">程序员问答社区</p>
    </div>
  </div>

</div>

<script>
// 确保所有链接在新窗口打开，并且阻止图片放大
document.addEventListener('DOMContentLoaded', function() {
  // 选择所有带有 href 和 target="_blank" 的链接
  const links = document.querySelectorAll('a[href][target="_blank"]');
  
  links.forEach(link => {
    const img = link.querySelector('img');
    if (img) {
      // 阻止图片默认行为（放大）
      img.addEventListener('touchstart', function(e) {
        e.preventDefault();
      });
      
      // 阻止长按菜单
      img.addEventListener('contextmenu', function(e) {
        e.preventDefault();
      });
      
      // 确保点击图片时触发链接跳转
      img.addEventListener('click', function(e) {
        e.stopPropagation();
        window.open(link.href, '_blank');
      });
    }
  });
});
</script>
---
# 互换友链格式如下：
暂时不会整Astro评论，换友链
[发送邮件](mailto:skyvale@163.com?subject=互换友链&body=名称\n图标\n简介\n链接)

```

名称：逐梦逸风

图标(需使用URL)：https://blog.966911.xyz/_astro/txt.oS-3Xo7D_BJ34H.webp

简介：记录追梦路上的点滴感悟。分享生活、学习与成长的故事，在微风中逐梦前行。

链接：https://blog.966911.xyz/

```

