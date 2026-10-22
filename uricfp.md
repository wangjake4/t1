代发 wailian999

[U87] JS：解构默认值
来源：http://dali.shzxlz.cn/Article/details/gt2vwmuhaxe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sysykeji.top/Article/details/gt2sbuuntaw.html

[U88] JS：对象展开合并
来源：http://dali.yuanzhike.top/Article/details/gt2zymrrrcp.html

{ ...a, ...b }
来源：http://dali.ybcxt.top/Article/details/gt2hzwacexs.html

[U89] JS：数组去重
来源：http://dali.zdqjudy.top/Article/details/gt2mnmkrxrx.html

[...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gt2mezkpaoe.html

[U90] JS：数字数组排序
来源：http://dali.aizwys.cn/Article/details/gt2lowbzdfr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2jkkxzmqo.html

[U91] JS：对象键值遍历
来源：http://dali.fengsongda.top/Article/details/gt2jjnennmu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.dashuyun.cn/Article/details/gt2zmccmzjm.html

[U92] JS：深拷贝
来源：http://dali.redwolf501.top/Article/details/gt2gyztgzva.html

structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2raeozklk.html

[U93] JS：模板字符串
来源：http://dali.birdmap.top/Article/details/gt2cnvqchsj.html

`共 ${n} 条`
来源：http://dali.sufxvd.cn/Article/details/gt2yyityuwu.html

[U94] JS：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gt2zllxzegk.html

const double = x => x * 2;
来源：http://dali.yj20258.top/Article/details/gt2pcbxpeis.html

[U95] JS：Promise 包装
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbehsumq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhongyouzk.top/Article/details/gt2ejositjj.html

[U96] JS：async/await 与异常
来源：http://dali.aizwys.cn/Article/details/gt2eivqpvvi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gt2lmhwogpf.html

[U97] JS：并发请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2vczzefjh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2yguspfws.html

[U98] JS：fetch 带 JSON
来源：http://dali.tanke756.top/Article/details/gt2logwsobr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.havefunace.top/Article/details/gt2unfhkrkg.html

[U99] JS：事件监听
来源：http://dali.0kj1m.cn/Article/details/gt2lluxoydy.html

el.addEventListener("click", e => {})
来源：http://dali.bjfxy.top/Article/details/gt2keoixvrz.html

[U100] JS：DOM 查询
来源：http://dali.bjfxy.top/Article/details/gt2abktintm.html

document.querySelector(".item")
来源：http://dali.smart0.xyz/Article/details/gt2ffadscvh.html

[U101] JS：classList 操作
来源：http://dali.hfpthk.cn/Article/details/gt2gvzgydrx.html

el.classList.toggle("active")
来源：http://dali.meibo888.top/Article/details/gt2uehbzhkd.html

[U102] JS：本地存储
来源：http://dali.dashuyun.cn/Article/details/gt2jzxcunzx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yvedp.cn/Article/details/gt2nsqoucei.html

[U103] JS：定时器
来源：http://dali.hywenlv.cn/Article/details/gt2akzmjqsk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gt2mdjbzrac.html

[U104] JS：防抖
来源：http://dali.dashuyun.cn/Article/details/gt2okpvyhxd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gt2fhmvjvce.html

[U105] JS：节流
来源：http://dali.wangdashe.top/Article/details/gt2epowlalc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gt2mbxsnnlf.html

[U106] JS：日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2eesglkbg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.svipenyu.cn/Article/details/gt2ferhabmn.html

[U107] JS：数字千分位
来源：http://dali.yuxming.cn/Article/details/gt2ikensykp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gt2xrzbzklh.html

[U108] JS：随机整数
来源：http://dali.shzxlz.cn/Article/details/gt2ecgyaxma.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnxiangtu.top/Article/details/gt2ebvdfcno.html

[U109] JS：数组分组
来源：http://dali.yj202588.top/Article/details/gt2ntgoturp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gt2ekwakfsj.html

[U110] JS：数组分块
来源：http://dali.c1oappe.top/Article/details/gt2tcgwdxqk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tianlin.xyz/Article/details/gt2ckpuxenz.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gt2pqnmbvqd.html

new Map(Object.entries(obj))
来源：http://dali.ivvv.top/Article/details/gt2xqvidwqf.html

[U112] JS：字符串补位
来源：http://dali.yueranfly.top/Article/details/gt2xnogoghd.html

"7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2qxkyhvtb.html

[U113] JS：正则替换全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xijuxbev.html

s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2xqwhegzx.html

[U114] JS：JSON 深比较
来源：http://dali.guannengcc.top/Article/details/gt2jbmytmvv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2dsbbnwip.html

[U115] JS：生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gt2dzdojwky.html

crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gt2rmjydiqj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.andypj.xyz/Article/details/gt2flxyphkg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nanxinkj.top/Article/details/gt2qbndjuge.html

[U117] JS：单元测试
来源：http://dali.shzxlz.cn/Article/details/gt2laqvhrim.html

npm i -D vitest;  npx vitest
来源：http://dali.hfpthk.cn/Article/details/gt2zocateuh.html

[U118] JS：开发服务器
来源：http://dali.cashguo.top/Article/details/gt2tipfopbo.html

npm i -D vite;  npx vite
来源：http://dali.kuanghao11.cn/Article/details/gt2aeydhhsn.html

[U119] JS：生产构建
来源：http://dali.zhixingplan.top/Article/details/gt2tylxftek.html

npx vite build
来源：http://dali.haohaochexian.top/Article/details/gt2kpfkwwet.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zetdrxfu.html

import.meta.env.VITE_API_URL
来源：http://dali.iojbl.cn/Article/details/gt2ghzghpto.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2rzmbusdi.html

统计汇总
来源：http://dali.aibaodan.cn/Article/details/gt2ppphytzv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2fdciihqe.html

按语言统计（条）：
来源：http://dali.zhongyouzk.top/Article/details/gt2yvvxoiyy.html

Python ......... 252
来源：http://dali.tian-w.cn/Article/details/gt2buxguytf.html

PHP ............ 252
来源：http://dali.gotoacloud.top/Article/details/gt2ciucehqa.html

JavaScript ..... 252
来源：http://dali.chenlongwang.top/Article/details/gt2hgrrzprd.html

TypeScript ..... 212
来源：http://dali.nwbrower.top/Article/details/gt2kuwtzqri.html

Java ........... 212
来源：http://dali.svipenyu.cn/Article/details/gt2xoyjwxqr.html

Go ............. 212
来源：http://dali.daria6918.cn/Article/details/gt2zrjawajq.html

Ruby ........... 212
来源：http://dali.ehwqpu.com/Article/details/gt2khxzcaes.html

C# ............. 212
来源：http://dali.yj20258888.top/Article/details/gt2fhjtgbqu.html

C .............. 30
来源：http://dali.fengsongda.top/Article/details/gt2jbpslgue.html

C++ ............ 30
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqabfxqu.html

SQL ............ 90
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2doyjrzmt.html

Bash ........... 80
来源：http://dali.yuanzhike.top/Article/details/gt2hxzmtoev.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gt2weguyhwj.html

Swift .......... 15
来源：http://dali.shuidangran.top/Article/details/gt2uswirvxj.html

Lua ............ 10
来源：http://dali.hnqzz.top/Article/details/gt2pwiftyfc.html

Perl ........... 10
来源：http://dali.shzxlz.cn/Article/details/gt2pjypfgmg.html

Scala .......... 10
来源：http://dali.vqdsnc.cn/Article/details/gt2qvlolmdw.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxljokyr.html

合计 ........... 2106 条
来源：http://dali.xylfe.cn/Article/details/gt2untlenld.html

按章节统计：
来源：http://dali.bjfxy.top/Article/details/gt2kgywsola.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gt2tqvjqzdq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdcunndj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gt2xugjuawa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gt2jkbmlwpd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ybcxt.top/Article/details/gt2bpzbjaal.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shuidangran.top/Article/details/gt2vvevpxgy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2mgcjsewg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.andypj.xyz/Article/details/gt2fapkrxsr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gt2uizxorjy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gt2imhvcrsk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2ifoqdxcw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gt2uleuksvp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2kejfgrrx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daria6918.cn/Article/details/gt2mclffqav.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ivvv.top/Article/details/gt2gcvqlnfd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gt2hfpkgqhf.html

Q SQL 专题                              90
来源：http://dali.hammf.cn/Article/details/gt2osveuten.html

R Bash 专题                             80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfpbnyda.html

S C / C++ 专题                          60
来源：http://dali.daxiang520.top/Article/details/gt2dniamdyg.html

T 其他语言补充                          60
来源：http://dali.yangfankeji.com/Article/details/gt2ktqkgvyk.html

U 高频实用片段                         120
来源：http://dali.xziqi.cn/Article/details/gt2odegxzfa.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2pktgmzyt.html

合计                                  2106 条
来源：http://dali.yj20258888.top/Article/details/gt2ygksbfxv.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2wqppijyt.html

使用提醒
来源：http://dali.guowangkeji.top/Article/details/gt2rqeltrjj.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2wafyhzae.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yongpay.top/Article/details/gt2sfbsabup.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gogol.net.cn/Article/details/gt2wwdfxacv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hfpthk.cn/Article/details/gt2evighuxo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.pycfn.com/Article/details/gt2zlsjfnng.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vhpvzken.html

—— 文件结束 ——
来源：http://dali.gotoacloud.top/Article/details/gt2jpgxvjvm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2zvxbbzvr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhoulong.xyz/Article/details/gt2udvnwozs.html

Common Programming Examples Cheat Book
来源：http://dali.shzxlz.cn/Article/details/gt2moqtqlst.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2etijskcz.html

【收录内容】
来源：http://dali.hywenlv.cn/Article/details/gt2tiubbhxc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tianlin.xyz/Article/details/gt2aitqoblp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwalqqwi.html

SQL · Bash · C · C++
来源：http://dali.snrcjt.cn/Article/details/gt2tkuisahf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yonumen.top/Article/details/gt2yxoaxnnm.html

【使用说明】
来源：http://dali.hongshengwenyu.top/Article/details/gt2wilsbmeq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cdnleiting.top/Article/details/gt2qhegwphn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sufxvd.cn/Article/details/gt2hurbwwer.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yangfankeji.com/Article/details/gt2iragzyfy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jiagoushi.top/Article/details/gt2sxllqwkm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jianghu66.top/Article/details/gt2zzycvdtw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhengqikj.top/Article/details/gt2wnmozmmq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzcvukfb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.dashuyun.cn/Article/details/gt2divbevfy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sweek.top/Article/details/gt2ggylbmxz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hongshengwenyu.top/Article/details/gt2shosnjgx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jyoumei.cn/Article/details/gt2kaweqpbk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jiagoushi.top/Article/details/gt2jxvsojlm.html

【文件统计】
来源：http://dali.wangshuangyany.cn/Article/details/gt2aecdudip.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.quarkkingdee.top/Article/details/gt2agafzupg.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2tqulogag.html

目  录
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqtrvotj.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfeqdmbg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.svipenyu.cn/Article/details/gt2hiqfvajd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gt2uxovyyvp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gt2lvqxxjou.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gt2xrvbdbii.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.haohaochexian.top/Article/details/gt2asrznviw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycplggoc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2jstqiexs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gt2abiyyzto.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gt2lefveknr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj202588.top/Article/details/gt2foarnbpp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gt2tpljnasd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gt2xrhbekkd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gt2uaxpwnmq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hammf.cn/Article/details/gt2agiavksp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xuanzx.com/Article/details/gt2nochsduv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gt2rruaotvw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2gxxppmet.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.havefunace.top/Article/details/gt2mtltmgvb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sweek.top/Article/details/gt2shtihrpu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmieibgw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gt2cpskjtab.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ajqkyyer.html

A. 基础语法与类型
来源：http://dali.yuxming.cn/Article/details/gt2kwysbwnd.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2nwqgsdpt.html

[A01] Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jgazcdix.html

Py:   print("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gt2aosriuio.html

PHP:  echo "Hello, World!";
来源：http://dali.iojbl.cn/Article/details/gt2zmbrcism.html

JS:   console.log("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gt2hfuqwtom.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tianlin.xyz/Article/details/gt2dwwrqgfg.html

Java: System.out.println("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gt2jgxnsgbd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gt2drvbqphj.html

Ruby: puts "Hello, World!"
来源：http://dali.cucudq.cn/Article/details/gt2uydhsmpg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gt2cnlydygh.html

[A02] 变量声明与赋值
来源：http://dali.cheryme.top/Article/details/gt2bvdtlpui.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sysykeji.top/Article/details/gt2bumruhsc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhixingplan.top/Article/details/gt2oyushoai.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atfdcjzt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cucudq.cn/Article/details/gt2qxbzuiyl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gt2lyxyarau.html

Go:   name := "Alex"; age := 20
来源：http://dali.0kj1m.cn/Article/details/gt2qwzcfxvy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnqzz.top/Article/details/gt2mvvjhpec.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.aibaodan.cn/Article/details/gt2plqtagag.html

[A03] 常量定义
来源：http://dali.guannengcc.top/Article/details/gt2bkchmhyv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.aibaodan.cn/Article/details/gt2rdkkosqv.html

PHP:  const PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2lnvjxljk.html

JS:   const PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2flypchql.html

TS:   const PI: number = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2hwqlvkxr.html

Java: static final double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2ayeifsjb.html

Go:   const PI = 3.14159
来源：http://dali.gzhubu.top/Article/details/gt2vukqdexm.html

Ruby: PI = 3.14159
来源：http://dali.bjfxy.top/Article/details/gt2oifjwgvd.html

C#:   const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2cnpuimuv.html

[A04] 判断变量类型
来源：http://dali.shzxlz.cn/Article/details/gt2uzkvdluo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.redwolf501.top/Article/details/gt2frrcfhay.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ybcxt.top/Article/details/gt2kqwhufgd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yj202588.top/Article/details/gt2qomeoccu.html

TS:   typeof x; x instanceof Date
来源：http://dali.ppjwa.cn/Article/details/gt2tpysumab.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jlsjyb.cn/Article/details/gt2pfuhwxcu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sufxvd.cn/Article/details/gt2rjklpikp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xziqi.cn/Article/details/gt2fwwknmrc.html

C#:   x.GetType().Name; x is int
来源：http://dali.cheryme.top/Article/details/gt2kelmaxgv.html

[A05] 整数除法与取模
来源：http://dali.ydzc1.top/Article/details/gt2ctujayjh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jiagoushi.top/Article/details/gt2ddmdgsxz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gt2nmnpoqcu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gt2wpircvce.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gt2mkjcgyzv.html

Java: 7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gt2dqjoumic.html

Go:   7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gt2dwieedcj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2ieprnwhe.html

C#:   7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gt2zewaqquu.html

[A06] 字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gt2rdgvzcsl.html

Py:   int("42"); float("3.14")
来源：http://dali.aizwys.cn/Article/details/gt2auiohrcp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.havefunace.top/Article/details/gt2vniigdiy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gt2pdwswtwa.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gt2zwxhmdaa.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.birdmap.top/Article/details/gt2wobhmrrq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ppjwa.cn/Article/details/gt2ybkwsswe.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gzhubu.top/Article/details/gt2addufoed.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.redwolf501.top/Article/details/gt2nhibsuhr.html

[A07] 数字转字符串
来源：http://dali.c1oappe.top/Article/details/gt2ompweelg.html

Py:   str(42)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgyehsro.html

PHP:  (string) 42; strval(42)
来源：http://dali.shuidangran.top/Article/details/gt2iclecgoh.html

JS:   String(42); (42).toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2cdbqfnwz.html

TS:   String(42)
来源：http://dali.guannengcc.top/Article/details/gt2kxsneqdu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yonumen.top/Article/details/gt2fiycccxm.html

Go:   strconv.Itoa(42)
来源：http://dali.yuxming.cn/Article/details/gt2mkgeorlp.html

Ruby: 42.to_s
来源：http://dali.aizwys.cn/Article/details/gt2tjqoyhcl.html

C#:   42.ToString()
来源：http://dali.sufxvd.cn/Article/details/gt2kcveqliq.html

[A08] 取整与四舍五入
来源：http://dali.gotoacloud.top/Article/details/gt2wigmmtlh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gt2pvuuvodc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuanzhike.top/Article/details/gt2lnxwoega.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gt2jdubgzsq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj20258.top/Article/details/gt2qrcdesvm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrwqrxeo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qisoywrd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zycfv.cn/Article/details/gt2fdmwyten.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sweek.top/Article/details/gt2npvcjobf.html

[A09] 绝对值与最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmmqdgwd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2mepdwuud.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2kxulxmix.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gt2rhzhitst.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zntpicgw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjvrtotk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jinqigufen.top/Article/details/gt2dfabldkl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvupmgki.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2onkgzvyi.html

[A10] 生成随机数
来源：http://dali.0kj1m.cn/Article/details/gt2bjxgxlce.html

Py:   import random; random.randint(1, 100)
来源：http://dali.birdmap.top/Article/details/gt2qczzseyw.html

PHP:  random_int(1, 100);
来源：http://dali.0kj1m.cn/Article/details/gt2ltyqjked.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptornpdg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2qenoiodh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.chenzaomai.com/Article/details/gt2wpipkwma.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtsvpeez.html

Ruby: rand(1..100)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxosbnbe.html

C#:   new Random().Next(1, 101)
来源：http://dali.haohaochexian.top/Article/details/gt2amfyncir.html

[A11] 条件表达式（三元）
来源：http://dali.andypj.xyz/Article/details/gt2esbgcdzt.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.redwolf501.top/Article/details/gt2kissiyic.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gt2iykyvczf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2qfdtxtmn.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gt2jbsjcdxa.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqseaoxd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ivvv.top/Article/details/gt2dvkcrzbz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gt2mtiddung.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gt2inwkjvmo.html

[A12] 字符串插值 / 格式化
来源：http://dali.kuanghao11.cn/Article/details/gt2idtxinow.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhxekuzc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eahdxmdp.html

JS:   `Hello, ${name}!`
来源：http://dali.cheryme.top/Article/details/gt2sdtyyxbh.html

TS:   `Hello, ${name}!`
来源：http://dali.gaohongyu789.top/Article/details/gt2eqohycfz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.0kj1m.cn/Article/details/gt2kzqsauak.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.redwolf501.top/Article/details/gt2kbizperp.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhiwuduotai.top/Article/details/gt2inzvfqor.html

C#:   $"Hello, {name}!"
来源：http://dali.gzhubu.top/Article/details/gt2xugeaxtf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.316326.xyz/Article/details/gt2dphgtsor.html

Py:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gt2wdrisjrd.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2catbzcct.html

JS:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gt2wrhjuecz.html

TS:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gt2jcdisqkk.html

Java: "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gt2ryxodtyw.html

Go:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrpnklcp.html

Ruby: "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gt2bmljqoho.html

C#:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gt2psqikiqi.html

[A14] 注释写法
来源：http://dali.svipenyu.cn/Article/details/gt2jneanvco.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yangfankeji.com/Article/details/gt2ahrhbond.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gt2bdpkugdr.html

JS:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gt2ezmgnlud.html

TS:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gt2jyxunqva.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yongpay.top/Article/details/gt2mmhfwtsm.html

Go:   // 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gt2waosribj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.svipenyu.cn/Article/details/gt2vjqibslt.html


<!-- 参考信息 -->