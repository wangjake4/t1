代发 wailian999

[U89] JS：数组去重
来源：http://dali.hnxiangtu.top/Article/details/gtuuqaynxs.html

[...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtsdvlwibg.html

[U90] JS：数字数组排序
来源：http://dali.cucudq.cn/Article/details/gthrwhutjg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtdptqkbuz.html

[U91] JS：对象键值遍历
来源：http://dali.hongshengwenyu.top/Article/details/gteuaksjdr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258888.top/Article/details/gttswcoyfq.html

[U92] JS：深拷贝
来源：http://dali.pycfn.com/Article/details/gtrcbfcsso.html

structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtubnfmmeo.html

[U93] JS：模板字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtmjwkzziu.html

`共 ${n} 条`
来源：http://dali.wangshuangyany.cn/Article/details/gtrqghevmg.html

[U94] JS：箭头函数
来源：http://dali.ivvv.top/Article/details/gtrylgnckg.html

const double = x => x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtzffaynvn.html

[U95] JS：Promise 包装
来源：http://dali.xziqi.cn/Article/details/gtekouhbls.html

new Promise((resolve, reject) => {})
来源：http://dali.iojbl.cn/Article/details/gtykfstykm.html

[U96] JS：async/await 与异常
来源：http://dali.svipenyu.cn/Article/details/gtewzdhwtk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtnbsogmqj.html

[U97] JS：并发请求
来源：http://dali.jiagoushi.top/Article/details/gtyobfghwx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtoaqddfme.html

[U98] JS：fetch 带 JSON
来源：http://dali.ybcxt.top/Article/details/gtpjzcftjx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.kuanghao11.cn/Article/details/gtacalmkua.html

[U99] JS：事件监听
来源：http://dali.sweek.top/Article/details/gtyqbdnpdc.html

el.addEventListener("click", e => {})
来源：http://dali.iojbl.cn/Article/details/gtogfjkksl.html

[U100] JS：DOM 查询
来源：http://dali.shzxlz.cn/Article/details/gtaroxyfsu.html

document.querySelector(".item")
来源：http://dali.316326.xyz/Article/details/gtvrcqngnq.html

[U101] JS：classList 操作
来源：http://dali.chenzaomai.com/Article/details/gtsblkkedz.html

el.classList.toggle("active")
来源：http://dali.quarkkingdee.top/Article/details/gtayyyqfmu.html

[U102] JS：本地存储
来源：http://dali.zhiwuduotai.top/Article/details/gtcyrnaiaa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yueranfly.top/Article/details/gtihmyllpc.html

[U103] JS：定时器
来源：http://dali.shuidangran.top/Article/details/gtiabxzdrw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jianghu66.top/Article/details/gtlmofpega.html

[U104] JS：防抖
来源：http://dali.tianlin.xyz/Article/details/gtkqaulxlh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtqznjvbht.html

[U105] JS：节流
来源：http://dali.snrcjt.cn/Article/details/gttdrpynug.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shzxlz.cn/Article/details/gtslrltljq.html

[U106] JS：日期格式化
来源：http://dali.guannengcc.top/Article/details/gtodmuqhtw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hongshengwenyu.top/Article/details/gttnclrkll.html

[U107] JS：数字千分位
来源：http://dali.ydzc1.top/Article/details/gtireishwn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gtovpulhkj.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotabdzwu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhiwuduotai.top/Article/details/gtlxjbuhjj.html

[U109] JS：数组分组
来源：http://dali.cashguo.top/Article/details/gtatswqqyc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gthlryijyw.html

[U110] JS：数组分块
来源：http://dali.chenzaomai.com/Article/details/gtttwsmxzm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hfpthk.cn/Article/details/gtziwwgflr.html

[U111] JS：对象转 Map
来源：http://dali.gaohongyu789.top/Article/details/gtwkefeygz.html

new Map(Object.entries(obj))
来源：http://dali.yj20258888.top/Article/details/gtoojsxesc.html

[U112] JS：字符串补位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkjbnwvl.html

"7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtprawxwqj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gtcqdqxtnu.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvishhkx.html

[U114] JS：JSON 深比较
来源：http://dali.dashuyun.cn/Article/details/gtaeeraijz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtxhzdfsca.html

[U115] JS：生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gtmzoobcsm.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gthplnited.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fengsongda.top/Article/details/gttugmtrsd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dianchejie.cn/Article/details/gtxvebuxcl.html

[U117] JS：单元测试
来源：http://dali.cdnleiting.top/Article/details/gtkaileqjy.html

npm i -D vitest;  npx vitest
来源：http://dali.xziqi.cn/Article/details/gtorrdfipg.html

[U118] JS：开发服务器
来源：http://dali.hysaishi.cn/Article/details/gtfxgspclt.html

npm i -D vite;  npx vite
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljeauztt.html

[U119] JS：生产构建
来源：http://dali.jiagoushi.top/Article/details/gteympakpu.html

npx vite build
来源：http://dali.aizwys.cn/Article/details/gtstyrbqng.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhongyouzk.top/Article/details/gtpmfkeske.html

import.meta.env.VITE_API_URL
来源：http://dali.sxryk.cn/Article/details/gtxlgmdpdh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthgadhioz.html

统计汇总
来源：http://dali.gogol.net.cn/Article/details/gtzgtgecau.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqgqqfvfx.html

按语言统计（条）：
来源：http://dali.zhixingplan.top/Article/details/gtraybccwy.html

Python ......... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdwmzmyt.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrextiaoj.html

JavaScript ..... 252
来源：http://dali.pycfn.com/Article/details/gttxsnundq.html

TypeScript ..... 212
来源：http://dali.vqdsnc.cn/Article/details/gtpuowzzwj.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gthfqafjvw.html

Go ............. 212
来源：http://dali.guowangkeji.top/Article/details/gtfilryivf.html

Ruby ........... 212
来源：http://dali.dashuyun.cn/Article/details/gttyejgqha.html

C# ............. 212
来源：http://dali.meibo888.top/Article/details/gtrqqclpnq.html

C .............. 30
来源：http://dali.yonumen.top/Article/details/gtlwwptcpm.html

C++ ............ 30
来源：http://dali.yuxming.cn/Article/details/gtglxnjqln.html

SQL ............ 90
来源：http://dali.316326.xyz/Article/details/gtxmyjasvc.html

Bash ........... 80
来源：http://dali.yj20258888.top/Article/details/gtueoslftz.html

Kotlin ......... 15
来源：http://dali.ehwqpu.com/Article/details/gtsefvoufv.html

Swift .......... 15
来源：http://dali.yanxiufei.cn/Article/details/gtjfefqcbv.html

Lua ............ 10
来源：http://dali.hfpthk.cn/Article/details/gtcsaensfy.html

Perl ........... 10
来源：http://dali.quarkkingdee.top/Article/details/gtjkauzdvh.html

Scala .......... 10
来源：http://dali.yj20258888.top/Article/details/gtxwadombp.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtsgdihxrs.html

合计 ........... 2106 条
来源：http://dali.hysaishi.cn/Article/details/gtuxntehgy.html

按章节统计：
来源：http://dali.hnxiangtu.top/Article/details/gtrdbpjxng.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.haohaochexian.top/Article/details/gtfjoldwvi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gtqesxquyx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtkgsvkysv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkblkmkoa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.iojbl.cn/Article/details/gtdgbwccrn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gtcvvleurz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrelvznx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yanxiufei.cn/Article/details/gtkjnbnigq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmcellbg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gtgpdevowk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtjygyarlp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtcqilshzc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gttrllgnjv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinqigfzy.top/Article/details/gtlehewckn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.havefunace.top/Article/details/gtmxmprceu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtxsrvnmko.html

Q SQL 专题                              90
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjweibsm.html

R Bash 专题                             80
来源：http://dali.quarkkingdee.top/Article/details/gtyifxiunh.html

S C / C++ 专题                          60
来源：http://dali.cashguo.top/Article/details/gtiivehexh.html

T 其他语言补充                          60
来源：http://dali.tianlin.xyz/Article/details/gthxgbmgpo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gtiwkbbdff.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtfdvsxbvx.html

合计                                  2106 条
来源：http://dali.zdqjudy.top/Article/details/gtucyspigd.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtuzxtijas.html

使用提醒
来源：http://dali.fengsongda.top/Article/details/gtsnpkieoq.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gtyfgslzah.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.316326.xyz/Article/details/gtcgqlmfnl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.mhx1999.top/Article/details/gtpijdxaxx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xylfe.cn/Article/details/gtfiaddnwg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.iojbl.cn/Article/details/gtlybqacba.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuanzx.com/Article/details/gtlxuzslgr.html

—— 文件结束 ——
来源：http://dali.sxryk.cn/Article/details/gtwwlimzts.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtjnyftrbe.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpamuqoa.html

Common Programming Examples Cheat Book
来源：http://dali.xylfe.cn/Article/details/gtclfwjpfo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjzmewdjd.html

【收录内容】
来源：http://dali.zhengqikj.top/Article/details/gtafknysdb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gogol.net.cn/Article/details/gteriudvaz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenjidiqi.icu/Article/details/gtqhpxpapz.html

SQL · Bash · C · C++
来源：http://dali.andypj.xyz/Article/details/gtfvvwjhap.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvjwxyav.html

【使用说明】
来源：http://dali.cucudq.cn/Article/details/gtvvpkhuke.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.316326.xyz/Article/details/gtxwzjimvu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.meibo888.top/Article/details/gtleuhimdn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.tianlin.xyz/Article/details/gtiqpccery.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuanzhike.top/Article/details/gtlbbswijm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cucudq.cn/Article/details/gtwsiofjne.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cheryme.top/Article/details/gtjtvogrbu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xinyue.icu/Article/details/gttlwclqpr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nwbrower.top/Article/details/gtfuafgdca.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinqigfzy.top/Article/details/gtpzvywcbi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhiwuduotai.top/Article/details/gtfenaqejk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gtopypnezp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hysaishi.cn/Article/details/gtokwjbkad.html

【文件统计】
来源：http://dali.hysaishi.cn/Article/details/gtvuaqfchp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zdqjudy.top/Article/details/gtsihgmfhi.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtiekwpohj.html

目  录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufdegbwj.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtscbhxghc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yanxiufei.cn/Article/details/gturbgcsgn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gtwandrzji.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gtoxclnnnb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yongpay.top/Article/details/gtxgrewxpz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtnagoghkw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgpxoyfo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gtnkuikxhj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gtaqwbhkqx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtpwwodvwj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.daria6918.cn/Article/details/gtfacymayg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtxduyclgg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujnsimsl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtiyygwsyz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gttysjggyn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.pycfn.com/Article/details/gtpaauftcj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtntlybcie.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jianghu66.top/Article/details/gtwzxzmsxq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pycfn.com/Article/details/gtfsrftqpl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.fzhhl.top/Article/details/gtuaghkquw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gtaqfcmoan.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtftzgcnqy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttmhdhbsa.html

A. 基础语法与类型
来源：http://dali.9152youxi.cn/Article/details/gtbyusgtho.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtprawmywz.html

[A01] Hello World
来源：http://dali.ivvv.top/Article/details/gtoilznisk.html

Py:   print("Hello, World!")
来源：http://dali.yueranfly.top/Article/details/gtgwgdusmw.html

PHP:  echo "Hello, World!";
来源：http://dali.c1oappe.top/Article/details/gtdtlzpjjs.html

JS:   console.log("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gttybhtvkj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.feifeiyinyue.top/Article/details/gtcrmlyorw.html

Java: System.out.println("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtmmhuytxo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggfehddd.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258888.top/Article/details/gtyedqoodg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.316326.xyz/Article/details/gtrsiysoba.html

[A02] 变量声明与赋值
来源：http://dali.dianchejie.cn/Article/details/gtfcgtvkyd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cdnleiting.top/Article/details/gtzehkzdfx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtqzoafqll.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xziqi.cn/Article/details/gtyukbicix.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.guowangkeji.top/Article/details/gtawsxfilq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtbgthezof.html

Go:   name := "Alex"; age := 20
来源：http://dali.birdmap.top/Article/details/gtvjyxkoia.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dianchejie.cn/Article/details/gtrimyfgcd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cucudq.cn/Article/details/gtsgzamvkq.html

[A03] 常量定义
来源：http://dali.yuxming.cn/Article/details/gtzwgdakwx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.aizwys.cn/Article/details/gtjlboaexo.html

PHP:  const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtuivicsvy.html

JS:   const PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasfzbbug.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtgzyyllab.html

Java: static final double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtcgpyerfe.html

Go:   const PI = 3.14159
来源：http://dali.hfpthk.cn/Article/details/gthqfhtmic.html

Ruby: PI = 3.14159
来源：http://dali.zhongyouzk.top/Article/details/gtxjzpwjap.html

C#:   const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtettdkbhk.html

[A04] 判断变量类型
来源：http://dali.hammf.cn/Article/details/gtejjmjiuu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gttivzbgxu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.mhx1999.top/Article/details/gteovrgdgl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.wangdashe.top/Article/details/gttbbaxdal.html

TS:   typeof x; x instanceof Date
来源：http://dali.sxryk.cn/Article/details/gtundkiuth.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.smart0.xyz/Article/details/gtjetgwzne.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.wangshuangyany.cn/Article/details/gtgklxzqxt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gtccohitrx.html

C#:   x.GetType().Name; x is int
来源：http://dali.mhx1999.top/Article/details/gtcphjircq.html

[A05] 整数除法与取模
来源：http://dali.nwbrower.top/Article/details/gtfcohhrug.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.316326.xyz/Article/details/gtuuuftoxu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gttvkrnqmm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtfzfbnvgq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gtqgjvulij.html

Java: 7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtyfrdcaak.html

Go:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtfmmkzdoh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtdwxsqvrx.html

C#:   7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtvsrahrlq.html

[A06] 字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtnitzdzdv.html

Py:   int("42"); float("3.14")
来源：http://dali.mhx1999.top/Article/details/gtfivqfzoy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shangyingyoupin.top/Article/details/gtekctrfzx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yonumen.top/Article/details/gttvaqchsu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cucudq.cn/Article/details/gtjfpwobrr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqylsiaf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nanxinkj.top/Article/details/gtxkljkllo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhoulong.xyz/Article/details/gtqpaaslzt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hammf.cn/Article/details/gtzztuudto.html

[A07] 数字转字符串
来源：http://dali.fzhhl.top/Article/details/gtnkeyasug.html

Py:   str(42)
来源：http://dali.cashguo.top/Article/details/gttxtsvdfx.html

PHP:  (string) 42; strval(42)
来源：http://dali.hfpthk.cn/Article/details/gtmdpmsutw.html

JS:   String(42); (42).toString()
来源：http://dali.tianlin.xyz/Article/details/gtyikpshhd.html

TS:   String(42)
来源：http://dali.ppjwa.cn/Article/details/gtlozfcehn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxmlpugo.html

Go:   strconv.Itoa(42)
来源：http://dali.hysaishi.cn/Article/details/gtzidfbdtl.html

Ruby: 42.to_s
来源：http://dali.yj20258888.top/Article/details/gtcqvjnsia.html

C#:   42.ToString()
来源：http://dali.hnqzz.top/Article/details/gtrgmvrdgo.html

[A08] 取整与四舍五入
来源：http://dali.zhiwuduotai.top/Article/details/gtegrxbbrg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gtstwhgdcb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.guowangkeji.top/Article/details/gtcjwsnvvf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gtmfjfglng.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.tian-w.cn/Article/details/gtkzxdhmpc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yangfankeji.com/Article/details/gtylwtebeh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtmahtungj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.dianchejie.cn/Article/details/gtusfsqsmh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sweek.top/Article/details/gtfnsdpttu.html

[A09] 绝对值与最大最小值
来源：http://dali.xinyue.icu/Article/details/gtjrsivzsj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtotlbmfqv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtragionvm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtigqpxiht.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtaickbafo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtjdtyemhy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwnbxjlc.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gaohongyu789.top/Article/details/gtxtlzhrbg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtxwoqmrqz.html

[A10] 生成随机数
来源：http://dali.c1oappe.top/Article/details/gtdhwbboda.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gaohongyu789.top/Article/details/gtgcfgnhhs.html

PHP:  random_int(1, 100);
来源：http://dali.ehwqpu.com/Article/details/gthstaemul.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cashguo.top/Article/details/gteqxibrjt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.bjfxy.top/Article/details/gtlymqzecj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.wangshuangyany.cn/Article/details/gtpfczxuly.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pycfn.com/Article/details/gtmblnliyo.html

Ruby: rand(1..100)
来源：http://dali.nwbrower.top/Article/details/gtggqxyydp.html

C#:   new Random().Next(1, 101)
来源：http://dali.ydzc1.top/Article/details/gtiryuujmf.html

[A11] 条件表达式（三元）
来源：http://dali.gaohongyu789.top/Article/details/gtizviopzu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hnqzz.top/Article/details/gtzjnvbluw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gtujzeghpd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtgavsqcyv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gtxsqnfvqk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gtsmhhpesi.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.svipenyu.cn/Article/details/gtprqtpqjy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gtbdzmaybw.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gtyigrubmg.html

[A12] 字符串插值 / 格式化
来源：http://dali.yj202588.top/Article/details/gtzylsantj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.svipenyu.cn/Article/details/gtduomrzgv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.fengsongda.top/Article/details/gtalkhibhm.html

JS:   `Hello, ${name}!`
来源：http://dali.yueranfly.top/Article/details/gtizfjcxlw.html

TS:   `Hello, ${name}!`
来源：http://dali.fzhhl.top/Article/details/gtlvtiuyhs.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.c1oappe.top/Article/details/gtxdovysmc.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhongyouzk.top/Article/details/gtmrszmcdz.html

Ruby: "Hello, #{name}!"
来源：http://dali.sysykeji.top/Article/details/gtjtcmgmuj.html

C#:   $"Hello, {name}!"
来源：http://dali.xuetiantiany.cn/Article/details/gtjrznlzrz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shuidangran.top/Article/details/gtanhayclt.html

Py:   "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtknklaome.html

PHP:  "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtmctwlzrr.html

JS:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtrllwhbbg.html

TS:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtreimgibh.html

Java: "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtvzcdanmq.html

Go:   "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gtapkcyfwj.html

Ruby: "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtrspnnvnn.html

C#:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtrreihnnb.html

[A14] 注释写法
来源：http://dali.zhengqikj.top/Article/details/gtreszlnnr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.aizwys.cn/Article/details/gtskwpmowf.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtpgqhkadz.html

JS:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gtutklgadl.html

TS:   // 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gtkfswunle.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jiagoushi.top/Article/details/gtnqjkpnfm.html

Go:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gttlyksdml.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xinyue.icu/Article/details/gtxtnealxu.html

C#:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gtgsxqpepv.html

[A15] 空值判断与默认值
来源：http://dali.hnqzz.top/Article/details/gtgicqncmz.html

Py:   value = data or "默认值"
来源：http://dali.jianghu66.top/Article/details/gteqfiauyd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gtdhdnqapd.html


<!-- 参考信息 -->