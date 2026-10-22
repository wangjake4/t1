代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfptchbo.html

throw new RuntimeException("失败", 500);
来源：http://dali.cucudq.cn/Article/details/gt2fhkpqnkz.html

[U72] PHP：写错误日志
来源：http://dali.sufxvd.cn/Article/details/gt2rxphrgro.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yangfankeji.com/Article/details/gt2kskyhzle.html

[U73] PHP：读取 ini 配置
来源：http://dali.daria6918.cn/Article/details/gt2wkbdnclx.html

parse_ini_file("config.ini", true)
来源：http://dali.ehwqpu.com/Article/details/gt2ccnpqlmw.html

[U74] PHP：读取环境变量
来源：http://dali.tanke756.top/Article/details/gt2vhwghrrl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.wangdashe.top/Article/details/gt2qisnjsaj.html

[U75] PHP：依赖注入
来源：http://dali.andypj.xyz/Article/details/gt2epctxioj.html

composer require psr/container
来源：http://dali.hfpthk.cn/Article/details/gt2ofxnngyz.html

[U76] PHP：简单路由
来源：http://dali.hfpthk.cn/Article/details/gt2aorvrdev.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.kuanghao11.cn/Article/details/gt2mumggich.html

[U77] PHP：模板渲染
来源：http://dali.kuanghao11.cn/Article/details/gt2anxtmkfn.html

composer require twig/twig
来源：http://dali.zycfv.cn/Article/details/gt2itkpzfvj.html

[U78] PHP：单元测试
来源：http://dali.nwbrower.top/Article/details/gt2duumdddt.html

composer require --dev phpunit/phpunit
来源：http://dali.ehwqpu.com/Article/details/gt2mydrrypz.html

[U79] PHP：静态分析
来源：http://dali.sxryk.cn/Article/details/gt2rlnyudny.html

composer require --dev phpstan/phpstan
来源：http://dali.chenjidiqi.icu/Article/details/gt2iyswzbhu.html

[U80] PHP：代码规范修复
来源：http://dali.cheryme.top/Article/details/gt2drsnkdax.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhzkpaos.html

[U81] JS：初始化项目
来源：http://dali.tian-w.cn/Article/details/gt2nyfkprco.html

npm init -y;  npm i express
来源：http://dali.tian-w.cn/Article/details/gt2fgcbhozb.html

[U82] JS：package.json 脚本
来源：http://dali.jqgufenzy.top/Article/details/gt2wvjamchy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenlongwang.top/Article/details/gt2imkgutxl.html

[U83] JS：ES Module 导入导出
来源：http://dali.jiagoushi.top/Article/details/gt2ymeedgrs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gt2gwbplxqq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntavcgsp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.snrcjt.cn/Article/details/gt2emztwydw.html

[U85] JS：可选链
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffvqgzzw.html

a?.b?.c
来源：http://dali.pycfn.com/Article/details/gt2anhvlzhz.html

[U86] JS：空值合并
来源：http://dali.zdqjudy.top/Article/details/gt2ravpevyu.html

a ?? b
来源：http://dali.gotoacloud.top/Article/details/gt2vbrvnjpd.html

[U87] JS：解构默认值
来源：http://dali.hywenlv.cn/Article/details/gt2mfzbqgcc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ppjwa.cn/Article/details/gt2yxxruzwv.html

[U88] JS：对象展开合并
来源：http://dali.chenlongwang.top/Article/details/gt2jozosarz.html

{ ...a, ...b }
来源：http://dali.ydzc1.top/Article/details/gt2nizjswhh.html

[U89] JS：数组去重
来源：http://dali.sufxvd.cn/Article/details/gt2wkagfoon.html

[...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gt2zkjfczbr.html

[U90] JS：数字数组排序
来源：http://dali.cqqwz.cn/Article/details/gt2fhksaatr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2bwdyhsxi.html

[U91] JS：对象键值遍历
来源：http://dali.yj20258888.top/Article/details/gt2qeajhijg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxxysgko.html

[U92] JS：深拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2cqphvljw.html

structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2xgrdtvdr.html

[U93] JS：模板字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2pmtpblsx.html

`共 ${n} 条`
来源：http://dali.daxiang520.top/Article/details/gt2otfcrwtg.html

[U94] JS：箭头函数
来源：http://dali.yuxming.cn/Article/details/gt2ebftrblb.html

const double = x => x * 2;
来源：http://dali.birdmap.top/Article/details/gt2hcuafafe.html

[U95] JS：Promise 包装
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmdfkglv.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gt2vjbqtwvt.html

[U96] JS：async/await 与异常
来源：http://dali.aizwys.cn/Article/details/gt2fbxrkoft.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2wxzhsjcb.html

[U97] JS：并发请求
来源：http://dali.wangdashe.top/Article/details/gt2zkvzzfcg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gt2nltiwzck.html

[U98] JS：fetch 带 JSON
来源：http://dali.andypj.xyz/Article/details/gt2qcpeinjt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nanxinkj.top/Article/details/gt2kayukgal.html

[U99] JS：事件监听
来源：http://dali.svipenyu.cn/Article/details/gt2hxknaagi.html

el.addEventListener("click", e => {})
来源：http://dali.zhoulong.xyz/Article/details/gt2svdbjxhz.html

[U100] JS：DOM 查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukutzjpq.html

document.querySelector(".item")
来源：http://dali.snrcjt.cn/Article/details/gt2ijqisxuv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wittjkwb.html

el.classList.toggle("active")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qmkyocsn.html

[U102] JS：本地存储
来源：http://dali.hywenlv.cn/Article/details/gt2wxkaowzb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenlongwang.top/Article/details/gt2zppafpjl.html

[U103] JS：定时器
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgbarlvu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gt2ufjokkoa.html

[U104] JS：防抖
来源：http://dali.jinqigufen.top/Article/details/gt2peuqydna.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2evlkudkg.html

[U105] JS：节流
来源：http://dali.feifeiyinyue.top/Article/details/gt2nmoivzyb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.pycfn.com/Article/details/gt2pjszhmak.html

[U106] JS：日期格式化
来源：http://dali.0kj1m.cn/Article/details/gt2qzjzweuo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tianlin.xyz/Article/details/gt2ofywaobz.html

[U107] JS：数字千分位
来源：http://dali.aizwys.cn/Article/details/gt2zrpcoqmz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sweek.top/Article/details/gt2nkzuqmus.html

[U108] JS：随机整数
来源：http://dali.xuetiantiany.cn/Article/details/gt2snxpgwiy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj202588.top/Article/details/gt2chbvdtsh.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxqbcatw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2iefaadre.html

[U110] JS：数组分块
来源：http://dali.bjfxy.top/Article/details/gt2olpmdllb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqernxxm.html

[U111] JS：对象转 Map
来源：http://dali.daxiang520.top/Article/details/gt2eymhhtdj.html

new Map(Object.entries(obj))
来源：http://dali.0kj1m.cn/Article/details/gt2drdltisx.html

[U112] JS：字符串补位
来源：http://dali.aizwys.cn/Article/details/gt2ylcmahql.html

"7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2tdzzsoiu.html

[U113] JS：正则替换全部
来源：http://dali.0kj1m.cn/Article/details/gt2tyhcsqin.html

s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2laulhuec.html

[U114] JS：JSON 深比较
来源：http://dali.yueranfly.top/Article/details/gt2kfgldsbi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkgdddbb.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gt2fywpmugl.html

crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gt2nkybjtim.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yueranfly.top/Article/details/gt2ateowttv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gzhubu.top/Article/details/gt2bcmbxzmg.html

[U117] JS：单元测试
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgxsokrr.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigufen.top/Article/details/gt2qlajrgwj.html

[U118] JS：开发服务器
来源：http://dali.yj202588.top/Article/details/gt2bnzpxhok.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gt2pvdkvkda.html

[U119] JS：生产构建
来源：http://dali.yangfankeji.com/Article/details/gt2iieudncz.html

npx vite build
来源：http://dali.hfpthk.cn/Article/details/gt2oovsxibj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldbevfqn.html

import.meta.env.VITE_API_URL
来源：http://dali.dianchejie.cn/Article/details/gt2pqduhmnz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2oavbgacv.html

统计汇总
来源：http://dali.tian-w.cn/Article/details/gt2thvsdptw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ikjbgsff.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgcgslo.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gt2wjksuqot.html

PHP ............ 252
来源：http://dali.hnxiangtu.top/Article/details/gt2vfzocqcz.html

JavaScript ..... 252
来源：http://dali.cqqwz.cn/Article/details/gt2xsqkmpfc.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gt2iqwmntdi.html

Java ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gt2vabsomra.html

Go ............. 212
来源：http://dali.jqgfzy.top/Article/details/gt2gdhabzbe.html

Ruby ........... 212
来源：http://dali.daria6918.cn/Article/details/gt2qujizmfz.html

C# ............. 212
来源：http://dali.chenlongwang.top/Article/details/gt2krtzhqtv.html

C .............. 30
来源：http://dali.yj20258.top/Article/details/gt2zdhjzufc.html

C++ ............ 30
来源：http://dali.316326.xyz/Article/details/gt2tmjasguj.html

SQL ............ 90
来源：http://dali.chenlongwang.top/Article/details/gt2pytnvdaz.html

Bash ........... 80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwkflyrt.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gt2gevqqxsq.html

Swift .......... 15
来源：http://dali.jinqigufen.top/Article/details/gt2kzkkmkue.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gt2gqsrnfoh.html

Perl ........... 10
来源：http://dali.snrcjt.cn/Article/details/gt2lpjpdlsm.html

Scala .......... 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gydwjrqk.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2nzqinxgr.html

合计 ........... 2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpuuqsvw.html

按章节统计：
来源：http://dali.316326.xyz/Article/details/gt2bpltlpyr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gt2ofpmxbql.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2bmnzcxfc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gt2fixxptlc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangtech.top/Article/details/gt2inlgnxto.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jianghu66.top/Article/details/gt2vdcaolex.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gt2pxwsekdm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtaogaz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gt2lavzqwix.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gt2mrfqiodp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhewydkf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gt2gsvwnijf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2yiqtxeli.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gt2havjyodh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.snrcjt.cn/Article/details/gt2jxagzpin.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.kuanghao11.cn/Article/details/gt2rpwmyasw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jwmmmxvo.html

Q SQL 专题                              90
来源：http://dali.snrcjt.cn/Article/details/gt2tpmpnpfl.html

R Bash 专题                             80
来源：http://dali.xuanzx.com/Article/details/gt2bprlhbkp.html

S C / C++ 专题                          60
来源：http://dali.yangfankeji.com/Article/details/gt2hevalstj.html

T 其他语言补充                          60
来源：http://dali.kuanghao11.cn/Article/details/gt2zkncqqpe.html

U 高频实用片段                         120
来源：http://dali.meibo888.top/Article/details/gt2ykfsqtgi.html

------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gcuifavf.html

合计                                  2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gt2dyukbozt.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2vbyspxwm.html

使用提醒
来源：http://dali.yuanzhike.top/Article/details/gt2cttayyit.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2vvwujydm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj20258.top/Article/details/gt2sdmymzqw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ydzc1.top/Article/details/gt2xmdrgrtu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.nwbrower.top/Article/details/gt2ndwouvwd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zycfv.cn/Article/details/gt2gcgkmbcw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aibaodan.cn/Article/details/gt2zwnxguyu.html

—— 文件结束 ——
来源：http://dali.zycfv.cn/Article/details/gt2qadxkrzo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2icqucupt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ivvv.top/Article/details/gt2htirtizd.html

Common Programming Examples Cheat Book
来源：http://dali.iojbl.cn/Article/details/gt2fzwckbbt.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2usencnye.html

【收录内容】
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkfyhcyd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xylfe.cn/Article/details/gt2boxzxxgp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.snrcjt.cn/Article/details/gt2sjbyetuz.html

SQL · Bash · C · C++
来源：http://dali.sysykeji.top/Article/details/gt2usnsoqxw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nwbrower.top/Article/details/gt2yuwqenqu.html

【使用说明】
来源：http://dali.jyoumei.cn/Article/details/gt2bvzjlvvq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjeavvst.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhengqikj.top/Article/details/gt2tlazglmc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aibaodan.cn/Article/details/gt2vgdcncou.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuanzhike.top/Article/details/gt2hnztxlaq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.daria6918.cn/Article/details/gt2rlhihaij.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muwzcsxa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aizwys.cn/Article/details/gt2jexlktep.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenzaomai.com/Article/details/gt2awmhugen.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhiwuduotai.top/Article/details/gt2ulpmhspm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hysaishi.cn/Article/details/gt2fcejeuor.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenlongwang.top/Article/details/gt2vvdjkpjt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.tianlin.xyz/Article/details/gt2kzckxjgf.html

【文件统计】
来源：http://dali.feifeiyinyue.top/Article/details/gt2xszumyhe.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yanxiufei.cn/Article/details/gt2njxdbvow.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gt2pafwavxq.html

目  录
来源：http://dali.fengsongda.top/Article/details/gt2vuaexoih.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gt2yvztkuly.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2byigreel.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.snrcjt.cn/Article/details/gt2udjwnfls.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gt2emopwtyi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sufxvd.cn/Article/details/gt2jdreuodd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.fzhhl.top/Article/details/gt2axhvgmio.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xinyue.icu/Article/details/gt2kcjtcyzj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gt2hzhovcez.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gt2efsfdrnq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gt2ghjjazxr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gt2nmpfaeyl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gt2lpmlndys.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gt2gdocgjrq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gt2wwbwjcbc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2dufnkilc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2thrmraus.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gt2clkmzhmm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2qtkpkbev.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gzhubu.top/Article/details/gt2rvdsgnxs.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.nanxinkj.top/Article/details/gt2jctrlwce.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gt2joiqqbjv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gt2gozmiyyt.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ffamhysx.html

A. 基础语法与类型
来源：http://dali.zhengqikj.top/Article/details/gt2lilefpia.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2zswwtomn.html

[A01] Hello World
来源：http://dali.xylfe.cn/Article/details/gt2thcnnrne.html

Py:   print("Hello, World!")
来源：http://dali.c1oappe.top/Article/details/gt2mmikttug.html

PHP:  echo "Hello, World!";
来源：http://dali.smart0.xyz/Article/details/gt2bhcnjbbl.html

JS:   console.log("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gt2rpilnswt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yongpay.top/Article/details/gt2tkbtfzix.html

Java: System.out.println("Hello, World!");
来源：http://dali.dianchejie.cn/Article/details/gt2wwyqcjqu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yljeljft.html

Ruby: puts "Hello, World!"
来源：http://dali.zdqjudy.top/Article/details/gt2xiykxpbb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gt2ojbhzkjc.html

[A02] 变量声明与赋值
来源：http://dali.sweek.top/Article/details/gt2jdrwqpxj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tanke756.top/Article/details/gt2akbagbmf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.0kj1m.cn/Article/details/gt2wlmlckvc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ybcxt.top/Article/details/gt2mnzoppmy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gaohongyu789.top/Article/details/gt2fbtsukrp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tianlin.xyz/Article/details/gt2fnpznlha.html

Go:   name := "Alex"; age := 20
来源：http://dali.yonumen.top/Article/details/gt2yhqlhscz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jiagoushi.top/Article/details/gt2tnlzvsss.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.guannengcc.top/Article/details/gt2jprlxykx.html

[A03] 常量定义
来源：http://dali.hysaishi.cn/Article/details/gt2hnqnnlqx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cdnleiting.top/Article/details/gt2qupaevqc.html

PHP:  const PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2uwyfeste.html

JS:   const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2hyvgpaks.html

TS:   const PI: number = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2yermlavl.html

Java: static final double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2bfbzjrbh.html

Go:   const PI = 3.14159
来源：http://dali.zdqjudy.top/Article/details/gt2jbwozrlq.html

Ruby: PI = 3.14159
来源：http://dali.jinqigufen.top/Article/details/gt2bldoaetc.html

C#:   const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2jpwfkfle.html

[A04] 判断变量类型
来源：http://dali.chenlongwang.top/Article/details/gt2jrxlpzfw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpkrlrcj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hywenlv.cn/Article/details/gt2onnsxkuk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinqigfzy.top/Article/details/gt2bkdivwfp.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258.top/Article/details/gt2jkgrhjub.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangtech.top/Article/details/gt2saprqhgg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.mhx1999.top/Article/details/gt2pcavxgfq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebodrzua.html

C#:   x.GetType().Name; x is int
来源：http://dali.hywenlv.cn/Article/details/gt2fzqsidkt.html

[A05] 整数除法与取模
来源：http://dali.daria6918.cn/Article/details/gt2zakzgiel.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yonumen.top/Article/details/gt2czhdigqw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gt2dnbstvwv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gt2rgszcrha.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gt2qnwrnwdl.html

Java: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gt2orqtclfo.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2xensfwga.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2qgywezcy.html

C#:   7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gt2miytfrsy.html

[A06] 字符串转数字
来源：http://dali.wangdashe.top/Article/details/gt2lzrsmrtd.html

Py:   int("42"); float("3.14")
来源：http://dali.iojbl.cn/Article/details/gt2bweetoac.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.pengpengdd.cyou/Article/details/gt2swenbjye.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gt2hwdyalbe.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnqzz.top/Article/details/gt2vklaujus.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shzxlz.cn/Article/details/gt2lcbnzglp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.tanke756.top/Article/details/gt2ptjimcxs.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daria6918.cn/Article/details/gt2fimqtyrl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gt2jukdyqfz.html

[A07] 数字转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2catmaqlh.html

Py:   str(42)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcqyffaj.html

PHP:  (string) 42; strval(42)
来源：http://dali.zdqjudy.top/Article/details/gt2dqgzuzst.html

JS:   String(42); (42).toString()
来源：http://dali.tanke756.top/Article/details/gt2aeuxjwfy.html

TS:   String(42)
来源：http://dali.wangdashe.top/Article/details/gt2xxjmnbbb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.nanxinkj.top/Article/details/gt2ettdmjhu.html

Go:   strconv.Itoa(42)
来源：http://dali.guannengcc.top/Article/details/gt2rcxateph.html

Ruby: 42.to_s
来源：http://dali.daria6918.cn/Article/details/gt2pyqydtdl.html

C#:   42.ToString()
来源：http://dali.haohaochexian.top/Article/details/gt2kmesukrm.html

[A08] 取整与四舍五入
来源：http://dali.meibo888.top/Article/details/gt2exugqndb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gt2npgspmpu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.vqdsnc.cn/Article/details/gt2mdtbdydm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gt2wmgnidev.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.aibaodan.cn/Article/details/gt2avucrbnl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gt2kueipzzq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2feixnxze.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nanxinkj.top/Article/details/gt2mwoesckf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gt2smsuqnjf.html

[A09] 绝对值与最大最小值
来源：http://dali.zhixingplan.top/Article/details/gt2uxnwpejz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2hqevnisu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gt2dyjlpuxo.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2jyzixlyp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sysykeji.top/Article/details/gt2yxerfmsl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.nwbrower.top/Article/details/gt2areuhwtf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.haohaochexian.top/Article/details/gt2lwxwmgao.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.nwbrower.top/Article/details/gt2zppooaus.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2dnyiffkd.html

[A10] 生成随机数
来源：http://dali.yj20258888.top/Article/details/gt2kvhyinkd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.tianlin.xyz/Article/details/gt2ecsvenoy.html

PHP:  random_int(1, 100);
来源：http://dali.yanxiufei.cn/Article/details/gt2pyvxilim.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.haohaochexian.top/Article/details/gt2qkzxunxl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jianghu66.top/Article/details/gt2lxhkwhms.html

Java: new Random().nextInt(100) + 1
来源：http://dali.bjfxy.top/Article/details/gt2hgkfotjp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hammf.cn/Article/details/gt2fvrmkjxb.html

Ruby: rand(1..100)
来源：http://dali.tian-w.cn/Article/details/gt2eyetdzpb.html

C#:   new Random().Next(1, 101)
来源：http://dali.pycfn.com/Article/details/gt2gbzxozyl.html

[A11] 条件表达式（三元）
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyvyuuji.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgsfxljj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gt2lnqwvrpu.html


<!-- 参考信息 -->