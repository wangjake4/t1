代发 wailian999

[U87] JS：解构默认值
来源：http://dali.xuanzx.com/Article/details/gtyutmocqk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.316326.xyz/Article/details/gtqhfqlvwq.html

[U88] JS：对象展开合并
来源：http://dali.jqgfzy.top/Article/details/gtvxinuimb.html

{ ...a, ...b }
来源：http://dali.andypj.xyz/Article/details/gtphdrcwwc.html

[U89] JS：数组去重
来源：http://dali.mhx1999.top/Article/details/gtqqiavsus.html

[...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtnxtkcvao.html

[U90] JS：数字数组排序
来源：http://dali.vqdsnc.cn/Article/details/gtwavvbiva.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtvdobeyyw.html

[U91] JS：对象键值遍历
来源：http://dali.bjfxy.top/Article/details/gtnmjpnzhl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258888.top/Article/details/gtfgoaywax.html

[U92] JS：深拷贝
来源：http://dali.chenlongwang.top/Article/details/gtjqufsqry.html

structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmxdfkhr.html

[U93] JS：模板字符串
来源：http://dali.aizwys.cn/Article/details/gtzmbesnfy.html

`共 ${n} 条`
来源：http://dali.tian-w.cn/Article/details/gtpllnnhew.html

[U94] JS：箭头函数
来源：http://dali.aizwys.cn/Article/details/gthffkardb.html

const double = x => x * 2;
来源：http://dali.xziqi.cn/Article/details/gtbebblcza.html

[U95] JS：Promise 包装
来源：http://dali.xuetiantiany.cn/Article/details/gtmqnpiqls.html

new Promise((resolve, reject) => {})
来源：http://dali.zhongyouzk.top/Article/details/gtrsoskxuz.html

[U96] JS：async/await 与异常
来源：http://dali.jqgfzy.top/Article/details/gtdngksrjo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtoubmzosf.html

[U97] JS：并发请求
来源：http://dali.cdnleiting.top/Article/details/gtlsuhafbl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtffeabcea.html

[U98] JS：fetch 带 JSON
来源：http://dali.jiagoushi.top/Article/details/gtonmhoaex.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gtdrnruetj.html

[U99] JS：事件监听
来源：http://dali.ivvv.top/Article/details/gtvdnaqrdj.html

el.addEventListener("click", e => {})
来源：http://dali.jyoumei.cn/Article/details/gtbggdyxjn.html

[U100] JS：DOM 查询
来源：http://dali.shzxlz.cn/Article/details/gtflpoexpr.html

document.querySelector(".item")
来源：http://dali.nwbrower.top/Article/details/gtfpjopdul.html

[U101] JS：classList 操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftoabyrv.html

el.classList.toggle("active")
来源：http://dali.xylfe.cn/Article/details/gtkqtmdlud.html

[U102] JS：本地存储
来源：http://dali.316326.xyz/Article/details/gtlkxwohng.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cqqwz.cn/Article/details/gtfbyoluxc.html

[U103] JS：定时器
来源：http://dali.smart0.xyz/Article/details/gtuqfaahyy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxuanxn.top/Article/details/gteazkdtxg.html

[U104] JS：防抖
来源：http://dali.hammf.cn/Article/details/gttxjnvqxk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtxnslobdq.html

[U105] JS：节流
来源：http://dali.smart0.xyz/Article/details/gtoqfrpesk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtsxhcwlhz.html

[U106] JS：日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtdskinovo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fzhhl.top/Article/details/gtmmcsbtzg.html

[U107] JS：数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoaahnaw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cucudq.cn/Article/details/gthjxqxato.html

[U108] JS：随机整数
来源：http://dali.bjfxy.top/Article/details/gtvwomjspy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zdqjudy.top/Article/details/gtqkrfyzud.html

[U109] JS：数组分组
来源：http://dali.yanxiufei.cn/Article/details/gtgtzudxym.html

Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtopvpatno.html

[U110] JS：数组分块
来源：http://dali.jianghu66.top/Article/details/gtppetvnjo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258.top/Article/details/gtyvuvyjew.html

[U111] JS：对象转 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtpxornjml.html

new Map(Object.entries(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeovmfgm.html

[U112] JS：字符串补位
来源：http://dali.cucudq.cn/Article/details/gtsgqcolwl.html

"7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtnfndvdhe.html

[U113] JS：正则替换全部
来源：http://dali.yj20258.top/Article/details/gtgxiecujk.html

s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gttlojavys.html

[U114] JS：JSON 深比较
来源：http://dali.yuanzhike.top/Article/details/gtjvfwhcch.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gtlwkpesop.html

[U115] JS：生成 UUID
来源：http://dali.sweek.top/Article/details/gtreksljnt.html

crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtufxuqjff.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gzhubu.top/Article/details/gtgnmndkye.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hammf.cn/Article/details/gtomckkqln.html

[U117] JS：单元测试
来源：http://dali.tian-w.cn/Article/details/gtlkrtopoy.html

npm i -D vitest;  npx vitest
来源：http://dali.yuxming.cn/Article/details/gtztcsielc.html

[U118] JS：开发服务器
来源：http://dali.wangdashe.top/Article/details/gtvkoujdmn.html

npm i -D vite;  npx vite
来源：http://dali.tanke756.top/Article/details/gtihomibel.html

[U119] JS：生产构建
来源：http://dali.jqgfzy.top/Article/details/gtgxrarxeg.html

npx vite build
来源：http://dali.daxiang520.top/Article/details/gtrvyybojk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pengpengdd.cyou/Article/details/gtgfuvysrl.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258.top/Article/details/gtinpsboca.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqemqfzw.html

统计汇总
来源：http://dali.yj20258.top/Article/details/gtprgvbisz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtygnjbdmr.html

按语言统计（条）：
来源：http://dali.yonumen.top/Article/details/gtyfvlgxqp.html

Python ......... 252
来源：http://dali.sweek.top/Article/details/gtlkfltyxh.html

PHP ............ 252
来源：http://dali.cqqwz.cn/Article/details/gtvrhkiifb.html

JavaScript ..... 252
来源：http://dali.zhiwuduotai.top/Article/details/gtwlebmbte.html

TypeScript ..... 212
来源：http://dali.zdqjudy.top/Article/details/gtfgxlmxmo.html

Java ........... 212
来源：http://dali.c1oappe.top/Article/details/gtzoyajxvz.html

Go ............. 212
来源：http://dali.ybcxt.top/Article/details/gtxwfgzzit.html

Ruby ........... 212
来源：http://dali.mhx1999.top/Article/details/gtsepaqzmd.html

C# ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtgsgxkltg.html

C .............. 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwpcjtzv.html

C++ ............ 30
来源：http://dali.vqdsnc.cn/Article/details/gtehydrcpi.html

SQL ............ 90
来源：http://dali.9152youxi.cn/Article/details/gtjiupcufe.html

Bash ........... 80
来源：http://dali.cheryme.top/Article/details/gtthtebnoq.html

Kotlin ......... 15
来源：http://dali.hnqzz.top/Article/details/gtgggthkpa.html

Swift .......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gteeqbiycn.html

Lua ............ 10
来源：http://dali.shangyingyoupin.top/Article/details/gtjtpxkspf.html

Perl ........... 10
来源：http://dali.hfpthk.cn/Article/details/gtuxtbohns.html

Scala .......... 10
来源：http://dali.andypj.xyz/Article/details/gtqchnbmjr.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtiieisvtn.html

合计 ........... 2106 条
来源：http://dali.hysaishi.cn/Article/details/gtxyquyvmg.html

按章节统计：
来源：http://dali.chenlongwang.top/Article/details/gtoussvept.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zdqjudy.top/Article/details/gtnafuuosa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gtoyardhqy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gttsztymft.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fzhhl.top/Article/details/gtutcawvdo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gtczkvhtho.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gtdjkkhbju.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gtmghoxjve.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gtgjabfzzz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtpluxtnka.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhiwuduotai.top/Article/details/gtgexyexco.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtywdwzmfp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtabqavubj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtjadjsqvn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yvedp.cn/Article/details/gtynwrovyt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yongpay.top/Article/details/gtddhdfmkf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqtxnapl.html

Q SQL 专题                              90
来源：http://dali.andypj.xyz/Article/details/gtrkqlxovx.html

R Bash 专题                             80
来源：http://dali.gotoacloud.top/Article/details/gtdpoqvxho.html

S C / C++ 专题                          60
来源：http://dali.cheryme.top/Article/details/gtaaepvpol.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gtptcsdftd.html

U 高频实用片段                         120
来源：http://dali.chenzaomai.com/Article/details/gtggdwezij.html

------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtsmmkxyok.html

合计                                  2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtmpjsjtpg.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtamovhghq.html

使用提醒
来源：http://dali.smart0.xyz/Article/details/gtlopirdmg.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gthhwhhmlo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.fzhhl.top/Article/details/gtbirwydfv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.iojbl.cn/Article/details/gtmozbmdln.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyxcoygv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sysykeji.top/Article/details/gtrdasujoa.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sufxvd.cn/Article/details/gtcfocuelk.html

—— 文件结束 ——
来源：http://dali.zhengqikj.top/Article/details/gtnrjlswgf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtbjytytmz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.andypj.xyz/Article/details/gtakwjzujx.html

Common Programming Examples Cheat Book
来源：http://dali.0kj1m.cn/Article/details/gtvnhrsxmr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtufqcgpik.html

【收录内容】
来源：http://dali.hysaishi.cn/Article/details/gtwmcfjqmf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yj202588.top/Article/details/gtvjiexang.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfpxqlol.html

SQL · Bash · C · C++
来源：http://dali.jqgufenzy.top/Article/details/gtcpigjkbk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhongyouzk.top/Article/details/gtccqihyme.html

【使用说明】
来源：http://dali.0kj1m.cn/Article/details/gtxzijwuai.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.vqdsnc.cn/Article/details/gtrmzklqqf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.fzhhl.top/Article/details/gteixtsmut.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nanxinkj.top/Article/details/gtnagxxdtg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinqigufen.top/Article/details/gthycpjiln.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hysaishi.cn/Article/details/gthefhqzmw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdzzfsuo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.andypj.xyz/Article/details/gtroeegiuv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hfpthk.cn/Article/details/gtmpowummr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.nanxuanxn.top/Article/details/gtnlgwhiyp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.guowangkeji.top/Article/details/gtzuymxxyc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yongpay.top/Article/details/gtbljzjdtu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fengsongda.top/Article/details/gtjtaqhspg.html

【文件统计】
来源：http://dali.jinqigfzy.top/Article/details/gtplkbqefq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.svipenyu.cn/Article/details/gtjpipewid.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtxqitzgcf.html

目  录
来源：http://dali.havefunace.top/Article/details/gtdbojmumi.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtsinvihdc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hammf.cn/Article/details/gtgpsjesmr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtyfooipug.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gtdjenicnd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jlsjyb.cn/Article/details/gtiojpfcbg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yanxiufei.cn/Article/details/gtqazutwjl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuxming.cn/Article/details/gtnqsktjop.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnskmxyzd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtjgxykzuk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtuuhtmmnd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cdnleiting.top/Article/details/gteleuroqs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtskfrrgdd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtbdqdqvji.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gtaimbfioc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtwnmtktxg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenlongwang.top/Article/details/gtwwnxvfie.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gtqktvvxmi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenzaomai.com/Article/details/gtemboiwnv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtyyxpgpup.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jiagoushi.top/Article/details/gtjqprwqfx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtoibeikel.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gtgvjmixnc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwmbhrbwt.html

A. 基础语法与类型
来源：http://dali.zhongyouzk.top/Article/details/gtnybbmlof.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbnxrsstg.html

[A01] Hello World
来源：http://dali.redwolf501.top/Article/details/gtnrnxqjbo.html

Py:   print("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gtxjuybwlv.html

PHP:  echo "Hello, World!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjsgakjh.html

JS:   console.log("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtupvwqfeh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.quarkkingdee.top/Article/details/gtmgoswifd.html

Java: System.out.println("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gtgnlnivsm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.kuanghao11.cn/Article/details/gtrcscelgv.html

Ruby: puts "Hello, World!"
来源：http://dali.dashuyun.cn/Article/details/gtkbbenasn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.316326.xyz/Article/details/gtlcnkbvap.html

[A02] 变量声明与赋值
来源：http://dali.zycfv.cn/Article/details/gtgvzeneaf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jlsjyb.cn/Article/details/gtfmjddsvx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hammf.cn/Article/details/gttzkqtwbf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.iojbl.cn/Article/details/gtjfjwxzuq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yueranfly.top/Article/details/gtciqmnkqp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtxqvpqskg.html

Go:   name := "Alex"; age := 20
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahplccbu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.daxiang520.top/Article/details/gtbqssitvc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cashguo.top/Article/details/gtfasgyrvl.html

[A03] 常量定义
来源：http://dali.daria6918.cn/Article/details/gtiqkuylrr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xinyue.icu/Article/details/gtyevbpaah.html

PHP:  const PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtkwtonibn.html

JS:   const PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtcbijeoze.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj202588.top/Article/details/gttiwkfniz.html

Java: static final double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtxrujgycb.html

Go:   const PI = 3.14159
来源：http://dali.sysykeji.top/Article/details/gtofcqjzvq.html

Ruby: PI = 3.14159
来源：http://dali.cucudq.cn/Article/details/gtnbxbehzs.html

C#:   const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtgnydbpwc.html

[A04] 判断变量类型
来源：http://dali.ydzc1.top/Article/details/gtzmegmewg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.birdmap.top/Article/details/gtumjwzsow.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.feifeiyinyue.top/Article/details/gthouemssp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.mhx1999.top/Article/details/gtjowcvaco.html

TS:   typeof x; x instanceof Date
来源：http://dali.aibaodan.cn/Article/details/gtymwvpuhk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yueranfly.top/Article/details/gtnbmzotov.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aibaodan.cn/Article/details/gtdfgawqkn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yvedp.cn/Article/details/gtbwmnzxat.html

C#:   x.GetType().Name; x is int
来源：http://dali.dashuyun.cn/Article/details/gttzxsaylg.html

[A05] 整数除法与取模
来源：http://dali.svipenyu.cn/Article/details/gtpzsmatfn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.iojbl.cn/Article/details/gtowustbep.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtvevkonmy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gtubdmwwih.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gthjiuklqw.html

Java: 7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtodsjyott.html

Go:   7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtoqxngojs.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtglimvfth.html

C#:   7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtkbxsjnqy.html

[A06] 字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtkienfnfu.html

Py:   int("42"); float("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtakmcsism.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.316326.xyz/Article/details/gtnksuqplg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sufxvd.cn/Article/details/gtyomiytay.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.aizwys.cn/Article/details/gtssvqsezi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cdnleiting.top/Article/details/gtycbxyprk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yangfankeji.com/Article/details/gtytlmidmc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.guowangkeji.top/Article/details/gtnwhdezbm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtozpypsvo.html

[A07] 数字转字符串
来源：http://dali.jiagoushi.top/Article/details/gtofhwijhu.html

Py:   str(42)
来源：http://dali.jiagoushi.top/Article/details/gtxummqqxa.html

PHP:  (string) 42; strval(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqndudces.html

JS:   String(42); (42).toString()
来源：http://dali.shuidangran.top/Article/details/gtzpfrvsji.html

TS:   String(42)
来源：http://dali.shuidangran.top/Article/details/gtpnrtylyt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dashuyun.cn/Article/details/gtikloztxi.html

Go:   strconv.Itoa(42)
来源：http://dali.nanxinkj.top/Article/details/gtpxluhbyd.html

Ruby: 42.to_s
来源：http://dali.zhixingplan.top/Article/details/gtauarsors.html

C#:   42.ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gtbsiwlaun.html

[A08] 取整与四舍五入
来源：http://dali.ydzc1.top/Article/details/gtoclapgxn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gtvzsfvjbg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.fengsongda.top/Article/details/gtjalxldoi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtnhdbsiet.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsanhwdk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtzxvptdwd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj202588.top/Article/details/gtpzpeyebk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.havefunace.top/Article/details/gtxmabccpb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gtzrazjljq.html

[A09] 绝对值与最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkutlvnxj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtlebckdfx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtyovkevim.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gterbviysn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cheryme.top/Article/details/gttcmonthe.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtssgjlina.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yangfankeji.com/Article/details/gtpnmlxzlw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhongyouzk.top/Article/details/gtvagmrekf.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtbfpbfxtr.html

[A10] 生成随机数
来源：http://dali.ivvv.top/Article/details/gtqlqydijl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sufxvd.cn/Article/details/gtyhzhdtym.html

PHP:  random_int(1, 100);
来源：http://dali.jqgfzy.top/Article/details/gtmaoduhkc.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tian-w.cn/Article/details/gtmokjbpsu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sufxvd.cn/Article/details/gtcqcfqwxu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hnxiangtu.top/Article/details/gtwqdpbrtt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hfpthk.cn/Article/details/gtobyduhjt.html

Ruby: rand(1..100)
来源：http://dali.nanxuanxn.top/Article/details/gtkmdlvcqr.html

C#:   new Random().Next(1, 101)
来源：http://dali.9152youxi.cn/Article/details/gtshdaazpi.html

[A11] 条件表达式（三元）
来源：http://dali.daria6918.cn/Article/details/gtvomdeajs.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tian-w.cn/Article/details/gtehicujsu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gtloptqpob.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gtwusdghwj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtrqvehvze.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gtqarhsggz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhongyouzk.top/Article/details/gtjeyscjql.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gtydyqtrkv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gthgasghir.html

[A12] 字符串插值 / 格式化
来源：http://dali.gaohongyu789.top/Article/details/gtrjlwoqwk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj20258.top/Article/details/gtjubzkxro.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.tian-w.cn/Article/details/gtgrzouxmw.html

JS:   `Hello, ${name}!`
来源：http://dali.havefunace.top/Article/details/gtmwiluzqm.html

TS:   `Hello, ${name}!`
来源：http://dali.daria6918.cn/Article/details/gtsjbbztxl.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jianghu66.top/Article/details/gtnlghdqgu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.mhx1999.top/Article/details/gtvjthsqur.html

Ruby: "Hello, #{name}!"
来源：http://dali.shzxlz.cn/Article/details/gtyfgmkjsz.html

C#:   $"Hello, {name}!"
来源：http://dali.shzxlz.cn/Article/details/gtzrpyibjf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yanxiufei.cn/Article/details/gthzfmwpto.html

Py:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtaahhnsxi.html

PHP:  "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtzphgjmrh.html

JS:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtbivhvdtz.html

TS:   "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtlqzoavfr.html

Java: "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcpkqlts.html

Go:   "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gtkgzgaydf.html

Ruby: "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtknhuoztm.html

C#:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtmlcggllb.html

[A14] 注释写法
来源：http://dali.cucudq.cn/Article/details/gtqbbzxeaf.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.nanxinkj.top/Article/details/gtewfwjtxc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gtydeorbgv.html

JS:   // 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdxocnjq.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gtqjgqbbtz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shuidangran.top/Article/details/gttjekfbsy.html

Go:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gtbdivamyv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yanxiufei.cn/Article/details/gtgitzoice.html


<!-- 参考信息 -->