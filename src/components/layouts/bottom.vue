<template>
  <div class="my-footer">
    <div class="container">
      <hr>
      <div class="row">
        <div class="col-md-3 col-sm-6 block">
          <div class="title">VỀ GAMATRA</div>
          <ul class="list">
            <li><a href="#">Cách thức thanh toán</a></li>
            <li><a href="#">Liên hệ</a></li>
            <li><a href="#">Giới thiệu</a></li>
            <li><a href="#">Blog</a></li>
          </ul>
        </div>
        <div class="col-md-3 col-sm-6 block">
          <div class="title">THỂ LOẠI</div>
          <ul class="list">
            <li><a href="#">Acc Đột Kích Săn Zom</a></li>
            <li><a href="#">Acc Đột kích C4</a></li>
            <li><a href="#">Acc FIFA</a></li>
            <li><a href="#">Thuê Acc PUBG</a></li>
          </ul>
        </div>
        <div class="col-md-3 col-sm-6 block">
          <div class="title">HỖ TRỢ NGƯỜI DÙNG</div>
          <ul class="list">
            <li><a href="#">Trung tâm trợ giúp</a></li>
            <li><a href="#">An toàn mua bán</a></li>
            <li><a href="#">Quy định cần biết</a></li>
            <li><a href="#">Liên hệ hỗ trợ</a></li>
          </ul>
        </div>
        <div class="col-md-3 col-sm-6 block">
          <div class="title">BẢN DI ĐỘNG</div>
          <ul class="list">
          </ul>
        </div>
      </div>
      <hr>
      <div class="my-info row">
        <div class="col-md-6">
          © 2017 - {{this.currTime.getFullYear()}} Design by <a target="_blank" href="http://www.facebook.com/phatamao">Le Tien Phat</a>
        </div>
        <div class="col-md-6">
          <div style="text-align: right;">
            <span><a href=""><i class="fa fa-facebook"></i></a> </span>
            <span><a href=""><i class="fa fa-linkedin"></i></a> </span>
            <span><a href=""><i class="fa fa-twitter"></i></a> </span>
            <span><a href=""><i class="fa fa-youtube"></i></a> </span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      currTime: new Date()
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.my-footer {
	background-color: #000;
	padding: 40px 0 40px 0;
	color: white;
	margin-top: 50px;
}

.my-footer hr {
	border-color: #383838;
}

.my-footer .title {
	color: white;
	font-weight: bold;
}

.my-footer .block {
	margin-top: 30px;
	margin-bottom: 30px;
}

.my-footer ul {
	list-style-type: none;
	padding-left: 0;
}

.my-footer .list {
	padding-top: 20px;
}

.my-footer ul li {
	padding-top: 10px;
}

.my-footer a {
	color: #009688;
	transition: 0.5s;
}

.my-footer a:hover {
	color: white;
	text-decoration: none;
	transition: 0.5s;
}

.my-footer p {
	color: #767676;
}

.my-footer .my-info {
	margin-top: 40px;
}

.my-footer .my-info, .my-footer .my-info a {
	color: #767676;
	transition: 0.5s;
}

.my-footer .my-info a:hover {
	color: #4eab04;
	transition: 0.5s;
}

.my-footer .my-info .right {
	text-align: right;
}

.my-footer .my-info .right span {
	margin-left: 20px;
	font-size: 20px;
}
</style>
