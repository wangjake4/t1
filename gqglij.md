代发 wailian999

[U81] JS：初始化项目
来源：http://dali.bjfxy.top/Article/details/gtpqhyhxsq.html

npm init -y;  npm i express
来源：http://dali.sufxvd.cn/Article/details/gtvoiwvzuy.html

[U82] JS：package.json 脚本
来源：http://dali.zhengqikj.top/Article/details/gtyrmkptfn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dianchejie.cn/Article/details/gtnxyjzvbt.html

[U83] JS：ES Module 导入导出
来源：http://dali.haohaochexian.top/Article/details/gtkzdphzgv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gtlyfaacea.html

[U84] JS：CommonJS 写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqkrawoz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xuanzx.com/Article/details/gtkfqaklgo.html

[U85] JS：可选链
来源：http://dali.mhx1999.top/Article/details/gthnqzexab.html

a?.b?.c
来源：http://dali.yueranfly.top/Article/details/gttkzmvsrk.html

[U86] JS：空值合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnzmaazm.html

a ?? b
来源：http://dali.iojbl.cn/Article/details/gtuxgdwpoe.html

[U87] JS：解构默认值
来源：http://dali.ydzc1.top/Article/details/gtxknmyxyy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.bjfxy.top/Article/details/gtkdmrwprp.html

[U88] JS：对象展开合并
来源：http://dali.yanxiufei.cn/Article/details/gtsejugftb.html

{ ...a, ...b }
来源：http://dali.shangyingyoupin.top/Article/details/gtumhmuuvb.html

[U89] JS：数组去重
来源：http://dali.hfpthk.cn/Article/details/gtvjxwhuak.html

[...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtdiieyzpn.html

[U90] JS：数字数组排序
来源：http://dali.haohaochexian.top/Article/details/gtcpkgtfje.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtawdldago.html

[U91] JS：对象键值遍历
来源：http://dali.wangdashe.top/Article/details/gtldyzzcfv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.dianchejie.cn/Article/details/gtfpjdqxhd.html

[U92] JS：深拷贝
来源：http://dali.yvedp.cn/Article/details/gteyqyfdig.html

structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtxuyjbgyf.html

[U93] JS：模板字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfzihdds.html

`共 ${n} 条`
来源：http://dali.hywenlv.cn/Article/details/gtuikbavsv.html

[U94] JS：箭头函数
来源：http://dali.yvedp.cn/Article/details/gtbqvhyjrr.html

const double = x => x * 2;
来源：http://dali.yuanzhike.top/Article/details/gtuytkjdqj.html

[U95] JS：Promise 包装
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqecdopb.html

new Promise((resolve, reject) => {})
来源：http://dali.shzxlz.cn/Article/details/gtddkdlmih.html

[U96] JS：async/await 与异常
来源：http://dali.daria6918.cn/Article/details/gtngydzlmg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtopedfxcx.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkitmgydt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtecjmbnaa.html

[U98] JS：fetch 带 JSON
来源：http://dali.andypj.xyz/Article/details/gtioygrheh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hywenlv.cn/Article/details/gtyzbbksys.html

[U99] JS：事件监听
来源：http://dali.jyoumei.cn/Article/details/gtgqfbajyx.html

el.addEventListener("click", e => {})
来源：http://dali.aibaodan.cn/Article/details/gthzvuvfbb.html

[U100] JS：DOM 查询
来源：http://dali.smart0.xyz/Article/details/gttvjmqegd.html

document.querySelector(".item")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuwwuwzc.html

[U101] JS：classList 操作
来源：http://dali.wangdashe.top/Article/details/gtnupptmhm.html

el.classList.toggle("active")
来源：http://dali.svipenyu.cn/Article/details/gtatvikbec.html

[U102] JS：本地存储
来源：http://dali.yanxiufei.cn/Article/details/gtjpoacyum.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daria6918.cn/Article/details/gtyayxkhqe.html

[U103] JS：定时器
来源：http://dali.gotoacloud.top/Article/details/gtatqrkwii.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigufen.top/Article/details/gtkjhhepwt.html

[U104] JS：防抖
来源：http://dali.zhixingplan.top/Article/details/gtsvvgoxpm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtrlaoomot.html

[U105] JS：节流
来源：http://dali.xuetiantiany.cn/Article/details/gtsgsxgzdk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.9152youxi.cn/Article/details/gtkgyqgvhv.html

[U106] JS：日期格式化
来源：http://dali.hammf.cn/Article/details/gtudloowbx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.0kj1m.cn/Article/details/gtxtdyhtpw.html

[U107] JS：数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtiuswwamo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtfowffocw.html

[U108] JS：随机整数
来源：http://dali.sufxvd.cn/Article/details/gtlgecckon.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cheryme.top/Article/details/gtxmplmott.html

[U109] JS：数组分组
来源：http://dali.smart0.xyz/Article/details/gtcyjvtzoc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtruevjqgf.html

[U110] JS：数组分块
来源：http://dali.fengsongda.top/Article/details/gtnwkvqkgv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.mhx1999.top/Article/details/gtnwdmspvl.html

[U111] JS：对象转 Map
来源：http://dali.dianchejie.cn/Article/details/gtwsjsyoyv.html

new Map(Object.entries(obj))
来源：http://dali.316326.xyz/Article/details/gtveqsnqvs.html

[U112] JS：字符串补位
来源：http://dali.jyoumei.cn/Article/details/gtdbhvrjdx.html

"7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtzaxmdium.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gtdmjhqstb.html

s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtmahvicmq.html

[U114] JS：JSON 深比较
来源：http://dali.yuanzhike.top/Article/details/gtltfatmjg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtlrqasfpk.html

[U115] JS：生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gtxkoubdvd.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gttznbbztn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.mhx1999.top/Article/details/gtdloxqtuq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmobbomt.html

[U117] JS：单元测试
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxfsiopn.html

npm i -D vitest;  npx vitest
来源：http://dali.cashguo.top/Article/details/gtldzhwtqs.html

[U118] JS：开发服务器
来源：http://dali.sufxvd.cn/Article/details/gtglkltvey.html

npm i -D vite;  npx vite
来源：http://dali.tanke756.top/Article/details/gtfcbenbvp.html

[U119] JS：生产构建
来源：http://dali.haohaochexian.top/Article/details/gtofgbsiza.html

npx vite build
来源：http://dali.daria6918.cn/Article/details/gtxxoswyzx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgufenzy.top/Article/details/gtavfoekxc.html

import.meta.env.VITE_API_URL
来源：http://dali.redwolf501.top/Article/details/gtvrqqkwec.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtgivjagyu.html

统计汇总
来源：http://dali.0kj1m.cn/Article/details/gtplwdlgsh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthsfabrpw.html

按语言统计（条）：
来源：http://dali.jyoumei.cn/Article/details/gtsrjdvaap.html

Python ......... 252
来源：http://dali.kuanghao11.cn/Article/details/gthybbknrm.html

PHP ............ 252
来源：http://dali.chenjidiqi.icu/Article/details/gtqusosbov.html

JavaScript ..... 252
来源：http://dali.sysykeji.top/Article/details/gtybxxjopd.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gtykueufpq.html

Java ........... 212
来源：http://dali.andypj.xyz/Article/details/gtpiqcnkbj.html

Go ............. 212
来源：http://dali.yvedp.cn/Article/details/gtvfhhukcw.html

Ruby ........... 212
来源：http://dali.zdqjudy.top/Article/details/gtpaglafti.html

C# ............. 212
来源：http://dali.cdnleiting.top/Article/details/gtwmslqhzq.html

C .............. 30
来源：http://dali.xinyue.icu/Article/details/gtcrkkwhip.html

C++ ............ 30
来源：http://dali.haohaochexian.top/Article/details/gtnxxdcdiu.html

SQL ............ 90
来源：http://dali.pengpengdd.cyou/Article/details/gtdmpvybdd.html

Bash ........... 80
来源：http://dali.ehwqpu.com/Article/details/gtfhbsimlw.html

Kotlin ......... 15
来源：http://dali.jianghu66.top/Article/details/gtugidhflt.html

Swift .......... 15
来源：http://dali.wangdashe.top/Article/details/gtdnlmvumz.html

Lua ............ 10
来源：http://dali.xziqi.cn/Article/details/gtesmqrodn.html

Perl ........... 10
来源：http://dali.gaohongyu789.top/Article/details/gthnmsylui.html

Scala .......... 10
来源：http://dali.zhengqikj.top/Article/details/gtaljibcgl.html

------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtzpdjevyu.html

合计 ........... 2106 条
来源：http://dali.daxiang520.top/Article/details/gtlygrtesj.html

按章节统计：
来源：http://dali.cqqwz.cn/Article/details/gttdosprbp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtajhxmwtw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtunrbyfko.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtcnzifvmr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtgatqkiir.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ybcxt.top/Article/details/gtsoahuqwm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gtmmedmnam.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsfhrqef.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gtrefhjmtd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmbkaiwi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gtredinkco.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtvyoujnem.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtblhryukf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtknvquwbt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gtseitryax.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guowangkeji.top/Article/details/gtjohusxnw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtzczkccgt.html

Q SQL 专题                              90
来源：http://dali.gzhubu.top/Article/details/gtmxzegtgm.html

R Bash 专题                             80
来源：http://dali.jinqigufen.top/Article/details/gtounjkynt.html

S C / C++ 专题                          60
来源：http://dali.zhixingplan.top/Article/details/gtaetoclop.html

T 其他语言补充                          60
来源：http://dali.xuanzx.com/Article/details/gtozdwfaem.html

U 高频实用片段                         120
来源：http://dali.hnqzz.top/Article/details/gtnpbylpcm.html

------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtphgaqqvr.html

合计                                  2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gtplqdbnwn.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gttnkixjjk.html

使用提醒
来源：http://dali.tanke756.top/Article/details/gtstakynhl.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtmwfwwteq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cashguo.top/Article/details/gtvlegytux.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.redwolf501.top/Article/details/gttqvkplpd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhengqikj.top/Article/details/gtsmvqodnt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gtygnhdveq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jyoumei.cn/Article/details/gtmxoforou.html

—— 文件结束 ——
来源：http://dali.xuetiantiany.cn/Article/details/gtshetdswm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthhlrqadt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.snrcjt.cn/Article/details/gtwwjuucvw.html

Common Programming Examples Cheat Book
来源：http://dali.jinghuilouyu.cn/Article/details/gtakgcliel.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgtehlwxt.html

【收录内容】
来源：http://dali.cheryme.top/Article/details/gtxgiqyrrn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.andypj.xyz/Article/details/gtumindcxy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.haohaochexian.top/Article/details/gtsjkmysln.html

SQL · Bash · C · C++
来源：http://dali.jinqigufen.top/Article/details/gtrgetetpb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jqgufenzy.top/Article/details/gtanjyobtv.html

【使用说明】
来源：http://dali.svipenyu.cn/Article/details/gtxwxguaxr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinqigfzy.top/Article/details/gtpsyneukz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnwfbeqm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zycfv.cn/Article/details/gtqurqxwuf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tian-w.cn/Article/details/gtqixjlopt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jiagoushi.top/Article/details/gtugvadgok.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gtkzxhrumx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.fzhhl.top/Article/details/gtgzzqtcfo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ppjwa.cn/Article/details/gterpxdlkm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.kuanghao11.cn/Article/details/gtbglxdzqr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shzxlz.cn/Article/details/gtghesmyxb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yanxiufei.cn/Article/details/gtitqrklcv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj20258888.top/Article/details/gtwmfesjmr.html

【文件统计】
来源：http://dali.feifeiyinyue.top/Article/details/gtmzltqygo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yuxming.cn/Article/details/gtwoxpecmw.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtgvfdxbjd.html

目  录
来源：http://dali.jiagoushi.top/Article/details/gtsqommjej.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtqdqxzcpv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.redwolf501.top/Article/details/gtpgolqogj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gtiostcbtp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gtmmguzgbt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sxryk.cn/Article/details/gtnnwpixas.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenjidiqi.icu/Article/details/gthfhkzsiv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnvscabl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gtjmiokpqw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.guannengcc.top/Article/details/gtqvqifpkz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtwnuhdpmp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjgesakq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtlnljdlhf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtymtuitiz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtefbjlvup.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gthwrzjkub.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tianlin.xyz/Article/details/gtwsgcualf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiohzdspt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gogol.net.cn/Article/details/gtxqnsoirh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hammf.cn/Article/details/gtgjabyrrx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yvedp.cn/Article/details/gtfyaeahsf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtqgnbrzfb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gteqhcpipi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtblbhjawy.html

A. 基础语法与类型
来源：http://dali.ppjwa.cn/Article/details/gtuoamiqig.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtkjnfscro.html

[A01] Hello World
来源：http://dali.jianghu66.top/Article/details/gtdlymoajs.html

Py:   print("Hello, World!")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjeqkbad.html

PHP:  echo "Hello, World!";
来源：http://dali.feifeiyinyue.top/Article/details/gtilcwenet.html

JS:   console.log("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gtkeyyutlk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cqqwz.cn/Article/details/gtdyxriuaa.html

Java: System.out.println("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gtkjdfxwgu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gtxnizeozs.html

Ruby: puts "Hello, World!"
来源：http://dali.shangyingyoupin.top/Article/details/gtokzgmewi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtoaxpmxvr.html

[A02] 变量声明与赋值
来源：http://dali.zhongyouzk.top/Article/details/gttzxhcton.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jlsjyb.cn/Article/details/gtxauxqksw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtvywhqnyq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pycfn.com/Article/details/gtbjpfbzof.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtzzykrgxa.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtcclpcnnc.html

Go:   name := "Alex"; age := 20
来源：http://dali.redwolf501.top/Article/details/gtmnofdxst.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gogol.net.cn/Article/details/gtqwmqnbhh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtaqevhtex.html

[A03] 常量定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxodfquue.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.redwolf501.top/Article/details/gtbohmnson.html

PHP:  const PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtjncoktba.html

JS:   const PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtcerwelro.html

TS:   const PI: number = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtecwmgqwo.html

Java: static final double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtvcgmmlfg.html

Go:   const PI = 3.14159
来源：http://dali.pycfn.com/Article/details/gtdywkwoww.html

Ruby: PI = 3.14159
来源：http://dali.cashguo.top/Article/details/gtahiofagf.html

C#:   const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gttbljqkdy.html

[A04] 判断变量类型
来源：http://dali.bjfxy.top/Article/details/gtvvrsunix.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.316326.xyz/Article/details/gtegvlgkqj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.9152youxi.cn/Article/details/gtlctbnydx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shuidangran.top/Article/details/gtetavvwix.html

TS:   typeof x; x instanceof Date
来源：http://dali.yueranfly.top/Article/details/gtnyfdiffi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yonumen.top/Article/details/gtwxjwcjxn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.redwolf501.top/Article/details/gtrrbgqcpe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.daxiang520.top/Article/details/gtkhgdfpcm.html

C#:   x.GetType().Name; x is int
来源：http://dali.meibo888.top/Article/details/gtehnfumiv.html

[A05] 整数除法与取模
来源：http://dali.jinghuilouyu.cn/Article/details/gtutgoilln.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.bjfxy.top/Article/details/gtdpqevvra.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtpentfzzt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtflzdiicu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtuixvnqpn.html

Java: 7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtlchibeyd.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtxxwfywwd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtocysvtrx.html

C#:   7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtfzupftsl.html

[A06] 字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtddeuidnr.html

Py:   int("42"); float("3.14")
来源：http://dali.gogol.net.cn/Article/details/gtunegstvw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.aizwys.cn/Article/details/gtoxjqeftr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gtjuoktxza.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.birdmap.top/Article/details/gtjjtdkhyx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tanke756.top/Article/details/gtrxpkhryp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtfndkaitj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tianlin.xyz/Article/details/gtljhpjmwj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hysaishi.cn/Article/details/gttusgncfm.html

[A07] 数字转字符串
来源：http://dali.cheryme.top/Article/details/gtglofsyru.html

Py:   str(42)
来源：http://dali.sufxvd.cn/Article/details/gtkokpysjw.html

PHP:  (string) 42; strval(42)
来源：http://dali.ybcxt.top/Article/details/gtmrnlhlbi.html

JS:   String(42); (42).toString()
来源：http://dali.yueranfly.top/Article/details/gtvdzyyzug.html

TS:   String(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtbcoqzpbz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.pycfn.com/Article/details/gtdalvtogp.html

Go:   strconv.Itoa(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtqgjhfmtf.html

Ruby: 42.to_s
来源：http://dali.quarkkingdee.top/Article/details/gtjvplzymp.html

C#:   42.ToString()
来源：http://dali.kuanghao11.cn/Article/details/gtqjurusod.html

[A08] 取整与四舍五入
来源：http://dali.sxryk.cn/Article/details/gtpomynszn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gteyktdzgf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlkddmvp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gtawizwfcn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yvedp.cn/Article/details/gtvrjftmlh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gthgqguwmu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gtrtnptyzy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.pycfn.com/Article/details/gthhtirjpp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtaullmpvd.html

[A09] 绝对值与最大最小值
来源：http://dali.iojbl.cn/Article/details/gtwofmyhrt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtpwnvchwt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtzzwvlvxn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtcqzsqisz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacxqpnqo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtqxhdntky.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.meibo888.top/Article/details/gtchgchnra.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.meibo888.top/Article/details/gtmhnunrpd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyxnlbry.html

[A10] 生成随机数
来源：http://dali.yongpay.top/Article/details/gthgmoatto.html

Py:   import random; random.randint(1, 100)
来源：http://dali.9152youxi.cn/Article/details/gtejqitshg.html

PHP:  random_int(1, 100);
来源：http://dali.ppjwa.cn/Article/details/gttqoisctn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinqigufen.top/Article/details/gtrrwefjyn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yangfankeji.com/Article/details/gtxynpkqmf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj202588.top/Article/details/gtunuixieb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hongshengwenyu.top/Article/details/gtwdavisbc.html

Ruby: rand(1..100)
来源：http://dali.ydzc1.top/Article/details/gtkjbaovnr.html

C#:   new Random().Next(1, 101)
来源：http://dali.hammf.cn/Article/details/gtaxrssiza.html

[A11] 条件表达式（三元）
来源：http://dali.hysaishi.cn/Article/details/gtgvurwfql.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhengqikj.top/Article/details/gtxokpdtxn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gtgbhcinii.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gttgvvkyez.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gttvguagme.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtzmzdvwki.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhixingplan.top/Article/details/gtyhfleejr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtznazioch.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtcjortzwx.html

[A12] 字符串插值 / 格式化
来源：http://dali.tianlin.xyz/Article/details/gtigeohuvh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhiwuduotai.top/Article/details/gtfblxqswu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zycfv.cn/Article/details/gtelcysekj.html

JS:   `Hello, ${name}!`
来源：http://dali.yangfankeji.com/Article/details/gtwnrqivpm.html

TS:   `Hello, ${name}!`
来源：http://dali.ehwqpu.com/Article/details/gtijaakuah.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cdnleiting.top/Article/details/gtkvimxpiy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.vqdsnc.cn/Article/details/gtnxjamfma.html

Ruby: "Hello, #{name}!"
来源：http://dali.andypj.xyz/Article/details/gtscyrwktr.html

C#:   $"Hello, {name}!"
来源：http://dali.yvedp.cn/Article/details/gtcjqpigia.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cucudq.cn/Article/details/gteqouqtny.html

Py:   "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtqfubjvbp.html

PHP:  "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtsqmwbdtz.html

JS:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtmonxegjp.html

TS:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gthcfcqcuq.html


<!-- 参考信息 -->