代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtientalkf.html

composer require psr/container
来源：http://dali.dashuyun.cn/Article/details/gtplpstyjj.html

[U76] PHP：简单路由
来源：http://dali.jqgfzy.top/Article/details/gtkerqcviy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hongshengwenyu.top/Article/details/gtmmmckkvt.html

[U77] PHP：模板渲染
来源：http://dali.feifeiyinyue.top/Article/details/gtydagjyam.html

composer require twig/twig
来源：http://dali.xuetiantiany.cn/Article/details/gtutrmdnmx.html

[U78] PHP：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gtlithenii.html

composer require --dev phpunit/phpunit
来源：http://dali.wangshuangyany.cn/Article/details/gtcsqnlatw.html

[U79] PHP：静态分析
来源：http://dali.xylfe.cn/Article/details/gtqcjdprph.html

composer require --dev phpstan/phpstan
来源：http://dali.yanxiufei.cn/Article/details/gtcvyecqaz.html

[U80] PHP：代码规范修复
来源：http://dali.fengsongda.top/Article/details/gtmkkcwxyi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.meibo888.top/Article/details/gttopoxrgv.html

[U81] JS：初始化项目
来源：http://dali.nanxinkj.top/Article/details/gtdwhljlxh.html

npm init -y;  npm i express
来源：http://dali.zycfv.cn/Article/details/gtdwalzqje.html

[U82] JS：package.json 脚本
来源：http://dali.pengpengdd.cyou/Article/details/gtxzseodov.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zycfv.cn/Article/details/gtfnfozvzv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gtjccqgxiy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtsshtulev.html

[U84] JS：CommonJS 写法
来源：http://dali.xuetiantiany.cn/Article/details/gtxwxbnjmy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.9152youxi.cn/Article/details/gtupzfqpfv.html

[U85] JS：可选链
来源：http://dali.sxryk.cn/Article/details/gtonnlklnd.html

a?.b?.c
来源：http://dali.xinyue.icu/Article/details/gtlupoousf.html

[U86] JS：空值合并
来源：http://dali.jyoumei.cn/Article/details/gtvrjgyxys.html

a ?? b
来源：http://dali.birdmap.top/Article/details/gtxigdleft.html

[U87] JS：解构默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtavqmqmph.html

const { a = 1, b = 2 } = obj;
来源：http://dali.daria6918.cn/Article/details/gtvmrjwvsm.html

[U88] JS：对象展开合并
来源：http://dali.sysykeji.top/Article/details/gteitkcaks.html

{ ...a, ...b }
来源：http://dali.pycfn.com/Article/details/gtkgfibhpg.html

[U89] JS：数组去重
来源：http://dali.zdqjudy.top/Article/details/gtbdgygjrq.html

[...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtoacjzdec.html

[U90] JS：数字数组排序
来源：http://dali.nwbrower.top/Article/details/gtsjchramm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtrifpzalf.html

[U91] JS：对象键值遍历
来源：http://dali.yj202588.top/Article/details/gtnvxyxmic.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hnxiangtu.top/Article/details/gtryollwgs.html

[U92] JS：深拷贝
来源：http://dali.jyoumei.cn/Article/details/gtxicdjkod.html

structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtnzvvxlkn.html

[U93] JS：模板字符串
来源：http://dali.sweek.top/Article/details/gtxshjoqaa.html

`共 ${n} 条`
来源：http://dali.kuanghao11.cn/Article/details/gtogacovfq.html

[U94] JS：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtvtsjzglc.html

const double = x => x * 2;
来源：http://dali.jlsjyb.cn/Article/details/gtxqwxwpru.html

[U95] JS：Promise 包装
来源：http://dali.hysaishi.cn/Article/details/gteohkuxkh.html

new Promise((resolve, reject) => {})
来源：http://dali.yonumen.top/Article/details/gteuduntvn.html

[U96] JS：async/await 与异常
来源：http://dali.zdqjudy.top/Article/details/gtcujaxaac.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gthwyhipbp.html

[U97] JS：并发请求
来源：http://dali.xylfe.cn/Article/details/gtugbpraie.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtvwhbenze.html

[U98] JS：fetch 带 JSON
来源：http://dali.sufxvd.cn/Article/details/gtcfbqjkdx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fzhhl.top/Article/details/gtnkxnsizf.html

[U99] JS：事件监听
来源：http://dali.316326.xyz/Article/details/gtpezcomiv.html

el.addEventListener("click", e => {})
来源：http://dali.ivvv.top/Article/details/gtdyphmcpz.html

[U100] JS：DOM 查询
来源：http://dali.aibaodan.cn/Article/details/gthtetuibj.html

document.querySelector(".item")
来源：http://dali.jlsjyb.cn/Article/details/gtrqsbjuob.html

[U101] JS：classList 操作
来源：http://dali.andypj.xyz/Article/details/gtzcjlfqzk.html

el.classList.toggle("active")
来源：http://dali.cqqwz.cn/Article/details/gtpwdaeazi.html

[U102] JS：本地存储
来源：http://dali.yangfankeji.com/Article/details/gtnzrpeudl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.svipenyu.cn/Article/details/gtoigknnfh.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gtyjwxtgzt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shuidangran.top/Article/details/gtdoisdpff.html

[U104] JS：防抖
来源：http://dali.0kj1m.cn/Article/details/gtnargwslx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtgsrgakcy.html

[U105] JS：节流
来源：http://dali.c1oappe.top/Article/details/gtaxdfkmcq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ydzc1.top/Article/details/gtoggxnabq.html

[U106] JS：日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtbxajqlma.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fengsongda.top/Article/details/gtdpftwvsk.html

[U107] JS：数字千分位
来源：http://dali.hammf.cn/Article/details/gtgxawgquy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gtoqpzoasi.html

[U108] JS：随机整数
来源：http://dali.yj202588.top/Article/details/gtjyfihrvn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlafgfmwh.html

[U109] JS：数组分组
来源：http://dali.guowangkeji.top/Article/details/gtpskxfjfv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtzjufqfxw.html

[U110] JS：数组分块
来源：http://dali.redwolf501.top/Article/details/gtyxybluow.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ivvv.top/Article/details/gtwctcdicy.html

[U111] JS：对象转 Map
来源：http://dali.shangyingyoupin.top/Article/details/gtnkhbhrvr.html

new Map(Object.entries(obj))
来源：http://dali.xinyue.icu/Article/details/gtjxhvvija.html

[U112] JS：字符串补位
来源：http://dali.nwbrower.top/Article/details/gtbnqgdkue.html

"7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtnpahtpig.html

[U113] JS：正则替换全部
来源：http://dali.cheryme.top/Article/details/gtkegarcya.html

s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtnfgohbrw.html

[U114] JS：JSON 深比较
来源：http://dali.shangyingyoupin.top/Article/details/gttcgvluos.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gtdiidufpm.html

[U115] JS：生成 UUID
来源：http://dali.cheryme.top/Article/details/gtlixkojzs.html

crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtzxrsdjih.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhoulong.xyz/Article/details/gtqqlpikii.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zdqjudy.top/Article/details/gtbxvbedbo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtukupcjvd.html

npm i -D vitest;  npx vitest
来源：http://dali.redwolf501.top/Article/details/gtbxhlkknh.html

[U118] JS：开发服务器
来源：http://dali.jianghu66.top/Article/details/gthfgusxub.html

npm i -D vite;  npx vite
来源：http://dali.ppjwa.cn/Article/details/gtcidpjjuy.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gtjnxwyhja.html

npx vite build
来源：http://dali.yuxming.cn/Article/details/gtoldvkxjm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxuanxn.top/Article/details/gtmfnemdfd.html

import.meta.env.VITE_API_URL
来源：http://dali.yj202588.top/Article/details/gtqqpcczjk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjqqvumui.html

统计汇总
来源：http://dali.zhongyouzk.top/Article/details/gtrhyxuwcl.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqzgcacol.html

按语言统计（条）：
来源：http://dali.tanke756.top/Article/details/gtmpncierm.html

Python ......... 252
来源：http://dali.shzxlz.cn/Article/details/gthenagtyn.html

PHP ............ 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlvtctae.html

JavaScript ..... 252
来源：http://dali.cheryme.top/Article/details/gtypppnccu.html

TypeScript ..... 212
来源：http://dali.9152youxi.cn/Article/details/gtrdmiqyuc.html

Java ........... 212
来源：http://dali.xinyue.icu/Article/details/gtjkhvwnrx.html

Go ............. 212
来源：http://dali.xuanzx.com/Article/details/gtgvshtdvv.html

Ruby ........... 212
来源：http://dali.dianchejie.cn/Article/details/gtnwrjkzpz.html

C# ............. 212
来源：http://dali.cdnleiting.top/Article/details/gtvpfbaymf.html

C .............. 30
来源：http://dali.sysykeji.top/Article/details/gtrnaepixb.html

C++ ............ 30
来源：http://dali.jinqigfzy.top/Article/details/gttcujqmlr.html

SQL ............ 90
来源：http://dali.dashuyun.cn/Article/details/gtcucrvgdk.html

Bash ........... 80
来源：http://dali.daria6918.cn/Article/details/gtxtsiditm.html

Kotlin ......... 15
来源：http://dali.ybcxt.top/Article/details/gtuqcbbvxq.html

Swift .......... 15
来源：http://dali.andypj.xyz/Article/details/gtcubgssne.html

Lua ............ 10
来源：http://dali.chenlongwang.top/Article/details/gtwtmpkezt.html

Perl ........... 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqeojgznr.html

Scala .......... 10
来源：http://dali.fengsongda.top/Article/details/gtaxdfixco.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gteaeyxdnm.html

合计 ........... 2106 条
来源：http://dali.fzhhl.top/Article/details/gtjtdgzsia.html

按章节统计：
来源：http://dali.jianghu66.top/Article/details/gtkimxupxs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gtjthndruj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gtdbkdsopy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtoapzggnx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gtosfpiuhm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.0kj1m.cn/Article/details/gtxdlhykhs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gtqvzoxixd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gtoxhykwqy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gtauwycmeb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtycqgsvjc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gthshbkppn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gttldltdbi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtjyxdygjr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtwyutuokn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gtgfxckhes.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tian-w.cn/Article/details/gtxabqxzau.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtpglfznui.html

Q SQL 专题                              90
来源：http://dali.hysaishi.cn/Article/details/gtsebxzuhv.html

R Bash 专题                             80
来源：http://dali.ybcxt.top/Article/details/gtqbjmkksc.html

S C / C++ 专题                          60
来源：http://dali.jianghu66.top/Article/details/gtfvowggik.html

T 其他语言补充                          60
来源：http://dali.kuanghao11.cn/Article/details/gtontwulcw.html

U 高频实用片段                         120
来源：http://dali.jlsjyb.cn/Article/details/gtaqnpgyue.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtchjdwlch.html

合计                                  2106 条
来源：http://dali.guannengcc.top/Article/details/gtffmoixvw.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtryunualw.html

使用提醒
来源：http://dali.jqgfzy.top/Article/details/gtofzomukc.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtwqrjjhsm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yonumen.top/Article/details/gtlvmuqqbl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guannengcc.top/Article/details/gttibwrqkc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.snrcjt.cn/Article/details/gtqxnirhzl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cashguo.top/Article/details/gthaelqoml.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnxiangtu.top/Article/details/gtiiaftfnc.html

—— 文件结束 ——
来源：http://dali.jlsjyb.cn/Article/details/gthnybaskq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtibpkaepf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhongyouzk.top/Article/details/gtkhoglwdo.html

Common Programming Examples Cheat Book
来源：http://dali.zhaomingkeji.xyz/Article/details/gteochkobj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkspqisep.html

【收录内容】
来源：http://dali.andypj.xyz/Article/details/gtbioxfaqy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shangyingyoupin.top/Article/details/gtyylyxtel.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj20258.top/Article/details/gthgpgvcza.html

SQL · Bash · C · C++
来源：http://dali.fengsongda.top/Article/details/gteijheizz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yvedp.cn/Article/details/gtrpbezgiy.html

【使用说明】
来源：http://dali.hysaishi.cn/Article/details/gtlunjvajl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gotoacloud.top/Article/details/gtvrwjjact.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tianlin.xyz/Article/details/gtsfyotadw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cucudq.cn/Article/details/gtefgypplf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.kuanghao11.cn/Article/details/gtsareqmvq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gtfshtkwce.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.birdmap.top/Article/details/gtbspetqsf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangdashe.top/Article/details/gtdoujhkoq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhiwuduotai.top/Article/details/gtjkfsxbjf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xuanzx.com/Article/details/gtzqcxgpef.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.wangshuangyany.cn/Article/details/gtwoukzemg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.guowangkeji.top/Article/details/gtmdwhylep.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.c1oappe.top/Article/details/gtiwhkdjbp.html

【文件统计】
来源：http://dali.cheryme.top/Article/details/gtwyoygywr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nanxinkj.top/Article/details/gtkrtlmjde.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtemljurtd.html

目  录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdbwiasm.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtpsiqjlbi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.snrcjt.cn/Article/details/gtwuelljyt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gtymrdbgmy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gttwjfdqta.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gtfsnqcgsr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tian-w.cn/Article/details/gtzqvzuzkg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.tanke756.top/Article/details/gtnnwjajcj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gthkkpdbca.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjrclgoc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtgstxlglb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shangyingyoupin.top/Article/details/gttrmlqqxs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gteusdatdc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtvnrjqbzu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtjemosioq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinqigufen.top/Article/details/gtvoltrjpr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nanxinkj.top/Article/details/gtfhkuwxbe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtzotlqfow.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.quarkkingdee.top/Article/details/gtetkrqbqt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zdqjudy.top/Article/details/gtbapbfags.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwqugibv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gtuqncjkvr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gtnvwtwjsr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrnaxfdid.html

A. 基础语法与类型
来源：http://dali.wangdashe.top/Article/details/gtzwqmlxno.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtnywuxdwf.html

[A01] Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohgtpwmc.html

Py:   print("Hello, World!")
来源：http://dali.ppjwa.cn/Article/details/gtypdelopr.html

PHP:  echo "Hello, World!";
来源：http://dali.gzhubu.top/Article/details/gtvbjuzcuz.html

JS:   console.log("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gtrmjadfqc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jqgfzy.top/Article/details/gttttkhizf.html

Java: System.out.println("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gtkxlziyry.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gthpyzypxb.html

Ruby: puts "Hello, World!"
来源：http://dali.pycfn.com/Article/details/gtdcjfnzvt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gthoulphnp.html

[A02] 变量声明与赋值
来源：http://dali.yuanzhike.top/Article/details/gtzsujizqx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj20258.top/Article/details/gtvovoepow.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.iojbl.cn/Article/details/gtdmzyiubl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xziqi.cn/Article/details/gteikcxbgm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shzxlz.cn/Article/details/gtvqqdhgck.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtulncdzkj.html

Go:   name := "Alex"; age := 20
来源：http://dali.sxryk.cn/Article/details/gtivpgbmhf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yueranfly.top/Article/details/gthmexzcuy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gtyuncjnth.html

[A03] 常量定义
来源：http://dali.pengpengdd.cyou/Article/details/gtnrpuggzb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxuanxn.top/Article/details/gtddalrarp.html

PHP:  const PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtymmbphqf.html

JS:   const PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtadoarkma.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtserjunui.html

Java: static final double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtkfkatsrd.html

Go:   const PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gtsobxcxrh.html

Ruby: PI = 3.14159
来源：http://dali.pycfn.com/Article/details/gtgyekhxvh.html

C#:   const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtkaiuwmuj.html

[A04] 判断变量类型
来源：http://dali.ppjwa.cn/Article/details/gtnredxocz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yueranfly.top/Article/details/gtbntbweic.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.havefunace.top/Article/details/gtbxshlpqb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cucudq.cn/Article/details/gtlnlznvte.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtaoualssr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hfpthk.cn/Article/details/gtgasvjjhf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhoulong.xyz/Article/details/gtwrcfdpgn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cashguo.top/Article/details/gtvqcczgej.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenzaomai.com/Article/details/gtehxsffek.html

[A05] 整数除法与取模
来源：http://dali.ybcxt.top/Article/details/gtgzmglpeg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dianchejie.cn/Article/details/gttetedviz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtcimricpp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtggyzrmxh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtkatslqee.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gtbqdnlbqt.html

Go:   7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gthkocrogm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtmncdhcfg.html

C#:   7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtupfyxuxc.html

[A06] 字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtzpdgeaio.html

Py:   int("42"); float("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqcwuuwx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.iojbl.cn/Article/details/gtkmdvelzq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xziqi.cn/Article/details/gtwkdbokba.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.wangdashe.top/Article/details/gtspufizst.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cashguo.top/Article/details/gtpwzyorda.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhdclydx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shangyingyoupin.top/Article/details/gtvabbddyg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xuanzx.com/Article/details/gtkkfoskow.html

[A07] 数字转字符串
来源：http://dali.andypj.xyz/Article/details/gtxwkdfcrc.html

Py:   str(42)
来源：http://dali.gogol.net.cn/Article/details/gtueoqbomd.html

PHP:  (string) 42; strval(42)
来源：http://dali.tian-w.cn/Article/details/gtxyuefsdm.html

JS:   String(42); (42).toString()
来源：http://dali.gzhubu.top/Article/details/gtdntshyfi.html

TS:   String(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtyhzeliay.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.iojbl.cn/Article/details/gttonerucq.html

Go:   strconv.Itoa(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtcknvxbdb.html

Ruby: 42.to_s
来源：http://dali.yongpay.top/Article/details/gtjcoqubbf.html

C#:   42.ToString()
来源：http://dali.hywenlv.cn/Article/details/gtybmxqpcr.html

[A08] 取整与四舍五入
来源：http://dali.tianlin.xyz/Article/details/gtikepaopk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtfwknzgoo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yj202588.top/Article/details/gtndyiiffy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtqtqbsytz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yuxming.cn/Article/details/gtonqmwbxn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtfiuobsft.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtibdapdxd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.iojbl.cn/Article/details/gtaxxlsxur.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtbwdvxfhd.html

[A09] 绝对值与最大最小值
来源：http://dali.shuidangran.top/Article/details/gtrgwlvova.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtvkjsgqli.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtudkugybn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gthhyeycct.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtlxzskcfe.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtlaktulvw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xuetiantiany.cn/Article/details/gthtvfouvk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yj20258888.top/Article/details/gtkwmwvwrg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtithtgnzl.html

[A10] 生成随机数
来源：http://dali.yonumen.top/Article/details/gtqjacplli.html

Py:   import random; random.randint(1, 100)
来源：http://dali.tanke756.top/Article/details/gtwbimpdoz.html

PHP:  random_int(1, 100);
来源：http://dali.gzhubu.top/Article/details/gtddrawiko.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangdashe.top/Article/details/gtukanihgy.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxinkj.top/Article/details/gtkrhqyrje.html

Java: new Random().nextInt(100) + 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtousfjeyu.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.daria6918.cn/Article/details/gtdfzvygih.html

Ruby: rand(1..100)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiuulxfm.html

C#:   new Random().Next(1, 101)
来源：http://dali.nanxuanxn.top/Article/details/gtnsrroghw.html

[A11] 条件表达式（三元）
来源：http://dali.feifeiyinyue.top/Article/details/gtuwrfoozz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shzxlz.cn/Article/details/gtkodkbpav.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gtvutuqvsz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtvewrxhop.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gtffjalbdl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtssidjfsm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhoulong.xyz/Article/details/gthgqcyszv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ppjwa.cn/Article/details/gtzdpvhtei.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtwiwzqvvg.html

[A12] 字符串插值 / 格式化
来源：http://dali.fzhhl.top/Article/details/gtezupebqe.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.vqdsnc.cn/Article/details/gtzlssfjam.html


<!-- 参考信息 -->