代发 wailian999

[U89] JS：数组去重
来源：http://dali.xuetiantiany.cn/Article/details/gtumkqqbrw.html

[...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoduclppa.html

[U90] JS：数字数组排序
来源：http://dali.sweek.top/Article/details/gtssikgtbj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtgdvaikwx.html

[U91] JS：对象键值遍历
来源：http://dali.gzhubu.top/Article/details/gtxkgynavz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.mhx1999.top/Article/details/gtitvnjjdp.html

[U92] JS：深拷贝
来源：http://dali.0kj1m.cn/Article/details/gtrylyuoqn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtaatchprb.html

[U93] JS：模板字符串
来源：http://dali.sweek.top/Article/details/gtlmxalhnl.html

`共 ${n} 条`
来源：http://dali.chenjidiqi.icu/Article/details/gtrpjccfcd.html

[U94] JS：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gtqczaxgjs.html

const double = x => x * 2;
来源：http://dali.smart0.xyz/Article/details/gtdppwbjdm.html

[U95] JS：Promise 包装
来源：http://dali.cheryme.top/Article/details/gttmntzgxp.html

new Promise((resolve, reject) => {})
来源：http://dali.ivvv.top/Article/details/gtjndbqshz.html

[U96] JS：async/await 与异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtbelmyuxw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtwnplrjky.html

[U97] JS：并发请求
来源：http://dali.zhengqikj.top/Article/details/gtdimnfsjs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gttnjyzzzo.html

[U98] JS：fetch 带 JSON
来源：http://dali.bjfxy.top/Article/details/gtngxpimdl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dianchejie.cn/Article/details/gttmxlfwwj.html

[U99] JS：事件监听
来源：http://dali.dashuyun.cn/Article/details/gtrchkekjz.html

el.addEventListener("click", e => {})
来源：http://dali.aibaodan.cn/Article/details/gteqmwlylz.html

[U100] JS：DOM 查询
来源：http://dali.wangdashe.top/Article/details/gteagzbdds.html

document.querySelector(".item")
来源：http://dali.jqgfzy.top/Article/details/gtejjfgedw.html

[U101] JS：classList 操作
来源：http://dali.mhx1999.top/Article/details/gtrhcqlhuw.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gtdkqrpbjz.html

[U102] JS：本地存储
来源：http://dali.andypj.xyz/Article/details/gtoyakcsrr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj20258888.top/Article/details/gtjtrkrpls.html

[U103] JS：定时器
来源：http://dali.zhoulong.xyz/Article/details/gtwdrblkth.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yueranfly.top/Article/details/gtptnpgwen.html

[U104] JS：防抖
来源：http://dali.zhiwuduotai.top/Article/details/gtjrsfamwr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtguyikrke.html

[U105] JS：节流
来源：http://dali.daxiang520.top/Article/details/gtagaxelxt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.guannengcc.top/Article/details/gtpqwomwsw.html

[U106] JS：日期格式化
来源：http://dali.hfpthk.cn/Article/details/gttantlaew.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cheryme.top/Article/details/gtefdqcfhu.html

[U107] JS：数字千分位
来源：http://dali.sxryk.cn/Article/details/gteezyfprp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtzrcukdaq.html

[U108] JS：随机整数
来源：http://dali.yonumen.top/Article/details/gtsvvbaamo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zycfv.cn/Article/details/gtlahpdvcj.html

[U109] JS：数组分组
来源：http://dali.9152youxi.cn/Article/details/gtckjxphvv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gtonpiufyt.html

[U110] JS：数组分块
来源：http://dali.bjfxy.top/Article/details/gtdaivperp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zdqjudy.top/Article/details/gtyumhxlpb.html

[U111] JS：对象转 Map
来源：http://dali.yonumen.top/Article/details/gttncrtzzg.html

new Map(Object.entries(obj))
来源：http://dali.gogol.net.cn/Article/details/gtkgxobofq.html

[U112] JS：字符串补位
来源：http://dali.zhongyouzk.top/Article/details/gtcqdslald.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaoyvyax.html

[U113] JS：正则替换全部
来源：http://dali.xziqi.cn/Article/details/gtwnoowwhx.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtgrbqtnri.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258888.top/Article/details/gtojvayxha.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtvrxscvji.html

[U115] JS：生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtamnfledj.html

crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwrdirbh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gotoacloud.top/Article/details/gtbunackbg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgzgipkax.html

[U117] JS：单元测试
来源：http://dali.pycfn.com/Article/details/gtdmgvmifn.html

npm i -D vitest;  npx vitest
来源：http://dali.redwolf501.top/Article/details/gtqglbvskv.html

[U118] JS：开发服务器
来源：http://dali.yangfankeji.com/Article/details/gtruirzkao.html

npm i -D vite;  npx vite
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdvkthrb.html

[U119] JS：生产构建
来源：http://dali.aizwys.cn/Article/details/gtwkybcllq.html

npx vite build
来源：http://dali.cucudq.cn/Article/details/gtqqrbegxv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zdqjudy.top/Article/details/gtsjrdtabw.html

import.meta.env.VITE_API_URL
来源：http://dali.cheryme.top/Article/details/gtsznfdbuf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwbrlakoi.html

统计汇总
来源：http://dali.ehwqpu.com/Article/details/gtschudrmh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwhkxxagh.html

按语言统计（条）：
来源：http://dali.wangdashe.top/Article/details/gtqkhrhqwz.html

Python ......... 252
来源：http://dali.mhx1999.top/Article/details/gtwrkpvlfi.html

PHP ............ 252
来源：http://dali.shzxlz.cn/Article/details/gtcaiatwbz.html

JavaScript ..... 252
来源：http://dali.dashuyun.cn/Article/details/gtkkzuqjed.html

TypeScript ..... 212
来源：http://dali.nanxuanxn.top/Article/details/gtyycnomdn.html

Java ........... 212
来源：http://dali.gotoacloud.top/Article/details/gtzrdgyyor.html

Go ............. 212
来源：http://dali.mhx1999.top/Article/details/gtzxaarwba.html

Ruby ........... 212
来源：http://dali.yongpay.top/Article/details/gtjokmuige.html

C# ............. 212
来源：http://dali.meibo888.top/Article/details/gttavfkzws.html

C .............. 30
来源：http://dali.dianchejie.cn/Article/details/gtgpkkvgvk.html

C++ ............ 30
来源：http://dali.zycfv.cn/Article/details/gthdgteyid.html

SQL ............ 90
来源：http://dali.dianchejie.cn/Article/details/gtfvhuvdzr.html

Bash ........... 80
来源：http://dali.chenjidiqi.icu/Article/details/gtrmnmfgym.html

Kotlin ......... 15
来源：http://dali.ivvv.top/Article/details/gtzlbhjduz.html

Swift .......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gtmsqlpwqg.html

Lua ............ 10
来源：http://dali.pengpengdd.cyou/Article/details/gtrpzcjpyd.html

Perl ........... 10
来源：http://dali.yj20258888.top/Article/details/gtchsngtcb.html

Scala .......... 10
来源：http://dali.svipenyu.cn/Article/details/gtcvgwwwqu.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gthfhesixz.html

合计 ........... 2106 条
来源：http://dali.zhongyouzk.top/Article/details/gtdrxfkbnb.html

按章节统计：
来源：http://dali.zhongyouzk.top/Article/details/gtaqxtonma.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guowangkeji.top/Article/details/gtsoicvnsz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtnzddkttk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtmjmzebdf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gttykfgmzl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tian-w.cn/Article/details/gtorpoteed.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gtielcteyo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtsdebuwtw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daxiang520.top/Article/details/gtqrhmxiuz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtvxgdoyia.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gtkamimwpr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtkkpuxwss.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtrbaygphp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gthzuksvnz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gtarfskzpe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hnxiangtu.top/Article/details/gtcgwmnmgb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtglypuxwu.html

Q SQL 专题                              90
来源：http://dali.hfpthk.cn/Article/details/gtawshvmkw.html

R Bash 专题                             80
来源：http://dali.gzhubu.top/Article/details/gtdidhsqby.html

S C / C++ 专题                          60
来源：http://dali.hongshengwenyu.top/Article/details/gtjlfdchym.html

T 其他语言补充                          60
来源：http://dali.pengpengdd.cyou/Article/details/gtgavjszzk.html

U 高频实用片段                         120
来源：http://dali.feifeiyinyue.top/Article/details/gthesnatfu.html

------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtvlpwbtvp.html

合计                                  2106 条
来源：http://dali.haohaochexian.top/Article/details/gttftkrxld.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtzgmzdudu.html

使用提醒
来源：http://dali.shangyingyoupin.top/Article/details/gtjtxtywno.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtdghjouui.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinyuanbaomall.cn/Article/details/gthysgafuv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gtzqexclgs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gzhubu.top/Article/details/gtseyzzbfj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinqigfzy.top/Article/details/gtcjofqrnb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.pengpengdd.cyou/Article/details/gtghfnvouy.html

—— 文件结束 ——
来源：http://dali.wangdashe.top/Article/details/gtwlpebwwx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtlhimdxfn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.andypj.xyz/Article/details/gtknlzhtww.html

Common Programming Examples Cheat Book
来源：http://dali.xylfe.cn/Article/details/gtycquicjb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlownotqn.html

【收录内容】
来源：http://dali.chenzaomai.com/Article/details/gtojkptkol.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xylfe.cn/Article/details/gtstdkeqsp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhixingplan.top/Article/details/gtfmaeubgd.html

SQL · Bash · C · C++
来源：http://dali.yvedp.cn/Article/details/gtlsppbpff.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.bjfxy.top/Article/details/gtxfjzjjmk.html

【使用说明】
来源：http://dali.daxiang520.top/Article/details/gtzcyijxoi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangtech.top/Article/details/gthpyjblbs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrzrosgt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shuidangran.top/Article/details/gtvptrqveb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gotoacloud.top/Article/details/gtqbhjkswz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ehwqpu.com/Article/details/gtjwrcvmwj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shzxlz.cn/Article/details/gtfzuhzwtc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tanke756.top/Article/details/gtrxvesfcs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jqgufenzy.top/Article/details/gthsdgudwu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenzaomai.com/Article/details/gtfnyipaci.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xuanzx.com/Article/details/gtzicghicb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenlongwang.top/Article/details/gtkjvkxvxs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.guannengcc.top/Article/details/gtcpwkgbji.html

【文件统计】
来源：http://dali.yj20258888.top/Article/details/gtbvltoned.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinghuilouyu.cn/Article/details/gtocppvgxu.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtjeztcart.html

目  录
来源：http://dali.ybcxt.top/Article/details/gtlsmawbcj.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtalnqztwj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jqgfzy.top/Article/details/gtowpqygqg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gtvqwstfow.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtvrgibkrn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.fzhhl.top/Article/details/gtsyzfaafv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.9152youxi.cn/Article/details/gtvsjgshoz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdoluksb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gtvubzrwho.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sxryk.cn/Article/details/gtrpxfmbvr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqsuhagr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtddmmzuig.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtrsgcbiks.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtlcuvebyz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtijebhtaf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.birdmap.top/Article/details/gtlyxrsifv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangdashe.top/Article/details/gtlgwnvfum.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtyrjwwjgh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhoulong.xyz/Article/details/gtdcghekac.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cashguo.top/Article/details/gtzcoxehfv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtospcxnqs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtqdlitwxi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gtuggogkzw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjvmqgwad.html

A. 基础语法与类型
来源：http://dali.daria6918.cn/Article/details/gtahntpipa.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgysiyva.html

[A01] Hello World
来源：http://dali.aizwys.cn/Article/details/gtbkndimfg.html

Py:   print("Hello, World!")
来源：http://dali.jqgufenzy.top/Article/details/gtilcxvfwe.html

PHP:  echo "Hello, World!";
来源：http://dali.tianlin.xyz/Article/details/gtmotgfcdj.html

JS:   console.log("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gtzjgslzeb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hongshengwenyu.top/Article/details/gthctthdkl.html

Java: System.out.println("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gtlxvapbjz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nanxinkj.top/Article/details/gtzybtpfma.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgfzy.top/Article/details/gtbcbzvgum.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gtfxibumlc.html

[A02] 变量声明与赋值
来源：http://dali.cheryme.top/Article/details/gttvnkbgsf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.wangdashe.top/Article/details/gtnacnpwba.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtfphcljzc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.redwolf501.top/Article/details/gtzjzxlngi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gttblxyuih.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.iojbl.cn/Article/details/gtbaizjekw.html

Go:   name := "Alex"; age := 20
来源：http://dali.tianlin.xyz/Article/details/gtsvxhyass.html

Ruby: name = "Alex"; age = 20
来源：http://dali.havefunace.top/Article/details/gtuynztroc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tianlin.xyz/Article/details/gtggbfpotf.html

[A03] 常量定义
来源：http://dali.jqgufenzy.top/Article/details/gtgzsnuqjp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fengsongda.top/Article/details/gtothyxsnw.html

PHP:  const PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gthfrvgqei.html

JS:   const PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehhyolva.html

TS:   const PI: number = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtdcfnuwdh.html

Java: static final double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtbrjhqflz.html

Go:   const PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtnrmltkgl.html

Ruby: PI = 3.14159
来源：http://dali.jinqigufen.top/Article/details/gtccibircl.html

C#:   const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtxxbsvqmh.html

[A04] 判断变量类型
来源：http://dali.yj202588.top/Article/details/gtgusvmser.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenzaomai.com/Article/details/gtafuuuqhg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.havefunace.top/Article/details/gtohgpzmqf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gtlynovaxj.html

TS:   typeof x; x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gtvwhtgwyu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.mhx1999.top/Article/details/gtnypvsuil.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.wangshuangyany.cn/Article/details/gtokfvrzzs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cashguo.top/Article/details/gtjytltzsu.html

C#:   x.GetType().Name; x is int
来源：http://dali.jlsjyb.cn/Article/details/gtxlwxwgfz.html

[A05] 整数除法与取模
来源：http://dali.aibaodan.cn/Article/details/gtyptblyci.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gotoacloud.top/Article/details/gtkiyelgml.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtgsdjbwye.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtkfscyelh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtdjslugui.html

Java: 7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gtfndqdglj.html

Go:   7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtizellasq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gthyeorbtm.html

C#:   7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtnmnoybzl.html

[A06] 字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gtngclxcgo.html

Py:   int("42"); float("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gtkqclnaws.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cheryme.top/Article/details/gtmiwowixr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xziqi.cn/Article/details/gtkdaphzpp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shzxlz.cn/Article/details/gtcncostvj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shuidangran.top/Article/details/gtateywcgs.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xinyue.icu/Article/details/gtwbfjnhfv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhongyouzk.top/Article/details/gtytcbiwmf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.tian-w.cn/Article/details/gtywffuywg.html

[A07] 数字转字符串
来源：http://dali.fzhhl.top/Article/details/gtrpuderdc.html

Py:   str(42)
来源：http://dali.smart0.xyz/Article/details/gtnnrvqkcr.html

PHP:  (string) 42; strval(42)
来源：http://dali.gaohongyu789.top/Article/details/gtinhcmlnn.html

JS:   String(42); (42).toString()
来源：http://dali.jinqigfzy.top/Article/details/gtwjwwnofj.html

TS:   String(42)
来源：http://dali.c1oappe.top/Article/details/gtlrydizzd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gtccynuylt.html

Go:   strconv.Itoa(42)
来源：http://dali.bjfxy.top/Article/details/gthzhhufmy.html

Ruby: 42.to_s
来源：http://dali.gogol.net.cn/Article/details/gtizpknctz.html

C#:   42.ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtuluhgnbu.html

[A08] 取整与四舍五入
来源：http://dali.sweek.top/Article/details/gtgkoascjc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtzzvaidjt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.svipenyu.cn/Article/details/gthudvkqjd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gttqwybfkj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj20258888.top/Article/details/gtdhytpimw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtnppvoiun.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtswndwnhi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.sufxvd.cn/Article/details/gtmkxzzpjv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gtinmzloqg.html

[A09] 绝对值与最大最小值
来源：http://dali.jyoumei.cn/Article/details/gtovyjgjnz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shuidangran.top/Article/details/gttsmuvqtw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuercldaa.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtpckedslw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtojkyfwba.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtwyfnkkmp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhengqikj.top/Article/details/gtvvtxbyrw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xuanzx.com/Article/details/gttejzpypq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadcofhfa.html

[A10] 生成随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtwifkfous.html

Py:   import random; random.randint(1, 100)
来源：http://dali.dashuyun.cn/Article/details/gtldmyzxua.html

PHP:  random_int(1, 100);
来源：http://dali.xylfe.cn/Article/details/gthxnbbzaz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypbpxtvr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cqqwz.cn/Article/details/gtxpeotczo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.shzxlz.cn/Article/details/gtyyrzojza.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvhndyqp.html

Ruby: rand(1..100)
来源：http://dali.daxiang520.top/Article/details/gtpwwfmtsy.html

C#:   new Random().Next(1, 101)
来源：http://dali.tanke756.top/Article/details/gtjdsqecho.html

[A11] 条件表达式（三元）
来源：http://dali.zycfv.cn/Article/details/gtkiiidlra.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yueranfly.top/Article/details/gtiyddfhsh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gthpzfjhyy.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtubbtzvdi.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtzlnfiyxl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gtpylqaoui.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hywenlv.cn/Article/details/gtewmryfnh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gtmoyxsoxq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtlrslehpk.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinqigfzy.top/Article/details/gtpegeccir.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.pengpengdd.cyou/Article/details/gtultmfgsk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jqgfzy.top/Article/details/gtqeieenvh.html

JS:   `Hello, ${name}!`
来源：http://dali.hammf.cn/Article/details/gtdivcqewj.html

TS:   `Hello, ${name}!`
来源：http://dali.smart0.xyz/Article/details/gtphtzijdf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtlngmhbnr.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhongyouzk.top/Article/details/gtdzckpbxi.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhiwuduotai.top/Article/details/gternzjkwh.html

C#:   $"Hello, {name}!"
来源：http://dali.cucudq.cn/Article/details/gtstfxrscb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.guowangkeji.top/Article/details/gtvseznkxe.html

Py:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtsfuyjgdw.html

PHP:  "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtocampamy.html

JS:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtqukljgbr.html

TS:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtsgzepaas.html

Java: "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtoyjavfhp.html

Go:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtrpzsotzi.html

Ruby: "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gthmsehtfq.html

C#:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtxsnmzjlq.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gtmtuprgyr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhoulong.xyz/Article/details/gtsbjwyhsu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gtjmwhaaxq.html

JS:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gttqfzbhkm.html

TS:   // 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gtohvqycuy.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xylfe.cn/Article/details/gtgdtnqway.html

Go:   // 单行；/* 多行 */
来源：http://dali.redwolf501.top/Article/details/gtnxnavvly.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ppjwa.cn/Article/details/gtvvnyzxsa.html

C#:   // 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvprynhh.html

[A15] 空值判断与默认值
来源：http://dali.zycfv.cn/Article/details/gtdjqtabiv.html

Py:   value = data or "默认值"
来源：http://dali.cqqwz.cn/Article/details/gtmliqpgtm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gtpwdembdf.html


<!-- 参考信息 -->