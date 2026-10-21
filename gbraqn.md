代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.chenlongwang.top/Article/details/gtxmwkdkab.html

parse_ini_file("config.ini", true)
来源：http://dali.zhongyouzk.top/Article/details/gtgicjkrod.html

[U74] PHP：读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtfhravvim.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jlsjyb.cn/Article/details/gtzzvimljm.html

[U75] PHP：依赖注入
来源：http://dali.yj20258888.top/Article/details/gtxhwuaxea.html

composer require psr/container
来源：http://dali.yj20258888.top/Article/details/gtmbeqjywm.html

[U76] PHP：简单路由
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsrqgqef.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aizwys.cn/Article/details/gtrrxvyxmb.html

[U77] PHP：模板渲染
来源：http://dali.ydzc1.top/Article/details/gtbwqaayoh.html

composer require twig/twig
来源：http://dali.guowangkeji.top/Article/details/gtlzedvxha.html

[U78] PHP：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygafdanc.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxuanxn.top/Article/details/gtrccfbxmi.html

[U79] PHP：静态分析
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyrkqyoi.html

composer require --dev phpstan/phpstan
来源：http://dali.tian-w.cn/Article/details/gtucqkvdwi.html

[U80] PHP：代码规范修复
来源：http://dali.cqqwz.cn/Article/details/gtxdkrwijt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhengqikj.top/Article/details/gtaarwaphq.html

[U81] JS：初始化项目
来源：http://dali.cheryme.top/Article/details/gtbtwikuvp.html

npm init -y;  npm i express
来源：http://dali.xuanzx.com/Article/details/gtmgagmiol.html

[U82] JS：package.json 脚本
来源：http://dali.cdnleiting.top/Article/details/gtlzlmqvaq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.0kj1m.cn/Article/details/gtrvcyflqn.html

[U83] JS：ES Module 导入导出
来源：http://dali.jyoumei.cn/Article/details/gtwyyyfweb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gtjtnolunl.html

[U84] JS：CommonJS 写法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedkbfapc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gotoacloud.top/Article/details/gttlndyjtm.html

[U85] JS：可选链
来源：http://dali.9152youxi.cn/Article/details/gtzibsgprs.html

a?.b?.c
来源：http://dali.iojbl.cn/Article/details/gtssokoebu.html

[U86] JS：空值合并
来源：http://dali.aibaodan.cn/Article/details/gtiktxrjlg.html

a ?? b
来源：http://dali.mhx1999.top/Article/details/gtcynkutvq.html

[U87] JS：解构默认值
来源：http://dali.yvedp.cn/Article/details/gthmcvtzpm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.guannengcc.top/Article/details/gtunfhinrj.html

[U88] JS：对象展开合并
来源：http://dali.guowangkeji.top/Article/details/gtzdygcmsh.html

{ ...a, ...b }
来源：http://dali.yanxiufei.cn/Article/details/gtiynygoqz.html

[U89] JS：数组去重
来源：http://dali.tanke756.top/Article/details/gtbrnmynev.html

[...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtnssdaihy.html

[U90] JS：数字数组排序
来源：http://dali.snrcjt.cn/Article/details/gtmalkxryr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtgaanaczc.html

[U91] JS：对象键值遍历
来源：http://dali.vqdsnc.cn/Article/details/gtlwomrfbs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj202588.top/Article/details/gtjxsfplqx.html

[U92] JS：深拷贝
来源：http://dali.cucudq.cn/Article/details/gtccdhqubj.html

structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtzhfuczoy.html

[U93] JS：模板字符串
来源：http://dali.ehwqpu.com/Article/details/gttbicuvic.html

`共 ${n} 条`
来源：http://dali.cdnleiting.top/Article/details/gtfgtfvpes.html

[U94] JS：箭头函数
来源：http://dali.pycfn.com/Article/details/gtmvunqwhl.html

const double = x => x * 2;
来源：http://dali.snrcjt.cn/Article/details/gtvzfsvour.html

[U95] JS：Promise 包装
来源：http://dali.ivvv.top/Article/details/gtzuzgrgrn.html

new Promise((resolve, reject) => {})
来源：http://dali.yj20258.top/Article/details/gtzbviwuoa.html

[U96] JS：async/await 与异常
来源：http://dali.nwbrower.top/Article/details/gtnghunmim.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfugvsvxa.html

[U97] JS：并发请求
来源：http://dali.snrcjt.cn/Article/details/gtrqnnjcmr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gttijiidhe.html

[U98] JS：fetch 带 JSON
来源：http://dali.daxiang520.top/Article/details/gtoehzcxrn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkgszguy.html

[U99] JS：事件监听
来源：http://dali.yuxming.cn/Article/details/gtdakfibuz.html

el.addEventListener("click", e => {})
来源：http://dali.ppjwa.cn/Article/details/gtztelotrn.html

[U100] JS：DOM 查询
来源：http://dali.gogol.net.cn/Article/details/gtcplcxbjn.html

document.querySelector(".item")
来源：http://dali.pengpengdd.cyou/Article/details/gtrbmgxmfv.html

[U101] JS：classList 操作
来源：http://dali.iojbl.cn/Article/details/gtxjuxjgog.html

el.classList.toggle("active")
来源：http://dali.andypj.xyz/Article/details/gtxktazllc.html

[U102] JS：本地存储
来源：http://dali.xuetiantiany.cn/Article/details/gtswcwftpw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.birdmap.top/Article/details/gthleavlnr.html

[U103] JS：定时器
来源：http://dali.cheryme.top/Article/details/gtomwmsycl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xziqi.cn/Article/details/gtcatickwl.html

[U104] JS：防抖
来源：http://dali.tianlin.xyz/Article/details/gtfviqacmo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtkkqhvdxi.html

[U105] JS：节流
来源：http://dali.kuanghao11.cn/Article/details/gtkgfsmraz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gtoshwbdbt.html

[U106] JS：日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtupvfqkex.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangtech.top/Article/details/gtynjajcjn.html

[U107] JS：数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtcrhwgzaf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtrxchikgs.html

[U108] JS：随机整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtnramnbwt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.redwolf501.top/Article/details/gtzgahewbf.html

[U109] JS：数组分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwyxidec.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtrhkkmqtn.html

[U110] JS：数组分块
来源：http://dali.c1oappe.top/Article/details/gtlwshgpql.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gtouavtvuw.html

[U111] JS：对象转 Map
来源：http://dali.jlsjyb.cn/Article/details/gtnxwtcbgd.html

new Map(Object.entries(obj))
来源：http://dali.zhixingplan.top/Article/details/gtyzllppsn.html

[U112] JS：字符串补位
来源：http://dali.hnqzz.top/Article/details/gtncprmanc.html

"7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtotxngbwu.html

[U113] JS：正则替换全部
来源：http://dali.xziqi.cn/Article/details/gtzqbhvuee.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtlxoacfwp.html

[U114] JS：JSON 深比较
来源：http://dali.havefunace.top/Article/details/gtwwiqgvnf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gtdqtfbkhn.html

[U115] JS：生成 UUID
来源：http://dali.gzhubu.top/Article/details/gtdenffnlm.html

crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgypttey.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj202588.top/Article/details/gtbouqvicn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvdmbyzd.html

[U117] JS：单元测试
来源：http://dali.ehwqpu.com/Article/details/gtrhmazggj.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigfzy.top/Article/details/gtrzmzedrz.html

[U118] JS：开发服务器
来源：http://dali.dashuyun.cn/Article/details/gtajlgumtf.html

npm i -D vite;  npx vite
来源：http://dali.jyoumei.cn/Article/details/gtduvufkqg.html

[U119] JS：生产构建
来源：http://dali.iojbl.cn/Article/details/gtpmzkrazi.html

npx vite build
来源：http://dali.cqqwz.cn/Article/details/gthobmtluj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guannengcc.top/Article/details/gtlqexjajm.html

import.meta.env.VITE_API_URL
来源：http://dali.hysaishi.cn/Article/details/gtkcplbvdy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjssgnmgg.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gtglckwwaf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtltojkcnn.html

按语言统计（条）：
来源：http://dali.ydzc1.top/Article/details/gtbqelsxsv.html

Python ......... 252
来源：http://dali.316326.xyz/Article/details/gtwacrcnqf.html

PHP ............ 252
来源：http://dali.yonumen.top/Article/details/gtbyetuppe.html

JavaScript ..... 252
来源：http://dali.fzhhl.top/Article/details/gtggjnouko.html

TypeScript ..... 212
来源：http://dali.yuanzhike.top/Article/details/gtlemyjnam.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gtvpjnjuzl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gtsxqiqhnh.html

Ruby ........... 212
来源：http://dali.meibo888.top/Article/details/gtqnkylqly.html

C# ............. 212
来源：http://dali.gzhubu.top/Article/details/gthicvyffc.html

C .............. 30
来源：http://dali.wangshuangyany.cn/Article/details/gtyivvnoss.html

C++ ............ 30
来源：http://dali.ivvv.top/Article/details/gttjucukho.html

SQL ............ 90
来源：http://dali.yongpay.top/Article/details/gtkvfjlpbd.html

Bash ........... 80
来源：http://dali.cheryme.top/Article/details/gtabgdcmxf.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gtivtpdsph.html

Swift .......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gtojaqivxc.html

Lua ............ 10
来源：http://dali.zhixingplan.top/Article/details/gtvhfkfshh.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gtktipffok.html

Scala .......... 10
来源：http://dali.aibaodan.cn/Article/details/gtvauppekr.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtdlpwofnv.html

合计 ........... 2106 条
来源：http://dali.gaohongyu789.top/Article/details/gtxebgeaxh.html

按章节统计：
来源：http://dali.shangyingyoupin.top/Article/details/gtwczwmrjd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gtfvvmodpb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtxahyyskh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtixspdfce.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gtdlrhkvgq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.316326.xyz/Article/details/gtopgstvvv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gtpzqbgksu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gtelttyggu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.smart0.xyz/Article/details/gtocjgqbcy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtozywiyhp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gtgwmzxfie.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtpkvfxpug.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtqqqkvbsr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtjmxgtfcp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gtizolrqsr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxinkj.top/Article/details/gtohpibkub.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtdzwnrtxy.html

Q SQL 专题                              90
来源：http://dali.yuanzhike.top/Article/details/gtowloamhb.html

R Bash 专题                             80
来源：http://dali.yueranfly.top/Article/details/gtmfdzchvi.html

S C / C++ 专题                          60
来源：http://dali.yuanzhike.top/Article/details/gtukzgretb.html

T 其他语言补充                          60
来源：http://dali.sxryk.cn/Article/details/gtxchftuah.html

U 高频实用片段                         120
来源：http://dali.chenlongwang.top/Article/details/gtrtdayuyh.html

------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gthovycfcx.html

合计                                  2106 条
来源：http://dali.svipenyu.cn/Article/details/gtxdtcubyp.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzhhuffl.html

使用提醒
来源：http://dali.jqgfzy.top/Article/details/gtpqnxpdhg.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtkydoelkx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hammf.cn/Article/details/gtgzouqmgp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hywenlv.cn/Article/details/gtcncsdjsj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tanke756.top/Article/details/gtieceauzd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zdqjudy.top/Article/details/gtpvosvrmz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenlongwang.top/Article/details/gtjvbldbqg.html

—— 文件结束 ——
来源：http://dali.dianchejie.cn/Article/details/gtjayluawb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtjqybgyly.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhiwuduotai.top/Article/details/gtbtosmook.html

Common Programming Examples Cheat Book
来源：http://dali.wangdashe.top/Article/details/gtjewufqxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtohjbffis.html

【收录内容】
来源：http://dali.fzhhl.top/Article/details/gtxkqpofgm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.dianchejie.cn/Article/details/gtvtvnwvdv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hammf.cn/Article/details/gtshafvvet.html

SQL · Bash · C · C++
来源：http://dali.sufxvd.cn/Article/details/gtswrgqwvf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxuanxn.top/Article/details/gtmhybzjfd.html

【使用说明】
来源：http://dali.mhx1999.top/Article/details/gtybkdvmlc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangtech.top/Article/details/gtgopwllis.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.svipenyu.cn/Article/details/gtfvourger.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aibaodan.cn/Article/details/gtudaksjzh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xinyue.icu/Article/details/gtslxubisz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jianghu66.top/Article/details/gtwydknkuc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj202588.top/Article/details/gtsewgzcwv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cqqwz.cn/Article/details/gtphetngxq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj202588.top/Article/details/gtctofcymz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.kuanghao11.cn/Article/details/gtiqqjrowo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gthimctocx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xziqi.cn/Article/details/gtdnbhjdoq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovmuyars.html

【文件统计】
来源：http://dali.c1oappe.top/Article/details/gtccgjkgki.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guowangkeji.top/Article/details/gtzkvkqiie.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtxedhxsnj.html

目  录
来源：http://dali.cashguo.top/Article/details/gtcwzukqjh.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtrbdxanke.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtyanxpxyh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtfiossrkr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xinyue.icu/Article/details/gtukqqpcct.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxbflrnh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.quarkkingdee.top/Article/details/gtqqlgrzqp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gtouipgzso.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtqfuapabk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gtfxijpctt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtxeeldxnq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gtzdookbnj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtpezimldc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtirtbtnfi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gthwnfpqdc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.smart0.xyz/Article/details/gtxualvftr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinqigufen.top/Article/details/gtttczvbme.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gttbwsmcep.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sysykeji.top/Article/details/gtpzlfxwqb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.meibo888.top/Article/details/gtjzxjpdoz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.daria6918.cn/Article/details/gtooshpgfd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gtwpqqpedi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yueranfly.top/Article/details/gtsxdcnepg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtyabskrji.html

A. 基础语法与类型
来源：http://dali.dashuyun.cn/Article/details/gtacitzqko.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduazubwb.html

[A01] Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyjbguuz.html

Py:   print("Hello, World!")
来源：http://dali.chenlongwang.top/Article/details/gtcwtyakty.html

PHP:  echo "Hello, World!";
来源：http://dali.jqgfzy.top/Article/details/gtowgqwmcx.html

JS:   console.log("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtfkquisjy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hysaishi.cn/Article/details/gtxxwszvel.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gtbovmfjnt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gtbxdeserq.html

Ruby: puts "Hello, World!"
来源：http://dali.ppjwa.cn/Article/details/gthpxbsqua.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gtttchsmjg.html

[A02] 变量声明与赋值
来源：http://dali.birdmap.top/Article/details/gtvawrrdem.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.kuanghao11.cn/Article/details/gtojbawkle.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtzdyxtaob.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtzkealvrg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtzaeyrskw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tanke756.top/Article/details/gtuselkjvz.html

Go:   name := "Alex"; age := 20
来源：http://dali.jiagoushi.top/Article/details/gtrxgdisys.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgqtnmju.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yonumen.top/Article/details/gtrfhxnonb.html

[A03] 常量定义
来源：http://dali.xuetiantiany.cn/Article/details/gteukalxkf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenlongwang.top/Article/details/gtvhazfqop.html

PHP:  const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtdcbtknit.html

JS:   const PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtkkfzvydj.html

TS:   const PI: number = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtfddgsvfa.html

Java: static final double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtyjrkfpjk.html

Go:   const PI = 3.14159
来源：http://dali.aizwys.cn/Article/details/gtlbosiyao.html

Ruby: PI = 3.14159
来源：http://dali.hnxiangtu.top/Article/details/gtigsjqnev.html

C#:   const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtmlqiveuh.html

[A04] 判断变量类型
来源：http://dali.0kj1m.cn/Article/details/gtfekqumdu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shuidangran.top/Article/details/gtswwjcnep.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sysykeji.top/Article/details/gtmriidlnb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gtuxdkrtnj.html

TS:   typeof x; x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gtfgjaqhto.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jianghu66.top/Article/details/gttuoizipx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yj20258888.top/Article/details/gtqzzxgriw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xinyue.icu/Article/details/gttrbfwdyk.html

C#:   x.GetType().Name; x is int
来源：http://dali.fengsongda.top/Article/details/gtcizmmqwb.html

[A05] 整数除法与取模
来源：http://dali.fengsongda.top/Article/details/gtzyeiibyk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gtjptngdcf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gttwmchspg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtujbyxxih.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtvdvfylhz.html

Java: 7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtbjguflon.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtbvhfjqpu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtuvfvmjzt.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdqbrisu.html

[A06] 字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gtdgkpioin.html

Py:   int("42"); float("3.14")
来源：http://dali.yuanzhike.top/Article/details/gtdzewnbuc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yueranfly.top/Article/details/gtclflvtfo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gtwvhgrbim.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.guowangkeji.top/Article/details/gtndcuqdfi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gtqcrlbinh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtrabhsdri.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sufxvd.cn/Article/details/gtrglxvefr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenzaomai.com/Article/details/gttgczqnns.html

[A07] 数字转字符串
来源：http://dali.hnqzz.top/Article/details/gtoevomrfo.html

Py:   str(42)
来源：http://dali.hysaishi.cn/Article/details/gtfmaxlxok.html

PHP:  (string) 42; strval(42)
来源：http://dali.hnxiangtu.top/Article/details/gtliqhjyio.html

JS:   String(42); (42).toString()
来源：http://dali.jiagoushi.top/Article/details/gttmuahdec.html

TS:   String(42)
来源：http://dali.dashuyun.cn/Article/details/gtwycqqfib.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yongpay.top/Article/details/gthbbhuzsw.html

Go:   strconv.Itoa(42)
来源：http://dali.tian-w.cn/Article/details/gtwvkvsodf.html

Ruby: 42.to_s
来源：http://dali.meibo888.top/Article/details/gtbnrmfmtv.html

C#:   42.ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtxpogojlx.html

[A08] 取整与四舍五入
来源：http://dali.sxryk.cn/Article/details/gtmbvzhjzo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtxrnhjdam.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnxiangtu.top/Article/details/gtbibmrldf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtavfiqxdn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yangfankeji.com/Article/details/gtfbpxdbky.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yongpay.top/Article/details/gtkuqvarxs.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gtwwryabxa.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.haohaochexian.top/Article/details/gtmxhnhlyc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvqgouma.html

[A09] 绝对值与最大最小值
来源：http://dali.jiagoushi.top/Article/details/gthpcfhwkc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtcquwivgf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtkgzkijga.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwybxparf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtjvczkfgn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbaajaqp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dashuyun.cn/Article/details/gtdcynilub.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.pengpengdd.cyou/Article/details/gthnbdbfob.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtpojgixji.html

[A10] 生成随机数
来源：http://dali.nanxinkj.top/Article/details/gtywavrpup.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jiagoushi.top/Article/details/gtsocngfzo.html

PHP:  random_int(1, 100);
来源：http://dali.jinqigfzy.top/Article/details/gtuspnclvt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258888.top/Article/details/gtvsvjmwft.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yangfankeji.com/Article/details/gtvyiplxvn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xuanzx.com/Article/details/gtlxtubdvb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hnqzz.top/Article/details/gtszssavei.html

Ruby: rand(1..100)
来源：http://dali.dianchejie.cn/Article/details/gtaoguthmz.html

C#:   new Random().Next(1, 101)
来源：http://dali.yongpay.top/Article/details/gtnfwrakqr.html

[A11] 条件表达式（三元）
来源：http://dali.cucudq.cn/Article/details/gtfqprwvay.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shzxlz.cn/Article/details/gtywihuuue.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gtcahbudpl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gtwxnowcco.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gtpnggcnkx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtddnhctnb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ydzc1.top/Article/details/gtsuipzqhe.html


<!-- 参考信息 -->