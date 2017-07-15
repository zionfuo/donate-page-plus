# Donate-Page simple

![](https://ws3.sinaimg.cn/large/c38cd5eagy1fhkm3c6er8g20a508vb2a.gif)

#### 直接 Fork 之后需要修改以下内容为你的账户

	/script.js:4-6 对应账户的二维码路径

	/index.html:28 PayPal.me 改为现在收款页面，这样可以删除原来的按钮方式了。

	/index.html:37 `<input id="btc-key" type="text" value="比特币账号" readonly="readonly">`

#### 针对不同项目可以直接在 URL 加入项目参数和金额，不过仅仅作用于 PayPal 方式.

`https://cdn.rawgit.com/zionfuo/donate-page-plus/6a958564/simple/index.html?item='donate-page&price=2'`


#### 使用 `iframe` 嵌入页面的代码，高度至少 `240px`，宽度至少 `310px`！

```
<iframe src="https://cdn.rawgit.com/zionfuo/donate-page-plus/6a958564/simple/index.html" style="overflow-x:hidden;overflow-y:hidden; border:0xp none #fff; min-height:240px; width:100%;"  frameborder="0" scrolling="no"></iframe>
```

### License

Released under the MIT license.
