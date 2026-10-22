代发 wailian999

[U65] PHP：会话
来源：http://dali.zycfv.cn/Article/details/gt2vltixbzq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2ccxleine.html

[U66] PHP：设置 Cookie
来源：http://dali.ydzc1.top/Article/details/gt2dzmaugju.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2yxkxswur.html

[U67] PHP：处理文件上传
来源：http://dali.jyoumei.cn/Article/details/gt2mgpkdkoh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glgpqqxx.html

[U68] PHP：PDO 连接
来源：http://dali.daria6918.cn/Article/details/gt2lzpngumn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jianghu66.top/Article/details/gt2pcydrojj.html

[U69] PHP：PDO 预处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcupeihd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.meibo888.top/Article/details/gt2zswfwhiy.html

[U70] PHP：PDO 事务
来源：http://dali.aizwys.cn/Article/details/gt2idsyptxh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.fzhhl.top/Article/details/gt2xwleicps.html

[U71] PHP：抛出异常
来源：http://dali.zhengqikj.top/Article/details/gt2slkxnnax.html

throw new RuntimeException("失败", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjhslahx.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gt2ohybajnp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.bjfxy.top/Article/details/gt2koclexmm.html

[U73] PHP：读取 ini 配置
来源：http://dali.xziqi.cn/Article/details/gt2tdsjxkyh.html

parse_ini_file("config.ini", true)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olcenpbw.html

[U74] PHP：读取环境变量
来源：http://dali.birdmap.top/Article/details/gt2gpjlczbg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwpmlmns.html

[U75] PHP：依赖注入
来源：http://dali.xziqi.cn/Article/details/gt2tosgaxsf.html

composer require psr/container
来源：http://dali.cheryme.top/Article/details/gt2mvwaeymc.html

[U76] PHP：简单路由
来源：http://dali.nwbrower.top/Article/details/gt2yhljfqgw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.mhx1999.top/Article/details/gt2uphftzgy.html

[U77] PHP：模板渲染
来源：http://dali.daria6918.cn/Article/details/gt2whtcieej.html

composer require twig/twig
来源：http://dali.gaohongyu789.top/Article/details/gt2kwtpzmgg.html

[U78] PHP：单元测试
来源：http://dali.snrcjt.cn/Article/details/gt2pmqmfvjc.html

composer require --dev phpunit/phpunit
来源：http://dali.zdqjudy.top/Article/details/gt2xjtdkezo.html

[U79] PHP：静态分析
来源：http://dali.meibo888.top/Article/details/gt2hithxdgw.html

composer require --dev phpstan/phpstan
来源：http://dali.hywenlv.cn/Article/details/gt2lodepjhs.html

[U80] PHP：代码规范修复
来源：http://dali.guowangkeji.top/Article/details/gt2pozsdcsb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenzaomai.com/Article/details/gt2krfowdbw.html

[U81] JS：初始化项目
来源：http://dali.zycfv.cn/Article/details/gt2kcbhijkg.html

npm init -y;  npm i express
来源：http://dali.shuidangran.top/Article/details/gt2klkduuto.html

[U82] JS：package.json 脚本
来源：http://dali.zdqjudy.top/Article/details/gt2rajoifeg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnqzz.top/Article/details/gt2vpxrnktt.html

[U83] JS：ES Module 导入导出
来源：http://dali.tianlin.xyz/Article/details/gt2alglnjnr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gt2inucpuul.html

[U84] JS：CommonJS 写法
来源：http://dali.tianlin.xyz/Article/details/gt2ebrtyset.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkfoijvf.html

[U85] JS：可选链
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pybyledg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpgirvv.html

[U86] JS：空值合并
来源：http://dali.jqgfzy.top/Article/details/gt2gpdubuel.html

a ?? b
来源：http://dali.bjfxy.top/Article/details/gt2tfywvsvt.html

[U87] JS：解构默认值
来源：http://dali.yueranfly.top/Article/details/gt2ubibgivi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.9152youxi.cn/Article/details/gt2ygjmcfbt.html

[U88] JS：对象展开合并
来源：http://dali.birdmap.top/Article/details/gt2ltgetuwr.html

{ ...a, ...b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qaqnarpi.html

[U89] JS：数组去重
来源：http://dali.pycfn.com/Article/details/gt2lvbvyduy.html

[...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gt2pacyvfvl.html

[U90] JS：数字数组排序
来源：http://dali.tian-w.cn/Article/details/gt2gbzqzifp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gt2wtmmkwwd.html

[U91] JS：对象键值遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lrfelgao.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.nwbrower.top/Article/details/gt2kfgaikcn.html

[U92] JS：深拷贝
来源：http://dali.hnqzz.top/Article/details/gt2pepujptx.html

structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2grvczghf.html

[U93] JS：模板字符串
来源：http://dali.tian-w.cn/Article/details/gt2zusanzjw.html

`共 ${n} 条`
来源：http://dali.iojbl.cn/Article/details/gt2biqpgkrq.html

[U94] JS：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gt2ndpvblkn.html

const double = x => x * 2;
来源：http://dali.zhengqikj.top/Article/details/gt2ydmclyiv.html

[U95] JS：Promise 包装
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2etsnpuwk.html

new Promise((resolve, reject) => {})
来源：http://dali.yuxming.cn/Article/details/gt2cmboxurf.html

[U96] JS：async/await 与异常
来源：http://dali.jqgfzy.top/Article/details/gt2gokicwzn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gt2hkngtxot.html

[U97] JS：并发请求
来源：http://dali.havefunace.top/Article/details/gt2kfgrfzkz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2rharcnqd.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2livbyqgt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fengsongda.top/Article/details/gt2uqkvfskm.html

[U99] JS：事件监听
来源：http://dali.nanxinkj.top/Article/details/gt2sgdfanko.html

el.addEventListener("click", e => {})
来源：http://dali.wangdashe.top/Article/details/gt2tholaqzx.html

[U100] JS：DOM 查询
来源：http://dali.nanxinkj.top/Article/details/gt2wisphwkf.html

document.querySelector(".item")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjzicagq.html

[U101] JS：classList 操作
来源：http://dali.zhoulong.xyz/Article/details/gt2vkflofvt.html

el.classList.toggle("active")
来源：http://dali.kuanghao11.cn/Article/details/gt2rfvmzdyn.html

[U102] JS：本地存储
来源：http://dali.cucudq.cn/Article/details/gt2nfftambi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.redwolf501.top/Article/details/gt2ashoxidf.html

[U103] JS：定时器
来源：http://dali.ppjwa.cn/Article/details/gt2otgqosok.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.dianchejie.cn/Article/details/gt2ythftzdp.html

[U104] JS：防抖
来源：http://dali.c1oappe.top/Article/details/gt2gglyaxil.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2pmdytvul.html

[U105] JS：节流
来源：http://dali.xylfe.cn/Article/details/gt2rxisasip.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fengsongda.top/Article/details/gt2vkqdjnnl.html

[U106] JS：日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gt2pynvvohe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xziqi.cn/Article/details/gt2uatqftom.html

[U107] JS：数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htljtyiu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gt2rsjshjme.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gt2dylptjep.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.9152youxi.cn/Article/details/gt2utsvgzmp.html

[U109] JS：数组分组
来源：http://dali.c1oappe.top/Article/details/gt2zabjfpmy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gt2nklsagzd.html

[U110] JS：数组分块
来源：http://dali.jqgfzy.top/Article/details/gt2tpwsxczh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ybcxt.top/Article/details/gt2kxpyvdgx.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gt2jorjnvor.html

new Map(Object.entries(obj))
来源：http://dali.316326.xyz/Article/details/gt2sumnjwzf.html

[U112] JS：字符串补位
来源：http://dali.zhoulong.xyz/Article/details/gt2fehshxod.html

"7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2eoenkzwa.html

[U113] JS：正则替换全部
来源：http://dali.shzxlz.cn/Article/details/gt2cdievssu.html

s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2lhaxloeo.html

[U114] JS：JSON 深比较
来源：http://dali.redwolf501.top/Article/details/gt2pbwavchu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2kejnyxqw.html

[U115] JS：生成 UUID
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojebmehu.html

crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gt2ipjibnzz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hywenlv.cn/Article/details/gt2arrrcvxq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbiqgbhu.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gt2vxufvopa.html

npm i -D vitest;  npx vitest
来源：http://dali.hfpthk.cn/Article/details/gt2hjmbthjq.html

[U118] JS：开发服务器
来源：http://dali.jinqigufen.top/Article/details/gt2kqcahknd.html

npm i -D vite;  npx vite
来源：http://dali.shzxlz.cn/Article/details/gt2cshmphol.html

[U119] JS：生产构建
来源：http://dali.chenzaomai.com/Article/details/gt2nrsblpck.html

npx vite build
来源：http://dali.mhx1999.top/Article/details/gt2hzrwjcdv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.haohaochexian.top/Article/details/gt2kmloyczf.html

import.meta.env.VITE_API_URL
来源：http://dali.andypj.xyz/Article/details/gt2klyijjws.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2awqjcvho.html

统计汇总
来源：http://dali.sweek.top/Article/details/gt2cnaewcmz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2anywpcaq.html

按语言统计（条）：
来源：http://dali.yj20258.top/Article/details/gt2ykgtrvgs.html

Python ......... 252
来源：http://dali.cashguo.top/Article/details/gt2zhiobpfc.html

PHP ............ 252
来源：http://dali.snrcjt.cn/Article/details/gt2rqiirqxr.html

JavaScript ..... 252
来源：http://dali.hongshengwenyu.top/Article/details/gt2idmsditg.html

TypeScript ..... 212
来源：http://dali.dianchejie.cn/Article/details/gt2txjvyecj.html

Java ........... 212
来源：http://dali.yj202588.top/Article/details/gt2tzqwnjdr.html

Go ............. 212
来源：http://dali.chenzaomai.com/Article/details/gt2tuqxsllg.html

Ruby ........... 212
来源：http://dali.9152youxi.cn/Article/details/gt2dynynang.html

C# ............. 212
来源：http://dali.cashguo.top/Article/details/gt2sfxdcopj.html

C .............. 30
来源：http://dali.ybcxt.top/Article/details/gt2wvqrdqsj.html

C++ ............ 30
来源：http://dali.wangshuangyany.cn/Article/details/gt2dyuazdhh.html

SQL ............ 90
来源：http://dali.snrcjt.cn/Article/details/gt2tuzsfgef.html

Bash ........... 80
来源：http://dali.tanke756.top/Article/details/gt2fvyzmhnw.html

Kotlin ......... 15
来源：http://dali.yanxiufei.cn/Article/details/gt2wibdgcpw.html

Swift .......... 15
来源：http://dali.zdqjudy.top/Article/details/gt2ypoxekme.html

Lua ............ 10
来源：http://dali.tianlin.xyz/Article/details/gt2zxtqmvlq.html

Perl ........... 10
来源：http://dali.hongshengwenyu.top/Article/details/gt2pldofyft.html

Scala .......... 10
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gorqatsy.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gt2vyuwdnnb.html

合计 ........... 2106 条
来源：http://dali.guowangkeji.top/Article/details/gt2jokletgs.html

按章节统计：
来源：http://dali.feifeiyinyue.top/Article/details/gt2eunlhgbw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gt2uxkbafja.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gt2xzfexnsr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kviuualr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gt2eeyvtrxt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cashguo.top/Article/details/gt2crqpkqmj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gt2ckpclyrn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gt2dxiqdujn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfmtpykk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddpsosgl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gt2fhqrhzab.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gt2hfdpttcn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2smgvshlq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2nmhjfuyv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gt2wtfrfape.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ppjwa.cn/Article/details/gt2sleeyybu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gt2fguulaur.html

Q SQL 专题                              90
来源：http://dali.cqqwz.cn/Article/details/gt2clddcthn.html

R Bash 专题                             80
来源：http://dali.sxryk.cn/Article/details/gt2eulkzndh.html

S C / C++ 专题                          60
来源：http://dali.shzxlz.cn/Article/details/gt2apxoenns.html

T 其他语言补充                          60
来源：http://dali.gogol.net.cn/Article/details/gt2mblqheab.html

U 高频实用片段                         120
来源：http://dali.zhengqikj.top/Article/details/gt2luyuzqyb.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2dxxgjtfz.html

合计                                  2106 条
来源：http://dali.tanke756.top/Article/details/gt2djjvfcel.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gt2ksmnmdiq.html

使用提醒
来源：http://dali.birdmap.top/Article/details/gt2kvmmfkcp.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2uazzsstz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yvedp.cn/Article/details/gt2cutycwid.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yonumen.top/Article/details/gt2ncwyefft.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yvedp.cn/Article/details/gt2wafqixjz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xziqi.cn/Article/details/gt2bysgqdnd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cdnleiting.top/Article/details/gt2dbltwhkx.html

—— 文件结束 ——
来源：http://dali.yangfankeji.com/Article/details/gt2aomytele.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cgazmwzv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jianghu66.top/Article/details/gt2gullmvgd.html

Common Programming Examples Cheat Book
来源：http://dali.ybcxt.top/Article/details/gt2ixaifokd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2txrkgght.html

【收录内容】
来源：http://dali.fengsongda.top/Article/details/gt2effmayzg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shuidangran.top/Article/details/gt2pkdbslux.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenzaomai.com/Article/details/gt2itvcdpfx.html

SQL · Bash · C · C++
来源：http://dali.xylfe.cn/Article/details/gt2lfcpssot.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhiwuduotai.top/Article/details/gt2tuvinysu.html

【使用说明】
来源：http://dali.0kj1m.cn/Article/details/gt2qininbww.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cdnleiting.top/Article/details/gt2uigeinwt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhixingplan.top/Article/details/gt2jpkvtpxr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aibaodan.cn/Article/details/gt2uttfhpih.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xylfe.cn/Article/details/gt2eiqbzlqm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigufen.top/Article/details/gt2plxtmfux.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.havefunace.top/Article/details/gt2ajfbpvlp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangdashe.top/Article/details/gt2lopcyvbm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.snrcjt.cn/Article/details/gt2qnnwhpan.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xinyue.icu/Article/details/gt2tcqfmrrn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aibaodan.cn/Article/details/gt2wtsftifl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zycfv.cn/Article/details/gt2gkdsxayb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yuanzhike.top/Article/details/gt2hyavtzag.html

【文件统计】
来源：http://dali.quarkkingdee.top/Article/details/gt2pnoweddy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hfpthk.cn/Article/details/gt2mywtxozr.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2qlaruyfe.html

目  录
来源：http://dali.vqdsnc.cn/Article/details/gt2lkznzvlc.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2jbuvnwlp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lauqsqdi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gt2xfmxbzxa.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gt2ezerulue.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gt2chsjtqdr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2bfwjvxwm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gt2cqnvmzmq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gt2djnhflxi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.smart0.xyz/Article/details/gt2mdvkazbt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgiuoyem.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.daria6918.cn/Article/details/gt2sprzefdg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gt2mqslvxqa.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gt2bblyfslu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gt2kvknhbuc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zycfv.cn/Article/details/gt2nzjpfiwg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2cvmmntyo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gt2vpptlpft.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zdqjudy.top/Article/details/gt2mtjoveff.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.bjfxy.top/Article/details/gt2sssvssfs.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aizwys.cn/Article/details/gt2zyfzrwdv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gt2dtoszcgt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gt2btfsjgij.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2hzowgapb.html

A. 基础语法与类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmcpmnjx.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2cgzmzovv.html

[A01] Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2qkxakjty.html

Py:   print("Hello, World!")
来源：http://dali.hnqzz.top/Article/details/gt2hvroutpf.html

PHP:  echo "Hello, World!";
来源：http://dali.guowangkeji.top/Article/details/gt2amztopxw.html

JS:   console.log("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gt2yuckbuag.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xinyue.icu/Article/details/gt2tffrmsfr.html

Java: System.out.println("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gt2jzqinotd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gt2rjmnhjnv.html

Ruby: puts "Hello, World!"
来源：http://dali.gogol.net.cn/Article/details/gt2rfhrkpgd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gt2gzoouyap.html

[A02] 变量声明与赋值
来源：http://dali.xuanzx.com/Article/details/gt2hbvenqhx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.redwolf501.top/Article/details/gt2gyrtxapt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.dianchejie.cn/Article/details/gt2hcklkazh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jqgfzy.top/Article/details/gt2rcjcbjjv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jniadhdj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2kgvltyjj.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owuxefzb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.wangshuangyany.cn/Article/details/gt2oylnsobf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hywenlv.cn/Article/details/gt2ngcyyekc.html

[A03] 常量定义
来源：http://dali.hnqzz.top/Article/details/gt2zyxhmskl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2komjmnws.html

PHP:  const PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2qgxfiyxm.html

JS:   const PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2gongcdfw.html

TS:   const PI: number = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2xiafzayd.html

Java: static final double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2vfhuqawu.html

Go:   const PI = 3.14159
来源：http://dali.guannengcc.top/Article/details/gt2njbzpcku.html

Ruby: PI = 3.14159
来源：http://dali.nanxinkj.top/Article/details/gt2usbopwoi.html

C#:   const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2ciuodpqs.html

[A04] 判断变量类型
来源：http://dali.yongpay.top/Article/details/gt2ngeocbti.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gt2qpzxoigq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuanzhike.top/Article/details/gt2brgyefke.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tanke756.top/Article/details/gt2ototefuc.html

TS:   typeof x; x instanceof Date
来源：http://dali.tanke756.top/Article/details/gt2ijttfcss.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.0kj1m.cn/Article/details/gt2zvksusvu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dashuyun.cn/Article/details/gt2xgeaoiiq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.iojbl.cn/Article/details/gt2pyiuyxfu.html

C#:   x.GetType().Name; x is int
来源：http://dali.guannengcc.top/Article/details/gt2jdeudjur.html

[A05] 整数除法与取模
来源：http://dali.yonumen.top/Article/details/gt2ehngcbxu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.fengsongda.top/Article/details/gt2ixkklnav.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2eodwxqmk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.smart0.xyz/Article/details/gt2oruolwru.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gt2qkjwpcan.html

Java: 7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2qxiucizw.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2xxfhirhh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gt2mbjgdfsh.html

C#:   7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytuhbhux.html

[A06] 字符串转数字
来源：http://dali.redwolf501.top/Article/details/gt2meuwqykd.html

Py:   int("42"); float("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlmyfyah.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.redwolf501.top/Article/details/gt2mjczpzjz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gt2nbtxbpay.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.pengpengdd.cyou/Article/details/gt2grpudxun.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aibaodan.cn/Article/details/gt2whfddila.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.aibaodan.cn/Article/details/gt2mjjavqfu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjaxgapm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhengqikj.top/Article/details/gt2wvuqgktw.html

[A07] 数字转字符串
来源：http://dali.jyoumei.cn/Article/details/gt2gxfouedq.html

Py:   str(42)
来源：http://dali.shangyingyoupin.top/Article/details/gt2guauheik.html

PHP:  (string) 42; strval(42)
来源：http://dali.ybcxt.top/Article/details/gt2gjkubeqo.html

JS:   String(42); (42).toString()
来源：http://dali.yuxming.cn/Article/details/gt2eojcftez.html

TS:   String(42)
来源：http://dali.fzhhl.top/Article/details/gt2ssinxvvl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.kuanghao11.cn/Article/details/gt2fzngwmtq.html

Go:   strconv.Itoa(42)
来源：http://dali.shuidangran.top/Article/details/gt2bnkimqbb.html

Ruby: 42.to_s
来源：http://dali.fengsongda.top/Article/details/gt2svuwjuzw.html

C#:   42.ToString()
来源：http://dali.ivvv.top/Article/details/gt2hggrqwbz.html

[A08] 取整与四舍五入
来源：http://dali.jinqigufen.top/Article/details/gt2cexqnezk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqkivavd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.daxiang520.top/Article/details/gt2mjkxtzps.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gt2ffhzujpt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jqgufenzy.top/Article/details/gt2pqihwfri.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gt2yobsbyqe.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gt2xqorlfcn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cucudq.cn/Article/details/gt2qinkppmm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.316326.xyz/Article/details/gt2dwmapcnw.html

[A09] 绝对值与最大最小值
来源：http://dali.yvedp.cn/Article/details/gt2vozjiacx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.iojbl.cn/Article/details/gt2jnjdlrjt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2sfsnjqei.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2sygszlqf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2jkayhhro.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2eifruhvm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.guannengcc.top/Article/details/gt2adyzpyoj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhengqikj.top/Article/details/gt2wremzcbo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2fgufmwwi.html


<!-- 参考信息 -->