代发 wailian999

[U85] JS：可选链
来源：http://dali.yangfankeji.com/Article/details/gtuwvgmziz.html

a?.b?.c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmkeeomk.html

[U86] JS：空值合并
来源：http://dali.yuanzhike.top/Article/details/gturrtbnfq.html

a ?? b
来源：http://dali.wangshuangyany.cn/Article/details/gtfwuxzokp.html

[U87] JS：解构默认值
来源：http://dali.cdnleiting.top/Article/details/gtqecnhdga.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxinkj.top/Article/details/gtvhczmyif.html

[U88] JS：对象展开合并
来源：http://dali.hysaishi.cn/Article/details/gtdxaykpcf.html

{ ...a, ...b }
来源：http://dali.tian-w.cn/Article/details/gtfevjqhgb.html

[U89] JS：数组去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtuidxdiig.html

[...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtboaitalr.html

[U90] JS：数字数组排序
来源：http://dali.zycfv.cn/Article/details/gtrbowwlko.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilwtsmnk.html

[U91] JS：对象键值遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytbdyvmw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pengpengdd.cyou/Article/details/gtqswufsxo.html

[U92] JS：深拷贝
来源：http://dali.ivvv.top/Article/details/gtcetqothp.html

structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtmukxghln.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsqxhwtq.html

`共 ${n} 条`
来源：http://dali.sweek.top/Article/details/gtyuudojkv.html

[U94] JS：箭头函数
来源：http://dali.xziqi.cn/Article/details/gtngwphfrm.html

const double = x => x * 2;
来源：http://dali.sysykeji.top/Article/details/gtatdrbjkf.html

[U95] JS：Promise 包装
来源：http://dali.yonumen.top/Article/details/gttjifwmzl.html

new Promise((resolve, reject) => {})
来源：http://dali.haohaochexian.top/Article/details/gtfowvdbqw.html

[U96] JS：async/await 与异常
来源：http://dali.dashuyun.cn/Article/details/gttyzpkgim.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtwidxxzmg.html

[U97] JS：并发请求
来源：http://dali.xylfe.cn/Article/details/gttrzbatdz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtzhwnmwri.html

[U98] JS：fetch 带 JSON
来源：http://dali.jiagoushi.top/Article/details/gtzdytrjjv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnqzz.top/Article/details/gthediokqe.html

[U99] JS：事件监听
来源：http://dali.zycfv.cn/Article/details/gtrmelmhjw.html

el.addEventListener("click", e => {})
来源：http://dali.jiagoushi.top/Article/details/gtkbsrsnjw.html

[U100] JS：DOM 查询
来源：http://dali.pengpengdd.cyou/Article/details/gtjlszmyxi.html

document.querySelector(".item")
来源：http://dali.c1oappe.top/Article/details/gtxztjblpf.html

[U101] JS：classList 操作
来源：http://dali.9152youxi.cn/Article/details/gtzvwphfsb.html

el.classList.toggle("active")
来源：http://dali.chenzaomai.com/Article/details/gtbajnjrtt.html

[U102] JS：本地存储
来源：http://dali.sweek.top/Article/details/gtycysqedw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tanke756.top/Article/details/gtvpnvxnps.html

[U103] JS：定时器
来源：http://dali.jiagoushi.top/Article/details/gtvzcftlry.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hywenlv.cn/Article/details/gtzdbaatyf.html

[U104] JS：防抖
来源：http://dali.havefunace.top/Article/details/gttqggmqku.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtrfkokqvx.html

[U105] JS：节流
来源：http://dali.fzhhl.top/Article/details/gtresmmsus.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.kuanghao11.cn/Article/details/gtywytavdl.html

[U106] JS：日期格式化
来源：http://dali.birdmap.top/Article/details/gtjngkhcgi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shangyingyoupin.top/Article/details/gttyuxxqef.html

[U107] JS：数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gttubohutt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gttqxoxstx.html

[U108] JS：随机整数
来源：http://dali.haohaochexian.top/Article/details/gtkkhfuvpj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shuidangran.top/Article/details/gtlmgbsxli.html

[U109] JS：数组分组
来源：http://dali.c1oappe.top/Article/details/gtdhqpkple.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtkmkhyjxa.html

[U110] JS：数组分块
来源：http://dali.zycfv.cn/Article/details/gtxrphxtpa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ybcxt.top/Article/details/gtwulmwhlp.html

[U111] JS：对象转 Map
来源：http://dali.pycfn.com/Article/details/gtzwihknnh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtymybafzp.html

[U112] JS：字符串补位
来源：http://dali.dashuyun.cn/Article/details/gtwjvhhhld.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtvxxwvzlk.html

[U113] JS：正则替换全部
来源：http://dali.yonumen.top/Article/details/gthohaenao.html

s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtunevobpk.html

[U114] JS：JSON 深比较
来源：http://dali.hnxiangtu.top/Article/details/gtppqzwcmv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtyxnzthsh.html

[U115] JS：生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtfycsgfjw.html

crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtbdjageki.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xziqi.cn/Article/details/gtswhufsqs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gtscsvcavk.html

[U117] JS：单元测试
来源：http://dali.sysykeji.top/Article/details/gtjeedldve.html

npm i -D vitest;  npx vitest
来源：http://dali.gzhubu.top/Article/details/gtaipmjycv.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsqzopun.html

npm i -D vite;  npx vite
来源：http://dali.shzxlz.cn/Article/details/gtodxrybqx.html

[U119] JS：生产构建
来源：http://dali.hywenlv.cn/Article/details/gtshohjqry.html

npx vite build
来源：http://dali.guowangkeji.top/Article/details/gtlaofrzec.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zycfv.cn/Article/details/gtkpurghhr.html

import.meta.env.VITE_API_URL
来源：http://dali.svipenyu.cn/Article/details/gtsvoqzwkx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtofeqkdou.html

统计汇总
来源：http://dali.xuetiantiany.cn/Article/details/gtoxajtgkl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtezvufxta.html

按语言统计（条）：
来源：http://dali.redwolf501.top/Article/details/gtipjfvlhz.html

Python ......... 252
来源：http://dali.yuanzhike.top/Article/details/gtmlgoiyme.html

PHP ............ 252
来源：http://dali.ydzc1.top/Article/details/gtjqvlraue.html

JavaScript ..... 252
来源：http://dali.havefunace.top/Article/details/gtpliklimb.html

TypeScript ..... 212
来源：http://dali.yonumen.top/Article/details/gtyqxasqjx.html

Java ........... 212
来源：http://dali.cheryme.top/Article/details/gtqrzyoqml.html

Go ............. 212
来源：http://dali.zhiwuduotai.top/Article/details/gtrmxodrbv.html

Ruby ........... 212
来源：http://dali.yongpay.top/Article/details/gtyfxbcyft.html

C# ............. 212
来源：http://dali.gogol.net.cn/Article/details/gtciewznxa.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcbwrijv.html

C++ ............ 30
来源：http://dali.jinqigfzy.top/Article/details/gtghnleiww.html

SQL ............ 90
来源：http://dali.yanxiufei.cn/Article/details/gtrupatfyz.html

Bash ........... 80
来源：http://dali.zhengqikj.top/Article/details/gtrgsubeun.html

Kotlin ......... 15
来源：http://dali.yj20258.top/Article/details/gtztnumpea.html

Swift .......... 15
来源：http://dali.mhx1999.top/Article/details/gtbbqpkzlj.html

Lua ............ 10
来源：http://dali.birdmap.top/Article/details/gtvlrjbisp.html

Perl ........... 10
来源：http://dali.cucudq.cn/Article/details/gtwpaqhayl.html

Scala .......... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtschyuyxp.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtdtvdqihb.html

合计 ........... 2106 条
来源：http://dali.zhoulong.xyz/Article/details/gturetyluf.html

按章节统计：
来源：http://dali.cheryme.top/Article/details/gtmcilhgnm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangtech.top/Article/details/gtbikkakxh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gtysygocpw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gtixvibsrj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gtkcoznpib.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.wangshuangyany.cn/Article/details/gtnmvahkcl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipdijoro.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gtvmcjdqrv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gtsbsecqlr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtjyydszhb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gtbrdyfsdg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkowldrlz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtdvhcrxlz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtrsgenvpm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gtjnmwslnt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenzaomai.com/Article/details/gtymsvfozu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtbbutmfhu.html

Q SQL 专题                              90
来源：http://dali.ydzc1.top/Article/details/gttqptkhsq.html

R Bash 专题                             80
来源：http://dali.c1oappe.top/Article/details/gtepjupapf.html

S C / C++ 专题                          60
来源：http://dali.snrcjt.cn/Article/details/gtdpzdufwl.html

T 其他语言补充                          60
来源：http://dali.mhx1999.top/Article/details/gtrwkxhcyw.html

U 高频实用片段                         120
来源：http://dali.hongshengwenyu.top/Article/details/gtpwljjlmw.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtlpyetmxd.html

合计                                  2106 条
来源：http://dali.yj202588.top/Article/details/gtbqvtlmmf.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtwitztxee.html

使用提醒
来源：http://dali.yvedp.cn/Article/details/gtjmvilyjh.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtqsuproxg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.aizwys.cn/Article/details/gtgzmprqgg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cqqwz.cn/Article/details/gtjetnrgol.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yanxiufei.cn/Article/details/gtzngkbvqp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj202588.top/Article/details/gtcibxwfmw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gzhubu.top/Article/details/gtklrbhuzs.html

—— 文件结束 ——
来源：http://dali.zhengqikj.top/Article/details/gteiczxkqd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtohthwevm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.kuanghao11.cn/Article/details/gtulihclld.html

Common Programming Examples Cheat Book
来源：http://dali.wangshuangyany.cn/Article/details/gtooydqrgn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtlhgbkwwn.html

【收录内容】
来源：http://dali.snrcjt.cn/Article/details/gtuekzqdqt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cheryme.top/Article/details/gtjfhxssoj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hnqzz.top/Article/details/gtagyeqkrz.html

SQL · Bash · C · C++
来源：http://dali.tanke756.top/Article/details/gtitjrjbhv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.meibo888.top/Article/details/gttcizytld.html

【使用说明】
来源：http://dali.daxiang520.top/Article/details/gtvncfdenc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jiagoushi.top/Article/details/gtezoptftw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yueranfly.top/Article/details/gtyidyzoqd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.wangshuangyany.cn/Article/details/gtlwbvvesj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aizwys.cn/Article/details/gtpkhuhupf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.meibo888.top/Article/details/gttqplkyfi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yangfankeji.com/Article/details/gtczemkovu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnxiangtu.top/Article/details/gtueilngkl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cqqwz.cn/Article/details/gtoexwxggo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.0kj1m.cn/Article/details/gtohyismbi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sysykeji.top/Article/details/gtcfefuknf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.316326.xyz/Article/details/gtpchxkhby.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.svipenyu.cn/Article/details/gtqnmtvswa.html

【文件统计】
来源：http://dali.yonumen.top/Article/details/gtgzqdmmec.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenlongwang.top/Article/details/gtkjuglzvx.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtlnczxvqr.html

目  录
来源：http://dali.gaohongyu789.top/Article/details/gtgjnknaol.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gtgrxtduzh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cdnleiting.top/Article/details/gtnxuertje.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gtizylamhm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.snrcjt.cn/Article/details/gtqykqcomv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hysaishi.cn/Article/details/gtizswsxpa.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hfpthk.cn/Article/details/gtgafmkuli.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gtpqkxcfer.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gtiercwpti.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj202588.top/Article/details/gtikzkdzps.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtipxxuisx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.pycfn.com/Article/details/gtattyclce.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtmnfgiwja.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtmgbimndq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gttbmdjxyy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.svipenyu.cn/Article/details/gtxwdjzbsu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nanxuanxn.top/Article/details/gtzwluaaca.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtbomzqkog.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj202588.top/Article/details/gtmegqespw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtuujmwpcg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xuanzx.com/Article/details/gttvuvwvoa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtxiwcsyls.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj202588.top/Article/details/gtypobcnkm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtttkihmrl.html

A. 基础语法与类型
来源：http://dali.hysaishi.cn/Article/details/gteeljihmh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtewoogohh.html

[A01] Hello World
来源：http://dali.hysaishi.cn/Article/details/gtcmejydki.html

Py:   print("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gtqcubraqv.html

PHP:  echo "Hello, World!";
来源：http://dali.tanke756.top/Article/details/gtilwouaev.html

JS:   console.log("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtkewmggbh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gtgdgkouab.html

Java: System.out.println("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gtnogngppu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gtclvpwheu.html

Ruby: puts "Hello, World!"
来源：http://dali.dashuyun.cn/Article/details/gtasdeuuno.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gtxeidgazx.html

[A02] 变量声明与赋值
来源：http://dali.iojbl.cn/Article/details/gthypegeno.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnzikxms.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj202588.top/Article/details/gtxmabodhg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtbjgyqnkw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.guowangkeji.top/Article/details/gtcslsgpez.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtqkwvizek.html

Go:   name := "Alex"; age := 20
来源：http://dali.0kj1m.cn/Article/details/gtpipglhfx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuetiantiany.cn/Article/details/gtbrhhuhxt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cashguo.top/Article/details/gtvdpjacha.html

[A03] 常量定义
来源：http://dali.yj20258888.top/Article/details/gtprxaigqn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cucudq.cn/Article/details/gtlmeksigk.html

PHP:  const PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtsuvwgfmv.html

JS:   const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtrwyokyey.html

TS:   const PI: number = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtsdwoofmv.html

Java: static final double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtatnpakon.html

Go:   const PI = 3.14159
来源：http://dali.nwbrower.top/Article/details/gtfvxunsik.html

Ruby: PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtipbirmvg.html

C#:   const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtfzsqjxvk.html

[A04] 判断变量类型
来源：http://dali.redwolf501.top/Article/details/gtswyuqpiu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhoulong.xyz/Article/details/gtjcigughn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cheryme.top/Article/details/gtnaqpqiav.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jqgufenzy.top/Article/details/gtwljqrqxo.html

TS:   typeof x; x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gtxmyhduxn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tanke756.top/Article/details/gtsjbesycb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnqzz.top/Article/details/gthvlcrekp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.tian-w.cn/Article/details/gtzdkpatsp.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenjidiqi.icu/Article/details/gtyfwesikz.html

[A05] 整数除法与取模
来源：http://dali.guowangkeji.top/Article/details/gtrpcrsnbw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.snrcjt.cn/Article/details/gtpeknapkn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtapxuzxuz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtlxfcwetq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtgkssrtka.html

Java: 7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtmmkkgnol.html

Go:   7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtirvklbfh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtzjazvbio.html

C#:   7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gtviskcwmi.html

[A06] 字符串转数字
来源：http://dali.yj20258888.top/Article/details/gtkdiotwrq.html

Py:   int("42"); float("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gtqtwrbced.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fengsongda.top/Article/details/gtmucnyyic.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtoxqempiw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hongshengwenyu.top/Article/details/gtuzfvbznd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sxryk.cn/Article/details/gtdruwyhsw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yongpay.top/Article/details/gtdpckqpke.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cashguo.top/Article/details/gtjaadirpf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ivvv.top/Article/details/gtuhxvddxl.html

[A07] 数字转字符串
来源：http://dali.sysykeji.top/Article/details/gtnabmqpfz.html

Py:   str(42)
来源：http://dali.daxiang520.top/Article/details/gtcyhpcubd.html

PHP:  (string) 42; strval(42)
来源：http://dali.yuxming.cn/Article/details/gthfxknsnj.html

JS:   String(42); (42).toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtqgfnighd.html

TS:   String(42)
来源：http://dali.0kj1m.cn/Article/details/gteubtpkdm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zycfv.cn/Article/details/gtqnervbir.html

Go:   strconv.Itoa(42)
来源：http://dali.fengsongda.top/Article/details/gtrqhidpcw.html

Ruby: 42.to_s
来源：http://dali.cqqwz.cn/Article/details/gtkzvomvmw.html

C#:   42.ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpdemqke.html

[A08] 取整与四舍五入
来源：http://dali.zhixingplan.top/Article/details/gtbbgpemrp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtpnipgeig.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ivvv.top/Article/details/gtyowejups.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gtkrjcfgas.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cashguo.top/Article/details/gtvcdjhxsr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtylevrmyk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtklkswbpr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.wangdashe.top/Article/details/gtwtaawfvk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gtbtqgptbn.html

[A09] 绝对值与最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqiuctpi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtbpnludkr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtdfaojdkx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtdjtjkmev.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtcsdhbglg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj202588.top/Article/details/gtappluxtj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.pycfn.com/Article/details/gtxmczzgxa.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sufxvd.cn/Article/details/gtdqccntxe.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cashguo.top/Article/details/gtscaljteu.html

[A10] 生成随机数
来源：http://dali.redwolf501.top/Article/details/gtpyqrcbrl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.kuanghao11.cn/Article/details/gtlzzfmicf.html

PHP:  random_int(1, 100);
来源：http://dali.gotoacloud.top/Article/details/gtrkyjfhdw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hammf.cn/Article/details/gtjsjbubmx.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ydzc1.top/Article/details/gtdpfxassz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinqigufen.top/Article/details/gtxinmdayr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.nanxuanxn.top/Article/details/gtfrdoxcst.html

Ruby: rand(1..100)
来源：http://dali.svipenyu.cn/Article/details/gtircmisoc.html

C#:   new Random().Next(1, 101)
来源：http://dali.nwbrower.top/Article/details/gthuhmwbdt.html

[A11] 条件表达式（三元）
来源：http://dali.zdqjudy.top/Article/details/gtkffwcjum.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jlsjyb.cn/Article/details/gtnvrvulmn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gtgssgfmmz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gtgwejofod.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gtbbbahack.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gtbaljzphc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinqigufen.top/Article/details/gthbozivhy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gtbiubmbjc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtkoomydqz.html

[A12] 字符串插值 / 格式化
来源：http://dali.9152youxi.cn/Article/details/gtzjulzkwe.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.svipenyu.cn/Article/details/gtmiudtijs.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cashguo.top/Article/details/gtbgaewozp.html

JS:   `Hello, ${name}!`
来源：http://dali.yuanzhike.top/Article/details/gtcumcxlvg.html

TS:   `Hello, ${name}!`
来源：http://dali.cucudq.cn/Article/details/gtjdegswmg.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.iojbl.cn/Article/details/gtskmxlfcq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hnxiangtu.top/Article/details/gtcigdnpou.html

Ruby: "Hello, #{name}!"
来源：http://dali.yj20258.top/Article/details/gtqgjnqjnb.html

C#:   $"Hello, {name}!"
来源：http://dali.meibo888.top/Article/details/gtljnnbsmj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.pengpengdd.cyou/Article/details/gtqmjypceo.html

Py:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gttspfhafu.html

PHP:  "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtdtxsajir.html

JS:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtpujijvnf.html

TS:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtcpnjympt.html

Java: "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtxnhfrdeb.html

Go:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtnycrxbsn.html

Ruby: "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtqjghguff.html

C#:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmqwnpxs.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gtlgzaodul.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hysaishi.cn/Article/details/gtlsggklbq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtcvymlntg.html

JS:   // 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gtsybjnybr.html


<!-- 参考信息 -->