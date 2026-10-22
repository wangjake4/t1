代发 wailian999

[U87] JS：解构默认值
来源：http://dali.zhiwuduotai.top/Article/details/gt2scuuvzim.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hywenlv.cn/Article/details/gt2tzufnnme.html

[U88] JS：对象展开合并
来源：http://dali.jlsjyb.cn/Article/details/gt2temtpynl.html

{ ...a, ...b }
来源：http://dali.fzhhl.top/Article/details/gt2kfowheti.html

[U89] JS：数组去重
来源：http://dali.quarkkingdee.top/Article/details/gt2pqwndbib.html

[...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2qwhmnwes.html

[U90] JS：数字数组排序
来源：http://dali.kuanghao11.cn/Article/details/gt2fvphyycb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2gdzwoumt.html

[U91] JS：对象键值遍历
来源：http://dali.ydzc1.top/Article/details/gt2enesexdf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jianghu66.top/Article/details/gt2fhnptuys.html

[U92] JS：深拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2tqahpial.html

structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2btafhayr.html

[U93] JS：模板字符串
来源：http://dali.fzhhl.top/Article/details/gt2fmfpevqe.html

`共 ${n} 条`
来源：http://dali.hysaishi.cn/Article/details/gt2cnpdtmie.html

[U94] JS：箭头函数
来源：http://dali.yj202588.top/Article/details/gt2qlngyjrq.html

const double = x => x * 2;
来源：http://dali.mhx1999.top/Article/details/gt2vlalfrzk.html

[U95] JS：Promise 包装
来源：http://dali.jinqigufen.top/Article/details/gt2dgurceak.html

new Promise((resolve, reject) => {})
来源：http://dali.yj202588.top/Article/details/gt2aqcxwoxy.html

[U96] JS：async/await 与异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqvfjixu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gt2tliwekxs.html

[U97] JS：并发请求
来源：http://dali.smart0.xyz/Article/details/gt2moupggxo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2kuzhsolg.html

[U98] JS：fetch 带 JSON
来源：http://dali.xinyue.icu/Article/details/gt2tyulnfwj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shzxlz.cn/Article/details/gt2hbklcbil.html

[U99] JS：事件监听
来源：http://dali.cdnleiting.top/Article/details/gt2qwjemwza.html

el.addEventListener("click", e => {})
来源：http://dali.birdmap.top/Article/details/gt2pgclihhf.html

[U100] JS：DOM 查询
来源：http://dali.cashguo.top/Article/details/gt2cizletgp.html

document.querySelector(".item")
来源：http://dali.haohaochexian.top/Article/details/gt2ksvinwcq.html

[U101] JS：classList 操作
来源：http://dali.316326.xyz/Article/details/gt2lkhnwzfq.html

el.classList.toggle("active")
来源：http://dali.tanke756.top/Article/details/gt2pkekfhdc.html

[U102] JS：本地存储
来源：http://dali.xuetiantiany.cn/Article/details/gt2prdhzzcj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gt2yscvfico.html

[U103] JS：定时器
来源：http://dali.havefunace.top/Article/details/gt2pbvmctha.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhixingplan.top/Article/details/gt2kuvtqxxi.html

[U104] JS：防抖
来源：http://dali.fzhhl.top/Article/details/gt2vpjmlkun.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2gcoxlyzy.html

[U105] JS：节流
来源：http://dali.xinyue.icu/Article/details/gt2rssevbyc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.0kj1m.cn/Article/details/gt2hbosvpzf.html

[U106] JS：日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2plkhqdqn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.guowangkeji.top/Article/details/gt2utwmtnxx.html

[U107] JS：数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbqdxaso.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzixqujc.html

[U108] JS：随机整数
来源：http://dali.tian-w.cn/Article/details/gt2ofxujbaw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dashuyun.cn/Article/details/gt2prrhyyoq.html

[U109] JS：数组分组
来源：http://dali.snrcjt.cn/Article/details/gt2wjoahsdi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqiszofo.html

[U110] JS：数组分块
来源：http://dali.daria6918.cn/Article/details/gt2lgrcwwke.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.iojbl.cn/Article/details/gt2lkhqysuv.html

[U111] JS：对象转 Map
来源：http://dali.yonumen.top/Article/details/gt2mcgjfble.html

new Map(Object.entries(obj))
来源：http://dali.yvedp.cn/Article/details/gt2yspwzqby.html

[U112] JS：字符串补位
来源：http://dali.haohaochexian.top/Article/details/gt2lxoelnvr.html

"7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2iolqwagx.html

[U113] JS：正则替换全部
来源：http://dali.ybcxt.top/Article/details/gt2tripxkpv.html

s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2qyldtaoo.html

[U114] JS：JSON 深比较
来源：http://dali.hfpthk.cn/Article/details/gt2iwxbhzoi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gt2idrjdkja.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gt2lctrbtxo.html

crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2ntvrdgmy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wvmncenp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yueranfly.top/Article/details/gt2ottdgrdu.html

[U117] JS：单元测试
来源：http://dali.cheryme.top/Article/details/gt2csadvjco.html

npm i -D vitest;  npx vitest
来源：http://dali.316326.xyz/Article/details/gt2edpbezav.html

[U118] JS：开发服务器
来源：http://dali.andypj.xyz/Article/details/gt2xezkghzq.html

npm i -D vite;  npx vite
来源：http://dali.nanxuanxn.top/Article/details/gt2expxfohk.html

[U119] JS：生产构建
来源：http://dali.aizwys.cn/Article/details/gt2kflbkkph.html

npx vite build
来源：http://dali.nanxinkj.top/Article/details/gt2mudlohvd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fengsongda.top/Article/details/gt2ellzpetz.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigufen.top/Article/details/gt2eszybgbx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2rnwsukrd.html

统计汇总
来源：http://dali.0kj1m.cn/Article/details/gt2ilstlhio.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2tupffwmm.html

按语言统计（条）：
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2innrbkqy.html

Python ......... 252
来源：http://dali.sysykeji.top/Article/details/gt2uttvmwls.html

PHP ............ 252
来源：http://dali.tian-w.cn/Article/details/gt2ytjlmsjp.html

JavaScript ..... 252
来源：http://dali.kuanghao11.cn/Article/details/gt2xaxqykjt.html

TypeScript ..... 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2woeotpti.html

Java ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gt2tzctiril.html

Go ............. 212
来源：http://dali.jiagoushi.top/Article/details/gt2aqdhbnsa.html

Ruby ........... 212
来源：http://dali.jyoumei.cn/Article/details/gt2vgkikjgw.html

C# ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gt2bnuoikss.html

C .............. 30
来源：http://dali.nanxuanxn.top/Article/details/gt2fvrcrjuf.html

C++ ............ 30
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikkndrtl.html

SQL ............ 90
来源：http://dali.zhiwuduotai.top/Article/details/gt2zaplhdgp.html

Bash ........... 80
来源：http://dali.jqgufenzy.top/Article/details/gt2aiaafzxz.html

Kotlin ......... 15
来源：http://dali.sweek.top/Article/details/gt2afxemmja.html

Swift .......... 15
来源：http://dali.hywenlv.cn/Article/details/gt2rrjfcgyk.html

Lua ............ 10
来源：http://dali.dianchejie.cn/Article/details/gt2pevhwbgw.html

Perl ........... 10
来源：http://dali.jiagoushi.top/Article/details/gt2nikhewlf.html

Scala .......... 10
来源：http://dali.xinyue.icu/Article/details/gt2rqncbxof.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2ytlbpdha.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gt2adnyuivx.html

按章节统计：
来源：http://dali.zdqjudy.top/Article/details/gt2buyfpmti.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gt2wagjpuip.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gt2ryhkjlnk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gt2idjjcdvp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vhuimmhb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aibaodan.cn/Article/details/gt2hvcybbui.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gt2cezhvzua.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gt2avdcukzw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqinkitf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2sxzukuek.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gt2yckyhxtg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gt2vybsukqt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gt2gdwabucr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfqkarpa.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gt2nqpwshur.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.aibaodan.cn/Article/details/gt2reznvzsz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2fhyqbexs.html

Q SQL 专题                              90
来源：http://dali.guowangkeji.top/Article/details/gt2wrdfyaow.html

R Bash 专题                             80
来源：http://dali.jqgufenzy.top/Article/details/gt2emwwflvl.html

S C / C++ 专题                          60
来源：http://dali.gotoacloud.top/Article/details/gt2bsttqpti.html

T 其他语言补充                          60
来源：http://dali.dashuyun.cn/Article/details/gt2rwtvsdzk.html

U 高频实用片段                         120
来源：http://dali.birdmap.top/Article/details/gt2apvlasqt.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gt2avurtjtq.html

合计                                  2106 条
来源：http://dali.dianchejie.cn/Article/details/gt2kmapwimd.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2iugssjwq.html

使用提醒
来源：http://dali.tanke756.top/Article/details/gt2artvtwsa.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2lyzmulwo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gt2psosdgud.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sweek.top/Article/details/gt2oqmfwagl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.iojbl.cn/Article/details/gt2xlwekqgx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gt2kwpmmfgs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhoulong.xyz/Article/details/gt2rdhvxwiz.html

—— 文件结束 ——
来源：http://dali.jyoumei.cn/Article/details/gt2pcatedtn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ivuhgjev.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cqqwz.cn/Article/details/gt2cziajyka.html

Common Programming Examples Cheat Book
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubpyyzlp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2rnnjblin.html

【收录内容】
来源：http://dali.birdmap.top/Article/details/gt2adlvuahv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shuidangran.top/Article/details/gt2hldbtfbj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daria6918.cn/Article/details/gt2cfonnndj.html

SQL · Bash · C · C++
来源：http://dali.nanxuanxn.top/Article/details/gt2kzgigcik.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbipvgpb.html

【使用说明】
来源：http://dali.jiagoushi.top/Article/details/gt2agksjftr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hnqzz.top/Article/details/gt2tdmblwdr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqfjarfb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cdnleiting.top/Article/details/gt2mwrdlfkg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.svipenyu.cn/Article/details/gt2psdogswr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hnqzz.top/Article/details/gt2ieiupfro.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yuxming.cn/Article/details/gt2nhmyhesk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yvedp.cn/Article/details/gt2uwncpctt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daria6918.cn/Article/details/gt2tezrcnrk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.svipenyu.cn/Article/details/gt2ishuyypn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jlsjyb.cn/Article/details/gt2ohfeowpb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdzuxpok.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinqigufen.top/Article/details/gt2gmrnfvry.html

【文件统计】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btopdrvk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqfwterj.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gt2ouwmtqib.html

目  录
来源：http://dali.gzhubu.top/Article/details/gt2suqmxhsw.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gt2bmsjcoow.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gt2taliwvfh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.daxiang520.top/Article/details/gt2afgxtylo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gt2kxmwxckh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gt2yckqwmch.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ehwqpu.com/Article/details/gt2fimtenjb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gt2ntnrqiij.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gt2ksaspbog.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aibaodan.cn/Article/details/gt2rtrckmwh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2kffeyhxi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxkwuvzc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tkumktmc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2pyafjlls.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gt2mbiqgfuj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gt2pabhfdzq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.daxiang520.top/Article/details/gt2dauwwbgv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfcaiblk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zycfv.cn/Article/details/gt2emnimvri.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hnqzz.top/Article/details/gt2hcbibbkf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aibaodan.cn/Article/details/gt2jtujgzcn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gt2usqqsebu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcliybwk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2vglcydkn.html

A. 基础语法与类型
来源：http://dali.c1oappe.top/Article/details/gt2gvvkrlzd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ypjoyklv.html

[A01] Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2htypaadb.html

Py:   print("Hello, World!")
来源：http://dali.zycfv.cn/Article/details/gt2ltyzhrwu.html

PHP:  echo "Hello, World!";
来源：http://dali.iojbl.cn/Article/details/gt2ekgmrywi.html

JS:   console.log("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gt2enjunfqi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cqqwz.cn/Article/details/gt2qsfkobus.html

Java: System.out.println("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gt2qllewyfq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gt2tfbumsgt.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgufenzy.top/Article/details/gt2eqgwilfr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhengqikj.top/Article/details/gt2nrywkhcm.html

[A02] 变量声明与赋值
来源：http://dali.yueranfly.top/Article/details/gt2quieesbb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sysykeji.top/Article/details/gt2uydimrpr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cdnleiting.top/Article/details/gt2ozumacic.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yuxming.cn/Article/details/gt2zwcydkrj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sxryk.cn/Article/details/gt2yazttizh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gt2fidxvbbn.html

Go:   name := "Alex"; age := 20
来源：http://dali.pycfn.com/Article/details/gt2pjcztupn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yonumen.top/Article/details/gt2iifxthou.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ydzc1.top/Article/details/gt2aeatkeks.html

[A03] 常量定义
来源：http://dali.pycfn.com/Article/details/gt2qfrbozyt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daria6918.cn/Article/details/gt2jgatkghv.html

PHP:  const PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wxwwcghx.html

JS:   const PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2uaagusnf.html

TS:   const PI: number = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2izvsswap.html

Java: static final double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2mrrvnaxc.html

Go:   const PI = 3.14159
来源：http://dali.jqgufenzy.top/Article/details/gt2ychiemyb.html

Ruby: PI = 3.14159
来源：http://dali.iojbl.cn/Article/details/gt2rjwxorec.html

C#:   const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2triwfxyf.html

[A04] 判断变量类型
来源：http://dali.redwolf501.top/Article/details/gt2lyaprfxj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yangfankeji.com/Article/details/gt2jcrbmlwd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhongyouzk.top/Article/details/gt2qxkreddo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tian-w.cn/Article/details/gt2wpetihlp.html

TS:   typeof x; x instanceof Date
来源：http://dali.ivvv.top/Article/details/gt2wywosnhq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jyoumei.cn/Article/details/gt2eymxboew.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xinyue.icu/Article/details/gt2itusmgie.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.meibo888.top/Article/details/gt2hzruelfh.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxsclapw.html

[A05] 整数除法与取模
来源：http://dali.jlsjyb.cn/Article/details/gt2lfiuzhve.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgufenzy.top/Article/details/gt2dcdpmpqx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gt2lvszbzgd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.smart0.xyz/Article/details/gt2qggquesc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2adqftogf.html

Java: 7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2zampabwp.html

Go:   7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gt2jbiikpee.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gt2ymbgngdw.html

C#:   7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2gaiwfwkb.html

[A06] 字符串转数字
来源：http://dali.ivvv.top/Article/details/gt2vmjlsvko.html

Py:   int("42"); float("3.14")
来源：http://dali.hfpthk.cn/Article/details/gt2yqayxfmo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yangfankeji.com/Article/details/gt2dktvyewc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jyoumei.cn/Article/details/gt2joyzymrn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenlongwang.top/Article/details/gt2ecuskger.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.iojbl.cn/Article/details/gt2yqedyzgr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.chenzaomai.com/Article/details/gt2wwawzyon.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cashguo.top/Article/details/gt2mopfdlxw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gt2njeohyqn.html

[A07] 数字转字符串
来源：http://dali.iojbl.cn/Article/details/gt2fturzcmw.html

Py:   str(42)
来源：http://dali.gogol.net.cn/Article/details/gt2adgufkvn.html

PHP:  (string) 42; strval(42)
来源：http://dali.xinyue.icu/Article/details/gt2dbvjfyhn.html

JS:   String(42); (42).toString()
来源：http://dali.chenzaomai.com/Article/details/gt2gjnjerpn.html

TS:   String(42)
来源：http://dali.jinqigfzy.top/Article/details/gt2yoocuhdb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ydzc1.top/Article/details/gt2shfohlgs.html

Go:   strconv.Itoa(42)
来源：http://dali.kuanghao11.cn/Article/details/gt2hhxoymiw.html

Ruby: 42.to_s
来源：http://dali.chenzaomai.com/Article/details/gt2fekfqsvk.html

C#:   42.ToString()
来源：http://dali.zhengqikj.top/Article/details/gt2qqzfjayk.html

[A08] 取整与四舍五入
来源：http://dali.tanke756.top/Article/details/gt2gxvshtex.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gt2peotfeef.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tian-w.cn/Article/details/gt2vyznpxqo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cheryme.top/Article/details/gt2spswwjuz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenlongwang.top/Article/details/gt2bmlirkvs.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gt2lddoxquj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gt2csdxzbth.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.guowangkeji.top/Article/details/gt2yfnhcael.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gt2uflauaoy.html

[A09] 绝对值与最大最小值
来源：http://dali.haohaochexian.top/Article/details/gt2laarclry.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xinyue.icu/Article/details/gt2cltlndbr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2lomddgdm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxaupfce.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2ivtvwosw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gt2cmgpzamj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cucudq.cn/Article/details/gt2ejvhxbvu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jqgfzy.top/Article/details/gt2yefrmsbp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2feffuxfk.html

[A10] 生成随机数
来源：http://dali.c1oappe.top/Article/details/gt2mamfldhb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cqqwz.cn/Article/details/gt2ycjlqbdi.html

PHP:  random_int(1, 100);
来源：http://dali.cheryme.top/Article/details/gt2tukczbmp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258888.top/Article/details/gt2uyjbaswm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cucudq.cn/Article/details/gt2mrgotbad.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hnxiangtu.top/Article/details/gt2lulimrbq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sysykeji.top/Article/details/gt2moyrymtx.html

Ruby: rand(1..100)
来源：http://dali.jiagoushi.top/Article/details/gt2badevbry.html

C#:   new Random().Next(1, 101)
来源：http://dali.cdnleiting.top/Article/details/gt2lbjkgxzu.html

[A11] 条件表达式（三元）
来源：http://dali.nwbrower.top/Article/details/gt2mxxgwzlm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cdnleiting.top/Article/details/gt2sritzwlu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gt2yvqmdwmo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nkgdunie.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hurgmcxq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gt2wkejpdze.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.sweek.top/Article/details/gt2wkpdthgr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gt2itoqvcwm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gt2ymoixcla.html

[A12] 字符串插值 / 格式化
来源：http://dali.hammf.cn/Article/details/gt2iyqbqeif.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ehwqpu.com/Article/details/gt2vvvomvjn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xziqi.cn/Article/details/gt2cztybbqo.html

JS:   `Hello, ${name}!`
来源：http://dali.tianlin.xyz/Article/details/gt2jojzhtiu.html

TS:   `Hello, ${name}!`
来源：http://dali.gaohongyu789.top/Article/details/gt2yewnuhln.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cashguo.top/Article/details/gt2uidjfobi.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.tian-w.cn/Article/details/gt2ihgemdwy.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npuhxkta.html

C#:   $"Hello, {name}!"
来源：http://dali.gogol.net.cn/Article/details/gt2loreeytc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.tianlin.xyz/Article/details/gt2wuxltkbz.html

Py:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2nhervxzm.html

PHP:  "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gt2dbulzbnc.html

JS:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gt2wreycolc.html

TS:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gt2etpahbcu.html

Java: "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2udjuhbnm.html

Go:   "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gt2cygdtgzr.html

Ruby: "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gt2klexjvdu.html

C#:   "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gt2setrjwfu.html

[A14] 注释写法
来源：http://dali.zhoulong.xyz/Article/details/gt2wcoktkkm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.wangshuangyany.cn/Article/details/gt2focguoqn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gt2gvdloits.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mjksxelc.html

TS:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gt2tsuafgne.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtpxtpaw.html

Go:   // 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gt2utelwbwl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xuanzx.com/Article/details/gt2ezsuoyby.html


<!-- 参考信息 -->