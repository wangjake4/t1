代发 wailian999

[U65] PHP：会话
来源：http://dali.yj20258888.top/Article/details/gt2jgicolxe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2whmxugis.html

[U66] PHP：设置 Cookie
来源：http://dali.shzxlz.cn/Article/details/gt2gegydjlr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.bjfxy.top/Article/details/gt2dzoppzld.html

[U67] PHP：处理文件上传
来源：http://dali.hnqzz.top/Article/details/gt2qihaufik.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sufxvd.cn/Article/details/gt2zffutddk.html

[U68] PHP：PDO 连接
来源：http://dali.yanxiufei.cn/Article/details/gt2wsrshdca.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xuanzx.com/Article/details/gt2xmpwsfnw.html

[U69] PHP：PDO 预处理
来源：http://dali.yueranfly.top/Article/details/gt2nvjgqysk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fzhhl.top/Article/details/gt2tvuvgfqt.html

[U70] PHP：PDO 事务
来源：http://dali.yangfankeji.com/Article/details/gt2eixhqtdl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.birdmap.top/Article/details/gt2xkkmzktm.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thhurvdr.html

throw new RuntimeException("失败", 500);
来源：http://dali.yongpay.top/Article/details/gt2haquzzcd.html

[U72] PHP：写错误日志
来源：http://dali.nanxinkj.top/Article/details/gt2zmklvnae.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufzupazw.html

[U73] PHP：读取 ini 配置
来源：http://dali.xziqi.cn/Article/details/gt2sunkbkhc.html

parse_ini_file("config.ini", true)
来源：http://dali.sweek.top/Article/details/gt2feuflcsa.html

[U74] PHP：读取环境变量
来源：http://dali.daxiang520.top/Article/details/gt2gphrurrc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hysaishi.cn/Article/details/gt2qzfmvcpq.html

[U75] PHP：依赖注入
来源：http://dali.sxryk.cn/Article/details/gt2xhxpmopt.html

composer require psr/container
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oaizplcb.html

[U76] PHP：简单路由
来源：http://dali.cashguo.top/Article/details/gt2mumucrya.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.smart0.xyz/Article/details/gt2xkvxpvwp.html

[U77] PHP：模板渲染
来源：http://dali.dashuyun.cn/Article/details/gt2dyyuslem.html

composer require twig/twig
来源：http://dali.sweek.top/Article/details/gt2sgijecai.html

[U78] PHP：单元测试
来源：http://dali.mhx1999.top/Article/details/gt2tgwkpqvc.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258.top/Article/details/gt2vyddldcz.html

[U79] PHP：静态分析
来源：http://dali.hfpthk.cn/Article/details/gt2dhzjwubo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znsrbfcf.html

[U80] PHP：代码规范修复
来源：http://dali.chenzaomai.com/Article/details/gt2gdvewyfr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tanke756.top/Article/details/gt2jxdzqpzy.html

[U81] JS：初始化项目
来源：http://dali.sweek.top/Article/details/gt2wvenmuyw.html

npm init -y;  npm i express
来源：http://dali.hammf.cn/Article/details/gt2cwkcbgjn.html

[U82] JS：package.json 脚本
来源：http://dali.aizwys.cn/Article/details/gt2oonjcgjt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jzosovqb.html

[U83] JS：ES Module 导入导出
来源：http://dali.xylfe.cn/Article/details/gt2mznngivm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gt2kotkmvvl.html

[U84] JS：CommonJS 写法
来源：http://dali.yvedp.cn/Article/details/gt2sizykasg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2leuodptt.html

[U85] JS：可选链
来源：http://dali.ivvv.top/Article/details/gt2lhivyhqb.html

a?.b?.c
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjhrywon.html

[U86] JS：空值合并
来源：http://dali.c1oappe.top/Article/details/gt2pdcvpcke.html

a ?? b
来源：http://dali.jinqigufen.top/Article/details/gt2fsoxguvy.html

[U87] JS：解构默认值
来源：http://dali.dianchejie.cn/Article/details/gt2ogremqrh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xuanzx.com/Article/details/gt2xpedhcvh.html

[U88] JS：对象展开合并
来源：http://dali.aizwys.cn/Article/details/gt2iwyqanwq.html

{ ...a, ...b }
来源：http://dali.sysykeji.top/Article/details/gt2kqkhfedx.html

[U89] JS：数组去重
来源：http://dali.sxryk.cn/Article/details/gt2eisqekbu.html

[...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gt2lkkinnvq.html

[U90] JS：数字数组排序
来源：http://dali.xziqi.cn/Article/details/gt2frmiavaz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gt2bkveztvq.html

[U91] JS：对象键值遍历
来源：http://dali.cheryme.top/Article/details/gt2nmomcggk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yongpay.top/Article/details/gt2brvzqrgk.html

[U92] JS：深拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2gplwkkdu.html

structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2kvaxyldb.html

[U93] JS：模板字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2plzlfkpa.html

`共 ${n} 条`
来源：http://dali.nanxuanxn.top/Article/details/gt2yfqrtats.html

[U94] JS：箭头函数
来源：http://dali.xylfe.cn/Article/details/gt2mfxtghbx.html

const double = x => x * 2;
来源：http://dali.sweek.top/Article/details/gt2zoxaickj.html

[U95] JS：Promise 包装
来源：http://dali.yueranfly.top/Article/details/gt2deiycnjm.html

new Promise((resolve, reject) => {})
来源：http://dali.9152youxi.cn/Article/details/gt2rhkppcue.html

[U96] JS：async/await 与异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fugkjujx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2pucydevq.html

[U97] JS：并发请求
来源：http://dali.tanke756.top/Article/details/gt2wwwmookg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2lnkpnbbk.html

[U98] JS：fetch 带 JSON
来源：http://dali.sxryk.cn/Article/details/gt2wbjochac.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gaohongyu789.top/Article/details/gt2zabomavd.html

[U99] JS：事件监听
来源：http://dali.fengsongda.top/Article/details/gt2bklrsbbu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nolhwktv.html

[U100] JS：DOM 查询
来源：http://dali.shzxlz.cn/Article/details/gt2gjgicplz.html

document.querySelector(".item")
来源：http://dali.tanke756.top/Article/details/gt2ipdgmdie.html

[U101] JS：classList 操作
来源：http://dali.ydzc1.top/Article/details/gt2fytnwizv.html

el.classList.toggle("active")
来源：http://dali.guannengcc.top/Article/details/gt2pctscwxh.html

[U102] JS：本地存储
来源：http://dali.hnxiangtu.top/Article/details/gt2cjpmlewj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gzhubu.top/Article/details/gt2igzwckyi.html

[U103] JS：定时器
来源：http://dali.andypj.xyz/Article/details/gt2wsnoqiuo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yonumen.top/Article/details/gt2djcoynzm.html

[U104] JS：防抖
来源：http://dali.chenzaomai.com/Article/details/gt2ruqkxemb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gt2qxtqbule.html

[U105] JS：节流
来源：http://dali.xziqi.cn/Article/details/gt2yqujdakr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hywenlv.cn/Article/details/gt2gizfelib.html

[U106] JS：日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezduidgw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.c1oappe.top/Article/details/gt2vimfadqp.html

[U107] JS：数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gt2sroznyfl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2oodxkewd.html

[U108] JS：随机整数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptibcupq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cheryme.top/Article/details/gt2hlnnytde.html

[U109] JS：数组分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjrshdgn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gt2izfejlyg.html

[U110] JS：数组分块
来源：http://dali.sysykeji.top/Article/details/gt2tdcgdxum.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cashguo.top/Article/details/gt2tqdhvsen.html

[U111] JS：对象转 Map
来源：http://dali.gaohongyu789.top/Article/details/gt2ybjdokoq.html

new Map(Object.entries(obj))
来源：http://dali.sxryk.cn/Article/details/gt2ltcmgdpf.html

[U112] JS：字符串补位
来源：http://dali.vqdsnc.cn/Article/details/gt2nvifcqhw.html

"7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2qgialyhq.html

[U113] JS：正则替换全部
来源：http://dali.hnxiangtu.top/Article/details/gt2selrysvt.html

s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2nudcucte.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gt2kqaqtopm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvncgrwu.html

[U115] JS：生成 UUID
来源：http://dali.xinyue.icu/Article/details/gt2qdszawfl.html

crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gt2sroypxgn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hfpthk.cn/Article/details/gt2rfmdjelx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.bjfxy.top/Article/details/gt2yxouvdgq.html

[U117] JS：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gt2dunygsuh.html

npm i -D vitest;  npx vitest
来源：http://dali.yangfankeji.com/Article/details/gt2nyqqqqqq.html

[U118] JS：开发服务器
来源：http://dali.chenlongwang.top/Article/details/gt2pfibpmzl.html

npm i -D vite;  npx vite
来源：http://dali.snrcjt.cn/Article/details/gt2httzpchp.html

[U119] JS：生产构建
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qukswnef.html

npx vite build
来源：http://dali.iojbl.cn/Article/details/gt2tvgnuzvy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tanke756.top/Article/details/gt2qrwhgkzy.html

import.meta.env.VITE_API_URL
来源：http://dali.tianlin.xyz/Article/details/gt2vcormplo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2sjstzvaa.html

统计汇总
来源：http://dali.cucudq.cn/Article/details/gt2woitnajm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ruxghpho.html

按语言统计（条）：
来源：http://dali.zhengqikj.top/Article/details/gt2lseeizgd.html

Python ......... 252
来源：http://dali.birdmap.top/Article/details/gt2hlqqitth.html

PHP ............ 252
来源：http://dali.jqgfzy.top/Article/details/gt2yajztyas.html

JavaScript ..... 252
来源：http://dali.daxiang520.top/Article/details/gt2dibtvwdb.html

TypeScript ..... 212
来源：http://dali.jianghu66.top/Article/details/gt2hdbmxvoq.html

Java ........... 212
来源：http://dali.tianlin.xyz/Article/details/gt2rfbabxco.html

Go ............. 212
来源：http://dali.c1oappe.top/Article/details/gt2nbxvbtbr.html

Ruby ........... 212
来源：http://dali.jlsjyb.cn/Article/details/gt2hkcjphoz.html

C# ............. 212
来源：http://dali.pycfn.com/Article/details/gt2hqtkrlep.html

C .............. 30
来源：http://dali.nanxinkj.top/Article/details/gt2wnmveufb.html

C++ ............ 30
来源：http://dali.shangyingyoupin.top/Article/details/gt2qlxogvej.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjxdmmd.html

Bash ........... 80
来源：http://dali.zhoulong.xyz/Article/details/gt2pgwphywz.html

Kotlin ......... 15
来源：http://dali.ehwqpu.com/Article/details/gt2rkonkkip.html

Swift .......... 15
来源：http://dali.wangdashe.top/Article/details/gt2gawcrszw.html

Lua ............ 10
来源：http://dali.sysykeji.top/Article/details/gt2csyqbatk.html

Perl ........... 10
来源：http://dali.yanxiufei.cn/Article/details/gt2ixdbdywp.html

Scala .......... 10
来源：http://dali.zdqjudy.top/Article/details/gt2fiscgocv.html

------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmzukbju.html

合计 ........... 2106 条
来源：http://dali.wangdashe.top/Article/details/gt2ynmihrbe.html

按章节统计：
来源：http://dali.jinqigufen.top/Article/details/gt2dchwpntn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jqgufenzy.top/Article/details/gt2hltmgunk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2doflymza.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gt2eglfxuct.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gt2abvigujc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.bjfxy.top/Article/details/gt2cimbphgp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xsxbhfbz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gt2kimemgcm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrxqbgho.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gt2rlbdfnqp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gt2jhtexadk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gt2ansvfnhz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2avnswmji.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2oipzzxhr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gt2orgrtcff.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenlongwang.top/Article/details/gt2ifpjiuxv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gt2dyhtipnz.html

Q SQL 专题                              90
来源：http://dali.yuanzhike.top/Article/details/gt2syjbsivu.html

R Bash 专题                             80
来源：http://dali.cashguo.top/Article/details/gt2rxpsgfsw.html

S C / C++ 专题                          60
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzebyldd.html

T 其他语言补充                          60
来源：http://dali.yj20258888.top/Article/details/gt2dgnzhgdf.html

U 高频实用片段                         120
来源：http://dali.ivvv.top/Article/details/gt2bvksvnst.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gt2neocxszk.html

合计                                  2106 条
来源：http://dali.vqdsnc.cn/Article/details/gt2lsfoqukd.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gt2qydjsnmm.html

使用提醒
来源：http://dali.yueranfly.top/Article/details/gt2srhglrim.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gt2syovhlhr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zycfv.cn/Article/details/gt2tmayysol.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.dianchejie.cn/Article/details/gt2rotutnxu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.dianchejie.cn/Article/details/gt2kgxjechb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jlsjyb.cn/Article/details/gt2ewkvholv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwjusscm.html

—— 文件结束 ——
来源：http://dali.snrcjt.cn/Article/details/gt2xwgycapf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqrcnuim.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sysykeji.top/Article/details/gt2ohtnpbqi.html

Common Programming Examples Cheat Book
来源：http://dali.birdmap.top/Article/details/gt2znicloti.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifdgbfsp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ikppndpm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.wangdashe.top/Article/details/gt2dzzhpvsh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pengpengdd.cyou/Article/details/gt2sycwakyw.html

SQL · Bash · C · C++
来源：http://dali.xuetiantiany.cn/Article/details/gt2pysjnfew.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.quarkkingdee.top/Article/details/gt2zliameol.html

【使用说明】
来源：http://dali.jlsjyb.cn/Article/details/gt2dxajczuj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.9152youxi.cn/Article/details/gt2tnccfipc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenlongwang.top/Article/details/gt2wjjmcodh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.fengsongda.top/Article/details/gt2ffdxpbgj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zdqjudy.top/Article/details/gt2jhfjhukh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nwbrower.top/Article/details/gt2clksuadr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmlqwxzv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gotoacloud.top/Article/details/gt2ntqocirf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xinyue.icu/Article/details/gt2cpdgzyqy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2lczdrchb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aizwys.cn/Article/details/gt2jpesfgot.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hywenlv.cn/Article/details/gt2mifgmlpm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenlongwang.top/Article/details/gt2mwkohtef.html

【文件统计】
来源：http://dali.hfpthk.cn/Article/details/gt2xvbkhcgx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xziqi.cn/Article/details/gt2qfoqstep.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gt2zagbhhen.html

目  录
来源：http://dali.gogol.net.cn/Article/details/gt2jorpnujy.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gt2qkmcffhs.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvzubpqv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gt2kpgpjvjt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzyekcf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gt2idnumczb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcacealq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2fsbzaufw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gt2arslexxf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yangfankeji.com/Article/details/gt2dgwzuyep.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2lsoqrqza.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hnqzz.top/Article/details/gt2seyyggqd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydgvejto.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gt2uvagwizo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gt2xitbpqtj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gt2nfqdzdun.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.meibo888.top/Article/details/gt2jxhzkssn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nskxnobc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuxming.cn/Article/details/gt2utbwzrxx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.aizwys.cn/Article/details/gt2mxlqybpp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2istinsbz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gt2wjcfbqbg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gt2flwvzcgo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2iluenvks.html

A. 基础语法与类型
来源：http://dali.xuanzx.com/Article/details/gt2gdbtejez.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ostimdcb.html

[A01] Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjfrfezt.html

Py:   print("Hello, World!")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcwbjzwz.html

PHP:  echo "Hello, World!";
来源：http://dali.gotoacloud.top/Article/details/gt2vfrfhfih.html

JS:   console.log("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gt2pbqjgspr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tian-w.cn/Article/details/gt2fklrzcmt.html

Java: System.out.println("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gt2ilmtoohr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj20258888.top/Article/details/gt2meagbbjr.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgufenzy.top/Article/details/gt2gcyjuizs.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinqigufen.top/Article/details/gt2adgbefwq.html

[A02] 变量声明与赋值
来源：http://dali.iojbl.cn/Article/details/gt2kluvoveg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgbdiufe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ehwqpu.com/Article/details/gt2rovjwtnf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shuidangran.top/Article/details/gt2vsbxgyab.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hammf.cn/Article/details/gt2qgxlwgrs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gt2uxqdymhl.html

Go:   name := "Alex"; age := 20
来源：http://dali.xuetiantiany.cn/Article/details/gt2ymkekhta.html

Ruby: name = "Alex"; age = 20
来源：http://dali.quarkkingdee.top/Article/details/gt2rzxxohsz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gt2kgbgqanz.html

[A03] 常量定义
来源：http://dali.gzhubu.top/Article/details/gt2ccsedivk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ppjwa.cn/Article/details/gt2wiclkahm.html

PHP:  const PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2xasefidj.html

JS:   const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2dgrxhhzz.html

TS:   const PI: number = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2rbsftvaz.html

Java: static final double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2hxcngxsr.html

Go:   const PI = 3.14159
来源：http://dali.0kj1m.cn/Article/details/gt2qwenpnub.html

Ruby: PI = 3.14159
来源：http://dali.ybcxt.top/Article/details/gt2akaphpte.html

C#:   const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2mmovqblj.html

[A04] 判断变量类型
来源：http://dali.smart0.xyz/Article/details/gt2gnjiktyh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhongyouzk.top/Article/details/gt2peblhbma.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj20258.top/Article/details/gt2vpuvttml.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ehwqpu.com/Article/details/gt2pqcpaxtw.html

TS:   typeof x; x instanceof Date
来源：http://dali.aibaodan.cn/Article/details/gt2xfaazqeb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zycfv.cn/Article/details/gt2hbbouumx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhixingplan.top/Article/details/gt2fgoaeqtv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xuanzx.com/Article/details/gt2drvmffvw.html

C#:   x.GetType().Name; x is int
来源：http://dali.cashguo.top/Article/details/gt2itmfnzhs.html

[A05] 整数除法与取模
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rghxpqkk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dashuyun.cn/Article/details/gt2daipvkfe.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gt2fijhxnpl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2phmkhdnx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gt2quanplsc.html

Java: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2gslryomu.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2gifuxwhm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gt2akxabygu.html

C#:   7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gt2jznkkjjh.html

[A06] 字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gt2aerpuoqn.html

Py:   int("42"); float("3.14")
来源：http://dali.cucudq.cn/Article/details/gt2tuqdjboh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kusfhgqu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.fengsongda.top/Article/details/gt2sajdushr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gt2yypttjia.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.mhx1999.top/Article/details/gt2yayrysxs.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jqgufenzy.top/Article/details/gt2etbzmyhv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqqewujv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sufxvd.cn/Article/details/gt2ptmwjcyc.html

[A07] 数字转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2vqjvmaxa.html

Py:   str(42)
来源：http://dali.wangdashe.top/Article/details/gt2gcomxqbt.html

PHP:  (string) 42; strval(42)
来源：http://dali.yuxming.cn/Article/details/gt2nvzatfgm.html

JS:   String(42); (42).toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2fmkevpsi.html

TS:   String(42)
来源：http://dali.jyoumei.cn/Article/details/gt2fvxfzaib.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cdnleiting.top/Article/details/gt2pystemva.html

Go:   strconv.Itoa(42)
来源：http://dali.ehwqpu.com/Article/details/gt2rexbftip.html

Ruby: 42.to_s
来源：http://dali.mhx1999.top/Article/details/gt2djukqsmy.html

C#:   42.ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbvbdrnb.html

[A08] 取整与四舍五入
来源：http://dali.cdnleiting.top/Article/details/gt2rabjjesf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gt2hvqappuk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.wangdashe.top/Article/details/gt2wfgthrsq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gt2czdmfsuj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhixingplan.top/Article/details/gt2vsgchawr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gt2zdjyyqjg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gt2qfbgisfc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.haohaochexian.top/Article/details/gt2gvqqtawh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gt2bntjgpso.html

[A09] 绝对值与最大最小值
来源：http://dali.yvedp.cn/Article/details/gt2nuqxepom.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2fqgthhzd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2mjexuvng.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2bhiayepn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjtnheuo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvmarqnk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.guowangkeji.top/Article/details/gt2kgiydydu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hfpthk.cn/Article/details/gt2qqmdciny.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gt2lmrgoizy.html


<!-- 参考信息 -->