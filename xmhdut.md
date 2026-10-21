代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.dianchejie.cn/Article/details/gthbvzttai.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gtzmjjgbgk.html

[U92] JS：深拷贝
来源：http://dali.zhengqikj.top/Article/details/gtsrrxkcvd.html

structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtarjzktkl.html

[U93] JS：模板字符串
来源：http://dali.jqgufenzy.top/Article/details/gtkfbnkxrt.html

`共 ${n} 条`
来源：http://dali.wangshuangyany.cn/Article/details/gtogswjliy.html

[U94] JS：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gtfzxmrdeq.html

const double = x => x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpcuiidz.html

[U95] JS：Promise 包装
来源：http://dali.zhixingplan.top/Article/details/gttxqwvnfg.html

new Promise((resolve, reject) => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtcynjjtzb.html

[U96] JS：async/await 与异常
来源：http://dali.jiagoushi.top/Article/details/gtboprkpga.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtcnmaolkk.html

[U97] JS：并发请求
来源：http://dali.nanxinkj.top/Article/details/gtwvkjxhic.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtumczxszu.html

[U98] JS：fetch 带 JSON
来源：http://dali.cucudq.cn/Article/details/gtugegcilb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtggbtsuqy.html

[U99] JS：事件监听
来源：http://dali.nanxuanxn.top/Article/details/gtomjorrxt.html

el.addEventListener("click", e => {})
来源：http://dali.yj202588.top/Article/details/gtxiucabsd.html

[U100] JS：DOM 查询
来源：http://dali.nanxinkj.top/Article/details/gtnyloxxbl.html

document.querySelector(".item")
来源：http://dali.hongshengwenyu.top/Article/details/gtvbjydqfy.html

[U101] JS：classList 操作
来源：http://dali.guannengcc.top/Article/details/gtzpquyrnf.html

el.classList.toggle("active")
来源：http://dali.redwolf501.top/Article/details/gtibbdyuvv.html

[U102] JS：本地存储
来源：http://dali.zhixingplan.top/Article/details/gtrhygjnja.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yuanzhike.top/Article/details/gtvohptqws.html

[U103] JS：定时器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvulnlock.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cqqwz.cn/Article/details/gtfibpqaen.html

[U104] JS：防抖
来源：http://dali.dianchejie.cn/Article/details/gtkpvaeuzp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtnywzsmpz.html

[U105] JS：节流
来源：http://dali.pengpengdd.cyou/Article/details/gtaerecysa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xziqi.cn/Article/details/gtvciukmax.html

[U106] JS：日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtyrfqgpkq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigfzy.top/Article/details/gtreikvefo.html

[U107] JS：数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gtrriwvbdp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtowvtlyub.html

[U108] JS：随机整数
来源：http://dali.chenjidiqi.icu/Article/details/gtacncfsvx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daxiang520.top/Article/details/gtuipayysh.html

[U109] JS：数组分组
来源：http://dali.gotoacloud.top/Article/details/gtmunbtkeh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gtrbiopwzs.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gtemjtxuee.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gtjdwsnskj.html

[U111] JS：对象转 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtenniepyh.html

new Map(Object.entries(obj))
来源：http://dali.dashuyun.cn/Article/details/gtmevweiix.html

[U112] JS：字符串补位
来源：http://dali.guowangkeji.top/Article/details/gtiusyjzgi.html

"7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtpglghhes.html

[U113] JS：正则替换全部
来源：http://dali.shangyingyoupin.top/Article/details/gtwlluiadz.html

s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtbzxnlzfe.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtbibsfgmi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtiebluuod.html

[U115] JS：生成 UUID
来源：http://dali.pycfn.com/Article/details/gtbjhrswpn.html

crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdoqwxfb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jianghu66.top/Article/details/gtunyqteze.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtduvainpm.html

[U117] JS：单元测试
来源：http://dali.guannengcc.top/Article/details/gtqmuhdaqy.html

npm i -D vitest;  npx vitest
来源：http://dali.xuetiantiany.cn/Article/details/gtoweayxfp.html

[U118] JS：开发服务器
来源：http://dali.wangdashe.top/Article/details/gtynvnbgea.html

npm i -D vite;  npx vite
来源：http://dali.andypj.xyz/Article/details/gtprltxoce.html

[U119] JS：生产构建
来源：http://dali.chenjidiqi.icu/Article/details/gtielmysgu.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gtmigpgggc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.meibo888.top/Article/details/gtyiaakkwp.html

import.meta.env.VITE_API_URL
来源：http://dali.xinyue.icu/Article/details/gtlbclmprq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtpcaqxacc.html

统计汇总
来源：http://dali.xuetiantiany.cn/Article/details/gthalpcsuj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvqjiejjo.html

按语言统计（条）：
来源：http://dali.shanyushiyangtech.top/Article/details/gtsialguph.html

Python ......... 252
来源：http://dali.hongshengwenyu.top/Article/details/gtynybvptk.html

PHP ............ 252
来源：http://dali.sxryk.cn/Article/details/gtkpvngeit.html

JavaScript ..... 252
来源：http://dali.aizwys.cn/Article/details/gtzthzsaon.html

TypeScript ..... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbqciguc.html

Java ........... 212
来源：http://dali.feifeiyinyue.top/Article/details/gticjnqwlr.html

Go ............. 212
来源：http://dali.yuanzhike.top/Article/details/gtbojinidi.html

Ruby ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gtyzlbuyem.html

C# ............. 212
来源：http://dali.jinqigufen.top/Article/details/gtkfjtvhiz.html

C .............. 30
来源：http://dali.gotoacloud.top/Article/details/gtmsyarrxp.html

C++ ............ 30
来源：http://dali.fzhhl.top/Article/details/gtznyflped.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gtivarqyyc.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gtygipwhrs.html

Kotlin ......... 15
来源：http://dali.jqgufenzy.top/Article/details/gtnpmqsxiq.html

Swift .......... 15
来源：http://dali.pycfn.com/Article/details/gttgqjqaxg.html

Lua ............ 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplpkfcls.html

Perl ........... 10
来源：http://dali.gogol.net.cn/Article/details/gtnsxercpp.html

Scala .......... 10
来源：http://dali.yueranfly.top/Article/details/gtnbrbvepl.html

------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtgeaptals.html

合计 ........... 2106 条
来源：http://dali.vqdsnc.cn/Article/details/gtshsrrgpl.html

按章节统计：
来源：http://dali.hongshengwenyu.top/Article/details/gtahbxjalj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtorlnkeeo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gthrezxlnb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtjnnccjmz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gtabppwkqn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.pengpengdd.cyou/Article/details/gtwjgcghnm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xinyue.icu/Article/details/gtlflgrvre.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gtrhvlcduk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj202588.top/Article/details/gtbttbfapa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtqdllyfdl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gtxkuecake.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gttskvnmfp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtierpheos.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtmplugrxs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gtwazsnxuq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj20258.top/Article/details/gtjioujpba.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtiphfvsoj.html

Q SQL 专题                              90
来源：http://dali.hysaishi.cn/Article/details/gtpbwztcyn.html

R Bash 专题                             80
来源：http://dali.wangdashe.top/Article/details/gtiibdfnrd.html

S C / C++ 专题                          60
来源：http://dali.gotoacloud.top/Article/details/gthpuubjof.html

T 其他语言补充                          60
来源：http://dali.pycfn.com/Article/details/gtdriwahig.html

U 高频实用片段                         120
来源：http://dali.fzhhl.top/Article/details/gthxnfwbht.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtymwpmons.html

合计                                  2106 条
来源：http://dali.kuanghao11.cn/Article/details/gtzgzqouiq.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtepzgcnah.html

使用提醒
来源：http://dali.smart0.xyz/Article/details/gtauoewwzo.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtbdnnejvx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.fengsongda.top/Article/details/gtoresxsdr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hfpthk.cn/Article/details/gtinemzyse.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj202588.top/Article/details/gtxtccxorq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuetiantiany.cn/Article/details/gtmiyvefzi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgfzy.top/Article/details/gtdzteyegl.html

—— 文件结束 ——
来源：http://dali.xziqi.cn/Article/details/gtzemfiqhd.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgajamkrv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ppjwa.cn/Article/details/gtjosatfks.html

Common Programming Examples Cheat Book
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysptjqjx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtissuifsx.html

【收录内容】
来源：http://dali.zhongyouzk.top/Article/details/gtsnhgzmlx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxuhjtnfs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tanke756.top/Article/details/gtjtvcvalz.html

SQL · Bash · C · C++
来源：http://dali.andypj.xyz/Article/details/gtfygxwewn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhneejby.html

【使用说明】
来源：http://dali.yj20258888.top/Article/details/gteyokubtb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.0kj1m.cn/Article/details/gtkfkfrbdz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cucudq.cn/Article/details/gtvilieatg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cucudq.cn/Article/details/gttclkjplj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.svipenyu.cn/Article/details/gtldboohfb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenjidiqi.icu/Article/details/gtbbmyqmpc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jinqigufen.top/Article/details/gtpnlfolsf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ivvv.top/Article/details/gtcumohxlp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhongyouzk.top/Article/details/gtqrofbwmq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hfpthk.cn/Article/details/gtvqmqmzao.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.bjfxy.top/Article/details/gtblijogdu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shzxlz.cn/Article/details/gtjlffwwqh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.guannengcc.top/Article/details/gtptclceil.html

【文件统计】
来源：http://dali.sxryk.cn/Article/details/gtzqsdczkh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gtkyejzwzp.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gtqpucnnrx.html

目  录
来源：http://dali.nanxinkj.top/Article/details/gtfebebici.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqxxptzg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gtkiyoxvfo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gtvgurlunz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gttevtpfvq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gtojvqejqf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xziqi.cn/Article/details/gtyigvkvje.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hywenlv.cn/Article/details/gtikkapdqe.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jiagoushi.top/Article/details/gtozvnzhvs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cucudq.cn/Article/details/gtgkmgqgis.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtihpshqmp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yuxming.cn/Article/details/gtoapgyrop.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtgaevplna.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gtajzjcpty.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtsykyrtnl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.aizwys.cn/Article/details/gthojyvzvm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsqtssks.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtwsdfldpe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.smart0.xyz/Article/details/gtbefahffj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.bjfxy.top/Article/details/gtiqedrsuz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhixingplan.top/Article/details/gtxzusonim.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gtkgmzbmaj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtccvkfakq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtsuijdkje.html

A. 基础语法与类型
来源：http://dali.xuetiantiany.cn/Article/details/gtbwudjtto.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxcwpjgjp.html

[A01] Hello World
来源：http://dali.shzxlz.cn/Article/details/gtpsktxqfk.html

Py:   print("Hello, World!")
来源：http://dali.yj20258888.top/Article/details/gtjuiuaqya.html

PHP:  echo "Hello, World!";
来源：http://dali.redwolf501.top/Article/details/gtlsalurkx.html

JS:   console.log("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbacxbnc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnqzz.top/Article/details/gtfdqaweho.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrwghuuw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.bjfxy.top/Article/details/gtcqganvjt.html

Ruby: puts "Hello, World!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcjxstou.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gttbemlcjb.html

[A02] 变量声明与赋值
来源：http://dali.vqdsnc.cn/Article/details/gtvvouttuu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.mhx1999.top/Article/details/gtwiqzbdfg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tian-w.cn/Article/details/gtuadwlwfj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ivvv.top/Article/details/gtbqsckupl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ppjwa.cn/Article/details/gtjgaawlpe.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gtnvjzsvpk.html

Go:   name := "Alex"; age := 20
来源：http://dali.316326.xyz/Article/details/gtlreyjbty.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhengqikj.top/Article/details/gtlwgbqjkc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gthmtxlijg.html

[A03] 常量定义
来源：http://dali.yanxiufei.cn/Article/details/gtjaxzmpho.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yueranfly.top/Article/details/gtxtbmeixv.html

PHP:  const PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtiuofzrri.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtqnrnwstn.html

TS:   const PI: number = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtfzdyhqqs.html

Java: static final double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtyhnhuwjl.html

Go:   const PI = 3.14159
来源：http://dali.fengsongda.top/Article/details/gtcplyekid.html

Ruby: PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gtvrqtnlud.html

C#:   const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtltkuwkgq.html

[A04] 判断变量类型
来源：http://dali.zhongyouzk.top/Article/details/gtahbrxkit.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.0kj1m.cn/Article/details/gtrrlyrrqa.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cqqwz.cn/Article/details/gtpkachllp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.wangshuangyany.cn/Article/details/gtopvowulh.html

TS:   typeof x; x instanceof Date
来源：http://dali.yueranfly.top/Article/details/gtwgeoebpy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shangyingyoupin.top/Article/details/gtobvkhmfu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sxryk.cn/Article/details/gttkqvbaya.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gogol.net.cn/Article/details/gthvslxwyw.html

C#:   x.GetType().Name; x is int
来源：http://dali.yangfankeji.com/Article/details/gtdjamvqjd.html

[A05] 整数除法与取模
来源：http://dali.daria6918.cn/Article/details/gtqqfzqfzn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkffqglze.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtpppyfhir.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtteacglqq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtpjvnkygt.html

Java: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtyiqticoh.html

Go:   7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebwrkzsa.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gtmheslwhh.html

C#:   7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtexparhgg.html

[A06] 字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gtghpuaiws.html

Py:   int("42"); float("3.14")
来源：http://dali.zycfv.cn/Article/details/gtezgacdly.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gotoacloud.top/Article/details/gtmjqtwvbw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.haohaochexian.top/Article/details/gtkrsbjlcn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.quarkkingdee.top/Article/details/gtnfmnmadj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgstptnr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sysykeji.top/Article/details/gtnokwugss.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gtanissfhs.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hfpthk.cn/Article/details/gtlvtixnfl.html

[A07] 数字转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsfcryob.html

Py:   str(42)
来源：http://dali.hywenlv.cn/Article/details/gtulvsejrq.html

PHP:  (string) 42; strval(42)
来源：http://dali.yangfankeji.com/Article/details/gtgjrmtiko.html

JS:   String(42); (42).toString()
来源：http://dali.fengsongda.top/Article/details/gthbuxdbof.html

TS:   String(42)
来源：http://dali.yj20258.top/Article/details/gtirlrbjkm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.nwbrower.top/Article/details/gtexxcbcpi.html

Go:   strconv.Itoa(42)
来源：http://dali.aibaodan.cn/Article/details/gtfbtrsqvf.html

Ruby: 42.to_s
来源：http://dali.nanxuanxn.top/Article/details/gttpidgbjs.html

C#:   42.ToString()
来源：http://dali.yvedp.cn/Article/details/gtiqxefokv.html

[A08] 取整与四舍五入
来源：http://dali.dashuyun.cn/Article/details/gtcsmpdsso.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gtmuvrchjd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhixingplan.top/Article/details/gtfrgkvkdi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ivvv.top/Article/details/gtjdiindox.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.dianchejie.cn/Article/details/gtejcnbgyn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gogol.net.cn/Article/details/gttjbxnlrb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtfruuimpy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhengqikj.top/Article/details/gtmoblpelz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gtfodlddoq.html

[A09] 绝对值与最大最小值
来源：http://dali.redwolf501.top/Article/details/gtrzojcneh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtxjnvuknh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtczsajcqw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtcckgwvvb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtmuooodhi.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtfikhwfdc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dianchejie.cn/Article/details/gtabchvkam.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.dashuyun.cn/Article/details/gtruuhfwui.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtiqvoyqkg.html

[A10] 生成随机数
来源：http://dali.jqgfzy.top/Article/details/gtrtlcpeok.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhengqikj.top/Article/details/gtzhvqozyu.html

PHP:  random_int(1, 100);
来源：http://dali.yueranfly.top/Article/details/gtzpozoyud.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guannengcc.top/Article/details/gthspvbrxm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenlongwang.top/Article/details/gtacxkaizv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcgeinad.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pengpengdd.cyou/Article/details/gtjlkotsxt.html

Ruby: rand(1..100)
来源：http://dali.yangfankeji.com/Article/details/gtgwnegxrx.html

C#:   new Random().Next(1, 101)
来源：http://dali.316326.xyz/Article/details/gtfcqjfgsd.html

[A11] 条件表达式（三元）
来源：http://dali.chenzaomai.com/Article/details/gtbdsrtqvr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.haohaochexian.top/Article/details/gtqbqfiacr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtkftsdufu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gtgceukwrk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtdrtbjysx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gtvdaxwvkj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hnqzz.top/Article/details/gtxphpijby.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gtqmlucqam.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtxmohodhe.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxgdjutf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jlsjyb.cn/Article/details/gtiwlxqqcj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.nanxuanxn.top/Article/details/gtpjljvykr.html

JS:   `Hello, ${name}!`
来源：http://dali.jinghuilouyu.cn/Article/details/gththfakgh.html

TS:   `Hello, ${name}!`
来源：http://dali.snrcjt.cn/Article/details/gterowzxkd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hysaishi.cn/Article/details/gtlrvureup.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtsqyutxog.html

Ruby: "Hello, #{name}!"
来源：http://dali.yj20258888.top/Article/details/gtrbtytdwe.html

C#:   $"Hello, {name}!"
来源：http://dali.jinqigufen.top/Article/details/gtxrcowynm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jlsjyb.cn/Article/details/gtiznqpmic.html

Py:   "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gttzumpxxy.html

PHP:  "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtcqxsocsh.html

JS:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtbsbvrbax.html

TS:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtbrozteut.html

Java: "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtlummgllc.html

Go:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtooyighpr.html

Ruby: "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gthdudwhth.html

C#:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtapiluzaj.html

[A14] 注释写法
来源：http://dali.tian-w.cn/Article/details/gtfnxpfgpd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ybcxt.top/Article/details/gtcpzqlugd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.chenlongwang.top/Article/details/gtjhbhupel.html

JS:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtfcbtscwl.html

TS:   // 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gtfbamjzhp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.bjfxy.top/Article/details/gthzkyoyfl.html

Go:   // 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gtmisnatmi.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.quarkkingdee.top/Article/details/gtgacwemak.html

C#:   // 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gtxexmlwdi.html

[A15] 空值判断与默认值
来源：http://dali.yanxiufei.cn/Article/details/gtupxyjfng.html

Py:   value = data or "默认值"
来源：http://dali.cashguo.top/Article/details/gtatrdvktp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gtkqxhpypm.html

JS:   const value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gtnmdgwqhf.html

TS:   const value = data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gtfdqeikma.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofrkysph.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.quarkkingdee.top/Article/details/gtjgbqdrfu.html


<!-- 参考信息 -->