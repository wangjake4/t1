代发 wailian999

[U65] PHP：会话
来源：http://dali.0kj1m.cn/Article/details/gt2ahhtbkws.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2aedexzes.html

[U66] PHP：设置 Cookie
来源：http://dali.cqqwz.cn/Article/details/gt2uhatbvsr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ivvv.top/Article/details/gt2hnenmoan.html

[U67] PHP：处理文件上传
来源：http://dali.cqqwz.cn/Article/details/gt2ijukdsiy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hfpthk.cn/Article/details/gt2xjmyqqgv.html

[U68] PHP：PDO 连接
来源：http://dali.yueranfly.top/Article/details/gt2rqgqhwio.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2diuwjmrh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwiopqi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangdashe.top/Article/details/gt2wtvzwuwz.html

[U70] PHP：PDO 事务
来源：http://dali.iojbl.cn/Article/details/gt2skancqyx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj202588.top/Article/details/gt2hsejfvuv.html

[U71] PHP：抛出异常
来源：http://dali.sufxvd.cn/Article/details/gt2zdvmbqmj.html

throw new RuntimeException("失败", 500);
来源：http://dali.quarkkingdee.top/Article/details/gt2kopnpivf.html

[U72] PHP：写错误日志
来源：http://dali.gogol.net.cn/Article/details/gt2cmnfnldf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhixingplan.top/Article/details/gt2ekcntpsn.html

[U73] PHP：读取 ini 配置
来源：http://dali.cdnleiting.top/Article/details/gt2maclwhod.html

parse_ini_file("config.ini", true)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oaefdayx.html

[U74] PHP：读取环境变量
来源：http://dali.cheryme.top/Article/details/gt2whxwckcu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhiwuduotai.top/Article/details/gt2sugnoncp.html

[U75] PHP：依赖注入
来源：http://dali.daxiang520.top/Article/details/gt2jfggelmn.html

composer require psr/container
来源：http://dali.yuanzhike.top/Article/details/gt2blixmida.html

[U76] PHP：简单路由
来源：http://dali.sysykeji.top/Article/details/gt2nesrdefh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abcpdcci.html

[U77] PHP：模板渲染
来源：http://dali.yanxiufei.cn/Article/details/gt2jmwqlmos.html

composer require twig/twig
来源：http://dali.sxryk.cn/Article/details/gt2vytanqfo.html

[U78] PHP：单元测试
来源：http://dali.nanxinkj.top/Article/details/gt2oykqezlx.html

composer require --dev phpunit/phpunit
来源：http://dali.pycfn.com/Article/details/gt2mcpohcqb.html

[U79] PHP：静态分析
来源：http://dali.ivvv.top/Article/details/gt2zqqifdar.html

composer require --dev phpstan/phpstan
来源：http://dali.tianlin.xyz/Article/details/gt2qyegmqsi.html

[U80] PHP：代码规范修复
来源：http://dali.sxryk.cn/Article/details/gt2tsbfmecp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gt2svugnxnw.html

[U81] JS：初始化项目
来源：http://dali.nanxinkj.top/Article/details/gt2yukuaurg.html

npm init -y;  npm i express
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxxwpkcf.html

[U82] JS：package.json 脚本
来源：http://dali.daria6918.cn/Article/details/gt2ebvlysnt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sufxvd.cn/Article/details/gt2peejyxdt.html

[U83] JS：ES Module 导入导出
来源：http://dali.hnxiangtu.top/Article/details/gt2zzxcvjoc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gt2sqtpveau.html

[U84] JS：CommonJS 写法
来源：http://dali.ppjwa.cn/Article/details/gt2vatyueyu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xuanzx.com/Article/details/gt2bjpevscm.html

[U85] JS：可选链
来源：http://dali.sweek.top/Article/details/gt2ahfaflee.html

a?.b?.c
来源：http://dali.jiagoushi.top/Article/details/gt2mmhsxbjw.html

[U86] JS：空值合并
来源：http://dali.andypj.xyz/Article/details/gt2mzwsbfmi.html

a ?? b
来源：http://dali.hnxiangtu.top/Article/details/gt2tpwqhfnm.html

[U87] JS：解构默认值
来源：http://dali.cucudq.cn/Article/details/gt2obnscunf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj202588.top/Article/details/gt2tsiyozac.html

[U88] JS：对象展开合并
来源：http://dali.gaohongyu789.top/Article/details/gt2vjwfazzs.html

{ ...a, ...b }
来源：http://dali.yanxiufei.cn/Article/details/gt2iraqsswh.html

[U89] JS：数组去重
来源：http://dali.aizwys.cn/Article/details/gt2hyaaoevi.html

[...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpudlfup.html

[U90] JS：数字数组排序
来源：http://dali.fengsongda.top/Article/details/gt2utgoloaa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gt2mthwdlch.html

[U91] JS：对象键值遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2wsndqvxn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.vqdsnc.cn/Article/details/gt2szizsmna.html

[U92] JS：深拷贝
来源：http://dali.ybcxt.top/Article/details/gt2pdktukxi.html

structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlbgfbbd.html

[U93] JS：模板字符串
来源：http://dali.jiagoushi.top/Article/details/gt2tgiftnqw.html

`共 ${n} 条`
来源：http://dali.zhongyouzk.top/Article/details/gt2qcrpfrgl.html

[U94] JS：箭头函数
来源：http://dali.guannengcc.top/Article/details/gt2jmsbjero.html

const double = x => x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhaapcsv.html

[U95] JS：Promise 包装
来源：http://dali.yongpay.top/Article/details/gt2tiythygr.html

new Promise((resolve, reject) => {})
来源：http://dali.guannengcc.top/Article/details/gt2gftbxoew.html

[U96] JS：async/await 与异常
来源：http://dali.dianchejie.cn/Article/details/gt2cvjeixqz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ypzpjqde.html

[U97] JS：并发请求
来源：http://dali.shuidangran.top/Article/details/gt2cljdynxv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2vjzxhppq.html

[U98] JS：fetch 带 JSON
来源：http://dali.guowangkeji.top/Article/details/gt2fddlxtdp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hfpthk.cn/Article/details/gt2zzeurtze.html

[U99] JS：事件监听
来源：http://dali.vqdsnc.cn/Article/details/gt2mcgkbbia.html

el.addEventListener("click", e => {})
来源：http://dali.9152youxi.cn/Article/details/gt2rchitqdk.html

[U100] JS：DOM 查询
来源：http://dali.cdnleiting.top/Article/details/gt2iqerfnel.html

document.querySelector(".item")
来源：http://dali.daria6918.cn/Article/details/gt2bgnswtel.html

[U101] JS：classList 操作
来源：http://dali.aizwys.cn/Article/details/gt2zvgkrheb.html

el.classList.toggle("active")
来源：http://dali.wangdashe.top/Article/details/gt2dfmeukgk.html

[U102] JS：本地存储
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzhzawui.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.iojbl.cn/Article/details/gt2jcpjtlba.html

[U103] JS：定时器
来源：http://dali.sufxvd.cn/Article/details/gt2wolrqppo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aibaodan.cn/Article/details/gt2opeslgat.html

[U104] JS：防抖
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpbsjddn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2uxharurd.html

[U105] JS：节流
来源：http://dali.meibo888.top/Article/details/gt2fcuelxmb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tian-w.cn/Article/details/gt2wvkcltct.html

[U106] JS：日期格式化
来源：http://dali.ppjwa.cn/Article/details/gt2daggywem.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hysaishi.cn/Article/details/gt2jptziuev.html

[U107] JS：数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gt2cstmuvdw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gt2xguzejmj.html

[U108] JS：随机整数
来源：http://dali.tanke756.top/Article/details/gt2rcmdbklv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gt2ilxlvwyn.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjyrsrro.html

Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gt2enqshdju.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbhnzpwb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sxryk.cn/Article/details/gt2livwaugx.html

[U111] JS：对象转 Map
来源：http://dali.yj20258888.top/Article/details/gt2nwygtrdr.html

new Map(Object.entries(obj))
来源：http://dali.guannengcc.top/Article/details/gt2eoigcyuf.html

[U112] JS：字符串补位
来源：http://dali.xuetiantiany.cn/Article/details/gt2tothwqix.html

"7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2wezgimso.html

[U113] JS：正则替换全部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qijanwzo.html

s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2obtmvhdz.html

[U114] JS：JSON 深比较
来源：http://dali.smart0.xyz/Article/details/gt2yiudxsmo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gt2ddcojhjn.html

[U115] JS：生成 UUID
来源：http://dali.ybcxt.top/Article/details/gt2czjbvgwh.html

crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2zmccgyvd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.smart0.xyz/Article/details/gt2qdlrbxxo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.andypj.xyz/Article/details/gt2wqiuzxdx.html

[U117] JS：单元测试
来源：http://dali.jinqigufen.top/Article/details/gt2ftrdytyc.html

npm i -D vitest;  npx vitest
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bopwykqj.html

[U118] JS：开发服务器
来源：http://dali.gogol.net.cn/Article/details/gt2nalkskkb.html

npm i -D vite;  npx vite
来源：http://dali.gzhubu.top/Article/details/gt2azhxennz.html

[U119] JS：生产构建
来源：http://dali.pycfn.com/Article/details/gt2uoneeynh.html

npx vite build
来源：http://dali.zhoulong.xyz/Article/details/gt2ptwdnpbx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.havefunace.top/Article/details/gt2gckhdnsy.html

import.meta.env.VITE_API_URL
来源：http://dali.yangfankeji.com/Article/details/gt2wsibfnze.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ryuvdrxu.html

统计汇总
来源：http://dali.xylfe.cn/Article/details/gt2rkusjgup.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2uehrgcxl.html

按语言统计（条）：
来源：http://dali.daxiang520.top/Article/details/gt2ysxevoeb.html

Python ......... 252
来源：http://dali.nanxuanxn.top/Article/details/gt2uxvseoku.html

PHP ............ 252
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bshmaggk.html

JavaScript ..... 252
来源：http://dali.andypj.xyz/Article/details/gt2jvnhuqow.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvapumvg.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gt2ifiycgav.html

Go ............. 212
来源：http://dali.sxryk.cn/Article/details/gt2ljtusgkz.html

Ruby ........... 212
来源：http://dali.nanxinkj.top/Article/details/gt2ozbddhhh.html

C# ............. 212
来源：http://dali.fengsongda.top/Article/details/gt2sqrivchb.html

C .............. 30
来源：http://dali.fzhhl.top/Article/details/gt2rkmkzfpz.html

C++ ............ 30
来源：http://dali.hywenlv.cn/Article/details/gt2xdiatnek.html

SQL ............ 90
来源：http://dali.xylfe.cn/Article/details/gt2jyqbydej.html

Bash ........... 80
来源：http://dali.shzxlz.cn/Article/details/gt2nsishbtw.html

Kotlin ......... 15
来源：http://dali.yonumen.top/Article/details/gt2dskguahx.html

Swift .......... 15
来源：http://dali.wangdashe.top/Article/details/gt2yfoftktn.html

Lua ............ 10
来源：http://dali.meibo888.top/Article/details/gt2uyitvmxq.html

Perl ........... 10
来源：http://dali.daxiang520.top/Article/details/gt2tiivdwje.html

Scala .......... 10
来源：http://dali.sxryk.cn/Article/details/gt2bqlztcbg.html

------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gt2zsmdnzsp.html

合计 ........... 2106 条
来源：http://dali.jlsjyb.cn/Article/details/gt2lcoyxjxn.html

按章节统计：
来源：http://dali.aibaodan.cn/Article/details/gt2rzsedrxm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gt2pqwizowg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gt2uqfzokgm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gt2pvyjgomc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gt2ptapbcol.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258.top/Article/details/gt2ypvonimc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gt2hrfvnukm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwvczesd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tanke756.top/Article/details/gt2duxdwdmg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gt2jptwfsle.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvtldzfw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gt2ioicpqgx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gt2fntlbgvv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gt2jvgvgqws.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gt2tybgaewk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangdashe.top/Article/details/gt2krghjsad.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gt2tscqhslo.html

Q SQL 专题                              90
来源：http://dali.xziqi.cn/Article/details/gt2dodetadz.html

R Bash 专题                             80
来源：http://dali.tianlin.xyz/Article/details/gt2lgxxljmd.html

S C / C++ 专题                          60
来源：http://dali.hysaishi.cn/Article/details/gt2neetmuxs.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrilkcqt.html

U 高频实用片段                         120
来源：http://dali.smart0.xyz/Article/details/gt2iqkzobuy.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2ybfrfiel.html

合计                                  2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gt2amcvsven.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gt2nacpcqwe.html

使用提醒
来源：http://dali.havefunace.top/Article/details/gt2cajauldx.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcimrwdm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jlsjyb.cn/Article/details/gt2fagppvof.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hfpthk.cn/Article/details/gt2cacyrbjc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmfzjhxo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinqigufen.top/Article/details/gt2fisqepvd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenzaomai.com/Article/details/gt2cjwiexcj.html

—— 文件结束 ——
来源：http://dali.yonumen.top/Article/details/gt2ghvzopme.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2xlotuppl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xinyue.icu/Article/details/gt2cooensli.html

Common Programming Examples Cheat Book
来源：http://dali.meibo888.top/Article/details/gt2hpvczuyl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2dmhuixhg.html

【收录内容】
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgioikss.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.meibo888.top/Article/details/gt2zhjauwxq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhoulong.xyz/Article/details/gt2ktexefcr.html

SQL · Bash · C · C++
来源：http://dali.sweek.top/Article/details/gt2hbrhqjuo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.9152youxi.cn/Article/details/gt2nbicpoly.html

【使用说明】
来源：http://dali.yj20258888.top/Article/details/gt2znsvjirm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.fengsongda.top/Article/details/gt2jahqjpry.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgiicpdw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aizwys.cn/Article/details/gt2oieydyin.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinqigufen.top/Article/details/gt2ewgutblg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tian-w.cn/Article/details/gt2dzctraed.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.iojbl.cn/Article/details/gt2cnlfcnki.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpjkxgsl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.wangdashe.top/Article/details/gt2wbtuvqfh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.aibaodan.cn/Article/details/gt2bnoapfiw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gzhubu.top/Article/details/gt2prrshcte.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.havefunace.top/Article/details/gt2gursxccs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hfpthk.cn/Article/details/gt2rjfobpvd.html

【文件统计】
来源：http://dali.guannengcc.top/Article/details/gt2vcydlmct.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yj20258.top/Article/details/gt2cpsgbnlf.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gt2kcsobsmi.html

目  录
来源：http://dali.ybcxt.top/Article/details/gt2ghxaiiww.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gt2oajgqkye.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hysaishi.cn/Article/details/gt2bsogucwz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xofapljr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gt2umcsdbwc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkevwnef.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gotoacloud.top/Article/details/gt2vrellpbe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sufxvd.cn/Article/details/gt2vzeaequa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gt2hnryqvqn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.redwolf501.top/Article/details/gt2ccwzajae.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gt2katgfvhp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hfpthk.cn/Article/details/gt2kluvdzom.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2ulwroxxo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2cakeofha.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2iclpgbjf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gt2iwcxrkli.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.andypj.xyz/Article/details/gt2ehzefqff.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gt2fmppvzpm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ehwqpu.com/Article/details/gt2rjlmpzeo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yueranfly.top/Article/details/gt2ezvfjvkw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.andypj.xyz/Article/details/gt2qzwnkynb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gt2clluhgag.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gt2scrvghmq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2fceoczkl.html

A. 基础语法与类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uujbmchs.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2lldytgea.html

[A01] Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2oztkbhso.html

Py:   print("Hello, World!")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anlvkeqq.html

PHP:  echo "Hello, World!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkmtxccl.html

JS:   console.log("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okikiwoz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sxryk.cn/Article/details/gt2aarkofzd.html

Java: System.out.println("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gt2iucpilvn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gt2mvhlzgmm.html

Ruby: puts "Hello, World!"
来源：http://dali.hysaishi.cn/Article/details/gt2mbwebhec.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cdnleiting.top/Article/details/gt2ytymdohy.html

[A02] 变量声明与赋值
来源：http://dali.hysaishi.cn/Article/details/gt2usxejawp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.c1oappe.top/Article/details/gt2apouxhrk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.birdmap.top/Article/details/gt2mrbxxtlc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cashguo.top/Article/details/gt2eyevvxqc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.daxiang520.top/Article/details/gt2jzeghcey.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqzysjjs.html

Go:   name := "Alex"; age := 20
来源：http://dali.bjfxy.top/Article/details/gt2ptkoznds.html

Ruby: name = "Alex"; age = 20
来源：http://dali.vqdsnc.cn/Article/details/gt2lrrfmrqa.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwfletax.html

[A03] 常量定义
来源：http://dali.zdqjudy.top/Article/details/gt2worzxiin.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daxiang520.top/Article/details/gt2pkzjvnaz.html

PHP:  const PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2vnbvhsvb.html

JS:   const PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2szsealte.html

TS:   const PI: number = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2fqbmjofb.html

Java: static final double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2mhiaoxon.html

Go:   const PI = 3.14159
来源：http://dali.tian-w.cn/Article/details/gt2cybnyxum.html

Ruby: PI = 3.14159
来源：http://dali.jianghu66.top/Article/details/gt2sptykzgm.html

C#:   const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2ycxsrgvu.html

[A04] 判断变量类型
来源：http://dali.gzhubu.top/Article/details/gt2fuahtusa.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hammf.cn/Article/details/gt2klpcfrjd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigfzy.top/Article/details/gt2cznpvbik.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gt2ffhqougo.html

TS:   typeof x; x instanceof Date
来源：http://dali.xziqi.cn/Article/details/gt2vmkaqjru.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hnxiangtu.top/Article/details/gt2rwmoqony.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zgygxcan.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhixingplan.top/Article/details/gt2hypxsmcm.html

C#:   x.GetType().Name; x is int
来源：http://dali.fengsongda.top/Article/details/gt2mheykwva.html

[A05] 整数除法与取模
来源：http://dali.tanke756.top/Article/details/gt2oyzwjqor.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.meibo888.top/Article/details/gt2tdbcwzmx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejbzpujk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.316326.xyz/Article/details/gt2dcwhfomf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2otmnzuzs.html

Java: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrpivoet.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gt2tnodzazc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gt2luobpahq.html

C#:   7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2htktuakp.html

[A06] 字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gt2kbwydjhk.html

Py:   int("42"); float("3.14")
来源：http://dali.316326.xyz/Article/details/gt2hgiuqmab.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ffnttjnk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gt2xacawasj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnqzz.top/Article/details/gt2bguxawne.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jqgfzy.top/Article/details/gt2cnhmtmsy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yangfankeji.com/Article/details/gt2odmefpoy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hnxiangtu.top/Article/details/gt2zrjplkak.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlebfses.html

[A07] 数字转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2ahdgjmpt.html

Py:   str(42)
来源：http://dali.pycfn.com/Article/details/gt2murwalea.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onpysssb.html

JS:   String(42); (42).toString()
来源：http://dali.yonumen.top/Article/details/gt2cqpijigy.html

TS:   String(42)
来源：http://dali.9152youxi.cn/Article/details/gt2ljppgacl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gogol.net.cn/Article/details/gt2dcxtxfff.html

Go:   strconv.Itoa(42)
来源：http://dali.yangfankeji.com/Article/details/gt2ucedqobp.html

Ruby: 42.to_s
来源：http://dali.9152youxi.cn/Article/details/gt2uijevkxm.html

C#:   42.ToString()
来源：http://dali.jyoumei.cn/Article/details/gt2ejqclbhh.html

[A08] 取整与四舍五入
来源：http://dali.sweek.top/Article/details/gt2fnjrrzrm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctnyatvv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.fzhhl.top/Article/details/gt2bniorntz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gt2wtcnyeyc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hywenlv.cn/Article/details/gt2nuyqhdhz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gt2bqngvxmj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gt2hngvahxu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.316326.xyz/Article/details/gt2ouagwhew.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gt2nqrahoiy.html

[A09] 绝对值与最大最小值
来源：http://dali.sysykeji.top/Article/details/gt2czimklcn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shuidangran.top/Article/details/gt2lbdaistd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2kbhvskix.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2mieolpbg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2ubmbjwlt.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2vxdxrtbu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oluiuxgf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnqzz.top/Article/details/gt2nahazprb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.c1oappe.top/Article/details/gt2apgyoajz.html


<!-- 参考信息 -->