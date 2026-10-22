代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.haohaochexian.top/Article/details/gt2zwnfpkbz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.daria6918.cn/Article/details/gt2dllhoyta.html

[U92] JS：深拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2ofupsfcq.html

structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jouwvnta.html

[U93] JS：模板字符串
来源：http://dali.yj20258888.top/Article/details/gt2souxkmth.html

`共 ${n} 条`
来源：http://dali.sxryk.cn/Article/details/gt2lsvfdkrs.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnzoypzi.html

const double = x => x * 2;
来源：http://dali.snrcjt.cn/Article/details/gt2rvriffhu.html

[U95] JS：Promise 包装
来源：http://dali.chenlongwang.top/Article/details/gt2drmeeqmv.html

new Promise((resolve, reject) => {})
来源：http://dali.jiagoushi.top/Article/details/gt2eudsjlon.html

[U96] JS：async/await 与异常
来源：http://dali.mhx1999.top/Article/details/gt2dgibhzjm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqudyjsp.html

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2firknhke.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2ekwgrcvx.html

[U98] JS：fetch 带 JSON
来源：http://dali.nwbrower.top/Article/details/gt2gstojnyo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.svipenyu.cn/Article/details/gt2dxygjtrf.html

[U99] JS：事件监听
来源：http://dali.chenzaomai.com/Article/details/gt2wlzrxohl.html

el.addEventListener("click", e => {})
来源：http://dali.cucudq.cn/Article/details/gt2mdxfwjss.html

[U100] JS：DOM 查询
来源：http://dali.hysaishi.cn/Article/details/gt2dwjmftvn.html

document.querySelector(".item")
来源：http://dali.hnqzz.top/Article/details/gt2umrtmivj.html

[U101] JS：classList 操作
来源：http://dali.zhixingplan.top/Article/details/gt2utrjgvga.html

el.classList.toggle("active")
来源：http://dali.haohaochexian.top/Article/details/gt2dhyelakd.html

[U102] JS：本地存储
来源：http://dali.yj202588.top/Article/details/gt2naqszjen.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.svipenyu.cn/Article/details/gt2mraoqjvg.html

[U103] JS：定时器
来源：http://dali.ehwqpu.com/Article/details/gt2isedjfkm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cucudq.cn/Article/details/gt2okeqifkn.html

[U104] JS：防抖
来源：http://dali.yuxming.cn/Article/details/gt2zotlncxs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2nuyyyabz.html

[U105] JS：节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eyudkugs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhoulong.xyz/Article/details/gt2hhugobtu.html

[U106] JS：日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gt2obyqujdj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yueranfly.top/Article/details/gt2cdqinqzi.html

[U107] JS：数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gt2kreithgc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gt2yngmwvck.html

[U108] JS：随机整数
来源：http://dali.yj202588.top/Article/details/gt2wbdvdrut.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.pycfn.com/Article/details/gt2cihyduut.html

[U109] JS：数组分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdqucdsc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gt2mewtuaff.html

[U110] JS：数组分块
来源：http://dali.sysykeji.top/Article/details/gt2awypwyhv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pengpengdd.cyou/Article/details/gt2nrvigbat.html

[U111] JS：对象转 Map
来源：http://dali.cucudq.cn/Article/details/gt2xkazvmmv.html

new Map(Object.entries(obj))
来源：http://dali.sxryk.cn/Article/details/gt2lvsnuvrv.html

[U112] JS：字符串补位
来源：http://dali.hnxiangtu.top/Article/details/gt2ukrjgain.html

"7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2apmmmmry.html

[U113] JS：正则替换全部
来源：http://dali.yanxiufei.cn/Article/details/gt2lwieamao.html

s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2bgvokasv.html

[U114] JS：JSON 深比较
来源：http://dali.yangfankeji.com/Article/details/gt2taegakgx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gt2rpkmxjgz.html

[U115] JS：生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gt2bqocoixt.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gsdgkwxz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shzxlz.cn/Article/details/gt2nfiqyowp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gt2tvljayvo.html

[U117] JS：单元测试
来源：http://dali.tianlin.xyz/Article/details/gt2rapnjsmu.html

npm i -D vitest;  npx vitest
来源：http://dali.yj20258888.top/Article/details/gt2wifxlaqj.html

[U118] JS：开发服务器
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgcqhogi.html

npm i -D vite;  npx vite
来源：http://dali.cqqwz.cn/Article/details/gt2ouxxjnbn.html

[U119] JS：生产构建
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvalyhry.html

npx vite build
来源：http://dali.jqgfzy.top/Article/details/gt2vpiprcxr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.andypj.xyz/Article/details/gt2adiqdvtg.html

import.meta.env.VITE_API_URL
来源：http://dali.tian-w.cn/Article/details/gt2ojezmnij.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2buppppbd.html

统计汇总
来源：http://dali.redwolf501.top/Article/details/gt2ebaasnhg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2bcwqbyxv.html

按语言统计（条）：
来源：http://dali.ivvv.top/Article/details/gt2accxhtxp.html

Python ......... 252
来源：http://dali.sweek.top/Article/details/gt2wvnsgkod.html

PHP ............ 252
来源：http://dali.yueranfly.top/Article/details/gt2jizkqarz.html

JavaScript ..... 252
来源：http://dali.zhongyouzk.top/Article/details/gt2eawnpeiz.html

TypeScript ..... 212
来源：http://dali.9152youxi.cn/Article/details/gt2cbaeehhx.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gt2motumvyp.html

Go ............. 212
来源：http://dali.fzhhl.top/Article/details/gt2qzpmwxbg.html

Ruby ........... 212
来源：http://dali.andypj.xyz/Article/details/gt2gbkfgqdt.html

C# ............. 212
来源：http://dali.mhx1999.top/Article/details/gt2mzcggfye.html

C .............. 30
来源：http://dali.aizwys.cn/Article/details/gt2ktdyicvy.html

C++ ............ 30
来源：http://dali.cashguo.top/Article/details/gt2vdenqega.html

SQL ............ 90
来源：http://dali.dashuyun.cn/Article/details/gt2zuuylhfy.html

Bash ........... 80
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzewglcz.html

Kotlin ......... 15
来源：http://dali.yuanzhike.top/Article/details/gt2qlmskujm.html

Swift .......... 15
来源：http://dali.sufxvd.cn/Article/details/gt2dyvkbyes.html

Lua ............ 10
来源：http://dali.bjfxy.top/Article/details/gt2dclwsvgr.html

Perl ........... 10
来源：http://dali.ydzc1.top/Article/details/gt2shmyzfsz.html

Scala .......... 10
来源：http://dali.dianchejie.cn/Article/details/gt2nfynqawp.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2ijodftcx.html

合计 ........... 2106 条
来源：http://dali.tianlin.xyz/Article/details/gt2rfsfvyvb.html

按章节统计：
来源：http://dali.chenjidiqi.icu/Article/details/gt2llpoojgc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gt2latvrsjh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gt2xcxgmlzx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gt2zxncigct.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gt2fxikmpiv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cashguo.top/Article/details/gt2uzquelza.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gt2bktqtlld.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gt2cfevhkrr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gt2vumwgjhd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2huwcqnnj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gt2esstghbk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2cceshled.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gt2jzunuhkp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gt2mloicfhw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gt2xihuwail.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ivvv.top/Article/details/gt2leofopij.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2ctwpekue.html

Q SQL 专题                              90
来源：http://dali.yueranfly.top/Article/details/gt2jeglsldd.html

R Bash 专题                             80
来源：http://dali.jiagoushi.top/Article/details/gt2navyujzw.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtajojzg.html

T 其他语言补充                          60
来源：http://dali.hnxiangtu.top/Article/details/gt2buvmybpj.html

U 高频实用片段                         120
来源：http://dali.zhoulong.xyz/Article/details/gt2rsqwnpxy.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gt2zxfflerx.html

合计                                  2106 条
来源：http://dali.xinyue.icu/Article/details/gt2tmdwoaus.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gt2lskmhvxn.html

使用提醒
来源：http://dali.kuanghao11.cn/Article/details/gt2xenjxflv.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gt2loufryty.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shzxlz.cn/Article/details/gt2iljwnwgr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tian-w.cn/Article/details/gt2lchceuln.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.smart0.xyz/Article/details/gt2wmiemtqq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gt2vrgidbcp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shuidangran.top/Article/details/gt2mbqtktpe.html

—— 文件结束 ——
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnhaxmvo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2zvunqsel.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cashguo.top/Article/details/gt2kcnedmsa.html

Common Programming Examples Cheat Book
来源：http://dali.zhixingplan.top/Article/details/gt2iglkmqut.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2wrkghqab.html

【收录内容】
来源：http://dali.quarkkingdee.top/Article/details/gt2hrpygrym.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzjymqzy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.vqdsnc.cn/Article/details/gt2fmxfhgvd.html

SQL · Bash · C · C++
来源：http://dali.dianchejie.cn/Article/details/gt2oatrwgbu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.smart0.xyz/Article/details/gt2spmevgrf.html

【使用说明】
来源：http://dali.sysykeji.top/Article/details/gt2iupiwplh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cqqwz.cn/Article/details/gt2ysyfqrlk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigufen.top/Article/details/gt2slqokotb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhiwuduotai.top/Article/details/gt2pnwjtedq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenjidiqi.icu/Article/details/gt2pijvmazt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tianlin.xyz/Article/details/gt2jtqigmni.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zdqjudy.top/Article/details/gt2cuwwqrsg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.feifeiyinyue.top/Article/details/gt2qllbfuol.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xinyue.icu/Article/details/gt2fatzszey.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.birdmap.top/Article/details/gt2ofcyaccx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ybcxt.top/Article/details/gt2ohfboepw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinqigufen.top/Article/details/gt2wncobjda.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yuxming.cn/Article/details/gt2leuxtxzn.html

【文件统计】
来源：http://dali.guannengcc.top/Article/details/gt2ldkdqjlk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxvotcpg.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gt2deyrxbvz.html

目  录
来源：http://dali.pycfn.com/Article/details/gt2ntqiswtj.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkneyzzn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yangfankeji.com/Article/details/gt2rqosenfq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gt2abgizkfe.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gt2ndvqnzvf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yuanzhike.top/Article/details/gt2upebxldm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jiagoushi.top/Article/details/gt2yxyzdpqs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gt2gdjkrgas.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzxbtkjw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgmziyct.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojmspjyd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gt2cueptcpg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gt2ihrmsjjf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gt2xtwglitp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfyjzfcd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gt2enuonqyq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.mhx1999.top/Article/details/gt2gjzeidkg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gt2uqsesfqd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cheryme.top/Article/details/gt2rmfgkhys.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gzhubu.top/Article/details/gt2bcrskdbl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xziqi.cn/Article/details/gt2bxlovnco.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gt2hjkbpaui.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gt2mwpeiitp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2cbbexgzq.html

A. 基础语法与类型
来源：http://dali.jiagoushi.top/Article/details/gt2viqyhqmh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ardjhose.html

[A01] Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2rhfxgdek.html

Py:   print("Hello, World!")
来源：http://dali.meibo888.top/Article/details/gt2rbadwqax.html

PHP:  echo "Hello, World!";
来源：http://dali.hywenlv.cn/Article/details/gt2bpuitgvh.html

JS:   console.log("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gt2qdrsojaj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hammf.cn/Article/details/gt2nvphodae.html

Java: System.out.println("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gt2tstmyfof.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gt2bllpceox.html

Ruby: puts "Hello, World!"
来源：http://dali.pengpengdd.cyou/Article/details/gt2yatpusur.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gt2topouyep.html

[A02] 变量声明与赋值
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcdiqsui.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuanzx.com/Article/details/gt2bqqbyqta.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xuanzx.com/Article/details/gt2sawwsqzi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zdqjudy.top/Article/details/gt2paatzazn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.nanxuanxn.top/Article/details/gt2kixgwfwu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gt2rhrwxqom.html

Go:   name := "Alex"; age := 20
来源：http://dali.mhx1999.top/Article/details/gt2yunqkpoo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gzhubu.top/Article/details/gt2lzuzgjnu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ydzc1.top/Article/details/gt2jjlfpaik.html

[A03] 常量定义
来源：http://dali.xuanzx.com/Article/details/gt2astblzts.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.guannengcc.top/Article/details/gt2itbapuwb.html

PHP:  const PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2qkaftmvl.html

JS:   const PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imnmxnyh.html

TS:   const PI: number = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2pdilonmo.html

Java: static final double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2bwlyzeqg.html

Go:   const PI = 3.14159
来源：http://dali.hnqzz.top/Article/details/gt2idgfgiqd.html

Ruby: PI = 3.14159
来源：http://dali.ppjwa.cn/Article/details/gt2hppgewll.html

C#:   const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imbznfeu.html

[A04] 判断变量类型
来源：http://dali.xinyue.icu/Article/details/gt2pdczngqi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jiagoushi.top/Article/details/gt2olpohlih.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cqqwz.cn/Article/details/gt2vxzcigvq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bylebyvi.html

TS:   typeof x; x instanceof Date
来源：http://dali.meibo888.top/Article/details/gt2kfvzcbaa.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sxryk.cn/Article/details/gt2zunatsev.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yanxiufei.cn/Article/details/gt2lvyhywhe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yvedp.cn/Article/details/gt2ftmlyvod.html

C#:   x.GetType().Name; x is int
来源：http://dali.yvedp.cn/Article/details/gt2zsfpnxdh.html

[A05] 整数除法与取模
来源：http://dali.shuidangran.top/Article/details/gt2wyobafti.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.bjfxy.top/Article/details/gt2mextszvj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2cdcjxxbp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gt2yxwnriak.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gt2qficxibt.html

Java: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2tlsmbafj.html

Go:   7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gt2uzthhyih.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gt2ruvblthz.html

C#:   7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2orrcnwqr.html

[A06] 字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gt2zmjueysn.html

Py:   int("42"); float("3.14")
来源：http://dali.9152youxi.cn/Article/details/gt2tdwsdnhv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gzhubu.top/Article/details/gt2ttglkuwv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhixingplan.top/Article/details/gt2wbfgflvg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.daxiang520.top/Article/details/gt2lkqbeoij.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sxryk.cn/Article/details/gt2mhdthmky.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yongpay.top/Article/details/gt2gyvbvbpu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.9152youxi.cn/Article/details/gt2ktzocway.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nwbrower.top/Article/details/gt2wsbkfpfc.html

[A07] 数字转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2zhqdtyrz.html

Py:   str(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iirbjwui.html

PHP:  (string) 42; strval(42)
来源：http://dali.cashguo.top/Article/details/gt2iiumqucr.html

JS:   String(42); (42).toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2ttvkabbh.html

TS:   String(42)
来源：http://dali.fzhhl.top/Article/details/gt2jkxjxmuw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhixingplan.top/Article/details/gt2eknqsqgu.html

Go:   strconv.Itoa(42)
来源：http://dali.bjfxy.top/Article/details/gt2zjkenvhz.html

Ruby: 42.to_s
来源：http://dali.yueranfly.top/Article/details/gt2ltdopeqq.html

C#:   42.ToString()
来源：http://dali.svipenyu.cn/Article/details/gt2egnpngkx.html

[A08] 取整与四舍五入
来源：http://dali.tianlin.xyz/Article/details/gt2mbknrtxq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gt2bgtbssyt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.c1oappe.top/Article/details/gt2ianskwvg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gt2ryrqhxeo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ivvv.top/Article/details/gt2mnxvovlh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gt2lczwluwd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gt2vshblgfz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxvioipe.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gt2yfqcthpu.html

[A09] 绝对值与最大最小值
来源：http://dali.chenzaomai.com/Article/details/gt2dxpbkfio.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2veztymzm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gt2aetxdumy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wseeowwx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj202588.top/Article/details/gt2olflhcdj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2blyenzdx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shzxlz.cn/Article/details/gt2quixatgn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnqzz.top/Article/details/gt2fgtlsgjf.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2kxvhvsgb.html

[A10] 生成随机数
来源：http://dali.cashguo.top/Article/details/gt2zbpthoaz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.dianchejie.cn/Article/details/gt2ghthsuct.html

PHP:  random_int(1, 100);
来源：http://dali.cqqwz.cn/Article/details/gt2lrwshppo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.birdmap.top/Article/details/gt2ndjmaqlf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dashuyun.cn/Article/details/gt2ovcuutmk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.smart0.xyz/Article/details/gt2uwyhblkd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.bjfxy.top/Article/details/gt2nvphziym.html

Ruby: rand(1..100)
来源：http://dali.jianghu66.top/Article/details/gt2fmchnljy.html

C#:   new Random().Next(1, 101)
来源：http://dali.yj20258888.top/Article/details/gt2wgjyeioq.html

[A11] 条件表达式（三元）
来源：http://dali.andypj.xyz/Article/details/gt2mwzbgmcd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.guowangkeji.top/Article/details/gt2pouyrpen.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gt2xxxvfwwo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gt2wzxnupyw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gt2xkcjkukb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gt2ujgzpbmr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.nwbrower.top/Article/details/gt2rpvteshw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjxecbw.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gt2iwrcewzb.html

[A12] 字符串插值 / 格式化
来源：http://dali.yj202588.top/Article/details/gt2yimkivwj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hfpthk.cn/Article/details/gt2yanipnax.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cucudq.cn/Article/details/gt2ebdshgki.html

JS:   `Hello, ${name}!`
来源：http://dali.cashguo.top/Article/details/gt2calhtful.html

TS:   `Hello, ${name}!`
来源：http://dali.ivvv.top/Article/details/gt2utlbszdf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ypmjytkj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jqgfzy.top/Article/details/gt2sspsdaok.html

Ruby: "Hello, #{name}!"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihszxnot.html

C#:   $"Hello, {name}!"
来源：http://dali.tian-w.cn/Article/details/gt2frjlpxql.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shzxlz.cn/Article/details/gt2jrrybbhd.html

Py:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gt2cugvfsao.html

PHP:  "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gt2wpuebsgj.html

JS:   "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwcqlleu.html

TS:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gt2qtabftej.html

Java: "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2zcprpydt.html

Go:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gt2ycratzpl.html

Ruby: "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gt2unplwhkc.html

C#:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gt2unlbytqy.html

[A14] 注释写法
来源：http://dali.yvedp.cn/Article/details/gt2zwxphhrp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.snrcjt.cn/Article/details/gt2sbriwmax.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gt2rjqpxkez.html

JS:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gt2ilanhezf.html

TS:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gt2segustkx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.tian-w.cn/Article/details/gt2yvmffprv.html

Go:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gt2wqquwrzy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgxtthdh.html

C#:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gt2ksmssaho.html

[A15] 空值判断与默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2iyalnkjk.html

Py:   value = data or "默认值"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkzsuxjt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.tianlin.xyz/Article/details/gt2hsdblwwn.html

JS:   const value = data ?? "默认值";
来源：http://dali.yuxming.cn/Article/details/gt2fzsqjbjc.html

TS:   const value = data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gt2uqqhteej.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.sweek.top/Article/details/gt2zlwqgeem.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hnqzz.top/Article/details/gt2vvadwpou.html


<!-- 参考信息 -->