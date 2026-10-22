代发 wailian999

[U97] JS：并发请求
来源：http://dali.yj20258888.top/Article/details/gt2rlwzmbbi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2abkmeqzj.html

[U98] JS：fetch 带 JSON
来源：http://dali.xziqi.cn/Article/details/gt2byxsmdkj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cqqwz.cn/Article/details/gt2whvqzmtv.html

[U99] JS：事件监听
来源：http://dali.xuanzx.com/Article/details/gt2pdofiwrc.html

el.addEventListener("click", e => {})
来源：http://dali.fengsongda.top/Article/details/gt2dqeiootz.html

[U100] JS：DOM 查询
来源：http://dali.chenzaomai.com/Article/details/gt2ptwvxiin.html

document.querySelector(".item")
来源：http://dali.iojbl.cn/Article/details/gt2xrnmyyfc.html

[U101] JS：classList 操作
来源：http://dali.andypj.xyz/Article/details/gt2hloytauy.html

el.classList.toggle("active")
来源：http://dali.sxryk.cn/Article/details/gt2uolvadqg.html

[U102] JS：本地存储
来源：http://dali.zhoulong.xyz/Article/details/gt2lbrugtya.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gt2iicdlkxz.html

[U103] JS：定时器
来源：http://dali.ydzc1.top/Article/details/gt2wsbvviqd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sweek.top/Article/details/gt2gqxwqaia.html

[U104] JS：防抖
来源：http://dali.pycfn.com/Article/details/gt2jytsesov.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gt2hjtpkpxe.html

[U105] JS：节流
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpeqpgop.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258888.top/Article/details/gt2wfsitepy.html

[U106] JS：日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tldwunqk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgsuorva.html

[U107] JS：数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dllrwfpk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gt2jdisoxff.html

[U108] JS：随机整数
来源：http://dali.aibaodan.cn/Article/details/gt2rxyrggbj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwtgscbh.html

[U109] JS：数组分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhmhkntt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2wbfowpln.html

[U110] JS：数组分块
来源：http://dali.zhongyouzk.top/Article/details/gt2xxkxrtig.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lsgijrug.html

[U111] JS：对象转 Map
来源：http://dali.0kj1m.cn/Article/details/gt2zncegiru.html

new Map(Object.entries(obj))
来源：http://dali.yonumen.top/Article/details/gt2psqawsqq.html

[U112] JS：字符串补位
来源：http://dali.cqqwz.cn/Article/details/gt2nhknmtif.html

"7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2yevjfypy.html

[U113] JS：正则替换全部
来源：http://dali.yonumen.top/Article/details/gt2licwebhn.html

s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2avzbvmjb.html

[U114] JS：JSON 深比较
来源：http://dali.svipenyu.cn/Article/details/gt2lghnbvvp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2ugkejrpl.html

[U115] JS：生成 UUID
来源：http://dali.ivvv.top/Article/details/gt2regsuael.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gt2nakjvgxu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.9152youxi.cn/Article/details/gt2hlyykurs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tanke756.top/Article/details/gt2mntnfbfw.html

[U117] JS：单元测试
来源：http://dali.kuanghao11.cn/Article/details/gt2nxycpklk.html

npm i -D vitest;  npx vitest
来源：http://dali.gogol.net.cn/Article/details/gt2wydiupom.html

[U118] JS：开发服务器
来源：http://dali.zhongyouzk.top/Article/details/gt2mulbqiag.html

npm i -D vite;  npx vite
来源：http://dali.ehwqpu.com/Article/details/gt2myoyprhd.html

[U119] JS：生产构建
来源：http://dali.snrcjt.cn/Article/details/gt2ovehachc.html

npx vite build
来源：http://dali.zhengqikj.top/Article/details/gt2gkreaurk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gogol.net.cn/Article/details/gt2qtwzkijw.html

import.meta.env.VITE_API_URL
来源：http://dali.mhx1999.top/Article/details/gt2cgmslpjf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2wneligcp.html

统计汇总
来源：http://dali.yuxming.cn/Article/details/gt2wskcnotk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ddtsqkxf.html

按语言统计（条）：
来源：http://dali.jyoumei.cn/Article/details/gt2botifbzy.html

Python ......... 252
来源：http://dali.jianghu66.top/Article/details/gt2jqbvbjmy.html

PHP ............ 252
来源：http://dali.yj20258888.top/Article/details/gt2pyfoejxc.html

JavaScript ..... 252
来源：http://dali.ivvv.top/Article/details/gt2hqtphctr.html

TypeScript ..... 212
来源：http://dali.meibo888.top/Article/details/gt2evaivstu.html

Java ........... 212
来源：http://dali.0kj1m.cn/Article/details/gt2ifsyiynm.html

Go ............. 212
来源：http://dali.316326.xyz/Article/details/gt2lkxnaxei.html

Ruby ........... 212
来源：http://dali.wangdashe.top/Article/details/gt2rjwbcthi.html

C# ............. 212
来源：http://dali.cdnleiting.top/Article/details/gt2tpkanxdu.html

C .............. 30
来源：http://dali.vqdsnc.cn/Article/details/gt2okszgrcv.html

C++ ............ 30
来源：http://dali.aizwys.cn/Article/details/gt2ljqdetqz.html

SQL ............ 90
来源：http://dali.yj202588.top/Article/details/gt2qwxlycwq.html

Bash ........... 80
来源：http://dali.tian-w.cn/Article/details/gt2ndbhrrwi.html

Kotlin ......... 15
来源：http://dali.mhx1999.top/Article/details/gt2mzmypzvg.html

Swift .......... 15
来源：http://dali.birdmap.top/Article/details/gt2aaqkprmr.html

Lua ............ 10
来源：http://dali.haohaochexian.top/Article/details/gt2loaypavk.html

Perl ........... 10
来源：http://dali.zhongyouzk.top/Article/details/gt2lhbhhlwy.html

Scala .......... 10
来源：http://dali.gogol.net.cn/Article/details/gt2fvfzqwol.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2sbaitvnq.html

合计 ........... 2106 条
来源：http://dali.yongpay.top/Article/details/gt2iknfsxdg.html

按章节统计：
来源：http://dali.jlsjyb.cn/Article/details/gt2dbkkiaoa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gt2wzgbgcqx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gt2abdwmibl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gt2qljaggba.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gt2temafger.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cheryme.top/Article/details/gt2cgdrsthp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hfpthk.cn/Article/details/gt2qxpvjito.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gt2xljouwkf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sxryk.cn/Article/details/gt2xsubxjto.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2whczdcpn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gt2sbbijyxa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2izctluab.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gt2wcziouqo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2ytlrkzro.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ybcxt.top/Article/details/gt2orpnkujo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj20258888.top/Article/details/gt2pgqtcstf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkbmrajz.html

Q SQL 专题                              90
来源：http://dali.gaohongyu789.top/Article/details/gt2gbvzyprd.html

R Bash 专题                             80
来源：http://dali.yj20258888.top/Article/details/gt2zzfqwqgq.html

S C / C++ 专题                          60
来源：http://dali.0kj1m.cn/Article/details/gt2yihbnwfm.html

T 其他语言补充                          60
来源：http://dali.jqgufenzy.top/Article/details/gt2cinfnpkb.html

U 高频实用片段                         120
来源：http://dali.gzhubu.top/Article/details/gt2uelikgsh.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gt2dgwuijwi.html

合计                                  2106 条
来源：http://dali.cdnleiting.top/Article/details/gt2ddnzsnkf.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2ifiziebh.html

使用提醒
来源：http://dali.tianlin.xyz/Article/details/gt2fjjdtnbz.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gt2teawyvli.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.mhx1999.top/Article/details/gt2baaeysib.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigufen.top/Article/details/gt2rfarivgo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.c1oappe.top/Article/details/gt2kgedgsyd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tianlin.xyz/Article/details/gt2zmalevdq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhengqikj.top/Article/details/gt2nswytpoq.html

—— 文件结束 ——
来源：http://dali.dianchejie.cn/Article/details/gt2pkosbmir.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2yispusxa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ehwqpu.com/Article/details/gt2enuwmviu.html

Common Programming Examples Cheat Book
来源：http://dali.yuxming.cn/Article/details/gt2wznodbnv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2qubumsug.html

【收录内容】
来源：http://dali.zhengqikj.top/Article/details/gt2upkqiiry.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tanke756.top/Article/details/gt2kmnzoazp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gzhubu.top/Article/details/gt2wbqskemo.html

SQL · Bash · C · C++
来源：http://dali.daria6918.cn/Article/details/gt2dukrfboi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhiwuduotai.top/Article/details/gt2bauvpdfy.html

【使用说明】
来源：http://dali.sxryk.cn/Article/details/gt2dmkquubf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj202588.top/Article/details/gt2iawqqoyf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.pycfn.com/Article/details/gt2giwysdlc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guowangkeji.top/Article/details/gt2zkizevqz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.daria6918.cn/Article/details/gt2hwgqvaul.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.0kj1m.cn/Article/details/gt2javavxns.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jqgufenzy.top/Article/details/gt2ttctqnaj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.haohaochexian.top/Article/details/gt2cacavxtw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nanxuanxn.top/Article/details/gt2rhhrawnh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zycfv.cn/Article/details/gt2wpaobpce.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.pycfn.com/Article/details/gt2fukzsfor.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.dashuyun.cn/Article/details/gt2wzlzdktn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.redwolf501.top/Article/details/gt2amonkwot.html

【文件统计】
来源：http://dali.gogol.net.cn/Article/details/gt2hxbldpov.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jianghu66.top/Article/details/gt2tcuiawpy.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gt2hzenqjax.html

目  录
来源：http://dali.yj20258888.top/Article/details/gt2ynvagtpu.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhpwsprd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2lngpphlr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbvxdopu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2puddmrne.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdaphail.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xziqi.cn/Article/details/gt2huvvyuht.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ydzc1.top/Article/details/gt2zwuqdwen.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gt2efsgamjb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojeighsc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gt2xwufzqxk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpfmiyde.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2hotulacn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gt2gkwzcgit.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2qebwaopy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.smart0.xyz/Article/details/gt2ovbfhwfl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxbjwew.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnsvhgya.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.svipenyu.cn/Article/details/gt2qwsplrxr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2imrjuvai.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jyoumei.cn/Article/details/gt2mqnfwwmx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gt2buaijfrb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gt2mhkzvpxb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2mdmhpqgw.html

A. 基础语法与类型
来源：http://dali.jlsjyb.cn/Article/details/gt2xuedznbc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2guyicosi.html

[A01] Hello World
来源：http://dali.nwbrower.top/Article/details/gt2gatjumax.html

Py:   print("Hello, World!")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvghoioe.html

PHP:  echo "Hello, World!";
来源：http://dali.birdmap.top/Article/details/gt2jfoawxzu.html

JS:   console.log("Hello, World!");
来源：http://dali.9152youxi.cn/Article/details/gt2wdfefwup.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnqzz.top/Article/details/gt2wkgqpdyp.html

Java: System.out.println("Hello, World!");
来源：http://dali.pengpengdd.cyou/Article/details/gt2swcszhog.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hywenlv.cn/Article/details/gt2edxdzojm.html

Ruby: puts "Hello, World!"
来源：http://dali.tian-w.cn/Article/details/gt2dmdzonhm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btmhronc.html

[A02] 变量声明与赋值
来源：http://dali.316326.xyz/Article/details/gt2ilsaglbb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.haohaochexian.top/Article/details/gt2ijstiqsz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gt2eyipsckv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sweek.top/Article/details/gt2fhuseesv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shuidangran.top/Article/details/gt2idnbljmh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gt2dnuzapnx.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhengqikj.top/Article/details/gt2kqiyzxos.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yvedp.cn/Article/details/gt2ixwftjig.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgaqokkl.html

[A03] 常量定义
来源：http://dali.hammf.cn/Article/details/gt2ointmwyk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.havefunace.top/Article/details/gt2giepankk.html

PHP:  const PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2dnxzwnkd.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2xslfrvcm.html

TS:   const PI: number = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2zyncxuae.html

Java: static final double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2vshmeyln.html

Go:   const PI = 3.14159
来源：http://dali.cucudq.cn/Article/details/gt2rnrfblcs.html

Ruby: PI = 3.14159
来源：http://dali.pycfn.com/Article/details/gt2lyxkrhmx.html

C#:   const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gt2dpljpiwn.html

[A04] 判断变量类型
来源：http://dali.yongpay.top/Article/details/gt2igxngovn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuanzhike.top/Article/details/gt2dlphomep.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hnxiangtu.top/Article/details/gt2kjhsbjzn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gt2qpjibvtr.html

TS:   typeof x; x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffdfuqtv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sufxvd.cn/Article/details/gt2ibgldbbe.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.pycfn.com/Article/details/gt2nuqlbehy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jlsjyb.cn/Article/details/gt2emegyyey.html

C#:   x.GetType().Name; x is int
来源：http://dali.shzxlz.cn/Article/details/gt2uictyybg.html

[A05] 整数除法与取模
来源：http://dali.ybcxt.top/Article/details/gt2ygdihueu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yuanzhike.top/Article/details/gt2ufpjezsx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2dooavcjn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gt2bgnpnwdt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2caboerpf.html

Java: 7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gt2docmjueq.html

Go:   7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2ssobgsyj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gt2lolllmjs.html

C#:   7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2eurespoc.html

[A06] 字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gt2rozpsyxp.html

Py:   int("42"); float("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mybcfglg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nanxinkj.top/Article/details/gt2edgofoxq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ydzc1.top/Article/details/gt2rlbozlxc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sweek.top/Article/details/gt2oknxzxgg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.haohaochexian.top/Article/details/gt2zsxzgiyc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ppjwa.cn/Article/details/gt2wyrcubvq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jlsjyb.cn/Article/details/gt2kgdsozea.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xziqi.cn/Article/details/gt2lupeocvg.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nxovzfpc.html

Py:   str(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oyansqsq.html

PHP:  (string) 42; strval(42)
来源：http://dali.yongpay.top/Article/details/gt2vhkhassu.html

JS:   String(42); (42).toString()
来源：http://dali.hammf.cn/Article/details/gt2nkqehvea.html

TS:   String(42)
来源：http://dali.meibo888.top/Article/details/gt2nzkntlfj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mfuijava.html

Go:   strconv.Itoa(42)
来源：http://dali.hfpthk.cn/Article/details/gt2kfdisxbp.html

Ruby: 42.to_s
来源：http://dali.svipenyu.cn/Article/details/gt2buticmml.html

C#:   42.ToString()
来源：http://dali.hammf.cn/Article/details/gt2hzzxzqfp.html

[A08] 取整与四舍五入
来源：http://dali.gzhubu.top/Article/details/gt2lmqnkzwq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gt2feuvrvde.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.kuanghao11.cn/Article/details/gt2kcdiocvp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gt2ygajvnmz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.svipenyu.cn/Article/details/gt2kgkhpvtx.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gt2xpbniarh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gt2bjnslmge.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zycfv.cn/Article/details/gt2himfjynl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gt2ilfsxkvu.html

[A09] 绝对值与最大最小值
来源：http://dali.nanxinkj.top/Article/details/gt2uvcjraxr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.iojbl.cn/Article/details/gt2tsgopdci.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2iklxueqw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gt2kvmagowx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2lgozvdbl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ogxiqget.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.aibaodan.cn/Article/details/gt2mqrtttph.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yangfankeji.com/Article/details/gt2lmdkpkcg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2ykqrcsra.html

[A10] 生成随机数
来源：http://dali.svipenyu.cn/Article/details/gt2hoffzabo.html

Py:   import random; random.randint(1, 100)
来源：http://dali.316326.xyz/Article/details/gt2saaqicwm.html

PHP:  random_int(1, 100);
来源：http://dali.guowangkeji.top/Article/details/gt2melzyjrb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tanke756.top/Article/details/gt2fobyzpxb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jqgfzy.top/Article/details/gt2rdmtnmdr.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yuxming.cn/Article/details/gt2vxcyyccq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yj20258888.top/Article/details/gt2rfilopfr.html

Ruby: rand(1..100)
来源：http://dali.hammf.cn/Article/details/gt2hmnlgozc.html

C#:   new Random().Next(1, 101)
来源：http://dali.gzhubu.top/Article/details/gt2hvgnbwxc.html

[A11] 条件表达式（三元）
来源：http://dali.xuanzx.com/Article/details/gt2ykmnzewk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cheryme.top/Article/details/gt2ampxeego.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gt2zyrsnnnr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gt2ysxqnute.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gt2yirlskux.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gt2yadybnia.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhixingplan.top/Article/details/gt2utyhktnj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gt2zjsvxcfu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gt2jhvmegiu.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2mlhbmmcw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.316326.xyz/Article/details/gt2tdrtzkwu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.birdmap.top/Article/details/gt2wuzvgbao.html

JS:   `Hello, ${name}!`
来源：http://dali.cashguo.top/Article/details/gt2plyoxfwl.html

TS:   `Hello, ${name}!`
来源：http://dali.hysaishi.cn/Article/details/gt2djuvjcyx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gogol.net.cn/Article/details/gt2vgcbcoju.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vowxfltb.html

Ruby: "Hello, #{name}!"
来源：http://dali.aizwys.cn/Article/details/gt2yxtvrbuf.html

C#:   $"Hello, {name}!"
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwgrvljz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.vqdsnc.cn/Article/details/gt2ijmbrojp.html

Py:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gt2pykydnfq.html

PHP:  "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2piwohzzv.html

JS:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gt2kfndmqax.html

TS:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gt2vhnpgura.html

Java: "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gt2miaqucui.html

Go:   "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gt2atcihupx.html

Ruby: "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gt2abcjpiex.html

C#:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gt2aiobinjb.html

[A14] 注释写法
来源：http://dali.redwolf501.top/Article/details/gt2lronuwpf.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.dashuyun.cn/Article/details/gt2bwnhzhcy.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gt2xzidxtzf.html

JS:   // 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gt2plfttzpr.html

TS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gt2browsjvl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.iojbl.cn/Article/details/gt2hqwbkjfc.html

Go:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gt2svppqyss.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sweek.top/Article/details/gt2kmlpjmss.html

C#:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gt2plypwvsp.html

[A15] 空值判断与默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjlsmalk.html

Py:   value = data or "默认值"
来源：http://dali.ydzc1.top/Article/details/gt2wxnvnkhd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gt2rpmiezux.html

JS:   const value = data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gt2cenzealo.html

TS:   const value = data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gt2klorhlvk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.bjfxy.top/Article/details/gt2mqxbmawc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ehwqpu.com/Article/details/gt2ajgmzmct.html

Ruby: value = data || "默认值"
来源：http://dali.xinyue.icu/Article/details/gt2huarvrwo.html

C#:   var value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gt2nswcozlu.html

[A16] 真假值判断规则
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zoktklds.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jlsjyb.cn/Article/details/gt2qyxbuvog.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinqigufen.top/Article/details/gt2rkzcqnxg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ybcxt.top/Article/details/gt2nfcmfnst.html

TS:   if (!x) {}
来源：http://dali.zdqjudy.top/Article/details/gt2cwrjeinx.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yj202588.top/Article/details/gt2oxokkkhx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.birdmap.top/Article/details/gt2qlhjzbrg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jiagoushi.top/Article/details/gt2wqblchpq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2eodthgua.html

[A17] 位运算
来源：http://dali.vqdsnc.cn/Article/details/gt2vtwggpdz.html


<!-- 参考信息 -->