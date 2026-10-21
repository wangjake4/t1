代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.redwolf501.top/Article/details/gtqvrqruub.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gtngoldjju.html

[U84] JS：CommonJS 写法
来源：http://dali.xuetiantiany.cn/Article/details/gttvjumpeu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.fengsongda.top/Article/details/gthsivtxqd.html

[U85] JS：可选链
来源：http://dali.sweek.top/Article/details/gtlxvqcqpj.html

a?.b?.c
来源：http://dali.zhongyouzk.top/Article/details/gtjynjiqpy.html

[U86] JS：空值合并
来源：http://dali.haohaochexian.top/Article/details/gtnhohdgbg.html

a ?? b
来源：http://dali.sufxvd.cn/Article/details/gtsinwezmf.html

[U87] JS：解构默认值
来源：http://dali.wangdashe.top/Article/details/gtcqblkvgn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.andypj.xyz/Article/details/gtgmdoistd.html

[U88] JS：对象展开合并
来源：http://dali.quarkkingdee.top/Article/details/gtotvfhpyx.html

{ ...a, ...b }
来源：http://dali.wangdashe.top/Article/details/gtgleckiyq.html

[U89] JS：数组去重
来源：http://dali.9152youxi.cn/Article/details/gtenzhbufh.html

[...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtriukntyo.html

[U90] JS：数字数组排序
来源：http://dali.quarkkingdee.top/Article/details/gtgndeslqh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtnistslhi.html

[U91] JS：对象键值遍历
来源：http://dali.sxryk.cn/Article/details/gtlhpnmcrc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.wangshuangyany.cn/Article/details/gtqzxbfjbj.html

[U92] JS：深拷贝
来源：http://dali.mhx1999.top/Article/details/gtvgxkjoxg.html

structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtdjnyipkr.html

[U93] JS：模板字符串
来源：http://dali.hfpthk.cn/Article/details/gtdjtuvilo.html

`共 ${n} 条`
来源：http://dali.xziqi.cn/Article/details/gtqetvzmia.html

[U94] JS：箭头函数
来源：http://dali.c1oappe.top/Article/details/gtldshqgdd.html

const double = x => x * 2;
来源：http://dali.dianchejie.cn/Article/details/gtyidozcnt.html

[U95] JS：Promise 包装
来源：http://dali.xuetiantiany.cn/Article/details/gtepvvrnks.html

new Promise((resolve, reject) => {})
来源：http://dali.yuxming.cn/Article/details/gtwdnpgeqn.html

[U96] JS：async/await 与异常
来源：http://dali.hysaishi.cn/Article/details/gtjapuprup.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtwktzutnj.html

[U97] JS：并发请求
来源：http://dali.nanxinkj.top/Article/details/gtftthravl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtbhpwgybh.html

[U98] JS：fetch 带 JSON
来源：http://dali.gotoacloud.top/Article/details/gtqjxntfhq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guowangkeji.top/Article/details/gtafdziltt.html

[U99] JS：事件监听
来源：http://dali.hnxiangtu.top/Article/details/gtzgfblaeg.html

el.addEventListener("click", e => {})
来源：http://dali.ivvv.top/Article/details/gtabtespop.html

[U100] JS：DOM 查询
来源：http://dali.gzhubu.top/Article/details/gtpczqqcrk.html

document.querySelector(".item")
来源：http://dali.yanxiufei.cn/Article/details/gtjxnzyjsg.html

[U101] JS：classList 操作
来源：http://dali.zhongyouzk.top/Article/details/gtwfyrssrj.html

el.classList.toggle("active")
来源：http://dali.jyoumei.cn/Article/details/gtdubggchv.html

[U102] JS：本地存储
来源：http://dali.c1oappe.top/Article/details/gtuziriqdc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ybcxt.top/Article/details/gtkpojpshn.html

[U103] JS：定时器
来源：http://dali.hywenlv.cn/Article/details/gtulpdtgbm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cdnleiting.top/Article/details/gtrnfghfur.html

[U104] JS：防抖
来源：http://dali.hammf.cn/Article/details/gttzebvqne.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtaekyksns.html

[U105] JS：节流
来源：http://dali.gogol.net.cn/Article/details/gthreinvzb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hammf.cn/Article/details/gtrxqaptcq.html

[U106] JS：日期格式化
来源：http://dali.fengsongda.top/Article/details/gtcvoolqbj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hongshengwenyu.top/Article/details/gthvownfos.html

[U107] JS：数字千分位
来源：http://dali.ydzc1.top/Article/details/gtftbmuokv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtgjgcbarx.html

[U108] JS：随机整数
来源：http://dali.xuanzx.com/Article/details/gtvblqvwax.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.quarkkingdee.top/Article/details/gtrjexagly.html

[U109] JS：数组分组
来源：http://dali.svipenyu.cn/Article/details/gtvyspwire.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtjbqaoxjv.html

[U110] JS：数组分块
来源：http://dali.hnqzz.top/Article/details/gtoblfcihp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhoulong.xyz/Article/details/gtifsnpapa.html

[U111] JS：对象转 Map
来源：http://dali.yuxming.cn/Article/details/gtmizqyrfr.html

new Map(Object.entries(obj))
来源：http://dali.hywenlv.cn/Article/details/gtxuszlhsw.html

[U112] JS：字符串补位
来源：http://dali.jiagoushi.top/Article/details/gtlsihojqm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtnaltbzjg.html

[U113] JS：正则替换全部
来源：http://dali.hfpthk.cn/Article/details/gtrqdyykvr.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmgmsrne.html

[U114] JS：JSON 深比较
来源：http://dali.kuanghao11.cn/Article/details/gthlbagdpk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtxyysnszu.html

[U115] JS：生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtxnrgwlgi.html

crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtxjzmhncx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dianchejie.cn/Article/details/gtfnhebxom.html

/** @param {string} name */ function f(name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtrmnbvysc.html

[U117] JS：单元测试
来源：http://dali.yongpay.top/Article/details/gtblvhlvnu.html

npm i -D vitest;  npx vitest
来源：http://dali.shzxlz.cn/Article/details/gtlejaohsj.html

[U118] JS：开发服务器
来源：http://dali.hfpthk.cn/Article/details/gtpbexnamw.html

npm i -D vite;  npx vite
来源：http://dali.wangshuangyany.cn/Article/details/gttrppugbr.html

[U119] JS：生产构建
来源：http://dali.shuidangran.top/Article/details/gtjoikvayd.html

npx vite build
来源：http://dali.jianghu66.top/Article/details/gtmostxije.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqskvtxl.html

import.meta.env.VITE_API_URL
来源：http://dali.0kj1m.cn/Article/details/gtkhkdqvqm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gteksishds.html

统计汇总
来源：http://dali.jqgfzy.top/Article/details/gtrurrltga.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrvotyerl.html

按语言统计（条）：
来源：http://dali.yangfankeji.com/Article/details/gtrwtntuwf.html

Python ......... 252
来源：http://dali.smart0.xyz/Article/details/gtodaeedqc.html

PHP ............ 252
来源：http://dali.hongshengwenyu.top/Article/details/gtvvbhwcjb.html

JavaScript ..... 252
来源：http://dali.shangyingyoupin.top/Article/details/gtkvuzqnsg.html

TypeScript ..... 212
来源：http://dali.shzxlz.cn/Article/details/gtdfzgflvm.html

Java ........... 212
来源：http://dali.yuxming.cn/Article/details/gtjhchcpym.html

Go ............. 212
来源：http://dali.xylfe.cn/Article/details/gttzefskhl.html

Ruby ........... 212
来源：http://dali.cdnleiting.top/Article/details/gtkxnoapnc.html

C# ............. 212
来源：http://dali.havefunace.top/Article/details/gtfytetliu.html

C .............. 30
来源：http://dali.xziqi.cn/Article/details/gtdtchvopj.html

C++ ............ 30
来源：http://dali.chenzaomai.com/Article/details/gthgxffidg.html

SQL ............ 90
来源：http://dali.cheryme.top/Article/details/gtlydnvwdg.html

Bash ........... 80
来源：http://dali.fzhhl.top/Article/details/gtubyetwwy.html

Kotlin ......... 15
来源：http://dali.jqgufenzy.top/Article/details/gtwwymzjof.html

Swift .......... 15
来源：http://dali.sxryk.cn/Article/details/gttuluheeb.html

Lua ............ 10
来源：http://dali.hnxiangtu.top/Article/details/gtrhyhyzyx.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gtyalaonyx.html

Scala .......... 10
来源：http://dali.daria6918.cn/Article/details/gtgkmgemkv.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gthxmromeh.html

合计 ........... 2106 条
来源：http://dali.c1oappe.top/Article/details/gtdssabnko.html

按章节统计：
来源：http://dali.9152youxi.cn/Article/details/gtqojrgymr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gtpgmgtlus.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtzzdigeiw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gthwcwbpeg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yueranfly.top/Article/details/gtohqvesvd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.kuanghao11.cn/Article/details/gtdwidimdv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gtmdhwmoki.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gtyyhrpbdl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnxiangtu.top/Article/details/gtgsetichv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtjanecnhn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtqyygopzj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdycuvbt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtweudfyus.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gtyyjhpada.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gthbgznkmj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pengpengdd.cyou/Article/details/gtbdgxilzs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtlbepahlv.html

Q SQL 专题                              90
来源：http://dali.cashguo.top/Article/details/gtcaqvckcc.html

R Bash 专题                             80
来源：http://dali.sufxvd.cn/Article/details/gtqwlcykfk.html

S C / C++ 专题                          60
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyonfytx.html

T 其他语言补充                          60
来源：http://dali.chenzaomai.com/Article/details/gtedulmktc.html

U 高频实用片段                         120
来源：http://dali.yanxiufei.cn/Article/details/gtowawizcv.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gtuxgrcqvd.html

合计                                  2106 条
来源：http://dali.cqqwz.cn/Article/details/gtdckjjiex.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gttfkgpjdu.html

使用提醒
来源：http://dali.ehwqpu.com/Article/details/gtpdfbbfxc.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gtexnmyfjp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuanzhike.top/Article/details/gtikxkjqoa.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gaohongyu789.top/Article/details/gtnkuxminl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigfzy.top/Article/details/gtwrzsjyqv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aizwys.cn/Article/details/gtjaifqbep.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.redwolf501.top/Article/details/gttudocunm.html

—— 文件结束 ——
来源：http://dali.dashuyun.cn/Article/details/gtvbtoftmt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtsyiqommp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sweek.top/Article/details/gtzrwoqmmp.html

Common Programming Examples Cheat Book
来源：http://dali.wangdashe.top/Article/details/gtshaugysn.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtpfvvfpey.html

【收录内容】
来源：http://dali.jqgufenzy.top/Article/details/gtyjkpbpph.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.chenjidiqi.icu/Article/details/gtlpkzizis.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shuidangran.top/Article/details/gtueagtxru.html

SQL · Bash · C · C++
来源：http://dali.shzxlz.cn/Article/details/gtlahknfvk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.iojbl.cn/Article/details/gtpfyynwrx.html

【使用说明】
来源：http://dali.zycfv.cn/Article/details/gtsrwvgzcl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgfzy.top/Article/details/gtwhzdrybv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.aizwys.cn/Article/details/gtnddoxckw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yangfankeji.com/Article/details/gtgexbxdew.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.birdmap.top/Article/details/gthprxuqcm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.316326.xyz/Article/details/gtsofrzwac.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.iojbl.cn/Article/details/gtdcnwlacm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdopgrtij.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cashguo.top/Article/details/gtrlyhhbsu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclbanjjh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ybcxt.top/Article/details/gtpumqrfkb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tian-w.cn/Article/details/gtlnyyhxib.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinqigfzy.top/Article/details/gtxzvobbcn.html

【文件统计】
来源：http://dali.kuanghao11.cn/Article/details/gtbnplgpjy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.wangshuangyany.cn/Article/details/gtjgtkqwgs.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtwyrvggzj.html

目  录
来源：http://dali.xuetiantiany.cn/Article/details/gtbrdnqrtw.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gttktgrpeu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gtrnaojpkw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gtxqnjhgyq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtbloitsgu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shzxlz.cn/Article/details/gtuglteubl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xziqi.cn/Article/details/gtnrkwoknq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ybcxt.top/Article/details/gtsobdxdsw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtutyfvwvc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj20258888.top/Article/details/gtvjhwcdye.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gthgndewod.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinqigufen.top/Article/details/gtehllsksx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gthelfwkvx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtlyomxkto.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrqpufvh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hfpthk.cn/Article/details/gtegncutij.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdccdyutr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtqgofptte.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nanxinkj.top/Article/details/gtezqakmrn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinqigufen.top/Article/details/gtwuifvpeh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cqqwz.cn/Article/details/gtispdttug.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtskydnzpy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtbwulkdmr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxxwpazgz.html

A. 基础语法与类型
来源：http://dali.hfpthk.cn/Article/details/gtihymixsh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvzazmbjy.html

[A01] Hello World
来源：http://dali.yuanzhike.top/Article/details/gtwmqzitgk.html

Py:   print("Hello, World!")
来源：http://dali.hnqzz.top/Article/details/gtchlpfjfx.html

PHP:  echo "Hello, World!";
来源：http://dali.cdnleiting.top/Article/details/gtrpydxgef.html

JS:   console.log("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gtymvgmeil.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.meibo888.top/Article/details/gtzypemajs.html

Java: System.out.println("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gtpwiwdkbu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gtxrcjgfrt.html

Ruby: puts "Hello, World!"
来源：http://dali.yuxming.cn/Article/details/gtjakkdvlx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.aibaodan.cn/Article/details/gtqhejwxqx.html

[A02] 变量声明与赋值
来源：http://dali.jianghu66.top/Article/details/gtksipuonr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenjidiqi.icu/Article/details/gtdfxamotj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sxryk.cn/Article/details/gtdzgcpiga.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nwbrower.top/Article/details/gtrnivdwds.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.nwbrower.top/Article/details/gtcgtxiccy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtkkcavnaj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gtqxijqsfa.html

Ruby: name = "Alex"; age = 20
来源：http://dali.c1oappe.top/Article/details/gtwobsooyv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gtdeqdtyus.html

[A03] 常量定义
来源：http://dali.fengsongda.top/Article/details/gtxscrgadf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yonumen.top/Article/details/gtybrkxlju.html

PHP:  const PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtghdwhmto.html

JS:   const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtxiflsslt.html

TS:   const PI: number = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtxofyapho.html

Java: static final double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtsksysfvw.html

Go:   const PI = 3.14159
来源：http://dali.ppjwa.cn/Article/details/gteqeefgmx.html

Ruby: PI = 3.14159
来源：http://dali.ppjwa.cn/Article/details/gtzbmfmrvg.html

C#:   const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtaqvojwmt.html

[A04] 判断变量类型
来源：http://dali.ybcxt.top/Article/details/gtjwsvlcwh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.dianchejie.cn/Article/details/gtfkijowwb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daxiang520.top/Article/details/gtbnnoaiha.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tanke756.top/Article/details/gtobwdpssd.html

TS:   typeof x; x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gtxjefgaps.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gzhubu.top/Article/details/gtvvcaiobb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhengqikj.top/Article/details/gtxoncvwkd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shangyingyoupin.top/Article/details/gtznencftv.html

C#:   x.GetType().Name; x is int
来源：http://dali.xinyue.icu/Article/details/gtyounkwki.html

[A05] 整数除法与取模
来源：http://dali.zhixingplan.top/Article/details/gtnqtqwcex.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.fengsongda.top/Article/details/gtbmuteufa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtjtdyjbuc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtasggrbzd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtdbcwjeff.html

Java: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonigpynv.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtwmkobzdx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtfvqjldvc.html

C#:   7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtzxdmwcms.html

[A06] 字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gttjatyxvp.html

Py:   int("42"); float("3.14")
来源：http://dali.sysykeji.top/Article/details/gtchuttfoy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hongshengwenyu.top/Article/details/gtnrxiarfs.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.nwbrower.top/Article/details/gtfypjsyxi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jqgufenzy.top/Article/details/gtwbmbydvr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.pycfn.com/Article/details/gtcircyueb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.birdmap.top/Article/details/gtjvfielkz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daxiang520.top/Article/details/gteiyktdbv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gtjrzbgyvj.html

[A07] 数字转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtoigppgre.html

Py:   str(42)
来源：http://dali.jiagoushi.top/Article/details/gtnxvmftpv.html

PHP:  (string) 42; strval(42)
来源：http://dali.xziqi.cn/Article/details/gtugtkqbhi.html

JS:   String(42); (42).toString()
来源：http://dali.gaohongyu789.top/Article/details/gtnxpzevzm.html

TS:   String(42)
来源：http://dali.yongpay.top/Article/details/gtjobdsipe.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yuxming.cn/Article/details/gtsoyqdmzp.html

Go:   strconv.Itoa(42)
来源：http://dali.jqgufenzy.top/Article/details/gtrzyacxkx.html

Ruby: 42.to_s
来源：http://dali.jinqigufen.top/Article/details/gtibcnoyvb.html

C#:   42.ToString()
来源：http://dali.yueranfly.top/Article/details/gtmygxjjfc.html

[A08] 取整与四舍五入
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmyzozja.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gtzlfnmdzp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.chenjidiqi.icu/Article/details/gtpumeupzn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gtpnwvgldq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj202588.top/Article/details/gtiepbbmwd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtfrdgjwis.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtcbzztwns.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigufen.top/Article/details/gtcylwsdcr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtosqgfeib.html

[A09] 绝对值与最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtdbtreanh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrntnnqit.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtaxhxfctv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtthsstwov.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtxfimojny.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtozcyddrg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jiagoushi.top/Article/details/gtntlnzhvj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yj202588.top/Article/details/gtbszunjgi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtlloqwaro.html

[A10] 生成随机数
来源：http://dali.guowangkeji.top/Article/details/gttkzqrkhd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.tanke756.top/Article/details/gtpwcuheuy.html

PHP:  random_int(1, 100);
来源：http://dali.iojbl.cn/Article/details/gtmnhrkgcs.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dashuyun.cn/Article/details/gtkavyojkc.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gtjonmadum.html

Java: new Random().nextInt(100) + 1
来源：http://dali.haohaochexian.top/Article/details/gtmgwbmyfw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhongyouzk.top/Article/details/gtuljvkxvh.html

Ruby: rand(1..100)
来源：http://dali.pycfn.com/Article/details/gtejmxqbxy.html

C#:   new Random().Next(1, 101)
来源：http://dali.yj202588.top/Article/details/gtfzsmpzek.html

[A11] 条件表达式（三元）
来源：http://dali.yj20258888.top/Article/details/gtzfwtqudv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xylfe.cn/Article/details/gtaiqvitzy.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtmrsjrwrh.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gtivhildwl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ybcxt.top/Article/details/gtbbcggjrm.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gtdjincrpq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.gotoacloud.top/Article/details/gtsbnwylki.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gtuupfisjm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtjgrorpjk.html

[A12] 字符串插值 / 格式化
来源：http://dali.gaohongyu789.top/Article/details/gtqqolegpj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj20258.top/Article/details/gtxlnfpdnp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.daria6918.cn/Article/details/gtvhkbpxod.html

JS:   `Hello, ${name}!`
来源：http://dali.yuanzhike.top/Article/details/gtqutxkbng.html

TS:   `Hello, ${name}!`
来源：http://dali.andypj.xyz/Article/details/gtwztgikaf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sweek.top/Article/details/gtfpvrejsl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gotoacloud.top/Article/details/gtwkwjumfo.html

Ruby: "Hello, #{name}!"
来源：http://dali.hnqzz.top/Article/details/gtgixlboiy.html

C#:   $"Hello, {name}!"
来源：http://dali.chenlongwang.top/Article/details/gtnspbfcsf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.pengpengdd.cyou/Article/details/gtkpnbqash.html

Py:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtaooihjaf.html

PHP:  "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtokiwcmei.html

JS:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtatxfqnsi.html

TS:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gthgpkwunc.html

Java: "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtoobfcpta.html

Go:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtyeudlryd.html

Ruby: "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtpyvsppkj.html

C#:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtrlduawrc.html


<!-- 参考信息 -->