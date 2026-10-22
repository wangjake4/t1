代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.ybcxt.top/Article/details/gt2mpubiqin.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ispwzpux.html

[U68] PHP：PDO 连接
来源：http://dali.cashguo.top/Article/details/gt2ewsnmdho.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqvngsal.html

[U69] PHP：PDO 预处理
来源：http://dali.hnxiangtu.top/Article/details/gt2phqpxvgm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj202588.top/Article/details/gt2sgptkhxs.html

[U70] PHP：PDO 事务
来源：http://dali.dianchejie.cn/Article/details/gt2fntxulqn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sysykeji.top/Article/details/gt2rqqjhoca.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnacpgsg.html

throw new RuntimeException("失败", 500);
来源：http://dali.yonumen.top/Article/details/gt2bycghvuo.html

[U72] PHP：写错误日志
来源：http://dali.tianlin.xyz/Article/details/gt2nalwtnda.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jiagoushi.top/Article/details/gt2imstpegs.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvtopqu.html

parse_ini_file("config.ini", true)
来源：http://dali.havefunace.top/Article/details/gt2yjegqzbp.html

[U74] PHP：读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gt2dyiimrns.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sufxvd.cn/Article/details/gt2saxbtdax.html

[U75] PHP：依赖注入
来源：http://dali.c1oappe.top/Article/details/gt2gknofjcu.html

composer require psr/container
来源：http://dali.dashuyun.cn/Article/details/gt2anqlysdi.html

[U76] PHP：简单路由
来源：http://dali.yj20258888.top/Article/details/gt2oantjcso.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fengsongda.top/Article/details/gt2kblvoock.html

[U77] PHP：模板渲染
来源：http://dali.aizwys.cn/Article/details/gt2gfmuuykx.html

composer require twig/twig
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwobgcup.html

[U78] PHP：单元测试
来源：http://dali.svipenyu.cn/Article/details/gt2ubstorht.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgufenzy.top/Article/details/gt2ehispluk.html

[U79] PHP：静态分析
来源：http://dali.316326.xyz/Article/details/gt2aqmnflai.html

composer require --dev phpstan/phpstan
来源：http://dali.ivvv.top/Article/details/gt2fcrasqek.html

[U80] PHP：代码规范修复
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igosvkwd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cheryme.top/Article/details/gt2isxxeuym.html

[U81] JS：初始化项目
来源：http://dali.havefunace.top/Article/details/gt2bftpqgdg.html

npm init -y;  npm i express
来源：http://dali.dianchejie.cn/Article/details/gt2kdyukljs.html

[U82] JS：package.json 脚本
来源：http://dali.mhx1999.top/Article/details/gt2dchpsnjb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrswaas.html

[U83] JS：ES Module 导入导出
来源：http://dali.havefunace.top/Article/details/gt2tonzfayt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gt2teapzlfn.html

[U84] JS：CommonJS 写法
来源：http://dali.gotoacloud.top/Article/details/gt2mnajgxsr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.smart0.xyz/Article/details/gt2yahwdxti.html

[U85] JS：可选链
来源：http://dali.jqgufenzy.top/Article/details/gt2ztdszhrs.html

a?.b?.c
来源：http://dali.c1oappe.top/Article/details/gt2jzsztkyk.html

[U86] JS：空值合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipqjcytm.html

a ?? b
来源：http://dali.hnxiangtu.top/Article/details/gt2rbpvzjhe.html

[U87] JS：解构默认值
来源：http://dali.snrcjt.cn/Article/details/gt2llrnubrg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.smart0.xyz/Article/details/gt2nsafxnnj.html

[U88] JS：对象展开合并
来源：http://dali.hnqzz.top/Article/details/gt2pcmuoivi.html

{ ...a, ...b }
来源：http://dali.jyoumei.cn/Article/details/gt2zwurbund.html

[U89] JS：数组去重
来源：http://dali.wangdashe.top/Article/details/gt2zdnqyyyk.html

[...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2lmmdfprt.html

[U90] JS：数字数组排序
来源：http://dali.cashguo.top/Article/details/gt2egctitef.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gt2ejqusxng.html

[U91] JS：对象键值遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2idjxfozd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hfpthk.cn/Article/details/gt2duxmllbh.html

[U92] JS：深拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2awtfzzqw.html

structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2jzmistmz.html

[U93] JS：模板字符串
来源：http://dali.zdqjudy.top/Article/details/gt2zokhoikz.html

`共 ${n} 条`
来源：http://dali.hysaishi.cn/Article/details/gt2lymzqjmj.html

[U94] JS：箭头函数
来源：http://dali.sweek.top/Article/details/gt2aoranwmt.html

const double = x => x * 2;
来源：http://dali.havefunace.top/Article/details/gt2jadwmijx.html

[U95] JS：Promise 包装
来源：http://dali.cdnleiting.top/Article/details/gt2piyakgdo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhoulong.xyz/Article/details/gt2syhyugkj.html

[U96] JS：async/await 与异常
来源：http://dali.hnxiangtu.top/Article/details/gt2lyyrcmry.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrlingsr.html

[U97] JS：并发请求
来源：http://dali.zhoulong.xyz/Article/details/gt2otdjzijk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gt2fgtxvxew.html

[U98] JS：fetch 带 JSON
来源：http://dali.xziqi.cn/Article/details/gt2zqgzjhcg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gudoygtp.html

[U99] JS：事件监听
来源：http://dali.fzhhl.top/Article/details/gt2hnqdlpiu.html

el.addEventListener("click", e => {})
来源：http://dali.fengsongda.top/Article/details/gt2iefddbru.html

[U100] JS：DOM 查询
来源：http://dali.iojbl.cn/Article/details/gt2lzommycf.html

document.querySelector(".item")
来源：http://dali.cqqwz.cn/Article/details/gt2yirkrtzc.html

[U101] JS：classList 操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xusjopfi.html

el.classList.toggle("active")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnyiffcr.html

[U102] JS：本地存储
来源：http://dali.zhongyouzk.top/Article/details/gt2gnfxuwbr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yanxiufei.cn/Article/details/gt2xynvofqo.html

[U103] JS：定时器
来源：http://dali.tanke756.top/Article/details/gt2sdsbsdwx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uayxthva.html

[U104] JS：防抖
来源：http://dali.yj202588.top/Article/details/gt2gyrtxisc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2fwtzfcfk.html

[U105] JS：节流
来源：http://dali.zhongyouzk.top/Article/details/gt2wrcraaib.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ppjwa.cn/Article/details/gt2lvnrqaxj.html

[U106] JS：日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2mvuqffqo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dashuyun.cn/Article/details/gt2yfgdpyox.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cfilicjb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gt2trysnbis.html

[U108] JS：随机整数
来源：http://dali.iojbl.cn/Article/details/gt2vjarkeog.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxinkj.top/Article/details/gt2xufrnccn.html

[U109] JS：数组分组
来源：http://dali.jinqigfzy.top/Article/details/gt2grkhdttx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gt2gbtkbmsx.html

[U110] JS：数组分块
来源：http://dali.cqqwz.cn/Article/details/gt2uwotoume.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj202588.top/Article/details/gt2hxtduqly.html

[U111] JS：对象转 Map
来源：http://dali.quarkkingdee.top/Article/details/gt2avtqmnyi.html

new Map(Object.entries(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovejxukl.html

[U112] JS：字符串补位
来源：http://dali.dianchejie.cn/Article/details/gt2jkhnzjmz.html

"7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2lnzpjpsr.html

[U113] JS：正则替换全部
来源：http://dali.birdmap.top/Article/details/gt2hhlcdugl.html

s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ieyiemga.html

[U114] JS：JSON 深比较
来源：http://dali.iojbl.cn/Article/details/gt2dzwlpcvf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gt2lsmuceya.html

[U115] JS：生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcndrfev.html

crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2lomaxbsu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jlsjyb.cn/Article/details/gt2dqicivub.html

/** @param {string} name */ function f(name) {}
来源：http://dali.bjfxy.top/Article/details/gt2khckdmdm.html

[U117] JS：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knkuppvo.html

npm i -D vitest;  npx vitest
来源：http://dali.hywenlv.cn/Article/details/gt2sayctxhw.html

[U118] JS：开发服务器
来源：http://dali.pycfn.com/Article/details/gt2qexuidtc.html

npm i -D vite;  npx vite
来源：http://dali.nanxuanxn.top/Article/details/gt2aiqblfii.html

[U119] JS：生产构建
来源：http://dali.0kj1m.cn/Article/details/gt2bgunjbco.html

npx vite build
来源：http://dali.jqgfzy.top/Article/details/gt2lraojiic.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nwbrower.top/Article/details/gt2yqlidjtb.html

import.meta.env.VITE_API_URL
来源：http://dali.0kj1m.cn/Article/details/gt2bavorxku.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2edefxbnu.html

统计汇总
来源：http://dali.chenzaomai.com/Article/details/gt2iwoypdlv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcthumkw.html

按语言统计（条）：
来源：http://dali.nwbrower.top/Article/details/gt2vnwqwvgn.html

Python ......... 252
来源：http://dali.zycfv.cn/Article/details/gt2zimddaar.html

PHP ............ 252
来源：http://dali.andypj.xyz/Article/details/gt2ccegpats.html

JavaScript ..... 252
来源：http://dali.gzhubu.top/Article/details/gt2jbtppwba.html

TypeScript ..... 212
来源：http://dali.guannengcc.top/Article/details/gt2akgkesnb.html

Java ........... 212
来源：http://dali.jqgufenzy.top/Article/details/gt2rogrtwug.html

Go ............. 212
来源：http://dali.guannengcc.top/Article/details/gt2sumhdabo.html

Ruby ........... 212
来源：http://dali.nwbrower.top/Article/details/gt2ochihtjh.html

C# ............. 212
来源：http://dali.haohaochexian.top/Article/details/gt2mkdbozbi.html

C .............. 30
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqzvigrg.html

C++ ............ 30
来源：http://dali.jianghu66.top/Article/details/gt2vntaziss.html

SQL ............ 90
来源：http://dali.cqqwz.cn/Article/details/gt2dfozvlsv.html

Bash ........... 80
来源：http://dali.fengsongda.top/Article/details/gt2girpwphu.html

Kotlin ......... 15
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwngmnbk.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gt2zkdfccyn.html

Lua ............ 10
来源：http://dali.dianchejie.cn/Article/details/gt2ufdaflwa.html

Perl ........... 10
来源：http://dali.cashguo.top/Article/details/gt2njaxpnwy.html

Scala .......... 10
来源：http://dali.yj202588.top/Article/details/gt2slyhekdn.html

------------------------------------
来源：http://dali.shuidangran.top/Article/details/gt2srrhjrhf.html

合计 ........... 2106 条
来源：http://dali.shzxlz.cn/Article/details/gt2dvhfqrfp.html

按章节统计：
来源：http://dali.iojbl.cn/Article/details/gt2tslmdkfn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gt2gjmgrypn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gt2exvnjrin.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gt2hdzsgyfv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gt2bzlurths.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.quarkkingdee.top/Article/details/gt2zglyreci.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2apguxnyz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gt2gjgcqfqp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gt2lobwhlfa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gt2shrifgyl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gt2yrymamth.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gt2rpctsdmt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2svdactyo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gt2zbfxkujy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.pengpengdd.cyou/Article/details/gt2syhyvpza.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gzhubu.top/Article/details/gt2hhdaiwus.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gt2qpyavgyn.html

Q SQL 专题                              90
来源：http://dali.jlsjyb.cn/Article/details/gt2skmzsvzw.html

R Bash 专题                             80
来源：http://dali.zhixingplan.top/Article/details/gt2wfaugkrm.html

S C / C++ 专题                          60
来源：http://dali.jianghu66.top/Article/details/gt2symmqonf.html

T 其他语言补充                          60
来源：http://dali.hysaishi.cn/Article/details/gt2spqtsxja.html

U 高频实用片段                         120
来源：http://dali.ydzc1.top/Article/details/gt2javiyoyi.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2djrgfjtb.html

合计                                  2106 条
来源：http://dali.nwbrower.top/Article/details/gt2uyqvwyzi.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2yplnwpyp.html

使用提醒
来源：http://dali.yuxming.cn/Article/details/gt2dqupieml.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2pagljcol.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnqzz.top/Article/details/gt2xyzdiwrp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nanxinkj.top/Article/details/gt2abiabwvb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhoulong.xyz/Article/details/gt2iyfevbjp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.mhx1999.top/Article/details/gt2bfwggyex.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yanxiufei.cn/Article/details/gt2hvtdzecv.html

—— 文件结束 ——
来源：http://dali.meibo888.top/Article/details/gt2vnpltvxx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ignzuyuf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.guannengcc.top/Article/details/gt2wqxforsn.html

Common Programming Examples Cheat Book
来源：http://dali.xziqi.cn/Article/details/gt2jbzxtbaw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2jvjhbvye.html

【收录内容】
来源：http://dali.cheryme.top/Article/details/gt2cpqmxnzd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jiagoushi.top/Article/details/gt2hnshhpzd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hongshengwenyu.top/Article/details/gt2wffhmklz.html

SQL · Bash · C · C++
来源：http://dali.jiagoushi.top/Article/details/gt2rtvnzrdn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gaohongyu789.top/Article/details/gt2tuhapqen.html

【使用说明】
来源：http://dali.daxiang520.top/Article/details/gt2hjvgyxpb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.snrcjt.cn/Article/details/gt2zbzjtkyv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tian-w.cn/Article/details/gt2kbdwucil.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgufenzy.top/Article/details/gt2feztysai.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sysykeji.top/Article/details/gt2fdgmzsto.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yvedp.cn/Article/details/gt2asmwlrhs.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xziqi.cn/Article/details/gt2tarsdmjq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbizuasc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xziqi.cn/Article/details/gt2tzplspbs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinqigufen.top/Article/details/gt2sfcykned.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.fengsongda.top/Article/details/gt2rzjkzzxk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yangfankeji.com/Article/details/gt2okfispdz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj20258.top/Article/details/gt2fxyfdseh.html

【文件统计】
来源：http://dali.iojbl.cn/Article/details/gt2keztxhpw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yongpay.top/Article/details/gt2xgykwbrk.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gt2rxuomgzd.html

目  录
来源：http://dali.ehwqpu.com/Article/details/gt2mwjphxsq.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2sjijowqn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2tukxjelu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gt2mjdlvgjj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gt2ousmeccg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujpytckq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gzhubu.top/Article/details/gt2ivgoiqrp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hywenlv.cn/Article/details/gt2nzbskzhv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinqigufen.top/Article/details/gt2xnjulvxu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jyoumei.cn/Article/details/gt2wtalfqjq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpecpxgq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.bjfxy.top/Article/details/gt2rphtkxrw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gt2uvdrttqa.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gt2acujjrjr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gt2lraonjmv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.havefunace.top/Article/details/gt2nbgbatyr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tian-w.cn/Article/details/gt2qaesrmmk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gt2wqoryolw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gogol.net.cn/Article/details/gt2jxeklpas.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2baasholw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shzxlz.cn/Article/details/gt2bwjbabdg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gt2sbilbuyg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gt2wathhepc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2zlblrdhr.html

A. 基础语法与类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2kfaqjrtf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2rrclnywf.html

[A01] Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2goboyvry.html

Py:   print("Hello, World!")
来源：http://dali.gogol.net.cn/Article/details/gt2yiyjxsof.html

PHP:  echo "Hello, World!";
来源：http://dali.iojbl.cn/Article/details/gt2wdlyegfe.html

JS:   console.log("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gt2paocdizf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhixingplan.top/Article/details/gt2ztfospez.html

Java: System.out.println("Hello, World!");
来源：http://dali.yuxming.cn/Article/details/gt2dkqodune.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yongpay.top/Article/details/gt2zqevluwv.html

Ruby: puts "Hello, World!"
来源：http://dali.fzhhl.top/Article/details/gt2sxjwikzo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gt2miatldku.html

[A02] 变量声明与赋值
来源：http://dali.meibo888.top/Article/details/gt2rznutngj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.pycfn.com/Article/details/gt2zgtlpdlz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.andypj.xyz/Article/details/gt2zibfymod.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.smart0.xyz/Article/details/gt2vvlccnsq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hnqzz.top/Article/details/gt2yeatffjz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yongpay.top/Article/details/gt2mwmefkac.html

Go:   name := "Alex"; age := 20
来源：http://dali.sysykeji.top/Article/details/gt2jcyhaqus.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aibaodan.cn/Article/details/gt2uujvmtxh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gt2vkxeqpzc.html

[A03] 常量定义
来源：http://dali.haohaochexian.top/Article/details/gt2uiisklil.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.mhx1999.top/Article/details/gt2mducdwde.html

PHP:  const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2wkdslnlt.html

JS:   const PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2yuhdjunt.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gt2yulnkjuc.html

Java: static final double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2qkjfbfgt.html

Go:   const PI = 3.14159
来源：http://dali.xziqi.cn/Article/details/gt2etfvqcrp.html

Ruby: PI = 3.14159
来源：http://dali.guowangkeji.top/Article/details/gt2ractrzqw.html

C#:   const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2ihxfnvaz.html

[A04] 判断变量类型
来源：http://dali.andypj.xyz/Article/details/gt2zdpycojx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenlongwang.top/Article/details/gt2fyjyuhyy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuanzhike.top/Article/details/gt2woqwnmsl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.haohaochexian.top/Article/details/gt2rvhoghpt.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gt2kwqeeupy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangdashe.top/Article/details/gt2kczzzorr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenlongwang.top/Article/details/gt2mygcjifg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jianghu66.top/Article/details/gt2cbhtruph.html

C#:   x.GetType().Name; x is int
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhmjqdbu.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2crdxjebd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cheryme.top/Article/details/gt2sgfmbvqh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2fytmyyzo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uksxamag.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2trjrpoay.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2fylhpldb.html

Go:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gt2douqyyyy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2wzxcozzt.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gt2biojjvus.html

[A06] 字符串转数字
来源：http://dali.aizwys.cn/Article/details/gt2rmodebvu.html

Py:   int("42"); float("3.14")
来源：http://dali.guowangkeji.top/Article/details/gt2ersxwbvs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cucudq.cn/Article/details/gt2gertjqpt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shuidangran.top/Article/details/gt2uyplrnrd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shzxlz.cn/Article/details/gt2xwyypkzd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jiagoushi.top/Article/details/gt2ekerltlv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.chenzaomai.com/Article/details/gt2irexmkew.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jianghu66.top/Article/details/gt2sydikyre.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xylfe.cn/Article/details/gt2urgwbhot.html

[A07] 数字转字符串
来源：http://dali.chenlongwang.top/Article/details/gt2lhczcoov.html

Py:   str(42)
来源：http://dali.xinyue.icu/Article/details/gt2mmfvslis.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2edsmxnhc.html

JS:   String(42); (42).toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2fuyfrmxf.html

TS:   String(42)
来源：http://dali.kuanghao11.cn/Article/details/gt2rmiacbnc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.fzhhl.top/Article/details/gt2hjoaqufu.html

Go:   strconv.Itoa(42)
来源：http://dali.ivvv.top/Article/details/gt2vuaynibt.html

Ruby: 42.to_s
来源：http://dali.redwolf501.top/Article/details/gt2hxuntgct.html

C#:   42.ToString()
来源：http://dali.yj202588.top/Article/details/gt2acnnqlxn.html

[A08] 取整与四舍五入
来源：http://dali.zhoulong.xyz/Article/details/gt2nembrtgj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gt2rdgksfyw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hywenlv.cn/Article/details/gt2gdmitrkt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gt2aolzoahr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.9152youxi.cn/Article/details/gt2yqjbkrrg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gt2euideasc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gt2vudflvyx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tianlin.xyz/Article/details/gt2vufvolgi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cheryme.top/Article/details/gt2bfcevudl.html

[A09] 绝对值与最大最小值
来源：http://dali.iojbl.cn/Article/details/gt2smctucbz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2knxnmmpp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gt2phknhkms.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2ubiarmqt.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2qyhpwgcz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gt2youhtgzb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.9152youxi.cn/Article/details/gt2luvvcxon.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.tianlin.xyz/Article/details/gt2znrikhom.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2yvhrzxuu.html

[A10] 生成随机数
来源：http://dali.fengsongda.top/Article/details/gt2jtpkvtal.html

Py:   import random; random.randint(1, 100)
来源：http://dali.guannengcc.top/Article/details/gt2jjsbeuxi.html

PHP:  random_int(1, 100);
来源：http://dali.quarkkingdee.top/Article/details/gt2ximfvyar.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dianchejie.cn/Article/details/gt2zemcgbtn.html


<!-- 参考信息 -->