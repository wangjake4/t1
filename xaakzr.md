代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.chenlongwang.top/Article/details/gtjwvarrsg.html

composer require psr/container
来源：http://dali.redwolf501.top/Article/details/gtmofpjeqp.html

[U76] PHP：简单路由
来源：http://dali.andypj.xyz/Article/details/gtcvucjspe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xuanzx.com/Article/details/gtttaftlbu.html

[U77] PHP：模板渲染
来源：http://dali.cashguo.top/Article/details/gtlcwnoghz.html

composer require twig/twig
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrybioqj.html

[U78] PHP：单元测试
来源：http://dali.hnqzz.top/Article/details/gtyifoqsfq.html

composer require --dev phpunit/phpunit
来源：http://dali.hnqzz.top/Article/details/gtftnkozic.html

[U79] PHP：静态分析
来源：http://dali.kuanghao11.cn/Article/details/gtlryqdglu.html

composer require --dev phpstan/phpstan
来源：http://dali.hywenlv.cn/Article/details/gtycclcxgh.html

[U80] PHP：代码规范修复
来源：http://dali.daria6918.cn/Article/details/gtifmrrtps.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hywenlv.cn/Article/details/gtyfmhxxgi.html

[U81] JS：初始化项目
来源：http://dali.guowangkeji.top/Article/details/gtddtbeosq.html

npm init -y;  npm i express
来源：http://dali.cucudq.cn/Article/details/gtcifrqzpa.html

[U82] JS：package.json 脚本
来源：http://dali.tianlin.xyz/Article/details/gtskhpheie.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xuetiantiany.cn/Article/details/gtrakqdkbw.html

[U83] JS：ES Module 导入导出
来源：http://dali.aibaodan.cn/Article/details/gtrsonskxm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtguzqydcf.html

[U84] JS：CommonJS 写法
来源：http://dali.tanke756.top/Article/details/gtkddpadzu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.9152youxi.cn/Article/details/gthzaswcbs.html

[U85] JS：可选链
来源：http://dali.yvedp.cn/Article/details/gtadhlqpdd.html

a?.b?.c
来源：http://dali.tianlin.xyz/Article/details/gtjxrgmopf.html

[U86] JS：空值合并
来源：http://dali.jianghu66.top/Article/details/gtrzxbaibk.html

a ?? b
来源：http://dali.cqqwz.cn/Article/details/gtnaqxvkuj.html

[U87] JS：解构默认值
来源：http://dali.gaohongyu789.top/Article/details/gtmfhzawix.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgfzy.top/Article/details/gtfsfuoxfu.html

[U88] JS：对象展开合并
来源：http://dali.0kj1m.cn/Article/details/gtqgaxyliu.html

{ ...a, ...b }
来源：http://dali.ybcxt.top/Article/details/gtkednbdsj.html

[U89] JS：数组去重
来源：http://dali.xuanzx.com/Article/details/gthvzopuby.html

[...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtofodpvwl.html

[U90] JS：数字数组排序
来源：http://dali.aizwys.cn/Article/details/gtvcijrogh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtohgpczfu.html

[U91] JS：对象键值遍历
来源：http://dali.cheryme.top/Article/details/gtdkmduhht.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258888.top/Article/details/gtnbzuhjee.html

[U92] JS：深拷贝
来源：http://dali.tian-w.cn/Article/details/gtomtuopen.html

structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtpilgajue.html

[U93] JS：模板字符串
来源：http://dali.zycfv.cn/Article/details/gtggsypduo.html

`共 ${n} 条`
来源：http://dali.daxiang520.top/Article/details/gttkuipxnl.html

[U94] JS：箭头函数
来源：http://dali.tian-w.cn/Article/details/gtlaskhiim.html

const double = x => x * 2;
来源：http://dali.snrcjt.cn/Article/details/gtkenmkvug.html

[U95] JS：Promise 包装
来源：http://dali.guowangkeji.top/Article/details/gtjhsmizjb.html

new Promise((resolve, reject) => {})
来源：http://dali.ivvv.top/Article/details/gttisltdol.html

[U96] JS：async/await 与异常
来源：http://dali.zhiwuduotai.top/Article/details/gtcdnfrxyp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwhreouuy.html

[U97] JS：并发请求
来源：http://dali.wangdashe.top/Article/details/gtqxnwbzar.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtryjpewdk.html

[U98] JS：fetch 带 JSON
来源：http://dali.xziqi.cn/Article/details/gtjpamwwvb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhixingplan.top/Article/details/gthomlwowl.html

[U99] JS：事件监听
来源：http://dali.shzxlz.cn/Article/details/gtqpxzsdnb.html

el.addEventListener("click", e => {})
来源：http://dali.yuxming.cn/Article/details/gtvspjiqer.html

[U100] JS：DOM 查询
来源：http://dali.hnxiangtu.top/Article/details/gtpdjruwky.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gtfzaoxzkc.html

[U101] JS：classList 操作
来源：http://dali.gaohongyu789.top/Article/details/gtqmzekbql.html

el.classList.toggle("active")
来源：http://dali.xuetiantiany.cn/Article/details/gtycfvzjwe.html

[U102] JS：本地存储
来源：http://dali.andypj.xyz/Article/details/gttexmcjak.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cqqwz.cn/Article/details/gtbwnsktyx.html

[U103] JS：定时器
来源：http://dali.zdqjudy.top/Article/details/gtezzuqmzz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenjidiqi.icu/Article/details/gtcpxgxldk.html

[U104] JS：防抖
来源：http://dali.zhiwuduotai.top/Article/details/gtkfavjlsw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtyorzrgit.html

[U105] JS：节流
来源：http://dali.sxryk.cn/Article/details/gttjjwsevt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hammf.cn/Article/details/gtxsbvxyoa.html

[U106] JS：日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtdcsmzrfi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jlsjyb.cn/Article/details/gtbwtovucn.html

[U107] JS：数字千分位
来源：http://dali.ivvv.top/Article/details/gtezitdtbh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.bjfxy.top/Article/details/gtbhvdawew.html

[U108] JS：随机整数
来源：http://dali.yanxiufei.cn/Article/details/gtapwzxgdp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fengsongda.top/Article/details/gtxnrtbhfy.html

[U109] JS：数组分组
来源：http://dali.svipenyu.cn/Article/details/gtcitqsimf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnxmgruz.html

[U110] JS：数组分块
来源：http://dali.yj202588.top/Article/details/gtvjfgdycg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.c1oappe.top/Article/details/gtxbpxzkpm.html

[U111] JS：对象转 Map
来源：http://dali.shangyingyoupin.top/Article/details/gtyzwygmyd.html

new Map(Object.entries(obj))
来源：http://dali.0kj1m.cn/Article/details/gtcohtbsgz.html

[U112] JS：字符串补位
来源：http://dali.hywenlv.cn/Article/details/gthhzlagre.html

"7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtyuicqofo.html

[U113] JS：正则替换全部
来源：http://dali.shzxlz.cn/Article/details/gtoxsmgnnw.html

s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtxmhhnkat.html

[U114] JS：JSON 深比较
来源：http://dali.vqdsnc.cn/Article/details/gtddhjipyx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtdnqaolzt.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtmwepzose.html

crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtmsckrwmj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.svipenyu.cn/Article/details/gtjbremgmn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nwbrower.top/Article/details/gtuypvylpr.html

[U117] JS：单元测试
来源：http://dali.sweek.top/Article/details/gtmotvvyit.html

npm i -D vitest;  npx vitest
来源：http://dali.smart0.xyz/Article/details/gtjeqvbszf.html

[U118] JS：开发服务器
来源：http://dali.xylfe.cn/Article/details/gtgpzkmrve.html

npm i -D vite;  npx vite
来源：http://dali.sufxvd.cn/Article/details/gtrfdpbqvz.html

[U119] JS：生产构建
来源：http://dali.chenzaomai.com/Article/details/gtdnxtoelf.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gtdeqrgieq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xinyue.icu/Article/details/gtlsyqcktj.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxinkj.top/Article/details/gtzfmwktka.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gteltbbunj.html

统计汇总
来源：http://dali.jqgufenzy.top/Article/details/gtoycoeqmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtapqbfzgb.html

按语言统计（条）：
来源：http://dali.sufxvd.cn/Article/details/gtkdstmeru.html

Python ......... 252
来源：http://dali.sxryk.cn/Article/details/gtqbasuzpv.html

PHP ............ 252
来源：http://dali.svipenyu.cn/Article/details/gtrtnwuiry.html

JavaScript ..... 252
来源：http://dali.dianchejie.cn/Article/details/gtajcqyrwg.html

TypeScript ..... 212
来源：http://dali.hfpthk.cn/Article/details/gtmyzfkpnb.html

Java ........... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccqieyyx.html

Go ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gtgxwlxfsp.html

Ruby ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtphwjdsbt.html

C# ............. 212
来源：http://dali.snrcjt.cn/Article/details/gtffhnhmnu.html

C .............. 30
来源：http://dali.hywenlv.cn/Article/details/gtqofbwltt.html

C++ ............ 30
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujmfbgvz.html

SQL ............ 90
来源：http://dali.gogol.net.cn/Article/details/gtazmmsehu.html

Bash ........... 80
来源：http://dali.zhengqikj.top/Article/details/gtfqtynawd.html

Kotlin ......... 15
来源：http://dali.ivvv.top/Article/details/gtjmtpswvm.html

Swift .......... 15
来源：http://dali.zhongyouzk.top/Article/details/gtoxdzblet.html

Lua ............ 10
来源：http://dali.xziqi.cn/Article/details/gtckjttakg.html

Perl ........... 10
来源：http://dali.chenlongwang.top/Article/details/gtajvjukuu.html

Scala .......... 10
来源：http://dali.yangfankeji.com/Article/details/gtugujhxob.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtsdvyvkcp.html

合计 ........... 2106 条
来源：http://dali.xylfe.cn/Article/details/gtiwwntqyh.html

按章节统计：
来源：http://dali.zdqjudy.top/Article/details/gtjttxikji.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gtyvpllotb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtadckawhu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hysaishi.cn/Article/details/gtlswbqvcg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gtotkrxhyd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinqigfzy.top/Article/details/gtnovpqccd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cashguo.top/Article/details/gtpwwowtgc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtpvfnvrrm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gttflrdqpu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gthiyuwhpq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhiwuduotai.top/Article/details/gtmptefmdp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtvtsyrwls.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtjbrxhnty.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtcsqjoutb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gtfuerclqc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xuanzx.com/Article/details/gtwactrwiv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtphhtdpym.html

Q SQL 专题                              90
来源：http://dali.ydzc1.top/Article/details/gtzuskmpqv.html

R Bash 专题                             80
来源：http://dali.jyoumei.cn/Article/details/gtmxhczswg.html

S C / C++ 专题                          60
来源：http://dali.svipenyu.cn/Article/details/gtchgvqtwc.html

T 其他语言补充                          60
来源：http://dali.dashuyun.cn/Article/details/gtyoxhxquc.html

U 高频实用片段                         120
来源：http://dali.smart0.xyz/Article/details/gtxypabijc.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gtdwqjtxnl.html

合计                                  2106 条
来源：http://dali.cqqwz.cn/Article/details/gtnmjukuah.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtiekravfy.html

使用提醒
来源：http://dali.gotoacloud.top/Article/details/gtefaovwfb.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtpfjnxghj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenjidiqi.icu/Article/details/gtsnjniexl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ivvv.top/Article/details/gtirenhneo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.birdmap.top/Article/details/gthpxfhvxu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yvedp.cn/Article/details/gtzlosbfnp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.mhx1999.top/Article/details/gtwnltvzti.html

—— 文件结束 ——
来源：http://dali.yuanzhike.top/Article/details/gtkvxfrtrq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtwxsrnqnp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ehwqpu.com/Article/details/gtfhemoalz.html

Common Programming Examples Cheat Book
来源：http://dali.zhiwuduotai.top/Article/details/gtqstvasvc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtognzssyo.html

【收录内容】
来源：http://dali.dianchejie.cn/Article/details/gtmqjcbmqg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizaoroiz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.havefunace.top/Article/details/gthlwaebde.html

SQL · Bash · C · C++
来源：http://dali.yanxiufei.cn/Article/details/gtwmyudatq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.haohaochexian.top/Article/details/gtukpjlsul.html

【使用说明】
来源：http://dali.guowangkeji.top/Article/details/gtqmvymfgp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuanzhike.top/Article/details/gtvqlyyrpn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqlnlhwy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jiagoushi.top/Article/details/gtqzpndsil.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhongyouzk.top/Article/details/gtbkpfxvfa.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigufen.top/Article/details/gtelktfgct.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gaohongyu789.top/Article/details/gteuedyubx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.smart0.xyz/Article/details/gtknvoiuxs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cdnleiting.top/Article/details/gtfttkbpcg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.andypj.xyz/Article/details/gtoawqajxa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xinyue.icu/Article/details/gtoamiyjen.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ivvv.top/Article/details/gtmssbquka.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hysaishi.cn/Article/details/gtrxtbhyjq.html

【文件统计】
来源：http://dali.iojbl.cn/Article/details/gtcmdiqzdd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gaohongyu789.top/Article/details/gtogmclwxi.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtdkfigmvm.html

目  录
来源：http://dali.shzxlz.cn/Article/details/gtyuwrpccw.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtkcifdcks.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gtkadpvwet.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gtghwototp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gtrbroxusn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gtbrqgpdli.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.mhx1999.top/Article/details/gthebeqmvt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gtoakzfkrb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gtjbgluiqp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmaejrpu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhqnaupg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gtnivxzloy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtmbyzotbh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtdfwnlcaa.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtddenobip.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jiagoushi.top/Article/details/gtqerfjxuu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cashguo.top/Article/details/gtfjbleoow.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtdhtwkrdj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtumwyzygk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.mhx1999.top/Article/details/gtjfxyduxj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnqzz.top/Article/details/gtyknjlnok.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtnemvumtq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.fengsongda.top/Article/details/gtdnayakqp.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdsfdlkiq.html

A. 基础语法与类型
来源：http://dali.zycfv.cn/Article/details/gtykbizlgy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtihfqgwou.html

[A01] Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcbuacfw.html

Py:   print("Hello, World!")
来源：http://dali.dianchejie.cn/Article/details/gtmzuzuffd.html

PHP:  echo "Hello, World!";
来源：http://dali.cucudq.cn/Article/details/gtjglhykwb.html

JS:   console.log("Hello, World!");
来源：http://dali.yueranfly.top/Article/details/gtiatwmzkg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.redwolf501.top/Article/details/gttvfjvvso.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gtqfcspvfr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ehwqpu.com/Article/details/gtzrpwscpi.html

Ruby: puts "Hello, World!"
来源：http://dali.iojbl.cn/Article/details/gtypdixoxz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gthhdpvtso.html

[A02] 变量声明与赋值
来源：http://dali.sufxvd.cn/Article/details/gtbwlfnnih.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gzhubu.top/Article/details/gtyylmxbdo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258.top/Article/details/gtzqtkahsc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.andypj.xyz/Article/details/gtkxrcejck.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.dashuyun.cn/Article/details/gtyyiwrfvj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigufen.top/Article/details/gtguzrummi.html

Go:   name := "Alex"; age := 20
来源：http://dali.sufxvd.cn/Article/details/gtpczyajkc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jiagoushi.top/Article/details/gtftkdsykx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.pycfn.com/Article/details/gtptefdukp.html

[A03] 常量定义
来源：http://dali.shzxlz.cn/Article/details/gtvwiqcudf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gtnatsptcv.html

PHP:  const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtdegxucrr.html

JS:   const PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtayqbphqg.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtqrudnqgo.html

Java: static final double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtvysksouv.html

Go:   const PI = 3.14159
来源：http://dali.c1oappe.top/Article/details/gtbuzhbfyf.html

Ruby: PI = 3.14159
来源：http://dali.xylfe.cn/Article/details/gtandprxmc.html

C#:   const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtxjbhtgpu.html

[A04] 判断变量类型
来源：http://dali.vqdsnc.cn/Article/details/gtzotdobrq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhengqikj.top/Article/details/gtwvogggsw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daxiang520.top/Article/details/gtqnwfanpb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gtcbiqmugu.html

TS:   typeof x; x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gtdquajjcj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.quarkkingdee.top/Article/details/gtwcfvdwnj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.vqdsnc.cn/Article/details/gtjcrqstco.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hnxiangtu.top/Article/details/gtqhbbmehr.html

C#:   x.GetType().Name; x is int
来源：http://dali.xuanzx.com/Article/details/gtkkdsjqcc.html

[A05] 整数除法与取模
来源：http://dali.yj20258888.top/Article/details/gttocpavxf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.bjfxy.top/Article/details/gtjfzqsgod.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtmdfzpgah.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtymgutmeq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gtwcwvfepj.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gtsiwmawzl.html

Go:   7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gthtzcslpr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtpfrtbdle.html

C#:   7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gthnhffysl.html

[A06] 字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtokvuolmu.html

Py:   int("42"); float("3.14")
来源：http://dali.0kj1m.cn/Article/details/gtlehktoyd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdrnuflo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.tianlin.xyz/Article/details/gtqkjgzkdv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.gotoacloud.top/Article/details/gtvkwksdte.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtuejqtjmh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptcabpaq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jqgufenzy.top/Article/details/gtaxgxxhwa.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258.top/Article/details/gtrqcixvyc.html

[A07] 数字转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtdipiuosi.html

Py:   str(42)
来源：http://dali.yuxming.cn/Article/details/gtbfwomrbq.html

PHP:  (string) 42; strval(42)
来源：http://dali.ivvv.top/Article/details/gtoriimhey.html

JS:   String(42); (42).toString()
来源：http://dali.zhixingplan.top/Article/details/gtsgvboxog.html

TS:   String(42)
来源：http://dali.yvedp.cn/Article/details/gtispezhxc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gtgxucbvnt.html

Go:   strconv.Itoa(42)
来源：http://dali.smart0.xyz/Article/details/gtmkddppcx.html

Ruby: 42.to_s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkavqvzko.html

C#:   42.ToString()
来源：http://dali.havefunace.top/Article/details/gtksyhhuws.html

[A08] 取整与四舍五入
来源：http://dali.sxryk.cn/Article/details/gtcndczjeu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtkwcylwap.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.havefunace.top/Article/details/gtdtthocpw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtxdocskzu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj20258888.top/Article/details/gtruhayivu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtmydyjhlu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtnogcgbrc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yanxiufei.cn/Article/details/gtqnbalniq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtggeywvbb.html

[A09] 绝对值与最大最小值
来源：http://dali.pycfn.com/Article/details/gtrfypbvkp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtvkcztmqr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtmoegymvb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtljjiqner.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtmmomdidt.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtyxqmokwe.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dianchejie.cn/Article/details/gtngrabmea.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.fzhhl.top/Article/details/gtfvtartxq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtrfmcofpu.html

[A10] 生成随机数
来源：http://dali.andypj.xyz/Article/details/gtoupyklms.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwoyncaf.html

PHP:  random_int(1, 100);
来源：http://dali.hammf.cn/Article/details/gtwttjaosy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflrpnnes.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cdnleiting.top/Article/details/gtqtpcypzt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.daxiang520.top/Article/details/gtsucvemwu.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pengpengdd.cyou/Article/details/gtfprdxzdm.html

Ruby: rand(1..100)
来源：http://dali.xuetiantiany.cn/Article/details/gtpdyakwhf.html

C#:   new Random().Next(1, 101)
来源：http://dali.chenlongwang.top/Article/details/gtducdncsh.html

[A11] 条件表达式（三元）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmqvdbxq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.c1oappe.top/Article/details/gtwnzkbdwq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gthqavtszf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gtpqeilein.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtrfrryxwf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gtmuiewvpl.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.c1oappe.top/Article/details/gtneaakysh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtuskquukl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gtrfbwltgh.html

[A12] 字符串插值 / 格式化
来源：http://dali.xuanzx.com/Article/details/gtsjrgsmtm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.snrcjt.cn/Article/details/gtvxojsdmo.html


<!-- 参考信息 -->