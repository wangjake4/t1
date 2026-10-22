代发 wailian999

[U87] JS：解构默认值
来源：http://dali.ivvv.top/Article/details/gt2oqveaybk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.andypj.xyz/Article/details/gt2dcqezhbb.html

[U88] JS：对象展开合并
来源：http://dali.bjfxy.top/Article/details/gt2arzvjwvm.html

{ ...a, ...b }
来源：http://dali.jqgufenzy.top/Article/details/gt2carnqdqk.html

[U89] JS：数组去重
来源：http://dali.xziqi.cn/Article/details/gt2flusbgji.html

[...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gt2rgfabqbq.html

[U90] JS：数字数组排序
来源：http://dali.ybcxt.top/Article/details/gt2yxiwfnrf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2dmbcmpaz.html

[U91] JS：对象键值遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2soijymun.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hysaishi.cn/Article/details/gt2wvtnspxr.html

[U92] JS：深拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjmejfxk.html

structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2teaqgjtr.html

[U93] JS：模板字符串
来源：http://dali.daria6918.cn/Article/details/gt2qyjasxfh.html

`共 ${n} 条`
来源：http://dali.nanxuanxn.top/Article/details/gt2wijgeqdn.html

[U94] JS：箭头函数
来源：http://dali.wangdashe.top/Article/details/gt2zewkpysy.html

const double = x => x * 2;
来源：http://dali.yangfankeji.com/Article/details/gt2pthxyqck.html

[U95] JS：Promise 包装
来源：http://dali.jiagoushi.top/Article/details/gt2aqsppzij.html

new Promise((resolve, reject) => {})
来源：http://dali.cucudq.cn/Article/details/gt2itktsneu.html

[U96] JS：async/await 与异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjwhhcww.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2hfbwztct.html

[U97] JS：并发请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2acggfjjw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2gowaqqdz.html

[U98] JS：fetch 带 JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2frdllfjy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftuchpwi.html

[U99] JS：事件监听
来源：http://dali.hfpthk.cn/Article/details/gt2nuaawkga.html

el.addEventListener("click", e => {})
来源：http://dali.guannengcc.top/Article/details/gt2hydnmiuf.html

[U100] JS：DOM 查询
来源：http://dali.mhx1999.top/Article/details/gt2cusffcss.html

document.querySelector(".item")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xnyddyta.html

[U101] JS：classList 操作
来源：http://dali.xylfe.cn/Article/details/gt2dmpxnwpz.html

el.classList.toggle("active")
来源：http://dali.cucudq.cn/Article/details/gt2hvirsmft.html

[U102] JS：本地存储
来源：http://dali.dianchejie.cn/Article/details/gt2fbqhtqih.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yuanzhike.top/Article/details/gt2bxlzmwcj.html

[U103] JS：定时器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aszsfvvz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhixingplan.top/Article/details/gt2uwmsnsrt.html

[U104] JS：防抖
来源：http://dali.gzhubu.top/Article/details/gt2liupxkfc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gt2hgmokwvp.html

[U105] JS：节流
来源：http://dali.c1oappe.top/Article/details/gt2penzxwvy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yvedp.cn/Article/details/gt2nxbjqnwo.html

[U106] JS：日期格式化
来源：http://dali.cdnleiting.top/Article/details/gt2ontuuizw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.guannengcc.top/Article/details/gt2unbvwsph.html

[U107] JS：数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gt2esqrbdjr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gt2idpoftmi.html

[U108] JS：随机整数
来源：http://dali.sweek.top/Article/details/gt2pansezdk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gt2gbkrfkhr.html

[U109] JS：数组分组
来源：http://dali.ivvv.top/Article/details/gt2soqicaqh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gt2vbaqepxd.html

[U110] JS：数组分块
来源：http://dali.pycfn.com/Article/details/gt2jqpenjqt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghmjrffj.html

[U111] JS：对象转 Map
来源：http://dali.smart0.xyz/Article/details/gt2iuqlghgr.html

new Map(Object.entries(obj))
来源：http://dali.quarkkingdee.top/Article/details/gt2foixrlre.html

[U112] JS：字符串补位
来源：http://dali.hywenlv.cn/Article/details/gt2kuzahcon.html

"7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2qqnqlskb.html

[U113] JS：正则替换全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yaejpzvx.html

s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2wornrkbm.html

[U114] JS：JSON 深比较
来源：http://dali.cdnleiting.top/Article/details/gt2eyldppqq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gt2ordgvhxx.html

[U115] JS：生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gt2ilfspxni.html

crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2ohjwwncq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daxiang520.top/Article/details/gt2wlkjbiab.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gt2rnsbtekj.html

[U117] JS：单元测试
来源：http://dali.fengsongda.top/Article/details/gt2jzfqrzve.html

npm i -D vitest;  npx vitest
来源：http://dali.gogol.net.cn/Article/details/gt2hmpjjemg.html

[U118] JS：开发服务器
来源：http://dali.ydzc1.top/Article/details/gt2uxvivzwl.html

npm i -D vite;  npx vite
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxjvmpbo.html

[U119] JS：生产构建
来源：http://dali.dashuyun.cn/Article/details/gt2xxmwadim.html

npx vite build
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukgpqupu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xinyue.icu/Article/details/gt2owvlrtjt.html

import.meta.env.VITE_API_URL
来源：http://dali.kuanghao11.cn/Article/details/gt2zkxsrjjo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2bnubngsx.html

统计汇总
来源：http://dali.pengpengdd.cyou/Article/details/gt2acluhzaa.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2fcerznos.html

按语言统计（条）：
来源：http://dali.sweek.top/Article/details/gt2pufedqrp.html

Python ......... 252
来源：http://dali.ydzc1.top/Article/details/gt2tkecbcnx.html

PHP ............ 252
来源：http://dali.gzhubu.top/Article/details/gt2ifzaxmlf.html

JavaScript ..... 252
来源：http://dali.nanxuanxn.top/Article/details/gt2blqxpyyv.html

TypeScript ..... 212
来源：http://dali.guowangkeji.top/Article/details/gt2fmnyhlir.html

Java ........... 212
来源：http://dali.yangfankeji.com/Article/details/gt2dqlojypt.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gt2xvkvgqry.html

Ruby ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upwfyikv.html

C# ............. 212
来源：http://dali.smart0.xyz/Article/details/gt2uqhujbjs.html

C .............. 30
来源：http://dali.yuanzhike.top/Article/details/gt2onkretqj.html

C++ ............ 30
来源：http://dali.ppjwa.cn/Article/details/gt2trttpypv.html

SQL ............ 90
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oshmaxsk.html

Bash ........... 80
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2diarlliq.html

Kotlin ......... 15
来源：http://dali.jiagoushi.top/Article/details/gt2nirssrcc.html

Swift .......... 15
来源：http://dali.dianchejie.cn/Article/details/gt2akdlxvfr.html

Lua ............ 10
来源：http://dali.hfpthk.cn/Article/details/gt2mtatobli.html

Perl ........... 10
来源：http://dali.shuidangran.top/Article/details/gt2myqidiqj.html

Scala .......... 10
来源：http://dali.feifeiyinyue.top/Article/details/gt2knqnxsjb.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2zsltldue.html

合计 ........... 2106 条
来源：http://dali.yonumen.top/Article/details/gt2ahekxtac.html

按章节统计：
来源：http://dali.tian-w.cn/Article/details/gt2uojlgvsm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gt2yzrkeeie.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xetfxjlk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gt2dzklaqin.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.tianlin.xyz/Article/details/gt2pvcrkyui.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.9152youxi.cn/Article/details/gt2mdezbbdf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tian-w.cn/Article/details/gt2fbsnmkpz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gt2lrtbzqhm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gt2onlttqiy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gt2ndkpdhtp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gt2kvveonbk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2oppzdzqx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2atbwbytl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gt2tuockoil.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shuidangran.top/Article/details/gt2oxtajblt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzwintoo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2exxnzdbb.html

Q SQL 专题                              90
来源：http://dali.hnqzz.top/Article/details/gt2bbsgiomj.html

R Bash 专题                             80
来源：http://dali.ehwqpu.com/Article/details/gt2cacjftxv.html

S C / C++ 专题                          60
来源：http://dali.xziqi.cn/Article/details/gt2pvtbyroj.html

T 其他语言补充                          60
来源：http://dali.fengsongda.top/Article/details/gt2qenhiagg.html

U 高频实用片段                         120
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmqvawcf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qzromjcq.html

合计                                  2106 条
来源：http://dali.hnqzz.top/Article/details/gt2dsrrrsgv.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gt2rslomsog.html

使用提醒
来源：http://dali.tanke756.top/Article/details/gt2diiflyaz.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gt2folyolxv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cashguo.top/Article/details/gt2lfyhijeh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lsgwmltw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.nanxinkj.top/Article/details/gt2jznhpnge.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuanzx.com/Article/details/gt2qietxjff.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigufen.top/Article/details/gt2ismeolcp.html

—— 文件结束 ——
来源：http://dali.redwolf501.top/Article/details/gt2lsrdsfoz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2rbxmvlvt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gogol.net.cn/Article/details/gt2xcopiycz.html

Common Programming Examples Cheat Book
来源：http://dali.gzhubu.top/Article/details/gt2esfhfldl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2nndielfw.html

【收录内容】
来源：http://dali.jiagoushi.top/Article/details/gt2pxhhfora.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yanxiufei.cn/Article/details/gt2gnsnnfjn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gt2gusbljwi.html

SQL · Bash · C · C++
来源：http://dali.hnqzz.top/Article/details/gt2hfxbavwb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.smart0.xyz/Article/details/gt2juqniuij.html

【使用说明】
来源：http://dali.yj202588.top/Article/details/gt2evnlclvw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ppjwa.cn/Article/details/gt2pxkqcmay.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.vqdsnc.cn/Article/details/gt2kwmxwsyz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.fengsongda.top/Article/details/gt2wjfletxo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yangfankeji.com/Article/details/gt2pimsfdhx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nanxinkj.top/Article/details/gt2yxsguqpd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.feifeiyinyue.top/Article/details/gt2zuokbobc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.svipenyu.cn/Article/details/gt2zctwodyg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.aibaodan.cn/Article/details/gt2nxnjczcn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.dianchejie.cn/Article/details/gt2kecmxnfk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sufxvd.cn/Article/details/gt2ohzbvdas.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cqqwz.cn/Article/details/gt2twhuehxl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ydzc1.top/Article/details/gt2cupikocu.html

【文件统计】
来源：http://dali.hammf.cn/Article/details/gt2gsfwgeru.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhixingplan.top/Article/details/gt2rtnfqspp.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gt2bcarigwq.html

目  录
来源：http://dali.zhiwuduotai.top/Article/details/gt2euemgatf.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gt2bqlrhhbl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cqqwz.cn/Article/details/gt2dnznxker.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinqigufen.top/Article/details/gt2ttxnnnip.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gt2xpstcnlk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ybcxt.top/Article/details/gt2eeajnivm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hywenlv.cn/Article/details/gt2jgacxprz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gt2powwrybt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gt2cvyjyalh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kigkuuzs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2lyarbbou.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gt2tahtsngw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gt2fsjigttl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gt2rbpncdjb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2yltndymg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sufxvd.cn/Article/details/gt2yuimqxni.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.daxiang520.top/Article/details/gt2zuvfeiwb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gt2fyhuhmhw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ybcxt.top/Article/details/gt2lrhtoqym.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258888.top/Article/details/gt2nkrlccyv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nizorrir.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgsshesz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gt2ukrnpkqx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2tvonbsmi.html

A. 基础语法与类型
来源：http://dali.nanxinkj.top/Article/details/gt2yhkusisk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2oiehveka.html

[A01] Hello World
来源：http://dali.nwbrower.top/Article/details/gt2lhsdymeu.html

Py:   print("Hello, World!")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltqhhflb.html

PHP:  echo "Hello, World!";
来源：http://dali.jqgfzy.top/Article/details/gt2hjrlyxgs.html

JS:   console.log("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gt2njcolhhf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhoulong.xyz/Article/details/gt2oqjgusek.html

Java: System.out.println("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gt2dhpfpwji.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gt2guofhdur.html

Ruby: puts "Hello, World!"
来源：http://dali.dianchejie.cn/Article/details/gt2dgzcujio.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gt2pcojgtxw.html

[A02] 变量声明与赋值
来源：http://dali.0kj1m.cn/Article/details/gt2xffwyzto.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.mhx1999.top/Article/details/gt2hunkvsru.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.andypj.xyz/Article/details/gt2vblwwyjb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jyoumei.cn/Article/details/gt2cobusoff.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmkinndc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhengqikj.top/Article/details/gt2vosfvgms.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhixingplan.top/Article/details/gt2teyihmth.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aizwys.cn/Article/details/gt2tiefqtdi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.bjfxy.top/Article/details/gt2tyqvajic.html

[A03] 常量定义
来源：http://dali.zycfv.cn/Article/details/gt2pmqxvhvv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cheryme.top/Article/details/gt2zdgguawv.html

PHP:  const PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2jpqqnsuf.html

JS:   const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2oiviryst.html

TS:   const PI: number = 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2sfrqzxoz.html

Java: static final double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2pmggxsmz.html

Go:   const PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gt2kziembbg.html

Ruby: PI = 3.14159
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzyycbpg.html

C#:   const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2xfvtvrut.html

[A04] 判断变量类型
来源：http://dali.jlsjyb.cn/Article/details/gt2jcfwgwrn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuxming.cn/Article/details/gt2cotljzdm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xinyue.icu/Article/details/gt2sqkkbytr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pengpengdd.cyou/Article/details/gt2lelblnzt.html

TS:   typeof x; x instanceof Date
来源：http://dali.haohaochexian.top/Article/details/gt2ioqsywzy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hfpthk.cn/Article/details/gt2daxgcsul.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.fzhhl.top/Article/details/gt2ohpiezua.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.kuanghao11.cn/Article/details/gt2mgpmscsd.html

C#:   x.GetType().Name; x is int
来源：http://dali.bjfxy.top/Article/details/gt2ebssurhr.html

[A05] 整数除法与取模
来源：http://dali.quarkkingdee.top/Article/details/gt2wshdukyd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ehwqpu.com/Article/details/gt2qwcchzom.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2gwiorusa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gt2hokslptr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gt2lwvrjvwv.html

Java: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2wcnidvdv.html

Go:   7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gt2vxgjurdp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gt2mfpyuilx.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2gexpknjq.html

[A06] 字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gt2yihklglw.html

Py:   int("42"); float("3.14")
来源：http://dali.dashuyun.cn/Article/details/gt2wcsihdds.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.pycfn.com/Article/details/gt2ewtzqwes.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sysykeji.top/Article/details/gt2frpggnyc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xziqi.cn/Article/details/gt2drdsfhsn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cqqwz.cn/Article/details/gt2tbqgjnce.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hnxiangtu.top/Article/details/gt2twuzlozc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ydzc1.top/Article/details/gt2bvmunncl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yuxming.cn/Article/details/gt2relqswfq.html

[A07] 数字转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpivhawi.html

Py:   str(42)
来源：http://dali.zycfv.cn/Article/details/gt2fpfxebbq.html

PHP:  (string) 42; strval(42)
来源：http://dali.gotoacloud.top/Article/details/gt2bacnivfp.html

JS:   String(42); (42).toString()
来源：http://dali.cucudq.cn/Article/details/gt2ojgutfmo.html

TS:   String(42)
来源：http://dali.yueranfly.top/Article/details/gt2tewcpbng.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yonumen.top/Article/details/gt2lhqvglob.html

Go:   strconv.Itoa(42)
来源：http://dali.ehwqpu.com/Article/details/gt2oouavuie.html

Ruby: 42.to_s
来源：http://dali.jlsjyb.cn/Article/details/gt2tqnhbafm.html

C#:   42.ToString()
来源：http://dali.yj20258.top/Article/details/gt2lmyagryd.html

[A08] 取整与四舍五入
来源：http://dali.jqgfzy.top/Article/details/gt2qwisacgg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2prdqukvb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yonumen.top/Article/details/gt2tpirrlma.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gt2yrenpaef.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eijculkb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gt2zbwjkkxi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gt2thatvyms.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj202588.top/Article/details/gt2pzfsapni.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gt2veijhnpj.html

[A09] 绝对值与最大最小值
来源：http://dali.chenzaomai.com/Article/details/gt2kdommcdy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2ooyeidqg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2vxxbjazm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2peernxeb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2fxhsvoej.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2yiwoknxa.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.guowangkeji.top/Article/details/gt2uxxuvyzn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.dianchejie.cn/Article/details/gt2pmutmrwe.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gkuounkz.html

[A10] 生成随机数
来源：http://dali.daxiang520.top/Article/details/gt2clrrlluw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhengqikj.top/Article/details/gt2hthamwoh.html

PHP:  random_int(1, 100);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lyqtnvui.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srzpwkza.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guannengcc.top/Article/details/gt2dpddhgmq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.0kj1m.cn/Article/details/gt2erpqlwoo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cashguo.top/Article/details/gt2sukffepx.html

Ruby: rand(1..100)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtmsvhfn.html

C#:   new Random().Next(1, 101)
来源：http://dali.ybcxt.top/Article/details/gt2icptoroz.html

[A11] 条件表达式（三元）
来源：http://dali.smart0.xyz/Article/details/gt2vqnpznkt.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.wangdashe.top/Article/details/gt2khftmatn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gt2iwepqqqh.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovcotjnf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gt2mukogrlc.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gt2bzjwccxo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj202588.top/Article/details/gt2tsfkhwvc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gt2uhaxeagm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnniruog.html

[A12] 字符串插值 / 格式化
来源：http://dali.hnqzz.top/Article/details/gt2ttogorur.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cdnleiting.top/Article/details/gt2lbdxdsja.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.c1oappe.top/Article/details/gt2zqlimlhy.html

JS:   `Hello, ${name}!`
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyswcaym.html

TS:   `Hello, ${name}!`
来源：http://dali.hnxiangtu.top/Article/details/gt2kisnjzkc.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.nwbrower.top/Article/details/gt2exgvwpah.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenzaomai.com/Article/details/gt2lrfdxalz.html

Ruby: "Hello, #{name}!"
来源：http://dali.havefunace.top/Article/details/gt2zgqhkfjj.html

C#:   $"Hello, {name}!"
来源：http://dali.zdqjudy.top/Article/details/gt2fophvkck.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ivvv.top/Article/details/gt2ekngqwbi.html

Py:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2gpurcppg.html

PHP:  "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gt2wtrnpqcx.html

JS:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gt2pkieyugg.html

TS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2awqgknjk.html

Java: "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gt2skguquve.html

Go:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yooosttb.html

Ruby: "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gt2actdojsl.html

C#:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gt2jrhfzrze.html

[A14] 注释写法
来源：http://dali.yuanzhike.top/Article/details/gt2vohgckry.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zdqjudy.top/Article/details/gt2cnncreum.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbxmzqpb.html

JS:   // 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gt2wdnqoktk.html

TS:   // 单行；/* 多行 */
来源：http://dali.svipenyu.cn/Article/details/gt2jvpihlwr.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sxryk.cn/Article/details/gt2rlasftvd.html

Go:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gt2gqeqedii.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yonumen.top/Article/details/gt2qmcecmgk.html


<!-- 参考信息 -->