代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.aizwys.cn/Article/details/gt2kizgotis.html

new Promise((resolve, reject) => {})
来源：http://dali.aibaodan.cn/Article/details/gt2tfzcraai.html

[U96] JS：async/await 与异常
来源：http://dali.shuidangran.top/Article/details/gt2fuvnzzjd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2glijtjyu.html

[U97] JS：并发请求
来源：http://dali.yuxming.cn/Article/details/gt2gaetezjh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2plgcsdea.html

[U98] JS：fetch 带 JSON
来源：http://dali.gzhubu.top/Article/details/gt2oprbpjuk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzzmprzi.html

[U99] JS：事件监听
来源：http://dali.zdqjudy.top/Article/details/gt2jbwbjbhl.html

el.addEventListener("click", e => {})
来源：http://dali.yuxming.cn/Article/details/gt2anwqzdam.html

[U100] JS：DOM 查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2konxfiqk.html

document.querySelector(".item")
来源：http://dali.xziqi.cn/Article/details/gt2sbgitpai.html

[U101] JS：classList 操作
来源：http://dali.xuanzx.com/Article/details/gt2iiczuiru.html

el.classList.toggle("active")
来源：http://dali.redwolf501.top/Article/details/gt2watyipnb.html

[U102] JS：本地存储
来源：http://dali.ivvv.top/Article/details/gt2kwywtxkm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhengqikj.top/Article/details/gt2ahmuscqs.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gt2gdhosfct.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uexwmkca.html

[U104] JS：防抖
来源：http://dali.mhx1999.top/Article/details/gt2hdxvawdi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gt2qqqvhzax.html

[U105] JS：节流
来源：http://dali.iojbl.cn/Article/details/gt2yresvnsh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hysaishi.cn/Article/details/gt2afylzcva.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxiieew.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jyoumei.cn/Article/details/gt2tglgrrmb.html

[U107] JS：数字千分位
来源：http://dali.sufxvd.cn/Article/details/gt2bkqacpbx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gt2xrsegmul.html

[U108] JS：随机整数
来源：http://dali.yj202588.top/Article/details/gt2cjvomddp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fengsongda.top/Article/details/gt2gibikmxh.html

[U109] JS：数组分组
来源：http://dali.ivvv.top/Article/details/gt2hboobeof.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gt2dcyrhatl.html

[U110] JS：数组分块
来源：http://dali.ivvv.top/Article/details/gt2vfcdknzi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnxiangtu.top/Article/details/gt2pjhnllul.html

[U111] JS：对象转 Map
来源：http://dali.tanke756.top/Article/details/gt2ztrxmtla.html

new Map(Object.entries(obj))
来源：http://dali.cqqwz.cn/Article/details/gt2dszpnume.html

[U112] JS：字符串补位
来源：http://dali.mhx1999.top/Article/details/gt2gddlkbae.html

"7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2wkeydlsz.html

[U113] JS：正则替换全部
来源：http://dali.jinqigfzy.top/Article/details/gt2ivewjwyp.html

s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2dssqqljz.html

[U114] JS：JSON 深比较
来源：http://dali.jyoumei.cn/Article/details/gt2zqwugsvm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gt2xrnhukfk.html

[U115] JS：生成 UUID
来源：http://dali.sweek.top/Article/details/gt2brokpaxs.html

crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdrfnndc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenzaomai.com/Article/details/gt2pixlavlz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uebikdsq.html

[U117] JS：单元测试
来源：http://dali.yuanzhike.top/Article/details/gt2tbkhtcqs.html

npm i -D vitest;  npx vitest
来源：http://dali.yuanzhike.top/Article/details/gt2ixpdnipr.html

[U118] JS：开发服务器
来源：http://dali.redwolf501.top/Article/details/gt2gopaclxj.html

npm i -D vite;  npx vite
来源：http://dali.yueranfly.top/Article/details/gt2xdtdvjcq.html

[U119] JS：生产构建
来源：http://dali.hfpthk.cn/Article/details/gt2mittbkhw.html

npx vite build
来源：http://dali.aizwys.cn/Article/details/gt2rqxejiaz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhixingplan.top/Article/details/gt2yycjprlz.html

import.meta.env.VITE_API_URL
来源：http://dali.hysaishi.cn/Article/details/gt2acdxbvso.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ypumyleg.html

统计汇总
来源：http://dali.zhongyouzk.top/Article/details/gt2ekhsvvel.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2jahyxxcv.html

按语言统计（条）：
来源：http://dali.dianchejie.cn/Article/details/gt2zydwcqhg.html

Python ......... 252
来源：http://dali.yuxming.cn/Article/details/gt2icvkczbs.html

PHP ............ 252
来源：http://dali.wangshuangyany.cn/Article/details/gt2slasfhqv.html

JavaScript ..... 252
来源：http://dali.svipenyu.cn/Article/details/gt2faxvxymh.html

TypeScript ..... 212
来源：http://dali.zycfv.cn/Article/details/gt2nigftjhy.html

Java ........... 212
来源：http://dali.dashuyun.cn/Article/details/gt2nsnkjoys.html

Go ............. 212
来源：http://dali.daria6918.cn/Article/details/gt2mygkjnpl.html

Ruby ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2weqjrgny.html

C# ............. 212
来源：http://dali.yongpay.top/Article/details/gt2fdmrzjst.html

C .............. 30
来源：http://dali.chenlongwang.top/Article/details/gt2prfwevyw.html

C++ ............ 30
来源：http://dali.gogol.net.cn/Article/details/gt2fxbkedhb.html

SQL ............ 90
来源：http://dali.zycfv.cn/Article/details/gt2xdgurtqs.html

Bash ........... 80
来源：http://dali.cucudq.cn/Article/details/gt2xwbyrsyb.html

Kotlin ......... 15
来源：http://dali.guowangkeji.top/Article/details/gt2yxdrovrt.html

Swift .......... 15
来源：http://dali.zhoulong.xyz/Article/details/gt2aemygfef.html

Lua ............ 10
来源：http://dali.hfpthk.cn/Article/details/gt2mytbjpcy.html

Perl ........... 10
来源：http://dali.ppjwa.cn/Article/details/gt2axpsdggz.html

Scala .......... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlymwlew.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gt2ijshzmbu.html

合计 ........... 2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owkxznda.html

按章节统计：
来源：http://dali.yuanzhike.top/Article/details/gt2irozsvrf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xziqi.cn/Article/details/gt2tqvlymre.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gt2cjlvmtrp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gt2biutplre.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gt2fvatsxyx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenjidiqi.icu/Article/details/gt2kdcmjfru.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gt2hsnxtlhs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oazvtrsu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ormuuskb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2lxrpgjns.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gt2afgwjpbo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gt2klvztljx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gt2thwzxata.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gt2eempjnnt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdzwihfn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gzhubu.top/Article/details/gt2eczzivgn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2sfcpjfgo.html

Q SQL 专题                              90
来源：http://dali.hywenlv.cn/Article/details/gt2fyfpepts.html

R Bash 专题                             80
来源：http://dali.tian-w.cn/Article/details/gt2yagfvxns.html

S C / C++ 专题                          60
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfcukhfi.html

T 其他语言补充                          60
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubgdwtee.html

U 高频实用片段                         120
来源：http://dali.gogol.net.cn/Article/details/gt2qyofwcao.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2woovcekh.html

合计                                  2106 条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsuigxlz.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjdfhbzr.html

使用提醒
来源：http://dali.yj20258.top/Article/details/gt2tpmdpicv.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gt2vbzjsybs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxuanxn.top/Article/details/gt2fkobiajk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daria6918.cn/Article/details/gt2yrkiohcc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shangyingyoupin.top/Article/details/gt2vsbwysch.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yangfankeji.com/Article/details/gt2tqqztxmr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jyoumei.cn/Article/details/gt2wmbxtxrh.html

—— 文件结束 ——
来源：http://dali.guowangkeji.top/Article/details/gt2pshdfrci.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2drtdgnww.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyfodlmg.html

Common Programming Examples Cheat Book
来源：http://dali.gaohongyu789.top/Article/details/gt2hyuycgfh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2uvcupihk.html

【收录内容】
来源：http://dali.nanxuanxn.top/Article/details/gt2rqfnzdel.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yanxiufei.cn/Article/details/gt2ysaexouc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gotoacloud.top/Article/details/gt2ijnvjfmu.html

SQL · Bash · C · C++
来源：http://dali.jianghu66.top/Article/details/gt2cqhzolya.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yanxiufei.cn/Article/details/gt2uwdketgj.html

【使用说明】
来源：http://dali.yonumen.top/Article/details/gt2ibhlztyv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tanke756.top/Article/details/gt2ntbwkgch.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shzxlz.cn/Article/details/gt2qcmrgwhj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgufenzy.top/Article/details/gt2kwplvdwe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjahadfr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.feifeiyinyue.top/Article/details/gt2ketqubiv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ydzc1.top/Article/details/gt2uunsbjiu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ybcxt.top/Article/details/gt2ievmrrnt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmryzmfi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgufenzy.top/Article/details/gt2evafogyl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhixingplan.top/Article/details/gt2vfvlgfnm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gogol.net.cn/Article/details/gt2isxabhan.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cucudq.cn/Article/details/gt2xhmfdqzm.html

【文件统计】
来源：http://dali.zdqjudy.top/Article/details/gt2vxsxshor.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenzaomai.com/Article/details/gt2ygznqntw.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gt2nffraawb.html

目  录
来源：http://dali.snrcjt.cn/Article/details/gt2zecqxeek.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gt2mlsxcoew.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbcgxgwq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gt2smbvzdtd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxsxtyvy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gt2xixsdfhk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jqgfzy.top/Article/details/gt2xryabars.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gt2azfrpgdv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxlzkmzt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sysykeji.top/Article/details/gt2xaqzyvst.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gt2nrwvwlwn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2xuycjryg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gt2gpjtuwky.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gt2weuktfjg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2xbjlsacw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xziqi.cn/Article/details/gt2elqekbpw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2wtohirkc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gt2fpjvdocm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xuanzx.com/Article/details/gt2bkuqmdss.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cqqwz.cn/Article/details/gt2mukrgqur.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cdnleiting.top/Article/details/gt2jtmxqwsn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gt2qseuejql.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2khkegrhm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ckpkgxib.html

A. 基础语法与类型
来源：http://dali.dianchejie.cn/Article/details/gt2vovdzisu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2gssapamh.html

[A01] Hello World
来源：http://dali.nwbrower.top/Article/details/gt2jjifeohy.html

Py:   print("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjnltiix.html

PHP:  echo "Hello, World!";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psxzdzix.html

JS:   console.log("Hello, World!");
来源：http://dali.gotoacloud.top/Article/details/gt2rafljmlg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shzxlz.cn/Article/details/gt2tmftxova.html

Java: System.out.println("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gt2bspxuxcf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hfpthk.cn/Article/details/gt2szylisys.html

Ruby: puts "Hello, World!"
来源：http://dali.shzxlz.cn/Article/details/gt2saohliob.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gt2tqqhxcju.html

[A02] 变量声明与赋值
来源：http://dali.zhengqikj.top/Article/details/gt2dvffcrmz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ppjwa.cn/Article/details/gt2qjhawkzu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zuencnsu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.tian-w.cn/Article/details/gt2miqbcotc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jqgufenzy.top/Article/details/gt2angdrizt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gt2osfxzdwv.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinqigufen.top/Article/details/gt2tvaqpfda.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nanxuanxn.top/Article/details/gt2lnbcslai.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.guannengcc.top/Article/details/gt2lzwwingw.html

[A03] 常量定义
来源：http://dali.hnqzz.top/Article/details/gt2ylqazime.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zycfv.cn/Article/details/gt2etwsincl.html

PHP:  const PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2krelmfmp.html

JS:   const PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2aqilejoa.html

TS:   const PI: number = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2khpxbtnd.html

Java: static final double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2irzhizwc.html

Go:   const PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gt2anvsrkxb.html

Ruby: PI = 3.14159
来源：http://dali.gotoacloud.top/Article/details/gt2lfcncvjd.html

C#:   const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2tvgcsmgv.html

[A04] 判断变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ueelciry.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.kuanghao11.cn/Article/details/gt2qiqdhjdp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuxming.cn/Article/details/gt2xosetrbo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.nanxuanxn.top/Article/details/gt2fvmqqkpy.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhoulong.xyz/Article/details/gt2vcnvvizy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tianlin.xyz/Article/details/gt2togxjhfb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnxiangtu.top/Article/details/gt2gqztqiby.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.tianlin.xyz/Article/details/gt2djkohpnd.html

C#:   x.GetType().Name; x is int
来源：http://dali.snrcjt.cn/Article/details/gt2btmvboau.html

[A05] 整数除法与取模
来源：http://dali.ehwqpu.com/Article/details/gt2bnktwzoz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cdnleiting.top/Article/details/gt2blyyvzyn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2xhzyflzs.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2muqhompf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2zvncplmz.html

Java: 7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gt2rhlhzwde.html

Go:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2ncrnrpad.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gt2airpfaod.html

C#:   7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gt2vbiisjog.html

[A06] 字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gt2hmqopcki.html

Py:   int("42"); float("3.14")
来源：http://dali.gotoacloud.top/Article/details/gt2zptfnqjz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sxryk.cn/Article/details/gt2bdymzfwt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yonumen.top/Article/details/gt2wbtcouzt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yangfankeji.com/Article/details/gt2napsusvo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ppjwa.cn/Article/details/gt2ayvhfmwv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jqgufenzy.top/Article/details/gt2gbtrijrb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.bjfxy.top/Article/details/gt2qhhkxgvg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.aibaodan.cn/Article/details/gt2sdwpfuez.html

[A07] 数字转字符串
来源：http://dali.sysykeji.top/Article/details/gt2nqfnvvak.html

Py:   str(42)
来源：http://dali.yuanzhike.top/Article/details/gt2yziwplwe.html

PHP:  (string) 42; strval(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trwmueaf.html

JS:   String(42); (42).toString()
来源：http://dali.xinyue.icu/Article/details/gt2gnefnnel.html

TS:   String(42)
来源：http://dali.fzhhl.top/Article/details/gt2npygkwzz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.andypj.xyz/Article/details/gt2mrrkveqb.html

Go:   strconv.Itoa(42)
来源：http://dali.hywenlv.cn/Article/details/gt2puwajuyd.html

Ruby: 42.to_s
来源：http://dali.shzxlz.cn/Article/details/gt2urmjfxwe.html

C#:   42.ToString()
来源：http://dali.aizwys.cn/Article/details/gt2ardqkefg.html

[A08] 取整与四舍五入
来源：http://dali.sufxvd.cn/Article/details/gt2suplhfho.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjspdxbj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinqigfzy.top/Article/details/gt2pjdgyxxn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gt2ibavjzof.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hnqzz.top/Article/details/gt2xibvgpkv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gt2joqeskpq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqmcnnyx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhengqikj.top/Article/details/gt2fduzpehk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gt2osinvori.html

[A09] 绝对值与最大最小值
来源：http://dali.ydzc1.top/Article/details/gt2mzyttwjw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2iomuscnb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygrhfubk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.bjfxy.top/Article/details/gt2odlsgdtb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2gsgibasj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zycfv.cn/Article/details/gt2txknfpdf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.pycfn.com/Article/details/gt2nkytoyhk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ergvwufi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2njebslzi.html

[A10] 生成随机数
来源：http://dali.yvedp.cn/Article/details/gt2uhimwkgq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.daria6918.cn/Article/details/gt2cgugopde.html

PHP:  random_int(1, 100);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gduyfhps.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.daria6918.cn/Article/details/gt2aaznburl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gaohongyu789.top/Article/details/gt2koptahyk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hddilfcv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yvedp.cn/Article/details/gt2drbmkrpt.html

Ruby: rand(1..100)
来源：http://dali.yanxiufei.cn/Article/details/gt2lsbjmhih.html

C#:   new Random().Next(1, 101)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdsrnzqx.html

[A11] 条件表达式（三元）
来源：http://dali.cheryme.top/Article/details/gt2ejancmee.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jqgfzy.top/Article/details/gt2whaoqlra.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gt2xjqfdyat.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ybcxt.top/Article/details/gt2qwxynxik.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gt2tasvkuly.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gt2ufexljsx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.svipenyu.cn/Article/details/gt2otaitjur.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gt2fntxrmpr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gt2bduehmci.html

[A12] 字符串插值 / 格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2luegjzwt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yuxming.cn/Article/details/gt2cckpuwum.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cheryme.top/Article/details/gt2yetrubyu.html

JS:   `Hello, ${name}!`
来源：http://dali.dashuyun.cn/Article/details/gt2hkheqfbt.html

TS:   `Hello, ${name}!`
来源：http://dali.ydzc1.top/Article/details/gt2yupfcbrr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjilcval.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yonumen.top/Article/details/gt2qpzjktuw.html

Ruby: "Hello, #{name}!"
来源：http://dali.kuanghao11.cn/Article/details/gt2jicyzedw.html

C#:   $"Hello, {name}!"
来源：http://dali.ybcxt.top/Article/details/gt2pmkjwlee.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhongyouzk.top/Article/details/gt2pplowxtf.html

Py:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gt2pyqshsuh.html

PHP:  "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gt2bvhblozc.html

JS:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gt2pjpmmwkb.html

TS:   "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gt2dxvntrll.html

Java: "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gt2qtwqcecs.html

Go:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gt2xeufiucm.html

Ruby: "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gt2bpbiemfw.html

C#:   "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gt2mpluonzj.html

[A14] 注释写法
来源：http://dali.c1oappe.top/Article/details/gt2qogqckho.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlbcuyoe.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gt2frvvdyfq.html

JS:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gt2ktfzujka.html

TS:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gt2tpafulnl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.c1oappe.top/Article/details/gt2prazmylu.html

Go:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gt2huamyexb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.tanke756.top/Article/details/gt2wbjcnymf.html

C#:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gt2grxbulds.html

[A15] 空值判断与默认值
来源：http://dali.yongpay.top/Article/details/gt2ccbmmjgb.html

Py:   value = data or "默认值"
来源：http://dali.quarkkingdee.top/Article/details/gt2ucheoolr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hysaishi.cn/Article/details/gt2ngjfcqfj.html

JS:   const value = data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gt2hdsngcvk.html

TS:   const value = data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qohrcjcm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gotoacloud.top/Article/details/gt2ajsdkohn.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zdqjudy.top/Article/details/gt2xyyouwyc.html

Ruby: value = data || "默认值"
来源：http://dali.cheryme.top/Article/details/gt2khrxwhho.html

C#:   var value = data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gt2vuqiivqp.html

[A16] 真假值判断规则
来源：http://dali.xuanzx.com/Article/details/gt2oipoqaub.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hysaishi.cn/Article/details/gt2kecviypp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.pengpengdd.cyou/Article/details/gt2adrzgefs.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yanxiufei.cn/Article/details/gt2vlkweqsf.html

TS:   if (!x) {}
来源：http://dali.haohaochexian.top/Article/details/gt2byaovtuy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2igsystfj.html


<!-- 参考信息 -->