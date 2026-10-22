代发 wailian999

[U89] JS：数组去重
来源：http://dali.ehwqpu.com/Article/details/gt2angjfhdt.html

[...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gt2gsheohjd.html

[U90] JS：数字数组排序
来源：http://dali.sweek.top/Article/details/gt2cjkojazm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2rrdyimix.html

[U91] JS：对象键值遍历
来源：http://dali.wangdashe.top/Article/details/gt2bseqgskm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jqgfzy.top/Article/details/gt2kmxefqvo.html

[U92] JS：深拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2dzysdsll.html

structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gt2nlqgvoeo.html

[U93] JS：模板字符串
来源：http://dali.tanke756.top/Article/details/gt2vsbpckeg.html

`共 ${n} 条`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dxometgn.html

[U94] JS：箭头函数
来源：http://dali.tian-w.cn/Article/details/gt2qzubyznj.html

const double = x => x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gt2ydrfemzl.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qydrudyz.html

new Promise((resolve, reject) => {})
来源：http://dali.jinqigufen.top/Article/details/gt2tktgwook.html

[U96] JS：async/await 与异常
来源：http://dali.aizwys.cn/Article/details/gt2gycolamz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gt2oaxsgqkz.html

[U97] JS：并发请求
来源：http://dali.tian-w.cn/Article/details/gt2hghlultl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2ozrrmvcj.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmvvhmrx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgufenzy.top/Article/details/gt2elnqhndx.html

[U99] JS：事件监听
来源：http://dali.dianchejie.cn/Article/details/gt2aaprcbpu.html

el.addEventListener("click", e => {})
来源：http://dali.tian-w.cn/Article/details/gt2xteenuuv.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2akzjawgj.html

document.querySelector(".item")
来源：http://dali.ydzc1.top/Article/details/gt2qxdmhdkw.html

[U101] JS：classList 操作
来源：http://dali.xylfe.cn/Article/details/gt2pzlqxpww.html

el.classList.toggle("active")
来源：http://dali.nwbrower.top/Article/details/gt2rvhtrnmg.html

[U102] JS：本地存储
来源：http://dali.ppjwa.cn/Article/details/gt2gfmgvzvg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2avqnwnnz.html

[U103] JS：定时器
来源：http://dali.birdmap.top/Article/details/gt2ravlcmfv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hongshengwenyu.top/Article/details/gt2luzsamtl.html

[U104] JS：防抖
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iuuxfvia.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gt2uhfozsfb.html

[U105] JS：节流
来源：http://dali.cashguo.top/Article/details/gt2pechrptl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ehwqpu.com/Article/details/gt2qtzwzkgi.html

[U106] JS：日期格式化
来源：http://dali.iojbl.cn/Article/details/gt2auzywzwe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fengsongda.top/Article/details/gt2fuiiljvi.html

[U107] JS：数字千分位
来源：http://dali.xziqi.cn/Article/details/gt2ytppyucv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gt2gbzvhvuo.html

[U108] JS：随机整数
来源：http://dali.zhengqikj.top/Article/details/gt2mcvnwbdu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmafltft.html

[U109] JS：数组分组
来源：http://dali.tianlin.xyz/Article/details/gt2nfvkftfj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gt2nzbigyhl.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwgrtiiu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.kuanghao11.cn/Article/details/gt2tgoyzydx.html

[U111] JS：对象转 Map
来源：http://dali.sufxvd.cn/Article/details/gt2cvgurete.html

new Map(Object.entries(obj))
来源：http://dali.cucudq.cn/Article/details/gt2nllpkyki.html

[U112] JS：字符串补位
来源：http://dali.jqgufenzy.top/Article/details/gt2lsezqnre.html

"7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2mnafgjjh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfngbpa.html

s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2qikpmfgt.html

[U114] JS：JSON 深比较
来源：http://dali.kuanghao11.cn/Article/details/gt2ekxgbgyz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gt2oyqutqxh.html

[U115] JS：生成 UUID
来源：http://dali.xziqi.cn/Article/details/gt2cdviicnl.html

crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gt2tiiawxci.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2eltxlssz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sysykeji.top/Article/details/gt2ihdpfmyn.html

[U117] JS：单元测试
来源：http://dali.quarkkingdee.top/Article/details/gt2kiwuifki.html

npm i -D vitest;  npx vitest
来源：http://dali.mhx1999.top/Article/details/gt2cbwixijg.html

[U118] JS：开发服务器
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpwckczq.html

npm i -D vite;  npx vite
来源：http://dali.sufxvd.cn/Article/details/gt2uexsjkue.html

[U119] JS：生产构建
来源：http://dali.sxryk.cn/Article/details/gt2zpadjpsr.html

npx vite build
来源：http://dali.zhongyouzk.top/Article/details/gt2erjaozpd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hywenlv.cn/Article/details/gt2jtjtyrlu.html

import.meta.env.VITE_API_URL
来源：http://dali.zycfv.cn/Article/details/gt2hjvbgnbn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2luagmidc.html

统计汇总
来源：http://dali.gotoacloud.top/Article/details/gt2oasqkwfc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2jjrwlefk.html

按语言统计（条）：
来源：http://dali.chenlongwang.top/Article/details/gt2lmkexotb.html

Python ......... 252
来源：http://dali.jlsjyb.cn/Article/details/gt2lhhmleba.html

PHP ............ 252
来源：http://dali.sufxvd.cn/Article/details/gt2kfmkmhoh.html

JavaScript ..... 252
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlgecbbh.html

TypeScript ..... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbvdtraa.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gt2zygfrorz.html

Go ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvqmxeyu.html

Ruby ........... 212
来源：http://dali.9152youxi.cn/Article/details/gt2eaioscfw.html

C# ............. 212
来源：http://dali.yj202588.top/Article/details/gt2epskdpah.html

C .............. 30
来源：http://dali.sysykeji.top/Article/details/gt2yeoouhmz.html

C++ ............ 30
来源：http://dali.bjfxy.top/Article/details/gt2gbqmzcxt.html

SQL ............ 90
来源：http://dali.daria6918.cn/Article/details/gt2mrhqaeuu.html

Bash ........... 80
来源：http://dali.xuetiantiany.cn/Article/details/gt2modhbqmz.html

Kotlin ......... 15
来源：http://dali.zhongyouzk.top/Article/details/gt2nbuwfzse.html

Swift .......... 15
来源：http://dali.jiagoushi.top/Article/details/gt2mjjdxhpe.html

Lua ............ 10
来源：http://dali.jinqigfzy.top/Article/details/gt2bzfbhbmr.html

Perl ........... 10
来源：http://dali.yueranfly.top/Article/details/gt2xxpxxzhj.html

Scala .......... 10
来源：http://dali.cqqwz.cn/Article/details/gt2joghxvon.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gt2nrnlmqoz.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvmwtxmb.html

按章节统计：
来源：http://dali.sysykeji.top/Article/details/gt2uwxadztu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hywenlv.cn/Article/details/gt2yvecbwdq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gt2umwdqqnh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gt2pjgglzoi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gt2kisykrfh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sufxvd.cn/Article/details/gt2mzseokum.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gt2mzemrdgb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gt2cbmcowht.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.haohaochexian.top/Article/details/gt2bawibxiz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gt2oitiilia.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gt2wmhwhene.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gt2udrggznn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gt2wvxvclto.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gt2hlxxbydu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gt2bclxkjrw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xuetiantiany.cn/Article/details/gt2puvpbtpv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gt2oghtvxoe.html

Q SQL 专题                              90
来源：http://dali.mhx1999.top/Article/details/gt2ieekwodj.html

R Bash 专题                             80
来源：http://dali.yanxiufei.cn/Article/details/gt2vskmbxsh.html

S C / C++ 专题                          60
来源：http://dali.svipenyu.cn/Article/details/gt2oanwpaae.html

T 其他语言补充                          60
来源：http://dali.ehwqpu.com/Article/details/gt2nviozvra.html

U 高频实用片段                         120
来源：http://dali.shuidangran.top/Article/details/gt2liesyhyy.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2zevbbkda.html

合计                                  2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2qanhbokl.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2qeforkik.html

使用提醒
来源：http://dali.fzhhl.top/Article/details/gt2udjhloom.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkuecvpa.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cashguo.top/Article/details/gt2ffgoyamx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhoulong.xyz/Article/details/gt2fnrqgooe.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuanzx.com/Article/details/gt2zrnkvgem.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgfzy.top/Article/details/gt2qguqgivj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.dashuyun.cn/Article/details/gt2dlansamw.html

—— 文件结束 ——
来源：http://dali.nanxuanxn.top/Article/details/gt2jllhvhnn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2jqebnjne.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euricias.html

Common Programming Examples Cheat Book
来源：http://dali.xziqi.cn/Article/details/gt2cnqxhpel.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2tclqzgur.html

【收录内容】
来源：http://dali.c1oappe.top/Article/details/gt2uywpgupj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ivvv.top/Article/details/gt2hqjxyzlj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wtqzhfnq.html

SQL · Bash · C · C++
来源：http://dali.zhixingplan.top/Article/details/gt2rlyjcuot.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hefbhxym.html

【使用说明】
来源：http://dali.zhixingplan.top/Article/details/gt2ytdxowyz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cheryme.top/Article/details/gt2swcchoht.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.mhx1999.top/Article/details/gt2pttxtofu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgfzy.top/Article/details/gt2cjccrkcq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.snrcjt.cn/Article/details/gt2elemukbv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj202588.top/Article/details/gt2zdaqmtof.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuanzx.com/Article/details/gt2oqstrxsl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.dashuyun.cn/Article/details/gt2kuimpmpe.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.kuanghao11.cn/Article/details/gt2dswjdzsk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.birdmap.top/Article/details/gt2ptkxvdwv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcttymni.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yongpay.top/Article/details/gt2cjxsyjkc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.havefunace.top/Article/details/gt2yqsvzgvg.html

【文件统计】
来源：http://dali.chenjidiqi.icu/Article/details/gt2bshwmbvv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xinyue.icu/Article/details/gt2pabfaalk.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gt2neqlpxfs.html

目  录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwhhoghe.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlldgypy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gotoacloud.top/Article/details/gt2cwrtqnwm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gt2whqnzujz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhixingplan.top/Article/details/gt2cqahuggt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zdqjudy.top/Article/details/gt2onjnwnnc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yvedp.cn/Article/details/gt2euotjmwd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jyoumei.cn/Article/details/gt2fxoumjhl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gt2dnujvjzv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipdttonh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gt2nrnnqqbg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gt2dybuattb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gt2angldbaq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gt2jjkgzjnl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gt2lhuwsuvn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gt2qxsxbmys.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cheryme.top/Article/details/gt2dqxxpjzc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gt2qsideavw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hopfhmnk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dobehxfo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxgcedoi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gt2jrjrzpmn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gt2lblhxeqi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2dllxleyt.html

A. 基础语法与类型
来源：http://dali.aibaodan.cn/Article/details/gt2ybnxybpo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2vwlsctkz.html

[A01] Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2medaqedu.html

Py:   print("Hello, World!")
来源：http://dali.smart0.xyz/Article/details/gt2rmfptpdr.html

PHP:  echo "Hello, World!";
来源：http://dali.cheryme.top/Article/details/gt2plyxueca.html

JS:   console.log("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gt2hxeldoyc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xinyue.icu/Article/details/gt2dqgdxmnu.html

Java: System.out.println("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gt2dhofppyc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cashguo.top/Article/details/gt2zzvagbuj.html

Ruby: puts "Hello, World!"
来源：http://dali.jlsjyb.cn/Article/details/gt2qqpawteh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gt2dcnxttwv.html

[A02] 变量声明与赋值
来源：http://dali.yonumen.top/Article/details/gt2jqpuripl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gogol.net.cn/Article/details/gt2ntmlxksv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jiagoushi.top/Article/details/gt2xfqyxczl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yuxming.cn/Article/details/gt2bjuqudhq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ppjwa.cn/Article/details/gt2qsstjxdx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gt2nmerqwvb.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258.top/Article/details/gt2torwqxlq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.fengsongda.top/Article/details/gt2lbfcetkl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj202588.top/Article/details/gt2opakdumk.html

[A03] 常量定义
来源：http://dali.gzhubu.top/Article/details/gt2gpmwazcm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfzvvefk.html

PHP:  const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2zqizvoog.html

JS:   const PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2fxneigpe.html

TS:   const PI: number = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2umpfjehj.html

Java: static final double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2iyedfxew.html

Go:   const PI = 3.14159
来源：http://dali.yanxiufei.cn/Article/details/gt2zzmwgwqh.html

Ruby: PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gt2uesbqign.html

C#:   const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2knpxnvaf.html

[A04] 判断变量类型
来源：http://dali.hysaishi.cn/Article/details/gt2mxqumsdj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yangfankeji.com/Article/details/gt2ooenrihh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.bjfxy.top/Article/details/gt2qudsbrzm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.9152youxi.cn/Article/details/gt2hqqaacdm.html

TS:   typeof x; x instanceof Date
来源：http://dali.smart0.xyz/Article/details/gt2dylxwpos.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.c1oappe.top/Article/details/gt2gfxijlxm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjijlmap.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.aizwys.cn/Article/details/gt2pjebkcfs.html

C#:   x.GetType().Name; x is int
来源：http://dali.daria6918.cn/Article/details/gt2wuedfurv.html

[A05] 整数除法与取模
来源：http://dali.zycfv.cn/Article/details/gt2ohdjfmgt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yongpay.top/Article/details/gt2leyubkgl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2nftvhnuo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2samsyhpx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gt2vtjygfdn.html

Java: 7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gt2iqnwoigy.html

Go:   7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gt2lrkbherr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gt2vipperyd.html

C#:   7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gt2csalyssi.html

[A06] 字符串转数字
来源：http://dali.yj20258888.top/Article/details/gt2kaspmhwp.html

Py:   int("42"); float("3.14")
来源：http://dali.ydzc1.top/Article/details/gt2bqnfuykw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.smart0.xyz/Article/details/gt2hwbdixsr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.haohaochexian.top/Article/details/gt2ypoqgeya.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.kuanghao11.cn/Article/details/gt2rjfcgxtk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axynavsj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hnxiangtu.top/Article/details/gt2fovxlyhc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.fengsongda.top/Article/details/gt2wevlpdtf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ehwqpu.com/Article/details/gt2goglvpnn.html

[A07] 数字转字符串
来源：http://dali.shuidangran.top/Article/details/gt2ziglkdra.html

Py:   str(42)
来源：http://dali.ybcxt.top/Article/details/gt2eyyfftut.html

PHP:  (string) 42; strval(42)
来源：http://dali.jqgfzy.top/Article/details/gt2jqdsituy.html

JS:   String(42); (42).toString()
来源：http://dali.hysaishi.cn/Article/details/gt2afanswms.html

TS:   String(42)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rouzmvju.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.nanxuanxn.top/Article/details/gt2qdaotose.html

Go:   strconv.Itoa(42)
来源：http://dali.gotoacloud.top/Article/details/gt2juupggyz.html

Ruby: 42.to_s
来源：http://dali.nanxinkj.top/Article/details/gt2eembesfc.html

C#:   42.ToString()
来源：http://dali.zdqjudy.top/Article/details/gt2cswdyugq.html

[A08] 取整与四舍五入
来源：http://dali.xziqi.cn/Article/details/gt2vtbagbro.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gt2whtomcut.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yueranfly.top/Article/details/gt2mkixazfy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gt2imzdcsfr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhoulong.xyz/Article/details/gt2hydxhfwz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gt2kkjjjnic.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gt2dwpjpzai.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ehwqpu.com/Article/details/gt2gxrndzrx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gt2ospymsxf.html

[A09] 绝对值与最大最小值
来源：http://dali.yuanzhike.top/Article/details/gt2rfhthjlz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sweek.top/Article/details/gt2zcdptlez.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2uylspdgs.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2jarzsvkx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2iedjvvdw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2vzfmgrum.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shzxlz.cn/Article/details/gt2ywziluoa.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shuidangran.top/Article/details/gt2dqhvpkyi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2hzilbccf.html

[A10] 生成随机数
来源：http://dali.yj202588.top/Article/details/gt2oztbmkpl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.nwbrower.top/Article/details/gt2bhszftcm.html

PHP:  random_int(1, 100);
来源：http://dali.hywenlv.cn/Article/details/gt2oglhkgpy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xziqi.cn/Article/details/gt2xjboqolq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2iezkyjqu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.havefunace.top/Article/details/gt2lwithwwo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.fengsongda.top/Article/details/gt2rdbichau.html

Ruby: rand(1..100)
来源：http://dali.hnxiangtu.top/Article/details/gt2azcmmycd.html

C#:   new Random().Next(1, 101)
来源：http://dali.guannengcc.top/Article/details/gt2foqmjmxp.html

[A11] 条件表达式（三元）
来源：http://dali.yuanzhike.top/Article/details/gt2puazblzz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.havefunace.top/Article/details/gt2bzbajsrh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gt2vmpxfrtd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gt2tgpdcltc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gt2zdtysrip.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gt2uuddfmmc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.chenlongwang.top/Article/details/gt2pgmahmyn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gt2zwhfzcat.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gt2wnrqekme.html

[A12] 字符串插值 / 格式化
来源：http://dali.jqgufenzy.top/Article/details/gt2jddeqylg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.kuanghao11.cn/Article/details/gt2byhtbfmv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gzhubu.top/Article/details/gt2ecngzaan.html

JS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkxlcrya.html

TS:   `Hello, ${name}!`
来源：http://dali.chenlongwang.top/Article/details/gt2xlmfcubh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jyoumei.cn/Article/details/gt2ntetrctl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.smart0.xyz/Article/details/gt2zxcsbccx.html

Ruby: "Hello, #{name}!"
来源：http://dali.zdqjudy.top/Article/details/gt2ojlpevpb.html

C#:   $"Hello, {name}!"
来源：http://dali.jianghu66.top/Article/details/gt2zmmbijzr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sufxvd.cn/Article/details/gt2xohjehzv.html

Py:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gt2sckwfffk.html

PHP:  "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gt2iafbfnsi.html

JS:   "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gt2tmzprztb.html

TS:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gt2ufxmbjdr.html

Java: "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gt2kafsbbbk.html

Go:   "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gt2qqukcbky.html

Ruby: "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gt2gkitkjmk.html

C#:   "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gt2hxfdfrhy.html

[A14] 注释写法
来源：http://dali.nanxinkj.top/Article/details/gt2oojbaqbn.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xinyue.icu/Article/details/gt2cqikuibc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gt2wofykyif.html

JS:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gt2mykqubay.html

TS:   // 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gt2afnapldw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.chenzaomai.com/Article/details/gt2gaaaoyfb.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usboopzt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yuxming.cn/Article/details/gt2foutswzo.html

C#:   // 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gt2wkarxclx.html

[A15] 空值判断与默认值
来源：http://dali.hfpthk.cn/Article/details/gt2pdjompos.html

Py:   value = data or "默认值"
来源：http://dali.hfpthk.cn/Article/details/gt2intixdku.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gt2plwthhol.html


<!-- 参考信息 -->