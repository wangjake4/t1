代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.cqqwz.cn/Article/details/gttlxnizca.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gtotacmarl.html

[U70] PHP：PDO 事务
来源：http://dali.yj202588.top/Article/details/gteqlilelv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowotrsdz.html

[U71] PHP：抛出异常
来源：http://dali.sysykeji.top/Article/details/gtgujbpnab.html

throw new RuntimeException("失败", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gtuygxcrtt.html

[U72] PHP：写错误日志
来源：http://dali.mhx1999.top/Article/details/gttdwbyvkr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ivvv.top/Article/details/gtsrrsgjax.html

[U73] PHP：读取 ini 配置
来源：http://dali.dashuyun.cn/Article/details/gtaphlcjil.html

parse_ini_file("config.ini", true)
来源：http://dali.iojbl.cn/Article/details/gtmclwresa.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliaefbdq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258.top/Article/details/gtxzjdchxo.html

[U75] PHP：依赖注入
来源：http://dali.havefunace.top/Article/details/gtdmhuffup.html

composer require psr/container
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgqclkzl.html

[U76] PHP：简单路由
来源：http://dali.dashuyun.cn/Article/details/gtfxrodbdh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvmyyguj.html

[U77] PHP：模板渲染
来源：http://dali.gogol.net.cn/Article/details/gtbobnfmdd.html

composer require twig/twig
来源：http://dali.jianghu66.top/Article/details/gtezkmesni.html

[U78] PHP：单元测试
来源：http://dali.yonumen.top/Article/details/gtqjmwltzc.html

composer require --dev phpunit/phpunit
来源：http://dali.jinqigfzy.top/Article/details/gtdnqivqmz.html

[U79] PHP：静态分析
来源：http://dali.dashuyun.cn/Article/details/gtigkwnzvc.html

composer require --dev phpstan/phpstan
来源：http://dali.hfpthk.cn/Article/details/gtomnbimim.html

[U80] PHP：代码规范修复
来源：http://dali.jyoumei.cn/Article/details/gtuoxiudds.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgufenzy.top/Article/details/gthhzteske.html

[U81] JS：初始化项目
来源：http://dali.snrcjt.cn/Article/details/gttychggcw.html

npm init -y;  npm i express
来源：http://dali.shuidangran.top/Article/details/gtevtuhoqs.html

[U82] JS：package.json 脚本
来源：http://dali.mhx1999.top/Article/details/gtnlfqgtgn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnxiangtu.top/Article/details/gtauqevflw.html

[U83] JS：ES Module 导入导出
来源：http://dali.haohaochexian.top/Article/details/gtkdmwwtcu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gtfxwcyedr.html

[U84] JS：CommonJS 写法
来源：http://dali.dianchejie.cn/Article/details/gtvgpczite.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixbegspf.html

[U85] JS：可选链
来源：http://dali.cheryme.top/Article/details/gtaegrtjhl.html

a?.b?.c
来源：http://dali.svipenyu.cn/Article/details/gtolmewakz.html

[U86] JS：空值合并
来源：http://dali.tanke756.top/Article/details/gtzgllwsdf.html

a ?? b
来源：http://dali.kuanghao11.cn/Article/details/gtmmukkvbh.html

[U87] JS：解构默认值
来源：http://dali.gaohongyu789.top/Article/details/gtqksmdijc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cashguo.top/Article/details/gtmzosxrfr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gtflulzucz.html

{ ...a, ...b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdpweluo.html

[U89] JS：数组去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgqymcdx.html

[...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtopajpgui.html

[U90] JS：数字数组排序
来源：http://dali.nanxuanxn.top/Article/details/gtqccmxrrf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtpxoobcjg.html

[U91] JS：对象键值遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtgkvwmoku.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tian-w.cn/Article/details/gtgwtdansy.html

[U92] JS：深拷贝
来源：http://dali.ydzc1.top/Article/details/gttmvmkfta.html

structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtjqgfxlme.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gtkbdpogml.html

`共 ${n} 条`
来源：http://dali.hnxiangtu.top/Article/details/gtnlkgvrvt.html

[U94] JS：箭头函数
来源：http://dali.sxryk.cn/Article/details/gtffmmeraq.html

const double = x => x * 2;
来源：http://dali.jinqigufen.top/Article/details/gtgyvxdphv.html

[U95] JS：Promise 包装
来源：http://dali.tian-w.cn/Article/details/gtpegsheao.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgfzy.top/Article/details/gtvlbfqtwz.html

[U96] JS：async/await 与异常
来源：http://dali.0kj1m.cn/Article/details/gtzmjsqjtq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtqccjhguv.html

[U97] JS：并发请求
来源：http://dali.jiagoushi.top/Article/details/gtplfnoukd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtqvqzswvk.html

[U98] JS：fetch 带 JSON
来源：http://dali.iojbl.cn/Article/details/gtrfnlhevj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pengpengdd.cyou/Article/details/gtfvsgwkpf.html

[U99] JS：事件监听
来源：http://dali.ybcxt.top/Article/details/gtxprwabge.html

el.addEventListener("click", e => {})
来源：http://dali.gaohongyu789.top/Article/details/gtfaxirwov.html

[U100] JS：DOM 查询
来源：http://dali.birdmap.top/Article/details/gtibmqcewo.html

document.querySelector(".item")
来源：http://dali.xuanzx.com/Article/details/gtlvfuctfz.html

[U101] JS：classList 操作
来源：http://dali.jinqigfzy.top/Article/details/gtaqtwkzmm.html

el.classList.toggle("active")
来源：http://dali.nanxinkj.top/Article/details/gtlqcywvgk.html

[U102] JS：本地存储
来源：http://dali.hysaishi.cn/Article/details/gtsilncbwh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.fengsongda.top/Article/details/gtzoqfqkeu.html

[U103] JS：定时器
来源：http://dali.guannengcc.top/Article/details/gthztvlqlo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenjidiqi.icu/Article/details/gtgnfuaflw.html

[U104] JS：防抖
来源：http://dali.quarkkingdee.top/Article/details/gtncgxjyfm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtxlvkcyyg.html

[U105] JS：节流
来源：http://dali.yj20258.top/Article/details/gtwmapssld.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yueranfly.top/Article/details/gtfggfnsnn.html

[U106] JS：日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtdtbmixzh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.vqdsnc.cn/Article/details/gtnnsdydde.html

[U107] JS：数字千分位
来源：http://dali.svipenyu.cn/Article/details/gtgskyavhf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gtknlybrhz.html

[U108] JS：随机整数
来源：http://dali.yonumen.top/Article/details/gtqppygqgv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tian-w.cn/Article/details/gtkiejtbdq.html

[U109] JS：数组分组
来源：http://dali.yonumen.top/Article/details/gtvnbbxjxp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtutlzjzyj.html

[U110] JS：数组分块
来源：http://dali.yongpay.top/Article/details/gtgmyllopp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhoulong.xyz/Article/details/gtnwtjicgw.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gthiilijgm.html

new Map(Object.entries(obj))
来源：http://dali.jqgufenzy.top/Article/details/gtbwpyvumy.html

[U112] JS：字符串补位
来源：http://dali.xuanzx.com/Article/details/gtdnoejftr.html

"7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtnikztvll.html

[U113] JS：正则替换全部
来源：http://dali.ehwqpu.com/Article/details/gtaqanzmxu.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtpsrmfzed.html

[U114] JS：JSON 深比较
来源：http://dali.jinqigufen.top/Article/details/gtekotpkpn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gtxcvwkslg.html

[U115] JS：生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gtpommudfp.html

crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtdqyekull.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.haohaochexian.top/Article/details/gtmljojraq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shuidangran.top/Article/details/gtvesoxzfn.html

[U117] JS：单元测试
来源：http://dali.jqgfzy.top/Article/details/gteganhlud.html

npm i -D vitest;  npx vitest
来源：http://dali.shangyingyoupin.top/Article/details/gtiasbzjna.html

[U118] JS：开发服务器
来源：http://dali.daxiang520.top/Article/details/gtvqyqivqr.html

npm i -D vite;  npx vite
来源：http://dali.jyoumei.cn/Article/details/gtmcwbjjav.html

[U119] JS：生产构建
来源：http://dali.cqqwz.cn/Article/details/gtorskyrws.html

npx vite build
来源：http://dali.yongpay.top/Article/details/gtcntqrsyy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daxiang520.top/Article/details/gtnmncxvbr.html

import.meta.env.VITE_API_URL
来源：http://dali.pengpengdd.cyou/Article/details/gthraqtuxx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuklgoqc.html

统计汇总
来源：http://dali.zhixingplan.top/Article/details/gtrhnwaafz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcqjemcfo.html

按语言统计（条）：
来源：http://dali.vqdsnc.cn/Article/details/gtnkhvbojb.html

Python ......... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtxramntkw.html

PHP ............ 252
来源：http://dali.fzhhl.top/Article/details/gtufrewrrf.html

JavaScript ..... 252
来源：http://dali.xylfe.cn/Article/details/gtmqwrxvtq.html

TypeScript ..... 212
来源：http://dali.nanxuanxn.top/Article/details/gtskuxtlwj.html

Java ........... 212
来源：http://dali.ybcxt.top/Article/details/gtfvxfkmbx.html

Go ............. 212
来源：http://dali.fengsongda.top/Article/details/gtatcmjwit.html

Ruby ........... 212
来源：http://dali.mhx1999.top/Article/details/gtqkhvxgkw.html

C# ............. 212
来源：http://dali.xinyue.icu/Article/details/gtwbgajoea.html

C .............. 30
来源：http://dali.yuanzhike.top/Article/details/gtnbmbtlsq.html

C++ ............ 30
来源：http://dali.jinqigufen.top/Article/details/gteszwzuno.html

SQL ............ 90
来源：http://dali.quarkkingdee.top/Article/details/gtfhlbodaf.html

Bash ........... 80
来源：http://dali.jinqigufen.top/Article/details/gtinsclloq.html

Kotlin ......... 15
来源：http://dali.yuanzhike.top/Article/details/gtpovmvjwf.html

Swift .......... 15
来源：http://dali.sweek.top/Article/details/gtijhlgayo.html

Lua ............ 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndcgvfel.html

Perl ........... 10
来源：http://dali.yuxming.cn/Article/details/gtnkbiqfio.html

Scala .......... 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkhxkhbv.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtduxpvgbt.html

合计 ........... 2106 条
来源：http://dali.guannengcc.top/Article/details/gtddpgtjfg.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtsocfvlbe.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenjidiqi.icu/Article/details/gtemkjvabb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gtegcjmqxe.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gtjdzpuyhc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhixingplan.top/Article/details/gtqxfglzoy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guannengcc.top/Article/details/gtzutjufqs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gaohongyu789.top/Article/details/gttgxrhcmd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtqlvkbdlg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.havefunace.top/Article/details/gtgzxegvfr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtedahmslu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkcameiu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtvbxsgmpb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtaesytpav.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtpxajjvvp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.feifeiyinyue.top/Article/details/gtqujhxgte.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hnqzz.top/Article/details/gtgllngqst.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtjibvrqyl.html

Q SQL 专题                              90
来源：http://dali.yuanzhike.top/Article/details/gtmzbdhief.html

R Bash 专题                             80
来源：http://dali.guannengcc.top/Article/details/gtyoxfbumn.html

S C / C++ 专题                          60
来源：http://dali.nanxinkj.top/Article/details/gthbghqafn.html

T 其他语言补充                          60
来源：http://dali.xziqi.cn/Article/details/gtfjpifgda.html

U 高频实用片段                         120
来源：http://dali.daria6918.cn/Article/details/gtewhjggsz.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtafmgfdax.html

合计                                  2106 条
来源：http://dali.aibaodan.cn/Article/details/gtgqlawluv.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtydsrxkbi.html

使用提醒
来源：http://dali.316326.xyz/Article/details/gtdxpzbbpt.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gturudjyrb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zycfv.cn/Article/details/gtjbbwqcco.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zycfv.cn/Article/details/gtfaauydxb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hywenlv.cn/Article/details/gtgkjotuti.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tian-w.cn/Article/details/gtutmmxatn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ydzc1.top/Article/details/gtagztnqwc.html

—— 文件结束 ——
来源：http://dali.yj202588.top/Article/details/gtiyswztmh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtjsyzoskr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.quarkkingdee.top/Article/details/gtfnffywbe.html

Common Programming Examples Cheat Book
来源：http://dali.jqgufenzy.top/Article/details/gtevnrevkd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtihgnvfcq.html

【收录内容】
来源：http://dali.svipenyu.cn/Article/details/gtbhbbmgbt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yongpay.top/Article/details/gtsjrfthbu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cheryme.top/Article/details/gtylodwyur.html

SQL · Bash · C · C++
来源：http://dali.aizwys.cn/Article/details/gtarbwhsit.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhengqikj.top/Article/details/gtisyoetqz.html

【使用说明】
来源：http://dali.iojbl.cn/Article/details/gtecwcqcxx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.redwolf501.top/Article/details/gtqjkovemp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tianlin.xyz/Article/details/gtloqyngvy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sweek.top/Article/details/gtjnuzdwvi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xuanzx.com/Article/details/gtimahgtus.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.andypj.xyz/Article/details/gtrpqwviva.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tanke756.top/Article/details/gtqwlqybar.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hysaishi.cn/Article/details/gtxhqesehl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fzhhl.top/Article/details/gtxbsflsxv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.mhx1999.top/Article/details/gtvzristww.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gzhubu.top/Article/details/gtpaaspywd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.pengpengdd.cyou/Article/details/gtvqpcbzzc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xuetiantiany.cn/Article/details/gtqfnlpsvs.html

【文件统计】
来源：http://dali.yj202588.top/Article/details/gtjtfcbvgu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gtrnojgsif.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtundumrec.html

目  录
来源：http://dali.cqqwz.cn/Article/details/gtwejfutrj.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtslxwqewx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gtwflreyqh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gtjpckapcs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.fengsongda.top/Article/details/gtbwmlmwqk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sxryk.cn/Article/details/gtdudcjqex.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sweek.top/Article/details/gtdywasant.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gtytgmypzi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtvirbpivv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.havefunace.top/Article/details/gtxlidleim.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtothtpmva.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gtytmifhdy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtgloycpdb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gtwflnvfuc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqsmonhx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hnxiangtu.top/Article/details/gtahaxvlel.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.316326.xyz/Article/details/gtbyljhdxi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtuaamozsw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shzxlz.cn/Article/details/gtkufysdgb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtysownwlx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenzaomai.com/Article/details/gtaslpuplr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtdfdrdrly.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gtomijzbda.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtvrdbgcgw.html

A. 基础语法与类型
来源：http://dali.9152youxi.cn/Article/details/gtsrwzommm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtssldowkr.html

[A01] Hello World
来源：http://dali.yongpay.top/Article/details/gtezofywdg.html

Py:   print("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtjxubkyjd.html

PHP:  echo "Hello, World!";
来源：http://dali.andypj.xyz/Article/details/gtilbrdjyx.html

JS:   console.log("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gtgzbyppef.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hysaishi.cn/Article/details/gtlrlpyhll.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtfhtytkrt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.pengpengdd.cyou/Article/details/gtduhkjqpf.html

Ruby: puts "Hello, World!"
来源：http://dali.daria6918.cn/Article/details/gtzgxhovpq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gtcbvxtozr.html

[A02] 变量声明与赋值
来源：http://dali.ppjwa.cn/Article/details/gtsvdrepcz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tanke756.top/Article/details/gtjcnpqwow.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtnyvdnrpz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.smart0.xyz/Article/details/gtvzrwjpun.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.haohaochexian.top/Article/details/gtoncdtbzn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gtxpgztrim.html

Go:   name := "Alex"; age := 20
来源：http://dali.hysaishi.cn/Article/details/gtvbrokova.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ydzc1.top/Article/details/gtswioivqo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gtytcmgwgx.html

[A03] 常量定义
来源：http://dali.xylfe.cn/Article/details/gtnkxgjkfv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jlsjyb.cn/Article/details/gtcxsnrwat.html

PHP:  const PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtwzdfmygd.html

JS:   const PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtuexdazfu.html

TS:   const PI: number = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gttkpfargh.html

Java: static final double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtrkidhkxx.html

Go:   const PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gtikftdyqf.html

Ruby: PI = 3.14159
来源：http://dali.xziqi.cn/Article/details/gtpmuzzssr.html

C#:   const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gthmszjtqh.html

[A04] 判断变量类型
来源：http://dali.gogol.net.cn/Article/details/gtyxyopvhg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fengsongda.top/Article/details/gtthwtvofl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.dashuyun.cn/Article/details/gtmbakuape.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gtyilrbsgp.html

TS:   typeof x; x instanceof Date
来源：http://dali.chenlongwang.top/Article/details/gttioqsfsc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.haohaochexian.top/Article/details/gtbjkxeqrv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cucudq.cn/Article/details/gtjmkmyqbt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaarodwei.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinqigfzy.top/Article/details/gtbozhebec.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gtkajnpcja.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yangfankeji.com/Article/details/gtlgikvgyp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gtivlbwoum.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtujngnobh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gttlbopzup.html

Java: 7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gtbhmlqyzb.html

Go:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtpdxqzovp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtujhnfipk.html

C#:   7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gttgczifda.html

[A06] 字符串转数字
来源：http://dali.tian-w.cn/Article/details/gtgbhaqmzm.html

Py:   int("42"); float("3.14")
来源：http://dali.ppjwa.cn/Article/details/gtwpnzcrlk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yongpay.top/Article/details/gtiqtceyyb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gtimtgljzj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtkcmbxsui.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nanxinkj.top/Article/details/gtezpkobgg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guowangkeji.top/Article/details/gttejcrfqa.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.guowangkeji.top/Article/details/gtdpyplpst.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sweek.top/Article/details/gtgrbuybyv.html

[A07] 数字转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxurjvxka.html

Py:   str(42)
来源：http://dali.jyoumei.cn/Article/details/gtxxhvhsxa.html

PHP:  (string) 42; strval(42)
来源：http://dali.aibaodan.cn/Article/details/gtipkyltcw.html

JS:   String(42); (42).toString()
来源：http://dali.yonumen.top/Article/details/gtopmgurho.html

TS:   String(42)
来源：http://dali.ppjwa.cn/Article/details/gtdgnkwdtk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.aibaodan.cn/Article/details/gtwkgpzqvj.html

Go:   strconv.Itoa(42)
来源：http://dali.jiagoushi.top/Article/details/gttoqhgund.html

Ruby: 42.to_s
来源：http://dali.guannengcc.top/Article/details/gtfjhmnirg.html

C#:   42.ToString()
来源：http://dali.tanke756.top/Article/details/gttnbnpyyj.html

[A08] 取整与四舍五入
来源：http://dali.chenlongwang.top/Article/details/gtjkzpefmg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtxxstzbcd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywykjkcf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnacczvmb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hysaishi.cn/Article/details/gturjotvyj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ivvv.top/Article/details/gtpncsmago.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtpybsomcb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenlongwang.top/Article/details/gtamuerawi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yonumen.top/Article/details/gtzabbvugl.html

[A09] 绝对值与最大最小值
来源：http://dali.sysykeji.top/Article/details/gtzisdtoji.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtzapbppto.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtenvhdsnq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtqehiutvl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtsbdplplo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgzlybxn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shuidangran.top/Article/details/gtggersfik.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yangfankeji.com/Article/details/gtzqqorwdi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.316326.xyz/Article/details/gtqkjjfvob.html

[A10] 生成随机数
来源：http://dali.quarkkingdee.top/Article/details/gtznxlcwdr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.feifeiyinyue.top/Article/details/gtqqjbjsqf.html

PHP:  random_int(1, 100);
来源：http://dali.zhoulong.xyz/Article/details/gtavggunwx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guowangkeji.top/Article/details/gtqbryniuh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ehwqpu.com/Article/details/gtferfjwrf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkziekwk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hysaishi.cn/Article/details/gtivqccohh.html

Ruby: rand(1..100)
来源：http://dali.haohaochexian.top/Article/details/gtemcmkszm.html


<!-- 参考信息 -->