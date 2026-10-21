代发 wailian999

[U93] JS：模板字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtxenuvdji.html

`共 ${n} 条`
来源：http://dali.yuanzhike.top/Article/details/gtdsbgnadk.html

[U94] JS：箭头函数
来源：http://dali.cucudq.cn/Article/details/gteamaqzrb.html

const double = x => x * 2;
来源：http://dali.yanxiufei.cn/Article/details/gtcenjjtst.html

[U95] JS：Promise 包装
来源：http://dali.xylfe.cn/Article/details/gtdmdrufgc.html

new Promise((resolve, reject) => {})
来源：http://dali.sufxvd.cn/Article/details/gtggmupfii.html

[U96] JS：async/await 与异常
来源：http://dali.yuxming.cn/Article/details/gtmideodrq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtmieqksbp.html

[U97] JS：并发请求
来源：http://dali.yj20258.top/Article/details/gtyrltauqs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtzloqkuwh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zdqjudy.top/Article/details/gtrhxmjqaj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nanxinkj.top/Article/details/gtbwacngkr.html

[U99] JS：事件监听
来源：http://dali.yvedp.cn/Article/details/gtwlausoxw.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258888.top/Article/details/gtxrbpbhtv.html

[U100] JS：DOM 查询
来源：http://dali.sysykeji.top/Article/details/gtugkziave.html

document.querySelector(".item")
来源：http://dali.yj20258.top/Article/details/gtqjhanlxw.html

[U101] JS：classList 操作
来源：http://dali.snrcjt.cn/Article/details/gtaiejuder.html

el.classList.toggle("active")
来源：http://dali.sufxvd.cn/Article/details/gtqaugpjna.html

[U102] JS：本地存储
来源：http://dali.quarkkingdee.top/Article/details/gtlyyzjkdk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sufxvd.cn/Article/details/gtgzvanwcf.html

[U103] JS：定时器
来源：http://dali.fzhhl.top/Article/details/gtegrcbvwj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gtwbqjiacf.html

[U104] JS：防抖
来源：http://dali.pengpengdd.cyou/Article/details/gtwtyvuwsm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtwdzrolwx.html

[U105] JS：节流
来源：http://dali.jinqigfzy.top/Article/details/gtaackhhsh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.c1oappe.top/Article/details/gtgyoymyan.html

[U106] JS：日期格式化
来源：http://dali.andypj.xyz/Article/details/gtolseygnw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.havefunace.top/Article/details/gtmbmphvco.html

[U107] JS：数字千分位
来源：http://dali.yuxming.cn/Article/details/gtfsgmjade.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtfcbbgoex.html

[U108] JS：随机整数
来源：http://dali.jinqigfzy.top/Article/details/gtiafjwzpp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj20258888.top/Article/details/gtmtnylpop.html

[U109] JS：数组分组
来源：http://dali.jqgfzy.top/Article/details/gthznqfsjr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gthichmhbo.html

[U110] JS：数组分块
来源：http://dali.shzxlz.cn/Article/details/gtdcfulwie.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjisjxwl.html

[U111] JS：对象转 Map
来源：http://dali.wangshuangyany.cn/Article/details/gttsicqfug.html

new Map(Object.entries(obj))
来源：http://dali.9152youxi.cn/Article/details/gtvuyaiyan.html

[U112] JS：字符串补位
来源：http://dali.jinghuilouyu.cn/Article/details/gtaibxbkmu.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtseputbbc.html

[U113] JS：正则替换全部
来源：http://dali.yuanzhike.top/Article/details/gtvkdemtng.html

s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtvpykrytr.html

[U114] JS：JSON 深比较
来源：http://dali.daxiang520.top/Article/details/gtoxypkdtd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gtbaesujba.html

[U115] JS：生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtfdironkh.html

crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtzvfxgujv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nanxinkj.top/Article/details/gthnjnviqm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hysaishi.cn/Article/details/gteozwfixx.html

[U117] JS：单元测试
来源：http://dali.nanxinkj.top/Article/details/gthgdwcyxh.html

npm i -D vitest;  npx vitest
来源：http://dali.hywenlv.cn/Article/details/gtnbvaresi.html

[U118] JS：开发服务器
来源：http://dali.cheryme.top/Article/details/gtsjeuggul.html

npm i -D vite;  npx vite
来源：http://dali.jqgufenzy.top/Article/details/gtqveesaew.html

[U119] JS：生产构建
来源：http://dali.chenzaomai.com/Article/details/gtfwmawsmw.html

npx vite build
来源：http://dali.pengpengdd.cyou/Article/details/gtoxrqyzna.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.9152youxi.cn/Article/details/gthhtvlnzm.html

import.meta.env.VITE_API_URL
来源：http://dali.wangdashe.top/Article/details/gtfajkffmv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtpflpiiyg.html

统计汇总
来源：http://dali.9152youxi.cn/Article/details/gtrabfxoxj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtaqjwhfpc.html

按语言统计（条）：
来源：http://dali.9152youxi.cn/Article/details/gteoonoxlv.html

Python ......... 252
来源：http://dali.quarkkingdee.top/Article/details/gtdcbomypq.html

PHP ............ 252
来源：http://dali.jinghuilouyu.cn/Article/details/gtokmnylzm.html

JavaScript ..... 252
来源：http://dali.chenzaomai.com/Article/details/gtuzuibjof.html

TypeScript ..... 212
来源：http://dali.zycfv.cn/Article/details/gtfwwyzpcv.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gtxabonrad.html

Go ............. 212
来源：http://dali.xinyue.icu/Article/details/gtipdxtvev.html

Ruby ........... 212
来源：http://dali.redwolf501.top/Article/details/gtvuduzqse.html

C# ............. 212
来源：http://dali.andypj.xyz/Article/details/gttypcscqu.html

C .............. 30
来源：http://dali.fzhhl.top/Article/details/gtfytoqahs.html

C++ ............ 30
来源：http://dali.sxryk.cn/Article/details/gtxtbeiqsq.html

SQL ............ 90
来源：http://dali.0kj1m.cn/Article/details/gtyzzctjzy.html

Bash ........... 80
来源：http://dali.jinqigfzy.top/Article/details/gtcdpcjcry.html

Kotlin ......... 15
来源：http://dali.jqgfzy.top/Article/details/gtruncqkvp.html

Swift .......... 15
来源：http://dali.xinyue.icu/Article/details/gtjiarfier.html

Lua ............ 10
来源：http://dali.sweek.top/Article/details/gtrqbckbnx.html

Perl ........... 10
来源：http://dali.nanxinkj.top/Article/details/gthputybai.html

Scala .......... 10
来源：http://dali.zhengqikj.top/Article/details/gtbkdkzzxj.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtvokgfafs.html

合计 ........... 2106 条
来源：http://dali.birdmap.top/Article/details/gtzahcubme.html

按章节统计：
来源：http://dali.pycfn.com/Article/details/gtmlyscuur.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangtech.top/Article/details/gteuenexuk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtlkjvonmc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtxfxlddjc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gtowupxylv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ydzc1.top/Article/details/gtnktpgcyv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gttwupawpe.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtbzcdmzrv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinyuanbaomall.cn/Article/details/gttivjxegr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtvcpazlbr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gtkudpalft.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtcuaolitz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtnlxqbenk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtnsuuihlw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gttgdmmrhj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangtech.top/Article/details/gtaonrctqm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtchyceqgk.html

Q SQL 专题                              90
来源：http://dali.chenzaomai.com/Article/details/gthykqrsvf.html

R Bash 专题                             80
来源：http://dali.hnqzz.top/Article/details/gtrtjldfns.html

S C / C++ 专题                          60
来源：http://dali.yuanzhike.top/Article/details/gtgbyebdec.html

T 其他语言补充                          60
来源：http://dali.jianghu66.top/Article/details/gtozwzbkpy.html

U 高频实用片段                         120
来源：http://dali.yangfankeji.com/Article/details/gtkhvmwmza.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtlgkthtmd.html

合计                                  2106 条
来源：http://dali.chenjidiqi.icu/Article/details/gthvuddjob.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtnrkjxetg.html

使用提醒
来源：http://dali.sufxvd.cn/Article/details/gtowdelhuo.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtauvfwhbm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhixingplan.top/Article/details/gtaoywzzvt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhixingplan.top/Article/details/gtxqsrukrh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gaohongyu789.top/Article/details/gtipajrymp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgfzy.top/Article/details/gtpzhhcqcl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tanke756.top/Article/details/gtdjigcrcl.html

—— 文件结束 ——
来源：http://dali.sufxvd.cn/Article/details/gtwfcwbtlt.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtosmvallv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.guannengcc.top/Article/details/gtoxlgdskt.html

Common Programming Examples Cheat Book
来源：http://dali.sysykeji.top/Article/details/gtaopdlecy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnynnfqky.html

【收录内容】
来源：http://dali.xylfe.cn/Article/details/gtvcfuxxbl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gzhubu.top/Article/details/gtlgylawfd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jyoumei.cn/Article/details/gtkefntenc.html

SQL · Bash · C · C++
来源：http://dali.yongpay.top/Article/details/gtadrkoktn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhxihmkx.html

【使用说明】
来源：http://dali.jinghuilouyu.cn/Article/details/gtltvwqzgx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.smart0.xyz/Article/details/gthupyoliq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhoulong.xyz/Article/details/gtjxfuyysp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sysykeji.top/Article/details/gtwicpvexq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gogol.net.cn/Article/details/gtkwyypmuh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.haohaochexian.top/Article/details/gthgufxlpm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.feifeiyinyue.top/Article/details/gtlrexugso.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yongpay.top/Article/details/gtbpwubbfa.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hywenlv.cn/Article/details/gtqecjhyac.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.iojbl.cn/Article/details/gtuxjxeibz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hongshengwenyu.top/Article/details/gtcjfhtsfu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxkorblf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinqigufen.top/Article/details/gtxvfzgyvc.html

【文件统计】
来源：http://dali.gogol.net.cn/Article/details/gtioepneqk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.daxiang520.top/Article/details/gtulictqvw.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtgahjzurq.html

目  录
来源：http://dali.sxryk.cn/Article/details/gtereweipa.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtmpcrtdgv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gtfpjifyrq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsaqtytqv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gtjslpammw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gtpxkevoax.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jianghu66.top/Article/details/gtgylyavdd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gtyxzesiti.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gtlhophnav.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hfpthk.cn/Article/details/gtwruccoft.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtllvraxkm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gtvfvvqmon.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjrqssqe.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtxvmomfqh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdhxtebe.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sysykeji.top/Article/details/gtjrlrlsgq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnifnpjnh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gthbmaslak.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenzaomai.com/Article/details/gtgzcjgzoc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pycfn.com/Article/details/gtsonksdhk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtnrinhc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gtivisklyl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjxsgkyc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtexszirqm.html

A. 基础语法与类型
来源：http://dali.daxiang520.top/Article/details/gtceojltru.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjameuagb.html

[A01] Hello World
来源：http://dali.ivvv.top/Article/details/gteuczyvan.html

Py:   print("Hello, World!")
来源：http://dali.tianlin.xyz/Article/details/gthnibvgnv.html

PHP:  echo "Hello, World!";
来源：http://dali.ppjwa.cn/Article/details/gtwrywanco.html

JS:   console.log("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gtlnjvqund.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cheryme.top/Article/details/gtqoldkfxe.html

Java: System.out.println("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gtyprwuxqu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.pengpengdd.cyou/Article/details/gtluiznmea.html

Ruby: puts "Hello, World!"
来源：http://dali.gzhubu.top/Article/details/gttrxjvzgd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yonumen.top/Article/details/gtrsvqfysa.html

[A02] 变量声明与赋值
来源：http://dali.aizwys.cn/Article/details/gtqyiwxrbo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj20258.top/Article/details/gtmlapnzls.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.mhx1999.top/Article/details/gtczcrjojf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtnoeqmvsw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yangfankeji.com/Article/details/gtgoxumeym.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gtdxkthvbr.html

Go:   name := "Alex"; age := 20
来源：http://dali.yanxiufei.cn/Article/details/gtbjdsjllq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shuidangran.top/Article/details/gtpwviujye.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtdtfryjub.html

[A03] 常量定义
来源：http://dali.ivvv.top/Article/details/gtwwtmtpjf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yueranfly.top/Article/details/gtxuhbyexl.html

PHP:  const PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtxbjjdgnu.html

JS:   const PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtaxcnrfow.html

TS:   const PI: number = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtweekcqzl.html

Java: static final double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtznvglqru.html

Go:   const PI = 3.14159
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglczfasf.html

Ruby: PI = 3.14159
来源：http://dali.fzhhl.top/Article/details/gtgvnsdngk.html

C#:   const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtojbhufuv.html

[A04] 判断变量类型
来源：http://dali.ppjwa.cn/Article/details/gtxnfspdpc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.nanxuanxn.top/Article/details/gtxfnjgziw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hammf.cn/Article/details/gtxrvthvxz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuanzhike.top/Article/details/gtognhvefa.html

TS:   typeof x; x instanceof Date
来源：http://dali.sweek.top/Article/details/gtrrzkkzyr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.vqdsnc.cn/Article/details/gtifmetnwq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sufxvd.cn/Article/details/gtntszeaoa.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ppjwa.cn/Article/details/gtiflnrbud.html

C#:   x.GetType().Name; x is int
来源：http://dali.hammf.cn/Article/details/gttockflod.html

[A05] 整数除法与取模
来源：http://dali.pycfn.com/Article/details/gtdjczxnjt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dashuyun.cn/Article/details/gtuiuecpbu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtzxavpelx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtscnjklyv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtccqwvggv.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtldqpijdo.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtyxbhuspy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtoszngrci.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtdzkjwhqq.html

[A06] 字符串转数字
来源：http://dali.yj20258.top/Article/details/gtlqgmiioq.html

Py:   int("42"); float("3.14")
来源：http://dali.havefunace.top/Article/details/gtuxotcdtr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ehwqpu.com/Article/details/gthxvzsmpl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hysaishi.cn/Article/details/gtmtiwrvvz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yuxming.cn/Article/details/gtirujwuli.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtayahbgex.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sysykeji.top/Article/details/gtqegxdbmj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jiagoushi.top/Article/details/gtoadwpvcs.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ybcxt.top/Article/details/gtltdgxzkr.html

[A07] 数字转字符串
来源：http://dali.haohaochexian.top/Article/details/gtzgxvatai.html

Py:   str(42)
来源：http://dali.ehwqpu.com/Article/details/gthgaeqrhv.html

PHP:  (string) 42; strval(42)
来源：http://dali.c1oappe.top/Article/details/gtelleokxf.html

JS:   String(42); (42).toString()
来源：http://dali.hammf.cn/Article/details/gtgrzllbyp.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gtctwbvvws.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jiagoushi.top/Article/details/gtqnavpbbp.html

Go:   strconv.Itoa(42)
来源：http://dali.cashguo.top/Article/details/gtxvfczisz.html

Ruby: 42.to_s
来源：http://dali.wangdashe.top/Article/details/gtagvxhikh.html

C#:   42.ToString()
来源：http://dali.yj202588.top/Article/details/gtqqevmsyn.html

[A08] 取整与四舍五入
来源：http://dali.aizwys.cn/Article/details/gtrgodgvat.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gtgdsmkivy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gzhubu.top/Article/details/gtzbkylfel.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtnhtjjkcs.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jiagoushi.top/Article/details/gtsexbtpaf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtoeqrdkra.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gteypktqyl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yuanzhike.top/Article/details/gthgcypoif.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtsqywqqol.html

[A09] 绝对值与最大最小值
来源：http://dali.daxiang520.top/Article/details/gtbtaptbho.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yongpay.top/Article/details/gtdnashhjd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtcfwwwqhc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gthngehckm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtfeeskfti.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtvemvghla.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yuanzhike.top/Article/details/gtlupgxnmi.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sufxvd.cn/Article/details/gtcwmswyww.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.birdmap.top/Article/details/gtiowqlfmu.html

[A10] 生成随机数
来源：http://dali.mhx1999.top/Article/details/gtvpxblsts.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaryboapx.html

PHP:  random_int(1, 100);
来源：http://dali.nanxinkj.top/Article/details/gtgciqllpi.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.daxiang520.top/Article/details/gtdwvgbiur.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.snrcjt.cn/Article/details/gtqqqmlzal.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guowangkeji.top/Article/details/gtmlycmqhm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.iojbl.cn/Article/details/gtvdcclhua.html

Ruby: rand(1..100)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngmslpas.html

C#:   new Random().Next(1, 101)
来源：http://dali.havefunace.top/Article/details/gtuvwjqepr.html

[A11] 条件表达式（三元）
来源：http://dali.gzhubu.top/Article/details/gtljysgvcz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yangfankeji.com/Article/details/gtcxoegeab.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gtpbsewops.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtqgnafsjz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gtzvxgqcvv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtqbaldpcu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jqgfzy.top/Article/details/gtwvohwttt.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkglqytwg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gtqtzfiwsh.html

[A12] 字符串插值 / 格式化
来源：http://dali.dianchejie.cn/Article/details/gtmpstbbeb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shangyingyoupin.top/Article/details/gtcofoohjz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.guannengcc.top/Article/details/gtsbceflsj.html

JS:   `Hello, ${name}!`
来源：http://dali.birdmap.top/Article/details/gtqtxzyjtv.html

TS:   `Hello, ${name}!`
来源：http://dali.zhixingplan.top/Article/details/gthjddregy.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.iojbl.cn/Article/details/gtkbieeztz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ivvv.top/Article/details/gtnnuyfzic.html

Ruby: "Hello, #{name}!"
来源：http://dali.xinyue.icu/Article/details/gtbzeepnkt.html

C#:   $"Hello, {name}!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopufewec.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nwbrower.top/Article/details/gttpaaiebh.html

Py:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gthxpckdrb.html

PHP:  "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtdxlprtmk.html

JS:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtjmovnaoj.html

TS:   "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtivuqiuhw.html

Java: "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtqbexysqz.html

Go:   "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gttizxmolx.html

Ruby: "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtnjdkarfz.html

C#:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtsysunmji.html

[A14] 注释写法
来源：http://dali.zdqjudy.top/Article/details/gtzfnxuetv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.nwbrower.top/Article/details/gtfnvmkuhe.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadysmref.html

JS:   // 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjxzvhyz.html

TS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtgxtpphlv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hammf.cn/Article/details/gtopomshzm.html

Go:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtdjlxahff.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zycfv.cn/Article/details/gtqrrfdaxn.html

C#:   // 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtkfyrglpk.html

[A15] 空值判断与默认值
来源：http://dali.yj20258.top/Article/details/gtltardtpn.html

Py:   value = data or "默认值"
来源：http://dali.sxryk.cn/Article/details/gtlkhgrzie.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ehwqpu.com/Article/details/gtaxugcgut.html

JS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtjtjxqimv.html

TS:   const value = data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gtrxlpsyoo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.andypj.xyz/Article/details/gtgczynjeh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gaohongyu789.top/Article/details/gtubefargg.html

Ruby: value = data || "默认值"
来源：http://dali.yuxming.cn/Article/details/gtawrjphcr.html

C#:   var value = data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gtimgbwlmc.html

[A16] 真假值判断规则
来源：http://dali.xuanzx.com/Article/details/gtqnwysgqb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.tianlin.xyz/Article/details/gtbpyydeqc.html


<!-- 参考信息 -->