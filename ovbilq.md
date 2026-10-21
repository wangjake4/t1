代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.gotoacloud.top/Article/details/gtiwlcltkp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ivvv.top/Article/details/gtitxenisg.html

[U92] JS：深拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtykaxlmzs.html

structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtfbczyvdx.html

[U93] JS：模板字符串
来源：http://dali.andypj.xyz/Article/details/gthjsnpmnz.html

`共 ${n} 条`
来源：http://dali.daxiang520.top/Article/details/gtpzrifknk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gtonsoobaa.html

const double = x => x * 2;
来源：http://dali.gzhubu.top/Article/details/gtrtglbplz.html

[U95] JS：Promise 包装
来源：http://dali.feifeiyinyue.top/Article/details/gtwqkezkhj.html

new Promise((resolve, reject) => {})
来源：http://dali.yonumen.top/Article/details/gtyzjpwnnp.html

[U96] JS：async/await 与异常
来源：http://dali.zhixingplan.top/Article/details/gtxvwhxazn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkwjltklm.html

[U97] JS：并发请求
来源：http://dali.pycfn.com/Article/details/gtwbfqxrny.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpmbktod.html

[U98] JS：fetch 带 JSON
来源：http://dali.kuanghao11.cn/Article/details/gtehkcmlsp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shangyingyoupin.top/Article/details/gtfhmxbybx.html

[U99] JS：事件监听
来源：http://dali.jqgufenzy.top/Article/details/gtocbvirql.html

el.addEventListener("click", e => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqomyjeff.html

[U100] JS：DOM 查询
来源：http://dali.316326.xyz/Article/details/gtfcwxtwsm.html

document.querySelector(".item")
来源：http://dali.svipenyu.cn/Article/details/gtifkvmoup.html

[U101] JS：classList 操作
来源：http://dali.jqgufenzy.top/Article/details/gtpsjignex.html

el.classList.toggle("active")
来源：http://dali.hysaishi.cn/Article/details/gtcjcopzws.html

[U102] JS：本地存储
来源：http://dali.gzhubu.top/Article/details/gtoracrkud.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gtrbudqguf.html

[U103] JS：定时器
来源：http://dali.yj20258.top/Article/details/gtxbhnagbx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.redwolf501.top/Article/details/gtivpstqfu.html

[U104] JS：防抖
来源：http://dali.tianlin.xyz/Article/details/gtwapokcnq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtenxnmhfo.html

[U105] JS：节流
来源：http://dali.shzxlz.cn/Article/details/gtyloaxmun.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.guannengcc.top/Article/details/gthjakrhrp.html

[U106] JS：日期格式化
来源：http://dali.birdmap.top/Article/details/gteleunbgn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.daxiang520.top/Article/details/gtayphawly.html

[U107] JS：数字千分位
来源：http://dali.bjfxy.top/Article/details/gtwumsjhdd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtuzfngjcc.html

[U108] JS：随机整数
来源：http://dali.svipenyu.cn/Article/details/gtviatodge.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jiagoushi.top/Article/details/gttcgvotir.html

[U109] JS：数组分组
来源：http://dali.daxiang520.top/Article/details/gtlacqppwh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtosbfswmy.html

[U110] JS：数组分块
来源：http://dali.zhoulong.xyz/Article/details/gttuumlbnn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenzaomai.com/Article/details/gtqfeqxyev.html

[U111] JS：对象转 Map
来源：http://dali.zhengqikj.top/Article/details/gtatwiejgv.html

new Map(Object.entries(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtvihxgghf.html

[U112] JS：字符串补位
来源：http://dali.9152youxi.cn/Article/details/gtxwilxkfq.html

"7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtmmfmbdlm.html

[U113] JS：正则替换全部
来源：http://dali.gaohongyu789.top/Article/details/gtwwmfgmch.html

s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtkkdocjra.html

[U114] JS：JSON 深比较
来源：http://dali.hywenlv.cn/Article/details/gtekqynjfy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gtufovodmf.html

[U115] JS：生成 UUID
来源：http://dali.tanke756.top/Article/details/gtiuzqhptq.html

crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtgekyvdsh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jyoumei.cn/Article/details/gtbfcotzkt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gogol.net.cn/Article/details/gtnxzttbpj.html

[U117] JS：单元测试
来源：http://dali.redwolf501.top/Article/details/gtllhirkgt.html

npm i -D vitest;  npx vitest
来源：http://dali.jianghu66.top/Article/details/gtppnxusos.html

[U118] JS：开发服务器
来源：http://dali.snrcjt.cn/Article/details/gtbklgmmbe.html

npm i -D vite;  npx vite
来源：http://dali.tianlin.xyz/Article/details/gtzsptjwaq.html

[U119] JS：生产构建
来源：http://dali.ehwqpu.com/Article/details/gtrgdescyr.html

npx vite build
来源：http://dali.wangdashe.top/Article/details/gthlcojgpd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sxryk.cn/Article/details/gtoldlelss.html

import.meta.env.VITE_API_URL
来源：http://dali.c1oappe.top/Article/details/gtcqfueikz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnhiqrgmn.html

统计汇总
来源：http://dali.jinqigfzy.top/Article/details/gtyggwyvfq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtcwbumzkb.html

按语言统计（条）：
来源：http://dali.zhongyouzk.top/Article/details/gtjvndiodb.html

Python ......... 252
来源：http://dali.316326.xyz/Article/details/gttkjqemra.html

PHP ............ 252
来源：http://dali.gzhubu.top/Article/details/gtsiokyzje.html

JavaScript ..... 252
来源：http://dali.jyoumei.cn/Article/details/gtjkopsnvr.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtxnrjlr.html

Java ........... 212
来源：http://dali.aibaodan.cn/Article/details/gtaovzzotm.html

Go ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gttsqrngei.html

Ruby ........... 212
来源：http://dali.yueranfly.top/Article/details/gttslipbap.html

C# ............. 212
来源：http://dali.xinyue.icu/Article/details/gtutexxnov.html

C .............. 30
来源：http://dali.shangyingyoupin.top/Article/details/gtwwyhvizq.html

C++ ............ 30
来源：http://dali.wangshuangyany.cn/Article/details/gtjkarnvvb.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gtwzjxlkrb.html

Bash ........... 80
来源：http://dali.yangfankeji.com/Article/details/gtpgiqfdny.html

Kotlin ......... 15
来源：http://dali.chenzaomai.com/Article/details/gtvokxgesp.html

Swift .......... 15
来源：http://dali.xinyue.icu/Article/details/gtcdxypxba.html

Lua ............ 10
来源：http://dali.nwbrower.top/Article/details/gtajoczrzt.html

Perl ........... 10
来源：http://dali.cheryme.top/Article/details/gtvvvtpgoh.html

Scala .......... 10
来源：http://dali.dianchejie.cn/Article/details/gtrkpwsjxc.html

------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhrrvyiw.html

合计 ........... 2106 条
来源：http://dali.yj20258.top/Article/details/gtktycufxg.html

按章节统计：
来源：http://dali.fengsongda.top/Article/details/gtjwffrclr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gotoacloud.top/Article/details/gtwraieuqh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gtufpeyuub.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gtyhyahzfz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gthhirzgoo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daxiang520.top/Article/details/gttvvugocm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gttwcsuyea.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtbkbpzgab.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gtotlhyrgf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gttrsacfxu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gtcpqprfhv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtcxfytoxn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdotfnsqq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtqqkmvvpg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.bjfxy.top/Article/details/gtuqmffpof.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hnxiangtu.top/Article/details/gtnubanxvx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtjgitmfto.html

Q SQL 专题                              90
来源：http://dali.ydzc1.top/Article/details/gtqsbyeqyq.html

R Bash 专题                             80
来源：http://dali.shangyingyoupin.top/Article/details/gtzjjczfsr.html

S C / C++ 专题                          60
来源：http://dali.yj202588.top/Article/details/gtfagmdtxg.html

T 其他语言补充                          60
来源：http://dali.jqgufenzy.top/Article/details/gtbvfojjrj.html

U 高频实用片段                         120
来源：http://dali.yuanzhike.top/Article/details/gtuviqbgyv.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gtbdtrfsvu.html

合计                                  2106 条
来源：http://dali.ppjwa.cn/Article/details/gtrexvhkaa.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtmjvxmcrb.html

使用提醒
来源：http://dali.fzhhl.top/Article/details/gtcwrhtufo.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtemngulxg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gaohongyu789.top/Article/details/gtphzpxesp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yuanzhike.top/Article/details/gtgbpvltyl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjroapgmj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenlongwang.top/Article/details/gtplxdqagn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hywenlv.cn/Article/details/gtqegrnndi.html

—— 文件结束 ——
来源：http://dali.zycfv.cn/Article/details/gtzubsitpc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijevyyze.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.redwolf501.top/Article/details/gtlzgzfdod.html

Common Programming Examples Cheat Book
来源：http://dali.yongpay.top/Article/details/gtxrsabjqn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjnkslxju.html

【收录内容】
来源：http://dali.gotoacloud.top/Article/details/gttpxvylxf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.0kj1m.cn/Article/details/gttkzwdvkf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cdnleiting.top/Article/details/gtxqubrbrt.html

SQL · Bash · C · C++
来源：http://dali.haohaochexian.top/Article/details/gtttmbzbjq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhixingplan.top/Article/details/gtkvfpkwmi.html

【使用说明】
来源：http://dali.hammf.cn/Article/details/gtyjfawiol.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ybcxt.top/Article/details/gtdxgebryc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ydzc1.top/Article/details/gtvwfjzxlz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.c1oappe.top/Article/details/gtalqbgrhf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.wangshuangyany.cn/Article/details/gtfyssfpxh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkusidrw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jyoumei.cn/Article/details/gtwnwiacqb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nwbrower.top/Article/details/gtvbtbhqgx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.svipenyu.cn/Article/details/gtqmwreare.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sysykeji.top/Article/details/gthpodefvm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ehwqpu.com/Article/details/gtsgeofmpi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yvedp.cn/Article/details/gtykbtlcys.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.smart0.xyz/Article/details/gtckkvfvwh.html

【文件统计】
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwswydsyg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guannengcc.top/Article/details/gthbjbxovb.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtprllnduh.html

目  录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnmptfca.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtejhlyblu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.c1oappe.top/Article/details/gtvfcaiuiw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tianlin.xyz/Article/details/gtbqekgdfi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmahytxhs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gtnjevwocv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhongyouzk.top/Article/details/gtvubvqmou.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gtedxcgfkd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gtsechwsaa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.mhx1999.top/Article/details/gtzljtknbe.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtzqdskvvo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkbdstaa.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtkwoosyac.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gtonkbdgmf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtdxlyoztd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcvlwtff.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cucudq.cn/Article/details/gttgwgrgvm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtcpuvyaqe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hnxiangtu.top/Article/details/gtsxvqqvmp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fengsongda.top/Article/details/gtupgoupcp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ybcxt.top/Article/details/gtyiqxsvbv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gtnrhpbkvr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gtkbxilpnp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtaepzmngq.html

A. 基础语法与类型
来源：http://dali.cheryme.top/Article/details/gtewnpccpd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtoqzpydne.html

[A01] Hello World
来源：http://dali.nanxinkj.top/Article/details/gteifacoob.html

Py:   print("Hello, World!")
来源：http://dali.haohaochexian.top/Article/details/gtqzmpxoye.html

PHP:  echo "Hello, World!";
来源：http://dali.wangdashe.top/Article/details/gtwvyydpma.html

JS:   console.log("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gtpikbzokp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhixingplan.top/Article/details/gtwomoozhn.html

Java: System.out.println("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtcnixvebh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gtmfhjupwp.html

Ruby: puts "Hello, World!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjusqohjt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gtizdtwpwt.html

[A02] 变量声明与赋值
来源：http://dali.tianlin.xyz/Article/details/gthkqdyiyg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuetiantiany.cn/Article/details/gtccjczggj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hywenlv.cn/Article/details/gthfzteepl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xuanzx.com/Article/details/gtetojoryh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.aibaodan.cn/Article/details/gtdcxgqhgb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtlzwvzqpy.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenzaomai.com/Article/details/gtxsnvcgzs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenjidiqi.icu/Article/details/gteskuswgj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.meibo888.top/Article/details/gtluacqbhn.html

[A03] 常量定义
来源：http://dali.smart0.xyz/Article/details/gtqzuezeoy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yj20258888.top/Article/details/gtbeoulsrl.html

PHP:  const PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtvypwtcrj.html

JS:   const PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtmwegllxt.html

TS:   const PI: number = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtzphfzfsg.html

Java: static final double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtsbpmfnpw.html

Go:   const PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gtyupbrcrk.html

Ruby: PI = 3.14159
来源：http://dali.cucudq.cn/Article/details/gtjjukkfqc.html

C#:   const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtbowbuvhb.html

[A04] 判断变量类型
来源：http://dali.zycfv.cn/Article/details/gtlrcfplqt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xziqi.cn/Article/details/gtsjtkrlls.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gaohongyu789.top/Article/details/gtejblfrwc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gtdlosmfme.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxuanxn.top/Article/details/gtibavuoas.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shuidangran.top/Article/details/gtczcnywub.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ydzc1.top/Article/details/gtglfcyoeo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yvedp.cn/Article/details/gtuuiemuaf.html

C#:   x.GetType().Name; x is int
来源：http://dali.hysaishi.cn/Article/details/gtnpgtiqes.html

[A05] 整数除法与取模
来源：http://dali.ppjwa.cn/Article/details/gtfakqyudk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.haohaochexian.top/Article/details/gtcygnwwyb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtuuiikrfy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gtrgqgzdtf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtsmcjxrcx.html

Java: 7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtutyghvuq.html

Go:   7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtnzjsithx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gtzmzvlfbl.html

C#:   7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtawiaikki.html

[A06] 字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtmtwtvvsm.html

Py:   int("42"); float("3.14")
来源：http://dali.shzxlz.cn/Article/details/gtiuzpxunh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhiwuduotai.top/Article/details/gtzqqahnsk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhoulong.xyz/Article/details/gtxuitjubh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gtwchzajav.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtxlgmvhux.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shuidangran.top/Article/details/gteckoguhi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sufxvd.cn/Article/details/gtpdooijwv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yanxiufei.cn/Article/details/gtflziygjt.html

[A07] 数字转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtgshuqjtr.html

Py:   str(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrfbkcjd.html

PHP:  (string) 42; strval(42)
来源：http://dali.dianchejie.cn/Article/details/gtiieucdim.html

JS:   String(42); (42).toString()
来源：http://dali.xylfe.cn/Article/details/gtedjlmnqc.html

TS:   String(42)
来源：http://dali.zhixingplan.top/Article/details/gtgblymnlw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gaohongyu789.top/Article/details/gtjipxqnlp.html

Go:   strconv.Itoa(42)
来源：http://dali.fzhhl.top/Article/details/gtvkrcqyqf.html

Ruby: 42.to_s
来源：http://dali.zhixingplan.top/Article/details/gtkngguxum.html

C#:   42.ToString()
来源：http://dali.sxryk.cn/Article/details/gtuclmskoh.html

[A08] 取整与四舍五入
来源：http://dali.fzhhl.top/Article/details/gtfszqqslc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gturhiwecm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cashguo.top/Article/details/gtaomlouuf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtnwpnukjh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jiagoushi.top/Article/details/gthwkjilkq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yangfankeji.com/Article/details/gtelxcxebi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtuhthdwar.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xuetiantiany.cn/Article/details/gtvgnadgvx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtohzceshh.html

[A09] 绝对值与最大最小值
来源：http://dali.yj20258.top/Article/details/gtknosgjci.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtbnickkha.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtrijswlra.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtjwrbnntk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtdvrjyhpl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqbawsnu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gogol.net.cn/Article/details/gtwgpopelq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhixingplan.top/Article/details/gtqgyjxazx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.tian-w.cn/Article/details/gttjfnzfpe.html

[A10] 生成随机数
来源：http://dali.cdnleiting.top/Article/details/gtrofmoqmw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.316326.xyz/Article/details/gtrchqcxtd.html

PHP:  random_int(1, 100);
来源：http://dali.birdmap.top/Article/details/gtirfcdhoz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxuanxn.top/Article/details/gtassggoot.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.birdmap.top/Article/details/gtyrzluodm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cheryme.top/Article/details/gtyfmrcdmx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.guannengcc.top/Article/details/gtlrwsgusj.html

Ruby: rand(1..100)
来源：http://dali.zhengqikj.top/Article/details/gtendynalc.html

C#:   new Random().Next(1, 101)
来源：http://dali.gotoacloud.top/Article/details/gtcbpecrch.html

[A11] 条件表达式（三元）
来源：http://dali.zdqjudy.top/Article/details/gtewkuvcpj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.redwolf501.top/Article/details/gtywbkzsou.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtokyejwrv.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gtseferouw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiizwieh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gtlgwxbdnh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.snrcjt.cn/Article/details/gtfwtvynmk.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtioxjchup.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtmtcrcwpi.html

[A12] 字符串插值 / 格式化
来源：http://dali.jqgfzy.top/Article/details/gtczjqpgzy.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yuanzhike.top/Article/details/gtjxdanzjy.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.aizwys.cn/Article/details/gtfveeiprl.html

JS:   `Hello, ${name}!`
来源：http://dali.yonumen.top/Article/details/gtkpqfxvho.html

TS:   `Hello, ${name}!`
来源：http://dali.xuetiantiany.cn/Article/details/gtjwgzzoro.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sxryk.cn/Article/details/gticdhrcfh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.iojbl.cn/Article/details/gtujxelajp.html

Ruby: "Hello, #{name}!"
来源：http://dali.svipenyu.cn/Article/details/gtvywxitzh.html

C#:   $"Hello, {name}!"
来源：http://dali.nanxinkj.top/Article/details/gtmastnrgd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhiwuduotai.top/Article/details/gtwvairvzx.html

Py:   "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtrmszgoln.html

PHP:  "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtruacpbfc.html

JS:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtehubzzzv.html

TS:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtehghgggo.html

Java: "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtvvkxoyya.html

Go:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtzycsatvx.html

Ruby: "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtncvwxzct.html

C#:   "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtyxyrnytf.html

[A14] 注释写法
来源：http://dali.cheryme.top/Article/details/gtwuvwgmjn.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ybcxt.top/Article/details/gtbvakhwgb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gtsixgauvg.html

JS:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gtfcmcrixb.html

TS:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gtgdebmcah.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sysykeji.top/Article/details/gtfcouvkfh.html

Go:   // 单行；/* 多行 */
来源：http://dali.redwolf501.top/Article/details/gtelmwzmhm.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhoulong.xyz/Article/details/gtfjxpkico.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhengqikj.top/Article/details/gtjcxcdxso.html

[A15] 空值判断与默认值
来源：http://dali.quarkkingdee.top/Article/details/gtexfkpbbz.html

Py:   value = data or "默认值"
来源：http://dali.tanke756.top/Article/details/gthyqckrul.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.havefunace.top/Article/details/gtbivnqdys.html

JS:   const value = data ?? "默认值";
来源：http://dali.gzhubu.top/Article/details/gtqfdbvseu.html

TS:   const value = data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gtzmeyphoo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shanyushiyangtech.top/Article/details/gtumhduqqj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylhxfdgn.html


<!-- 参考信息 -->