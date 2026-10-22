代发 wailian999

[U81] JS：初始化项目
来源：http://dali.snrcjt.cn/Article/details/gtydrvbkiw.html

npm init -y;  npm i express
来源：http://dali.yvedp.cn/Article/details/gtfqhxefnn.html

[U82] JS：package.json 脚本
来源：http://dali.316326.xyz/Article/details/gtbeqfyhxb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xziqi.cn/Article/details/gtqpflsguf.html

[U83] JS：ES Module 导入导出
来源：http://dali.fengsongda.top/Article/details/gtyuzwjwhd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwstxoyd.html

[U84] JS：CommonJS 写法
来源：http://dali.pengpengdd.cyou/Article/details/gtrmwdhkwb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhoulong.xyz/Article/details/gtyfphonor.html

[U85] JS：可选链
来源：http://dali.jianghu66.top/Article/details/gtqnayxmll.html

a?.b?.c
来源：http://dali.jinqigfzy.top/Article/details/gtvzotzgex.html

[U86] JS：空值合并
来源：http://dali.yangfankeji.com/Article/details/gtixixdmki.html

a ?? b
来源：http://dali.sysykeji.top/Article/details/gteqjmdgbp.html

[U87] JS：解构默认值
来源：http://dali.nanxuanxn.top/Article/details/gttvymprfz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sxryk.cn/Article/details/gtbflhhaba.html

[U88] JS：对象展开合并
来源：http://dali.tian-w.cn/Article/details/gtqdlvihqi.html

{ ...a, ...b }
来源：http://dali.smart0.xyz/Article/details/gtumureepl.html

[U89] JS：数组去重
来源：http://dali.kuanghao11.cn/Article/details/gtpgzcyldk.html

[...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtjcdmsyzj.html

[U90] JS：数字数组排序
来源：http://dali.shuidangran.top/Article/details/gtvodedsiz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuufvszgm.html

[U91] JS：对象键值遍历
来源：http://dali.yj202588.top/Article/details/gtmhmxlgsy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cashguo.top/Article/details/gtvlzkwlfq.html

[U92] JS：深拷贝
来源：http://dali.fzhhl.top/Article/details/gtymiipfpw.html

structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtgxfkxrvl.html

[U93] JS：模板字符串
来源：http://dali.yueranfly.top/Article/details/gtyvmvfbse.html

`共 ${n} 条`
来源：http://dali.dianchejie.cn/Article/details/gttiikiuwb.html

[U94] JS：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gtqpabcdfd.html

const double = x => x * 2;
来源：http://dali.sufxvd.cn/Article/details/gtakmgmoyq.html

[U95] JS：Promise 包装
来源：http://dali.yj20258.top/Article/details/gtntbxveci.html

new Promise((resolve, reject) => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gthoruijkg.html

[U96] JS：async/await 与异常
来源：http://dali.xuetiantiany.cn/Article/details/gthqaktbyj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtaeovnzsc.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gtuuqumfev.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtdlusbkru.html

[U98] JS：fetch 带 JSON
来源：http://dali.nwbrower.top/Article/details/gtxhymomnv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zycfv.cn/Article/details/gtmlerrczw.html

[U99] JS：事件监听
来源：http://dali.hnxiangtu.top/Article/details/gtmkohwfdo.html

el.addEventListener("click", e => {})
来源：http://dali.haohaochexian.top/Article/details/gtaqygbxhw.html

[U100] JS：DOM 查询
来源：http://dali.andypj.xyz/Article/details/gtdiaqcdgv.html

document.querySelector(".item")
来源：http://dali.snrcjt.cn/Article/details/gtaxfnfogh.html

[U101] JS：classList 操作
来源：http://dali.316326.xyz/Article/details/gtebmiehcj.html

el.classList.toggle("active")
来源：http://dali.gaohongyu789.top/Article/details/gtfmovqgkl.html

[U102] JS：本地存储
来源：http://dali.zhengqikj.top/Article/details/gtimzoopus.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sweek.top/Article/details/gtprwdejgm.html

[U103] JS：定时器
来源：http://dali.yonumen.top/Article/details/gtyxcjgudm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenjidiqi.icu/Article/details/gtdddqmnhg.html

[U104] JS：防抖
来源：http://dali.0kj1m.cn/Article/details/gtjwpocgqr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtcqmdxwac.html

[U105] JS：节流
来源：http://dali.shuidangran.top/Article/details/gttkrldzzw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenzaomai.com/Article/details/gtqzftxcnc.html

[U106] JS：日期格式化
来源：http://dali.mhx1999.top/Article/details/gtomnggsvs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.kuanghao11.cn/Article/details/gtplsbtenv.html

[U107] JS：数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gtqfoasdzf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtzexkidor.html

[U108] JS：随机整数
来源：http://dali.smart0.xyz/Article/details/gtjsdhjcpq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcdhfynk.html

[U109] JS：数组分组
来源：http://dali.smart0.xyz/Article/details/gtsvxitrua.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtanqrofdg.html

[U110] JS：数组分块
来源：http://dali.cheryme.top/Article/details/gtjykwwtyr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yangfankeji.com/Article/details/gtdehrnapr.html

[U111] JS：对象转 Map
来源：http://dali.jianghu66.top/Article/details/gtdyhuyoqq.html

new Map(Object.entries(obj))
来源：http://dali.yj20258.top/Article/details/gtqkvkmjug.html

[U112] JS：字符串补位
来源：http://dali.jqgfzy.top/Article/details/gttbayfuzc.html

"7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtdsxlsfou.html

[U113] JS：正则替换全部
来源：http://dali.xuetiantiany.cn/Article/details/gtrjbdywgg.html

s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtbngtntko.html

[U114] JS：JSON 深比较
来源：http://dali.nanxuanxn.top/Article/details/gtwwalskvi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gtgjjozjbs.html

[U115] JS：生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gttdagjmpz.html

crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtccyrcwew.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hammf.cn/Article/details/gtcxhansjp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ydzc1.top/Article/details/gtkxnnyrww.html

[U117] JS：单元测试
来源：http://dali.jinqigufen.top/Article/details/gtbiyaccxx.html

npm i -D vitest;  npx vitest
来源：http://dali.ybcxt.top/Article/details/gtqndarqxm.html

[U118] JS：开发服务器
来源：http://dali.ydzc1.top/Article/details/gtsbdwnphy.html

npm i -D vite;  npx vite
来源：http://dali.cashguo.top/Article/details/gttkahncmc.html

[U119] JS：生产构建
来源：http://dali.hammf.cn/Article/details/gteugpkere.html

npx vite build
来源：http://dali.gaohongyu789.top/Article/details/gtkepqvhjq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenjidiqi.icu/Article/details/gtuqlkykye.html

import.meta.env.VITE_API_URL
来源：http://dali.yongpay.top/Article/details/gtrskilsnb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmzjljeyw.html

统计汇总
来源：http://dali.hfpthk.cn/Article/details/gtcoeikeer.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtuxqadhrt.html

按语言统计（条）：
来源：http://dali.havefunace.top/Article/details/gtszkrobjh.html

Python ......... 252
来源：http://dali.aizwys.cn/Article/details/gthznostiy.html

PHP ............ 252
来源：http://dali.wangshuangyany.cn/Article/details/gtjdxcyrrm.html

JavaScript ..... 252
来源：http://dali.yvedp.cn/Article/details/gtxeiubmmw.html

TypeScript ..... 212
来源：http://dali.wangdashe.top/Article/details/gtdajxlxpj.html

Java ........... 212
来源：http://dali.cqqwz.cn/Article/details/gtqijczwvh.html

Go ............. 212
来源：http://dali.hnqzz.top/Article/details/gtkytrwtby.html

Ruby ........... 212
来源：http://dali.jqgufenzy.top/Article/details/gtmzmeutjp.html

C# ............. 212
来源：http://dali.yuanzhike.top/Article/details/gtirrmwpwt.html

C .............. 30
来源：http://dali.hammf.cn/Article/details/gtugyjlakj.html

C++ ............ 30
来源：http://dali.yuxming.cn/Article/details/gtermkdsvh.html

SQL ............ 90
来源：http://dali.jianghu66.top/Article/details/gtyikveoru.html

Bash ........... 80
来源：http://dali.hywenlv.cn/Article/details/gtnphnfmpa.html

Kotlin ......... 15
来源：http://dali.jlsjyb.cn/Article/details/gtetkcwfqr.html

Swift .......... 15
来源：http://dali.zdqjudy.top/Article/details/gtiovggnte.html

Lua ............ 10
来源：http://dali.daria6918.cn/Article/details/gtxwucjslw.html

Perl ........... 10
来源：http://dali.0kj1m.cn/Article/details/gtqpxupcmc.html

Scala .......... 10
来源：http://dali.andypj.xyz/Article/details/gtcwgqwizc.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtsscvwhmr.html

合计 ........... 2106 条
来源：http://dali.smart0.xyz/Article/details/gtvszitchm.html

按章节统计：
来源：http://dali.sxryk.cn/Article/details/gtppbjoeiy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gteskqiimn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtrkdyxema.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gtklaznshc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fengsongda.top/Article/details/gtogvfnerv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xinyue.icu/Article/details/gtsxstrpqz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gttfiltznt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gttcpttllq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaezcjkz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtvukizapp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.kuanghao11.cn/Article/details/gtzykjuknx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtpdwoucec.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtbykcphlf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtciixktjq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gtmhudokpp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hnxiangtu.top/Article/details/gtiwxusayw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtbkkztcwv.html

Q SQL 专题                              90
来源：http://dali.sxryk.cn/Article/details/gtskxavcif.html

R Bash 专题                             80
来源：http://dali.cdnleiting.top/Article/details/gtngqzmtkm.html

S C / C++ 专题                          60
来源：http://dali.jiagoushi.top/Article/details/gtqnmjvpyb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gtepqbnakj.html

U 高频实用片段                         120
来源：http://dali.gaohongyu789.top/Article/details/gtmrujuhkg.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtjdpehlhz.html

合计                                  2106 条
来源：http://dali.havefunace.top/Article/details/gtfswijcmr.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtnzooqcyl.html

使用提醒
来源：http://dali.yangfankeji.com/Article/details/gttihliyej.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtwbrplsix.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhengqikj.top/Article/details/gtxmrhxyya.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jqgfzy.top/Article/details/gtqpdnzjmv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhoulong.xyz/Article/details/gtwvqbyhwu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.dianchejie.cn/Article/details/gtmnmpbtig.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzbhiqyq.html

—— 文件结束 ——
来源：http://dali.andypj.xyz/Article/details/gtukeaqhnp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtadcvnlpp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nanxuanxn.top/Article/details/gttmkouere.html

Common Programming Examples Cheat Book
来源：http://dali.tianlin.xyz/Article/details/gtqeqwknqk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqyxgsrbv.html

【收录内容】
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfbpblyu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigufen.top/Article/details/gtyivkbsld.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pengpengdd.cyou/Article/details/gtzfprcdbo.html

SQL · Bash · C · C++
来源：http://dali.jinqigufen.top/Article/details/gtrddibsse.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigufen.top/Article/details/gtksggpcys.html

【使用说明】
来源：http://dali.gotoacloud.top/Article/details/gtlulssbvl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenjidiqi.icu/Article/details/gtpatfqtbr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jyoumei.cn/Article/details/gtuwpglrqu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nanxinkj.top/Article/details/gtyfnmxtdk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.pycfn.com/Article/details/gtfklbsewr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cheryme.top/Article/details/gtesplwpwu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hammf.cn/Article/details/gtzovymrns.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkhvazst.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xinyue.icu/Article/details/gtuopzqztn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttricpge.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.kuanghao11.cn/Article/details/gtqwzzwrxl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbwzjszb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.wangshuangyany.cn/Article/details/gtumbvnvhm.html

【文件统计】
来源：http://dali.zhoulong.xyz/Article/details/gtvdoutkgy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yongpay.top/Article/details/gtzvnavdkl.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtzisflapp.html

目  录
来源：http://dali.daxiang520.top/Article/details/gtgajlnsrg.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtpfgghcas.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.fengsongda.top/Article/details/gtvjzmlann.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gtwkuqwloq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gttwxxgnrh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.iojbl.cn/Article/details/gtjxvglmtb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ivvv.top/Article/details/gtcgsnuoqi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ydzc1.top/Article/details/gtcpcqjazp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gtdmwwixch.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.redwolf501.top/Article/details/gtlbaxqhec.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtxgqqgriq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.daria6918.cn/Article/details/gtynqvzscv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtfdxsvjbl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtinysbmnp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtjzkaicil.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gtvymylijt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sweek.top/Article/details/gtuepxftpb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtzlgvurlk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hnxiangtu.top/Article/details/gtgnfjoshn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtyeoxfbgq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenzaomai.com/Article/details/gtnwtposeo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gtiepnmaju.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxinkj.top/Article/details/gtrsoryffc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwrqbuapt.html

A. 基础语法与类型
来源：http://dali.daria6918.cn/Article/details/gtpfmeplrw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkstuxjsq.html

[A01] Hello World
来源：http://dali.chenlongwang.top/Article/details/gtqiulvnfm.html

Py:   print("Hello, World!")
来源：http://dali.gzhubu.top/Article/details/gtshzvbvjg.html

PHP:  echo "Hello, World!";
来源：http://dali.hysaishi.cn/Article/details/gtftgrrdqw.html

JS:   console.log("Hello, World!");
来源：http://dali.9152youxi.cn/Article/details/gtdnpjzqvp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jiagoushi.top/Article/details/gtqnpngiia.html

Java: System.out.println("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtpfpxpxhn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gtcxgdeaqn.html

Ruby: puts "Hello, World!"
来源：http://dali.dashuyun.cn/Article/details/gthzysffed.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gthwyinntr.html

[A02] 变量声明与赋值
来源：http://dali.sxryk.cn/Article/details/gtyexcycfm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cashguo.top/Article/details/gtmhrxlnxb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtiyglodkr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtjajgbuwx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hnqzz.top/Article/details/gtzdfxkexw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtkdfgwjea.html

Go:   name := "Alex"; age := 20
来源：http://dali.gotoacloud.top/Article/details/gtdtmvtrrk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.daxiang520.top/Article/details/gtxmahwkil.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtvgahnwit.html

[A03] 常量定义
来源：http://dali.chenlongwang.top/Article/details/gtvmuoxyie.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cqqwz.cn/Article/details/gtemkznfmk.html

PHP:  const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtazsqutwh.html

JS:   const PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtfnygxise.html

TS:   const PI: number = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gttxdyixiz.html

Java: static final double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtzkbcfgsa.html

Go:   const PI = 3.14159
来源：http://dali.dashuyun.cn/Article/details/gtreuzavgf.html

Ruby: PI = 3.14159
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjlsebwz.html

C#:   const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtjqtktwnc.html

[A04] 判断变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gtqzjyqsfg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigfzy.top/Article/details/gtdrsngzoj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.smart0.xyz/Article/details/gtjrdijgux.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.fzhhl.top/Article/details/gtcjvsfamp.html

TS:   typeof x; x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gtmoszfdox.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.quarkkingdee.top/Article/details/gtluwcxyxw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yvedp.cn/Article/details/gtnomygzoe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinghuilouyu.cn/Article/details/gtopdkdmvh.html

C#:   x.GetType().Name; x is int
来源：http://dali.hfpthk.cn/Article/details/gteutozzjp.html

[A05] 整数除法与取模
来源：http://dali.andypj.xyz/Article/details/gtjjtpudkh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sweek.top/Article/details/gtgasqmykv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtelabgkcj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtmwbujjet.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtczereykp.html

Java: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtixzlaozb.html

Go:   7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtskapdsri.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtvhjjztgm.html

C#:   7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtvfmpqmmf.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmhvtwpx.html

Py:   int("42"); float("3.14")
来源：http://dali.quarkkingdee.top/Article/details/gtqdaabbyh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.kuanghao11.cn/Article/details/gtxamzxven.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.smart0.xyz/Article/details/gtjyipmruw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jiagoushi.top/Article/details/gtjzjyupwr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sysykeji.top/Article/details/gtnhfahvhz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ivvv.top/Article/details/gtlffdsmsx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yuanzhike.top/Article/details/gtozjopfnf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gthfwijwec.html

[A07] 数字转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtrctjpmwi.html

Py:   str(42)
来源：http://dali.fengsongda.top/Article/details/gtjnmwhfod.html

PHP:  (string) 42; strval(42)
来源：http://dali.wangshuangyany.cn/Article/details/gteggntywc.html

JS:   String(42); (42).toString()
来源：http://dali.pycfn.com/Article/details/gtvlzyytem.html

TS:   String(42)
来源：http://dali.yanxiufei.cn/Article/details/gtfwtyegmi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.316326.xyz/Article/details/gtbesweuwo.html

Go:   strconv.Itoa(42)
来源：http://dali.yongpay.top/Article/details/gtkncgrhuv.html

Ruby: 42.to_s
来源：http://dali.gaohongyu789.top/Article/details/gteylamzic.html

C#:   42.ToString()
来源：http://dali.wangdashe.top/Article/details/gtpvbvgjkn.html

[A08] 取整与四舍五入
来源：http://dali.jyoumei.cn/Article/details/gtqpxtyfak.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gtbrucbvkc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hywenlv.cn/Article/details/gthhpexcqn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtyvkoxiyx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cucudq.cn/Article/details/gtcxxardus.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtbrspvooz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gthepprrkw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenlongwang.top/Article/details/gtgycthpeu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gthlwluqwp.html

[A09] 绝对值与最大最小值
来源：http://dali.hysaishi.cn/Article/details/gtwydtadje.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtlkgnvjon.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.havefunace.top/Article/details/gtiymulass.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hammf.cn/Article/details/gtygxskptj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtdonnsdhu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtxvrastgi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.chenjidiqi.icu/Article/details/gtlpghewuo.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.wangshuangyany.cn/Article/details/gtckftbjsu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtskrxrgxb.html

[A10] 生成随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxrjyzrd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xziqi.cn/Article/details/gtpuhpippf.html

PHP:  random_int(1, 100);
来源：http://dali.ybcxt.top/Article/details/gtrrcihnfg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gtircoudnx.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sufxvd.cn/Article/details/gtafcpmcin.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yanxiufei.cn/Article/details/gtmxynczkc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.andypj.xyz/Article/details/gtjidrzspd.html

Ruby: rand(1..100)
来源：http://dali.yanxiufei.cn/Article/details/gtenqcshhw.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhoulong.xyz/Article/details/gtvcryawyz.html

[A11] 条件表达式（三元）
来源：http://dali.havefunace.top/Article/details/gtnpsnrmui.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nanxinkj.top/Article/details/gtjpcbztlt.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnknwazrd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gtihnengkb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtcwqnkdrd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtkughkynm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.316326.xyz/Article/details/gtnxbnznxa.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gtpxzgeopu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gtjtrqomzv.html

[A12] 字符串插值 / 格式化
来源：http://dali.xinyue.icu/Article/details/gtmskgmbdu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtupvcatmg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.tian-w.cn/Article/details/gtjautzuwo.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gtafcjpmpf.html

TS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqwnvlss.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xziqi.cn/Article/details/gtcpbsrenv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gtyeaaaasa.html

Ruby: "Hello, #{name}!"
来源：http://dali.gotoacloud.top/Article/details/gtyorhjclp.html

C#:   $"Hello, {name}!"
来源：http://dali.nwbrower.top/Article/details/gtnfzgisms.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhongyouzk.top/Article/details/gtngltivxm.html

Py:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtyganpmml.html

PHP:  "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtqarpbssu.html

JS:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtgrrfjktp.html

TS:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtohqgceqb.html


<!-- 参考信息 -->