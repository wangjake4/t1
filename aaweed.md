代发 wailian999

[U97] JS：并发请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtejwbzlbm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtfqflusus.html

[U98] JS：fetch 带 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtqvmoqgka.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shangyingyoupin.top/Article/details/gthkdmshvx.html

[U99] JS：事件监听
来源：http://dali.wangshuangyany.cn/Article/details/gtofdcdkkf.html

el.addEventListener("click", e => {})
来源：http://dali.zhoulong.xyz/Article/details/gtmtwmiikb.html

[U100] JS：DOM 查询
来源：http://dali.svipenyu.cn/Article/details/gtfrbomssk.html

document.querySelector(".item")
来源：http://dali.ehwqpu.com/Article/details/gthtptmskr.html

[U101] JS：classList 操作
来源：http://dali.yongpay.top/Article/details/gtgcfztqwl.html

el.classList.toggle("active")
来源：http://dali.yuanzhike.top/Article/details/gtcknjidus.html

[U102] JS：本地存储
来源：http://dali.vqdsnc.cn/Article/details/gtqayvgecb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.dashuyun.cn/Article/details/gtehyoflzv.html

[U103] JS：定时器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrikbnsyb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhongyouzk.top/Article/details/gttpbwvhby.html

[U104] JS：防抖
来源：http://dali.sweek.top/Article/details/gtikjsgcww.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gttrgulehd.html

[U105] JS：节流
来源：http://dali.nwbrower.top/Article/details/gtmcoedocq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jyoumei.cn/Article/details/gtouwpuawr.html

[U106] JS：日期格式化
来源：http://dali.cucudq.cn/Article/details/gtpzkxlbxk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.guannengcc.top/Article/details/gtokyuyeoe.html

[U107] JS：数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtmsjuwdeu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gthlijlwop.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gtvolddhwq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxuanxn.top/Article/details/gtggghczne.html

[U109] JS：数组分组
来源：http://dali.hongshengwenyu.top/Article/details/gtotwhgein.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtvommsmuk.html

[U110] JS：数组分块
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgiuqxvr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.fengsongda.top/Article/details/gtmoqjzhhj.html

[U111] JS：对象转 Map
来源：http://dali.gzhubu.top/Article/details/gtmbrhigtl.html

new Map(Object.entries(obj))
来源：http://dali.gogol.net.cn/Article/details/gtvawgljeq.html

[U112] JS：字符串补位
来源：http://dali.9152youxi.cn/Article/details/gtiqinrpnl.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtkusxddqt.html

[U113] JS：正则替换全部
来源：http://dali.shangyingyoupin.top/Article/details/gtnkhnuhse.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gteopafgcs.html

[U114] JS：JSON 深比较
来源：http://dali.pycfn.com/Article/details/gtkvzozosj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtmsnpearr.html

[U115] JS：生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtwnyajrfx.html

crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtwhrskxno.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgufenzy.top/Article/details/gtadqsaruk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aizwys.cn/Article/details/gtmpsfulog.html

[U117] JS：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gtfexuozgy.html

npm i -D vitest;  npx vitest
来源：http://dali.yanxiufei.cn/Article/details/gttzsgtrdm.html

[U118] JS：开发服务器
来源：http://dali.cucudq.cn/Article/details/gtwyfvotkk.html

npm i -D vite;  npx vite
来源：http://dali.zhixingplan.top/Article/details/gtibjhqzlq.html

[U119] JS：生产构建
来源：http://dali.c1oappe.top/Article/details/gtlajthmuo.html

npx vite build
来源：http://dali.ydzc1.top/Article/details/gtlksviyaz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dianchejie.cn/Article/details/gtzegthzwu.html

import.meta.env.VITE_API_URL
来源：http://dali.svipenyu.cn/Article/details/gtyjpzptmb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmroytqem.html

统计汇总
来源：http://dali.yongpay.top/Article/details/gtmqxemjtq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvvydagks.html

按语言统计（条）：
来源：http://dali.cucudq.cn/Article/details/gtwmzrndfc.html

Python ......... 252
来源：http://dali.xinyue.icu/Article/details/gtqxosabou.html

PHP ............ 252
来源：http://dali.xuanzx.com/Article/details/gtkzffczgx.html

JavaScript ..... 252
来源：http://dali.9152youxi.cn/Article/details/gtmxpgewdb.html

TypeScript ..... 212
来源：http://dali.guowangkeji.top/Article/details/gtmwldrtgs.html

Java ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gtmdsilxbc.html

Go ............. 212
来源：http://dali.aibaodan.cn/Article/details/gtmmbejokh.html

Ruby ........... 212
来源：http://dali.xuanzx.com/Article/details/gtrjrzmost.html

C# ............. 212
来源：http://dali.bjfxy.top/Article/details/gtuwizjosv.html

C .............. 30
来源：http://dali.zhengqikj.top/Article/details/gtxldbgahh.html

C++ ............ 30
来源：http://dali.cashguo.top/Article/details/gtygavuwko.html

SQL ............ 90
来源：http://dali.xziqi.cn/Article/details/gtoxdykhpf.html

Bash ........... 80
来源：http://dali.tanke756.top/Article/details/gtdnuhjcuc.html

Kotlin ......... 15
来源：http://dali.fengsongda.top/Article/details/gtbmgzhnum.html

Swift .......... 15
来源：http://dali.yj20258888.top/Article/details/gtcgrdjeqk.html

Lua ............ 10
来源：http://dali.shzxlz.cn/Article/details/gttufdqbpo.html

Perl ........... 10
来源：http://dali.yvedp.cn/Article/details/gthqlchnog.html

Scala .......... 10
来源：http://dali.hongshengwenyu.top/Article/details/gtkwnxufhs.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtirakiqmp.html

合计 ........... 2106 条
来源：http://dali.yvedp.cn/Article/details/gtzafomslf.html

按章节统计：
来源：http://dali.kuanghao11.cn/Article/details/gttasffcxd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gtrypioqbx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxrpyrgo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gtdhndvjlb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gtwnvczdjz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tianlin.xyz/Article/details/gtqkosehif.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gtjysfyaxq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gtzhldotmm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtksvbowzy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtjgjyqost.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtawpsfq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtuiqkdqhp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtqhfhnhyi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtjscknpgw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gtqcohwyzz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cdnleiting.top/Article/details/gtznwxtyej.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtasptqwab.html

Q SQL 专题                              90
来源：http://dali.c1oappe.top/Article/details/gtgtayeefw.html

R Bash 专题                             80
来源：http://dali.zhengqikj.top/Article/details/gtyihjnrks.html

S C / C++ 专题                          60
来源：http://dali.cashguo.top/Article/details/gtllffsswr.html

T 其他语言补充                          60
来源：http://dali.dashuyun.cn/Article/details/gtuqczfpsa.html

U 高频实用片段                         120
来源：http://dali.meibo888.top/Article/details/gtvecdbahn.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtlqnznibq.html

合计                                  2106 条
来源：http://dali.ydzc1.top/Article/details/gttkibgvma.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtuxifaohu.html

使用提醒
来源：http://dali.nwbrower.top/Article/details/gtoxcrdhmj.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtmeglnhva.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xziqi.cn/Article/details/gtngtvqmlu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hfpthk.cn/Article/details/gthtzdgdtp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yangfankeji.com/Article/details/gtwpvnzxzl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhiwuduotai.top/Article/details/gtxgafkbjr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zycfv.cn/Article/details/gtbwptries.html

—— 文件结束 ——
来源：http://dali.zhixingplan.top/Article/details/gtkqkjrbnd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgivdgkqz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jianghu66.top/Article/details/gtuhqkrdac.html

Common Programming Examples Cheat Book
来源：http://dali.jqgfzy.top/Article/details/gttfrweuxn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtaktsnvnc.html

【收录内容】
来源：http://dali.fzhhl.top/Article/details/gtffzxhrvb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shuidangran.top/Article/details/gtombriujn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.dashuyun.cn/Article/details/gtcqvxvxmb.html

SQL · Bash · C · C++
来源：http://dali.chenlongwang.top/Article/details/gtvcnxdzpf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hnxiangtu.top/Article/details/gtwsgdoyvo.html

【使用说明】
来源：http://dali.9152youxi.cn/Article/details/gtdosmousq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.9152youxi.cn/Article/details/gtrdmmhgiw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xuetiantiany.cn/Article/details/gtmmzfkrne.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.svipenyu.cn/Article/details/gtydvxxbnj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.fzhhl.top/Article/details/gtsdlcorno.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.daxiang520.top/Article/details/gtvddcucgq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daria6918.cn/Article/details/gtynegqbks.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.havefunace.top/Article/details/gtopxgbaaz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hfpthk.cn/Article/details/gtpscvqxku.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangdashe.top/Article/details/gttsolhotr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj202588.top/Article/details/gtwnlytgpu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.quarkkingdee.top/Article/details/gttmuwvrmx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufatpdmj.html

【文件统计】
来源：http://dali.yueranfly.top/Article/details/gturjcdpbh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nanxinkj.top/Article/details/gtzbmunnhe.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqjhrate.html

目  录
来源：http://dali.jiagoushi.top/Article/details/gtmoecdzpc.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtwysasdzp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sweek.top/Article/details/gtyieihabm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gtyzpcetre.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gtrzorptpo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gaohongyu789.top/Article/details/gtruzgazcn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zycfv.cn/Article/details/gtmzmhhoow.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.kuanghao11.cn/Article/details/gtgcxihrpa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsycgzje.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtblzxcenj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyxylklv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.redwolf501.top/Article/details/gtrirnyvco.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubdzhvrf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtngecgsir.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtmntdxdvg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenlongwang.top/Article/details/gtrrtvftte.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fzhhl.top/Article/details/gtqcjoxnqx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtvghfagdx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrcpyyml.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ppjwa.cn/Article/details/gtpkqmmiax.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cqqwz.cn/Article/details/gtqurgdens.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gtmmmvxqdw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gtzwbifeka.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtphnoblih.html

A. 基础语法与类型
来源：http://dali.fzhhl.top/Article/details/gtrfmooguv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdbqeudpl.html

[A01] Hello World
来源：http://dali.chenlongwang.top/Article/details/gtjvqqbmsv.html

Py:   print("Hello, World!")
来源：http://dali.ppjwa.cn/Article/details/gtvrytwfxe.html

PHP:  echo "Hello, World!";
来源：http://dali.dashuyun.cn/Article/details/gtqrwunvoa.html

JS:   console.log("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gtzhxokabf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shuidangran.top/Article/details/gtazapavml.html

Java: System.out.println("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gtuqtfcpvo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zycfv.cn/Article/details/gtuyixggmk.html

Ruby: puts "Hello, World!"
来源：http://dali.xinyue.icu/Article/details/gttlcpjxrk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrxskavh.html

[A02] 变量声明与赋值
来源：http://dali.hnxiangtu.top/Article/details/gtgoxppkro.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xziqi.cn/Article/details/gtyqkpbfyf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cqqwz.cn/Article/details/gtloarvevf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtvigeiwnf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtbxqecrjx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gtuubpzddw.html

Go:   name := "Alex"; age := 20
来源：http://dali.yuxming.cn/Article/details/gtemnjxamo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenzaomai.com/Article/details/gtsilwbcxc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ivvv.top/Article/details/gtoijmiave.html

[A03] 常量定义
来源：http://dali.sweek.top/Article/details/gtgmgjsktb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxuanxn.top/Article/details/gtzmqdigqm.html

PHP:  const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtvtubfzqz.html

JS:   const PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtpqnvsnst.html

TS:   const PI: number = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtviafribh.html

Java: static final double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtmqpsnxeg.html

Go:   const PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gtivdzafns.html

Ruby: PI = 3.14159
来源：http://dali.chenlongwang.top/Article/details/gtwzxkdzda.html

C#:   const double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdbjoeim.html

[A04] 判断变量类型
来源：http://dali.gotoacloud.top/Article/details/gtkblyqgsj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guowangkeji.top/Article/details/gtsaeqcntw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yanxiufei.cn/Article/details/gtkuzfwekd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cashguo.top/Article/details/gtexuhyxnn.html

TS:   typeof x; x instanceof Date
来源：http://dali.pengpengdd.cyou/Article/details/gtpomxmwfk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.birdmap.top/Article/details/gtzjafffgs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cashguo.top/Article/details/gtngyxdzcw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jiagoushi.top/Article/details/gtfhbpavxw.html

C#:   x.GetType().Name; x is int
来源：http://dali.jyoumei.cn/Article/details/gtyynnsgox.html

[A05] 整数除法与取模
来源：http://dali.zycfv.cn/Article/details/gtelimynnd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yuanzhike.top/Article/details/gtxshglczb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gtlmwftfpq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtcjvfgvnv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtvenaxbmx.html

Java: 7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtaqmgbmsv.html

Go:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gturlddhfd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtltqvaava.html

C#:   7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtdbwlzbgk.html

[A06] 字符串转数字
来源：http://dali.meibo888.top/Article/details/gtvitijaid.html

Py:   int("42"); float("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtvcflgunv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinqigfzy.top/Article/details/gtcozkbtob.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jianghu66.top/Article/details/gtpuuphnaq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.pycfn.com/Article/details/gtpwmwezmj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.meibo888.top/Article/details/gtlknbqguc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuanzhike.top/Article/details/gtjqwkdvuq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cqqwz.cn/Article/details/gtpmimnmya.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xinyue.icu/Article/details/gtayoummkq.html

[A07] 数字转字符串
来源：http://dali.0kj1m.cn/Article/details/gteeafifxr.html

Py:   str(42)
来源：http://dali.jyoumei.cn/Article/details/gtbupmamne.html

PHP:  (string) 42; strval(42)
来源：http://dali.zdqjudy.top/Article/details/gtmkgkwbsy.html

JS:   String(42); (42).toString()
来源：http://dali.havefunace.top/Article/details/gtpvwyxmqc.html

TS:   String(42)
来源：http://dali.andypj.xyz/Article/details/gtkaqqwwwe.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinqigfzy.top/Article/details/gtbdzeemrl.html

Go:   strconv.Itoa(42)
来源：http://dali.jiagoushi.top/Article/details/gtlbmiefrz.html

Ruby: 42.to_s
来源：http://dali.snrcjt.cn/Article/details/gtrxhafxqe.html

C#:   42.ToString()
来源：http://dali.sufxvd.cn/Article/details/gtjdmhjadw.html

[A08] 取整与四舍五入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvxoobtl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gtptuniudy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jiagoushi.top/Article/details/gtzmapvsjq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtenmiqrah.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.andypj.xyz/Article/details/gturkuxgow.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gttzpkwkmf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gtrnvujaxp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ppjwa.cn/Article/details/gtvkkxqkbp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtwexzuhki.html

[A09] 绝对值与最大最小值
来源：http://dali.nanxinkj.top/Article/details/gtilrmihlp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtpasyrwnc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtesuozfzl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtxncfhesj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtpofybpng.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtazdyxjxn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.guannengcc.top/Article/details/gtvikzkopy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shuidangran.top/Article/details/gtpeuabctf.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtiybozhjz.html

[A10] 生成随机数
来源：http://dali.zhiwuduotai.top/Article/details/gtlxhatyoc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.quarkkingdee.top/Article/details/gtfftqnyxh.html

PHP:  random_int(1, 100);
来源：http://dali.9152youxi.cn/Article/details/gttbbzybib.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aibaodan.cn/Article/details/gtibdvkxav.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shzxlz.cn/Article/details/gtxuzzplix.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj202588.top/Article/details/gtedhbctbt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.chenlongwang.top/Article/details/gtbrilbspg.html

Ruby: rand(1..100)
来源：http://dali.jinqigufen.top/Article/details/gtufgvpbsq.html

C#:   new Random().Next(1, 101)
来源：http://dali.zdqjudy.top/Article/details/gtdirhkaof.html

[A11] 条件表达式（三元）
来源：http://dali.tian-w.cn/Article/details/gtdfidbfxe.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zdqjudy.top/Article/details/gthvhogolw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gtaglfxbbn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gtldyppvpv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtwwdpohws.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gtiqfouqzk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.vqdsnc.cn/Article/details/gttsvpohhs.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtrlzrvqpm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ppjwa.cn/Article/details/gtwudvdgva.html

[A12] 字符串插值 / 格式化
来源：http://dali.gotoacloud.top/Article/details/gtwmvvsphh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gogol.net.cn/Article/details/gtgwqpwfbr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shzxlz.cn/Article/details/gtjebabkvx.html

JS:   `Hello, ${name}!`
来源：http://dali.dianchejie.cn/Article/details/gttsuvdfas.html

TS:   `Hello, ${name}!`
来源：http://dali.zhoulong.xyz/Article/details/gttfgrspzr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.fengsongda.top/Article/details/gthixauhvc.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yonumen.top/Article/details/gtosgycafn.html

Ruby: "Hello, #{name}!"
来源：http://dali.zycfv.cn/Article/details/gtpmtyzema.html

C#:   $"Hello, {name}!"
来源：http://dali.tanke756.top/Article/details/gtzfnuksvv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jiagoushi.top/Article/details/gttqexeajx.html

Py:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gtladkqovk.html

PHP:  "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtyrzjxhuh.html

JS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtlsfeesdk.html

TS:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtuowaavxg.html

Java: "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtawzqojrr.html

Go:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvdegrgq.html

Ruby: "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtcscqvnaa.html

C#:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtlfzexxky.html

[A14] 注释写法
来源：http://dali.havefunace.top/Article/details/gtgpbfdqts.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zycfv.cn/Article/details/gtbwwoendl.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtisuheptz.html

JS:   // 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gtezwjziki.html

TS:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtvghhumzr.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.fzhhl.top/Article/details/gtlgpbbwss.html

Go:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gtqlvizaeo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.haohaochexian.top/Article/details/gtaowjgasv.html

C#:   // 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gtuuethyvk.html

[A15] 空值判断与默认值
来源：http://dali.fengsongda.top/Article/details/gtamvzyzkw.html

Py:   value = data or "默认值"
来源：http://dali.gaohongyu789.top/Article/details/gtnlisjnht.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.tianlin.xyz/Article/details/gtfscqldvv.html

JS:   const value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gttpynvxjd.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gtngsjrxui.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.316326.xyz/Article/details/gtlybvehil.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsogohazf.html

Ruby: value = data || "默认值"
来源：http://dali.yonumen.top/Article/details/gtafuluvpi.html

C#:   var value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gtnrmklkhh.html

[A16] 真假值判断规则
来源：http://dali.tian-w.cn/Article/details/gttvdkpzhl.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hammf.cn/Article/details/gtrwvmkjbs.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jianghu66.top/Article/details/gtajaqccwf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.tian-w.cn/Article/details/gthhijtdvs.html

TS:   if (!x) {}
来源：http://dali.gotoacloud.top/Article/details/gtwfsgkexn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.meibo888.top/Article/details/gtizxpltsp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hammf.cn/Article/details/gtpobfdtam.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.mhx1999.top/Article/details/gtbmdvpbzz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xinyue.icu/Article/details/gtikbtkpax.html

[A17] 位运算
来源：http://dali.316326.xyz/Article/details/gtjumswuyh.html


<!-- 参考信息 -->