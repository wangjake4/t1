代发 wailian999

[U89] JS：数组去重
来源：http://dali.hnxiangtu.top/Article/details/gtwnxkanqw.html

[...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtlfwjaqor.html

[U90] JS：数字数组排序
来源：http://dali.zhengqikj.top/Article/details/gtdazucuaj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtlvsaidxg.html

[U91] JS：对象键值遍历
来源：http://dali.ydzc1.top/Article/details/gtnlyglbxd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jianghu66.top/Article/details/gtpmhxfqzh.html

[U92] JS：深拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcvuwnfz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtjrddjwub.html

[U93] JS：模板字符串
来源：http://dali.kuanghao11.cn/Article/details/gtmsmqdojk.html

`共 ${n} 条`
来源：http://dali.jqgfzy.top/Article/details/gtjwkjhpnn.html

[U94] JS：箭头函数
来源：http://dali.sxryk.cn/Article/details/gtpjdgcbpy.html

const double = x => x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtowaheqds.html

[U95] JS：Promise 包装
来源：http://dali.tian-w.cn/Article/details/gtkcyuwdgj.html

new Promise((resolve, reject) => {})
来源：http://dali.havefunace.top/Article/details/gtixjmxjgm.html

[U96] JS：async/await 与异常
来源：http://dali.ydzc1.top/Article/details/gtosepfqpq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtondyfcdl.html

[U97] JS：并发请求
来源：http://dali.pengpengdd.cyou/Article/details/gtlwrroqgw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtrgjepttz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtzyikmklv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.feifeiyinyue.top/Article/details/gtoicupwof.html

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gtibusfgmb.html

el.addEventListener("click", e => {})
来源：http://dali.xinyue.icu/Article/details/gtkyzfptqc.html

[U100] JS：DOM 查询
来源：http://dali.redwolf501.top/Article/details/gtxyoutaiv.html

document.querySelector(".item")
来源：http://dali.xuetiantiany.cn/Article/details/gtbjbvupjl.html

[U101] JS：classList 操作
来源：http://dali.0kj1m.cn/Article/details/gtfhmfxwtd.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzycqrou.html

[U102] JS：本地存储
来源：http://dali.wangdashe.top/Article/details/gtlxgkbmbd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tian-w.cn/Article/details/gtnxmjxpbf.html

[U103] JS：定时器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkqgpnhb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.iojbl.cn/Article/details/gtrhipqany.html

[U104] JS：防抖
来源：http://dali.aibaodan.cn/Article/details/gtvvedurle.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtegjvwnhm.html

[U105] JS：节流
来源：http://dali.sxryk.cn/Article/details/gttribmniu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gtnqgkicwx.html

[U106] JS：日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtjmovcifw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cashguo.top/Article/details/gtjrkwrcnv.html

[U107] JS：数字千分位
来源：http://dali.yonumen.top/Article/details/gtcrxkljqz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gtltljpums.html

[U108] JS：随机整数
来源：http://dali.xinyue.icu/Article/details/gtzigukyne.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sxryk.cn/Article/details/gttojhzoef.html

[U109] JS：数组分组
来源：http://dali.chenzaomai.com/Article/details/gtsgzcjsbl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtdqqlseeb.html

[U110] JS：数组分块
来源：http://dali.9152youxi.cn/Article/details/gtelpusquq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yueranfly.top/Article/details/gtycbroygd.html

[U111] JS：对象转 Map
来源：http://dali.yangfankeji.com/Article/details/gtvygnzjtz.html

new Map(Object.entries(obj))
来源：http://dali.pycfn.com/Article/details/gtopkomqnm.html

[U112] JS：字符串补位
来源：http://dali.jlsjyb.cn/Article/details/gtacoovkth.html

"7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gteovjmswy.html

[U113] JS：正则替换全部
来源：http://dali.iojbl.cn/Article/details/gtkdwvrqvx.html

s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtobldaxzw.html

[U114] JS：JSON 深比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaplzsyr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtflqdcfhn.html

[U115] JS：生成 UUID
来源：http://dali.shzxlz.cn/Article/details/gtecgxoqhv.html

crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdmbdyqj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gotoacloud.top/Article/details/gtypxphpxj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ehwqpu.com/Article/details/gtbofyixcd.html

[U117] JS：单元测试
来源：http://dali.mhx1999.top/Article/details/gterawizfp.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxuanxn.top/Article/details/gtzyttlkvv.html

[U118] JS：开发服务器
来源：http://dali.daxiang520.top/Article/details/gttoggtcgo.html

npm i -D vite;  npx vite
来源：http://dali.sweek.top/Article/details/gtgywzejlm.html

[U119] JS：生产构建
来源：http://dali.yvedp.cn/Article/details/gtbasqajlx.html

npx vite build
来源：http://dali.mhx1999.top/Article/details/gtouzpjvfo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenzaomai.com/Article/details/gtwymoeqvt.html

import.meta.env.VITE_API_URL
来源：http://dali.yanxiufei.cn/Article/details/gtikyxemvk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmrxryyq.html

统计汇总
来源：http://dali.shangyingyoupin.top/Article/details/gtpxceijgt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtaekqhnys.html

按语言统计（条）：
来源：http://dali.xuanzx.com/Article/details/gtfdmxjmgi.html

Python ......... 252
来源：http://dali.ybcxt.top/Article/details/gtabxygxql.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdlwvugx.html

JavaScript ..... 252
来源：http://dali.xylfe.cn/Article/details/gthkgpefme.html

TypeScript ..... 212
来源：http://dali.fzhhl.top/Article/details/gtnrqimjwd.html

Java ........... 212
来源：http://dali.ivvv.top/Article/details/gtsrfdznen.html

Go ............. 212
来源：http://dali.guannengcc.top/Article/details/gtkufqsuir.html

Ruby ........... 212
来源：http://dali.yj20258888.top/Article/details/gtkiyvlfer.html

C# ............. 212
来源：http://dali.xylfe.cn/Article/details/gthcgpdoep.html

C .............. 30
来源：http://dali.c1oappe.top/Article/details/gtsmpupapk.html

C++ ............ 30
来源：http://dali.jlsjyb.cn/Article/details/gtykryyxqe.html

SQL ............ 90
来源：http://dali.hnqzz.top/Article/details/gttilryeat.html

Bash ........... 80
来源：http://dali.yanxiufei.cn/Article/details/gtgfkjzzac.html

Kotlin ......... 15
来源：http://dali.iojbl.cn/Article/details/gtzgqpshnu.html

Swift .......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gtjsxlvogr.html

Lua ............ 10
来源：http://dali.jqgfzy.top/Article/details/gtwkwxiamk.html

Perl ........... 10
来源：http://dali.gogol.net.cn/Article/details/gtwakwhwql.html

Scala .......... 10
来源：http://dali.snrcjt.cn/Article/details/gtueytlqjj.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtrqqazpem.html

合计 ........... 2106 条
来源：http://dali.9152youxi.cn/Article/details/gtfmapibyh.html

按章节统计：
来源：http://dali.nanxinkj.top/Article/details/gtdfpxxvws.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gttmrkkyys.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtwfumsukm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtrlntqd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.snrcjt.cn/Article/details/gtyzaffmtq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cqqwz.cn/Article/details/gtrxpgbdbl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gtsmrywrgl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gticuuqrwj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gtcmlgbfwa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtqkzjspwc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gtvkhnmvac.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtrjkdbchy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtmwiurfmr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtokeprrwg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhengqikj.top/Article/details/gtcavmrare.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yonumen.top/Article/details/gtavwpettr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtrkboneoc.html

Q SQL 专题                              90
来源：http://dali.bjfxy.top/Article/details/gtvrahamml.html

R Bash 专题                             80
来源：http://dali.gogol.net.cn/Article/details/gtdhwvoyou.html

S C / C++ 专题                          60
来源：http://dali.jlsjyb.cn/Article/details/gtabpgfaxj.html

T 其他语言补充                          60
来源：http://dali.zhongyouzk.top/Article/details/gtbnhnvybr.html

U 高频实用片段                         120
来源：http://dali.snrcjt.cn/Article/details/gteubnbyne.html

------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqeyerauh.html

合计                                  2106 条
来源：http://dali.zhengqikj.top/Article/details/gtyclegkmt.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtliedafzm.html

使用提醒
来源：http://dali.hysaishi.cn/Article/details/gtnfjbxjef.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtcdkaduet.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxmftfpz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.wangdashe.top/Article/details/gtuemvzgvs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gotoacloud.top/Article/details/gtcqmpayhu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ydzc1.top/Article/details/gtgcvnpqqw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbsdfzdx.html

—— 文件结束 ——
来源：http://dali.xinyue.icu/Article/details/gtflhgolbl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtirqvzkpt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zycfv.cn/Article/details/gthlwsivxj.html

Common Programming Examples Cheat Book
来源：http://dali.nwbrower.top/Article/details/gtnornnpkv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrwnkhage.html

【收录内容】
来源：http://dali.ybcxt.top/Article/details/gtwhbmzxyq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xinyue.icu/Article/details/gtvjaqynym.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sweek.top/Article/details/gtabtkseyj.html

SQL · Bash · C · C++
来源：http://dali.zhoulong.xyz/Article/details/gtfknqlxzk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yueranfly.top/Article/details/gtmuidezff.html

【使用说明】
来源：http://dali.jinqigfzy.top/Article/details/gtddajxifs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nwbrower.top/Article/details/gtbjzjajla.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxinkj.top/Article/details/gtbpwtkola.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpjzdjbb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxuanxn.top/Article/details/gtmcbszwed.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.pycfn.com/Article/details/gtpemdjpfj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hongshengwenyu.top/Article/details/gttfdujqtx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnqzz.top/Article/details/gtorawuenj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yonumen.top/Article/details/gtmusiwhfq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenjidiqi.icu/Article/details/gtvuxttriu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hfpthk.cn/Article/details/gtqvctrziv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.fengsongda.top/Article/details/gtiqfjibos.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xuetiantiany.cn/Article/details/gttndrthfm.html

【文件统计】
来源：http://dali.shangyingyoupin.top/Article/details/gtzotogfng.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.redwolf501.top/Article/details/gtixhjcdua.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtvwcmkoul.html

目  录
来源：http://dali.snrcjt.cn/Article/details/gtwqukbhml.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtdkauymuj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xuanzx.com/Article/details/gthhplctcy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gtluptftwk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gtpxkbusug.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jqgfzy.top/Article/details/gtgbjqyqcc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.havefunace.top/Article/details/gtpaqpubue.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxuanxn.top/Article/details/gtxrdkogrk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tianlin.xyz/Article/details/gtqtgpyaup.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xziqi.cn/Article/details/gtradyjuxp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtlxuidviv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jiagoushi.top/Article/details/gtkrrlemer.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtjvfpsken.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtbqdmmxsp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtolqlymsi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gtjvjwjozb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtimcpwyri.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gttyxbslat.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yueranfly.top/Article/details/gttceybwht.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yongpay.top/Article/details/gtczxftbwt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.vqdsnc.cn/Article/details/gtfibgvtnn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtlthlxdiz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gthirzjbcv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtevpishhx.html

A. 基础语法与类型
来源：http://dali.xuanzx.com/Article/details/gtqnrzxrgg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtcwqwzfwl.html

[A01] Hello World
来源：http://dali.meibo888.top/Article/details/gtcuxgqywl.html

Py:   print("Hello, World!")
来源：http://dali.ydzc1.top/Article/details/gtyykyqziy.html

PHP:  echo "Hello, World!";
来源：http://dali.yueranfly.top/Article/details/gttysuckcg.html

JS:   console.log("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gtqbrtwkur.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zycfv.cn/Article/details/gtwxowsijo.html

Java: System.out.println("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gtmkpdpakq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtutkkleqt.html

Ruby: puts "Hello, World!"
来源：http://dali.bjfxy.top/Article/details/gtumfyepvz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gtiuibsujw.html

[A02] 变量声明与赋值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthbwscac.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.dianchejie.cn/Article/details/gteshdgwza.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyeiclzor.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.birdmap.top/Article/details/gtfexthfmu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtveqfirfj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.fzhhl.top/Article/details/gtrplybfgy.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenjidiqi.icu/Article/details/gtpyylwsgh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shuidangran.top/Article/details/gtgqjnawxj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.daria6918.cn/Article/details/gtqkjdgfih.html

[A03] 常量定义
来源：http://dali.yonumen.top/Article/details/gtiraovghy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hysaishi.cn/Article/details/gtxmqdfdwh.html

PHP:  const PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gteaogeycq.html

JS:   const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtjemzqxhs.html

TS:   const PI: number = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtrcwxzszs.html

Java: static final double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtcpkmixlt.html

Go:   const PI = 3.14159
来源：http://dali.c1oappe.top/Article/details/gtztdcbxdw.html

Ruby: PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gteojngmgh.html

C#:   const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtlzevfgpf.html

[A04] 判断变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvcjguco.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigfzy.top/Article/details/gtsiskvead.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj202588.top/Article/details/gtzrrbwgxz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.aibaodan.cn/Article/details/gtmfttsubs.html

TS:   typeof x; x instanceof Date
来源：http://dali.xylfe.cn/Article/details/gtqorbwkpw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ehwqpu.com/Article/details/gtwfhusmpp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cheryme.top/Article/details/gtyvmvzwjy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hammf.cn/Article/details/gthalwzael.html

C#:   x.GetType().Name; x is int
来源：http://dali.cheryme.top/Article/details/gtmkggbdlz.html

[A05] 整数除法与取模
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxidqoqr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gaohongyu789.top/Article/details/gtuitqhwfk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gtpvqqztit.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtgaegbfso.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtpiecwpes.html

Java: 7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtirtxpqer.html

Go:   7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gtejbwltkl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtgmcnrtrs.html

C#:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtqowpumui.html

[A06] 字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gtaunnqkcr.html

Py:   int("42"); float("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtoducgwkm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.guannengcc.top/Article/details/gtqqplovyw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.fzhhl.top/Article/details/gtiaisiwfs.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nanxinkj.top/Article/details/gtuuspfcje.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj20258.top/Article/details/gtowqsuvdk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ppjwa.cn/Article/details/gtystqvsrv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.vqdsnc.cn/Article/details/gthccxzxkw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenzaomai.com/Article/details/gtomartpko.html

[A07] 数字转字符串
来源：http://dali.tian-w.cn/Article/details/gtzqjwfwqf.html

Py:   str(42)
来源：http://dali.hysaishi.cn/Article/details/gtlidmtcfu.html

PHP:  (string) 42; strval(42)
来源：http://dali.yongpay.top/Article/details/gtuuhimvun.html

JS:   String(42); (42).toString()
来源：http://dali.gogol.net.cn/Article/details/gtxhynxqtg.html

TS:   String(42)
来源：http://dali.ydzc1.top/Article/details/gtsgqrexhp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhengqikj.top/Article/details/gtdimytqyd.html

Go:   strconv.Itoa(42)
来源：http://dali.hysaishi.cn/Article/details/gtaiemlhkh.html

Ruby: 42.to_s
来源：http://dali.yonumen.top/Article/details/gtojuklinf.html

C#:   42.ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyagcrcom.html

[A08] 取整与四舍五入
来源：http://dali.birdmap.top/Article/details/gtdzlcjbhh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gtnyrogzzg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jqgfzy.top/Article/details/gtuxvdolhc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccbutyfl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.pycfn.com/Article/details/gtoqpghsiq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtxpjnfjir.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.haohaochexian.top/Article/details/gtvmwunbvq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.guowangkeji.top/Article/details/gtyzrttaxd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtackrvrbf.html

[A09] 绝对值与最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjiodllt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtcvlvdmae.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiywlobwb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtdrkrsdcv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtdippgibl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtmqjbzrzv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.feifeiyinyue.top/Article/details/gtbrfeanrs.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.0kj1m.cn/Article/details/gtwvpozroz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtlvoikhqs.html

[A10] 生成随机数
来源：http://dali.jlsjyb.cn/Article/details/gtnkfyhimj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sysykeji.top/Article/details/gtgdfgfymk.html

PHP:  random_int(1, 100);
来源：http://dali.haohaochexian.top/Article/details/gtnlvjnrcg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nwbrower.top/Article/details/gtddfnjbwm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj202588.top/Article/details/gtopecqdyn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cheryme.top/Article/details/gtkmvavlna.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jiagoushi.top/Article/details/gtwqimidsq.html

Ruby: rand(1..100)
来源：http://dali.yuanzhike.top/Article/details/gtvzqcljbb.html

C#:   new Random().Next(1, 101)
来源：http://dali.nwbrower.top/Article/details/gtkyjjyjsb.html

[A11] 条件表达式（三元）
来源：http://dali.vqdsnc.cn/Article/details/gtavooosrz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jianghu66.top/Article/details/gtgywoidnj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ppjwa.cn/Article/details/gtpsvlrveh.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtqrpfvyus.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtpxakhtyi.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gticyhhthc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuginfar.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gtdcwlglmh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqwzhxie.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhongyouzk.top/Article/details/gtwxuaflbf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shuidangran.top/Article/details/gtqkajvdyx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sweek.top/Article/details/gtcasxpsez.html

JS:   `Hello, ${name}!`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmknfzog.html

TS:   `Hello, ${name}!`
来源：http://dali.shzxlz.cn/Article/details/gthockzvwo.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sweek.top/Article/details/gtilhbfhis.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shzxlz.cn/Article/details/gtihkvgdxf.html

Ruby: "Hello, #{name}!"
来源：http://dali.yj20258888.top/Article/details/gtvsfykaur.html

C#:   $"Hello, {name}!"
来源：http://dali.yueranfly.top/Article/details/gtyfoxoshe.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.meibo888.top/Article/details/gtkngqqoqi.html

Py:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtmemibakz.html

PHP:  "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gtqgeljbor.html

JS:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtpmeuceqq.html

TS:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtrxkdzpod.html

Java: "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtzjikneri.html

Go:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtpfbljryn.html

Ruby: "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtqfxamdje.html

C#:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtoydfelqm.html

[A14] 注释写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppdzjdlg.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hywenlv.cn/Article/details/gtgzvoukuw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gtlwhzbspu.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuubzwdo.html

TS:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjvlbqyv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gzhubu.top/Article/details/gtbvvcvcyh.html

Go:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gthlpbxifc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cqqwz.cn/Article/details/gtxcbmsdmf.html

C#:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtrnusuwqu.html

[A15] 空值判断与默认值
来源：http://dali.redwolf501.top/Article/details/gtbwuldsxx.html

Py:   value = data or "默认值"
来源：http://dali.daria6918.cn/Article/details/gttbumdykx.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zdqjudy.top/Article/details/gtcrepchwf.html


<!-- 参考信息 -->