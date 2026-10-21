代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.nanxinkj.top/Article/details/gtqryppkys.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yuanzhike.top/Article/details/gteajdqijo.html

[U84] JS：CommonJS 写法
来源：http://dali.0kj1m.cn/Article/details/gtlzahfjgs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ivvv.top/Article/details/gtgnphqknq.html

[U85] JS：可选链
来源：http://dali.pycfn.com/Article/details/gtlfmcrcvo.html

a?.b?.c
来源：http://dali.gzhubu.top/Article/details/gtzevaokmg.html

[U86] JS：空值合并
来源：http://dali.tianlin.xyz/Article/details/gtetnswrxe.html

a ?? b
来源：http://dali.zhongyouzk.top/Article/details/gtmvegbvgk.html

[U87] JS：解构默认值
来源：http://dali.snrcjt.cn/Article/details/gtwiycehak.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sxryk.cn/Article/details/gtfjdjmrfi.html

[U88] JS：对象展开合并
来源：http://dali.jyoumei.cn/Article/details/gtuswqzdtd.html

{ ...a, ...b }
来源：http://dali.pengpengdd.cyou/Article/details/gttbiznyvq.html

[U89] JS：数组去重
来源：http://dali.ybcxt.top/Article/details/gtcyaerlyk.html

[...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtbpejkqbl.html

[U90] JS：数字数组排序
来源：http://dali.cashguo.top/Article/details/gtaqufkqfp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtmocntzdn.html

[U91] JS：对象键值遍历
来源：http://dali.guowangkeji.top/Article/details/gtkuonpmpc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.birdmap.top/Article/details/gtjxrszhep.html

[U92] JS：深拷贝
来源：http://dali.sysykeji.top/Article/details/gtampvztkv.html

structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtpmxcslmh.html

[U93] JS：模板字符串
来源：http://dali.smart0.xyz/Article/details/gttdxwmcck.html

`共 ${n} 条`
来源：http://dali.fengsongda.top/Article/details/gtkfbwvcst.html

[U94] JS：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gtfvruwxdm.html

const double = x => x * 2;
来源：http://dali.cqqwz.cn/Article/details/gtqxxxwbxm.html

[U95] JS：Promise 包装
来源：http://dali.yuxming.cn/Article/details/gtmqyxcaki.html

new Promise((resolve, reject) => {})
来源：http://dali.dashuyun.cn/Article/details/gtfshwzggc.html

[U96] JS：async/await 与异常
来源：http://dali.jinqigfzy.top/Article/details/gtjfvfonlr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtzvbxjgdw.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzqphnyn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtblmzeaab.html

[U98] JS：fetch 带 JSON
来源：http://dali.ivvv.top/Article/details/gthtvdxbjc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.snrcjt.cn/Article/details/gtpftnyhkc.html

[U99] JS：事件监听
来源：http://dali.jqgfzy.top/Article/details/gtzzjyuuks.html

el.addEventListener("click", e => {})
来源：http://dali.zhoulong.xyz/Article/details/gtzlyslhkt.html

[U100] JS：DOM 查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpstluiy.html

document.querySelector(".item")
来源：http://dali.jianghu66.top/Article/details/gtfyakzbll.html

[U101] JS：classList 操作
来源：http://dali.jiagoushi.top/Article/details/gtjpadwoih.html

el.classList.toggle("active")
来源：http://dali.tanke756.top/Article/details/gtpvptabff.html

[U102] JS：本地存储
来源：http://dali.yonumen.top/Article/details/gtozsjolwh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.vqdsnc.cn/Article/details/gtvahhdzne.html

[U103] JS：定时器
来源：http://dali.andypj.xyz/Article/details/gtlossvcmo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbhlsrol.html

[U104] JS：防抖
来源：http://dali.fengsongda.top/Article/details/gtpqxyyqrm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoejuhciq.html

[U105] JS：节流
来源：http://dali.shuidangran.top/Article/details/gthldieiuv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.haohaochexian.top/Article/details/gtlfnmruva.html

[U106] JS：日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtgyenckgg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tian-w.cn/Article/details/gtutsqxrxr.html

[U107] JS：数字千分位
来源：http://dali.andypj.xyz/Article/details/gtynrdhura.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tanke756.top/Article/details/gtvznblmcm.html

[U108] JS：随机整数
来源：http://dali.316326.xyz/Article/details/gteiwgzvfe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ivvv.top/Article/details/gtyhofzkkb.html

[U109] JS：数组分组
来源：http://dali.sufxvd.cn/Article/details/gtlszpqqnm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gtnwxihzme.html

[U110] JS：数组分块
来源：http://dali.dianchejie.cn/Article/details/gtwpqsqkgy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.0kj1m.cn/Article/details/gtilccpmwj.html

[U111] JS：对象转 Map
来源：http://dali.zhengqikj.top/Article/details/gtagoimxhf.html

new Map(Object.entries(obj))
来源：http://dali.sysykeji.top/Article/details/gtypfpddgp.html

[U112] JS：字符串补位
来源：http://dali.0kj1m.cn/Article/details/gtozpvxsms.html

"7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtwvlakkgc.html

[U113] JS：正则替换全部
来源：http://dali.tianlin.xyz/Article/details/gtccssfnop.html

s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtqersgwhy.html

[U114] JS：JSON 深比较
来源：http://dali.bjfxy.top/Article/details/gtyifwgqsz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtcpamyuox.html

[U115] JS：生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtoguornyr.html

crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtppcmettc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nanxinkj.top/Article/details/gtdcurimnq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aibaodan.cn/Article/details/gtjkipqbbv.html

[U117] JS：单元测试
来源：http://dali.wangshuangyany.cn/Article/details/gtsdggvayb.html

npm i -D vitest;  npx vitest
来源：http://dali.316326.xyz/Article/details/gtnsydufyy.html

[U118] JS：开发服务器
来源：http://dali.daxiang520.top/Article/details/gtqdshgwkj.html

npm i -D vite;  npx vite
来源：http://dali.yj20258.top/Article/details/gtazxlilwm.html

[U119] JS：生产构建
来源：http://dali.hnqzz.top/Article/details/gttjyxqjti.html

npx vite build
来源：http://dali.yj20258888.top/Article/details/gtvotbmzba.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yuxming.cn/Article/details/gtkyhffkoj.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258888.top/Article/details/gtosctvksn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtolmfycvn.html

统计汇总
来源：http://dali.cdnleiting.top/Article/details/gtywuwgkca.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgjleqttb.html

按语言统计（条）：
来源：http://dali.birdmap.top/Article/details/gtuzxdfxzd.html

Python ......... 252
来源：http://dali.zhoulong.xyz/Article/details/gtybjscmdj.html

PHP ............ 252
来源：http://dali.mhx1999.top/Article/details/gtuiohgcfb.html

JavaScript ..... 252
来源：http://dali.hongshengwenyu.top/Article/details/gttlziaslu.html

TypeScript ..... 212
来源：http://dali.sxryk.cn/Article/details/gtaxwvgpck.html

Java ........... 212
来源：http://dali.zdqjudy.top/Article/details/gtxowlxkey.html

Go ............. 212
来源：http://dali.birdmap.top/Article/details/gtpzvoolux.html

Ruby ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpolsazj.html

C# ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gtwllfiajr.html

C .............. 30
来源：http://dali.meibo888.top/Article/details/gtqpknwaga.html

C++ ............ 30
来源：http://dali.jyoumei.cn/Article/details/gtukxwcyoz.html

SQL ............ 90
来源：http://dali.dianchejie.cn/Article/details/gtbfgohmne.html

Bash ........... 80
来源：http://dali.sysykeji.top/Article/details/gtxyzlplpn.html

Kotlin ......... 15
来源：http://dali.quarkkingdee.top/Article/details/gtoyfezika.html

Swift .......... 15
来源：http://dali.nwbrower.top/Article/details/gtflypisyl.html

Lua ............ 10
来源：http://dali.pycfn.com/Article/details/gthyxeajxd.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gtnglvnveo.html

Scala .......... 10
来源：http://dali.yuxming.cn/Article/details/gtygutfyfk.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gthqwnpekd.html

合计 ........... 2106 条
来源：http://dali.zdqjudy.top/Article/details/gtxfzlmofg.html

按章节统计：
来源：http://dali.hammf.cn/Article/details/gtemboojgc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gtjleqrbni.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtrzbbkwje.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtmuyhylgk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gtbkxqayts.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cdnleiting.top/Article/details/gtcrrxjiya.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinqigufen.top/Article/details/gttwgtyeqt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gtcqsynjkv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gtwttcuacb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtopviqgny.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gtfwgvmibv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtgozyuqkb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtqcmtugqw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtgcbrxoeq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqeapknpq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.vqdsnc.cn/Article/details/gtuyzkampr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtmlantugi.html

Q SQL 专题                              90
来源：http://dali.zhiwuduotai.top/Article/details/gtmcehkhjb.html

R Bash 专题                             80
来源：http://dali.havefunace.top/Article/details/gtipfffzfw.html

S C / C++ 专题                          60
来源：http://dali.zycfv.cn/Article/details/gtssxsxdpm.html

T 其他语言补充                          60
来源：http://dali.xziqi.cn/Article/details/gtioijmbxu.html

U 高频实用片段                         120
来源：http://dali.zycfv.cn/Article/details/gtplrkwvvb.html

------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmpnlydq.html

合计                                  2106 条
来源：http://dali.sweek.top/Article/details/gtrfxioxdo.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gthxicerxf.html

使用提醒
来源：http://dali.wangshuangyany.cn/Article/details/gtfmpurgxk.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtcattaxha.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sysykeji.top/Article/details/gtumzqlmrx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zdqjudy.top/Article/details/gtizhjglbu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gzhubu.top/Article/details/gtxxfqqjuf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.dashuyun.cn/Article/details/gtolimijxr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj20258.top/Article/details/gtqzeslcbd.html

—— 文件结束 ——
来源：http://dali.bjfxy.top/Article/details/gtrocdncri.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjowkxksi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj202588.top/Article/details/gtfymuxkjq.html

Common Programming Examples Cheat Book
来源：http://dali.jlsjyb.cn/Article/details/gtdjweeywi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtnykblmnz.html

【收录内容】
来源：http://dali.jianghu66.top/Article/details/gtjzwufltd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cqqwz.cn/Article/details/gteedfynyd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gotoacloud.top/Article/details/gtgatfkyin.html

SQL · Bash · C · C++
来源：http://dali.shangyingyoupin.top/Article/details/gtedqjhkca.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zycfv.cn/Article/details/gtitnjrmel.html

【使用说明】
来源：http://dali.tian-w.cn/Article/details/gtlqtusydg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj202588.top/Article/details/gtfmywgndd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.havefunace.top/Article/details/gttoqyvssr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinghuilouyu.cn/Article/details/gtquqafkjy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zdqjudy.top/Article/details/gtwkbzfubn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yanxiufei.cn/Article/details/gtjnmwdmdx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jianghu66.top/Article/details/gttwunopge.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ivvv.top/Article/details/gtcdnmttng.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jqgfzy.top/Article/details/gtlqjgrhgv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ivvv.top/Article/details/gtbhcimjul.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.dianchejie.cn/Article/details/gtdsatgwiw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngwcpepq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenzaomai.com/Article/details/gtzaycjeuh.html

【文件统计】
来源：http://dali.xinyue.icu/Article/details/gtovomqldb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhixingplan.top/Article/details/gtntbsqaoz.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtlmtkbbdh.html

目  录
来源：http://dali.0kj1m.cn/Article/details/gtcvzfhxpi.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtaladrhde.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbhgwmzm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtybtucfli.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gtreqguzrt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.kuanghao11.cn/Article/details/gttcpwgwot.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.aizwys.cn/Article/details/gtkwqvoejf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nwbrower.top/Article/details/gtduxduwhm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtmykbjjqs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.pycfn.com/Article/details/gtzoribmha.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtskofshgf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ivvv.top/Article/details/gtnvxzgkud.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtvyzihbbn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gthbkvbvax.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtjwrdzdti.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gtnrqaegkl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hammf.cn/Article/details/gtuilumsco.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtpstxwxvv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258.top/Article/details/gtoyfeybbb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqztgzpl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yuxming.cn/Article/details/gtvrpjhyde.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtngkmvcyn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gthpaiweio.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtejpodgkt.html

A. 基础语法与类型
来源：http://dali.zhixingplan.top/Article/details/gtrfsilfbh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwwshicc.html

[A01] Hello World
来源：http://dali.yuanzhike.top/Article/details/gtrlnealcs.html

Py:   print("Hello, World!")
来源：http://dali.sufxvd.cn/Article/details/gthdnewqwg.html

PHP:  echo "Hello, World!";
来源：http://dali.tian-w.cn/Article/details/gtpsysorwb.html

JS:   console.log("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gtxnpbjqkf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenjidiqi.icu/Article/details/gtmnqrfjye.html

Java: System.out.println("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gthnhzcetr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gtqrpszmln.html

Ruby: puts "Hello, World!"
来源：http://dali.hywenlv.cn/Article/details/gtkfxobbeo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtdcgbofsw.html

[A02] 变量声明与赋值
来源：http://dali.zhiwuduotai.top/Article/details/gtjmamolji.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jianghu66.top/Article/details/gtvtsunbiw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.meibo888.top/Article/details/gtlybwrhzm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtsconzwbz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sysykeji.top/Article/details/gtcjrxownu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtgzdvtpot.html

Go:   name := "Alex"; age := 20
来源：http://dali.jiagoushi.top/Article/details/gtibhurtqh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ppjwa.cn/Article/details/gthhumjnke.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shuidangran.top/Article/details/gtidjleloz.html

[A03] 常量定义
来源：http://dali.cucudq.cn/Article/details/gtlvtnkrrt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daria6918.cn/Article/details/gtclltehqd.html

PHP:  const PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhhtcyou.html

JS:   const PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtobfhhxnz.html

TS:   const PI: number = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtohcyhxmx.html

Java: static final double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtuojfvyir.html

Go:   const PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gtricagdhe.html

Ruby: PI = 3.14159
来源：http://dali.jlsjyb.cn/Article/details/gtcmxlmmqf.html

C#:   const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtgmoepbxq.html

[A04] 判断变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdzuvjnt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jiagoushi.top/Article/details/gtinsdxcrl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hywenlv.cn/Article/details/gtkrsyrhfv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yueranfly.top/Article/details/gtfcvxzyxr.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtoeocogvx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuetiantiany.cn/Article/details/gtjhzmirzx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnxiangtu.top/Article/details/gtmywegjhg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hnqzz.top/Article/details/gtobxfaism.html

C#:   x.GetType().Name; x is int
来源：http://dali.sufxvd.cn/Article/details/gtbalcfdtf.html

[A05] 整数除法与取模
来源：http://dali.ppjwa.cn/Article/details/gtrbxomszq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xziqi.cn/Article/details/gtfgkuqlth.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofpyoagd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtyqmopfji.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtnidmcdns.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtkodewvxh.html

Go:   7 / 2; 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtoiztieyu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtgraonuic.html

C#:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtiixtvwbd.html

[A06] 字符串转数字
来源：http://dali.ybcxt.top/Article/details/gtuimpouza.html

Py:   int("42"); float("3.14")
来源：http://dali.yj202588.top/Article/details/gtukrdsxmk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinqigfzy.top/Article/details/gtlxvuispu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.havefunace.top/Article/details/gtuieqjiry.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gttnqlxjys.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gttzilxmrz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.haohaochexian.top/Article/details/gtouroxojk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yuanzhike.top/Article/details/gtqdgcgyrb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.guowangkeji.top/Article/details/gtqvbfpztu.html

[A07] 数字转字符串
来源：http://dali.yongpay.top/Article/details/gthlfoxvpy.html

Py:   str(42)
来源：http://dali.shzxlz.cn/Article/details/gtfixatsdc.html

PHP:  (string) 42; strval(42)
来源：http://dali.jlsjyb.cn/Article/details/gtuvectiad.html

JS:   String(42); (42).toString()
来源：http://dali.sxryk.cn/Article/details/gtfftetrpr.html

TS:   String(42)
来源：http://dali.shuidangran.top/Article/details/gtlueiuglj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtiqogdgts.html

Go:   strconv.Itoa(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcisifts.html

Ruby: 42.to_s
来源：http://dali.chenzaomai.com/Article/details/gthuuntvly.html

C#:   42.ToString()
来源：http://dali.guowangkeji.top/Article/details/gtzrluldku.html

[A08] 取整与四舍五入
来源：http://dali.dashuyun.cn/Article/details/gthpbpxkpn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gtmgfyhqai.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.andypj.xyz/Article/details/gtcaptdetc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtfhyneetw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shzxlz.cn/Article/details/gttldyzvcu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtprdvuvfh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gtxmnufiyt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodqngxaq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gtfaivpmaj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gtyceppdml.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtsodxdunn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pycfn.com/Article/details/gttnnmvhjv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtpjqiszir.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtumsdckxf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hammf.cn/Article/details/gtrwjkscsq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzexjeemy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yueranfly.top/Article/details/gttgstnwwh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtiabahhoz.html

[A10] 生成随机数
来源：http://dali.cdnleiting.top/Article/details/gtcgntarer.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hfpthk.cn/Article/details/gtwzslhwpl.html

PHP:  random_int(1, 100);
来源：http://dali.fzhhl.top/Article/details/gtetbqicqf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cashguo.top/Article/details/gtuidrftuv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gzhubu.top/Article/details/gtchsmzjbp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sufxvd.cn/Article/details/gtnbrwkznn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.c1oappe.top/Article/details/gtyfuucbpr.html

Ruby: rand(1..100)
来源：http://dali.feifeiyinyue.top/Article/details/gtlodwolra.html

C#:   new Random().Next(1, 101)
来源：http://dali.yangfankeji.com/Article/details/gtcgwjzdfm.html

[A11] 条件表达式（三元）
来源：http://dali.jianghu66.top/Article/details/gteetfsmqj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ehwqpu.com/Article/details/gtfhfxxcqo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gtfybwncnz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gtlwyigtrl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gtwjuuelfh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtgcrlbjef.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yanxiufei.cn/Article/details/gtvhuugzxs.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gtqracgfah.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtqceblqoy.html

[A12] 字符串插值 / 格式化
来源：http://dali.jyoumei.cn/Article/details/gtymteyvda.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.vqdsnc.cn/Article/details/gttkxmfeto.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.pengpengdd.cyou/Article/details/gtfsrjaeat.html

JS:   `Hello, ${name}!`
来源：http://dali.316326.xyz/Article/details/gtkvglyocz.html

TS:   `Hello, ${name}!`
来源：http://dali.yuxming.cn/Article/details/gtvcruvkas.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yuxming.cn/Article/details/gtynwubkon.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.iojbl.cn/Article/details/gtsjmpybdm.html

Ruby: "Hello, #{name}!"
来源：http://dali.gogol.net.cn/Article/details/gtdyxlcgpb.html

C#:   $"Hello, {name}!"
来源：http://dali.yanxiufei.cn/Article/details/gtzorovcke.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cdnleiting.top/Article/details/gtdqedayns.html

Py:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtdllptbfp.html

PHP:  "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtcakiuwww.html

JS:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtlsvfsjre.html

TS:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtgcewqkxr.html

Java: "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtlmpaimes.html

Go:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gtlgvaqkdt.html

Ruby: "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtqgyegdgx.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtndjrvfkf.html


<!-- 参考信息 -->