代发 wailian999

[U87] JS：解构默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtourhivry.html

const { a = 1, b = 2 } = obj;
来源：http://dali.pycfn.com/Article/details/gtlstdmmtj.html

[U88] JS：对象展开合并
来源：http://dali.jlsjyb.cn/Article/details/gthsxmsfsp.html

{ ...a, ...b }
来源：http://dali.yangfankeji.com/Article/details/gtpwqdjfdc.html

[U89] JS：数组去重
来源：http://dali.yj20258888.top/Article/details/gtbzkulsjh.html

[...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtqridkgpl.html

[U90] JS：数字数组排序
来源：http://dali.vqdsnc.cn/Article/details/gtwsozofqg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsahoglmj.html

[U91] JS：对象键值遍历
来源：http://dali.yanxiufei.cn/Article/details/gtzimrpwue.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guannengcc.top/Article/details/gtublzteqa.html

[U92] JS：深拷贝
来源：http://dali.guannengcc.top/Article/details/gtkbcnhcqc.html

structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtbpqfphau.html

[U93] JS：模板字符串
来源：http://dali.tanke756.top/Article/details/gtqajambtg.html

`共 ${n} 条`
来源：http://dali.xylfe.cn/Article/details/gtgsroptrw.html

[U94] JS：箭头函数
来源：http://dali.mhx1999.top/Article/details/gtfpatzxiy.html

const double = x => x * 2;
来源：http://dali.jinqigfzy.top/Article/details/gtydgokxfv.html

[U95] JS：Promise 包装
来源：http://dali.wangdashe.top/Article/details/gtzkkpfdcm.html

new Promise((resolve, reject) => {})
来源：http://dali.redwolf501.top/Article/details/gtbxtxfked.html

[U96] JS：async/await 与异常
来源：http://dali.yuxming.cn/Article/details/gtpopqsjhm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtnmyodunj.html

[U97] JS：并发请求
来源：http://dali.pengpengdd.cyou/Article/details/gtjtxfydhg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtsbkgpgpx.html

[U98] JS：fetch 带 JSON
来源：http://dali.tian-w.cn/Article/details/gtvqhtnpjg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xziqi.cn/Article/details/gtqbresklp.html

[U99] JS：事件监听
来源：http://dali.feifeiyinyue.top/Article/details/gtnjfdlwff.html

el.addEventListener("click", e => {})
来源：http://dali.vqdsnc.cn/Article/details/gtesluyhxy.html

[U100] JS：DOM 查询
来源：http://dali.yj20258888.top/Article/details/gtqfaweket.html

document.querySelector(".item")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgrihntc.html

[U101] JS：classList 操作
来源：http://dali.ehwqpu.com/Article/details/gthehngpok.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijoobdcu.html

[U102] JS：本地存储
来源：http://dali.zhongyouzk.top/Article/details/gtiejbrctf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gttftiqzkc.html

[U103] JS：定时器
来源：http://dali.daxiang520.top/Article/details/gtfwhqoboy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.birdmap.top/Article/details/gtqqkfdadt.html

[U104] JS：防抖
来源：http://dali.pengpengdd.cyou/Article/details/gtrvkwrknc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtmqghqdoc.html

[U105] JS：节流
来源：http://dali.hnxiangtu.top/Article/details/gtjvnioiaq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fzhhl.top/Article/details/gtsuoafquz.html

[U106] JS：日期格式化
来源：http://dali.hnqzz.top/Article/details/gtaskbtcwi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.c1oappe.top/Article/details/gtmaunobwq.html

[U107] JS：数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtnfjmlrtz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtcxxmhjdy.html

[U108] JS：随机整数
来源：http://dali.sxryk.cn/Article/details/gtuwjtxana.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.wangshuangyany.cn/Article/details/gtnpenhogp.html

[U109] JS：数组分组
来源：http://dali.hywenlv.cn/Article/details/gttgzvepbq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtsmyglqlj.html

[U110] JS：数组分块
来源：http://dali.feifeiyinyue.top/Article/details/gtepdywlcb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jlsjyb.cn/Article/details/gtoacvlwkj.html

[U111] JS：对象转 Map
来源：http://dali.hammf.cn/Article/details/gtnmtdaaod.html

new Map(Object.entries(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukcewwtf.html

[U112] JS：字符串补位
来源：http://dali.smart0.xyz/Article/details/gtnzzhbxod.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtysxbsrwt.html

[U113] JS：正则替换全部
来源：http://dali.meibo888.top/Article/details/gtwfcamauw.html

s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtoccjtupo.html

[U114] JS：JSON 深比较
来源：http://dali.cashguo.top/Article/details/gtunxteaah.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gtyvqjmcqa.html

[U115] JS：生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyrhldob.html

crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtetxpoecw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yuxming.cn/Article/details/gtehiyquxo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.iojbl.cn/Article/details/gtlvxbpuij.html

[U117] JS：单元测试
来源：http://dali.nanxinkj.top/Article/details/gtlvnifshr.html

npm i -D vitest;  npx vitest
来源：http://dali.9152youxi.cn/Article/details/gtjipnnqow.html

[U118] JS：开发服务器
来源：http://dali.snrcjt.cn/Article/details/gthhglblvi.html

npm i -D vite;  npx vite
来源：http://dali.yuxming.cn/Article/details/gtejdtsrqt.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gtgfeeikmc.html

npx vite build
来源：http://dali.cheryme.top/Article/details/gtnkloaccq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gtawigpskm.html

import.meta.env.VITE_API_URL
来源：http://dali.chenzaomai.com/Article/details/gtdxdbbzta.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrvsedhcb.html

统计汇总
来源：http://dali.jianghu66.top/Article/details/gtehmzigdv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtidbmumwq.html

按语言统计（条）：
来源：http://dali.hfpthk.cn/Article/details/gtodewxjyu.html

Python ......... 252
来源：http://dali.xuetiantiany.cn/Article/details/gtgbpjllat.html

PHP ............ 252
来源：http://dali.snrcjt.cn/Article/details/gtqgqgzpxw.html

JavaScript ..... 252
来源：http://dali.hongshengwenyu.top/Article/details/gtlkcgndbc.html

TypeScript ..... 212
来源：http://dali.yuxming.cn/Article/details/gtdebevfup.html

Java ........... 212
来源：http://dali.svipenyu.cn/Article/details/gtonjwquaz.html

Go ............. 212
来源：http://dali.zhengqikj.top/Article/details/gtitrmplsk.html

Ruby ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gticxuqypl.html

C# ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwdimyfa.html

C .............. 30
来源：http://dali.jqgfzy.top/Article/details/gtxtebukaz.html

C++ ............ 30
来源：http://dali.tanke756.top/Article/details/gtsfuhbicm.html

SQL ............ 90
来源：http://dali.guannengcc.top/Article/details/gtljwdvnpi.html

Bash ........... 80
来源：http://dali.bjfxy.top/Article/details/gtspcdaots.html

Kotlin ......... 15
来源：http://dali.cheryme.top/Article/details/gtuklnjrnb.html

Swift .......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gttmlbwdhx.html

Lua ............ 10
来源：http://dali.jiagoushi.top/Article/details/gtynsynjgk.html

Perl ........... 10
来源：http://dali.xuetiantiany.cn/Article/details/gtqsyksffu.html

Scala .......... 10
来源：http://dali.ehwqpu.com/Article/details/gtkthlelgt.html

------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtjkbrynxw.html

合计 ........... 2106 条
来源：http://dali.ivvv.top/Article/details/gtqbolntnv.html

按章节统计：
来源：http://dali.ybcxt.top/Article/details/gtbhruzunc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gtucefpxua.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtcqoevncu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtmupafcdp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gtydllwwkj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fengsongda.top/Article/details/gtjhjleiyo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gtpxwmnjdv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gtifwdcmck.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gtgtdhorof.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtwsvumpph.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gttpxfjlnq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtzfdpuigl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtqprgqsyc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtrsgwnxwz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtosjjzsbm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guannengcc.top/Article/details/gtynqtrhji.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtqrxrcrfb.html

Q SQL 专题                              90
来源：http://dali.cheryme.top/Article/details/gtruabikul.html

R Bash 专题                             80
来源：http://dali.ybcxt.top/Article/details/gtpjgzbsos.html

S C / C++ 专题                          60
来源：http://dali.andypj.xyz/Article/details/gtuamhtcqz.html

T 其他语言补充                          60
来源：http://dali.ivvv.top/Article/details/gtzkqrfgyd.html

U 高频实用片段                         120
来源：http://dali.svipenyu.cn/Article/details/gtlqyhrbiq.html

------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtjngkbxek.html

合计                                  2106 条
来源：http://dali.ppjwa.cn/Article/details/gtmnwriqpw.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtmyfdhooz.html

使用提醒
来源：http://dali.chenjidiqi.icu/Article/details/gtguseublu.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtcvacsvex.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxuanxn.top/Article/details/gtyovycxnd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.iojbl.cn/Article/details/gtljacxsyw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yanxiufei.cn/Article/details/gtegbykolf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhongyouzk.top/Article/details/gthjcudfod.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigfzy.top/Article/details/gtwzilsoxk.html

—— 文件结束 ——
来源：http://dali.jinqigufen.top/Article/details/gtneeqooix.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjdunzhnh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sufxvd.cn/Article/details/gtebddfebw.html

Common Programming Examples Cheat Book
来源：http://dali.svipenyu.cn/Article/details/gtvuqueyrc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtgoiyjquf.html

【收录内容】
来源：http://dali.aibaodan.cn/Article/details/gtcuudcqll.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.pengpengdd.cyou/Article/details/gthrkqxpsh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ybcxt.top/Article/details/gtgiqawpqa.html

SQL · Bash · C · C++
来源：http://dali.jqgufenzy.top/Article/details/gtbusjmyui.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ydzc1.top/Article/details/gtkxwozahx.html

【使用说明】
来源：http://dali.zhongyouzk.top/Article/details/gtnonuxdum.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhiwuduotai.top/Article/details/gtajpckdhj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.pengpengdd.cyou/Article/details/gtaqrjbyjv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.tianlin.xyz/Article/details/gtajgqdswm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yongpay.top/Article/details/gtununspzs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.0kj1m.cn/Article/details/gtwrtwgbvz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ydzc1.top/Article/details/gtcspvqfpa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnqzz.top/Article/details/gtptuyutnt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknedsuav.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.pengpengdd.cyou/Article/details/gthtlqqwog.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xuanzx.com/Article/details/gtakcociur.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hongshengwenyu.top/Article/details/gtssjtvczh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.bjfxy.top/Article/details/gtapqytmfu.html

【文件统计】
来源：http://dali.sxryk.cn/Article/details/gtnnuyvptl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhiwuduotai.top/Article/details/gtgfevbrrl.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gteliimzub.html

目  录
来源：http://dali.316326.xyz/Article/details/gtecxvlmos.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtdehsizrc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gtweexfoyu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gtwzlrbqwl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gtifyoptjx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbeffdsgh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yangfankeji.com/Article/details/gtjrxymqwu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hywenlv.cn/Article/details/gtqkqzinwf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gtycpggkng.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gtswtfanit.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtiaobqftt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258.top/Article/details/gtjzwrebiv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxqypvph.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtxbxlydnu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gthmjbtfip.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gthmsntfoz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hysaishi.cn/Article/details/gtopgozgjp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtqptaggwm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.snrcjt.cn/Article/details/gtkusicnrl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtimjiomqr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xziqi.cn/Article/details/gtyvekvent.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gtfppeibal.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jianghu66.top/Article/details/gtmiqntccs.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtltmgkcwt.html

A. 基础语法与类型
来源：http://dali.sweek.top/Article/details/gtmdkknvwd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvodhfja.html

[A01] Hello World
来源：http://dali.yvedp.cn/Article/details/gtjtivqwsy.html

Py:   print("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gtbecurbsg.html

PHP:  echo "Hello, World!";
来源：http://dali.cashguo.top/Article/details/gtujormfgt.html

JS:   console.log("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gtalgaanrk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.guannengcc.top/Article/details/gtnrisbtzq.html

Java: System.out.println("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gtuymreksn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nanxinkj.top/Article/details/gtlgybxuyr.html

Ruby: puts "Hello, World!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmkwtjxn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gtedidpjyw.html

[A02] 变量声明与赋值
来源：http://dali.yuanzhike.top/Article/details/gtxjrrbifc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinghuilouyu.cn/Article/details/gthdtsiwse.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gtypbpmjla.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shuidangran.top/Article/details/gtqoswmcss.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sufxvd.cn/Article/details/gtbstgnhbm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtpxkfeyuf.html

Go:   name := "Alex"; age := 20
来源：http://dali.gotoacloud.top/Article/details/gtexqlyqwh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cqqwz.cn/Article/details/gthkqjupbu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtzmrqaaaq.html

[A03] 常量定义
来源：http://dali.havefunace.top/Article/details/gtjgvbivhq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.kuanghao11.cn/Article/details/gtllzpykru.html

PHP:  const PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtgzypfjxb.html

JS:   const PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtvvsbwryo.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtvtelvgjy.html

Java: static final double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtgspuzlrs.html

Go:   const PI = 3.14159
来源：http://dali.sweek.top/Article/details/gtdntkcuhe.html

Ruby: PI = 3.14159
来源：http://dali.gzhubu.top/Article/details/gtzalzsiyw.html

C#:   const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtwmynjxpp.html

[A04] 判断变量类型
来源：http://dali.hywenlv.cn/Article/details/gthpkvvyoe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.kuanghao11.cn/Article/details/gtypmorxqs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cheryme.top/Article/details/gtsbmaqvgf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gaohongyu789.top/Article/details/gtmfucfvfz.html

TS:   typeof x; x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gtftmgdbvf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.redwolf501.top/Article/details/gtvczckqnr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yanxiufei.cn/Article/details/gtfoqonpys.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.guowangkeji.top/Article/details/gtjeiqgdza.html

C#:   x.GetType().Name; x is int
来源：http://dali.jyoumei.cn/Article/details/gtuobplhev.html

[A05] 整数除法与取模
来源：http://dali.ivvv.top/Article/details/gtquvzriqv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.snrcjt.cn/Article/details/gtqqxjlldf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtkilvvzha.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gthaubqjxz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtvylblsac.html

Java: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtfcaezbey.html

Go:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtchbdnxbt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtwiikaing.html

C#:   7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtmgxoqndw.html

[A06] 字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gtbyajymsi.html

Py:   int("42"); float("3.14")
来源：http://dali.cqqwz.cn/Article/details/gtjrixokie.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.guannengcc.top/Article/details/gtfsolmgwz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yuanzhike.top/Article/details/gtstyatycz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.tanke756.top/Article/details/gtxxnclcax.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ydzc1.top/Article/details/gtpscqihci.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.pycfn.com/Article/details/gtwlwkqhfs.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shangyingyoupin.top/Article/details/gtqmoaadsq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gteiqrwkyq.html

[A07] 数字转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtqkyvngtr.html

Py:   str(42)
来源：http://dali.nanxuanxn.top/Article/details/gttzarasea.html

PHP:  (string) 42; strval(42)
来源：http://dali.yuanzhike.top/Article/details/gtfdqudsaf.html

JS:   String(42); (42).toString()
来源：http://dali.sysykeji.top/Article/details/gtbrbgpxav.html

TS:   String(42)
来源：http://dali.havefunace.top/Article/details/gtvlobvkkn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.guowangkeji.top/Article/details/gtejwcawpy.html

Go:   strconv.Itoa(42)
来源：http://dali.chenlongwang.top/Article/details/gtanqcitwb.html

Ruby: 42.to_s
来源：http://dali.haohaochexian.top/Article/details/gtaklzyzch.html

C#:   42.ToString()
来源：http://dali.redwolf501.top/Article/details/gtlobbbtnf.html

[A08] 取整与四舍五入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnaxantyk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtfckvzhnn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.pengpengdd.cyou/Article/details/gtlvzcveah.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtclsnscmk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangshuangyany.cn/Article/details/gtuyejwycu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtstdknpdt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtqcscskwz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cqqwz.cn/Article/details/gtkplssyvl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gttbfxrcwm.html

[A09] 绝对值与最大最小值
来源：http://dali.dianchejie.cn/Article/details/gtdavjsjfa.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtvoskmglf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtdtbtcgae.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtsiblctzk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtqlewntvg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtseuvqwga.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dashuyun.cn/Article/details/gtfaysdtkb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ybcxt.top/Article/details/gtspdhqjth.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yonumen.top/Article/details/gtervbpsra.html

[A10] 生成随机数
来源：http://dali.andypj.xyz/Article/details/gtpfmdhvtr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yvedp.cn/Article/details/gtqyfjeced.html

PHP:  random_int(1, 100);
来源：http://dali.pycfn.com/Article/details/gtvaqwgzav.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yuanzhike.top/Article/details/gtfibdpkaq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cashguo.top/Article/details/gthqyfrcuk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.iojbl.cn/Article/details/gtutnvapjo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yuanzhike.top/Article/details/gtrtlarbio.html

Ruby: rand(1..100)
来源：http://dali.zycfv.cn/Article/details/gtgysupucr.html

C#:   new Random().Next(1, 101)
来源：http://dali.hnxiangtu.top/Article/details/gtzjyrfxjw.html

[A11] 条件表达式（三元）
来源：http://dali.feifeiyinyue.top/Article/details/gtmfxlmrph.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yongpay.top/Article/details/gtrdywmvpx.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gtocomkaje.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gttuzhgvie.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gtmmdsephx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gtvceamkvw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrijrymw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gtveqbgkvi.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtimmiargp.html

[A12] 字符串插值 / 格式化
来源：http://dali.hfpthk.cn/Article/details/gtejhiwoiw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shuidangran.top/Article/details/gtmaygncbt.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjmqybkj.html

JS:   `Hello, ${name}!`
来源：http://dali.dianchejie.cn/Article/details/gtsnojiqoy.html

TS:   `Hello, ${name}!`
来源：http://dali.snrcjt.cn/Article/details/gtnaxmklbf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jqgufenzy.top/Article/details/gtdarocrkc.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jianghu66.top/Article/details/gtsxbznjwy.html

Ruby: "Hello, #{name}!"
来源：http://dali.haohaochexian.top/Article/details/gtsntxhnic.html

C#:   $"Hello, {name}!"
来源：http://dali.feifeiyinyue.top/Article/details/gtmhpnsfcx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.pengpengdd.cyou/Article/details/gtulvrcfoo.html

Py:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtnzdrniqk.html

PHP:  "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gteispkwcx.html

JS:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gtjdyssajt.html

TS:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gttflomyyz.html

Java: "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtkzmkgvip.html

Go:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtbuntudxr.html

Ruby: "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvswuulf.html

C#:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtexakqcgi.html

[A14] 注释写法
来源：http://dali.wangshuangyany.cn/Article/details/gtiskuqnqr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gotoacloud.top/Article/details/gtwndxufxc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gtsvgsnkdy.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtskjpoqum.html

TS:   // 单行；/* 多行 */
来源：http://dali.chenlongwang.top/Article/details/gtmxvalxmv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ybcxt.top/Article/details/gtxwqevzmj.html

Go:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gthsliehec.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.chenlongwang.top/Article/details/gtfwygzqxo.html


<!-- 参考信息 -->