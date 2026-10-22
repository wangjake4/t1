代发 wailian999

[U65] PHP：会话
来源：http://dali.birdmap.top/Article/details/gtonpsagtf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtwbayzmrv.html

[U66] PHP：设置 Cookie
来源：http://dali.sxryk.cn/Article/details/gtvevuajzm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj202588.top/Article/details/gtrwbflyil.html

[U67] PHP：处理文件上传
来源：http://dali.yuanzhike.top/Article/details/gtncojqfzk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ybcxt.top/Article/details/gtcynjcllg.html

[U68] PHP：PDO 连接
来源：http://dali.tian-w.cn/Article/details/gtwjmbgqkm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.quarkkingdee.top/Article/details/gtjdebrcwi.html

[U69] PHP：PDO 预处理
来源：http://dali.ehwqpu.com/Article/details/gtndnqbpav.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhiwuduotai.top/Article/details/gttvfivnld.html

[U70] PHP：PDO 事务
来源：http://dali.xuanzx.com/Article/details/gtlwtesfko.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.kuanghao11.cn/Article/details/gtjydwkboa.html

[U71] PHP：抛出异常
来源：http://dali.zdqjudy.top/Article/details/gtnxzcoryn.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258.top/Article/details/gtbipqtniw.html

[U72] PHP：写错误日志
来源：http://dali.yj202588.top/Article/details/gtbabmcbve.html

error_log("失败: " . $e->getMessage());
来源：http://dali.redwolf501.top/Article/details/gtroeccdwk.html

[U73] PHP：读取 ini 配置
来源：http://dali.yangfankeji.com/Article/details/gthrjltxeu.html

parse_ini_file("config.ini", true)
来源：http://dali.sysykeji.top/Article/details/gtdqulluex.html

[U74] PHP：读取环境变量
来源：http://dali.yonumen.top/Article/details/gtqvosfapx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.andypj.xyz/Article/details/gtogixicxk.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gtucprkzym.html

composer require psr/container
来源：http://dali.zhongyouzk.top/Article/details/gtnkciabit.html

[U76] PHP：简单路由
来源：http://dali.sysykeji.top/Article/details/gttngznfyf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gttlspqnpl.html

[U77] PHP：模板渲染
来源：http://dali.nwbrower.top/Article/details/gtoqkcyedc.html

composer require twig/twig
来源：http://dali.andypj.xyz/Article/details/gtrkulgppg.html

[U78] PHP：单元测试
来源：http://dali.jinqigufen.top/Article/details/gtpfdpgmjl.html

composer require --dev phpunit/phpunit
来源：http://dali.andypj.xyz/Article/details/gtymhkmuzk.html

[U79] PHP：静态分析
来源：http://dali.jqgfzy.top/Article/details/gthbmqibdi.html

composer require --dev phpstan/phpstan
来源：http://dali.pycfn.com/Article/details/gtogdlyfwr.html

[U80] PHP：代码规范修复
来源：http://dali.hnxiangtu.top/Article/details/gttqagrujt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jianghu66.top/Article/details/gtsnxjmday.html

[U81] JS：初始化项目
来源：http://dali.hammf.cn/Article/details/gtbxuzayne.html

npm init -y;  npm i express
来源：http://dali.jqgufenzy.top/Article/details/gtynbiqvnb.html

[U82] JS：package.json 脚本
来源：http://dali.fzhhl.top/Article/details/gtydadapdh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dashuyun.cn/Article/details/gtqpfkiqav.html

[U83] JS：ES Module 导入导出
来源：http://dali.gzhubu.top/Article/details/gtzsfvazsv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gtsqosodcp.html

[U84] JS：CommonJS 写法
来源：http://dali.hywenlv.cn/Article/details/gtnltvsqnx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cqqwz.cn/Article/details/gtrewxlpuy.html

[U85] JS：可选链
来源：http://dali.jyoumei.cn/Article/details/gtosancypt.html

a?.b?.c
来源：http://dali.shanyushiyangtech.top/Article/details/gtciwyqspu.html

[U86] JS：空值合并
来源：http://dali.meibo888.top/Article/details/gtmazrpiix.html

a ?? b
来源：http://dali.zhaomingkeji.xyz/Article/details/gteovrriyo.html

[U87] JS：解构默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtbxqmdkky.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxuanxn.top/Article/details/gtotggvhhp.html

[U88] JS：对象展开合并
来源：http://dali.smart0.xyz/Article/details/gtvwgqfqpo.html

{ ...a, ...b }
来源：http://dali.jqgufenzy.top/Article/details/gtafpsvnwn.html

[U89] JS：数组去重
来源：http://dali.tanke756.top/Article/details/gtvlrcrmhk.html

[...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtzskdrgdw.html

[U90] JS：数字数组排序
来源：http://dali.cheryme.top/Article/details/gtvzmbbwwd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtlrfaqgvp.html

[U91] JS：对象键值遍历
来源：http://dali.zhongyouzk.top/Article/details/gteablymzj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzxuldkz.html

[U92] JS：深拷贝
来源：http://dali.yueranfly.top/Article/details/gtaicpfhqm.html

structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtgqczdqdz.html

[U93] JS：模板字符串
来源：http://dali.jianghu66.top/Article/details/gtuwtmgsgu.html

`共 ${n} 条`
来源：http://dali.aibaodan.cn/Article/details/gtpymwmnca.html

[U94] JS：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gtmybbmzzj.html

const double = x => x * 2;
来源：http://dali.zhongyouzk.top/Article/details/gtxvjfuihc.html

[U95] JS：Promise 包装
来源：http://dali.quarkkingdee.top/Article/details/gttfupzdxx.html

new Promise((resolve, reject) => {})
来源：http://dali.chenjidiqi.icu/Article/details/gtdlsgdoxr.html

[U96] JS：async/await 与异常
来源：http://dali.quarkkingdee.top/Article/details/gtetyljwsa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtlmdohczt.html

[U97] JS：并发请求
来源：http://dali.redwolf501.top/Article/details/gticoczigb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtmbzcqcjb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhixingplan.top/Article/details/gtwlrzwnsl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenzaomai.com/Article/details/gtwcmpkxsq.html

[U99] JS：事件监听
来源：http://dali.wangshuangyany.cn/Article/details/gtvedwkpwv.html

el.addEventListener("click", e => {})
来源：http://dali.wangdashe.top/Article/details/gthdhyawoh.html

[U100] JS：DOM 查询
来源：http://dali.quarkkingdee.top/Article/details/gtkabrdfvw.html

document.querySelector(".item")
来源：http://dali.yj202588.top/Article/details/gtbcouhuxg.html

[U101] JS：classList 操作
来源：http://dali.feifeiyinyue.top/Article/details/gtiwvpvdzo.html

el.classList.toggle("active")
来源：http://dali.kuanghao11.cn/Article/details/gtnxxkpgvr.html

[U102] JS：本地存储
来源：http://dali.zdqjudy.top/Article/details/gtfarlaile.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guannengcc.top/Article/details/gtsfocfdpa.html

[U103] JS：定时器
来源：http://dali.daria6918.cn/Article/details/gthaqyfrkn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tian-w.cn/Article/details/gtyhxeqqwh.html

[U104] JS：防抖
来源：http://dali.zdqjudy.top/Article/details/gtqpooangk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtwtzvtydn.html

[U105] JS：节流
来源：http://dali.kuanghao11.cn/Article/details/gtdjgnyfmh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nwbrower.top/Article/details/gtlbrxxtsp.html

[U106] JS：日期格式化
来源：http://dali.jianghu66.top/Article/details/gthgywrjbb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jqgfzy.top/Article/details/gtbiqzgmvm.html

[U107] JS：数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtsryvwpmb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtieoxridy.html

[U108] JS：随机整数
来源：http://dali.chenzaomai.com/Article/details/gtrdqaeckg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gtpqsjcmpr.html

[U109] JS：数组分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiiucviil.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtdcaksiam.html

[U110] JS：数组分块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlphwqts.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenlongwang.top/Article/details/gtgkxhdhzp.html

[U111] JS：对象转 Map
来源：http://dali.sysykeji.top/Article/details/gtubmccvei.html

new Map(Object.entries(obj))
来源：http://dali.vqdsnc.cn/Article/details/gtfihfeadb.html

[U112] JS：字符串补位
来源：http://dali.jinqigfzy.top/Article/details/gtqtycpadh.html

"7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtnfppdnle.html

[U113] JS：正则替换全部
来源：http://dali.sxryk.cn/Article/details/gtyywjzpkr.html

s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtbswwjzwz.html

[U114] JS：JSON 深比较
来源：http://dali.chenzaomai.com/Article/details/gtdxwgcemr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtlvzjhgdr.html

[U115] JS：生成 UUID
来源：http://dali.xuanzx.com/Article/details/gtqlmywzwl.html

crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtznbjdcgm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ivvv.top/Article/details/gtbdjmmcou.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ybcxt.top/Article/details/gtlgbmocmr.html

[U117] JS：单元测试
来源：http://dali.fengsongda.top/Article/details/gttnwmwfeh.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigufen.top/Article/details/gtcxuysxjc.html

[U118] JS：开发服务器
来源：http://dali.hfpthk.cn/Article/details/gthibtdkhr.html

npm i -D vite;  npx vite
来源：http://dali.hnxiangtu.top/Article/details/gttcapngxe.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangtech.top/Article/details/gtlamhjitj.html

npx vite build
来源：http://dali.wangshuangyany.cn/Article/details/gtrantxdey.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.0kj1m.cn/Article/details/gtqzzatzik.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigfzy.top/Article/details/gtziroaccv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtturabfew.html

统计汇总
来源：http://dali.yj20258.top/Article/details/gtrcojlsyk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvbxljtt.html

按语言统计（条）：
来源：http://dali.svipenyu.cn/Article/details/gtjtvawbpg.html

Python ......... 252
来源：http://dali.quarkkingdee.top/Article/details/gtpydszwps.html

PHP ............ 252
来源：http://dali.havefunace.top/Article/details/gtdmizscqj.html

JavaScript ..... 252
来源：http://dali.jlsjyb.cn/Article/details/gtiacchrsi.html

TypeScript ..... 212
来源：http://dali.c1oappe.top/Article/details/gtnvvcqmjx.html

Java ........... 212
来源：http://dali.hammf.cn/Article/details/gtdknhhbak.html

Go ............. 212
来源：http://dali.tianlin.xyz/Article/details/gtfvskjhtr.html

Ruby ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtzcsudnxd.html

C# ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gtpyecsarc.html

C .............. 30
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrcmdlkx.html

C++ ............ 30
来源：http://dali.pengpengdd.cyou/Article/details/gteppamjhp.html

SQL ............ 90
来源：http://dali.tian-w.cn/Article/details/gtggzoewaz.html

Bash ........... 80
来源：http://dali.gaohongyu789.top/Article/details/gtfoguezoh.html

Kotlin ......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwanvqjik.html

Swift .......... 15
来源：http://dali.yuanzhike.top/Article/details/gtwlqpkqky.html

Lua ............ 10
来源：http://dali.bjfxy.top/Article/details/gtatwufewe.html

Perl ........... 10
来源：http://dali.zhongyouzk.top/Article/details/gtepuinufe.html

Scala .......... 10
来源：http://dali.jlsjyb.cn/Article/details/gtddglltbs.html

------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtgtqfxnre.html

合计 ........... 2106 条
来源：http://dali.hysaishi.cn/Article/details/gtqnnpctfm.html

按章节统计：
来源：http://dali.svipenyu.cn/Article/details/gtnfmfccqb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gtlsbejwdl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gtchcttgxh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtaafnrkyf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpixtlrtj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgufenzy.top/Article/details/gtyfcyzzgk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gtyxcjqjwk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtrirxmaqf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cashguo.top/Article/details/gtfaleqwaw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtalcwkdkl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyhfhpwm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtzoddzqph.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtkdgbnvtp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtobesjczk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gtntgqeshm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuxming.cn/Article/details/gthzzimvcu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtiqmsuldt.html

Q SQL 专题                              90
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrfpartq.html

R Bash 专题                             80
来源：http://dali.tian-w.cn/Article/details/gtfbfxgpgt.html

S C / C++ 专题                          60
来源：http://dali.hywenlv.cn/Article/details/gtgnlcojmy.html

T 其他语言补充                          60
来源：http://dali.yongpay.top/Article/details/gtegklxjhe.html

U 高频实用片段                         120
来源：http://dali.mhx1999.top/Article/details/gtwiapedin.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtpxrnrjia.html

合计                                  2106 条
来源：http://dali.chenlongwang.top/Article/details/gtgdbcwwlj.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtuywszwzy.html

使用提醒
来源：http://dali.cheryme.top/Article/details/gtzzuiaccy.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtsagmgzbx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tianlin.xyz/Article/details/gtnjzfooec.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yongpay.top/Article/details/gtzarcopcc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shanyushiyangtech.top/Article/details/gtkobghfzl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinqigufen.top/Article/details/gtvrkafkdz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnxiangtu.top/Article/details/gtjpbfwwzm.html

—— 文件结束 ——
来源：http://dali.zhixingplan.top/Article/details/gttfavlrru.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtsxpwneie.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.haohaochexian.top/Article/details/gtkylkjtwg.html

Common Programming Examples Cheat Book
来源：http://dali.pycfn.com/Article/details/gtodzlyilc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwrezynek.html

【收录内容】
来源：http://dali.shzxlz.cn/Article/details/gtldorbbpn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sysykeji.top/Article/details/gtetvfpsfq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsjmivxj.html

SQL · Bash · C · C++
来源：http://dali.tian-w.cn/Article/details/gtyxbhycrh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yuxming.cn/Article/details/gtgjdvzbvz.html

【使用说明】
来源：http://dali.hywenlv.cn/Article/details/gtfbmrfqjs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yueranfly.top/Article/details/gtfuqqlwqn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.havefunace.top/Article/details/gtexcccpsy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj202588.top/Article/details/gtcqdoizog.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sweek.top/Article/details/gtgfccbqtd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aizwys.cn/Article/details/gtkfcvrcul.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jqgfzy.top/Article/details/gtdrnouich.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cucudq.cn/Article/details/gtglvarwaq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fzhhl.top/Article/details/gtnueadpgh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yongpay.top/Article/details/gtfodijkui.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cqqwz.cn/Article/details/gtiblqnzac.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.fengsongda.top/Article/details/gtonvvbugz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrfjidse.html

【文件统计】
来源：http://dali.gaohongyu789.top/Article/details/gtuevylbxu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cqqwz.cn/Article/details/gturwyknnp.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtkupmvhal.html

目  录
来源：http://dali.c1oappe.top/Article/details/gtfkgcbhbt.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtvldqyvqr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gotoacloud.top/Article/details/gtpvgshask.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecxzmkeq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yanxiufei.cn/Article/details/gtyluqnqgh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gtuksugiot.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gogol.net.cn/Article/details/gtmbvaznvc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gtnopzilrr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gtteotgefu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gtxublkffq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtpxjpkuls.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gtspewzxcs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gtxpxgalhk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtrsxqjlem.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjqaauyc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gtxmwyffpa.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gzhubu.top/Article/details/gtxwgqajes.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gteearzugh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sysykeji.top/Article/details/gtrscnjopx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jianghu66.top/Article/details/gtqyvqznuw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.nanxuanxn.top/Article/details/gtemqcdchu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfoulbmxc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxinkj.top/Article/details/gtraibllqo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtyovqldxi.html

A. 基础语法与类型
来源：http://dali.kuanghao11.cn/Article/details/gttvahjcjf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrrzxkwlr.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gthwaqkrpm.html

Py:   print("Hello, World!")
来源：http://dali.dashuyun.cn/Article/details/gtvjvepwkw.html

PHP:  echo "Hello, World!";
来源：http://dali.cdnleiting.top/Article/details/gtumgnctaj.html

JS:   console.log("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gtvvdaimqq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.svipenyu.cn/Article/details/gtcuzikgat.html

Java: System.out.println("Hello, World!");
来源：http://dali.shuidangran.top/Article/details/gthmoydumi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjixndoc.html

Ruby: puts "Hello, World!"
来源：http://dali.yuxming.cn/Article/details/gtmjnqsffj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gtxfzibqkz.html

[A02] 变量声明与赋值
来源：http://dali.hnxiangtu.top/Article/details/gthdnqzaco.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexizumum.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sxryk.cn/Article/details/gtigcbwgdb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtinnijknj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.snrcjt.cn/Article/details/gttrgcsbdh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtfxsapbyq.html

Go:   name := "Alex"; age := 20
来源：http://dali.quarkkingdee.top/Article/details/gtzapmhyqd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hysaishi.cn/Article/details/gtrultamje.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinqigufen.top/Article/details/gtaifxyqms.html

[A03] 常量定义
来源：http://dali.tanke756.top/Article/details/gtdkmguzzi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.aizwys.cn/Article/details/gtgrefenlg.html

PHP:  const PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtcbfqjast.html

JS:   const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtidpcyznd.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtdoiwiyzu.html

Java: static final double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtiryqfolw.html

Go:   const PI = 3.14159
来源：http://dali.xylfe.cn/Article/details/gtzrhkfbqt.html

Ruby: PI = 3.14159
来源：http://dali.birdmap.top/Article/details/gtfcejaoks.html

C#:   const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtsfufrnvy.html

[A04] 判断变量类型
来源：http://dali.hammf.cn/Article/details/gtobydcsrc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.9152youxi.cn/Article/details/gtdghptjce.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ybcxt.top/Article/details/gtfkhmgtcf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gotoacloud.top/Article/details/gtuaxcygru.html

TS:   typeof x; x instanceof Date
来源：http://dali.smart0.xyz/Article/details/gtavtbwntr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.snrcjt.cn/Article/details/gtjhbeoryh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yuxming.cn/Article/details/gtxlcyydgj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ppjwa.cn/Article/details/gtyfomgbae.html

C#:   x.GetType().Name; x is int
来源：http://dali.nwbrower.top/Article/details/gtqfreqjjm.html

[A05] 整数除法与取模
来源：http://dali.nanxinkj.top/Article/details/gtsmjdznuh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zycfv.cn/Article/details/gtuqgmyija.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gtzczkftfq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gtfupotwbf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtknbvttzm.html

Java: 7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtuiaxphxo.html

Go:   7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtpuyrnmlr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtjuzfeyry.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtmzqexjmp.html

[A06] 字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtuhajctsc.html

Py:   int("42"); float("3.14")
来源：http://dali.sxryk.cn/Article/details/gtdscdmepa.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gogol.net.cn/Article/details/gtqckynlyh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sweek.top/Article/details/gtviycdgql.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gtnivjlepn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zycfv.cn/Article/details/gtdvquaziv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shuidangran.top/Article/details/gtvtkrptcx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkbeovwb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.andypj.xyz/Article/details/gtmueymftu.html

[A07] 数字转字符串
来源：http://dali.fengsongda.top/Article/details/gtsachpjqy.html

Py:   str(42)
来源：http://dali.birdmap.top/Article/details/gtmjsfkyxk.html

PHP:  (string) 42; strval(42)
来源：http://dali.yonumen.top/Article/details/gtznrfveas.html

JS:   String(42); (42).toString()
来源：http://dali.9152youxi.cn/Article/details/gthkpoierl.html

TS:   String(42)
来源：http://dali.yuxming.cn/Article/details/gtopfyegsm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gotoacloud.top/Article/details/gtfechyzfr.html

Go:   strconv.Itoa(42)
来源：http://dali.zdqjudy.top/Article/details/gtjskdnqjk.html

Ruby: 42.to_s
来源：http://dali.xinyue.icu/Article/details/gtissghnld.html

C#:   42.ToString()
来源：http://dali.daxiang520.top/Article/details/gtnuyxguvy.html

[A08] 取整与四舍五入
来源：http://dali.kuanghao11.cn/Article/details/gtbrvsiskm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gtbdvviczu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jqgfzy.top/Article/details/gtrclztnas.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtxgwalmvw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.dianchejie.cn/Article/details/gtmbjqbgtp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gtklwdvivh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtghesgwxk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nanxinkj.top/Article/details/gtdzwxdtae.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtdcsypbds.html

[A09] 绝对值与最大最小值
来源：http://dali.cdnleiting.top/Article/details/gtyesgbldi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtsxnbzxsd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hammf.cn/Article/details/gtiliaamet.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtcgmbdafm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sysykeji.top/Article/details/gthpxklgyf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwaouolo.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hongshengwenyu.top/Article/details/gtzbxvhnno.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbcjretl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtcrtezjzb.html


<!-- 参考信息 -->