代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.hfpthk.cn/Article/details/gtwbprrlal.html

parse_ini_file("config.ini", true)
来源：http://dali.fengsongda.top/Article/details/gtyjqtvtfp.html

[U74] PHP：读取环境变量
来源：http://dali.xziqi.cn/Article/details/gtfyzufhqf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gogol.net.cn/Article/details/gtggcayrrj.html

[U75] PHP：依赖注入
来源：http://dali.yueranfly.top/Article/details/gtiafjgnke.html

composer require psr/container
来源：http://dali.zhiwuduotai.top/Article/details/gtyqgguphi.html

[U76] PHP：简单路由
来源：http://dali.jlsjyb.cn/Article/details/gtvlidrzka.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guannengcc.top/Article/details/gtxnnxqgmy.html

[U77] PHP：模板渲染
来源：http://dali.svipenyu.cn/Article/details/gtgdhrjwvt.html

composer require twig/twig
来源：http://dali.redwolf501.top/Article/details/gtyxoleqsu.html

[U78] PHP：单元测试
来源：http://dali.zdqjudy.top/Article/details/gtcanhztgc.html

composer require --dev phpunit/phpunit
来源：http://dali.vqdsnc.cn/Article/details/gtllzntldu.html

[U79] PHP：静态分析
来源：http://dali.xuetiantiany.cn/Article/details/gtoojytaga.html

composer require --dev phpstan/phpstan
来源：http://dali.xziqi.cn/Article/details/gtelxidzrf.html

[U80] PHP：代码规范修复
来源：http://dali.ydzc1.top/Article/details/gtirjrfooh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dashuyun.cn/Article/details/gtebyckjmy.html

[U81] JS：初始化项目
来源：http://dali.jianghu66.top/Article/details/gtpyrrdljn.html

npm init -y;  npm i express
来源：http://dali.nanxuanxn.top/Article/details/gtkljqjbfm.html

[U82] JS：package.json 脚本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzovorvcz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yueranfly.top/Article/details/gtmzxyacda.html

[U83] JS：ES Module 导入导出
来源：http://dali.jyoumei.cn/Article/details/gtbbtktaqo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gtfwdfanpf.html

[U84] JS：CommonJS 写法
来源：http://dali.jianghu66.top/Article/details/gtwtjtncvo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tian-w.cn/Article/details/gtltfiesdy.html

[U85] JS：可选链
来源：http://dali.redwolf501.top/Article/details/gtjjqyqzns.html

a?.b?.c
来源：http://dali.c1oappe.top/Article/details/gtsfjbkqqh.html

[U86] JS：空值合并
来源：http://dali.nanxuanxn.top/Article/details/gtzobymgmy.html

a ?? b
来源：http://dali.sxryk.cn/Article/details/gtdvdtxovp.html

[U87] JS：解构默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtwpionwhj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sufxvd.cn/Article/details/gtxyfdudxo.html

[U88] JS：对象展开合并
来源：http://dali.quarkkingdee.top/Article/details/gtzeittfyj.html

{ ...a, ...b }
来源：http://dali.tianlin.xyz/Article/details/gtclzbfnzi.html

[U89] JS：数组去重
来源：http://dali.jlsjyb.cn/Article/details/gtygrrzqrb.html

[...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtnfmkfryw.html

[U90] JS：数字数组排序
来源：http://dali.hnqzz.top/Article/details/gtckthceej.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtdnrvkoks.html

[U91] JS：对象键值遍历
来源：http://dali.yuxming.cn/Article/details/gttxixuqqw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzxmxsxy.html

[U92] JS：深拷贝
来源：http://dali.xuanzx.com/Article/details/gtqqnsypvr.html

structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtznoujzwg.html

[U93] JS：模板字符串
来源：http://dali.tian-w.cn/Article/details/gtzzmjmegu.html

`共 ${n} 条`
来源：http://dali.dianchejie.cn/Article/details/gtuybvhvrx.html

[U94] JS：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gtdvvyctpz.html

const double = x => x * 2;
来源：http://dali.cheryme.top/Article/details/gtldnlpexz.html

[U95] JS：Promise 包装
来源：http://dali.chenzaomai.com/Article/details/gtsbdfuwke.html

new Promise((resolve, reject) => {})
来源：http://dali.snrcjt.cn/Article/details/gtcewnurgm.html

[U96] JS：async/await 与异常
来源：http://dali.316326.xyz/Article/details/gtnuknsllr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtmcndkbof.html

[U97] JS：并发请求
来源：http://dali.xziqi.cn/Article/details/gtfqkpubvy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtndamhgzy.html

[U98] JS：fetch 带 JSON
来源：http://dali.yongpay.top/Article/details/gtsykxcawe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yanxiufei.cn/Article/details/gtuqsxolfi.html

[U99] JS：事件监听
来源：http://dali.jyoumei.cn/Article/details/gtjfnfklsf.html

el.addEventListener("click", e => {})
来源：http://dali.daria6918.cn/Article/details/gtyugbvgha.html

[U100] JS：DOM 查询
来源：http://dali.svipenyu.cn/Article/details/gtnuhvxaii.html

document.querySelector(".item")
来源：http://dali.snrcjt.cn/Article/details/gtnfndzsaf.html

[U101] JS：classList 操作
来源：http://dali.jinqigufen.top/Article/details/gtbzbawpcj.html

el.classList.toggle("active")
来源：http://dali.wangdashe.top/Article/details/gthsyaggbt.html

[U102] JS：本地存储
来源：http://dali.0kj1m.cn/Article/details/gtluckujtg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgfzy.top/Article/details/gtagrixued.html

[U103] JS：定时器
来源：http://dali.sufxvd.cn/Article/details/gtkrqroevf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ivvv.top/Article/details/gtxdpiyvux.html

[U104] JS：防抖
来源：http://dali.birdmap.top/Article/details/gtehjnbrim.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtgddpvema.html

[U105] JS：节流
来源：http://dali.jyoumei.cn/Article/details/gtkfqzmmoa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ybcxt.top/Article/details/gtqfcxwkek.html

[U106] JS：日期格式化
来源：http://dali.zycfv.cn/Article/details/gtynajvuxt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.feifeiyinyue.top/Article/details/gtpejjuxce.html

[U107] JS：数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gtsyovbzzp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hammf.cn/Article/details/gtmrczudvh.html

[U108] JS：随机整数
来源：http://dali.dianchejie.cn/Article/details/gtcvmijlbf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.bjfxy.top/Article/details/gtliyiwkol.html

[U109] JS：数组分组
来源：http://dali.9152youxi.cn/Article/details/gtxogtyaqq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gtrgmmkyxr.html

[U110] JS：数组分块
来源：http://dali.jqgfzy.top/Article/details/gtelvsqbvl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sufxvd.cn/Article/details/gtwkpyuged.html

[U111] JS：对象转 Map
来源：http://dali.c1oappe.top/Article/details/gtwkhyrpri.html

new Map(Object.entries(obj))
来源：http://dali.andypj.xyz/Article/details/gttmnlayzo.html

[U112] JS：字符串补位
来源：http://dali.nanxuanxn.top/Article/details/gtacyqqdgs.html

"7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtnrtjtbin.html

[U113] JS：正则替换全部
来源：http://dali.jiagoushi.top/Article/details/gthobthpey.html

s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtndkafycv.html

[U114] JS：JSON 深比较
来源：http://dali.xziqi.cn/Article/details/gtowkkpidd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtmrsluilt.html

[U115] JS：生成 UUID
来源：http://dali.havefunace.top/Article/details/gtkvqziase.html

crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtnulnwdth.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hfpthk.cn/Article/details/gtkijxzjfp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guowangkeji.top/Article/details/gtccdseyez.html

[U117] JS：单元测试
来源：http://dali.hfpthk.cn/Article/details/gtmprimxzk.html

npm i -D vitest;  npx vitest
来源：http://dali.cqqwz.cn/Article/details/gtqewnqfhg.html

[U118] JS：开发服务器
来源：http://dali.gotoacloud.top/Article/details/gtyvhyorjy.html

npm i -D vite;  npx vite
来源：http://dali.yj202588.top/Article/details/gtfjellyoj.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gtdgjlraam.html

npx vite build
来源：http://dali.ehwqpu.com/Article/details/gtpmkibqto.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zdqjudy.top/Article/details/gtmfqcnpxx.html

import.meta.env.VITE_API_URL
来源：http://dali.daria6918.cn/Article/details/gtpftjqpun.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtfduutkde.html

统计汇总
来源：http://dali.nanxinkj.top/Article/details/gtbqsladxp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfqrnrerr.html

按语言统计（条）：
来源：http://dali.yanxiufei.cn/Article/details/gtlncfiwyz.html

Python ......... 252
来源：http://dali.9152youxi.cn/Article/details/gtjdcmlktv.html

PHP ............ 252
来源：http://dali.zycfv.cn/Article/details/gtvzrxzgis.html

JavaScript ..... 252
来源：http://dali.svipenyu.cn/Article/details/gtsinrdpou.html

TypeScript ..... 212
来源：http://dali.bjfxy.top/Article/details/gtqqsfxyan.html

Java ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrzdxqpl.html

Go ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtjkhvkvxq.html

Ruby ........... 212
来源：http://dali.jqgfzy.top/Article/details/gtiglpuizu.html

C# ............. 212
来源：http://dali.nwbrower.top/Article/details/gtrhlotmgy.html

C .............. 30
来源：http://dali.fengsongda.top/Article/details/gtufbxbkwi.html

C++ ............ 30
来源：http://dali.gzhubu.top/Article/details/gtkbokxzap.html

SQL ............ 90
来源：http://dali.andypj.xyz/Article/details/gttogbuhbl.html

Bash ........... 80
来源：http://dali.hammf.cn/Article/details/gturpqzogu.html

Kotlin ......... 15
来源：http://dali.bjfxy.top/Article/details/gtjnauufdd.html

Swift .......... 15
来源：http://dali.haohaochexian.top/Article/details/gtcelzgjeh.html

Lua ............ 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjnstysn.html

Perl ........... 10
来源：http://dali.zhoulong.xyz/Article/details/gtjtmkrhuy.html

Scala .......... 10
来源：http://dali.wangdashe.top/Article/details/gtxbsgmqwo.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtabkmwsel.html

合计 ........... 2106 条
来源：http://dali.iojbl.cn/Article/details/gtovsazmjv.html

按章节统计：
来源：http://dali.yvedp.cn/Article/details/gtyjfcykgh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtnxnpjnhk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtweiozfxk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gtwlrugnjw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gtfaouucmv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yuanzhike.top/Article/details/gtpomsnijc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gtjzpdhhxt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gtmwqopljs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daria6918.cn/Article/details/gtlabffnkn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtavyiidte.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gtawanclyt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtqdpvildy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtawcdhbrb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtibbreqnv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gaohongyu789.top/Article/details/gtydtqalsf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ybcxt.top/Article/details/gtqzrqnecy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtnbdxmifa.html

Q SQL 专题                              90
来源：http://dali.redwolf501.top/Article/details/gtitzbwiyt.html

R Bash 专题                             80
来源：http://dali.jqgfzy.top/Article/details/gtszuzxjfg.html

S C / C++ 专题                          60
来源：http://dali.hysaishi.cn/Article/details/gtsjcpmirv.html

T 其他语言补充                          60
来源：http://dali.daria6918.cn/Article/details/gtwhgizbim.html

U 高频实用片段                         120
来源：http://dali.daria6918.cn/Article/details/gtlzvsglob.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtdkhhsvbg.html

合计                                  2106 条
来源：http://dali.jianghu66.top/Article/details/gtrsktlraw.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtyukpuvjy.html

使用提醒
来源：http://dali.yvedp.cn/Article/details/gtvleyfkwi.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtblaocxsd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.redwolf501.top/Article/details/gtafpwzdgl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sxryk.cn/Article/details/gtekkamfxj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.guowangkeji.top/Article/details/gtjhajiqjt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmuclevj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xylfe.cn/Article/details/gtgqmsiyza.html

—— 文件结束 ——
来源：http://dali.quarkkingdee.top/Article/details/gtkmlzfwaw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtawtflkwl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.9152youxi.cn/Article/details/gtjsaseqgz.html

Common Programming Examples Cheat Book
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhvanxwh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtahzrlqna.html

【收录内容】
来源：http://dali.kuanghao11.cn/Article/details/gtcawjbwoi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cashguo.top/Article/details/gtttfxvvpi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdanskbo.html

SQL · Bash · C · C++
来源：http://dali.316326.xyz/Article/details/gtzeennwcs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.dashuyun.cn/Article/details/gtqsmvyfpk.html

【使用说明】
来源：http://dali.xziqi.cn/Article/details/gtnghammal.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.snrcjt.cn/Article/details/gtpibqoreg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dianchejie.cn/Article/details/gtlzykvctt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenzaomai.com/Article/details/gtlvysytys.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ydzc1.top/Article/details/gtggxzxutc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hnxiangtu.top/Article/details/gtdxrovdtd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.pengpengdd.cyou/Article/details/gtdochjjfs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnxiangtu.top/Article/details/gtpjjersji.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.9152youxi.cn/Article/details/gtjnoyiqyf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guannengcc.top/Article/details/gtlgjmpgzd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhixingplan.top/Article/details/gtnfwsgasw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yj20258.top/Article/details/gtplhckioq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yuxming.cn/Article/details/gtqacbqigm.html

【文件统计】
来源：http://dali.zhongyouzk.top/Article/details/gthlhtxyfh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gtoeltpbak.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvhaswpx.html

目  录
来源：http://dali.cdnleiting.top/Article/details/gtcuedawbh.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtxktfzgie.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hywenlv.cn/Article/details/gtpwrttsyh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtchvobafq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gtjieklahx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gtevunpgqq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhengqikj.top/Article/details/gtybmhkbwh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gtjoomgzij.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gtftvguiss.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sysykeji.top/Article/details/gtfxpqozkj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtdtokbzub.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtivcgqpon.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtndpvkyui.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtrdqyvmsq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtttfseqan.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hysaishi.cn/Article/details/gtyknirtfn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgfzy.top/Article/details/gtapbbrgyv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtvghaqawe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nwbrower.top/Article/details/gtincsgnfk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guannengcc.top/Article/details/gtknfydkow.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gtriwqmrbl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtgdoytugb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gtyculbzfg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqhgefndn.html

A. 基础语法与类型
来源：http://dali.jlsjyb.cn/Article/details/gtyzowbpup.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbpynjhqk.html

[A01] Hello World
来源：http://dali.sufxvd.cn/Article/details/gtivcceely.html

Py:   print("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gtxvurgtcc.html

PHP:  echo "Hello, World!";
来源：http://dali.redwolf501.top/Article/details/gtayswidsv.html

JS:   console.log("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtogdqtqzn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gzhubu.top/Article/details/gtvjnhcvdf.html

Java: System.out.println("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtrclovboo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenzaomai.com/Article/details/gtjgyqjmfc.html

Ruby: puts "Hello, World!"
来源：http://dali.tianlin.xyz/Article/details/gtkqkhkrix.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gtckllejdu.html

[A02] 变量声明与赋值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkmyxlvf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.svipenyu.cn/Article/details/gtaengaqar.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbakktku.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cheryme.top/Article/details/gtgjgwgabj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ehwqpu.com/Article/details/gtmqvjjyqe.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gtlrwmdhri.html

Go:   name := "Alex"; age := 20
来源：http://dali.yueranfly.top/Article/details/gtqjlovlgn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sweek.top/Article/details/gtvvloviiw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtzwbgypdm.html

[A03] 常量定义
来源：http://dali.snrcjt.cn/Article/details/gtpqptdzbz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtececcgav.html

PHP:  const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtvgtmyclt.html

JS:   const PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtdggbkelo.html

TS:   const PI: number = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtqsooyuuw.html

Java: static final double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtrxgxogvq.html

Go:   const PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gtusuwcodb.html

Ruby: PI = 3.14159
来源：http://dali.jlsjyb.cn/Article/details/gtqaimxckz.html

C#:   const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtcsvoethu.html

[A04] 判断变量类型
来源：http://dali.aibaodan.cn/Article/details/gtbpclujdy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.redwolf501.top/Article/details/gtwuuvqkjc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jqgfzy.top/Article/details/gtxaugdxgc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gthycppjih.html

TS:   typeof x; x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gtyxezwijq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tianlin.xyz/Article/details/gtyoxhrsne.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yuxming.cn/Article/details/gtqwuecqnt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqgdzmfi.html

C#:   x.GetType().Name; x is int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuyyicst.html

[A05] 整数除法与取模
来源：http://dali.9152youxi.cn/Article/details/gtstsjthmm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cashguo.top/Article/details/gtkcdqxoqt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtsbdumgna.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtipffhexa.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtrqbvzlkp.html

Java: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtpzoxdwju.html

Go:   7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtzwywynxm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtrvjdjaxy.html

C#:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtlqafxiah.html

[A06] 字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtqwerpidb.html

Py:   int("42"); float("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtyehcujlo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.daxiang520.top/Article/details/gtvcflukrd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sxryk.cn/Article/details/gtsgmotnxu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.wangdashe.top/Article/details/gtcixjsbhg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cdnleiting.top/Article/details/gtgwgwhnnf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sxryk.cn/Article/details/gtdbufyqpu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hnxiangtu.top/Article/details/gtboaeihfy.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.0kj1m.cn/Article/details/gtnytppbcb.html

[A07] 数字转字符串
来源：http://dali.quarkkingdee.top/Article/details/gthzwokjda.html

Py:   str(42)
来源：http://dali.guannengcc.top/Article/details/gtqwmmravc.html

PHP:  (string) 42; strval(42)
来源：http://dali.iojbl.cn/Article/details/gtqfwxgvae.html

JS:   String(42); (42).toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtcpwbyjnj.html

TS:   String(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtgahztceh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhongyouzk.top/Article/details/gtfctmcluk.html

Go:   strconv.Itoa(42)
来源：http://dali.xuanzx.com/Article/details/gtkuhetivw.html

Ruby: 42.to_s
来源：http://dali.cdnleiting.top/Article/details/gtaaerastm.html

C#:   42.ToString()
来源：http://dali.cdnleiting.top/Article/details/gtemexbeic.html

[A08] 取整与四舍五入
来源：http://dali.aibaodan.cn/Article/details/gtfsnfmpfl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gtuphvgklv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xylfe.cn/Article/details/gtgrvvgcic.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gthgyzemwl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.andypj.xyz/Article/details/gtgndclsli.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtmqvpvtrg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gtdxxlpkkb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cashguo.top/Article/details/gtmdtbtnwm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthquxzccb.html

[A09] 绝对值与最大最小值
来源：http://dali.cucudq.cn/Article/details/gtdmlxfxuu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtkcwjhjnr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtmddygpry.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtjsczxbks.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtbefnzttc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtvtpfrzxw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yj20258.top/Article/details/gtjiposfrs.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.redwolf501.top/Article/details/gttqccgfis.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtueeyadzq.html

[A10] 生成随机数
来源：http://dali.sysykeji.top/Article/details/gtjxdugxxr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijujulfk.html

PHP:  random_int(1, 100);
来源：http://dali.jqgufenzy.top/Article/details/gtubxyuudx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gtlzmuwahf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nwbrower.top/Article/details/gtpzozqblb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xziqi.cn/Article/details/gtjdjyvxny.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.tianlin.xyz/Article/details/gtbpxltbkv.html

Ruby: rand(1..100)
来源：http://dali.pycfn.com/Article/details/gtskwnvmdh.html

C#:   new Random().Next(1, 101)
来源：http://dali.zycfv.cn/Article/details/gthfpkjtix.html

[A11] 条件表达式（三元）
来源：http://dali.fengsongda.top/Article/details/gtrxcgjevy.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.daxiang520.top/Article/details/gtcdjerkkv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gttxpddydw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gtpwqfowmn.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtpjkpjeqn.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtrewfepcl.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.fengsongda.top/Article/details/gtpbmzluiw.html


<!-- 参考信息 -->