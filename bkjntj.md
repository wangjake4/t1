代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zycfv.cn/Article/details/gt2tytlrzif.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cucudq.cn/Article/details/gt2dbpkojey.html

[U92] JS：深拷贝
来源：http://dali.cashguo.top/Article/details/gt2qcoiepnq.html

structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2kfjodwcm.html

[U93] JS：模板字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2jzdhhsrm.html

`共 ${n} 条`
来源：http://dali.xuanzx.com/Article/details/gt2hgtqguuy.html

[U94] JS：箭头函数
来源：http://dali.yongpay.top/Article/details/gt2uaowjuwh.html

const double = x => x * 2;
来源：http://dali.hysaishi.cn/Article/details/gt2alkuzghd.html

[U95] JS：Promise 包装
来源：http://dali.andypj.xyz/Article/details/gt2uproeawi.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gt2vorgyznm.html

[U96] JS：async/await 与异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvbrniak.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2xyuyjcpi.html

[U97] JS：并发请求
来源：http://dali.hnxiangtu.top/Article/details/gt2atmuytnf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2tdprdizn.html

[U98] JS：fetch 带 JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2mmrokoqb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojkdatsg.html

[U99] JS：事件监听
来源：http://dali.jinqigfzy.top/Article/details/gt2vwpfdmyg.html

el.addEventListener("click", e => {})
来源：http://dali.sxryk.cn/Article/details/gt2glydfjkg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2feouejhw.html

document.querySelector(".item")
来源：http://dali.wangdashe.top/Article/details/gt2gkgqhazj.html

[U101] JS：classList 操作
来源：http://dali.sxryk.cn/Article/details/gt2xdcxwhoc.html

el.classList.toggle("active")
来源：http://dali.svipenyu.cn/Article/details/gt2nqbtcxjg.html

[U102] JS：本地存储
来源：http://dali.snrcjt.cn/Article/details/gt2merxqeuv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daria6918.cn/Article/details/gt2kqbbrfyv.html

[U103] JS：定时器
来源：http://dali.sxryk.cn/Article/details/gt2umnxkywv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jiagoushi.top/Article/details/gt2xaxgcobx.html

[U104] JS：防抖
来源：http://dali.cqqwz.cn/Article/details/gt2hondhqha.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bthphmum.html

[U105] JS：节流
来源：http://dali.yvedp.cn/Article/details/gt2lgbgrqjk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxwelhok.html

[U106] JS：日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2eabzeptm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.vqdsnc.cn/Article/details/gt2bdhvmuhp.html

[U107] JS：数字千分位
来源：http://dali.ppjwa.cn/Article/details/gt2mnalapxh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gt2whqztgja.html

[U108] JS：随机整数
来源：http://dali.birdmap.top/Article/details/gt2uqsffauz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yongpay.top/Article/details/gt2zqctgbqm.html

[U109] JS：数组分组
来源：http://dali.cdnleiting.top/Article/details/gt2gfhimcgj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gt2fygwdfow.html

[U110] JS：数组分块
来源：http://dali.dashuyun.cn/Article/details/gt2sicvoega.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2apbstoox.html

[U111] JS：对象转 Map
来源：http://dali.shzxlz.cn/Article/details/gt2iuawxsig.html

new Map(Object.entries(obj))
来源：http://dali.yvedp.cn/Article/details/gt2rlxhuelw.html

[U112] JS：字符串补位
来源：http://dali.cashguo.top/Article/details/gt2gkefbxaq.html

"7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2tyldehib.html

[U113] JS：正则替换全部
来源：http://dali.yj202588.top/Article/details/gt2erbtnhax.html

s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhfulagw.html

[U114] JS：JSON 深比较
来源：http://dali.tianlin.xyz/Article/details/gt2tseafavt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gt2xdovqxpy.html

[U115] JS：生成 UUID
来源：http://dali.shzxlz.cn/Article/details/gt2kxnhdwoa.html

crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gt2wldqicyg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jlsjyb.cn/Article/details/gt2txglvkmf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2flzmuykm.html

[U117] JS：单元测试
来源：http://dali.aibaodan.cn/Article/details/gt2isojgilf.html

npm i -D vitest;  npx vitest
来源：http://dali.jianghu66.top/Article/details/gt2hjxrobjo.html

[U118] JS：开发服务器
来源：http://dali.daria6918.cn/Article/details/gt2bupfpybb.html

npm i -D vite;  npx vite
来源：http://dali.nwbrower.top/Article/details/gt2mjniripk.html

[U119] JS：生产构建
来源：http://dali.yj20258.top/Article/details/gt2cjlhtxzj.html

npx vite build
来源：http://dali.nanxinkj.top/Article/details/gt2brkpysnc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ybcxt.top/Article/details/gt2brkvgcjk.html

import.meta.env.VITE_API_URL
来源：http://dali.cqqwz.cn/Article/details/gt2izjlphki.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2dqzuzbhf.html

统计汇总
来源：http://dali.zhoulong.xyz/Article/details/gt2nrhsnntn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2fhdhigpj.html

按语言统计（条）：
来源：http://dali.yanxiufei.cn/Article/details/gt2qzeokozw.html

Python ......... 252
来源：http://dali.chenzaomai.com/Article/details/gt2ekcpnewd.html

PHP ............ 252
来源：http://dali.hnqzz.top/Article/details/gt2owbslvpg.html

JavaScript ..... 252
来源：http://dali.daria6918.cn/Article/details/gt2pvfupdth.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idirvgku.html

Java ........... 212
来源：http://dali.yj202588.top/Article/details/gt2pakmdchi.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcxkgek.html

Ruby ........... 212
来源：http://dali.daria6918.cn/Article/details/gt2lpubvmie.html

C# ............. 212
来源：http://dali.hnqzz.top/Article/details/gt2tliritlg.html

C .............. 30
来源：http://dali.meibo888.top/Article/details/gt2rbuwkzdo.html

C++ ............ 30
来源：http://dali.zhiwuduotai.top/Article/details/gt2xiklenvg.html

SQL ............ 90
来源：http://dali.c1oappe.top/Article/details/gt2qnxxmswj.html

Bash ........... 80
来源：http://dali.chenlongwang.top/Article/details/gt2okhdmzxg.html

Kotlin ......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gt2tihjumcz.html

Swift .......... 15
来源：http://dali.jqgufenzy.top/Article/details/gt2eiljwmun.html

Lua ............ 10
来源：http://dali.xinyue.icu/Article/details/gt2thcstubn.html

Perl ........... 10
来源：http://dali.nanxuanxn.top/Article/details/gt2egotiuvc.html

Scala .......... 10
来源：http://dali.yuanzhike.top/Article/details/gt2mnrgvklm.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2pzvfvsdx.html

合计 ........... 2106 条
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrjuvcua.html

按章节统计：
来源：http://dali.aizwys.cn/Article/details/gt2yyndnukv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gt2jgyjkskf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gt2izfdbrfo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gt2ypgrvwkv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gt2azblkmnk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnxiangtu.top/Article/details/gt2pvfouvkl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gt2fjfaspez.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gt2ahwoafnf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gt2htqmsvzn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gt2jbysnuca.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ydzc1.top/Article/details/gt2qyjbxwyw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2jrrbwank.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gt2cctoxivy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjmwgcvt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.smart0.xyz/Article/details/gt2vfenxmuf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.vqdsnc.cn/Article/details/gt2ncvmfulx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2luxewumm.html

Q SQL 专题                              90
来源：http://dali.bjfxy.top/Article/details/gt2krdvbixm.html

R Bash 专题                             80
来源：http://dali.nanxuanxn.top/Article/details/gt2xmfyaywh.html

S C / C++ 专题                          60
来源：http://dali.xziqi.cn/Article/details/gt2pjmgurqy.html

T 其他语言补充                          60
来源：http://dali.zycfv.cn/Article/details/gt2atnaztij.html

U 高频实用片段                         120
来源：http://dali.yonumen.top/Article/details/gt2wckbafds.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gt2gwtbayap.html

合计                                  2106 条
来源：http://dali.jqgufenzy.top/Article/details/gt2tahyalqy.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2pqblgvon.html

使用提醒
来源：http://dali.yueranfly.top/Article/details/gt2xmgjajih.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2ttgodpdn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yvedp.cn/Article/details/gt2fnkrsasw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhrcdamo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ivvv.top/Article/details/gt2jrusdjaq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.316326.xyz/Article/details/gt2drcwtgfz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zdqjudy.top/Article/details/gt2freynqje.html

—— 文件结束 ——
来源：http://dali.hammf.cn/Article/details/gt2frtnphkf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2zhrmicel.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.haohaochexian.top/Article/details/gt2suvhtplo.html

Common Programming Examples Cheat Book
来源：http://dali.wangshuangyany.cn/Article/details/gt2rflipgik.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2uireogry.html

【收录内容】
来源：http://dali.fzhhl.top/Article/details/gt2xbkroshn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.0kj1m.cn/Article/details/gt2lvrcnoet.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.dashuyun.cn/Article/details/gt2xxprwjub.html

SQL · Bash · C · C++
来源：http://dali.sxryk.cn/Article/details/gt2jkesjrgv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jianghu66.top/Article/details/gt2xiutezmw.html

【使用说明】
来源：http://dali.yueranfly.top/Article/details/gt2kztxsdmx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yvedp.cn/Article/details/gt2yodftgzr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jlsjyb.cn/Article/details/gt2roigzfvr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sxryk.cn/Article/details/gt2czhysxbc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hnqzz.top/Article/details/gt2xssooiyj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cheryme.top/Article/details/gt2sceuhtui.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.kuanghao11.cn/Article/details/gt2cmclsvyc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yuxming.cn/Article/details/gt2wjsasmbu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenzaomai.com/Article/details/gt2qpmmqaeo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.mhx1999.top/Article/details/gt2veqwfowg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfrtmrsv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hongshengwenyu.top/Article/details/gt2fksqrvrw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.daria6918.cn/Article/details/gt2wmsmmcwy.html

【文件统计】
来源：http://dali.haohaochexian.top/Article/details/gt2oxraqsjs.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pycfn.com/Article/details/gt2oxugwwed.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2cgvclgtw.html

目  录
来源：http://dali.cucudq.cn/Article/details/gt2qfzohzag.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gt2bwkezwyk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hammf.cn/Article/details/gt2cnbcvzof.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gt2ikwckugy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gt2dmzkpirg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gt2mlppfdnh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ybcxt.top/Article/details/gt2lrqrlpsd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hnqzz.top/Article/details/gt2wreiyolo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gt2tmgonuow.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.dashuyun.cn/Article/details/gt2rannqfxf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gt2xquyxhoo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezjxagtf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gt2russkbco.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2gnrautpj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2xcnzuluj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jqgfzy.top/Article/details/gt2fmbzjydu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdjelodg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2cfiuxmul.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258888.top/Article/details/gt2ipsrsays.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nwbrower.top/Article/details/gt2cyretltd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenlongwang.top/Article/details/gt2kjtideuh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gt2ddvbwind.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2plktjuhn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2vdqzwsyf.html

A. 基础语法与类型
来源：http://dali.ivvv.top/Article/details/gt2rnzdeucu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulpwrqlw.html

[A01] Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2eefzmgfs.html

Py:   print("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gt2wfjkagro.html

PHP:  echo "Hello, World!";
来源：http://dali.yuxming.cn/Article/details/gt2bqkzolfc.html

JS:   console.log("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gt2polnqjoi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.c1oappe.top/Article/details/gt2pmsahjps.html

Java: System.out.println("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gt2txbmjwvk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj20258888.top/Article/details/gt2nvdytlbw.html

Ruby: puts "Hello, World!"
来源：http://dali.gotoacloud.top/Article/details/gt2cborkbkp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gt2chkgaumh.html

[A02] 变量声明与赋值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltxieycf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zycfv.cn/Article/details/gt2xtjoonts.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tian-w.cn/Article/details/gt2qxzcmjxt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gt2eijckoef.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuanzx.com/Article/details/gt2bmvqkeko.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.wangdashe.top/Article/details/gt2kayapifg.html

Go:   name := "Alex"; age := 20
来源：http://dali.aizwys.cn/Article/details/gt2myokgcwi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ivvv.top/Article/details/gt2bryiohdo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jyoumei.cn/Article/details/gt2kxjuufzc.html

[A03] 常量定义
来源：http://dali.gogol.net.cn/Article/details/gt2vtpyvbvx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdwiavis.html

PHP:  const PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2alwpeqrm.html

JS:   const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2hgoofrst.html

TS:   const PI: number = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2qbjmnjuf.html

Java: static final double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2suqxwhyc.html

Go:   const PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trberwfr.html

Ruby: PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gt2gcayjyfb.html

C#:   const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2iviiymvf.html

[A04] 判断变量类型
来源：http://dali.yvedp.cn/Article/details/gt2hcmsykqk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.birdmap.top/Article/details/gt2njoavktu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zycfv.cn/Article/details/gt2skjktogd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gt2vamvhlhs.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxinkj.top/Article/details/gt2kidcjmxs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tian-w.cn/Article/details/gt2cpqltxtq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqhosxpg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.bjfxy.top/Article/details/gt2bccgotxe.html

C#:   x.GetType().Name; x is int
来源：http://dali.cashguo.top/Article/details/gt2qpzhutwx.html

[A05] 整数除法与取模
来源：http://dali.redwolf501.top/Article/details/gt2wibapaag.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.meibo888.top/Article/details/gt2wbgkfcxj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gt2doviyzfb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gt2darheywk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gt2davwjrvw.html

Java: 7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gt2qdquyyrw.html

Go:   7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2cxvpswnl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gt2czqhspuw.html

C#:   7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gt2vmcminjj.html

[A06] 字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfyastch.html

Py:   int("42"); float("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mthqfzjg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yj20258888.top/Article/details/gt2mxyjynbs.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czeetdgl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ybcxt.top/Article/details/gt2cwqgeser.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj20258888.top/Article/details/gt2mqgdkpeg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.aizwys.cn/Article/details/gt2zxlxbecm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj20258888.top/Article/details/gt2kbvlvvcc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jiagoushi.top/Article/details/gt2txnvtlkv.html

[A07] 数字转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2njmbrqml.html

Py:   str(42)
来源：http://dali.tanke756.top/Article/details/gt2nqspuspe.html

PHP:  (string) 42; strval(42)
来源：http://dali.daria6918.cn/Article/details/gt2qoymtouh.html

JS:   String(42); (42).toString()
来源：http://dali.birdmap.top/Article/details/gt2gjgbtvfm.html

TS:   String(42)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnwfsvik.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yongpay.top/Article/details/gt2xidieuou.html

Go:   strconv.Itoa(42)
来源：http://dali.zhengqikj.top/Article/details/gt2xkfasxbn.html

Ruby: 42.to_s
来源：http://dali.tian-w.cn/Article/details/gt2ugqdciyc.html

C#:   42.ToString()
来源：http://dali.ybcxt.top/Article/details/gt2btebluis.html

[A08] 取整与四舍五入
来源：http://dali.gzhubu.top/Article/details/gt2hfhusril.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gt2wvoypxgc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.chenlongwang.top/Article/details/gt2ugyglixf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gt2qpyopqfd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhengqikj.top/Article/details/gt2lallucto.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gt2apgwvsdb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gt2cajjocpl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigfzy.top/Article/details/gt2dvoiuwrr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gt2rlabqifq.html

[A09] 绝对值与最大最小值
来源：http://dali.jqgfzy.top/Article/details/gt2ofpwnrbg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xinyue.icu/Article/details/gt2mosgagxp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2zjiodnnw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2lmifiodg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2pgktttab.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2kwabzogz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jinqigfzy.top/Article/details/gt2ebxtnkcl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jlsjyb.cn/Article/details/gt2sirecxfd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cucudq.cn/Article/details/gt2smqiecur.html

[A10] 生成随机数
来源：http://dali.cucudq.cn/Article/details/gt2jpauveim.html

Py:   import random; random.randint(1, 100)
来源：http://dali.haohaochexian.top/Article/details/gt2gwfflhii.html

PHP:  random_int(1, 100);
来源：http://dali.dashuyun.cn/Article/details/gt2aaiashxq.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.snrcjt.cn/Article/details/gt2quxbpany.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxinkj.top/Article/details/gt2pbryljuq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hnxiangtu.top/Article/details/gt2tniziuvw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jianghu66.top/Article/details/gt2rlatcsly.html

Ruby: rand(1..100)
来源：http://dali.jinqigfzy.top/Article/details/gt2eoyahwgt.html

C#:   new Random().Next(1, 101)
来源：http://dali.xuanzx.com/Article/details/gt2rzcseqxk.html

[A11] 条件表达式（三元）
来源：http://dali.yonumen.top/Article/details/gt2npjfzmuh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhengqikj.top/Article/details/gt2tqoyfbyg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gt2eqtvayah.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gt2odgrtdcc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gt2bhqnypwm.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gt2bthqfauh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.fengsongda.top/Article/details/gt2bcjjzvuu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mkltyelt.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gt2fqjykwvo.html

[A12] 字符串插值 / 格式化
来源：http://dali.bjfxy.top/Article/details/gt2wquokfff.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhoulong.xyz/Article/details/gt2okgcghcp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinqigufen.top/Article/details/gt2mpxifkkm.html

JS:   `Hello, ${name}!`
来源：http://dali.gzhubu.top/Article/details/gt2jkvfxvhm.html

TS:   `Hello, ${name}!`
来源：http://dali.9152youxi.cn/Article/details/gt2enuwwzwi.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sweek.top/Article/details/gt2onmohjag.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2fegzzgow.html

Ruby: "Hello, #{name}!"
来源：http://dali.shzxlz.cn/Article/details/gt2qdrkovso.html

C#:   $"Hello, {name}!"
来源：http://dali.guowangkeji.top/Article/details/gt2pwgnziwn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hfpthk.cn/Article/details/gt2eiwrbukw.html

Py:   "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gt2azsfudwf.html

PHP:  "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gt2weuhgxtk.html

JS:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gt2waerottz.html

TS:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gt2wawwpyeh.html

Java: "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gt2vmbcvltc.html

Go:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gt2oqhghrfn.html

Ruby: "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2ybjeaszv.html

C#:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gt2omvrmtps.html

[A14] 注释写法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlabucxz.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqifecbg.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gt2jmmxpmoe.html

JS:   // 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uterkwhb.html

TS:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gt2rrccjodg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yj20258.top/Article/details/gt2irxrpjgu.html

Go:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gt2omfayial.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.svipenyu.cn/Article/details/gt2btwfcopw.html

C#:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gt2wdvjfosx.html

[A15] 空值判断与默认值
来源：http://dali.zhoulong.xyz/Article/details/gt2ojnznmrs.html

Py:   value = data or "默认值"
来源：http://dali.ivvv.top/Article/details/gt2dcryibme.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.havefunace.top/Article/details/gt2ibwwxfkc.html

JS:   const value = data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gt2fkimbmbf.html

TS:   const value = data ?? "默认值";
来源：http://dali.sxryk.cn/Article/details/gt2yyvfqgxc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.redwolf501.top/Article/details/gt2yftmmgbg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yuxming.cn/Article/details/gt2hgnqloht.html


<!-- 参考信息 -->