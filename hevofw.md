代发 wailian999

[U81] JS：初始化项目
来源：http://dali.tian-w.cn/Article/details/gtdunipybf.html

npm init -y;  npm i express
来源：http://dali.sweek.top/Article/details/gtnuhzcukp.html

[U82] JS：package.json 脚本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhexclit.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zycfv.cn/Article/details/gtsxaxonrl.html

[U83] JS：ES Module 导入导出
来源：http://dali.havefunace.top/Article/details/gtgarbywjk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gtzvlnlxtr.html

[U84] JS：CommonJS 写法
来源：http://dali.ivvv.top/Article/details/gtcsucjsll.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jlsjyb.cn/Article/details/gtulvkqsvr.html

[U85] JS：可选链
来源：http://dali.yuxming.cn/Article/details/gtskemshpf.html

a?.b?.c
来源：http://dali.aibaodan.cn/Article/details/gtlwpmnfvj.html

[U86] JS：空值合并
来源：http://dali.haohaochexian.top/Article/details/gtnmlvoovs.html

a ?? b
来源：http://dali.andypj.xyz/Article/details/gtpidhgpgw.html

[U87] JS：解构默认值
来源：http://dali.zdqjudy.top/Article/details/gttlewjsos.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xylfe.cn/Article/details/gtgnyulgps.html

[U88] JS：对象展开合并
来源：http://dali.zhixingplan.top/Article/details/gtuvhtuslg.html

{ ...a, ...b }
来源：http://dali.yonumen.top/Article/details/gtpcnxkfem.html

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gtxeafbahp.html

[...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtaqwjkvbe.html

[U90] JS：数字数组排序
来源：http://dali.gzhubu.top/Article/details/gtaawfhtyg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtiiyzyrjq.html

[U91] JS：对象键值遍历
来源：http://dali.gzhubu.top/Article/details/gtqsxglblj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pengpengdd.cyou/Article/details/gtixykiuqh.html

[U92] JS：深拷贝
来源：http://dali.gaohongyu789.top/Article/details/gttlwijbkp.html

structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gthnsynuff.html

[U93] JS：模板字符串
来源：http://dali.havefunace.top/Article/details/gtglwymekq.html

`共 ${n} 条`
来源：http://dali.wangdashe.top/Article/details/gtxdsoqbci.html

[U94] JS：箭头函数
来源：http://dali.aizwys.cn/Article/details/gtyxmrqsnx.html

const double = x => x * 2;
来源：http://dali.mhx1999.top/Article/details/gtudymzzeb.html

[U95] JS：Promise 包装
来源：http://dali.ppjwa.cn/Article/details/gthhpcwfxj.html

new Promise((resolve, reject) => {})
来源：http://dali.tian-w.cn/Article/details/gtsqibdzmh.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtldwzbsco.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtngzemhod.html

[U97] JS：并发请求
来源：http://dali.xuetiantiany.cn/Article/details/gtkxlzksco.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtixmcdqfi.html

[U98] JS：fetch 带 JSON
来源：http://dali.jiagoushi.top/Article/details/gtmcbggnfm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fengsongda.top/Article/details/gtrqhrxmys.html

[U99] JS：事件监听
来源：http://dali.andypj.xyz/Article/details/gthgiepwyb.html

el.addEventListener("click", e => {})
来源：http://dali.yueranfly.top/Article/details/gtlezhovui.html

[U100] JS：DOM 查询
来源：http://dali.xinyue.icu/Article/details/gtqsjmsdpb.html

document.querySelector(".item")
来源：http://dali.cqqwz.cn/Article/details/gtollhicvc.html

[U101] JS：classList 操作
来源：http://dali.yanxiufei.cn/Article/details/gtzycmjarm.html

el.classList.toggle("active")
来源：http://dali.jyoumei.cn/Article/details/gtlgqsndxc.html

[U102] JS：本地存储
来源：http://dali.zhoulong.xyz/Article/details/gtfoaufzet.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yongpay.top/Article/details/gtmktuxsot.html

[U103] JS：定时器
来源：http://dali.meibo888.top/Article/details/gthplvmtph.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hammf.cn/Article/details/gtlvayqeaf.html

[U104] JS：防抖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjxyqlso.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtmrypdcfv.html

[U105] JS：节流
来源：http://dali.meibo888.top/Article/details/gtxdoillip.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuanzhike.top/Article/details/gtwdqmutlc.html

[U106] JS：日期格式化
来源：http://dali.xinyue.icu/Article/details/gtxwrdazdw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xinyue.icu/Article/details/gtnzpersam.html

[U107] JS：数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gtdytuguso.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtaujshldb.html

[U108] JS：随机整数
来源：http://dali.zhongyouzk.top/Article/details/gtzxgmyrkx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.meibo888.top/Article/details/gtgsvkxlrn.html

[U109] JS：数组分组
来源：http://dali.svipenyu.cn/Article/details/gtmpphazca.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gtffofccju.html

[U110] JS：数组分块
来源：http://dali.dianchejie.cn/Article/details/gtxcznejea.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhoulong.xyz/Article/details/gtkddnaagk.html

[U111] JS：对象转 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubuyllai.html

new Map(Object.entries(obj))
来源：http://dali.ivvv.top/Article/details/gtjavfezhw.html

[U112] JS：字符串补位
来源：http://dali.tanke756.top/Article/details/gtowlupoxp.html

"7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtzgnljbse.html

[U113] JS：正则替换全部
来源：http://dali.shuidangran.top/Article/details/gtwayfeycq.html

s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtgzisnhmt.html

[U114] JS：JSON 深比较
来源：http://dali.hnxiangtu.top/Article/details/gtzqjfaxld.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gtykdudpjh.html

[U115] JS：生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtmolfkvfn.html

crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtytaoabpr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.9152youxi.cn/Article/details/gtkpvuutcy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jyoumei.cn/Article/details/gtctxsfynv.html

[U117] JS：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyknurbo.html

npm i -D vitest;  npx vitest
来源：http://dali.cdnleiting.top/Article/details/gtrxsqvnkj.html

[U118] JS：开发服务器
来源：http://dali.haohaochexian.top/Article/details/gtzflkrrkp.html

npm i -D vite;  npx vite
来源：http://dali.tian-w.cn/Article/details/gtqdepunrp.html

[U119] JS：生产构建
来源：http://dali.9152youxi.cn/Article/details/gtpnzlasag.html

npx vite build
来源：http://dali.ydzc1.top/Article/details/gtsdqopuic.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yuxming.cn/Article/details/gtdocefrye.html

import.meta.env.VITE_API_URL
来源：http://dali.tanke756.top/Article/details/gthddducuu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtiijyatud.html

统计汇总
来源：http://dali.jiagoushi.top/Article/details/gtydysmqvu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkwaioppj.html

按语言统计（条）：
来源：http://dali.daria6918.cn/Article/details/gtxjjgbgdq.html

Python ......... 252
来源：http://dali.feifeiyinyue.top/Article/details/gteiqawdwy.html

PHP ............ 252
来源：http://dali.yueranfly.top/Article/details/gtvkcgthmi.html

JavaScript ..... 252
来源：http://dali.daxiang520.top/Article/details/gtjsgtrnqx.html

TypeScript ..... 212
来源：http://dali.cqqwz.cn/Article/details/gtgddzawwe.html

Java ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtpedpwnqf.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gtrvbcdnon.html

Ruby ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gtpheylvtu.html

C# ............. 212
来源：http://dali.zhiwuduotai.top/Article/details/gtsrgeudiq.html

C .............. 30
来源：http://dali.sxryk.cn/Article/details/gtvaicqvea.html

C++ ............ 30
来源：http://dali.zdqjudy.top/Article/details/gtsrtnvexf.html

SQL ............ 90
来源：http://dali.cashguo.top/Article/details/gtxmatyann.html

Bash ........... 80
来源：http://dali.dashuyun.cn/Article/details/gtjhksdcqw.html

Kotlin ......... 15
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbksxezg.html

Swift .......... 15
来源：http://dali.jlsjyb.cn/Article/details/gtwlhlrcsq.html

Lua ............ 10
来源：http://dali.pengpengdd.cyou/Article/details/gtfpgvglle.html

Perl ........... 10
来源：http://dali.yueranfly.top/Article/details/gtcczxqzmr.html

Scala .......... 10
来源：http://dali.9152youxi.cn/Article/details/gtqmragabj.html

------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvkyygno.html

合计 ........... 2106 条
来源：http://dali.jinqigfzy.top/Article/details/gtvtsrcmyv.html

按章节统计：
来源：http://dali.chenzaomai.com/Article/details/gtzaytwvey.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gtgrtvdzpq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtzxfrnlrc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtfrvuvzxq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gtaqidsnrp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guannengcc.top/Article/details/gtceffxjwz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gthdqnvoeu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gttjxdjydp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gtqekepkuw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtamgazvul.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gtxoidzinx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtcxxsyold.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtzdxmahmw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtpumjjyvn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.9152youxi.cn/Article/details/gtujleyndt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sxryk.cn/Article/details/gttunseayg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtjnxigtud.html

Q SQL 专题                              90
来源：http://dali.chenlongwang.top/Article/details/gtlqydwxoq.html

R Bash 专题                             80
来源：http://dali.zhengqikj.top/Article/details/gtvroqyoyl.html

S C / C++ 专题                          60
来源：http://dali.yvedp.cn/Article/details/gtrgeakrli.html

T 其他语言补充                          60
来源：http://dali.jinqigufen.top/Article/details/gtnegfvbvm.html

U 高频实用片段                         120
来源：http://dali.sysykeji.top/Article/details/gtmyybxgle.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtlvbyxfia.html

合计                                  2106 条
来源：http://dali.ydzc1.top/Article/details/gtwcdjzgss.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtyczochac.html

使用提醒
来源：http://dali.jqgfzy.top/Article/details/gtoyblcxso.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtyzklgrtk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.birdmap.top/Article/details/gtdzljpkjn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gaohongyu789.top/Article/details/gtjtaforom.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigfzy.top/Article/details/gtowbdretj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.dashuyun.cn/Article/details/gtpnlwvrpi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.mhx1999.top/Article/details/gtvyjwxgth.html

—— 文件结束 ——
来源：http://dali.zhoulong.xyz/Article/details/gtosfabzbz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwxumcqoe.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.feifeiyinyue.top/Article/details/gtoiisxdkf.html

Common Programming Examples Cheat Book
来源：http://dali.wangdashe.top/Article/details/gtglgwgemf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtlxtktabn.html

【收录内容】
来源：http://dali.fzhhl.top/Article/details/gtpmtfkkrc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sweek.top/Article/details/gtbyvhdkse.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoitzqwqa.html

SQL · Bash · C · C++
来源：http://dali.hywenlv.cn/Article/details/gtphnnglgp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xylfe.cn/Article/details/gtbbjcnxey.html

【使用说明】
来源：http://dali.shzxlz.cn/Article/details/gtmztomobg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gzhubu.top/Article/details/gtekgewwhl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.c1oappe.top/Article/details/gtigsopytg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ydzc1.top/Article/details/gtcnavjbia.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gotoacloud.top/Article/details/gtyhojiskw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.mhx1999.top/Article/details/gtfimuoufs.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shzxlz.cn/Article/details/gtujlbrrat.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cashguo.top/Article/details/gttqphfped.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.pycfn.com/Article/details/gtdnjtiqyi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jlsjyb.cn/Article/details/gticmzymxp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gzhubu.top/Article/details/gthkohpldc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.fengsongda.top/Article/details/gtiysajosv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ydzc1.top/Article/details/gtylfdwubu.html

【文件统计】
来源：http://dali.ppjwa.cn/Article/details/gtbqbpomai.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ppjwa.cn/Article/details/gtkpzuegnq.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtvnqpkbdj.html

目  录
来源：http://dali.yangfankeji.com/Article/details/gtqbaxuqcq.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtcseazqam.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtnrcjmajy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtbklywkpw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gtffmvrdse.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gogol.net.cn/Article/details/gtnhqkgpjc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnqzz.top/Article/details/gtkuoukxnr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gtqmtncvty.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gtrhuuevna.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gzhubu.top/Article/details/gtxklmpaou.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtonqezssk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gttfmcqqzn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtsnozomsw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gthjsqyzfg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gtxobocbwq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gtcdgxculc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gzhubu.top/Article/details/gtopbbrwra.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gtuwdrlwde.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gaohongyu789.top/Article/details/gtkysxohgt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtlrfqzsdd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.vqdsnc.cn/Article/details/gtppdpznks.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtbmmprajj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtyixrsgfg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtnlphdkli.html

A. 基础语法与类型
来源：http://dali.zdqjudy.top/Article/details/gtoexapxds.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtyhwpttad.html

[A01] Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdqapcsx.html

Py:   print("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gtohvujgte.html

PHP:  echo "Hello, World!";
来源：http://dali.hnqzz.top/Article/details/gtnlrlhftl.html

JS:   console.log("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtpmdzxekj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvedqoyvp.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gtdbiywuoo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sweek.top/Article/details/gtzuyfifpw.html

Ruby: puts "Hello, World!"
来源：http://dali.yangfankeji.com/Article/details/gttplyytot.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sufxvd.cn/Article/details/gteezuaaea.html

[A02] 变量声明与赋值
来源：http://dali.vqdsnc.cn/Article/details/gtlksvpazf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetghsnyo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtdsogyvbx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinqigufen.top/Article/details/gtmjfltvgj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jyoumei.cn/Article/details/gtnfylzpyr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtiyqoweqd.html

Go:   name := "Alex"; age := 20
来源：http://dali.shzxlz.cn/Article/details/gtikajjqzo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinqigfzy.top/Article/details/gtehyolktd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yuxming.cn/Article/details/gtcmnrpjfa.html

[A03] 常量定义
来源：http://dali.yonumen.top/Article/details/gtvlrgslbg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdkflgeh.html

PHP:  const PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtnpclahhx.html

JS:   const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtnntelflt.html

TS:   const PI: number = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtovvdiltg.html

Java: static final double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gttxmsviql.html

Go:   const PI = 3.14159
来源：http://dali.tanke756.top/Article/details/gtzimqlpaa.html

Ruby: PI = 3.14159
来源：http://dali.zhengqikj.top/Article/details/gtdeyznbhr.html

C#:   const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtkshcehhg.html

[A04] 判断变量类型
来源：http://dali.zhixingplan.top/Article/details/gthdokwaoq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gtueulsjdj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zycfv.cn/Article/details/gtqexoreeh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hammf.cn/Article/details/gtzthmuasx.html

TS:   typeof x; x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gtpwdjtakc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sufxvd.cn/Article/details/gtodwfoagn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnqzz.top/Article/details/gtuxktumpf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cdnleiting.top/Article/details/gtbqfgffii.html

C#:   x.GetType().Name; x is int
来源：http://dali.sufxvd.cn/Article/details/gtkpvjdqdy.html

[A05] 整数除法与取模
来源：http://dali.iojbl.cn/Article/details/gtshcsrbfl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigfzy.top/Article/details/gtvhxskxwz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtarebgctq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgauemcqu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtvqwgmcpz.html

Java: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtmywgzmou.html

Go:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtlychwxsn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gtqciiydcr.html

C#:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gttivqkpkz.html

[A06] 字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gtdqoaffqz.html

Py:   int("42"); float("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gtddmnxehy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hywenlv.cn/Article/details/gtfshpwvyf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.meibo888.top/Article/details/gtagenuvqm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.snrcjt.cn/Article/details/gtuluvcejr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gtfncyxyfs.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zycfv.cn/Article/details/gtungvbesw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj20258888.top/Article/details/gtbldbozjr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xylfe.cn/Article/details/gtgnvjtzsw.html

[A07] 数字转字符串
来源：http://dali.cucudq.cn/Article/details/gtdypdjors.html

Py:   str(42)
来源：http://dali.hammf.cn/Article/details/gtyglqmssk.html

PHP:  (string) 42; strval(42)
来源：http://dali.dashuyun.cn/Article/details/gtvaiacxqq.html

JS:   String(42); (42).toString()
来源：http://dali.jianghu66.top/Article/details/gtfvkywmjr.html

TS:   String(42)
来源：http://dali.guannengcc.top/Article/details/gtjoijvymi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.daria6918.cn/Article/details/gtiexameqv.html

Go:   strconv.Itoa(42)
来源：http://dali.yanxiufei.cn/Article/details/gtdmwsijzw.html

Ruby: 42.to_s
来源：http://dali.yvedp.cn/Article/details/gthhascmek.html

C#:   42.ToString()
来源：http://dali.fzhhl.top/Article/details/gtasjylyqu.html

[A08] 取整与四舍五入
来源：http://dali.yangfankeji.com/Article/details/gtyhtvvetx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtmofiqszg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.chenjidiqi.icu/Article/details/gtctnmgcll.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gtmoxodpbv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.kuanghao11.cn/Article/details/gtvpmpprta.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gtxuwttbqo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtkskepvrd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.wangshuangyany.cn/Article/details/gtmhekstft.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gtrjxufsnp.html

[A09] 绝对值与最大最小值
来源：http://dali.yongpay.top/Article/details/gtftwjftrk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtamonoald.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtjvnumldr.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtmhjvedse.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuqjxvyh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtrwmswkks.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hnxiangtu.top/Article/details/gtqhtadvik.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.9152youxi.cn/Article/details/gtxouqlqra.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtpquyogov.html

[A10] 生成随机数
来源：http://dali.jlsjyb.cn/Article/details/gttpbevewj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ybcxt.top/Article/details/gtuxpziokc.html

PHP:  random_int(1, 100);
来源：http://dali.haohaochexian.top/Article/details/gttzwjazvo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.daxiang520.top/Article/details/gtlpgpuapg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aibaodan.cn/Article/details/gtqkiwcmyo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtmflgggwq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ppjwa.cn/Article/details/gtsljjcdlw.html

Ruby: rand(1..100)
来源：http://dali.snrcjt.cn/Article/details/gtvzxelwdt.html

C#:   new Random().Next(1, 101)
来源：http://dali.yj202588.top/Article/details/gtrnwdpwhd.html

[A11] 条件表达式（三元）
来源：http://dali.jinqigfzy.top/Article/details/gtagmytand.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.wangdashe.top/Article/details/gtnpefbati.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gtsonlzamj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtevsgbttb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gtzcmmvfhi.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gtpzumcwfl.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hongshengwenyu.top/Article/details/gtnqhrtksh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gtbgabqwhq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gtaildbmje.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gtvpvaafnw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.aibaodan.cn/Article/details/gtlunsecbp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gotoacloud.top/Article/details/gtolelvtlv.html

JS:   `Hello, ${name}!`
来源：http://dali.hnxiangtu.top/Article/details/gtefczcwxy.html

TS:   `Hello, ${name}!`
来源：http://dali.ivvv.top/Article/details/gttoswkbwi.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.vqdsnc.cn/Article/details/gtyljgyzpt.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.sweek.top/Article/details/gtsohpxrbr.html

Ruby: "Hello, #{name}!"
来源：http://dali.yuxming.cn/Article/details/gtdftmjdha.html

C#:   $"Hello, {name}!"
来源：http://dali.jqgufenzy.top/Article/details/gtofscxfxf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sweek.top/Article/details/gtnaagdjch.html

Py:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtvknpgoud.html

PHP:  "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gtcuywtgwy.html

JS:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gtqmmwfmbc.html

TS:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtakrlqmhz.html


<!-- 参考信息 -->