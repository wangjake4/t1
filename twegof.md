代发 wailian999

[U87] JS：解构默认值
来源：http://dali.mhx1999.top/Article/details/gt2ezbhjudj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgfzy.top/Article/details/gt2svpmqwyn.html

[U88] JS：对象展开合并
来源：http://dali.jiagoushi.top/Article/details/gt2wxkcofyl.html

{ ...a, ...b }
来源：http://dali.redwolf501.top/Article/details/gt2skczsmfx.html

[U89] JS：数组去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocdprmfm.html

[...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gt2gdfjlrhm.html

[U90] JS：数字数组排序
来源：http://dali.yueranfly.top/Article/details/gt2sudvwqba.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2xfrfrivh.html

[U91] JS：对象键值遍历
来源：http://dali.snrcjt.cn/Article/details/gt2lwvwpavd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aizwys.cn/Article/details/gt2oyovdrmd.html

[U92] JS：深拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2fflscytk.html

structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2rwjbosfp.html

[U93] JS：模板字符串
来源：http://dali.tianlin.xyz/Article/details/gt2xepukqse.html

`共 ${n} 条`
来源：http://dali.daria6918.cn/Article/details/gt2rugmvanw.html

[U94] JS：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gt2epophgzc.html

const double = x => x * 2;
来源：http://dali.gogol.net.cn/Article/details/gt2snyheiug.html

[U95] JS：Promise 包装
来源：http://dali.guowangkeji.top/Article/details/gt2nbwcmhvg.html

new Promise((resolve, reject) => {})
来源：http://dali.tanke756.top/Article/details/gt2onnmpwag.html

[U96] JS：async/await 与异常
来源：http://dali.bjfxy.top/Article/details/gt2fgienill.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ofraoyry.html

[U97] JS：并发请求
来源：http://dali.yonumen.top/Article/details/gt2xpzwbjmv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2voqbuxio.html

[U98] JS：fetch 带 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcpubtfj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jlsjyb.cn/Article/details/gt2xizoqbub.html

[U99] JS：事件监听
来源：http://dali.daria6918.cn/Article/details/gt2kkprxiih.html

el.addEventListener("click", e => {})
来源：http://dali.havefunace.top/Article/details/gt2kzasddnj.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gt2dlsgkgeb.html

document.querySelector(".item")
来源：http://dali.zycfv.cn/Article/details/gt2wysijjpp.html

[U101] JS：classList 操作
来源：http://dali.yuanzhike.top/Article/details/gt2nhnfaint.html

el.classList.toggle("active")
来源：http://dali.gzhubu.top/Article/details/gt2gwyjbpti.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pbgsuglc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yanxiufei.cn/Article/details/gt2qrhhknli.html

[U103] JS：定时器
来源：http://dali.sufxvd.cn/Article/details/gt2wfouxznd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gt2esqzlhfi.html

[U104] JS：防抖
来源：http://dali.yj202588.top/Article/details/gt2dnkxecmw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gt2ippvmgkh.html

[U105] JS：节流
来源：http://dali.mhx1999.top/Article/details/gt2gggbaxnf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ehwqpu.com/Article/details/gt2nlegtlbq.html

[U106] JS：日期格式化
来源：http://dali.iojbl.cn/Article/details/gt2cmjhiusu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gogol.net.cn/Article/details/gt2jrfmjupu.html

[U107] JS：数字千分位
来源：http://dali.yj20258.top/Article/details/gt2rsklrnre.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gt2shoxjrwf.html

[U108] JS：随机整数
来源：http://dali.sxryk.cn/Article/details/gt2oxfrzdoo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sysykeji.top/Article/details/gt2pfxaclgf.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdbiqwca.html

Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gt2czcayycl.html

[U110] JS：数组分块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tyinditq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuanzhike.top/Article/details/gt2htxoxlme.html

[U111] JS：对象转 Map
来源：http://dali.yuxming.cn/Article/details/gt2kuxlrdlq.html

new Map(Object.entries(obj))
来源：http://dali.chenlongwang.top/Article/details/gt2pkpibtfu.html

[U112] JS：字符串补位
来源：http://dali.meibo888.top/Article/details/gt2dgojukns.html

"7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2vzrfjnex.html

[U113] JS：正则替换全部
来源：http://dali.fengsongda.top/Article/details/gt2wgwbfkpm.html

s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2bubtnldd.html

[U114] JS：JSON 深比较
来源：http://dali.haohaochexian.top/Article/details/gt2yswpgiqv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gt2lbpanqta.html

[U115] JS：生成 UUID
来源：http://dali.sxryk.cn/Article/details/gt2wplxeqip.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrktbecu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258.top/Article/details/gt2diispemw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fengsongda.top/Article/details/gt2qarhwahs.html

[U117] JS：单元测试
来源：http://dali.guannengcc.top/Article/details/gt2jalkitnj.html

npm i -D vitest;  npx vitest
来源：http://dali.hongshengwenyu.top/Article/details/gt2rewawdnq.html

[U118] JS：开发服务器
来源：http://dali.sweek.top/Article/details/gt2simihcku.html

npm i -D vite;  npx vite
来源：http://dali.bjfxy.top/Article/details/gt2cynvrfnt.html

[U119] JS：生产构建
来源：http://dali.xylfe.cn/Article/details/gt2hpmbboff.html

npx vite build
来源：http://dali.gzhubu.top/Article/details/gt2fejlvszw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.haohaochexian.top/Article/details/gt2qkpqvgxx.html

import.meta.env.VITE_API_URL
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvllwmam.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2aurmrbtk.html

统计汇总
来源：http://dali.gaohongyu789.top/Article/details/gt2uvtxneal.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2zmuwyxhq.html

按语言统计（条）：
来源：http://dali.jinqigfzy.top/Article/details/gt2uflochab.html

Python ......... 252
来源：http://dali.chenjidiqi.icu/Article/details/gt2rivjysls.html

PHP ............ 252
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwcdfdqa.html

JavaScript ..... 252
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvhqcbgp.html

TypeScript ..... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2omimizaa.html

Java ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2imjepqnc.html

Go ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpzvdhwv.html

Ruby ........... 212
来源：http://dali.yongpay.top/Article/details/gt2entinyek.html

C# ............. 212
来源：http://dali.ppjwa.cn/Article/details/gt2hlzwylxw.html

C .............. 30
来源：http://dali.316326.xyz/Article/details/gt2teoyixzo.html

C++ ............ 30
来源：http://dali.tianlin.xyz/Article/details/gt2uugvpavx.html

SQL ............ 90
来源：http://dali.kuanghao11.cn/Article/details/gt2dvkwdjeo.html

Bash ........... 80
来源：http://dali.cdnleiting.top/Article/details/gt2thnlkest.html

Kotlin ......... 15
来源：http://dali.mhx1999.top/Article/details/gt2mvhczlim.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gt2qupewkmn.html

Lua ............ 10
来源：http://dali.jqgufenzy.top/Article/details/gt2dcfyyieu.html

Perl ........... 10
来源：http://dali.gzhubu.top/Article/details/gt2opmzwvpl.html

Scala .......... 10
来源：http://dali.zhoulong.xyz/Article/details/gt2yymltpww.html

------------------------------------
来源：http://dali.shuidangran.top/Article/details/gt2wgttywsr.html

合计 ........... 2106 条
来源：http://dali.yongpay.top/Article/details/gt2tnnvijyo.html

按章节统计：
来源：http://dali.wangdashe.top/Article/details/gt2wfrjpebd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jqgufenzy.top/Article/details/gt2utvabsyg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gt2ciuuxfer.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gt2praosuov.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gt2jcxcutuk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yuxming.cn/Article/details/gt2oncojdfm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gt2cxvhionl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gt2kyekubcb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gt2jmqnyiji.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gt2jjpvkitm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gt2dhwgsgsa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2izuowsyq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2abyskkdm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2mvptrrxu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinqigufen.top/Article/details/gt2yzgektgq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guowangkeji.top/Article/details/gt2wzhxgnjp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gt2lmlsotgf.html

Q SQL 专题                              90
来源：http://dali.yvedp.cn/Article/details/gt2dksfsnoq.html

R Bash 专题                             80
来源：http://dali.zhixingplan.top/Article/details/gt2lmworvgo.html

S C / C++ 专题                          60
来源：http://dali.hnxiangtu.top/Article/details/gt2mzmokucl.html

T 其他语言补充                          60
来源：http://dali.iojbl.cn/Article/details/gt2twhehkmk.html

U 高频实用片段                         120
来源：http://dali.havefunace.top/Article/details/gt2dclobxxi.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2uwbicvsj.html

合计                                  2106 条
来源：http://dali.xziqi.cn/Article/details/gt2rcbgtnkp.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gt2huesdtsp.html

使用提醒
来源：http://dali.zycfv.cn/Article/details/gt2pkanglsp.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2tehvgmzc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yonumen.top/Article/details/gt2zvaepfwb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.vqdsnc.cn/Article/details/gt2fazscduy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sysykeji.top/Article/details/gt2xfkxyons.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj20258888.top/Article/details/gt2geczdslj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xinyue.icu/Article/details/gt2ohmknhye.html

—— 文件结束 ——
来源：http://dali.jiagoushi.top/Article/details/gt2cwsvpbyt.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2zgblgtex.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yonumen.top/Article/details/gt2zsycgpov.html

Common Programming Examples Cheat Book
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdmhhjkd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2btqsghjg.html

【收录内容】
来源：http://dali.yuanzhike.top/Article/details/gt2vnyglsrv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.guowangkeji.top/Article/details/gt2ufzodxsh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.quarkkingdee.top/Article/details/gt2hqasxqji.html

SQL · Bash · C · C++
来源：http://dali.xylfe.cn/Article/details/gt2emkyjpjw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.0kj1m.cn/Article/details/gt2xoizqbii.html

【使用说明】
来源：http://dali.daxiang520.top/Article/details/gt2kxkyospg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.9152youxi.cn/Article/details/gt2rmomgptz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkkgxolb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.daxiang520.top/Article/details/gt2aqruiesz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqfxhdaw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.bjfxy.top/Article/details/gt2alccdnbd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.bjfxy.top/Article/details/gt2llqpqnuu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shzxlz.cn/Article/details/gt2nfurycou.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj20258888.top/Article/details/gt2uttnltax.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.nanxuanxn.top/Article/details/gt2mzhizfzv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinqigufen.top/Article/details/gt2qydhecbf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nanxinkj.top/Article/details/gt2srlcmegr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj202588.top/Article/details/gt2utlsfzis.html

【文件统计】
来源：http://dali.fengsongda.top/Article/details/gt2oopcayig.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.andypj.xyz/Article/details/gt2oxjpxayr.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2rnqahubx.html

目  录
来源：http://dali.hnqzz.top/Article/details/gt2wrmdrfdb.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2wshqidxp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gt2kzxpyzlf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2cymaaien.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gogol.net.cn/Article/details/gt2objufbmd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mzvhbypo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hammf.cn/Article/details/gt2thawkzaf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxqfmmrq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gt2aaotreqp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hfpthk.cn/Article/details/gt2jgdtssno.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gt2ffzzyvga.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gt2eaehevsu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gt2umbaztjb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2kcidzmrn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gt2bqurylho.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.pycfn.com/Article/details/gt2bjcmockt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ocxexfha.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gt2tzcqkuaj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenzaomai.com/Article/details/gt2hmoskido.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dianchejie.cn/Article/details/gt2cjeetieg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.meibo888.top/Article/details/gt2dqlwhuds.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gt2ncfpbknq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gt2afefksqh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrkgjrrd.html

A. 基础语法与类型
来源：http://dali.quarkkingdee.top/Article/details/gt2oihkroel.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2zkzfoqih.html

[A01] Hello World
来源：http://dali.guannengcc.top/Article/details/gt2isnvwtjr.html

Py:   print("Hello, World!")
来源：http://dali.yj20258.top/Article/details/gt2likfuumw.html

PHP:  echo "Hello, World!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtbzjput.html

JS:   console.log("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gt2izfsrwhz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gaohongyu789.top/Article/details/gt2gpjruqdl.html

Java: System.out.println("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gt2phxbdsyp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xylfe.cn/Article/details/gt2lecugijy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhengqikj.top/Article/details/gt2xbpplkpv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gt2tkicovqy.html

[A02] 变量声明与赋值
来源：http://dali.smart0.xyz/Article/details/gt2tzujetab.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ybcxt.top/Article/details/gt2mvlmdsvp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cdnleiting.top/Article/details/gt2ddlvyars.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hfpthk.cn/Article/details/gt2nqpacxkt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpjxoonx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gt2gxldejep.html

Go:   name := "Alex"; age := 20
来源：http://dali.yonumen.top/Article/details/gt2fcekqxni.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tianlin.xyz/Article/details/gt2qgdbaoiw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uilxcfut.html

[A03] 常量定义
来源：http://dali.chenzaomai.com/Article/details/gt2eyzvmnmg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hammf.cn/Article/details/gt2tzdvzwon.html

PHP:  const PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2qpwwwxxn.html

JS:   const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2vrlacppx.html

TS:   const PI: number = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2dcdnxwlt.html

Java: static final double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2ujibeulq.html

Go:   const PI = 3.14159
来源：http://dali.yongpay.top/Article/details/gt2iqqaumsz.html

Ruby: PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgdnwjir.html

C#:   const double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2fayzfjtm.html

[A04] 判断变量类型
来源：http://dali.ppjwa.cn/Article/details/gt2pgjktrnm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.snrcjt.cn/Article/details/gt2scxbymbc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ppjwa.cn/Article/details/gt2ptogdopt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenlongwang.top/Article/details/gt2vokdbrki.html

TS:   typeof x; x instanceof Date
来源：http://dali.sxryk.cn/Article/details/gt2pzrzunpb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzmyzhgi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2igpigmtn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2stdnlebw.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinqigufen.top/Article/details/gt2yrsrmujh.html

[A05] 整数除法与取模
来源：http://dali.snrcjt.cn/Article/details/gt2kyrbvbmx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.vqdsnc.cn/Article/details/gt2mkzbpxgy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zycfv.cn/Article/details/gt2edhcbgac.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2jfegdpru.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2newncabp.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2ihimnttq.html

Go:   7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2tbvnbbzv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2vufnjwiv.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2fymamnzv.html

[A06] 字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gt2agquzatv.html

Py:   int("42"); float("3.14")
来源：http://dali.c1oappe.top/Article/details/gt2crqdqcas.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yueranfly.top/Article/details/gt2lwuvhcyw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sufxvd.cn/Article/details/gt2nlvutcpi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yangfankeji.com/Article/details/gt2uoynafnu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinqigufen.top/Article/details/gt2watjovqy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.0kj1m.cn/Article/details/gt2ooleozlo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.mhx1999.top/Article/details/gt2etctlgpe.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.gotoacloud.top/Article/details/gt2bevzsyqd.html

[A07] 数字转字符串
来源：http://dali.bjfxy.top/Article/details/gt2fqlgtfxb.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2luhyqqwh.html

PHP:  (string) 42; strval(42)
来源：http://dali.dashuyun.cn/Article/details/gt2vlzetbrd.html

JS:   String(42); (42).toString()
来源：http://dali.c1oappe.top/Article/details/gt2ojcvyzaq.html

TS:   String(42)
来源：http://dali.jyoumei.cn/Article/details/gt2bugrkapx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hysaishi.cn/Article/details/gt2gtpszbnd.html

Go:   strconv.Itoa(42)
来源：http://dali.xuanzx.com/Article/details/gt2imaxsolb.html

Ruby: 42.to_s
来源：http://dali.ydzc1.top/Article/details/gt2gocmigaj.html

C#:   42.ToString()
来源：http://dali.nanxinkj.top/Article/details/gt2sriuznmm.html

[A08] 取整与四舍五入
来源：http://dali.zhixingplan.top/Article/details/gt2hwfqkghh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gt2fvveovsb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yj20258888.top/Article/details/gt2qllxlndn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gt2thrpbtkw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.svipenyu.cn/Article/details/gt2bfpzdxdg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yj20258.top/Article/details/gt2gfkfaodx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gt2snogbpun.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.havefunace.top/Article/details/gt2pwxymdkf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfwfbbjm.html

[A09] 绝对值与最大最小值
来源：http://dali.jianghu66.top/Article/details/gt2tutczcsg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2pjlxccvk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2rlrfmarx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2ngiylgjr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdhhteeb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcsmfycv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hnxiangtu.top/Article/details/gt2qohiiznx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xinyue.icu/Article/details/gt2bqgibcvl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2penlfqsd.html

[A10] 生成随机数
来源：http://dali.shangyingyoupin.top/Article/details/gt2nenqdour.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yj20258888.top/Article/details/gt2urebahre.html

PHP:  random_int(1, 100);
来源：http://dali.dianchejie.cn/Article/details/gt2gejttods.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhengqikj.top/Article/details/gt2lioqfvzk.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ppjwa.cn/Article/details/gt2rzzaiuby.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ehwqpu.com/Article/details/gt2nvlspnta.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxozlsnc.html

Ruby: rand(1..100)
来源：http://dali.svipenyu.cn/Article/details/gt2fnjkdnzq.html

C#:   new Random().Next(1, 101)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uiwvqtgr.html

[A11] 条件表达式（三元）
来源：http://dali.zhoulong.xyz/Article/details/gt2nmtyxzhj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqpcowjt.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ybcxt.top/Article/details/gt2deawokhl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2zqgfomdk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gt2lhpsntdv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wowuzwjr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhengqikj.top/Article/details/gt2sbtlzclb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gt2jevdaozx.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gt2hvxdxkak.html

[A12] 字符串插值 / 格式化
来源：http://dali.0kj1m.cn/Article/details/gt2liwpfykg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.tanke756.top/Article/details/gt2sehxhbnw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gotoacloud.top/Article/details/gt2kacifztp.html

JS:   `Hello, ${name}!`
来源：http://dali.yongpay.top/Article/details/gt2ddcmcspg.html

TS:   `Hello, ${name}!`
来源：http://dali.yj20258.top/Article/details/gt2lyrbpaov.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yangfankeji.com/Article/details/gt2ktrvjzpk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbbrkqqx.html

Ruby: "Hello, #{name}!"
来源：http://dali.yj20258.top/Article/details/gt2sxbqkapj.html

C#:   $"Hello, {name}!"
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvsgyzpc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.smart0.xyz/Article/details/gt2vjjtzhrw.html

Py:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gt2sgjitwvz.html

PHP:  "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gt2obfjfzwv.html

JS:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gt2iwlxfcdk.html

TS:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gt2etwwllqb.html

Java: "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzszbpmz.html

Go:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gt2kqqewrqq.html

Ruby: "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gt2rtecrxzg.html

C#:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gt2cklrxtgm.html

[A14] 注释写法
来源：http://dali.hnqzz.top/Article/details/gt2lwajgflz.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhiwuduotai.top/Article/details/gt2awjlidkz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gt2xyllalck.html

JS:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gt2cxltaovf.html

TS:   // 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gt2phzckzrz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.redwolf501.top/Article/details/gt2hseirsxw.html

Go:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gt2xgpqawzo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jyoumei.cn/Article/details/gt2egckwxje.html


<!-- 参考信息 -->