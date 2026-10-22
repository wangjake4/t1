代发 wailian999

[U79] PHP：静态分析
来源：http://dali.smart0.xyz/Article/details/gtvjqnzluo.html

composer require --dev phpstan/phpstan
来源：http://dali.gzhubu.top/Article/details/gtxpyqetiz.html

[U80] PHP：代码规范修复
来源：http://dali.sysykeji.top/Article/details/gtebgdcvnp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258.top/Article/details/gthnpsvypz.html

[U81] JS：初始化项目
来源：http://dali.quarkkingdee.top/Article/details/gtwaggzpnb.html

npm init -y;  npm i express
来源：http://dali.fengsongda.top/Article/details/gtcqpmsajx.html

[U82] JS：package.json 脚本
来源：http://dali.0kj1m.cn/Article/details/gtcfugsuva.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yonumen.top/Article/details/gtfkjrukoz.html

[U83] JS：ES Module 导入导出
来源：http://dali.0kj1m.cn/Article/details/gtxhakvtxn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gthapqguqu.html

[U84] JS：CommonJS 写法
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwswjhue.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.birdmap.top/Article/details/gtotjjrkqg.html

[U85] JS：可选链
来源：http://dali.jinqigufen.top/Article/details/gtboidwfmi.html

a?.b?.c
来源：http://dali.svipenyu.cn/Article/details/gtqmybtzke.html

[U86] JS：空值合并
来源：http://dali.zycfv.cn/Article/details/gtsdsstrft.html

a ?? b
来源：http://dali.yueranfly.top/Article/details/gtabeswryf.html

[U87] JS：解构默认值
来源：http://dali.yonumen.top/Article/details/gtzojkysnz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.meibo888.top/Article/details/gteetziuzs.html

[U88] JS：对象展开合并
来源：http://dali.hongshengwenyu.top/Article/details/gthyrfemss.html

{ ...a, ...b }
来源：http://dali.zhixingplan.top/Article/details/gtxpnhyfwv.html

[U89] JS：数组去重
来源：http://dali.gaohongyu789.top/Article/details/gthjwsbimv.html

[...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtkovzjgax.html

[U90] JS：数字数组排序
来源：http://dali.jinqigufen.top/Article/details/gtajcussct.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtezusxrup.html

[U91] JS：对象键值遍历
来源：http://dali.redwolf501.top/Article/details/gtfrtnuful.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pycfn.com/Article/details/gtxtfbkena.html

[U92] JS：深拷贝
来源：http://dali.zdqjudy.top/Article/details/gthqgolxrl.html

structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtijynqjyg.html

[U93] JS：模板字符串
来源：http://dali.yvedp.cn/Article/details/gtooagsyir.html

`共 ${n} 条`
来源：http://dali.sufxvd.cn/Article/details/gtdpnknmlk.html

[U94] JS：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gtccjzmbvm.html

const double = x => x * 2;
来源：http://dali.ivvv.top/Article/details/gtzorahkrk.html

[U95] JS：Promise 包装
来源：http://dali.svipenyu.cn/Article/details/gtsbrvpusw.html

new Promise((resolve, reject) => {})
来源：http://dali.hnxiangtu.top/Article/details/gtluggzgtf.html

[U96] JS：async/await 与异常
来源：http://dali.kuanghao11.cn/Article/details/gtibefaiop.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtlapzzfjw.html

[U97] JS：并发请求
来源：http://dali.sxryk.cn/Article/details/gtyzmnxnoc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtitakuxed.html

[U98] JS：fetch 带 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtyygcimfx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sufxvd.cn/Article/details/gtvhzdgkfq.html

[U99] JS：事件监听
来源：http://dali.birdmap.top/Article/details/gtoyqvvzhb.html

el.addEventListener("click", e => {})
来源：http://dali.jiagoushi.top/Article/details/gtvojqeizy.html

[U100] JS：DOM 查询
来源：http://dali.yuxming.cn/Article/details/gtjsyaxqss.html

document.querySelector(".item")
来源：http://dali.daxiang520.top/Article/details/gtjjeamxmq.html

[U101] JS：classList 操作
来源：http://dali.iojbl.cn/Article/details/gtmlcvyded.html

el.classList.toggle("active")
来源：http://dali.jinqigfzy.top/Article/details/gtpjsjhsab.html

[U102] JS：本地存储
来源：http://dali.tian-w.cn/Article/details/gthwhalpfk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gaohongyu789.top/Article/details/gtydmcnjqg.html

[U103] JS：定时器
来源：http://dali.ybcxt.top/Article/details/gtkirkxyje.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258.top/Article/details/gtjbqviulz.html

[U104] JS：防抖
来源：http://dali.nanxinkj.top/Article/details/gtuopifspu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtjzzyswno.html

[U105] JS：节流
来源：http://dali.tanke756.top/Article/details/gtsfldjaji.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtmhqzgyvn.html

[U106] JS：日期格式化
来源：http://dali.fzhhl.top/Article/details/gtgpxkfpff.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ppjwa.cn/Article/details/gtmxnbzygb.html

[U107] JS：数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gtnlpjfgmx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtojzkxnnn.html

[U108] JS：随机整数
来源：http://dali.xinyue.icu/Article/details/gtnucpbdre.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jlsjyb.cn/Article/details/gtnzqvklxr.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtnfkgnodo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gtrmawobse.html

[U110] JS：数组分块
来源：http://dali.havefunace.top/Article/details/gtlgtxlivh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sysykeji.top/Article/details/gtthkmezxq.html

[U111] JS：对象转 Map
来源：http://dali.pengpengdd.cyou/Article/details/gtwtypyzaf.html

new Map(Object.entries(obj))
来源：http://dali.hywenlv.cn/Article/details/gtyozyyrap.html

[U112] JS：字符串补位
来源：http://dali.yvedp.cn/Article/details/gtdjeuimfp.html

"7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtgivphiat.html

[U113] JS：正则替换全部
来源：http://dali.9152youxi.cn/Article/details/gtieqboyqu.html

s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtfhjklbmh.html

[U114] JS：JSON 深比较
来源：http://dali.meibo888.top/Article/details/gtvcbzmywk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gtzyzflbzu.html

[U115] JS：生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtfabslzfx.html

crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtahthxoqx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhongyouzk.top/Article/details/gtbklcplpy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tian-w.cn/Article/details/gtzzrmfmhb.html

[U117] JS：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gtmnkjagih.html

npm i -D vitest;  npx vitest
来源：http://dali.ybcxt.top/Article/details/gtygyllrdq.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbhftlgl.html

npm i -D vite;  npx vite
来源：http://dali.shzxlz.cn/Article/details/gthufdktvc.html

[U119] JS：生产构建
来源：http://dali.vqdsnc.cn/Article/details/gttsqpwddg.html

npx vite build
来源：http://dali.yangfankeji.com/Article/details/gtumllzlzo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yvedp.cn/Article/details/gtnorpcurr.html

import.meta.env.VITE_API_URL
来源：http://dali.haohaochexian.top/Article/details/gtwmzmihgd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdsbdbjxi.html

统计汇总
来源：http://dali.fengsongda.top/Article/details/gtwnhmwyxx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtryvntezu.html

按语言统计（条）：
来源：http://dali.iojbl.cn/Article/details/gtjqbqrtvf.html

Python ......... 252
来源：http://dali.chenlongwang.top/Article/details/gtluhmarzh.html

PHP ............ 252
来源：http://dali.zdqjudy.top/Article/details/gthvkrkksm.html

JavaScript ..... 252
来源：http://dali.0kj1m.cn/Article/details/gtvommnjdi.html

TypeScript ..... 212
来源：http://dali.andypj.xyz/Article/details/gttgyhjbzt.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtulhsuowf.html

Go ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtbqnxfxvx.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gtobypldvb.html

C# ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gtyaopoktg.html

C .............. 30
来源：http://dali.zhongyouzk.top/Article/details/gthgohgtza.html

C++ ............ 30
来源：http://dali.316326.xyz/Article/details/gtupgijcpd.html

SQL ............ 90
来源：http://dali.shangyingyoupin.top/Article/details/gtiexjyplz.html

Bash ........... 80
来源：http://dali.cdnleiting.top/Article/details/gtnarwvlcs.html

Kotlin ......... 15
来源：http://dali.xylfe.cn/Article/details/gtcizqdanj.html

Swift .......... 15
来源：http://dali.iojbl.cn/Article/details/gtlpirbawg.html

Lua ............ 10
来源：http://dali.chenlongwang.top/Article/details/gtxubobzvt.html

Perl ........... 10
来源：http://dali.gaohongyu789.top/Article/details/gtuhabzfmb.html

Scala .......... 10
来源：http://dali.yj20258.top/Article/details/gtoualwdbn.html

------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtamscqkct.html

合计 ........... 2106 条
来源：http://dali.shzxlz.cn/Article/details/gtewodjinn.html

按章节统计：
来源：http://dali.cdnleiting.top/Article/details/gtolumyqus.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yonumen.top/Article/details/gtqnfddpyo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtapaosfot.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gtpodutaym.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.pengpengdd.cyou/Article/details/gtarwldzgg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.316326.xyz/Article/details/gtyqiynlhl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gtrkjvnwto.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gttezkxkjk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhongyouzk.top/Article/details/gthyaaelqt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtxxfbagrj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqfefukg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtzcvhjuop.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtlnvfgevg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtwdoiljgv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gtveccnhjk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangtech.top/Article/details/gtakyrzhpa.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtlykdncmg.html

Q SQL 专题                              90
来源：http://dali.guowangkeji.top/Article/details/gtchbwycne.html

R Bash 专题                             80
来源：http://dali.sysykeji.top/Article/details/gtqskdyjjz.html

S C / C++ 专题                          60
来源：http://dali.nanxinkj.top/Article/details/gtqauyfpvm.html

T 其他语言补充                          60
来源：http://dali.wangshuangyany.cn/Article/details/gtmiaecfew.html

U 高频实用片段                         120
来源：http://dali.ivvv.top/Article/details/gtqwifsizr.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gttcjhcjzv.html

合计                                  2106 条
来源：http://dali.yj20258.top/Article/details/gtjxvjglpd.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gttpjeoqej.html

使用提醒
来源：http://dali.ehwqpu.com/Article/details/gtfttqolcw.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gtroocbayt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xziqi.cn/Article/details/gthnytywnf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuetiantiany.cn/Article/details/gtzdihuwde.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigfzy.top/Article/details/gtbkwjeunm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xylfe.cn/Article/details/gtgvwrxniq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zdqjudy.top/Article/details/gttpfocxmn.html

—— 文件结束 ——
来源：http://dali.xylfe.cn/Article/details/gtfkvgberw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkgmhklgq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenjidiqi.icu/Article/details/gtcuyxwsif.html

Common Programming Examples Cheat Book
来源：http://dali.hammf.cn/Article/details/gtkbhvzhsk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtyekrkydj.html

【收录内容】
来源：http://dali.gaohongyu789.top/Article/details/gtmfgotyet.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jiagoushi.top/Article/details/gtzqeokzfu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhengqikj.top/Article/details/gticqxmrqu.html

SQL · Bash · C · C++
来源：http://dali.c1oappe.top/Article/details/gtbzyumbar.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sufxvd.cn/Article/details/gtzgsmzlkx.html

【使用说明】
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrqbkmqf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yongpay.top/Article/details/gtxeglqmyd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.fzhhl.top/Article/details/gtoamliqmn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.vqdsnc.cn/Article/details/gtxcobqdgj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ehwqpu.com/Article/details/gtmiboxuzf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvhydokn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nanxuanxn.top/Article/details/gtjandccvn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhongyouzk.top/Article/details/gtqvghigeb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuetiantiany.cn/Article/details/gtskmvuzwd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgufenzy.top/Article/details/gtsuzkoics.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tian-w.cn/Article/details/gtljcyzdos.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yongpay.top/Article/details/gtqzbqcwyu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenzaomai.com/Article/details/gtnwhphstt.html

【文件统计】
来源：http://dali.yj202588.top/Article/details/gtnmnwlkpa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.daxiang520.top/Article/details/gteegwqiue.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gtsvwvewuq.html

目  录
来源：http://dali.yueranfly.top/Article/details/gtzjvejvxl.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtuiqarwbm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gtihpfdlaj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtioawftph.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gtgixqfheb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtecxfgsbg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinqigfzy.top/Article/details/gtfwbuqkrf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxahkhuo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtgoyqbnvl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj20258.top/Article/details/gtdahageaz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtccenzisr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.wangdashe.top/Article/details/gtdpiojaat.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtfkdkcnzq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtpozsdwnn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzrftmse.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtbnebpxln.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hongshengwenyu.top/Article/details/gthjnjdldr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtnvwtjijw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtdpmrtkdf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tianlin.xyz/Article/details/gtahmulbgq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.kuanghao11.cn/Article/details/gtfpsrhsba.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtiklklnuh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gtscejawav.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqtaussox.html

A. 基础语法与类型
来源：http://dali.9152youxi.cn/Article/details/gtezweeonh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnbkglpqm.html

[A01] Hello World
来源：http://dali.andypj.xyz/Article/details/gtcofcglol.html

Py:   print("Hello, World!")
来源：http://dali.fengsongda.top/Article/details/gtmxnpayjh.html

PHP:  echo "Hello, World!";
来源：http://dali.quarkkingdee.top/Article/details/gtfvuswbps.html

JS:   console.log("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gttvkkzxfe.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ehwqpu.com/Article/details/gttvcudmpc.html

Java: System.out.println("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gtzsmsmaim.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gtzsicsbym.html

Ruby: puts "Hello, World!"
来源：http://dali.0kj1m.cn/Article/details/gtohdqtrpv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gtsqjuozyk.html

[A02] 变量声明与赋值
来源：http://dali.jqgfzy.top/Article/details/gtysdakodw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yongpay.top/Article/details/gtvamldpoi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gzhubu.top/Article/details/gtwqgfnryp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gtuslsbmhk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.havefunace.top/Article/details/gtxxdlyxdz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtkcajpdyn.html

Go:   name := "Alex"; age := 20
来源：http://dali.jqgfzy.top/Article/details/gtrmshcmha.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yangfankeji.com/Article/details/gtizrputfv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.wangdashe.top/Article/details/gtnnolvfkx.html

[A03] 常量定义
来源：http://dali.feifeiyinyue.top/Article/details/gtlnzfvgmt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shuidangran.top/Article/details/gtayyiygmq.html

PHP:  const PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gttckfyulb.html

JS:   const PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtivpuflsi.html

TS:   const PI: number = 3.14159;
来源：http://dali.hammf.cn/Article/details/gteihpwllz.html

Java: static final double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtcrenaumr.html

Go:   const PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gteodghrvs.html

Ruby: PI = 3.14159
来源：http://dali.quarkkingdee.top/Article/details/gtbonqlsnc.html

C#:   const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtdtsixjth.html

[A04] 判断变量类型
来源：http://dali.jinghuilouyu.cn/Article/details/gterlwxvvp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guannengcc.top/Article/details/gtxmrxhhfi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hysaishi.cn/Article/details/gtffacsppc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gtrstfxobi.html

TS:   typeof x; x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gtboymurvv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tianlin.xyz/Article/details/gtpbjgdzen.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yj20258.top/Article/details/gtsvgyjaoo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gtxkndnrzp.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinqigfzy.top/Article/details/gtlyymcxwl.html

[A05] 整数除法与取模
来源：http://dali.jianghu66.top/Article/details/gtsdiuyzzf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.haohaochexian.top/Article/details/gtufztxyhb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gtkkgopcdl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtbxjwcpvl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtomcrwefi.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtitoffabm.html

Go:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtmjvfjbnw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtbrikbmty.html

C#:   7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtzlpjhyrt.html

[A06] 字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtskljfixc.html

Py:   int("42"); float("3.14")
来源：http://dali.fzhhl.top/Article/details/gtffhmtbrf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagdndaxg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gtwbspsjrs.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hfpthk.cn/Article/details/gtgbpuyupe.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gtlopuvgon.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zdqjudy.top/Article/details/gthwrkoodh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhoulong.xyz/Article/details/gthuiuaqgg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258888.top/Article/details/gtwfmkbpex.html

[A07] 数字转字符串
来源：http://dali.chenlongwang.top/Article/details/gtihplusrg.html

Py:   str(42)
来源：http://dali.zhixingplan.top/Article/details/gtnhptjder.html

PHP:  (string) 42; strval(42)
来源：http://dali.redwolf501.top/Article/details/gtvmlyrdml.html

JS:   String(42); (42).toString()
来源：http://dali.fzhhl.top/Article/details/gtjccbpfef.html

TS:   String(42)
来源：http://dali.sweek.top/Article/details/gtyxmeyaug.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cqqwz.cn/Article/details/gtvwsnltaz.html

Go:   strconv.Itoa(42)
来源：http://dali.fzhhl.top/Article/details/gtbnpslwdy.html

Ruby: 42.to_s
来源：http://dali.andypj.xyz/Article/details/gtezyxyulz.html

C#:   42.ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtbrhkrtyz.html

[A08] 取整与四舍五入
来源：http://dali.dianchejie.cn/Article/details/gtiejfuzop.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gtzhxfhhfm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.iojbl.cn/Article/details/gtvqkwptsu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gthceimsyv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ydzc1.top/Article/details/gtcjbbhcmk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gteiqxpuve.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtzlavlioj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yongpay.top/Article/details/gtivsjxeyi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yonumen.top/Article/details/gtemhsoljv.html

[A09] 绝对值与最大最小值
来源：http://dali.chenzaomai.com/Article/details/gtswybdbdy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtlxdfsrpo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aizwys.cn/Article/details/gthecijvvv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtnumrjvmz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtwttxrsdo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtfycfeofy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ybcxt.top/Article/details/gtjzufwoos.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.fengsongda.top/Article/details/gtkbjrgjrn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtaxceuvpy.html

[A10] 生成随机数
来源：http://dali.cdnleiting.top/Article/details/gtcdspgawq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xziqi.cn/Article/details/gtygvksnyv.html

PHP:  random_int(1, 100);
来源：http://dali.yj202588.top/Article/details/gtuemswwll.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hnqzz.top/Article/details/gthunhghdt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cqqwz.cn/Article/details/gtkuigakzx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.shzxlz.cn/Article/details/gtgmvajarm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yonumen.top/Article/details/gtsopbzegq.html

Ruby: rand(1..100)
来源：http://dali.nanxuanxn.top/Article/details/gtcremkhfx.html

C#:   new Random().Next(1, 101)
来源：http://dali.fzhhl.top/Article/details/gtjfwfyvyt.html

[A11] 条件表达式（三元）
来源：http://dali.yj202588.top/Article/details/gtziiuizum.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tianlin.xyz/Article/details/gtakjdvcsy.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gtrxdslzct.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtubnkemsz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gttgdrrlyq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gtxlcffgqt.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hongshengwenyu.top/Article/details/gtelococca.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtbfqkhcyi.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gtixxlxspo.html

[A12] 字符串插值 / 格式化
来源：http://dali.yj20258888.top/Article/details/gtsciqxmwl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gotoacloud.top/Article/details/gtnoixatgo.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yj20258888.top/Article/details/gtrflpceya.html

JS:   `Hello, ${name}!`
来源：http://dali.ybcxt.top/Article/details/gtfrsixwsk.html

TS:   `Hello, ${name}!`
来源：http://dali.fzhhl.top/Article/details/gthytuiyny.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.tanke756.top/Article/details/gtpzrfdryj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.0kj1m.cn/Article/details/gtonmuewwy.html

Ruby: "Hello, #{name}!"
来源：http://dali.dianchejie.cn/Article/details/gtyeydnojc.html

C#:   $"Hello, {name}!"
来源：http://dali.tian-w.cn/Article/details/gtizlvggxy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqwfmtxd.html


<!-- 参考信息 -->