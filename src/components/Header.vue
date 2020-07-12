<template>
  <div class="header clearfix">
    <img src="../assets/cnode.svg"/>
    <input type="text" value="搜索" />
    <ul>
      <li><a href="#">首页</a></li>
      <li><a href="#">新手入门</a></li>
      <li><a href="#">API</a></li>
      <li><a href="#">关于</a></li>
      <li><a href="#">注册</a></li>
      <li><a href="#">登录</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
.clearfix:after{
  content: '';
  display: block;
  clear: both;
}
.header{
  height: 50px;
  background: #444;
  font-size: 14px;

  position: relative;
}
input{
  border: 1px solid #888;
  padding: 3px 7px;
  width: 206px; height: 20px;
  background: #888;
  border-radius: 15px;
  color: #ddd;

  position: absolute;
  top: 12px;
}
input:focus{
  outline: none;
  background: white;
  transition: all 0.3s;
  color: #444;
}
img{
  max-width: 120px;
  margin: 9px 10px 0 50px;
}
ul{
  list-style: none;
  float: right;
  margin: 13px 0;
  margin-right: 70px;
}
li{
  display: inline-block;
  color: #ccc;
  padding: 0 15px;
}
a{
  text-decoration: none;
  color: #ccc;
  font-weight: bold;
}
a:hover{
  color: white;
}

</style>>