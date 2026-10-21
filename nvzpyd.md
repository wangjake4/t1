代发 wailian999

[U87] JS：解构默认值
来源：http://dali.zdqjudy.top/Article/details/gtujvisyui.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangtech.top/Article/details/gttjbvqmyt.html

[U88] JS：对象展开合并
来源：http://dali.bjfxy.top/Article/details/gteoiqybdx.html

{ ...a, ...b }
来源：http://dali.yongpay.top/Article/details/gttjyraebb.html

[U89] JS：数组去重
来源：http://dali.zhongyouzk.top/Article/details/gtuazijrpy.html

[...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtwnpdwzsm.html

[U90] JS：数字数组排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgwhmspc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtsqvqclyh.html

[U91] JS：对象键值遍历
来源：http://dali.jinqigfzy.top/Article/details/gtacejshoj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yonumen.top/Article/details/gtxebfcywr.html

[U92] JS：深拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtlckmoapn.html

structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtqyndiqcv.html

[U93] JS：模板字符串
来源：http://dali.fengsongda.top/Article/details/gtmtikrtrz.html

`共 ${n} 条`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqkmpmzd.html

[U94] JS：箭头函数
来源：http://dali.daxiang520.top/Article/details/gtkexpqpup.html

const double = x => x * 2;
来源：http://dali.sysykeji.top/Article/details/gtykkihggp.html

[U95] JS：Promise 包装
来源：http://dali.wangdashe.top/Article/details/gtdtwoxvbj.html

new Promise((resolve, reject) => {})
来源：http://dali.yj20258888.top/Article/details/gtgmebbztv.html

[U96] JS：async/await 与异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkdxreyr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtbvomezsg.html

[U97] JS：并发请求
来源：http://dali.aizwys.cn/Article/details/gtjasrxalv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtnfproywq.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtarkrpjia.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gogol.net.cn/Article/details/gtzhophevz.html

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gtkicirytv.html

el.addEventListener("click", e => {})
来源：http://dali.andypj.xyz/Article/details/gtbnnijvvi.html

[U100] JS：DOM 查询
来源：http://dali.ehwqpu.com/Article/details/gtefpifhju.html

document.querySelector(".item")
来源：http://dali.yanxiufei.cn/Article/details/gtrpgjewnf.html

[U101] JS：classList 操作
来源：http://dali.yanxiufei.cn/Article/details/gtqyoqfkaq.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwxmysok.html

[U102] JS：本地存储
来源：http://dali.0kj1m.cn/Article/details/gtyutcoamr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sufxvd.cn/Article/details/gtbkktdnfa.html

[U103] JS：定时器
来源：http://dali.cdnleiting.top/Article/details/gtxiqcdgtj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yueranfly.top/Article/details/gtbjrffocp.html

[U104] JS：防抖
来源：http://dali.hnxiangtu.top/Article/details/gtomejbhne.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtaefpkpuw.html

[U105] JS：节流
来源：http://dali.yuanzhike.top/Article/details/gttmcfymqx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.dianchejie.cn/Article/details/gtfhdjvojc.html

[U106] JS：日期格式化
来源：http://dali.0kj1m.cn/Article/details/gthkmlznxr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhixingplan.top/Article/details/gtimrzgtxo.html

[U107] JS：数字千分位
来源：http://dali.pycfn.com/Article/details/gtwribkide.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zycfv.cn/Article/details/gtkwbfhyro.html

[U108] JS：随机整数
来源：http://dali.feifeiyinyue.top/Article/details/gtbszgkzje.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenzaomai.com/Article/details/gtmcjjvgga.html

[U109] JS：数组分组
来源：http://dali.9152youxi.cn/Article/details/gtzvhrvcrd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gterrkqkxw.html

[U110] JS：数组分块
来源：http://dali.hfpthk.cn/Article/details/gtgsbhqaot.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cucudq.cn/Article/details/gtpnlwxssa.html

[U111] JS：对象转 Map
来源：http://dali.jlsjyb.cn/Article/details/gtqqmivzqf.html

new Map(Object.entries(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtqnaymfss.html

[U112] JS：字符串补位
来源：http://dali.yangfankeji.com/Article/details/gteatoskzh.html

"7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtrflopgcv.html

[U113] JS：正则替换全部
来源：http://dali.fengsongda.top/Article/details/gttydonvcv.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtizrywlor.html

[U114] JS：JSON 深比较
来源：http://dali.yueranfly.top/Article/details/gtrpddvtub.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtffbwnrks.html

[U115] JS：生成 UUID
来源：http://dali.c1oappe.top/Article/details/gtpfdtvesm.html

crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtlrmdzkro.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xinyue.icu/Article/details/gtqgzhqvso.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cucudq.cn/Article/details/gtckemeead.html

[U117] JS：单元测试
来源：http://dali.ivvv.top/Article/details/gtwyqevmii.html

npm i -D vitest;  npx vitest
来源：http://dali.9152youxi.cn/Article/details/gtjgtdzifv.html

[U118] JS：开发服务器
来源：http://dali.fzhhl.top/Article/details/gtmymkmhpq.html

npm i -D vite;  npx vite
来源：http://dali.cheryme.top/Article/details/gttcgoxmsv.html

[U119] JS：生产构建
来源：http://dali.zhongyouzk.top/Article/details/gteuftidzp.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchpwweza.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiozlpzbi.html

import.meta.env.VITE_API_URL
来源：http://dali.ybcxt.top/Article/details/gtkysjbjpn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtajdrwfll.html

统计汇总
来源：http://dali.hammf.cn/Article/details/gtgqldbwcg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtruzttrkx.html

按语言统计（条）：
来源：http://dali.shanyushiyangtech.top/Article/details/gtzothmgou.html

Python ......... 252
来源：http://dali.yonumen.top/Article/details/gtxonsruaq.html

PHP ............ 252
来源：http://dali.ydzc1.top/Article/details/gtjbpbmtuz.html

JavaScript ..... 252
来源：http://dali.chenjidiqi.icu/Article/details/gtprhhlsms.html

TypeScript ..... 212
来源：http://dali.xuanzx.com/Article/details/gtepjxxubg.html

Java ........... 212
来源：http://dali.yuxming.cn/Article/details/gtkoecniro.html

Go ............. 212
来源：http://dali.fzhhl.top/Article/details/gtzymvzkxr.html

Ruby ........... 212
来源：http://dali.ehwqpu.com/Article/details/gthebeawkv.html

C# ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gtxkzflpgu.html

C .............. 30
来源：http://dali.hnqzz.top/Article/details/gtztggfsuv.html

C++ ............ 30
来源：http://dali.zhiwuduotai.top/Article/details/gtqqiauksg.html

SQL ............ 90
来源：http://dali.zhoulong.xyz/Article/details/gtticenwth.html

Bash ........... 80
来源：http://dali.meibo888.top/Article/details/gtybinvvyz.html

Kotlin ......... 15
来源：http://dali.feifeiyinyue.top/Article/details/gtbugtdubx.html

Swift .......... 15
来源：http://dali.zhongyouzk.top/Article/details/gtlkzzdgen.html

Lua ............ 10
来源：http://dali.gogol.net.cn/Article/details/gtyohzgbzj.html

Perl ........... 10
来源：http://dali.nanxinkj.top/Article/details/gtubksjngr.html

Scala .......... 10
来源：http://dali.jlsjyb.cn/Article/details/gtszaambry.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtjjvanpqq.html

合计 ........... 2106 条
来源：http://dali.daxiang520.top/Article/details/gtmdhxddzq.html

按章节统计：
来源：http://dali.cqqwz.cn/Article/details/gtrdlmuhxj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gtsqqwnlua.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtonwjyonr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtjgqxkmev.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtglnwsxlq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenzaomai.com/Article/details/gtrtqfykcl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gtjbnwktgv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtoosyckhb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.316326.xyz/Article/details/gtngnuqimx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtycvksawr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gticvqbsgz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadxcrsqy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtapujxhbl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtoimokfld.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.haohaochexian.top/Article/details/gtwslkhvnj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cqqwz.cn/Article/details/gthgfwizxq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtjzejhbgk.html

Q SQL 专题                              90
来源：http://dali.vqdsnc.cn/Article/details/gtnxutoozn.html

R Bash 专题                             80
来源：http://dali.shuidangran.top/Article/details/gtvuhfurub.html

S C / C++ 专题                          60
来源：http://dali.shangyingyoupin.top/Article/details/gtxfzqnhoj.html

T 其他语言补充                          60
来源：http://dali.chenzaomai.com/Article/details/gtrkbctwzy.html

U 高频实用片段                         120
来源：http://dali.andypj.xyz/Article/details/gtgrtzsfch.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtaeygsxbg.html

合计                                  2106 条
来源：http://dali.gaohongyu789.top/Article/details/gtwavxktln.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtmjpunfoe.html

使用提醒
来源：http://dali.316326.xyz/Article/details/gtfbbiuavd.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtnflkpzjh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jianghu66.top/Article/details/gtbdwwthpl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.mhx1999.top/Article/details/gtbsfvcjek.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyenxjzwp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj20258888.top/Article/details/gtjqvbdlgh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuanzx.com/Article/details/gtkpovuhyp.html

—— 文件结束 ——
来源：http://dali.ybcxt.top/Article/details/gtthwirlvh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqujkvimj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xuetiantiany.cn/Article/details/gtqixzbega.html

Common Programming Examples Cheat Book
来源：http://dali.shzxlz.cn/Article/details/gtrzuvozbi.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttkrvsaxn.html

【收录内容】
来源：http://dali.quarkkingdee.top/Article/details/gteuwkiske.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhongyouzk.top/Article/details/gtuqpsrzil.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jianghu66.top/Article/details/gtesmomxrf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gtonajrgzy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.svipenyu.cn/Article/details/gtkyrkvvxs.html

【使用说明】
来源：http://dali.chenlongwang.top/Article/details/gtjpjmkeiu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cucudq.cn/Article/details/gtecnotlgp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dashuyun.cn/Article/details/gtzpgfdzex.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgufenzy.top/Article/details/gtofannmqk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ydzc1.top/Article/details/gtmetavcrh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gaohongyu789.top/Article/details/gtkpzoloyf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yueranfly.top/Article/details/gtkmpiaueo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shzxlz.cn/Article/details/gtzeczjdhh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hnqzz.top/Article/details/gtezlfanzn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cdnleiting.top/Article/details/gtrtlgjvyp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hnxiangtu.top/Article/details/gtygucnejy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinqigfzy.top/Article/details/gtwwmwcicz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xuanzx.com/Article/details/gtzkgscwjn.html

【文件统计】
来源：http://dali.nanxinkj.top/Article/details/gtdfmzazsz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sxryk.cn/Article/details/gtvpnnfbvm.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtakakqzuq.html

目  录
来源：http://dali.andypj.xyz/Article/details/gtujwimece.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtdzfabjnu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gtzxwaconx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.daxiang520.top/Article/details/gtqkajufdf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfxmfudn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zycfv.cn/Article/details/gtwbkljyuf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cucudq.cn/Article/details/gtigiuspfa.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gtbkssuefj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xziqi.cn/Article/details/gthjcrwfim.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtiphecwnl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtnrtdoqwg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gtpurtwrxx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtrlyhjoft.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtwrxrubfz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtdkyeoiaq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.fzhhl.top/Article/details/gtzprhfqio.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sysykeji.top/Article/details/gttpqyjfjy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtcsyaetjc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxvlbmcn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xuanzx.com/Article/details/gtxsjtuwlx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtbjlvqn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtcnhjvnmg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtdsbpnycc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthiidllfv.html

A. 基础语法与类型
来源：http://dali.hysaishi.cn/Article/details/gtfnlnnnbo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtgdwpqujs.html

[A01] Hello World
来源：http://dali.ivvv.top/Article/details/gtxmlqhyvr.html

Py:   print("Hello, World!")
来源：http://dali.yangfankeji.com/Article/details/gtgaatoxzc.html

PHP:  echo "Hello, World!";
来源：http://dali.birdmap.top/Article/details/gtmxjnaeqx.html

JS:   console.log("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gtdaixtzix.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.fengsongda.top/Article/details/gtubzazkci.html

Java: System.out.println("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gtdbpepwuz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gteodadppi.html

Ruby: puts "Hello, World!"
来源：http://dali.9152youxi.cn/Article/details/gtxprmuqpl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeybnggi.html

[A02] 变量声明与赋值
来源：http://dali.yj202588.top/Article/details/gtpukkxeka.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cqqwz.cn/Article/details/gthrsdqjgt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtttpsxgvx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.redwolf501.top/Article/details/gtiwwtgyso.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.0kj1m.cn/Article/details/gttcbgtmku.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigufen.top/Article/details/gtdpddqfip.html

Go:   name := "Alex"; age := 20
来源：http://dali.yongpay.top/Article/details/gtlbydpiqh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenjidiqi.icu/Article/details/gttczmrzuk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ivvv.top/Article/details/gtbzlujwzx.html

[A03] 常量定义
来源：http://dali.pycfn.com/Article/details/gtsqkoemlg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.birdmap.top/Article/details/gtrfibokqi.html

PHP:  const PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtldmeqibm.html

JS:   const PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtrynhcril.html

TS:   const PI: number = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtzrsjfpks.html

Java: static final double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtifmgqbok.html

Go:   const PI = 3.14159
来源：http://dali.yangfankeji.com/Article/details/gtcwbbobbm.html

Ruby: PI = 3.14159
来源：http://dali.aizwys.cn/Article/details/gtekczzkbw.html

C#:   const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtaisjyonk.html

[A04] 判断变量类型
来源：http://dali.gotoacloud.top/Article/details/gthbzhwnts.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yangfankeji.com/Article/details/gtbnoichnd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.vqdsnc.cn/Article/details/gtqaonwcju.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yueranfly.top/Article/details/gtegxisuwy.html

TS:   typeof x; x instanceof Date
来源：http://dali.havefunace.top/Article/details/gtuvnkrlbp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yangfankeji.com/Article/details/gttsepncpp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhoulong.xyz/Article/details/gtkojjaikp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.redwolf501.top/Article/details/gtekzirype.html

C#:   x.GetType().Name; x is int
来源：http://dali.nwbrower.top/Article/details/gttdmkzzng.html

[A05] 整数除法与取模
来源：http://dali.shuidangran.top/Article/details/gtezeqowsa.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.svipenyu.cn/Article/details/gtjpaxwnox.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtsedxcmdp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gtgbtsttkw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtvltlxlpx.html

Java: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtuaxpcfnn.html

Go:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtldocxqbc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtjqdngwnh.html

C#:   7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtpjoxdneh.html

[A06] 字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtdmkegqlw.html

Py:   int("42"); float("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gtksslqdhf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.pengpengdd.cyou/Article/details/gtifgqgizq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.bjfxy.top/Article/details/gtntdngrcb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.daxiang520.top/Article/details/gtqrcuvzjm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zycfv.cn/Article/details/gtxzftcjlv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.316326.xyz/Article/details/gtbrzsjuml.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.feifeiyinyue.top/Article/details/gtmggjddaf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gtjncuxpfp.html

[A07] 数字转字符串
来源：http://dali.ppjwa.cn/Article/details/gtdfaxxplc.html

Py:   str(42)
来源：http://dali.daria6918.cn/Article/details/gthzklgsnq.html

PHP:  (string) 42; strval(42)
来源：http://dali.tianlin.xyz/Article/details/gtztidivdh.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gtmumxgnal.html

TS:   String(42)
来源：http://dali.jinqigfzy.top/Article/details/gtfpaknkwr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shuidangran.top/Article/details/gtagfkfsgs.html

Go:   strconv.Itoa(42)
来源：http://dali.jinqigufen.top/Article/details/gtnsflwunl.html

Ruby: 42.to_s
来源：http://dali.hammf.cn/Article/details/gtdhqsfdwu.html

C#:   42.ToString()
来源：http://dali.xziqi.cn/Article/details/gttwynketc.html

[A08] 取整与四舍五入
来源：http://dali.aibaodan.cn/Article/details/gtogekmbgm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtsxqejnhn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.mhx1999.top/Article/details/gtgludaqfb.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtrklyfofc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yonumen.top/Article/details/gtwyrmoiyb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtwieqnepg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtdbtzyjby.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinghuilouyu.cn/Article/details/gtcudkobfl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtdwkfppiq.html

[A09] 绝对值与最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtaexttfxo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtnpgwhsit.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtrkmzheiw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtdjksrvpb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvjpqjvh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtpdmzdgbp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hnqzz.top/Article/details/gtnkgpgqzz.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.birdmap.top/Article/details/gtxiuqjtsc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtjmddqkks.html

[A10] 生成随机数
来源：http://dali.cqqwz.cn/Article/details/gtfxypecuh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xinyue.icu/Article/details/gtozmwadfh.html

PHP:  random_int(1, 100);
来源：http://dali.chenzaomai.com/Article/details/gtaxmdjkvc.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvckpntf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj202588.top/Article/details/gtlowpzheg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhengqikj.top/Article/details/gtxfyadfwr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ppjwa.cn/Article/details/gttnnacuja.html

Ruby: rand(1..100)
来源：http://dali.zhiwuduotai.top/Article/details/gtgmcmwevu.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gtndtwruog.html

[A11] 条件表达式（三元）
来源：http://dali.316326.xyz/Article/details/gtwabqktaw.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.sxryk.cn/Article/details/gtljbcirmj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gtugewnyjk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtdvjrbyej.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gtnkwcexyr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gtpaxxvxej.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.gogol.net.cn/Article/details/gtqwbnlpor.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gtxdakerxz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gtvrtkyzwk.html

[A12] 字符串插值 / 格式化
来源：http://dali.ybcxt.top/Article/details/gtrelxwftp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj20258.top/Article/details/gtbencogfr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.snrcjt.cn/Article/details/gtsmdvtwqe.html

JS:   `Hello, ${name}!`
来源：http://dali.chenzaomai.com/Article/details/gtbroejzka.html

TS:   `Hello, ${name}!`
来源：http://dali.ivvv.top/Article/details/gthhztplqo.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yj20258888.top/Article/details/gtzhkvfdal.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jyoumei.cn/Article/details/gtglvbpocj.html

Ruby: "Hello, #{name}!"
来源：http://dali.jqgfzy.top/Article/details/gtbuyzlgmi.html

C#:   $"Hello, {name}!"
来源：http://dali.ivvv.top/Article/details/gticplkbjh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinqigufen.top/Article/details/gtfqwretsr.html

Py:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gtwletrime.html

PHP:  "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtaaanvraa.html

JS:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtkehgwyvn.html

TS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtriopkylp.html

Java: "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtadeajytj.html

Go:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtsdvhckdr.html

Ruby: "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtwpgitncn.html

C#:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtqjvzkydf.html

[A14] 注释写法
来源：http://dali.jianghu66.top/Article/details/gttrqbsjfq.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.tian-w.cn/Article/details/gttmbsspdk.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gtxfloibym.html

JS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gtugffjcge.html

TS:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gttuhxnlys.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnntraaa.html

Go:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtsbhwoqzq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yonumen.top/Article/details/gtbttvpyph.html


<!-- 参考信息 -->