#### 情报对接

该页面提供对接两种来自微步在线的威胁情报，欢迎社区用户贡献新的情报接口。用户还可以在该页面添加白名单IP，加入白名单的IP攻击蜜罐不会产生告警。

>  为什么要对接威胁情报

对接精准的云端的威胁情报，可对攻击行为进行更准的研判，帮助用户更科学的进行处置。

<img src="https://hfish.net/images/image-20210806093718827.png" alt="image-20210806093718827" style="zoom:50%;" />

对接威胁情报后，当HFish蜜罐捕获到了来自外网的攻击行为，HFish会把在云端查询到的情报在本地缓存3天，保持攻击情报时效性的同时，节省查询次数。


> 对接微步在线本地威胁情报管理平台（TIP）

该接口对接微步商业产品本地威胁情报管理平台（TIP）

<img src="https://hfish.net/images/image-20210806093916207.png" alt="image-20210806093916207" style="zoom:50%;" />


#### 本地白名单

在企业使用使用场景中，可能会有内/外部地址被用于扫描内网资产，这可能会导致HFish蜜罐产生大量误报，为避免此问题，用户可以将内/外部地址一个一行加入白名单中。

用户也可以通过鼠标在【攻击列表】页面的攻击IP上悬停，点击最后一个图标，或在【攻击来源】页面点击相应图标将该IP快速添加到白名单中。

`注意：加入白名单的IP不会再产生告警信息。`
