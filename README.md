# wl_bmoji
Waline|B站表情

~~前作：https://github.com/s-019/W-b~~    
现在Bmoji已Pr到 [walinejs/emojis](https://github.com/walinejs/emojis) 仓库中

## 使用Bmoji
### Jsdelivr(Gcore)
> https://gcore.jsdelivr.net/gh/w0oo/wl_bmoji@bmoji1.2/bmoji/

### Unpkg（官用）
> https://unpkg.com/@waline/emojis@1.1.0/bmoji/

#### 使用方法
请阅读 [Waline自定义表情](https://waline.js.org/guide/client/emoji.html)
‘‘

Waline.init({
  el: '#waline',
  serverURL: 'https://你的Waline',

  // 设置 emoji 为微博与哔哩哔哩
  emoji: [
    'https://unpkg.com/@waline/emojis@1.1.0/bmoji/',
  ],
});

‘‘

## 更多
[walinejs/emojis](https://github.com/walinejs/emojis) Pr 的仓库：    
> [w0oo/emojis](https://github.com/w0oo/emojis)

提出建议：Nick8_1@qq.com
