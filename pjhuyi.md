代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.hongshengwenyu.top/Article/details/gt2onkckbfl.html

composer require psr/container
来源：http://dali.yuxming.cn/Article/details/gt2yixtjcno.html

[U76] PHP：简单路由
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahzyjald.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nanxuanxn.top/Article/details/gt2kxbdyhnb.html

[U77] PHP：模板渲染
来源：http://dali.smart0.xyz/Article/details/gt2fqzziqlb.html

composer require twig/twig
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vosrxlzv.html

[U78] PHP：单元测试
来源：http://dali.yueranfly.top/Article/details/gt2vpwqodwl.html

composer require --dev phpunit/phpunit
来源：http://dali.snrcjt.cn/Article/details/gt2duozypir.html

[U79] PHP：静态分析
来源：http://dali.hammf.cn/Article/details/gt2bctevuxn.html

composer require --dev phpstan/phpstan
来源：http://dali.shuidangran.top/Article/details/gt2ukqzyapj.html

[U80] PHP：代码规范修复
来源：http://dali.fzhhl.top/Article/details/gt2mkzonwge.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlowkgut.html

[U81] JS：初始化项目
来源：http://dali.gogol.net.cn/Article/details/gt2xfsjazsi.html

npm init -y;  npm i express
来源：http://dali.xuanzx.com/Article/details/gt2vqlmdhnr.html

[U82] JS：package.json 脚本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmepozws.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.9152youxi.cn/Article/details/gt2dbgukvsr.html

[U83] JS：ES Module 导入导出
来源：http://dali.andypj.xyz/Article/details/gt2lkktlnlb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gt2cdcvqlsg.html

[U84] JS：CommonJS 写法
来源：http://dali.xylfe.cn/Article/details/gt2phsypfga.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ydzc1.top/Article/details/gt2wngxxusr.html

[U85] JS：可选链
来源：http://dali.daria6918.cn/Article/details/gt2vfwnbftw.html

a?.b?.c
来源：http://dali.jianghu66.top/Article/details/gt2hhppddky.html

[U86] JS：空值合并
来源：http://dali.yanxiufei.cn/Article/details/gt2kzzbgfhp.html

a ?? b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llsgfzua.html

[U87] JS：解构默认值
来源：http://dali.chenzaomai.com/Article/details/gt2eypewyrl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.guowangkeji.top/Article/details/gt2ogsjoczc.html

[U88] JS：对象展开合并
来源：http://dali.shangyingyoupin.top/Article/details/gt2wxmnjmfc.html

{ ...a, ...b }
来源：http://dali.jqgfzy.top/Article/details/gt2lcflpast.html

[U89] JS：数组去重
来源：http://dali.daxiang520.top/Article/details/gt2slzppmac.html

[...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gt2ylpmrsnr.html

[U90] JS：数字数组排序
来源：http://dali.havefunace.top/Article/details/gt2zkwrjcjp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2ynfffkwx.html

[U91] JS：对象键值遍历
来源：http://dali.gotoacloud.top/Article/details/gt2krgpgdtu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.haohaochexian.top/Article/details/gt2pmsuuyxc.html

[U92] JS：深拷贝
来源：http://dali.chenlongwang.top/Article/details/gt2vcpjfkkp.html

structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2tbshhcnv.html

[U93] JS：模板字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2hamsvadu.html

`共 ${n} 条`
来源：http://dali.aibaodan.cn/Article/details/gt2xjldrpdu.html

[U94] JS：箭头函数
来源：http://dali.dianchejie.cn/Article/details/gt2pqcttfcs.html

const double = x => x * 2;
来源：http://dali.zdqjudy.top/Article/details/gt2metcufxa.html

[U95] JS：Promise 包装
来源：http://dali.xziqi.cn/Article/details/gt2jvzqrbej.html

new Promise((resolve, reject) => {})
来源：http://dali.jyoumei.cn/Article/details/gt2dxjynrqt.html

[U96] JS：async/await 与异常
来源：http://dali.meibo888.top/Article/details/gt2vkxvtaee.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gt2zxfihtiu.html

[U97] JS：并发请求
来源：http://dali.nanxinkj.top/Article/details/gt2jxnfdrim.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2qvxnpawm.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgfzy.top/Article/details/gt2fzppoull.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhoulong.xyz/Article/details/gt2drugehla.html

[U99] JS：事件监听
来源：http://dali.havefunace.top/Article/details/gt2oczuiiyb.html

el.addEventListener("click", e => {})
来源：http://dali.hongshengwenyu.top/Article/details/gt2wopgmncb.html

[U100] JS：DOM 查询
来源：http://dali.ydzc1.top/Article/details/gt2lgcswllh.html

document.querySelector(".item")
来源：http://dali.fzhhl.top/Article/details/gt2afreczjz.html

[U101] JS：classList 操作
来源：http://dali.zycfv.cn/Article/details/gt2bmxqktxv.html

el.classList.toggle("active")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fraetrle.html

[U102] JS：本地存储
来源：http://dali.cqqwz.cn/Article/details/gt2hmuzvijb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.fzhhl.top/Article/details/gt2cfqjahcr.html

[U103] JS：定时器
来源：http://dali.pycfn.com/Article/details/gt2ngcjwine.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhongyouzk.top/Article/details/gt2nrdadqfs.html

[U104] JS：防抖
来源：http://dali.haohaochexian.top/Article/details/gt2wtuorhvu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2jhrmrbjf.html

[U105] JS：节流
来源：http://dali.dashuyun.cn/Article/details/gt2jlvdjikr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fzhhl.top/Article/details/gt2mhhypnjh.html

[U106] JS：日期格式化
来源：http://dali.jinqigufen.top/Article/details/gt2wazyvgvt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nwbrower.top/Article/details/gt2mfchevfo.html

[U107] JS：数字千分位
来源：http://dali.cashguo.top/Article/details/gt2afhvfosz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.smart0.xyz/Article/details/gt2fapsjtnw.html

[U108] JS：随机整数
来源：http://dali.haohaochexian.top/Article/details/gt2acqlzcjb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.vqdsnc.cn/Article/details/gt2neylvqub.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2albxlmvz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gt2vqjnsfqh.html

[U110] JS：数组分块
来源：http://dali.nwbrower.top/Article/details/gt2cxhioggr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.meibo888.top/Article/details/gt2xtssvrag.html

[U111] JS：对象转 Map
来源：http://dali.sysykeji.top/Article/details/gt2cohdhldv.html

new Map(Object.entries(obj))
来源：http://dali.birdmap.top/Article/details/gt2fbfrpvub.html

[U112] JS：字符串补位
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdpenigz.html

"7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2phbhpnex.html

[U113] JS：正则替换全部
来源：http://dali.yangfankeji.com/Article/details/gt2tufwnjhe.html

s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2ufeagobs.html

[U114] JS：JSON 深比较
来源：http://dali.sxryk.cn/Article/details/gt2udueatlw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gt2jfcjywet.html

[U115] JS：生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gt2fbbrzcqf.html

crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gt2mwdavtaf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gotoacloud.top/Article/details/gt2pvvoaudt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2clpiqtrr.html

[U117] JS：单元测试
来源：http://dali.haohaochexian.top/Article/details/gt2mxqxlpll.html

npm i -D vitest;  npx vitest
来源：http://dali.nwbrower.top/Article/details/gt2ankmqhha.html

[U118] JS：开发服务器
来源：http://dali.vqdsnc.cn/Article/details/gt2pcakmtjc.html

npm i -D vite;  npx vite
来源：http://dali.jianghu66.top/Article/details/gt2zodhlzct.html

[U119] JS：生产构建
来源：http://dali.nwbrower.top/Article/details/gt2tmhodqao.html

npx vite build
来源：http://dali.ppjwa.cn/Article/details/gt2rmfxilbd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tianlin.xyz/Article/details/gt2igyqlaga.html

import.meta.env.VITE_API_URL
来源：http://dali.bjfxy.top/Article/details/gt2oiskctwq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2kuhzqmjb.html

统计汇总
来源：http://dali.tanke756.top/Article/details/gt2ndhtadra.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2lfehcdwt.html

按语言统计（条）：
来源：http://dali.cashguo.top/Article/details/gt2rwfrspbf.html

Python ......... 252
来源：http://dali.dashuyun.cn/Article/details/gt2cmamtilj.html

PHP ............ 252
来源：http://dali.tian-w.cn/Article/details/gt2txhrjdcb.html

JavaScript ..... 252
来源：http://dali.hysaishi.cn/Article/details/gt2bxvivzmo.html

TypeScript ..... 212
来源：http://dali.yanxiufei.cn/Article/details/gt2oczemygs.html

Java ........... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlaxgtuy.html

Go ............. 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpzvadrm.html

Ruby ........... 212
来源：http://dali.ehwqpu.com/Article/details/gt2gxqmcvdl.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gt2kvggaxnp.html

C .............. 30
来源：http://dali.zhongyouzk.top/Article/details/gt2qgrzobkw.html

C++ ............ 30
来源：http://dali.gogol.net.cn/Article/details/gt2kulasqzg.html

SQL ............ 90
来源：http://dali.yj20258.top/Article/details/gt2nivlgeer.html

Bash ........... 80
来源：http://dali.shzxlz.cn/Article/details/gt2bhbynowg.html

Kotlin ......... 15
来源：http://dali.nwbrower.top/Article/details/gt2jemjntni.html

Swift .......... 15
来源：http://dali.jyoumei.cn/Article/details/gt2sgztaozb.html

Lua ............ 10
来源：http://dali.zycfv.cn/Article/details/gt2eyzrcpxs.html

Perl ........... 10
来源：http://dali.jqgufenzy.top/Article/details/gt2vbtwwupk.html

Scala .......... 10
来源：http://dali.fengsongda.top/Article/details/gt2laykzquq.html

------------------------------------
来源：http://dali.sysykeji.top/Article/details/gt2jabgqoht.html

合计 ........... 2106 条
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfwufyrd.html

按章节统计：
来源：http://dali.guowangkeji.top/Article/details/gt2zrehffvf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gt2wmbtzeoa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gt2znbthkus.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2osmatfgb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gt2tgbydndp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.mhx1999.top/Article/details/gt2oizfrmre.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cucudq.cn/Article/details/gt2rptgxtph.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gt2tmqkgsgs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.0kj1m.cn/Article/details/gt2nvzdcrpc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gt2joyfoskq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gt2ujalaglo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2uprvpdft.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwovojww.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2gliscwtq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinqigufen.top/Article/details/gt2kszbcxnw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hfpthk.cn/Article/details/gt2owunzhpn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2xgzueozt.html

Q SQL 专题                              90
来源：http://dali.bjfxy.top/Article/details/gt2kdfdgwyx.html

R Bash 专题                             80
来源：http://dali.tianlin.xyz/Article/details/gt2bxxajlcb.html

S C / C++ 专题                          60
来源：http://dali.chenjidiqi.icu/Article/details/gt2nngtfmwt.html

T 其他语言补充                          60
来源：http://dali.snrcjt.cn/Article/details/gt2yhqdjupt.html

U 高频实用片段                         120
来源：http://dali.jianghu66.top/Article/details/gt2xbhzyzya.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2wxvaywqd.html

合计                                  2106 条
来源：http://dali.hfpthk.cn/Article/details/gt2wyxksbrr.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwxnkcgc.html

使用提醒
来源：http://dali.yueranfly.top/Article/details/gt2lhtimuor.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2fmuqtipq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.birdmap.top/Article/details/gt2qukgkpab.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nanxinkj.top/Article/details/gt2iuylvjcf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.vqdsnc.cn/Article/details/gt2mmdvyzte.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcdglddz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shuidangran.top/Article/details/gt2qklyqxft.html

—— 文件结束 ——
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2unmrzqyj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2neymzviv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jiagoushi.top/Article/details/gt2saqhbitz.html

Common Programming Examples Cheat Book
来源：http://dali.tian-w.cn/Article/details/gt2zyhgxcbx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2jhsyyxbt.html

【收录内容】
来源：http://dali.jianghu66.top/Article/details/gt2eqigagbx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hnqzz.top/Article/details/gt2ypvvjawt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2laeyqokg.html

SQL · Bash · C · C++
来源：http://dali.smart0.xyz/Article/details/gt2lfzwsiad.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxuanxn.top/Article/details/gt2sgfbgusx.html

【使用说明】
来源：http://dali.hysaishi.cn/Article/details/gt2fyedvfwk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.meibo888.top/Article/details/gt2wpwjlpsi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sufxvd.cn/Article/details/gt2zgmgzrhh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yangfankeji.com/Article/details/gt2dphbrahe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.guannengcc.top/Article/details/gt2nrvuverk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ppjwa.cn/Article/details/gt2fuhgdpwa.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.wangshuangyany.cn/Article/details/gt2jcczndhp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.snrcjt.cn/Article/details/gt2ryqxchjt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gzhubu.top/Article/details/gt2dillyzor.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangdashe.top/Article/details/gt2jrnjriad.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cscwhbwr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jyoumei.cn/Article/details/gt2zydxngcz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jtqngycv.html

【文件统计】
来源：http://dali.9152youxi.cn/Article/details/gt2cegigewp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cheryme.top/Article/details/gt2pptvvkzu.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gt2fptvcqqc.html

目  录
来源：http://dali.nwbrower.top/Article/details/gt2buczpuut.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gt2ggwqugdy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wvtvfzdw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gt2ivuanscp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gt2fqpdrawl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrpodgzj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjbjpbfn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhengqikj.top/Article/details/gt2xgsiutob.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gt2wppryvvu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gt2dvkylhoo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gt2gqwvrtgm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sxryk.cn/Article/details/gt2chncayzk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gt2vcokiygz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gt2fuhblnow.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gt2vaavqslj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gt2eukugptm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shzxlz.cn/Article/details/gt2xiquzelr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gt2gwocjyru.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tianlin.xyz/Article/details/gt2teilksrf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dianchejie.cn/Article/details/gt2aczknsuv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aibaodan.cn/Article/details/gt2ljiuiznj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gt2xyyyxjsb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gt2sbqcqggm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2yokkwpzn.html

A. 基础语法与类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2iuyjldjr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzhlwzrb.html

[A01] Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2ndhgjvjv.html

Py:   print("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gt2ifvmxbvz.html

PHP:  echo "Hello, World!";
来源：http://dali.zdqjudy.top/Article/details/gt2cxfuhhfu.html

JS:   console.log("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gt2udutxzbt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yangfankeji.com/Article/details/gt2sevchjey.html

Java: System.out.println("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gt2lhesriqm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.dianchejie.cn/Article/details/gt2qxvycjza.html

Ruby: puts "Hello, World!"
来源：http://dali.fengsongda.top/Article/details/gt2hmepefoj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gt2pkzenezw.html

[A02] 变量声明与赋值
来源：http://dali.cdnleiting.top/Article/details/gt2mxxfxapk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjkzjzjm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2elesceak.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.guowangkeji.top/Article/details/gt2ucowlbrg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.quarkkingdee.top/Article/details/gt2vkyogygk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjzlxeyd.html

Go:   name := "Alex"; age := 20
来源：http://dali.fzhhl.top/Article/details/gt2luixwiku.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xinyue.icu/Article/details/gt2rldbqjqw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gt2djpwukod.html

[A03] 常量定义
来源：http://dali.cdnleiting.top/Article/details/gt2tjchffhe.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenlongwang.top/Article/details/gt2jhpxsgic.html

PHP:  const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2iaricamk.html

JS:   const PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmromuch.html

TS:   const PI: number = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2wsurfien.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2xzfiwgzh.html

Go:   const PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gt2rttlwrcc.html

Ruby: PI = 3.14159
来源：http://dali.shuidangran.top/Article/details/gt2ugkbpnmv.html

C#:   const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2ejflmzll.html

[A04] 判断变量类型
来源：http://dali.yueranfly.top/Article/details/gt2rrpoajad.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuxming.cn/Article/details/gt2ornrdqle.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenzaomai.com/Article/details/gt2gbbmffkn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sweek.top/Article/details/gt2fetpjqac.html

TS:   typeof x; x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gt2whmzlbqy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xinyue.icu/Article/details/gt2ylgyncqa.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cashguo.top/Article/details/gt2oukldinv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.tianlin.xyz/Article/details/gt2rqbszzie.html

C#:   x.GetType().Name; x is int
来源：http://dali.guowangkeji.top/Article/details/gt2soqjhkxq.html

[A05] 整数除法与取模
来源：http://dali.sysykeji.top/Article/details/gt2pjzzoxul.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigufen.top/Article/details/gt2laqmyaho.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2cpubjwbr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nwbrower.top/Article/details/gt2cwxplmqs.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gt2jhisysiv.html

Java: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qenqgrln.html

Go:   7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2dufopuij.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gt2pchomyhu.html

C#:   7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gt2nwzhqgcf.html

[A06] 字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gt2komjrcct.html

Py:   int("42"); float("3.14")
来源：http://dali.daria6918.cn/Article/details/gt2mekqvxzu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jyoumei.cn/Article/details/gt2guutiesu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.dianchejie.cn/Article/details/gt2fvdkknru.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahutijbi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.316326.xyz/Article/details/gt2xmpxclai.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jiagoushi.top/Article/details/gt2nzlrzedl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinqigfzy.top/Article/details/gt2vxfmgvgh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258888.top/Article/details/gt2dctymrgc.html

[A07] 数字转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2jgbnonkg.html

Py:   str(42)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmccbrbh.html

PHP:  (string) 42; strval(42)
来源：http://dali.hnqzz.top/Article/details/gt2uaezoovw.html

JS:   String(42); (42).toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2niayftlb.html

TS:   String(42)
来源：http://dali.ydzc1.top/Article/details/gt2mwdhtszr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ybcxt.top/Article/details/gt2cqpqidzv.html

Go:   strconv.Itoa(42)
来源：http://dali.guannengcc.top/Article/details/gt2cesfwuiy.html

Ruby: 42.to_s
来源：http://dali.yonumen.top/Article/details/gt2usnsnaxi.html

C#:   42.ToString()
来源：http://dali.jiagoushi.top/Article/details/gt2bhwjduyr.html

[A08] 取整与四舍五入
来源：http://dali.yongpay.top/Article/details/gt2gbfwyzfc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gt2nkappdmd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xylfe.cn/Article/details/gt2cezpmpis.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqdjdnvp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.nwbrower.top/Article/details/gt2sserevtp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gt2irurdgtw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gt2dibbtjnk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.havefunace.top/Article/details/gt2ofpfiokm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gt2agnmwwhi.html

[A09] 绝对值与最大最小值
来源：http://dali.xinyue.icu/Article/details/gt2qsbqauum.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2csjvmyae.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2sauyviao.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gt2jsdaxgoa.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.tian-w.cn/Article/details/gt2inuofmrc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2pcpfrhst.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jlsjyb.cn/Article/details/gt2wkgkupoa.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sufxvd.cn/Article/details/gt2ikvhcfet.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2dnyikmom.html

[A10] 生成随机数
来源：http://dali.andypj.xyz/Article/details/gt2ahgnklri.html

Py:   import random; random.randint(1, 100)
来源：http://dali.wangdashe.top/Article/details/gt2ihkviair.html

PHP:  random_int(1, 100);
来源：http://dali.sufxvd.cn/Article/details/gt2jfmbivyn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fengsongda.top/Article/details/gt2fgwybjal.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fengsongda.top/Article/details/gt2dwspqjet.html

Java: new Random().nextInt(100) + 1
来源：http://dali.dianchejie.cn/Article/details/gt2divjhyvo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pycfn.com/Article/details/gt2nnqwovah.html

Ruby: rand(1..100)
来源：http://dali.guannengcc.top/Article/details/gt2hfhybwty.html

C#:   new Random().Next(1, 101)
来源：http://dali.haohaochexian.top/Article/details/gt2mggmwhim.html

[A11] 条件表达式（三元）
来源：http://dali.ppjwa.cn/Article/details/gt2erxzkcua.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hywenlv.cn/Article/details/gt2eakdxsfd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gt2hfscgjhw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2awlwgsqb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdnsacho.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gt2tvreuhyf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.haohaochexian.top/Article/details/gt2vbhpecto.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gt2ajqpaytc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gt2gikwucam.html

[A12] 字符串插值 / 格式化
来源：http://dali.316326.xyz/Article/details/gt2lzytmjhr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hysaishi.cn/Article/details/gt2qbhreett.html


<!-- 参考信息 -->