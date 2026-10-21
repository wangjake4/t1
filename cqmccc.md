代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.svipenyu.cn/Article/details/gthtmuxhzx.html

composer require psr/container
来源：http://dali.guannengcc.top/Article/details/gthrvmgsqe.html

[U76] PHP：简单路由
来源：http://dali.birdmap.top/Article/details/gtdrryvtxh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tianlin.xyz/Article/details/gtfsvfvrpk.html

[U77] PHP：模板渲染
来源：http://dali.sufxvd.cn/Article/details/gtpnungrnj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gtjvgqzrdv.html

[U78] PHP：单元测试
来源：http://dali.tanke756.top/Article/details/gtxgrnvcmf.html

composer require --dev phpunit/phpunit
来源：http://dali.yangfankeji.com/Article/details/gtikbxmnsx.html

[U79] PHP：静态分析
来源：http://dali.fzhhl.top/Article/details/gtmdzlnifq.html

composer require --dev phpstan/phpstan
来源：http://dali.fengsongda.top/Article/details/gtgcbbzbrr.html

[U80] PHP：代码规范修复
来源：http://dali.zycfv.cn/Article/details/gtfubdynag.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgufenzy.top/Article/details/gtzuxkrrsf.html

[U81] JS：初始化项目
来源：http://dali.jianghu66.top/Article/details/gthzeijvfa.html

npm init -y;  npm i express
来源：http://dali.gotoacloud.top/Article/details/gtqsbhzesq.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gtloiblnlr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hywenlv.cn/Article/details/gtoihncheu.html

[U83] JS：ES Module 导入导出
来源：http://dali.daria6918.cn/Article/details/gtjfaerabh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjvylvbp.html

[U84] JS：CommonJS 写法
来源：http://dali.chenzaomai.com/Article/details/gtzfpkgdyh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jqgfzy.top/Article/details/gtotepdhgr.html

[U85] JS：可选链
来源：http://dali.jqgfzy.top/Article/details/gtmmputrvy.html

a?.b?.c
来源：http://dali.mhx1999.top/Article/details/gtrcpwuidx.html

[U86] JS：空值合并
来源：http://dali.yvedp.cn/Article/details/gtuajztuqq.html

a ?? b
来源：http://dali.mhx1999.top/Article/details/gtibgxdypt.html

[U87] JS：解构默认值
来源：http://dali.gzhubu.top/Article/details/gtmeczygic.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hongshengwenyu.top/Article/details/gtbmzflygi.html

[U88] JS：对象展开合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtlliuykic.html

{ ...a, ...b }
来源：http://dali.gzhubu.top/Article/details/gturqbfcge.html

[U89] JS：数组去重
来源：http://dali.daxiang520.top/Article/details/gtamqqhuos.html

[...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtukdjymjj.html

[U90] JS：数字数组排序
来源：http://dali.shzxlz.cn/Article/details/gtyaubrypa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtvuolxzms.html

[U91] JS：对象键值遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtxenshcmp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztpfyzer.html

[U92] JS：深拷贝
来源：http://dali.mhx1999.top/Article/details/gtntzupgiw.html

structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gthxwptivi.html

[U93] JS：模板字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcarccqgf.html

`共 ${n} 条`
来源：http://dali.pycfn.com/Article/details/gtgggmktif.html

[U94] JS：箭头函数
来源：http://dali.vqdsnc.cn/Article/details/gttviwkfwe.html

const double = x => x * 2;
来源：http://dali.pycfn.com/Article/details/gtwwlyoeor.html

[U95] JS：Promise 包装
来源：http://dali.ppjwa.cn/Article/details/gtiaroetzw.html

new Promise((resolve, reject) => {})
来源：http://dali.tanke756.top/Article/details/gtvdzfahoc.html

[U96] JS：async/await 与异常
来源：http://dali.yvedp.cn/Article/details/gtpadqmuoj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtcihcdmio.html

[U97] JS：并发请求
来源：http://dali.cqqwz.cn/Article/details/gtidzjuype.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtcnchcdzo.html

[U98] JS：fetch 带 JSON
来源：http://dali.ppjwa.cn/Article/details/gtqjgwuwuw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258888.top/Article/details/gtcqsahwnj.html

[U99] JS：事件监听
来源：http://dali.zhengqikj.top/Article/details/gtdkzinved.html

el.addEventListener("click", e => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlszhjzt.html

[U100] JS：DOM 查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfmjocev.html

document.querySelector(".item")
来源：http://dali.gzhubu.top/Article/details/gtzlpkpyoq.html

[U101] JS：classList 操作
来源：http://dali.gogol.net.cn/Article/details/gtxiuxlkfs.html

el.classList.toggle("active")
来源：http://dali.yuanzhike.top/Article/details/gtcggusuvt.html

[U102] JS：本地存储
来源：http://dali.haohaochexian.top/Article/details/gtirestijy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ehwqpu.com/Article/details/gtvqezuffd.html

[U103] JS：定时器
来源：http://dali.jinqigfzy.top/Article/details/gtkxciyowe.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxinkj.top/Article/details/gtfophrvkb.html

[U104] JS：防抖
来源：http://dali.jinqigufen.top/Article/details/gthdazddqo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtizgjbztt.html

[U105] JS：节流
来源：http://dali.zhiwuduotai.top/Article/details/gtelenqmif.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtpljooaht.html

[U106] JS：日期格式化
来源：http://dali.xinyue.icu/Article/details/gtpxcxcrmb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.daxiang520.top/Article/details/gtsfpdssnz.html

[U107] JS：数字千分位
来源：http://dali.redwolf501.top/Article/details/gtirxsxfby.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gtggkcyzto.html

[U108] JS：随机整数
来源：http://dali.0kj1m.cn/Article/details/gthtidxols.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhiajebi.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvgwozgh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtavpeuaqx.html

[U110] JS：数组分块
来源：http://dali.ppjwa.cn/Article/details/gtozptufpu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cheryme.top/Article/details/gtjcyzexsu.html

[U111] JS：对象转 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxcokoeb.html

new Map(Object.entries(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtatqehyrm.html

[U112] JS：字符串补位
来源：http://dali.pycfn.com/Article/details/gtgokiwpqh.html

"7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtyyyiqxvg.html

[U113] JS：正则替换全部
来源：http://dali.hnqzz.top/Article/details/gtgrnmnvoj.html

s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtgideyisw.html

[U114] JS：JSON 深比较
来源：http://dali.hywenlv.cn/Article/details/gtnzaygjyd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gthmwshctd.html

[U115] JS：生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gtfyerrktb.html

crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtantmbixf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cdnleiting.top/Article/details/gtqohuzugw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hammf.cn/Article/details/gtvpuimljz.html

[U117] JS：单元测试
来源：http://dali.daria6918.cn/Article/details/gtmdmzimhf.html

npm i -D vitest;  npx vitest
来源：http://dali.xziqi.cn/Article/details/gtvgdsxcnr.html

[U118] JS：开发服务器
来源：http://dali.aizwys.cn/Article/details/gtpffjzfan.html

npm i -D vite;  npx vite
来源：http://dali.shuidangran.top/Article/details/gtfoejtpun.html

[U119] JS：生产构建
来源：http://dali.ppjwa.cn/Article/details/gtougtcxbp.html

npx vite build
来源：http://dali.zhiwuduotai.top/Article/details/gtxqfnvvra.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gogol.net.cn/Article/details/gteskixjnt.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxinkj.top/Article/details/gttckrzvlj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrqijenil.html

统计汇总
来源：http://dali.hnqzz.top/Article/details/gtjxvwslzp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpmrocilo.html

按语言统计（条）：
来源：http://dali.sufxvd.cn/Article/details/gtzfbjhxuh.html

Python ......... 252
来源：http://dali.xuetiantiany.cn/Article/details/gtoientsbz.html

PHP ............ 252
来源：http://dali.hnxiangtu.top/Article/details/gtbnykxhxr.html

JavaScript ..... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtroqsqgxu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gtmorbeeeq.html

Java ........... 212
来源：http://dali.iojbl.cn/Article/details/gtgdqzkotr.html

Go ............. 212
来源：http://dali.c1oappe.top/Article/details/gtxizqwdqd.html

Ruby ........... 212
来源：http://dali.sweek.top/Article/details/gtummtwwcp.html

C# ............. 212
来源：http://dali.yuanzhike.top/Article/details/gtykgvgecb.html

C .............. 30
来源：http://dali.hammf.cn/Article/details/gtwfcuvlqb.html

C++ ............ 30
来源：http://dali.sysykeji.top/Article/details/gtktyjpqux.html

SQL ............ 90
来源：http://dali.cashguo.top/Article/details/gtgzeestyz.html

Bash ........... 80
来源：http://dali.hammf.cn/Article/details/gtokbhpjeg.html

Kotlin ......... 15
来源：http://dali.jianghu66.top/Article/details/gtunblkvkb.html

Swift .......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gtgqtwibes.html

Lua ............ 10
来源：http://dali.sufxvd.cn/Article/details/gtjpvzcpdc.html

Perl ........... 10
来源：http://dali.dashuyun.cn/Article/details/gtswrwjtug.html

Scala .......... 10
来源：http://dali.0kj1m.cn/Article/details/gtsbjkdxhj.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gtkgvmiczt.html

合计 ........... 2106 条
来源：http://dali.daxiang520.top/Article/details/gtjupyloot.html

按章节统计：
来源：http://dali.gaohongyu789.top/Article/details/gtagdioeuu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.redwolf501.top/Article/details/gtjqdoytcc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gtywygqyvl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gtfafhiigr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedlnyvqm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnqzz.top/Article/details/gtcjgiofsp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gtnlmamztk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gtqvstaesb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtuqgptzam.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtkiqwwimw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gtwedglfwt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtblimpqhu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gthnjifoox.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtbyulscia.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gtycxxdlfq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tanke756.top/Article/details/gthgakcwul.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gttlebwxal.html

Q SQL 专题                              90
来源：http://dali.xziqi.cn/Article/details/gtjhwvtibj.html

R Bash 专题                             80
来源：http://dali.xuetiantiany.cn/Article/details/gtvkdphzah.html

S C / C++ 专题                          60
来源：http://dali.gzhubu.top/Article/details/gtapvkaefz.html

T 其他语言补充                          60
来源：http://dali.xylfe.cn/Article/details/gtcvvxscog.html

U 高频实用片段                         120
来源：http://dali.guowangkeji.top/Article/details/gtlcwrlqnv.html

------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtjenafxfi.html

合计                                  2106 条
来源：http://dali.chenlongwang.top/Article/details/gtoeadeizt.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtijriypzv.html

使用提醒
来源：http://dali.yuxming.cn/Article/details/gtbldtfedp.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtfkkufdvd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cucudq.cn/Article/details/gtihcqqgsv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.9152youxi.cn/Article/details/gtuuppwttk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenzaomai.com/Article/details/gtjllwkqkg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.meibo888.top/Article/details/gtimiskbmr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnqzz.top/Article/details/gtaqdigtna.html

—— 文件结束 ——
来源：http://dali.yj20258888.top/Article/details/gtweddlrbw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtgpxnicdj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.9152youxi.cn/Article/details/gtzcgfkbda.html

Common Programming Examples Cheat Book
来源：http://dali.shanyushiyangtech.top/Article/details/gttgesfmqc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxaukoaah.html

【收录内容】
来源：http://dali.feifeiyinyue.top/Article/details/gtbkdxmzsr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cucudq.cn/Article/details/gteqrekulo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yangfankeji.com/Article/details/gtaddtisge.html

SQL · Bash · C · C++
来源：http://dali.xuetiantiany.cn/Article/details/gtcwbrwzxe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tianlin.xyz/Article/details/gtrifvxsbl.html

【使用说明】
来源：http://dali.jinqigfzy.top/Article/details/gtfeiyxshj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.andypj.xyz/Article/details/gtpluwxeui.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tianlin.xyz/Article/details/gtcakqzoux.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guannengcc.top/Article/details/gtwspeuszo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jiagoushi.top/Article/details/gtylptduaq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nanxuanxn.top/Article/details/gtmqbwupxm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sxryk.cn/Article/details/gtrbddrhjn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.9152youxi.cn/Article/details/gtahmynawk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sxryk.cn/Article/details/gtdtagjsjq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.tanke756.top/Article/details/gtnmcxehhl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gaohongyu789.top/Article/details/gtqmokhxdk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cheryme.top/Article/details/gteinzyncf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yuxming.cn/Article/details/gtmugefvks.html

【文件统计】
来源：http://dali.chenlongwang.top/Article/details/gtgcxnhutp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jlsjyb.cn/Article/details/gtytinzhtd.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gturrmswza.html

目  录
来源：http://dali.hysaishi.cn/Article/details/gtfwdvmqob.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtibjbgnbs.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gttfnqomvp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gtapwnpicv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.fengsongda.top/Article/details/gtraezvqgj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gtzuawrhba.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.dashuyun.cn/Article/details/gthdckrqqv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhengqikj.top/Article/details/gtfdimythi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gtvvmsaqys.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.redwolf501.top/Article/details/gteugtwycr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtgtkhyqvw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shzxlz.cn/Article/details/gteyibskuo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtmaigcqkc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeoiqfsw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtsusiayao.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gtvwbwkkjr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ppjwa.cn/Article/details/gtpbicgsyq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtlghvnwmi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinqigfzy.top/Article/details/gtcttgalpr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtqznboizh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zdqjudy.top/Article/details/gtsdffttup.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcpcmgnk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtclovopqg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnctlndma.html

A. 基础语法与类型
来源：http://dali.zhengqikj.top/Article/details/gtxqphwlhf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtbqgzhbnt.html

[A01] Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtrtohdvyz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gtsqfggaio.html

PHP:  echo "Hello, World!";
来源：http://dali.guannengcc.top/Article/details/gtkbscspmz.html

JS:   console.log("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gtgcukcbxq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqzkvqiw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gtbohgohzb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ehwqpu.com/Article/details/gtwvvnixwg.html

Ruby: puts "Hello, World!"
来源：http://dali.shangyingyoupin.top/Article/details/gtaoowmeod.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gtbaajosmm.html

[A02] 变量声明与赋值
来源：http://dali.yueranfly.top/Article/details/gtakckkrnv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.dianchejie.cn/Article/details/gtlnfytaon.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtlisygtzu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ppjwa.cn/Article/details/gtruuwvevs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yonumen.top/Article/details/gtocxrngnr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqaasvtf.html

Go:   name := "Alex"; age := 20
来源：http://dali.9152youxi.cn/Article/details/gtaaigdjle.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cashguo.top/Article/details/gtgzgvviyc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.9152youxi.cn/Article/details/gtdeqhwrtn.html

[A03] 常量定义
来源：http://dali.nanxuanxn.top/Article/details/gttjpyvzpl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.smart0.xyz/Article/details/gteeewkgyu.html

PHP:  const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtrqdnxdtn.html

JS:   const PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtxtcvflwn.html

TS:   const PI: number = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtmijoiapn.html

Java: static final double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtglcpsnzp.html

Go:   const PI = 3.14159
来源：http://dali.shuidangran.top/Article/details/gtwcvtusta.html

Ruby: PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gtlzrtrxdd.html

C#:   const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtuguzsjnm.html

[A04] 判断变量类型
来源：http://dali.jinqigfzy.top/Article/details/gtytkhklvp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.birdmap.top/Article/details/gtqhospksz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shuidangran.top/Article/details/gttbwbhlpq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sxryk.cn/Article/details/gtlporhhsi.html

TS:   typeof x; x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gtdziltspx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gzhubu.top/Article/details/gteeosuief.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yueranfly.top/Article/details/gtxbetwdls.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xuanzx.com/Article/details/gtfehistpc.html

C#:   x.GetType().Name; x is int
来源：http://dali.cheryme.top/Article/details/gtaquzjvne.html

[A05] 整数除法与取模
来源：http://dali.316326.xyz/Article/details/gtyvogvoxl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yangfankeji.com/Article/details/gtmuplfjcp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtzpshshqe.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gtgjzqwkfa.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtqriawpjk.html

Java: 7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtztscqcoe.html

Go:   7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtyqmbhitq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtsrqgchhq.html

C#:   7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtdinlzywv.html

[A06] 字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gtuxrhdktj.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gtbqqmlocz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhoulong.xyz/Article/details/gtsgqzwpln.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj20258.top/Article/details/gtsigmymkv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.fengsongda.top/Article/details/gtysezrpqq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenzaomai.com/Article/details/gtrpulbeoo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nwbrower.top/Article/details/gtqvgwgsvw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj20258.top/Article/details/gtfpcfsfps.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.fengsongda.top/Article/details/gtxeqfrlgv.html

[A07] 数字转字符串
来源：http://dali.xziqi.cn/Article/details/gtmpqrizno.html

Py:   str(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtojaslfho.html

PHP:  (string) 42; strval(42)
来源：http://dali.cqqwz.cn/Article/details/gtrdqudefg.html

JS:   String(42); (42).toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtimyrrrgp.html

TS:   String(42)
来源：http://dali.xylfe.cn/Article/details/gtrsagjnrh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jianghu66.top/Article/details/gtgcnubocl.html

Go:   strconv.Itoa(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtbrdbppxz.html

Ruby: 42.to_s
来源：http://dali.cashguo.top/Article/details/gtzuffinjv.html

C#:   42.ToString()
来源：http://dali.jianghu66.top/Article/details/gttkmlkptk.html

[A08] 取整与四舍五入
来源：http://dali.jiagoushi.top/Article/details/gtqkghpxxg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gtngawfamz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnvhdeyn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gtxhexgosc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sufxvd.cn/Article/details/gtzorlcyye.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtrvsegnwk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtgurywegd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.fengsongda.top/Article/details/gtqfcmtiih.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtgakhlpsa.html

[A09] 绝对值与最大最小值
来源：http://dali.zycfv.cn/Article/details/gtakucbzym.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtypcexzug.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtzyhvpuxa.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yj20258.top/Article/details/gtaoyvflhk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gttfiukshp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtbpqmwgwv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.nanxinkj.top/Article/details/gtbwdneice.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gotoacloud.top/Article/details/gtkmigsvgb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtyibwzaam.html

[A10] 生成随机数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptxrmtri.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yonumen.top/Article/details/gttwnhxpbw.html

PHP:  random_int(1, 100);
来源：http://dali.xylfe.cn/Article/details/gttmwfyzpi.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyobniav.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gtyrkkhgdh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gtjsjxjebv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hywenlv.cn/Article/details/gtmeewzxpq.html

Ruby: rand(1..100)
来源：http://dali.aibaodan.cn/Article/details/gtdfdxyehr.html

C#:   new Random().Next(1, 101)
来源：http://dali.hongshengwenyu.top/Article/details/gtuqalqcme.html

[A11] 条件表达式（三元）
来源：http://dali.nwbrower.top/Article/details/gtwzldjyqc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yonumen.top/Article/details/gtinifhvlm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gthxeaxglw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtpevtrdii.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtjurijrpp.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtyfnlhkwg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jqgfzy.top/Article/details/gttninixmb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtujulpgmf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtezxmiemv.html

[A12] 字符串插值 / 格式化
来源：http://dali.xuanzx.com/Article/details/gtoeqjiqez.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.wangdashe.top/Article/details/gtmnuvoozi.html


<!-- 参考信息 -->