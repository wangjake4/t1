代发 wailian999

[U87] JS：解构默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbeuuxiu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhiwuduotai.top/Article/details/gt2mypayulv.html

[U88] JS：对象展开合并
来源：http://dali.jqgufenzy.top/Article/details/gt2zajmjyqz.html

{ ...a, ...b }
来源：http://dali.9152youxi.cn/Article/details/gt2acvgfdur.html

[U89] JS：数组去重
来源：http://dali.xziqi.cn/Article/details/gt2oamadycw.html

[...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gt2xcneftjh.html

[U90] JS：数字数组排序
来源：http://dali.c1oappe.top/Article/details/gt2djpdsvhj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gt2nufdfhlp.html

[U91] JS：对象键值遍历
来源：http://dali.sysykeji.top/Article/details/gt2xxfyienb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sufxvd.cn/Article/details/gt2rannlpyg.html

[U92] JS：深拷贝
来源：http://dali.yangfankeji.com/Article/details/gt2nxwgmqxl.html

structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcbltudb.html

[U93] JS：模板字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2wbqrfbch.html

`共 ${n} 条`
来源：http://dali.gzhubu.top/Article/details/gt2ymwgkfmx.html

[U94] JS：箭头函数
来源：http://dali.aizwys.cn/Article/details/gt2evbumgfl.html

const double = x => x * 2;
来源：http://dali.andypj.xyz/Article/details/gt2qylnrfyu.html

[U95] JS：Promise 包装
来源：http://dali.xylfe.cn/Article/details/gt2dcbxzfeh.html

new Promise((resolve, reject) => {})
来源：http://dali.ybcxt.top/Article/details/gt2rzriumof.html

[U96] JS：async/await 与异常
来源：http://dali.ehwqpu.com/Article/details/gt2grzujqls.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2giomjdcy.html

[U97] JS：并发请求
来源：http://dali.sxryk.cn/Article/details/gt2rnbnnwyj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2zlyjrdhv.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj20258888.top/Article/details/gt2rkunesvp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.svipenyu.cn/Article/details/gt2gwslayqg.html

[U99] JS：事件监听
来源：http://dali.guannengcc.top/Article/details/gt2ebfzacga.html

el.addEventListener("click", e => {})
来源：http://dali.havefunace.top/Article/details/gt2zgjbvvzp.html

[U100] JS：DOM 查询
来源：http://dali.cucudq.cn/Article/details/gt2dspssbyg.html

document.querySelector(".item")
来源：http://dali.tianlin.xyz/Article/details/gt2amdddfsj.html

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gt2vzyrqjxu.html

el.classList.toggle("active")
来源：http://dali.ehwqpu.com/Article/details/gt2mthmvvvt.html

[U102] JS：本地存储
来源：http://dali.wangshuangyany.cn/Article/details/gt2hozbjyrv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuetiantiany.cn/Article/details/gt2zetzguly.html

[U103] JS：定时器
来源：http://dali.smart0.xyz/Article/details/gt2cbjfgzrd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258888.top/Article/details/gt2jevbpfhw.html

[U104] JS：防抖
来源：http://dali.jlsjyb.cn/Article/details/gt2hkoiduno.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gt2rlkzmdwg.html

[U105] JS：节流
来源：http://dali.xylfe.cn/Article/details/gt2ayidhxvs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.316326.xyz/Article/details/gt2pnmdfchn.html

[U106] JS：日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2zwduhioh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jianghu66.top/Article/details/gt2kujhbsky.html

[U107] JS：数字千分位
来源：http://dali.sxryk.cn/Article/details/gt2dbgvezny.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.c1oappe.top/Article/details/gt2hlqscznu.html

[U108] JS：随机整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dilouzmc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xinyue.icu/Article/details/gt2zegyznui.html

[U109] JS：数组分组
来源：http://dali.zhongyouzk.top/Article/details/gt2jqwvmwxo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gt2kbisoblo.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gt2yvmqbhxi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.9152youxi.cn/Article/details/gt2hzhhdpfr.html

[U111] JS：对象转 Map
来源：http://dali.xinyue.icu/Article/details/gt2uezhofwr.html

new Map(Object.entries(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ayxzcejf.html

[U112] JS：字符串补位
来源：http://dali.shuidangran.top/Article/details/gt2xdpymxwh.html

"7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2qkjonseu.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gt2nspabsrv.html

s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2xluspsrf.html

[U114] JS：JSON 深比较
来源：http://dali.cdnleiting.top/Article/details/gt2yyvylbdc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gt2inhsrchq.html

[U115] JS：生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gt2mfozyrzd.html

crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gt2trqskusv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nanxuanxn.top/Article/details/gt2lqfwmopd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhixingplan.top/Article/details/gt2jrpmpede.html

[U117] JS：单元测试
来源：http://dali.jiagoushi.top/Article/details/gt2nryevqpt.html

npm i -D vitest;  npx vitest
来源：http://dali.yj20258888.top/Article/details/gt2qsswvnwc.html

[U118] JS：开发服务器
来源：http://dali.quarkkingdee.top/Article/details/gt2jfztgvxd.html

npm i -D vite;  npx vite
来源：http://dali.kuanghao11.cn/Article/details/gt2mzowftjk.html

[U119] JS：生产构建
来源：http://dali.ybcxt.top/Article/details/gt2enikiaos.html

npx vite build
来源：http://dali.xinyue.icu/Article/details/gt2cxtixqcv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hysaishi.cn/Article/details/gt2foiatqcp.html

import.meta.env.VITE_API_URL
来源：http://dali.daria6918.cn/Article/details/gt2phgoruai.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2rtycbmzk.html

统计汇总
来源：http://dali.nanxinkj.top/Article/details/gt2hwnmlzhf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qxdkzxky.html

按语言统计（条）：
来源：http://dali.yongpay.top/Article/details/gt2gslqldzx.html

Python ......... 252
来源：http://dali.havefunace.top/Article/details/gt2coyunnrn.html

PHP ............ 252
来源：http://dali.jyoumei.cn/Article/details/gt2ybcyvlws.html

JavaScript ..... 252
来源：http://dali.guowangkeji.top/Article/details/gt2sbeyvfng.html

TypeScript ..... 212
来源：http://dali.yueranfly.top/Article/details/gt2dkhayzsd.html

Java ........... 212
来源：http://dali.yj202588.top/Article/details/gt2xcfulgtp.html

Go ............. 212
来源：http://dali.pycfn.com/Article/details/gt2huwggqyu.html

Ruby ........... 212
来源：http://dali.hammf.cn/Article/details/gt2tlvoprbb.html

C# ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gt2yxbjsxll.html

C .............. 30
来源：http://dali.sweek.top/Article/details/gt2pacuxocz.html

C++ ............ 30
来源：http://dali.pycfn.com/Article/details/gt2mqjznjpy.html

SQL ............ 90
来源：http://dali.gzhubu.top/Article/details/gt2qnvmflsm.html

Bash ........... 80
来源：http://dali.andypj.xyz/Article/details/gt2mocnmfaq.html

Kotlin ......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gt2ajuhsacn.html

Swift .......... 15
来源：http://dali.tianlin.xyz/Article/details/gt2pnbunfxp.html

Lua ............ 10
来源：http://dali.wangdashe.top/Article/details/gt2cdbcqugc.html

Perl ........... 10
来源：http://dali.sxryk.cn/Article/details/gt2iqbnwnvv.html

Scala .......... 10
来源：http://dali.zycfv.cn/Article/details/gt2mcfbvhal.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2unblpckg.html

合计 ........... 2106 条
来源：http://dali.sufxvd.cn/Article/details/gt2swuulfgy.html

按章节统计：
来源：http://dali.zdqjudy.top/Article/details/gt2wsjiqjob.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gt2kyzemrnz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvkxnkhk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gt2ihlraksz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gt2sfuhexkr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenzaomai.com/Article/details/gt2sdgmvgkg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.meibo888.top/Article/details/gt2wdmciyhr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gt2mnhoqpbo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jyoumei.cn/Article/details/gt2zsnfbvvh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gt2koppsuoq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tianlin.xyz/Article/details/gt2nthspkqk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gt2kcmjieoz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gt2mtyljmbo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2xbvlzrof.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gt2gtiwyrjn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yueranfly.top/Article/details/gt2ieioerga.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2xntkxgkv.html

Q SQL 专题                              90
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqhcunvx.html

R Bash 专题                             80
来源：http://dali.9152youxi.cn/Article/details/gt2lubvynwb.html

S C / C++ 专题                          60
来源：http://dali.vqdsnc.cn/Article/details/gt2fggqslrg.html

T 其他语言补充                          60
来源：http://dali.sysykeji.top/Article/details/gt2asiilvlx.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwgnmmgk.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gt2mnfiqzws.html

合计                                  2106 条
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpqdtqyt.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gt2hnxozgsx.html

使用提醒
来源：http://dali.cqqwz.cn/Article/details/gt2mgmeoaix.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2dvchzaur.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj202588.top/Article/details/gt2klazmbbt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnofsbwz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ehwqpu.com/Article/details/gt2qtxxdrru.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hnxiangtu.top/Article/details/gt2jrutuptn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xylfe.cn/Article/details/gt2evtgsqmg.html

—— 文件结束 ——
来源：http://dali.yuanzhike.top/Article/details/gt2qjolznbh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2orgxvhtk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.redwolf501.top/Article/details/gt2rgxzumdt.html

Common Programming Examples Cheat Book
来源：http://dali.zycfv.cn/Article/details/gt2mbmhryge.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2cewfikuv.html

【收录内容】
来源：http://dali.nwbrower.top/Article/details/gt2agvupirs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xylfe.cn/Article/details/gt2yhvdqfox.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxzhezfe.html

SQL · Bash · C · C++
来源：http://dali.nwbrower.top/Article/details/gt2bavwqokn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.9152youxi.cn/Article/details/gt2mcpufebz.html

【使用说明】
来源：http://dali.jqgufenzy.top/Article/details/gt2hxwpjsei.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbodfsac.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhixingplan.top/Article/details/gt2qozuzxqw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guowangkeji.top/Article/details/gt2ftrldmty.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenlongwang.top/Article/details/gt2tsqhbbjx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.wangshuangyany.cn/Article/details/gt2dslofuth.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hfpthk.cn/Article/details/gt2ewlwculb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnqzz.top/Article/details/gt2ylrxamds.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.andypj.xyz/Article/details/gt2tooxxtkp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.havefunace.top/Article/details/gt2rhkjyzoi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yongpay.top/Article/details/gt2sbceiryc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.316326.xyz/Article/details/gt2gqpmcqxu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yvedp.cn/Article/details/gt2rgsehwzi.html

【文件统计】
来源：http://dali.pycfn.com/Article/details/gt2rxjsbewh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jlsjyb.cn/Article/details/gt2ioryqizz.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2emzkgzla.html

目  录
来源：http://dali.sysykeji.top/Article/details/gt2kpzekorc.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gt2keesuskx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilfrefek.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tianlin.xyz/Article/details/gt2nefbkbmj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gt2ivwdortx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2msqgipxj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tian-w.cn/Article/details/gt2ywdfexyu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhengqikj.top/Article/details/gt2fhlmhllb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tifuajwq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qamtduhc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gt2vmhoxfbw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gt2yognfqnp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gt2cziodyrf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gt2bgmuqwvz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gt2dhgvdjvu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tyoihccw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cucudq.cn/Article/details/gt2nklclmmk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gt2gkwbpvjd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ehwqpu.com/Article/details/gt2zccqxypa.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ybcxt.top/Article/details/gt2zxfqqnms.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2unppxzuq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gt2vwlecmzb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gt2sbrssvsc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2eefzfbzr.html

A. 基础语法与类型
来源：http://dali.jyoumei.cn/Article/details/gt2rprpexua.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2xxeqipkj.html

[A01] Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2xrhiemlq.html

Py:   print("Hello, World!")
来源：http://dali.haohaochexian.top/Article/details/gt2rmhoinjf.html

PHP:  echo "Hello, World!";
来源：http://dali.redwolf501.top/Article/details/gt2fzqmaozk.html

JS:   console.log("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gt2dkvpyvan.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqzypkbb.html

Java: System.out.println("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gt2mscgrvbx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cdnleiting.top/Article/details/gt2svwmpkjc.html

Ruby: puts "Hello, World!"
来源：http://dali.ivvv.top/Article/details/gt2etbppviz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gt2ccmntwdj.html

[A02] 变量声明与赋值
来源：http://dali.316326.xyz/Article/details/gt2nollsvgy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aibaodan.cn/Article/details/gt2fbqdafwv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.guannengcc.top/Article/details/gt2lejdtkny.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.dashuyun.cn/Article/details/gt2pfzigxki.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.nanxuanxn.top/Article/details/gt2cokisvfy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenlongwang.top/Article/details/gt2mmtddsgl.html

Go:   name := "Alex"; age := 20
来源：http://dali.ydzc1.top/Article/details/gt2lyvrdquc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gzhubu.top/Article/details/gt2exofefyw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.0kj1m.cn/Article/details/gt2rpzzzauq.html

[A03] 常量定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrlrfdmk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.guannengcc.top/Article/details/gt2hbkvinlp.html

PHP:  const PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2pjakfcii.html

JS:   const PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2pbwwhakv.html

TS:   const PI: number = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2hwthbgxl.html

Java: static final double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozxqvuoc.html

Go:   const PI = 3.14159
来源：http://dali.birdmap.top/Article/details/gt2ctwuenho.html

Ruby: PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdjkvtpz.html

C#:   const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2ogdtppuz.html

[A04] 判断变量类型
来源：http://dali.sweek.top/Article/details/gt2ahyrvdcc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hnxiangtu.top/Article/details/gt2nqrnuyxi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xylfe.cn/Article/details/gt2prcyylxq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.meibo888.top/Article/details/gt2swdxczre.html

TS:   typeof x; x instanceof Date
来源：http://dali.c1oappe.top/Article/details/gt2rlrjorpm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.guowangkeji.top/Article/details/gt2efjspjne.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sweek.top/Article/details/gt2zifckyxw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfitrqqr.html

C#:   x.GetType().Name; x is int
来源：http://dali.svipenyu.cn/Article/details/gt2vbqwfxru.html

[A05] 整数除法与取模
来源：http://dali.yuanzhike.top/Article/details/gt2bcgiaohp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sxryk.cn/Article/details/gt2csymhwpw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2cdjghniw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gt2nvewvouo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2dehegbaf.html

Java: 7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gt2ghrfggmm.html

Go:   7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2eefjvsse.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2zdzvolyq.html

C#:   7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2jslkrkud.html

[A06] 字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gt2ubaxuiqh.html

Py:   int("42"); float("3.14")
来源：http://dali.cashguo.top/Article/details/gt2nrcumswp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.aibaodan.cn/Article/details/gt2djeqirgh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aizwys.cn/Article/details/gt2ijeajgkv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.wangdashe.top/Article/details/gt2rvsbfcyy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj20258888.top/Article/details/gt2snuzatzz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hnxiangtu.top/Article/details/gt2arptklsu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinqigufen.top/Article/details/gt2gsuliium.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258.top/Article/details/gt2runubgot.html

[A07] 数字转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2kigpibjb.html

Py:   str(42)
来源：http://dali.iojbl.cn/Article/details/gt2duachlxa.html

PHP:  (string) 42; strval(42)
来源：http://dali.shzxlz.cn/Article/details/gt2lvkebxjf.html

JS:   String(42); (42).toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2lhesszpn.html

TS:   String(42)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzojmpsp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yvedp.cn/Article/details/gt2avcckenr.html

Go:   strconv.Itoa(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybotfgrq.html

Ruby: 42.to_s
来源：http://dali.yvedp.cn/Article/details/gt2tumgnhwk.html

C#:   42.ToString()
来源：http://dali.ivvv.top/Article/details/gt2srtnwsoj.html

[A08] 取整与四舍五入
来源：http://dali.yuanzhike.top/Article/details/gt2ipwmcfth.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tkhthweg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yueranfly.top/Article/details/gt2fscnwjoc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gt2nnzxopbt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sweek.top/Article/details/gt2jtqhskhn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgajksmd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gt2qpzjeciy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.fzhhl.top/Article/details/gt2fxcaaryi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cheryme.top/Article/details/gt2nskrvjiv.html

[A09] 绝对值与最大最小值
来源：http://dali.guowangkeji.top/Article/details/gt2llbxqbjn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2aivncqbw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2jrscsakf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqfuvgmi.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2utqgcyyn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258888.top/Article/details/gt2qadzvfax.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.wangshuangyany.cn/Article/details/gt2xypuliuk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cheryme.top/Article/details/gt2ffbvgyln.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2krjzxgsm.html

[A10] 生成随机数
来源：http://dali.sufxvd.cn/Article/details/gt2ricagdgi.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhixingplan.top/Article/details/gt2sfadnohg.html

PHP:  random_int(1, 100);
来源：http://dali.shuidangran.top/Article/details/gt2dbtzkbvb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xylfe.cn/Article/details/gt2hnjvbkgw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zzscnder.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhengqikj.top/Article/details/gt2vwfwbuzp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.birdmap.top/Article/details/gt2ardzghkd.html

Ruby: rand(1..100)
来源：http://dali.jinqigufen.top/Article/details/gt2fktfrvwt.html

C#:   new Random().Next(1, 101)
来源：http://dali.zdqjudy.top/Article/details/gt2sxnhzasz.html

[A11] 条件表达式（三元）
来源：http://dali.yuanzhike.top/Article/details/gt2uorhnnvp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shzxlz.cn/Article/details/gt2wpfstjie.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gt2yklvlufl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gt2iifdybdq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gt2kkwchbky.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gt2tesextxr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrjshcxp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gt2spsheddy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gt2hahsirzt.html

[A12] 字符串插值 / 格式化
来源：http://dali.andypj.xyz/Article/details/gt2jabuthur.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjsqurij.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cheryme.top/Article/details/gt2vrjzxqro.html

JS:   `Hello, ${name}!`
来源：http://dali.zdqjudy.top/Article/details/gt2wgvoflre.html

TS:   `Hello, ${name}!`
来源：http://dali.zhengqikj.top/Article/details/gt2tciumgvp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.birdmap.top/Article/details/gt2dlwurjrj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.c1oappe.top/Article/details/gt2dynwgqst.html

Ruby: "Hello, #{name}!"
来源：http://dali.hywenlv.cn/Article/details/gt2wbfuvvla.html

C#:   $"Hello, {name}!"
来源：http://dali.yongpay.top/Article/details/gt2rhvoacvr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.gzhubu.top/Article/details/gt2iriqmzmm.html

Py:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gt2eukduhdd.html

PHP:  "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gt2znkqjgth.html

JS:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gt2qcaocqtq.html

TS:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gt2gxrrwzja.html

Java: "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gt2jankrroc.html

Go:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gt2lozafisi.html

Ruby: "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gt2yptuawjl.html

C#:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gt2puasgrwh.html

[A14] 注释写法
来源：http://dali.jlsjyb.cn/Article/details/gt2sdgqudvi.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfngbtfa.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jianghu66.top/Article/details/gt2mzxniryl.html

JS:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gt2iirfucgs.html

TS:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gt2fpvslseg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.andypj.xyz/Article/details/gt2mbtvcwvx.html

Go:   // 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gt2qgoldcyg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.aibaodan.cn/Article/details/gt2nnykqkcm.html


<!-- 参考信息 -->