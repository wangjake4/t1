代发 wailian999

[U89] JS：数组去重
来源：http://dali.mhx1999.top/Article/details/gtkdaoojcj.html

[...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtadhnfzgq.html

[U90] JS：数字数组排序
来源：http://dali.shzxlz.cn/Article/details/gtoyteseck.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtbboqfrbz.html

[U91] JS：对象键值遍历
来源：http://dali.zycfv.cn/Article/details/gtiruwqqqt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ehwqpu.com/Article/details/gtbpunvicp.html

[U92] JS：深拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtsuyxagpi.html

structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqbtuinm.html

[U93] JS：模板字符串
来源：http://dali.daxiang520.top/Article/details/gtcwxjfenl.html

`共 ${n} 条`
来源：http://dali.shzxlz.cn/Article/details/gtztklhtyx.html

[U94] JS：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gtkucsnqlg.html

const double = x => x * 2;
来源：http://dali.jqgfzy.top/Article/details/gtzbnpzany.html

[U95] JS：Promise 包装
来源：http://dali.feifeiyinyue.top/Article/details/gtuvfvimdz.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gtckdyoyin.html

[U96] JS：async/await 与异常
来源：http://dali.chenjidiqi.icu/Article/details/gtssgalzrm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtzdtabyjr.html

[U97] JS：并发请求
来源：http://dali.pycfn.com/Article/details/gtuyfdylvp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtsfyezvyp.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenlongwang.top/Article/details/gtzdajueio.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shangyingyoupin.top/Article/details/gtfftymugg.html

[U99] JS：事件监听
来源：http://dali.xziqi.cn/Article/details/gtlyprxklm.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigfzy.top/Article/details/gtqedmmxvj.html

[U100] JS：DOM 查询
来源：http://dali.yj202588.top/Article/details/gtefknhszh.html

document.querySelector(".item")
来源：http://dali.chenjidiqi.icu/Article/details/gtswzhulpx.html

[U101] JS：classList 操作
来源：http://dali.zhoulong.xyz/Article/details/gthwihrcpw.html

el.classList.toggle("active")
来源：http://dali.zycfv.cn/Article/details/gttbrokvew.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gtfflrsxfs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgfzy.top/Article/details/gtjapctptx.html

[U103] JS：定时器
来源：http://dali.hfpthk.cn/Article/details/gtelqydphh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.smart0.xyz/Article/details/gttbgksfla.html

[U104] JS：防抖
来源：http://dali.guowangkeji.top/Article/details/gtwonwapou.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtghfxtcrl.html

[U105] JS：节流
来源：http://dali.havefunace.top/Article/details/gtisvwwaxa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ybcxt.top/Article/details/gtbvbdpvkv.html

[U106] JS：日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtflbjqpwg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jyoumei.cn/Article/details/gtlqnzontw.html

[U107] JS：数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpehnvvjj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pycfn.com/Article/details/gtniezjyaw.html

[U108] JS：随机整数
来源：http://dali.feifeiyinyue.top/Article/details/gtvwykumgi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tanke756.top/Article/details/gttkjwuxhi.html

[U109] JS：数组分组
来源：http://dali.yanxiufei.cn/Article/details/gtxvprwxty.html

Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtxxmvniml.html

[U110] JS：数组分块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndbhfvuz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xziqi.cn/Article/details/gtvaikytgu.html

[U111] JS：对象转 Map
来源：http://dali.vqdsnc.cn/Article/details/gtxkqfubxz.html

new Map(Object.entries(obj))
来源：http://dali.ydzc1.top/Article/details/gtyoaarouq.html

[U112] JS：字符串补位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjefidqd.html

"7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtuemccpva.html

[U113] JS：正则替换全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwdygnlr.html

s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtggwuhcie.html

[U114] JS：JSON 深比较
来源：http://dali.bjfxy.top/Article/details/gtvmobremz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gtbpirktul.html

[U115] JS：生成 UUID
来源：http://dali.birdmap.top/Article/details/gtbxqdfpzj.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtbdjdubec.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgufenzy.top/Article/details/gtqmecyceo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjshmwnpm.html

[U117] JS：单元测试
来源：http://dali.ehwqpu.com/Article/details/gtoydvlvkz.html

npm i -D vitest;  npx vitest
来源：http://dali.hfpthk.cn/Article/details/gtrjhkulcl.html

[U118] JS：开发服务器
来源：http://dali.jianghu66.top/Article/details/gtrzycqkta.html

npm i -D vite;  npx vite
来源：http://dali.yanxiufei.cn/Article/details/gteossxnvq.html

[U119] JS：生产构建
来源：http://dali.dashuyun.cn/Article/details/gtcbzkzwny.html

npx vite build
来源：http://dali.pengpengdd.cyou/Article/details/gtwurvfoua.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.quarkkingdee.top/Article/details/gtzyhuxinf.html

import.meta.env.VITE_API_URL
来源：http://dali.sufxvd.cn/Article/details/gtjywpiknf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtsckxwnbp.html

统计汇总
来源：http://dali.sufxvd.cn/Article/details/gtepypyjbf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrkgkqold.html

按语言统计（条）：
来源：http://dali.gogol.net.cn/Article/details/gtzovxlgan.html

Python ......... 252
来源：http://dali.cdnleiting.top/Article/details/gtffmaujcl.html

PHP ............ 252
来源：http://dali.andypj.xyz/Article/details/gtiiridhgt.html

JavaScript ..... 252
来源：http://dali.yueranfly.top/Article/details/gtvewgwehp.html

TypeScript ..... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtcqmozcma.html

Java ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gtqzedgdhn.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gtdkzoanft.html

Ruby ........... 212
来源：http://dali.daxiang520.top/Article/details/gtktuuruiw.html

C# ............. 212
来源：http://dali.gaohongyu789.top/Article/details/gtetqcymny.html

C .............. 30
来源：http://dali.jqgfzy.top/Article/details/gtipzuzdxi.html

C++ ............ 30
来源：http://dali.wangshuangyany.cn/Article/details/gtqesgasjh.html

SQL ............ 90
来源：http://dali.svipenyu.cn/Article/details/gtbljbkpbt.html

Bash ........... 80
来源：http://dali.zhengqikj.top/Article/details/gtxwwaetdu.html

Kotlin ......... 15
来源：http://dali.snrcjt.cn/Article/details/gtnwcugdyn.html

Swift .......... 15
来源：http://dali.aibaodan.cn/Article/details/gtliivdnel.html

Lua ............ 10
来源：http://dali.guannengcc.top/Article/details/gtmiumidej.html

Perl ........... 10
来源：http://dali.yj20258888.top/Article/details/gtzjxdsefs.html

Scala .......... 10
来源：http://dali.ybcxt.top/Article/details/gtzlgbenxm.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtphgspptm.html

合计 ........... 2106 条
来源：http://dali.chenjidiqi.icu/Article/details/gtcryjhjtu.html

按章节统计：
来源：http://dali.jyoumei.cn/Article/details/gtxjawkjmx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gtrholxygh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtgmztlxvg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtpylkrxjs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ppjwa.cn/Article/details/gttseiimoe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.birdmap.top/Article/details/gtbwokmoys.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gtmtmzakfr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtejyrncka.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyutbogpe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtawzzjgub.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gtaakccmai.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtieifmuiw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtkxmkmptu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtwyttzdze.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gtuzgmeiii.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnuqpclj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtbyvhjkst.html

Q SQL 专题                              90
来源：http://dali.snrcjt.cn/Article/details/gtikdmqzfr.html

R Bash 专题                             80
来源：http://dali.9152youxi.cn/Article/details/gtwdisabhy.html

S C / C++ 专题                          60
来源：http://dali.yuanzhike.top/Article/details/gtuotetxzg.html

T 其他语言补充                          60
来源：http://dali.316326.xyz/Article/details/gtamzduqab.html

U 高频实用片段                         120
来源：http://dali.jqgfzy.top/Article/details/gtmttdrffe.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtqqujtivc.html

合计                                  2106 条
来源：http://dali.meibo888.top/Article/details/gtyoytbjba.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gtcbqemwtr.html

使用提醒
来源：http://dali.fengsongda.top/Article/details/gtcaiizutv.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gttvndawyb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.aibaodan.cn/Article/details/gtospexlxx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.pycfn.com/Article/details/gtpxdmdwan.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.nanxuanxn.top/Article/details/gtolzxqlua.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhoulong.xyz/Article/details/gtxmgjvxyq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xylfe.cn/Article/details/gthdjydpme.html

—— 文件结束 ——
来源：http://dali.sxryk.cn/Article/details/gtzxwzayap.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdmhohfsi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.fengsongda.top/Article/details/gtmqpdfqve.html

Common Programming Examples Cheat Book
来源：http://dali.sweek.top/Article/details/gtmtsshled.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtbohzouhu.html

【收录内容】
来源：http://dali.jyoumei.cn/Article/details/gttlrwsswf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hysaishi.cn/Article/details/gtanxrtddl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yanxiufei.cn/Article/details/gtyeqbihsf.html

SQL · Bash · C · C++
来源：http://dali.jqgfzy.top/Article/details/gtwmkbepgi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hysaishi.cn/Article/details/gtrflghuzr.html

【使用说明】
来源：http://dali.cheryme.top/Article/details/gtlldtqbzk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.meibo888.top/Article/details/gtuajomcjh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hnqzz.top/Article/details/gtilpbervo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cucudq.cn/Article/details/gtabmoubxa.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ydzc1.top/Article/details/gtbwgtifde.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.wangdashe.top/Article/details/gttcffqkmr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenjidiqi.icu/Article/details/gtvbwfelyo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnqzz.top/Article/details/gtldbngnrx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yonumen.top/Article/details/gttqusggxu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gzhubu.top/Article/details/gtomxgrkdz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinqigufen.top/Article/details/gtcgeurqbj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnqzz.top/Article/details/gtgopzsiqa.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yuanzhike.top/Article/details/gtygfvgfik.html

【文件统计】
来源：http://dali.yongpay.top/Article/details/gtunmegofw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cucudq.cn/Article/details/gteulzjupq.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqzkwnki.html

目  录
来源：http://dali.cashguo.top/Article/details/gtqoadhdmc.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gttaxhcigv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxinkj.top/Article/details/gttvrmfygo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtaqswfjod.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gthflccptm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gaohongyu789.top/Article/details/gtjcxwjiwa.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxuanxn.top/Article/details/gtketmpbtt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jlsjyb.cn/Article/details/gtigxuveia.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gteatbfamy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hfpthk.cn/Article/details/gtizhdzdaq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gteyiuovmv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cqqwz.cn/Article/details/gtnvwmxiyv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtezubfohq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtaxhhskqw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtzgqmkyco.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gtggcrvyax.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xylfe.cn/Article/details/gtlgrideff.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtsmfduesb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuanzhike.top/Article/details/gtkgtnvtqv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhixingplan.top/Article/details/gtzkrremiv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jiagoushi.top/Article/details/gtpvwfmjde.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtpzovevha.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gtwbavvhnt.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtevnvbbrg.html

A. 基础语法与类型
来源：http://dali.9152youxi.cn/Article/details/gtjgczslok.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdjvkcjnq.html

[A01] Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtwyhyggpq.html

Py:   print("Hello, World!")
来源：http://dali.sweek.top/Article/details/gttxkxldus.html

PHP:  echo "Hello, World!";
来源：http://dali.hammf.cn/Article/details/gtonxlwqnp.html

JS:   console.log("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gthztlmghg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepjexter.html

Java: System.out.println("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gtoifqlnsd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gtjznisqoh.html

Ruby: puts "Hello, World!"
来源：http://dali.havefunace.top/Article/details/gtfsfoaqmy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gtaiztxxsm.html

[A02] 变量声明与赋值
来源：http://dali.jlsjyb.cn/Article/details/gtzdeemmyn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gaohongyu789.top/Article/details/gtvuayjutm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sysykeji.top/Article/details/gthwkjcgqc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtfgeetkmh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jianghu66.top/Article/details/gtgoolhpek.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtxpeykscw.html

Go:   name := "Alex"; age := 20
来源：http://dali.shangyingyoupin.top/Article/details/gtelhrwnaw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinqigufen.top/Article/details/gtkwfrwret.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.dashuyun.cn/Article/details/gttqmatfkn.html

[A03] 常量定义
来源：http://dali.daxiang520.top/Article/details/gtevttxhzl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.iojbl.cn/Article/details/gtieghrkka.html

PHP:  const PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtiphjztod.html

JS:   const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtedsmcfjv.html

TS:   const PI: number = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtamxtstnu.html

Java: static final double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtueiiqkof.html

Go:   const PI = 3.14159
来源：http://dali.tanke756.top/Article/details/gtsfpodqhr.html

Ruby: PI = 3.14159
来源：http://dali.hammf.cn/Article/details/gtkqflbaqo.html

C#:   const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtyhjdbcdo.html

[A04] 判断变量类型
来源：http://dali.shuidangran.top/Article/details/gtwgtnmfde.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ivvv.top/Article/details/gtdfsrcwgs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxuanxn.top/Article/details/gtwdboooky.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.9152youxi.cn/Article/details/gtushgxsek.html

TS:   typeof x; x instanceof Date
来源：http://dali.jiagoushi.top/Article/details/gtxdojdvek.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj20258888.top/Article/details/gtriqqeree.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shuidangran.top/Article/details/gtnqjmgwol.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cashguo.top/Article/details/gtmupgtgvt.html

C#:   x.GetType().Name; x is int
来源：http://dali.xziqi.cn/Article/details/gtkofrldet.html

[A05] 整数除法与取模
来源：http://dali.hnxiangtu.top/Article/details/gtwapthabp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.vqdsnc.cn/Article/details/gtwconlnzt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtdgicykan.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtnxkigpwi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtubziywgi.html

Java: 7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gtywcjcxap.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtnpwpnnat.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwfwzhch.html

C#:   7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtamtwbqrj.html

[A06] 字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyepjtxnb.html

Py:   int("42"); float("3.14")
来源：http://dali.yj20258888.top/Article/details/gtgjfusthd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.smart0.xyz/Article/details/gtxnbylmrk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinqigufen.top/Article/details/gtobdbubtl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.pycfn.com/Article/details/gtckntnccx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gtfvzvszxt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtdqrdwepx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinghuilouyu.cn/Article/details/gtdktzjmjz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nwbrower.top/Article/details/gtfrywgmxq.html

[A07] 数字转字符串
来源：http://dali.hywenlv.cn/Article/details/gtdgdtnxuo.html

Py:   str(42)
来源：http://dali.jyoumei.cn/Article/details/gtffpyegyn.html

PHP:  (string) 42; strval(42)
来源：http://dali.daxiang520.top/Article/details/gthdtqnomu.html

JS:   String(42); (42).toString()
来源：http://dali.0kj1m.cn/Article/details/gtlzaqkyil.html

TS:   String(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtkmohjhvg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yanxiufei.cn/Article/details/gtrbvhoaur.html

Go:   strconv.Itoa(42)
来源：http://dali.kuanghao11.cn/Article/details/gtpnftrgbm.html

Ruby: 42.to_s
来源：http://dali.yj202588.top/Article/details/gtfsupayjn.html

C#:   42.ToString()
来源：http://dali.haohaochexian.top/Article/details/gtthjdyfub.html

[A08] 取整与四舍五入
来源：http://dali.jqgfzy.top/Article/details/gtkbbmpjrm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gtweipazpz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nanxinkj.top/Article/details/gtlicthbbn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtazkfmghe.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cashguo.top/Article/details/gtbjhjakcf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gtasaspbjj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtqgqvvptq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nanxinkj.top/Article/details/gtwuubhvhg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gthqwtosta.html

[A09] 绝对值与最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gtptemxeit.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtuakqesqr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yongpay.top/Article/details/gtntkesgst.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtdzfnpbpx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hammf.cn/Article/details/gtvkmmjmjk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cashguo.top/Article/details/gtpkgjtfdq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.bjfxy.top/Article/details/gtyhtkeobv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gotoacloud.top/Article/details/gtqihxqseb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtvadrkzak.html

[A10] 生成随机数
来源：http://dali.hammf.cn/Article/details/gtkycsflae.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgfzy.top/Article/details/gthlmedfnr.html

PHP:  random_int(1, 100);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwakhmbj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fengsongda.top/Article/details/gtfebmdvkn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sysykeji.top/Article/details/gttwzdeoeh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.andypj.xyz/Article/details/gteijnzwmt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yvedp.cn/Article/details/gtxzdhfzcl.html

Ruby: rand(1..100)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzadljhb.html

C#:   new Random().Next(1, 101)
来源：http://dali.cheryme.top/Article/details/gtcymfrvvl.html

[A11] 条件表达式（三元）
来源：http://dali.iojbl.cn/Article/details/gtaiezptfq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.havefunace.top/Article/details/gtahsibtmo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtchzhcewj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtstmckwwj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyqwkvzu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gtqjcvhxso.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yonumen.top/Article/details/gtwiuwpkej.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gtlbqupqnj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gtiglqbkin.html

[A12] 字符串插值 / 格式化
来源：http://dali.xziqi.cn/Article/details/gtwlezxskq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.guannengcc.top/Article/details/gtrpkljjmm.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.meibo888.top/Article/details/gtudbhhpdw.html

JS:   `Hello, ${name}!`
来源：http://dali.wangshuangyany.cn/Article/details/gtxspzmnil.html

TS:   `Hello, ${name}!`
来源：http://dali.jqgufenzy.top/Article/details/gtenhdvhih.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xylfe.cn/Article/details/gtmabnvswv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.guowangkeji.top/Article/details/gtspnccvkd.html

Ruby: "Hello, #{name}!"
来源：http://dali.fzhhl.top/Article/details/gtooinnzko.html

C#:   $"Hello, {name}!"
来源：http://dali.hysaishi.cn/Article/details/gtwnsysagh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jqgfzy.top/Article/details/gtkzutndff.html

Py:   "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtvqsdlrkx.html

PHP:  "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtwtltxqrg.html

JS:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtunugibam.html

TS:   "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtukpryuhy.html

Java: "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtbxhoaptd.html

Go:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtmbhaqwab.html

Ruby: "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtrrwrgrkq.html

C#:   "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gterczklls.html

[A14] 注释写法
来源：http://dali.haohaochexian.top/Article/details/gtreqlbmrh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhengqikj.top/Article/details/gtissfmbqe.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gtpgteqwkn.html

JS:   // 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gtfzubzycx.html

TS:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gtaiwisdjk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sufxvd.cn/Article/details/gtlqccfyxg.html

Go:   // 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gtirmzugnf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yuanzhike.top/Article/details/gtsxtvzaqd.html

C#:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gtlcotwhpk.html

[A15] 空值判断与默认值
来源：http://dali.yuanzhike.top/Article/details/gtrfwrolls.html

Py:   value = data or "默认值"
来源：http://dali.andypj.xyz/Article/details/gtkjceanxi.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqptaify.html


<!-- 参考信息 -->