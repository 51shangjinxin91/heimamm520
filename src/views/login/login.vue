<template>
    <div class="login.box">
        <div class="form-box"></div>
        <img class="login-pic" src="../../assets/login_banner_ele.png" alt="">
    </div>
</template>

<script>
export default {
    name: "login"
};
</script>

<style lang="less">
/* lang="less" 多层嵌套,变量计算 */
.login-box {
    /* 开启弹性布局 */
    display: flex;
    /* 上下居中 */
    align-items: center;
    // 左右均分
    justify-content: space-around;
    // 背景线性渐变
    background: linear-gradient(225deg,rgba(20,147,250,1),rgba(1,198,250,1));
    .from-box {
        width: 478px;
        height: 550px;
        background: #f5f5f5;
    }
    .login-pic {
        
    }
}
</style>