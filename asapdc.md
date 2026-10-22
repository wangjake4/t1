代发 wailian999

[U85] JS：可选链
来源：http://dali.yangfankeji.com/Article/details/gt2xzvrqyts.html

a?.b?.c
来源：http://dali.daxiang520.top/Article/details/gt2cemmuttb.html

[U86] JS：空值合并
来源：http://dali.kuanghao11.cn/Article/details/gt2nrirasol.html

a ?? b
来源：http://dali.cdnleiting.top/Article/details/gt2iafkkfot.html

[U87] JS：解构默认值
来源：http://dali.cheryme.top/Article/details/gt2wqpydwmx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.svipenyu.cn/Article/details/gt2cotrpmgq.html

[U88] JS：对象展开合并
来源：http://dali.fzhhl.top/Article/details/gt2bowmoqjn.html

{ ...a, ...b }
来源：http://dali.meibo888.top/Article/details/gt2tkeqdfdr.html

[U89] JS：数组去重
来源：http://dali.ehwqpu.com/Article/details/gt2lgwwburk.html

[...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2obaiufih.html

[U90] JS：数字数组排序
来源：http://dali.fzhhl.top/Article/details/gt2xjugcdlw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gt2zlrmkbxe.html

[U91] JS：对象键值遍历
来源：http://dali.jyoumei.cn/Article/details/gt2ndaymdkk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fengsongda.top/Article/details/gt2umndfiyy.html

[U92] JS：深拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2xftenwma.html

structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfbabkmn.html

[U93] JS：模板字符串
来源：http://dali.xuanzx.com/Article/details/gt2cjuiguxo.html

`共 ${n} 条`
来源：http://dali.shuidangran.top/Article/details/gt2hibjrvar.html

[U94] JS：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gt2vngxjxen.html

const double = x => x * 2;
来源：http://dali.zycfv.cn/Article/details/gt2tmgrgrms.html

[U95] JS：Promise 包装
来源：http://dali.haohaochexian.top/Article/details/gt2xvsgpkxm.html

new Promise((resolve, reject) => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eivwzndc.html

[U96] JS：async/await 与异常
来源：http://dali.sysykeji.top/Article/details/gt2xuejhhvm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwwldlli.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnqtuty.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gt2gvbmzsba.html

[U98] JS：fetch 带 JSON
来源：http://dali.fengsongda.top/Article/details/gt2ayddgdez.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yongpay.top/Article/details/gt2jhndfbga.html

[U99] JS：事件监听
来源：http://dali.meibo888.top/Article/details/gt2bmpwdecs.html

el.addEventListener("click", e => {})
来源：http://dali.chenzaomai.com/Article/details/gt2psmiyofj.html

[U100] JS：DOM 查询
来源：http://dali.redwolf501.top/Article/details/gt2miznmrcf.html

document.querySelector(".item")
来源：http://dali.dashuyun.cn/Article/details/gt2yihotcnd.html

[U101] JS：classList 操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwyolbeb.html

el.classList.toggle("active")
来源：http://dali.yj202588.top/Article/details/gt2xjwthtsx.html

[U102] JS：本地存储
来源：http://dali.kuanghao11.cn/Article/details/gt2ppuybdus.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jianghu66.top/Article/details/gt2agvhvurl.html

[U103] JS：定时器
来源：http://dali.zhengqikj.top/Article/details/gt2sshdgecj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ehwqpu.com/Article/details/gt2eugquyof.html

[U104] JS：防抖
来源：http://dali.0kj1m.cn/Article/details/gt2txpqcvmd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gt2yeeurohw.html

[U105] JS：节流
来源：http://dali.yj20258.top/Article/details/gt2icpgntaj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ivvv.top/Article/details/gt2szilklkt.html

[U106] JS：日期格式化
来源：http://dali.shzxlz.cn/Article/details/gt2qlauggad.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zycfv.cn/Article/details/gt2etjqfslj.html

[U107] JS：数字千分位
来源：http://dali.yj202588.top/Article/details/gt2bycygqzw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2sertwhov.html

[U108] JS：随机整数
来源：http://dali.gzhubu.top/Article/details/gt2mcfpsegj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gzhubu.top/Article/details/gt2byhmfzrt.html

[U109] JS：数组分组
来源：http://dali.shuidangran.top/Article/details/gt2njvdyrpo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkpqesiw.html

[U110] JS：数组分块
来源：http://dali.jianghu66.top/Article/details/gt2zylibdqq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxuanxn.top/Article/details/gt2dziovkmy.html

[U111] JS：对象转 Map
来源：http://dali.cashguo.top/Article/details/gt2lixpfcsg.html

new Map(Object.entries(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwccerbo.html

[U112] JS：字符串补位
来源：http://dali.jianghu66.top/Article/details/gt2utsxingp.html

"7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwlqpkzq.html

[U113] JS：正则替换全部
来源：http://dali.jinqigfzy.top/Article/details/gt2nebpgwuw.html

s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2yuevooru.html

[U114] JS：JSON 深比较
来源：http://dali.cucudq.cn/Article/details/gt2rscrfkoa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gt2ebtvzhbo.html

[U115] JS：生成 UUID
来源：http://dali.ivvv.top/Article/details/gt2iznxaqdr.html

crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gt2iiuefzjz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhoulong.xyz/Article/details/gt2qdkczgzd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzievund.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gt2wojiozfi.html

npm i -D vitest;  npx vitest
来源：http://dali.svipenyu.cn/Article/details/gt2ssjijjzz.html

[U118] JS：开发服务器
来源：http://dali.yj202588.top/Article/details/gt2flaknpvx.html

npm i -D vite;  npx vite
来源：http://dali.jinqigufen.top/Article/details/gt2ieohrqph.html

[U119] JS：生产构建
来源：http://dali.sweek.top/Article/details/gt2ycrjenkd.html

npx vite build
来源：http://dali.jyoumei.cn/Article/details/gt2djcwiysf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yuanzhike.top/Article/details/gt2lnyjcdtf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dejhvzwe.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2igkgcnro.html

统计汇总
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnugsrgx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2bdwqfiau.html

按语言统计（条）：
来源：http://dali.zdqjudy.top/Article/details/gt2abkjcjzv.html

Python ......... 252
来源：http://dali.yvedp.cn/Article/details/gt2imodclnf.html

PHP ............ 252
来源：http://dali.chenjidiqi.icu/Article/details/gt2ofohowxe.html

JavaScript ..... 252
来源：http://dali.pengpengdd.cyou/Article/details/gt2mogjplnt.html

TypeScript ..... 212
来源：http://dali.gaohongyu789.top/Article/details/gt2xignnfci.html

Java ........... 212
来源：http://dali.tianlin.xyz/Article/details/gt2sppgzfnk.html

Go ............. 212
来源：http://dali.mhx1999.top/Article/details/gt2vujcfvts.html

Ruby ........... 212
来源：http://dali.fzhhl.top/Article/details/gt2asrhachk.html

C# ............. 212
来源：http://dali.nanxinkj.top/Article/details/gt2wtdkyulx.html

C .............. 30
来源：http://dali.yonumen.top/Article/details/gt2imcrcnsy.html

C++ ............ 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aspjyeda.html

SQL ............ 90
来源：http://dali.svipenyu.cn/Article/details/gt2vjvvvatq.html

Bash ........... 80
来源：http://dali.zhixingplan.top/Article/details/gt2qeesqcab.html

Kotlin ......... 15
来源：http://dali.sufxvd.cn/Article/details/gt2vetftupr.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gt2ltatczab.html

Lua ............ 10
来源：http://dali.ppjwa.cn/Article/details/gt2psoqjuxx.html

Perl ........... 10
来源：http://dali.bjfxy.top/Article/details/gt2rxvcxdox.html

Scala .......... 10
来源：http://dali.zhengqikj.top/Article/details/gt2fbvltujb.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2pltdhmor.html

合计 ........... 2106 条
来源：http://dali.jlsjyb.cn/Article/details/gt2outerogt.html

按章节统计：
来源：http://dali.tianlin.xyz/Article/details/gt2lzjmokkm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gt2bgwcxcrr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gt2ixdyvptm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vcykuunp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gt2rvccydev.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwvpwhgy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gt2quduxmzr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gt2ovjhrnri.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gt2cgpfuamc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2abfklqlg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gt2lgxwtezj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gt2rfsnejlx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmvchbca.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2cntmrqxg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gt2ofxtwxro.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangshuangyany.cn/Article/details/gt2vulrywei.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gt2ryomoyag.html

Q SQL 专题                              90
来源：http://dali.daria6918.cn/Article/details/gt2ptvnzaer.html

R Bash 专题                             80
来源：http://dali.cashguo.top/Article/details/gt2agjmyegr.html

S C / C++ 专题                          60
来源：http://dali.sweek.top/Article/details/gt2jdxhwsqo.html

T 其他语言补充                          60
来源：http://dali.zdqjudy.top/Article/details/gt2xgoubsvm.html

U 高频实用片段                         120
来源：http://dali.yj20258.top/Article/details/gt2riodlvds.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gt2ihshifat.html

合计                                  2106 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccdmbsye.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gt2avupwcpj.html

使用提醒
来源：http://dali.sysykeji.top/Article/details/gt2pzxiapcn.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2bqoxxvti.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnqzz.top/Article/details/gt2aznyfixv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hnqzz.top/Article/details/gt2yssxoshz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.bjfxy.top/Article/details/gt2edddpulo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgufenzy.top/Article/details/gt2hkwfturc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.c1oappe.top/Article/details/gt2bdwhdqlh.html

—— 文件结束 ——
来源：http://dali.yanxiufei.cn/Article/details/gt2iwttcjre.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2edumtyiw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.mhx1999.top/Article/details/gt2rcckggmt.html

Common Programming Examples Cheat Book
来源：http://dali.shuidangran.top/Article/details/gt2dqqhgngw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2gewhsjdr.html

【收录内容】
来源：http://dali.yj20258888.top/Article/details/gt2qfikhhys.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.pycfn.com/Article/details/gt2qhdvnulp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cqqwz.cn/Article/details/gt2anrnbfam.html

SQL · Bash · C · C++
来源：http://dali.hnxiangtu.top/Article/details/gt2nutmrjgv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxinkj.top/Article/details/gt2mwahrxax.html

【使用说明】
来源：http://dali.ehwqpu.com/Article/details/gt2idilrlfa.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hnqzz.top/Article/details/gt2ppokzudy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigufen.top/Article/details/gt2obujzmxh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shangyingyoupin.top/Article/details/gt2trtimomu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yongpay.top/Article/details/gt2dxzeptqc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qtxcjiql.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cdnleiting.top/Article/details/gt2wgvozlfv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.dianchejie.cn/Article/details/gt2gntztvrl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.dashuyun.cn/Article/details/gt2pcstybxm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.nanxuanxn.top/Article/details/gt2qwpzyeil.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.smart0.xyz/Article/details/gt2lmwwckza.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.9152youxi.cn/Article/details/gt2kdhxwrnn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jiagoushi.top/Article/details/gt2rjmlolhz.html

【文件统计】
来源：http://dali.birdmap.top/Article/details/gt2sqjaygsv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.wangshuangyany.cn/Article/details/gt2pgfhihci.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gt2moigzrme.html

目  录
来源：http://dali.hammf.cn/Article/details/gt2qzvpzrac.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2wqaumahj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.redwolf501.top/Article/details/gt2extrxfue.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2zbnkyhib.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gt2uzhhfuls.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xziqi.cn/Article/details/gt2pmwplxgb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2caeyhiza.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2xowagrdn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2isexbehm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cashguo.top/Article/details/gt2oehzvqot.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gt2vvtlltgi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ppjwa.cn/Article/details/gt2pezffbbc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gt2avivoblz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gt2ytseeenw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gt2jgeqdnxk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gt2bnfohvaa.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.andypj.xyz/Article/details/gt2vbzxmghu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gt2vypjjjif.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinqigufen.top/Article/details/gt2mkwbbtmc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ybcxt.top/Article/details/gt2mvaddank.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xziqi.cn/Article/details/gt2bgtkzbol.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gt2lgflfsii.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2tjddwizw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2lpfozaqq.html

A. 基础语法与类型
来源：http://dali.yongpay.top/Article/details/gt2lrphnvqx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2fdfoagoh.html

[A01] Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2hbpikhjp.html

Py:   print("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gt2yqxstlaw.html

PHP:  echo "Hello, World!";
来源：http://dali.ybcxt.top/Article/details/gt2zlpavpxs.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gt2ryyznmaj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.svipenyu.cn/Article/details/gt2lsngbgbg.html

Java: System.out.println("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gt2rprqewoe.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gt2rwohxzah.html

Ruby: puts "Hello, World!"
来源：http://dali.gaohongyu789.top/Article/details/gt2hydlkzis.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gt2iifundev.html

[A02] 变量声明与赋值
来源：http://dali.sysykeji.top/Article/details/gt2uvivlwpg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.pycfn.com/Article/details/gt2ufkmvwuk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xziqi.cn/Article/details/gt2uyoyjsgg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hnqzz.top/Article/details/gt2ljwpbuqd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.316326.xyz/Article/details/gt2qynhyuhl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gt2gurozqok.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhongyouzk.top/Article/details/gt2gxslmeum.html

Ruby: name = "Alex"; age = 20
来源：http://dali.mhx1999.top/Article/details/gt2mreaiwhb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.pycfn.com/Article/details/gt2soapjgne.html

[A03] 常量定义
来源：http://dali.0kj1m.cn/Article/details/gt2qmwzdacy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxinkj.top/Article/details/gt2lszjbzkh.html

PHP:  const PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gt2sguuvhxq.html

JS:   const PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2mbtbyarg.html

TS:   const PI: number = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2ugfjedrb.html

Java: static final double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2erwrymcp.html

Go:   const PI = 3.14159
来源：http://dali.aizwys.cn/Article/details/gt2jqulskag.html

Ruby: PI = 3.14159
来源：http://dali.tian-w.cn/Article/details/gt2reblzpcd.html

C#:   const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2ufjladti.html

[A04] 判断变量类型
来源：http://dali.jinqigufen.top/Article/details/gt2yvcpdugm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.sxryk.cn/Article/details/gt2laoppsqn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sysykeji.top/Article/details/gt2yblpjgoz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjvjbjgv.html

TS:   typeof x; x instanceof Date
来源：http://dali.cdnleiting.top/Article/details/gt2ivbqsvhs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hfpthk.cn/Article/details/gt2pglpaepw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhixingplan.top/Article/details/gt2trizztbb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nwbrower.top/Article/details/gt2hpiqbgbr.html

C#:   x.GetType().Name; x is int
来源：http://dali.meibo888.top/Article/details/gt2qedxaocq.html

[A05] 整数除法与取模
来源：http://dali.jiagoushi.top/Article/details/gt2bzglbzmz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.meibo888.top/Article/details/gt2udxmmtzx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2ctbsrbwy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gt2wmahyffc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2pidcmjmf.html

Java: 7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gt2ihvewpvo.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trnuxtgt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2ykqgytvx.html

C#:   7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gt2vsziodbz.html

[A06] 字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gt2emlqregf.html

Py:   int("42"); float("3.14")
来源：http://dali.9152youxi.cn/Article/details/gt2asinysie.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nanxinkj.top/Article/details/gt2cldxrrke.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gt2mgelujhu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gt2paswhltn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sxryk.cn/Article/details/gt2kuqrdvjp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xylfe.cn/Article/details/gt2galrogch.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj20258.top/Article/details/gt2adttikbp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gt2ooolbjgm.html

[A07] 数字转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2hiecielc.html

Py:   str(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hlckjwhk.html

PHP:  (string) 42; strval(42)
来源：http://dali.0kj1m.cn/Article/details/gt2mwitzgnk.html

JS:   String(42); (42).toString()
来源：http://dali.havefunace.top/Article/details/gt2ojprnyci.html

TS:   String(42)
来源：http://dali.0kj1m.cn/Article/details/gt2giduhmkk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.0kj1m.cn/Article/details/gt2lvopnnus.html

Go:   strconv.Itoa(42)
来源：http://dali.hysaishi.cn/Article/details/gt2twcpdgat.html

Ruby: 42.to_s
来源：http://dali.yj202588.top/Article/details/gt2gpateyjm.html

C#:   42.ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kieitmgo.html

[A08] 取整与四舍五入
来源：http://dali.yuanzhike.top/Article/details/gt2zeumengm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gt2cdgiaiaz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnqzz.top/Article/details/gt2evmfdxes.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.birdmap.top/Article/details/gt2kbddytdd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.haohaochexian.top/Article/details/gt2twxebgen.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gt2svdsmktl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gt2xyfqvhcd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.9152youxi.cn/Article/details/gt2llthidqv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gt2mbrfcgbt.html

[A09] 绝对值与最大最小值
来源：http://dali.ybcxt.top/Article/details/gt2lsqydtsx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2rabvafje.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxhglnb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2fysincxj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2jupxjqqb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2zbcntfco.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.tanke756.top/Article/details/gt2ibtitzfn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ybcxt.top/Article/details/gt2nyxsgbpg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xinyue.icu/Article/details/gt2gnnettab.html

[A10] 生成随机数
来源：http://dali.yuxming.cn/Article/details/gt2jeatxbxb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.mhx1999.top/Article/details/gt2mafbttba.html

PHP:  random_int(1, 100);
来源：http://dali.quarkkingdee.top/Article/details/gt2gawlafvr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gt2tsdoijbj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sufxvd.cn/Article/details/gt2ikzpkhew.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guannengcc.top/Article/details/gt2urtgembs.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.nanxuanxn.top/Article/details/gt2gbtaeyih.html

Ruby: rand(1..100)
来源：http://dali.hnqzz.top/Article/details/gt2lbxrbwpk.html

C#:   new Random().Next(1, 101)
来源：http://dali.gzhubu.top/Article/details/gt2ropynhxt.html

[A11] 条件表达式（三元）
来源：http://dali.yj20258888.top/Article/details/gt2hfkhhody.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.smart0.xyz/Article/details/gt2jyprqhmo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwqeoszq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gt2yrevdlhx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okkpjynd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gt2srntmzts.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zdqjudy.top/Article/details/gt2wbcnzpef.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gt2tbejkauv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gt2mbiftxct.html

[A12] 字符串插值 / 格式化
来源：http://dali.cashguo.top/Article/details/gt2fpnyjrcj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.sysykeji.top/Article/details/gt2prnwdzpy.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sysykeji.top/Article/details/gt2ntolwirl.html

JS:   `Hello, ${name}!`
来源：http://dali.meibo888.top/Article/details/gt2ogxfvavd.html

TS:   `Hello, ${name}!`
来源：http://dali.quarkkingdee.top/Article/details/gt2vgiparlu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.mhx1999.top/Article/details/gt2beelxggl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hnqzz.top/Article/details/gt2nmptnvtq.html

Ruby: "Hello, #{name}!"
来源：http://dali.cashguo.top/Article/details/gt2osuhsyen.html

C#:   $"Hello, {name}!"
来源：http://dali.gaohongyu789.top/Article/details/gt2fkpkwnne.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.pycfn.com/Article/details/gt2iqvcckee.html

Py:   "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gt2dzrqwelg.html

PHP:  "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlyxdtij.html

JS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gt2itnuwgnj.html

TS:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gt2jzixtxke.html

Java: "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gt2ibxctfci.html

Go:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gt2ywuanazi.html

Ruby: "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2udbpctud.html

C#:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gt2mrsisxhu.html

[A14] 注释写法
来源：http://dali.316326.xyz/Article/details/gt2oqiuqdeq.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yuxming.cn/Article/details/gt2xsaaxjwc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gt2zdkethmv.html

JS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gt2lxfualme.html


<!-- 参考信息 -->