代发 wailian999

[U81] JS：初始化项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamafdaay.html

npm init -y;  npm i express
来源：http://dali.quarkkingdee.top/Article/details/gtaxtdtlmy.html

[U82] JS：package.json 脚本
来源：http://dali.xziqi.cn/Article/details/gtcrmwqwwz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gogol.net.cn/Article/details/gtvgznbari.html

[U83] JS：ES Module 导入导出
来源：http://dali.cucudq.cn/Article/details/gtxuwkshxe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtkqhgvnml.html

[U84] JS：CommonJS 写法
来源：http://dali.yj202588.top/Article/details/gtwtiuozkx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxldqnldq.html

[U85] JS：可选链
来源：http://dali.hywenlv.cn/Article/details/gtzwsnicic.html

a?.b?.c
来源：http://dali.chenlongwang.top/Article/details/gtvyggestg.html

[U86] JS：空值合并
来源：http://dali.gogol.net.cn/Article/details/gtltemagfu.html

a ?? b
来源：http://dali.gzhubu.top/Article/details/gtqgoggsoz.html

[U87] JS：解构默认值
来源：http://dali.yj202588.top/Article/details/gtdgbkvlqh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigfzy.top/Article/details/gtutlzkbtw.html

[U88] JS：对象展开合并
来源：http://dali.zdqjudy.top/Article/details/gtrjjyyoio.html

{ ...a, ...b }
来源：http://dali.havefunace.top/Article/details/gtycgazncx.html

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gtfbwxzazm.html

[...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtndsbutky.html

[U90] JS：数字数组排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsarjqzr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtbmwnhzap.html

[U91] JS：对象键值遍历
来源：http://dali.yonumen.top/Article/details/gtmzzycrve.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aibaodan.cn/Article/details/gtwxihvxag.html

[U92] JS：深拷贝
来源：http://dali.dashuyun.cn/Article/details/gtklsuorrm.html

structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtcbozsfxk.html

[U93] JS：模板字符串
来源：http://dali.gotoacloud.top/Article/details/gtapbjgvap.html

`共 ${n} 条`
来源：http://dali.yangfankeji.com/Article/details/gtcptjumle.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbstodrm.html

const double = x => x * 2;
来源：http://dali.aizwys.cn/Article/details/gtebzebtgs.html

[U95] JS：Promise 包装
来源：http://dali.kuanghao11.cn/Article/details/gtzwqimbdf.html

new Promise((resolve, reject) => {})
来源：http://dali.cheryme.top/Article/details/gtqrgqzdur.html

[U96] JS：async/await 与异常
来源：http://dali.cucudq.cn/Article/details/gtnovkpzbs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtdoruwdag.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gtlsnpobhs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtqjwdqrrj.html

[U98] JS：fetch 带 JSON
来源：http://dali.sweek.top/Article/details/gtzuhzjvnm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhengqikj.top/Article/details/gthrptfmrm.html

[U99] JS：事件监听
来源：http://dali.guannengcc.top/Article/details/gtaewtopge.html

el.addEventListener("click", e => {})
来源：http://dali.yueranfly.top/Article/details/gtjyhwmtcy.html

[U100] JS：DOM 查询
来源：http://dali.zhixingplan.top/Article/details/gtjnkwufzt.html

document.querySelector(".item")
来源：http://dali.nanxuanxn.top/Article/details/gtjvwlpshy.html

[U101] JS：classList 操作
来源：http://dali.chenlongwang.top/Article/details/gtecgjvuph.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangtech.top/Article/details/gtykdrcwbc.html

[U102] JS：本地存储
来源：http://dali.fzhhl.top/Article/details/gtgacbodui.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhixingplan.top/Article/details/gtwwfgsjtd.html

[U103] JS：定时器
来源：http://dali.quarkkingdee.top/Article/details/gthsgcmclb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.wangdashe.top/Article/details/gtkjdunyrp.html

[U104] JS：防抖
来源：http://dali.shzxlz.cn/Article/details/gtxtjvakjn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtacirqlau.html

[U105] JS：节流
来源：http://dali.feifeiyinyue.top/Article/details/gtaocrcplj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.meibo888.top/Article/details/gtnhogamuv.html

[U106] JS：日期格式化
来源：http://dali.tanke756.top/Article/details/gtilmkfwad.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhengqikj.top/Article/details/gtqgqwyijs.html

[U107] JS：数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtsxgzyibt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfwjvcsa.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gtzozdtoya.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gaohongyu789.top/Article/details/gtewpbumse.html

[U109] JS：数组分组
来源：http://dali.hysaishi.cn/Article/details/gtdmoiztjx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtjebrvwxs.html

[U110] JS：数组分块
来源：http://dali.yj20258888.top/Article/details/gtywxnoqsj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.svipenyu.cn/Article/details/gtyrwatfty.html

[U111] JS：对象转 Map
来源：http://dali.316326.xyz/Article/details/gtwedngcxz.html

new Map(Object.entries(obj))
来源：http://dali.gogol.net.cn/Article/details/gtsapiarqj.html

[U112] JS：字符串补位
来源：http://dali.jinghuilouyu.cn/Article/details/gtdullvxdm.html

"7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmfhxerk.html

[U113] JS：正则替换全部
来源：http://dali.yonumen.top/Article/details/gtoeoocjod.html

s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtjxsndewj.html

[U114] JS：JSON 深比较
来源：http://dali.chenjidiqi.icu/Article/details/gtfsmngyqc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gtyhobuidx.html

[U115] JS：生成 UUID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbpwmlkp.html

crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtdvkgencw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hongshengwenyu.top/Article/details/gtvfnlkrga.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtpdcvwgep.html

[U117] JS：单元测试
来源：http://dali.pengpengdd.cyou/Article/details/gtginqhjej.html

npm i -D vitest;  npx vitest
来源：http://dali.zycfv.cn/Article/details/gtfffgzjuh.html

[U118] JS：开发服务器
来源：http://dali.yanxiufei.cn/Article/details/gtihuojjed.html

npm i -D vite;  npx vite
来源：http://dali.yj202588.top/Article/details/gtotyomjkn.html

[U119] JS：生产构建
来源：http://dali.tanke756.top/Article/details/gtsdwlunsy.html

npx vite build
来源：http://dali.iojbl.cn/Article/details/gtzcswrfhs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj202588.top/Article/details/gttgrvdjsa.html

import.meta.env.VITE_API_URL
来源：http://dali.tianlin.xyz/Article/details/gtknccbwsn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzdghtelp.html

统计汇总
来源：http://dali.cqqwz.cn/Article/details/gtlulfrgax.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtggonkscw.html

按语言统计（条）：
来源：http://dali.yj20258888.top/Article/details/gtixrgviga.html

Python ......... 252
来源：http://dali.yonumen.top/Article/details/gtqmsprgfg.html

PHP ............ 252
来源：http://dali.zhoulong.xyz/Article/details/gtsadmzcdd.html

JavaScript ..... 252
来源：http://dali.c1oappe.top/Article/details/gtwmukubky.html

TypeScript ..... 212
来源：http://dali.hnxiangtu.top/Article/details/gtmxazwecj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gtrdyyraju.html

Go ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gtyuhyxjbn.html

Ruby ........... 212
来源：http://dali.dashuyun.cn/Article/details/gtlfwkzkvf.html

C# ............. 212
来源：http://dali.hammf.cn/Article/details/gtsieqwvsu.html

C .............. 30
来源：http://dali.zhixingplan.top/Article/details/gtantelzeg.html

C++ ............ 30
来源：http://dali.jinqigufen.top/Article/details/gtxcjtrgju.html

SQL ............ 90
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdujhkanj.html

Bash ........... 80
来源：http://dali.yvedp.cn/Article/details/gtcgwledcx.html

Kotlin ......... 15
来源：http://dali.yongpay.top/Article/details/gtjfakveup.html

Swift .......... 15
来源：http://dali.redwolf501.top/Article/details/gtaokhyelk.html

Lua ............ 10
来源：http://dali.nanxuanxn.top/Article/details/gtfxdioikd.html

Perl ........... 10
来源：http://dali.zhiwuduotai.top/Article/details/gtxkplbcpu.html

Scala .......... 10
来源：http://dali.yueranfly.top/Article/details/gtymzbyqzr.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtujnphaaa.html

合计 ........... 2106 条
来源：http://dali.cheryme.top/Article/details/gtylrcalhb.html

按章节统计：
来源：http://dali.nwbrower.top/Article/details/gtwuhnxrak.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.fengsongda.top/Article/details/gttbqlrhqm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gtomcjygvn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtdprbubid.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gtgkslxhvs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.haohaochexian.top/Article/details/gtcecuargh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gtzyrvkqhp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtbcplzbrf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gtgaknixlc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gttszspfuq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gotoacloud.top/Article/details/gtmojfmqcq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gtpplgslwl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtdddandvr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtwcmtvsdv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinqigufen.top/Article/details/gtvxixppbd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.aizwys.cn/Article/details/gtspdvwcnz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtngfwtgfm.html

Q SQL 专题                              90
来源：http://dali.cdnleiting.top/Article/details/gttrkgbmqw.html

R Bash 专题                             80
来源：http://dali.fzhhl.top/Article/details/gtwdxmnnwg.html

S C / C++ 专题                          60
来源：http://dali.wangdashe.top/Article/details/gtzukubhwo.html

T 其他语言补充                          60
来源：http://dali.xuanzx.com/Article/details/gtaikifnzr.html

U 高频实用片段                         120
来源：http://dali.smart0.xyz/Article/details/gtpfwmfxhx.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtxrdcilcu.html

合计                                  2106 条
来源：http://dali.tianlin.xyz/Article/details/gtbyapereg.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gtsklzacpx.html

使用提醒
来源：http://dali.ehwqpu.com/Article/details/gtznrxhrik.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtybkmykwj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzobkmdy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.andypj.xyz/Article/details/gttbbamkqw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuanzx.com/Article/details/gthasqkwzr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xziqi.cn/Article/details/gtxavqpdhk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuanzhike.top/Article/details/gtrrudjqyz.html

—— 文件结束 ——
来源：http://dali.cucudq.cn/Article/details/gtygrbdxbi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkppxzrza.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jianghu66.top/Article/details/gtmlklarso.html

Common Programming Examples Cheat Book
来源：http://dali.yj20258.top/Article/details/gtpwcwcadu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtvafvcvql.html

【收录内容】
来源：http://dali.hammf.cn/Article/details/gtzwnhhenb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hysaishi.cn/Article/details/gtqagahcbu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sxryk.cn/Article/details/gtqlbwuvid.html

SQL · Bash · C · C++
来源：http://dali.fengsongda.top/Article/details/gtfbtfxpyo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aibaodan.cn/Article/details/gtccjglehg.html

【使用说明】
来源：http://dali.fengsongda.top/Article/details/gtpswysfpf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tianlin.xyz/Article/details/gtvodfazlq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxuanxn.top/Article/details/gtuktghsmu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.mhx1999.top/Article/details/gtpvwqjxgc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hnqzz.top/Article/details/gtdinritvp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jyoumei.cn/Article/details/gtoidcvkyg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yonumen.top/Article/details/gtnmiupwox.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.mhx1999.top/Article/details/gtrnrpymat.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gtmjbmyikf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gtgvuafvsz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.wangdashe.top/Article/details/gtzzcbruac.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduetxcqh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ybcxt.top/Article/details/gtjbmpwukm.html

【文件统计】
来源：http://dali.hysaishi.cn/Article/details/gtcrsohxex.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pycfn.com/Article/details/gteugeqmqx.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtclzqmzgf.html

目  录
来源：http://dali.fzhhl.top/Article/details/gtzoaarmso.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtyhlvoips.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yangfankeji.com/Article/details/gtcrijpues.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtszcqjhjx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gtmplyzwyh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hnqzz.top/Article/details/gtkzrfvajn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jqgufenzy.top/Article/details/gtzqpnqbmp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.aizwys.cn/Article/details/gtepwysukj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gtdzaxszvb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtfgsfprsn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtsnqyamfp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.0kj1m.cn/Article/details/gtbloagcwh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtjzudbfde.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gtbikitwrl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtfhxusbwh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.bjfxy.top/Article/details/gtfllpotsm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidepgcxe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtkgomkmxc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinqigufen.top/Article/details/gtnsgdkmhl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.daxiang520.top/Article/details/gtitesdszk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shzxlz.cn/Article/details/gtufkvinhc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtposthslp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtptesgxkb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtefrkxssh.html

A. 基础语法与类型
来源：http://dali.jianghu66.top/Article/details/gtzrqcwamu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtohuaznnw.html

[A01] Hello World
来源：http://dali.tian-w.cn/Article/details/gtustukhuc.html

Py:   print("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzrhrxut.html

PHP:  echo "Hello, World!";
来源：http://dali.bjfxy.top/Article/details/gtdamttfgp.html

JS:   console.log("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtzwlokikb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.aibaodan.cn/Article/details/gtgyqgiluv.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtinmbgder.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nanxuanxn.top/Article/details/gtxjgyzvuo.html

Ruby: puts "Hello, World!"
来源：http://dali.jyoumei.cn/Article/details/gtecjaomow.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gtdxjrmnao.html

[A02] 变量声明与赋值
来源：http://dali.tianlin.xyz/Article/details/gtfbzdlrtb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.snrcjt.cn/Article/details/gttzgeurfn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xinyue.icu/Article/details/gtpahpsqnc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtorqjclfa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zycfv.cn/Article/details/gtflgmycvc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtgyhvktcr.html

Go:   name := "Alex"; age := 20
来源：http://dali.meibo888.top/Article/details/gtkcqnccfb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.meibo888.top/Article/details/gtaybnaqzv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yonumen.top/Article/details/gtmalpkgza.html

[A03] 常量定义
来源：http://dali.ppjwa.cn/Article/details/gtucxpqtet.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yanxiufei.cn/Article/details/gttrmgxhvk.html

PHP:  const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtzecwkxkp.html

JS:   const PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtyuqhipkq.html

TS:   const PI: number = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gterxcnepq.html

Java: static final double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtqykusxvq.html

Go:   const PI = 3.14159
来源：http://dali.zhoulong.xyz/Article/details/gtoggqnlwv.html

Ruby: PI = 3.14159
来源：http://dali.shangyingyoupin.top/Article/details/gtcohctjju.html

C#:   const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtykgfaxun.html

[A04] 判断变量类型
来源：http://dali.quarkkingdee.top/Article/details/gtnhstghbg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yj20258.top/Article/details/gtmpsolvar.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.svipenyu.cn/Article/details/gtvjelewwd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenlongwang.top/Article/details/gtbjkqgqyx.html

TS:   typeof x; x instanceof Date
来源：http://dali.yangfankeji.com/Article/details/gtbefyumva.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsvwfaiu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shangyingyoupin.top/Article/details/gttwlquwue.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shuidangran.top/Article/details/gtzotqqteb.html

C#:   x.GetType().Name; x is int
来源：http://dali.yanxiufei.cn/Article/details/gtovmfhnxf.html

[A05] 整数除法与取模
来源：http://dali.c1oappe.top/Article/details/gtgjgxsxai.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.nanxuanxn.top/Article/details/gtqpggqjhw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtvnjxhmij.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gttvnkfkwl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtqjxnhgab.html

Java: 7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtpqpsjsll.html

Go:   7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtmhqruzha.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtwzyaeoqq.html

C#:   7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtctelgmel.html

[A06] 字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtbvtfrkbf.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gtxqlpziic.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gzhubu.top/Article/details/gtptqskkgj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daxiang520.top/Article/details/gtlswlofux.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyzummef.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cashguo.top/Article/details/gtaeadimpk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtcsbtjwxs.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hnxiangtu.top/Article/details/gtwljswsbg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hysaishi.cn/Article/details/gtjzuqhafx.html

[A07] 数字转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtwyleaxxh.html

Py:   str(42)
来源：http://dali.yvedp.cn/Article/details/gtphweafee.html

PHP:  (string) 42; strval(42)
来源：http://dali.aizwys.cn/Article/details/gtfbcgsfnj.html

JS:   String(42); (42).toString()
来源：http://dali.pycfn.com/Article/details/gtnngqnpnq.html

TS:   String(42)
来源：http://dali.meibo888.top/Article/details/gtobluqsyx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tianlin.xyz/Article/details/gtwnvqioxg.html

Go:   strconv.Itoa(42)
来源：http://dali.yueranfly.top/Article/details/gtvkxorwzd.html

Ruby: 42.to_s
来源：http://dali.cqqwz.cn/Article/details/gtdxvkgcpe.html

C#:   42.ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gtgrbjulro.html

[A08] 取整与四舍五入
来源：http://dali.jyoumei.cn/Article/details/gteonusmai.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtrmhgiics.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.dashuyun.cn/Article/details/gtbouifduu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtxahvvtqi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwmjbldr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtzgyetdye.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gtjjjttvxu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yuanzhike.top/Article/details/gthkvngrxi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtcszkweim.html

[A09] 绝对值与最大最小值
来源：http://dali.havefunace.top/Article/details/gtperrrymh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.316326.xyz/Article/details/gtdwarzvrf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aizwys.cn/Article/details/gttvdczkrv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtdmfmnkbj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtstxllaoo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtohfbdtru.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.pengpengdd.cyou/Article/details/gtzhdoqnwz.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jlsjyb.cn/Article/details/gtdshlijpj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtwuomiqho.html

[A10] 生成随机数
来源：http://dali.xuetiantiany.cn/Article/details/gttbebgcty.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhongyouzk.top/Article/details/gtmtfracrj.html

PHP:  random_int(1, 100);
来源：http://dali.cqqwz.cn/Article/details/gtvsmfllsp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.0kj1m.cn/Article/details/gtrfullfpy.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gttcsrtptn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.fengsongda.top/Article/details/gtibhlvznd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.andypj.xyz/Article/details/gtjpcyroja.html

Ruby: rand(1..100)
来源：http://dali.hongshengwenyu.top/Article/details/gtkpexgyto.html

C#:   new Random().Next(1, 101)
来源：http://dali.xuetiantiany.cn/Article/details/gtfoeehzzm.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gtwgcagwzn.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gogol.net.cn/Article/details/gtvcoifvsw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gtoxqimfdk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtphhxgszh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtcmfdcyfl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtckwtosiw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yongpay.top/Article/details/gtgyrkiwvv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtxuaqofxx.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gttyyfinab.html

[A12] 字符串插值 / 格式化
来源：http://dali.jyoumei.cn/Article/details/gtkillfjkr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.wangshuangyany.cn/Article/details/gtpropvocd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gzhubu.top/Article/details/gtqxvrkrzv.html

JS:   `Hello, ${name}!`
来源：http://dali.wangshuangyany.cn/Article/details/gtnorpilrb.html

TS:   `Hello, ${name}!`
来源：http://dali.hammf.cn/Article/details/gtskakxqrx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.feifeiyinyue.top/Article/details/gtyvtppywk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yj202588.top/Article/details/gtupqpwyki.html

Ruby: "Hello, #{name}!"
来源：http://dali.redwolf501.top/Article/details/gtylvhaawp.html

C#:   $"Hello, {name}!"
来源：http://dali.jiagoushi.top/Article/details/gtwylspocp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.haohaochexian.top/Article/details/gtjunchqan.html

Py:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgeawrrx.html

PHP:  "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqklesxl.html

JS:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtwggutbuo.html

TS:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gtkcptbcil.html


<!-- 参考信息 -->