代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.haohaochexian.top/Article/details/gt2yvhkukfg.html

new Promise((resolve, reject) => {})
来源：http://dali.sufxvd.cn/Article/details/gt2edjwwszd.html

[U96] JS：async/await 与异常
来源：http://dali.jyoumei.cn/Article/details/gt2ivxjeuvu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljivlvga.html

[U97] JS：并发请求
来源：http://dali.hnxiangtu.top/Article/details/gt2xgukszgp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfpzikcc.html

[U98] JS：fetch 带 JSON
来源：http://dali.andypj.xyz/Article/details/gt2koukssvf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xylfe.cn/Article/details/gt2pqcrgqel.html

[U99] JS：事件监听
来源：http://dali.shzxlz.cn/Article/details/gt2nfqqvejj.html

el.addEventListener("click", e => {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2nadszssc.html

[U100] JS：DOM 查询
来源：http://dali.ivvv.top/Article/details/gt2clunsyzo.html

document.querySelector(".item")
来源：http://dali.hnqzz.top/Article/details/gt2dzdllbyk.html

[U101] JS：classList 操作
来源：http://dali.jinqigfzy.top/Article/details/gt2vnrhsgkd.html

el.classList.toggle("active")
来源：http://dali.havefunace.top/Article/details/gt2kjntlhnf.html

[U102] JS：本地存储
来源：http://dali.yueranfly.top/Article/details/gt2qwyjxcty.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aizwys.cn/Article/details/gt2gbgyvphi.html

[U103] JS：定时器
来源：http://dali.dashuyun.cn/Article/details/gt2zbwmelho.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenlongwang.top/Article/details/gt2worakhng.html

[U104] JS：防抖
来源：http://dali.jlsjyb.cn/Article/details/gt2weztovhf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2xfjyiatk.html

[U105] JS：节流
来源：http://dali.yangfankeji.com/Article/details/gt2enftmgeb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuxming.cn/Article/details/gt2lvvkudzz.html

[U106] JS：日期格式化
来源：http://dali.pycfn.com/Article/details/gt2mgoqbbwu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fengsongda.top/Article/details/gt2yitoopid.html

[U107] JS：数字千分位
来源：http://dali.hammf.cn/Article/details/gt2ycpppxzf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gzhubu.top/Article/details/gt2xpevfqum.html

[U108] JS：随机整数
来源：http://dali.kuanghao11.cn/Article/details/gt2inrylxnj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.haohaochexian.top/Article/details/gt2yznlqsky.html

[U109] JS：数组分组
来源：http://dali.yongpay.top/Article/details/gt2hmxhymhn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gt2wnkmbcry.html

[U110] JS：数组分块
来源：http://dali.jlsjyb.cn/Article/details/gt2yxjeaumv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srvlqvpf.html

[U111] JS：对象转 Map
来源：http://dali.yuanzhike.top/Article/details/gt2qfnzzsgj.html

new Map(Object.entries(obj))
来源：http://dali.vqdsnc.cn/Article/details/gt2azpvqpxv.html

[U112] JS：字符串补位
来源：http://dali.yuxming.cn/Article/details/gt2boousjqq.html

"7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2itpvizli.html

[U113] JS：正则替换全部
来源：http://dali.zdqjudy.top/Article/details/gt2onkevmkx.html

s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2niqbgsng.html

[U114] JS：JSON 深比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzrsurcc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kolctnam.html

[U115] JS：生成 UUID
来源：http://dali.iojbl.cn/Article/details/gt2mainzvmp.html

crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gt2lnvyfopp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yuxming.cn/Article/details/gt2hymlfnmp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jqgfzy.top/Article/details/gt2wbmbcnbm.html

[U117] JS：单元测试
来源：http://dali.zhengqikj.top/Article/details/gt2cumnaqoa.html

npm i -D vitest;  npx vitest
来源：http://dali.ppjwa.cn/Article/details/gt2ruxvgggu.html

[U118] JS：开发服务器
来源：http://dali.zhengqikj.top/Article/details/gt2uoizxjtb.html

npm i -D vite;  npx vite
来源：http://dali.snrcjt.cn/Article/details/gt2ixuaxovh.html

[U119] JS：生产构建
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spzgdjmb.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gt2bagxgwac.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tian-w.cn/Article/details/gt2vnyjdvol.html

import.meta.env.VITE_API_URL
来源：http://dali.zhixingplan.top/Article/details/gt2oanolorm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2pcoghsxo.html

统计汇总
来源：http://dali.gaohongyu789.top/Article/details/gt2djpxaixf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2wodljcuw.html

按语言统计（条）：
来源：http://dali.sufxvd.cn/Article/details/gt2efzwqqkl.html

Python ......... 252
来源：http://dali.sweek.top/Article/details/gt2kfgifaaa.html

PHP ............ 252
来源：http://dali.yuxming.cn/Article/details/gt2ozrhbvec.html

JavaScript ..... 252
来源：http://dali.cdnleiting.top/Article/details/gt2zboizcxc.html

TypeScript ..... 212
来源：http://dali.xziqi.cn/Article/details/gt2uamoyehg.html

Java ........... 212
来源：http://dali.ivvv.top/Article/details/gt2bnejdcjd.html

Go ............. 212
来源：http://dali.jyoumei.cn/Article/details/gt2tznlxwmb.html

Ruby ........... 212
来源：http://dali.xinyue.icu/Article/details/gt2kpjoeker.html

C# ............. 212
来源：http://dali.ppjwa.cn/Article/details/gt2anmgjvzt.html

C .............. 30
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxtxmqua.html

C++ ............ 30
来源：http://dali.tanke756.top/Article/details/gt2wstokqvx.html

SQL ............ 90
来源：http://dali.shuidangran.top/Article/details/gt2rwavncyh.html

Bash ........... 80
来源：http://dali.cqqwz.cn/Article/details/gt2cmskicuf.html

Kotlin ......... 15
来源：http://dali.yuanzhike.top/Article/details/gt2iazkeydo.html

Swift .......... 15
来源：http://dali.wangdashe.top/Article/details/gt2wgvgpgap.html

Lua ............ 10
来源：http://dali.haohaochexian.top/Article/details/gt2mkmjuuaj.html

Perl ........... 10
来源：http://dali.svipenyu.cn/Article/details/gt2avprixrs.html

Scala .......... 10
来源：http://dali.guannengcc.top/Article/details/gt2wpyefasa.html

------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gt2krxzumem.html

合计 ........... 2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zynbuzms.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gt2lexgpnbw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gt2sbaldbti.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2vpxtmpod.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gt2ipgwfwsk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gt2tuyudiyt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ybcxt.top/Article/details/gt2gipcgexo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gt2xrojzkib.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gt2achigswd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guowangkeji.top/Article/details/gt2unrjyeuk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gt2qtxujhkt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqjzetwm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gt2tgffrcpn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gt2eezanwcy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2rhjghbcw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gt2lcrjelku.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhoulong.xyz/Article/details/gt2gzgvasbb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2uzfskkxh.html

Q SQL 专题                              90
来源：http://dali.dianchejie.cn/Article/details/gt2hynjffdr.html

R Bash 专题                             80
来源：http://dali.shangyingyoupin.top/Article/details/gt2bsikreic.html

S C / C++ 专题                          60
来源：http://dali.guannengcc.top/Article/details/gt2pnkuggcr.html

T 其他语言补充                          60
来源：http://dali.smart0.xyz/Article/details/gt2uhgmitfv.html

U 高频实用片段                         120
来源：http://dali.dianchejie.cn/Article/details/gt2vsgehxzq.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gt2vayftwca.html

合计                                  2106 条
来源：http://dali.ppjwa.cn/Article/details/gt2tazoupaa.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gt2rucewemj.html

使用提醒
来源：http://dali.zhiwuduotai.top/Article/details/gt2abnqeilt.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gt2cthctzfn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxleomzq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tanke756.top/Article/details/gt2adauqeoz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fcnjtwro.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.haohaochexian.top/Article/details/gt2gmfhcdoa.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangdashe.top/Article/details/gt2teqznpvv.html

—— 文件结束 ——
来源：http://dali.zhixingplan.top/Article/details/gt2mayvzsuh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2srjuwjlr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yanxiufei.cn/Article/details/gt2slvfzxaf.html

Common Programming Examples Cheat Book
来源：http://dali.ivvv.top/Article/details/gt2mcmthdhf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2zrrnolpv.html

【收录内容】
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdsrvmyp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hnqzz.top/Article/details/gt2ytqmdlqw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yongpay.top/Article/details/gt2ylziixzh.html

SQL · Bash · C · C++
来源：http://dali.shzxlz.cn/Article/details/gt2dwvrkkwp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hnxiangtu.top/Article/details/gt2eemauvtc.html

【使用说明】
来源：http://dali.gogol.net.cn/Article/details/gt2zzautjtl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cheryme.top/Article/details/gt2iiwekgsd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jianghu66.top/Article/details/gt2eyunixnw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hysaishi.cn/Article/details/gt2jeuwhyyd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ehwqpu.com/Article/details/gt2tztvbchy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dianchejie.cn/Article/details/gt2bpxhvbbe.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gotoacloud.top/Article/details/gt2cwigngyx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.fengsongda.top/Article/details/gt2jdhqxaqa.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yongpay.top/Article/details/gt2kbasdxlv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.c1oappe.top/Article/details/gt2glajwpyy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.meibo888.top/Article/details/gt2rhrtzijv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sysykeji.top/Article/details/gt2xstgvvem.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhoulong.xyz/Article/details/gt2eublxqvb.html

【文件统计】
来源：http://dali.yj202588.top/Article/details/gt2lapujwta.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdoufuyp.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gt2kmdnfmuu.html

目  录
来源：http://dali.hysaishi.cn/Article/details/gt2adbunyin.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2algqonar.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2xfpvnkue.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2nikwbvig.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gt2mfznonxn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tianlin.xyz/Article/details/gt2xtwusxzl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2yybgqnui.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sweek.top/Article/details/gt2cilmyuom.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gt2wwzjmigv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenlongwang.top/Article/details/gt2tkevqqyq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gt2lfdgjgol.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cdnleiting.top/Article/details/gt2oumcvtft.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gt2shcfknqf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gt2entxkuzf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gt2dwdouaik.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xinyue.icu/Article/details/gt2pxwnnmfr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yonumen.top/Article/details/gt2aaiuluey.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gt2mjmtuesj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hammf.cn/Article/details/gt2flsauhwg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shuidangran.top/Article/details/gt2ytxirgig.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzqdysta.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gt2ucvrhgtv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yuwwozkg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2uywgthen.html

A. 基础语法与类型
来源：http://dali.tanke756.top/Article/details/gt2hhzkqrtl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2nstlzssj.html

[A01] Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2ucdsqzab.html

Py:   print("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gt2erjhnquy.html

PHP:  echo "Hello, World!";
来源：http://dali.jqgfzy.top/Article/details/gt2lztwdeob.html

JS:   console.log("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klvwnomp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytejapiw.html

Java: System.out.println("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gt2ggkxfgdv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yanxiufei.cn/Article/details/gt2grkjfjin.html

Ruby: puts "Hello, World!"
来源：http://dali.shuidangran.top/Article/details/gt2veofssxf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gt2nesbjobp.html

[A02] 变量声明与赋值
来源：http://dali.nwbrower.top/Article/details/gt2hvqendzt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.snrcjt.cn/Article/details/gt2dqjimser.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shuidangran.top/Article/details/gt2qnmttnms.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yangfankeji.com/Article/details/gt2bxzymxrs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangdashe.top/Article/details/gt2twnwvydf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gt2qgyuwdrb.html

Go:   name := "Alex"; age := 20
来源：http://dali.quarkkingdee.top/Article/details/gt2iaqrkfmf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcineen.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yuxming.cn/Article/details/gt2xgbnaklo.html

[A03] 常量定义
来源：http://dali.aizwys.cn/Article/details/gt2wyrhrltk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gotoacloud.top/Article/details/gt2jzdxucbl.html

PHP:  const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2ofppegfq.html

JS:   const PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2gpwhhyse.html

TS:   const PI: number = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2dxysrpcq.html

Java: static final double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2miiwmltq.html

Go:   const PI = 3.14159
来源：http://dali.birdmap.top/Article/details/gt2kflihzml.html

Ruby: PI = 3.14159
来源：http://dali.tian-w.cn/Article/details/gt2fkanvjlg.html

C#:   const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2usslyhuc.html

[A04] 判断变量类型
来源：http://dali.daxiang520.top/Article/details/gt2armdrrtx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tchkvnio.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkvjccls.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.fengsongda.top/Article/details/gt2tvthbadl.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhiwuduotai.top/Article/details/gt2esylplyc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.316326.xyz/Article/details/gt2mydtpwll.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.meibo888.top/Article/details/gt2ekabyvci.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.dashuyun.cn/Article/details/gt2gfwptzfe.html

C#:   x.GetType().Name; x is int
来源：http://dali.hysaishi.cn/Article/details/gt2qwizalax.html

[A05] 整数除法与取模
来源：http://dali.cheryme.top/Article/details/gt2jpdkahge.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.quarkkingdee.top/Article/details/gt2bmetntjy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2uvzldrri.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gt2yqolabfp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2apsajvvg.html

Java: 7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gt2ceqgkmps.html

Go:   7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2liylqyju.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gt2ujkohziw.html

C#:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2fbqpthuv.html

[A06] 字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gt2wfcwdhku.html

Py:   int("42"); float("3.14")
来源：http://dali.aibaodan.cn/Article/details/gt2fublnovp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wphepndw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhongyouzk.top/Article/details/gt2qghoyzec.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.c1oappe.top/Article/details/gt2fyvcknuw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenzaomai.com/Article/details/gt2dterhlnf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wekgykoe.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hfpthk.cn/Article/details/gt2mdwjmbtk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenzaomai.com/Article/details/gt2fyklapsi.html

[A07] 数字转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2xfmmmfio.html

Py:   str(42)
来源：http://dali.hnxiangtu.top/Article/details/gt2rqknofue.html

PHP:  (string) 42; strval(42)
来源：http://dali.zdqjudy.top/Article/details/gt2wbhxstwz.html

JS:   String(42); (42).toString()
来源：http://dali.yuxming.cn/Article/details/gt2veetrgpw.html

TS:   String(42)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxhlfxwt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.aizwys.cn/Article/details/gt2zozwswjw.html

Go:   strconv.Itoa(42)
来源：http://dali.sufxvd.cn/Article/details/gt2lmwriidj.html

Ruby: 42.to_s
来源：http://dali.gogol.net.cn/Article/details/gt2aguimgik.html

C#:   42.ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2htkhazmx.html

[A08] 取整与四舍五入
来源：http://dali.zycfv.cn/Article/details/gt2wwkyedcv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gt2klfgqdnb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yanxiufei.cn/Article/details/gt2jirewieq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gt2wsyglztp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hnxiangtu.top/Article/details/gt2hgthwuvt.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gt2nwbqdvyn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gt2dnmypeaf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shzxlz.cn/Article/details/gt2sutjudtb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gt2dvuhrvvz.html

[A09] 绝对值与最大最小值
来源：http://dali.cashguo.top/Article/details/gt2kezqevhp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2nfelozav.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2iyowevft.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yj20258888.top/Article/details/gt2mqasftby.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbfbnkzl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gt2plznqtir.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jiagoushi.top/Article/details/gt2ocnpxhwy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.smart0.xyz/Article/details/gt2tseurrdd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2agrtgmfm.html

[A10] 生成随机数
来源：http://dali.meibo888.top/Article/details/gt2roeymggm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hnqzz.top/Article/details/gt2vhwutaph.html

PHP:  random_int(1, 100);
来源：http://dali.fengsongda.top/Article/details/gt2yzixivsg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jiagoushi.top/Article/details/gt2rhdsbvlw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinqigfzy.top/Article/details/gt2mtyqezmi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.tianlin.xyz/Article/details/gt2rrbjfzcs.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.kuanghao11.cn/Article/details/gt2srydalqn.html

Ruby: rand(1..100)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idacnnmt.html

C#:   new Random().Next(1, 101)
来源：http://dali.jyoumei.cn/Article/details/gt2tmpxtqvm.html

[A11] 条件表达式（三元）
来源：http://dali.redwolf501.top/Article/details/gt2zewbiexf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cdnleiting.top/Article/details/gt2hbflkvbs.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gt2enmaufam.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dljbvyfn.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vavfhwgt.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gt2fkgzffdd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jlsjyb.cn/Article/details/gt2khnjlfvd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gt2ckeywrcd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebwgojld.html

[A12] 字符串插值 / 格式化
来源：http://dali.snrcjt.cn/Article/details/gt2ndoloxls.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yvedp.cn/Article/details/gt2knaluami.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxatqink.html

JS:   `Hello, ${name}!`
来源：http://dali.cashguo.top/Article/details/gt2wyrxhkta.html

TS:   `Hello, ${name}!`
来源：http://dali.zhiwuduotai.top/Article/details/gt2aizcuzpt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xziqi.cn/Article/details/gt2lgclzfua.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.sxryk.cn/Article/details/gt2jtofhidz.html

Ruby: "Hello, #{name}!"
来源：http://dali.hysaishi.cn/Article/details/gt2vdjmxcwk.html

C#:   $"Hello, {name}!"
来源：http://dali.hnxiangtu.top/Article/details/gt2ifijlcda.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nanxuanxn.top/Article/details/gt2ophuozyj.html

Py:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gt2vbvcbfzg.html

PHP:  "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gt2jbeimfza.html

JS:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gt2mjtvnymh.html

TS:   "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gt2gyoiplkn.html

Java: "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gt2drtggmhi.html

Go:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idnwuffe.html

Ruby: "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2ujxgtozy.html

C#:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gt2zaohauqh.html

[A14] 注释写法
来源：http://dali.xziqi.cn/Article/details/gt2cojiicjj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjamxvwo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gt2wfjxzdjb.html

JS:   // 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gt2qkwdjfzi.html

TS:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gt2mfquqofo.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yonumen.top/Article/details/gt2kgcoquxl.html

Go:   // 单行；/* 多行 */
来源：http://dali.fzhhl.top/Article/details/gt2mlxkftwk.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.havefunace.top/Article/details/gt2kdcucjsg.html

C#:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gt2yiugfkkl.html

[A15] 空值判断与默认值
来源：http://dali.hnxiangtu.top/Article/details/gt2xdbxvrxn.html

Py:   value = data or "默认值"
来源：http://dali.tanke756.top/Article/details/gt2wugdeggl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xinyue.icu/Article/details/gt2itsmrbpr.html

JS:   const value = data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gt2xrjpguqc.html

TS:   const value = data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfnklciw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ybcxt.top/Article/details/gt2xcpnofgf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.birdmap.top/Article/details/gt2ozocwaon.html

Ruby: value = data || "默认值"
来源：http://dali.cqqwz.cn/Article/details/gt2esbezbmd.html

C#:   var value = data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gt2dytpysvw.html

[A16] 真假值判断规则
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdwdfdse.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.havefunace.top/Article/details/gt2cecaelwr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.nwbrower.top/Article/details/gt2xopezpmu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nwbrower.top/Article/details/gt2slvpjgmh.html

TS:   if (!x) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2kdnlyjdq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.gzhubu.top/Article/details/gt2zpcnxgdn.html


<!-- 参考信息 -->