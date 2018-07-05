<template>
    <div class="resume-warpper">
        <div class="resume-left">
            <div class="avatar">
                <img src="../assets/BYJ-resume.jpg">
            </div>
            <div class="job">
                <span class="name">岗位：WEB前端</span>
            </div>
            <div class="info-wrapper">
                <div class="info">
                    <div class="icon">
                        <i class="iconfont icon-jibenxinxi2"></i>
                    </div>
                    <div class="title-wrapper">
                        <span class="title">基本信息</span>
                    </div>
                </div>
                <div class="des">
                    <div class="title">
                        <i class="iconfont icon-icon-person"></i>
                        <p class="name">姓&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp名：毕扬君</p>
                    </div>
                    <div class="title">
                        <i class="iconfont icon-icon-person"></i>
                        <p class="name">性&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp别：女</p>
                    </div>
                    <div class="title">
                        <i class="iconfont icon-biyejiaoyuhuodong"></i>
                        <p class="name">毕业学校：四川师范大学</p>
                    </div>
                    <div class="title">
                        <i class="iconfont icon-zhuanyezhishijineng"></i>
                        <p class="name">专&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp业：环境工程</p>
                    </div>
                </div>
            </div>
            <div class="info-wrapper">
                <div class="info">
                    <div class="icon">
                        <i class="iconfont icon-wo"></i>
                    </div>
                    <div class="title-wrapper">
                        <span class="title">联系方式</span>
                    </div>
                </div>
                <div class="des">
                    <div class="title">
                        <i class="iconfont icon-dianhua1"></i>
                        <p class="name">电&nbsp&nbsp&nbsp&nbsp话：13981739826</p>
                    </div>
                    <div class="title">
                        <i class="iconfont icon-tubiao209"></i>
                        <p class="name"><a href="https://mail.qq.com/cgi-bin/frame_html?sid=CHmD32eVY6_Sqzxn&r=177550b1f68a20e84d61b56f81bfdd8e" class="link">邮箱：2546776177@qq.com</a></p>
                    </div>
                    <div class="title">
                        <i class="iconfont icon-GitHub"></i>
                        <p class="name"><a href="https://github.com/MissBeyond" class="link">Github：MissBeyond</a></p>
                    </div>
                    <div class="title">
                        <i class="iconfont icon-shouye"></i>
                        <p class="name">住&nbsp&nbsp&nbsp&nbsp址：深圳南山区</p>
                    </div>
                </div>
            </div>
            <div class="info-wrapper">
                <div class="info">
                    <div class="icon">
                        <i class="iconfont icon-gongju1"></i>
                    </div>
                    <div class="title-wrapper">
                        <span class="title">专业技能</span>
                    </div>
                </div>
                <ul class="skill">
                    <li class="detail">
                        <p class="title">HTML</p>
                        <span class="progress"><span class="highlight"></span></span>
                    </li>
                    <li class="detail">
                        <p class="title">CSS</p>
                        <span class="progress"><span class="highlight css"></span></span>
                    </li>
                    <li class="detail">
                        <p class="title">JavaScipt</p>
                        <span class="progress"><span class="highlight js"></span></span>
                    </li>
                    <li class="detail">
                        <p class="title">Vue</p>
                        <span class="progress"><span class="highlight vue"></span></span>
                    </li>
                    <li class="detail">
                        <p class="title">PhotoShop</p>
                        <span class="progress"><span class="highlight ps"></span></span>
                    </li>
                </ul>
            </div>
            
        </div>
        <div class="resume-right">
            <div class="work">
                <div class="title">
                    <div class="icon">
                        <i class="iconfont icon-gongju1"></i>
                    </div>
                    <span class="name">工作经历</span>
                    <!-- <span class="name-english">WORK&nbsp&nbspEXPERIENCE</span> -->
                </div>
                <div class="desc">
                    <!-- <div class="job">
                        <i class="iconfont icon-ic_pending"></i>
                        <span class="time">2017/06~2017/08</span>
                        <span class="company">科全经贸有限公司</span>
                        <span class="jobname">工作职位：电商美工</span>
                        <p class="text">工作内容：负责公司淘宝、天猫店铺的装修、宠物产品的拍摄、图片后期处理，详情页、主图、海报设计</p>
                    </div> -->
                    <div class="job">
                        <i class="iconfont icon-ic_pending"></i>
                        <span class="time">2017/09—2018/05</span>
                        <span class="company abs">深圳市中天兴衍科技有限公司</span>
                        <span class="jobname">工作职位：设计/前端</span>
                        <p class="text">工作内容：主要负责设计各类活动的海报（节假日、早起卡、晚安图等），完成活动页面设计及前端静态页实现</p>
                    </div>
                </div>
            </div>
            <div class="work">
                <div class="title">
                    <div class="icon">
                        <i class="iconfont icon-xiangmu"></i>
                    </div>
                    <span class="name">项目经历</span>
                    <!-- <span class="name-english">PROJECTS&nbsp&nbspEXPERIENCE</span> -->
                    </div>
                <div class="desc">
                    <div class="job">
                        <i class="iconfont icon-ic_pending"></i>
                        <span class="time">早起打卡页面的静态页</span>
                        <p class="text">技术：HTML/CSS</p>
                        <p class="text">微信公众号页面，使用rem布局，能够编写语义化的HTML，模块化的CSS，了解常见浏览器兼容性问题及解决方案，了解stylus、sass等css预处理器技术</p>
                    </div>
                    <div class="job">
                        <i class="iconfont icon-ic_pending"></i>
                        <span class="time">高仿饿了么外卖WebApp</span>
                        <p class="text">技术栈：MVVM框架（Vue.js 2.0）、状态管理（Vuex）、前端路由（Vue-router）、服务端通讯（axios）、滚动插件（better-scroll）、构建工具（webpack）、CSS 预处理（stylus）</p>
                    </div>
                    <div class="job">
                        <i class="iconfont icon-ic_pending"></i>
                        <span class="time">快餐店的POS系统</span>
                        <p class="text">系统使用的技术栈为：</p>
                        <p class="text">Vue+Webpack+Element+Axios<br/>+vueRouter</p>
                    </div>
                </div>
            </div>
            <div class="work">
                <div class="title">
                    <div class="icon">
                        <i class="iconfont icon-aixin"></i>
                    </div>
                    <span class="name">自我评价</span>
                    <!-- <span class="name-english">SELF&nbsp&nbspEVALUATION</span> -->
                    </div>
                <div class="desc">
                    <div class="job">
                        <p class="text">1.良好的沟通能力，性格开朗，乐于分享，喜欢有活力的团队</p>
                        <p class="text">2.自学能力强，善于思考，善于与他人沟通，有团队合作精神</p>
                        <!-- <p class="text extra">3.自己也有不足之处，比如：社会经验等欠缺，不过这些可以通过自身的努力而达到的</p> -->
                    </div>
                    
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'Resume'
}
</script>
<style lang="stylus" scoped>
    .resume-warpper
        width 100%
        margin 0 auto
        height 17rem
        background-color pink
        .resume-left
            position relative
            float left
            top 0
            left 0
            width 46%
            height 100%
            background-color #2f3a40
            .avatar
                position relative
                overflow hidden
                margin .4rem auto .2rem 
                width 1.4rem
                height 1.4rem
                border-radius 50%
                img
                    vertical-align top
                    width 1.4rem
                    height 1.4rem  
            .job
                display flex
                justify-content center
                .name
                    display inline-block
                    font-size .28rem
                    font-weight 400
                    color #ffffff
                    padding-bottom .04rem
                    border-bottom .04rem solid #f6961e
                
            .info-wrapper
                margin-top .4rem
                .info
                    display flex
                    align-items center
                    padding-left .24rem
                    font-size 0
                    .icon
                        display flex
                        justify-content center
                        align-items center
                        z-index 99
                        width .48rem
                        height .48rem
                        border-radius 50%
                        border .04rem solid #2f3a40
                        background-color #f6961e
                        .iconfont
                            font-size .24rem
                            color #ffffff
                    .title-wrapper
                        display inline-block
                        position absolute
                        margin-left 0.2rem
                        z-index 80
                        width 1.8rem
                        height .32rem
                        background-color #f6961e
                        text-align center
                        border-radius 0.12rem
                        .title
                            font-size .24rem
                            line-height .32rem
                            color #ffffff
                .des
                    margin .16rem 0 0 .32rem
                    .title
                        font-size 0
                        margin-bottom 0.1rem
                        .iconfont
                            display inline-block
                            vertical-align top
                            margin-right .12rem
                            font-size .28rem
                            color #c9cdce
                        .name
                            display inline-block
                            font-size .2rem
                            color #ffffff
                            .link
                                text-decoration none
                                color #f6961e
            .info-wrapper
                .skill
                    margin .2rem 0 0 .36rem
                    .detail
                        line-height .2rem
                        font-size 0
                        margin-bottom .1rem
                        .title
                            font-size .2rem
                            color #ffffff
                            margin-bottom .08rem
                        .progress
                            display inline-block
                            width 2.4rem
                            height .12rem
                            border-radius .08rem
                            background-color #d2d2d2
                            .highlight
                                display inline-block
                                width 75%
                                height 100%
                                border-radius .08rem
                                background-color #f6961e
                            .css
                                width 65%
                            .js
                                width 40%
                            .vue
                                width 55%
                            .ps
                                width 55%
                
        .resume-right
            float right
            width 54%
            height 100%
            background-color #effbfe
            .work
                position relative
                margin .4rem auto 0
                font-size 0
                .title
                    display flex
                    font-size 0
                    align-items center
                    .icon
                        display flex
                        justify-content center
                        align-items center
                        margin-left -0.2 rem
                        width .44rem
                        height .44rem
                        border-radius 50%
                        border .04rem solid #2f3a40
                        background-color #fff
                        .iconfont
                            font-size .24rem
                            color #f6961e
                    .name
                        display inline-block
                        margin-left .08rem
                        font-size .24rem
                        color #2f3a40
                        line-height .48rem
                        font-weight 500
                    .name-english
                        display inline-block
                        margin-left .2rem
                        font-size .2rem
                        line-height .48rem
                        color #abacaf
            .desc
                margin .08rem .32rem
                .job
                    margin-bottom .2rem
                    font-size 0
                    color #2f3a40
                    .iconfont 
                        font-size .24rem
                        color #2f3a40
                    .time
                        display inline-block
                        margin 0 .2rem 0 .08rem
                        font-size .2rem
                        font-weight 700
                        padding-bottom .04rem
                    .company
                        display inline-block
                        font-size 0.2rem
                        font-weight 500 
                    .abs
                        margin-left .28rem
                        padding-bottom .04rem
                        font-weight 700
                    .jobname
                        display inline-block
                        margin-left .28rem
                        font-size .2rem
                    .text
                        display inline-block
                        margin-left .28rem
                        line-height .32rem
                        font-size 0.2rem
                   




        
</style>


