<template>
  <div>
    <div id="about">
      <div class="wrap">
        <Header></Header>
        <div class="content">
          <h2>About</h2>
          <p style="color:#f3c0cb">声明：本站所有文章均为本人原创，仅代表个人思想，与其他任何人或组织无关！</p>
          <h2>个人介绍</h2>
          <p>名字:胡森</p>
          <p>武汉大学GIS专业大三学生</p>
          <p>目前专注于Web端开发，对Java一站式开发流程较为熟悉</p>
          <p>你能通过以下方式联系到我：</p>
          <p>Email：2309780282@qq.com</p>
          <a href="https://github.com/civitasv">Github@Civitasv</a>
          <h2>关于本站</h2>
          <p>拥有一个个人博客在我看来是件非常酷的事情，因此我做了该blog</p>

          <h2>update @2020-03-28.</h2>
          <p>添加域名，适配手机</p>
          <h2>update @2020-05-15.</h2>
          <p>设置动态title，改变为history模式</p>
          <h2>update @2020-05-24.</h2>
          <p>添加评论功能</p>
          <b>欢迎交换友链~</b>
        </div>
      </div>
      <Footer></Footer>
      <GoTop></GoTop>
    </div>
    <SideBar></SideBar>
  </div>
</template>

<style scoped>
#about {
  background-image: url("../../assets/images/bg.jpg");
  background-size: cover;
  background-attachment: fixed;
  background-repeat: no-repeat;
  transition: margin-right 1s;
}
.wrap {
  min-height: 100vh;
  padding-bottom: 100px;
}
.content {
  width: 80vw;
  border-radius: 0;
  margin: 0 auto;
  margin-top: 10vh;
  color: whitesmoke;
  line-height: 3rem;
}
.content a {
  color: whitesmoke;
}
</style>
<script>
const Header = () => import("../../components/Header");
const Footer = () => import("../../components/Footer");
const GoTop = () => import("../../components/GoTop");
const SideBar = () => import("../../components/SideBar");

export default {
  data() {
    return {};
  },
  computed: {},
  components: {
    Header,
    Footer,
    GoTop,
    SideBar
  },
  methods: {}
};
</script>