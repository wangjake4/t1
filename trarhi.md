代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdkdhvfw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.wangdashe.top/Article/details/gt2bkjjqkye.html

[U92] JS：深拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2eoagttta.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uemksknn.html

[U93] JS：模板字符串
来源：http://dali.shzxlz.cn/Article/details/gt2tjfttxau.html

`共 ${n} 条`
来源：http://dali.0kj1m.cn/Article/details/gt2yvitbjvl.html

[U94] JS：箭头函数
来源：http://dali.tian-w.cn/Article/details/gt2mevnztew.html

const double = x => x * 2;
来源：http://dali.jiagoushi.top/Article/details/gt2kwivzcqq.html

[U95] JS：Promise 包装
来源：http://dali.fzhhl.top/Article/details/gt2jtgyxhmh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuuhqxa.html

[U96] JS：async/await 与异常
来源：http://dali.mhx1999.top/Article/details/gt2ouujtnvz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gt2anwjpbyt.html

[U97] JS：并发请求
来源：http://dali.dashuyun.cn/Article/details/gt2suruqtbf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2nxsuukiy.html

[U98] JS：fetch 带 JSON
来源：http://dali.yongpay.top/Article/details/gt2useezgsp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.iojbl.cn/Article/details/gt2uvpjlsvm.html

[U99] JS：事件监听
来源：http://dali.xylfe.cn/Article/details/gt2vwkttqlf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pezvilym.html

[U100] JS：DOM 查询
来源：http://dali.yj202588.top/Article/details/gt2vatzbtdh.html

document.querySelector(".item")
来源：http://dali.kuanghao11.cn/Article/details/gt2ngeyvmxt.html

[U101] JS：classList 操作
来源：http://dali.cheryme.top/Article/details/gt2cvurymnj.html

el.classList.toggle("active")
来源：http://dali.yangfankeji.com/Article/details/gt2hkqlfkjc.html

[U102] JS：本地存储
来源：http://dali.sweek.top/Article/details/gt2llzpgkcd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuetiantiany.cn/Article/details/gt2nuutuwfv.html

[U103] JS：定时器
来源：http://dali.havefunace.top/Article/details/gt2luzioyor.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ehwqpu.com/Article/details/gt2axanffra.html

[U104] JS：防抖
来源：http://dali.ppjwa.cn/Article/details/gt2krleubuw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gt2anuawpuy.html

[U105] JS：节流
来源：http://dali.gzhubu.top/Article/details/gt2kyuydddp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cashguo.top/Article/details/gt2xqbqezuw.html

[U106] JS：日期格式化
来源：http://dali.yuanzhike.top/Article/details/gt2uhefwnnm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnxiangtu.top/Article/details/gt2vbwchftb.html

[U107] JS：数字千分位
来源：http://dali.nanxinkj.top/Article/details/gt2ythrwcrm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gt2famtnaue.html

[U108] JS：随机整数
来源：http://dali.mhx1999.top/Article/details/gt2jtsoicbx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.vqdsnc.cn/Article/details/gt2wbdhopwo.html

[U109] JS：数组分组
来源：http://dali.zdqjudy.top/Article/details/gt2oykaxwfz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrzoxbx.html

[U110] JS：数组分块
来源：http://dali.aibaodan.cn/Article/details/gt2cfwrcoye.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.svipenyu.cn/Article/details/gt2tvjznlcg.html

[U111] JS：对象转 Map
来源：http://dali.wangshuangyany.cn/Article/details/gt2rewjblxp.html

new Map(Object.entries(obj))
来源：http://dali.chenzaomai.com/Article/details/gt2cqoxycbq.html

[U112] JS：字符串补位
来源：http://dali.yj202588.top/Article/details/gt2weegrxob.html

"7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2mpbpeebt.html

[U113] JS：正则替换全部
来源：http://dali.yongpay.top/Article/details/gt2lauzarwr.html

s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2leatpexx.html

[U114] JS：JSON 深比较
来源：http://dali.sxryk.cn/Article/details/gt2nnupunpa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxbxpokm.html

[U115] JS：生成 UUID
来源：http://dali.iojbl.cn/Article/details/gt2dqpulysq.html

crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2wioneddc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.kuanghao11.cn/Article/details/gt2zyzglmfr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2teohziql.html

[U117] JS：单元测试
来源：http://dali.zhoulong.xyz/Article/details/gt2muetixak.html

npm i -D vitest;  npx vitest
来源：http://dali.hywenlv.cn/Article/details/gt2erzcwpuh.html

[U118] JS：开发服务器
来源：http://dali.sufxvd.cn/Article/details/gt2qikbvvgq.html

npm i -D vite;  npx vite
来源：http://dali.meibo888.top/Article/details/gt2egrbqzci.html

[U119] JS：生产构建
来源：http://dali.zycfv.cn/Article/details/gt2izsegzye.html

npx vite build
来源：http://dali.ehwqpu.com/Article/details/gt2ajgaoltw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxinkj.top/Article/details/gt2mynbckec.html

import.meta.env.VITE_API_URL
来源：http://dali.quarkkingdee.top/Article/details/gt2puqdjsjf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2exatijzu.html

统计汇总
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjnhjogl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2qszgxpsr.html

按语言统计（条）：
来源：http://dali.andypj.xyz/Article/details/gt2czqfqydp.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gt2pyjmvuph.html

PHP ............ 252
来源：http://dali.andypj.xyz/Article/details/gt2rvirpppw.html

JavaScript ..... 252
来源：http://dali.yangfankeji.com/Article/details/gt2tdfjqhkx.html

TypeScript ..... 212
来源：http://dali.zhixingplan.top/Article/details/gt2lahtyamn.html

Java ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhquabdm.html

Go ............. 212
来源：http://dali.pycfn.com/Article/details/gt2ucacxzdl.html

Ruby ........... 212
来源：http://dali.tanke756.top/Article/details/gt2dxppuovu.html

C# ............. 212
来源：http://dali.sysykeji.top/Article/details/gt2gdcxvxsl.html

C .............. 30
来源：http://dali.chenzaomai.com/Article/details/gt2nntcpfcz.html

C++ ............ 30
来源：http://dali.316326.xyz/Article/details/gt2jmpllmqp.html

SQL ............ 90
来源：http://dali.shzxlz.cn/Article/details/gt2zjkdzqvq.html

Bash ........... 80
来源：http://dali.mhx1999.top/Article/details/gt2aiigwpyf.html

Kotlin ......... 15
来源：http://dali.iojbl.cn/Article/details/gt2loxlyhee.html

Swift .......... 15
来源：http://dali.yuanzhike.top/Article/details/gt2dfgercjp.html

Lua ............ 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qidaokwf.html

Perl ........... 10
来源：http://dali.c1oappe.top/Article/details/gt2ifqnensj.html

Scala .......... 10
来源：http://dali.aibaodan.cn/Article/details/gt2vygjsvwo.html

------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijbwrgjp.html

合计 ........... 2106 条
来源：http://dali.yongpay.top/Article/details/gt2vkrxeehl.html

按章节统计：
来源：http://dali.hysaishi.cn/Article/details/gt2xgzkygbw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gt2ooibwxol.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjjuchrz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gt2zrqvqzfi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xinyue.icu/Article/details/gt2xxjupiix.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hywenlv.cn/Article/details/gt2beysgjjk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gt2gifrobpx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gt2enigxgnd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gt2jxgenfvd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gt2cjbjwkmd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gt2paxqhgng.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gt2zbqsquwl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gt2futdiynd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gt2rbjxsfjq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewsmohkn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.9152youxi.cn/Article/details/gt2opefdjnf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2uksthycl.html

Q SQL 专题                              90
来源：http://dali.feifeiyinyue.top/Article/details/gt2nllybeqo.html

R Bash 专题                             80
来源：http://dali.yangfankeji.com/Article/details/gt2jijjfyjq.html

S C / C++ 专题                          60
来源：http://dali.daxiang520.top/Article/details/gt2iqtleljw.html

T 其他语言补充                          60
来源：http://dali.hysaishi.cn/Article/details/gt2tajybczv.html

U 高频实用片段                         120
来源：http://dali.gogol.net.cn/Article/details/gt2ozkwqqji.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gt2koigrmvw.html

合计                                  2106 条
来源：http://dali.cheryme.top/Article/details/gt2ztdhudgo.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gt2knejxbue.html

使用提醒
来源：http://dali.ehwqpu.com/Article/details/gt2varqbzvz.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gt2ojdqbiqw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cheryme.top/Article/details/gt2mfrhscbk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hnxiangtu.top/Article/details/gt2fsqwolcy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenzaomai.com/Article/details/gt2onnhbacq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yonumen.top/Article/details/gt2qrpuustn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xziqi.cn/Article/details/gt2wilasppz.html

—— 文件结束 ——
来源：http://dali.guannengcc.top/Article/details/gt2ftrzqkdi.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2luvbabzd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhiwuduotai.top/Article/details/gt2coebsiqy.html

Common Programming Examples Cheat Book
来源：http://dali.hammf.cn/Article/details/gt2zxxxklki.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijtwccyb.html

【收录内容】
来源：http://dali.guannengcc.top/Article/details/gt2cbnxioax.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yj202588.top/Article/details/gt2xbapfpgk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cucudq.cn/Article/details/gt2rxkcxltw.html

SQL · Bash · C · C++
来源：http://dali.gaohongyu789.top/Article/details/gt2vphgitdh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hammf.cn/Article/details/gt2koubykdv.html

【使用说明】
来源：http://dali.wangshuangyany.cn/Article/details/gt2vbnjiplx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxuanxn.top/Article/details/gt2kotszkjh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.mhx1999.top/Article/details/gt2zdtspfjt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ehwqpu.com/Article/details/gt2rzirwjnk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.birdmap.top/Article/details/gt2tvfqxffu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xinyue.icu/Article/details/gt2sidoregr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.bjfxy.top/Article/details/gt2zofgccew.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tian-w.cn/Article/details/gt2gcszyzxl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.andypj.xyz/Article/details/gt2qpnancyr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.316326.xyz/Article/details/gt2kmkossgi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.0kj1m.cn/Article/details/gt2lbhbpuqu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqxmxqwc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ybcxt.top/Article/details/gt2lrbijiok.html

【文件统计】
来源：http://dali.ppjwa.cn/Article/details/gt2ficaojso.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhengqikj.top/Article/details/gt2fkequdvq.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2yepjiyxb.html

目  录
来源：http://dali.kuanghao11.cn/Article/details/gt2xhlqypsb.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gt2egrfncun.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenzaomai.com/Article/details/gt2kleiflvs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.daxiang520.top/Article/details/gt2yntgacsa.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gt2tcwsnhai.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinqigufen.top/Article/details/gt2lostbzej.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj202588.top/Article/details/gt2uyonfiwa.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcirfvft.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gt2aruigvew.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gt2uotqgywf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gt2sjptvzmj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.316326.xyz/Article/details/gt2jqihbzrc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gt2bhsvbnvp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2goqyvijk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gt2ighozmio.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gt2yynidndt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2nnhndkxt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gt2cyebdnzh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hysaishi.cn/Article/details/gt2mmkydskb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cuaebcgm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2bezhhswe.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gt2yykopjjw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2uyfcsxuq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2jrklpbax.html

A. 基础语法与类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrfkxftt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2jblrgnin.html

[A01] Hello World
来源：http://dali.cashguo.top/Article/details/gt2eqifgmwb.html

Py:   print("Hello, World!")
来源：http://dali.andypj.xyz/Article/details/gt2vucqrxtj.html

PHP:  echo "Hello, World!";
来源：http://dali.nwbrower.top/Article/details/gt2uccnblcr.html

JS:   console.log("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gt2mhkeylat.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yongpay.top/Article/details/gt2freabjgr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlrepdac.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gt2rsojunui.html

Ruby: puts "Hello, World!"
来源：http://dali.hnqzz.top/Article/details/gt2rjdncbfv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajyvesmz.html

[A02] 变量声明与赋值
来源：http://dali.mhx1999.top/Article/details/gt2sffprqtd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.smart0.xyz/Article/details/gt2ddsgoojb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.9152youxi.cn/Article/details/gt2upezyqpn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ybcxt.top/Article/details/gt2pwqmdzea.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenzaomai.com/Article/details/gt2qloynnan.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gt2sdirjzlv.html

Go:   name := "Alex"; age := 20
来源：http://dali.yvedp.cn/Article/details/gt2xctxqveq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.bjfxy.top/Article/details/gt2evhjnuwn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yuxming.cn/Article/details/gt2firbdrxk.html

[A03] 常量定义
来源：http://dali.yvedp.cn/Article/details/gt2fggqlhid.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fzhhl.top/Article/details/gt2otswxajm.html

PHP:  const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cryqdnlj.html

JS:   const PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2zzcgpcco.html

TS:   const PI: number = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2jqjrmzif.html

Java: static final double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2mzcvuiab.html

Go:   const PI = 3.14159
来源：http://dali.smart0.xyz/Article/details/gt2vuejhqgh.html

Ruby: PI = 3.14159
来源：http://dali.xylfe.cn/Article/details/gt2qslvhzrf.html

C#:   const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2pzcjpgnv.html

[A04] 判断变量类型
来源：http://dali.hysaishi.cn/Article/details/gt2plqrduqo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mostsznk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj20258888.top/Article/details/gt2wsymuvtd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gaohongyu789.top/Article/details/gt2pirirqqo.html

TS:   typeof x; x instanceof Date
来源：http://dali.havefunace.top/Article/details/gt2rlsniirl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jlsjyb.cn/Article/details/gt2smaecmct.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.fengsongda.top/Article/details/gt2jlnacztt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ybcxt.top/Article/details/gt2lozwjzzu.html

C#:   x.GetType().Name; x is int
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzqtdxkz.html

[A05] 整数除法与取模
来源：http://dali.ppjwa.cn/Article/details/gt2vnxvhepm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.mhx1999.top/Article/details/gt2udvihifp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gt2ncbjwghr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ivvv.top/Article/details/gt2sfguyylw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gt2rzxootyp.html

Java: 7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gt2beyeluct.html

Go:   7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2rnvzyktu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2prfprizm.html

C#:   7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2oknorwvm.html

[A06] 字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gt2ierhxzyq.html

Py:   int("42"); float("3.14")
来源：http://dali.sweek.top/Article/details/gt2yonwmjrc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yonumen.top/Article/details/gt2cogpgptm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gt2dscmcvar.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gt2xwvmjvkb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlcwhedb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.smart0.xyz/Article/details/gt2kwoxqnqh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.aizwys.cn/Article/details/gt2nlxloctk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nwbrower.top/Article/details/gt2qltkkrus.html

[A07] 数字转字符串
来源：http://dali.yuxming.cn/Article/details/gt2ornqmwzq.html

Py:   str(42)
来源：http://dali.shzxlz.cn/Article/details/gt2dhxgagfb.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfwxandp.html

JS:   String(42); (42).toString()
来源：http://dali.0kj1m.cn/Article/details/gt2eznkyuxb.html

TS:   String(42)
来源：http://dali.aizwys.cn/Article/details/gt2puciuqcw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hysaishi.cn/Article/details/gt2qkeisxni.html

Go:   strconv.Itoa(42)
来源：http://dali.jiagoushi.top/Article/details/gt2fpmmgeli.html

Ruby: 42.to_s
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpymtoda.html

C#:   42.ToString()
来源：http://dali.gotoacloud.top/Article/details/gt2jujpzrip.html

[A08] 取整与四舍五入
来源：http://dali.mhx1999.top/Article/details/gt2dkuwyfru.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gt2wgnbzcrc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tianlin.xyz/Article/details/gt2ivnbwnrr.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gt2pyzvzqrj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.fengsongda.top/Article/details/gt2wkkcukoq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gt2kaafkqfu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gt2kvwkwkci.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenlongwang.top/Article/details/gt2wjwgignj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gt2xwectybb.html

[A09] 绝对值与最大最小值
来源：http://dali.zdqjudy.top/Article/details/gt2pcndvplw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2avrabnzf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gt2ixphlanq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2magburkl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2lnvfjysd.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibenzpfg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jteupmkj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.aibaodan.cn/Article/details/gt2mdmapvwm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2ogubsoie.html

[A10] 生成随机数
来源：http://dali.ydzc1.top/Article/details/gt2xfwtgwql.html

Py:   import random; random.randint(1, 100)
来源：http://dali.bjfxy.top/Article/details/gt2ipxfxgkd.html

PHP:  random_int(1, 100);
来源：http://dali.fzhhl.top/Article/details/gt2jvyhlfto.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aizwys.cn/Article/details/gt2iafhlgnj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sufxvd.cn/Article/details/gt2ludsjgka.html

Java: new Random().nextInt(100) + 1
来源：http://dali.bjfxy.top/Article/details/gt2cilgwygf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zdqjudy.top/Article/details/gt2wifcgkyp.html

Ruby: rand(1..100)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbiuhhuz.html

C#:   new Random().Next(1, 101)
来源：http://dali.aizwys.cn/Article/details/gt2qyvghykf.html

[A11] 条件表达式（三元）
来源：http://dali.jlsjyb.cn/Article/details/gt2uzferbsu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhengqikj.top/Article/details/gt2tmyyezjz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gt2dlwartnr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gt2fhpnberu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gt2evnfrjhz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gt2dqjcbwec.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.guannengcc.top/Article/details/gt2cdmhxlfa.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gt2ioubydbm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gt2hnlrxqvr.html

[A12] 字符串插值 / 格式化
来源：http://dali.andypj.xyz/Article/details/gt2csfpongb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljzpyont.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.bjfxy.top/Article/details/gt2gxxfslsp.html

JS:   `Hello, ${name}!`
来源：http://dali.xinyue.icu/Article/details/gt2rldipjhk.html

TS:   `Hello, ${name}!`
来源：http://dali.yj20258.top/Article/details/gt2gmrwveiu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xinyue.icu/Article/details/gt2lxnkdszh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.daxiang520.top/Article/details/gt2hoflweyy.html

Ruby: "Hello, #{name}!"
来源：http://dali.meibo888.top/Article/details/gt2syteapzk.html

C#:   $"Hello, {name}!"
来源：http://dali.xziqi.cn/Article/details/gt2mrjeylsb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ppjwa.cn/Article/details/gt2ukhfdvdy.html

Py:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gt2jzdeqsav.html

PHP:  "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gt2eukjvojo.html

JS:   "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gt2mzjrrkbi.html

TS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gt2rrqcgplw.html

Java: "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gt2xspdhish.html

Go:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gt2mcldrfsa.html

Ruby: "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gt2tdzknctk.html

C#:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gt2ebjlzant.html

[A14] 注释写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2beyujavj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.haohaochexian.top/Article/details/gt2jdwrmsng.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gt2fpjxkrdd.html

JS:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gt2fixcicix.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gt2swqttopu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hnxiangtu.top/Article/details/gt2pmsjxnds.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gt2dmtghbkd.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.gaohongyu789.top/Article/details/gt2njwbquld.html

C#:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmwwbmzf.html

[A15] 空值判断与默认值
来源：http://dali.xuanzx.com/Article/details/gt2qpxkszpe.html

Py:   value = data or "默认值"
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtsbaqwu.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gt2scwtqbxp.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckmfjrja.html

TS:   const value = data ?? "默认值";
来源：http://dali.jqgufenzy.top/Article/details/gt2xodgneor.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.nanxinkj.top/Article/details/gt2dnlrjxrd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guannengcc.top/Article/details/gt2awkdnsrl.html


<!-- 参考信息 -->