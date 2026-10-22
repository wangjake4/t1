代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.nwbrower.top/Article/details/gt2ldunpesj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hammf.cn/Article/details/gt2rnqyuzfq.html

[U70] PHP：PDO 事务
来源：http://dali.havefunace.top/Article/details/gt2jcexmjmj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.aizwys.cn/Article/details/gt2kcaffymq.html

[U71] PHP：抛出异常
来源：http://dali.snrcjt.cn/Article/details/gt2ffnqtnxz.html

throw new RuntimeException("失败", 500);
来源：http://dali.havefunace.top/Article/details/gt2tufrytcs.html

[U72] PHP：写错误日志
来源：http://dali.sxryk.cn/Article/details/gt2zdgwalzl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zycfv.cn/Article/details/gt2uvxrsxyf.html

[U73] PHP：读取 ini 配置
来源：http://dali.pycfn.com/Article/details/gt2gvfuttqe.html

parse_ini_file("config.ini", true)
来源：http://dali.andypj.xyz/Article/details/gt2zewviskm.html

[U74] PHP：读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2tpzknbda.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jlsjyb.cn/Article/details/gt2gkyxzhbu.html

[U75] PHP：依赖注入
来源：http://dali.nanxuanxn.top/Article/details/gt2rqierakb.html

composer require psr/container
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2caxncfir.html

[U76] PHP：简单路由
来源：http://dali.mhx1999.top/Article/details/gt2htubmujb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.birdmap.top/Article/details/gt2bjdixkvy.html

[U77] PHP：模板渲染
来源：http://dali.yuanzhike.top/Article/details/gt2gfsdfpvk.html

composer require twig/twig
来源：http://dali.pycfn.com/Article/details/gt2ijflmsbr.html

[U78] PHP：单元测试
来源：http://dali.tanke756.top/Article/details/gt2wubqgfcx.html

composer require --dev phpunit/phpunit
来源：http://dali.andypj.xyz/Article/details/gt2jendydxm.html

[U79] PHP：静态分析
来源：http://dali.hammf.cn/Article/details/gt2mlyjqjtb.html

composer require --dev phpstan/phpstan
来源：http://dali.shzxlz.cn/Article/details/gt2ubfjzsky.html

[U80] PHP：代码规范修复
来源：http://dali.gotoacloud.top/Article/details/gt2lhklybpf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gotoacloud.top/Article/details/gt2wjzoyqci.html

[U81] JS：初始化项目
来源：http://dali.pycfn.com/Article/details/gt2psldphfw.html

npm init -y;  npm i express
来源：http://dali.bjfxy.top/Article/details/gt2uesljnwx.html

[U82] JS：package.json 脚本
来源：http://dali.hongshengwenyu.top/Article/details/gt2qaygbpnx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwbfjihf.html

[U83] JS：ES Module 导入导出
来源：http://dali.fzhhl.top/Article/details/gt2hfpxqpzu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gt2hhigslmb.html

[U84] JS：CommonJS 写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tiulcppm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nanxuanxn.top/Article/details/gt2fauuyxym.html

[U85] JS：可选链
来源：http://dali.feifeiyinyue.top/Article/details/gt2nuztcqmx.html

a?.b?.c
来源：http://dali.guowangkeji.top/Article/details/gt2pmkdfeaf.html

[U86] JS：空值合并
来源：http://dali.pycfn.com/Article/details/gt2jbjecqvh.html

a ?? b
来源：http://dali.sxryk.cn/Article/details/gt2dhzupmzx.html

[U87] JS：解构默认值
来源：http://dali.jlsjyb.cn/Article/details/gt2kahoiclg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hysaishi.cn/Article/details/gt2gopetjgh.html

[U88] JS：对象展开合并
来源：http://dali.havefunace.top/Article/details/gt2lxltbhta.html

{ ...a, ...b }
来源：http://dali.yj202588.top/Article/details/gt2mxwkfyej.html

[U89] JS：数组去重
来源：http://dali.c1oappe.top/Article/details/gt2plyfsmwc.html

[...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gt2ssifvpho.html

[U90] JS：数字数组排序
来源：http://dali.svipenyu.cn/Article/details/gt2gelstvxy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2vfphfceb.html

[U91] JS：对象键值遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2izlmhcxz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.birdmap.top/Article/details/gt2zfaorodf.html

[U92] JS：深拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2wezfrwek.html

structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gt2kablvyly.html

[U93] JS：模板字符串
来源：http://dali.zhengqikj.top/Article/details/gt2hknhgytp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qevqbccn.html

[U94] JS：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gt2dgyyauqj.html

const double = x => x * 2;
来源：http://dali.gogol.net.cn/Article/details/gt2ovuvfppd.html

[U95] JS：Promise 包装
来源：http://dali.zycfv.cn/Article/details/gt2czcjwtmk.html

new Promise((resolve, reject) => {})
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcyyswaw.html

[U96] JS：async/await 与异常
来源：http://dali.guowangkeji.top/Article/details/gt2ipywavez.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2krryitdz.html

[U97] JS：并发请求
来源：http://dali.chenzaomai.com/Article/details/gt2ipukkjnc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2cnropdum.html

[U98] JS：fetch 带 JSON
来源：http://dali.gzhubu.top/Article/details/gt2czodfgvc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cucudq.cn/Article/details/gt2gmuqpdwh.html

[U99] JS：事件监听
来源：http://dali.jqgufenzy.top/Article/details/gt2kqvfuzgn.html

el.addEventListener("click", e => {})
来源：http://dali.xuanzx.com/Article/details/gt2qwhyaoxz.html

[U100] JS：DOM 查询
来源：http://dali.9152youxi.cn/Article/details/gt2ouiqevle.html

document.querySelector(".item")
来源：http://dali.gotoacloud.top/Article/details/gt2uujhqzap.html

[U101] JS：classList 操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qssxbrne.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2osokwwhv.html

[U102] JS：本地存储
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwpdtcpq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenjidiqi.icu/Article/details/gt2aigosdat.html

[U103] JS：定时器
来源：http://dali.xinyue.icu/Article/details/gt2etsdvecr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnxiangtu.top/Article/details/gt2wtlydfpt.html

[U104] JS：防抖
来源：http://dali.ydzc1.top/Article/details/gt2uhckijsn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbyrkyrr.html

[U105] JS：节流
来源：http://dali.yueranfly.top/Article/details/gt2vjyldtkp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hywenlv.cn/Article/details/gt2iwmwirgf.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmthdfbt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cheryme.top/Article/details/gt2wtbmytfa.html

[U107] JS：数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynpihpcr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.daria6918.cn/Article/details/gt2vwixsrcp.html

[U108] JS：随机整数
来源：http://dali.dashuyun.cn/Article/details/gt2kvlfbwoa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cqqwz.cn/Article/details/gt2gmyqwrtb.html

[U109] JS：数组分组
来源：http://dali.yj202588.top/Article/details/gt2yuumaihl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gt2llulhhat.html

[U110] JS：数组分块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxqslhmk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnxiangtu.top/Article/details/gt2gggctxpy.html

[U111] JS：对象转 Map
来源：http://dali.ivvv.top/Article/details/gt2ijyqtuax.html

new Map(Object.entries(obj))
来源：http://dali.gzhubu.top/Article/details/gt2tjamsqnf.html

[U112] JS：字符串补位
来源：http://dali.nanxuanxn.top/Article/details/gt2lkbzdvva.html

"7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2fmtusqjj.html

[U113] JS：正则替换全部
来源：http://dali.tianlin.xyz/Article/details/gt2cyjbzxts.html

s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2wkysremh.html

[U114] JS：JSON 深比较
来源：http://dali.hammf.cn/Article/details/gt2lnpaeukp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndmhtmss.html

[U115] JS：生成 UUID
来源：http://dali.cucudq.cn/Article/details/gt2znowxzxq.html

crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gt2buqhnzzh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2penukvks.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cqqwz.cn/Article/details/gt2ippkclwo.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gt2xehnzups.html

npm i -D vitest;  npx vitest
来源：http://dali.zhoulong.xyz/Article/details/gt2ttpviiqc.html

[U118] JS：开发服务器
来源：http://dali.tanke756.top/Article/details/gt2klzgdvfp.html

npm i -D vite;  npx vite
来源：http://dali.hysaishi.cn/Article/details/gt2hsggdful.html

[U119] JS：生产构建
来源：http://dali.hongshengwenyu.top/Article/details/gt2zuhaktkp.html

npx vite build
来源：http://dali.fengsongda.top/Article/details/gt2zdemcbui.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.0kj1m.cn/Article/details/gt2tdwcymnc.html

import.meta.env.VITE_API_URL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdiwpuim.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2tsrymlru.html

统计汇总
来源：http://dali.smart0.xyz/Article/details/gt2vjkncebu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2aonbugns.html

按语言统计（条）：
来源：http://dali.haohaochexian.top/Article/details/gt2feyxhaae.html

Python ......... 252
来源：http://dali.xinyue.icu/Article/details/gt2cqkgwqkk.html

PHP ............ 252
来源：http://dali.cashguo.top/Article/details/gt2clmdjjrl.html

JavaScript ..... 252
来源：http://dali.jqgufenzy.top/Article/details/gt2anqelrxr.html

TypeScript ..... 212
来源：http://dali.aizwys.cn/Article/details/gt2hstslmqf.html

Java ........... 212
来源：http://dali.cashguo.top/Article/details/gt2iswqxkbc.html

Go ............. 212
来源：http://dali.meibo888.top/Article/details/gt2yflxpvpz.html

Ruby ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbobwwai.html

C# ............. 212
来源：http://dali.jqgfzy.top/Article/details/gt2ondsljkx.html

C .............. 30
来源：http://dali.yueranfly.top/Article/details/gt2hskfapda.html

C++ ............ 30
来源：http://dali.yj202588.top/Article/details/gt2lqtelutf.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gt2dovajmme.html

Bash ........... 80
来源：http://dali.gaohongyu789.top/Article/details/gt2dajmgjuo.html

Kotlin ......... 15
来源：http://dali.shzxlz.cn/Article/details/gt2zxrlusna.html

Swift .......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixijgwbf.html

Lua ............ 10
来源：http://dali.tianlin.xyz/Article/details/gt2tsekeigu.html

Perl ........... 10
来源：http://dali.cqqwz.cn/Article/details/gt2cvttwucr.html

Scala .......... 10
来源：http://dali.hfpthk.cn/Article/details/gt2gfdrxeje.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gt2ayljpjoi.html

合计 ........... 2106 条
来源：http://dali.gotoacloud.top/Article/details/gt2iltroess.html

按章节统计：
来源：http://dali.cucudq.cn/Article/details/gt2whkuhnbw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gt2invfueyh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gt2bequqaph.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gt2uzcjnrrt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gt2ftwgznpd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhongyouzk.top/Article/details/gt2wbvfrsqo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgfzy.top/Article/details/gt2mluaodcn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gt2zurjyqkv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gt2yylmtpfw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2rmzjysbg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuanzx.com/Article/details/gt2fbllrenc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2kejyvfqj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gt2ktfquxne.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gt2tfnftoiz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gt2lgkzbbjo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zdqjudy.top/Article/details/gt2zfjjpwms.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gt2gqcumbmb.html

Q SQL 专题                              90
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbslvlxo.html

R Bash 专题                             80
来源：http://dali.kuanghao11.cn/Article/details/gt2ltotnamh.html

S C / C++ 专题                          60
来源：http://dali.gzhubu.top/Article/details/gt2mkweujnh.html

T 其他语言补充                          60
来源：http://dali.yuanzhike.top/Article/details/gt2khdhzsmr.html

U 高频实用片段                         120
来源：http://dali.jiagoushi.top/Article/details/gt2egsnsoll.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2qjkjffvk.html

合计                                  2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gt2udxukzcd.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exqoafpf.html

使用提醒
来源：http://dali.chenjidiqi.icu/Article/details/gt2cifmswrq.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gt2feywjroj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afrzrqzs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.dashuyun.cn/Article/details/gt2othpnmtb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gogol.net.cn/Article/details/gt2uoozjtea.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yueranfly.top/Article/details/gt2mdkenpoa.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yangfankeji.com/Article/details/gt2nfanuexq.html

—— 文件结束 ——
来源：http://dali.wangdashe.top/Article/details/gt2fwernmut.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2mkfewmgp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hysaishi.cn/Article/details/gt2ihsicyhi.html

Common Programming Examples Cheat Book
来源：http://dali.yongpay.top/Article/details/gt2vegsvvxa.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2sbboxfez.html

【收录内容】
来源：http://dali.tian-w.cn/Article/details/gt2hdfheljm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.redwolf501.top/Article/details/gt2ycigphtk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhengqikj.top/Article/details/gt2wjrvdooy.html

SQL · Bash · C · C++
来源：http://dali.jqgfzy.top/Article/details/gt2uynlenwi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gaohongyu789.top/Article/details/gt2bzoutvtn.html

【使用说明】
来源：http://dali.jyoumei.cn/Article/details/gt2qnzhuyal.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.guannengcc.top/Article/details/gt2oyghjipd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sufxvd.cn/Article/details/gt2bjwbntic.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hysaishi.cn/Article/details/gt2ytcyvdne.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ppjwa.cn/Article/details/gt2pckeyksc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jianghu66.top/Article/details/gt2yykhiibw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daxiang520.top/Article/details/gt2fmdinihs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.meibo888.top/Article/details/gt2tqvgqeov.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuanzhike.top/Article/details/gt2nxayybzc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hywenlv.cn/Article/details/gt2txfslkuj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jianghu66.top/Article/details/gt2gbbxbolr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.316326.xyz/Article/details/gt2rvyjuslm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgfzy.top/Article/details/gt2kxoplukp.html

【文件统计】
来源：http://dali.yanxiufei.cn/Article/details/gt2zorppxsa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nanxuanxn.top/Article/details/gt2gtodamia.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2ypujasup.html

目  录
来源：http://dali.jinqigfzy.top/Article/details/gt2whlyzwnq.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gt2acattamn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjgtxaqx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tianlin.xyz/Article/details/gt2pedmghwg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gt2mhdfqsmc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yyhrudhj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.haohaochexian.top/Article/details/gt2xiipxbqn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhixingplan.top/Article/details/gt2fjgrisca.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gt2mllyolud.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgrdlghs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gt2jlfxpymg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2lyoqhjax.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gt2hbktzyaa.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrusuvdd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gt2ublmplyi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2xhyfxnjs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2zdhrjnsd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gt2jykqjcdp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xylfe.cn/Article/details/gt2feaktnli.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinqigufen.top/Article/details/gt2mygwiovo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnqzz.top/Article/details/gt2bjzfxiyt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iygdawus.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yueranfly.top/Article/details/gt2yhxjojsa.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2uwtamybp.html

A. 基础语法与类型
来源：http://dali.svipenyu.cn/Article/details/gt2regdbycb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2oenvvwcu.html

[A01] Hello World
来源：http://dali.zycfv.cn/Article/details/gt2ywropqry.html

Py:   print("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gt2tajkolvr.html

PHP:  echo "Hello, World!";
来源：http://dali.zdqjudy.top/Article/details/gt2faelrgdq.html

JS:   console.log("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gt2khysuytj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shuidangran.top/Article/details/gt2kumfkqfl.html

Java: System.out.println("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gt2mvnknipg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gt2cwuykwfz.html

Ruby: puts "Hello, World!"
来源：http://dali.aizwys.cn/Article/details/gt2iiinhwyz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.9152youxi.cn/Article/details/gt2tknaejpu.html

[A02] 变量声明与赋值
来源：http://dali.9152youxi.cn/Article/details/gt2ilyymcna.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.quarkkingdee.top/Article/details/gt2gwyqkzlm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jyoumei.cn/Article/details/gt2dtamhhuh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrevkaci.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crlrohmz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gt2mozkskbm.html

Go:   name := "Alex"; age := 20
来源：http://dali.sweek.top/Article/details/gt2ceypqhjd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqhoukwh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gt2ktyrgxnn.html

[A03] 常量定义
来源：http://dali.quarkkingdee.top/Article/details/gt2fexqzxka.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cashguo.top/Article/details/gt2dlgeeoqd.html

PHP:  const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2iqibeoww.html

JS:   const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zatxgtdq.html

TS:   const PI: number = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2tzqdecrx.html

Java: static final double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2lnfizjhp.html

Go:   const PI = 3.14159
来源：http://dali.daria6918.cn/Article/details/gt2fdfujogx.html

Ruby: PI = 3.14159
来源：http://dali.ybcxt.top/Article/details/gt2kwdemtyj.html

C#:   const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2pxethdyy.html

[A04] 判断变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmvxhrkh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shzxlz.cn/Article/details/gt2wyzhtcpp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jlsjyb.cn/Article/details/gt2bwayevyb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gt2lidchedn.html

TS:   typeof x; x instanceof Date
来源：http://dali.0kj1m.cn/Article/details/gt2dvkycmen.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.vqdsnc.cn/Article/details/gt2evxchfxs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dashuyun.cn/Article/details/gt2jlrznwgq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yongpay.top/Article/details/gt2txtxcwnf.html

C#:   x.GetType().Name; x is int
来源：http://dali.andypj.xyz/Article/details/gt2phnlxpfz.html

[A05] 整数除法与取模
来源：http://dali.yonumen.top/Article/details/gt2raidrybp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbyoasxp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2kbwrbscf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shuidangran.top/Article/details/gt2ohbdlklw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2vdrojgdj.html

Java: 7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2lpubbbnu.html

Go:   7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gt2cfvvsjis.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxckvilu.html

C#:   7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2vniaublx.html

[A06] 字符串转数字
来源：http://dali.xziqi.cn/Article/details/gt2ywjjnyso.html

Py:   int("42"); float("3.14")
来源：http://dali.cashguo.top/Article/details/gt2blhrehmv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yanxiufei.cn/Article/details/gt2nxrdezwh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gotoacloud.top/Article/details/gt2zzwitkgk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhongyouzk.top/Article/details/gt2shkreacl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.316326.xyz/Article/details/gt2fjchznqv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.fengsongda.top/Article/details/gt2bzppgoiu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nwbrower.top/Article/details/gt2vnfztiqq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gt2rmunzvpb.html

[A07] 数字转字符串
来源：http://dali.xuanzx.com/Article/details/gt2bxpkfnzb.html

Py:   str(42)
来源：http://dali.aibaodan.cn/Article/details/gt2kxblaofc.html

PHP:  (string) 42; strval(42)
来源：http://dali.cdnleiting.top/Article/details/gt2velisizz.html

JS:   String(42); (42).toString()
来源：http://dali.316326.xyz/Article/details/gt2slmiqqoi.html

TS:   String(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmsewifw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.bjfxy.top/Article/details/gt2pmyuozgc.html

Go:   strconv.Itoa(42)
来源：http://dali.9152youxi.cn/Article/details/gt2kmegpsap.html

Ruby: 42.to_s
来源：http://dali.yanxiufei.cn/Article/details/gt2bacrzalz.html

C#:   42.ToString()
来源：http://dali.chenlongwang.top/Article/details/gt2ynhezwcb.html

[A08] 取整与四舍五入
来源：http://dali.hnxiangtu.top/Article/details/gt2ojqoxuth.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gt2pemlands.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2smenlecq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gt2qnlotyfu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjiesxrw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gt2wobqsdzv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gt2zvexeqan.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbhjbhez.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ogbqflgf.html

[A09] 绝对值与最大最小值
来源：http://dali.9152youxi.cn/Article/details/gt2nejgwoiq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpymipnq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gt2ggfkhmxl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxjgczpl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gt2kizeazjg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2xwmieeeg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.nanxinkj.top/Article/details/gt2woafjbpv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sxryk.cn/Article/details/gt2okielldt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sweek.top/Article/details/gt2ynxizbpg.html

[A10] 生成随机数
来源：http://dali.sxryk.cn/Article/details/gt2afvnybjn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hysaishi.cn/Article/details/gt2hwhfvsrf.html

PHP:  random_int(1, 100);
来源：http://dali.316326.xyz/Article/details/gt2qxjgqdff.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangdashe.top/Article/details/gt2vzfjwqhl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxinkj.top/Article/details/gt2pleohsxz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hnxiangtu.top/Article/details/gt2goekjyyw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.birdmap.top/Article/details/gt2couwlmvo.html

Ruby: rand(1..100)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ucrueojd.html


<!-- 参考信息 -->