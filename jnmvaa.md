代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.yanxiufei.cn/Article/details/gt2uzwgpkpg.html

composer require psr/container
来源：http://dali.sxryk.cn/Article/details/gt2pcgjidkd.html

[U76] PHP：简单路由
来源：http://dali.cqqwz.cn/Article/details/gt2drivelqe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqmplpzz.html

[U77] PHP：模板渲染
来源：http://dali.yongpay.top/Article/details/gt2byohufiz.html

composer require twig/twig
来源：http://dali.yuanzhike.top/Article/details/gt2woroevjf.html

[U78] PHP：单元测试
来源：http://dali.ydzc1.top/Article/details/gt2quheycmy.html

composer require --dev phpunit/phpunit
来源：http://dali.hongshengwenyu.top/Article/details/gt2lastvevt.html

[U79] PHP：静态分析
来源：http://dali.cucudq.cn/Article/details/gt2amlqlnlt.html

composer require --dev phpstan/phpstan
来源：http://dali.feifeiyinyue.top/Article/details/gt2enrqqtef.html

[U80] PHP：代码规范修复
来源：http://dali.vqdsnc.cn/Article/details/gt2wixvkyjn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hnxiangtu.top/Article/details/gt2mvnttrny.html

[U81] JS：初始化项目
来源：http://dali.snrcjt.cn/Article/details/gt2cspqhsvs.html

npm init -y;  npm i express
来源：http://dali.redwolf501.top/Article/details/gt2nupfrmdg.html

[U82] JS：package.json 脚本
来源：http://dali.tianlin.xyz/Article/details/gt2itpzrpzv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dianchejie.cn/Article/details/gt2dtemrmca.html

[U83] JS：ES Module 导入导出
来源：http://dali.yj20258888.top/Article/details/gt2ipljvjdz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj202588.top/Article/details/gt2ocoadveb.html

[U84] JS：CommonJS 写法
来源：http://dali.yvedp.cn/Article/details/gt2fbwwpryx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dashuyun.cn/Article/details/gt2ymqrgncf.html

[U85] JS：可选链
来源：http://dali.jinqigufen.top/Article/details/gt2nxbrnjic.html

a?.b?.c
来源：http://dali.shuidangran.top/Article/details/gt2qxqnlcnt.html

[U86] JS：空值合并
来源：http://dali.andypj.xyz/Article/details/gt2weylpvoe.html

a ?? b
来源：http://dali.dashuyun.cn/Article/details/gt2rypdwvjh.html

[U87] JS：解构默认值
来源：http://dali.nanxinkj.top/Article/details/gt2mmrhkziw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.snrcjt.cn/Article/details/gt2srlvkbvu.html

[U88] JS：对象展开合并
来源：http://dali.yvedp.cn/Article/details/gt2whyjtdcq.html

{ ...a, ...b }
来源：http://dali.nanxuanxn.top/Article/details/gt2qfhqfbjc.html

[U89] JS：数组去重
来源：http://dali.cheryme.top/Article/details/gt2endshsyo.html

[...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gt2tenggsqm.html

[U90] JS：数字数组排序
来源：http://dali.yj202588.top/Article/details/gt2qrigqqwi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gt2tgmmxzig.html

[U91] JS：对象键值遍历
来源：http://dali.ehwqpu.com/Article/details/gt2lkhifvwb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinqigufen.top/Article/details/gt2iywajcdg.html

[U92] JS：深拷贝
来源：http://dali.zhoulong.xyz/Article/details/gt2opvkpawn.html

structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gt2qinalevj.html

[U93] JS：模板字符串
来源：http://dali.shzxlz.cn/Article/details/gt2frimzhzo.html

`共 ${n} 条`
来源：http://dali.jinqigufen.top/Article/details/gt2ksqxyfxw.html

[U94] JS：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gt2rutttnko.html

const double = x => x * 2;
来源：http://dali.smart0.xyz/Article/details/gt2yblcirzr.html

[U95] JS：Promise 包装
来源：http://dali.guannengcc.top/Article/details/gt2cmvjadyy.html

new Promise((resolve, reject) => {})
来源：http://dali.sufxvd.cn/Article/details/gt2utdkimrw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkidvku.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2bzubeisb.html

[U97] JS：并发请求
来源：http://dali.hfpthk.cn/Article/details/gt2onwnzpnl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2rswxrlyi.html

[U98] JS：fetch 带 JSON
来源：http://dali.gogol.net.cn/Article/details/gt2oidtatht.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yuxming.cn/Article/details/gt2fyhgmvbd.html

[U99] JS：事件监听
来源：http://dali.pycfn.com/Article/details/gt2ntyeghbb.html

el.addEventListener("click", e => {})
来源：http://dali.jqgufenzy.top/Article/details/gt2eazgehiz.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gt2rggifllx.html

document.querySelector(".item")
来源：http://dali.jlsjyb.cn/Article/details/gt2tlpunwhg.html

[U101] JS：classList 操作
来源：http://dali.gotoacloud.top/Article/details/gt2lqcnmrym.html

el.classList.toggle("active")
来源：http://dali.yvedp.cn/Article/details/gt2rkwqxfii.html

[U102] JS：本地存储
来源：http://dali.nanxinkj.top/Article/details/gt2amrspwbk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtnvzqya.html

[U103] JS：定时器
来源：http://dali.xylfe.cn/Article/details/gt2npbbblby.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gt2ysqtlzfm.html

[U104] JS：防抖
来源：http://dali.gaohongyu789.top/Article/details/gt2teiralep.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2bbvxgzfk.html

[U105] JS：节流
来源：http://dali.yvedp.cn/Article/details/gt2horohotw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2nimqfdtv.html

[U106] JS：日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2seucqhba.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yuanzhike.top/Article/details/gt2yfarprph.html

[U107] JS：数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gt2fvpbbwdo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tanke756.top/Article/details/gt2jhpyjatg.html

[U108] JS：随机整数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbqnzxba.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhixingplan.top/Article/details/gt2xraxvbbe.html

[U109] JS：数组分组
来源：http://dali.zhoulong.xyz/Article/details/gt2hlaucoan.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqyywzqm.html

[U110] JS：数组分块
来源：http://dali.wangdashe.top/Article/details/gt2scqbllgx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cqqwz.cn/Article/details/gt2deiyarrg.html

[U111] JS：对象转 Map
来源：http://dali.cucudq.cn/Article/details/gt2fqscoeic.html

new Map(Object.entries(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2xrgvlghe.html

[U112] JS：字符串补位
来源：http://dali.hammf.cn/Article/details/gt2katyllsv.html

"7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2jmzhdkbt.html

[U113] JS：正则替换全部
来源：http://dali.gotoacloud.top/Article/details/gt2riwavoow.html

s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2maqwfrnq.html

[U114] JS：JSON 深比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcyhgbph.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gt2tthyqhlo.html

[U115] JS：生成 UUID
来源：http://dali.sweek.top/Article/details/gt2deanwocz.html

crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2bmjtdktk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cucudq.cn/Article/details/gt2cupskpnt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.316326.xyz/Article/details/gt2hnujeyxg.html

[U117] JS：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gt2tshdeljq.html

npm i -D vitest;  npx vitest
来源：http://dali.ivvv.top/Article/details/gt2vxdctgqv.html

[U118] JS：开发服务器
来源：http://dali.snrcjt.cn/Article/details/gt2hpybdcyh.html

npm i -D vite;  npx vite
来源：http://dali.hfpthk.cn/Article/details/gt2aixmtmxk.html

[U119] JS：生产构建
来源：http://dali.ehwqpu.com/Article/details/gt2wvgbviaq.html

npx vite build
来源：http://dali.chenzaomai.com/Article/details/gt2ziwiyncb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hnxiangtu.top/Article/details/gt2cgvwkfka.html

import.meta.env.VITE_API_URL
来源：http://dali.smart0.xyz/Article/details/gt2rlvzmmtt.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2rhkwgooh.html

统计汇总
来源：http://dali.iojbl.cn/Article/details/gt2glhhhudq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2oeaeirjx.html

按语言统计（条）：
来源：http://dali.sxryk.cn/Article/details/gt2ytpeefjy.html

Python ......... 252
来源：http://dali.hnxiangtu.top/Article/details/gt2chknsluh.html

PHP ............ 252
来源：http://dali.gaohongyu789.top/Article/details/gt2colmxrkg.html

JavaScript ..... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmdlhsex.html

TypeScript ..... 212
来源：http://dali.aizwys.cn/Article/details/gt2rppatdvv.html

Java ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbjokjzg.html

Go ............. 212
来源：http://dali.ybcxt.top/Article/details/gt2lzmpydai.html

Ruby ........... 212
来源：http://dali.svipenyu.cn/Article/details/gt2fftioork.html

C# ............. 212
来源：http://dali.daxiang520.top/Article/details/gt2hlkivodn.html

C .............. 30
来源：http://dali.yvedp.cn/Article/details/gt2lssayzdr.html

C++ ............ 30
来源：http://dali.c1oappe.top/Article/details/gt2sthhfmac.html

SQL ............ 90
来源：http://dali.aibaodan.cn/Article/details/gt2sfndpwer.html

Bash ........... 80
来源：http://dali.0kj1m.cn/Article/details/gt2egrqgcxe.html

Kotlin ......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gt2copkgwdx.html

Swift .......... 15
来源：http://dali.meibo888.top/Article/details/gt2ykxvydnf.html

Lua ............ 10
来源：http://dali.316326.xyz/Article/details/gt2lddqzsjm.html

Perl ........... 10
来源：http://dali.redwolf501.top/Article/details/gt2deoqraug.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzvqtjj.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gt2sknqvhch.html

合计 ........... 2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezfxwosv.html

按章节统计：
来源：http://dali.shuidangran.top/Article/details/gt2zdcdpife.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gt2qvdgytjz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gt2pxjhvqox.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2jqrxeqhn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gt2chsechfi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhixingplan.top/Article/details/gt2pjwvwpad.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2popkkcer.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gt2ddampsfq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnxiangtu.top/Article/details/gt2ydfaxyjz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2hsdrbnjr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gt2clefffjm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gt2crhyybra.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gt2kyupzidz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gt2ucppdijt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gt2hydxnoix.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wpcglxfa.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzzofwai.html

Q SQL 专题                              90
来源：http://dali.sweek.top/Article/details/gt2mhsxwrkl.html

R Bash 专题                             80
来源：http://dali.yanxiufei.cn/Article/details/gt2lccedrax.html

S C / C++ 专题                          60
来源：http://dali.ivvv.top/Article/details/gt2nssgjtoa.html

T 其他语言补充                          60
来源：http://dali.fzhhl.top/Article/details/gt2jrrnfpqk.html

U 高频实用片段                         120
来源：http://dali.jqgufenzy.top/Article/details/gt2wikselyn.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gt2sijorzbv.html

合计                                  2106 条
来源：http://dali.xylfe.cn/Article/details/gt2bzbpocfr.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gt2esmexkqn.html

使用提醒
来源：http://dali.0kj1m.cn/Article/details/gt2xrwytjpi.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzoixpzw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xinyue.icu/Article/details/gt2hudrcxnr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guowangkeji.top/Article/details/gt2ovimnudw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsxvswkq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hysaishi.cn/Article/details/gt2xrnnkrjc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.bjfxy.top/Article/details/gt2wrrbhjwx.html

—— 文件结束 ——
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sadkaqed.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqnosed.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ehwqpu.com/Article/details/gt2npwejvsw.html

Common Programming Examples Cheat Book
来源：http://dali.havefunace.top/Article/details/gt2cpybhbon.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2cqygnpqt.html

【收录内容】
来源：http://dali.yuanzhike.top/Article/details/gt2fzwyvzir.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgeqtpzj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.dashuyun.cn/Article/details/gt2gaaokxyq.html

SQL · Bash · C · C++
来源：http://dali.nwbrower.top/Article/details/gt2qhzxsyiy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xuanzx.com/Article/details/gt2uisuyjjf.html

【使用说明】
来源：http://dali.ybcxt.top/Article/details/gt2heigucch.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.9152youxi.cn/Article/details/gt2fqvkxrlg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nwbrower.top/Article/details/gt2zuifsilj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgufenzy.top/Article/details/gt2azftmegy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sufxvd.cn/Article/details/gt2ftujdxlt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hywenlv.cn/Article/details/gt2cdibbghj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hammf.cn/Article/details/gt2inlgofas.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uonilthh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xylfe.cn/Article/details/gt2gkkptkme.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xuanzx.com/Article/details/gt2lcevoqpd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.316326.xyz/Article/details/gt2rgqjhnit.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dclcdbte.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xylfe.cn/Article/details/gt2naythoim.html

【文件统计】
来源：http://dali.yvedp.cn/Article/details/gt2qvvkkqwq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shzxlz.cn/Article/details/gt2jcozwpos.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2igwsywue.html

目  录
来源：http://dali.wangdashe.top/Article/details/gt2csriqwbg.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gt2xriosiae.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.meibo888.top/Article/details/gt2fklcbnmh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gt2igpnanjt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2wfhwkbkr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cashguo.top/Article/details/gt2rxtajayf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.wangdashe.top/Article/details/gt2vjzhblxs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2xecadqfw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gt2mwqbiotr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2havycrxr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gt2ognaegww.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258.top/Article/details/gt2thnzpzst.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gt2tugegpkn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gt2lccsbssu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gt2yncnwcey.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jqgfzy.top/Article/details/gt2uakqnddu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangdashe.top/Article/details/gt2ptujhjxn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2abbtexfp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xylfe.cn/Article/details/gt2bybtpdia.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.chenzaomai.com/Article/details/gt2xpigbakq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigufen.top/Article/details/gt2ehrzudxr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gt2tpchlvls.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gt2aquxrtuy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2mineeccl.html

A. 基础语法与类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpfhhlqu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xmiwpufi.html

[A01] Hello World
来源：http://dali.yj20258.top/Article/details/gt2tpnmdgyd.html

Py:   print("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gt2ttxflxdx.html

PHP:  echo "Hello, World!";
来源：http://dali.guannengcc.top/Article/details/gt2eorsdqfc.html

JS:   console.log("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gt2gradjkhd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinqigfzy.top/Article/details/gt2daoxaqnn.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nsarjhih.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jlsjyb.cn/Article/details/gt2tbdtuexq.html

Ruby: puts "Hello, World!"
来源：http://dali.cucudq.cn/Article/details/gt2csndxqxt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aujwogsx.html

[A02] 变量声明与赋值
来源：http://dali.aizwys.cn/Article/details/gt2dcezsyet.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.dianchejie.cn/Article/details/gt2udvvicoz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xinyue.icu/Article/details/gt2wqkbkybv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cdnleiting.top/Article/details/gt2qhcpddfu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ydzc1.top/Article/details/gt2wmruqbes.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gt2rtxhtifq.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258.top/Article/details/gt2illdlyhj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xziqi.cn/Article/details/gt2ygqbapnf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xuanzx.com/Article/details/gt2nubwzsum.html

[A03] 常量定义
来源：http://dali.mhx1999.top/Article/details/gt2pfajwobz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenjidiqi.icu/Article/details/gt2oicvkeyi.html

PHP:  const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2lojwdpov.html

JS:   const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2uaqfsput.html

TS:   const PI: number = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gtynzdgc.html

Java: static final double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2wccixyuf.html

Go:   const PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gt2afdevdmh.html

Ruby: PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gt2wjhasrwy.html

C#:   const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2owjlafvt.html

[A04] 判断变量类型
来源：http://dali.ydzc1.top/Article/details/gt2kmkofvxa.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xuanzx.com/Article/details/gt2undrmvwk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guannengcc.top/Article/details/gt2nihaqmrg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yj20258888.top/Article/details/gt2coezulyy.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgufenzy.top/Article/details/gt2onbooluz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.mhx1999.top/Article/details/gt2yifeqrmv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenzaomai.com/Article/details/gt2vqruouov.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cdnleiting.top/Article/details/gt2smsuickd.html

C#:   x.GetType().Name; x is int
来源：http://dali.dashuyun.cn/Article/details/gt2ccydlagr.html

[A05] 整数除法与取模
来源：http://dali.mhx1999.top/Article/details/gt2dypbuipp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.redwolf501.top/Article/details/gt2xqdwabvw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gt2ecflgwig.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gt2pvsiitqk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2yecwssft.html

Java: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eglcmdtj.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjrnunaj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukirfyen.html

C#:   7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2aogkavgv.html

[A06] 字符串转数字
来源：http://dali.smart0.xyz/Article/details/gt2euvctmyo.html

Py:   int("42"); float("3.14")
来源：http://dali.jianghu66.top/Article/details/gt2lqsxkfys.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xuanzx.com/Article/details/gt2ljiinmyl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhiwuduotai.top/Article/details/gt2luzdwrhn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gt2wjhkosyh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gt2iogtalzt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.vqdsnc.cn/Article/details/gt2xhvlwfyv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.dashuyun.cn/Article/details/gt2yzpnhcmi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xsxmttdd.html

[A07] 数字转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bncyykjq.html

Py:   str(42)
来源：http://dali.9152youxi.cn/Article/details/gt2thjbmzde.html

PHP:  (string) 42; strval(42)
来源：http://dali.bjfxy.top/Article/details/gt2uejrrgrc.html

JS:   String(42); (42).toString()
来源：http://dali.dianchejie.cn/Article/details/gt2igybcmxf.html

TS:   String(42)
来源：http://dali.hywenlv.cn/Article/details/gt2jusylkxk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.meibo888.top/Article/details/gt2knunoqfg.html

Go:   strconv.Itoa(42)
来源：http://dali.tanke756.top/Article/details/gt2gbtqkfym.html

Ruby: 42.to_s
来源：http://dali.xinyue.icu/Article/details/gt2oxfhzrcx.html

C#:   42.ToString()
来源：http://dali.yj20258888.top/Article/details/gt2udxvubsb.html

[A08] 取整与四舍五入
来源：http://dali.hywenlv.cn/Article/details/gt2tvlzefra.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gt2iwpsrdcm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zycfv.cn/Article/details/gt2ozzzovwq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gt2cirtqbfr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.dianchejie.cn/Article/details/gt2kpzgedrp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gt2dwsenbmh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gt2teypkxrd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tianlin.xyz/Article/details/gt2ughhkyao.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gt2etwflpyt.html

[A09] 绝对值与最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2vbsazxxf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2bvptlpwb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2juuhandd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgaclwj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gt2jtivhsvy.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2siassdxk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.guannengcc.top/Article/details/gt2esczahbe.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.meibo888.top/Article/details/gt2hxsaifto.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sweek.top/Article/details/gt2kqkskknz.html

[A10] 生成随机数
来源：http://dali.zhongyouzk.top/Article/details/gt2ozktmybm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ybcxt.top/Article/details/gt2nhvdyfhv.html

PHP:  random_int(1, 100);
来源：http://dali.jiagoushi.top/Article/details/gt2sucrlpiy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258888.top/Article/details/gt2rwnmzxdz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guowangkeji.top/Article/details/gt2lcnfzenb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rcnqvnan.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yj20258888.top/Article/details/gt2tmxpezfo.html

Ruby: rand(1..100)
来源：http://dali.iojbl.cn/Article/details/gt2abybyxdq.html

C#:   new Random().Next(1, 101)
来源：http://dali.sxryk.cn/Article/details/gt2edcyjoml.html

[A11] 条件表达式（三元）
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzknsjro.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.smart0.xyz/Article/details/gt2mpuexuhn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gt2xuhlslop.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gt2ahsdgfqg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gt2vwvhgnaa.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdodgonk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.nanxinkj.top/Article/details/gt2woktlogw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvofmqxb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gt2iuirocmc.html

[A12] 字符串插值 / 格式化
来源：http://dali.jianghu66.top/Article/details/gt2jiifyjoo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ybcxt.top/Article/details/gt2gbkgzhau.html


<!-- 参考信息 -->