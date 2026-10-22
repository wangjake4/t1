代发 wailian999

[U99] JS：事件监听
来源：http://dali.quarkkingdee.top/Article/details/gtyzjsnvke.html

el.addEventListener("click", e => {})
来源：http://dali.hnqzz.top/Article/details/gtykoybvut.html

[U100] JS：DOM 查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpycutzpw.html

document.querySelector(".item")
来源：http://dali.vqdsnc.cn/Article/details/gtnaxjslbu.html

[U101] JS：classList 操作
来源：http://dali.guowangkeji.top/Article/details/gtdwocskrq.html

el.classList.toggle("active")
来源：http://dali.redwolf501.top/Article/details/gtukiokbbd.html

[U102] JS：本地存储
来源：http://dali.zhengqikj.top/Article/details/gtksyejsxg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guannengcc.top/Article/details/gtqyjotyeu.html

[U103] JS：定时器
来源：http://dali.yonumen.top/Article/details/gtzxxygldc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.guannengcc.top/Article/details/gtzqeggejc.html

[U104] JS：防抖
来源：http://dali.gotoacloud.top/Article/details/gtyabcudst.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtfiztqtgw.html

[U105] JS：节流
来源：http://dali.haohaochexian.top/Article/details/gtpixcdkwr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.guannengcc.top/Article/details/gtkfrfwmen.html

[U106] JS：日期格式化
来源：http://dali.yuxming.cn/Article/details/gtbvkyydyo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpulgojzk.html

[U107] JS：数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiznklzjh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtpgsketlf.html

[U108] JS：随机整数
来源：http://dali.xuanzx.com/Article/details/gthqrmzbbz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.kuanghao11.cn/Article/details/gtdcbdynrj.html

[U109] JS：数组分组
来源：http://dali.ivvv.top/Article/details/gtssfzwwmq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtuiyjfpkn.html

[U110] JS：数组分块
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxcngqpd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yonumen.top/Article/details/gtqxqniaxn.html

[U111] JS：对象转 Map
来源：http://dali.quarkkingdee.top/Article/details/gtfxgvrbxa.html

new Map(Object.entries(obj))
来源：http://dali.fengsongda.top/Article/details/gthehrxcjj.html

[U112] JS：字符串补位
来源：http://dali.feifeiyinyue.top/Article/details/gtpcxsxvjs.html

"7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtdofiiyrf.html

[U113] JS：正则替换全部
来源：http://dali.quarkkingdee.top/Article/details/gthsepkyeg.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtikoaokos.html

[U114] JS：JSON 深比较
来源：http://dali.tianlin.xyz/Article/details/gtyjqbpheq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gtbxvcecud.html

[U115] JS：生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtsbiyyfwf.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrctwwps.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daria6918.cn/Article/details/gthplcpzhd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aibaodan.cn/Article/details/gtfzbikexq.html

[U117] JS：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gtivteuaof.html

npm i -D vitest;  npx vitest
来源：http://dali.yangfankeji.com/Article/details/gtnleitjkx.html

[U118] JS：开发服务器
来源：http://dali.sysykeji.top/Article/details/gtsuyynyml.html

npm i -D vite;  npx vite
来源：http://dali.cqqwz.cn/Article/details/gtarkzufqo.html

[U119] JS：生产构建
来源：http://dali.gogol.net.cn/Article/details/gtuqtvlbqh.html

npx vite build
来源：http://dali.havefunace.top/Article/details/gtpswitrmy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xziqi.cn/Article/details/gtpqvbjtbk.html

import.meta.env.VITE_API_URL
来源：http://dali.jiagoushi.top/Article/details/gtqlrsrdwr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbvcyzhkj.html

统计汇总
来源：http://dali.hnqzz.top/Article/details/gtpzsscpsk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtsplmaczm.html

按语言统计（条）：
来源：http://dali.hywenlv.cn/Article/details/gtfndnexfq.html

Python ......... 252
来源：http://dali.birdmap.top/Article/details/gthjbthuzz.html

PHP ............ 252
来源：http://dali.316326.xyz/Article/details/gthrnyfier.html

JavaScript ..... 252
来源：http://dali.jiagoushi.top/Article/details/gtdwomvffj.html

TypeScript ..... 212
来源：http://dali.sysykeji.top/Article/details/gtemsvksco.html

Java ........... 212
来源：http://dali.nwbrower.top/Article/details/gtcqpnntis.html

Go ............. 212
来源：http://dali.aizwys.cn/Article/details/gtakpsgcar.html

Ruby ........... 212
来源：http://dali.zhixingplan.top/Article/details/gttvirsvlk.html

C# ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gtessnjpoj.html

C .............. 30
来源：http://dali.fengsongda.top/Article/details/gtbkdjgoim.html

C++ ............ 30
来源：http://dali.hnxiangtu.top/Article/details/gtdkrtyeno.html

SQL ............ 90
来源：http://dali.shanyushiyangtech.top/Article/details/gtovwwlgeo.html

Bash ........... 80
来源：http://dali.pycfn.com/Article/details/gtpubruqos.html

Kotlin ......... 15
来源：http://dali.cucudq.cn/Article/details/gtneheaobr.html

Swift .......... 15
来源：http://dali.zhixingplan.top/Article/details/gtgtxdxbul.html

Lua ............ 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruyukdlg.html

Perl ........... 10
来源：http://dali.tianlin.xyz/Article/details/gtcnfzxuda.html

Scala .......... 10
来源：http://dali.daxiang520.top/Article/details/gtjsnzgxap.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtufobyqpu.html

合计 ........... 2106 条
来源：http://dali.hnqzz.top/Article/details/gtjwwlfzef.html

按章节统计：
来源：http://dali.bjfxy.top/Article/details/gtxmqxcudz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtnrcxsjma.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtpksurxdr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtvptxtceg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtpmhjwshk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.wangshuangyany.cn/Article/details/gtibhcctih.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhengqikj.top/Article/details/gtguhxfdka.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtaumpyscb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gtllhossdm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtqnejljxs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gtssfqeznv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtokeksmya.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtpbspzbho.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtdvrimrey.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sxryk.cn/Article/details/gtakqktlic.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jqgufenzy.top/Article/details/gtuvscwshf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtzaeqpvem.html

Q SQL 专题                              90
来源：http://dali.hysaishi.cn/Article/details/gtihnrjxhc.html

R Bash 专题                             80
来源：http://dali.0kj1m.cn/Article/details/gtwvntahor.html

S C / C++ 专题                          60
来源：http://dali.redwolf501.top/Article/details/gtmjzxnrty.html

T 其他语言补充                          60
来源：http://dali.hammf.cn/Article/details/gtkvkovbby.html

U 高频实用片段                         120
来源：http://dali.hammf.cn/Article/details/gtqqgdlivc.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gttlgdbrgl.html

合计                                  2106 条
来源：http://dali.zhongyouzk.top/Article/details/gttgfrjsai.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtzkomshjo.html

使用提醒
来源：http://dali.zhaomingkeji.xyz/Article/details/gtespxwdmt.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtmvurzgod.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj20258888.top/Article/details/gtyywqtidx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.svipenyu.cn/Article/details/gttjtlrpbg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.meibo888.top/Article/details/gtdijmuimr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gogol.net.cn/Article/details/gtrkvbvwsl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgufenzy.top/Article/details/gtbnnttjij.html

—— 文件结束 ——
来源：http://dali.hongshengwenyu.top/Article/details/gtdbvfclrf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqdntidgy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ivvv.top/Article/details/gtjheyemyc.html

Common Programming Examples Cheat Book
来源：http://dali.gogol.net.cn/Article/details/gtdjtpyueb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtvwnmsihc.html

【收录内容】
来源：http://dali.dashuyun.cn/Article/details/gtylqdetrg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.feifeiyinyue.top/Article/details/gtvlkswnku.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcnyjczu.html

SQL · Bash · C · C++
来源：http://dali.aibaodan.cn/Article/details/gttzspowda.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.pycfn.com/Article/details/gtmbaflyrx.html

【使用说明】
来源：http://dali.yj20258888.top/Article/details/gtluqucgpg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tanke756.top/Article/details/gttoobxgfd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.snrcjt.cn/Article/details/gtujsqtcep.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gtptvyqhmt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinqigfzy.top/Article/details/gtwrvxjcwa.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hfpthk.cn/Article/details/gttsunrmwc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gtxzsvodis.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aizwys.cn/Article/details/gtmxpsljsc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhengqikj.top/Article/details/gtsgtykita.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hongshengwenyu.top/Article/details/gtpzufsgln.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tian-w.cn/Article/details/gtkzwjsiik.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.wangdashe.top/Article/details/gtknfepdru.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhoulong.xyz/Article/details/gtlakqyrig.html

【文件统计】
来源：http://dali.zhoulong.xyz/Article/details/gtvwmcowye.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.meibo888.top/Article/details/gtlggycjds.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gthryvdeiy.html

目  录
来源：http://dali.yanxiufei.cn/Article/details/gtzvvbtlpz.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtrwddkbmw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gtjhhdxnhq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtgnehxwfg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gtwisubvem.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jiagoushi.top/Article/details/gtkzsycguy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.wangdashe.top/Article/details/gtqiwdkhif.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gttairvzhn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gtclptjmia.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.smart0.xyz/Article/details/gtwtrszwid.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjazbfazd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtmniijezy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gthzsuqtsp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gthzrffplt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gtnlhabyra.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gtrqsiwgzh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.mhx1999.top/Article/details/gtypjeqptc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtdlteagln.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhongyouzk.top/Article/details/gtweljwlvh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yongpay.top/Article/details/gtjhglldvi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.nanxinkj.top/Article/details/gtqiulzaun.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtcnowrttj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gtqheubpmu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjnpmakbg.html

A. 基础语法与类型
来源：http://dali.shuidangran.top/Article/details/gtmdqgifac.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtxnhuwfca.html

[A01] Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtxdvycufh.html

Py:   print("Hello, World!")
来源：http://dali.hnqzz.top/Article/details/gthtaeypxa.html

PHP:  echo "Hello, World!";
来源：http://dali.ivvv.top/Article/details/gtvbmttvcy.html

JS:   console.log("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gtgxawsbbv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhongyouzk.top/Article/details/gtzluorzlq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbppfiyo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hnxiangtu.top/Article/details/gtrqbnfhvx.html

Ruby: puts "Hello, World!"
来源：http://dali.yueranfly.top/Article/details/gtnoojcwqm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinqigufen.top/Article/details/gtdbcrgpds.html

[A02] 变量声明与赋值
来源：http://dali.sxryk.cn/Article/details/gthsbxraqe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.kuanghao11.cn/Article/details/gtuxrmlvsl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinqigufen.top/Article/details/gtjihywgyo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtltvvcmma.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtantylmpe.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.meibo888.top/Article/details/gtjydwvmey.html

Go:   name := "Alex"; age := 20
来源：http://dali.smart0.xyz/Article/details/gtdmrzqupj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gogol.net.cn/Article/details/gtzyueoxvu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.chenzaomai.com/Article/details/gtiuauyjuw.html

[A03] 常量定义
来源：http://dali.chenzaomai.com/Article/details/gtjfnlunge.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhongyouzk.top/Article/details/gtcegaagty.html

PHP:  const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtwzdtprjt.html

JS:   const PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtyfodafsa.html

TS:   const PI: number = 3.14159;
来源：http://dali.birdmap.top/Article/details/gthlcaqxrj.html

Java: static final double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtznbdwsbp.html

Go:   const PI = 3.14159
来源：http://dali.0kj1m.cn/Article/details/gtasxxurio.html

Ruby: PI = 3.14159
来源：http://dali.zhengqikj.top/Article/details/gtihoekgtj.html

C#:   const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtirkptkrp.html

[A04] 判断变量类型
来源：http://dali.gzhubu.top/Article/details/gtnrkhigbk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.smart0.xyz/Article/details/gtxoioivhh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yueranfly.top/Article/details/gtvfeyyexw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhengqikj.top/Article/details/gtuvvmjrsr.html

TS:   typeof x; x instanceof Date
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchaistzp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqkewdre.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.quarkkingdee.top/Article/details/gtygbqhclo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigfzy.top/Article/details/gttsxaeplp.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcowxjrzh.html

[A05] 整数除法与取模
来源：http://dali.xuetiantiany.cn/Article/details/gtaoyigebs.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xuanzx.com/Article/details/gtriieifny.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtjibttvaq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtbxioeryc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtbqtjptxe.html

Java: 7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtjknzjuwj.html

Go:   7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtdgzszbva.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtkolbvazl.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtofdihxhc.html

[A06] 字符串转数字
来源：http://dali.xylfe.cn/Article/details/gtkclpiqqs.html

Py:   int("42"); float("3.14")
来源：http://dali.316326.xyz/Article/details/gtphvakztx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyyzsrua.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.iojbl.cn/Article/details/gtwbtzyxnv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ydzc1.top/Article/details/gtrbtmntrk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gtrvtexxcv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinqigfzy.top/Article/details/gtapqdjceu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shangyingyoupin.top/Article/details/gtwswqgicn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yueranfly.top/Article/details/gthmsaswxo.html

[A07] 数字转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtjdesszir.html

Py:   str(42)
来源：http://dali.zhongyouzk.top/Article/details/gtatkewjwu.html

PHP:  (string) 42; strval(42)
来源：http://dali.yj20258888.top/Article/details/gtidjrnhxs.html

JS:   String(42); (42).toString()
来源：http://dali.yongpay.top/Article/details/gtiewtrurg.html

TS:   String(42)
来源：http://dali.cqqwz.cn/Article/details/gtkxfvxqku.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xziqi.cn/Article/details/gtmzxavzry.html

Go:   strconv.Itoa(42)
来源：http://dali.xylfe.cn/Article/details/gtugsunbti.html

Ruby: 42.to_s
来源：http://dali.0kj1m.cn/Article/details/gtzwduewja.html

C#:   42.ToString()
来源：http://dali.c1oappe.top/Article/details/gtpobliwsp.html

[A08] 取整与四舍五入
来源：http://dali.sysykeji.top/Article/details/gtqojfrmmy.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtagyataeq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xziqi.cn/Article/details/gtdkqmkzte.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtyznewpht.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cucudq.cn/Article/details/gtefvggvme.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtxubmwqjp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisijadvl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.gaohongyu789.top/Article/details/gtnjyhlfrh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtycfqdwxy.html

[A09] 绝对值与最大最小值
来源：http://dali.smart0.xyz/Article/details/gtjztguvzv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gticitzxti.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtgizberjn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yj202588.top/Article/details/gtksjbevfb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtlqbuxjun.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtvhzylvox.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sweek.top/Article/details/gtwowofyuh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.pengpengdd.cyou/Article/details/gtiqkbyejc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtcobqykhz.html

[A10] 生成随机数
来源：http://dali.aizwys.cn/Article/details/gtadpasotw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zdqjudy.top/Article/details/gtnecgotqx.html

PHP:  random_int(1, 100);
来源：http://dali.ivvv.top/Article/details/gtjmaeszwc.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhoulong.xyz/Article/details/gtkuhtaxvl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuanzx.com/Article/details/gtraprkdkf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.havefunace.top/Article/details/gtoapyiwjg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gogol.net.cn/Article/details/gtamjumwbl.html

Ruby: rand(1..100)
来源：http://dali.hnxiangtu.top/Article/details/gtjqpcoygv.html

C#:   new Random().Next(1, 101)
来源：http://dali.c1oappe.top/Article/details/gtrflqnmdu.html

[A11] 条件表达式（三元）
来源：http://dali.mhx1999.top/Article/details/gthizfdnuq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.iojbl.cn/Article/details/gtpesrnozp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gtukvkdoay.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gthcvacjfu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtebvfvlel.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtoqwmjqhx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj20258888.top/Article/details/gtlwlcczfx.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gtkjgragad.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gtwvbpearp.html

[A12] 字符串插值 / 格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtaavgunig.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gogol.net.cn/Article/details/gtnatflgvc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yj202588.top/Article/details/gtidaqipfe.html

JS:   `Hello, ${name}!`
来源：http://dali.chenzaomai.com/Article/details/gtbqxoqkqu.html

TS:   `Hello, ${name}!`
来源：http://dali.birdmap.top/Article/details/gtzbozunoy.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.redwolf501.top/Article/details/gtganbuwrm.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtjnfpppxk.html

Ruby: "Hello, #{name}!"
来源：http://dali.sxryk.cn/Article/details/gtnycemztn.html

C#:   $"Hello, {name}!"
来源：http://dali.snrcjt.cn/Article/details/gtzzsjwvhs.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.smart0.xyz/Article/details/gtmsqefeni.html

Py:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtrefdeeuc.html

PHP:  "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtuuowfajs.html

JS:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtiwrpvanx.html

TS:   "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtccuaplio.html

Java: "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtuzjngibz.html

Go:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtkguaynmq.html

Ruby: "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtychjbzvs.html

C#:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtnpbjldfc.html

[A14] 注释写法
来源：http://dali.zhoulong.xyz/Article/details/gtwohhulfe.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.guowangkeji.top/Article/details/gtjgxudvwh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gtkmdjxyhx.html

JS:   // 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtapeaiabd.html

TS:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gtybeompps.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.haohaochexian.top/Article/details/gtyndvojje.html

Go:   // 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gtwngdsvuf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.dashuyun.cn/Article/details/gtoukbgkeb.html

C#:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsewgmjd.html

[A15] 空值判断与默认值
来源：http://dali.daxiang520.top/Article/details/gtqwunxvvz.html

Py:   value = data or "默认值"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpajzgrg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gtmjeflzry.html

JS:   const value = data ?? "默认值";
来源：http://dali.zdqjudy.top/Article/details/gtkelclrhr.html

TS:   const value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gtcwxbutgu.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258.top/Article/details/gtqxlhdgtr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhixingplan.top/Article/details/gtmarbheco.html

Ruby: value = data || "默认值"
来源：http://dali.xuanzx.com/Article/details/gttyvltxah.html

C#:   var value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtjnbvakje.html

[A16] 真假值判断规则
来源：http://dali.sufxvd.cn/Article/details/gtisjgjezr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hnqzz.top/Article/details/gtqmkemhuh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.pycfn.com/Article/details/gtihdvgfwg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.smart0.xyz/Article/details/gtljapaitz.html

TS:   if (!x) {}
来源：http://dali.nanxinkj.top/Article/details/gtysxdvbrv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.bjfxy.top/Article/details/gtmstrvkis.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jiagoushi.top/Article/details/gtgolkifuj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xinyue.icu/Article/details/gtqcemumsn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.chenzaomai.com/Article/details/gthseqlykx.html

[A17] 位运算
来源：http://dali.redwolf501.top/Article/details/gtmqlxdghz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtcsngbwwu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtpglrwqds.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gthwiyahjp.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtnaslqsua.html


<!-- 参考信息 -->