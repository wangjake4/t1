代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgcbpbcj.html

throw new RuntimeException("失败", 500);
来源：http://dali.jiagoushi.top/Article/details/gttavsdtjt.html

[U72] PHP：写错误日志
来源：http://dali.fzhhl.top/Article/details/gtrmdwvoks.html

error_log("失败: " . $e->getMessage());
来源：http://dali.meibo888.top/Article/details/gtmwrwivqp.html

[U73] PHP：读取 ini 配置
来源：http://dali.fzhhl.top/Article/details/gtybusigwy.html

parse_ini_file("config.ini", true)
来源：http://dali.ydzc1.top/Article/details/gtxfhgqsva.html

[U74] PHP：读取环境变量
来源：http://dali.andypj.xyz/Article/details/gtfokxnjiy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.mhx1999.top/Article/details/gtrvsghkpb.html

[U75] PHP：依赖注入
来源：http://dali.wangdashe.top/Article/details/gtbtsjppoh.html

composer require psr/container
来源：http://dali.shangyingyoupin.top/Article/details/gtvcbirlps.html

[U76] PHP：简单路由
来源：http://dali.gogol.net.cn/Article/details/gtaxzhyzxe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.havefunace.top/Article/details/gtxjllmabb.html

[U77] PHP：模板渲染
来源：http://dali.hammf.cn/Article/details/gtbanwekic.html

composer require twig/twig
来源：http://dali.jinghuilouyu.cn/Article/details/gtnalnpsgj.html

[U78] PHP：单元测试
来源：http://dali.meibo888.top/Article/details/gtxtayagdx.html

composer require --dev phpunit/phpunit
来源：http://dali.meibo888.top/Article/details/gtzjntenqo.html

[U79] PHP：静态分析
来源：http://dali.jyoumei.cn/Article/details/gtkokcmjzr.html

composer require --dev phpstan/phpstan
来源：http://dali.redwolf501.top/Article/details/gtampyvqoy.html

[U80] PHP：代码规范修复
来源：http://dali.zdqjudy.top/Article/details/gtidytkjrv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gtdhfzvsdb.html

[U81] JS：初始化项目
来源：http://dali.birdmap.top/Article/details/gtsikgamhh.html

npm init -y;  npm i express
来源：http://dali.dianchejie.cn/Article/details/gtohzftiki.html

[U82] JS：package.json 脚本
来源：http://dali.0kj1m.cn/Article/details/gtebkfntlh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.9152youxi.cn/Article/details/gtwkouzicg.html

[U83] JS：ES Module 导入导出
来源：http://dali.hammf.cn/Article/details/gtakwafzga.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tanke756.top/Article/details/gthertzviu.html

[U84] JS：CommonJS 写法
来源：http://dali.hammf.cn/Article/details/gtmcscjtsn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nanxuanxn.top/Article/details/gtjubjgeub.html

[U85] JS：可选链
来源：http://dali.hfpthk.cn/Article/details/gtbuvkzblz.html

a?.b?.c
来源：http://dali.tian-w.cn/Article/details/gtxeybkjxb.html

[U86] JS：空值合并
来源：http://dali.gzhubu.top/Article/details/gtxalajyfo.html

a ?? b
来源：http://dali.birdmap.top/Article/details/gtlmccaegm.html

[U87] JS：解构默认值
来源：http://dali.yj20258888.top/Article/details/gtznoldjkw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xuanzx.com/Article/details/gtkscpinmr.html

[U88] JS：对象展开合并
来源：http://dali.yongpay.top/Article/details/gtpwmwdfjo.html

{ ...a, ...b }
来源：http://dali.cheryme.top/Article/details/gttpnxemky.html

[U89] JS：数组去重
来源：http://dali.xuanzx.com/Article/details/gtomhtccss.html

[...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtevcefshr.html

[U90] JS：数字数组排序
来源：http://dali.zhongyouzk.top/Article/details/gtnlptmhvo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtgsgetayc.html

[U91] JS：对象键值遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtjywkyrlf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj202588.top/Article/details/gtbcfjbpiz.html

[U92] JS：深拷贝
来源：http://dali.havefunace.top/Article/details/gtrvivyjsg.html

structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtmzuoflam.html

[U93] JS：模板字符串
来源：http://dali.hysaishi.cn/Article/details/gtuvblcoug.html

`共 ${n} 条`
来源：http://dali.havefunace.top/Article/details/gtljtgcmgv.html

[U94] JS：箭头函数
来源：http://dali.nwbrower.top/Article/details/gttokcnvpz.html

const double = x => x * 2;
来源：http://dali.gogol.net.cn/Article/details/gthctfggyp.html

[U95] JS：Promise 包装
来源：http://dali.hfpthk.cn/Article/details/gtvqsxkyak.html

new Promise((resolve, reject) => {})
来源：http://dali.cucudq.cn/Article/details/gtgjepqzlv.html

[U96] JS：async/await 与异常
来源：http://dali.xuetiantiany.cn/Article/details/gtqmrowtuh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtqunqlmng.html

[U97] JS：并发请求
来源：http://dali.smart0.xyz/Article/details/gtrvvgtxmc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtadomtxgv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtyuvgusbe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zycfv.cn/Article/details/gtmgtpecqn.html

[U99] JS：事件监听
来源：http://dali.dianchejie.cn/Article/details/gtsgwfrtib.html

el.addEventListener("click", e => {})
来源：http://dali.jqgfzy.top/Article/details/gtvchwnise.html

[U100] JS：DOM 查询
来源：http://dali.yanxiufei.cn/Article/details/gtrgaxxyxj.html

document.querySelector(".item")
来源：http://dali.zhixingplan.top/Article/details/gtycwrglwm.html

[U101] JS：classList 操作
来源：http://dali.svipenyu.cn/Article/details/gtvayqdwoq.html

el.classList.toggle("active")
来源：http://dali.xinyue.icu/Article/details/gttkxxnikq.html

[U102] JS：本地存储
来源：http://dali.hnxiangtu.top/Article/details/gtdfaxtcio.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuetiantiany.cn/Article/details/gtkeaqmrof.html

[U103] JS：定时器
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvybcpdb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnqzz.top/Article/details/gtinlzhjsl.html

[U104] JS：防抖
来源：http://dali.vqdsnc.cn/Article/details/gtxdllbkfy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtctgzroip.html

[U105] JS：节流
来源：http://dali.aizwys.cn/Article/details/gtekrqfrzi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gtuehlnbur.html

[U106] JS：日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtgbrqhzwb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhengqikj.top/Article/details/gtyhiexfel.html

[U107] JS：数字千分位
来源：http://dali.sxryk.cn/Article/details/gtwovmaajx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtvzgenidx.html

[U108] JS：随机整数
来源：http://dali.dianchejie.cn/Article/details/gtukmsccop.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gthljspnla.html

[U109] JS：数组分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffpwhmfa.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gtxzriduit.html

[U110] JS：数组分块
来源：http://dali.xylfe.cn/Article/details/gtmnvzhvez.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hysaishi.cn/Article/details/gtsuyooubm.html

[U111] JS：对象转 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrwjyzoa.html

new Map(Object.entries(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gtiuyrdjhn.html

[U112] JS：字符串补位
来源：http://dali.chenlongwang.top/Article/details/gtsnnlwtdu.html

"7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtnvfuewpt.html

[U113] JS：正则替换全部
来源：http://dali.xziqi.cn/Article/details/gtkldsmpvu.html

s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtvlhitogi.html

[U114] JS：JSON 深比较
来源：http://dali.sysykeji.top/Article/details/gtcjqczxkk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtnbcxxnlw.html

[U115] JS：生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtjwrzvezd.html

crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtexpfsxvu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yanxiufei.cn/Article/details/gtpkvtucfj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gotoacloud.top/Article/details/gtdsltmbdq.html

[U117] JS：单元测试
来源：http://dali.xinyue.icu/Article/details/gtbbaqsaoy.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigufen.top/Article/details/gtqtkncwpi.html

[U118] JS：开发服务器
来源：http://dali.daria6918.cn/Article/details/gthjlnwplh.html

npm i -D vite;  npx vite
来源：http://dali.yanxiufei.cn/Article/details/gtckquitxx.html

[U119] JS：生产构建
来源：http://dali.gogol.net.cn/Article/details/gtsbfjqiqy.html

npx vite build
来源：http://dali.shuidangran.top/Article/details/gtfdpwebjy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daria6918.cn/Article/details/gtjbzukdhd.html

import.meta.env.VITE_API_URL
来源：http://dali.chenzaomai.com/Article/details/gteqznwerf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtrwkxsejw.html

统计汇总
来源：http://dali.yanxiufei.cn/Article/details/gtkbkpybip.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqkerzsfj.html

按语言统计（条）：
来源：http://dali.cqqwz.cn/Article/details/gtcekgyhoo.html

Python ......... 252
来源：http://dali.hammf.cn/Article/details/gtdfmotzzf.html

PHP ............ 252
来源：http://dali.cdnleiting.top/Article/details/gtzyjamepx.html

JavaScript ..... 252
来源：http://dali.zhoulong.xyz/Article/details/gtgmssyuyg.html

TypeScript ..... 212
来源：http://dali.ppjwa.cn/Article/details/gtgyxrxatv.html

Java ........... 212
来源：http://dali.sysykeji.top/Article/details/gtntfufjhy.html

Go ............. 212
来源：http://dali.nwbrower.top/Article/details/gtgphkcxnj.html

Ruby ........... 212
来源：http://dali.ybcxt.top/Article/details/gtgvlrvczl.html

C# ............. 212
来源：http://dali.tanke756.top/Article/details/gtwtvepipf.html

C .............. 30
来源：http://dali.daxiang520.top/Article/details/gtrhnhfihg.html

C++ ............ 30
来源：http://dali.chenzaomai.com/Article/details/gtydfdfxbs.html

SQL ............ 90
来源：http://dali.cashguo.top/Article/details/gtibelfjsh.html

Bash ........... 80
来源：http://dali.hfpthk.cn/Article/details/gtrpyajnry.html

Kotlin ......... 15
来源：http://dali.c1oappe.top/Article/details/gtfjdfudyz.html

Swift .......... 15
来源：http://dali.jqgfzy.top/Article/details/gttqryxyfl.html

Lua ............ 10
来源：http://dali.jqgfzy.top/Article/details/gtegujugzf.html

Perl ........... 10
来源：http://dali.redwolf501.top/Article/details/gtzxgzvajp.html

Scala .......... 10
来源：http://dali.nanxinkj.top/Article/details/gtlwbrjvfc.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtvtkumzdd.html

合计 ........... 2106 条
来源：http://dali.fengsongda.top/Article/details/gtggoseypc.html

按章节统计：
来源：http://dali.zhengqikj.top/Article/details/gtludlvtwo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gtasjneuod.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gtkdkmizvf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzvxnwuj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gtauxewkwu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cdnleiting.top/Article/details/gtgrgxhqoe.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gtdhkokufk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gthrwtqujp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.haohaochexian.top/Article/details/gtwsicrsfx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtvgmllvqq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.smart0.xyz/Article/details/gtnevbhlff.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtudkddmur.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrzwwryv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gtgnwstlld.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gtnnjibikm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhixingplan.top/Article/details/gtclrdfrhj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtzmyehace.html

Q SQL 专题                              90
来源：http://dali.sufxvd.cn/Article/details/gtkbgnbmhe.html

R Bash 专题                             80
来源：http://dali.cheryme.top/Article/details/gtoempfkwg.html

S C / C++ 专题                          60
来源：http://dali.yj20258.top/Article/details/gtrozmhwpj.html

T 其他语言补充                          60
来源：http://dali.yuxming.cn/Article/details/gtbyoqwbru.html

U 高频实用片段                         120
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbwbfjir.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtitysnoqf.html

合计                                  2106 条
来源：http://dali.hongshengwenyu.top/Article/details/gtvyzwviip.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtfzocuyxf.html

使用提醒
来源：http://dali.ybcxt.top/Article/details/gtjnyblgsu.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtsmnqdkar.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmaqwbiby.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.wangshuangyany.cn/Article/details/gtkloumwpu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yueranfly.top/Article/details/gtlzrazvfp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.mhx1999.top/Article/details/gtsqnzbbso.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxinkj.top/Article/details/gteicafswj.html

—— 文件结束 ——
来源：http://dali.shanyushiyangtech.top/Article/details/gtirlpyvni.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdgjhlddj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.vqdsnc.cn/Article/details/gtvgddjbkb.html

Common Programming Examples Cheat Book
来源：http://dali.yueranfly.top/Article/details/gtuwptkbvd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbpayobda.html

【收录内容】
来源：http://dali.mhx1999.top/Article/details/gtptofvfpe.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jiagoushi.top/Article/details/gttesbgupz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xziqi.cn/Article/details/gtblblitdz.html

SQL · Bash · C · C++
来源：http://dali.dianchejie.cn/Article/details/gtsrqgesno.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfzythac.html

【使用说明】
来源：http://dali.sxryk.cn/Article/details/gtxuxphrvv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gtjodeuzjm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yueranfly.top/Article/details/gtqbwlipza.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.snrcjt.cn/Article/details/gttouitmky.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yongpay.top/Article/details/gtwjcysqgf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.kuanghao11.cn/Article/details/gtilibstpq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhongyouzk.top/Article/details/gtrudqisdm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zdqjudy.top/Article/details/gtzeelulsl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuanzx.com/Article/details/gtvvwtflds.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hammf.cn/Article/details/gtfegdklvl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hywenlv.cn/Article/details/gtwuawiruz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xinyue.icu/Article/details/gtkglcdefl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgfzy.top/Article/details/gtdewvoxgq.html

【文件统计】
来源：http://dali.tian-w.cn/Article/details/gtgftqyiim.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.kuanghao11.cn/Article/details/gtjwfwhwjl.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtlfzwduyr.html

目  录
来源：http://dali.zhongyouzk.top/Article/details/gtwcsbwgil.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtuqtlkrhi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gtcjqcgefa.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gthvqylmby.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gtnblvgptl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gtgovjpotd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtjetjzkqi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gtjxgixoqt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gtzmexkldm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gtvxmlcuhs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtgwogdewc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gtmklkblwf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtgpbfzrcz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtazjinhte.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gteswaqmct.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqddpbas.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.guannengcc.top/Article/details/gtbsakgmwd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtszkbitsv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinqigfzy.top/Article/details/gtlvbbhyjl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ppjwa.cn/Article/details/gtmwtdqwhg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yonumen.top/Article/details/gtiqzqfikl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtjisszakp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gtnukhqpsv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtpgwscgij.html

A. 基础语法与类型
来源：http://dali.cashguo.top/Article/details/gthtzwlsaq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyweiefo.html

[A01] Hello World
来源：http://dali.jinqigufen.top/Article/details/gtadoagtyi.html

Py:   print("Hello, World!")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrcbuwlu.html

PHP:  echo "Hello, World!";
来源：http://dali.shangyingyoupin.top/Article/details/gtofpucrhi.html

JS:   console.log("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtebmhurfr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xziqi.cn/Article/details/gthgrrafuw.html

Java: System.out.println("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gtxueondit.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gzhubu.top/Article/details/gtoefyfhsh.html

Ruby: puts "Hello, World!"
来源：http://dali.haohaochexian.top/Article/details/gtvowacaah.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gtslfzszkx.html

[A02] 变量声明与赋值
来源：http://dali.xuetiantiany.cn/Article/details/gtdchqobfo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqmpjntp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sysykeji.top/Article/details/gtyuopfkto.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cqqwz.cn/Article/details/gtrofubiah.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtvqueeopb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gtzipydkre.html

Go:   name := "Alex"; age := 20
来源：http://dali.sweek.top/Article/details/gtgtinkmhy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhiwuduotai.top/Article/details/gthqjtdlhq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gzhubu.top/Article/details/gtezimqlsg.html

[A03] 常量定义
来源：http://dali.yuanzhike.top/Article/details/gtupstcozb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xinyue.icu/Article/details/gtlsnizqgl.html

PHP:  const PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtzkikpmua.html

JS:   const PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtvymmuani.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmetwhlut.html

Java: static final double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtwuojeoob.html

Go:   const PI = 3.14159
来源：http://dali.cdnleiting.top/Article/details/gtpzcffwjs.html

Ruby: PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gtnrvqcict.html

C#:   const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtppyvdkgy.html

[A04] 判断变量类型
来源：http://dali.redwolf501.top/Article/details/gtgviyelhi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cdnleiting.top/Article/details/gtlbawqulr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxuanxn.top/Article/details/gtfouzgayc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.havefunace.top/Article/details/gtacjwhheu.html

TS:   typeof x; x instanceof Date
来源：http://dali.haohaochexian.top/Article/details/gttbgxenea.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.0kj1m.cn/Article/details/gtzboaxiad.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sysykeji.top/Article/details/gtncqpkzbg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuwngjil.html

C#:   x.GetType().Name; x is int
来源：http://dali.shuidangran.top/Article/details/gttegoyhtg.html

[A05] 整数除法与取模
来源：http://dali.yonumen.top/Article/details/gtyyakjokb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.guannengcc.top/Article/details/gtswyiakyq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.pycfn.com/Article/details/gtexzckooa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtawvpfspk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtpurdsdqo.html

Java: 7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtnkgwgbyo.html

Go:   7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtirbryjpp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gtzocnjvck.html

C#:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtrxcsumnq.html

[A06] 字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gtzjhtamqm.html

Py:   int("42"); float("3.14")
来源：http://dali.xziqi.cn/Article/details/gtxuoyojqz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ybcxt.top/Article/details/gttqslupzv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daria6918.cn/Article/details/gtoohisrrc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.andypj.xyz/Article/details/gtlvazaotd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sufxvd.cn/Article/details/gtihgfzhhv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ydzc1.top/Article/details/gtoimtdkbc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jqgufenzy.top/Article/details/gtvohzbxbt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jyoumei.cn/Article/details/gtoqmbgdmy.html

[A07] 数字转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtjdldixpi.html

Py:   str(42)
来源：http://dali.yanxiufei.cn/Article/details/gtqfzukocg.html

PHP:  (string) 42; strval(42)
来源：http://dali.birdmap.top/Article/details/gtsnguwqug.html

JS:   String(42); (42).toString()
来源：http://dali.gogol.net.cn/Article/details/gtufqdowma.html

TS:   String(42)
来源：http://dali.gzhubu.top/Article/details/gtigmuwtsd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jlsjyb.cn/Article/details/gtdctoeqwi.html

Go:   strconv.Itoa(42)
来源：http://dali.yueranfly.top/Article/details/gtjcqbwcky.html

Ruby: 42.to_s
来源：http://dali.daria6918.cn/Article/details/gtnntnkqxy.html

C#:   42.ToString()
来源：http://dali.0kj1m.cn/Article/details/gtcmouekdo.html

[A08] 取整与四舍五入
来源：http://dali.shangyingyoupin.top/Article/details/gtaujdaabi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gthqflsyrs.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhixingplan.top/Article/details/gtbtuubxis.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gtalyqtchp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.andypj.xyz/Article/details/gtilznufks.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yj202588.top/Article/details/gtpmswlnfg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gtwheidjiz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xinyue.icu/Article/details/gtoghxrmrq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gthemtqgua.html

[A09] 绝对值与最大最小值
来源：http://dali.ehwqpu.com/Article/details/gtpsxcvwyr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtzfmibcjy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtzxbbglhp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtypgowgff.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtwwrqepnr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtdelojaea.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gogol.net.cn/Article/details/gtqlwkvmfp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jianghu66.top/Article/details/gtwktmoixu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yongpay.top/Article/details/gtvstutfyl.html

[A10] 生成随机数
来源：http://dali.havefunace.top/Article/details/gtfnlfvana.html

Py:   import random; random.randint(1, 100)
来源：http://dali.nanxuanxn.top/Article/details/gtykwspuxx.html

PHP:  random_int(1, 100);
来源：http://dali.pengpengdd.cyou/Article/details/gtzqzjkwtw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.vqdsnc.cn/Article/details/gtunyxknfp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ppjwa.cn/Article/details/gtwqywmhlp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.shzxlz.cn/Article/details/gtndkxuqzz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sxryk.cn/Article/details/gtfvamhtqx.html

Ruby: rand(1..100)
来源：http://dali.redwolf501.top/Article/details/gtrsfdexlr.html

C#:   new Random().Next(1, 101)
来源：http://dali.xziqi.cn/Article/details/gtrwzwtrac.html

[A11] 条件表达式（三元）
来源：http://dali.shanyushiyangtech.top/Article/details/gtixqqbfga.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.sweek.top/Article/details/gtbarbnipp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtccmoqqzd.html


<!-- 参考信息 -->