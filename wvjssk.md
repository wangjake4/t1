代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.hnqzz.top/Article/details/gt2jazuulej.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gt2vevhereo.html

[U84] JS：CommonJS 写法
来源：http://dali.yj202588.top/Article/details/gt2peqhwvdy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zdqjudy.top/Article/details/gt2dsqecywk.html

[U85] JS：可选链
来源：http://dali.jinghuilouyu.cn/Article/details/gt2azbmantz.html

a?.b?.c
来源：http://dali.hfpthk.cn/Article/details/gt2hxhpykqq.html

[U86] JS：空值合并
来源：http://dali.jinqigfzy.top/Article/details/gt2tlkrhweq.html

a ?? b
来源：http://dali.ivvv.top/Article/details/gt2dqovmbrf.html

[U87] JS：解构默认值
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdgecfdu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnxiangtu.top/Article/details/gt2ojohppve.html

[U88] JS：对象展开合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pajkdvpw.html

{ ...a, ...b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqgqfoho.html

[U89] JS：数组去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ynjoxftk.html

[...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gt2uqqfyjed.html

[U90] JS：数字数组排序
来源：http://dali.hnxiangtu.top/Article/details/gt2jejokqie.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gt2rgtupsja.html

[U91] JS：对象键值遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2tcxvwysb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zycfv.cn/Article/details/gt2ndbozzvf.html

[U92] JS：深拷贝
来源：http://dali.quarkkingdee.top/Article/details/gt2wqaemomv.html

structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gt2upaxktpk.html

[U93] JS：模板字符串
来源：http://dali.daria6918.cn/Article/details/gt2fgojxhke.html

`共 ${n} 条`
来源：http://dali.guowangkeji.top/Article/details/gt2lesgybqf.html

[U94] JS：箭头函数
来源：http://dali.shuidangran.top/Article/details/gt2pktwhkmo.html

const double = x => x * 2;
来源：http://dali.shuidangran.top/Article/details/gt2bkyyifoj.html

[U95] JS：Promise 包装
来源：http://dali.yangfankeji.com/Article/details/gt2ygyxorng.html

new Promise((resolve, reject) => {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2rctmysxe.html

[U96] JS：async/await 与异常
来源：http://dali.sweek.top/Article/details/gt2xstdhukd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2abamppcp.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxvbcutn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2gekkjlln.html

[U98] JS：fetch 带 JSON
来源：http://dali.cheryme.top/Article/details/gt2lygzhyss.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gogol.net.cn/Article/details/gt2czwsswvx.html

[U99] JS：事件监听
来源：http://dali.sufxvd.cn/Article/details/gt2qaquhsfq.html

el.addEventListener("click", e => {})
来源：http://dali.ydzc1.top/Article/details/gt2psffattj.html

[U100] JS：DOM 查询
来源：http://dali.guannengcc.top/Article/details/gt2pgpeetlx.html

document.querySelector(".item")
来源：http://dali.zhixingplan.top/Article/details/gt2mtbpesys.html

[U101] JS：classList 操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvmiregu.html

el.classList.toggle("active")
来源：http://dali.ydzc1.top/Article/details/gt2iamquhwk.html

[U102] JS：本地存储
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqrqxamn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuanzx.com/Article/details/gt2jxijijzb.html

[U103] JS：定时器
来源：http://dali.jyoumei.cn/Article/details/gt2qbdqvvcy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zycfv.cn/Article/details/gt2hvbtitgj.html

[U104] JS：防抖
来源：http://dali.birdmap.top/Article/details/gt2kvphpwpc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxlnzwdi.html

[U105] JS：节流
来源：http://dali.haohaochexian.top/Article/details/gt2bynrjgcn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhoulong.xyz/Article/details/gt2xhbsgyib.html

[U106] JS：日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2mebnnyyr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuanzx.com/Article/details/gt2kmehnyzf.html

[U107] JS：数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2byojfdpt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gt2ooranukx.html

[U108] JS：随机整数
来源：http://dali.hongshengwenyu.top/Article/details/gt2irlxilge.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xylfe.cn/Article/details/gt2wahpvroa.html

[U109] JS：数组分组
来源：http://dali.yj20258.top/Article/details/gt2wqsbaahz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gt2pqskrlzt.html

[U110] JS：数组分块
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpamcgnj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjgdktsy.html

[U111] JS：对象转 Map
来源：http://dali.feifeiyinyue.top/Article/details/gt2owrxrxcm.html

new Map(Object.entries(obj))
来源：http://dali.chenlongwang.top/Article/details/gt2qoibdozg.html

[U112] JS：字符串补位
来源：http://dali.jinqigfzy.top/Article/details/gt2trugukti.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2onksgkyj.html

[U113] JS：正则替换全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sabpalaf.html

s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2qfacevik.html

[U114] JS：JSON 深比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcwpkrth.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2aawgdhxv.html

[U115] JS：生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gt2paaatvvd.html

crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gt2jppcoomm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hfpthk.cn/Article/details/gt2tggrxbxq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sweek.top/Article/details/gt2stgovwrb.html

[U117] JS：单元测试
来源：http://dali.cheryme.top/Article/details/gt2gkolnuua.html

npm i -D vitest;  npx vitest
来源：http://dali.shzxlz.cn/Article/details/gt2wwzpotwj.html

[U118] JS：开发服务器
来源：http://dali.xinyue.icu/Article/details/gt2xsssiqgb.html

npm i -D vite;  npx vite
来源：http://dali.jianghu66.top/Article/details/gt2vhrsjton.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gt2ebwzgcga.html

npx vite build
来源：http://dali.gogol.net.cn/Article/details/gt2tavyhzoe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.redwolf501.top/Article/details/gt2qtkqhgyu.html

import.meta.env.VITE_API_URL
来源：http://dali.xuanzx.com/Article/details/gt2ydwdcuiy.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2dabihxjc.html

统计汇总
来源：http://dali.aibaodan.cn/Article/details/gt2sojqdfel.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2xccodouy.html

按语言统计（条）：
来源：http://dali.haohaochexian.top/Article/details/gt2itictmkv.html

Python ......... 252
来源：http://dali.yueranfly.top/Article/details/gt2ilbpokil.html

PHP ............ 252
来源：http://dali.sweek.top/Article/details/gt2qdqqjqej.html

JavaScript ..... 252
来源：http://dali.jlsjyb.cn/Article/details/gt2cururrne.html

TypeScript ..... 212
来源：http://dali.yj20258.top/Article/details/gt2kokggajd.html

Java ........... 212
来源：http://dali.yangfankeji.com/Article/details/gt2uaiquhsa.html

Go ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcsgzfsh.html

Ruby ........... 212
来源：http://dali.0kj1m.cn/Article/details/gt2immbupvp.html

C# ............. 212
来源：http://dali.svipenyu.cn/Article/details/gt2anytqhqe.html

C .............. 30
来源：http://dali.meibo888.top/Article/details/gt2uijwbbol.html

C++ ............ 30
来源：http://dali.zhengqikj.top/Article/details/gt2gereaurv.html

SQL ............ 90
来源：http://dali.chenzaomai.com/Article/details/gt2zozesfgo.html

Bash ........... 80
来源：http://dali.yj20258.top/Article/details/gt2wybnofmd.html

Kotlin ......... 15
来源：http://dali.ivvv.top/Article/details/gt2lgzhvjwy.html

Swift .......... 15
来源：http://dali.smart0.xyz/Article/details/gt2gkhfyzia.html

Lua ............ 10
来源：http://dali.tanke756.top/Article/details/gt2vmchwwnr.html

Perl ........... 10
来源：http://dali.cqqwz.cn/Article/details/gt2acdqelyk.html

Scala .......... 10
来源：http://dali.yvedp.cn/Article/details/gt2wgjtlqkg.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gt2hndqgppq.html

合计 ........... 2106 条
来源：http://dali.dashuyun.cn/Article/details/gt2bvdoafcp.html

按章节统计：
来源：http://dali.jqgfzy.top/Article/details/gt2rziqgfki.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gt2dcnettmn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hfpthk.cn/Article/details/gt2cylnnuha.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gt2ciyjoech.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gt2qtpaihwz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcxblnuu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gt2ehehpmgd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gt2mkgfomve.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gt2hsyknmev.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwkajdwn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.mhx1999.top/Article/details/gt2nqksrrgf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gt2ouitugrv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2cpnlxrmw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gt2ccwkpgyx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zdqjudy.top/Article/details/gt2cauggqwg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.aizwys.cn/Article/details/gt2amjmpumi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gt2jfiiouxz.html

Q SQL 专题                              90
来源：http://dali.gzhubu.top/Article/details/gt2bljtwjqv.html

R Bash 专题                             80
来源：http://dali.jlsjyb.cn/Article/details/gt2yhtwtmug.html

S C / C++ 专题                          60
来源：http://dali.yangfankeji.com/Article/details/gt2hvffckgf.html

T 其他语言补充                          60
来源：http://dali.nanxuanxn.top/Article/details/gt2bokqnqjk.html

U 高频实用片段                         120
来源：http://dali.xylfe.cn/Article/details/gt2glypvsbg.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlsskrmx.html

合计                                  2106 条
来源：http://dali.shuidangran.top/Article/details/gt2fevjpski.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnbbihxf.html

使用提醒
来源：http://dali.shzxlz.cn/Article/details/gt2lfzrjzzb.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gt2eszydtvr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.vqdsnc.cn/Article/details/gt2qhywfvjb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.havefunace.top/Article/details/gt2tlcfanbl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.aibaodan.cn/Article/details/gt2cwfjxrfe.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yonumen.top/Article/details/gt2komzswry.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxuanxn.top/Article/details/gt2wxiptujr.html

—— 文件结束 ——
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpptakym.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2zsuqbnhq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jqgfzy.top/Article/details/gt2xenaazha.html

Common Programming Examples Cheat Book
来源：http://dali.meibo888.top/Article/details/gt2olsdfczd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2qxaztucc.html

【收录内容】
来源：http://dali.yangfankeji.com/Article/details/gt2iwmqfmmq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xinyue.icu/Article/details/gt2lmblrzyf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.nanxinkj.top/Article/details/gt2urpbeyst.html

SQL · Bash · C · C++
来源：http://dali.zycfv.cn/Article/details/gt2ofydgthj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.0kj1m.cn/Article/details/gt2xgrzowoa.html

【使用说明】
来源：http://dali.tian-w.cn/Article/details/gt2qiqfwzgf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuanzhike.top/Article/details/gt2zachccpl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.havefunace.top/Article/details/gt2zhpsilxt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinqigfzy.top/Article/details/gt2totemysx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.svipenyu.cn/Article/details/gt2nrmqvnas.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.pengpengdd.cyou/Article/details/gt2mixkgcza.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenzaomai.com/Article/details/gt2iqlnxdww.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cdnleiting.top/Article/details/gt2rqckntwf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.quarkkingdee.top/Article/details/gt2dwibqhzp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hfpthk.cn/Article/details/gt2pkrwqlor.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nanxuanxn.top/Article/details/gt2xydwtwie.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnqzz.top/Article/details/gt2utlhaozz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xylfe.cn/Article/details/gt2jfymbsug.html

【文件统计】
来源：http://dali.vqdsnc.cn/Article/details/gt2dgvhdnmi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinqigfzy.top/Article/details/gt2walirpyv.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gt2sxffosux.html

目  录
来源：http://dali.jqgufenzy.top/Article/details/gt2jaqapuzd.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2agshfrpn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnapkosx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tianlin.xyz/Article/details/gt2oiuvcqlo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkfxgfmf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuanzx.com/Article/details/gt2qfmfveja.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yonumen.top/Article/details/gt2oklrzjaf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.havefunace.top/Article/details/gt2bzwgudrb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gt2srloxbbt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnqzssvu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gt2vujyfhfw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gt2prixlqkp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gt2pztpuuxy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2wtzaetqp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gt2ertnvksq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2guuaytgj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.316326.xyz/Article/details/gt2mozedxkt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gt2lpyjdtfm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vwijmlov.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2qwzxrsae.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj202588.top/Article/details/gt2fbqjzepc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gt2ehtctdcc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yongpay.top/Article/details/gt2vxlzekgo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2hionkjju.html

A. 基础语法与类型
来源：http://dali.cdnleiting.top/Article/details/gt2pohvrdkx.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ekevdvvl.html

[A01] Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eppxmjen.html

Py:   print("Hello, World!")
来源：http://dali.nanxinkj.top/Article/details/gt2ojgltsbr.html

PHP:  echo "Hello, World!";
来源：http://dali.sysykeji.top/Article/details/gt2dugtajcw.html

JS:   console.log("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gt2pglhvisq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpeejqxn.html

Java: System.out.println("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gt2bpvemqqr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hnqzz.top/Article/details/gt2ehtsnail.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258888.top/Article/details/gt2qkusvyha.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sweek.top/Article/details/gt2krwvfjev.html

[A02] 变量声明与赋值
来源：http://dali.sysykeji.top/Article/details/gt2rsscbhby.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ppjwa.cn/Article/details/gt2hneawaki.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xziqi.cn/Article/details/gt2omoysvua.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvjpwft.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cheryme.top/Article/details/gt2mdjphqdt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shuidangran.top/Article/details/gt2atojjrfh.html

Go:   name := "Alex"; age := 20
来源：http://dali.ehwqpu.com/Article/details/gt2xrelbakj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sweek.top/Article/details/gt2phbpqqqw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2selaeytl.html

[A03] 常量定义
来源：http://dali.pycfn.com/Article/details/gt2zkfkxipu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.havefunace.top/Article/details/gt2zyekyvpx.html

PHP:  const PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2lvsklrfw.html

JS:   const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2oukypaxk.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2rnmujhkd.html

Java: static final double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2kspuvjkb.html

Go:   const PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gt2xleyoeki.html

Ruby: PI = 3.14159
来源：http://dali.dashuyun.cn/Article/details/gt2ccpysrvu.html

C#:   const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2xhvpmkgo.html

[A04] 判断变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usfohebj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yonumen.top/Article/details/gt2qiwthtak.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gzhubu.top/Article/details/gt2uzzuqdxc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukmgtngq.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhixingplan.top/Article/details/gt2wzohvsqu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.0kj1m.cn/Article/details/gt2zdxizloq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnxiangtu.top/Article/details/gt2evpwtwqe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cdnleiting.top/Article/details/gt2mpsvkaxg.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2uoadqnox.html

[A05] 整数除法与取模
来源：http://dali.sweek.top/Article/details/gt2zjyqghrs.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhengqikj.top/Article/details/gt2vpqljfmd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2asplatia.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2biddaqso.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gt2bhdmxgbd.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gt2vazwkhfo.html

Go:   7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gt2zpqaeplb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gt2ftkkdmow.html

C#:   7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gt2jdrvunsn.html

[A06] 字符串转数字
来源：http://dali.aizwys.cn/Article/details/gt2cwcoqonw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yptqtodw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gogol.net.cn/Article/details/gt2ieuwljgv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.haohaochexian.top/Article/details/gt2esrqapny.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnqzz.top/Article/details/gt2vsyffesb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gt2ntruomyo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guannengcc.top/Article/details/gt2pzshdodg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj20258.top/Article/details/gt2vsxkrjab.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzyzejhk.html

[A07] 数字转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2zzorxndl.html

Py:   str(42)
来源：http://dali.sysykeji.top/Article/details/gt2viaxfxso.html

PHP:  (string) 42; strval(42)
来源：http://dali.daria6918.cn/Article/details/gt2hqibygci.html

JS:   String(42); (42).toString()
来源：http://dali.birdmap.top/Article/details/gt2ipqvfrjn.html

TS:   String(42)
来源：http://dali.sxryk.cn/Article/details/gt2xdfhwcub.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.iojbl.cn/Article/details/gt2cgngmmih.html

Go:   strconv.Itoa(42)
来源：http://dali.tanke756.top/Article/details/gt2zsgyfznh.html

Ruby: 42.to_s
来源：http://dali.svipenyu.cn/Article/details/gt2xfjmdgci.html

C#:   42.ToString()
来源：http://dali.nanxuanxn.top/Article/details/gt2lfkmautm.html

[A08] 取整与四舍五入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kthmchpc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gt2jmbwdmyk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.guannengcc.top/Article/details/gt2jdgqtjlt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gt2grspreyx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangdashe.top/Article/details/gt2bgerijjz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gt2zkpuruhl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cashguo.top/Article/details/gt2kgwcjozs.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cheryme.top/Article/details/gt2eljhtwpw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dlsyxhpd.html

[A09] 绝对值与最大最小值
来源：http://dali.yuanzhike.top/Article/details/gt2nqoxjhdv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2eyuhpcyf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cashguo.top/Article/details/gt2isfaubne.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2fgrjfkss.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gt2titujnik.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2fgtoutdb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cdnleiting.top/Article/details/gt2ichyscsp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xziqi.cn/Article/details/gt2sgkypail.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2lrwgwypf.html

[A10] 生成随机数
来源：http://dali.zhoulong.xyz/Article/details/gt2pfudaonf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.aizwys.cn/Article/details/gt2dhuevyca.html

PHP:  random_int(1, 100);
来源：http://dali.birdmap.top/Article/details/gt2iswdyqtn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hammf.cn/Article/details/gt2gccmdvar.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jocozefw.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ehwqpu.com/Article/details/gt2nanvygtk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.tian-w.cn/Article/details/gt2hmdxhpfm.html

Ruby: rand(1..100)
来源：http://dali.sxryk.cn/Article/details/gt2yviiuxzm.html

C#:   new Random().Next(1, 101)
来源：http://dali.ybcxt.top/Article/details/gt2tuvjzgcr.html

[A11] 条件表达式（三元）
来源：http://dali.tian-w.cn/Article/details/gt2zjygkhoe.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ehwqpu.com/Article/details/gt2nvmqpqye.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjgujbfr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gt2yaswpfpa.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gt2dvvpxymd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gt2qptibtvs.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfywhmgq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkcvtzlp.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gt2uqowrdxb.html

[A12] 字符串插值 / 格式化
来源：http://dali.aizwys.cn/Article/details/gt2yjforewi.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yvedp.cn/Article/details/gt2xqloiyxa.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gogol.net.cn/Article/details/gt2bviozlde.html

JS:   `Hello, ${name}!`
来源：http://dali.yj202588.top/Article/details/gt2ykfirrgp.html

TS:   `Hello, ${name}!`
来源：http://dali.jinqigfzy.top/Article/details/gt2uhsiwxip.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.fengsongda.top/Article/details/gt2znzbuwsw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jyoumei.cn/Article/details/gt2odilfrap.html

Ruby: "Hello, #{name}!"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnibtxqd.html

C#:   $"Hello, {name}!"
来源：http://dali.hywenlv.cn/Article/details/gt2aqgoxhlm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2uppepzqj.html

Py:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gt2vkgjqvaj.html

PHP:  "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gt2tdcbcyis.html

JS:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gt2osgpemly.html

TS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2ubyqwwfk.html

Java: "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gt2fevyztnx.html

Go:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndejjofx.html

Ruby: "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gt2cwxubhmf.html

C#:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elifjgml.html


<!-- 参考信息 -->