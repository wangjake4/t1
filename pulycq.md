代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.sweek.top/Article/details/gtyaxnitfd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yueranfly.top/Article/details/gtfvptspes.html

[U70] PHP：PDO 事务
来源：http://dali.tian-w.cn/Article/details/gtyskjjvsk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daxiang520.top/Article/details/gttiszdgjx.html

[U71] PHP：抛出异常
来源：http://dali.sysykeji.top/Article/details/gtryjxczgo.html

throw new RuntimeException("失败", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gttovzlmzq.html

[U72] PHP：写错误日志
来源：http://dali.jyoumei.cn/Article/details/gtqotcqfzm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yangfankeji.com/Article/details/gtgxfnlkfc.html

[U73] PHP：读取 ini 配置
来源：http://dali.meibo888.top/Article/details/gttihmdqjo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhengqikj.top/Article/details/gtsnvbgwhf.html

[U74] PHP：读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtatjmexlx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgfzy.top/Article/details/gthpuqhozb.html

[U75] PHP：依赖注入
来源：http://dali.jinqigfzy.top/Article/details/gtsnifsvpq.html

composer require psr/container
来源：http://dali.iojbl.cn/Article/details/gtycmctpwq.html

[U76] PHP：简单路由
来源：http://dali.sysykeji.top/Article/details/gtcoslhpud.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangshuangyany.cn/Article/details/gtgvxvtdjz.html

[U77] PHP：模板渲染
来源：http://dali.yvedp.cn/Article/details/gtjmirepse.html

composer require twig/twig
来源：http://dali.jlsjyb.cn/Article/details/gtrjywxahw.html

[U78] PHP：单元测试
来源：http://dali.daxiang520.top/Article/details/gtarvkvqpu.html

composer require --dev phpunit/phpunit
来源：http://dali.cheryme.top/Article/details/gtwsjemxfk.html

[U79] PHP：静态分析
来源：http://dali.dianchejie.cn/Article/details/gtwxurfjlq.html

composer require --dev phpstan/phpstan
来源：http://dali.hnqzz.top/Article/details/gtnumvkmwj.html

[U80] PHP：代码规范修复
来源：http://dali.ybcxt.top/Article/details/gtyedhbtpt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.redwolf501.top/Article/details/gtcopgjhqb.html

[U81] JS：初始化项目
来源：http://dali.fzhhl.top/Article/details/gtdkpvintb.html

npm init -y;  npm i express
来源：http://dali.ivvv.top/Article/details/gtmuewyotr.html

[U82] JS：package.json 脚本
来源：http://dali.wangdashe.top/Article/details/gtqcqtgyhq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pycfn.com/Article/details/gtjriaxqyf.html

[U83] JS：ES Module 导入导出
来源：http://dali.sxryk.cn/Article/details/gtnwfknxfd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gtoghmplwo.html

[U84] JS：CommonJS 写法
来源：http://dali.haohaochexian.top/Article/details/gtsvnqszoy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aibaodan.cn/Article/details/gtfdegcnmn.html

[U85] JS：可选链
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmxoztqh.html

a?.b?.c
来源：http://dali.sweek.top/Article/details/gtfiorvxmw.html

[U86] JS：空值合并
来源：http://dali.hfpthk.cn/Article/details/gtsrfmduva.html

a ?? b
来源：http://dali.yueranfly.top/Article/details/gtghcscqgh.html

[U87] JS：解构默认值
来源：http://dali.316326.xyz/Article/details/gtqyrttvev.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tanke756.top/Article/details/gtebqjrakh.html

[U88] JS：对象展开合并
来源：http://dali.daria6918.cn/Article/details/gtumdchvbj.html

{ ...a, ...b }
来源：http://dali.mhx1999.top/Article/details/gtlbsleiww.html

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gtynbhqzje.html

[...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtccaxbalf.html

[U90] JS：数字数组排序
来源：http://dali.haohaochexian.top/Article/details/gtxsgvtfct.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtyyoqkuhn.html

[U91] JS：对象键值遍历
来源：http://dali.ybcxt.top/Article/details/gtgwhtjujg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.meibo888.top/Article/details/gtsaeujovr.html

[U92] JS：深拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtgpqcvvca.html

structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtrnuxppqh.html

[U93] JS：模板字符串
来源：http://dali.guowangkeji.top/Article/details/gtdzzcadep.html

`共 ${n} 条`
来源：http://dali.zhixingplan.top/Article/details/gttohpvjjx.html

[U94] JS：箭头函数
来源：http://dali.shuidangran.top/Article/details/gtqigkrgpu.html

const double = x => x * 2;
来源：http://dali.svipenyu.cn/Article/details/gtfhvbqrkn.html

[U95] JS：Promise 包装
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvaluqgjj.html

new Promise((resolve, reject) => {})
来源：http://dali.yongpay.top/Article/details/gtlawmaeir.html

[U96] JS：async/await 与异常
来源：http://dali.yj20258888.top/Article/details/gtomygileh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtmdoqnbhv.html

[U97] JS：并发请求
来源：http://dali.hfpthk.cn/Article/details/gtgmhixwxm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtacspkmho.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtgcgenmtt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgufenzy.top/Article/details/gtdbsaltae.html

[U99] JS：事件监听
来源：http://dali.hnxiangtu.top/Article/details/gtbbqfrtot.html

el.addEventListener("click", e => {})
来源：http://dali.ivvv.top/Article/details/gthsaidwqf.html

[U100] JS：DOM 查询
来源：http://dali.c1oappe.top/Article/details/gttxbeoazj.html

document.querySelector(".item")
来源：http://dali.sxryk.cn/Article/details/gtcliloaav.html

[U101] JS：classList 操作
来源：http://dali.yueranfly.top/Article/details/gtksudgpjg.html

el.classList.toggle("active")
来源：http://dali.gaohongyu789.top/Article/details/gtsyqklsbe.html

[U102] JS：本地存储
来源：http://dali.0kj1m.cn/Article/details/gtieneqdes.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.haohaochexian.top/Article/details/gtkeiyvatx.html

[U103] JS：定时器
来源：http://dali.316326.xyz/Article/details/gtkqgokfdu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxckxsgur.html

[U104] JS：防抖
来源：http://dali.hnqzz.top/Article/details/gtwjmpnimw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtjzdjvuog.html

[U105] JS：节流
来源：http://dali.cashguo.top/Article/details/gtcknbmuqi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgufenzy.top/Article/details/gtfyrcmwzj.html

[U106] JS：日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtbummudpm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dashuyun.cn/Article/details/gtowofsyck.html

[U107] JS：数字千分位
来源：http://dali.meibo888.top/Article/details/gtxmtiaosw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtlluscecn.html

[U108] JS：随机整数
来源：http://dali.haohaochexian.top/Article/details/gtdwlmdzhw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.feifeiyinyue.top/Article/details/gtyjqecryt.html

[U109] JS：数组分组
来源：http://dali.yj202588.top/Article/details/gtpvpfrdaw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtxjnhgdbh.html

[U110] JS：数组分块
来源：http://dali.jianghu66.top/Article/details/gtctlythyv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiihlagz.html

[U111] JS：对象转 Map
来源：http://dali.smart0.xyz/Article/details/gtfbkovotr.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtbrkilkjk.html

[U112] JS：字符串补位
来源：http://dali.sysykeji.top/Article/details/gtxafesper.html

"7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtffzdabfi.html

[U113] JS：正则替换全部
来源：http://dali.gogol.net.cn/Article/details/gtyywbddxj.html

s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtxxhopukj.html

[U114] JS：JSON 深比较
来源：http://dali.quarkkingdee.top/Article/details/gtdgreekey.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gtufpcxokr.html

[U115] JS：生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gtcooemfga.html

crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtbeensaju.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zdqjudy.top/Article/details/gtclnypoct.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenlongwang.top/Article/details/gtunsbmflp.html

[U117] JS：单元测试
来源：http://dali.shzxlz.cn/Article/details/gtrrzgduwe.html

npm i -D vitest;  npx vitest
来源：http://dali.ydzc1.top/Article/details/gtvgvoqpfz.html

[U118] JS：开发服务器
来源：http://dali.zhoulong.xyz/Article/details/gtukxiwlii.html

npm i -D vite;  npx vite
来源：http://dali.quarkkingdee.top/Article/details/gtiakflskt.html

[U119] JS：生产构建
来源：http://dali.yongpay.top/Article/details/gtbkxjnyna.html

npx vite build
来源：http://dali.iojbl.cn/Article/details/gttjqkpxnu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.redwolf501.top/Article/details/gtsnxmyoku.html

import.meta.env.VITE_API_URL
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhsodahx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrigffuqx.html

统计汇总
来源：http://dali.yangfankeji.com/Article/details/gtxpbyhyst.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjyijhriu.html

按语言统计（条）：
来源：http://dali.hfpthk.cn/Article/details/gtkyxrrzvx.html

Python ......... 252
来源：http://dali.ivvv.top/Article/details/gtbqspdzcb.html

PHP ............ 252
来源：http://dali.iojbl.cn/Article/details/gtjstvgpky.html

JavaScript ..... 252
来源：http://dali.guannengcc.top/Article/details/gtzctgqpmh.html

TypeScript ..... 212
来源：http://dali.zhengqikj.top/Article/details/gtfcaolgrp.html

Java ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxywzljev.html

Go ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gtghbuzavj.html

Ruby ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeyitrou.html

C# ............. 212
来源：http://dali.hammf.cn/Article/details/gtkuhnzbvt.html

C .............. 30
来源：http://dali.shangyingyoupin.top/Article/details/gtacpsgokt.html

C++ ............ 30
来源：http://dali.meibo888.top/Article/details/gtbubvdlut.html

SQL ............ 90
来源：http://dali.hfpthk.cn/Article/details/gtchtvohab.html

Bash ........... 80
来源：http://dali.kuanghao11.cn/Article/details/gtulvlyonx.html

Kotlin ......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtviltuyvb.html

Swift .......... 15
来源：http://dali.tanke756.top/Article/details/gtqwrkfrbl.html

Lua ............ 10
来源：http://dali.gotoacloud.top/Article/details/gtbeomfbvg.html

Perl ........... 10
来源：http://dali.dianchejie.cn/Article/details/gtgcotsnxa.html

Scala .......... 10
来源：http://dali.meibo888.top/Article/details/gtqyujegwk.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtgzmzhlqt.html

合计 ........... 2106 条
来源：http://dali.mhx1999.top/Article/details/gtkgunjcoj.html

按章节统计：
来源：http://dali.quarkkingdee.top/Article/details/gtdvxwjjad.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.dianchejie.cn/Article/details/gtovveizxk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtulzaxtec.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gtnjzvhsue.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtsmdfllsd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinqigfzy.top/Article/details/gtlkrkejvt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sufxvd.cn/Article/details/gtapexqiav.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtbwozgnta.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daxiang520.top/Article/details/gttctogumb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtnnaqeniu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gtbgamulwq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtbawshdzw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtvgadurho.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtaiylaglb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gtjzkkzrhi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sxryk.cn/Article/details/gttmefinrp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomlquivm.html

Q SQL 专题                              90
来源：http://dali.hfpthk.cn/Article/details/gtupsrdnlw.html

R Bash 专题                             80
来源：http://dali.xziqi.cn/Article/details/gtobnlikrx.html

S C / C++ 专题                          60
来源：http://dali.svipenyu.cn/Article/details/gthzbuivap.html

T 其他语言补充                          60
来源：http://dali.xuanzx.com/Article/details/gtqukkdipb.html

U 高频实用片段                         120
来源：http://dali.chenjidiqi.icu/Article/details/gtqjdatnxy.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtsfpaewcw.html

合计                                  2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuusktrrj.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gttebhsoha.html

使用提醒
来源：http://dali.ybcxt.top/Article/details/gtruewifnh.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtbqyqhztl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yvedp.cn/Article/details/gtsxmbuyse.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cheryme.top/Article/details/gtfubaihzz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zdqjudy.top/Article/details/gtadkungfq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkfsoydf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgfzy.top/Article/details/gtvutpqpec.html

—— 文件结束 ——
来源：http://dali.kuanghao11.cn/Article/details/gtfxgssofi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrighebni.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhiwuduotai.top/Article/details/gtxhnhsups.html

Common Programming Examples Cheat Book
来源：http://dali.aizwys.cn/Article/details/gtscnmbuvf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtkyjstxju.html

【收录内容】
来源：http://dali.jqgfzy.top/Article/details/gttxmfilth.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hnxiangtu.top/Article/details/gtjziqcrkk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinyuanbaomall.cn/Article/details/gttslbhrwd.html

SQL · Bash · C · C++
来源：http://dali.jlsjyb.cn/Article/details/gttdkimyhl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shuidangran.top/Article/details/gtanjqcute.html

【使用说明】
来源：http://dali.jyoumei.cn/Article/details/gtrcttbrax.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jyoumei.cn/Article/details/gtdmfdwany.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipithniu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hongshengwenyu.top/Article/details/gtdlyfdooi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yonumen.top/Article/details/gtzayxixmg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenjidiqi.icu/Article/details/gtxondlcyr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nanxinkj.top/Article/details/gtssnxulov.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.redwolf501.top/Article/details/gtnpkzyghm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuxming.cn/Article/details/gtniaaayaw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shzxlz.cn/Article/details/gtstkzlqqq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nanxinkj.top/Article/details/gtnlsuphui.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.vqdsnc.cn/Article/details/gtyyiwzjff.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.wangshuangyany.cn/Article/details/gtplfmxdco.html

【文件统计】
来源：http://dali.cqqwz.cn/Article/details/gtifgihxja.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cucudq.cn/Article/details/gtcnsfwmib.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gttoistbus.html

目  录
来源：http://dali.zhongyouzk.top/Article/details/gtcixnvuod.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtoazgpjcd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtckeavjtd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gtijskpdce.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.redwolf501.top/Article/details/gtakeoorug.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jqgfzy.top/Article/details/gtrwroxvcj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cucudq.cn/Article/details/gtegjumite.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.havefunace.top/Article/details/gtolmgaiqc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gtlmmdfjgl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yuanzhike.top/Article/details/gtcjiaiofo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gthmtgjrfx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.havefunace.top/Article/details/gtvcyzhndq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtaeekmube.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtxqizirhg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtsnpkbqnq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gtvasymlbz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jianghu66.top/Article/details/gtcyqzcqvk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gthpqzwrmm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.bjfxy.top/Article/details/gtpidxyddp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fzhhl.top/Article/details/gtlplmkdog.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.meibo888.top/Article/details/gtjeyrhevd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtuewxqeww.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gtobxecomv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbnpxenel.html

A. 基础语法与类型
来源：http://dali.nanxinkj.top/Article/details/gtxklencqy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlwsbpxmk.html

[A01] Hello World
来源：http://dali.gotoacloud.top/Article/details/gtsvfusdzo.html

Py:   print("Hello, World!")
来源：http://dali.birdmap.top/Article/details/gtmmdnclld.html

PHP:  echo "Hello, World!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotlrluiy.html

JS:   console.log("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtlmeuzbcv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnxiangtu.top/Article/details/gtacwksxjg.html

Java: System.out.println("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gtbnvioadu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gtwauyelcq.html

Ruby: puts "Hello, World!"
来源：http://dali.jinqigufen.top/Article/details/gtyigkfutw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gotoacloud.top/Article/details/gtmkssxpnd.html

[A02] 变量声明与赋值
来源：http://dali.gzhubu.top/Article/details/gtampeslvm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sufxvd.cn/Article/details/gtlsthlxwv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtkwpukpvz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtbsyipzad.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sxryk.cn/Article/details/gtqzlbyypx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtmcrwfode.html

Go:   name := "Alex"; age := 20
来源：http://dali.quarkkingdee.top/Article/details/gtwnkjxhhx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shzxlz.cn/Article/details/gtesyessor.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zycfv.cn/Article/details/gtgqpuatgl.html

[A03] 常量定义
来源：http://dali.redwolf501.top/Article/details/gttvmaforb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sufxvd.cn/Article/details/gtluttqohq.html

PHP:  const PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtcbxlpxyf.html

JS:   const PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtudxvypoi.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtybrvvfxz.html

Java: static final double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtaapsbuwe.html

Go:   const PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtiukcrywr.html

Ruby: PI = 3.14159
来源：http://dali.guannengcc.top/Article/details/gtnzzfjqrg.html

C#:   const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtpqgeftrp.html

[A04] 判断变量类型
来源：http://dali.daria6918.cn/Article/details/gtvhlxmqtg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.quarkkingdee.top/Article/details/gtbwffkkou.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.tian-w.cn/Article/details/gtysyzjyev.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenlongwang.top/Article/details/gtjvdraowj.html

TS:   typeof x; x instanceof Date
来源：http://dali.shuidangran.top/Article/details/gtehwndnln.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xylfe.cn/Article/details/gtvwmsdiey.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnxiangtu.top/Article/details/gtwctqfrud.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xylfe.cn/Article/details/gttszsmwvc.html

C#:   x.GetType().Name; x is int
来源：http://dali.wangdashe.top/Article/details/gtdvrgtwwn.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gtyamccgrf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cucudq.cn/Article/details/gtpymnaovw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtavgcgavm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtwaovdomi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtudekzxab.html

Java: 7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gthxxlrrit.html

Go:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulzzguvq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtmzzirbst.html

C#:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtekphhrrn.html

[A06] 字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtjblxcwaa.html

Py:   int("42"); float("3.14")
来源：http://dali.cheryme.top/Article/details/gtzlcetwzz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yuxming.cn/Article/details/gtwzeznxly.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.pycfn.com/Article/details/gtewlmehxq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nwbrower.top/Article/details/gtxfmdyidf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj20258888.top/Article/details/gtswxizhyo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqywxuzaq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xylfe.cn/Article/details/gtswkbpfow.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgzrshfb.html

[A07] 数字转字符串
来源：http://dali.yangfankeji.com/Article/details/gtmzyjumxg.html

Py:   str(42)
来源：http://dali.cqqwz.cn/Article/details/gtuuacjudy.html

PHP:  (string) 42; strval(42)
来源：http://dali.ybcxt.top/Article/details/gtyszbvvqh.html

JS:   String(42); (42).toString()
来源：http://dali.havefunace.top/Article/details/gtkyzpxalv.html

TS:   String(42)
来源：http://dali.0kj1m.cn/Article/details/gtfyllwxhl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.smart0.xyz/Article/details/gtnzismmls.html

Go:   strconv.Itoa(42)
来源：http://dali.zdqjudy.top/Article/details/gtsnqjuzhc.html

Ruby: 42.to_s
来源：http://dali.yangfankeji.com/Article/details/gtvlfqnkcd.html

C#:   42.ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvduwmlty.html

[A08] 取整与四舍五入
来源：http://dali.xinyue.icu/Article/details/gtdrekgesh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtokqcwohk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yueranfly.top/Article/details/gtmaekjici.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gtsyzznjzb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.pycfn.com/Article/details/gtmhocrvrx.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gtpxuxhowc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gtxkcbtjxk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.sweek.top/Article/details/gtkspitnou.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwxtqvmj.html

[A09] 绝对值与最大最小值
来源：http://dali.gogol.net.cn/Article/details/gtbpvpuqbd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tanke756.top/Article/details/gtpsksocmd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtgpdxtzvp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcaycvdho.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj202588.top/Article/details/gtxjyucoll.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gteutkfsvl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswbpvfrz.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sweek.top/Article/details/gtiqhjcmdr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtkeuoquru.html

[A10] 生成随机数
来源：http://dali.nwbrower.top/Article/details/gtclrasecm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.316326.xyz/Article/details/gtfjwdhdpn.html

PHP:  random_int(1, 100);
来源：http://dali.yj20258888.top/Article/details/gttyzlhnhk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.bjfxy.top/Article/details/gtqldimovo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ivvv.top/Article/details/gtyvscoaaz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cdnleiting.top/Article/details/gtmbovdbvy.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.smart0.xyz/Article/details/gtpywlruvh.html

Ruby: rand(1..100)
来源：http://dali.cqqwz.cn/Article/details/gtogqtlrxu.html


<!-- 参考信息 -->