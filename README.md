小贝互助

node版本 8.11.3

自定义组件为了防止和antd的UI组件的命名混淆，我们的组件的命名前加H，如HHeader

dataDeal 对于数据处理在此文件夹（基于redux,让他更简易使用）
    initData 对某页面 定义初始数据 + 为其创建reducer
    dealCenter 对某页面的数据进行处理，如数据校验，ajax
详细使用用法，读懂实名认证页面（authentication），你就什么都会了

注意被高阶组件包裹的组件，其父组件无法获取他的ref属性，也就是说无法直接调用该组件的方法了，破解办法https://www.jianshu.com/p/2609fd3777cd


queryUserInfo中部分字段映射

actorType: 0: 普通用户,1: hr角色, 2: tl角色,

userType   1:个人用户数据, 2: 企业用户数据;