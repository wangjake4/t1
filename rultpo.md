代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.bjfxy.top/Article/details/gt2hwcmesdx.html

new Promise((resolve, reject) => {})
来源：http://dali.iojbl.cn/Article/details/gt2oqhvtorb.html

[U96] JS：async/await 与异常
来源：http://dali.yueranfly.top/Article/details/gt2zumczlfk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2nmvgzfoq.html

[U97] JS：并发请求
来源：http://dali.sufxvd.cn/Article/details/gt2dlpjcdpi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2rubkpmre.html

[U98] JS：fetch 带 JSON
来源：http://dali.gogol.net.cn/Article/details/gt2peoxgeyc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj202588.top/Article/details/gt2pwploaof.html

[U99] JS：事件监听
来源：http://dali.cdnleiting.top/Article/details/gt2ckdjyrjr.html

el.addEventListener("click", e => {})
来源：http://dali.mhx1999.top/Article/details/gt2ssbaxatt.html

[U100] JS：DOM 查询
来源：http://dali.jqgfzy.top/Article/details/gt2cbwehtjg.html

document.querySelector(".item")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzzepesp.html

[U101] JS：classList 操作
来源：http://dali.gzhubu.top/Article/details/gt2ynvvrjpq.html

el.classList.toggle("active")
来源：http://dali.zdqjudy.top/Article/details/gt2rkiqnzke.html

[U102] JS：本地存储
来源：http://dali.pycfn.com/Article/details/gt2nirobwdf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shuidangran.top/Article/details/gt2jzbopytj.html

[U103] JS：定时器
来源：http://dali.0kj1m.cn/Article/details/gt2gxdmtlam.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.havefunace.top/Article/details/gt2hugbdbjz.html

[U104] JS：防抖
来源：http://dali.zhixingplan.top/Article/details/gt2pyufxujq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2xnarylmf.html

[U105] JS：节流
来源：http://dali.cdnleiting.top/Article/details/gt2bohvasxa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgfzy.top/Article/details/gt2ubmtctmg.html

[U106] JS：日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2ylifwnwg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwxiehtv.html

[U107] JS：数字千分位
来源：http://dali.bjfxy.top/Article/details/gt2osdcbixc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gt2rbjmhjto.html

[U108] JS：随机整数
来源：http://dali.gzhubu.top/Article/details/gt2zsfpexxx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dashuyun.cn/Article/details/gt2syjbmjms.html

[U109] JS：数组分组
来源：http://dali.sufxvd.cn/Article/details/gt2tclfovug.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gt2ucvzwncs.html

[U110] JS：数组分块
来源：http://dali.gotoacloud.top/Article/details/gt2jybwoape.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgufenzy.top/Article/details/gt2agdpmwze.html

[U111] JS：对象转 Map
来源：http://dali.pengpengdd.cyou/Article/details/gt2ycmldurc.html

new Map(Object.entries(obj))
来源：http://dali.jqgfzy.top/Article/details/gt2ieeacqgx.html

[U112] JS：字符串补位
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmzcowws.html

"7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2grqurwvt.html

[U113] JS：正则替换全部
来源：http://dali.wangshuangyany.cn/Article/details/gt2okbtknjd.html

s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2mccaaeph.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gt2jfqqcfra.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258888.top/Article/details/gt2gfgkfzfr.html

[U115] JS：生成 UUID
来源：http://dali.yj20258.top/Article/details/gt2pkbzitve.html

crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2taoiseqb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xylfe.cn/Article/details/gt2mfxqqlyx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cheryme.top/Article/details/gt2dvuhphks.html

[U117] JS：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gt2hfxcnnxj.html

npm i -D vitest;  npx vitest
来源：http://dali.birdmap.top/Article/details/gt2wdqslmsh.html

[U118] JS：开发服务器
来源：http://dali.daxiang520.top/Article/details/gt2hgljvvxn.html

npm i -D vite;  npx vite
来源：http://dali.hongshengwenyu.top/Article/details/gt2claiszfl.html

[U119] JS：生产构建
来源：http://dali.vqdsnc.cn/Article/details/gt2zuuowqju.html

npx vite build
来源：http://dali.316326.xyz/Article/details/gt2vslnurrk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yueranfly.top/Article/details/gt2ugokufmy.html

import.meta.env.VITE_API_URL
来源：http://dali.shuidangran.top/Article/details/gt2pgxfocbx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2brqkwulm.html

统计汇总
来源：http://dali.xziqi.cn/Article/details/gt2zodoswik.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2zhxffwsr.html

按语言统计（条）：
来源：http://dali.nanxuanxn.top/Article/details/gt2idlrjlfz.html

Python ......... 252
来源：http://dali.nwbrower.top/Article/details/gt2yqvetrvo.html

PHP ............ 252
来源：http://dali.hnqzz.top/Article/details/gt2acehcgpu.html

JavaScript ..... 252
来源：http://dali.havefunace.top/Article/details/gt2oupfwgjf.html

TypeScript ..... 212
来源：http://dali.gogol.net.cn/Article/details/gt2zqmrmhfl.html

Java ........... 212
来源：http://dali.ybcxt.top/Article/details/gt2jlckooqv.html

Go ............. 212
来源：http://dali.c1oappe.top/Article/details/gt2ogeqwbry.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gt2ziymwyfp.html

C# ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gt2ceewbhps.html

C .............. 30
来源：http://dali.pycfn.com/Article/details/gt2wkrbzhln.html

C++ ............ 30
来源：http://dali.316326.xyz/Article/details/gt2pcpbvhna.html

SQL ............ 90
来源：http://dali.cucudq.cn/Article/details/gt2ohipgywr.html

Bash ........... 80
来源：http://dali.xinyue.icu/Article/details/gt2tjewkndi.html

Kotlin ......... 15
来源：http://dali.yuxming.cn/Article/details/gt2lrsexmjl.html

Swift .......... 15
来源：http://dali.xinyue.icu/Article/details/gt2yrhwodfv.html

Lua ............ 10
来源：http://dali.zhongyouzk.top/Article/details/gt2msoedaum.html

Perl ........... 10
来源：http://dali.ydzc1.top/Article/details/gt2ywfljrwi.html

Scala .......... 10
来源：http://dali.ydzc1.top/Article/details/gt2qfepdjgj.html

------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gt2lelboiqc.html

合计 ........... 2106 条
来源：http://dali.yonumen.top/Article/details/gt2pxfksvnl.html

按章节统计：
来源：http://dali.redwolf501.top/Article/details/gt2budoxhps.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzygoitp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gt2jrhvcyau.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gt2kutaatdc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gt2nhjzutjf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tianlin.xyz/Article/details/gt2dionrrcn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cashguo.top/Article/details/gt2rlnqyxhk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gt2zvuybozs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daria6918.cn/Article/details/gt2xbtnqoig.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gt2wwuvdypb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gt2tfkyjkdh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gt2rvqwdfru.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gt2hbtsldpj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2fphxsdwd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gt2zknwkqxi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhengqikj.top/Article/details/gt2pbkjclsd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gt2muqjyxym.html

Q SQL 专题                              90
来源：http://dali.xuanzx.com/Article/details/gt2vdhzwdvq.html

R Bash 专题                             80
来源：http://dali.smart0.xyz/Article/details/gt2ybbsbota.html

S C / C++ 专题                          60
来源：http://dali.tian-w.cn/Article/details/gt2qsmjedpj.html

T 其他语言补充                          60
来源：http://dali.guannengcc.top/Article/details/gt2elgeivii.html

U 高频实用片段                         120
来源：http://dali.yongpay.top/Article/details/gt2wdhtjval.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhrgwkyf.html

合计                                  2106 条
来源：http://dali.sufxvd.cn/Article/details/gt2mvyypmzb.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2oqyrvara.html

使用提醒
来源：http://dali.meibo888.top/Article/details/gt2ryhjiwxx.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2dbqxijpy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gt2gydtawuy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.wangdashe.top/Article/details/gt2wafpygjb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yuxming.cn/Article/details/gt2rrgrmvsz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cucudq.cn/Article/details/gt2usfxaxnw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jianghu66.top/Article/details/gt2wucaqzdn.html

—— 文件结束 ——
来源：http://dali.xinyue.icu/Article/details/gt2bbvsfyiw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2wsstjbeh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.316326.xyz/Article/details/gt2nyzybxeu.html

Common Programming Examples Cheat Book
来源：http://dali.andypj.xyz/Article/details/gt2oplbumyp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ugzvcxos.html

【收录内容】
来源：http://dali.yanxiufei.cn/Article/details/gt2zguarrck.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yuanzhike.top/Article/details/gt2qrlfdpke.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.aizwys.cn/Article/details/gt2zzsqwdlu.html

SQL · Bash · C · C++
来源：http://dali.yvedp.cn/Article/details/gt2kqcqfbim.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenjidiqi.icu/Article/details/gt2sudlrrux.html

【使用说明】
来源：http://dali.yj20258.top/Article/details/gt2fnymdtlm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cqqwz.cn/Article/details/gt2wizashqr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhixingplan.top/Article/details/gt2ezsoeqfb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohykoehg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvqmvkdf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.0kj1m.cn/Article/details/gt2pxvrdzmz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hnqzz.top/Article/details/gt2kdmdblws.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shzxlz.cn/Article/details/gt2hhkadsxj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jqgfzy.top/Article/details/gt2udjnxqjz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.daxiang520.top/Article/details/gt2nteuryxa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.daria6918.cn/Article/details/gt2kjnremll.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhengqikj.top/Article/details/gt2mrzyqzma.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.9152youxi.cn/Article/details/gt2wxqdsxmq.html

【文件统计】
来源：http://dali.jiagoushi.top/Article/details/gt2gfloyokc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hnxiangtu.top/Article/details/gt2sdlvsylf.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2zwuoievq.html

目  录
来源：http://dali.sysykeji.top/Article/details/gt2wmhzkxfa.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2mcmmtdti.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqqhguit.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gogol.net.cn/Article/details/gt2wfzikyqt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gt2pxyqzchy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gt2ieuiqvmp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenlongwang.top/Article/details/gt2zdhosswn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dianchejie.cn/Article/details/gt2tpysjivx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2xmhyagpt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gt2isacccys.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gt2nemjpsuj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sabccbxb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsdesbuq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gt2ijkoznyc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gt2mrjuzpvh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylvfzvpx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hysaishi.cn/Article/details/gt2zwnjorpn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gt2datgalwu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cucudq.cn/Article/details/gt2uyrnvozm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yonumen.top/Article/details/gt2zpailyeu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigufen.top/Article/details/gt2ugcrccid.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzdubutg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gt2zsfwhhmc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2llicbxwc.html

A. 基础语法与类型
来源：http://dali.yj20258.top/Article/details/gt2hjjuksyu.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2kzpchsow.html

[A01] Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2kagbglaz.html

Py:   print("Hello, World!")
来源：http://dali.yonumen.top/Article/details/gt2ovtxlryx.html

PHP:  echo "Hello, World!";
来源：http://dali.ivvv.top/Article/details/gt2hyaqjmtn.html

JS:   console.log("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wtyhwuzg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuanzx.com/Article/details/gt2acasppxw.html

Java: System.out.println("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gt2dyozgibk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cashguo.top/Article/details/gt2splzffmw.html

Ruby: puts "Hello, World!"
来源：http://dali.dianchejie.cn/Article/details/gt2vxnvxksl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gt2puqmpzsj.html

[A02] 变量声明与赋值
来源：http://dali.quarkkingdee.top/Article/details/gt2vcrxzvmy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ehwqpu.com/Article/details/gt2izjsnoet.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmjiaedl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gt2ftazksim.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.nanxuanxn.top/Article/details/gt2cjtyqbnq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ivvv.top/Article/details/gt2ybmglxsy.html

Go:   name := "Alex"; age := 20
来源：http://dali.cqqwz.cn/Article/details/gt2nsmrktbk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iioavldq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yonumen.top/Article/details/gt2hanvaxoa.html

[A03] 常量定义
来源：http://dali.hnqzz.top/Article/details/gt2dpyknadm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnxiangtu.top/Article/details/gt2hvdlptdo.html

PHP:  const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2djqjlrqy.html

JS:   const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2dhmneass.html

TS:   const PI: number = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2blzfbelg.html

Java: static final double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2xdvmwper.html

Go:   const PI = 3.14159
来源：http://dali.nwbrower.top/Article/details/gt2mjdfxiyw.html

Ruby: PI = 3.14159
来源：http://dali.quarkkingdee.top/Article/details/gt2lcntgstr.html

C#:   const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2fiucewqc.html

[A04] 判断变量类型
来源：http://dali.sxryk.cn/Article/details/gt2nphfnrxx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jqgufenzy.top/Article/details/gt2vocmufvq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ivvv.top/Article/details/gt2velsbwfj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xinyue.icu/Article/details/gt2vtocmkax.html

TS:   typeof x; x instanceof Date
来源：http://dali.daxiang520.top/Article/details/gt2fqfxojub.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hammf.cn/Article/details/gt2kwkdgzdo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nanxinkj.top/Article/details/gt2lpwjexuo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigfzy.top/Article/details/gt2jsewfvpp.html

C#:   x.GetType().Name; x is int
来源：http://dali.yangfankeji.com/Article/details/gt2vcckpfcz.html

[A05] 整数除法与取模
来源：http://dali.c1oappe.top/Article/details/gt2ftkpuynh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.wangdashe.top/Article/details/gt2yzvszzlm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gt2uxwnloxn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gt2symhukbr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2qmepejcu.html

Java: 7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gt2zylxiuog.html

Go:   7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2biahxuhk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gt2smubkvko.html

C#:   7 / 2; 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gt2lkblcsyn.html

[A06] 字符串转数字
来源：http://dali.hnqzz.top/Article/details/gt2hknmnwqg.html

Py:   int("42"); float("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gt2jekfeqkp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nwbrower.top/Article/details/gt2syhmyobp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.nanxinkj.top/Article/details/gt2nzsjfjgz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cheryme.top/Article/details/gt2iughhcnw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yuxming.cn/Article/details/gt2teduzczj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cheryme.top/Article/details/gt2olpjzadm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.andypj.xyz/Article/details/gt2msrlszvj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.andypj.xyz/Article/details/gt2xdesmrrh.html

[A07] 数字转字符串
来源：http://dali.xziqi.cn/Article/details/gt2memmlump.html

Py:   str(42)
来源：http://dali.daxiang520.top/Article/details/gt2fgkurfff.html

PHP:  (string) 42; strval(42)
来源：http://dali.nanxuanxn.top/Article/details/gt2wxuuocly.html

JS:   String(42); (42).toString()
来源：http://dali.c1oappe.top/Article/details/gt2sgcsauua.html

TS:   String(42)
来源：http://dali.yonumen.top/Article/details/gt2xwqopmta.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.iojbl.cn/Article/details/gt2sdvgoyrp.html

Go:   strconv.Itoa(42)
来源：http://dali.9152youxi.cn/Article/details/gt2opsxairk.html

Ruby: 42.to_s
来源：http://dali.nwbrower.top/Article/details/gt2hongdknj.html

C#:   42.ToString()
来源：http://dali.svipenyu.cn/Article/details/gt2lylrkcxf.html

[A08] 取整与四舍五入
来源：http://dali.dashuyun.cn/Article/details/gt2eszbpjfe.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yj202588.top/Article/details/gt2zilfrknq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zycfv.cn/Article/details/gt2eymakyre.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gt2peetogeo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhoulong.xyz/Article/details/gt2qcvuqdmk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkmcxykk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sweek.top/Article/details/gt2yyoghbxz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cheryme.top/Article/details/gt2rxoxitsy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gt2beqnzrcd.html

[A09] 绝对值与最大最小值
来源：http://dali.chenlongwang.top/Article/details/gt2fmyborsh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2umepbfvx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwuaylva.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2jtcjsona.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2adcrdwhf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjnpkmya.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hnxiangtu.top/Article/details/gt2aztpdymj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.316326.xyz/Article/details/gt2uorombsu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sweek.top/Article/details/gt2mkrqyxys.html

[A10] 生成随机数
来源：http://dali.aizwys.cn/Article/details/gt2ajexqqwi.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gogol.net.cn/Article/details/gt2qcdspbyp.html

PHP:  random_int(1, 100);
来源：http://dali.smart0.xyz/Article/details/gt2bghyglnr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gt2nqoofbeq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jianghu66.top/Article/details/gt2samrjbdg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.gaohongyu789.top/Article/details/gt2vusarcfh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.svipenyu.cn/Article/details/gt2ykebdflw.html

Ruby: rand(1..100)
来源：http://dali.gotoacloud.top/Article/details/gt2bqvcpvnr.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinqigufen.top/Article/details/gt2oxihzetp.html

[A11] 条件表达式（三元）
来源：http://dali.yangfankeji.com/Article/details/gt2qhoamdjh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.sxryk.cn/Article/details/gt2eltukukb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gt2xmlaeofc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gt2eijcqhun.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmdwfoae.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gt2pmbidwbl.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yuanzhike.top/Article/details/gt2iyyrfnex.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gt2savlbuku.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gt2oyomzjdo.html

[A12] 字符串插值 / 格式化
来源：http://dali.jianghu66.top/Article/details/gt2bljjvjkj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinqigufen.top/Article/details/gt2drxzkbjx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.svipenyu.cn/Article/details/gt2ozauikqh.html

JS:   `Hello, ${name}!`
来源：http://dali.dashuyun.cn/Article/details/gt2frebdrpa.html

TS:   `Hello, ${name}!`
来源：http://dali.0kj1m.cn/Article/details/gt2bqsalfdk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jqgfzy.top/Article/details/gt2gkzjpsdh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xinyue.icu/Article/details/gt2alonyriv.html

Ruby: "Hello, #{name}!"
来源：http://dali.yueranfly.top/Article/details/gt2wigprtan.html

C#:   $"Hello, {name}!"
来源：http://dali.daxiang520.top/Article/details/gt2ohrwrssm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.daxiang520.top/Article/details/gt2avgvsmli.html

Py:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gt2tgsatowj.html

PHP:  "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gt2cmrmcshf.html

JS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2ccuzfkew.html

TS:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2tuekxxam.html

Java: "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gt2edyofrjg.html

Go:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkcmjmef.html

Ruby: "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gt2xlilktyr.html

C#:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gt2fperglml.html

[A14] 注释写法
来源：http://dali.zhoulong.xyz/Article/details/gt2zxlvuvoy.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.guowangkeji.top/Article/details/gt2ohsfxtvq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jianghu66.top/Article/details/gt2qaycktax.html

JS:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gt2rfkeevut.html

TS:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gt2lbauaxnf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntccjhmi.html

Go:   // 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gt2ueimehuz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.guannengcc.top/Article/details/gt2bjfbdhcy.html

C#:   // 单行；/* 多行 */
来源：http://dali.redwolf501.top/Article/details/gt2yrckjcdw.html

[A15] 空值判断与默认值
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyyykzag.html

Py:   value = data or "默认值"
来源：http://dali.cashguo.top/Article/details/gt2maviwayj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhengqikj.top/Article/details/gt2wdjnkmrq.html

JS:   const value = data ?? "默认值";
来源：http://dali.yangfankeji.com/Article/details/gt2cednunsh.html

TS:   const value = data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gt2fstsvtwq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ybcxt.top/Article/details/gt2mhqqsido.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnlvrris.html

Ruby: value = data || "默认值"
来源：http://dali.nanxuanxn.top/Article/details/gt2nmncxiyz.html

C#:   var value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gt2wtnvmkhf.html

[A16] 真假值判断规则
来源：http://dali.dashuyun.cn/Article/details/gt2dhbbuewt.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ybcxt.top/Article/details/gt2hnwoxkdu.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hongshengwenyu.top/Article/details/gt2owhhpwti.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yvedp.cn/Article/details/gt2ptjrrymb.html

TS:   if (!x) {}
来源：http://dali.chenzaomai.com/Article/details/gt2orfnoeaz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.birdmap.top/Article/details/gt2ijtohprw.html


<!-- 参考信息 -->