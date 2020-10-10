<template>
    <div class="login_container">
        <div class="login_box">
            <!-- 头像区域 -->
            <div class="avatar_box">
                <img src="../assets/logo.png">
            </div>
            <!-- 登录表单 -->
            <el-form label-width="80px">
                <el-form-item label="活动名称">
                <el-input></el-input>
            </el-form-item>
            </el-form>
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style scoped>
.login_container{
    background-color: #2b4b6b;
    height: 100%;
}
.login_box{
    width: 450px;
    height: 300px;
    background-color: #ffff;
    border-radius: 3px;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%,-50%);
}
</style>
