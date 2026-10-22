代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.jinqigufen.top/Article/details/gtkvafuxpl.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigufen.top/Article/details/gtygyswixb.html

[U74] PHP：读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gtqhydscdk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.feifeiyinyue.top/Article/details/gtqiqzloem.html

[U75] PHP：依赖注入
来源：http://dali.nanxinkj.top/Article/details/gtgqdjklxw.html

composer require psr/container
来源：http://dali.pycfn.com/Article/details/gtmgjrndqi.html

[U76] PHP：简单路由
来源：http://dali.quarkkingdee.top/Article/details/gtgvcgxado.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hywenlv.cn/Article/details/gtaqwgbfym.html

[U77] PHP：模板渲染
来源：http://dali.haohaochexian.top/Article/details/gtavawlext.html

composer require twig/twig
来源：http://dali.shzxlz.cn/Article/details/gturozvrnr.html

[U78] PHP：单元测试
来源：http://dali.snrcjt.cn/Article/details/gtropoiyza.html

composer require --dev phpunit/phpunit
来源：http://dali.hongshengwenyu.top/Article/details/gtdcbxidww.html

[U79] PHP：静态分析
来源：http://dali.cheryme.top/Article/details/gtnjtjktkr.html

composer require --dev phpstan/phpstan
来源：http://dali.cucudq.cn/Article/details/gtxyykwpcr.html

[U80] PHP：代码规范修复
来源：http://dali.nanxuanxn.top/Article/details/gtaakopsya.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.316326.xyz/Article/details/gtsrmshphp.html

[U81] JS：初始化项目
来源：http://dali.gogol.net.cn/Article/details/gtlpwqflgb.html

npm init -y;  npm i express
来源：http://dali.yangfankeji.com/Article/details/gtkzmamgaz.html

[U82] JS：package.json 脚本
来源：http://dali.chenlongwang.top/Article/details/gtppnpexok.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nanxinkj.top/Article/details/gtykihurqn.html

[U83] JS：ES Module 导入导出
来源：http://dali.fengsongda.top/Article/details/gtjpwqwawf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtangelqoc.html

[U84] JS：CommonJS 写法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazmshnet.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.fengsongda.top/Article/details/gtuwoiaktw.html

[U85] JS：可选链
来源：http://dali.chenzaomai.com/Article/details/gtdpdxvfwj.html

a?.b?.c
来源：http://dali.vqdsnc.cn/Article/details/gtcavcqype.html

[U86] JS：空值合并
来源：http://dali.xylfe.cn/Article/details/gtsseyaqle.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gteubofhva.html

[U87] JS：解构默认值
来源：http://dali.wangdashe.top/Article/details/gtatobqcvy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigfzy.top/Article/details/gtosaogehb.html

[U88] JS：对象展开合并
来源：http://dali.vqdsnc.cn/Article/details/gtakentegs.html

{ ...a, ...b }
来源：http://dali.hongshengwenyu.top/Article/details/gtcqyilcbw.html

[U89] JS：数组去重
来源：http://dali.fzhhl.top/Article/details/gtgfdnpgwn.html

[...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtjnmeeczg.html

[U90] JS：数字数组排序
来源：http://dali.tianlin.xyz/Article/details/gtrandqord.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtrdbicqms.html

[U91] JS：对象键值遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqmtamiz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jlsjyb.cn/Article/details/gtalccjuwb.html

[U92] JS：深拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtdsywvpyl.html

structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gttyvourih.html

[U93] JS：模板字符串
来源：http://dali.hysaishi.cn/Article/details/gtfanvzfxk.html

`共 ${n} 条`
来源：http://dali.hammf.cn/Article/details/gtdxghcxal.html

[U94] JS：箭头函数
来源：http://dali.ydzc1.top/Article/details/gtlntujchx.html

const double = x => x * 2;
来源：http://dali.pycfn.com/Article/details/gtnplhnrkf.html

[U95] JS：Promise 包装
来源：http://dali.daria6918.cn/Article/details/gtfzkcwwwi.html

new Promise((resolve, reject) => {})
来源：http://dali.jinqigfzy.top/Article/details/gtaqduhsqm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gtqwyhyrxc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtlqtdfyzs.html

[U97] JS：并发请求
来源：http://dali.gotoacloud.top/Article/details/gtaoydltfh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtobjlqsjm.html

[U98] JS：fetch 带 JSON
来源：http://dali.yuanzhike.top/Article/details/gtnftsqeal.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yongpay.top/Article/details/gtoerbkort.html

[U99] JS：事件监听
来源：http://dali.jyoumei.cn/Article/details/gttbfjauum.html

el.addEventListener("click", e => {})
来源：http://dali.svipenyu.cn/Article/details/gtudenaawz.html

[U100] JS：DOM 查询
来源：http://dali.nanxinkj.top/Article/details/gtuldyprvt.html

document.querySelector(".item")
来源：http://dali.cqqwz.cn/Article/details/gturwzepsb.html

[U101] JS：classList 操作
来源：http://dali.zhongyouzk.top/Article/details/gtoelzbeux.html

el.classList.toggle("active")
来源：http://dali.chenlongwang.top/Article/details/gtpvlbxooc.html

[U102] JS：本地存储
来源：http://dali.chenlongwang.top/Article/details/gtyulwimjf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gotoacloud.top/Article/details/gtupwfhkzr.html

[U103] JS：定时器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycoodzms.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cqqwz.cn/Article/details/gtdmhhoiiu.html

[U104] JS：防抖
来源：http://dali.daria6918.cn/Article/details/gtbstfmzrr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtmnjrzbmv.html

[U105] JS：节流
来源：http://dali.gaohongyu789.top/Article/details/gtkmqzfuoi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gzhubu.top/Article/details/gtqrchkiji.html

[U106] JS：日期格式化
来源：http://dali.cucudq.cn/Article/details/gthxcaeacq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yvedp.cn/Article/details/gtukhhwdhv.html

[U107] JS：数字千分位
来源：http://dali.pycfn.com/Article/details/gtazkklcpx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sxryk.cn/Article/details/gtoobdrqte.html

[U108] JS：随机整数
来源：http://dali.yj20258888.top/Article/details/gthvbgtrbk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.meibo888.top/Article/details/gtjbielhbz.html

[U109] JS：数组分组
来源：http://dali.aibaodan.cn/Article/details/gtoumgdymq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtgqubiazy.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqcvrbbm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gtneykoyfe.html

[U111] JS：对象转 Map
来源：http://dali.tanke756.top/Article/details/gtxjnjiosb.html

new Map(Object.entries(obj))
来源：http://dali.yonumen.top/Article/details/gtirxlnycm.html

[U112] JS：字符串补位
来源：http://dali.yvedp.cn/Article/details/gtqxtwwbrb.html

"7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtkvecydqx.html

[U113] JS：正则替换全部
来源：http://dali.0kj1m.cn/Article/details/gtxrnfkywj.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtiivafaut.html

[U114] JS：JSON 深比较
来源：http://dali.sysykeji.top/Article/details/gtzenhdith.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtaabpaurn.html

[U115] JS：生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtxuqdiyfn.html

crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtzvetqdql.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.vqdsnc.cn/Article/details/gthsyomiwo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ivvv.top/Article/details/gtbnznzgzw.html

[U117] JS：单元测试
来源：http://dali.jqgfzy.top/Article/details/gtnipdthky.html

npm i -D vitest;  npx vitest
来源：http://dali.zhiwuduotai.top/Article/details/gtutusjval.html

[U118] JS：开发服务器
来源：http://dali.shzxlz.cn/Article/details/gtipqdhegf.html

npm i -D vite;  npx vite
来源：http://dali.nwbrower.top/Article/details/gtijmehqur.html

[U119] JS：生产构建
来源：http://dali.pycfn.com/Article/details/gtqsiicllq.html

npx vite build
来源：http://dali.0kj1m.cn/Article/details/gthxnfmmjt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxinkj.top/Article/details/gtoljybdqs.html

import.meta.env.VITE_API_URL
来源：http://dali.cashguo.top/Article/details/gtcwvsvsvo.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtaamlvbih.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gturzwuryh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtyqsfojse.html

按语言统计（条）：
来源：http://dali.yj20258888.top/Article/details/gtolkqqjgb.html

Python ......... 252
来源：http://dali.hammf.cn/Article/details/gtwkphsaee.html

PHP ............ 252
来源：http://dali.yueranfly.top/Article/details/gtfwlsgweb.html

JavaScript ..... 252
来源：http://dali.tian-w.cn/Article/details/gtmvdutlsz.html

TypeScript ..... 212
来源：http://dali.cdnleiting.top/Article/details/gtnluhsuvr.html

Java ........... 212
来源：http://dali.yj20258888.top/Article/details/gtfgxxtysd.html

Go ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gtguzbapjr.html

Ruby ........... 212
来源：http://dali.yvedp.cn/Article/details/gtekexyhng.html

C# ............. 212
来源：http://dali.yongpay.top/Article/details/gtwxmfxusj.html

C .............. 30
来源：http://dali.wangshuangyany.cn/Article/details/gtulmlniys.html

C++ ............ 30
来源：http://dali.nwbrower.top/Article/details/gtajswdlwc.html

SQL ............ 90
来源：http://dali.yj202588.top/Article/details/gtyprllhjm.html

Bash ........... 80
来源：http://dali.daria6918.cn/Article/details/gtyxgliueu.html

Kotlin ......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavepruge.html

Swift .......... 15
来源：http://dali.yangfankeji.com/Article/details/gtkotacsru.html

Lua ............ 10
来源：http://dali.zhengqikj.top/Article/details/gtqauikbbp.html

Perl ........... 10
来源：http://dali.chenjidiqi.icu/Article/details/gtwrlgapit.html

Scala .......... 10
来源：http://dali.yueranfly.top/Article/details/gtohzefiew.html

------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gthvgvwwfb.html

合计 ........... 2106 条
来源：http://dali.sufxvd.cn/Article/details/gtgxlmlrzk.html

按章节统计：
来源：http://dali.xylfe.cn/Article/details/gtcvzapdwp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gtnilcyhgo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtlvykltte.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gteskhauhy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpozzpxve.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yanxiufei.cn/Article/details/gtjfgdgwuu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluaiwztd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtaucnyrfb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gtdummlnqo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtcsehqkin.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gthpxnzjzg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtynlynzkt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtpudcnbyu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtkrqilemm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nanxuanxn.top/Article/details/gtnagyjmaw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenzaomai.com/Article/details/gtfpfsughh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtrsavhtem.html

Q SQL 专题                              90
来源：http://dali.zhongyouzk.top/Article/details/gtahenspen.html

R Bash 专题                             80
来源：http://dali.andypj.xyz/Article/details/gttvpxqpwu.html

S C / C++ 专题                          60
来源：http://dali.nanxinkj.top/Article/details/gtqxlspayv.html

T 其他语言补充                          60
来源：http://dali.zdqjudy.top/Article/details/gtjalxowtw.html

U 高频实用片段                         120
来源：http://dali.svipenyu.cn/Article/details/gteuljqfic.html

------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtvjvtiden.html

合计                                  2106 条
来源：http://dali.hysaishi.cn/Article/details/gtzihygfkd.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtzugnzmfw.html

使用提醒
来源：http://dali.xuetiantiany.cn/Article/details/gtkvhksfpu.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtaranncxt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtushzrund.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.vqdsnc.cn/Article/details/gtturpjpqr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ehwqpu.com/Article/details/gtfvvsfetb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nwbrower.top/Article/details/gtijwpnrya.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.0kj1m.cn/Article/details/gtefwupmoo.html

—— 文件结束 ——
来源：http://dali.guannengcc.top/Article/details/gtwassylqe.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtxlnybykl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.aibaodan.cn/Article/details/gtjtpdgbgv.html

Common Programming Examples Cheat Book
来源：http://dali.yuanzhike.top/Article/details/gtfxzqeodn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqqvgljxz.html

【收录内容】
来源：http://dali.dianchejie.cn/Article/details/gtyioelzds.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zdqjudy.top/Article/details/gtmwtmpefy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.dianchejie.cn/Article/details/gtncdokxzs.html

SQL · Bash · C · C++
来源：http://dali.yuxming.cn/Article/details/gtqzdwnybt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.fzhhl.top/Article/details/gturtnqvpr.html

【使用说明】
来源：http://dali.cucudq.cn/Article/details/gtuibbzyqu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.0kj1m.cn/Article/details/gtgzkxsfjr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenlongwang.top/Article/details/gtcdmisgtl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xinyue.icu/Article/details/gtglalsduj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xylfe.cn/Article/details/gtptfoatcm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj202588.top/Article/details/gtkbprvxju.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jlsjyb.cn/Article/details/gtrgvakmav.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhengqikj.top/Article/details/gtvnxbwauw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shanyushiyangtech.top/Article/details/gtflahujsf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cashguo.top/Article/details/gtntgfhcaq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinqigufen.top/Article/details/gtqelxdeat.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.mhx1999.top/Article/details/gtgduwmman.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jyoumei.cn/Article/details/gtdsqdzmgg.html

【文件统计】
来源：http://dali.zdqjudy.top/Article/details/gtyahhbjri.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gotoacloud.top/Article/details/gtnrexkkij.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtxmucxhrg.html

目  录
来源：http://dali.yuanzhike.top/Article/details/gtzrjqsxef.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtndsqxkwo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cqqwz.cn/Article/details/gtbqkczrva.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gtuxbacpkx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtabisxuzl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gtzqmtecfy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yuanzhike.top/Article/details/gtferghyzo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gtediytikg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yanxiufei.cn/Article/details/gtmscaacgp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtrrnnfqeq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtzgzesovk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xinyue.icu/Article/details/gtelhvvzev.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtrjhhlvot.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gthkvgjqee.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtldodfcba.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sufxvd.cn/Article/details/gtfnkyngoq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgksvrmiw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtezxvtjlx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.quarkkingdee.top/Article/details/gtzhbotpdx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.daxiang520.top/Article/details/gthenycdog.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hfpthk.cn/Article/details/gtsslonypb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gtmuamajis.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtcmsvbkpq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtnulvcrfn.html

A. 基础语法与类型
来源：http://dali.aizwys.cn/Article/details/gtbbxkfmvp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrnibtehu.html

[A01] Hello World
来源：http://dali.zhengqikj.top/Article/details/gtabadiizo.html

Py:   print("Hello, World!")
来源：http://dali.svipenyu.cn/Article/details/gtgspyqzmp.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxuanxn.top/Article/details/gtzltjkbzr.html

JS:   console.log("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gtorpmlupn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.guannengcc.top/Article/details/gtsjbytjdo.html

Java: System.out.println("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gtjnpawvpr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gtjdcqrhxt.html

Ruby: puts "Hello, World!"
来源：http://dali.zhixingplan.top/Article/details/gtrljiteac.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gttezwxtlt.html

[A02] 变量声明与赋值
来源：http://dali.shuidangran.top/Article/details/gtwtaazibr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.bjfxy.top/Article/details/gtgvqtjbdl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtnmtzqglm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.iojbl.cn/Article/details/gtwxqtuoeb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomokkmiv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtebaouhwf.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumxndfbu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.wangshuangyany.cn/Article/details/gtdmubhgzv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.chenlongwang.top/Article/details/gtvxbirahh.html

[A03] 常量定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwboryyp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sxryk.cn/Article/details/gtvhydxixh.html

PHP:  const PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtjizqxxtr.html

JS:   const PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gthbgdpxws.html

TS:   const PI: number = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtqmplnprq.html

Java: static final double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtwhnsanzo.html

Go:   const PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gtuilvdqco.html

Ruby: PI = 3.14159
来源：http://dali.yangfankeji.com/Article/details/gtribpquqy.html

C#:   const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtmxrbzclj.html

[A04] 判断变量类型
来源：http://dali.zhengqikj.top/Article/details/gtxzevggaw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gtogrqyake.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xuanzx.com/Article/details/gtpftvfmef.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cucudq.cn/Article/details/gtelsxozcf.html

TS:   typeof x; x instanceof Date
来源：http://dali.pengpengdd.cyou/Article/details/gtnqkntffs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.c1oappe.top/Article/details/gtxmhzgclh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraeqkmri.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj20258888.top/Article/details/gtrsvdljnr.html

C#:   x.GetType().Name; x is int
来源：http://dali.yuanzhike.top/Article/details/gtpeabyizs.html

[A05] 整数除法与取模
来源：http://dali.c1oappe.top/Article/details/gtdexbjhyp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj202588.top/Article/details/gtonktquhh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupeuregj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtznvcqmev.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtgjnynetz.html

Java: 7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gtwhadcyub.html

Go:   7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtskqueyxd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtiyoyekvr.html

C#:   7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtrajzesyb.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeszmpwm.html

Py:   int("42"); float("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gtyspzhucl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nwbrower.top/Article/details/gthnglizdk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhoulong.xyz/Article/details/gtskcwhedb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.c1oappe.top/Article/details/gtqkbwxhdx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtebpgobof.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zycfv.cn/Article/details/gtxylismcc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhiwuduotai.top/Article/details/gtmkkcmshl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtmfmzhbqy.html

[A07] 数字转字符串
来源：http://dali.jqgfzy.top/Article/details/gtptubiatt.html

Py:   str(42)
来源：http://dali.xuanzx.com/Article/details/gttiyrqtsn.html

PHP:  (string) 42; strval(42)
来源：http://dali.mhx1999.top/Article/details/gtwgzdwhuq.html

JS:   String(42); (42).toString()
来源：http://dali.tanke756.top/Article/details/gteebdzptz.html

TS:   String(42)
来源：http://dali.yongpay.top/Article/details/gtnhsfvsje.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtrksvtgtm.html

Go:   strconv.Itoa(42)
来源：http://dali.yj202588.top/Article/details/gttsbxqyqg.html

Ruby: 42.to_s
来源：http://dali.bjfxy.top/Article/details/gthhmdijwv.html

C#:   42.ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtgevmuztw.html

[A08] 取整与四舍五入
来源：http://dali.wangdashe.top/Article/details/gtbbjvqwme.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtvggxnbbb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zdqjudy.top/Article/details/gtkuuvrfti.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtqubjfqxr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.kuanghao11.cn/Article/details/gtiapucrmi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gtjowupqws.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj202588.top/Article/details/gtglxgbuwx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hnxiangtu.top/Article/details/gtgewehhku.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sweek.top/Article/details/gtltjtxqxo.html

[A09] 绝对值与最大最小值
来源：http://dali.mhx1999.top/Article/details/gtnhpcjhik.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtbherbwgs.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtwlarspdp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtuovmdbpc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258.top/Article/details/gtofqlyzux.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gthktdbgaz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.iojbl.cn/Article/details/gthfiquivp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.guowangkeji.top/Article/details/gtmdmtzcmz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtwvlgtdrm.html

[A10] 生成随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtaieaizfp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xuetiantiany.cn/Article/details/gtwxqoxgpi.html

PHP:  random_int(1, 100);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcjykkvd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.9152youxi.cn/Article/details/gtxvjihedz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dianchejie.cn/Article/details/gttwlphbob.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guannengcc.top/Article/details/gthiqdunvl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.tian-w.cn/Article/details/gtfookqlgn.html

Ruby: rand(1..100)
来源：http://dali.tian-w.cn/Article/details/gtjakiybhv.html

C#:   new Random().Next(1, 101)
来源：http://dali.vqdsnc.cn/Article/details/gtsvcctiwk.html

[A11] 条件表达式（三元）
来源：http://dali.yvedp.cn/Article/details/gtmslipfun.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.iojbl.cn/Article/details/gtprttehch.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gtpzergunk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtcktwqbbf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gtkyptzinv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gttvmzylup.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcbvbhdz.html


<!-- 参考信息 -->