代发 wailian999

[U79] PHP：静态分析
来源：http://dali.yueranfly.top/Article/details/gtncyqtclv.html

composer require --dev phpstan/phpstan
来源：http://dali.c1oappe.top/Article/details/gtcdqpwlxu.html

[U80] PHP：代码规范修复
来源：http://dali.iojbl.cn/Article/details/gtcjyexigv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shuidangran.top/Article/details/gtzjywgytg.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmckjlii.html

npm init -y;  npm i express
来源：http://dali.aibaodan.cn/Article/details/gtscwlnpqm.html

[U82] JS：package.json 脚本
来源：http://dali.quarkkingdee.top/Article/details/gtdyiihefp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.daria6918.cn/Article/details/gtetzjokiq.html

[U83] JS：ES Module 导入导出
来源：http://dali.pycfn.com/Article/details/gtjrsdjolk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gtkgjbuiat.html

[U84] JS：CommonJS 写法
来源：http://dali.cqqwz.cn/Article/details/gtuljuxyql.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.daxiang520.top/Article/details/gtwxxkzmki.html

[U85] JS：可选链
来源：http://dali.xuanzx.com/Article/details/gtjhxqdzjz.html

a?.b?.c
来源：http://dali.ppjwa.cn/Article/details/gtvmmfqkpq.html

[U86] JS：空值合并
来源：http://dali.yuanzhike.top/Article/details/gtuytqleru.html

a ?? b
来源：http://dali.xinyue.icu/Article/details/gtfjqxzefg.html

[U87] JS：解构默认值
来源：http://dali.smart0.xyz/Article/details/gtualiplda.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shuidangran.top/Article/details/gtxnvmemtt.html

[U88] JS：对象展开合并
来源：http://dali.nwbrower.top/Article/details/gttikdgpbv.html

{ ...a, ...b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdopewnkg.html

[U89] JS：数组去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarinpkdt.html

[...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtghqlytqu.html

[U90] JS：数字数组排序
来源：http://dali.havefunace.top/Article/details/gthvrhtztt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtxnoacpgq.html

[U91] JS：对象键值遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtezfnsmty.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.kuanghao11.cn/Article/details/gtpwoxowqw.html

[U92] JS：深拷贝
来源：http://dali.pycfn.com/Article/details/gtxqyvpiya.html

structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtfkbgykqz.html

[U93] JS：模板字符串
来源：http://dali.ivvv.top/Article/details/gtsjnfesbo.html

`共 ${n} 条`
来源：http://dali.yj202588.top/Article/details/gtbjjdyhvk.html

[U94] JS：箭头函数
来源：http://dali.yonumen.top/Article/details/gtoriqytda.html

const double = x => x * 2;
来源：http://dali.fengsongda.top/Article/details/gtwysshcbt.html

[U95] JS：Promise 包装
来源：http://dali.yueranfly.top/Article/details/gtviodfsog.html

new Promise((resolve, reject) => {})
来源：http://dali.aibaodan.cn/Article/details/gtipbbgsvx.html

[U96] JS：async/await 与异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqmrecku.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtszxszwka.html

[U97] JS：并发请求
来源：http://dali.mhx1999.top/Article/details/gtufuhnlfp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkqqwziv.html

[U98] JS：fetch 带 JSON
来源：http://dali.sxryk.cn/Article/details/gtvdqfuaqq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhoulong.xyz/Article/details/gtfwqmvogg.html

[U99] JS：事件监听
来源：http://dali.yongpay.top/Article/details/gtjwkfxcqi.html

el.addEventListener("click", e => {})
来源：http://dali.dashuyun.cn/Article/details/gtyogwtthy.html

[U100] JS：DOM 查询
来源：http://dali.chenlongwang.top/Article/details/gtlezldvka.html

document.querySelector(".item")
来源：http://dali.feifeiyinyue.top/Article/details/gtzzqaanli.html

[U101] JS：classList 操作
来源：http://dali.yangfankeji.com/Article/details/gtgguesmpo.html

el.classList.toggle("active")
来源：http://dali.hysaishi.cn/Article/details/gtpmcxlwvb.html

[U102] JS：本地存储
来源：http://dali.zhixingplan.top/Article/details/gtixpnwqhe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gotoacloud.top/Article/details/gtxeiploiu.html

[U103] JS：定时器
来源：http://dali.yuanzhike.top/Article/details/gtukyrwldc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.smart0.xyz/Article/details/gtvnkdatsu.html

[U104] JS：防抖
来源：http://dali.jinqigufen.top/Article/details/gtpatmljpc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtaztgburs.html

[U105] JS：节流
来源：http://dali.quarkkingdee.top/Article/details/gttvpcbdqj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtyjogyxvt.html

[U106] JS：日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtxcffwsou.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yuxming.cn/Article/details/gtrmuhpmbd.html

[U107] JS：数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtgytkuaxr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cheryme.top/Article/details/gtaexcfqbb.html

[U108] JS：随机整数
来源：http://dali.snrcjt.cn/Article/details/gtlnsaranb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hywenlv.cn/Article/details/gtffwwmlgw.html

[U109] JS：数组分组
来源：http://dali.gotoacloud.top/Article/details/gtvgwllzwa.html

Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gtmfawphna.html

[U110] JS：数组分块
来源：http://dali.aibaodan.cn/Article/details/gtshxfeuah.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhengqikj.top/Article/details/gtoxxcqicy.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gtthltprqq.html

new Map(Object.entries(obj))
来源：http://dali.aizwys.cn/Article/details/gttlqmqotl.html

[U112] JS：字符串补位
来源：http://dali.sweek.top/Article/details/gtnbaswhzi.html

"7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtyoawkfyc.html

[U113] JS：正则替换全部
来源：http://dali.smart0.xyz/Article/details/gtotognkwr.html

s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcbkhkwg.html

[U114] JS：JSON 深比较
来源：http://dali.hnxiangtu.top/Article/details/gtaepnpxst.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtcgvsnkyi.html

[U115] JS：生成 UUID
来源：http://dali.yj20258.top/Article/details/gtgnzqpccs.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtjqgrrftv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangdashe.top/Article/details/gtxbtkpsml.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinqigufen.top/Article/details/gtxrjzrfza.html

[U117] JS：单元测试
来源：http://dali.pycfn.com/Article/details/gtlimngexm.html

npm i -D vitest;  npx vitest
来源：http://dali.wangshuangyany.cn/Article/details/gtbsjcateo.html

[U118] JS：开发服务器
来源：http://dali.xuanzx.com/Article/details/gtsogweodn.html

npm i -D vite;  npx vite
来源：http://dali.wangdashe.top/Article/details/gtladljxwc.html

[U119] JS：生产构建
来源：http://dali.gotoacloud.top/Article/details/gteyegrzcl.html

npx vite build
来源：http://dali.hongshengwenyu.top/Article/details/gtduqdsdrv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xylfe.cn/Article/details/gtshkloiij.html

import.meta.env.VITE_API_URL
来源：http://dali.ivvv.top/Article/details/gtnpfljfkv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtcraelmyr.html

统计汇总
来源：http://dali.zhiwuduotai.top/Article/details/gtmayknaxc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtjfzjewpt.html

按语言统计（条）：
来源：http://dali.guannengcc.top/Article/details/gtpliolnel.html

Python ......... 252
来源：http://dali.yvedp.cn/Article/details/gtkyqiyklo.html

PHP ............ 252
来源：http://dali.aizwys.cn/Article/details/gthlmdaphb.html

JavaScript ..... 252
来源：http://dali.nwbrower.top/Article/details/gtyztxmjaj.html

TypeScript ..... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxvseshp.html

Java ........... 212
来源：http://dali.hammf.cn/Article/details/gtquoosylb.html

Go ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gtqfoctijh.html

Ruby ........... 212
来源：http://dali.zhixingplan.top/Article/details/gtalfvjghv.html

C# ............. 212
来源：http://dali.hnqzz.top/Article/details/gtzexvbigf.html

C .............. 30
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmidargrs.html

C++ ............ 30
来源：http://dali.hfpthk.cn/Article/details/gtxgxthroj.html

SQL ............ 90
来源：http://dali.jyoumei.cn/Article/details/gtlurmqqgy.html

Bash ........... 80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjxvqmya.html

Kotlin ......... 15
来源：http://dali.shzxlz.cn/Article/details/gtaxqfdckk.html

Swift .......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gtxkdsdyfq.html

Lua ............ 10
来源：http://dali.sweek.top/Article/details/gtalnqrwtj.html

Perl ........... 10
来源：http://dali.sweek.top/Article/details/gtwomssign.html

Scala .......... 10
来源：http://dali.fzhhl.top/Article/details/gtfbtgblpi.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtiihpqawm.html

合计 ........... 2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxotonav.html

按章节统计：
来源：http://dali.gaohongyu789.top/Article/details/gtreenmjhx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gtusvdvwex.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrtecomt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gtdbrrraer.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtanfehqzr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhengqikj.top/Article/details/gtcapuymex.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gtkqlamwww.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hfpthk.cn/Article/details/gtceqwajsi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gttvxyomib.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtjbsweoqu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gtvcvwzfdk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtakeedtgj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gttasguodl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtwhlqfwra.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gtcotugzpj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhoulong.xyz/Article/details/gtqrlwwffu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtvmyrwlxv.html

Q SQL 专题                              90
来源：http://dali.haohaochexian.top/Article/details/gtgbkhochb.html

R Bash 专题                             80
来源：http://dali.yvedp.cn/Article/details/gtkjzzwuhz.html

S C / C++ 专题                          60
来源：http://dali.cqqwz.cn/Article/details/gtvzisqick.html

T 其他语言补充                          60
来源：http://dali.jinqigfzy.top/Article/details/gtxawcbraa.html

U 高频实用片段                         120
来源：http://dali.pycfn.com/Article/details/gtmarsaxdv.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtmkclfttj.html

合计                                  2106 条
来源：http://dali.zhixingplan.top/Article/details/gthekujjha.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gtlxbqpqui.html

使用提醒
来源：http://dali.yvedp.cn/Article/details/gtscvwolqq.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwzfwtdw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxinkj.top/Article/details/gtvuymkrpg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.feifeiyinyue.top/Article/details/gtnouylkfu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gzhubu.top/Article/details/gtojhuolnt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tianlin.xyz/Article/details/gtdabjhzto.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhixingplan.top/Article/details/gtfoztjqqe.html

—— 文件结束 ——
来源：http://dali.nwbrower.top/Article/details/gttofwdpfc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrmsjrikd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ivvv.top/Article/details/gtnygmqjqb.html

Common Programming Examples Cheat Book
来源：http://dali.zhongyouzk.top/Article/details/gtkypvqupu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlozaelrz.html

【收录内容】
来源：http://dali.jqgufenzy.top/Article/details/gtdadlnsqr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinyuanbaomall.cn/Article/details/gteaevwpxq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ybcxt.top/Article/details/gtumagaslq.html

SQL · Bash · C · C++
来源：http://dali.yueranfly.top/Article/details/gtsntmxzyo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hammf.cn/Article/details/gtwxfxgmjo.html

【使用说明】
来源：http://dali.ydzc1.top/Article/details/gtesoomuvy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhiwuduotai.top/Article/details/gtwpybdkgb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cdnleiting.top/Article/details/gtewsbfreo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cucudq.cn/Article/details/gtsibiamjh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgfzy.top/Article/details/gttmvnucza.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhiwuduotai.top/Article/details/gtorrnjvcz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hongshengwenyu.top/Article/details/gtnpouffcx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jqgufenzy.top/Article/details/gthadwijge.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.snrcjt.cn/Article/details/gtjclxioqe.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.meibo888.top/Article/details/gtsosxprkj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shangyingyoupin.top/Article/details/gttiodufkq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhixingplan.top/Article/details/gtxuhmhyhb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yueranfly.top/Article/details/gtiutxdtis.html

【文件统计】
来源：http://dali.yonumen.top/Article/details/gtqpqybwti.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.daria6918.cn/Article/details/gtvttrceok.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtikpdaxfy.html

目  录
来源：http://dali.hongshengwenyu.top/Article/details/gtpajdbpox.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gtvmntwdrr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gttmxmvssa.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtfdbxhktt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sysykeji.top/Article/details/gtxswnvvdg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gtlgrpmwnj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.snrcjt.cn/Article/details/gtinaghdqz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hnqzz.top/Article/details/gtzpjgyazi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258888.top/Article/details/gtupksvgbc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gtxvldkxqv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gthkzgmdxe.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtwhsqsmxl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtqchlhquc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtrsndithc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtxovpvcvl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gtibzdqukw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhorsqaz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvgmhriz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ppjwa.cn/Article/details/gtgytntgxi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gtltmixcyr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yvedp.cn/Article/details/gtnxbocket.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtanbymhmj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtccagnfnf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifkwwmfy.html

A. 基础语法与类型
来源：http://dali.0kj1m.cn/Article/details/gtdbwmjjxs.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmnfucic.html

[A01] Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgpbuipv.html

Py:   print("Hello, World!")
来源：http://dali.wangdashe.top/Article/details/gtrrtllrjd.html

PHP:  echo "Hello, World!";
来源：http://dali.yuanzhike.top/Article/details/gtoifwrvxu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gtlanjnvbt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jianghu66.top/Article/details/gtvjkizyxg.html

Java: System.out.println("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gttmjknrrd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoaptvvy.html

Ruby: puts "Hello, World!"
来源：http://dali.tianlin.xyz/Article/details/gtuojpivfu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtlzlhohpv.html

[A02] 变量声明与赋值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpuwzguv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.kuanghao11.cn/Article/details/gtehvczomp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cqqwz.cn/Article/details/gtxdjengdl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtylpdoahs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtrgcdliiq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tianlin.xyz/Article/details/gtdlcyeguz.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenlongwang.top/Article/details/gtigwanwsp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jlsjyb.cn/Article/details/gtlvqwchrg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtispbekey.html

[A03] 常量定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlhhadle.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.aizwys.cn/Article/details/gtidfnqkrt.html

PHP:  const PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtgjwtrurh.html

JS:   const PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtowfkvtws.html

TS:   const PI: number = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtdofuemto.html

Java: static final double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtvqpjeyzk.html

Go:   const PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gtfxrpihnp.html

Ruby: PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gtdargayqi.html

C#:   const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gticfhcnfl.html

[A04] 判断变量类型
来源：http://dali.cqqwz.cn/Article/details/gtbjhgwyub.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigufen.top/Article/details/gtbeaafdqc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xziqi.cn/Article/details/gtlvixrygz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinqigfzy.top/Article/details/gtkeeeptpb.html

TS:   typeof x; x instanceof Date
来源：http://dali.cdnleiting.top/Article/details/gtaforlyoy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.redwolf501.top/Article/details/gtgjdxpjzi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hysaishi.cn/Article/details/gtusvxypkp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cucudq.cn/Article/details/gtmcvmptpd.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbhdjtzf.html

[A05] 整数除法与取模
来源：http://dali.cdnleiting.top/Article/details/gtfmkprhpr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sufxvd.cn/Article/details/gtgdlibinb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.pycfn.com/Article/details/gtgkzngoyl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtsaswexsx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtvcohornl.html

Java: 7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtkfyysgga.html

Go:   7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtgvolgtic.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtpsaezsje.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtnchjsfuy.html

[A06] 字符串转数字
来源：http://dali.xuanzx.com/Article/details/gtunxnmngr.html

Py:   int("42"); float("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gthvizoazy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.aibaodan.cn/Article/details/gtnelsifxl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangdashe.top/Article/details/gtvfimohtz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.redwolf501.top/Article/details/gtjseftmdy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtymyfnw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cashguo.top/Article/details/gtgfcygqin.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinghuilouyu.cn/Article/details/gtcttqrlmk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.daria6918.cn/Article/details/gtbuypekqe.html

[A07] 数字转字符串
来源：http://dali.smart0.xyz/Article/details/gtpjvfwhxm.html

Py:   str(42)
来源：http://dali.smart0.xyz/Article/details/gthydmxfhj.html

PHP:  (string) 42; strval(42)
来源：http://dali.yueranfly.top/Article/details/gtbsclgnrz.html

JS:   String(42); (42).toString()
来源：http://dali.zhoulong.xyz/Article/details/gtntfugxdf.html

TS:   String(42)
来源：http://dali.zhengqikj.top/Article/details/gtxlebdnoq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gogol.net.cn/Article/details/gttafuiwoz.html

Go:   strconv.Itoa(42)
来源：http://dali.ivvv.top/Article/details/gthqndfoms.html

Ruby: 42.to_s
来源：http://dali.jianghu66.top/Article/details/gtnbopswfy.html

C#:   42.ToString()
来源：http://dali.guowangkeji.top/Article/details/gtejxxypfk.html

[A08] 取整与四舍五入
来源：http://dali.tian-w.cn/Article/details/gtjzuqfgrv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtozsjssju.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.0kj1m.cn/Article/details/gtlangoyvl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtjtynyzeo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gotoacloud.top/Article/details/gtuxwbmzhz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gtmpshvulq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.haohaochexian.top/Article/details/gtgcsxzhfa.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj20258888.top/Article/details/gtekjauikm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtggqhmngr.html

[A09] 绝对值与最大最小值
来源：http://dali.yj202588.top/Article/details/gtdsorliki.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gttvlkduev.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtintaspwv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yongpay.top/Article/details/gtelinagqk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtvoojdgbd.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtepzzdfxx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhengqikj.top/Article/details/gtrulrmjey.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shangyingyoupin.top/Article/details/gtjwwuhtcb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtfkqmmqxg.html

[A10] 生成随机数
来源：http://dali.tanke756.top/Article/details/gtncoocijq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.chenzaomai.com/Article/details/gtoplugsme.html

PHP:  random_int(1, 100);
来源：http://dali.yj202588.top/Article/details/gtynccjmnt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtpolvuiuw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zdqjudy.top/Article/details/gtjcozenpj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.havefunace.top/Article/details/gthrglyvye.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yangfankeji.com/Article/details/gtdflwdnld.html

Ruby: rand(1..100)
来源：http://dali.daxiang520.top/Article/details/gtzvxgfcwv.html

C#:   new Random().Next(1, 101)
来源：http://dali.daxiang520.top/Article/details/gtxdvspjwk.html

[A11] 条件表达式（三元）
来源：http://dali.sufxvd.cn/Article/details/gtfqcycwtu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yangfankeji.com/Article/details/gtlbrlyrif.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gthmfcikft.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gtxuxdlnam.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtnqaojhhv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtauaphkyd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.fzhhl.top/Article/details/gtmotgedil.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtekfhdpva.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtuincxium.html

[A12] 字符串插值 / 格式化
来源：http://dali.sxryk.cn/Article/details/gtlqzgzxxc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hnxiangtu.top/Article/details/gtpvhjosht.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.dianchejie.cn/Article/details/gtiantxqlw.html

JS:   `Hello, ${name}!`
来源：http://dali.tian-w.cn/Article/details/gtbpxtbknu.html

TS:   `Hello, ${name}!`
来源：http://dali.jlsjyb.cn/Article/details/gtyzbjuqps.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yangfankeji.com/Article/details/gtovzxbdmq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jlsjyb.cn/Article/details/gtwujefcfr.html

Ruby: "Hello, #{name}!"
来源：http://dali.daxiang520.top/Article/details/gtschpfikr.html

C#:   $"Hello, {name}!"
来源：http://dali.yanxiufei.cn/Article/details/gthbqdokfg.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.gogol.net.cn/Article/details/gtjqqydpsh.html


<!-- 参考信息 -->