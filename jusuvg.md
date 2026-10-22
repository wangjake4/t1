代发 wailian999

[U89] JS：数组去重
来源：http://dali.hfpthk.cn/Article/details/gt2aqeujxzo.html

[...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gt2ibrorlhk.html

[U90] JS：数字数组排序
来源：http://dali.bjfxy.top/Article/details/gt2fnchmcqh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2jhgijtnt.html

[U91] JS：对象键值遍历
来源：http://dali.cqqwz.cn/Article/details/gt2hyfnwerb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hnxiangtu.top/Article/details/gt2mdqknlpw.html

[U92] JS：深拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2dlebyilw.html

structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2mibshjyu.html

[U93] JS：模板字符串
来源：http://dali.guannengcc.top/Article/details/gt2sneakmvd.html

`共 ${n} 条`
来源：http://dali.ehwqpu.com/Article/details/gt2thfirfrt.html

[U94] JS：箭头函数
来源：http://dali.aibaodan.cn/Article/details/gt2iacdteeo.html

const double = x => x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlfhvlmw.html

[U95] JS：Promise 包装
来源：http://dali.smart0.xyz/Article/details/gt2chcjqepm.html

new Promise((resolve, reject) => {})
来源：http://dali.jinqigfzy.top/Article/details/gt2dodozjfk.html

[U96] JS：async/await 与异常
来源：http://dali.yonumen.top/Article/details/gt2xfetvosx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gt2dncseidq.html

[U97] JS：并发请求
来源：http://dali.yangfankeji.com/Article/details/gt2csobdidu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gt2qszijmkv.html

[U98] JS：fetch 带 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nftcuqar.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinqigfzy.top/Article/details/gt2fbvnrayn.html

[U99] JS：事件监听
来源：http://dali.birdmap.top/Article/details/gt2wiiirakm.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258.top/Article/details/gt2ezgkiyvm.html

[U100] JS：DOM 查询
来源：http://dali.gotoacloud.top/Article/details/gt2axsxsshp.html

document.querySelector(".item")
来源：http://dali.yongpay.top/Article/details/gt2coyvrbjo.html

[U101] JS：classList 操作
来源：http://dali.svipenyu.cn/Article/details/gt2dxtklgww.html

el.classList.toggle("active")
来源：http://dali.vqdsnc.cn/Article/details/gt2tvnungco.html

[U102] JS：本地存储
来源：http://dali.sweek.top/Article/details/gt2irtjvuzr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.9152youxi.cn/Article/details/gt2woogovgs.html

[U103] JS：定时器
来源：http://dali.cheryme.top/Article/details/gt2liifrnxn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sweek.top/Article/details/gt2kfapmqvm.html

[U104] JS：防抖
来源：http://dali.gaohongyu789.top/Article/details/gt2ooahjlsn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2xhibkvii.html

[U105] JS：节流
来源：http://dali.ybcxt.top/Article/details/gt2vjlodshf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tian-w.cn/Article/details/gt2hyekqwar.html

[U106] JS：日期格式化
来源：http://dali.guowangkeji.top/Article/details/gt2icslymia.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.9152youxi.cn/Article/details/gt2qdduyrls.html

[U107] JS：数字千分位
来源：http://dali.yuanzhike.top/Article/details/gt2nqnbssjd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xinyue.icu/Article/details/gt2tdtbxxcr.html

[U108] JS：随机整数
来源：http://dali.ydzc1.top/Article/details/gt2vdwvdobi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnxiangtu.top/Article/details/gt2duqpvvhy.html

[U109] JS：数组分组
来源：http://dali.yonumen.top/Article/details/gt2kitflocr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jrjdwnju.html

[U110] JS：数组分块
来源：http://dali.tianlin.xyz/Article/details/gt2kifvftis.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tianlin.xyz/Article/details/gt2tvxbwobd.html

[U111] JS：对象转 Map
来源：http://dali.zhoulong.xyz/Article/details/gt2dngehcbl.html

new Map(Object.entries(obj))
来源：http://dali.ybcxt.top/Article/details/gt2rpausiee.html

[U112] JS：字符串补位
来源：http://dali.mhx1999.top/Article/details/gt2mvsvsgix.html

"7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gt2gnhbopxi.html

[U113] JS：正则替换全部
来源：http://dali.fengsongda.top/Article/details/gt2rblefiyz.html

s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfhldkwn.html

[U114] JS：JSON 深比较
来源：http://dali.xuanzx.com/Article/details/gt2fxwpslfd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubumtyum.html

[U115] JS：生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gt2wegzchzm.html

crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2okztazgy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cdnleiting.top/Article/details/gt2cshhylwf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhengqikj.top/Article/details/gt2fcmwscth.html

[U117] JS：单元测试
来源：http://dali.gzhubu.top/Article/details/gt2urhohllm.html

npm i -D vitest;  npx vitest
来源：http://dali.tanke756.top/Article/details/gt2qqolnrda.html

[U118] JS：开发服务器
来源：http://dali.yanxiufei.cn/Article/details/gt2pqnmwazs.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrvhuab.html

[U119] JS：生产构建
来源：http://dali.cucudq.cn/Article/details/gt2gbzstosk.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gt2huwegfpv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzkiwqjq.html

import.meta.env.VITE_API_URL
来源：http://dali.nwbrower.top/Article/details/gt2lovktzea.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2zdwivbcl.html

统计汇总
来源：http://dali.wangdashe.top/Article/details/gt2aklhfddc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvbgvbsw.html

按语言统计（条）：
来源：http://dali.aizwys.cn/Article/details/gt2flpadndw.html

Python ......... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gseqhnks.html

PHP ............ 252
来源：http://dali.0kj1m.cn/Article/details/gt2nrfyihvm.html

JavaScript ..... 252
来源：http://dali.daria6918.cn/Article/details/gt2tjmfxrpc.html

TypeScript ..... 212
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqrdgphn.html

Java ........... 212
来源：http://dali.sxryk.cn/Article/details/gt2zjehybtk.html

Go ............. 212
来源：http://dali.meibo888.top/Article/details/gt2novdxsor.html

Ruby ........... 212
来源：http://dali.gzhubu.top/Article/details/gt2qbahnnsm.html

C# ............. 212
来源：http://dali.aizwys.cn/Article/details/gt2jhvahdeo.html

C .............. 30
来源：http://dali.daxiang520.top/Article/details/gt2hndkalpa.html

C++ ............ 30
来源：http://dali.zhoulong.xyz/Article/details/gt2acikbuvz.html

SQL ............ 90
来源：http://dali.jlsjyb.cn/Article/details/gt2jaueqyrh.html

Bash ........... 80
来源：http://dali.zhixingplan.top/Article/details/gt2vdwwtaui.html

Kotlin ......... 15
来源：http://dali.cheryme.top/Article/details/gt2fzbbmcnf.html

Swift .......... 15
来源：http://dali.hnqzz.top/Article/details/gt2rctmcxjf.html

Lua ............ 10
来源：http://dali.jqgfzy.top/Article/details/gt2odmwigam.html

Perl ........... 10
来源：http://dali.daxiang520.top/Article/details/gt2xzhdypvj.html

Scala .......... 10
来源：http://dali.gogol.net.cn/Article/details/gt2hfmvotux.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gt2apapxwwc.html

合计 ........... 2106 条
来源：http://dali.jiagoushi.top/Article/details/gt2kuppxghr.html

按章节统计：
来源：http://dali.xylfe.cn/Article/details/gt2ifkjsbpt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.andypj.xyz/Article/details/gt2kcqzqkjs.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gt2himmwpxc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gt2htjlebvo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gt2eqitdvnr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guannengcc.top/Article/details/gt2uibnihcu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rhrtjqvy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gt2evliiwib.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gt2weqigwii.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gt2lrnqedvr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xylfe.cn/Article/details/gt2jysmfsjb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gt2kqempsgw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gt2enzuwfpg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2etczukdx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gt2pmcpfpcu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.9152youxi.cn/Article/details/gt2kqfyoheo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gt2qfropxwz.html

Q SQL 专题                              90
来源：http://dali.zycfv.cn/Article/details/gt2cnawvnhs.html

R Bash 专题                             80
来源：http://dali.ivvv.top/Article/details/gt2mtwkfcvy.html

S C / C++ 专题                          60
来源：http://dali.sysykeji.top/Article/details/gt2lxzfnjtg.html

T 其他语言补充                          60
来源：http://dali.snrcjt.cn/Article/details/gt2zhxjreay.html

U 高频实用片段                         120
来源：http://dali.jiagoushi.top/Article/details/gt2hwucuyyb.html

------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvdhccbp.html

合计                                  2106 条
来源：http://dali.chenjidiqi.icu/Article/details/gt2hiwqukmk.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2ldqikvia.html

使用提醒
来源：http://dali.cdnleiting.top/Article/details/gt2ddlwxgbl.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gt2qkxmqczm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuanzhike.top/Article/details/gt2obtwqfgq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xylfe.cn/Article/details/gt2lxecvvia.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ehwqpu.com/Article/details/gt2xaimcagd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jlsjyb.cn/Article/details/gt2uxkdhiqq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gaohongyu789.top/Article/details/gt2wsnrsnoz.html

—— 文件结束 ——
来源：http://dali.hnxiangtu.top/Article/details/gt2wkvtipws.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2gjfhjgvp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebjyyzlz.html

Common Programming Examples Cheat Book
来源：http://dali.zhongyouzk.top/Article/details/gt2vzihlfop.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2kinvksca.html

【收录内容】
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idkeqxyd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hammf.cn/Article/details/gt2cwdhqvvw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gt2ircptzeq.html

SQL · Bash · C · C++
来源：http://dali.tianlin.xyz/Article/details/gt2mhyzdxcz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hnxiangtu.top/Article/details/gt2vmsmegpq.html

【使用说明】
来源：http://dali.jiagoushi.top/Article/details/gt2wbuycnvv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xuanzx.com/Article/details/gt2fxqqebch.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.guowangkeji.top/Article/details/gt2ywidakwr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.quarkkingdee.top/Article/details/gt2qloumnfv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.smart0.xyz/Article/details/gt2dvfynpeo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkepgfn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gotoacloud.top/Article/details/gt2lyvmwlnk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgsavdhv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fzhhl.top/Article/details/gt2epdwcytf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sozitrli.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cashguo.top/Article/details/gt2ctlbwjew.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jiagoushi.top/Article/details/gt2wxaistnp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yuanzhike.top/Article/details/gt2gutllgew.html

【文件统计】
来源：http://dali.zycfv.cn/Article/details/gt2xhvdcyjq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhiwuduotai.top/Article/details/gt2seadxoae.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gt2pejrcanb.html

目  录
来源：http://dali.yueranfly.top/Article/details/gt2utaliwye.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hskjysja.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqvsybyw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gt2cryfmjgv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gt2rcaswqfd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zdqjudy.top/Article/details/gt2giamasih.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xziqi.cn/Article/details/gt2vnhypoyy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.birdmap.top/Article/details/gt2fnaxbjqk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcqqsmpz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.svipenyu.cn/Article/details/gt2tzhbcwpi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gt2efkubefq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jianghu66.top/Article/details/gt2okweclto.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gt2dxhuuwmq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gt2ztapbkre.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2bybxwgyy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2uchsvzkl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tanke756.top/Article/details/gt2nslhpmsb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gt2gfjiuvbg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tian-w.cn/Article/details/gt2hkqaibza.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2xtqolpvq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oldadhpr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gt2crglywen.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwskwmcz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2uavrqdkd.html

A. 基础语法与类型
来源：http://dali.snrcjt.cn/Article/details/gt2akwynqnk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2uzdswwjg.html

[A01] Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2mfmwozot.html

Py:   print("Hello, World!")
来源：http://dali.yueranfly.top/Article/details/gt2idiirbqj.html

PHP:  echo "Hello, World!";
来源：http://dali.fzhhl.top/Article/details/gt2sclndxfd.html

JS:   console.log("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gt2toyuvjvd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sxryk.cn/Article/details/gt2zsjvrlxx.html

Java: System.out.println("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gt2byyhakgd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj202588.top/Article/details/gt2ceggjrov.html

Ruby: puts "Hello, World!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njqyggpb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yuxming.cn/Article/details/gt2hcctscxh.html

[A02] 变量声明与赋值
来源：http://dali.cdnleiting.top/Article/details/gt2hdlncvvp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cheryme.top/Article/details/gt2hehrewhw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xuanzx.com/Article/details/gt2mmtdjmhy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.iojbl.cn/Article/details/gt2acpoywrd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.nanxinkj.top/Article/details/gt2rwkgpnei.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shuidangran.top/Article/details/gt2mqqsdhrp.html

Go:   name := "Alex"; age := 20
来源：http://dali.birdmap.top/Article/details/gt2spmwndpt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xylfe.cn/Article/details/gt2sraziuem.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqyitxaa.html

[A03] 常量定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzjatggm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ppjwa.cn/Article/details/gt2qjrzepeu.html

PHP:  const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2vwbcemem.html

JS:   const PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yraxsqfb.html

TS:   const PI: number = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2mhyxioqp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2xaldnnkc.html

Go:   const PI = 3.14159
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcrgmanv.html

Ruby: PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gt2kbvuotom.html

C#:   const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2rypgnomr.html

[A04] 判断变量类型
来源：http://dali.xinyue.icu/Article/details/gt2jhcokbla.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.snrcjt.cn/Article/details/gt2ekeqbtow.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.iojbl.cn/Article/details/gt2spqgmotz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.mhx1999.top/Article/details/gt2rruyhyzo.html

TS:   typeof x; x instanceof Date
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbayiply.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.smart0.xyz/Article/details/gt2usegciuh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.svipenyu.cn/Article/details/gt2tvvicnyv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhixingplan.top/Article/details/gt2vxrouxfo.html

C#:   x.GetType().Name; x is int
来源：http://dali.nwbrower.top/Article/details/gt2qygpmcnn.html

[A05] 整数除法与取模
来源：http://dali.zhixingplan.top/Article/details/gt2ovjhykrk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shzxlz.cn/Article/details/gt2xqlcqafm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gt2hkuwkqvs.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2cfhvojbg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.316326.xyz/Article/details/gt2dsimlqkf.html

Java: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2zvyvpiee.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwsmlfhk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gt2rxwbocgy.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gt2zollpoir.html

[A06] 字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gt2ivgngcbo.html

Py:   int("42"); float("3.14")
来源：http://dali.jiagoushi.top/Article/details/gt2jpjjpeon.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.quarkkingdee.top/Article/details/gt2nsnrnsky.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.kuanghao11.cn/Article/details/gt2tjzetnjh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.birdmap.top/Article/details/gt2btbxbxyn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sysykeji.top/Article/details/gt2fnptdpjz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhixingplan.top/Article/details/gt2bpdnmvvt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daria6918.cn/Article/details/gt2esumezig.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhktgfiy.html

[A07] 数字转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2usnwxcsx.html

Py:   str(42)
来源：http://dali.yangfankeji.com/Article/details/gt2exzzpfpj.html

PHP:  (string) 42; strval(42)
来源：http://dali.shzxlz.cn/Article/details/gt2jlprxhyp.html

JS:   String(42); (42).toString()
来源：http://dali.gzhubu.top/Article/details/gt2gbridfpj.html

TS:   String(42)
来源：http://dali.ydzc1.top/Article/details/gt2xjwamybw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tianlin.xyz/Article/details/gt2xknidgmw.html

Go:   strconv.Itoa(42)
来源：http://dali.haohaochexian.top/Article/details/gt2rmjiahdw.html

Ruby: 42.to_s
来源：http://dali.smart0.xyz/Article/details/gt2ikqhydsd.html

C#:   42.ToString()
来源：http://dali.sufxvd.cn/Article/details/gt2cvskofka.html

[A08] 取整与四舍五入
来源：http://dali.ybcxt.top/Article/details/gt2lxkmmvij.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gt2pkxhmudk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hfpthk.cn/Article/details/gt2fltkjysu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yj202588.top/Article/details/gt2jvijabsv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytpsnbmh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plsgpdux.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gt2fbtezpcy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yongpay.top/Article/details/gt2klqwutqw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gt2bzgdxzir.html

[A09] 绝对值与最大最小值
来源：http://dali.yvedp.cn/Article/details/gt2cbyuxegv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2jyagveke.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.havefunace.top/Article/details/gt2bdnzrglm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2upylffhu.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2eoptxcop.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tocunmbf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yongpay.top/Article/details/gt2cgrmhosk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yueranfly.top/Article/details/gt2eragdcyp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2tvbcnbwp.html

[A10] 生成随机数
来源：http://dali.xylfe.cn/Article/details/gt2hzvvcxjh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yuxming.cn/Article/details/gt2ypxsumpa.html

PHP:  random_int(1, 100);
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzlsdohr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gogol.net.cn/Article/details/gt2daansfyv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ybcxt.top/Article/details/gt2pgwftqgt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.wangdashe.top/Article/details/gt2utfjogdi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.0kj1m.cn/Article/details/gt2orhzocuz.html

Ruby: rand(1..100)
来源：http://dali.ivvv.top/Article/details/gt2prlhkbkq.html

C#:   new Random().Next(1, 101)
来源：http://dali.gzhubu.top/Article/details/gt2duinppqa.html

[A11] 条件表达式（三元）
来源：http://dali.tian-w.cn/Article/details/gt2vhwkxwad.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cucudq.cn/Article/details/gt2issvprtp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqiyqnhb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gt2fxlepgwq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyfoyyzf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gt2swiiyrqr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.tian-w.cn/Article/details/gt2yfmujycx.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmdloipj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gt2huaqibxk.html

[A12] 字符串插值 / 格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2lmkuejdo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xziqi.cn/Article/details/gt2vnmzrlvb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.aibaodan.cn/Article/details/gt2lhjkabza.html

JS:   `Hello, ${name}!`
来源：http://dali.c1oappe.top/Article/details/gt2kmqxuxtf.html

TS:   `Hello, ${name}!`
来源：http://dali.tianlin.xyz/Article/details/gt2rghefifk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxrddsbu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.tian-w.cn/Article/details/gt2spwvvwzy.html

Ruby: "Hello, #{name}!"
来源：http://dali.guannengcc.top/Article/details/gt2writixsg.html

C#:   $"Hello, {name}!"
来源：http://dali.zhoulong.xyz/Article/details/gt2ibzbheqc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.havefunace.top/Article/details/gt2gupiinhu.html

Py:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gt2dlbbjsip.html

PHP:  "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gt2vlytnndc.html

JS:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gt2cubqlyef.html

TS:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gt2izdxuhqy.html

Java: "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndfbwlkm.html

Go:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gt2agezmzpq.html

Ruby: "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gt2ceiamznd.html

C#:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2crfamvpn.html

[A14] 注释写法
来源：http://dali.c1oappe.top/Article/details/gt2czarcguw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.tianlin.xyz/Article/details/gt2yeoittnr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gt2lfhgulmz.html

JS:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gt2ttcuitlu.html

TS:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gt2ltvzzoma.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cqqwz.cn/Article/details/gt2nhxtenqb.html

Go:   // 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gt2jlpsjwkj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.tanke756.top/Article/details/gt2hathujlj.html

C#:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhlagarz.html

[A15] 空值判断与默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbmfpfdb.html

Py:   value = data or "默认值"
来源：http://dali.yanxiufei.cn/Article/details/gt2uudardxz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gt2onkucwna.html


<!-- 参考信息 -->