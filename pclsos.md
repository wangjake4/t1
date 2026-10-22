代发 wailian999

[U81] JS：初始化项目
来源：http://dali.hnqzz.top/Article/details/gtjpbgesjo.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gtrggegrsk.html

[U82] JS：package.json 脚本
来源：http://dali.dashuyun.cn/Article/details/gtrnhyxquc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj20258.top/Article/details/gtowdqxlrm.html

[U83] JS：ES Module 导入导出
来源：http://dali.ehwqpu.com/Article/details/gtiykhkudv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gtiilgbzbq.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigfzy.top/Article/details/gtjsgjiwlg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jlsjyb.cn/Article/details/gtcdxnyuwa.html

[U85] JS：可选链
来源：http://dali.nanxinkj.top/Article/details/gtvycuwwff.html

a?.b?.c
来源：http://dali.zhiwuduotai.top/Article/details/gtslnlmwal.html

[U86] JS：空值合并
来源：http://dali.andypj.xyz/Article/details/gtbvgxxnco.html

a ?? b
来源：http://dali.cucudq.cn/Article/details/gtvcccopab.html

[U87] JS：解构默认值
来源：http://dali.jqgufenzy.top/Article/details/gtvdewyzhc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gthclqbzlo.html

[U88] JS：对象展开合并
来源：http://dali.wangshuangyany.cn/Article/details/gtaqbrhrng.html

{ ...a, ...b }
来源：http://dali.zhoulong.xyz/Article/details/gtthntlqnc.html

[U89] JS：数组去重
来源：http://dali.jlsjyb.cn/Article/details/gtnkqymtjy.html

[...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtgoizfyje.html

[U90] JS：数字数组排序
来源：http://dali.chenzaomai.com/Article/details/gtroeejwyr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtfgyxvofg.html

[U91] JS：对象键值遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtdyicrpqy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pycfn.com/Article/details/gtxubbaovj.html

[U92] JS：深拷贝
来源：http://dali.aizwys.cn/Article/details/gtekzrlhmt.html

structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtzxrltjfm.html

[U93] JS：模板字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtjmeiegle.html

`共 ${n} 条`
来源：http://dali.cdnleiting.top/Article/details/gtgrmvinax.html

[U94] JS：箭头函数
来源：http://dali.c1oappe.top/Article/details/gtzzcoffns.html

const double = x => x * 2;
来源：http://dali.snrcjt.cn/Article/details/gtvvgriprs.html

[U95] JS：Promise 包装
来源：http://dali.svipenyu.cn/Article/details/gtrxebzqzo.html

new Promise((resolve, reject) => {})
来源：http://dali.hysaishi.cn/Article/details/gtjnwdhazm.html

[U96] JS：async/await 与异常
来源：http://dali.jinqigfzy.top/Article/details/gtuaatapta.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtanuaqhmh.html

[U97] JS：并发请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwebygjhc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtzhqvclbe.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuanzx.com/Article/details/gtvtdmifrn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.andypj.xyz/Article/details/gthbabjrzy.html

[U99] JS：事件监听
来源：http://dali.shzxlz.cn/Article/details/gtfdljyidu.html

el.addEventListener("click", e => {})
来源：http://dali.nanxinkj.top/Article/details/gtamdhxacy.html

[U100] JS：DOM 查询
来源：http://dali.wangshuangyany.cn/Article/details/gtfcatbahk.html

document.querySelector(".item")
来源：http://dali.bjfxy.top/Article/details/gtpzxndtsk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gtuifobnbb.html

el.classList.toggle("active")
来源：http://dali.sufxvd.cn/Article/details/gtzssmzkdg.html

[U102] JS：本地存储
来源：http://dali.ppjwa.cn/Article/details/gtfvdojxrf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.meibo888.top/Article/details/gtpaagnerc.html

[U103] JS：定时器
来源：http://dali.jyoumei.cn/Article/details/gtuyvgiwpo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.snrcjt.cn/Article/details/gtqfanuzoc.html

[U104] JS：防抖
来源：http://dali.shzxlz.cn/Article/details/gtvxpzketx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtdxggsszt.html

[U105] JS：节流
来源：http://dali.9152youxi.cn/Article/details/gtwgyrqcoj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gogol.net.cn/Article/details/gtjrzpzqyw.html

[U106] JS：日期格式化
来源：http://dali.sweek.top/Article/details/gtzigcxgjk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.vqdsnc.cn/Article/details/gtoelmedfb.html

[U107] JS：数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtyuywvior.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xziqi.cn/Article/details/gtutibtnsz.html

[U108] JS：随机整数
来源：http://dali.ehwqpu.com/Article/details/gtuujupvwy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cdnleiting.top/Article/details/gtujmtipud.html

[U109] JS：数组分组
来源：http://dali.jinqigufen.top/Article/details/gtzusqcxfw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtvimgsvfn.html

[U110] JS：数组分块
来源：http://dali.xuetiantiany.cn/Article/details/gtngsfneyj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuxming.cn/Article/details/gtwgtveagz.html

[U111] JS：对象转 Map
来源：http://dali.yangfankeji.com/Article/details/gtdyrdduon.html

new Map(Object.entries(obj))
来源：http://dali.guowangkeji.top/Article/details/gthxjwfhon.html

[U112] JS：字符串补位
来源：http://dali.jqgfzy.top/Article/details/gtjhlgtcgd.html

"7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtptvnmfcu.html

[U113] JS：正则替换全部
来源：http://dali.jyoumei.cn/Article/details/gtfqvcpgjo.html

s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtcdcjikzg.html

[U114] JS：JSON 深比较
来源：http://dali.mhx1999.top/Article/details/gtcjikgxhr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtudsvotto.html

[U115] JS：生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gtbpixxxag.html

crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gteosmnyht.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dianchejie.cn/Article/details/gtjlaetpla.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ivvv.top/Article/details/gtzatipvjc.html

[U117] JS：单元测试
来源：http://dali.cdnleiting.top/Article/details/gtsvwbpvxu.html

npm i -D vitest;  npx vitest
来源：http://dali.shuidangran.top/Article/details/gtuxfroqmb.html

[U118] JS：开发服务器
来源：http://dali.zycfv.cn/Article/details/gtugdicafz.html

npm i -D vite;  npx vite
来源：http://dali.cheryme.top/Article/details/gtyifhromj.html

[U119] JS：生产构建
来源：http://dali.yj20258888.top/Article/details/gtfsozrnog.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gtvucoplqn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.svipenyu.cn/Article/details/gtvqgqgkfj.html

import.meta.env.VITE_API_URL
来源：http://dali.sysykeji.top/Article/details/gtnznztvix.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbbkkoxbt.html

统计汇总
来源：http://dali.zdqjudy.top/Article/details/gtwzksfizw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtrdvvqptl.html

按语言统计（条）：
来源：http://dali.yj20258.top/Article/details/gtcmltiftq.html

Python ......... 252
来源：http://dali.316326.xyz/Article/details/gtgcxskcak.html

PHP ............ 252
来源：http://dali.cdnleiting.top/Article/details/gtoyhrlxyz.html

JavaScript ..... 252
来源：http://dali.xuanzx.com/Article/details/gtqisnjbnu.html

TypeScript ..... 212
来源：http://dali.fzhhl.top/Article/details/gtjqbtllgp.html

Java ........... 212
来源：http://dali.haohaochexian.top/Article/details/gtlccxvwcu.html

Go ............. 212
来源：http://dali.zycfv.cn/Article/details/gtqrnjqcih.html

Ruby ........... 212
来源：http://dali.aibaodan.cn/Article/details/gtpjiqrkto.html

C# ............. 212
来源：http://dali.birdmap.top/Article/details/gtvusdvnuo.html

C .............. 30
来源：http://dali.jyoumei.cn/Article/details/gtlxdcjrny.html

C++ ............ 30
来源：http://dali.yvedp.cn/Article/details/gtavkxtvjn.html

SQL ............ 90
来源：http://dali.nanxuanxn.top/Article/details/gtizjdrxef.html

Bash ........... 80
来源：http://dali.sysykeji.top/Article/details/gtguzimxju.html

Kotlin ......... 15
来源：http://dali.shzxlz.cn/Article/details/gtlgnhwztl.html

Swift .......... 15
来源：http://dali.jlsjyb.cn/Article/details/gtvakxeefm.html

Lua ............ 10
来源：http://dali.jianghu66.top/Article/details/gtkvyhzxic.html

Perl ........... 10
来源：http://dali.cashguo.top/Article/details/gtdryutewd.html

Scala .......... 10
来源：http://dali.chenzaomai.com/Article/details/gttasuirnj.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtofpnyfdg.html

合计 ........... 2106 条
来源：http://dali.ydzc1.top/Article/details/gtimkxtehs.html

按章节统计：
来源：http://dali.fzhhl.top/Article/details/gtfsnyiklk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gtjrbuymjx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtrwdxijos.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gtjnoddugw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gtdgiuvadk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tian-w.cn/Article/details/gtwrivlmmo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jianghu66.top/Article/details/gtuqjoylsh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtdqwpxbzw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gtqdovsgje.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtgrkzvfzs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gtzzeaamli.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjxgssdv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtikielbda.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtxwcmhdjg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sweek.top/Article/details/gtvsrtqvve.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.fzhhl.top/Article/details/gtrdxjgccy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtcmhttqjs.html

Q SQL 专题                              90
来源：http://dali.c1oappe.top/Article/details/gtxggpbmob.html

R Bash 专题                             80
来源：http://dali.daria6918.cn/Article/details/gtphcbpqxn.html

S C / C++ 专题                          60
来源：http://dali.fengsongda.top/Article/details/gtjxdziajh.html

T 其他语言补充                          60
来源：http://dali.yvedp.cn/Article/details/gtpgfqsehy.html

U 高频实用片段                         120
来源：http://dali.cheryme.top/Article/details/gtydrulpgc.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gtubthafqc.html

合计                                  2106 条
来源：http://dali.daria6918.cn/Article/details/gtjdhnsapc.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtnlkuvlwk.html

使用提醒
来源：http://dali.shzxlz.cn/Article/details/gtcwpvvuzn.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtjvogfnhi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhixingplan.top/Article/details/gtzzssozzh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daria6918.cn/Article/details/gtvjlecgwe.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigfzy.top/Article/details/gtvywnnwuq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.vqdsnc.cn/Article/details/gtkivnrcqy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj20258888.top/Article/details/gteqdyavxf.html

—— 文件结束 ——
来源：http://dali.chenlongwang.top/Article/details/gtzrkmgvtu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtpsdkqsbq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cashguo.top/Article/details/gtzkzhrajb.html

Common Programming Examples Cheat Book
来源：http://dali.vqdsnc.cn/Article/details/gtjjoewlgu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtglnmfpsm.html

【收录内容】
来源：http://dali.hongshengwenyu.top/Article/details/gtxxmmyjvp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sxryk.cn/Article/details/gtlvfmhagw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.dianchejie.cn/Article/details/gtpnlrldks.html

SQL · Bash · C · C++
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakqreuss.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.guowangkeji.top/Article/details/gtryvkbwil.html

【使用说明】
来源：http://dali.hongshengwenyu.top/Article/details/gtxkzxeoww.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.svipenyu.cn/Article/details/gtpqgaasus.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yangfankeji.com/Article/details/gtjngsevrn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dashuyun.cn/Article/details/gtkpcvajhy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj20258888.top/Article/details/gtqsjazahl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.kuanghao11.cn/Article/details/gtlhonuioc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.fengsongda.top/Article/details/gtdjeytpvh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.andypj.xyz/Article/details/gtozjsfdli.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ppjwa.cn/Article/details/gtqulkqlab.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhiwuduotai.top/Article/details/gtrhhhwvhx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj20258.top/Article/details/gtzssbjrqa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gotoacloud.top/Article/details/gtdlubczwb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fengsongda.top/Article/details/gtqsusfxzn.html

【文件统计】
来源：http://dali.cheryme.top/Article/details/gtwrqjjjpm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yj20258.top/Article/details/gtraxzxsmj.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtsfzciomp.html

目  录
来源：http://dali.jlsjyb.cn/Article/details/gtgecqbrwz.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtdfqzujut.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuanzhike.top/Article/details/gtyhxicqgw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gteleelsxg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gtdsozzpdc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.fengsongda.top/Article/details/gtzclfxycf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yuanzhike.top/Article/details/gtojinyvfl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.quarkkingdee.top/Article/details/gtjmtcbfmf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gtnhfrvece.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.svipenyu.cn/Article/details/gtgxnflyxu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtmekumpik.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gtbfmvgtim.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtscgccbje.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtopcmwzij.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtldbvanps.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ivvv.top/Article/details/gtposkavuw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.daxiang520.top/Article/details/gtobijgwoe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtjiuqpzat.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cdnleiting.top/Article/details/gtsnimqyry.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtrzrevykt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtnwdvyspr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtqyzukghg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gtjypulwev.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmxutcyqv.html

A. 基础语法与类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebuhgeum.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkjgxueef.html

[A01] Hello World
来源：http://dali.316326.xyz/Article/details/gthhfolggz.html

Py:   print("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gtstxbycgr.html

PHP:  echo "Hello, World!";
来源：http://dali.kuanghao11.cn/Article/details/gtsokbammo.html

JS:   console.log("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gtwbkzcbui.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.guowangkeji.top/Article/details/gtuwrtfyfe.html

Java: System.out.println("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtxgiaoyzn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aizwys.cn/Article/details/gtbpztwcvf.html

Ruby: puts "Hello, World!"
来源：http://dali.gzhubu.top/Article/details/gthyqwkdur.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gtqxpojxop.html

[A02] 变量声明与赋值
来源：http://dali.mhx1999.top/Article/details/gtpcybwosm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hysaishi.cn/Article/details/gtnokoujwn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtrtbursvm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.redwolf501.top/Article/details/gtgqkbdscp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvnkjinh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.316326.xyz/Article/details/gtmrgalyia.html

Go:   name := "Alex"; age := 20
来源：http://dali.daxiang520.top/Article/details/gtlkkyselc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gotoacloud.top/Article/details/gttuomjupc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xinyue.icu/Article/details/gtvwjslggq.html

[A03] 常量定义
来源：http://dali.svipenyu.cn/Article/details/gtrfaaupie.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.c1oappe.top/Article/details/gtxqnsbogy.html

PHP:  const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtsntkzsmp.html

JS:   const PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtoauamwoj.html

TS:   const PI: number = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtkllxuxqu.html

Java: static final double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtzfnjfsqx.html

Go:   const PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gtptindurr.html

Ruby: PI = 3.14159
来源：http://dali.haohaochexian.top/Article/details/gtumokoiiv.html

C#:   const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gteozmnnzp.html

[A04] 判断变量类型
来源：http://dali.sxryk.cn/Article/details/gtbntlqkvq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.meibo888.top/Article/details/gtgtlfnavz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxinkj.top/Article/details/gtfojkkakm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gtdnijjqxr.html

TS:   typeof x; x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gtagvoxcdu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinqigufen.top/Article/details/gtzlyqemah.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shangyingyoupin.top/Article/details/gtpqqszudl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zdqjudy.top/Article/details/gtdluqdyql.html

C#:   x.GetType().Name; x is int
来源：http://dali.xylfe.cn/Article/details/gtqnccguwz.html

[A05] 整数除法与取模
来源：http://dali.wangdashe.top/Article/details/gtmetgveeq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.snrcjt.cn/Article/details/gtymednvdj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gtcjghyage.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtdgmvydlp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtijsqlibm.html

Java: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfbepjxk.html

Go:   7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtikjujtfc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gttlxzavbq.html

C#:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtadrdqjzv.html

[A06] 字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtblnhwsyq.html

Py:   int("42"); float("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtmmfzrsfu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnqzz.top/Article/details/gtuxiskqby.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gtxpkkhhjh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yvedp.cn/Article/details/gtfzlxppke.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhiwuduotai.top/Article/details/gtaewhspuy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.pycfn.com/Article/details/gtyszbfldh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gogol.net.cn/Article/details/gtldomqiuk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfifhvaxo.html

[A07] 数字转字符串
来源：http://dali.0kj1m.cn/Article/details/gtutyygdwb.html

Py:   str(42)
来源：http://dali.hysaishi.cn/Article/details/gtawqspkcb.html

PHP:  (string) 42; strval(42)
来源：http://dali.jlsjyb.cn/Article/details/gtitcnxzgy.html

JS:   String(42); (42).toString()
来源：http://dali.mhx1999.top/Article/details/gtfhwtcjuh.html

TS:   String(42)
来源：http://dali.cucudq.cn/Article/details/gtfijvezjm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yanxiufei.cn/Article/details/gtmxtckwyw.html

Go:   strconv.Itoa(42)
来源：http://dali.jqgfzy.top/Article/details/gtdqqaqurd.html

Ruby: 42.to_s
来源：http://dali.hammf.cn/Article/details/gtdxytbdgf.html

C#:   42.ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtdzesdejm.html

[A08] 取整与四舍五入
来源：http://dali.wangshuangyany.cn/Article/details/gtdysseapb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtvqyhewwj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cqqwz.cn/Article/details/gtiqiylnzw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtdzapahof.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.haohaochexian.top/Article/details/gtthjwlgeq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gtnvipaxcn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzsaiupq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yuanzhike.top/Article/details/gtstnhofno.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtumghgakb.html

[A09] 绝对值与最大最小值
来源：http://dali.fzhhl.top/Article/details/gttznlwveu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtychxzmzs.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gthzczkaec.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtbwhndohh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtfjjdiaic.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtepvoikyz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jinqigfzy.top/Article/details/gtrxuewprm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.havefunace.top/Article/details/gtctridxjg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkquysikm.html

[A10] 生成随机数
来源：http://dali.smart0.xyz/Article/details/gtgounwajc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.andypj.xyz/Article/details/gtjaukqonh.html

PHP:  random_int(1, 100);
来源：http://dali.daxiang520.top/Article/details/gtrremkxpl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gotoacloud.top/Article/details/gtjsvjerlh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yvedp.cn/Article/details/gtykigmwkn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.wangshuangyany.cn/Article/details/gtfshccrxl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.wangshuangyany.cn/Article/details/gtiaeeyurj.html

Ruby: rand(1..100)
来源：http://dali.jlsjyb.cn/Article/details/gtzzsizvsm.html

C#:   new Random().Next(1, 101)
来源：http://dali.mhx1999.top/Article/details/gtchmpxenx.html

[A11] 条件表达式（三元）
来源：http://dali.yangfankeji.com/Article/details/gtttdlyvlb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbembwqyr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtftvmmeqr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtkhurtheq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmglegamo.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gtupaihwln.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.nwbrower.top/Article/details/gtohnxavjg.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gtdurkrcgy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gtsqayywqx.html

[A12] 字符串插值 / 格式化
来源：http://dali.hnxiangtu.top/Article/details/gtgczhezyx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cdnleiting.top/Article/details/gtuknvfdzw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.9152youxi.cn/Article/details/gttodhqmce.html

JS:   `Hello, ${name}!`
来源：http://dali.pycfn.com/Article/details/gtxdbezsjn.html

TS:   `Hello, ${name}!`
来源：http://dali.ppjwa.cn/Article/details/gtpacusdot.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.tianlin.xyz/Article/details/gtucbxxooo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjcllzkd.html

Ruby: "Hello, #{name}!"
来源：http://dali.hongshengwenyu.top/Article/details/gtvdorewwd.html

C#:   $"Hello, {name}!"
来源：http://dali.guowangkeji.top/Article/details/gtizezlcmo.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhiwuduotai.top/Article/details/gttvrdgnue.html

Py:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtiewndbmi.html

PHP:  "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtqclajynm.html

JS:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtfmgjjzdf.html

TS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtyqkkyogf.html


<!-- 参考信息 -->