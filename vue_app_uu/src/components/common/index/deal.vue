<template>
  <div id="deal">
    <el-container>
      <!-- 左侧 -->
      <div class="column-flex">
        <el-aside id="zb" width="200px" class="wq-bg rankhover" @click.native="zb">
          <span class="tit">装备交易</span>
          <span class="f_tit">成交排行榜</span>
          <i class="el-icon-caret-right icon-r"></i>
        </el-aside>
        <el-aside id="zh" width="200px" class="zh-bg" @click.native="zh">
          <span class="tit">账号交易</span>
          <span class="f_tit">成交排行榜</span>
          <i class="el-icon-caret-right icon-r"></i>
        </el-aside>
      </div>
      <!-- 右侧内容 -->
      <el-container style="overflow:hidden">
        <!-- 头部 -->
        <el-header>
          <el-row :gutter="20">
            <el-col :span="2">
              <div>排行</div>
            </el-col>
            <el-col :span="4">
              <div>游戏名称</div>
            </el-col>
            <el-col :span="11">
              <div>出售物品描述</div>
            </el-col>
            <el-col :span="3">
              <div>价格</div>
            </el-col>
            <el-col :span="4">
              <div>成交时间</div>
            </el-col>
          </el-row>
        </el-header>
        <!-- 内容 -->
        <el-main class="pa">
          <!-- pa写有溢出隐藏 -->
          <!-- 装备 -->
          <div id="y">
            <div style="margin:10px 0">
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num-1 num">1</span>
                </el-col>
                <el-col :span="4">
                  <div>上古世纪</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【神赐巨匠烟波单手仗（现货）】神赐巨匠烟波单手仗（现货）</a>
                </el-col>
                <el-col :span="3">
                  <div>8000</div>
                </el-col>
                <el-col :span="4">
                  <div>7月11号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-2">2</span>
                </el-col>
                <el-col :span="4">
                  <div>梦幻诛仙2</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【八卦兑换卡】八卦兑换卡★安全赔付，找回立刻赔★</a>
                </el-col>
                <el-col :span="3">
                  <div>7100</div>
                </el-col>
                <el-col :span="4">
                  <div>7月12号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-3">3</span>
                </el-col>
                <el-col :span="4">
                  <div>第九大陆</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【女神的信任顶级符文一套】顶级女神信任符文</a>
                </el-col>
                <el-col :span="3">
                  <div>6666</div>
                </el-col>
                <el-col :span="4">
                  <div>7月12号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-4">4</span>
                </el-col>
                <el-col :span="4">
                  <div>梦幻诛仙2</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【必成】必成★安全赔付，找回立刻赔★）</a>
                </el-col>
                <el-col :span="3">
                  <div>4700</div>
                </el-col>
                <el-col :span="4">
                  <div>7月12号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-5">5</span>
                </el-col>
                <el-col :span="4">
                  <div>上古世纪</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【单手6阶咒力】38属性8个</a>
                </el-col>
                <el-col :span="3">
                  <div>3360</div>
                </el-col>
                <el-col :span="4">
                  <div>7月11号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-6">6</span>
                </el-col>
                <el-col :span="4">
                  <div>上古世纪(台服)</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【时装】太初+神赐各一件</a>
                </el-col>
                <el-col :span="3">
                  <div>2599</div>
                </el-col>
                <el-col :span="4">
                  <div>7月11号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-7">7</span>
                </el-col>
                <el-col :span="4">
                  <div>诺亚传说</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【11级劳尔】11级劳尔</a>
                </el-col>
                <el-col :span="3">
                  <div>2499</div>
                </el-col>
                <el-col :span="4">
                  <div>7月12号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-8">8</span>
                </el-col>
                <el-col :span="4">
                  <div>笑傲江湖OL</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【如来第3章】如来第3章★安全赔付，找回立刻赔★</a>
                </el-col>
                <el-col :span="3">
                  <div>2300</div>
                </el-col>
                <el-col :span="4">
                  <div>7月10号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-9">9</span>
                </el-col>
                <el-col :span="4">
                  <div>梦幻诛仙2</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【修为】修为★安全赔付，找回立刻赔★</a>
                </el-col>
                <el-col :span="3">
                  <div>2200</div>
                </el-col>
                <el-col :span="4">
                  <div>7月12号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-10">10</span>
                </el-col>
                <el-col :span="4">
                  <div>诛仙3</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【伤心花】281伤心花便宜大甩卖★安全赔付，找回立刻赔★</a>
                </el-col>
                <el-col :span="3">
                  <div>2150</div>
                </el-col>
                <el-col :span="4">
                  <div>7月10号交易成功</div>
                </el-col>
              </el-row>
            </div>
            <!-- 账号 -->
            <div style="margin:25px 0">
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num-1 num">1</span>
                </el-col>
                <el-col :span="4">
                  <div>笑傲江湖OL</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【华山 男 角色等级86 】665华山</a>
                </el-col>
                <el-col :span="3">
                  <div>41000</div>
                </el-col>
                <el-col :span="4">
                  <div>7月10号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-2">2</span>
                </el-col>
                <el-col :span="4">
                  <div>笑傲江湖OL</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【唐门 男 角色等级87 】琉璃唐门全区没几个</a>
                </el-col>
                <el-col :span="3">
                  <div>14500</div>
                </el-col>
                <el-col :span="4">
                  <div>7月12号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-3">3</span>
                </el-col>
                <el-col :span="4">
                  <div>笑傲江湖OL</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【峨嵋 女 角色等级77 】四兽峨眉能打能抗</a>
                </el-col>
                <el-col :span="3">
                  <div>12600</div>
                </el-col>
                <el-col :span="4">
                  <div>7月10号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-4">4</span>
                </el-col>
                <el-col :span="4">
                  <div>轩辕传奇2</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【男 法师 角色等级59 QQ等级1~5级 无QQ好友 】随缘卖号有意看图</a>
                </el-col>
                <el-col :span="3">
                  <div>8500</div>
                </el-col>
                <el-col :span="4">
                  <div>7月12号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-5">5</span>
                </el-col>
                <el-col :span="4">
                  <div>泰亚史诗</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【终身找回包赔】极品武士★指定买家购买★</a>
                </el-col>
                <el-col :span="3">
                  <div>8400</div>
                </el-col>
                <el-col :span="4">
                  <div>7月10号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-6">6</span>
                </el-col>
                <el-col :span="4">
                  <div>地下城与勇士</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">制裁不超过24小时，32个Q打包指定</a>
                </el-col>
                <el-col :span="3">
                  <div>8400</div>
                </el-col>
                <el-col :span="4">
                  <div>7月12号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-7">7</span>
                </el-col>
                <el-col :span="4">
                  <div>地下城与勇士</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">微信申诉解封，59个号</a>
                </el-col>
                <el-col :span="3">
                  <div>8062</div>
                </el-col>
                <el-col :span="4">
                  <div>7月12号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-8">8</span>
                </el-col>
                <el-col :span="4">
                  <div>天谕</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【终身找回包赔】【圣堂 女 角色等级68 网易类型帐号 】42W圣堂都换完</a>
                </el-col>
                <el-col :span="3">
                  <div>7800</div>
                </el-col>
                <el-col :span="4">
                  <div>7月12号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-9">9</span>
                </el-col>
                <el-col :span="4">
                  <div>天涯明月刀</div>
                </el-col>
                <el-col :span="11">
                  <a
                    href="javascript:;"
                    target="_blank"
                  >【太白 QQ等级31~40级 角色等级100 有QQ好友 男 杀手 身份重置需要：火玉冰心 】3.3功4.1战单特效太白</a>
                </el-col>
                <el-col :span="3">
                  <div>7000</div>
                </el-col>
                <el-col :span="4">
                  <div>7月10号交易成功</div>
                </el-col>
              </el-row>
              <el-row :gutter="20">
                <el-col :span="2">
                  <span class="num num-10">10</span>
                </el-col>
                <el-col :span="4">
                  <div>鹿鼎记怀旧版</div>
                </el-col>
                <el-col :span="11">
                  <a href="javascript:;" target="_blank">【角色等级96 支持清空资料 男 火枪手 】全5石头，双7攻击，3级钻便宜</a>
                </el-col>
                <el-col :span="3">
                  <div>6500</div>
                </el-col>
                <el-col :span="4">
                  <div>7月12号交易成功</div>
                </el-col>
              </el-row>
            </div>
          </div>
        </el-main>
      </el-container>
    </el-container>
    <br />
    <!-- 点卡商城 -->
    <el-container>
      <div class="column-flex">
        <el-aside width="200px" class="card-nav">
          <h2>点卡商城</h2>
          <div @click="nav" class="a">
            <a data-id="0" href="javascript:;" class="active">热门游戏</a>
            <a data-id="1" href="javascript:;">完美时空</a>
            <a data-id="2" href="javascript:;">网易</a>
          </div>
        </el-aside>
      </div>
      <el-container>
        <el-main class="pa">
          <div id="main">
            <div class="card-list clearfix">
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-53-37.png" />
                <span style="opacity: 1;">
                  剑侠情缘3
                  <em>￥49.70</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-20-28.png" />
                <span style="opacity: 1;">
                  传奇永恒
                  <em>￥98.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-50-38.png" />
                <span style="opacity: 1;">
                  完美国际2
                  <em>￥100.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-52-43.png" />
                <span style="opacity: 1;">
                  诛仙3
                  <em>￥100.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-4-27.png" />
                <span style="opacity: 1;">
                  笑傲江湖OL
                  <em>￥100.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-5-34.png" />
                <span style="opacity: 1;">
                  梦幻诛仙2
                  <em>￥100.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <a href="JavaScript:;" target="_blank" class="more-a">更多游戏</a>
              </div>
            </div>
            <div class="card-list clearfix">
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-53-35.png" />
                <span style="opacity: 1;">
                  无冬online
                  <em>￥100.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-6-20.png" />
                <span style="opacity: 1;">
                  第三把剑
                  <em>￥100.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-7-37.png" />
                <span style="opacity: 1;">
                  蜀山缥缈录
                  <em>￥100.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-4-27.png" />
                <span style="opacity: 1;">
                  笑傲江湖OL
                  <em>￥100.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-6-56.png" />
                <span style="opacity: 1;">
                  神雕侠侣
                  <em>￥100.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-54-22.png" />
                <span style="opacity: 1;">
                  神魔大陆2
                  <em>￥100.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-52-43.png" />
                <span style="opacity: 1;">
                  诛仙3
                  <em>￥100.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-50-38.png" />
                <span style="opacity: 1;">
                  完美国际2
                  <em>￥100.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-5-34.png" />
                <span style="opacity: 1;">
                  梦幻诛仙2
                  <em>￥100.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <a href="JavaScript:;" target="_blank" class="more-a">更多游戏</a>
              </div>
            </div>
            <div class="card-list clearfix">
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-18-32.png" />
                <span style="opacity: 1;">
                  西楚霸王
                  <em>￥99.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <img src="../../../img/index/cardimg-20-53.png" />
                <span style="opacity: 1;">
                  逆水寒OL
                  <em>￥99.00</em>
                </span>
                <a class="gm-btn" href="javascript:;" target="_blank">立即购买</a>
              </div>
              <div class="card-list-item">
                <a href="JavaScript:;" target="_blank" class="more-a">更多游戏</a>
              </div>
            </div>
          </div>
        </el-main>
      </el-container>
    </el-container>
    <br />
    <el-container>
      <el-header class="link-tit">友情链接</el-header>
      <el-main class="link-content">
        <ul>
          <li>
            <a href="javascript:;">暗黑破坏神3</a>
          </li>
          <li>
            <a href="javascript:;">17173视频</a>
          </li>
          <li>
            <a href="javascript:;">华耀游戏</a>
          </li>
          <li>
            <a href="javascript:;">8899捕鱼</a>
          </li>
        </ul>
      </el-main>
    </el-container>

    <el-container>
      <el-footer class="bz-bg"></el-footer>
    </el-container>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  methods: {
    // 排行榜
    zb() {
      //console.log("123")
      var zh = document.getElementById("zh");
      var y = document.getElementById("y");
      //console.log(zh);
      if (zh.classList.contains("rankhover")) {
        zh.classList.remove("rankhover");
        zb.classList.add("rankhover");
        y.style.transform = "transLateY(0px)";
        y.style.transition = "all .5s ease 0s";
      }
    },
    zh() {
      var zb = document.getElementById("zb");
      if (zb.classList.contains("rankhover")) {
        zb.classList.remove("rankhover");
        zh.classList.add("rankhover");
        y.style.transform = "transLateY(-345px)";
        y.style.transition = "all .5s ease 0s";
      }
    },
    // 点卡商城
    nav(e) {
      var act = e.target;
      //console.log(act);
      var b = document.querySelectorAll(".card-nav a");
      //console.log(b);
      var id_ = act.dataset.id;
      //console.log(id_)
      var main=document.getElementById("main")
      main.style.marginTop=-id_*356+"px";
      main.style.transition="all 0.5s linear";
      if (!act.classList.contains("active")) {
        for (var i = 0; i < b.length; i++) {
          console.log(b[i]);
          b[i].classList.remove("active");
        }
        act.classList.add("active");
      }
    }
  }
};
</script>

<style lang="scss" scoped>
a {
  text-decoration: none;
  color: #333;
}
li {
  list-style: none;
}
.clearfix::after,
.clearfix::before {
  content: "";
  clear: both;
  display: table;
}
#deal {
  width: 1200px !important;
  margin: auto;
  // 此处与最终样式有区别需修改 background :#f5f5f5
}
.el-header {
  background-color: #b3c0d1;
  background-image: url("../../../img/index/colum-bg.jpg");
  color: #fff;
  text-align: center;
  line-height: 60px;
}

.el-aside {
  background-color: #d3dce6;
  color: #333;
  text-align: center;
  height: 200px;
}
/* 自改  侧边栏 start */
.column-flex {
  display: flex;
  flex-direction: column;
  margin-right: 10px;
}
// 上侧边栏
.el-aside.wq-bg {
  background: url("../../../img/index/wq.png") no-repeat 55px 85px;
}
.el-aside.zh-bg {
  background: url("../../../img/index/zh.png") no-repeat 55px 85px;
}
.el-aside.rankhover {
  display: block;
  z-index: 100;
  color: #fff;
  line-height: 140px;
  background: url("../../../img/index/nav-bg.png") no-repeat;
}

.el-container:nth-child(1) .el-aside {
  height: 205px;
  position: relative;
}
/* 主标题 */
.el-aside .tit {
  position: absolute;
  top: 20px;
  left: 20px;
  font-size: 20px;
  font-weight: bold;
}
/* 副标题 */
.el-aside .f_tit {
  position: absolute;
  top: 45px;
  left: 20px;
  font-size: 14px;
}
// 箭头图标
.icon-r {
  position: absolute;
  right: 10px;
  top: 50%;
  font-size: 22px;
}
.el-container:nth-child(3) .el-aside {
  width: 210px;
  height: 352px;
  background: url("../../../img/index/card-bg.png") no-repeat -10px;
}
/* 侧边栏 end */

.el-main {
  background-color: #f3f3f3;
  color: #333;
  text-align: center;
  // line-height: 160px;
}

body > .el-container {
  margin-bottom: 40px;
}
// 排行榜头部
.el-row {
  margin-bottom: 12px;
}
.el-main {
  font: 13px/1.5 "微软雅黑";
  color: #434343;
  padding: 10px;
}
// el-main 列表
.el-col .num {
  display: block;
  margin: auto;
  width: 18px;
  height: 21px;
  color: #fff;
}
.el-col .num-1 {
  background: url("../../../img/index/index_bg.png") -57px -60px;
}
.el-col .num-2 {
  background: url("../../../img/index/index_bg.png") -77px -60px;
}
.el-col .num-3 {
  background: url("../../../img/index/index_bg.png") -96px -60px;
}
.el-col .num-4,
.num-5,
.num-6,
.num-7,
.num-8,
.num-9,
.num-10 {
  background: url("../../../img/index/index_bg.png") -116px -60px;
}
// .el-col a:hover{
//   color: #00b0ff !important;
// }
.el-main .el-col.el-col-3 {
  color: #ff3a56;
}
.el-main .el-col.el-col-4 {
  color: #999;
}

// 出售物品描述文本溢出隐藏为"..."
.el-col-11 {
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}
// 交易 end

// 点卡商城样式
.card-nav h2 {
  color: #fff;
  font-weight: normal;
  font-size: 26px;
  margin: 35px 0 30px 0;
}
.card-nav a {
  display: inline-block;
  width: 135px;
  height: 35px;
  line-height: 35px;
  border: 1px solid #fff;
  border-radius: 3px;
  margin: 10px auto;
  color: #fff;
  letter-spacing: 5px;
  background: url("../../../img/index/bg-btn.png") repeat;
}
.card-nav a:hover,
.card-nav a.active {
  background: #fff;
  color: #ff850a;
}
.card-list-item {
  width: 195px;
  height: 175px;
  border-right: 1px solid #cac8c8;
  border-bottom: 1px solid #cac8c8;
  float: left;
  cursor: pointer;
  position: relative;
}
// 因不能同行显示5个 修改padding
.pa {
  padding: 2px;
  height: 352px;
  overflow: hidden; //隐藏
}

.card-list-item img {
  margin-top: 14px;
  box-shadow: 3px 2px 5px #ddd;
  transition: transform 0.4s ease;
}
.card-list-item:hover img {
  transform: translateY(5px);
}
.card-list-item span {
  display: block;
  margin-top: 17px;
  transition: transform 0.4s ease, opacity 0.4s ease;
}
.card-list-item:hover span {
  transform: translateY(5px);
  opacity: 0 !important;
}
// 取消标签字体默认样式
em,
i {
  font-style: normal;
}
.card-list-item span em {
  display: block;
  color: red;
  font-weight: bold;
}
// 立即购买按钮
.gm-btn {
  display: inline-block;
  width: 115px;
  height: 35px;
  line-height: 35px;
  background: #fff;
  border: 1px solid #00b0ff;
  color: #00b0ff !important;
  border-radius: 3px;
  position: absolute;
  bottom: 18px;
  left: 20%;
  opacity: 0;
  transition: transform 0.4s ease, opacity 0.4s ease;
}
.card-list-item:hover .gm-btn {
  transform: translateY(-10px);
  opacity: 1;
}
.gm-btn:hover {
  background: #00b0ff;
  color: #fff !important;
  display: block;
}
// 更多游戏样式
.more-a {
  display: block;
  width: 80px;
  font-size: 30px;
  font-weight: 700;
  line-height: 33px;
  text-align: center;
  margin: 55px auto 0 auto;
  color: #c6c6c6 !important;
}
// 友情链接样式
.link-tit {
  text-align: left;
  height: 48px !important;
  line-height: 48px;
  padding-left: 50px;
  background: url("../../../img/index/yqlj.png") no-repeat;
}
.link-content {
  padding: 20px 0;
  background: #fff;
  margin-bottom: 20px;
  border: 1px solid #efefef;
}
.link-content li {
  float: left;
  margin: 0 24px;
}
.el-footer.bz-bg {
  height: 92px !important;
  background: url("../../../img/index/jysx.png") no-repeat center center;
}
a:hover {
  color: #00b0ff;
}
</style>