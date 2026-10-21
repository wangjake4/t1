代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.0kj1m.cn/Article/details/gtnulvnwoz.html

composer require psr/container
来源：http://dali.yj202588.top/Article/details/gtpncuqavs.html

[U76] PHP：简单路由
来源：http://dali.xuanzx.com/Article/details/gtovknahes.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shuidangran.top/Article/details/gtuxfooskv.html

[U77] PHP：模板渲染
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdpclfzw.html

composer require twig/twig
来源：http://dali.tian-w.cn/Article/details/gtkevxcjsk.html

[U78] PHP：单元测试
来源：http://dali.yongpay.top/Article/details/gtlhfqyhsl.html

composer require --dev phpunit/phpunit
来源：http://dali.guannengcc.top/Article/details/gtqpdlgqxb.html

[U79] PHP：静态分析
来源：http://dali.ybcxt.top/Article/details/gtxskmyfsn.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvdmeyhb.html

[U80] PHP：代码规范修复
来源：http://dali.xinyue.icu/Article/details/gthsxgbvds.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhoulong.xyz/Article/details/gtqfthgbip.html

[U81] JS：初始化项目
来源：http://dali.tianlin.xyz/Article/details/gtlvdhtxxc.html

npm init -y;  npm i express
来源：http://dali.sufxvd.cn/Article/details/gtpwqtkwkt.html

[U82] JS：package.json 脚本
来源：http://dali.redwolf501.top/Article/details/gtrzrnptnq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tian-w.cn/Article/details/gtslyuxcid.html

[U83] JS：ES Module 导入导出
来源：http://dali.svipenyu.cn/Article/details/gtstbjbxim.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sweek.top/Article/details/gtamgdjmle.html

[U84] JS：CommonJS 写法
来源：http://dali.dianchejie.cn/Article/details/gtsphuovjn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ydzc1.top/Article/details/gtaqlcvhym.html

[U85] JS：可选链
来源：http://dali.svipenyu.cn/Article/details/gtkocmhoaf.html

a?.b?.c
来源：http://dali.svipenyu.cn/Article/details/gtxdkffjxb.html

[U86] JS：空值合并
来源：http://dali.jlsjyb.cn/Article/details/gtcnivnlxr.html

a ?? b
来源：http://dali.yj20258.top/Article/details/gtyazhwrdq.html

[U87] JS：解构默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtipjqqirs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.wangdashe.top/Article/details/gtgrpvpquw.html

[U88] JS：对象展开合并
来源：http://dali.havefunace.top/Article/details/gtoxijthhc.html

{ ...a, ...b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhuxbalc.html

[U89] JS：数组去重
来源：http://dali.jianghu66.top/Article/details/gtotasxmts.html

[...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gtylhejajy.html

[U90] JS：数字数组排序
来源：http://dali.zycfv.cn/Article/details/gtzqzfvsjo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtpqehcqxw.html

[U91] JS：对象键值遍历
来源：http://dali.yonumen.top/Article/details/gtbfzstelx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaynilgfk.html

[U92] JS：深拷贝
来源：http://dali.meibo888.top/Article/details/gtsobdsras.html

structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtwifycxre.html

[U93] JS：模板字符串
来源：http://dali.meibo888.top/Article/details/gtggpxacni.html

`共 ${n} 条`
来源：http://dali.wangshuangyany.cn/Article/details/gtbnakddxu.html

[U94] JS：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gtevxonzul.html

const double = x => x * 2;
来源：http://dali.9152youxi.cn/Article/details/gtqoffcezg.html

[U95] JS：Promise 包装
来源：http://dali.nwbrower.top/Article/details/gtqqfidgzk.html

new Promise((resolve, reject) => {})
来源：http://dali.svipenyu.cn/Article/details/gtdkqofbud.html

[U96] JS：async/await 与异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzhcytwb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtniaspdxl.html

[U97] JS：并发请求
来源：http://dali.aibaodan.cn/Article/details/gtpmaklhsr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtdyouksqh.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtuelndrca.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ybcxt.top/Article/details/gtbngbdzkr.html

[U99] JS：事件监听
来源：http://dali.hnxiangtu.top/Article/details/gtuettuudp.html

el.addEventListener("click", e => {})
来源：http://dali.xuanzx.com/Article/details/gtzqpvkcla.html

[U100] JS：DOM 查询
来源：http://dali.xylfe.cn/Article/details/gtfywkwtmu.html

document.querySelector(".item")
来源：http://dali.yongpay.top/Article/details/gtxwakmjhk.html

[U101] JS：classList 操作
来源：http://dali.xziqi.cn/Article/details/gtixahotsd.html

el.classList.toggle("active")
来源：http://dali.xylfe.cn/Article/details/gtmikwatda.html

[U102] JS：本地存储
来源：http://dali.yj20258888.top/Article/details/gtpdwtwnrs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aibaodan.cn/Article/details/gtlnbgmcdf.html

[U103] JS：定时器
来源：http://dali.daria6918.cn/Article/details/gtgefyemyy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ivvv.top/Article/details/gtoyglbtxw.html

[U104] JS：防抖
来源：http://dali.wangshuangyany.cn/Article/details/gtkhpdrtpk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtocztxuiy.html

[U105] JS：节流
来源：http://dali.hnxiangtu.top/Article/details/gtxlrtqmuy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxuanxn.top/Article/details/gtwiuucklo.html

[U106] JS：日期格式化
来源：http://dali.sxryk.cn/Article/details/gtuxifuxhn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jianghu66.top/Article/details/gtsmirouyv.html

[U107] JS：数字千分位
来源：http://dali.hnqzz.top/Article/details/gtacwyblkp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.meibo888.top/Article/details/gtrqcbduaw.html

[U108] JS：随机整数
来源：http://dali.hysaishi.cn/Article/details/gthqafrrdl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinghuilouyu.cn/Article/details/gtrookkowr.html

[U109] JS：数组分组
来源：http://dali.zdqjudy.top/Article/details/gtjmdjfwzc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gtmldtrkow.html

[U110] JS：数组分块
来源：http://dali.pycfn.com/Article/details/gtmrikswxe.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nwbrower.top/Article/details/gtqkputeql.html

[U111] JS：对象转 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqnclels.html

new Map(Object.entries(obj))
来源：http://dali.snrcjt.cn/Article/details/gtmcddrmtt.html

[U112] JS：字符串补位
来源：http://dali.zhiwuduotai.top/Article/details/gttugvjsnx.html

"7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtvoifgxza.html

[U113] JS：正则替换全部
来源：http://dali.yuanzhike.top/Article/details/gtofyaozoo.html

s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtpywfcudi.html

[U114] JS：JSON 深比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxspiprx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvlpwebp.html

[U115] JS：生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtoaqtmbmk.html

crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtjxeedrvq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hywenlv.cn/Article/details/gtmkumstle.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sweek.top/Article/details/gtqczjexcd.html

[U117] JS：单元测试
来源：http://dali.zhoulong.xyz/Article/details/gtvhrvjjpy.html

npm i -D vitest;  npx vitest
来源：http://dali.haohaochexian.top/Article/details/gtzwmevnfg.html

[U118] JS：开发服务器
来源：http://dali.xinyue.icu/Article/details/gtmptokrzi.html

npm i -D vite;  npx vite
来源：http://dali.redwolf501.top/Article/details/gtbjbpgksg.html

[U119] JS：生产构建
来源：http://dali.snrcjt.cn/Article/details/gthnytrzdr.html

npx vite build
来源：http://dali.aibaodan.cn/Article/details/gteogsyejw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sweek.top/Article/details/gtzyslcixk.html

import.meta.env.VITE_API_URL
来源：http://dali.tian-w.cn/Article/details/gtkuqgkpwd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtizetwaaw.html

统计汇总
来源：http://dali.hongshengwenyu.top/Article/details/gtyfztpeki.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkzvojpb.html

按语言统计（条）：
来源：http://dali.yueranfly.top/Article/details/gthaayznif.html

Python ......... 252
来源：http://dali.hysaishi.cn/Article/details/gtpozwwwlp.html

PHP ............ 252
来源：http://dali.chenlongwang.top/Article/details/gtsgslxvcc.html

JavaScript ..... 252
来源：http://dali.guannengcc.top/Article/details/gtftiszzvf.html

TypeScript ..... 212
来源：http://dali.mhx1999.top/Article/details/gtugbvclyc.html

Java ........... 212
来源：http://dali.sweek.top/Article/details/gtjorrzjjd.html

Go ............. 212
来源：http://dali.wangdashe.top/Article/details/gtufemnazc.html

Ruby ........... 212
来源：http://dali.zhengqikj.top/Article/details/gtulwqzlfx.html

C# ............. 212
来源：http://dali.0kj1m.cn/Article/details/gtugexbfit.html

C .............. 30
来源：http://dali.meibo888.top/Article/details/gthkrtjfuq.html

C++ ............ 30
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufvpcxvc.html

SQL ............ 90
来源：http://dali.ywan-chungtsiang.top/Article/details/gtingopskl.html

Bash ........... 80
来源：http://dali.haohaochexian.top/Article/details/gtutckcmdv.html

Kotlin ......... 15
来源：http://dali.dashuyun.cn/Article/details/gtafdqjiib.html

Swift .......... 15
来源：http://dali.0kj1m.cn/Article/details/gtvbfirlss.html

Lua ............ 10
来源：http://dali.ehwqpu.com/Article/details/gtvnmvthll.html

Perl ........... 10
来源：http://dali.zhengqikj.top/Article/details/gtzvqezlxg.html

Scala .......... 10
来源：http://dali.nanxuanxn.top/Article/details/gtljoswblg.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gttqevawbo.html

合计 ........... 2106 条
来源：http://dali.zhengqikj.top/Article/details/gtjezfrknb.html

按章节统计：
来源：http://dali.havefunace.top/Article/details/gtqmrhwjbl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gtthozpiwx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gtxggledrn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gtbhnwrcff.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj20258888.top/Article/details/gtlrfaqxhd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zycfv.cn/Article/details/gtlaiptfrr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtxiyotakf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gtmidnedeq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzytqzgf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtgxpykjpr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gthpblkzui.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtiiupvtav.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtgfwulyty.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtjidrfifi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gteotxjksj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.svipenyu.cn/Article/details/gtmuzbmkcc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtnunboisl.html

Q SQL 专题                              90
来源：http://dali.xylfe.cn/Article/details/gtvcfqtigy.html

R Bash 专题                             80
来源：http://dali.nwbrower.top/Article/details/gtsquyzfpe.html

S C / C++ 专题                          60
来源：http://dali.tanke756.top/Article/details/gtltozqzdj.html

T 其他语言补充                          60
来源：http://dali.jinqigfzy.top/Article/details/gtnbuzbvbq.html

U 高频实用片段                         120
来源：http://dali.guowangkeji.top/Article/details/gteccwbisx.html

------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtfuwrplet.html

合计                                  2106 条
来源：http://dali.cucudq.cn/Article/details/gtnxnihezc.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqeqifhxp.html

使用提醒
来源：http://dali.gogol.net.cn/Article/details/gtdgoopdec.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtthnyidek.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tanke756.top/Article/details/gtfbgfgylr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yvedp.cn/Article/details/gtlhpcfbzo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hfpthk.cn/Article/details/gtybautirv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jyoumei.cn/Article/details/gthujdekhf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sufxvd.cn/Article/details/gtyuertewa.html

—— 文件结束 ——
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgrndsup.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmtcyknsz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258888.top/Article/details/gtanucinnx.html

Common Programming Examples Cheat Book
来源：http://dali.vqdsnc.cn/Article/details/gtxvmjwtsx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpjbsuqph.html

【收录内容】
来源：http://dali.yangfankeji.com/Article/details/gtgrxyyelt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtickkcqvj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gtdikwrszn.html

SQL · Bash · C · C++
来源：http://dali.feifeiyinyue.top/Article/details/gthxnrqzyt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sxryk.cn/Article/details/gtqbtzswft.html

【使用说明】
来源：http://dali.9152youxi.cn/Article/details/gtljhusrsc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangtech.top/Article/details/gtohyprqrr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xylfe.cn/Article/details/gtwrtjnxro.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj20258.top/Article/details/gtrlssutcz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.iojbl.cn/Article/details/gtatgtbyqk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj20258.top/Article/details/gtnruidxoc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgtnnnxe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cheryme.top/Article/details/gtmmlmlnih.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sysykeji.top/Article/details/gtfzwnshvb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj20258.top/Article/details/gtuhiqvtrm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhongyouzk.top/Article/details/gtldfdlsnm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.wangdashe.top/Article/details/gtcozwlqip.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.quarkkingdee.top/Article/details/gttrwkabex.html

【文件统计】
来源：http://dali.daxiang520.top/Article/details/gtipsjxlku.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guannengcc.top/Article/details/gtfunkarnd.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtxpdzdcyd.html

目  录
来源：http://dali.xinyue.icu/Article/details/gtlzcnulfa.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtkmichibq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xziqi.cn/Article/details/gteedyjmrr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gthuhqxmjx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtmqedvpal.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstevctbd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daria6918.cn/Article/details/gtmfgtjtqj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuxming.cn/Article/details/gtpxilujsc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gtsjjwggly.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sysykeji.top/Article/details/gtxzjrgiwj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtccgvzpin.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtkbtfyntk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtzyzmzchq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtcpwypjtt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gtconhvqcn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gtefmlaoog.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jlsjyb.cn/Article/details/gtlojumcnq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtpykwjbjp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.fengsongda.top/Article/details/gtadzgvddt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yuxming.cn/Article/details/gtafdtdzjp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlncslsho.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtkusbrhxg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gtzdvwfqxy.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtaczjankh.html

A. 基础语法与类型
来源：http://dali.pengpengdd.cyou/Article/details/gtusgjkvtj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtcrxjldls.html

[A01] Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtfumzjykm.html

Py:   print("Hello, World!")
来源：http://dali.fzhhl.top/Article/details/gtacowwhdp.html

PHP:  echo "Hello, World!";
来源：http://dali.shangyingyoupin.top/Article/details/gtfvkjhmnj.html

JS:   console.log("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gtekrphdkx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.nanxuanxn.top/Article/details/gtfzyaoyrv.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthusypdyp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangtech.top/Article/details/gthktluhhv.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgufenzy.top/Article/details/gtielykcql.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gtzczecmfp.html

[A02] 变量声明与赋值
来源：http://dali.shangyingyoupin.top/Article/details/gtqswyqmxw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yangfankeji.com/Article/details/gtkzilpcxq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.smart0.xyz/Article/details/gtllqsuzsw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtgtauoqah.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuanzx.com/Article/details/gtmrzkjzbe.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtqtrxpybd.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhixingplan.top/Article/details/gtkgwmoati.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenjidiqi.icu/Article/details/gtvvpvjuob.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gtjaepfzpk.html

[A03] 常量定义
来源：http://dali.dianchejie.cn/Article/details/gthkcqbujb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gtqjvtdbos.html

PHP:  const PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtxfwbexig.html

JS:   const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtzsdhjedq.html

TS:   const PI: number = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtmquhlctp.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtgrqpjdna.html

Go:   const PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gtkieziqzb.html

Ruby: PI = 3.14159
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvcqjnne.html

C#:   const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtlhjertcw.html

[A04] 判断变量类型
来源：http://dali.guowangkeji.top/Article/details/gtfqcurzsv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangdashe.top/Article/details/gtsbpsonfp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ybcxt.top/Article/details/gtbegaydjr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.wangdashe.top/Article/details/gttpgxoqgz.html

TS:   typeof x; x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gtxjfeljbk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfkpvdxs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinqigufen.top/Article/details/gtmhzpwoda.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.fzhhl.top/Article/details/gtemfslzsa.html

C#:   x.GetType().Name; x is int
来源：http://dali.zycfv.cn/Article/details/gtkkxwdjhk.html

[A05] 整数除法与取模
来源：http://dali.nwbrower.top/Article/details/gtjsusurck.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gtwpuwdygs.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gteoqyjthi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtprwvotsk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtthtfvmni.html

Java: 7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gtqfsbksnl.html

Go:   7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtoopaurso.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gttonupwwf.html

C#:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtuezfylyz.html

[A06] 字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gtsbtufusg.html

Py:   int("42"); float("3.14")
来源：http://dali.bjfxy.top/Article/details/gtxzrslgut.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.pengpengdd.cyou/Article/details/gtngftugyu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj20258.top/Article/details/gtikwyezzo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gtyjokxowf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xylfe.cn/Article/details/gtzvtyoflz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sxryk.cn/Article/details/gtwwmefppg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sufxvd.cn/Article/details/gtxktsrdyf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gtgvuyljur.html

[A07] 数字转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtqhtmjvbt.html

Py:   str(42)
来源：http://dali.yangfankeji.com/Article/details/gtnezwlaso.html

PHP:  (string) 42; strval(42)
来源：http://dali.smart0.xyz/Article/details/gtcpbsqicr.html

JS:   String(42); (42).toString()
来源：http://dali.pycfn.com/Article/details/gtopcxdkwk.html

TS:   String(42)
来源：http://dali.jyoumei.cn/Article/details/gtxfjsafqk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtrusfzeqn.html

Go:   strconv.Itoa(42)
来源：http://dali.chenlongwang.top/Article/details/gtmeddsxwz.html

Ruby: 42.to_s
来源：http://dali.zhoulong.xyz/Article/details/gtlhrlfnbd.html

C#:   42.ToString()
来源：http://dali.zhengqikj.top/Article/details/gtodslzyij.html

[A08] 取整与四舍五入
来源：http://dali.shuidangran.top/Article/details/gtahwvwoht.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gtcknpeswn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yanxiufei.cn/Article/details/gttdbulkpb.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gtxkeykmls.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangdashe.top/Article/details/gtrdrodobu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gtyypgmgnr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtbdvvhikx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdevxpakb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gtdhgjnqdv.html

[A09] 绝对值与最大最小值
来源：http://dali.c1oappe.top/Article/details/gtnpesvlvc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtrtomaema.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtnzwiudhd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtdlahhnlr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtolytbsss.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtmddlribi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.havefunace.top/Article/details/gtzcpfsofp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cheryme.top/Article/details/gtncwkfhmo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gthbmshpdz.html

[A10] 生成随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdunstlv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.aizwys.cn/Article/details/gtdcfdwcww.html

PHP:  random_int(1, 100);
来源：http://dali.gzhubu.top/Article/details/gtzcagynlm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.bjfxy.top/Article/details/gtvymklbpu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gzhubu.top/Article/details/gttqwrfusv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.tanke756.top/Article/details/gtuzwcprul.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.guowangkeji.top/Article/details/gtwphxwpek.html

Ruby: rand(1..100)
来源：http://dali.feifeiyinyue.top/Article/details/gthalaecbm.html

C#:   new Random().Next(1, 101)
来源：http://dali.vqdsnc.cn/Article/details/gtmhtlsqxq.html

[A11] 条件表达式（三元）
来源：http://dali.haohaochexian.top/Article/details/gtiydkcgww.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gtjiwvsrig.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtprihirzw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtybbeegvz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gtfnekmwuo.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtwqrfexpt.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ydzc1.top/Article/details/gthkitzcif.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtlfkqqhzh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gtliofkuvs.html

[A12] 字符串插值 / 格式化
来源：http://dali.guowangkeji.top/Article/details/gtrksitrdq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.sysykeji.top/Article/details/gtrmotnicz.html


<!-- 参考信息 -->