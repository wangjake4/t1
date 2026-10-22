代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.0kj1m.cn/Article/details/gt2hjyexwsw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.redwolf501.top/Article/details/gt2dkwzduoa.html

[U92] JS：深拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gt2pjajxybo.html

structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2sewouysq.html

[U93] JS：模板字符串
来源：http://dali.gogol.net.cn/Article/details/gt2iojgdqwp.html

`共 ${n} 条`
来源：http://dali.aizwys.cn/Article/details/gt2cyosivma.html

[U94] JS：箭头函数
来源：http://dali.fzhhl.top/Article/details/gt2icewrldr.html

const double = x => x * 2;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkitnjas.html

[U95] JS：Promise 包装
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjglghbk.html

new Promise((resolve, reject) => {})
来源：http://dali.redwolf501.top/Article/details/gt2xlpxwppy.html

[U96] JS：async/await 与异常
来源：http://dali.ybcxt.top/Article/details/gt2qnsprbst.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2iaqlinvh.html

[U97] JS：并发请求
来源：http://dali.kuanghao11.cn/Article/details/gt2dhlcrvnq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2qpvetiaq.html

[U98] JS：fetch 带 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2igkqmbjr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yuxming.cn/Article/details/gt2juxvrlgb.html

[U99] JS：事件监听
来源：http://dali.cdnleiting.top/Article/details/gt2ckxpwkjx.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258888.top/Article/details/gt2olrdueji.html

[U100] JS：DOM 查询
来源：http://dali.gzhubu.top/Article/details/gt2cfbomkrm.html

document.querySelector(".item")
来源：http://dali.gogol.net.cn/Article/details/gt2cmugtdaj.html

[U101] JS：classList 操作
来源：http://dali.jinqigufen.top/Article/details/gt2rpehwvnb.html

el.classList.toggle("active")
来源：http://dali.shzxlz.cn/Article/details/gt2lefregjp.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gt2xtaiewsi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lpdyfnuf.html

[U103] JS：定时器
来源：http://dali.daxiang520.top/Article/details/gt2bggjrvqs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yonumen.top/Article/details/gt2xqcgbjuo.html

[U104] JS：防抖
来源：http://dali.jqgfzy.top/Article/details/gt2sbhjkkre.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gt2nnfyftpe.html

[U105] JS：节流
来源：http://dali.andypj.xyz/Article/details/gt2pqkycdxj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sweek.top/Article/details/gt2dtwbdagv.html

[U106] JS：日期格式化
来源：http://dali.0kj1m.cn/Article/details/gt2zxchmqpj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zdqjudy.top/Article/details/gt2dhuybisa.html

[U107] JS：数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gt2suldwyun.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2flpzjjan.html

[U108] JS：随机整数
来源：http://dali.ehwqpu.com/Article/details/gt2pmvtmpir.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.redwolf501.top/Article/details/gt2xexxbgkb.html

[U109] JS：数组分组
来源：http://dali.nanxinkj.top/Article/details/gt2kaunykhy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gt2vazwfxca.html

[U110] JS：数组分块
来源：http://dali.yongpay.top/Article/details/gt2jccjtwhc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.wangshuangyany.cn/Article/details/gt2etnweyrl.html

[U111] JS：对象转 Map
来源：http://dali.svipenyu.cn/Article/details/gt2amtviqcv.html

new Map(Object.entries(obj))
来源：http://dali.tanke756.top/Article/details/gt2yzipoxzg.html

[U112] JS：字符串补位
来源：http://dali.yvedp.cn/Article/details/gt2zqwdsyqc.html

"7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2dzhjmxyx.html

[U113] JS：正则替换全部
来源：http://dali.svipenyu.cn/Article/details/gt2grvyygni.html

s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2urzajoqc.html

[U114] JS：JSON 深比较
来源：http://dali.gaohongyu789.top/Article/details/gt2cxchfbbv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2urnthihl.html

[U115] JS：生成 UUID
来源：http://dali.zycfv.cn/Article/details/gt2lozzfxam.html

crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2jevajwop.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.0kj1m.cn/Article/details/gt2ondftgey.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tianlin.xyz/Article/details/gt2ggrzjaec.html

[U117] JS：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gt2tzoftbah.html

npm i -D vitest;  npx vitest
来源：http://dali.chenzaomai.com/Article/details/gt2ijdnjknr.html

[U118] JS：开发服务器
来源：http://dali.redwolf501.top/Article/details/gt2pcycfncl.html

npm i -D vite;  npx vite
来源：http://dali.guowangkeji.top/Article/details/gt2lrzvtcwi.html

[U119] JS：生产构建
来源：http://dali.kuanghao11.cn/Article/details/gt2gbkyewku.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gt2syabjmhh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxuanxn.top/Article/details/gt2bvxzqjtk.html

import.meta.env.VITE_API_URL
来源：http://dali.redwolf501.top/Article/details/gt2xsvvwtfv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2swdmzhfd.html

统计汇总
来源：http://dali.smart0.xyz/Article/details/gt2tbartklj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2rmlnjpnj.html

按语言统计（条）：
来源：http://dali.xziqi.cn/Article/details/gt2eobmtyhu.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gt2caamkyas.html

PHP ............ 252
来源：http://dali.yonumen.top/Article/details/gt2xnpgsjsc.html

JavaScript ..... 252
来源：http://dali.nanxuanxn.top/Article/details/gt2ostspddx.html

TypeScript ..... 212
来源：http://dali.daria6918.cn/Article/details/gt2lbqymhoe.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gt2jeqtxhpw.html

Go ............. 212
来源：http://dali.birdmap.top/Article/details/gt2ltwleeld.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2csyxktmi.html

C# ............. 212
来源：http://dali.jianghu66.top/Article/details/gt2sxsmoifw.html

C .............. 30
来源：http://dali.guannengcc.top/Article/details/gt2nmidjorn.html

C++ ............ 30
来源：http://dali.gzhubu.top/Article/details/gt2koiirtwu.html

SQL ............ 90
来源：http://dali.shuidangran.top/Article/details/gt2tnkutgyi.html

Bash ........... 80
来源：http://dali.yvedp.cn/Article/details/gt2argrbmve.html

Kotlin ......... 15
来源：http://dali.xylfe.cn/Article/details/gt2gujdfgsf.html

Swift .......... 15
来源：http://dali.gaohongyu789.top/Article/details/gt2kjkwnhnx.html

Lua ............ 10
来源：http://dali.zhengqikj.top/Article/details/gt2kmcaiwwp.html

Perl ........... 10
来源：http://dali.xylfe.cn/Article/details/gt2sohdgnym.html

Scala .......... 10
来源：http://dali.shuidangran.top/Article/details/gt2luoxzjzy.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnaimyrs.html

合计 ........... 2106 条
来源：http://dali.zdqjudy.top/Article/details/gt2hzppnxlj.html

按章节统计：
来源：http://dali.c1oappe.top/Article/details/gt2sbswtepg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnqzz.top/Article/details/gt2eczstgqj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gt2bfrbkbwy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gt2yqddgupo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gt2slydylzf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gotoacloud.top/Article/details/gt2rqchsupi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gt2sfmfapag.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxrmaek.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gt2hrbjwoqg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2vztdogtl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gt2qtxiloml.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gt2fcupuzut.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gt2rkibbjkb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gt2xpuxcbjc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gt2vffatkcq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhongyouzk.top/Article/details/gt2ykwqrwgi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gt2rvabgvhe.html

Q SQL 专题                              90
来源：http://dali.hywenlv.cn/Article/details/gt2hactxtrv.html

R Bash 专题                             80
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygzfdvlw.html

S C / C++ 专题                          60
来源：http://dali.shzxlz.cn/Article/details/gt2hcvsqkaw.html

T 其他语言补充                          60
来源：http://dali.cashguo.top/Article/details/gt2enjlyqzx.html

U 高频实用片段                         120
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmsmyoun.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gt2hqqnsfjd.html

合计                                  2106 条
来源：http://dali.yj20258.top/Article/details/gt2agdagbsq.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gt2ztjrkgis.html

使用提醒
来源：http://dali.wangdashe.top/Article/details/gt2azblcwtw.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2yrmrjejo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhongyouzk.top/Article/details/gt2fkjoniwm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhongyouzk.top/Article/details/gt2wcnopqdv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hywenlv.cn/Article/details/gt2erebpjaf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.svipenyu.cn/Article/details/gt2xnvwopsb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gaohongyu789.top/Article/details/gt2xsidvilb.html

—— 文件结束 ——
来源：http://dali.c1oappe.top/Article/details/gt2gipuydhq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2uqzfyify.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cafcvrek.html

Common Programming Examples Cheat Book
来源：http://dali.bjfxy.top/Article/details/gt2wvmpshoo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2jzpbghut.html

【收录内容】
来源：http://dali.ivvv.top/Article/details/gt2ygkfirej.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yuxming.cn/Article/details/gt2vtgvyzdu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ppjwa.cn/Article/details/gt2nrovhjph.html

SQL · Bash · C · C++
来源：http://dali.yangfankeji.com/Article/details/gt2pzqeakqn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cashguo.top/Article/details/gt2jlhwmtsj.html

【使用说明】
来源：http://dali.hysaishi.cn/Article/details/gt2bouebmwo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfaebbyb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yonumen.top/Article/details/gt2dgojgyqn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hfpthk.cn/Article/details/gt2cnbwdmst.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tian-w.cn/Article/details/gt2wcuxobby.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gotoacloud.top/Article/details/gt2hvbpuxml.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.0kj1m.cn/Article/details/gt2gonrvbor.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.haohaochexian.top/Article/details/gt2wctbtffx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hnqzz.top/Article/details/gt2jfjphffj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.haohaochexian.top/Article/details/gt2jypjvjcb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ivvv.top/Article/details/gt2hfdcelaa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gogol.net.cn/Article/details/gt2zbyisovs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yaikeail.html

【文件统计】
来源：http://dali.havefunace.top/Article/details/gt2hfomoiez.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.mhx1999.top/Article/details/gt2bxawpeng.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2zjjqxlbr.html

目  录
来源：http://dali.hammf.cn/Article/details/gt2evcvsrzs.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gt2xzhcxqtb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sysykeji.top/Article/details/gt2jfecrzsi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2ojfqrots.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gt2msssnmrl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gt2wqjxnqof.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cashguo.top/Article/details/gt2snerqicc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yj20258888.top/Article/details/gt2ybiafhcn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gt2gtsswead.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yongpay.top/Article/details/gt2dxudeluv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gt2dgynpbxw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gt2ljgtczku.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gt2wkegeegp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2xdizsovs.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2yocsybxq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gt2tcowblrp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bailzlho.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gt2igidaoun.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tian-w.cn/Article/details/gt2bscnzdim.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.smart0.xyz/Article/details/gt2ulbxltwr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.haohaochexian.top/Article/details/gt2fmxovbzj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gt2bekvofnc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gt2vrpvwjly.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2smvhvwsx.html

A. 基础语法与类型
来源：http://dali.quarkkingdee.top/Article/details/gt2dvlrqnwu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2gcjasyup.html

[A01] Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2afhxypvq.html

Py:   print("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gt2gjjhxtdn.html

PHP:  echo "Hello, World!";
来源：http://dali.aibaodan.cn/Article/details/gt2xhhxijfd.html

JS:   console.log("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gt2vsfdjdhr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwmljepo.html

Java: System.out.println("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gt2obvxgqmg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gt2nawmhcsk.html

Ruby: puts "Hello, World!"
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcppszdz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gt2vgwbnkyh.html

[A02] 变量声明与赋值
来源：http://dali.cucudq.cn/Article/details/gt2rqtmkltm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gaohongyu789.top/Article/details/gt2zgmonzcq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgfzy.top/Article/details/gt2hqumkwhu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ivvv.top/Article/details/gt2jhngwktl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sysykeji.top/Article/details/gt2pgjyygsp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.birdmap.top/Article/details/gt2jprrrnpr.html

Go:   name := "Alex"; age := 20
来源：http://dali.yongpay.top/Article/details/gt2jbbgjhie.html

Ruby: name = "Alex"; age = 20
来源：http://dali.smart0.xyz/Article/details/gt2feggpjmr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gt2gcztzxkk.html

[A03] 常量定义
来源：http://dali.jinqigufen.top/Article/details/gt2nonmubpb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yongpay.top/Article/details/gt2klwisuni.html

PHP:  const PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2zmsbrutk.html

JS:   const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2sezeuion.html

TS:   const PI: number = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gt2dnoaxrjw.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hixlaogq.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gt2hhcxlhov.html

Ruby: PI = 3.14159
来源：http://dali.hnqzz.top/Article/details/gt2rdphdrgp.html

C#:   const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2dmotactj.html

[A04] 判断变量类型
来源：http://dali.pycfn.com/Article/details/gt2jtpdgovj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amcuoqry.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.fzhhl.top/Article/details/gt2juibgmek.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gt2wgyjvssf.html

TS:   typeof x; x instanceof Date
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2albsoiug.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sweek.top/Article/details/gt2szlwzaia.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.meibo888.top/Article/details/gt2wzuiwqfu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.pengpengdd.cyou/Article/details/gt2osuqhhqb.html

C#:   x.GetType().Name; x is int
来源：http://dali.c1oappe.top/Article/details/gt2dnfsmaav.html

[A05] 整数除法与取模
来源：http://dali.guowangkeji.top/Article/details/gt2wlisjhtv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dianchejie.cn/Article/details/gt2wxkztxug.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gt2mwezsfzq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhqcglmr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gt2aobzhmxd.html

Java: 7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2vbfdnhoi.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbmmoufh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adxguvaf.html

C#:   7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2hrovmdhw.html

[A06] 字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gt2cbipxdtl.html

Py:   int("42"); float("3.14")
来源：http://dali.gzhubu.top/Article/details/gt2qrbbcqzj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2epicqycu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shzxlz.cn/Article/details/gt2bnnhcthx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hammf.cn/Article/details/gt2jcpnaqac.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwapjdlt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gogol.net.cn/Article/details/gt2idnwdoyo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sufxvd.cn/Article/details/gt2waskdgeb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.dianchejie.cn/Article/details/gt2ztfzucnt.html

[A07] 数字转字符串
来源：http://dali.mhx1999.top/Article/details/gt2tivdeojd.html

Py:   str(42)
来源：http://dali.aizwys.cn/Article/details/gt2qfbeuhay.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhixingplan.top/Article/details/gt2qsbbqbfv.html

JS:   String(42); (42).toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fyvuajax.html

TS:   String(42)
来源：http://dali.gzhubu.top/Article/details/gt2vbugoyio.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yuxming.cn/Article/details/gt2vwdolsrp.html

Go:   strconv.Itoa(42)
来源：http://dali.9152youxi.cn/Article/details/gt2eswqajjw.html

Ruby: 42.to_s
来源：http://dali.nanxinkj.top/Article/details/gt2qztjmadd.html

C#:   42.ToString()
来源：http://dali.zhixingplan.top/Article/details/gt2covkwukp.html

[A08] 取整与四舍五入
来源：http://dali.fengsongda.top/Article/details/gt2nzmjhwxn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gt2lboaixqu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ppjwa.cn/Article/details/gt2xdxaheib.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gt2rgmnzyjk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yuxming.cn/Article/details/gt2pmcejmrv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gt2bidiqgzj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gt2ftypmenr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cqqwz.cn/Article/details/gt2encreiqm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gt2axxsavif.html

[A09] 绝对值与最大最小值
来源：http://dali.ivvv.top/Article/details/gt2ubfident.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urrknixk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2qcyidcbz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jianghu66.top/Article/details/gt2rmqdtxxt.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2rjieiogp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qawephhr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gaohongyu789.top/Article/details/gt2fhijwiqs.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xziqi.cn/Article/details/gt2qixtxlvu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2iqezvgfa.html

[A10] 生成随机数
来源：http://dali.ivvv.top/Article/details/gt2nujbmhnl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.aizwys.cn/Article/details/gt2xadxnifb.html

PHP:  random_int(1, 100);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlyogomu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hywenlv.cn/Article/details/gt2qroggscm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yuanzhike.top/Article/details/gt2tfksnsqq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qumvrjss.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.iojbl.cn/Article/details/gt2ahzbznfs.html

Ruby: rand(1..100)
来源：http://dali.hysaishi.cn/Article/details/gt2rvycklrb.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinqigufen.top/Article/details/gt2kobzaexm.html

[A11] 条件表达式（三元）
来源：http://dali.guannengcc.top/Article/details/gt2brcdhmsw.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.c1oappe.top/Article/details/gt2hxfgubpk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gt2exvunnhe.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gt2cjuclpye.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfgwlkua.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gt2iaejiwqm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhoulong.xyz/Article/details/gt2jyukuwxm.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gt2cockrohk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2jancnbou.html

[A12] 字符串插值 / 格式化
来源：http://dali.yuanzhike.top/Article/details/gt2oylrqpcm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.dashuyun.cn/Article/details/gt2bqcgrpix.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hammf.cn/Article/details/gt2eicpacnb.html

JS:   `Hello, ${name}!`
来源：http://dali.cucudq.cn/Article/details/gt2lbilrnwm.html

TS:   `Hello, ${name}!`
来源：http://dali.zdqjudy.top/Article/details/gt2rgrjcfbl.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yongpay.top/Article/details/gt2cqtipdet.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2zfqabveg.html

Ruby: "Hello, #{name}!"
来源：http://dali.meibo888.top/Article/details/gt2yvvnrufr.html

C#:   $"Hello, {name}!"
来源：http://dali.hysaishi.cn/Article/details/gt2qvbyxzyp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulsvwcod.html

Py:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2hluypdjz.html

PHP:  "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljwvmiya.html

JS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gt2lernvsxd.html

TS:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2htxglonr.html

Java: "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gt2bilsvtdo.html

Go:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2amekpjyp.html

Ruby: "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjewghol.html

C#:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gt2ndlgvlow.html

[A14] 注释写法
来源：http://dali.guowangkeji.top/Article/details/gt2wauqjssa.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.redwolf501.top/Article/details/gt2rukldhsn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkewaffx.html

JS:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gt2xuxsfdst.html

TS:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gt2pmehaxms.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.wangdashe.top/Article/details/gt2srnreuzs.html

Go:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gt2ddscnylp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulizfivl.html

C#:   // 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gt2cxsbiqxh.html

[A15] 空值判断与默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ruxzqvks.html

Py:   value = data or "默认值"
来源：http://dali.guannengcc.top/Article/details/gt2esaupqud.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ydzc1.top/Article/details/gt2fwbzhlyw.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbllyhd.html

TS:   const value = data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gt2iygucppv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yuanzhike.top/Article/details/gt2eutzrqlj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shzxlz.cn/Article/details/gt2tflujfoa.html


<!-- 参考信息 -->