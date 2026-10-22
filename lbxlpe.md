代发 wailian999

[U89] JS：数组去重
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqrctfkp.html

[...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2aumkvaht.html

[U90] JS：数字数组排序
来源：http://dali.daxiang520.top/Article/details/gt2pbgwlyva.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gt2qcrsnliu.html

[U91] JS：对象键值遍历
来源：http://dali.svipenyu.cn/Article/details/gt2khbdazsa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cucudq.cn/Article/details/gt2ehygljtb.html

[U92] JS：深拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwryfrzq.html

structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2rjbdxsif.html

[U93] JS：模板字符串
来源：http://dali.jqgfzy.top/Article/details/gt2obyoouzk.html

`共 ${n} 条`
来源：http://dali.hnqzz.top/Article/details/gt2obvwrcmn.html

[U94] JS：箭头函数
来源：http://dali.daria6918.cn/Article/details/gt2uxpdobnv.html

const double = x => x * 2;
来源：http://dali.yj202588.top/Article/details/gt2chsttlhd.html

[U95] JS：Promise 包装
来源：http://dali.yanxiufei.cn/Article/details/gt2ztrvnjtm.html

new Promise((resolve, reject) => {})
来源：http://dali.cashguo.top/Article/details/gt2unxbpsbe.html

[U96] JS：async/await 与异常
来源：http://dali.hfpthk.cn/Article/details/gt2yktpcdif.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2jsulxxwa.html

[U97] JS：并发请求
来源：http://dali.iojbl.cn/Article/details/gt2niybvgpl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2cjvliynq.html

[U98] JS：fetch 带 JSON
来源：http://dali.gogol.net.cn/Article/details/gt2jzzoznui.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.mhx1999.top/Article/details/gt2dycyxqdq.html

[U99] JS：事件监听
来源：http://dali.xuanzx.com/Article/details/gt2jxyvuejo.html

el.addEventListener("click", e => {})
来源：http://dali.tianlin.xyz/Article/details/gt2kilbskno.html

[U100] JS：DOM 查询
来源：http://dali.zhongyouzk.top/Article/details/gt2rzkdczbr.html

document.querySelector(".item")
来源：http://dali.fzhhl.top/Article/details/gt2zypuufnd.html

[U101] JS：classList 操作
来源：http://dali.mhx1999.top/Article/details/gt2myiukiji.html

el.classList.toggle("active")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cexbjvtd.html

[U102] JS：本地存储
来源：http://dali.hfpthk.cn/Article/details/gt2mqaqcmvx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yangfankeji.com/Article/details/gt2fijweogf.html

[U103] JS：定时器
来源：http://dali.sysykeji.top/Article/details/gt2ryduyiew.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nwbrower.top/Article/details/gt2tbcxnvse.html

[U104] JS：防抖
来源：http://dali.ppjwa.cn/Article/details/gt2gngcawsd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gt2fwrbhjud.html

[U105] JS：节流
来源：http://dali.hywenlv.cn/Article/details/gt2ktwandwc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.c1oappe.top/Article/details/gt2xfamupac.html

[U106] JS：日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxetcoas.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aizwys.cn/Article/details/gt2dolcljym.html

[U107] JS：数字千分位
来源：http://dali.ppjwa.cn/Article/details/gt2lvkuobah.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gt2budwntsf.html

[U108] JS：随机整数
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzpxemma.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fzhhl.top/Article/details/gt2vbziyfgc.html

[U109] JS：数组分组
来源：http://dali.nanxinkj.top/Article/details/gt2cirqvtsr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gt2ytkfstur.html

[U110] JS：数组分块
来源：http://dali.daria6918.cn/Article/details/gt2ewwhfhui.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gogol.net.cn/Article/details/gt2tjkdoniv.html

[U111] JS：对象转 Map
来源：http://dali.chenlongwang.top/Article/details/gt2jxbrrpzr.html

new Map(Object.entries(obj))
来源：http://dali.birdmap.top/Article/details/gt2bsskxion.html

[U112] JS：字符串补位
来源：http://dali.zhengqikj.top/Article/details/gt2jutjkzbj.html

"7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2pyelxbmk.html

[U113] JS：正则替换全部
来源：http://dali.cdnleiting.top/Article/details/gt2eqqgdztu.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldofvzzx.html

[U114] JS：JSON 深比较
来源：http://dali.xuanzx.com/Article/details/gt2ijqcfoap.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gt2afpkjsct.html

[U115] JS：生成 UUID
来源：http://dali.daria6918.cn/Article/details/gt2uvzecocz.html

crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gt2yansgvrd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhiwuduotai.top/Article/details/gt2csobyjyd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jiagoushi.top/Article/details/gt2tftazrox.html

[U117] JS：单元测试
来源：http://dali.yuxming.cn/Article/details/gt2osdvpdss.html

npm i -D vitest;  npx vitest
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sdbhwtez.html

[U118] JS：开发服务器
来源：http://dali.iojbl.cn/Article/details/gt2uayxinra.html

npm i -D vite;  npx vite
来源：http://dali.kuanghao11.cn/Article/details/gt2hhekglsc.html

[U119] JS：生产构建
来源：http://dali.sysykeji.top/Article/details/gt2pjzktaxs.html

npx vite build
来源：http://dali.yonumen.top/Article/details/gt2dntvcuna.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgufenzy.top/Article/details/gt2jwoxyxng.html

import.meta.env.VITE_API_URL
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcfclarr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2jbfctrvq.html

统计汇总
来源：http://dali.bjfxy.top/Article/details/gt2frmfazrm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2sgrdtfgt.html

按语言统计（条）：
来源：http://dali.yanxiufei.cn/Article/details/gt2ejqxguth.html

Python ......... 252
来源：http://dali.hywenlv.cn/Article/details/gt2jepwnjmv.html

PHP ............ 252
来源：http://dali.gaohongyu789.top/Article/details/gt2sscdoexu.html

JavaScript ..... 252
来源：http://dali.xuanzx.com/Article/details/gt2vqmgqvix.html

TypeScript ..... 212
来源：http://dali.jianghu66.top/Article/details/gt2fbxkvzja.html

Java ........... 212
来源：http://dali.meibo888.top/Article/details/gt2cgkiosur.html

Go ............. 212
来源：http://dali.andypj.xyz/Article/details/gt2uyzitede.html

Ruby ........... 212
来源：http://dali.shuidangran.top/Article/details/gt2nvgshspb.html

C# ............. 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjztglnt.html

C .............. 30
来源：http://dali.hammf.cn/Article/details/gt2flxlhtzh.html

C++ ............ 30
来源：http://dali.hysaishi.cn/Article/details/gt2vzovtpbs.html

SQL ............ 90
来源：http://dali.yonumen.top/Article/details/gt2ektbnugs.html

Bash ........... 80
来源：http://dali.yj20258888.top/Article/details/gt2lhalxfgr.html

Kotlin ......... 15
来源：http://dali.ehwqpu.com/Article/details/gt2tqpevcdj.html

Swift .......... 15
来源：http://dali.hammf.cn/Article/details/gt2vhpratin.html

Lua ............ 10
来源：http://dali.ybcxt.top/Article/details/gt2doqhezup.html

Perl ........... 10
来源：http://dali.zhengqikj.top/Article/details/gt2alncxfih.html

Scala .......... 10
来源：http://dali.hammf.cn/Article/details/gt2vqthbunw.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2zqtlthqk.html

合计 ........... 2106 条
来源：http://dali.dianchejie.cn/Article/details/gt2imnjxhqd.html

按章节统计：
来源：http://dali.zhengqikj.top/Article/details/gt2wxlzuopf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhmaamzn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gt2dbrscree.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2nzisurio.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdltaeep.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sufxvd.cn/Article/details/gt2ousbazvd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.kuanghao11.cn/Article/details/gt2thravznz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gt2oddadqqr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gt2gqsglxpv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2twnbezpf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gt2zlozahdj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2iqyewapc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2skhoidku.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gt2qpjfrqid.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gt2xzyfuvjy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvxukwx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2xzosrmyd.html

Q SQL 专题                              90
来源：http://dali.tianlin.xyz/Article/details/gt2mhsovlri.html

R Bash 专题                             80
来源：http://dali.9152youxi.cn/Article/details/gt2cqpofwlx.html

S C / C++ 专题                          60
来源：http://dali.hnqzz.top/Article/details/gt2krpfqmsc.html

T 其他语言补充                          60
来源：http://dali.zhoulong.xyz/Article/details/gt2ljchjilh.html

U 高频实用片段                         120
来源：http://dali.guannengcc.top/Article/details/gt2qmjyhsce.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gt2enuthjed.html

合计                                  2106 条
来源：http://dali.guowangkeji.top/Article/details/gt2qtwzbwnh.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gt2ssxbovpz.html

使用提醒
来源：http://dali.aibaodan.cn/Article/details/gt2ddenzddt.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2lxtlorcy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sxryk.cn/Article/details/gt2mworqbgm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yonumen.top/Article/details/gt2smxsylni.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuanzx.com/Article/details/gt2hijctlpr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sysykeji.top/Article/details/gt2otjxidwd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cdnleiting.top/Article/details/gt2exioykee.html

—— 文件结束 ——
来源：http://dali.yj20258888.top/Article/details/gt2luiygvxx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2pkvyeebo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cashguo.top/Article/details/gt2mttarajt.html

Common Programming Examples Cheat Book
来源：http://dali.zycfv.cn/Article/details/gt2ifwdxcam.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2kziezdem.html

【收录内容】
来源：http://dali.tian-w.cn/Article/details/gt2kqfgvqnh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ooxvljrg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj20258888.top/Article/details/gt2whtllsom.html

SQL · Bash · C · C++
来源：http://dali.jiagoushi.top/Article/details/gt2yhieiblt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.meibo888.top/Article/details/gt2lpbakezd.html

【使用说明】
来源：http://dali.cashguo.top/Article/details/gt2bjpybuul.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258888.top/Article/details/gt2oyddvfts.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.316326.xyz/Article/details/gt2asjuntdk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.daria6918.cn/Article/details/gt2xsqtedvc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tanke756.top/Article/details/gt2bjvhkeex.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gaohongyu789.top/Article/details/gt2syndxwth.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daria6918.cn/Article/details/gt2bcxchtxk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ybcxt.top/Article/details/gt2tbikftde.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yangfankeji.com/Article/details/gt2qnudroaf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinqigufen.top/Article/details/gt2kvayhvlx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yangfankeji.com/Article/details/gt2umyeoave.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenlongwang.top/Article/details/gt2oorqefuq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gaohongyu789.top/Article/details/gt2kgpvbhbp.html

【文件统计】
来源：http://dali.xziqi.cn/Article/details/gt2xrodqbwo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zavalyqm.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2qpbcyitx.html

目  录
来源：http://dali.zhengqikj.top/Article/details/gt2koxtsfmj.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2ufyhefvk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gt2vbpwmgag.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gt2ehmjqnez.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gt2bbphnacx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2jtnlxviu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.mhx1999.top/Article/details/gt2eowkbear.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sufxvd.cn/Article/details/gt2dlejqagi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jiagoushi.top/Article/details/gt2bmcprthh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2eacekvmk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gt2ojvczplu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.meibo888.top/Article/details/gt2mryainwv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gt2opdhywim.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gt2dqyncghh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gt2cgzlyrvy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yongpay.top/Article/details/gt2qorywdxm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj20258888.top/Article/details/gt2ouawfdhc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gt2ntvmvsdx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.redwolf501.top/Article/details/gt2ogamdduu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcdentdu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shzxlz.cn/Article/details/gt2sdkpqwdl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gt2jfodoqab.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwpnmmit.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2xqxdvynf.html

A. 基础语法与类型
来源：http://dali.0kj1m.cn/Article/details/gt2dqvlxwbc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjsinisj.html

[A01] Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2wnhgwnvu.html

Py:   print("Hello, World!")
来源：http://dali.hnxiangtu.top/Article/details/gt2mqappekb.html

PHP:  echo "Hello, World!";
来源：http://dali.jiagoushi.top/Article/details/gt2seijjnsr.html

JS:   console.log("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gt2rvatnknq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrbotszc.html

Java: System.out.println("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gt2nncwbpyr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gogol.net.cn/Article/details/gt2jyrrftbf.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gt2znkxhjjr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gt2mtxhaabm.html

[A02] 变量声明与赋值
来源：http://dali.guannengcc.top/Article/details/gt2iwapllde.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sufxvd.cn/Article/details/gt2zkmlbetq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gt2jjpotjrp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ydzc1.top/Article/details/gt2vnwvxufo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hywenlv.cn/Article/details/gt2zqfcslhn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sufxvd.cn/Article/details/gt2tktzsrqo.html

Go:   name := "Alex"; age := 20
来源：http://dali.cdnleiting.top/Article/details/gt2ifwqaeol.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinqigfzy.top/Article/details/gt2jqeqttrc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gt2gepdhite.html

[A03] 常量定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcmygqin.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnycmfv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2caocvshk.html

JS:   const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2onbyybjc.html

TS:   const PI: number = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2elbbqomi.html

Java: static final double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2ejkaxhue.html

Go:   const PI = 3.14159
来源：http://dali.jyoumei.cn/Article/details/gt2oauyjvbd.html

Ruby: PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gt2oixfmaan.html

C#:   const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2knfygscj.html

[A04] 判断变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjhoqlpq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gzhubu.top/Article/details/gt2wvovnaha.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.9152youxi.cn/Article/details/gt2avqcticq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.fengsongda.top/Article/details/gt2vqillehs.html

TS:   typeof x; x instanceof Date
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rssdfvze.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gogol.net.cn/Article/details/gt2yktqyjlp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ydzc1.top/Article/details/gt2bakdasro.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cucudq.cn/Article/details/gt2arsrmfgz.html

C#:   x.GetType().Name; x is int
来源：http://dali.mhx1999.top/Article/details/gt2dybaxkpd.html

[A05] 整数除法与取模
来源：http://dali.ydzc1.top/Article/details/gt2hupfuwsl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cqqwz.cn/Article/details/gt2cwggbkma.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvsimnvj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2gccsmmts.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gt2yrwozhlj.html

Java: 7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gt2vfujjerf.html

Go:   7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2avitanak.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2xixuiazd.html

C#:   7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2osihknlg.html

[A06] 字符串转数字
来源：http://dali.yj202588.top/Article/details/gt2etcxveyp.html

Py:   int("42"); float("3.14")
来源：http://dali.xziqi.cn/Article/details/gt2bqbxatdv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssalypgp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daxiang520.top/Article/details/gt2dnxgqqkh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xziqi.cn/Article/details/gt2duiunoyl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nanxinkj.top/Article/details/gt2dluabswb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.fzhhl.top/Article/details/gt2qoizpzai.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.c1oappe.top/Article/details/gt2hbljljzs.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gt2wfzqsozx.html

[A07] 数字转字符串
来源：http://dali.bjfxy.top/Article/details/gt2vpgbjclm.html

Py:   str(42)
来源：http://dali.nwbrower.top/Article/details/gt2ivzmnnne.html

PHP:  (string) 42; strval(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygjxkwfk.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bteddqhd.html

TS:   String(42)
来源：http://dali.quarkkingdee.top/Article/details/gt2xwhdxvvb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwyeiujw.html

Go:   strconv.Itoa(42)
来源：http://dali.meibo888.top/Article/details/gt2elnysmer.html

Ruby: 42.to_s
来源：http://dali.jlsjyb.cn/Article/details/gt2rtngrpce.html

C#:   42.ToString()
来源：http://dali.haohaochexian.top/Article/details/gt2wnsgxysg.html

[A08] 取整与四舍五入
来源：http://dali.jlsjyb.cn/Article/details/gt2jqyfnmmh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gt2jledtscw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ivvv.top/Article/details/gt2ctyxrkmf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gt2frfwbhja.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zdqjudy.top/Article/details/gt2pcemsmxp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmenxzde.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gt2qmhfbqcn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.svipenyu.cn/Article/details/gt2hiznlzud.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gt2rzgdpxde.html

[A09] 绝对值与最大最小值
来源：http://dali.zhixingplan.top/Article/details/gt2mfmjiynf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2vicgnczj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2ylobbzut.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2zdeqtzmc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sweek.top/Article/details/gt2tkookgqe.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2hwocyuvi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hammf.cn/Article/details/gt2uxogslyh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cashguo.top/Article/details/gt2oqbnjrph.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2zqwcbjft.html

[A10] 生成随机数
来源：http://dali.yueranfly.top/Article/details/gt2thalwpab.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yj20258.top/Article/details/gt2jmeffbdo.html

PHP:  random_int(1, 100);
来源：http://dali.tianlin.xyz/Article/details/gt2npemdkqy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hammf.cn/Article/details/gt2sggdlxhx.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhengqikj.top/Article/details/gt2dnfuidot.html

Java: new Random().nextInt(100) + 1
来源：http://dali.smart0.xyz/Article/details/gt2lxsufmqz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hfpthk.cn/Article/details/gt2crnjdyav.html

Ruby: rand(1..100)
来源：http://dali.cucudq.cn/Article/details/gt2vrbrcbmd.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhongyouzk.top/Article/details/gt2rcdqishx.html

[A11] 条件表达式（三元）
来源：http://dali.zhixingplan.top/Article/details/gt2dtmcvycd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shuidangran.top/Article/details/gt2opdakxiy.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gt2vlzrnlul.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gt2fdbgyaff.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gt2kdoexwgf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gt2pksnubap.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zycfv.cn/Article/details/gt2odhpchhl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gt2xnbqedpy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2zqrpwqom.html

[A12] 字符串插值 / 格式化
来源：http://dali.daria6918.cn/Article/details/gt2mjwnmilm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtgdczhs.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sweek.top/Article/details/gt2pgzmseng.html

JS:   `Hello, ${name}!`
来源：http://dali.zhoulong.xyz/Article/details/gt2maojamgw.html

TS:   `Hello, ${name}!`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxieyfcr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xziqi.cn/Article/details/gt2myqfhlcf.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenzaomai.com/Article/details/gt2ioregxaw.html

Ruby: "Hello, #{name}!"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ooitzeyu.html

C#:   $"Hello, {name}!"
来源：http://dali.nwbrower.top/Article/details/gt2rdiuhnhj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zycfv.cn/Article/details/gt2tsroofyo.html

Py:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gt2lhzxxxqj.html

PHP:  "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gt2jckbdayc.html

JS:   "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gt2lbsjgsrc.html

TS:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2vxnyutpw.html

Java: "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gt2ainzcuer.html

Go:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtxkvbzq.html

Ruby: "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gt2mmlntotc.html

C#:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gt2wtgrtpua.html

[A14] 注释写法
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmtgtxtv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yanxiufei.cn/Article/details/gt2edrrfrsm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gt2zhucwxco.html

JS:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gt2ubrnwglc.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gt2smktddwk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.316326.xyz/Article/details/gt2vgqcnjpl.html

Go:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gt2lglzthuz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sxryk.cn/Article/details/gt2gpxzlkdp.html

C#:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gt2tdpldtha.html

[A15] 空值判断与默认值
来源：http://dali.jyoumei.cn/Article/details/gt2ztejcmmi.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdhykap.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gt2jrssfsgu.html


<!-- 参考信息 -->