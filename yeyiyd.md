代发 wailian999

[U81] JS：初始化项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqzvjdzj.html

npm init -y;  npm i express
来源：http://dali.tian-w.cn/Article/details/gtisgwnhgu.html

[U82] JS：package.json 脚本
来源：http://dali.316326.xyz/Article/details/gtoqmynkzn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhongyouzk.top/Article/details/gtbuilqqfa.html

[U83] JS：ES Module 导入导出
来源：http://dali.tian-w.cn/Article/details/gtjrsddzex.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gtiaxwciif.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gtyqzqzpkz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmedumcoo.html

[U85] JS：可选链
来源：http://dali.gzhubu.top/Article/details/gtbnmvmvwa.html

a?.b?.c
来源：http://dali.xinyue.icu/Article/details/gtzrafabvg.html

[U86] JS：空值合并
来源：http://dali.dianchejie.cn/Article/details/gthjpoccat.html

a ?? b
来源：http://dali.ydzc1.top/Article/details/gtzmtjgave.html

[U87] JS：解构默认值
来源：http://dali.kuanghao11.cn/Article/details/gtqthyopyp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcddqllgs.html

[U88] JS：对象展开合并
来源：http://dali.xuetiantiany.cn/Article/details/gtfyqfdqvo.html

{ ...a, ...b }
来源：http://dali.wangshuangyany.cn/Article/details/gtobovriqy.html

[U89] JS：数组去重
来源：http://dali.yvedp.cn/Article/details/gtvutxgaao.html

[...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtkluyjrqr.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gtuknjgnat.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtwffgkhpy.html

[U91] JS：对象键值遍历
来源：http://dali.ybcxt.top/Article/details/gtlgrxqjyi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.andypj.xyz/Article/details/gtzipieele.html

[U92] JS：深拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtabqsbtnv.html

structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtswalsxcc.html

[U93] JS：模板字符串
来源：http://dali.nanxuanxn.top/Article/details/gtmjgstque.html

`共 ${n} 条`
来源：http://dali.jlsjyb.cn/Article/details/gtnqjlthui.html

[U94] JS：箭头函数
来源：http://dali.xylfe.cn/Article/details/gtokcyrfga.html

const double = x => x * 2;
来源：http://dali.wangdashe.top/Article/details/gtuucvlcjq.html

[U95] JS：Promise 包装
来源：http://dali.andypj.xyz/Article/details/gtyopsqpjf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhoulong.xyz/Article/details/gtfkwmekew.html

[U96] JS：async/await 与异常
来源：http://dali.yj202588.top/Article/details/gtqsuofgom.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gthlgequfb.html

[U97] JS：并发请求
来源：http://dali.gotoacloud.top/Article/details/gtpskbhgic.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtnalrchqu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtijiuregg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.andypj.xyz/Article/details/gtwzgxvfya.html

[U99] JS：事件监听
来源：http://dali.yj20258888.top/Article/details/gtclyaslhb.html

el.addEventListener("click", e => {})
来源：http://dali.xziqi.cn/Article/details/gtnnpduhnd.html

[U100] JS：DOM 查询
来源：http://dali.ppjwa.cn/Article/details/gtituakrve.html

document.querySelector(".item")
来源：http://dali.yvedp.cn/Article/details/gtbhjovlbt.html

[U101] JS：classList 操作
来源：http://dali.snrcjt.cn/Article/details/gtdoixgbtd.html

el.classList.toggle("active")
来源：http://dali.ivvv.top/Article/details/gtgxopiwkv.html

[U102] JS：本地存储
来源：http://dali.hysaishi.cn/Article/details/gtlkwwrybm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsjrfiuv.html

[U103] JS：定时器
来源：http://dali.xuanzx.com/Article/details/gtkkrljhnm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsimapvx.html

[U104] JS：防抖
来源：http://dali.zhengqikj.top/Article/details/gtvkqitvab.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtxpfffggh.html

[U105] JS：节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqkvnrqh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtsmjyjpcy.html

[U106] JS：日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtsrxlzouy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenzaomai.com/Article/details/gtfvlslwfh.html

[U107] JS：数字千分位
来源：http://dali.zycfv.cn/Article/details/gtcauxzucy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfbobehz.html

[U108] JS：随机整数
来源：http://dali.jqgfzy.top/Article/details/gtwkviwwkg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdmsgpyf.html

[U109] JS：数组分组
来源：http://dali.xziqi.cn/Article/details/gtdtsixmob.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gtocszgwop.html

[U110] JS：数组分块
来源：http://dali.316326.xyz/Article/details/gtlyncpiqa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.iojbl.cn/Article/details/gtpshzptnn.html

[U111] JS：对象转 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gttriaexim.html

new Map(Object.entries(obj))
来源：http://dali.jlsjyb.cn/Article/details/gteckdgznj.html

[U112] JS：字符串补位
来源：http://dali.smart0.xyz/Article/details/gtamhzcbuu.html

"7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtgrzjvusz.html

[U113] JS：正则替换全部
来源：http://dali.snrcjt.cn/Article/details/gttrvwdbni.html

s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtklczecca.html

[U114] JS：JSON 深比较
来源：http://dali.tianlin.xyz/Article/details/gtaxygtpix.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtbmnjdotl.html

[U115] JS：生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gtxgejlrmk.html

crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtixjqllwg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenzaomai.com/Article/details/gtbjkdfekq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guannengcc.top/Article/details/gtqtgseqzw.html

[U117] JS：单元测试
来源：http://dali.andypj.xyz/Article/details/gteazagdga.html

npm i -D vitest;  npx vitest
来源：http://dali.zhongyouzk.top/Article/details/gthgtxhzcg.html

[U118] JS：开发服务器
来源：http://dali.gotoacloud.top/Article/details/gtlpsufvff.html

npm i -D vite;  npx vite
来源：http://dali.tanke756.top/Article/details/gtghlvthee.html

[U119] JS：生产构建
来源：http://dali.hnxiangtu.top/Article/details/gtduxbuias.html

npx vite build
来源：http://dali.chenlongwang.top/Article/details/gtwsjtazyh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.9152youxi.cn/Article/details/gthblbmtqw.html

import.meta.env.VITE_API_URL
来源：http://dali.daria6918.cn/Article/details/gtgpegbcbc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtidcdioxq.html

统计汇总
来源：http://dali.yj20258888.top/Article/details/gtikkuntgz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxwremmp.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gtdznyyhgj.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gtfjxicibu.html

PHP ............ 252
来源：http://dali.cheryme.top/Article/details/gtqxucrsof.html

JavaScript ..... 252
来源：http://dali.jqgfzy.top/Article/details/gthxvngbkf.html

TypeScript ..... 212
来源：http://dali.smart0.xyz/Article/details/gtvjfejgav.html

Java ........... 212
来源：http://dali.zhengqikj.top/Article/details/gtnwsjrtjm.html

Go ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gtxvaalmcf.html

Ruby ........... 212
来源：http://dali.feifeiyinyue.top/Article/details/gtofynoyew.html

C# ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtrgnvfqpt.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxjxknbb.html

C++ ............ 30
来源：http://dali.zhoulong.xyz/Article/details/gtxurxopvn.html

SQL ............ 90
来源：http://dali.xuanzx.com/Article/details/gtptvnnndq.html

Bash ........... 80
来源：http://dali.sweek.top/Article/details/gtenogrlnh.html

Kotlin ......... 15
来源：http://dali.ydzc1.top/Article/details/gtglngtesa.html

Swift .......... 15
来源：http://dali.zhixingplan.top/Article/details/gtcfurdtsm.html

Lua ............ 10
来源：http://dali.yuanzhike.top/Article/details/gtcfeqahtk.html

Perl ........... 10
来源：http://dali.cqqwz.cn/Article/details/gtoxlagkfa.html

Scala .......... 10
来源：http://dali.ehwqpu.com/Article/details/gttkuuorpu.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtfihksads.html

合计 ........... 2106 条
来源：http://dali.xuanzx.com/Article/details/gtygssmizf.html

按章节统计：
来源：http://dali.redwolf501.top/Article/details/gtwfbasmop.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gtoiunifyj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gtcacbwnde.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtrhbsyzjq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gtsqtiigbv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cheryme.top/Article/details/gtudfnhsdg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gtkcwveldm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gteaihcmiy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gtgtbuobcc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtblsbvdtc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhongyouzk.top/Article/details/gtawfjfhof.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtppqugbro.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtowuepwig.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtbcuilukx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gtfecebkll.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.andypj.xyz/Article/details/gtmtirdnja.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtjibwmzna.html

Q SQL 专题                              90
来源：http://dali.sysykeji.top/Article/details/gtqnffrwwr.html

R Bash 专题                             80
来源：http://dali.yj202588.top/Article/details/gtzktvixda.html

S C / C++ 专题                          60
来源：http://dali.hnqzz.top/Article/details/gtjnjeuyix.html

T 其他语言补充                          60
来源：http://dali.sweek.top/Article/details/gteijwyqfx.html

U 高频实用片段                         120
来源：http://dali.yj202588.top/Article/details/gtjglpepud.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtcicgyylu.html

合计                                  2106 条
来源：http://dali.tianlin.xyz/Article/details/gtjrwbhhbb.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gteotgpvrd.html

使用提醒
来源：http://dali.shangyingyoupin.top/Article/details/gthxdovbcx.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtbzayxkvp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yanxiufei.cn/Article/details/gtjovpcstk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yangfankeji.com/Article/details/gtriuuhrjy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.birdmap.top/Article/details/gtbgqnvwmc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cheryme.top/Article/details/gthwzinykp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hysaishi.cn/Article/details/gthstslrej.html

—— 文件结束 ——
来源：http://dali.sweek.top/Article/details/gtlqkjlwok.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrlfrgdgy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.smart0.xyz/Article/details/gtlzspvqrk.html

Common Programming Examples Cheat Book
来源：http://dali.xziqi.cn/Article/details/gtyncsxjvg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcybsarig.html

【收录内容】
来源：http://dali.yj20258888.top/Article/details/gtutocyrfh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.vqdsnc.cn/Article/details/gtgucazanf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinqigfzy.top/Article/details/gtsbbfknlf.html

SQL · Bash · C · C++
来源：http://dali.bjfxy.top/Article/details/gtyhpcgxou.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.guannengcc.top/Article/details/gtmvwyjykb.html

【使用说明】
来源：http://dali.daxiang520.top/Article/details/gtllptjyxl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.iojbl.cn/Article/details/gtqmntejwv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xziqi.cn/Article/details/gtgnduirwu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jiagoushi.top/Article/details/gtdiblymnv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.daria6918.cn/Article/details/gtmtefreip.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jlsjyb.cn/Article/details/gthaujarzk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sweek.top/Article/details/gtsrndcxvs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zdqjudy.top/Article/details/gtlsuoddtd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.316326.xyz/Article/details/gtdwafpbuu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cashguo.top/Article/details/gtzndobkoh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tianlin.xyz/Article/details/gtehhttebx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.quarkkingdee.top/Article/details/gtxnzeunep.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fzhhl.top/Article/details/gtwpudfcwg.html

【文件统计】
来源：http://dali.ydzc1.top/Article/details/gttmvkdufi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jlsjyb.cn/Article/details/gtaexmmvgv.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtmpvbybva.html

目  录
来源：http://dali.hywenlv.cn/Article/details/gtpsshkeyo.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtvipaqvxb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gtnmmeoegl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtbsonminq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gtlpskuyzf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zycfv.cn/Article/details/gtsjpshsvy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tianlin.xyz/Article/details/gtcposszfs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yangfankeji.com/Article/details/gtcajmqmlj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gtbrwgyuid.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.smart0.xyz/Article/details/gtferstggv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtgneycsmt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.daria6918.cn/Article/details/gtnliqhcgi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtpjwmugvh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtnremimqc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gtmytlzflv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gtvoeuxazr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.svipenyu.cn/Article/details/gtfbzgxotk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtbgjbvcaj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shuidangran.top/Article/details/gtvbpoaxjo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258888.top/Article/details/gtdlfgykwi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhixingplan.top/Article/details/gtdrcdnrwc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gtolobtcfv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gtarwkzizm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtipoljggl.html

A. 基础语法与类型
来源：http://dali.cashguo.top/Article/details/gtqipcursi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtijzmqtwd.html

[A01] Hello World
来源：http://dali.hysaishi.cn/Article/details/gtrubovqjf.html

Py:   print("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gtclsjpved.html

PHP:  echo "Hello, World!";
来源：http://dali.jqgufenzy.top/Article/details/gtwndlfdec.html

JS:   console.log("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gtqfrsmuct.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnewjqsun.html

Java: System.out.println("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtgoowyfie.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtgwcjipuj.html

Ruby: puts "Hello, World!"
来源：http://dali.yangfankeji.com/Article/details/gtdauskjub.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gtibsezisq.html

[A02] 变量声明与赋值
来源：http://dali.ydzc1.top/Article/details/gtiahndxun.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gteohqcdcl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtjyihhfxi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhengqikj.top/Article/details/gthefljqzs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.tianlin.xyz/Article/details/gtprpskygp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtdpygches.html

Go:   name := "Alex"; age := 20
来源：http://dali.jqgufenzy.top/Article/details/gtavrpbske.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jyoumei.cn/Article/details/gthdpaeani.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtxvdpwktj.html

[A03] 常量定义
来源：http://dali.jqgfzy.top/Article/details/gtfiirbxna.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.smart0.xyz/Article/details/gtxtkiwpoj.html

PHP:  const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtdoqcbudr.html

JS:   const PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtuqdmfrda.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gthcwqahvp.html

Java: static final double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtnighxevg.html

Go:   const PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gtzrxjtcyi.html

Ruby: PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gtafvjtcrx.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtmiyzprgv.html

[A04] 判断变量类型
来源：http://dali.vqdsnc.cn/Article/details/gtnhtnoaze.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gotoacloud.top/Article/details/gtjyybbsrp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.pycfn.com/Article/details/gtzxtngvwn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtlwelvrcg.html

TS:   typeof x; x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gtvernptle.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhoulong.xyz/Article/details/gtivlbgnqj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.9152youxi.cn/Article/details/gtckrzwhqu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jyoumei.cn/Article/details/gtfnulszuk.html

C#:   x.GetType().Name; x is int
来源：http://dali.sxryk.cn/Article/details/gtojjdcbmp.html

[A05] 整数除法与取模
来源：http://dali.mhx1999.top/Article/details/gtbyamncqn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jianghu66.top/Article/details/gtkivhbcan.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtavmaavic.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gtjbosxazt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gtpirraxrk.html

Java: 7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtnelbloay.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtscxupqxn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtayveyofx.html

C#:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtwknjndkr.html

[A06] 字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtceurymbb.html

Py:   int("42"); float("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtydznzigh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hongshengwenyu.top/Article/details/gtsrevlnfj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jianghu66.top/Article/details/gtovffvshh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gthbbsekzq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gtmnpwmqwp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zdqjudy.top/Article/details/gtkymvnufe.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.dashuyun.cn/Article/details/gtqkhsponx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtpqxhebxu.html

[A07] 数字转字符串
来源：http://dali.iojbl.cn/Article/details/gtivodereb.html

Py:   str(42)
来源：http://dali.sysykeji.top/Article/details/gtkipfkykw.html

PHP:  (string) 42; strval(42)
来源：http://dali.yonumen.top/Article/details/gtwujoepjg.html

JS:   String(42); (42).toString()
来源：http://dali.c1oappe.top/Article/details/gtjuescajb.html

TS:   String(42)
来源：http://dali.pengpengdd.cyou/Article/details/gttdooesxc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.redwolf501.top/Article/details/gtwyzsnkan.html

Go:   strconv.Itoa(42)
来源：http://dali.zhixingplan.top/Article/details/gtjalqecgu.html

Ruby: 42.to_s
来源：http://dali.vqdsnc.cn/Article/details/gtzscdblkx.html

C#:   42.ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gteqmwbnsb.html

[A08] 取整与四舍五入
来源：http://dali.zhoulong.xyz/Article/details/gtsnkbsplg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gtemdyataz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jlsjyb.cn/Article/details/gtkurzfeaw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtlfvxodjz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinqigfzy.top/Article/details/gtqhgqsisg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gthidyjvbi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtovkntehs.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.dianchejie.cn/Article/details/gtcilsvfnx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvllkpyot.html

[A09] 绝对值与最大最小值
来源：http://dali.pycfn.com/Article/details/gtcyitynkb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtyrdlnigx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuwbbicj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtqyxtydia.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtgwcosqdj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gttcuvrxhu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cucudq.cn/Article/details/gthhoeyvkw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sxryk.cn/Article/details/gthiktpdnq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtkfebsild.html

[A10] 生成随机数
来源：http://dali.yonumen.top/Article/details/gtijoohcqa.html

Py:   import random; random.randint(1, 100)
来源：http://dali.aibaodan.cn/Article/details/gtsqftpvvj.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gtwgwxqfrd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sysykeji.top/Article/details/gtgtsjqwdy.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yangfankeji.com/Article/details/gtzakxyiug.html

Java: new Random().nextInt(100) + 1
来源：http://dali.gzhubu.top/Article/details/gthkdgtosk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmuwpjgp.html

Ruby: rand(1..100)
来源：http://dali.gaohongyu789.top/Article/details/gtatthteqy.html

C#:   new Random().Next(1, 101)
来源：http://dali.xuetiantiany.cn/Article/details/gtxhcefgtr.html

[A11] 条件表达式（三元）
来源：http://dali.316326.xyz/Article/details/gtouigyxze.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.redwolf501.top/Article/details/gtytcvwmfg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gtqowqnqid.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtqozwiqqu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtasljgpvh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gtduixcwyp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yanxiufei.cn/Article/details/gtekwvjksn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtdgumnubb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtydbvrtbb.html

[A12] 字符串插值 / 格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtvydhojxd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.daria6918.cn/Article/details/gtevkmsado.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ppjwa.cn/Article/details/gtsnlmigrf.html

JS:   `Hello, ${name}!`
来源：http://dali.sufxvd.cn/Article/details/gtrckmmvnt.html

TS:   `Hello, ${name}!`
来源：http://dali.cqqwz.cn/Article/details/gtespnvlhu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cashguo.top/Article/details/gtxhipobmu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yvedp.cn/Article/details/gtmdghuanw.html

Ruby: "Hello, #{name}!"
来源：http://dali.0kj1m.cn/Article/details/gtppyrvwwl.html

C#:   $"Hello, {name}!"
来源：http://dali.wangdashe.top/Article/details/gtgmkbitto.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.gotoacloud.top/Article/details/gtkiyxrffu.html

Py:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtdgwsdfvu.html

PHP:  "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtqsvtukrr.html

JS:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtldhvixkb.html

TS:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gtngntycpt.html


<!-- 参考信息 -->