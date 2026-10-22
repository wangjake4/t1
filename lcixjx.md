代发 wailian999

[U87] JS：解构默认值
来源：http://dali.hnxiangtu.top/Article/details/gt2caegcdiy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxinkj.top/Article/details/gt2mfubccir.html

[U88] JS：对象展开合并
来源：http://dali.tian-w.cn/Article/details/gt2cacmscpz.html

{ ...a, ...b }
来源：http://dali.wangdashe.top/Article/details/gt2fuurrmlx.html

[U89] JS：数组去重
来源：http://dali.yvedp.cn/Article/details/gt2ukbgjyvk.html

[...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxgkdcdz.html

[U90] JS：数字数组排序
来源：http://dali.zdqjudy.top/Article/details/gt2ujkdsxcu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gt2idrzyvil.html

[U91] JS：对象键值遍历
来源：http://dali.svipenyu.cn/Article/details/gt2wpnzbzdx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yuanzhike.top/Article/details/gt2cvcvilsn.html

[U92] JS：深拷贝
来源：http://dali.cdnleiting.top/Article/details/gt2vfwpaktv.html

structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2qdfwwrkn.html

[U93] JS：模板字符串
来源：http://dali.9152youxi.cn/Article/details/gt2ojozycht.html

`共 ${n} 条`
来源：http://dali.meibo888.top/Article/details/gt2wtxqgyuo.html

[U94] JS：箭头函数
来源：http://dali.yanxiufei.cn/Article/details/gt2ssefwwnw.html

const double = x => x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gt2bvboaucn.html

[U95] JS：Promise 包装
来源：http://dali.jqgfzy.top/Article/details/gt2fexphapu.html

new Promise((resolve, reject) => {})
来源：http://dali.jlsjyb.cn/Article/details/gt2laiowzwd.html

[U96] JS：async/await 与异常
来源：http://dali.haohaochexian.top/Article/details/gt2ftllgxju.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gt2vrropcnk.html

[U97] JS：并发请求
来源：http://dali.zycfv.cn/Article/details/gt2fhcosche.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2ezirqpcj.html

[U98] JS：fetch 带 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbkzuvrd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgufenzy.top/Article/details/gt2hrxahstc.html

[U99] JS：事件监听
来源：http://dali.yj20258.top/Article/details/gt2jaylzuhi.html

el.addEventListener("click", e => {})
来源：http://dali.yonumen.top/Article/details/gt2hljtguni.html

[U100] JS：DOM 查询
来源：http://dali.yj202588.top/Article/details/gt2pjjrvbqk.html

document.querySelector(".item")
来源：http://dali.yuxming.cn/Article/details/gt2jlxvjyyb.html

[U101] JS：classList 操作
来源：http://dali.nanxinkj.top/Article/details/gt2kqlsulpq.html

el.classList.toggle("active")
来源：http://dali.jianghu66.top/Article/details/gt2spymoupd.html

[U102] JS：本地存储
来源：http://dali.zycfv.cn/Article/details/gt2ixrtkbaz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqqtpnne.html

[U103] JS：定时器
来源：http://dali.zhongyouzk.top/Article/details/gt2jtlftjln.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hysaishi.cn/Article/details/gt2uqoklfhn.html

[U104] JS：防抖
来源：http://dali.vqdsnc.cn/Article/details/gt2akofnwxh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gt2hdvlecqe.html

[U105] JS：节流
来源：http://dali.jinqigfzy.top/Article/details/gt2mkoposgc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258888.top/Article/details/gt2lphbhrsc.html

[U106] JS：日期格式化
来源：http://dali.jianghu66.top/Article/details/gt2nunehjrt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dianchejie.cn/Article/details/gt2dttyvvqs.html

[U107] JS：数字千分位
来源：http://dali.svipenyu.cn/Article/details/gt2fplpoiuh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gahbqgmk.html

[U108] JS：随机整数
来源：http://dali.ppjwa.cn/Article/details/gt2rvsbdyei.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.snrcjt.cn/Article/details/gt2aidnnfne.html

[U109] JS：数组分组
来源：http://dali.yanxiufei.cn/Article/details/gt2ypivlszr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gt2zxlmuyro.html

[U110] JS：数组分块
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdpsjmdm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.316326.xyz/Article/details/gt2klhetsfb.html

[U111] JS：对象转 Map
来源：http://dali.wangdashe.top/Article/details/gt2uexvuggj.html

new Map(Object.entries(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yylidfdy.html

[U112] JS：字符串补位
来源：http://dali.zhengqikj.top/Article/details/gt2mrxlxukm.html

"7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gt2fqwphfux.html

[U113] JS：正则替换全部
来源：http://dali.jyoumei.cn/Article/details/gt2igihwfqu.html

s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2jemegyhs.html

[U114] JS：JSON 深比较
来源：http://dali.0kj1m.cn/Article/details/gt2apjxmclm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gt2skizxnnu.html

[U115] JS：生成 UUID
来源：http://dali.mhx1999.top/Article/details/gt2dfcjuppk.html

crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gt2tsfubgty.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guannengcc.top/Article/details/gt2vkqhgfts.html

/** @param {string} name */ function f(name) {}
来源：http://dali.9152youxi.cn/Article/details/gt2endkdldu.html

[U117] JS：单元测试
来源：http://dali.yongpay.top/Article/details/gt2ijuwqpcc.html

npm i -D vitest;  npx vitest
来源：http://dali.sxryk.cn/Article/details/gt2qhfdkdzh.html

[U118] JS：开发服务器
来源：http://dali.nwbrower.top/Article/details/gt2cpjzcquv.html

npm i -D vite;  npx vite
来源：http://dali.redwolf501.top/Article/details/gt2yvsfhgyd.html

[U119] JS：生产构建
来源：http://dali.shzxlz.cn/Article/details/gt2ghehybal.html

npx vite build
来源：http://dali.shuidangran.top/Article/details/gt2yrvediod.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywmjclzo.html

import.meta.env.VITE_API_URL
来源：http://dali.havefunace.top/Article/details/gt2grdiobup.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ebpeeqdo.html

统计汇总
来源：http://dali.gogol.net.cn/Article/details/gt2odewzjid.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2pmikzfdo.html

按语言统计（条）：
来源：http://dali.zhixingplan.top/Article/details/gt2urzwpidf.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxjphrrg.html

PHP ............ 252
来源：http://dali.ydzc1.top/Article/details/gt2rjuggtom.html

JavaScript ..... 252
来源：http://dali.ehwqpu.com/Article/details/gt2cowwwmly.html

TypeScript ..... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xrbijatc.html

Java ........... 212
来源：http://dali.9152youxi.cn/Article/details/gt2kgszuoaa.html

Go ............. 212
来源：http://dali.jianghu66.top/Article/details/gt2kprfggme.html

Ruby ........... 212
来源：http://dali.quarkkingdee.top/Article/details/gt2ycbicxpq.html

C# ............. 212
来源：http://dali.smart0.xyz/Article/details/gt2kdyaqpbj.html

C .............. 30
来源：http://dali.shangyingyoupin.top/Article/details/gt2moeuinao.html

C++ ............ 30
来源：http://dali.yvedp.cn/Article/details/gt2fivyzfuu.html

SQL ............ 90
来源：http://dali.guowangkeji.top/Article/details/gt2jgpeogpe.html

Bash ........... 80
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbvzautq.html

Kotlin ......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixqimtmq.html

Swift .......... 15
来源：http://dali.sweek.top/Article/details/gt2vfcuxmdl.html

Lua ............ 10
来源：http://dali.zycfv.cn/Article/details/gt2qmlfezhx.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gt2rtstddtu.html

Scala .......... 10
来源：http://dali.yuxming.cn/Article/details/gt2uvrcvkyl.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gt2gkrzsnyk.html

合计 ........... 2106 条
来源：http://dali.hammf.cn/Article/details/gt2duavnbhb.html

按章节统计：
来源：http://dali.guannengcc.top/Article/details/gt2xxziouep.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.0kj1m.cn/Article/details/gt2ogubgqdq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gt2gbwmmzej.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gt2hlfeimnt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gt2nyurvkwe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gogol.net.cn/Article/details/gt2umodpndd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.feifeiyinyue.top/Article/details/gt2jglhqzvc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gt2qfoypwgt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.iojbl.cn/Article/details/gt2gzyapmqc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2gpqeomfu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.andypj.xyz/Article/details/gt2yjzlgsqy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gt2kyqqjayg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2csbpjowi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2jicnjitn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.meibo888.top/Article/details/gt2casykjou.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guowangkeji.top/Article/details/gt2wqhktqey.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhrohrey.html

Q SQL 专题                              90
来源：http://dali.fengsongda.top/Article/details/gt2muhuttnv.html

R Bash 专题                             80
来源：http://dali.9152youxi.cn/Article/details/gt2iaqvwbcb.html

S C / C++ 专题                          60
来源：http://dali.daxiang520.top/Article/details/gt2lrsoebdh.html

T 其他语言补充                          60
来源：http://dali.yonumen.top/Article/details/gt2wugvepvs.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaobewv.html

------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsoqdblf.html

合计                                  2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlzltius.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2kcgtvpnc.html

使用提醒
来源：http://dali.birdmap.top/Article/details/gt2sehisypk.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2unmgbktu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shzxlz.cn/Article/details/gt2zidctzyu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sweek.top/Article/details/gt2ovyvvohs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.316326.xyz/Article/details/gt2factddst.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmhfhqcn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuetiantiany.cn/Article/details/gt2eudzjmjt.html

—— 文件结束 ——
来源：http://dali.xuetiantiany.cn/Article/details/gt2pudyruqp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ijzsxlju.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gotoacloud.top/Article/details/gt2hqxpmqkx.html

Common Programming Examples Cheat Book
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lsryovcr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2hphxqykb.html

【收录内容】
来源：http://dali.yvedp.cn/Article/details/gt2lztzjbyn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jyoumei.cn/Article/details/gt2qxcljuwh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xylfe.cn/Article/details/gt2stlfaaix.html

SQL · Bash · C · C++
来源：http://dali.cqqwz.cn/Article/details/gt2zoxvofqf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.meibo888.top/Article/details/gt2torlgwod.html

【使用说明】
来源：http://dali.nwbrower.top/Article/details/gt2bcqxvzbz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.aizwys.cn/Article/details/gt2mmonvmhv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.birdmap.top/Article/details/gt2nqveufnl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.birdmap.top/Article/details/gt2bqxwzbmo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jlsjyb.cn/Article/details/gt2soglywtr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aibaodan.cn/Article/details/gt2jznodlhq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.c1oappe.top/Article/details/gt2ruqguyxr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shzxlz.cn/Article/details/gt2atedcdsv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.guannengcc.top/Article/details/gt2wxqreuvf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.aizwys.cn/Article/details/gt2fsbtelrq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hongshengwenyu.top/Article/details/gt2cyrepyea.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gogol.net.cn/Article/details/gt2trtdqywq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xinyue.icu/Article/details/gt2mvzhsxjz.html

【文件统计】
来源：http://dali.yvedp.cn/Article/details/gt2ohydtiik.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2adiwqcyt.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2suozeiuw.html

目  录
来源：http://dali.ydzc1.top/Article/details/gt2ozcbazgn.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2hukpjlbn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gt2iqhczfbt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fengsongda.top/Article/details/gt2zpuafleh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.redwolf501.top/Article/details/gt2miejxxfn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.dashuyun.cn/Article/details/gt2teleaswg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xuanzx.com/Article/details/gt2ldohdqtn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sufxvd.cn/Article/details/gt2xfoxlkwv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gt2prtnrwvi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aibaodan.cn/Article/details/gt2fdlbonnl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gt2hvuhzdok.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gt2wedcsstv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gt2mzpwluwf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gt2pyqrrbba.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gt2nwtwuiar.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yj202588.top/Article/details/gt2mlwsoheb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yangfankeji.com/Article/details/gt2knxgzrpa.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gt2mbbpbnqs.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zdqjudy.top/Article/details/gt2taiedlmk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2hopkuvyt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ppjwa.cn/Article/details/gt2jiszrsvm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gt2tvobcjwh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gt2hogrrhau.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2vyexjbdp.html

A. 基础语法与类型
来源：http://dali.jianghu66.top/Article/details/gt2yevozdcn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2hpoifdwi.html

[A01] Hello World
来源：http://dali.andypj.xyz/Article/details/gt2gvlozfwk.html

Py:   print("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfbcrojy.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxuanxn.top/Article/details/gt2ovnllimh.html

JS:   console.log("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gt2yhuirazw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gzhubu.top/Article/details/gt2gefqvhaj.html

Java: System.out.println("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gt2naokxotq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.fengsongda.top/Article/details/gt2saqmtpas.html

Ruby: puts "Hello, World!"
来源：http://dali.wangshuangyany.cn/Article/details/gt2lgxpsbxr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gt2mutqfbhu.html

[A02] 变量声明与赋值
来源：http://dali.yonumen.top/Article/details/gt2ffmodnlj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.wangdashe.top/Article/details/gt2smkzlefr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shzxlz.cn/Article/details/gt2stqgczvc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.fengsongda.top/Article/details/gt2sttrwbfl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iouthjib.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.wangdashe.top/Article/details/gt2qujumfxw.html

Go:   name := "Alex"; age := 20
来源：http://dali.sweek.top/Article/details/gt2dpcjaqhc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yvedp.cn/Article/details/gt2qeqoxxgn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.chenzaomai.com/Article/details/gt2kdbavrgq.html

[A03] 常量定义
来源：http://dali.jiagoushi.top/Article/details/gt2zlvgnzcr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cqqwz.cn/Article/details/gt2bdqtpxxz.html

PHP:  const PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2cumhibuw.html

JS:   const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2mazdjrkd.html

TS:   const PI: number = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2xhodkdhu.html

Java: static final double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2uiavzdpt.html

Go:   const PI = 3.14159
来源：http://dali.jlsjyb.cn/Article/details/gt2yuuseaxf.html

Ruby: PI = 3.14159
来源：http://dali.zhongyouzk.top/Article/details/gt2iidltrdi.html

C#:   const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2viwbffhy.html

[A04] 判断变量类型
来源：http://dali.andypj.xyz/Article/details/gt2slkztwde.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zycfv.cn/Article/details/gt2qtznaibf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hywenlv.cn/Article/details/gt2yfxfsciw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.haohaochexian.top/Article/details/gt2vuopksfc.html

TS:   typeof x; x instanceof Date
来源：http://dali.chenzaomai.com/Article/details/gt2ppqyrvtc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhengqikj.top/Article/details/gt2fyyyqfxm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.wangshuangyany.cn/Article/details/gt2blqvujzh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yangfankeji.com/Article/details/gt2khvyznlq.html

C#:   x.GetType().Name; x is int
来源：http://dali.gotoacloud.top/Article/details/gt2oqeaqszr.html

[A05] 整数除法与取模
来源：http://dali.shzxlz.cn/Article/details/gt2oqrcdixu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sufxvd.cn/Article/details/gt2qniwoors.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2rtwyytrd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzloyfmq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2wrlcwhug.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edursipv.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gt2lsiihdhg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gt2tizfecau.html

C#:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2izpojpsx.html

[A06] 字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gt2worxnfon.html

Py:   int("42"); float("3.14")
来源：http://dali.jiagoushi.top/Article/details/gt2jvcayfqm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhengqikj.top/Article/details/gt2gbzeqhcf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenlongwang.top/Article/details/gt2ghfqwvgz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shuidangran.top/Article/details/gt2bygoybdd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xylfe.cn/Article/details/gt2ucyerwuo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.9152youxi.cn/Article/details/gt2wkpoashu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daxiang520.top/Article/details/gt2kkwluzzn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258.top/Article/details/gt2zirsbdne.html

[A07] 数字转字符串
来源：http://dali.aizwys.cn/Article/details/gt2azoqfxoc.html

Py:   str(42)
来源：http://dali.gotoacloud.top/Article/details/gt2shyyuyqu.html

PHP:  (string) 42; strval(42)
来源：http://dali.yongpay.top/Article/details/gt2hchfjivx.html

JS:   String(42); (42).toString()
来源：http://dali.haohaochexian.top/Article/details/gt2rksuigbn.html

TS:   String(42)
来源：http://dali.nanxinkj.top/Article/details/gt2oqkrhnzw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egogmqyx.html

Go:   strconv.Itoa(42)
来源：http://dali.yuanzhike.top/Article/details/gt2zbmzlwsa.html

Ruby: 42.to_s
来源：http://dali.pengpengdd.cyou/Article/details/gt2icznifhs.html

C#:   42.ToString()
来源：http://dali.chenzaomai.com/Article/details/gt2rakmjyfj.html

[A08] 取整与四舍五入
来源：http://dali.hongshengwenyu.top/Article/details/gt2zkhxaqze.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gt2nldoamcx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuanzhike.top/Article/details/gt2ocysrbwz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gt2eigoseks.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uswfpcai.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gt2vfntdqse.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yonumen.top/Article/details/gt2mttkkfem.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.svipenyu.cn/Article/details/gt2knwwnlso.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gicodhpz.html

[A09] 绝对值与最大最小值
来源：http://dali.svipenyu.cn/Article/details/gt2nxwrcvnb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2kynwyysk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2wzsppazf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2asyxmowm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2lykyotaf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2qyetvucf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.wangdashe.top/Article/details/gt2qlzevesf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cashguo.top/Article/details/gt2shpbhoax.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gt2mqikfstg.html

[A10] 生成随机数
来源：http://dali.cucudq.cn/Article/details/gt2xpfapbek.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pafsjwvq.html

PHP:  random_int(1, 100);
来源：http://dali.0kj1m.cn/Article/details/gt2hpkbdxff.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hysaishi.cn/Article/details/gt2qoqrbetx.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.svipenyu.cn/Article/details/gt2qkckcynw.html

Java: new Random().nextInt(100) + 1
来源：http://dali.aibaodan.cn/Article/details/gt2vdkoeggt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xinyue.icu/Article/details/gt2xbqyljqx.html

Ruby: rand(1..100)
来源：http://dali.yuanzhike.top/Article/details/gt2qooztyap.html

C#:   new Random().Next(1, 101)
来源：http://dali.ppjwa.cn/Article/details/gt2ooitwdzv.html

[A11] 条件表达式（三元）
来源：http://dali.pengpengdd.cyou/Article/details/gt2bfxxedoo.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hywenlv.cn/Article/details/gt2octixlpg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gt2ujvvierz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gt2irckrmsh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gt2kcrmbetq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gt2mixuhaxz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.andypj.xyz/Article/details/gt2gtlgvokn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gt2mafhbjkq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gt2kghnjwma.html

[A12] 字符串插值 / 格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2qebfezuq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gaohongyu789.top/Article/details/gt2fynsywtl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.316326.xyz/Article/details/gt2fjuqhohs.html

JS:   `Hello, ${name}!`
来源：http://dali.mhx1999.top/Article/details/gt2qckcbfhl.html

TS:   `Hello, ${name}!`
来源：http://dali.snrcjt.cn/Article/details/gt2ipchdlhv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gaohongyu789.top/Article/details/gt2umjbrghe.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2brjrnpbj.html

Ruby: "Hello, #{name}!"
来源：http://dali.guowangkeji.top/Article/details/gt2kgfspldg.html

C#:   $"Hello, {name}!"
来源：http://dali.bjfxy.top/Article/details/gt2ruyzkpie.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sufxvd.cn/Article/details/gt2cvyjvedu.html

Py:   "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gt2jhttcewf.html

PHP:  "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gt2beiikzug.html

JS:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gt2uilhsaae.html

TS:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2foqxgprv.html

Java: "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gt2brbjdzbd.html

Go:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gt2vtkvwdig.html

Ruby: "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gt2tjqqrzwu.html

C#:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gt2szcgpesn.html

[A14] 注释写法
来源：http://dali.meibo888.top/Article/details/gt2earqpele.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.chenzaomai.com/Article/details/gt2utusmrso.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxlbooqv.html

JS:   // 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gt2jwzmcndn.html

TS:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gt2tkcdllcc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hywenlv.cn/Article/details/gt2tjuvknnj.html

Go:   // 单行；/* 多行 */
来源：http://dali.jqgufenzy.top/Article/details/gt2llmibvir.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.redwolf501.top/Article/details/gt2xomaztgx.html


<!-- 参考信息 -->