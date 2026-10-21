代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.hysaishi.cn/Article/details/gtmpwyluqu.html

composer require psr/container
来源：http://dali.shangyingyoupin.top/Article/details/gtbuapfrgw.html

[U76] PHP：简单路由
来源：http://dali.iojbl.cn/Article/details/gtioseyqkv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.daxiang520.top/Article/details/gtudtjqggq.html

[U77] PHP：模板渲染
来源：http://dali.cdnleiting.top/Article/details/gtnotwpvyc.html

composer require twig/twig
来源：http://dali.hfpthk.cn/Article/details/gteghcjpqh.html

[U78] PHP：单元测试
来源：http://dali.xinyue.icu/Article/details/gtxbrawzxq.html

composer require --dev phpunit/phpunit
来源：http://dali.yvedp.cn/Article/details/gtgkoonhfw.html

[U79] PHP：静态分析
来源：http://dali.chenlongwang.top/Article/details/gtrxsrqpvf.html

composer require --dev phpstan/phpstan
来源：http://dali.redwolf501.top/Article/details/gtseojbsro.html

[U80] PHP：代码规范修复
来源：http://dali.feifeiyinyue.top/Article/details/gtrfhqovrg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cheryme.top/Article/details/gtllznouyh.html

[U81] JS：初始化项目
来源：http://dali.jqgfzy.top/Article/details/gtsuoitfxx.html

npm init -y;  npm i express
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjhuiwgm.html

[U82] JS：package.json 脚本
来源：http://dali.tian-w.cn/Article/details/gtncogrcfi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.kuanghao11.cn/Article/details/gtsnxmtkyi.html

[U83] JS：ES Module 导入导出
来源：http://dali.hnqzz.top/Article/details/gtbwdzoqpk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gtorxhplji.html

[U84] JS：CommonJS 写法
来源：http://dali.daria6918.cn/Article/details/gtxznrbehs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dianchejie.cn/Article/details/gtklshxwlr.html

[U85] JS：可选链
来源：http://dali.fengsongda.top/Article/details/gtuecrmqxu.html

a?.b?.c
来源：http://dali.ybcxt.top/Article/details/gtunxniipt.html

[U86] JS：空值合并
来源：http://dali.shuidangran.top/Article/details/gtumehdfwj.html

a ?? b
来源：http://dali.xuanzx.com/Article/details/gttlouydli.html

[U87] JS：解构默认值
来源：http://dali.birdmap.top/Article/details/gtnjxsmxkm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nwbrower.top/Article/details/gtqnkejhar.html

[U88] JS：对象展开合并
来源：http://dali.nanxuanxn.top/Article/details/gtjpzcdfnn.html

{ ...a, ...b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqdhdxsv.html

[U89] JS：数组去重
来源：http://dali.jinqigufen.top/Article/details/gtlzwlugjg.html

[...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtgoehqmii.html

[U90] JS：数字数组排序
来源：http://dali.hongshengwenyu.top/Article/details/gtfvuwnvlu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtxkxpdrmi.html

[U91] JS：对象键值遍历
来源：http://dali.meibo888.top/Article/details/gtsmqzxrce.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guannengcc.top/Article/details/gtpjlbyzib.html

[U92] JS：深拷贝
来源：http://dali.guannengcc.top/Article/details/gtnhoalaoq.html

structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtpexbfbpx.html

[U93] JS：模板字符串
来源：http://dali.ehwqpu.com/Article/details/gtcpmboiqq.html

`共 ${n} 条`
来源：http://dali.sufxvd.cn/Article/details/gtlvkjlsew.html

[U94] JS：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gtsffbxino.html

const double = x => x * 2;
来源：http://dali.shzxlz.cn/Article/details/gtbozzqspg.html

[U95] JS：Promise 包装
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyvzsqct.html

new Promise((resolve, reject) => {})
来源：http://dali.9152youxi.cn/Article/details/gtbgsuvwyc.html

[U96] JS：async/await 与异常
来源：http://dali.hywenlv.cn/Article/details/gtknbtatbb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gticnozlep.html

[U97] JS：并发请求
来源：http://dali.haohaochexian.top/Article/details/gtyuxphwec.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtcvovvagu.html

[U98] JS：fetch 带 JSON
来源：http://dali.smart0.xyz/Article/details/gtsagqzcdq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.kuanghao11.cn/Article/details/gtqnywikox.html

[U99] JS：事件监听
来源：http://dali.nwbrower.top/Article/details/gtbbekyjez.html

el.addEventListener("click", e => {})
来源：http://dali.aibaodan.cn/Article/details/gtdxgmziwj.html

[U100] JS：DOM 查询
来源：http://dali.birdmap.top/Article/details/gtukagxklr.html

document.querySelector(".item")
来源：http://dali.fengsongda.top/Article/details/gtmohwktwq.html

[U101] JS：classList 操作
来源：http://dali.jqgfzy.top/Article/details/gtwixtdfze.html

el.classList.toggle("active")
来源：http://dali.jqgfzy.top/Article/details/gtuxnkpdfg.html

[U102] JS：本地存储
来源：http://dali.zycfv.cn/Article/details/gtqxqenilw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.fengsongda.top/Article/details/gtlrlijtrl.html

[U103] JS：定时器
来源：http://dali.shanyushiyangtech.top/Article/details/gtizsruavr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sxryk.cn/Article/details/gtyrwsykcr.html

[U104] JS：防抖
来源：http://dali.havefunace.top/Article/details/gtnsvgulhp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmuefrcp.html

[U105] JS：节流
来源：http://dali.ppjwa.cn/Article/details/gtxwuvlaoj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ehwqpu.com/Article/details/gtpzefjmps.html

[U106] JS：日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtwhjnpzjp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.guowangkeji.top/Article/details/gtfreutdll.html

[U107] JS：数字千分位
来源：http://dali.aizwys.cn/Article/details/gtdycsvrzt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtqaloaeir.html

[U108] JS：随机整数
来源：http://dali.316326.xyz/Article/details/gtqsonxoqv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tian-w.cn/Article/details/gtlghkosuk.html

[U109] JS：数组分组
来源：http://dali.cheryme.top/Article/details/gtyrpopoyf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtpufvfyqk.html

[U110] JS：数组分块
来源：http://dali.guannengcc.top/Article/details/gtbmesxzub.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtwtlgpc.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gtbdocajfx.html

new Map(Object.entries(obj))
来源：http://dali.jyoumei.cn/Article/details/gtgmrfwawa.html

[U112] JS：字符串补位
来源：http://dali.guowangkeji.top/Article/details/gtmkvgdiko.html

"7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtxcctgtjn.html

[U113] JS：正则替换全部
来源：http://dali.shuidangran.top/Article/details/gtfmdkqmhl.html

s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtmilyhohb.html

[U114] JS：JSON 深比较
来源：http://dali.meibo888.top/Article/details/gtknlibqjq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtuvntcksa.html

[U115] JS：生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsxwnznw.html

crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtpofrftyn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aibaodan.cn/Article/details/gtkkjkbkrz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtftbvqaxz.html

[U117] JS：单元测试
来源：http://dali.yj20258.top/Article/details/gtaskumnet.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxuanxn.top/Article/details/gttqmjmepd.html

[U118] JS：开发服务器
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgaojfel.html

npm i -D vite;  npx vite
来源：http://dali.yj202588.top/Article/details/gtrwupmzpk.html

[U119] JS：生产构建
来源：http://dali.hfpthk.cn/Article/details/gtvuiwanbv.html

npx vite build
来源：http://dali.jlsjyb.cn/Article/details/gtfwgeybvb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shuidangran.top/Article/details/gtafufahrg.html

import.meta.env.VITE_API_URL
来源：http://dali.sxryk.cn/Article/details/gtseuqppbh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtvzigjoby.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gtwicjwvyv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtboxngbpc.html

按语言统计（条）：
来源：http://dali.guannengcc.top/Article/details/gtgyggpkox.html

Python ......... 252
来源：http://dali.xylfe.cn/Article/details/gttqofyone.html

PHP ............ 252
来源：http://dali.fengsongda.top/Article/details/gtbbygjvhw.html

JavaScript ..... 252
来源：http://dali.chenzaomai.com/Article/details/gttlcbjuvz.html

TypeScript ..... 212
来源：http://dali.hnqzz.top/Article/details/gtqglttbtj.html

Java ........... 212
来源：http://dali.0kj1m.cn/Article/details/gtemrdaabe.html

Go ............. 212
来源：http://dali.yuanzhike.top/Article/details/gtblqgxpet.html

Ruby ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtrnlrmwnj.html

C# ............. 212
来源：http://dali.cashguo.top/Article/details/gthllzwfjf.html

C .............. 30
来源：http://dali.iojbl.cn/Article/details/gtvvtteoyx.html

C++ ............ 30
来源：http://dali.birdmap.top/Article/details/gtnxbrmuyu.html

SQL ............ 90
来源：http://dali.zhiwuduotai.top/Article/details/gtapnbabem.html

Bash ........... 80
来源：http://dali.chenjidiqi.icu/Article/details/gtdmxiarkd.html

Kotlin ......... 15
来源：http://dali.cqqwz.cn/Article/details/gtytxaxkhr.html

Swift .......... 15
来源：http://dali.xuanzx.com/Article/details/gttcatahiy.html

Lua ............ 10
来源：http://dali.jqgufenzy.top/Article/details/gtwqbsejyw.html

Perl ........... 10
来源：http://dali.chenzaomai.com/Article/details/gtblfkeekb.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gtesidkxke.html

------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtjcuwwips.html

合计 ........... 2106 条
来源：http://dali.jlsjyb.cn/Article/details/gtjiptchwn.html

按章节统计：
来源：http://dali.0kj1m.cn/Article/details/gtddpbfmda.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gtfeuzeyto.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtckobnxbd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gtlksefwuf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gtlayxchob.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.c1oappe.top/Article/details/gtvhovhdop.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gtsvblfdej.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gtbelhmohv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gtrawyyccc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtozvoxocm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gtxtjuwffm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtjwnkjzpa.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtrgaohzkm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtorrwivhl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gtsevubnsv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guannengcc.top/Article/details/gtoohtbwae.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtccdhafog.html

Q SQL 专题                              90
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczhlnluk.html

R Bash 专题                             80
来源：http://dali.ehwqpu.com/Article/details/gtzxpmlirp.html

S C / C++ 专题                          60
来源：http://dali.316326.xyz/Article/details/gtjwrxzqot.html

T 其他语言补充                          60
来源：http://dali.nanxuanxn.top/Article/details/gtmwakjfui.html

U 高频实用片段                         120
来源：http://dali.yuanzhike.top/Article/details/gtdpelrwpu.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gtglkegyrq.html

合计                                  2106 条
来源：http://dali.aizwys.cn/Article/details/gtqskmcwsn.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtpkcclhow.html

使用提醒
来源：http://dali.sysykeji.top/Article/details/gtdpvgnxue.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtxgawmwdc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.c1oappe.top/Article/details/gtpyuyauxz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guowangkeji.top/Article/details/gtfnnancmx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.quarkkingdee.top/Article/details/gtkbqqvttr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.snrcjt.cn/Article/details/gtzlewlljj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.meibo888.top/Article/details/gtwzlsupue.html

—— 文件结束 ——
来源：http://dali.andypj.xyz/Article/details/gtxfixgljr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtltjdzbxy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangdashe.top/Article/details/gttznkymxq.html

Common Programming Examples Cheat Book
来源：http://dali.chenjidiqi.icu/Article/details/gtkjxlkgkr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkppmxrth.html

【收录内容】
来源：http://dali.yvedp.cn/Article/details/gtomiuvlxg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sufxvd.cn/Article/details/gtszskefmz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangdashe.top/Article/details/gtddrxguoe.html

SQL · Bash · C · C++
来源：http://dali.yanxiufei.cn/Article/details/gtjqemokxt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.havefunace.top/Article/details/gtcdsrlbho.html

【使用说明】
来源：http://dali.zhengqikj.top/Article/details/gtjfwvwhzr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxuanxn.top/Article/details/gtsfnikcls.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.birdmap.top/Article/details/gtlqiozxsp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznncbrzo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tian-w.cn/Article/details/gtaxmcncys.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenzaomai.com/Article/details/gthhohaojj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.bjfxy.top/Article/details/gthxvubxor.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.havefunace.top/Article/details/gtovgnmysm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gtvqfsmizo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangshuangyany.cn/Article/details/gtwbsgfrig.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hnxiangtu.top/Article/details/gtlneujqjn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yuxming.cn/Article/details/gtdkfkgeel.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cashguo.top/Article/details/gtqdayjrdb.html

【文件统计】
来源：http://dali.jinghuilouyu.cn/Article/details/gtkegnndet.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hnqzz.top/Article/details/gtejttsggd.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtjmqbqzfh.html

目  录
来源：http://dali.tian-w.cn/Article/details/gttxhaclsp.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gthbexsxlr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gtlyvkqlzx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gtbnuwyusp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtyhcrxkdz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmsnswkw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.316326.xyz/Article/details/gtckkmfqre.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ydzc1.top/Article/details/gtbdiylseq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gtclmjhomj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zycfv.cn/Article/details/gtqhlmykyu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gtimoyrhme.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hywenlv.cn/Article/details/gtqkdnjnnb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtgesgvsxk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtnemyejet.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtnhqnbfvp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.haohaochexian.top/Article/details/gtredaoxsh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.haohaochexian.top/Article/details/gthkjoanhw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtqyqsyvsc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakqsnxgt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gttbrlvung.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.316326.xyz/Article/details/gtolfwnhqv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gtesrjptld.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gtsifhvsdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtlsrarhml.html

A. 基础语法与类型
来源：http://dali.nwbrower.top/Article/details/gtvkjakpct.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtplcsqkcn.html

[A01] Hello World
来源：http://dali.hnqzz.top/Article/details/gtoznoaker.html

Py:   print("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gtjkgdncbu.html

PHP:  echo "Hello, World!";
来源：http://dali.svipenyu.cn/Article/details/gtnjhcmthc.html

JS:   console.log("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gtpxcctifr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hammf.cn/Article/details/gtccguypsw.html

Java: System.out.println("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gtwgvifokg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdegumnw.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258888.top/Article/details/gtmjpbrtvj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gtnwjxwmam.html

[A02] 变量声明与赋值
来源：http://dali.yuanzhike.top/Article/details/gtcvaelmwx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhiwuduotai.top/Article/details/gtbrdouzub.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtcduhitcq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtmgkjvlms.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtipxaertv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gtlwcfioet.html

Go:   name := "Alex"; age := 20
来源：http://dali.tian-w.cn/Article/details/gteopafmkk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sysykeji.top/Article/details/gtdranhztv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtzswnxjhr.html

[A03] 常量定义
来源：http://dali.yuanzhike.top/Article/details/gtdwxvkzbe.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yonumen.top/Article/details/gtdhucbieb.html

PHP:  const PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtetpilgha.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtgacytprk.html

TS:   const PI: number = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtedptogum.html

Java: static final double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gthhgmstgs.html

Go:   const PI = 3.14159
来源：http://dali.fzhhl.top/Article/details/gtglbiqzss.html

Ruby: PI = 3.14159
来源：http://dali.jlsjyb.cn/Article/details/gtfjzsfrvt.html

C#:   const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtdyqabryi.html

[A04] 判断变量类型
来源：http://dali.ehwqpu.com/Article/details/gtrafmsntz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jqgfzy.top/Article/details/gtlpokrgey.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cdnleiting.top/Article/details/gtcpeiuyug.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.vqdsnc.cn/Article/details/gtmgyepmem.html

TS:   typeof x; x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gtponujkyc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.haohaochexian.top/Article/details/gtpffnlgoj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zycfv.cn/Article/details/gtxtztjraf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xuetiantiany.cn/Article/details/gtnwoqocyp.html

C#:   x.GetType().Name; x is int
来源：http://dali.aizwys.cn/Article/details/gtmoxcivgb.html

[A05] 整数除法与取模
来源：http://dali.feifeiyinyue.top/Article/details/gtdkpcttoi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tanke756.top/Article/details/gtwxhcqnuh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gtfwjbjfjd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gttefpyoun.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtxeiozhmx.html

Java: 7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtdtuueluz.html

Go:   7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gteinugygd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtknzmetwd.html

C#:   7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtdpxldybp.html

[A06] 字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtggyuqvjw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gthlldxsfs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.snrcjt.cn/Article/details/gttrrmtaez.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.pengpengdd.cyou/Article/details/gtmlxvirft.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gtqkxgdrmk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcekpsiid.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ehwqpu.com/Article/details/gtpyxsjgge.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hnxiangtu.top/Article/details/gthucshevx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinqigufen.top/Article/details/gtitpkbnnd.html

[A07] 数字转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtbbdwbztu.html

Py:   str(42)
来源：http://dali.cheryme.top/Article/details/gtkgjnevhv.html

PHP:  (string) 42; strval(42)
来源：http://dali.yanxiufei.cn/Article/details/gtejjwptau.html

JS:   String(42); (42).toString()
来源：http://dali.dianchejie.cn/Article/details/gtzznormkj.html

TS:   String(42)
来源：http://dali.ppjwa.cn/Article/details/gttolfedfp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shuidangran.top/Article/details/gtuwlkhkpv.html

Go:   strconv.Itoa(42)
来源：http://dali.feifeiyinyue.top/Article/details/gtlmzvfgkb.html

Ruby: 42.to_s
来源：http://dali.yueranfly.top/Article/details/gttxmhfdgc.html

C#:   42.ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtmmnzudas.html

[A08] 取整与四舍五入
来源：http://dali.yuxming.cn/Article/details/gtqpdkwucu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gtlxuxfmgs.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tanke756.top/Article/details/gtmtuuiptt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gttiotjhyd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jyoumei.cn/Article/details/gtifsgakgt.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yj202588.top/Article/details/gtmtuwncnz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtzqjgswug.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shzxlz.cn/Article/details/gtqfviqkbj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gtxlkcviac.html

[A09] 绝对值与最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gtnyaedaux.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtlcitvlqz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtxnftrswd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtgcyptuwi.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtkfzhxrmp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258888.top/Article/details/gticpycdjz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.havefunace.top/Article/details/gtxzqgbonm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.dianchejie.cn/Article/details/gtqvazhudv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtfzqixwus.html

[A10] 生成随机数
来源：http://dali.9152youxi.cn/Article/details/gtenqbwxmn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shangyingyoupin.top/Article/details/gtjakhdmaa.html

PHP:  random_int(1, 100);
来源：http://dali.chenzaomai.com/Article/details/gtnvberjat.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhiwuduotai.top/Article/details/gtroxiuocv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guannengcc.top/Article/details/gtbecleito.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hywenlv.cn/Article/details/gtgcwdnxlf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cucudq.cn/Article/details/gtfvwrehta.html

Ruby: rand(1..100)
来源：http://dali.smart0.xyz/Article/details/gtocevrfrm.html

C#:   new Random().Next(1, 101)
来源：http://dali.aizwys.cn/Article/details/gtgnjcjzae.html

[A11] 条件表达式（三元）
来源：http://dali.jlsjyb.cn/Article/details/gtdclgwrmp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinqigfzy.top/Article/details/gtglaahhqk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gtwmhbhtpo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gtllpspmpi.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtzscwgzoe.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gtvpdhpvzy.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.tanke756.top/Article/details/gtzcwdlxwp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gtkflbyjey.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gtabebqrjw.html

[A12] 字符串插值 / 格式化
来源：http://dali.c1oappe.top/Article/details/gthnwzzyzw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yuanzhike.top/Article/details/gtavqpyqcd.html


<!-- 参考信息 -->