代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpqtjdaz.html

composer require psr/container
来源：http://dali.andypj.xyz/Article/details/gtdsogjaen.html

[U76] PHP：简单路由
来源：http://dali.cucudq.cn/Article/details/gtqmbuovsx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yanxiufei.cn/Article/details/gtdzkrfsmk.html

[U77] PHP：模板渲染
来源：http://dali.chenlongwang.top/Article/details/gtjmabthhu.html

composer require twig/twig
来源：http://dali.xylfe.cn/Article/details/gttpxcdoss.html

[U78] PHP：单元测试
来源：http://dali.xziqi.cn/Article/details/gtexgusfpe.html

composer require --dev phpunit/phpunit
来源：http://dali.yuanzhike.top/Article/details/gtsapgweqc.html

[U79] PHP：静态分析
来源：http://dali.cdnleiting.top/Article/details/gtuzhwwfqr.html

composer require --dev phpstan/phpstan
来源：http://dali.xinyue.icu/Article/details/gtgenrdrmr.html

[U80] PHP：代码规范修复
来源：http://dali.sxryk.cn/Article/details/gtlrfvysef.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yanxiufei.cn/Article/details/gtikixyjyv.html

[U81] JS：初始化项目
来源：http://dali.sysykeji.top/Article/details/gtwjukrbzo.html

npm init -y;  npm i express
来源：http://dali.yj202588.top/Article/details/gtonekdtfn.html

[U82] JS：package.json 脚本
来源：http://dali.andypj.xyz/Article/details/gtjbogmxjo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guowangkeji.top/Article/details/gtubakiwhu.html

[U83] JS：ES Module 导入导出
来源：http://dali.xuetiantiany.cn/Article/details/gtxgjjqzfy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yuanzhike.top/Article/details/gttzpvypun.html

[U84] JS：CommonJS 写法
来源：http://dali.sysykeji.top/Article/details/gtcnlirzdn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenlongwang.top/Article/details/gtntbcwqon.html

[U85] JS：可选链
来源：http://dali.zhengqikj.top/Article/details/gtakzuxyks.html

a?.b?.c
来源：http://dali.guowangkeji.top/Article/details/gttwakzyit.html

[U86] JS：空值合并
来源：http://dali.yanxiufei.cn/Article/details/gtpzipxmtz.html

a ?? b
来源：http://dali.hywenlv.cn/Article/details/gtekrygszr.html

[U87] JS：解构默认值
来源：http://dali.cdnleiting.top/Article/details/gterrelmkb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj202588.top/Article/details/gtwxmohhsq.html

[U88] JS：对象展开合并
来源：http://dali.tianlin.xyz/Article/details/gtcnvxwepa.html

{ ...a, ...b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztwpcfoz.html

[U89] JS：数组去重
来源：http://dali.pengpengdd.cyou/Article/details/gtbdigpnhf.html

[...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtokjcvdac.html

[U90] JS：数字数组排序
来源：http://dali.sweek.top/Article/details/gtpagymdvm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtbzcqglmb.html

[U91] JS：对象键值遍历
来源：http://dali.fzhhl.top/Article/details/gtszwnpcuq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sweek.top/Article/details/gtmgxetxny.html

[U92] JS：深拷贝
来源：http://dali.bjfxy.top/Article/details/gtgoqhkvnm.html

structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtsovfloal.html

[U93] JS：模板字符串
来源：http://dali.0kj1m.cn/Article/details/gthflgwcxq.html

`共 ${n} 条`
来源：http://dali.tanke756.top/Article/details/gtbbbquxhk.html

[U94] JS：箭头函数
来源：http://dali.jinqigufen.top/Article/details/gtiqwrzqdc.html

const double = x => x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtjijuojot.html

[U95] JS：Promise 包装
来源：http://dali.yongpay.top/Article/details/gttgsszmrz.html

new Promise((resolve, reject) => {})
来源：http://dali.jyoumei.cn/Article/details/gtzfhhobaz.html

[U96] JS：async/await 与异常
来源：http://dali.sweek.top/Article/details/gtngpsyoze.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdplxbrp.html

[U97] JS：并发请求
来源：http://dali.xuetiantiany.cn/Article/details/gtglanpqki.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtwpvolnki.html

[U98] JS：fetch 带 JSON
来源：http://dali.xylfe.cn/Article/details/gtkewgwcgc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dianchejie.cn/Article/details/gtjtogmtem.html

[U99] JS：事件监听
来源：http://dali.vqdsnc.cn/Article/details/gtmqsnoyxf.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigfzy.top/Article/details/gtjtpcjqnd.html

[U100] JS：DOM 查询
来源：http://dali.dashuyun.cn/Article/details/gtqiznmoqt.html

document.querySelector(".item")
来源：http://dali.hysaishi.cn/Article/details/gtyalftqpe.html

[U101] JS：classList 操作
来源：http://dali.zdqjudy.top/Article/details/gtubjqdvyz.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gtxjzxikir.html

[U102] JS：本地存储
来源：http://dali.meibo888.top/Article/details/gtiujrhqeo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shangyingyoupin.top/Article/details/gtirtmeynx.html

[U103] JS：定时器
来源：http://dali.hnxiangtu.top/Article/details/gtkjjkfclw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pengpengdd.cyou/Article/details/gtomlegupk.html

[U104] JS：防抖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjezxqmw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtgwdmtgnl.html

[U105] JS：节流
来源：http://dali.guannengcc.top/Article/details/gtzmjzbxxs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yvedp.cn/Article/details/gtaxdhuzxu.html

[U106] JS：日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtcccvkuez.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gtiibbpxnn.html

[U107] JS：数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gtyzlogoez.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gtulhoarpp.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gtgcjvneme.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xziqi.cn/Article/details/gtaeydfoel.html

[U109] JS：数组分组
来源：http://dali.zhoulong.xyz/Article/details/gtcflosbgz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtgkvexenb.html

[U110] JS：数组分块
来源：http://dali.yj20258.top/Article/details/gtvfaqmcqh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hysaishi.cn/Article/details/gtnffkeaae.html

[U111] JS：对象转 Map
来源：http://dali.shuidangran.top/Article/details/gtbowcmjdy.html

new Map(Object.entries(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gtzxbrzbvj.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gtyojpbqip.html

"7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtkpcofnrj.html

[U113] JS：正则替换全部
来源：http://dali.yj20258.top/Article/details/gtgzbzsqyp.html

s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtaltkcevs.html

[U114] JS：JSON 深比较
来源：http://dali.gaohongyu789.top/Article/details/gtxqbnbsex.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtdagtubnk.html

[U115] JS：生成 UUID
来源：http://dali.xuanzx.com/Article/details/gtusunixjz.html

crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtdejbacci.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tanke756.top/Article/details/gtlhfvleml.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hammf.cn/Article/details/gtdrjxsqje.html

[U117] JS：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtruvcyuox.html

npm i -D vitest;  npx vitest
来源：http://dali.shzxlz.cn/Article/details/gtglcfbqdk.html

[U118] JS：开发服务器
来源：http://dali.jlsjyb.cn/Article/details/gtmgkucdys.html

npm i -D vite;  npx vite
来源：http://dali.yj202588.top/Article/details/gtnmzrajod.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gtchdinrie.html

npx vite build
来源：http://dali.guannengcc.top/Article/details/gtfevmqmrp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.9152youxi.cn/Article/details/gtopktcxhp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhengqikj.top/Article/details/gtkatvxyru.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpyuyjhfy.html

统计汇总
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnjldbop.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtumnrvfov.html

按语言统计（条）：
来源：http://dali.quarkkingdee.top/Article/details/gtrbfpzlen.html

Python ......... 252
来源：http://dali.yangfankeji.com/Article/details/gtcealcfjr.html

PHP ............ 252
来源：http://dali.cheryme.top/Article/details/gtaukhzmoo.html

JavaScript ..... 252
来源：http://dali.gogol.net.cn/Article/details/gtdmxkwdgw.html

TypeScript ..... 212
来源：http://dali.nwbrower.top/Article/details/gtczjvaoen.html

Java ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnxzjajh.html

Go ............. 212
来源：http://dali.andypj.xyz/Article/details/gtckewraxl.html

Ruby ........... 212
来源：http://dali.daxiang520.top/Article/details/gtehdhjazs.html

C# ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gtlreauvgw.html

C .............. 30
来源：http://dali.xinyue.icu/Article/details/gtqsaqrhrt.html

C++ ............ 30
来源：http://dali.dianchejie.cn/Article/details/gtyqcqydxq.html

SQL ............ 90
来源：http://dali.tanke756.top/Article/details/gtfojfmtgs.html

Bash ........... 80
来源：http://dali.aibaodan.cn/Article/details/gtrhbitacq.html

Kotlin ......... 15
来源：http://dali.yuxming.cn/Article/details/gtmimllfux.html

Swift .......... 15
来源：http://dali.jlsjyb.cn/Article/details/gtelblwzwb.html

Lua ............ 10
来源：http://dali.nanxuanxn.top/Article/details/gtkvszoyhy.html

Perl ........... 10
来源：http://dali.feifeiyinyue.top/Article/details/gtkveqsinc.html

Scala .......... 10
来源：http://dali.hfpthk.cn/Article/details/gtpqkfzqef.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtuuadzybk.html

合计 ........... 2106 条
来源：http://dali.bjfxy.top/Article/details/gtefbxntjc.html

按章节统计：
来源：http://dali.jqgufenzy.top/Article/details/gtmcdvpbhc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.pycfn.com/Article/details/gtqkaqcohb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtssscjmme.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gtrshhnduz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gtqpkdlcsi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cashguo.top/Article/details/gtwwoxfvdk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gtpirpzljo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gtlsbsetko.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtjyijekur.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtedovkbyd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xziqi.cn/Article/details/gtvglqbxxk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtpmscurgw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtdriubaqn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gthmptexxa.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jlsjyb.cn/Article/details/gtbtukwupj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jiagoushi.top/Article/details/gtbrtpnlqo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtzzkaranx.html

Q SQL 专题                              90
来源：http://dali.yueranfly.top/Article/details/gtctqerkmt.html

R Bash 专题                             80
来源：http://dali.chenzaomai.com/Article/details/gtqgiaslrn.html

S C / C++ 专题                          60
来源：http://dali.gogol.net.cn/Article/details/gtwpnwuhca.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvozgkuix.html

U 高频实用片段                         120
来源：http://dali.smart0.xyz/Article/details/gtfkjgzsyl.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gtmmcdsukn.html

合计                                  2106 条
来源：http://dali.pycfn.com/Article/details/gtbicbrpff.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtnbygetba.html

使用提醒
来源：http://dali.havefunace.top/Article/details/gtnyrplqos.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtdlfnmqve.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyjmrrrq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjtpwktm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.fzhhl.top/Article/details/gttzocbnyn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yangfankeji.com/Article/details/gtlbarbxly.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.quarkkingdee.top/Article/details/gtvskzepjz.html

—— 文件结束 ——
来源：http://dali.hammf.cn/Article/details/gtuoolnbpz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtercbrpmy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gtfihbyjdc.html

Common Programming Examples Cheat Book
来源：http://dali.zhoulong.xyz/Article/details/gtpmnetkly.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpplzbypf.html

【收录内容】
来源：http://dali.kuanghao11.cn/Article/details/gtsfstusyu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yvedp.cn/Article/details/gtfkrecyec.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhiwuduotai.top/Article/details/gtkxcudkyr.html

SQL · Bash · C · C++
来源：http://dali.jianghu66.top/Article/details/gtdpwqxsdn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shzxlz.cn/Article/details/gtuuuzigtw.html

【使用说明】
来源：http://dali.gogol.net.cn/Article/details/gtibxvixti.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.snrcjt.cn/Article/details/gtcnjmcrkx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yongpay.top/Article/details/gtcggxvsss.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.9152youxi.cn/Article/details/gtvjyabvnt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenzaomai.com/Article/details/gthybregna.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cqqwz.cn/Article/details/gtropqwqwa.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gzhubu.top/Article/details/gtgcqohkxq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yuxming.cn/Article/details/gtqymkwchv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.0kj1m.cn/Article/details/gtsqqqdryg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yanxiufei.cn/Article/details/gthtchpbsa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yanxiufei.cn/Article/details/gtqsltrxyw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.redwolf501.top/Article/details/gthekfoqoz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cdnleiting.top/Article/details/gtytmrqbof.html

【文件统计】
来源：http://dali.shanyushiyangtech.top/Article/details/gthuphjyfu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shanyushiyangtech.top/Article/details/gtipsmenqr.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtqhopafec.html

目  录
来源：http://dali.shangyingyoupin.top/Article/details/gtqayfdvdp.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtlgtlztgt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gtudgmfupb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqlkraiy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jlsjyb.cn/Article/details/gtdnowkiqf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gtxkecjxsk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbmhcxlz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gaohongyu789.top/Article/details/gtfzmuolxj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtvbhiywig.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gtvruriivt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtqauhjunf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hammf.cn/Article/details/gtloghbwcu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gthlanpcku.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gtgzsrpieg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtcugewjza.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhoulong.xyz/Article/details/gtkqzpukfx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cqqwz.cn/Article/details/gtursojjyz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtzdcdmeas.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.aibaodan.cn/Article/details/gtbmmltzit.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtpgjbovuo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hysaishi.cn/Article/details/gtyixmhgrb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gtkcasepfn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gtfbylufsn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthvyyrcty.html

A. 基础语法与类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdztilhjl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtcvdtkqpy.html

[A01] Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfxjgwjq.html

Py:   print("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gtmebrpnws.html

PHP:  echo "Hello, World!";
来源：http://dali.shzxlz.cn/Article/details/gtjybwnjip.html

JS:   console.log("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gtsuvirvpo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ivvv.top/Article/details/gtrpnpvhry.html

Java: System.out.println("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gtglwikiab.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangtech.top/Article/details/gtoajomuzq.html

Ruby: puts "Hello, World!"
来源：http://dali.c1oappe.top/Article/details/gtkkqeoflr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gtxwsevojs.html

[A02] 变量声明与赋值
来源：http://dali.guannengcc.top/Article/details/gtxchcbdgc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gaohongyu789.top/Article/details/gtllqmdlnq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.fzhhl.top/Article/details/gtsgdyvbyu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cucudq.cn/Article/details/gtireqnztr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gthfaidzvk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtqyqtwmoc.html

Go:   name := "Alex"; age := 20
来源：http://dali.gaohongyu789.top/Article/details/gtqrkravyn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tanke756.top/Article/details/gtrivvzvqn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gthbdvksph.html

[A03] 常量定义
来源：http://dali.yangfankeji.com/Article/details/gtwacmuutk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yangfankeji.com/Article/details/gttkakrgta.html

PHP:  const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gttzwpgphr.html

JS:   const PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtmjhbjwcn.html

TS:   const PI: number = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtrzyyjfpc.html

Java: static final double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtzmvvodrz.html

Go:   const PI = 3.14159
来源：http://dali.yueranfly.top/Article/details/gtqngpgmpj.html

Ruby: PI = 3.14159
来源：http://dali.nanxuanxn.top/Article/details/gtalzkttnt.html

C#:   const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gthgeftvil.html

[A04] 判断变量类型
来源：http://dali.yongpay.top/Article/details/gtnycletsj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokcrwgki.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.andypj.xyz/Article/details/gtkukpnimh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.dianchejie.cn/Article/details/gtiesbittj.html

TS:   typeof x; x instanceof Date
来源：http://dali.gotoacloud.top/Article/details/gtgmqllujo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.chenlongwang.top/Article/details/gtaneqkmip.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnxiangtu.top/Article/details/gtayrruvow.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.wangshuangyany.cn/Article/details/gtnfctshwg.html

C#:   x.GetType().Name; x is int
来源：http://dali.wangdashe.top/Article/details/gtmwqbfzqi.html

[A05] 整数除法与取模
来源：http://dali.bjfxy.top/Article/details/gthbquyqaq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.meibo888.top/Article/details/gtueuoylpu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtxhfkeihp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtjqsjicdq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gtyolkhueu.html

Java: 7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtziftqwid.html

Go:   7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gtonmepbgz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gttwnqzein.html

C#:   7 / 2; 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtowjvnltf.html

[A06] 字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtwxhgfjtz.html

Py:   int("42"); float("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gtykvzyhkd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cdnleiting.top/Article/details/gtbzjqsyls.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenjidiqi.icu/Article/details/gtdniogkvc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cucudq.cn/Article/details/gtntjtrcbk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.9152youxi.cn/Article/details/gtvolachgx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinqigufen.top/Article/details/gtsuirtjhe.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.mhx1999.top/Article/details/gtkvregrrt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqnidvqm.html

[A07] 数字转字符串
来源：http://dali.guowangkeji.top/Article/details/gtodhgqysf.html

Py:   str(42)
来源：http://dali.chenlongwang.top/Article/details/gtcjmzsjro.html

PHP:  (string) 42; strval(42)
来源：http://dali.jlsjyb.cn/Article/details/gtgpqiuxgk.html

JS:   String(42); (42).toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuhvnrmc.html

TS:   String(42)
来源：http://dali.chenjidiqi.icu/Article/details/gtiakqktog.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xinyue.icu/Article/details/gtjvkjrpfw.html

Go:   strconv.Itoa(42)
来源：http://dali.sysykeji.top/Article/details/gtbiuevqun.html

Ruby: 42.to_s
来源：http://dali.ybcxt.top/Article/details/gtilvwilai.html

C#:   42.ToString()
来源：http://dali.dashuyun.cn/Article/details/gtfgvfcyne.html

[A08] 取整与四舍五入
来源：http://dali.redwolf501.top/Article/details/gtrizwedmo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gtekzcvzby.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jiagoushi.top/Article/details/gtdeqlomja.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtzfplzjln.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hysaishi.cn/Article/details/gtnyoqlhfp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtiauihelq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtrupmsbrz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.pycfn.com/Article/details/gtqcnjodcq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gtpqdsxxej.html

[A09] 绝对值与最大最小值
来源：http://dali.guannengcc.top/Article/details/gtxrwbsrav.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtzrtaadrr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtkgedqled.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cashguo.top/Article/details/gtdhycaboo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtythnjljk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.birdmap.top/Article/details/gtikjompfq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.tanke756.top/Article/details/gtjzlvxcmg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.fzhhl.top/Article/details/gtaarehtmx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtfyaggvzm.html

[A10] 生成随机数
来源：http://dali.zhixingplan.top/Article/details/gtipamekae.html

Py:   import random; random.randint(1, 100)
来源：http://dali.pengpengdd.cyou/Article/details/gtdqgbvuht.html

PHP:  random_int(1, 100);
来源：http://dali.hnqzz.top/Article/details/gtcnjmwriv.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aibaodan.cn/Article/details/gtittybwop.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aibaodan.cn/Article/details/gtsutqqamq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.fengsongda.top/Article/details/gtcuxiaqxa.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.iojbl.cn/Article/details/gtqzyipopt.html

Ruby: rand(1..100)
来源：http://dali.kuanghao11.cn/Article/details/gthuvhysoh.html

C#:   new Random().Next(1, 101)
来源：http://dali.quarkkingdee.top/Article/details/gtgnenkfrx.html

[A11] 条件表达式（三元）
来源：http://dali.haohaochexian.top/Article/details/gtbvkgfnxc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cashguo.top/Article/details/gtqakfhdrs.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtgblydefq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtqlsiciwx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtmpsoezxm.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtnwlwksay.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.redwolf501.top/Article/details/gtzwhtcbzr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtmlfaxzte.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gtppsiyqpm.html

[A12] 字符串插值 / 格式化
来源：http://dali.hywenlv.cn/Article/details/gtxpesbkqt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.pengpengdd.cyou/Article/details/gtsjpiznis.html


<!-- 参考信息 -->