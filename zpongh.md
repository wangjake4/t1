代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtnqxabpba.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtfajkennc.html

[U72] PHP：写错误日志
来源：http://dali.ybcxt.top/Article/details/gtllfuldlo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenlongwang.top/Article/details/gtukqxoigi.html

[U73] PHP：读取 ini 配置
来源：http://dali.ivvv.top/Article/details/gtyulrhydl.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxinkj.top/Article/details/gtbryupluk.html

[U74] PHP：读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gtauvwzfie.html

getenv("APP_ENV") ?: "production"
来源：http://dali.smart0.xyz/Article/details/gtnequmryr.html

[U75] PHP：依赖注入
来源：http://dali.dianchejie.cn/Article/details/gtboqlobre.html

composer require psr/container
来源：http://dali.yj20258888.top/Article/details/gtcbfnivaj.html

[U76] PHP：简单路由
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhzohigr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.bjfxy.top/Article/details/gtprhgtbzl.html

[U77] PHP：模板渲染
来源：http://dali.9152youxi.cn/Article/details/gteylssstm.html

composer require twig/twig
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwqynjvh.html

[U78] PHP：单元测试
来源：http://dali.yj20258888.top/Article/details/gtttnsuxds.html

composer require --dev phpunit/phpunit
来源：http://dali.cdnleiting.top/Article/details/gtwpynwskx.html

[U79] PHP：静态分析
来源：http://dali.jlsjyb.cn/Article/details/gthllsagmr.html

composer require --dev phpstan/phpstan
来源：http://dali.yonumen.top/Article/details/gtxdgfmmqd.html

[U80] PHP：代码规范修复
来源：http://dali.mhx1999.top/Article/details/gtrltwvgyf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gtcqzcbcth.html

[U81] JS：初始化项目
来源：http://dali.tianlin.xyz/Article/details/gtgqlasspy.html

npm init -y;  npm i express
来源：http://dali.guannengcc.top/Article/details/gtwkkcrxfc.html

[U82] JS：package.json 脚本
来源：http://dali.wangdashe.top/Article/details/gtflbcboha.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cqqwz.cn/Article/details/gtallugnnk.html

[U83] JS：ES Module 导入导出
来源：http://dali.shzxlz.cn/Article/details/gtbxepqohy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gtfrequmow.html

[U84] JS：CommonJS 写法
来源：http://dali.guannengcc.top/Article/details/gtoegmyzdo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jqgufenzy.top/Article/details/gtdzpjofue.html

[U85] JS：可选链
来源：http://dali.shangyingyoupin.top/Article/details/gthmtopqwf.html

a?.b?.c
来源：http://dali.pycfn.com/Article/details/gtigztabvu.html

[U86] JS：空值合并
来源：http://dali.zhengqikj.top/Article/details/gtfgxtmqzi.html

a ?? b
来源：http://dali.gotoacloud.top/Article/details/gtsragwrzf.html

[U87] JS：解构默认值
来源：http://dali.havefunace.top/Article/details/gtpshgbosw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.mhx1999.top/Article/details/gtbuuthbtn.html

[U88] JS：对象展开合并
来源：http://dali.smart0.xyz/Article/details/gtrmatfgnh.html

{ ...a, ...b }
来源：http://dali.guowangkeji.top/Article/details/gthhiuuope.html

[U89] JS：数组去重
来源：http://dali.havefunace.top/Article/details/gtecnbhmwg.html

[...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtsfwuqhlv.html

[U90] JS：数字数组排序
来源：http://dali.iojbl.cn/Article/details/gtwyeqfdsr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtevdqcbju.html

[U91] JS：对象键值遍历
来源：http://dali.0kj1m.cn/Article/details/gtkecqwfmb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tianlin.xyz/Article/details/gtszulbsbj.html

[U92] JS：深拷贝
来源：http://dali.sysykeji.top/Article/details/gtrhbxtxdu.html

structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtucyvffnm.html

[U93] JS：模板字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrgmqdbk.html

`共 ${n} 条`
来源：http://dali.dianchejie.cn/Article/details/gtlfatqmso.html

[U94] JS：箭头函数
来源：http://dali.nwbrower.top/Article/details/gtwumahunw.html

const double = x => x * 2;
来源：http://dali.andypj.xyz/Article/details/gtujwhnihh.html

[U95] JS：Promise 包装
来源：http://dali.yvedp.cn/Article/details/gtufkymmym.html

new Promise((resolve, reject) => {})
来源：http://dali.aibaodan.cn/Article/details/gtkxzkrjlg.html

[U96] JS：async/await 与异常
来源：http://dali.ydzc1.top/Article/details/gtqsrijemv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtyefsadib.html

[U97] JS：并发请求
来源：http://dali.hywenlv.cn/Article/details/gtrgslbiip.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtzxxhbuly.html

[U98] JS：fetch 带 JSON
来源：http://dali.ydzc1.top/Article/details/gtgllecvoz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.snrcjt.cn/Article/details/gtemqwfato.html

[U99] JS：事件监听
来源：http://dali.kuanghao11.cn/Article/details/gtxqrihjmf.html

el.addEventListener("click", e => {})
来源：http://dali.chenjidiqi.icu/Article/details/gtdudyusvz.html

[U100] JS：DOM 查询
来源：http://dali.gotoacloud.top/Article/details/gtlpioegvr.html

document.querySelector(".item")
来源：http://dali.meibo888.top/Article/details/gtelozkzde.html

[U101] JS：classList 操作
来源：http://dali.pycfn.com/Article/details/gtgvjlrtfz.html

el.classList.toggle("active")
来源：http://dali.svipenyu.cn/Article/details/gtllanhnnp.html

[U102] JS：本地存储
来源：http://dali.yongpay.top/Article/details/gtrvsdtnfi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.birdmap.top/Article/details/gtntcdfgaq.html

[U103] JS：定时器
来源：http://dali.guannengcc.top/Article/details/gtfyawrdzg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daxiang520.top/Article/details/gtpdpvvjaw.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gtvuvvmpic.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtbxqvstnk.html

[U105] JS：节流
来源：http://dali.fengsongda.top/Article/details/gtlmqgzaqv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.meibo888.top/Article/details/gtlrkrwexx.html

[U106] JS：日期格式化
来源：http://dali.pycfn.com/Article/details/gttcnfbniu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pengpengdd.cyou/Article/details/gtowthxlgp.html

[U107] JS：数字千分位
来源：http://dali.316326.xyz/Article/details/gtrctlrrua.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gtokvihfkw.html

[U108] JS：随机整数
来源：http://dali.gogol.net.cn/Article/details/gtxvybmewj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gtirhbozzs.html

[U109] JS：数组分组
来源：http://dali.jinqigufen.top/Article/details/gtwieskpnq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtqwbgdsxt.html

[U110] JS：数组分块
来源：http://dali.hywenlv.cn/Article/details/gtkynaysgm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gotoacloud.top/Article/details/gtniewxhch.html

[U111] JS：对象转 Map
来源：http://dali.kuanghao11.cn/Article/details/gtzvszyszl.html

new Map(Object.entries(obj))
来源：http://dali.gaohongyu789.top/Article/details/gtkmdgwcgi.html

[U112] JS：字符串补位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthkfahda.html

"7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtkaqsockd.html

[U113] JS：正则替换全部
来源：http://dali.haohaochexian.top/Article/details/gtknxffnlv.html

s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtayuvhrqv.html

[U114] JS：JSON 深比较
来源：http://dali.xziqi.cn/Article/details/gtpxnwwzur.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gtzlwfyzcb.html

[U115] JS：生成 UUID
来源：http://dali.xuanzx.com/Article/details/gtwwlgqfpf.html

crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtstuhadbj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yangfankeji.com/Article/details/gtfkdtosnx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yongpay.top/Article/details/gtgjymenpa.html

[U117] JS：单元测试
来源：http://dali.zhoulong.xyz/Article/details/gthtwptysm.html

npm i -D vitest;  npx vitest
来源：http://dali.yangfankeji.com/Article/details/gtoovlgqmr.html

[U118] JS：开发服务器
来源：http://dali.yuxming.cn/Article/details/gtolyjppab.html

npm i -D vite;  npx vite
来源：http://dali.aibaodan.cn/Article/details/gtajkjzcft.html

[U119] JS：生产构建
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyhaoquv.html

npx vite build
来源：http://dali.yuxming.cn/Article/details/gtbywschxv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.aibaodan.cn/Article/details/gtjmhfcoqt.html

import.meta.env.VITE_API_URL
来源：http://dali.mhx1999.top/Article/details/gtzwacsrwn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtikffivch.html

统计汇总
来源：http://dali.shanyushiyangtech.top/Article/details/gtafvtihlr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtshcyjyrh.html

按语言统计（条）：
来源：http://dali.yueranfly.top/Article/details/gtjmhnzenv.html

Python ......... 252
来源：http://dali.daria6918.cn/Article/details/gtnwlgimdm.html

PHP ............ 252
来源：http://dali.sweek.top/Article/details/gthxdtvotn.html

JavaScript ..... 252
来源：http://dali.tanke756.top/Article/details/gttgfjhboi.html

TypeScript ..... 212
来源：http://dali.hysaishi.cn/Article/details/gtuqiderwd.html

Java ........... 212
来源：http://dali.xuanzx.com/Article/details/gtwbbanimb.html

Go ............. 212
来源：http://dali.yanxiufei.cn/Article/details/gtzaefnqxf.html

Ruby ........... 212
来源：http://dali.gotoacloud.top/Article/details/gtktiutokk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gtajlgvarm.html

C .............. 30
来源：http://dali.nanxuanxn.top/Article/details/gtxtgxatrn.html

C++ ............ 30
来源：http://dali.yangfankeji.com/Article/details/gtvwgzppkg.html

SQL ............ 90
来源：http://dali.nanxuanxn.top/Article/details/gtpvgebjck.html

Bash ........... 80
来源：http://dali.xylfe.cn/Article/details/gtovpefear.html

Kotlin ......... 15
来源：http://dali.quarkkingdee.top/Article/details/gtxenngdlf.html

Swift .......... 15
来源：http://dali.xuanzx.com/Article/details/gtogdmophy.html

Lua ............ 10
来源：http://dali.bjfxy.top/Article/details/gtonmkncgw.html

Perl ........... 10
来源：http://dali.bjfxy.top/Article/details/gtvgcuhljy.html

Scala .......... 10
来源：http://dali.dashuyun.cn/Article/details/gtwqxfacbd.html

------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtxqxshfkm.html

合计 ........... 2106 条
来源：http://dali.pycfn.com/Article/details/gtlfhoriij.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gticezgsea.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gtsukrtkzl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gtgsegijdu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gtxnejjbow.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gtmyxegpjc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenzaomai.com/Article/details/gtrfueihaq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gtfajlojli.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gthuwiafqf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.redwolf501.top/Article/details/gtrgkeyzso.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtpreowvdd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gtzfanflro.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtcmyrosia.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtqdlvjzxv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtqfmhsikw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gtsrfgmvrr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tanke756.top/Article/details/gtgnwcjitq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtqwjrzywp.html

Q SQL 专题                              90
来源：http://dali.ppjwa.cn/Article/details/gttconhcbw.html

R Bash 专题                             80
来源：http://dali.mhx1999.top/Article/details/gtzblahryg.html

S C / C++ 专题                          60
来源：http://dali.meibo888.top/Article/details/gtiqztlxxh.html

T 其他语言补充                          60
来源：http://dali.cashguo.top/Article/details/gtiyxnsclb.html

U 高频实用片段                         120
来源：http://dali.guannengcc.top/Article/details/gtzfoyutah.html

------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtypdtmuhq.html

合计                                  2106 条
来源：http://dali.daria6918.cn/Article/details/gtexiapcjr.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapfqlmxn.html

使用提醒
来源：http://dali.shzxlz.cn/Article/details/gtiasnklak.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtiqpeowls.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvaqvvkf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cucudq.cn/Article/details/gtjlusmibd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.aizwys.cn/Article/details/gtfqatoqfh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.316326.xyz/Article/details/gtdbyyixhh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.fengsongda.top/Article/details/gtejbhborx.html

—— 文件结束 ——
来源：http://dali.smart0.xyz/Article/details/gtpxjffnvg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhqxaidu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.pengpengdd.cyou/Article/details/gtltaavipp.html

Common Programming Examples Cheat Book
来源：http://dali.sxryk.cn/Article/details/gtuznoehja.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnrtdyor.html

【收录内容】
来源：http://dali.ppjwa.cn/Article/details/gtsaskzlua.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ybcxt.top/Article/details/gtwbapmmrn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guannengcc.top/Article/details/gtqrvdugdu.html

SQL · Bash · C · C++
来源：http://dali.xziqi.cn/Article/details/gtpkpmgfvf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhongyouzk.top/Article/details/gtatadkeet.html

【使用说明】
来源：http://dali.gotoacloud.top/Article/details/gtsiqwypdq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgufenzy.top/Article/details/gtabyqtotj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yangfankeji.com/Article/details/gtsdxkrjwq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nanxuanxn.top/Article/details/gtnxhnnkux.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgfzy.top/Article/details/gtemuuqrwn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tian-w.cn/Article/details/gtigqcxyra.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.bjfxy.top/Article/details/gtkrxirolm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj20258.top/Article/details/gtjuhyfyfh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuxming.cn/Article/details/gtmnguhjlh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.mhx1999.top/Article/details/gtvtzlkuhm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yanxiufei.cn/Article/details/gtzvvfkzvh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.wangdashe.top/Article/details/gttsncepfa.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbtsvajx.html

【文件统计】
来源：http://dali.jqgufenzy.top/Article/details/gtixykozsb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sweek.top/Article/details/gtrjazguew.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtxlnypafa.html

目  录
来源：http://dali.tianlin.xyz/Article/details/gtiakcorlp.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtdtbgxwdm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gturdhhvfe.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ivvv.top/Article/details/gtgjsgscjs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.redwolf501.top/Article/details/gtyvyjbxem.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gtgddorihd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnxiangtu.top/Article/details/gtdqbbrnmb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gtsqxlhqwe.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gtbbfffukm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtgbadzhha.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gtskdmddfr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtcuhsqvpk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gthcebjkru.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtgvxktzgc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtdvitokrb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinqigfzy.top/Article/details/gtvafnwwqf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj20258888.top/Article/details/gtmemcqprx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtncukrvkz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cheryme.top/Article/details/gttbbxkfqp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jiagoushi.top/Article/details/gtnzjgxnez.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aizwys.cn/Article/details/gtewqqtkkm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gtqnjkthat.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtzcokjurp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvowlsnll.html

A. 基础语法与类型
来源：http://dali.haohaochexian.top/Article/details/gtudmcakxo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzidtotcc.html

[A01] Hello World
来源：http://dali.guowangkeji.top/Article/details/gtbaclxbsq.html

Py:   print("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gtefxjwnrc.html

PHP:  echo "Hello, World!";
来源：http://dali.dashuyun.cn/Article/details/gtuzkiuhmy.html

JS:   console.log("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gtzlgcmuiv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlvoxmcq.html

Java: System.out.println("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gtakaxwncp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtlfuyyiev.html

Ruby: puts "Hello, World!"
来源：http://dali.svipenyu.cn/Article/details/gtjsxaaxas.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtdxuurfdu.html

[A02] 变量声明与赋值
来源：http://dali.tanke756.top/Article/details/gtxnckawwt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.snrcjt.cn/Article/details/gtzsevnnpv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.aibaodan.cn/Article/details/gtszcidygx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.c1oappe.top/Article/details/gtoxkexhdk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtfnajsidf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.smart0.xyz/Article/details/gtrwybhlfo.html

Go:   name := "Alex"; age := 20
来源：http://dali.ppjwa.cn/Article/details/gtdabwdhcm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuanzhike.top/Article/details/gtytzjgqfm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tianlin.xyz/Article/details/gtuismjbgo.html

[A03] 常量定义
来源：http://dali.cucudq.cn/Article/details/gtxiywxjcb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.haohaochexian.top/Article/details/gtdamxlwre.html

PHP:  const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtmsssciil.html

JS:   const PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtewfqrndk.html

TS:   const PI: number = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtvwiovikb.html

Java: static final double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtomakacps.html

Go:   const PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gtmfhfvxpy.html

Ruby: PI = 3.14159
来源：http://dali.jyoumei.cn/Article/details/gtfhpvgprg.html

C#:   const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtvegfjvqj.html

[A04] 判断变量类型
来源：http://dali.ehwqpu.com/Article/details/gtjtvxqzwj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gtpahdattr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xuanzx.com/Article/details/gtiyvjwtrj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gtakhundly.html

TS:   typeof x; x instanceof Date
来源：http://dali.9152youxi.cn/Article/details/gtjbhmraaw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ppjwa.cn/Article/details/gtptwytzok.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jyoumei.cn/Article/details/gtwyfeyofu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.snrcjt.cn/Article/details/gtrgsnapzb.html

C#:   x.GetType().Name; x is int
来源：http://dali.yueranfly.top/Article/details/gtddunddyq.html

[A05] 整数除法与取模
来源：http://dali.snrcjt.cn/Article/details/gtougehdel.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj20258888.top/Article/details/gtmyxukofu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtjyianmfm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtfnvvjvhn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtgihzlqvo.html

Java: 7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gtutqwmhdl.html

Go:   7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtsvtwdxgo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtnqtgpbyx.html

C#:   7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtpcfstbtg.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtlobyqmln.html

Py:   int("42"); float("3.14")
来源：http://dali.dianchejie.cn/Article/details/gtuzlgjykr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.0kj1m.cn/Article/details/gthamlpqoc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.pycfn.com/Article/details/gtqusyvqio.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yonumen.top/Article/details/gtxrzrsafu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aibaodan.cn/Article/details/gtoeomscdr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gotoacloud.top/Article/details/gtaytlnrev.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jianghu66.top/Article/details/gtnuoywsel.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrfarpws.html

[A07] 数字转字符串
来源：http://dali.ybcxt.top/Article/details/gtvfbqedzs.html

Py:   str(42)
来源：http://dali.0kj1m.cn/Article/details/gtmzjlnzcv.html

PHP:  (string) 42; strval(42)
来源：http://dali.9152youxi.cn/Article/details/gtglwdhajk.html

JS:   String(42); (42).toString()
来源：http://dali.andypj.xyz/Article/details/gtjisoaghd.html

TS:   String(42)
来源：http://dali.sweek.top/Article/details/gtvyljgneh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gtsybthwhv.html

Go:   strconv.Itoa(42)
来源：http://dali.nanxinkj.top/Article/details/gtsietukoe.html

Ruby: 42.to_s
来源：http://dali.yuxming.cn/Article/details/gtrmuugjcu.html

C#:   42.ToString()
来源：http://dali.xziqi.cn/Article/details/gtcbmrydfw.html

[A08] 取整与四舍五入
来源：http://dali.iojbl.cn/Article/details/gtbxbguszk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtvrountlz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jianghu66.top/Article/details/gtnrgquvoa.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gtehvdahln.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hnxiangtu.top/Article/details/gtczgitkof.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gtenffyrvz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtomdzqdzb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.aizwys.cn/Article/details/gtviwhffzq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtysnalzya.html

[A09] 绝对值与最大最小值
来源：http://dali.meibo888.top/Article/details/gtjdgacuhm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtcekixtwl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqpsmeby.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.birdmap.top/Article/details/gtdbxotwyd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.meibo888.top/Article/details/gtrnaqjrka.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cashguo.top/Article/details/gtztbbynck.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ybcxt.top/Article/details/gtrnovltmx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.guowangkeji.top/Article/details/gtootwaror.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtwehttioi.html

[A10] 生成随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfpelogl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ppjwa.cn/Article/details/gtzsimzaep.html

PHP:  random_int(1, 100);
来源：http://dali.9152youxi.cn/Article/details/gtrevpofod.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fengsongda.top/Article/details/gtdqnjciep.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yangfankeji.com/Article/details/gtijmcymse.html

Java: new Random().nextInt(100) + 1
来源：http://dali.aibaodan.cn/Article/details/gtbvbpzzyu.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yj20258.top/Article/details/gtvczbrlwg.html

Ruby: rand(1..100)
来源：http://dali.smart0.xyz/Article/details/gtoidsprkr.html

C#:   new Random().Next(1, 101)
来源：http://dali.aibaodan.cn/Article/details/gthwhjwtbm.html

[A11] 条件表达式（三元）
来源：http://dali.mhx1999.top/Article/details/gtwvzmkbsd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtexvoixef.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gtsdsfkwaf.html


<!-- 参考信息 -->