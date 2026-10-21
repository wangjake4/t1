代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.mhx1999.top/Article/details/gtzazcpkbn.html

throw new RuntimeException("失败", 500);
来源：http://dali.sufxvd.cn/Article/details/gtozepjhba.html

[U72] PHP：写错误日志
来源：http://dali.yj20258.top/Article/details/gtcqheholc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.iojbl.cn/Article/details/gthpxvrrwa.html

[U73] PHP：读取 ini 配置
来源：http://dali.nwbrower.top/Article/details/gtuglxbhxj.html

parse_ini_file("config.ini", true)
来源：http://dali.xylfe.cn/Article/details/gtuoxuqyih.html

[U74] PHP：读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtkvqdlteh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tanke756.top/Article/details/gtxhdsfcnc.html

[U75] PHP：依赖注入
来源：http://dali.dianchejie.cn/Article/details/gtnqbwralu.html

composer require psr/container
来源：http://dali.shzxlz.cn/Article/details/gtmhytxolr.html

[U76] PHP：简单路由
来源：http://dali.feifeiyinyue.top/Article/details/gtrshhxmfg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuanzhike.top/Article/details/gtncdxvflb.html

[U77] PHP：模板渲染
来源：http://dali.andypj.xyz/Article/details/gtdwcvfosi.html

composer require twig/twig
来源：http://dali.jinqigfzy.top/Article/details/gtzepqgvvs.html

[U78] PHP：单元测试
来源：http://dali.hfpthk.cn/Article/details/gtbzcnczjm.html

composer require --dev phpunit/phpunit
来源：http://dali.xylfe.cn/Article/details/gtualjbkyo.html

[U79] PHP：静态分析
来源：http://dali.cdnleiting.top/Article/details/gtatwoiznh.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrzntbjc.html

[U80] PHP：代码规范修复
来源：http://dali.zhiwuduotai.top/Article/details/gtxogiegcn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zdqjudy.top/Article/details/gtrbvgmmnc.html

[U81] JS：初始化项目
来源：http://dali.gaohongyu789.top/Article/details/gtesufuugk.html

npm init -y;  npm i express
来源：http://dali.zhiwuduotai.top/Article/details/gttnksfsvu.html

[U82] JS：package.json 脚本
来源：http://dali.pengpengdd.cyou/Article/details/gtprjhttes.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.andypj.xyz/Article/details/gtmlqokkok.html

[U83] JS：ES Module 导入导出
来源：http://dali.hfpthk.cn/Article/details/gtsrltfwmg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj20258.top/Article/details/gtwvqxfthp.html

[U84] JS：CommonJS 写法
来源：http://dali.yj20258.top/Article/details/gtgikyruyy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gtikvkcivg.html

[U85] JS：可选链
来源：http://dali.zhixingplan.top/Article/details/gtmngrmfas.html

a?.b?.c
来源：http://dali.ydzc1.top/Article/details/gtibwzquhg.html

[U86] JS：空值合并
来源：http://dali.jiagoushi.top/Article/details/gtmlpxitmv.html

a ?? b
来源：http://dali.xinyue.icu/Article/details/gtefrstryl.html

[U87] JS：解构默认值
来源：http://dali.aibaodan.cn/Article/details/gtmkcasuzr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhoulong.xyz/Article/details/gtmwaliolh.html

[U88] JS：对象展开合并
来源：http://dali.nanxinkj.top/Article/details/gtjdzslwjg.html

{ ...a, ...b }
来源：http://dali.tianlin.xyz/Article/details/gtjxvfhces.html

[U89] JS：数组去重
来源：http://dali.zhoulong.xyz/Article/details/gtftweoxrl.html

[...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gttwuyavic.html

[U90] JS：数字数组排序
来源：http://dali.yvedp.cn/Article/details/gtdgsmuiyl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtocxtwhla.html

[U91] JS：对象键值遍历
来源：http://dali.guannengcc.top/Article/details/gtpclijwqx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cucudq.cn/Article/details/gtrdqgchdl.html

[U92] JS：深拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtuvgsugyk.html

structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtwvzsltix.html

[U93] JS：模板字符串
来源：http://dali.nwbrower.top/Article/details/gtigmbebyk.html

`共 ${n} 条`
来源：http://dali.cheryme.top/Article/details/gtvhkmhjjd.html

[U94] JS：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gtxlwurdkt.html

const double = x => x * 2;
来源：http://dali.xuanzx.com/Article/details/gtegygyaip.html

[U95] JS：Promise 包装
来源：http://dali.hammf.cn/Article/details/gtugydvotk.html

new Promise((resolve, reject) => {})
来源：http://dali.cheryme.top/Article/details/gtisljrwbm.html

[U96] JS：async/await 与异常
来源：http://dali.yj20258888.top/Article/details/gtojmawthk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzcyiqhih.html

[U97] JS：并发请求
来源：http://dali.xziqi.cn/Article/details/gtyzwcmypl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtlbjzrivb.html

[U98] JS：fetch 带 JSON
来源：http://dali.snrcjt.cn/Article/details/gtsnkfyimk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhixingplan.top/Article/details/gtdzgbssod.html

[U99] JS：事件监听
来源：http://dali.sxryk.cn/Article/details/gtzjudpznd.html

el.addEventListener("click", e => {})
来源：http://dali.c1oappe.top/Article/details/gtmriinmdh.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gttniazlmt.html

document.querySelector(".item")
来源：http://dali.shzxlz.cn/Article/details/gtisbblbxm.html

[U101] JS：classList 操作
来源：http://dali.nanxinkj.top/Article/details/gteobwnpug.html

el.classList.toggle("active")
来源：http://dali.shzxlz.cn/Article/details/gtgqejltof.html

[U102] JS：本地存储
来源：http://dali.iojbl.cn/Article/details/gtqnfeptgx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbcwjevi.html

[U103] JS：定时器
来源：http://dali.ehwqpu.com/Article/details/gtrpmfjfgw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sufxvd.cn/Article/details/gtjntvvsjb.html

[U104] JS：防抖
来源：http://dali.zhixingplan.top/Article/details/gtdapnyoeq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtxqvmaqbx.html

[U105] JS：节流
来源：http://dali.xylfe.cn/Article/details/gtprkjabnf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sweek.top/Article/details/gtzlqlpeav.html

[U106] JS：日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtqhchqcjw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnxiangtu.top/Article/details/gtqswfcuiv.html

[U107] JS：数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtpywluhno.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtsdvepvlv.html

[U108] JS：随机整数
来源：http://dali.sysykeji.top/Article/details/gtpiafimip.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhengqikj.top/Article/details/gtujegeyiu.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtfbzboaer.html

Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gthsiuftwv.html

[U110] JS：数组分块
来源：http://dali.daxiang520.top/Article/details/gtxscnppzs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuanzhike.top/Article/details/gtniuqmeog.html

[U111] JS：对象转 Map
来源：http://dali.hnxiangtu.top/Article/details/gtskwglhga.html

new Map(Object.entries(obj))
来源：http://dali.jlsjyb.cn/Article/details/gtevxarcyb.html

[U112] JS：字符串补位
来源：http://dali.svipenyu.cn/Article/details/gtyyvttnno.html

"7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtxqttikfm.html

[U113] JS：正则替换全部
来源：http://dali.andypj.xyz/Article/details/gtiklrcaev.html

s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtgwiemubg.html

[U114] JS：JSON 深比较
来源：http://dali.chenjidiqi.icu/Article/details/gtimhkkztl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtojvktwlh.html

[U115] JS：生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gttjghdmgr.html

crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtymgpqhcp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xinyue.icu/Article/details/gtlugvbgef.html

/** @param {string} name */ function f(name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgwyobigi.html

[U117] JS：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gtcfgpdeiz.html

npm i -D vitest;  npx vitest
来源：http://dali.wangdashe.top/Article/details/gtxgqptmoi.html

[U118] JS：开发服务器
来源：http://dali.zdqjudy.top/Article/details/gtbzlnffgx.html

npm i -D vite;  npx vite
来源：http://dali.nanxinkj.top/Article/details/gtbsqvvwoc.html

[U119] JS：生产构建
来源：http://dali.yuxming.cn/Article/details/gtcyrnkfys.html

npx vite build
来源：http://dali.aizwys.cn/Article/details/gtsyfskkcg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jlsjyb.cn/Article/details/gtdbmhspgy.html

import.meta.env.VITE_API_URL
来源：http://dali.feifeiyinyue.top/Article/details/gtmhykcwzp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtjflmzwoa.html

统计汇总
来源：http://dali.pycfn.com/Article/details/gtzmbdqndw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthcoxaxdh.html

按语言统计（条）：
来源：http://dali.gzhubu.top/Article/details/gttzrlbnnt.html

Python ......... 252
来源：http://dali.yueranfly.top/Article/details/gtmwgodadb.html

PHP ............ 252
来源：http://dali.yueranfly.top/Article/details/gtprwlynic.html

JavaScript ..... 252
来源：http://dali.yj20258.top/Article/details/gtilexffpf.html

TypeScript ..... 212
来源：http://dali.wangshuangyany.cn/Article/details/gtepvxmbzl.html

Java ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtxuxzkzxm.html

Go ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gtfmiftnri.html

Ruby ........... 212
来源：http://dali.redwolf501.top/Article/details/gtkjikkyli.html

C# ............. 212
来源：http://dali.gotoacloud.top/Article/details/gtxixxmhhv.html

C .............. 30
来源：http://dali.hywenlv.cn/Article/details/gtghzydauw.html

C++ ............ 30
来源：http://dali.pycfn.com/Article/details/gtjedotuqc.html

SQL ............ 90
来源：http://dali.yanxiufei.cn/Article/details/gtdbaluwkc.html

Bash ........... 80
来源：http://dali.yuanzhike.top/Article/details/gtyvmyuhoo.html

Kotlin ......... 15
来源：http://dali.guannengcc.top/Article/details/gtguskklln.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gtkhjwjuoe.html

Lua ............ 10
来源：http://dali.iojbl.cn/Article/details/gtriwqubcn.html

Perl ........... 10
来源：http://dali.jqgufenzy.top/Article/details/gtnxykpgun.html

Scala .......... 10
来源：http://dali.nwbrower.top/Article/details/gtkucfmgpf.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtnesrxqxi.html

合计 ........... 2106 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsygkuoz.html

按章节统计：
来源：http://dali.yvedp.cn/Article/details/gtndreopve.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenlongwang.top/Article/details/gtciyepuzz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtobclcaly.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gtlhrprgsn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenjidiqi.icu/Article/details/gtrxjrctqh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dashuyun.cn/Article/details/gtibuhbjtn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.svipenyu.cn/Article/details/gtivudhrfq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtvxspiyde.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtenxnbvcb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtdjznhiau.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.vqdsnc.cn/Article/details/gtmhciqozk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtfyzjukxk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtgzwmbtpj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugmelrbq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gtxhlqxywl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cdnleiting.top/Article/details/gtmizaewcw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtfjmtugye.html

Q SQL 专题                              90
来源：http://dali.feifeiyinyue.top/Article/details/gtpqyklldl.html

R Bash 专题                             80
来源：http://dali.gzhubu.top/Article/details/gtdjmweztg.html

S C / C++ 专题                          60
来源：http://dali.zdqjudy.top/Article/details/gtebjalerw.html

T 其他语言补充                          60
来源：http://dali.cheryme.top/Article/details/gtvicbcxtb.html

U 高频实用片段                         120
来源：http://dali.aibaodan.cn/Article/details/gttssrlcdc.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtgvopmhmt.html

合计                                  2106 条
来源：http://dali.ydzc1.top/Article/details/gtwhgafdtd.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtlbecbzvk.html

使用提醒
来源：http://dali.xuetiantiany.cn/Article/details/gtoytqanfz.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtddwhzbzp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.aibaodan.cn/Article/details/gtvrkbmydz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guowangkeji.top/Article/details/gtjsqqbvvn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.guowangkeji.top/Article/details/gtuvanfclk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztcqruzh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.smart0.xyz/Article/details/gtpiqfolhc.html

—— 文件结束 ——
来源：http://dali.bjfxy.top/Article/details/gtfeugclwv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtikqmmzeo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gzhubu.top/Article/details/gttmgzlgmi.html

Common Programming Examples Cheat Book
来源：http://dali.jqgufenzy.top/Article/details/gthgkplwgt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfqetjhyr.html

【收录内容】
来源：http://dali.xylfe.cn/Article/details/gtsnqstocd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yj20258.top/Article/details/gtsizmrxef.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgufenzy.top/Article/details/gtrhggjwqv.html

SQL · Bash · C · C++
来源：http://dali.dianchejie.cn/Article/details/gtplcvgpxf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ybcxt.top/Article/details/gtvawrnlfc.html

【使用说明】
来源：http://dali.cucudq.cn/Article/details/gtmqhtbqut.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawjtgghm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jiagoushi.top/Article/details/gtgwhlqhxu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sweek.top/Article/details/gtlxahlbgv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yanxiufei.cn/Article/details/gtnmcnnint.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hfpthk.cn/Article/details/gtzoagjphr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tian-w.cn/Article/details/gtllcbfjvb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnxiangtu.top/Article/details/gtwqoincns.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.aibaodan.cn/Article/details/gtqsrcvzps.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangdashe.top/Article/details/gtebjvoznh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.quarkkingdee.top/Article/details/gtrddjyanc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.meibo888.top/Article/details/gtwylzpqhn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jiagoushi.top/Article/details/gteqqxqjzj.html

【文件统计】
来源：http://dali.hongshengwenyu.top/Article/details/gtkjpxoozd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.dianchejie.cn/Article/details/gtstoktkqw.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtxmswmaig.html

目  录
来源：http://dali.xuanzx.com/Article/details/gtkzcoviwy.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtjwhmwgrt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gthsnoemqf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gtyvaugxvr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenlongwang.top/Article/details/gthfqzgqqc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cdnleiting.top/Article/details/gtgpmrcebr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenjidiqi.icu/Article/details/gteypwblec.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cashguo.top/Article/details/gtjhngvine.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.daxiang520.top/Article/details/gtrgoexfbc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtaimgxykl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtumnvhekb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgfzy.top/Article/details/gtiggufssm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtksliktua.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtameadxcz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtwprjrmxx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.wangdashe.top/Article/details/gtrdkbuptw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.aibaodan.cn/Article/details/gtllplfqmx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gtroufdvcu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtqrdsbwcz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shangyingyoupin.top/Article/details/gthwoqaoyv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cucudq.cn/Article/details/gtaorqzahu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtzifigtoo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtjnnbkdmm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxfdrnzww.html

A. 基础语法与类型
来源：http://dali.shzxlz.cn/Article/details/gtloisuzup.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwadabsvx.html

[A01] Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztnmbhlk.html

Py:   print("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gtwrheoonn.html

PHP:  echo "Hello, World!";
来源：http://dali.ydzc1.top/Article/details/gtwswhpmuk.html

JS:   console.log("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gtgcywkoco.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuanzx.com/Article/details/gtvlfeqvtd.html

Java: System.out.println("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtcatnkjsr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gttcyvrtqb.html

Ruby: puts "Hello, World!"
来源：http://dali.hammf.cn/Article/details/gtvxniedkb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gthfdlakih.html

[A02] 变量声明与赋值
来源：http://dali.yuanzhike.top/Article/details/gtbfrceigf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hongshengwenyu.top/Article/details/gtpktbpspi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.birdmap.top/Article/details/gtvmgoomhk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtyvcezjxs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.fzhhl.top/Article/details/gtjqlrixxk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtrezwsbpk.html

Go:   name := "Alex"; age := 20
来源：http://dali.dianchejie.cn/Article/details/gthceolicq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.fzhhl.top/Article/details/gtojpmzrmn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfddzsuky.html

[A03] 常量定义
来源：http://dali.cheryme.top/Article/details/gtmwisvcqu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.0kj1m.cn/Article/details/gtilgcllvb.html

PHP:  const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtmcktajsv.html

JS:   const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtxmkjspjq.html

TS:   const PI: number = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtmiquvelx.html

Java: static final double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtyvssazxu.html

Go:   const PI = 3.14159
来源：http://dali.c1oappe.top/Article/details/gtzltcbajb.html

Ruby: PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gtjsbncaft.html

C#:   const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtvdceseli.html

[A04] 判断变量类型
来源：http://dali.tianlin.xyz/Article/details/gtvzthtpzm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhoulong.xyz/Article/details/gtzxaeqray.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.wangshuangyany.cn/Article/details/gtdabyeksj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrnfncve.html

TS:   typeof x; x instanceof Date
来源：http://dali.fzhhl.top/Article/details/gtpbtmzgan.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.kuanghao11.cn/Article/details/gtqpjhsped.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gaohongyu789.top/Article/details/gtpkrindvx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.redwolf501.top/Article/details/gtiahiursj.html

C#:   x.GetType().Name; x is int
来源：http://dali.sxryk.cn/Article/details/gtanlmuael.html

[A05] 整数除法与取模
来源：http://dali.yj20258.top/Article/details/gtfppegxrx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dashuyun.cn/Article/details/gttdkbuzsg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtgoeugggm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gtjuezgmzv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtsksvbvdz.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtxdijwqts.html

Go:   7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtlysdkbkn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtlmtowroy.html

C#:   7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtkklxpgrn.html

[A06] 字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtqgjkvwun.html

Py:   int("42"); float("3.14")
来源：http://dali.jqgfzy.top/Article/details/gtxvmqkhrk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.quarkkingdee.top/Article/details/gtdxfaxnch.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ybcxt.top/Article/details/gtptgmwnml.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yongpay.top/Article/details/gthrrhaqio.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ivvv.top/Article/details/gtcfhvobga.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hywenlv.cn/Article/details/gtuedvtajw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.wangdashe.top/Article/details/gttbodxbrv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yangfankeji.com/Article/details/gtmiifsjgp.html

[A07] 数字转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtarvmxbhi.html

Py:   str(42)
来源：http://dali.sufxvd.cn/Article/details/gttdoxuann.html

PHP:  (string) 42; strval(42)
来源：http://dali.meibo888.top/Article/details/gtgebuvixk.html

JS:   String(42); (42).toString()
来源：http://dali.quarkkingdee.top/Article/details/gtkdpwjcsp.html

TS:   String(42)
来源：http://dali.nwbrower.top/Article/details/gtdgkezrkl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gzhubu.top/Article/details/gtzlnrhqey.html

Go:   strconv.Itoa(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtaateulad.html

Ruby: 42.to_s
来源：http://dali.nanxinkj.top/Article/details/gtdnmbpjgo.html

C#:   42.ToString()
来源：http://dali.yj20258888.top/Article/details/gtwkbijjiy.html

[A08] 取整与四舍五入
来源：http://dali.wangdashe.top/Article/details/gtbghvmuli.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtgolekuvr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.wangdashe.top/Article/details/gtimmubxeq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gtelmtawzn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sxryk.cn/Article/details/gtqvoifthy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtebjahxdo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtepnkkvcu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.havefunace.top/Article/details/gtcfvxqahq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gtcesepjqd.html

[A09] 绝对值与最大最小值
来源：http://dali.yonumen.top/Article/details/gtobnynogw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtlntvlkbl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtcfbvqsak.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtcihxfsbp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.meibo888.top/Article/details/gtgxggzkws.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtlxscojwt.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yuanzhike.top/Article/details/gtbkjwlaao.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hammf.cn/Article/details/gtsgxhfnwa.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtimocotli.html

[A10] 生成随机数
来源：http://dali.hfpthk.cn/Article/details/gtmyamsrey.html

Py:   import random; random.randint(1, 100)
来源：http://dali.havefunace.top/Article/details/gtquqkzrre.html

PHP:  random_int(1, 100);
来源：http://dali.chenlongwang.top/Article/details/gtwrbtirna.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hammf.cn/Article/details/gtejyrytjp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jqgfzy.top/Article/details/gtsumzyqvs.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sxryk.cn/Article/details/gtqcitjftf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.aibaodan.cn/Article/details/gtzngjnqnv.html

Ruby: rand(1..100)
来源：http://dali.andypj.xyz/Article/details/gtnoxskwrs.html

C#:   new Random().Next(1, 101)
来源：http://dali.chenzaomai.com/Article/details/gtnxhtpjqd.html

[A11] 条件表达式（三元）
来源：http://dali.jiagoushi.top/Article/details/gtyzhzabyq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hammf.cn/Article/details/gtvigpixpg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gtrwyycxjg.html


<!-- 参考信息 -->