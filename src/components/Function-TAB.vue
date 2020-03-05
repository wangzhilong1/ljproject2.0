<!--
@Author:wangzhilong
@data:2020.03.04
@E-mail:15000367643@139.com
@实现功能：菜单栏
-->
<template>
<div id="TAB-dv">
    <div class="Project-management-area">
        <button class="project-but">项目</button><!--项目布局列表-->
        <button class="layout-but">临建布置</button><!--临建布置功能-->
        <button class="data-but">数据基础</button><!--基础数据控制按钮-->
    </div>
<div class="GNCD"><!--功能菜单栏 -->
    <div  class="xbsj-list-item">
        <span class="list-name">测量</span>
    </div>
    <div  class="xbsj-list-item">
        <span class="list-name"></span>
    </div>
    <div  class="xbsj-list-item">
        <span class="list-name"></span>
    </div>
    <div  class="xbsj-list-item">
        <span class="list-name"></span>
    </div>
    <div  class="xbsj-list-item">
        <span class="list-name"></span>
    </div>
</div>
</div>
</template>

<script>
    export default {
        name: "Function-TAB"
    }
</script>

<style scoped>
    #TAB-dv{
        width: 100%;
        height: 137px;
        background: #474747;
    }
    .Project-management-area{
        width: 100%;
        height: 41px;
        margin-top: 0;

    }
    .GNCD{
        width: 100%;
        height: 91px;
        background: #515a6e ;
        margin-top: 41px;
    }
    .list-name{
        display: inline-block;
        min-width: 57px;
        /* padding: 0 5px; */
        height: 18px;
        background: rgba(71, 71, 71, 1);
        border-radius: 3px;
        font-size: 12px;
        /* font-weight: bold; */
        color: rgba(221, 221, 221, 1);
        text-align: center;
        position: absolute;
        left: 16px;
        top: -2px;
    }
    .xbsj-list-item{
        width: auto;
        height: 72px;
        position: relative;
        margin: 12px 5px;
        border-right: 2px solid rgba(71, 71, 71, 1);
        padding-right: 25px;
        padding-left: 12px;
        display: flex;
    }
</style>
