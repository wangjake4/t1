代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.hnqzz.top/Article/details/gtwshnotyy.html

composer require psr/container
来源：http://dali.vqdsnc.cn/Article/details/gtfdgmiqyn.html

[U76] PHP：简单路由
来源：http://dali.zhiwuduotai.top/Article/details/gtundvddll.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhoulong.xyz/Article/details/gtadpztlrr.html

[U77] PHP：模板渲染
来源：http://dali.zhengqikj.top/Article/details/gtfcsbfuzj.html

composer require twig/twig
来源：http://dali.sweek.top/Article/details/gtjlcdople.html

[U78] PHP：单元测试
来源：http://dali.xylfe.cn/Article/details/gtggnnusyu.html

composer require --dev phpunit/phpunit
来源：http://dali.pengpengdd.cyou/Article/details/gtstfgerrj.html

[U79] PHP：静态分析
来源：http://dali.yonumen.top/Article/details/gtfvovygfp.html

composer require --dev phpstan/phpstan
来源：http://dali.aibaodan.cn/Article/details/gtmsojbznk.html

[U80] PHP：代码规范修复
来源：http://dali.yuanzhike.top/Article/details/gtsmksxoxu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cqqwz.cn/Article/details/gtoidzbhds.html

[U81] JS：初始化项目
来源：http://dali.kuanghao11.cn/Article/details/gtezsvakzi.html

npm init -y;  npm i express
来源：http://dali.yangfankeji.com/Article/details/gtxbdyljav.html

[U82] JS：package.json 脚本
来源：http://dali.redwolf501.top/Article/details/gtluytlmob.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gogol.net.cn/Article/details/gtmsbgwjiq.html

[U83] JS：ES Module 导入导出
来源：http://dali.yanxiufei.cn/Article/details/gthdzbqkdk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gtxmfbqeev.html

[U84] JS：CommonJS 写法
来源：http://dali.pycfn.com/Article/details/gtvzhdmsrb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.vqdsnc.cn/Article/details/gtgqexzkuq.html

[U85] JS：可选链
来源：http://dali.ydzc1.top/Article/details/gtbqnvivne.html

a?.b?.c
来源：http://dali.havefunace.top/Article/details/gtidzkonqq.html

[U86] JS：空值合并
来源：http://dali.hongshengwenyu.top/Article/details/gtcjcgnmqs.html

a ?? b
来源：http://dali.hfpthk.cn/Article/details/gtxhxqpgqc.html

[U87] JS：解构默认值
来源：http://dali.zhixingplan.top/Article/details/gttiulazpe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hfpthk.cn/Article/details/gtmbnxzyqm.html

[U88] JS：对象展开合并
来源：http://dali.aizwys.cn/Article/details/gtudsmatwr.html

{ ...a, ...b }
来源：http://dali.dianchejie.cn/Article/details/gttvkkewpk.html

[U89] JS：数组去重
来源：http://dali.kuanghao11.cn/Article/details/gtscxxgqcv.html

[...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtlupfcmmz.html

[U90] JS：数字数组排序
来源：http://dali.meibo888.top/Article/details/gtmjjtkkza.html

[...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gttenrbmyr.html

[U91] JS：对象键值遍历
来源：http://dali.dianchejie.cn/Article/details/gtjtercvxf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.0kj1m.cn/Article/details/gtsvrzepgz.html

[U92] JS：深拷贝
来源：http://dali.dashuyun.cn/Article/details/gtfyovidsm.html

structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtreqvmykf.html

[U93] JS：模板字符串
来源：http://dali.gotoacloud.top/Article/details/gtijcvubob.html

`共 ${n} 条`
来源：http://dali.gotoacloud.top/Article/details/gtcekrzmir.html

[U94] JS：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gtycjxgqho.html

const double = x => x * 2;
来源：http://dali.gotoacloud.top/Article/details/gtfqpfnltv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gtkcxmsarn.html

new Promise((resolve, reject) => {})
来源：http://dali.nanxinkj.top/Article/details/gtlrutgieq.html

[U96] JS：async/await 与异常
来源：http://dali.xuanzx.com/Article/details/gthyroixpo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtvwatqbnl.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnynyegye.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpleigsoe.html

[U98] JS：fetch 带 JSON
来源：http://dali.c1oappe.top/Article/details/gtmedqesud.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dashuyun.cn/Article/details/gtesixweuu.html

[U99] JS：事件监听
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfldvkze.html

el.addEventListener("click", e => {})
来源：http://dali.mhx1999.top/Article/details/gtgoqkghqg.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gtlluqrfny.html

document.querySelector(".item")
来源：http://dali.sysykeji.top/Article/details/gtksujivlu.html

[U101] JS：classList 操作
来源：http://dali.cashguo.top/Article/details/gtebstnoky.html

el.classList.toggle("active")
来源：http://dali.nanxuanxn.top/Article/details/gtcjiresfy.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsejsqetm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yuanzhike.top/Article/details/gtrgdcenov.html

[U103] JS：定时器
来源：http://dali.xinyue.icu/Article/details/gtppbkohyk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfssfmru.html

[U104] JS：防抖
来源：http://dali.kuanghao11.cn/Article/details/gtquyelnhk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtpegqwkci.html

[U105] JS：节流
来源：http://dali.gogol.net.cn/Article/details/gtdizikija.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuxming.cn/Article/details/gtfncaovqz.html

[U106] JS：日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtxuiqhvnh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fzhhl.top/Article/details/gtwqvdyvml.html

[U107] JS：数字千分位
来源：http://dali.c1oappe.top/Article/details/gtwnvhkaiv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sweek.top/Article/details/gtlsborcjc.html

[U108] JS：随机整数
来源：http://dali.aibaodan.cn/Article/details/gtwcqnxjdl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shzxlz.cn/Article/details/gtmwiijhwa.html

[U109] JS：数组分组
来源：http://dali.gzhubu.top/Article/details/gtdamplolb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtighqyuaw.html

[U110] JS：数组分块
来源：http://dali.hongshengwenyu.top/Article/details/gtpadaqzlv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sysykeji.top/Article/details/gtpavhnesf.html

[U111] JS：对象转 Map
来源：http://dali.sxryk.cn/Article/details/gtfxdetmnd.html

new Map(Object.entries(obj))
来源：http://dali.gaohongyu789.top/Article/details/gtarkzgrao.html

[U112] JS：字符串补位
来源：http://dali.jqgfzy.top/Article/details/gtgfoscsmp.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtkddliguw.html

[U113] JS：正则替换全部
来源：http://dali.ehwqpu.com/Article/details/gtdmoqkgki.html

s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtsxxnwcky.html

[U114] JS：JSON 深比较
来源：http://dali.ybcxt.top/Article/details/gtxkwepchw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.svipenyu.cn/Article/details/gtsxgsdlla.html

[U115] JS：生成 UUID
来源：http://dali.yj202588.top/Article/details/gtngiuekfe.html

crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtguunpivz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsyhmbwg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hfpthk.cn/Article/details/gtflqizulh.html

[U117] JS：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gtkcozzknw.html

npm i -D vitest;  npx vitest
来源：http://dali.ivvv.top/Article/details/gtyivxozam.html

[U118] JS：开发服务器
来源：http://dali.gaohongyu789.top/Article/details/gtrssrmcxl.html

npm i -D vite;  npx vite
来源：http://dali.yongpay.top/Article/details/gtzihynvql.html

[U119] JS：生产构建
来源：http://dali.ivvv.top/Article/details/gtioexddtt.html

npx vite build
来源：http://dali.guowangkeji.top/Article/details/gtypihwzpu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj202588.top/Article/details/gtvwoplvru.html

import.meta.env.VITE_API_URL
来源：http://dali.vqdsnc.cn/Article/details/gtytzvhvlm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtodvgxwyk.html

统计汇总
来源：http://dali.yuanzhike.top/Article/details/gtzdsqopsa.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvrwgxsvx.html

按语言统计（条）：
来源：http://dali.zhengqikj.top/Article/details/gtngpjceez.html

Python ......... 252
来源：http://dali.xuanzx.com/Article/details/gtghzowrij.html

PHP ............ 252
来源：http://dali.0kj1m.cn/Article/details/gtbbkzgfeo.html

JavaScript ..... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtjvrxyrpp.html

TypeScript ..... 212
来源：http://dali.aibaodan.cn/Article/details/gtxtlmxrcn.html

Java ........... 212
来源：http://dali.zdqjudy.top/Article/details/gthnwgasar.html

Go ............. 212
来源：http://dali.yueranfly.top/Article/details/gtfdhgzrvj.html

Ruby ........... 212
来源：http://dali.jqgufenzy.top/Article/details/gtkfswjzaf.html

C# ............. 212
来源：http://dali.zdqjudy.top/Article/details/gtcuxjqkmx.html

C .............. 30
来源：http://dali.jqgufenzy.top/Article/details/gtqhfybgdb.html

C++ ............ 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjyuziys.html

SQL ............ 90
来源：http://dali.jqgfzy.top/Article/details/gtdosfgdlt.html

Bash ........... 80
来源：http://dali.wangshuangyany.cn/Article/details/gthryrufhi.html

Kotlin ......... 15
来源：http://dali.aibaodan.cn/Article/details/gtabgngqyi.html

Swift .......... 15
来源：http://dali.chenzaomai.com/Article/details/gtmxjvjayq.html

Lua ............ 10
来源：http://dali.jinqigfzy.top/Article/details/gtrvtpyypn.html

Perl ........... 10
来源：http://dali.chenlongwang.top/Article/details/gtjgwzaart.html

Scala .......... 10
来源：http://dali.jiagoushi.top/Article/details/gtrrrqewzc.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtrtkpgzbg.html

合计 ........... 2106 条
来源：http://dali.yuxming.cn/Article/details/gtzoqrdykb.html

按章节统计：
来源：http://dali.zhoulong.xyz/Article/details/gttrrohjpb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gtjeganlbi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtiouywsif.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gtrydurbus.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gteaepxeoh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hammf.cn/Article/details/gtujkykmve.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.haohaochexian.top/Article/details/gtzhbrjfcq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtzlyxrqar.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.9152youxi.cn/Article/details/gtcyzfegsn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtotgzgebp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.havefunace.top/Article/details/gthncmpixx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtnigyleck.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtjnnvujgw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gttqcgcdha.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gtvqkyjudj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nwbrower.top/Article/details/gtaxuoekep.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtfgfekhsr.html

Q SQL 专题                              90
来源：http://dali.kuanghao11.cn/Article/details/gthtebhgks.html

R Bash 专题                             80
来源：http://dali.jiagoushi.top/Article/details/gtthyxrlye.html

S C / C++ 专题                          60
来源：http://dali.aizwys.cn/Article/details/gtbfydizle.html

T 其他语言补充                          60
来源：http://dali.gzhubu.top/Article/details/gtfcdclkea.html

U 高频实用片段                         120
来源：http://dali.jqgufenzy.top/Article/details/gtmbvhyjnv.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtdkopvwad.html

合计                                  2106 条
来源：http://dali.hammf.cn/Article/details/gtwpkfcxci.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlbwkaat.html

使用提醒
来源：http://dali.xuetiantiany.cn/Article/details/gtfsxamuqw.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtkpannanj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zdqjudy.top/Article/details/gthyxbgcdz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xylfe.cn/Article/details/gtiqxnmfjh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tanke756.top/Article/details/gtbqjloyau.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shuidangran.top/Article/details/gtawlocyvd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aibaodan.cn/Article/details/gtjivsjxcz.html

—— 文件结束 ——
来源：http://dali.shuidangran.top/Article/details/gtkujkesxi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtyscjsekl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shangyingyoupin.top/Article/details/gtdfyjjsxd.html

Common Programming Examples Cheat Book
来源：http://dali.wangshuangyany.cn/Article/details/gtrpioudcd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtluqhkspz.html

【收录内容】
来源：http://dali.mhx1999.top/Article/details/gtkhoveyuz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.snrcjt.cn/Article/details/gtzjuwqnql.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xuetiantiany.cn/Article/details/gtmjnufarz.html

SQL · Bash · C · C++
来源：http://dali.jlsjyb.cn/Article/details/gtkubdhplt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hywenlv.cn/Article/details/gtrkazmjug.html

【使用说明】
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdzkqiof.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sxryk.cn/Article/details/gtsxshecwa.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sweek.top/Article/details/gtzqopnivb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.wangshuangyany.cn/Article/details/gtqwysrajq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.pycfn.com/Article/details/gtjgtfwoqs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.kuanghao11.cn/Article/details/gtkndfmdqx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zdqjudy.top/Article/details/gtsjniqeyx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xuanzx.com/Article/details/gteadzmrhg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shzxlz.cn/Article/details/gtgojzbbvr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yangfankeji.com/Article/details/gtghlxjjqt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gtvtvqyigu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shuidangran.top/Article/details/gtfhevtowe.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ybcxt.top/Article/details/gtdpkofuqh.html

【文件统计】
来源：http://dali.tanke756.top/Article/details/gtqocsstub.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.andypj.xyz/Article/details/gtdvfzilyf.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtkizkdrgi.html

目  录
来源：http://dali.jyoumei.cn/Article/details/gtfwhvnnue.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtqgkuhplz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenjidiqi.icu/Article/details/gttxtkqvpo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gtznfssukj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtpfzcrzpg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cdnleiting.top/Article/details/gtrzpfbeia.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnqzz.top/Article/details/gtuhuxvjqu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yongpay.top/Article/details/gtzejwrfab.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gtpbvvbiuh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczgxkowu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtrgvyrdpw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gzhubu.top/Article/details/gtnsrajwkj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtcmymyzcg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgavdyhpy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsipcygeu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cdnleiting.top/Article/details/gtzkgrveng.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fzhhl.top/Article/details/gtgjctcprm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtplqwbcya.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.guannengcc.top/Article/details/gtmvslxnux.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtgdwmssqe.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.tanke756.top/Article/details/gtuountinx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtpyfdfena.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gtlrspttot.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthszwasti.html

A. 基础语法与类型
来源：http://dali.yuanzhike.top/Article/details/gtvlbqgakj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtveekjpsu.html

[A01] Hello World
来源：http://dali.tian-w.cn/Article/details/gtjrjpihkk.html

Py:   print("Hello, World!")
来源：http://dali.cqqwz.cn/Article/details/gtlkrmucdm.html

PHP:  echo "Hello, World!";
来源：http://dali.yangfankeji.com/Article/details/gtgmysjvyb.html

JS:   console.log("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gtbnpnmkpw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cheryme.top/Article/details/gtmbowmsls.html

Java: System.out.println("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gtubrhvlze.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ydzc1.top/Article/details/gteqxsixri.html

Ruby: puts "Hello, World!"
来源：http://dali.sweek.top/Article/details/gthrbhnbqx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gthiasbijv.html

[A02] 变量声明与赋值
来源：http://dali.ivvv.top/Article/details/gttbnegdaz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.vqdsnc.cn/Article/details/gtvkehxecb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtdthmxpij.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gogol.net.cn/Article/details/gteijymqwy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jqgfzy.top/Article/details/gtfopsuzaa.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yuanzhike.top/Article/details/gtkweypxag.html

Go:   name := "Alex"; age := 20
来源：http://dali.iojbl.cn/Article/details/gtsicqptxx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sysykeji.top/Article/details/gtxfjvxzcd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtmenhngiv.html

[A03] 常量定义
来源：http://dali.zdqjudy.top/Article/details/gtpxelhwsj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ybcxt.top/Article/details/gtygipujyq.html

PHP:  const PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtkvxwphmx.html

JS:   const PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtghrcnafo.html

TS:   const PI: number = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtdzotslyq.html

Java: static final double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtjdzmvqrj.html

Go:   const PI = 3.14159
来源：http://dali.gaohongyu789.top/Article/details/gtdbnspeqw.html

Ruby: PI = 3.14159
来源：http://dali.jiagoushi.top/Article/details/gtqwqwkllp.html

C#:   const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtjboywfku.html

[A04] 判断变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbngkqzy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.daxiang520.top/Article/details/gttaumkfej.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj202588.top/Article/details/gtyvjrqbdq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jqgufenzy.top/Article/details/gtrywdwyxr.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258.top/Article/details/gtygzeomel.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.aibaodan.cn/Article/details/gtltvdhlrh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnxiangtu.top/Article/details/gtwyrjmtlr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.fzhhl.top/Article/details/gtptuyojso.html

C#:   x.GetType().Name; x is int
来源：http://dali.hammf.cn/Article/details/gtlhkmkeet.html

[A05] 整数除法与取模
来源：http://dali.cheryme.top/Article/details/gtenxtzxon.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgfzy.top/Article/details/gtboorgvce.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtcpzmlpkc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.316326.xyz/Article/details/gtvsoyacgv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtimgpqcmh.html

Java: 7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gtwrqhplbt.html

Go:   7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtpurtkyic.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gthhpvctsh.html

C#:   7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtbkqyjquz.html

[A06] 字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gtefkcvvpa.html

Py:   int("42"); float("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtzeluqbef.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xziqi.cn/Article/details/gtvwbrjnhr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sufxvd.cn/Article/details/gtuncsflcb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hywenlv.cn/Article/details/gtuvarwqep.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tanke756.top/Article/details/gtunyektqb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.bjfxy.top/Article/details/gtsckjnnjf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.dashuyun.cn/Article/details/gtonrgdqzs.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xinyue.icu/Article/details/gtyxkhlnea.html

[A07] 数字转字符串
来源：http://dali.daxiang520.top/Article/details/gtjdupzzqo.html

Py:   str(42)
来源：http://dali.gotoacloud.top/Article/details/gtidbfikfn.html

PHP:  (string) 42; strval(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmorjykj.html

JS:   String(42); (42).toString()
来源：http://dali.ybcxt.top/Article/details/gtwzqyoaah.html

TS:   String(42)
来源：http://dali.gaohongyu789.top/Article/details/gtlelprofm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.bjfxy.top/Article/details/gtlsqiuyej.html

Go:   strconv.Itoa(42)
来源：http://dali.aibaodan.cn/Article/details/gteflmyquz.html

Ruby: 42.to_s
来源：http://dali.zhixingplan.top/Article/details/gtqtouamyw.html

C#:   42.ToString()
来源：http://dali.yvedp.cn/Article/details/gtwgpdupon.html

[A08] 取整与四舍五入
来源：http://dali.tanke756.top/Article/details/gtbgkqcbxr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtloomsznz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.feifeiyinyue.top/Article/details/gtqtjymrak.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitfpxkax.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gotoacloud.top/Article/details/gtsgmrtpcq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzjpolqu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtdeqmrwwt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cucudq.cn/Article/details/gtsyfyoqgl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.haohaochexian.top/Article/details/gtmkffufkn.html

[A09] 绝对值与最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtxksdqrab.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtlpvddamt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtprbnfqqs.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtxhdhfgif.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sweek.top/Article/details/gtsojhczzp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtkkjlugxx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.quarkkingdee.top/Article/details/gtyhdmscro.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ppjwa.cn/Article/details/gttiofeldk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtwbbiohgt.html

[A10] 生成随机数
来源：http://dali.cqqwz.cn/Article/details/gtzdxchkda.html

Py:   import random; random.randint(1, 100)
来源：http://dali.mhx1999.top/Article/details/gtkcvwuohd.html

PHP:  random_int(1, 100);
来源：http://dali.ehwqpu.com/Article/details/gttfsulfzc.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dashuyun.cn/Article/details/gtidjzpcnw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jianghu66.top/Article/details/gtdfnzqbxj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258888.top/Article/details/gtbqkxfqmx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhixingplan.top/Article/details/gtvhhbuynp.html

Ruby: rand(1..100)
来源：http://dali.pengpengdd.cyou/Article/details/gtzzgoisag.html

C#:   new Random().Next(1, 101)
来源：http://dali.shangyingyoupin.top/Article/details/gtwnrcckms.html

[A11] 条件表达式（三元）
来源：http://dali.zhixingplan.top/Article/details/gtauarfovi.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.sxryk.cn/Article/details/gtxrxvttkq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtothvjnth.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gtkhfkrdsc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtqpkhawaq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gtdlzrgkye.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.sweek.top/Article/details/gtteljgyaz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gtwilitvtf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gttcswobdb.html

[A12] 字符串插值 / 格式化
来源：http://dali.0kj1m.cn/Article/details/gtkeismqce.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hnqzz.top/Article/details/gttiyttspg.html


<!-- 参考信息 -->