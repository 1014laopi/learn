# ShadowDOM的意义及用法
内部节点的信息封装起来，同时可以渲染出来，W3C提出了ShadowDom的概念。它可以使一些DOM节点在特定范围内可见，在网页的DOM树中不可见，但是网页渲染的结果包含了这些节点。
## 怎么渲染ShadowDom的div的样式
(Pseudo Selector)伪类选择器
> 
    video::-webkit-media-controls-panel{
        background-color: red;
    }