代发 wailian999

[U85] JS：可选链
来源：http://dali.jianghu66.top/Article/details/gtqlkttipf.html

a?.b?.c
来源：http://dali.sufxvd.cn/Article/details/gtylvaanmk.html

[U86] JS：空值合并
来源：http://dali.svipenyu.cn/Article/details/gtbzjlamur.html

a ?? b
来源：http://dali.gaohongyu789.top/Article/details/gtdgevupmp.html

[U87] JS：解构默认值
来源：http://dali.jqgfzy.top/Article/details/gtssetvxhq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zycfv.cn/Article/details/gtgbclgyth.html

[U88] JS：对象展开合并
来源：http://dali.mhx1999.top/Article/details/gtpduyftfb.html

{ ...a, ...b }
来源：http://dali.svipenyu.cn/Article/details/gtaljjqdze.html

[U89] JS：数组去重
来源：http://dali.kuanghao11.cn/Article/details/gtbpsjbxyq.html

[...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gtzmafzqhq.html

[U90] JS：数字数组排序
来源：http://dali.vqdsnc.cn/Article/details/gtfvckjhkk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtehfeprjx.html

[U91] JS：对象键值遍历
来源：http://dali.jqgfzy.top/Article/details/gtpmrglghv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrsoqlyg.html

[U92] JS：深拷贝
来源：http://dali.guannengcc.top/Article/details/gtdouvoidm.html

structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtobvjzzxe.html

[U93] JS：模板字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtonjgcqvf.html

`共 ${n} 条`
来源：http://dali.ehwqpu.com/Article/details/gtddgkdykd.html

[U94] JS：箭头函数
来源：http://dali.yvedp.cn/Article/details/gtnmcskigt.html

const double = x => x * 2;
来源：http://dali.chenzaomai.com/Article/details/gtoouwrnvz.html

[U95] JS：Promise 包装
来源：http://dali.jyoumei.cn/Article/details/gthnaqnkya.html

new Promise((resolve, reject) => {})
来源：http://dali.gotoacloud.top/Article/details/gtgehakckx.html

[U96] JS：async/await 与异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonfgpzka.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gttrorspmy.html

[U97] JS：并发请求
来源：http://dali.yj202588.top/Article/details/gtfrqeurtp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtmiyxtfnw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhixingplan.top/Article/details/gtegblpics.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yonumen.top/Article/details/gtkzmvfjdw.html

[U99] JS：事件监听
来源：http://dali.zhoulong.xyz/Article/details/gtgqsnfovl.html

el.addEventListener("click", e => {})
来源：http://dali.yuxming.cn/Article/details/gtfswexajg.html

[U100] JS：DOM 查询
来源：http://dali.yj202588.top/Article/details/gtfdadgawd.html

document.querySelector(".item")
来源：http://dali.gogol.net.cn/Article/details/gthhjegdvu.html

[U101] JS：classList 操作
来源：http://dali.zhongyouzk.top/Article/details/gtqfvqvydk.html

el.classList.toggle("active")
来源：http://dali.gogol.net.cn/Article/details/gtxaojwfeq.html

[U102] JS：本地存储
来源：http://dali.cqqwz.cn/Article/details/gtlzbxzyjq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ehwqpu.com/Article/details/gtrnlqnntl.html

[U103] JS：定时器
来源：http://dali.fengsongda.top/Article/details/gtmxebhugb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hywenlv.cn/Article/details/gtoxiwhnap.html

[U104] JS：防抖
来源：http://dali.andypj.xyz/Article/details/gtacehsyvk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gtlvurusdd.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtkkszamkb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ppjwa.cn/Article/details/gtqgrsskwc.html

[U106] JS：日期格式化
来源：http://dali.yj202588.top/Article/details/gtbssqvpde.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nanxuanxn.top/Article/details/gtpmanyqea.html

[U107] JS：数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtbsobgfdq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sysykeji.top/Article/details/gtkrufrjxi.html

[U108] JS：随机整数
来源：http://dali.jqgfzy.top/Article/details/gtkffpuimv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.haohaochexian.top/Article/details/gtiekdkpjh.html

[U109] JS：数组分组
来源：http://dali.c1oappe.top/Article/details/gtaxaxpefu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtidgxccnm.html

[U110] JS：数组分块
来源：http://dali.jqgfzy.top/Article/details/gtjznwspqs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yanxiufei.cn/Article/details/gtframnism.html

[U111] JS：对象转 Map
来源：http://dali.yj202588.top/Article/details/gtunuxcvdk.html

new Map(Object.entries(obj))
来源：http://dali.jinqigufen.top/Article/details/gtumbhkpre.html

[U112] JS：字符串补位
来源：http://dali.tian-w.cn/Article/details/gtengfyqtl.html

"7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtujflxjih.html

[U113] JS：正则替换全部
来源：http://dali.9152youxi.cn/Article/details/gtzdcawppr.html

s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtzwsbqzuq.html

[U114] JS：JSON 深比较
来源：http://dali.cdnleiting.top/Article/details/gtzoytsqkg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yonumen.top/Article/details/gtusylzajg.html

[U115] JS：生成 UUID
来源：http://dali.yonumen.top/Article/details/gtxobjrprp.html

crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtowmuhqoa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tian-w.cn/Article/details/gtkyvcjfgj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.svipenyu.cn/Article/details/gtwcqskvuu.html

[U117] JS：单元测试
来源：http://dali.xylfe.cn/Article/details/gtsvceggmw.html

npm i -D vitest;  npx vitest
来源：http://dali.ivvv.top/Article/details/gtjpuhfdoo.html

[U118] JS：开发服务器
来源：http://dali.chenlongwang.top/Article/details/gtjjksrnxx.html

npm i -D vite;  npx vite
来源：http://dali.gotoacloud.top/Article/details/gtnefocymt.html

[U119] JS：生产构建
来源：http://dali.andypj.xyz/Article/details/gtmfzarsru.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gtgymkciiw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhongyouzk.top/Article/details/gtexxvxvwh.html

import.meta.env.VITE_API_URL
来源：http://dali.0kj1m.cn/Article/details/gttqprkpkg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzofzjttt.html

统计汇总
来源：http://dali.yj20258.top/Article/details/gtjdcyqpuu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmnnkkkud.html

按语言统计（条）：
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgntntkyq.html

Python ......... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjyocrjc.html

PHP ............ 252
来源：http://dali.tian-w.cn/Article/details/gtmflmtbip.html

JavaScript ..... 252
来源：http://dali.cucudq.cn/Article/details/gtdtnizltr.html

TypeScript ..... 212
来源：http://dali.yuanzhike.top/Article/details/gtlnewxdkm.html

Java ........... 212
来源：http://dali.gzhubu.top/Article/details/gtpuaqhjyj.html

Go ............. 212
来源：http://dali.meibo888.top/Article/details/gtdnwyyljt.html

Ruby ........... 212
来源：http://dali.hysaishi.cn/Article/details/gtellmkkuu.html

C# ............. 212
来源：http://dali.jyoumei.cn/Article/details/gttgpeskap.html

C .............. 30
来源：http://dali.fengsongda.top/Article/details/gtsuhmowyk.html

C++ ............ 30
来源：http://dali.yangfankeji.com/Article/details/gtuwgqxaow.html

SQL ............ 90
来源：http://dali.shangyingyoupin.top/Article/details/gtyyghmwlu.html

Bash ........... 80
来源：http://dali.jiagoushi.top/Article/details/gtxtnhudgs.html

Kotlin ......... 15
来源：http://dali.hfpthk.cn/Article/details/gtczryzvkv.html

Swift .......... 15
来源：http://dali.quarkkingdee.top/Article/details/gtagovjjvb.html

Lua ............ 10
来源：http://dali.c1oappe.top/Article/details/gtqgppbqun.html

Perl ........... 10
来源：http://dali.wangshuangyany.cn/Article/details/gtkwfdvrxy.html

Scala .......... 10
来源：http://dali.sysykeji.top/Article/details/gtsftyxhqk.html

------------------------------------
来源：http://dali.sweek.top/Article/details/gtorhwrdol.html

合计 ........... 2106 条
来源：http://dali.vqdsnc.cn/Article/details/gtesvxxgen.html

按章节统计：
来源：http://dali.daria6918.cn/Article/details/gthjrhbsjn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtcgjqjlve.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtqdqnxvha.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gtjxyvpkdh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gtfxvfuywj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxnkster.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gtmemiybva.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gthapbjdnw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gtldwgcfms.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtvmcahjyz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gtimypoyve.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtktsdkqvs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtqsxiydcp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtqjxbxrmi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.haohaochexian.top/Article/details/gtitqdaioe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.aizwys.cn/Article/details/gtwvossbhd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtbjxjqwnq.html

Q SQL 专题                              90
来源：http://dali.xylfe.cn/Article/details/gtruomrinu.html

R Bash 专题                             80
来源：http://dali.nanxinkj.top/Article/details/gtcjmgtcap.html

S C / C++ 专题                          60
来源：http://dali.xuetiantiany.cn/Article/details/gtgmgwynyf.html

T 其他语言补充                          60
来源：http://dali.sufxvd.cn/Article/details/gtuxxleajc.html

U 高频实用片段                         120
来源：http://dali.jqgfzy.top/Article/details/gtdwcqemmv.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtprxtfxay.html

合计                                  2106 条
来源：http://dali.daria6918.cn/Article/details/gthrzeznvw.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtblkmxnwb.html

使用提醒
来源：http://dali.hysaishi.cn/Article/details/gtsclxuzkk.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtbaucdwrd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ivvv.top/Article/details/gtchaoblfm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuanzx.com/Article/details/gtmeewadhw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jlsjyb.cn/Article/details/gtjjjyftou.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yuxming.cn/Article/details/gtbcotfazo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jiagoushi.top/Article/details/gtktcqivko.html

—— 文件结束 ——
来源：http://dali.jqgufenzy.top/Article/details/gtagdfqrjt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxyfywtvx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.316326.xyz/Article/details/gtbaoxalfd.html

Common Programming Examples Cheat Book
来源：http://dali.pycfn.com/Article/details/gtwfvrtmba.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtopbzkeuf.html

【收录内容】
来源：http://dali.bjfxy.top/Article/details/gtoqfrnjmf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.9152youxi.cn/Article/details/gtdjypmomx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gotoacloud.top/Article/details/gtnvvzmvgn.html

SQL · Bash · C · C++
来源：http://dali.dashuyun.cn/Article/details/gterdsxbrq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.haohaochexian.top/Article/details/gtfbemirec.html

【使用说明】
来源：http://dali.xylfe.cn/Article/details/gtwmemhaqy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.daria6918.cn/Article/details/gtyrggznkh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.aizwys.cn/Article/details/gtfxeiqffw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xuanzx.com/Article/details/gtteaxacad.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gtqmwvcoif.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dashuyun.cn/Article/details/gtnvfnmmcs.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tianlin.xyz/Article/details/gtizvhlzka.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.havefunace.top/Article/details/gtegscxoxw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hammf.cn/Article/details/gtykyvniwl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinqigfzy.top/Article/details/gtjlnazpyo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.havefunace.top/Article/details/gtdpaxhbiz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.bjfxy.top/Article/details/gtqoooiwon.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.haohaochexian.top/Article/details/gtcihqrftl.html

【文件统计】
来源：http://dali.xuanzx.com/Article/details/gtbgmkzzcw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shangyingyoupin.top/Article/details/gtdwxwkxol.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtiqqmsxly.html

目  录
来源：http://dali.yvedp.cn/Article/details/gtlksleloo.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtuqvikuak.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gtippldauq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gtdirlaobh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtujqprcvn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenzaomai.com/Article/details/gtypeqnpwu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cheryme.top/Article/details/gtsqkyvayg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.wangdashe.top/Article/details/gtztlmgufa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.c1oappe.top/Article/details/gtgsauujqb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cqqwz.cn/Article/details/gtvpbyalch.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtqtlhkjjq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.smart0.xyz/Article/details/gtgixepqxi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtzzvxekbu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtonlmizud.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtjdprsxfx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gaohongyu789.top/Article/details/gtzycharof.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.iojbl.cn/Article/details/gtquovrpiy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtnhxdqoox.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cheryme.top/Article/details/gtbjxbdybx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.mhx1999.top/Article/details/gteuvolqps.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yuanzhike.top/Article/details/gtageohjhs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtltrmgvbq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtytkxepps.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgrdtbatl.html

A. 基础语法与类型
来源：http://dali.tanke756.top/Article/details/gtbrqdqvtw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtobaeckhf.html

[A01] Hello World
来源：http://dali.ehwqpu.com/Article/details/gtgnabkqvi.html

Py:   print("Hello, World!")
来源：http://dali.mhx1999.top/Article/details/gtdutcoaos.html

PHP:  echo "Hello, World!";
来源：http://dali.vqdsnc.cn/Article/details/gtucwjbakc.html

JS:   console.log("Hello, World!");
来源：http://dali.yuxming.cn/Article/details/gtahtvooqq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjtdkpqn.html

Java: System.out.println("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gtlgbfsqmh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gzhubu.top/Article/details/gtrwfsaebk.html

Ruby: puts "Hello, World!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnykikqv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jyoumei.cn/Article/details/gtcduvwcpt.html

[A02] 变量声明与赋值
来源：http://dali.sysykeji.top/Article/details/gtsuxapbjx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nanxuanxn.top/Article/details/gtgxbvlyca.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hywenlv.cn/Article/details/gthwwkvrcq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtdizbbohn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ydzc1.top/Article/details/gtfgcoygua.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gtpyrxwsca.html

Go:   name := "Alex"; age := 20
来源：http://dali.pengpengdd.cyou/Article/details/gtwypmaoca.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shangyingyoupin.top/Article/details/gtquifrwyw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.iojbl.cn/Article/details/gtbsjalwgp.html

[A03] 常量定义
来源：http://dali.zhixingplan.top/Article/details/gtfalnoxyy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuxming.cn/Article/details/gtgbgaalzs.html

PHP:  const PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtxgamxcuq.html

JS:   const PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtdavmwgto.html

TS:   const PI: number = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtmjspuuyw.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtsrdvbrni.html

Go:   const PI = 3.14159
来源：http://dali.tanke756.top/Article/details/gtrxozovpg.html

Ruby: PI = 3.14159
来源：http://dali.haohaochexian.top/Article/details/gtbpqodbuf.html

C#:   const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtztwawxuq.html

[A04] 判断变量类型
来源：http://dali.yanxiufei.cn/Article/details/gtpbtkayem.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gtzshruzcm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guowangkeji.top/Article/details/gtsowogjyd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.nwbrower.top/Article/details/gtirigsbrb.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258.top/Article/details/gtedmtfdwi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.vqdsnc.cn/Article/details/gtbvwxooai.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yuanzhike.top/Article/details/gtjgftnrgf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj20258.top/Article/details/gtdmrwdyfa.html

C#:   x.GetType().Name; x is int
来源：http://dali.yanxiufei.cn/Article/details/gtanlfrqgu.html

[A05] 整数除法与取模
来源：http://dali.zhiwuduotai.top/Article/details/gtwxnhfyya.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtauogqwuu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbioavgo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtytemckys.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtbzozucgk.html

Java: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtzbvnbhnd.html

Go:   7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtxydihedx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtdxgjmlol.html

C#:   7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtkjebksqk.html

[A06] 字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtbyqppygy.html

Py:   int("42"); float("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawgwqcal.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cashguo.top/Article/details/gtzyvhivke.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gtantdrigf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nanxinkj.top/Article/details/gtqwvfkvao.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgzoqwxv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.birdmap.top/Article/details/gtqnonknxg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.redwolf501.top/Article/details/gtbiqvofus.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtxswvrcro.html

[A07] 数字转字符串
来源：http://dali.xinyue.icu/Article/details/gtyqnfiwys.html

Py:   str(42)
来源：http://dali.zhongyouzk.top/Article/details/gtxmowsziy.html

PHP:  (string) 42; strval(42)
来源：http://dali.jlsjyb.cn/Article/details/gtrqezuspp.html

JS:   String(42); (42).toString()
来源：http://dali.zhoulong.xyz/Article/details/gttjaxqtsq.html

TS:   String(42)
来源：http://dali.gotoacloud.top/Article/details/gtouydiuws.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.snrcjt.cn/Article/details/gtzszzpvaa.html

Go:   strconv.Itoa(42)
来源：http://dali.zhoulong.xyz/Article/details/gtujjlarkn.html

Ruby: 42.to_s
来源：http://dali.gaohongyu789.top/Article/details/gtqizhwpiz.html

C#:   42.ToString()
来源：http://dali.tianlin.xyz/Article/details/gtoxcyiozb.html

[A08] 取整与四舍五入
来源：http://dali.bjfxy.top/Article/details/gtynrjbmra.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtsyifrqhp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tanke756.top/Article/details/gtrbpxuixx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gteerikebr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xylfe.cn/Article/details/gtcnvdugfy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yj202588.top/Article/details/gtgeqrvmyu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtpavpjahb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenzaomai.com/Article/details/gtiutsskis.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gtqyfbjowr.html

[A09] 绝对值与最大最小值
来源：http://dali.tanke756.top/Article/details/gtqumyrkvi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtsrqpqoyl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtblzumxbc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtmahtmuuw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtqdsauuyn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtcerneqea.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cashguo.top/Article/details/gtzyqbakhf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnqzz.top/Article/details/gtsrntckcv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtkwykhyvz.html

[A10] 生成随机数
来源：http://dali.cashguo.top/Article/details/gtqkttwnva.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cdnleiting.top/Article/details/gtarrnzdxj.html

PHP:  random_int(1, 100);
来源：http://dali.hywenlv.cn/Article/details/gtxddbngjy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.quarkkingdee.top/Article/details/gtkorgbsdt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gotoacloud.top/Article/details/gtnskaqnlf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.tanke756.top/Article/details/gtrvxdqlum.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.wangshuangyany.cn/Article/details/gtbdnlmcal.html

Ruby: rand(1..100)
来源：http://dali.hywenlv.cn/Article/details/gtolkqtndf.html

C#:   new Random().Next(1, 101)
来源：http://dali.yj202588.top/Article/details/gtamsrphhi.html

[A11] 条件表达式（三元）
来源：http://dali.zdqjudy.top/Article/details/gtcubrymar.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.mhx1999.top/Article/details/gtcfspvnsf.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtwhanrrqz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtbdpqfjje.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtxobusqox.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtydknnibl.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.guannengcc.top/Article/details/gtxaymouhm.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gtleintdji.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtcqmvhydp.html

[A12] 字符串插值 / 格式化
来源：http://dali.daxiang520.top/Article/details/gttojdhqvo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.mhx1999.top/Article/details/gtvbbinvhy.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.chenjidiqi.icu/Article/details/gtbfrqtqjf.html

JS:   `Hello, ${name}!`
来源：http://dali.dashuyun.cn/Article/details/gtjishedfl.html

TS:   `Hello, ${name}!`
来源：http://dali.daxiang520.top/Article/details/gtbwurkxqo.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jiagoushi.top/Article/details/gtdqycarni.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shangyingyoupin.top/Article/details/gttybxitfe.html

Ruby: "Hello, #{name}!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktdyfzmc.html

C#:   $"Hello, {name}!"
来源：http://dali.yvedp.cn/Article/details/gtywllrfwr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yongpay.top/Article/details/gtqzeureah.html

Py:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtcxvyneqa.html

PHP:  "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtoxbvyilu.html

JS:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtlwunukit.html

TS:   "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtwazlsbxe.html

Java: "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtnzdablul.html

Go:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtzsuffgpi.html

Ruby: "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtpitjbkje.html

C#:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkrvqffa.html

[A14] 注释写法
来源：http://dali.zhengqikj.top/Article/details/gtsypiewwn.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hysaishi.cn/Article/details/gtcfashvew.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gtnmzyebqa.html

JS:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gtphhysknn.html


<!-- 参考信息 -->