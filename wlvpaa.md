代发 wailian999

[U85] JS：可选链
来源：http://dali.jiagoushi.top/Article/details/gtlbmmczqs.html

a?.b?.c
来源：http://dali.chenlongwang.top/Article/details/gtrorntpiq.html

[U86] JS：空值合并
来源：http://dali.dianchejie.cn/Article/details/gtttqocecm.html

a ?? b
来源：http://dali.c1oappe.top/Article/details/gtgvbsminw.html

[U87] JS：解构默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtqgyojsdw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ivvv.top/Article/details/gtleyzlvtr.html

[U88] JS：对象展开合并
来源：http://dali.cdnleiting.top/Article/details/gtoajvlioc.html

{ ...a, ...b }
来源：http://dali.jqgfzy.top/Article/details/gtwgnwnosc.html

[U89] JS：数组去重
来源：http://dali.gogol.net.cn/Article/details/gtpczudkkr.html

[...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtehqiymkh.html

[U90] JS：数字数组排序
来源：http://dali.yj20258.top/Article/details/gtfenvbtja.html

[...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gthdewkliz.html

[U91] JS：对象键值遍历
来源：http://dali.zdqjudy.top/Article/details/gttcgqdkra.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xinyue.icu/Article/details/gtswbgpgbu.html

[U92] JS：深拷贝
来源：http://dali.cheryme.top/Article/details/gtqvsjymhk.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtlwyivjzw.html

[U93] JS：模板字符串
来源：http://dali.yuanzhike.top/Article/details/gtbjvfewvz.html

`共 ${n} 条`
来源：http://dali.guannengcc.top/Article/details/gtcrkuxxze.html

[U94] JS：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbcmagct.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gtygkdjyot.html

[U95] JS：Promise 包装
来源：http://dali.haohaochexian.top/Article/details/gthijlyput.html

new Promise((resolve, reject) => {})
来源：http://dali.dashuyun.cn/Article/details/gtbzpizpwo.html

[U96] JS：async/await 与异常
来源：http://dali.gotoacloud.top/Article/details/gtqoskdhnh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtaaizobvr.html

[U97] JS：并发请求
来源：http://dali.gzhubu.top/Article/details/gtmcyjasoc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonoyxcqp.html

[U98] JS：fetch 带 JSON
来源：http://dali.fengsongda.top/Article/details/gtpmwwmdzw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yongpay.top/Article/details/gtkpopphni.html

[U99] JS：事件监听
来源：http://dali.smart0.xyz/Article/details/gtdpraxqiz.html

el.addEventListener("click", e => {})
来源：http://dali.nanxinkj.top/Article/details/gtwpchfkai.html

[U100] JS：DOM 查询
来源：http://dali.xylfe.cn/Article/details/gttjjolwin.html

document.querySelector(".item")
来源：http://dali.jyoumei.cn/Article/details/gtorkguzdg.html

[U101] JS：classList 操作
来源：http://dali.shangyingyoupin.top/Article/details/gteptqtosl.html

el.classList.toggle("active")
来源：http://dali.hysaishi.cn/Article/details/gtfpugunpj.html

[U102] JS：本地存储
来源：http://dali.tanke756.top/Article/details/gtrxdbykhq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.vqdsnc.cn/Article/details/gtbqzfsiap.html

[U103] JS：定时器
来源：http://dali.sufxvd.cn/Article/details/gtwzdpdpth.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj202588.top/Article/details/gtxfajuqfu.html

[U104] JS：防抖
来源：http://dali.zdqjudy.top/Article/details/gthbennymz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtcbfvxldq.html

[U105] JS：节流
来源：http://dali.andypj.xyz/Article/details/gtgnvnjpid.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gogol.net.cn/Article/details/gtacgfzbaz.html

[U106] JS：日期格式化
来源：http://dali.birdmap.top/Article/details/gtamwsxvcl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xylfe.cn/Article/details/gthbsxjgbg.html

[U107] JS：数字千分位
来源：http://dali.ppjwa.cn/Article/details/gtldjcuupe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtlfjsqdtd.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjapvplp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tianlin.xyz/Article/details/gtoviatszo.html

[U109] JS：数组分组
来源：http://dali.gaohongyu789.top/Article/details/gtdpldsnlg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtppoimhgy.html

[U110] JS：数组分块
来源：http://dali.hfpthk.cn/Article/details/gtulngebwe.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.guannengcc.top/Article/details/gtgmqfkjmh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gtdijelkve.html

new Map(Object.entries(obj))
来源：http://dali.jiagoushi.top/Article/details/gtqozdqurm.html

[U112] JS：字符串补位
来源：http://dali.fengsongda.top/Article/details/gtqysxmiaw.html

"7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtjdkrcgfa.html

[U113] JS：正则替换全部
来源：http://dali.daria6918.cn/Article/details/gtuoftoadr.html

s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqrzqpax.html

[U114] JS：JSON 深比较
来源：http://dali.hnqzz.top/Article/details/gtgrfdooom.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtqovqmmsg.html

[U115] JS：生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gtbxgpngiy.html

crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtcyaujvud.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daxiang520.top/Article/details/gtthvyydpw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.iojbl.cn/Article/details/gtcsjdeoag.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtvoazvkzt.html

npm i -D vitest;  npx vitest
来源：http://dali.zhongyouzk.top/Article/details/gtjxvebzpx.html

[U118] JS：开发服务器
来源：http://dali.chenzaomai.com/Article/details/gtkyiysuvd.html

npm i -D vite;  npx vite
来源：http://dali.gotoacloud.top/Article/details/gtfztoiodf.html

[U119] JS：生产构建
来源：http://dali.jinqigfzy.top/Article/details/gtakcqdhtz.html

npx vite build
来源：http://dali.jyoumei.cn/Article/details/gtvxdnfgmq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ehwqpu.com/Article/details/gtoozthzvn.html

import.meta.env.VITE_API_URL
来源：http://dali.smart0.xyz/Article/details/gthcsybmtg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtatcuaraa.html

统计汇总
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadaffdtx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsribzubf.html

按语言统计（条）：
来源：http://dali.chenjidiqi.icu/Article/details/gtzmbpsonx.html

Python ......... 252
来源：http://dali.hfpthk.cn/Article/details/gtfvjhyirn.html

PHP ............ 252
来源：http://dali.tanke756.top/Article/details/gtfeqohklk.html

JavaScript ..... 252
来源：http://dali.ybcxt.top/Article/details/gtdmwazwlx.html

TypeScript ..... 212
来源：http://dali.ivvv.top/Article/details/gtrwjahuwa.html

Java ........... 212
来源：http://dali.jiagoushi.top/Article/details/gtshekkdum.html

Go ............. 212
来源：http://dali.cheryme.top/Article/details/gtiluizmmw.html

Ruby ........... 212
来源：http://dali.zdqjudy.top/Article/details/gtiovedwtn.html

C# ............. 212
来源：http://dali.aizwys.cn/Article/details/gtbvokeuzx.html

C .............. 30
来源：http://dali.zdqjudy.top/Article/details/gtelqsbokx.html

C++ ............ 30
来源：http://dali.haohaochexian.top/Article/details/gtnfdccbiz.html

SQL ............ 90
来源：http://dali.wangshuangyany.cn/Article/details/gtgdxxksdo.html

Bash ........... 80
来源：http://dali.iojbl.cn/Article/details/gtvedsvopw.html

Kotlin ......... 15
来源：http://dali.0kj1m.cn/Article/details/gtcerbhuil.html

Swift .......... 15
来源：http://dali.daxiang520.top/Article/details/gttgeargaz.html

Lua ............ 10
来源：http://dali.hnxiangtu.top/Article/details/gthvxqhzgy.html

Perl ........... 10
来源：http://dali.316326.xyz/Article/details/gtluzwifox.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gtequqmuzr.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtipepejlx.html

合计 ........... 2106 条
来源：http://dali.yj202588.top/Article/details/gtbprtckbm.html

按章节统计：
来源：http://dali.sweek.top/Article/details/gtsnbfaqis.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtirorholy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtrzohkequ.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gttxsgfqgc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ppjwa.cn/Article/details/gtfqonpgdg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xylfe.cn/Article/details/gtfegvisll.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gtmehpmwbn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gtnuitzczf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gtxnlnjzfw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtiaqrbbni.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yongpay.top/Article/details/gtsjdorqdz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtjzecuvih.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtcyvpyimm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtsumzjgkm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cucudq.cn/Article/details/gtffbdfwzb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shangyingyoupin.top/Article/details/gtmczgblya.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtmpgvkfoz.html

Q SQL 专题                              90
来源：http://dali.sysykeji.top/Article/details/gthqlyldqk.html

R Bash 专题                             80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaphjweim.html

S C / C++ 专题                          60
来源：http://dali.yuanzhike.top/Article/details/gtrpmmrpcd.html

T 其他语言补充                          60
来源：http://dali.andypj.xyz/Article/details/gtmuczpcvi.html

U 高频实用片段                         120
来源：http://dali.jiagoushi.top/Article/details/gtdubwdnnn.html

------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtdtqgivtf.html

合计                                  2106 条
来源：http://dali.snrcjt.cn/Article/details/gtgdyqcqhp.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gttvrbvltf.html

使用提醒
来源：http://dali.zhixingplan.top/Article/details/gtoiwrqjxw.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gtzteyhlum.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cucudq.cn/Article/details/gtmwzhpphn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.pengpengdd.cyou/Article/details/gtuvojdjaj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yuxming.cn/Article/details/gtlmkehgwf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jianghu66.top/Article/details/gtvksnqszc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cashguo.top/Article/details/gtabwlpgmz.html

—— 文件结束 ——
来源：http://dali.chenlongwang.top/Article/details/gtcejthiyc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtojgksjgi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yanxiufei.cn/Article/details/gtolijkksf.html

Common Programming Examples Cheat Book
来源：http://dali.316326.xyz/Article/details/gtkwwltuva.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtucrseiyl.html

【收录内容】
来源：http://dali.nanxinkj.top/Article/details/gtgypiqncz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigfzy.top/Article/details/gthyqbivqs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuxming.cn/Article/details/gtyofacxhr.html

SQL · Bash · C · C++
来源：http://dali.9152youxi.cn/Article/details/gtrczrsjyi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hammf.cn/Article/details/gtwtuxmuzv.html

【使用说明】
来源：http://dali.andypj.xyz/Article/details/gtbtyzepqh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.haohaochexian.top/Article/details/gtdokqntym.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.haohaochexian.top/Article/details/gthqlhzhjr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.daxiang520.top/Article/details/gtwgzbmopa.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yueranfly.top/Article/details/gtetieqwgp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zdqjudy.top/Article/details/gtveiizbcs.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj20258888.top/Article/details/gthujvluna.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cdnleiting.top/Article/details/gtqzxdcrzs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.pengpengdd.cyou/Article/details/gtbxzoqvxx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.daria6918.cn/Article/details/gtbfepcpvd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqgsgaaa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.havefunace.top/Article/details/gtftmspdbb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenzaomai.com/Article/details/gtjshwuahs.html

【文件统计】
来源：http://dali.ydzc1.top/Article/details/gtcqyyrdpa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.snrcjt.cn/Article/details/gtappxhdeg.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtasieqirt.html

目  录
来源：http://dali.chenzaomai.com/Article/details/gtwjtwtuqr.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtdbydgqfw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yongpay.top/Article/details/gtoksuiuuy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ppjwa.cn/Article/details/gtoqhbyxoj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gtrjiefwap.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtkkxzkjzq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenlongwang.top/Article/details/gtnhhbnegk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtgyhmplbj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yanxiufei.cn/Article/details/gtgcjrbjvd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.havefunace.top/Article/details/gtrbnkunqd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtbzphwtrw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.c1oappe.top/Article/details/gtptzvocnt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtwnylclcf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtguqxklaz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtsfhkjfeu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gtdfdnnvhc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.haohaochexian.top/Article/details/gtuocpkswt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gtaijtuvpk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sxryk.cn/Article/details/gtfkesbdgu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pycfn.com/Article/details/gtuukvkoeh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.kuanghao11.cn/Article/details/gtdpylupls.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gteqcpheba.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gthwojobjm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtybhlitev.html

A. 基础语法与类型
来源：http://dali.gaohongyu789.top/Article/details/gtqvjyhqxs.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtijtnwvjp.html

[A01] Hello World
来源：http://dali.yuxming.cn/Article/details/gtfxfbzmqk.html

Py:   print("Hello, World!")
来源：http://dali.ehwqpu.com/Article/details/gtcsuqgdwn.html

PHP:  echo "Hello, World!";
来源：http://dali.zhiwuduotai.top/Article/details/gtqlyuxinz.html

JS:   console.log("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gtxmxnlepm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gotoacloud.top/Article/details/gtzhkrkwuj.html

Java: System.out.println("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtrwsqcvjp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknxzesor.html

Ruby: puts "Hello, World!"
来源：http://dali.bjfxy.top/Article/details/gteufrxhrf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtcqhosaeo.html

[A02] 变量声明与赋值
来源：http://dali.yj20258.top/Article/details/gtunlgsunl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.haohaochexian.top/Article/details/gtzhhqhbzh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hysaishi.cn/Article/details/gthlugxjys.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pycfn.com/Article/details/gtbrclrpgd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yongpay.top/Article/details/gtccmmswkp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtojsvxukr.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinqigufen.top/Article/details/gtaxlubdyk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gzhubu.top/Article/details/gtgyayfukz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.c1oappe.top/Article/details/gtvqyzgafo.html

[A03] 常量定义
来源：http://dali.cdnleiting.top/Article/details/gtwufmobtc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gtfoqcdest.html

PHP:  const PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtymjlzgar.html

JS:   const PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtnlndgoox.html

TS:   const PI: number = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtxjsegdui.html

Java: static final double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtxcypmnyf.html

Go:   const PI = 3.14159
来源：http://dali.smart0.xyz/Article/details/gtsatflmso.html

Ruby: PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gtjjeonxgf.html

C#:   const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtzwmnvqmk.html

[A04] 判断变量类型
来源：http://dali.gaohongyu789.top/Article/details/gtvacverox.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xuanzx.com/Article/details/gtvagcddzw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.tian-w.cn/Article/details/gtupesajks.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjqnwkkv.html

TS:   typeof x; x instanceof Date
来源：http://dali.hysaishi.cn/Article/details/gtwvccdfsf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gtgklfbwxy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xziqi.cn/Article/details/gtyfqegwbm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj20258.top/Article/details/gtawzyhmnb.html

C#:   x.GetType().Name; x is int
来源：http://dali.fengsongda.top/Article/details/gtrbdwnirx.html

[A05] 整数除法与取模
来源：http://dali.nanxinkj.top/Article/details/gtauirwnfe.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daxiang520.top/Article/details/gtmubdidgn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtqfzmbsdj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtoghfdgra.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtmtosdkul.html

Java: 7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtppnsxgtk.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtgagyfizn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gtcmzauelf.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtfnqvczkl.html

[A06] 字符串转数字
来源：http://dali.fengsongda.top/Article/details/gtsaebsnls.html

Py:   int("42"); float("3.14")
来源：http://dali.xziqi.cn/Article/details/gtqoresxzc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenzaomai.com/Article/details/gtruyhihau.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daria6918.cn/Article/details/gtbxrtbpbj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.gotoacloud.top/Article/details/gtilwozlrh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yueranfly.top/Article/details/gtqmmqfuhe.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.tianlin.xyz/Article/details/gtqabcrzlo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinghuilouyu.cn/Article/details/gthdhkbkrt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.tianlin.xyz/Article/details/gtqlorbtkr.html

[A07] 数字转字符串
来源：http://dali.dianchejie.cn/Article/details/gtlyucgupp.html

Py:   str(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtemtwntjj.html

PHP:  (string) 42; strval(42)
来源：http://dali.hnqzz.top/Article/details/gtqagcotxn.html

JS:   String(42); (42).toString()
来源：http://dali.xinyue.icu/Article/details/gtqfazmpqs.html

TS:   String(42)
来源：http://dali.cqqwz.cn/Article/details/gtxpgsyepg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tian-w.cn/Article/details/gtzculjyxt.html

Go:   strconv.Itoa(42)
来源：http://dali.chenlongwang.top/Article/details/gtfkbyikge.html

Ruby: 42.to_s
来源：http://dali.chenzaomai.com/Article/details/gtgcoakszc.html

C#:   42.ToString()
来源：http://dali.xylfe.cn/Article/details/gtwkyhatep.html

[A08] 取整与四舍五入
来源：http://dali.hfpthk.cn/Article/details/gtzcnocbfc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gtitiivokn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gzhubu.top/Article/details/gtonzbebvg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtzykllmqo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guannengcc.top/Article/details/gtocxmbzwb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtwjxrqrmk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtkdovrdto.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yongpay.top/Article/details/gtdbnjyhdm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gtbmpcqrfv.html

[A09] 绝对值与最大最小值
来源：http://dali.jinqigufen.top/Article/details/gtnvneyeyu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtkvuwdtqy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtrsncsaqf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtnoyglqlc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtsnveuwmc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtszncenrm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.nanxuanxn.top/Article/details/gtchsfhrto.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gotoacloud.top/Article/details/gtaygqmdtq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtuqanejjg.html

[A10] 生成随机数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspvxvmzn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.nwbrower.top/Article/details/gtbpesjotr.html

PHP:  random_int(1, 100);
来源：http://dali.dashuyun.cn/Article/details/gtlmfwkuic.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gtomqxowdv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtcduugyjb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xinyue.icu/Article/details/gtkfrbvlev.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cheryme.top/Article/details/gtwgbczctr.html

Ruby: rand(1..100)
来源：http://dali.jyoumei.cn/Article/details/gtxsicukti.html

C#:   new Random().Next(1, 101)
来源：http://dali.ppjwa.cn/Article/details/gtpzdlkioi.html

[A11] 条件表达式（三元）
来源：http://dali.smart0.xyz/Article/details/gtqrtotcxp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gotoacloud.top/Article/details/gtxvghhfgq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gtlodrfbxo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gtichtiopx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gtkbzvjiex.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gtlxjlidgk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.havefunace.top/Article/details/gtojgoibns.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gtcikwsofc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gtgoeoxhfb.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhongyouzk.top/Article/details/gtniuwtadm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.svipenyu.cn/Article/details/gtjlgpfjpf.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hammf.cn/Article/details/gtdavpfgix.html

JS:   `Hello, ${name}!`
来源：http://dali.birdmap.top/Article/details/gterphfwvp.html

TS:   `Hello, ${name}!`
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaushwch.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.mhx1999.top/Article/details/gtzlgljltv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.haohaochexian.top/Article/details/gtdwgmbwao.html

Ruby: "Hello, #{name}!"
来源：http://dali.xuetiantiany.cn/Article/details/gtgzuagury.html

C#:   $"Hello, {name}!"
来源：http://dali.tanke756.top/Article/details/gtlstulina.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.kuanghao11.cn/Article/details/gtamfctplx.html

Py:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtisjyvqaz.html

PHP:  "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtbrssvkya.html

JS:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtzbefmpoa.html

TS:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtbuylgkxk.html

Java: "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtaetsfhgm.html

Go:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gthxgcpybk.html

Ruby: "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtnlxcnqef.html

C#:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtfjwpcorz.html

[A14] 注释写法
来源：http://dali.nwbrower.top/Article/details/gtjuurjmxg.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.fengsongda.top/Article/details/gtyidadggj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gtkvrqwagi.html

JS:   // 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gtmcokwldy.html


<!-- 参考信息 -->