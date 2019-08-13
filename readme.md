# EasyUIEx 


EasyUIEx 是针对使用 `jQuery EasyUI` 框架开发的扩展性插件，主要对`EasyUI`框架的常用功能进行了封装和扩展。着重在CRUD方面进行了封装扩展，能大大提高`EasyUI`的易用性，简化操作的复杂性，并提供附加功能。

EasyUIEx is for the use of ` jQuery EasyUI`  framework for the development of extensible plug-ins, mainly for common functions `EasyUI` framework encapsulates and expanded. Focusing encapsulates CRUD aspect extensions, can greatly increase the `EasyUI` usability, simplify operational complexity, and provide additional functionality.

Test EasyUI version: `1.4.X`，`1.5.X`

## Feature/特征

- **中文**

 1. 遵循 Easy 的原则，目标是简化一切可以简化的部分，为一切不具备的需求提供扩展。

 2. 在进行项目开发时使用 `jQuery EasyUI + EasyUIEx` 架构能大大简化EasyUI框架使用的复杂性，尤其在各种数据网格的CRUD方面，做了高度封装。

 3. `jQuery EasyUI + EasyUIEx ` 的架构产生于企业开发实践，本身开源，对修改和添加开放，所以也欢迎在项目应用中产生的优秀实践继续对EasyUIEx进行扩展升级。

- **English**

 1. Easy to follow the principle, the goal is to simplify everything can simplify part, do not have to provide extended to all the needs.

 2. Use `jQuery EasyUI + EasyUIEx` architecture can greatly simplify the complexity of EasyUI framework used during project development, especially in terms of a variety of data CRUD grid, made a highly packages.

 3. `JQuery EasyUI + EasyUIEx` architecture produced in the enterprise development practice itself open source, open to modifications and additions, so it is welcome good practice generated in the project applications continue to expand EasyUIEx upgrade.


## Getting Started/开始使用

1. Download

 ```HTML
<!-- EasyUI CSS -->
<link rel="stylesheet" type="text/css" href="easyui/themes/bootstrap/easyui.css" id="themeLink">
<link rel="stylesheet" type="text/css" href="easyui/themes/icon.css">

<!-- EasyUI JS & Extension JS...-->
<script type="text/javascript" src="easyui/jquery.min.js"></script>
<script type="text/javascript" src="easyui/jquery.easyui.min.js"></script>
<script type="text/javascript" src="easyui/locale/easyui-lang-zh_CN.js"></script>

<!-- **EasyUIEx** -->
<link rel="stylesheet" type="text/css" href="easyuiex/css/easyuiex.css">
<script type="text/javascript" src="easyuiex/easy.easyuiex.min.js"></script>
<script type="text/javascript" src="easyuiex/easy.easyuiex-validate.js"></script>
<!-- EasyUIEx 'easy.jquery.edatagrid.js' instead of 'jquery.edatagrid.js' -->
<script type="text/javascript" src="easyuiex/easy.jquery.edatagrid.js"></script>
<!-- Language file -->
<script type="text/javascript" src="easyuiex/lang/easy.easyuiex-lang-zh_CN.js"></script> 
```

2. Use API method
 
 - **Directly within uiEx namespace**
 
   `uiEx.{methodName}(selector, [param1], ....);` 
   
    ```JavaScript
   uiEx.clearForm('#userForm')；

   uiEx.treeChk(
     "#rightsTree",
     {
        url:"do/menuJson.json"
     },
     [11]
   );
   ```
   
 - **Within jQuery function extend**
 
   `$(selector).{methodName}([param1], ....);`
  
    ```JavaScript
    $('#userForm').clearForm();
  
    $("#rightsTree").treeChk(
        {
            url:"do/menuJson.json"
        },
        [11]
    );
    ```

## API online/在线 API 速览

[中文 API 在线速览](http://www.easyproject.cn/easyuiex/doc/easyuiex-api_zh_CN.html)


[English API online](http://www.easyproject.cn/easyuiex/doc/easyuiex-api_en.html)

## Use document/使用文档

### 中文

[中文详细使用文档](doc/readme_zh_CN.md)

[官方主页](http://www.easyproject.cn/easyuiex/zh-cn/index.jsp '官方主页')

[留言评论](http://www.easyproject.cn/easyuiex/zh-cn/index.jsp#donation '留言评论')

如果您有更好意见，建议或想法，请联系我。

### English

[English detailed documentation](doc/readme_en.md)

[The official home page](http://www.easyproject.cn/easyuiex/en/index.jsp 'The official home page')

[Comments](http://www.easyproject.cn/easyuiex/en/index.jsp#donation 'Comments')

If you have more comments, suggestions or ideas, please contact me.


## EasyUIEx Demo：

[EasyUIEx demo online](http://www.easyproject.cn/easyUIExDemo 'EasyUIEx demo')

[EasyEE](http://www.easyproject.cn/easyee 'EasyEE')


## End

Email：<inthinkcolor@gmail.com>

[http://www.easyproject.cn](http://www.easyproject.cn "EasyProject Home")


**Donation/捐助:**

<a href="http://www.easyproject.cn/donation">
<img alt="
支付宝/微信/QQ/云闪付/PayPal 扫码支付" src="http://www.easyproject.cn/thanks/donation.png"  title="支付宝/微信/QQ/云闪付/PayPal 扫码支付"  height="320" width="320"></img></a>
<div>支付宝/微信/QQ/云闪付/PayPal</div>

<br/>

我们相信，每个人的点滴贡献，都将是推动产生更多、更好免费开源产品的一大步。

**感谢慷慨捐助，以支持服务器运行和鼓励更多社区成员。**

We believe that the contribution of each bit by bit, will be driven to produce more and better free and open source products a big step.

**Thank you donation to support the server running and encourage more community members.**

