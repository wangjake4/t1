代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gt2nwcnroxr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.snrcjt.cn/Article/details/gt2przggfjm.html

[U92] JS：深拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbbgtwev.html

structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gt2agwabyrd.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dniitckg.html

`共 ${n} 条`
来源：http://dali.redwolf501.top/Article/details/gt2cfimblcy.html

[U94] JS：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gt2zsjfgsam.html

const double = x => x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gt2vnucpthv.html

[U95] JS：Promise 包装
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftdhztgb.html

new Promise((resolve, reject) => {})
来源：http://dali.shzxlz.cn/Article/details/gt2ntcgredo.html

[U96] JS：async/await 与异常
来源：http://dali.snrcjt.cn/Article/details/gt2divmauxi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2reamkzmn.html

[U97] JS：并发请求
来源：http://dali.sufxvd.cn/Article/details/gt2jeafoaxf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2mkwruzna.html

[U98] JS：fetch 带 JSON
来源：http://dali.havefunace.top/Article/details/gt2ljbojrme.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gotoacloud.top/Article/details/gt2bkhbxtvm.html

[U99] JS：事件监听
来源：http://dali.hnxiangtu.top/Article/details/gt2clixopdy.html

el.addEventListener("click", e => {})
来源：http://dali.dianchejie.cn/Article/details/gt2mahyuinq.html

[U100] JS：DOM 查询
来源：http://dali.ivvv.top/Article/details/gt2pgvdhrhk.html

document.querySelector(".item")
来源：http://dali.zhixingplan.top/Article/details/gt2irbnbwui.html

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gt2jmwgpvuk.html

el.classList.toggle("active")
来源：http://dali.ehwqpu.com/Article/details/gt2oaokyeth.html

[U102] JS：本地存储
来源：http://dali.fengsongda.top/Article/details/gt2zkdqliqr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zdqjudy.top/Article/details/gt2xapvhzpg.html

[U103] JS：定时器
来源：http://dali.0kj1m.cn/Article/details/gt2ithtukgn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ehwqpu.com/Article/details/gt2haejohnz.html

[U104] JS：防抖
来源：http://dali.jlsjyb.cn/Article/details/gt2ieqxzznc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2oqynmuip.html

[U105] JS：节流
来源：http://dali.gzhubu.top/Article/details/gt2itojzcss.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hfpthk.cn/Article/details/gt2eeivbcaf.html

[U106] JS：日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2iovimacu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tian-w.cn/Article/details/gt2wrxtqryu.html

[U107] JS：数字千分位
来源：http://dali.haohaochexian.top/Article/details/gt2hrobmekj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sweek.top/Article/details/gt2tnpfyoql.html

[U108] JS：随机整数
来源：http://dali.tanke756.top/Article/details/gt2cskekjqo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yuxming.cn/Article/details/gt2simmclao.html

[U109] JS：数组分组
来源：http://dali.yuanzhike.top/Article/details/gt2fbyqbhyj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gt2iatgvilr.html

[U110] JS：数组分块
来源：http://dali.quarkkingdee.top/Article/details/gt2akmrifry.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhengqikj.top/Article/details/gt2vowmaadk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aiksiqwa.html

new Map(Object.entries(obj))
来源：http://dali.wangdashe.top/Article/details/gt2ozojbsiy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2sratehhv.html

"7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2iufvziin.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfjfzfbg.html

s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2bndgiddv.html

[U114] JS：JSON 深比较
来源：http://dali.ivvv.top/Article/details/gt2muwglpgx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gt2cbsiedgf.html

[U115] JS：生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gt2pviybutq.html

crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gt2unkmiuzb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guowangkeji.top/Article/details/gt2zjygklsk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmtmfnvw.html

[U117] JS：单元测试
来源：http://dali.cucudq.cn/Article/details/gt2jwwbluvl.html

npm i -D vitest;  npx vitest
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jaywlzjt.html

[U118] JS：开发服务器
来源：http://dali.xylfe.cn/Article/details/gt2idovvshj.html

npm i -D vite;  npx vite
来源：http://dali.gotoacloud.top/Article/details/gt2aysfzwww.html

[U119] JS：生产构建
来源：http://dali.hfpthk.cn/Article/details/gt2hwhcusee.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gt2dvltyjwy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fzhhl.top/Article/details/gt2rgfqfldl.html

import.meta.env.VITE_API_URL
来源：http://dali.sufxvd.cn/Article/details/gt2ioiwmpnb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2tnkuxmka.html

统计汇总
来源：http://dali.bjfxy.top/Article/details/gt2exowsgpt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2wsxzriom.html

按语言统计（条）：
来源：http://dali.jqgufenzy.top/Article/details/gt2viynlheh.html

Python ......... 252
来源：http://dali.yonumen.top/Article/details/gt2yvggkelu.html

PHP ............ 252
来源：http://dali.ppjwa.cn/Article/details/gt2miexomqv.html

JavaScript ..... 252
来源：http://dali.c1oappe.top/Article/details/gt2jvimaafq.html

TypeScript ..... 212
来源：http://dali.chenzaomai.com/Article/details/gt2wxmpuiyu.html

Java ........... 212
来源：http://dali.ybcxt.top/Article/details/gt2sxvgfvpi.html

Go ............. 212
来源：http://dali.sufxvd.cn/Article/details/gt2txgziztj.html

Ruby ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dsoicpkq.html

C# ............. 212
来源：http://dali.fengsongda.top/Article/details/gt2fupxsdjp.html

C .............. 30
来源：http://dali.yj20258.top/Article/details/gt2smlamasj.html

C++ ............ 30
来源：http://dali.cashguo.top/Article/details/gt2xzxvpmkv.html

SQL ............ 90
来源：http://dali.sysykeji.top/Article/details/gt2spwtjayl.html

Bash ........... 80
来源：http://dali.9152youxi.cn/Article/details/gt2liritzxj.html

Kotlin ......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohillmtp.html

Swift .......... 15
来源：http://dali.yangfankeji.com/Article/details/gt2brbdolks.html

Lua ............ 10
来源：http://dali.yuxming.cn/Article/details/gt2mncowitj.html

Perl ........... 10
来源：http://dali.birdmap.top/Article/details/gt2nkkwwzpm.html

Scala .......... 10
来源：http://dali.fzhhl.top/Article/details/gt2zbcifrsp.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2mebpdxzf.html

合计 ........... 2106 条
来源：http://dali.zhoulong.xyz/Article/details/gt2sywgklzz.html

按章节统计：
来源：http://dali.jyoumei.cn/Article/details/gt2fkbzkqye.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.fengsongda.top/Article/details/gt2jkwkqoxi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gt2rtjhczxu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gt2vftnvjfw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gt2hctdnnvh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinghuilouyu.cn/Article/details/gt2optfikli.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sufxvd.cn/Article/details/gt2sfgxqgup.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gt2xtkqjlvm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gt2cdcyisdx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2qwpsnwvq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gt2vnnykkfb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gt2osvzfjlv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2wvvrvjbo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2sxyqbjhc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gt2vefsecec.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jlsjyb.cn/Article/details/gt2iwjvfpbm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2ffvadveh.html

Q SQL 专题                              90
来源：http://dali.svipenyu.cn/Article/details/gt2bigtwqnu.html

R Bash 专题                             80
来源：http://dali.yj20258.top/Article/details/gt2grmtvtyu.html

S C / C++ 专题                          60
来源：http://dali.snrcjt.cn/Article/details/gt2slsffsdh.html

T 其他语言补充                          60
来源：http://dali.aibaodan.cn/Article/details/gt2wxdpqryl.html

U 高频实用片段                         120
来源：http://dali.cdnleiting.top/Article/details/gt2nwcyklnw.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2hmermlmu.html

合计                                  2106 条
来源：http://dali.gzhubu.top/Article/details/gt2wajruwrr.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2lvjamgjo.html

使用提醒
来源：http://dali.daria6918.cn/Article/details/gt2ctdzmaex.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2ffptqgck.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhiwuduotai.top/Article/details/gt2atoaatmn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjrxiyjj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daria6918.cn/Article/details/gt2qasfikby.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yangfankeji.com/Article/details/gt2siounupv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.daxiang520.top/Article/details/gt2yjwciqmj.html

—— 文件结束 ——
来源：http://dali.jyoumei.cn/Article/details/gt2xgzhythk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2hxzztzat.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigufen.top/Article/details/gt2umemugbp.html

Common Programming Examples Cheat Book
来源：http://dali.chenzaomai.com/Article/details/gt2sxdwuhiz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2qmiivoza.html

【收录内容】
来源：http://dali.zhixingplan.top/Article/details/gt2gmxucnxh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wakntxvm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cheryme.top/Article/details/gt2gyiqiuhx.html

SQL · Bash · C · C++
来源：http://dali.cheryme.top/Article/details/gt2qtxijdik.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvukpemi.html

【使用说明】
来源：http://dali.ybcxt.top/Article/details/gt2ildohaci.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hongshengwenyu.top/Article/details/gt2giwgapov.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yonumen.top/Article/details/gt2fclnbsnl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xylfe.cn/Article/details/gt2lgmlacep.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shangyingyoupin.top/Article/details/gt2xganmxkp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gogol.net.cn/Article/details/gt2zshhnqrk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.fzhhl.top/Article/details/gt2jfhesryb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nwbrower.top/Article/details/gt2erfaefnl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sufxvd.cn/Article/details/gt2gqzblvpl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangdashe.top/Article/details/gt2ghtlnrvx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdhpfmsb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zycfv.cn/Article/details/gt2yxeemwne.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.daria6918.cn/Article/details/gt2eddcmjqx.html

【文件统计】
来源：http://dali.fengsongda.top/Article/details/gt2avdbsyua.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hnxiangtu.top/Article/details/gt2hrsfdqqv.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2rcdkbwmk.html

目  录
来源：http://dali.pycfn.com/Article/details/gt2fwexlnvt.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gt2hnccgptf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gt2mjqmpmrr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gt2vtjeeemc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dianchejie.cn/Article/details/gt2cgghcbpw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mijbatbp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjtgzrjj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.haohaochexian.top/Article/details/gt2tjsoxbfw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gt2gndkuluo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jianghu66.top/Article/details/gt2pwjicsmg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gt2aeahxpio.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gt2zncayvmx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gt2tkpqcilo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gt2faykhjlp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2iefqyomf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jyoumei.cn/Article/details/gt2duyfdrtu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nwbrower.top/Article/details/gt2qlnexksf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gt2uvnwvsti.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.birdmap.top/Article/details/gt2dpqtpcey.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zycfv.cn/Article/details/gt2pbeurgdt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gzhubu.top/Article/details/gt2hxaktuiq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewtrwtla.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gt2iufwqdhv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2bltgklye.html

A. 基础语法与类型
来源：http://dali.sxryk.cn/Article/details/gt2rubhewpu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2iofejgvk.html

[A01] Hello World
来源：http://dali.ydzc1.top/Article/details/gt2jpxbcwne.html

Py:   print("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gt2fahdtmjw.html

PHP:  echo "Hello, World!";
来源：http://dali.tanke756.top/Article/details/gt2dublipbi.html

JS:   console.log("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gt2tmzlvhlv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.svipenyu.cn/Article/details/gt2pgtmxnuo.html

Java: System.out.println("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gt2wxkqmvgo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.kuanghao11.cn/Article/details/gt2xfoqyaxj.html

Ruby: puts "Hello, World!"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eurbpnhd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gt2muaijwlv.html

[A02] 变量声明与赋值
来源：http://dali.sxryk.cn/Article/details/gt2bnuavlwi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.snrcjt.cn/Article/details/gt2rcajzvft.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.c1oappe.top/Article/details/gt2kkdicmhe.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cheryme.top/Article/details/gt2nzrlhgip.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sysykeji.top/Article/details/gt2adugapzn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zdqjudy.top/Article/details/gt2ucucturi.html

Go:   name := "Alex"; age := 20
来源：http://dali.ppjwa.cn/Article/details/gt2tkurgarr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yj20258.top/Article/details/gt2yjlqfaug.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cucudq.cn/Article/details/gt2nigensxg.html

[A03] 常量定义
来源：http://dali.gaohongyu789.top/Article/details/gt2btaseewb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2rsylnrme.html

PHP:  const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2lliblcso.html

JS:   const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2aylxllfu.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2hgkhggdz.html

Java: static final double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2kwklmkwk.html

Go:   const PI = 3.14159
来源：http://dali.zhixingplan.top/Article/details/gt2cilonenz.html

Ruby: PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gt2ubwjjtku.html

C#:   const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2qkwjcbqm.html

[A04] 判断变量类型
来源：http://dali.hnxiangtu.top/Article/details/gt2vilwtjfr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.birdmap.top/Article/details/gt2txtvoidq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigufen.top/Article/details/gt2ninefzcj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sysykeji.top/Article/details/gt2aomcuhfh.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhengqikj.top/Article/details/gt2vlhgvwlm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ydzc1.top/Article/details/gt2nwahtmnz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hysaishi.cn/Article/details/gt2cayyhcuj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.c1oappe.top/Article/details/gt2gqnyvduh.html

C#:   x.GetType().Name; x is int
来源：http://dali.xinyue.icu/Article/details/gt2okrkuvbp.html

[A05] 整数除法与取模
来源：http://dali.xinyue.icu/Article/details/gt2dwtvsjwq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shzxlz.cn/Article/details/gt2kqqkgfiz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gt2rmqurfat.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gt2qjomuggk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gt2mpyntxxc.html

Java: 7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gt2dlwuqmjj.html

Go:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nyivhjhz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gt2tkiqsceo.html

C#:   7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gt2aqcpzddz.html

[A06] 字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gt2trfiqwsy.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqdiola.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvqsddue.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.haohaochexian.top/Article/details/gt2vqbsbogu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnqzz.top/Article/details/gt2rvribpmj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gt2plaagkua.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jyoumei.cn/Article/details/gt2jmlhckob.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.9152youxi.cn/Article/details/gt2gssagfqz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hysaishi.cn/Article/details/gt2gaavczga.html

[A07] 数字转字符串
来源：http://dali.hysaishi.cn/Article/details/gt2ftilqwyr.html

Py:   str(42)
来源：http://dali.mhx1999.top/Article/details/gt2qeswsopg.html

PHP:  (string) 42; strval(42)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvdnqhgf.html

JS:   String(42); (42).toString()
来源：http://dali.jiagoushi.top/Article/details/gt2dkkvqhwq.html

TS:   String(42)
来源：http://dali.mhx1999.top/Article/details/gt2ahjjyhuw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenzaomai.com/Article/details/gt2njoondmz.html

Go:   strconv.Itoa(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhfwcyjs.html

Ruby: 42.to_s
来源：http://dali.316326.xyz/Article/details/gt2qigdkins.html

C#:   42.ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2acbuferr.html

[A08] 取整与四舍五入
来源：http://dali.hammf.cn/Article/details/gt2ptamovvh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gt2brqxclyk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nwbrower.top/Article/details/gt2dtbnlqzo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gt2nlyjslhv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqjwriry.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gt2skndtdao.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gt2bzrwhjdm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.c1oappe.top/Article/details/gt2ysjluupn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gt2fledojkg.html

[A09] 绝对值与最大最小值
来源：http://dali.hfpthk.cn/Article/details/gt2rubyjrry.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gt2ugrzttiq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gt2drltbmqy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2izwcxnqy.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2owsccdju.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2rngjlagm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.pycfn.com/Article/details/gt2atddrekd.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.dashuyun.cn/Article/details/gt2nfpxfimn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfakrtam.html

[A10] 生成随机数
来源：http://dali.gotoacloud.top/Article/details/gt2ezsaiolu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sysykeji.top/Article/details/gt2rikblxld.html

PHP:  random_int(1, 100);
来源：http://dali.sufxvd.cn/Article/details/gt2owebayxi.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.vqdsnc.cn/Article/details/gt2tgmvfyfo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dianchejie.cn/Article/details/gt2ggrsmood.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yangfankeji.com/Article/details/gt2mohovbzd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hywenlv.cn/Article/details/gt2msgqusxq.html

Ruby: rand(1..100)
来源：http://dali.hnqzz.top/Article/details/gt2zofmxszc.html

C#:   new Random().Next(1, 101)
来源：http://dali.haohaochexian.top/Article/details/gt2ryaryosg.html

[A11] 条件表达式（三元）
来源：http://dali.ppjwa.cn/Article/details/gt2olarefcf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yanxiufei.cn/Article/details/gt2agtxtxys.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gt2faadcwqj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gt2fxazzalp.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqjhvdhy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gt2kvorkjuz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.chenlongwang.top/Article/details/gt2qdokjwmb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gt2feeaxiqh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gt2passiqbn.html

[A12] 字符串插值 / 格式化
来源：http://dali.daria6918.cn/Article/details/gt2tektwzgq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.tianlin.xyz/Article/details/gt2qbunzthh.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.pycfn.com/Article/details/gt2swyubpki.html

JS:   `Hello, ${name}!`
来源：http://dali.tianlin.xyz/Article/details/gt2cnfnoljq.html

TS:   `Hello, ${name}!`
来源：http://dali.hysaishi.cn/Article/details/gt2rjblioqp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zycfv.cn/Article/details/gt2gcpahaqi.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.birdmap.top/Article/details/gt2tmtaypxr.html

Ruby: "Hello, #{name}!"
来源：http://dali.mhx1999.top/Article/details/gt2oojmoczs.html

C#:   $"Hello, {name}!"
来源：http://dali.ydzc1.top/Article/details/gt2hazbglym.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ydzc1.top/Article/details/gt2asjulauw.html

Py:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gt2nwylyews.html

PHP:  "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2jrvbsscq.html

JS:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gt2vvyiqmfx.html

TS:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvkrahox.html

Java: "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gt2fizcdbaf.html

Go:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gt2tqmlflde.html

Ruby: "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqrahsgl.html

C#:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gt2xhjdoczy.html

[A14] 注释写法
来源：http://dali.zhoulong.xyz/Article/details/gt2wydejigs.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cqqwz.cn/Article/details/gt2rqichzvv.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gt2jprtuccx.html

JS:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gt2umxgdtvz.html

TS:   // 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gt2bhedgzvp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yj20258888.top/Article/details/gt2kjqdolms.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnfmrojw.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.snrcjt.cn/Article/details/gt2bnjmxzbc.html

C#:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gt2eajrpubn.html

[A15] 空值判断与默认值
来源：http://dali.yuanzhike.top/Article/details/gt2oaqclosv.html

Py:   value = data or "默认值"
来源：http://dali.jiagoushi.top/Article/details/gt2thfyfqki.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yueranfly.top/Article/details/gt2bqgqoulo.html

JS:   const value = data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gt2hmmfdweh.html

TS:   const value = data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gt2esfhqstq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hnqzz.top/Article/details/gt2pfwfhpww.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.svipenyu.cn/Article/details/gt2fwykapdv.html


<!-- 参考信息 -->