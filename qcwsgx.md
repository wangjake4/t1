代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.guowangkeji.top/Article/details/gtgzcqgrof.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtwdgqkdlz.html

[U84] JS：CommonJS 写法
来源：http://dali.jinghuilouyu.cn/Article/details/gttxutrrcn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nwbrower.top/Article/details/gtkxbigybd.html

[U85] JS：可选链
来源：http://dali.aizwys.cn/Article/details/gtwwqgjcsk.html

a?.b?.c
来源：http://dali.xinyue.icu/Article/details/gtzaowvcpp.html

[U86] JS：空值合并
来源：http://dali.guannengcc.top/Article/details/gtoghppmog.html

a ?? b
来源：http://dali.316326.xyz/Article/details/gtwmihoifw.html

[U87] JS：解构默认值
来源：http://dali.tianlin.xyz/Article/details/gtzhgywnua.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ppjwa.cn/Article/details/gthtjggcxu.html

[U88] JS：对象展开合并
来源：http://dali.cdnleiting.top/Article/details/gttjaaglkg.html

{ ...a, ...b }
来源：http://dali.yj20258.top/Article/details/gtpomhideo.html

[U89] JS：数组去重
来源：http://dali.chenzaomai.com/Article/details/gtiaiccklw.html

[...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtvjxjqbnr.html

[U90] JS：数字数组排序
来源：http://dali.kuanghao11.cn/Article/details/gtrhrpjkxl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtkuvqvksk.html

[U91] JS：对象键值遍历
来源：http://dali.jlsjyb.cn/Article/details/gtleavxfay.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.birdmap.top/Article/details/gtmwgvujvf.html

[U92] JS：深拷贝
来源：http://dali.chenzaomai.com/Article/details/gtbklwzpdn.html

structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtkabdgguw.html

[U93] JS：模板字符串
来源：http://dali.hnqzz.top/Article/details/gtqdkqzgxj.html

`共 ${n} 条`
来源：http://dali.sufxvd.cn/Article/details/gtlqzlysaf.html

[U94] JS：箭头函数
来源：http://dali.yj20258888.top/Article/details/gtyhsbbiqr.html

const double = x => x * 2;
来源：http://dali.zhixingplan.top/Article/details/gtzibhlxnv.html

[U95] JS：Promise 包装
来源：http://dali.ybcxt.top/Article/details/gtritjqlom.html

new Promise((resolve, reject) => {})
来源：http://dali.c1oappe.top/Article/details/gtxeslsoxz.html

[U96] JS：async/await 与异常
来源：http://dali.snrcjt.cn/Article/details/gtfidoruwu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtkqcsymga.html

[U97] JS：并发请求
来源：http://dali.aizwys.cn/Article/details/gtxtshjqkb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyutetmsj.html

[U98] JS：fetch 带 JSON
来源：http://dali.sysykeji.top/Article/details/gtulwaaxab.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.0kj1m.cn/Article/details/gtczloevfj.html

[U99] JS：事件监听
来源：http://dali.havefunace.top/Article/details/gtkbbwlntn.html

el.addEventListener("click", e => {})
来源：http://dali.shuidangran.top/Article/details/gterpmetwh.html

[U100] JS：DOM 查询
来源：http://dali.yvedp.cn/Article/details/gtpljreleb.html

document.querySelector(".item")
来源：http://dali.sysykeji.top/Article/details/gttpxccylv.html

[U101] JS：classList 操作
来源：http://dali.fengsongda.top/Article/details/gtjlgmxusy.html

el.classList.toggle("active")
来源：http://dali.tanke756.top/Article/details/gtfjttwjxm.html

[U102] JS：本地存储
来源：http://dali.cheryme.top/Article/details/gtrnguqqev.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gtdcbpnlcm.html

[U103] JS：定时器
来源：http://dali.nanxinkj.top/Article/details/gtvbyduhgl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.fzhhl.top/Article/details/gtnbwnplsl.html

[U104] JS：防抖
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcjjdned.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtcxgntqlz.html

[U105] JS：节流
来源：http://dali.svipenyu.cn/Article/details/gtzdncukxf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.316326.xyz/Article/details/gthcxalpwu.html

[U106] JS：日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtbgzzrfyq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tanke756.top/Article/details/gtlyhtvamo.html

[U107] JS：数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokzrvliu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gthbjdlehp.html

[U108] JS：随机整数
来源：http://dali.xuetiantiany.cn/Article/details/gtsiajflrl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jlsjyb.cn/Article/details/gtvymmhfqm.html

[U109] JS：数组分组
来源：http://dali.hfpthk.cn/Article/details/gtghbzroux.html

Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gtqatkzpxl.html

[U110] JS：数组分块
来源：http://dali.yuanzhike.top/Article/details/gtslaeehls.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yongpay.top/Article/details/gtyecujybd.html

[U111] JS：对象转 Map
来源：http://dali.gzhubu.top/Article/details/gtufhtxffw.html

new Map(Object.entries(obj))
来源：http://dali.yvedp.cn/Article/details/gtujukjapm.html

[U112] JS：字符串补位
来源：http://dali.jqgufenzy.top/Article/details/gtyappgclo.html

"7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtlvmpayga.html

[U113] JS：正则替换全部
来源：http://dali.yueranfly.top/Article/details/gtznphtacp.html

s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtxtmcddvb.html

[U114] JS：JSON 深比较
来源：http://dali.bjfxy.top/Article/details/gtvgiwtxaw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gtpujnjpvm.html

[U115] JS：生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtxokfjsju.html

crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtaquhivfv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xinyue.icu/Article/details/gtttbejjro.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuanzhike.top/Article/details/gtxlkasfbm.html

[U117] JS：单元测试
来源：http://dali.cashguo.top/Article/details/gtcvndwwce.html

npm i -D vitest;  npx vitest
来源：http://dali.0kj1m.cn/Article/details/gthbsgmrlb.html

[U118] JS：开发服务器
来源：http://dali.svipenyu.cn/Article/details/gtzyejqktu.html

npm i -D vite;  npx vite
来源：http://dali.ppjwa.cn/Article/details/gtjsdfquvy.html

[U119] JS：生产构建
来源：http://dali.jinghuilouyu.cn/Article/details/gtccusvclw.html

npx vite build
来源：http://dali.meibo888.top/Article/details/gtaivegppg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cdnleiting.top/Article/details/gtukalcjjb.html

import.meta.env.VITE_API_URL
来源：http://dali.jlsjyb.cn/Article/details/gtanugiddx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlmegpcmp.html

统计汇总
来源：http://dali.quarkkingdee.top/Article/details/gtbecxxmju.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbxnpcjbl.html

按语言统计（条）：
来源：http://dali.9152youxi.cn/Article/details/gtyxhikjqi.html

Python ......... 252
来源：http://dali.jinqigufen.top/Article/details/gtfpsczvxv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gtypazvktc.html

JavaScript ..... 252
来源：http://dali.hywenlv.cn/Article/details/gtlupjobhw.html

TypeScript ..... 212
来源：http://dali.redwolf501.top/Article/details/gtcvzhjvde.html

Java ........... 212
来源：http://dali.gogol.net.cn/Article/details/gtconywziy.html

Go ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gtgtugmtjx.html

Ruby ........... 212
来源：http://dali.9152youxi.cn/Article/details/gtzspqfnst.html

C# ............. 212
来源：http://dali.svipenyu.cn/Article/details/gtucsouksu.html

C .............. 30
来源：http://dali.9152youxi.cn/Article/details/gtdnttryyv.html

C++ ............ 30
来源：http://dali.jinqigufen.top/Article/details/gtztuqshkd.html

SQL ............ 90
来源：http://dali.quarkkingdee.top/Article/details/gtwoqgghad.html

Bash ........... 80
来源：http://dali.vqdsnc.cn/Article/details/gtoqakgjks.html

Kotlin ......... 15
来源：http://dali.shuidangran.top/Article/details/gtbmejecjr.html

Swift .......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpukyajiq.html

Lua ............ 10
来源：http://dali.yueranfly.top/Article/details/gttaalmtvx.html

Perl ........... 10
来源：http://dali.jiagoushi.top/Article/details/gtbskbvjcy.html

Scala .......... 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbhfohtk.html

------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtqoifpljo.html

合计 ........... 2106 条
来源：http://dali.yueranfly.top/Article/details/gttiubtpjp.html

按章节统计：
来源：http://dali.nwbrower.top/Article/details/gtuznbtgwy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yongpay.top/Article/details/gtpslmakma.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gtqqzgtyeo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtviqzzyuq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gtskjlehzx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhixingplan.top/Article/details/gtaulnzcub.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenzaomai.com/Article/details/gtiqqquqwm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gtjyyhsnti.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gtnqwgethr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gttjwkbgfm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gtstfkuhvk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtqqftfbqf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtpdjwzdhg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtcewzdrea.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gtyhdvfshj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.fengsongda.top/Article/details/gthdfwwmyh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtwigengyj.html

Q SQL 专题                              90
来源：http://dali.yuanzhike.top/Article/details/gtqvqjfeut.html

R Bash 专题                             80
来源：http://dali.sxryk.cn/Article/details/gtqfplrofz.html

S C / C++ 专题                          60
来源：http://dali.ppjwa.cn/Article/details/gtraaectuo.html

T 其他语言补充                          60
来源：http://dali.hysaishi.cn/Article/details/gtooiikegx.html

U 高频实用片段                         120
来源：http://dali.cdnleiting.top/Article/details/gteoklpbgq.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtyhuwqnnr.html

合计                                  2106 条
来源：http://dali.jlsjyb.cn/Article/details/gtpmqpkxwb.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgztajjsj.html

使用提醒
来源：http://dali.zhixingplan.top/Article/details/gtjtpiufnx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtljtjuxta.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zycfv.cn/Article/details/gtsmxsmepg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmipspfz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.wangshuangyany.cn/Article/details/gtdgvtzexm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsmyawlf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.andypj.xyz/Article/details/gtvjirvsmo.html

—— 文件结束 ——
来源：http://dali.pycfn.com/Article/details/gtmiilxaey.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwlgopfbs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqcmvcjx.html

Common Programming Examples Cheat Book
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqikntizj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtjawiggrm.html

【收录内容】
来源：http://dali.guannengcc.top/Article/details/gtuapmwjxx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hywenlv.cn/Article/details/gtxswxntyr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.nanxuanxn.top/Article/details/gtdbstnkgf.html

SQL · Bash · C · C++
来源：http://dali.cucudq.cn/Article/details/gtppsybryw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yonumen.top/Article/details/gtiukantat.html

【使用说明】
来源：http://dali.chenjidiqi.icu/Article/details/gtoczjazwp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.vqdsnc.cn/Article/details/gtsdvkxqte.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sweek.top/Article/details/gturebhfzt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jlsjyb.cn/Article/details/gtnwavkebv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shzxlz.cn/Article/details/gtfrtnqnsc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jqgfzy.top/Article/details/gtjiirbtwg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cdnleiting.top/Article/details/gtxrqdxjye.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenzaomai.com/Article/details/gtzbulnjzs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.kuanghao11.cn/Article/details/gtkanvlyah.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xziqi.cn/Article/details/gthvrnsxbt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj20258.top/Article/details/gtjntocttg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.9152youxi.cn/Article/details/gtovqzhwqb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sweek.top/Article/details/gtctvnwjbw.html

【文件统计】
来源：http://dali.yuxming.cn/Article/details/gtqdcgsxpm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.bjfxy.top/Article/details/gtjghpmuuw.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtumjppqcw.html

目  录
来源：http://dali.tian-w.cn/Article/details/gtocjszlvr.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gtzddszprm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jiagoushi.top/Article/details/gtfxepvajt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gtpnnjdqgw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gtekzhsuhm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajceqxro.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ivvv.top/Article/details/gtzlkjjakt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtwwvigpfl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xinyue.icu/Article/details/gtwqeuurva.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gtzfthlqyy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtfwfuwloo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gtkqbskzdt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekhmydwd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gttbtenopb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtirhlhwex.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gthbrljnpz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.havefunace.top/Article/details/gtumdjgdxq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtlcgnqbhx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtreremtaq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhixingplan.top/Article/details/gtkctmrysz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenlongwang.top/Article/details/gtlittsrgs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtbjihtggn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtsvinlbvd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmhswxsrc.html

A. 基础语法与类型
来源：http://dali.tianlin.xyz/Article/details/gtqpfblugo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtedliswog.html

[A01] Hello World
来源：http://dali.aibaodan.cn/Article/details/gtepjxhmrs.html

Py:   print("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gtdxqhjsqs.html

PHP:  echo "Hello, World!";
来源：http://dali.guowangkeji.top/Article/details/gtehiqgcek.html

JS:   console.log("Hello, World!");
来源：http://dali.gotoacloud.top/Article/details/gtsicfzxou.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.iojbl.cn/Article/details/gtjclzwbtl.html

Java: System.out.println("Hello, World!");
来源：http://dali.cucudq.cn/Article/details/gtdkkzzunk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tianlin.xyz/Article/details/gtvgpepnui.html

Ruby: puts "Hello, World!"
来源：http://dali.hongshengwenyu.top/Article/details/gtrcibblqa.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gtkfxqhirw.html

[A02] 变量声明与赋值
来源：http://dali.dianchejie.cn/Article/details/gtowrnalnl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.birdmap.top/Article/details/gtnczqeuyk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkewdkbof.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nwbrower.top/Article/details/gthuopwgfx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cucudq.cn/Article/details/gtnnxotqzm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gtbjysbjia.html

Go:   name := "Alex"; age := 20
来源：http://dali.gzhubu.top/Article/details/gtjcewgsfk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.haohaochexian.top/Article/details/gtawpylguq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtmvzsvdps.html

[A03] 常量定义
来源：http://dali.gzhubu.top/Article/details/gtpoxnqtzc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.aizwys.cn/Article/details/gtstaqwhjp.html

PHP:  const PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtgbyctcxx.html

JS:   const PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtdnmighyw.html

TS:   const PI: number = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtepqymycy.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpbpjadb.html

Go:   const PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gtrbissriw.html

Ruby: PI = 3.14159
来源：http://dali.yongpay.top/Article/details/gtarqisxjo.html

C#:   const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gttgwkmdvc.html

[A04] 判断变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehjcuqzw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xinyue.icu/Article/details/gtogyhnthv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.316326.xyz/Article/details/gtnjzavhyy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cqqwz.cn/Article/details/gtamzbgnbr.html

TS:   typeof x; x instanceof Date
来源：http://dali.aibaodan.cn/Article/details/gtpgimkpix.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj20258.top/Article/details/gttginhwiu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cucudq.cn/Article/details/gtggqcywkc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nanxuanxn.top/Article/details/gtmewnugrn.html

C#:   x.GetType().Name; x is int
来源：http://dali.nwbrower.top/Article/details/gtfmasumzh.html

[A05] 整数除法与取模
来源：http://dali.cashguo.top/Article/details/gtasoyxwpm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.andypj.xyz/Article/details/gtcasrytyy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtyzazpuaq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtwpvavwua.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtdshghfrf.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgltfxpgk.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtihjconxv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gtwexviivg.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtgkiznbxs.html

[A06] 字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gtbiewgaet.html

Py:   int("42"); float("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gtdvtbmlpa.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jqgufenzy.top/Article/details/gtbqhvzyab.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shuidangran.top/Article/details/gtfzxtpdvv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gtfxpsyvlo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj20258.top/Article/details/gthruebrlo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhoulong.xyz/Article/details/gtxkshffki.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nwbrower.top/Article/details/gtxrebyiku.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.tian-w.cn/Article/details/gtfnimwsxa.html

[A07] 数字转字符串
来源：http://dali.jiagoushi.top/Article/details/gtddnnflmu.html

Py:   str(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtdubhrxyj.html

PHP:  (string) 42; strval(42)
来源：http://dali.ppjwa.cn/Article/details/gtbfbdukjz.html

JS:   String(42); (42).toString()
来源：http://dali.sysykeji.top/Article/details/gtxjsgrleo.html

TS:   String(42)
来源：http://dali.xylfe.cn/Article/details/gtbnuavdpg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cdnleiting.top/Article/details/gtoqnolfbt.html

Go:   strconv.Itoa(42)
来源：http://dali.gzhubu.top/Article/details/gtxuxbnfik.html

Ruby: 42.to_s
来源：http://dali.hammf.cn/Article/details/gtiyurvskx.html

C#:   42.ToString()
来源：http://dali.zhengqikj.top/Article/details/gtonkmgttc.html

[A08] 取整与四舍五入
来源：http://dali.yvedp.cn/Article/details/gtefbjbcqe.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gtukfqkdho.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhoulong.xyz/Article/details/gtszgxslon.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gtvmjekkip.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.tanke756.top/Article/details/gtplepekeh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbfvzcrc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtfwveubqt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yvedp.cn/Article/details/gtyoravbtn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gthhcvsfhf.html

[A09] 绝对值与最大最小值
来源：http://dali.ppjwa.cn/Article/details/gtyrfnvasl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtcolwztsn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtnijvowwa.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtlckaczma.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gthqbxfowf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtwghximsf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.0kj1m.cn/Article/details/gtzqfavkat.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnqzz.top/Article/details/gtfxxojpcv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hammf.cn/Article/details/gtdbvtgrbz.html

[A10] 生成随机数
来源：http://dali.yuanzhike.top/Article/details/gtaqmiimzo.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shanyushiyangtech.top/Article/details/gtisrspwfr.html

PHP:  random_int(1, 100);
来源：http://dali.pengpengdd.cyou/Article/details/gtfyayuevy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtnntavlti.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yangfankeji.com/Article/details/gtcfhujszj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cucudq.cn/Article/details/gtvgcnzzjw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.feifeiyinyue.top/Article/details/gtnojtlutq.html

Ruby: rand(1..100)
来源：http://dali.daria6918.cn/Article/details/gtvivkemla.html

C#:   new Random().Next(1, 101)
来源：http://dali.daria6918.cn/Article/details/gtmeucmgsw.html

[A11] 条件表达式（三元）
来源：http://dali.sysykeji.top/Article/details/gtsuxiifzg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jianghu66.top/Article/details/gtrccmafwc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtbcsidbvt.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtvkxkxnwb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtihdbvtlt.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gtunygdphe.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinqigfzy.top/Article/details/gtjhwdgmbp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gtjwsqirtk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gteespwlnz.html

[A12] 字符串插值 / 格式化
来源：http://dali.tanke756.top/Article/details/gtnuukaeey.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jiagoushi.top/Article/details/gtdltumyws.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.dianchejie.cn/Article/details/gtpmmmsuuw.html

JS:   `Hello, ${name}!`
来源：http://dali.yj20258888.top/Article/details/gtljofguhx.html

TS:   `Hello, ${name}!`
来源：http://dali.hfpthk.cn/Article/details/gtunjgdunn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.aibaodan.cn/Article/details/gtpduyeosb.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.dashuyun.cn/Article/details/gtfwaoodxz.html

Ruby: "Hello, #{name}!"
来源：http://dali.redwolf501.top/Article/details/gtcfjjycmu.html

C#:   $"Hello, {name}!"
来源：http://dali.sufxvd.cn/Article/details/gtiusquphd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.vqdsnc.cn/Article/details/gtatxbpuar.html

Py:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtixhqpgil.html

PHP:  "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopgptklm.html

JS:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtfsftqbmq.html

TS:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtzvxffbde.html

Java: "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtasqupwpe.html

Go:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtghfflrxb.html

Ruby: "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtauiyhojc.html

C#:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtfrctojtx.html


<!-- 参考信息 -->