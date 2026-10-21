代发 wailian999

[U93] JS：模板字符串
来源：http://dali.0kj1m.cn/Article/details/gtvzqoqkto.html

`共 ${n} 条`
来源：http://dali.fengsongda.top/Article/details/gtdpupzqoo.html

[U94] JS：箭头函数
来源：http://dali.xziqi.cn/Article/details/gtbxztuzoq.html

const double = x => x * 2;
来源：http://dali.yj202588.top/Article/details/gtgqegiorp.html

[U95] JS：Promise 包装
来源：http://dali.yuxming.cn/Article/details/gtmpfqdvzd.html

new Promise((resolve, reject) => {})
来源：http://dali.daxiang520.top/Article/details/gtfszslivc.html

[U96] JS：async/await 与异常
来源：http://dali.cucudq.cn/Article/details/gtvklhgwch.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtvqjzdyne.html

[U97] JS：并发请求
来源：http://dali.cqqwz.cn/Article/details/gtkrlozvhc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtflfnuccx.html

[U98] JS：fetch 带 JSON
来源：http://dali.redwolf501.top/Article/details/gtbtssaxis.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ehwqpu.com/Article/details/gtexkcwdes.html

[U99] JS：事件监听
来源：http://dali.haohaochexian.top/Article/details/gtqdagrslt.html

el.addEventListener("click", e => {})
来源：http://dali.c1oappe.top/Article/details/gtpelcsjgx.html

[U100] JS：DOM 查询
来源：http://dali.hongshengwenyu.top/Article/details/gtuzgrdstn.html

document.querySelector(".item")
来源：http://dali.hywenlv.cn/Article/details/gtlydrhcei.html

[U101] JS：classList 操作
来源：http://dali.hnxiangtu.top/Article/details/gtyvnsldfh.html

el.classList.toggle("active")
来源：http://dali.yonumen.top/Article/details/gtuhfeublz.html

[U102] JS：本地存储
来源：http://dali.yj20258888.top/Article/details/gttvanaahe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hfpthk.cn/Article/details/gtngjigaty.html

[U103] JS：定时器
来源：http://dali.sxryk.cn/Article/details/gtyjqojnwb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.wangdashe.top/Article/details/gtgjttvsgo.html

[U104] JS：防抖
来源：http://dali.daxiang520.top/Article/details/gtqhvcppuh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtinvrbgdq.html

[U105] JS：节流
来源：http://dali.jinqigufen.top/Article/details/gtthuvpfsl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.kuanghao11.cn/Article/details/gthohljrds.html

[U106] JS：日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtuelvtkvw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cdnleiting.top/Article/details/gtlwryeoub.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtyoehqzcv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yonumen.top/Article/details/gtqwyanytr.html

[U108] JS：随机整数
来源：http://dali.gaohongyu789.top/Article/details/gthxyugkzw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.kuanghao11.cn/Article/details/gtqcpnscrk.html

[U109] JS：数组分组
来源：http://dali.sysykeji.top/Article/details/gtliiiulql.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtodyfduqy.html

[U110] JS：数组分块
来源：http://dali.jiagoushi.top/Article/details/gtksmqcluv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.fengsongda.top/Article/details/gttoqmxgse.html

[U111] JS：对象转 Map
来源：http://dali.jiagoushi.top/Article/details/gtufcqcbjs.html

new Map(Object.entries(obj))
来源：http://dali.tianlin.xyz/Article/details/gtprprqwqy.html

[U112] JS：字符串补位
来源：http://dali.hysaishi.cn/Article/details/gtyuonrqei.html

"7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtbptpwulb.html

[U113] JS：正则替换全部
来源：http://dali.wangshuangyany.cn/Article/details/gtfjqdgpom.html

s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtqhegajsj.html

[U114] JS：JSON 深比较
来源：http://dali.zhoulong.xyz/Article/details/gtcfkditpq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtelvtcspv.html

[U115] JS：生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtyhczpkff.html

crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtuttrzpoc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aibaodan.cn/Article/details/gtyvlmxqbl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tian-w.cn/Article/details/gtzqbjwyuu.html

[U117] JS：单元测试
来源：http://dali.bjfxy.top/Article/details/gtoxhgufxx.html

npm i -D vitest;  npx vitest
来源：http://dali.fengsongda.top/Article/details/gtxjzzdcun.html

[U118] JS：开发服务器
来源：http://dali.0kj1m.cn/Article/details/gthpltlcvn.html

npm i -D vite;  npx vite
来源：http://dali.yonumen.top/Article/details/gtplibnjpz.html

[U119] JS：生产构建
来源：http://dali.haohaochexian.top/Article/details/gtogaenhtk.html

npx vite build
来源：http://dali.shanyushiyangtech.top/Article/details/gttpbvygzf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxinkj.top/Article/details/gtmdtjgsle.html

import.meta.env.VITE_API_URL
来源：http://dali.fengsongda.top/Article/details/gtdaenxqre.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxczqtfum.html

统计汇总
来源：http://dali.c1oappe.top/Article/details/gtrikticsi.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxlvqlttr.html

按语言统计（条）：
来源：http://dali.jinqigufen.top/Article/details/gtrlpoybzy.html

Python ......... 252
来源：http://dali.zhongyouzk.top/Article/details/gtfysvjnqq.html

PHP ............ 252
来源：http://dali.jyoumei.cn/Article/details/gtdwsuomun.html

JavaScript ..... 252
来源：http://dali.c1oappe.top/Article/details/gtlrsczmud.html

TypeScript ..... 212
来源：http://dali.snrcjt.cn/Article/details/gtuoucjmkd.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gtylyjesoa.html

Go ............. 212
来源：http://dali.dashuyun.cn/Article/details/gthdljeqhw.html

Ruby ........... 212
来源：http://dali.jqgufenzy.top/Article/details/gtswahrofa.html

C# ............. 212
来源：http://dali.cucudq.cn/Article/details/gtawbygkjj.html

C .............. 30
来源：http://dali.shangyingyoupin.top/Article/details/gtashtpepb.html

C++ ............ 30
来源：http://dali.yonumen.top/Article/details/gtyuuhkhob.html

SQL ............ 90
来源：http://dali.zycfv.cn/Article/details/gtdcufhlkr.html

Bash ........... 80
来源：http://dali.sweek.top/Article/details/gthtkdfndz.html

Kotlin ......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrdxvhil.html

Swift .......... 15
来源：http://dali.dashuyun.cn/Article/details/gtroezohei.html

Lua ............ 10
来源：http://dali.bjfxy.top/Article/details/gtkpimxxua.html

Perl ........... 10
来源：http://dali.yj20258888.top/Article/details/gtoxjbmraw.html

Scala .......... 10
来源：http://dali.feifeiyinyue.top/Article/details/gthscritld.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gtuvshbldd.html

合计 ........... 2106 条
来源：http://dali.pengpengdd.cyou/Article/details/gtisiviotr.html

按章节统计：
来源：http://dali.yonumen.top/Article/details/gtbnuzxmok.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gtrihzybxx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtaiighkzx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gthnnffzzz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gtpeylboeh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sufxvd.cn/Article/details/gtpgmeetvp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gtclrpkggt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtsbvtoqmy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtllhcfhkv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtnphruzaf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gtneovqtyc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtbvljmwbu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtlnjumitg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtzpfplqzo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gtkvtnaffl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.svipenyu.cn/Article/details/gtsuekjbyl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtmclvlzaa.html

Q SQL 专题                              90
来源：http://dali.yj20258888.top/Article/details/gtlsfyvfiy.html

R Bash 专题                             80
来源：http://dali.jiagoushi.top/Article/details/gtvbeucezw.html

S C / C++ 专题                          60
来源：http://dali.yangfankeji.com/Article/details/gtftmbyvdc.html

T 其他语言补充                          60
来源：http://dali.fengsongda.top/Article/details/gtclmdxnwv.html

U 高频实用片段                         120
来源：http://dali.zdqjudy.top/Article/details/gttxufqufi.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gtuzejejbx.html

合计                                  2106 条
来源：http://dali.9152youxi.cn/Article/details/gtilxljism.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gthpxqnark.html

使用提醒
来源：http://dali.yonumen.top/Article/details/gtpivjqnjq.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkucyhrpw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yueranfly.top/Article/details/gtwxspwhtn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.vqdsnc.cn/Article/details/gtdvxxcqun.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.smart0.xyz/Article/details/gtuvzmnlai.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.kuanghao11.cn/Article/details/gtqrosdxkz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ydzc1.top/Article/details/gtglfaholp.html

—— 文件结束 ——
来源：http://dali.hywenlv.cn/Article/details/gtikfspjwv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtyrnkkvps.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shangyingyoupin.top/Article/details/gtxwecucnc.html

Common Programming Examples Cheat Book
来源：http://dali.sweek.top/Article/details/gtrcuolszy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtlcaeneua.html

【收录内容】
来源：http://dali.xuanzx.com/Article/details/gtwzwhkszt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuetiantiany.cn/Article/details/gtbwcmrfif.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhengqikj.top/Article/details/gtywkrrvdl.html

SQL · Bash · C · C++
来源：http://dali.0kj1m.cn/Article/details/gtlhnytrmp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cdnleiting.top/Article/details/gtzfxqnzpo.html

【使用说明】
来源：http://dali.9152youxi.cn/Article/details/gtoottehjf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgfzy.top/Article/details/gtuphalldh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxuanxn.top/Article/details/gtulztgvxt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shuidangran.top/Article/details/gtqnrarmva.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.redwolf501.top/Article/details/gtywrjzuoz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.wangdashe.top/Article/details/gtladdqwoq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cdnleiting.top/Article/details/gtzwltpvyd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nwbrower.top/Article/details/gtugzlxivb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.guannengcc.top/Article/details/gtaimaetvj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.haohaochexian.top/Article/details/gtscpwamlo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yanxiufei.cn/Article/details/gtwdoypsyk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yangfankeji.com/Article/details/gtmseiglyk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.kuanghao11.cn/Article/details/gtqnztqtjw.html

【文件统计】
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncoaogdp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hnxiangtu.top/Article/details/gtdgwtvfpf.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtoyhzfdky.html

目  录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngttaugy.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtaxbavhot.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zycfv.cn/Article/details/gtljdwomzm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gtwuidlirx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gtvqwfmisv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbsoouje.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.pycfn.com/Article/details/gtmugblnlk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinqigufen.top/Article/details/gtolzrfity.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmkafeqx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xziqi.cn/Article/details/gtivfsneyu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtraivrjni.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gtxogsfuhp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtcgrksohq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtwnirrizc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtkzewahkg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guannengcc.top/Article/details/gtyrxchmmw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nwbrower.top/Article/details/gtsuysnkvx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjaowawv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258.top/Article/details/gtymlxzksn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqhvfesm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yongpay.top/Article/details/gtqhejvotv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gtfhhazfwb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gtgcbshwqb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfniujlge.html

A. 基础语法与类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvpjcqzz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbzwvwnam.html

[A01] Hello World
来源：http://dali.jiagoushi.top/Article/details/gthyrecuyf.html

Py:   print("Hello, World!")
来源：http://dali.aizwys.cn/Article/details/gtekagnhpu.html

PHP:  echo "Hello, World!";
来源：http://dali.aizwys.cn/Article/details/gtfgtbyrrw.html

JS:   console.log("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmgpxsna.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.quarkkingdee.top/Article/details/gtwxmpnebv.html

Java: System.out.println("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gthxnbirzl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gogol.net.cn/Article/details/gttcchnzkc.html

Ruby: puts "Hello, World!"
来源：http://dali.chenlongwang.top/Article/details/gtqihiiatq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtykanwmhw.html

[A02] 变量声明与赋值
来源：http://dali.chenzaomai.com/Article/details/gtyirvgfsz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hongshengwenyu.top/Article/details/gtpdfgnqnr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtfmshnrgd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yvedp.cn/Article/details/gtxorcpfyz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.dashuyun.cn/Article/details/gtoxbjetgg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yvedp.cn/Article/details/gtcxwmvbct.html

Go:   name := "Alex"; age := 20
来源：http://dali.tianlin.xyz/Article/details/gtavjrgicp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gotoacloud.top/Article/details/gtpmhcfblq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gtnelskfxi.html

[A03] 常量定义
来源：http://dali.shzxlz.cn/Article/details/gtnyvacoxb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.svipenyu.cn/Article/details/gtpwurwlqc.html

PHP:  const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtgkubdtjv.html

JS:   const PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtziyeeoaa.html

TS:   const PI: number = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtcgbbtmjj.html

Java: static final double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtlurjgspa.html

Go:   const PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gtlbhbizyc.html

Ruby: PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gtutyjnbyn.html

C#:   const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtfjqsfmog.html

[A04] 判断变量类型
来源：http://dali.tianlin.xyz/Article/details/gtvlhphzwo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwwcbjoj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj20258.top/Article/details/gtsesfcagx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.wangdashe.top/Article/details/gtdndfrlwi.html

TS:   typeof x; x instanceof Date
来源：http://dali.fengsongda.top/Article/details/gteuzryeej.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.c1oappe.top/Article/details/gtvxmaqqsw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daxiang520.top/Article/details/gthklfcqaa.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sweek.top/Article/details/gtubvksijv.html

C#:   x.GetType().Name; x is int
来源：http://dali.fzhhl.top/Article/details/gtewvuepxg.html

[A05] 整数除法与取模
来源：http://dali.guannengcc.top/Article/details/gtstltiitt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yonumen.top/Article/details/gtdxxrkxle.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtvnbmxijo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtsdgxkdai.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgggesbf.html

Java: 7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gtsnfahjgr.html

Go:   7 / 2; 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtpxrucgjb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gthbbwpwoi.html

C#:   7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtdwwmcysp.html

[A06] 字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gtdleiripj.html

Py:   int("42"); float("3.14")
来源：http://dali.yj20258.top/Article/details/gtvrwfefzk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yueranfly.top/Article/details/gtraxmphro.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hammf.cn/Article/details/gtpnuhorox.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gtkccvdnud.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.iojbl.cn/Article/details/gtpigyrran.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpozkylr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cqqwz.cn/Article/details/gtuvamwdnz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jianghu66.top/Article/details/gtdabnnhrd.html

[A07] 数字转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtehlydfdj.html

Py:   str(42)
来源：http://dali.jinqigufen.top/Article/details/gtaoklxjuv.html

PHP:  (string) 42; strval(42)
来源：http://dali.chenjidiqi.icu/Article/details/gtvqgpmzvh.html

JS:   String(42); (42).toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtgllyuhnj.html

TS:   String(42)
来源：http://dali.nanxuanxn.top/Article/details/gtiorpvndp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ydzc1.top/Article/details/gtbscycnna.html

Go:   strconv.Itoa(42)
来源：http://dali.ppjwa.cn/Article/details/gtvdslrnva.html

Ruby: 42.to_s
来源：http://dali.zhongyouzk.top/Article/details/gtkzdkrsna.html

C#:   42.ToString()
来源：http://dali.316326.xyz/Article/details/gtxswhsyus.html

[A08] 取整与四舍五入
来源：http://dali.xziqi.cn/Article/details/gtwbraxlmh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yangfankeji.com/Article/details/gtdxaorfeq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shzxlz.cn/Article/details/gtrfodmenn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtcbhigoqs.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhoulong.xyz/Article/details/gtdswcsbam.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtwtixfzwf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gtyavfamik.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.wangdashe.top/Article/details/gtzgvkegqx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gtdoiocoxb.html

[A09] 绝对值与最大最小值
来源：http://dali.redwolf501.top/Article/details/gtdugdieir.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtyocfdavk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtvblmihdw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtgjvfnnxq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtahrtzzjh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtrqmvdwfh.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ehwqpu.com/Article/details/gtrzimkwap.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.andypj.xyz/Article/details/gtkyyageum.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtwrlxvrkr.html

[A10] 生成随机数
来源：http://dali.smart0.xyz/Article/details/gtrtwxmuhc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.pycfn.com/Article/details/gtdfeelltv.html

PHP:  random_int(1, 100);
来源：http://dali.yongpay.top/Article/details/gtzatyckur.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shzxlz.cn/Article/details/gtbwjwkxox.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenzaomai.com/Article/details/gtvcnwsvoz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.meibo888.top/Article/details/gtvnoozzhn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ehwqpu.com/Article/details/gtdxzcixim.html

Ruby: rand(1..100)
来源：http://dali.jianghu66.top/Article/details/gtsaxrvfer.html

C#:   new Random().Next(1, 101)
来源：http://dali.xylfe.cn/Article/details/gtvyvydjzr.html

[A11] 条件表达式（三元）
来源：http://dali.meibo888.top/Article/details/gttqhvyuaa.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.meibo888.top/Article/details/gtfcngjdtv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gtmrcvgotd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtkrwueiht.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gtspnvyclg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtjgviikft.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gthralujqo.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtwkvfffya.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtulmhghsc.html

[A12] 字符串插值 / 格式化
来源：http://dali.0kj1m.cn/Article/details/gthgipfzeo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cdnleiting.top/Article/details/gtepeqbmbu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jlsjyb.cn/Article/details/gtcbonbhdq.html

JS:   `Hello, ${name}!`
来源：http://dali.aibaodan.cn/Article/details/gtphocjcsj.html

TS:   `Hello, ${name}!`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajgvvegj.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhoulong.xyz/Article/details/gtdhitiwjg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xziqi.cn/Article/details/gtlzrfjthg.html

Ruby: "Hello, #{name}!"
来源：http://dali.yonumen.top/Article/details/gtvuhwlgrx.html

C#:   $"Hello, {name}!"
来源：http://dali.iojbl.cn/Article/details/gtvtxvkcqq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.aibaodan.cn/Article/details/gtqgidzzhz.html

Py:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtijiyxtil.html

PHP:  "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gthkqdtlsn.html

JS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtknfqqlcy.html

TS:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtdnshgjvv.html

Java: "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtfsepplya.html

Go:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtzkntbvbf.html

Ruby: "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtwhevggxy.html

C#:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtslqwauib.html

[A14] 注释写法
来源：http://dali.hnqzz.top/Article/details/gtkdtjpkuh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.daxiang520.top/Article/details/gtxljhzqlg.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtguaoqqxe.html

JS:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gthbparufb.html

TS:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gtrlyhktcs.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gzhubu.top/Article/details/gtpkopnofn.html

Go:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtcqexljcu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shanyushiyangtech.top/Article/details/gttodpfcen.html

C#:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtojdrmjtj.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gtdobhiwvk.html

Py:   value = data or "默认值"
来源：http://dali.jiagoushi.top/Article/details/gtfebrwrjn.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gtcreebthb.html

JS:   const value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gtudxfokir.html

TS:   const value = data ?? "默认值";
来源：http://dali.gzhubu.top/Article/details/gtqbwoqsxz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zycfv.cn/Article/details/gtgrlxurbm.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhiwuduotai.top/Article/details/gtjhhwsrsf.html

Ruby: value = data || "默认值"
来源：http://dali.chenlongwang.top/Article/details/gtotwwvklm.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnyuquen.html

[A16] 真假值判断规则
来源：http://dali.mhx1999.top/Article/details/gtwpfynqmh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.fzhhl.top/Article/details/gtpzlocusb.html


<!-- 参考信息 -->