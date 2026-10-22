代发 wailian999

[U93] JS：模板字符串
来源：http://dali.sxryk.cn/Article/details/gt2hnuewarc.html

`共 ${n} 条`
来源：http://dali.zhongyouzk.top/Article/details/gt2oynhzegj.html

[U94] JS：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gt2xopbwtse.html

const double = x => x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gt2oklkjqso.html

[U95] JS：Promise 包装
来源：http://dali.ivvv.top/Article/details/gt2akdyzgey.html

new Promise((resolve, reject) => {})
来源：http://dali.c1oappe.top/Article/details/gt2nsdgxtmd.html

[U96] JS：async/await 与异常
来源：http://dali.zdqjudy.top/Article/details/gt2agfldoro.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gt2ccajnvmc.html

[U97] JS：并发请求
来源：http://dali.birdmap.top/Article/details/gt2ojgtmoyz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2srcnkoii.html

[U98] JS：fetch 带 JSON
来源：http://dali.c1oappe.top/Article/details/gt2vtkvywvq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.0kj1m.cn/Article/details/gt2wzeizovu.html

[U99] JS：事件监听
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnxopvew.html

el.addEventListener("click", e => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wyrrvgmo.html

[U100] JS：DOM 查询
来源：http://dali.guowangkeji.top/Article/details/gt2nyyiopel.html

document.querySelector(".item")
来源：http://dali.vqdsnc.cn/Article/details/gt2bxsnnogu.html

[U101] JS：classList 操作
来源：http://dali.tian-w.cn/Article/details/gt2eejnsnpv.html

el.classList.toggle("active")
来源：http://dali.cheryme.top/Article/details/gt2bfkhcjhz.html

[U102] JS：本地存储
来源：http://dali.shuidangran.top/Article/details/gt2ljdkuavt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinqigufen.top/Article/details/gt2uscmffti.html

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gt2mpwpiqzf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.dianchejie.cn/Article/details/gt2cytmexce.html

[U104] JS：防抖
来源：http://dali.nanxinkj.top/Article/details/gt2asxwhxue.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gt2ytnpvdzh.html

[U105] JS：节流
来源：http://dali.xinyue.icu/Article/details/gt2ciiwwlpv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jlsjyb.cn/Article/details/gt2mrifdmku.html

[U106] JS：日期格式化
来源：http://dali.gogol.net.cn/Article/details/gt2iatogibr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gt2kiizwein.html

[U107] JS：数字千分位
来源：http://dali.ybcxt.top/Article/details/gt2cphgdhtu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gt2ptfmtupi.html

[U108] JS：随机整数
来源：http://dali.sysykeji.top/Article/details/gt2jptkjvsu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yonumen.top/Article/details/gt2eznncewd.html

[U109] JS：数组分组
来源：http://dali.sufxvd.cn/Article/details/gt2fapejydw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gt2ewbxmdjq.html

[U110] JS：数组分块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thcxrjtn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jyoumei.cn/Article/details/gt2lskkitxp.html

[U111] JS：对象转 Map
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjocyjlt.html

new Map(Object.entries(obj))
来源：http://dali.yangfankeji.com/Article/details/gt2msrncess.html

[U112] JS：字符串补位
来源：http://dali.yj20258888.top/Article/details/gt2cqzfvhnx.html

"7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2ngaiqrdx.html

[U113] JS：正则替换全部
来源：http://dali.shzxlz.cn/Article/details/gt2ogaqqswl.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkukayop.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gt2xrbdjvrz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2tskibdlo.html

[U115] JS：生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gt2rffjqtca.html

crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gt2qyteffta.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hywenlv.cn/Article/details/gt2sqharfdb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxijilvl.html

[U117] JS：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gt2jtluojvt.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigfzy.top/Article/details/gt2yfzvgior.html

[U118] JS：开发服务器
来源：http://dali.xinyue.icu/Article/details/gt2czjbjdrs.html

npm i -D vite;  npx vite
来源：http://dali.birdmap.top/Article/details/gt2wunmzszs.html

[U119] JS：生产构建
来源：http://dali.smart0.xyz/Article/details/gt2ujzyfgfw.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2blfoefxl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhixingplan.top/Article/details/gt2zffdgxln.html

import.meta.env.VITE_API_URL
来源：http://dali.svipenyu.cn/Article/details/gt2scuodygd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehsvpvse.html

统计汇总
来源：http://dali.gogol.net.cn/Article/details/gt2mejqctbr.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ltgcbjii.html

按语言统计（条）：
来源：http://dali.smart0.xyz/Article/details/gt2vyayfgpj.html

Python ......... 252
来源：http://dali.chenjidiqi.icu/Article/details/gt2syeinlhb.html

PHP ............ 252
来源：http://dali.cucudq.cn/Article/details/gt2prlkrmrr.html

JavaScript ..... 252
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfpxmciw.html

TypeScript ..... 212
来源：http://dali.smart0.xyz/Article/details/gt2gycurkrn.html

Java ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gt2slusfkbz.html

Go ............. 212
来源：http://dali.dashuyun.cn/Article/details/gt2kzqyhphl.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gt2pccrnbvi.html

C# ............. 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erjguapw.html

C .............. 30
来源：http://dali.smart0.xyz/Article/details/gt2sdgxkbza.html

C++ ............ 30
来源：http://dali.nanxuanxn.top/Article/details/gt2nwkvmbpr.html

SQL ............ 90
来源：http://dali.guannengcc.top/Article/details/gt2hgookymq.html

Bash ........... 80
来源：http://dali.yueranfly.top/Article/details/gt2uraexyoh.html

Kotlin ......... 15
来源：http://dali.zhengqikj.top/Article/details/gt2kaqfaaip.html

Swift .......... 15
来源：http://dali.shzxlz.cn/Article/details/gt2lxjmatak.html

Lua ............ 10
来源：http://dali.daxiang520.top/Article/details/gt2chlalxqk.html

Perl ........... 10
来源：http://dali.haohaochexian.top/Article/details/gt2wjmexkxd.html

Scala .......... 10
来源：http://dali.hnqzz.top/Article/details/gt2uussspgs.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gt2erbzueoj.html

合计 ........... 2106 条
来源：http://dali.pycfn.com/Article/details/gt2avbzvepy.html

按章节统计：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkyyrifu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gt2jlbshzas.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gt2ioabbana.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gt2buxsfowc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fengsongda.top/Article/details/gt2cmsgmime.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlpckszo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gt2cvbaqzbn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gt2sqlvwtoq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gt2kiqglezg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2ydufnwws.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.9152youxi.cn/Article/details/gt2kmiasdkj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvfqlqkf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlbifxjh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gt2yrlzvzjq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jcpmkzqg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hnqzz.top/Article/details/gt2jdshhfja.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gt2xqpesmfo.html

Q SQL 专题                              90
来源：http://dali.yj20258888.top/Article/details/gt2sxzxednc.html

R Bash 专题                             80
来源：http://dali.xylfe.cn/Article/details/gt2uqhmqnhq.html

S C / C++ 专题                          60
来源：http://dali.redwolf501.top/Article/details/gt2bmhoavrv.html

T 其他语言补充                          60
来源：http://dali.meibo888.top/Article/details/gt2zwomrzwn.html

U 高频实用片段                         120
来源：http://dali.xuetiantiany.cn/Article/details/gt2eybgnwdv.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gt2myrdcabm.html

合计                                  2106 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odybmisw.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gt2orckxkfk.html

使用提醒
来源：http://dali.feifeiyinyue.top/Article/details/gt2ylkrtfnw.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2qsyejiki.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hfpthk.cn/Article/details/gt2kyyzjtqx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigufen.top/Article/details/gt2vpgnaorh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gaohongyu789.top/Article/details/gt2cymsmuoh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jyoumei.cn/Article/details/gt2zdgqrbeg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cheryme.top/Article/details/gt2mujritak.html

—— 文件结束 ——
来源：http://dali.havefunace.top/Article/details/gt2wlbgcpte.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2votrlhjh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258888.top/Article/details/gt2gpllqmhr.html

Common Programming Examples Cheat Book
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfrrulai.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2oboxcnkv.html

【收录内容】
来源：http://dali.yueranfly.top/Article/details/gt2buegnlrz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.iojbl.cn/Article/details/gt2sluxrmqj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sxryk.cn/Article/details/gt2lsvlvymp.html

SQL · Bash · C · C++
来源：http://dali.jlsjyb.cn/Article/details/gt2euswujkf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jyoumei.cn/Article/details/gt2ydpsehpz.html

【使用说明】
来源：http://dali.gaohongyu789.top/Article/details/gt2vepfchxn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cheryme.top/Article/details/gt2desytntd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xuanzx.com/Article/details/gt2nkzpelck.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.haohaochexian.top/Article/details/gt2netwqfrk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gzhubu.top/Article/details/gt2suepftpw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.kuanghao11.cn/Article/details/gt2mhybjkxo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nwbrower.top/Article/details/gt2mqcayelv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xinyue.icu/Article/details/gt2okewpzyx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.316326.xyz/Article/details/gt2gkvdoncb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shzxlz.cn/Article/details/gt2bnnadylc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hywenlv.cn/Article/details/gt2pduhermx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhixingplan.top/Article/details/gt2uultpjpn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yvedp.cn/Article/details/gt2csvytysj.html

【文件统计】
来源：http://dali.yvedp.cn/Article/details/gt2zdhvidcu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yj20258888.top/Article/details/gt2krcatmwt.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2cdpzesos.html

目  录
来源：http://dali.daxiang520.top/Article/details/gt2ykygxnbp.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2diglbdfb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2yqoncung.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gt2muieygjs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gt2gcxpocys.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2kophnrcw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yvedp.cn/Article/details/gt2nqrvmkgu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.smart0.xyz/Article/details/gt2pzicewpm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gt2exbomffp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfbiapmx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gt2mqkoqssl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.dashuyun.cn/Article/details/gt2lqjfczms.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gt2yxwtsggg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2biehinqt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gt2cvzahccr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubybllxb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jyoumei.cn/Article/details/gt2xhzqbezv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gt2romcjimw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2sskbmjsi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gogol.net.cn/Article/details/gt2gaxjqywy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guannengcc.top/Article/details/gt2gjfjxvgi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gt2ulzidiub.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2hsgtsamp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ffjndhdj.html

A. 基础语法与类型
来源：http://dali.jlsjyb.cn/Article/details/gt2jblaloeb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2afmhkask.html

[A01] Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2islniorq.html

Py:   print("Hello, World!")
来源：http://dali.xylfe.cn/Article/details/gt2lcvoiync.html

PHP:  echo "Hello, World!";
来源：http://dali.0kj1m.cn/Article/details/gt2nspkkzma.html

JS:   console.log("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gt2itllsxob.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.mhx1999.top/Article/details/gt2tczzsnzd.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfkotjxf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gt2cybrusyb.html

Ruby: puts "Hello, World!"
来源：http://dali.zhoulong.xyz/Article/details/gt2lzrewxjt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gt2bqrtmxqf.html

[A02] 变量声明与赋值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnrvgzyd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ehwqpu.com/Article/details/gt2goxyamic.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2jyzreklo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gt2ieeppjda.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhoulong.xyz/Article/details/gt2pjygniij.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gotoacloud.top/Article/details/gt2rhflmlio.html

Go:   name := "Alex"; age := 20
来源：http://dali.havefunace.top/Article/details/gt2snbamgfj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efehygds.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2raextihd.html

[A03] 常量定义
来源：http://dali.zhoulong.xyz/Article/details/gt2udahfgyl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.c1oappe.top/Article/details/gt2ekwikviw.html

PHP:  const PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pylgnldn.html

JS:   const PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2jvxufyiy.html

TS:   const PI: number = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2ojqwipal.html

Java: static final double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2vetfftol.html

Go:   const PI = 3.14159
来源：http://dali.bjfxy.top/Article/details/gt2cnecmuic.html

Ruby: PI = 3.14159
来源：http://dali.nwbrower.top/Article/details/gt2dfviceef.html

C#:   const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2bseczust.html

[A04] 判断变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmhjfmry.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhongyouzk.top/Article/details/gt2zvvknlld.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guannengcc.top/Article/details/gt2kehclhcg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gt2iskjnxkz.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gt2bkmsxfek.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xawwnqll.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hfpthk.cn/Article/details/gt2xqyrhuas.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gaohongyu789.top/Article/details/gt2ovrcgefk.html

C#:   x.GetType().Name; x is int
来源：http://dali.snrcjt.cn/Article/details/gt2kxqfudph.html

[A05] 整数除法与取模
来源：http://dali.wangshuangyany.cn/Article/details/gt2jtksocnc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj20258.top/Article/details/gt2ngyqzivp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2jjkefhoy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2whugsxna.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gt2njazlzkh.html

Java: 7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gt2tbnvveaw.html

Go:   7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2hgcefqzt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gt2euhdvtry.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2nxznemow.html

[A06] 字符串转数字
来源：http://dali.daria6918.cn/Article/details/gt2rryochog.html

Py:   int("42"); float("3.14")
来源：http://dali.fzhhl.top/Article/details/gt2nbvcfout.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.andypj.xyz/Article/details/gt2kfzgotrq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hfpthk.cn/Article/details/gt2otcwikwa.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.vqdsnc.cn/Article/details/gt2rdtgwyei.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gt2umpetawk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj202588.top/Article/details/gt2fyyxzrzd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hywenlv.cn/Article/details/gt2kuhugxyp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sxryk.cn/Article/details/gt2xpheixin.html

[A07] 数字转字符串
来源：http://dali.ybcxt.top/Article/details/gt2bblowbjr.html

Py:   str(42)
来源：http://dali.jinqigfzy.top/Article/details/gt2tzaajbvw.html

PHP:  (string) 42; strval(42)
来源：http://dali.gogol.net.cn/Article/details/gt2ydykfofw.html

JS:   String(42); (42).toString()
来源：http://dali.hnqzz.top/Article/details/gt2tmdutfzi.html

TS:   String(42)
来源：http://dali.jyoumei.cn/Article/details/gt2kqnxpqxb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tianlin.xyz/Article/details/gt2clrhakgz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhiwuduotai.top/Article/details/gt2incgbobt.html

Ruby: 42.to_s
来源：http://dali.zhoulong.xyz/Article/details/gt2nxiodvof.html

C#:   42.ToString()
来源：http://dali.shzxlz.cn/Article/details/gt2eklbvjrl.html

[A08] 取整与四舍五入
来源：http://dali.nanxuanxn.top/Article/details/gt2hlubugow.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gt2qrjkzahz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.c1oappe.top/Article/details/gt2rpeyllga.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gt2apkxdlms.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvlqkdtk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkyfcqnr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pycfn.com/Article/details/gt2sxanpakg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ydzc1.top/Article/details/gt2ymskpojc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gt2hngmopzs.html

[A09] 绝对值与最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gt2achyrpyx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gt2aheofzhg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2nlwbkawv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.havefunace.top/Article/details/gt2thuxrfdg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqleocdn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.tanke756.top/Article/details/gt2chgxbxeo.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yueranfly.top/Article/details/gt2hvsdjsad.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnxiangtu.top/Article/details/gt2nokhbano.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qliqiahm.html

[A10] 生成随机数
来源：http://dali.yuanzhike.top/Article/details/gt2eexuvlkw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.iojbl.cn/Article/details/gt2idqfdkmw.html

PHP:  random_int(1, 100);
来源：http://dali.yj202588.top/Article/details/gt2ffdyxbus.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gt2fxwwagnj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhixingplan.top/Article/details/gt2hycdgtms.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258888.top/Article/details/gt2fycfactm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhoulong.xyz/Article/details/gt2gpdcsqqb.html

Ruby: rand(1..100)
来源：http://dali.ydzc1.top/Article/details/gt2drihptji.html

C#:   new Random().Next(1, 101)
来源：http://dali.dianchejie.cn/Article/details/gt2wvxwpjew.html

[A11] 条件表达式（三元）
来源：http://dali.hammf.cn/Article/details/gt2lpvnduoe.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yuanzhike.top/Article/details/gt2lsxxapwx.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixnshogq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ppjwa.cn/Article/details/gt2hqcmgzxi.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gt2wtudmbbu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gt2aiuykbzg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yangfankeji.com/Article/details/gt2xgmmilyi.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gt2ekrlvnfv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gt2ajcyqxhm.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhengqikj.top/Article/details/gt2smjdrjqr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.smart0.xyz/Article/details/gt2kufhrqnf.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhongyouzk.top/Article/details/gt2mmljubcb.html

JS:   `Hello, ${name}!`
来源：http://dali.shzxlz.cn/Article/details/gt2hsxfygak.html

TS:   `Hello, ${name}!`
来源：http://dali.yuxming.cn/Article/details/gt2kgkobuet.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.fengsongda.top/Article/details/gt2hdozqzkn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2lgcutcps.html

Ruby: "Hello, #{name}!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vycwjipm.html

C#:   $"Hello, {name}!"
来源：http://dali.zhongyouzk.top/Article/details/gt2ydvytanh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sweek.top/Article/details/gt2adhdjtsi.html

Py:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gt2aabzzvds.html

PHP:  "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gt2wuwwtyny.html

JS:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntbcfken.html

TS:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gt2jamylqfw.html

Java: "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gt2lctvsjph.html

Go:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gt2rordqlue.html

Ruby: "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gt2eckreuro.html

C#:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wixjmdjf.html

[A14] 注释写法
来源：http://dali.xinyue.icu/Article/details/gt2ipvpunad.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ehwqpu.com/Article/details/gt2wsahnnor.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gt2wkaqhjqc.html

JS:   // 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gt2kjusyweu.html

TS:   // 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gt2rfwwxyqw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhengqikj.top/Article/details/gt2njbfudow.html

Go:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gt2mlokpcea.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sxryk.cn/Article/details/gt2qhuboklo.html

C#:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frabmvbu.html

[A15] 空值判断与默认值
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtixwssm.html

Py:   value = data or "默认值"
来源：http://dali.dianchejie.cn/Article/details/gt2ztfsuhjj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgtqywzu.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrmpnsua.html

TS:   const value = data ?? "默认值";
来源：http://dali.ehwqpu.com/Article/details/gt2vccwyenx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehozkwbv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpdlkemj.html

Ruby: value = data || "默认值"
来源：http://dali.zhoulong.xyz/Article/details/gt2sgycsozd.html

C#:   var value = data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gt2ezvyypgq.html

[A16] 真假值判断规则
来源：http://dali.aibaodan.cn/Article/details/gt2jkngeggx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sufxvd.cn/Article/details/gt2hvtcxjqg.html


<!-- 参考信息 -->