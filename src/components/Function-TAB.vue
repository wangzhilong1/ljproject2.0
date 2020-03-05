<!--
    *@Author:wangzhilong
    *@data:2020.03.04
    *@E-mail:wangzhilongAIGIS@163.com
    *@实现功能：菜单栏
-->
<template>
<div id="TAB-dv">
    <div class="Project-management-area">
        <button class="project-but" v-on:click="xm">项目</button><!--项目布局列表-->
        <button class="layout-but" v-on:click="ljbj">临建布置</button><!--临建布置功能-->
        <button class="data-but" v-on:click="jcsj">数据基础</button><!--基础数据控制按钮-->
    </div>
    <div class="GNCD"><!--功能菜单栏 -->
    <div  class="list-item1">
        <span class="list-name">测量</span>
        <div class="item-but">
            <div class="point-but">
                <img src="../assets/images/img/point.png" style="width: 37px;height: 37px">
                <span class="select"><img src="../assets/images/img/xiatankuang.png"></span>

            </div>
            <span class="item-name1">点位</span>
        </div>

        <div class="item_but">
            <div class="distance_but">
                <img src="../assets/images/img/distance.png" style="width: 37px;height: 37px">
                <span class="select"><img src="../assets/images/img/xiatankuang.png"></span>

            </div>
            <span class="item-name1">点位</span>
        </div>

    </div>
    <div  class="list-item">
        <span class="list-name">模型</span>
        <div class="item-but">

        </div>
    </div>
    <div  class="list-item3">
        <span class="list-name">标注</span>
        <div class="item-but">

        </div>
    </div>
    <div  class="list-item4">
        <span class="list-name">其他</span>
        <div class="item-but">

        </div>

    </div>
</div>
</div>
</template>

<script>
    import '../../public/static/js/jquery-3.0.0'
    export default {
        name: "Function-TAB",
        // data:{
        //
        // }
        methods:{
        xm:function () {

        }
        }
    }
</script>

<style scoped>
    .item-name1{
        width: 60px;
        height: 23px;
        font-size: 14px;
        color: #FFFFFF;
        margin-top: 80px;
        /*margin-left: 16px;*/
        text-align: center;
    }
    #TAB-dv{
        width: 100%;
        height: 137px;
        background: #474747;
        z-index: 9999;
        position: relative
    }
    .Project-management-area{
        width: 100%;
        height: 41px;
        margin-top: 0;
        border:0;
        color: #f0f0f0;
    }
    button{
        float: left;
        padding: 10px 20px;
        list-style: none;
        font-size: 14px;
        /* border: 1px solid; */
        cursor: pointer;
        background-color: #474747;
        border: 0.1px;
        color: #f0f0f0;
    }
    .GNCD{
        width: 100%;
        height: 96px;
        display: flex;
        overflow-x: visible;
        overflow-y: hidden;
        -moz-user-select: none;
        -webkit-user-select: none;
        user-select: none;
        background: #515a6e;
    }
    .list-item1{
        width: auto;
        height: 72px;
        position: relative;
        margin: 12px 5px;
        border-right:rgba(107, 107, 107, 1);
        display: flex;
    }
    .list-name{
        width:57px;
        height:18px;
        font-size:12px;
        font-weight:bold;
        margin-left:16px;
        color:rgba(221, 221, 221, 1);
        background-color:#474747;
        top:-2px;
        text-align:center;
    }
    .select{
        display: inline-block;
        width: 9px;
        height: 8px;
        cursor: pointer;
    }
    .item-but{
        width: auto;
        height: 72px;
        position: relative;
        margin: 12px 5px;
        border-right: 2px solid rgba(71, 71, 71, 1);
        padding-right: 25px;
        padding-left: 12px;
        display: flex;
    }
    .point-but{

        background-size: contain;
        cursor: pointer;
        margin-top: 30px;
        margin-left: -16px;
    }
    /*.item-name{*/
    /*    position: absolute;*/
    /*    bottom: 0;*/
    /*    display: inline-block;*/
    /*    width: 100%;*/
    /*    font-size: 12px;*/
    /*    font-weight: bold;*/
    /*    !* color: rgba(221, 221, 221, 1); *!*/
    /*    text-align: center;*/
    /*    margin-top: 62px;*/
    /*}*/
    .item-but{
        position: absolute;
        bottom: 0;
        display: inline-block;
        width: 100%;
        font-size: 12px;
        font-weight: bold;
        /* color: rgba(221, 221, 221, 1); */
        text-align: center;
    }
</style>
