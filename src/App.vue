<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
@import './scss/index.scss';
body::-webkit-scrollbar {
  width: 6px;
  height: 6px;
  background-color: #F5F5F5;
}
body::-webkit-scrollbar-thumb {
  border-radius: 5px;
  box-shadow: inset 0 0 5px rgba(0,0,0,0.3);
  background-color: rgba(7,170,247,0.7);
}
body::-webkit-scrollbar-track {
  box-shadow: inset 0 0 5px rgba(0,0,0,0.3);
  background: #fff;
}
*{
  margin: 0;
  padding: 0;
}
body{
  background: #f1f1f1;
  font-family: 'fontHYQiHei';
}
.clearfix::after{
  content:'';
  display: block;
  clear: both;
}
.w960{
  width: 960px;
  margin:0 auto;
}
.w650{
  width: 650px;
  margin:0 auto;
}
.fl{
  float: left;
}
.fr{
  float: right;
}
.title{
  margin-top: 20px;
  font-weight: normal;
  padding-left: 10px;
  border-left:2px solid rgb(54, 52, 54);
  line-height: 1.5;
}
.song-cover {
  width: 50px;
  height: 50px;
  display: block;
}
ul{
  list-style: none;
}
.el-table {
  text-align: center;
}
.el-table th > .cell {
  text-align: center;
}
.el-table td > .cell {
  text-align: center;
}
.el-card {
  margin-top: 15px;
  min-height: calc(100vh - 200px);
}
.page-wrap {
  margin-top: 10px;
  width: 500px;
  margin-right: auto;
  margin-left: auto;
}
</style>
<style lang="scss">
.detail-content {
  display: flex;
  flex-direction: column;
  img {
    display:block;
    max-width: 900px;
    margin: 0 auto;
  }
  p {
    text-indent: 2em;
    color: #000;
    font-size: 12px;
    line-height: 2;
    margin-top:10px;
  }
  h1,h2,h3,h4{
    font-weight: 500;
  }
  h4 {
    font-size: 18px;
  }
  span {
    line-height: 2;
    font-size: 12px;
    color:rgb(34,34,34);
  }
}
</style>

