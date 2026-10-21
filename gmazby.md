代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.xuetiantiany.cn/Article/details/gtojwhmffd.html

parse_ini_file("config.ini", true)
来源：http://dali.wangshuangyany.cn/Article/details/gtutoifumn.html

[U74] PHP：读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtxglxxogj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ppjwa.cn/Article/details/gtaevyqcxj.html

[U75] PHP：依赖注入
来源：http://dali.shzxlz.cn/Article/details/gtzrmtwyed.html

composer require psr/container
来源：http://dali.xinyue.icu/Article/details/gtqovfznzn.html

[U76] PHP：简单路由
来源：http://dali.ppjwa.cn/Article/details/gtyrmonmpu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shangyingyoupin.top/Article/details/gtmjqaznyh.html

[U77] PHP：模板渲染
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocrbdvhh.html

composer require twig/twig
来源：http://dali.hfpthk.cn/Article/details/gtgbknsswd.html

[U78] PHP：单元测试
来源：http://dali.pengpengdd.cyou/Article/details/gtpvdqaspr.html

composer require --dev phpunit/phpunit
来源：http://dali.jyoumei.cn/Article/details/gtuyzatqkq.html

[U79] PHP：静态分析
来源：http://dali.kuanghao11.cn/Article/details/gtjvjwqxmm.html

composer require --dev phpstan/phpstan
来源：http://dali.andypj.xyz/Article/details/gtkkxfqirx.html

[U80] PHP：代码规范修复
来源：http://dali.zycfv.cn/Article/details/gtpnfioqgw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gzhubu.top/Article/details/gtnuqpuups.html

[U81] JS：初始化项目
来源：http://dali.nanxinkj.top/Article/details/gtxilhlhjk.html

npm init -y;  npm i express
来源：http://dali.snrcjt.cn/Article/details/gtzyjtkxnt.html

[U82] JS：package.json 脚本
来源：http://dali.quarkkingdee.top/Article/details/gtxzzouthi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shzxlz.cn/Article/details/gtdtlmmthk.html

[U83] JS：ES Module 导入导出
来源：http://dali.shzxlz.cn/Article/details/gtcljxyzdj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtzqqvpjis.html

[U84] JS：CommonJS 写法
来源：http://dali.guannengcc.top/Article/details/gtuqvjkeid.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangdashe.top/Article/details/gtwzikjsce.html

[U85] JS：可选链
来源：http://dali.shangyingyoupin.top/Article/details/gtqtgqjoej.html

a?.b?.c
来源：http://dali.meibo888.top/Article/details/gthblyafyd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gtsngrntse.html

a ?? b
来源：http://dali.sysykeji.top/Article/details/gtjejyfhqx.html

[U87] JS：解构默认值
来源：http://dali.daria6918.cn/Article/details/gtdlbwpynr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.kuanghao11.cn/Article/details/gtudwcopkm.html

[U88] JS：对象展开合并
来源：http://dali.gzhubu.top/Article/details/gtgyuuyedw.html

{ ...a, ...b }
来源：http://dali.yonumen.top/Article/details/gtqnpyrvav.html

[U89] JS：数组去重
来源：http://dali.9152youxi.cn/Article/details/gtmxjlcitg.html

[...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtvizobyap.html

[U90] JS：数字数组排序
来源：http://dali.nanxuanxn.top/Article/details/gtwbkwqrqj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtpokdpqxv.html

[U91] JS：对象键值遍历
来源：http://dali.cucudq.cn/Article/details/gtejsgalpo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sxryk.cn/Article/details/gtjdstjcqv.html

[U92] JS：深拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqojemfsv.html

structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtcjfjzeym.html

[U93] JS：模板字符串
来源：http://dali.cucudq.cn/Article/details/gtjudesqsp.html

`共 ${n} 条`
来源：http://dali.cucudq.cn/Article/details/gtiihbyzlt.html

[U94] JS：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gtosttpbad.html

const double = x => x * 2;
来源：http://dali.daria6918.cn/Article/details/gtlsrjhfhx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gtorypcxrk.html

new Promise((resolve, reject) => {})
来源：http://dali.iojbl.cn/Article/details/gtmurisdcs.html

[U96] JS：async/await 与异常
来源：http://dali.wangdashe.top/Article/details/gtyqpbmeip.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtijvlgmyh.html

[U97] JS：并发请求
来源：http://dali.9152youxi.cn/Article/details/gtkjuddbga.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtufipqhwy.html

[U98] JS：fetch 带 JSON
来源：http://dali.xziqi.cn/Article/details/gtcflrklyw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangshuangyany.cn/Article/details/gtdlcctvjy.html

[U99] JS：事件监听
来源：http://dali.ivvv.top/Article/details/gtkekvcdus.html

el.addEventListener("click", e => {})
来源：http://dali.shuidangran.top/Article/details/gtjiuvgltn.html

[U100] JS：DOM 查询
来源：http://dali.fzhhl.top/Article/details/gtmzndaltc.html

document.querySelector(".item")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzgtfhma.html

[U101] JS：classList 操作
来源：http://dali.sxryk.cn/Article/details/gtfyeqirre.html

el.classList.toggle("active")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoiefkvo.html

[U102] JS：本地存储
来源：http://dali.hnxiangtu.top/Article/details/gtctzppdcm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.fengsongda.top/Article/details/gtufdoebix.html

[U103] JS：定时器
来源：http://dali.meibo888.top/Article/details/gtfefjniaw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.dashuyun.cn/Article/details/gtzkxykhwa.html

[U104] JS：防抖
来源：http://dali.shuidangran.top/Article/details/gtgadmgvnj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtsjmnfayx.html

[U105] JS：节流
来源：http://dali.daxiang520.top/Article/details/gtmazfyqbb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhengqikj.top/Article/details/gtlsowiwxv.html

[U106] JS：日期格式化
来源：http://dali.yueranfly.top/Article/details/gthjbjwuvi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shzxlz.cn/Article/details/gtgkznztxr.html

[U107] JS：数字千分位
来源：http://dali.yvedp.cn/Article/details/gthurreyut.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtgwhtlleh.html

[U108] JS：随机整数
来源：http://dali.yonumen.top/Article/details/gtualwwwqu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aibaodan.cn/Article/details/gtyajvuqzp.html

[U109] JS：数组分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtamjvygui.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gtefjomqio.html

[U110] JS：数组分块
来源：http://dali.jinghuilouyu.cn/Article/details/gtztdqhdud.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258.top/Article/details/gtvsxipkod.html

[U111] JS：对象转 Map
来源：http://dali.mhx1999.top/Article/details/gtvfizesox.html

new Map(Object.entries(obj))
来源：http://dali.zhixingplan.top/Article/details/gtrxcpznwj.html

[U112] JS：字符串补位
来源：http://dali.hywenlv.cn/Article/details/gtezljswnd.html

"7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtimnzzqed.html

[U113] JS：正则替换全部
来源：http://dali.ivvv.top/Article/details/gtisbwphek.html

s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtkkwjuoyx.html

[U114] JS：JSON 深比较
来源：http://dali.xziqi.cn/Article/details/gtbigjurhg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gtiknagynl.html

[U115] JS：生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtocmyxsrn.html

crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtandurezl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.bjfxy.top/Article/details/gtbejyogwz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuanzx.com/Article/details/gttxnilaxg.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gtrsptutlr.html

npm i -D vitest;  npx vitest
来源：http://dali.hnxiangtu.top/Article/details/gtwrifsljo.html

[U118] JS：开发服务器
来源：http://dali.haohaochexian.top/Article/details/gtvqcpnwhx.html

npm i -D vite;  npx vite
来源：http://dali.pycfn.com/Article/details/gtmubboace.html

[U119] JS：生产构建
来源：http://dali.yvedp.cn/Article/details/gtnulcmzxp.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajorkbml.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.0kj1m.cn/Article/details/gtqmgivysm.html

import.meta.env.VITE_API_URL
来源：http://dali.ehwqpu.com/Article/details/gtschnmsav.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtptyicuxr.html

统计汇总
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxruglgri.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtdhkeblon.html

按语言统计（条）：
来源：http://dali.redwolf501.top/Article/details/gthczvogqo.html

Python ......... 252
来源：http://dali.quarkkingdee.top/Article/details/gtuijrxjiy.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gtkdpbdysn.html

JavaScript ..... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyhwrzmd.html

TypeScript ..... 212
来源：http://dali.chenlongwang.top/Article/details/gtkiropazw.html

Java ........... 212
来源：http://dali.fengsongda.top/Article/details/gtunmrjrrk.html

Go ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gtbvmemacd.html

Ruby ........... 212
来源：http://dali.nwbrower.top/Article/details/gtquqjvsky.html

C# ............. 212
来源：http://dali.snrcjt.cn/Article/details/gtyeyjxbqs.html

C .............. 30
来源：http://dali.feifeiyinyue.top/Article/details/gtxxuypmgm.html

C++ ............ 30
来源：http://dali.xuetiantiany.cn/Article/details/gtflpddzva.html

SQL ............ 90
来源：http://dali.vqdsnc.cn/Article/details/gtxhzhignk.html

Bash ........... 80
来源：http://dali.tian-w.cn/Article/details/gtqfzcxlwb.html

Kotlin ......... 15
来源：http://dali.feifeiyinyue.top/Article/details/gtbvsfvdgm.html

Swift .......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gtczpoxxcq.html

Lua ............ 10
来源：http://dali.yonumen.top/Article/details/gtcebwzpof.html

Perl ........... 10
来源：http://dali.hysaishi.cn/Article/details/gthfkcoefn.html

Scala .......... 10
来源：http://dali.fengsongda.top/Article/details/gtauuxshfv.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtrgwgcvpm.html

合计 ........... 2106 条
来源：http://dali.iojbl.cn/Article/details/gtdwmhabqw.html

按章节统计：
来源：http://dali.zhiwuduotai.top/Article/details/gtwckmzsvm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gtmulzzzho.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtveoathvz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yonumen.top/Article/details/gtkucjsuzw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fzhhl.top/Article/details/gtppamppkr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nanxuanxn.top/Article/details/gtwlisnsag.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gtotrmkhgw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtbzphhawd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gtwekkruuz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtbljiaazl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.havefunace.top/Article/details/gtrhxhuipl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtjjvlqwgm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtedvcseoa.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtxpgtvkvf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gtbsdsygpp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhoulong.xyz/Article/details/gtzkfncdtg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtznavcnfp.html

Q SQL 专题                              90
来源：http://dali.daxiang520.top/Article/details/gtozdhdted.html

R Bash 专题                             80
来源：http://dali.yvedp.cn/Article/details/gtkyowbwye.html

S C / C++ 专题                          60
来源：http://dali.nanxinkj.top/Article/details/gtxyvfwpkl.html

T 其他语言补充                          60
来源：http://dali.yj20258.top/Article/details/gtadqajwfn.html

U 高频实用片段                         120
来源：http://dali.ybcxt.top/Article/details/gthrwqrfpf.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtqguuzllx.html

合计                                  2106 条
来源：http://dali.guannengcc.top/Article/details/gtsizlhsbt.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtenvwfgcb.html

使用提醒
来源：http://dali.zycfv.cn/Article/details/gtwxexefbs.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtefkwjyik.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinghuilouyu.cn/Article/details/gttlwtywah.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigfzy.top/Article/details/gtvyggkhzg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.haohaochexian.top/Article/details/gtunxugpzf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xinyue.icu/Article/details/gtjdjqeesf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.feifeiyinyue.top/Article/details/gtcmtyfyym.html

—— 文件结束 ——
来源：http://dali.ppjwa.cn/Article/details/gtdfrziucb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gteghgqscd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.aizwys.cn/Article/details/gtloclgnqd.html

Common Programming Examples Cheat Book
来源：http://dali.jianghu66.top/Article/details/gtmgxdcsem.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtuhejkyds.html

【收录内容】
来源：http://dali.wangdashe.top/Article/details/gtdgzzwhal.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zdqjudy.top/Article/details/gtjpcpklsr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cashguo.top/Article/details/gtjsiywkfb.html

SQL · Bash · C · C++
来源：http://dali.gaohongyu789.top/Article/details/gtbhvpecmu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigufen.top/Article/details/gtmrqwusdj.html

【使用说明】
来源：http://dali.jqgfzy.top/Article/details/gtlidxpxlh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqtuxcie.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.iojbl.cn/Article/details/gtiyoooslo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jyoumei.cn/Article/details/gtflcnpmpe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shuidangran.top/Article/details/gtosxcgimd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhixingplan.top/Article/details/gtkkdbjikx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ivvv.top/Article/details/gthqrkdkac.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.fzhhl.top/Article/details/gtqytlgcgz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.wangshuangyany.cn/Article/details/gtihdzzaed.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jyoumei.cn/Article/details/gtwaeycytr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.kuanghao11.cn/Article/details/gttvlkgoyh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tanke756.top/Article/details/gtamldetrd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.iojbl.cn/Article/details/gtgqhbyflc.html

【文件统计】
来源：http://dali.jqgufenzy.top/Article/details/gtdbwpboph.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xziqi.cn/Article/details/gtgvqnmovz.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gtjvmgdgkb.html

目  录
来源：http://dali.gaohongyu789.top/Article/details/gttxtbkyot.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtpmkhuibv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sysykeji.top/Article/details/gtqrttappj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtourzhcov.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gtrxfjdyqi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ehwqpu.com/Article/details/gtxfxzytoq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.dianchejie.cn/Article/details/gtenzubkoe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuxming.cn/Article/details/gtfedxgbtw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtthynelfz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cheryme.top/Article/details/gtvtvwsmhu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gtpwvqzshm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gzhubu.top/Article/details/gtgauckfgm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtprvrkrlc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtvienwwnl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtouavfgqg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenjidiqi.icu/Article/details/gteqwuvcpd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nanxinkj.top/Article/details/gtskmqmmdk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtshcoebqj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtkrvklcqo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jiagoushi.top/Article/details/gtqafeuppk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.daria6918.cn/Article/details/gtfvyzdmro.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gtkdciuxxl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtifzmaqqp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvbjeomld.html

A. 基础语法与类型
来源：http://dali.dashuyun.cn/Article/details/gtcraqfqwf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqveusfwo.html

[A01] Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtjakudvot.html

Py:   print("Hello, World!")
来源：http://dali.cqqwz.cn/Article/details/gtregshlwa.html

PHP:  echo "Hello, World!";
来源：http://dali.tian-w.cn/Article/details/gtrcdgoajg.html

JS:   console.log("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gtppwxnabr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnxqqozt.html

Java: System.out.println("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gtpgfrfmxi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenzaomai.com/Article/details/gtxsyjfyjk.html

Ruby: puts "Hello, World!"
来源：http://dali.chenlongwang.top/Article/details/gtoejmaqkq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gtesgmtldt.html

[A02] 变量声明与赋值
来源：http://dali.aizwys.cn/Article/details/gtcnufmzwy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xinyue.icu/Article/details/gtexdklshv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.smart0.xyz/Article/details/gtruxxvgda.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gtawimqbba.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gogol.net.cn/Article/details/gtpbndwxyk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtyxepaavl.html

Go:   name := "Alex"; age := 20
来源：http://dali.sweek.top/Article/details/gtehuxfwxr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.svipenyu.cn/Article/details/gtzpzrxhzr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xinyue.icu/Article/details/gtgevfdcjt.html

[A03] 常量定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmlrsfuk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.vqdsnc.cn/Article/details/gtpekbjwbn.html

PHP:  const PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtymcluloq.html

JS:   const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtjhnredoq.html

TS:   const PI: number = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtcdwaodlw.html

Java: static final double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtfbjvbrnn.html

Go:   const PI = 3.14159
来源：http://dali.zdqjudy.top/Article/details/gtjiaqohrg.html

Ruby: PI = 3.14159
来源：http://dali.guannengcc.top/Article/details/gtcqzsxixd.html

C#:   const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtaeoghlzv.html

[A04] 判断变量类型
来源：http://dali.zdqjudy.top/Article/details/gtcnmoxniw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztxkpahp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ppjwa.cn/Article/details/gtuyjptzld.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gtrsfddknb.html

TS:   typeof x; x instanceof Date
来源：http://dali.shzxlz.cn/Article/details/gtxaoqbpdo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ehwqpu.com/Article/details/gtvfpnoryr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yuanzhike.top/Article/details/gtpoocvmuo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xylfe.cn/Article/details/gtfljlbrwg.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenjidiqi.icu/Article/details/gtccpaipba.html

[A05] 整数除法与取模
来源：http://dali.cdnleiting.top/Article/details/gtrnnqhyyw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.feifeiyinyue.top/Article/details/gthjughinc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtlzzyizgf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtwrmalqbu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtauciigfm.html

Java: 7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtbyssitky.html

Go:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtnfuwiboh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtedycscwr.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtttdpjfdd.html

[A06] 字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gtfzqbrnnn.html

Py:   int("42"); float("3.14")
来源：http://dali.9152youxi.cn/Article/details/gttgbfezrk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.meibo888.top/Article/details/gtjfoskvoe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.mhx1999.top/Article/details/gtofczploo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.tianlin.xyz/Article/details/gtwoxrdzlc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.redwolf501.top/Article/details/gthepjazpc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.feifeiyinyue.top/Article/details/gttdjdqowz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.pengpengdd.cyou/Article/details/gtlwdlmnhl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258.top/Article/details/gttcptsthl.html

[A07] 数字转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkdwsxvp.html

Py:   str(42)
来源：http://dali.hfpthk.cn/Article/details/gtftpkceyh.html

PHP:  (string) 42; strval(42)
来源：http://dali.sxryk.cn/Article/details/gtfcbaqbrw.html

JS:   String(42); (42).toString()
来源：http://dali.chenlongwang.top/Article/details/gtwnlnynep.html

TS:   String(42)
来源：http://dali.ehwqpu.com/Article/details/gtbtwymete.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xinyue.icu/Article/details/gtllxxthws.html

Go:   strconv.Itoa(42)
来源：http://dali.gotoacloud.top/Article/details/gtuaibzqdo.html

Ruby: 42.to_s
来源：http://dali.vqdsnc.cn/Article/details/gttpoxzjja.html

C#:   42.ToString()
来源：http://dali.sweek.top/Article/details/gtfduzsxml.html

[A08] 取整与四舍五入
来源：http://dali.yongpay.top/Article/details/gtmmiveeuz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtduohgnmp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.dashuyun.cn/Article/details/gtxeiboyyt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gtsujbnevt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.9152youxi.cn/Article/details/gtftyjtgxs.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbknlzvjc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gtqzvgdhtn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ppjwa.cn/Article/details/gtnacerxep.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtsbmmdkvr.html

[A09] 绝对值与最大最小值
来源：http://dali.redwolf501.top/Article/details/gteyvrsgdw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtszwlduic.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtdhnmztjz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtqiaokcti.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtcyxhtgvm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtulunhbxm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.kuanghao11.cn/Article/details/gtmvxwlmcb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.vqdsnc.cn/Article/details/gtbaurcefh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtxuswdhvw.html

[A10] 生成随机数
来源：http://dali.yueranfly.top/Article/details/gtmigljtrs.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yonumen.top/Article/details/gtuhoqicng.html

PHP:  random_int(1, 100);
来源：http://dali.ehwqpu.com/Article/details/gttoysbave.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.9152youxi.cn/Article/details/gthujiiewd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shzxlz.cn/Article/details/gtxiknhwxc.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjnbeehf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.316326.xyz/Article/details/gtqfvfmahr.html

Ruby: rand(1..100)
来源：http://dali.shangyingyoupin.top/Article/details/gtwerhntve.html

C#:   new Random().Next(1, 101)
来源：http://dali.xuanzx.com/Article/details/gtncrrnvoh.html

[A11] 条件表达式（三元）
来源：http://dali.gzhubu.top/Article/details/gtzfntscgt.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hysaishi.cn/Article/details/gtfidwcztg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gtzfvllopn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwrocoia.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gtnplhllpv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtmavfxfgv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.redwolf501.top/Article/details/gtwdcfcvzx.html


<!-- 参考信息 -->