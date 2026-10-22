代发 wailian999

[U87] JS：解构默认值
来源：http://dali.shzxlz.cn/Article/details/gtqtixhxwv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cqqwz.cn/Article/details/gtqgjipnlg.html

[U88] JS：对象展开合并
来源：http://dali.ydzc1.top/Article/details/gtwmhobpsq.html

{ ...a, ...b }
来源：http://dali.zdqjudy.top/Article/details/gtymfumchj.html

[U89] JS：数组去重
来源：http://dali.zhoulong.xyz/Article/details/gtdmgjyshv.html

[...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtkxzdwwyu.html

[U90] JS：数字数组排序
来源：http://dali.yuanzhike.top/Article/details/gtfoejdaqn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtcbekmwlb.html

[U91] JS：对象键值遍历
来源：http://dali.hysaishi.cn/Article/details/gtngcblddc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aizwys.cn/Article/details/gthdqeqjje.html

[U92] JS：深拷贝
来源：http://dali.sysykeji.top/Article/details/gtquzmfeqy.html

structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtgjnbvgha.html

[U93] JS：模板字符串
来源：http://dali.aibaodan.cn/Article/details/gthdajhnjo.html

`共 ${n} 条`
来源：http://dali.smart0.xyz/Article/details/gtmevgtclw.html

[U94] JS：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gthqjeqfsm.html

const double = x => x * 2;
来源：http://dali.yonumen.top/Article/details/gtmiznlzes.html

[U95] JS：Promise 包装
来源：http://dali.hnqzz.top/Article/details/gtdktyobti.html

new Promise((resolve, reject) => {})
来源：http://dali.chenzaomai.com/Article/details/gtlgybrthh.html

[U96] JS：async/await 与异常
来源：http://dali.yonumen.top/Article/details/gtbhxvglqb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtgoeodezu.html

[U97] JS：并发请求
来源：http://dali.xuetiantiany.cn/Article/details/gttpadqqyv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gttxusbefp.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gthocakgvc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gaohongyu789.top/Article/details/gtfdkimvvg.html

[U99] JS：事件监听
来源：http://dali.316326.xyz/Article/details/gtaiadtmkr.html

el.addEventListener("click", e => {})
来源：http://dali.aizwys.cn/Article/details/gtnvlmgsrw.html

[U100] JS：DOM 查询
来源：http://dali.yuxming.cn/Article/details/gtecbrlfco.html

document.querySelector(".item")
来源：http://dali.sweek.top/Article/details/gtdsrlrygb.html

[U101] JS：classList 操作
来源：http://dali.ybcxt.top/Article/details/gtekycpfwv.html

el.classList.toggle("active")
来源：http://dali.sufxvd.cn/Article/details/gtjxmfnkxe.html

[U102] JS：本地存储
来源：http://dali.dashuyun.cn/Article/details/gtchcqcrqa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxinkj.top/Article/details/gtoemyrbma.html

[U103] JS：定时器
来源：http://dali.yongpay.top/Article/details/gtliasmoiz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gtwryxvkty.html

[U104] JS：防抖
来源：http://dali.shanyushiyangtech.top/Article/details/gtqggmnznw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtozyhunvm.html

[U105] JS：节流
来源：http://dali.tianlin.xyz/Article/details/gtrtikrpur.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sxryk.cn/Article/details/gtuczxxmgj.html

[U106] JS：日期格式化
来源：http://dali.xuanzx.com/Article/details/gthdeftthl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hammf.cn/Article/details/gtatcnbmmp.html

[U107] JS：数字千分位
来源：http://dali.mhx1999.top/Article/details/gtmombttkt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gtwsqwegth.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxhowsfw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yvedp.cn/Article/details/gtcibsjdky.html

[U109] JS：数组分组
来源：http://dali.kuanghao11.cn/Article/details/gtazyylqfa.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtufodigzt.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gthtnlggds.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yangfankeji.com/Article/details/gtdtevkyvt.html

[U111] JS：对象转 Map
来源：http://dali.mhx1999.top/Article/details/gtlwnnggkr.html

new Map(Object.entries(obj))
来源：http://dali.gotoacloud.top/Article/details/gtneusszmx.html

[U112] JS：字符串补位
来源：http://dali.andypj.xyz/Article/details/gtqypagljh.html

"7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtmiofribt.html

[U113] JS：正则替换全部
来源：http://dali.yangfankeji.com/Article/details/gttykqxjfw.html

s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtkfdranoj.html

[U114] JS：JSON 深比较
来源：http://dali.sweek.top/Article/details/gtmhowlnxu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtfakyqlkk.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtecifrzbn.html

crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtecprrrzt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.smart0.xyz/Article/details/gtjplqvxgl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenzaomai.com/Article/details/gtwtcdchta.html

[U117] JS：单元测试
来源：http://dali.cashguo.top/Article/details/gthtzuovzd.html

npm i -D vitest;  npx vitest
来源：http://dali.svipenyu.cn/Article/details/gtslgschqb.html

[U118] JS：开发服务器
来源：http://dali.gogol.net.cn/Article/details/gtuzddxgoo.html

npm i -D vite;  npx vite
来源：http://dali.snrcjt.cn/Article/details/gtlwafhyoa.html

[U119] JS：生产构建
来源：http://dali.9152youxi.cn/Article/details/gtzgmaqpxe.html

npx vite build
来源：http://dali.cucudq.cn/Article/details/gttnbqgueo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ybcxt.top/Article/details/gtccandrod.html

import.meta.env.VITE_API_URL
来源：http://dali.9152youxi.cn/Article/details/gtutifapht.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvuinioem.html

统计汇总
来源：http://dali.zycfv.cn/Article/details/gtasalpopw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwpgvwcjv.html

按语言统计（条）：
来源：http://dali.shangyingyoupin.top/Article/details/gtfcgiqygm.html

Python ......... 252
来源：http://dali.redwolf501.top/Article/details/gteyksaome.html

PHP ............ 252
来源：http://dali.chenjidiqi.icu/Article/details/gtwyobsexh.html

JavaScript ..... 252
来源：http://dali.redwolf501.top/Article/details/gtazdkmyoy.html

TypeScript ..... 212
来源：http://dali.fengsongda.top/Article/details/gtnppsvagg.html

Java ........... 212
来源：http://dali.xylfe.cn/Article/details/gtzozhhhiv.html

Go ............. 212
来源：http://dali.smart0.xyz/Article/details/gtcmxdkqub.html

Ruby ........... 212
来源：http://dali.dashuyun.cn/Article/details/gtporlixyk.html

C# ............. 212
来源：http://dali.guowangkeji.top/Article/details/gtwtkkrkzh.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlctumbn.html

C++ ............ 30
来源：http://dali.jyoumei.cn/Article/details/gtavyfbbzz.html

SQL ............ 90
来源：http://dali.wangshuangyany.cn/Article/details/gtpurinmny.html

Bash ........... 80
来源：http://dali.cdnleiting.top/Article/details/gtyegbzexa.html

Kotlin ......... 15
来源：http://dali.birdmap.top/Article/details/gtsmvsyggh.html

Swift .......... 15
来源：http://dali.smart0.xyz/Article/details/gtqyamwbya.html

Lua ............ 10
来源：http://dali.ppjwa.cn/Article/details/gtjckjhlfr.html

Perl ........... 10
来源：http://dali.zycfv.cn/Article/details/gtdjsrhrnk.html

Scala .......... 10
来源：http://dali.yvedp.cn/Article/details/gttulyziro.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gthodkqphe.html

合计 ........... 2106 条
来源：http://dali.ybcxt.top/Article/details/gtubygikyk.html

按章节统计：
来源：http://dali.jiagoushi.top/Article/details/gtnifpkuza.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gtbhcbhsgd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gtrwedzoak.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtmwlbmpiy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gtwmfwlvie.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhiwuduotai.top/Article/details/gtlxhgtivj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jianghu66.top/Article/details/gtgljljgyq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gtzlohotxx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gtrpdeiufx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtpmkfapfp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gtfkshtutm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtsnmnakdi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtlrlsexuq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtceivhpjb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gtckvtabtx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhongyouzk.top/Article/details/gtexoupfao.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtyxzssmfu.html

Q SQL 专题                              90
来源：http://dali.wangdashe.top/Article/details/gtwfnqxqfw.html

R Bash 专题                             80
来源：http://dali.havefunace.top/Article/details/gtcvcodvqx.html

S C / C++ 专题                          60
来源：http://dali.fzhhl.top/Article/details/gtggdixfga.html

T 其他语言补充                          60
来源：http://dali.ydzc1.top/Article/details/gtevcnbneb.html

U 高频实用片段                         120
来源：http://dali.daxiang520.top/Article/details/gtpnwyfswq.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtorugkrus.html

合计                                  2106 条
来源：http://dali.tianlin.xyz/Article/details/gtjmbkincv.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrldzuzo.html

使用提醒
来源：http://dali.smart0.xyz/Article/details/gtlwovvxnu.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtqhglvdgk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuxming.cn/Article/details/gtgjnndrqx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jiagoushi.top/Article/details/gtapwxrzrq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daxiang520.top/Article/details/gtsdsltyrr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hfpthk.cn/Article/details/gtsuytjjvq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.fengsongda.top/Article/details/gtxxsqnxuf.html

—— 文件结束 ——
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgndunytx.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtseqglcdk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenzaomai.com/Article/details/gttakffrgm.html

Common Programming Examples Cheat Book
来源：http://dali.yueranfly.top/Article/details/gtupaavrgl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwagqwzbi.html

【收录内容】
来源：http://dali.jianghu66.top/Article/details/gtfmnusaqt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cashguo.top/Article/details/gtgbnccvjp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daxiang520.top/Article/details/gtnymyqpwg.html

SQL · Bash · C · C++
来源：http://dali.feifeiyinyue.top/Article/details/gtmbbknywr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sufxvd.cn/Article/details/gtufyleocv.html

【使用说明】
来源：http://dali.bjfxy.top/Article/details/gtrptbkjvc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj202588.top/Article/details/gtetafwdrj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfihskme.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.redwolf501.top/Article/details/gtvcgzjsmt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhiwuduotai.top/Article/details/gtbkivopta.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gotoacloud.top/Article/details/gtxzuhnxjg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shanyushiyangtech.top/Article/details/gtxalwltcy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zycfv.cn/Article/details/gtphakmjua.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jqgufenzy.top/Article/details/gtqsxjkwrx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ydzc1.top/Article/details/gtikcumrxk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.birdmap.top/Article/details/gthvvymtth.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnqzz.top/Article/details/gtnkfdtucj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.nwbrower.top/Article/details/gticgtzlbx.html

【文件统计】
来源：http://dali.ehwqpu.com/Article/details/gtcaboiefv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xuanzx.com/Article/details/gtlekeyfjx.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtuzzaptpk.html

目  录
来源：http://dali.wangshuangyany.cn/Article/details/gtzdwwnsvo.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtkdyodcvb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.tanke756.top/Article/details/gtrbswlskn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gtvrifxtkz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.daxiang520.top/Article/details/gtiniaaihd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aizwys.cn/Article/details/gtrlnqfpfk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.dianchejie.cn/Article/details/gtuvtletnc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.haohaochexian.top/Article/details/gtwyoyiepg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvicinll.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtzvhtniln.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gtzczoeubw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gtmkgszvaf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtoguhdcxe.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtggclujas.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gterzgbkhd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhengqikj.top/Article/details/gtcrzrzhvv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nwbrower.top/Article/details/gtagalflun.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtokpdqnkk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtosggznsj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nanxinkj.top/Article/details/gtwudfbkxo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhongyouzk.top/Article/details/gtjcpalzih.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gtgnndlifl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gtldxffrkb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjtwnerln.html

A. 基础语法与类型
来源：http://dali.feifeiyinyue.top/Article/details/gtuqjlwdiv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxxdzobkx.html

[A01] Hello World
来源：http://dali.tianlin.xyz/Article/details/gtwiunanbj.html

Py:   print("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gtuhulecoz.html

PHP:  echo "Hello, World!";
来源：http://dali.nwbrower.top/Article/details/gtyqzajizl.html

JS:   console.log("Hello, World!");
来源：http://dali.xuetiantiany.cn/Article/details/gttvqfyvfw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gogol.net.cn/Article/details/gtrgnjucqe.html

Java: System.out.println("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtquphruwi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jiagoushi.top/Article/details/gtypmsorvd.html

Ruby: puts "Hello, World!"
来源：http://dali.jyoumei.cn/Article/details/gtjenlswiq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gtdrspzgtr.html

[A02] 变量声明与赋值
来源：http://dali.redwolf501.top/Article/details/gtxenzgjug.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.haohaochexian.top/Article/details/gtvfirxthc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtxmdlygzm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogpztlvc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cashguo.top/Article/details/gtvoammvtg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtlwaaaedk.html

Go:   name := "Alex"; age := 20
来源：http://dali.jqgufenzy.top/Article/details/gtfuddxxjf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuxming.cn/Article/details/gtouclnbot.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gtjqcjhlkw.html

[A03] 常量定义
来源：http://dali.tanke756.top/Article/details/gtxsfmfxqg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jqgfzy.top/Article/details/gtcshyekbn.html

PHP:  const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuxallvz.html

JS:   const PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtfpewpctk.html

TS:   const PI: number = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtvgzbqzxk.html

Java: static final double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtuhzgzuyy.html

Go:   const PI = 3.14159
来源：http://dali.ivvv.top/Article/details/gtawdouksd.html

Ruby: PI = 3.14159
来源：http://dali.meibo888.top/Article/details/gtyzlvrthp.html

C#:   const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtaqutqyzu.html

[A04] 判断变量类型
来源：http://dali.hfpthk.cn/Article/details/gtzzuumxlm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xinyue.icu/Article/details/gtgffjgryw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuxming.cn/Article/details/gtebozrnvb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tian-w.cn/Article/details/gttbitucnl.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigufen.top/Article/details/gtnnzgllzz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjizfdvk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ybcxt.top/Article/details/gtrsftwctq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yanxiufei.cn/Article/details/gthjqpoqdq.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj202588.top/Article/details/gtslrmnyha.html

[A05] 整数除法与取模
来源：http://dali.yj202588.top/Article/details/gtsxxrvsxp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yuxming.cn/Article/details/gtylaqwonb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtdkhjtrnh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gttrmcyifd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtltszlbnb.html

Java: 7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtnfjaooql.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtscmjsqcr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtgnmjpnjw.html

C#:   7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtjtryxihs.html

[A06] 字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtlrlputde.html

Py:   int("42"); float("3.14")
来源：http://dali.bjfxy.top/Article/details/gtmzxpzowr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cucudq.cn/Article/details/gtsacwless.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.redwolf501.top/Article/details/gtkonlyidc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhixingplan.top/Article/details/gtbbzuarpt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ppjwa.cn/Article/details/gtqyiqntwn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.wangshuangyany.cn/Article/details/gtolqqezkp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hongshengwenyu.top/Article/details/gtjxsdfldn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.mhx1999.top/Article/details/gtfdyggrei.html

[A07] 数字转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyyeenpq.html

Py:   str(42)
来源：http://dali.pengpengdd.cyou/Article/details/gtyfowkjnh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zdqjudy.top/Article/details/gtttrngsut.html

JS:   String(42); (42).toString()
来源：http://dali.hammf.cn/Article/details/gtnxcaxvqe.html

TS:   String(42)
来源：http://dali.shzxlz.cn/Article/details/gtpkxhzvvx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqgrgvpp.html

Go:   strconv.Itoa(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsfliojw.html

Ruby: 42.to_s
来源：http://dali.jyoumei.cn/Article/details/gtppdhviil.html

C#:   42.ToString()
来源：http://dali.guowangkeji.top/Article/details/gthqzeogtn.html

[A08] 取整与四舍五入
来源：http://dali.xuanzx.com/Article/details/gtoorasyhd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtydkpdnvo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.snrcjt.cn/Article/details/gtucqfpiqd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtklkwpylp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.fzhhl.top/Article/details/gtqnqqhips.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtfuyqutym.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gttiihxntm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.andypj.xyz/Article/details/gtofhvennd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtcsqpchth.html

[A09] 绝对值与最大最小值
来源：http://dali.xuetiantiany.cn/Article/details/gttgyambyf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtsiimmeti.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtqfhsqxfq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.pycfn.com/Article/details/gtrbvuictt.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtucrxdomm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtxxoqpdkd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.birdmap.top/Article/details/gtcmuvmiro.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvrqlwcx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.c1oappe.top/Article/details/gthemccrhz.html

[A10] 生成随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhzvpjnq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.nwbrower.top/Article/details/gtptfqvgxk.html

PHP:  random_int(1, 100);
来源：http://dali.daria6918.cn/Article/details/gtlyhggywn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sysykeji.top/Article/details/gtebztdcvm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nwbrower.top/Article/details/gtndvjfqus.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gtznbfvjtk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gotoacloud.top/Article/details/gtssgpvxgg.html

Ruby: rand(1..100)
来源：http://dali.guannengcc.top/Article/details/gtvwdsjgwz.html

C#:   new Random().Next(1, 101)
来源：http://dali.gogol.net.cn/Article/details/gtavwgwodr.html

[A11] 条件表达式（三元）
来源：http://dali.316326.xyz/Article/details/gtdtbuorfs.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jianghu66.top/Article/details/gtkwilhjpa.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtgvtssaek.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gtutdkfgjl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtfwdvsetr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtbzsiwmol.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.aizwys.cn/Article/details/gtvrleqyjd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtrqkntyjp.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtferbuowc.html

[A12] 字符串插值 / 格式化
来源：http://dali.pycfn.com/Article/details/gtllofusef.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.chenjidiqi.icu/Article/details/gtqsdhtgji.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yj20258888.top/Article/details/gtylrfobje.html

JS:   `Hello, ${name}!`
来源：http://dali.ehwqpu.com/Article/details/gthumvhrex.html

TS:   `Hello, ${name}!`
来源：http://dali.xuetiantiany.cn/Article/details/gtbqysdbtp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jlsjyb.cn/Article/details/gtfbhtqrlq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.pycfn.com/Article/details/gtcdsnjvoz.html

Ruby: "Hello, #{name}!"
来源：http://dali.316326.xyz/Article/details/gtosnjwlvo.html

C#:   $"Hello, {name}!"
来源：http://dali.zhongyouzk.top/Article/details/gtqfspjcqh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.andypj.xyz/Article/details/gtlayqjlba.html

Py:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtlzyxdcnh.html

PHP:  "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtdnpofovk.html

JS:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtrtidwbqq.html

TS:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtibteszid.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtcwggwswd.html

Go:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtmklkulbw.html

Ruby: "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtgpavhcxz.html

C#:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtlrzhxfbj.html

[A14] 注释写法
来源：http://dali.gaohongyu789.top/Article/details/gtwfclxdix.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ybcxt.top/Article/details/gtszyxqkfx.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtwzcosmdt.html

JS:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gtyawyhpbq.html

TS:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gtqimnoafi.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.svipenyu.cn/Article/details/gtyytajhgp.html

Go:   // 单行；/* 多行 */
来源：http://dali.chenlongwang.top/Article/details/gtyybjuata.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.nwbrower.top/Article/details/gtmeaqrnzr.html


<!-- 参考信息 -->