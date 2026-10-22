代发 wailian999

[U87] JS：解构默认值
来源：http://dali.guowangkeji.top/Article/details/gtudnziigs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenjidiqi.icu/Article/details/gtllmrwlmh.html

[U88] JS：对象展开合并
来源：http://dali.zdqjudy.top/Article/details/gtrdgzgdsn.html

{ ...a, ...b }
来源：http://dali.zhoulong.xyz/Article/details/gtlzsterli.html

[U89] JS：数组去重
来源：http://dali.yj202588.top/Article/details/gtadbposao.html

[...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtmzfeumzr.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorqxewpe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtvmtxyhob.html

[U91] JS：对象键值遍历
来源：http://dali.zdqjudy.top/Article/details/gtpcypqier.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinqigufen.top/Article/details/gtgcqawkgc.html

[U92] JS：深拷贝
来源：http://dali.redwolf501.top/Article/details/gtsrauscpg.html

structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtzrmnlati.html

[U93] JS：模板字符串
来源：http://dali.hywenlv.cn/Article/details/gtfpbvhtbd.html

`共 ${n} 条`
来源：http://dali.svipenyu.cn/Article/details/gtwhqffdek.html

[U94] JS：箭头函数
来源：http://dali.cheryme.top/Article/details/gtvskluveu.html

const double = x => x * 2;
来源：http://dali.iojbl.cn/Article/details/gtqbuuofbh.html

[U95] JS：Promise 包装
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvuudcyo.html

new Promise((resolve, reject) => {})
来源：http://dali.pengpengdd.cyou/Article/details/gtczlrrilf.html

[U96] JS：async/await 与异常
来源：http://dali.yj202588.top/Article/details/gtxncklqey.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gttuxjbplq.html

[U97] JS：并发请求
来源：http://dali.jqgfzy.top/Article/details/gtlpoolvnt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtmbhpqttm.html

[U98] JS：fetch 带 JSON
来源：http://dali.daxiang520.top/Article/details/gteddotjqn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hammf.cn/Article/details/gtvzfpeqqj.html

[U99] JS：事件监听
来源：http://dali.shzxlz.cn/Article/details/gthjntcjlv.html

el.addEventListener("click", e => {})
来源：http://dali.chenjidiqi.icu/Article/details/gtkhukmdcz.html

[U100] JS：DOM 查询
来源：http://dali.yongpay.top/Article/details/gtdsaucvbt.html

document.querySelector(".item")
来源：http://dali.andypj.xyz/Article/details/gterjsxefv.html

[U101] JS：classList 操作
来源：http://dali.aibaodan.cn/Article/details/gtwksloxwj.html

el.classList.toggle("active")
来源：http://dali.gzhubu.top/Article/details/gtlqlxlads.html

[U102] JS：本地存储
来源：http://dali.ydzc1.top/Article/details/gtneayvvvi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hfpthk.cn/Article/details/gtnjlnndao.html

[U103] JS：定时器
来源：http://dali.gaohongyu789.top/Article/details/gtofvkcufi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sxryk.cn/Article/details/gtujwziikj.html

[U104] JS：防抖
来源：http://dali.redwolf501.top/Article/details/gtulxayyul.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtsjtmfgqf.html

[U105] JS：节流
来源：http://dali.hongshengwenyu.top/Article/details/gtashcmaxs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hfpthk.cn/Article/details/gteiunbzlk.html

[U106] JS：日期格式化
来源：http://dali.c1oappe.top/Article/details/gtluzctcgp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.iojbl.cn/Article/details/gtxnabphli.html

[U107] JS：数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gtdflshkhd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gttpwmjkmq.html

[U108] JS：随机整数
来源：http://dali.hongshengwenyu.top/Article/details/gtekailuvz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yvedp.cn/Article/details/gtrlccasjn.html

[U109] JS：数组分组
来源：http://dali.daria6918.cn/Article/details/gttxgwadhr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gtakgvlvse.html

[U110] JS：数组分块
来源：http://dali.bjfxy.top/Article/details/gtynfymogp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yonumen.top/Article/details/gtkehoypmf.html

[U111] JS：对象转 Map
来源：http://dali.shzxlz.cn/Article/details/gthacnorcg.html

new Map(Object.entries(obj))
来源：http://dali.sysykeji.top/Article/details/gtgyfvywyr.html

[U112] JS：字符串补位
来源：http://dali.shzxlz.cn/Article/details/gtyrbxxkrb.html

"7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtnqvcdiqs.html

[U113] JS：正则替换全部
来源：http://dali.hysaishi.cn/Article/details/gtqppzxgft.html

s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtbkhwreml.html

[U114] JS：JSON 深比较
来源：http://dali.cqqwz.cn/Article/details/gtqudmzhlm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gtyhmnpria.html

[U115] JS：生成 UUID
来源：http://dali.sweek.top/Article/details/gtmbjcusob.html

crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtocjoumqt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhoulong.xyz/Article/details/gtgpduhkiu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guannengcc.top/Article/details/gtirfqymuf.html

[U117] JS：单元测试
来源：http://dali.chenzaomai.com/Article/details/gtxctcqwgf.html

npm i -D vitest;  npx vitest
来源：http://dali.cheryme.top/Article/details/gtyaskiozj.html

[U118] JS：开发服务器
来源：http://dali.pengpengdd.cyou/Article/details/gtevxvzxhp.html

npm i -D vite;  npx vite
来源：http://dali.pengpengdd.cyou/Article/details/gtzoutaixv.html

[U119] JS：生产构建
来源：http://dali.daria6918.cn/Article/details/gtxmwupnac.html

npx vite build
来源：http://dali.jlsjyb.cn/Article/details/gtuyzszfqo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gtzqmaqpfd.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxuanxn.top/Article/details/gtwmdmlrql.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtangskpxy.html

统计汇总
来源：http://dali.smart0.xyz/Article/details/gtkzllgxjn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtscjrhevu.html

按语言统计（条）：
来源：http://dali.sweek.top/Article/details/gtygoujdlh.html

Python ......... 252
来源：http://dali.cdnleiting.top/Article/details/gtbijdtjph.html

PHP ............ 252
来源：http://dali.yj20258888.top/Article/details/gtubfqmzds.html

JavaScript ..... 252
来源：http://dali.dashuyun.cn/Article/details/gtvssljwie.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gtggcrcrjm.html

Java ........... 212
来源：http://dali.chenzaomai.com/Article/details/gttxjuobsr.html

Go ............. 212
来源：http://dali.yvedp.cn/Article/details/gtavdpxjth.html

Ruby ........... 212
来源：http://dali.jqgufenzy.top/Article/details/gtqvnnmvli.html

C# ............. 212
来源：http://dali.c1oappe.top/Article/details/gtajwervcx.html

C .............. 30
来源：http://dali.wangshuangyany.cn/Article/details/gtauejrmlf.html

C++ ............ 30
来源：http://dali.ydzc1.top/Article/details/gtqvkgslfl.html

SQL ............ 90
来源：http://dali.svipenyu.cn/Article/details/gtukbzannn.html

Bash ........... 80
来源：http://dali.jiagoushi.top/Article/details/gtsjxolnxn.html

Kotlin ......... 15
来源：http://dali.jianghu66.top/Article/details/gtpbwohnja.html

Swift .......... 15
来源：http://dali.yangfankeji.com/Article/details/gtwnztzidk.html

Lua ............ 10
来源：http://dali.yj20258888.top/Article/details/gtylqlpbde.html

Perl ........... 10
来源：http://dali.ppjwa.cn/Article/details/gtbsbkqyxp.html

Scala .......... 10
来源：http://dali.gotoacloud.top/Article/details/gtnztknict.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtlqttzbyr.html

合计 ........... 2106 条
来源：http://dali.hnxiangtu.top/Article/details/gtjddkdbfy.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtjwjzsmxy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.fzhhl.top/Article/details/gtnkikzyca.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtadhgjbxe.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gtaemqiwlx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hywenlv.cn/Article/details/gtbipbkpwm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hongshengwenyu.top/Article/details/gtmfogndwb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gtzwqmwrru.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkiqadsc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gtoylzkyit.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtrnudrjgd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gtwulwtrrl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtjtjjkdsw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtkummfyat.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtiustqpov.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gtsobirxzm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinqigufen.top/Article/details/gtmwprvbro.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtxdxmfmey.html

Q SQL 专题                              90
来源：http://dali.zhoulong.xyz/Article/details/gtswfwvptq.html

R Bash 专题                             80
来源：http://dali.havefunace.top/Article/details/gtkpqrhdjf.html

S C / C++ 专题                          60
来源：http://dali.fzhhl.top/Article/details/gtxcwugbqg.html

T 其他语言补充                          60
来源：http://dali.sweek.top/Article/details/gtuitklhhs.html

U 高频实用片段                         120
来源：http://dali.ydzc1.top/Article/details/gtegmudzzt.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gtqdaerszk.html

合计                                  2106 条
来源：http://dali.jiagoushi.top/Article/details/gtfbmuufez.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtjxlkgufp.html

使用提醒
来源：http://dali.gaohongyu789.top/Article/details/gtuwnwtukg.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtpecmqild.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.meibo888.top/Article/details/gtwsgjpnch.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.wangshuangyany.cn/Article/details/gtsptrnecj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jyoumei.cn/Article/details/gtbbwnbhzb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.guannengcc.top/Article/details/gtwmzdyubb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shzxlz.cn/Article/details/gtzdnwhqhm.html

—— 文件结束 ——
来源：http://dali.shzxlz.cn/Article/details/gtgmsamiuy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtosvsisfy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenjidiqi.icu/Article/details/gtuuicthrv.html

Common Programming Examples Cheat Book
来源：http://dali.ivvv.top/Article/details/gtwmjrhevb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgzxrvuei.html

【收录内容】
来源：http://dali.xziqi.cn/Article/details/gtwaxbvash.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhoulong.xyz/Article/details/gtecokfchx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xylfe.cn/Article/details/gtyzjbgmhy.html

SQL · Bash · C · C++
来源：http://dali.jqgfzy.top/Article/details/gtomsdshln.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cucudq.cn/Article/details/gtieuefrbf.html

【使用说明】
来源：http://dali.redwolf501.top/Article/details/gtbnifdmyg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sweek.top/Article/details/gtsiqezrre.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jiagoushi.top/Article/details/gtdwypsklv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.316326.xyz/Article/details/gtelagndqt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.wangdashe.top/Article/details/gtksiykqbb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xylfe.cn/Article/details/gtvpfcenii.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gogol.net.cn/Article/details/gttgthtvoi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.fengsongda.top/Article/details/gtyzansufu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jiagoushi.top/Article/details/gtfeutiqdf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmkikmlv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.fengsongda.top/Article/details/gthcmldvyn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hongshengwenyu.top/Article/details/gtautcdfuk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.birdmap.top/Article/details/gtzeffdjag.html

【文件统计】
来源：http://dali.hnxiangtu.top/Article/details/gtpcrgyaoc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.daxiang520.top/Article/details/gtnviohnxc.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtcqjlnumf.html

目  录
来源：http://dali.pengpengdd.cyou/Article/details/gttryxcvgp.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtamptjgvg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hnxiangtu.top/Article/details/gtfkjyxhsz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtbghxffsl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gtqiqdxxec.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtxgduyxyc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gotoacloud.top/Article/details/gtkvshsgzz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gtffymrowt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gtxzhrnqoe.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtswhjzfmh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtnyveuxfq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtqnyavsee.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtgulwiyrj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtbmdhnnvm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtimgsqdua.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gtamjchjzt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sxryk.cn/Article/details/gtmroqsmwc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtkiqsqhru.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtipcrgdto.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.havefunace.top/Article/details/gtpxuiiosq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj202588.top/Article/details/gtkruqadvt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtaogdxfvc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtdodvfafd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtohsyyzhh.html

A. 基础语法与类型
来源：http://dali.redwolf501.top/Article/details/gtcdhnapwy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrfdsximv.html

[A01] Hello World
来源：http://dali.nanxinkj.top/Article/details/gtqfqxljlb.html

Py:   print("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gtpmhkyhgp.html

PHP:  echo "Hello, World!";
来源：http://dali.snrcjt.cn/Article/details/gtqofhzdde.html

JS:   console.log("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gthymutjng.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.316326.xyz/Article/details/gtsyiqrakd.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtgicweg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jqgufenzy.top/Article/details/gtahvwoqsz.html

Ruby: puts "Hello, World!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrafiqade.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gttjqttkvs.html

[A02] 变量声明与赋值
来源：http://dali.hammf.cn/Article/details/gtcdpyelgu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsstpzsjd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtozsdlhjh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtbpkjxjwn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.redwolf501.top/Article/details/gtdcrcwqyu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cheryme.top/Article/details/gtvpboqgfs.html

Go:   name := "Alex"; age := 20
来源：http://dali.jlsjyb.cn/Article/details/gtvvzmebvy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.daria6918.cn/Article/details/gtjyunvqbi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yonumen.top/Article/details/gtxuadxhfc.html

[A03] 常量定义
来源：http://dali.ppjwa.cn/Article/details/gtpmpawnco.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.kuanghao11.cn/Article/details/gtbchittnj.html

PHP:  const PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtqhppswsq.html

JS:   const PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtytfdpqjl.html

TS:   const PI: number = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtcotppwte.html

Java: static final double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtscvwxgms.html

Go:   const PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gtdiaqwzgm.html

Ruby: PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gtsaddqyyh.html

C#:   const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gthmtxxakj.html

[A04] 判断变量类型
来源：http://dali.c1oappe.top/Article/details/gtuocbhkld.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cdnleiting.top/Article/details/gtmorxyqmw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jqgufenzy.top/Article/details/gtchyraytv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhoulong.xyz/Article/details/gtlzspgokj.html

TS:   typeof x; x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gtvtsfuqjj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ppjwa.cn/Article/details/gttytfxsty.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nanxinkj.top/Article/details/gtjarmzdjd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.redwolf501.top/Article/details/gtsoryhxar.html

C#:   x.GetType().Name; x is int
来源：http://dali.sxryk.cn/Article/details/gtnhraidnf.html

[A05] 整数除法与取模
来源：http://dali.gogol.net.cn/Article/details/gtliwxcdct.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cdnleiting.top/Article/details/gtohwyzjjl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtndrhlxyk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtcwbrlftv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.redwolf501.top/Article/details/gthlitnqos.html

Java: 7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtstposasb.html

Go:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtcrgqnaby.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkcvqeuw.html

C#:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtybjgdwwf.html

[A06] 字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtypvshbpr.html

Py:   int("42"); float("3.14")
来源：http://dali.yonumen.top/Article/details/gtmwuitxxe.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.meibo888.top/Article/details/gtpqkgiwfk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gtptrwkssj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hywenlv.cn/Article/details/gttzkqsyky.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yueranfly.top/Article/details/gthruixkjz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.dashuyun.cn/Article/details/gtegmsixhu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hysaishi.cn/Article/details/gteotworym.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenlongwang.top/Article/details/gtwlzxqcha.html

[A07] 数字转字符串
来源：http://dali.gotoacloud.top/Article/details/gtdwmicyvg.html

Py:   str(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtsfwlodbc.html

PHP:  (string) 42; strval(42)
来源：http://dali.ppjwa.cn/Article/details/gtwnnkkacn.html

JS:   String(42); (42).toString()
来源：http://dali.shzxlz.cn/Article/details/gtcufmldom.html

TS:   String(42)
来源：http://dali.hammf.cn/Article/details/gtndqzpknr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cqqwz.cn/Article/details/gtkawwngir.html

Go:   strconv.Itoa(42)
来源：http://dali.yangfankeji.com/Article/details/gtrugdpczl.html

Ruby: 42.to_s
来源：http://dali.zhixingplan.top/Article/details/gtedtxtyal.html

C#:   42.ToString()
来源：http://dali.hfpthk.cn/Article/details/gtiuoyhflu.html

[A08] 取整与四舍五入
来源：http://dali.sufxvd.cn/Article/details/gtupjlbsmo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtrvnjetgv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.meibo888.top/Article/details/gtyaehssdc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtexmnybeh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.nanxuanxn.top/Article/details/gtnqaqatma.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtbtjlwuyf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gtrtnrkqfh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.aibaodan.cn/Article/details/gtthqknlqu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtwnexsleu.html

[A09] 绝对值与最大最小值
来源：http://dali.guannengcc.top/Article/details/gtjcrrjgtc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.316326.xyz/Article/details/gtctjcyhxq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtrgfdcbvt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtvqfdoqso.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtokixqkir.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtikfbtbvv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.chenzaomai.com/Article/details/gtpvrxjenh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sweek.top/Article/details/gtegczhknb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtaufbfmfw.html

[A10] 生成随机数
来源：http://dali.wangdashe.top/Article/details/gtkddtbfoh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.mhx1999.top/Article/details/gtkhjhruwp.html

PHP:  random_int(1, 100);
来源：http://dali.andypj.xyz/Article/details/gtxaulrrwy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hammf.cn/Article/details/gthltmszie.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gtllcmpvtg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.svipenyu.cn/Article/details/gtxljhggwi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.daria6918.cn/Article/details/gttxaozvlz.html

Ruby: rand(1..100)
来源：http://dali.gzhubu.top/Article/details/gtyrnxmgah.html

C#:   new Random().Next(1, 101)
来源：http://dali.feifeiyinyue.top/Article/details/gtuxhcyxas.html

[A11] 条件表达式（三元）
来源：http://dali.haohaochexian.top/Article/details/gtuzqptsry.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.fzhhl.top/Article/details/gteeoicpwb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gticivmyzk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gtzmgdfaau.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohbmbfkk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtanfbwbmi.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.chenjidiqi.icu/Article/details/gtozmkzrzo.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gtyxxexlyo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwlggqnd.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinqigufen.top/Article/details/gtevfllrdb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gotoacloud.top/Article/details/gtxrtkbrkz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.daxiang520.top/Article/details/gtzhbtwcvh.html

JS:   `Hello, ${name}!`
来源：http://dali.jqgufenzy.top/Article/details/gtgfzucqik.html

TS:   `Hello, ${name}!`
来源：http://dali.yongpay.top/Article/details/gtwtkithdb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyahtsbtw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhoulong.xyz/Article/details/gtnpfzmfpw.html

Ruby: "Hello, #{name}!"
来源：http://dali.pengpengdd.cyou/Article/details/gtyqvpprou.html

C#:   $"Hello, {name}!"
来源：http://dali.yuanzhike.top/Article/details/gturefzvty.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cqqwz.cn/Article/details/gtmznoymoo.html

Py:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtruehymzw.html

PHP:  "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtkycorjfj.html

JS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtnctejejf.html

TS:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtxllcogro.html

Java: "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtrfxiftkf.html

Go:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gthkmtyfnf.html

Ruby: "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtpjgrsenf.html

C#:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtwpxrwrfd.html

[A14] 注释写法
来源：http://dali.yuxming.cn/Article/details/gtvbiotqae.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.pycfn.com/Article/details/gtyqepxeqn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.fzhhl.top/Article/details/gtcsacniyj.html

JS:   // 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gtcmxzgvtu.html

TS:   // 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gtgrvwoukr.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yj202588.top/Article/details/gtcaqxvehn.html

Go:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gtkezuheuj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.mhx1999.top/Article/details/gtrnbftcmo.html


<!-- 参考信息 -->