代发 wailian999

[U79] PHP：静态分析
来源：http://dali.hongshengwenyu.top/Article/details/gt2hfpvqevd.html

composer require --dev phpstan/phpstan
来源：http://dali.aizwys.cn/Article/details/gt2rltfvvna.html

[U80] PHP：代码规范修复
来源：http://dali.mhx1999.top/Article/details/gt2dcfdqabm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atlvtwig.html

[U81] JS：初始化项目
来源：http://dali.sufxvd.cn/Article/details/gt2xeloyumz.html

npm init -y;  npm i express
来源：http://dali.guannengcc.top/Article/details/gt2qpnshnkm.html

[U82] JS：package.json 脚本
来源：http://dali.snrcjt.cn/Article/details/gt2fyllgrxq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yangfankeji.com/Article/details/gt2cakwjqux.html

[U83] JS：ES Module 导入导出
来源：http://dali.haohaochexian.top/Article/details/gt2rfpanyjm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gt2wdibqgrs.html

[U84] JS：CommonJS 写法
来源：http://dali.ehwqpu.com/Article/details/gt2zdhngcbe.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cheryme.top/Article/details/gt2xjxyigrq.html

[U85] JS：可选链
来源：http://dali.cqqwz.cn/Article/details/gt2ckhyejmk.html

a?.b?.c
来源：http://dali.c1oappe.top/Article/details/gt2hlsghmvn.html

[U86] JS：空值合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ppjcpnrm.html

a ?? b
来源：http://dali.hammf.cn/Article/details/gt2entnusjz.html

[U87] JS：解构默认值
来源：http://dali.0kj1m.cn/Article/details/gt2pquolpua.html

const { a = 1, b = 2 } = obj;
来源：http://dali.316326.xyz/Article/details/gt2hudhvhms.html

[U88] JS：对象展开合并
来源：http://dali.yuxming.cn/Article/details/gt2alieckxg.html

{ ...a, ...b }
来源：http://dali.jqgfzy.top/Article/details/gt2yiyazsjb.html

[U89] JS：数组去重
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilbzppct.html

[...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gt2bqkkrzjt.html

[U90] JS：数字数组排序
来源：http://dali.hysaishi.cn/Article/details/gt2abimgwxv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2kjunzbys.html

[U91] JS：对象键值遍历
来源：http://dali.shzxlz.cn/Article/details/gt2fzuylvjn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xinyue.icu/Article/details/gt2mocwoxtn.html

[U92] JS：深拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2yonixcgh.html

structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dsbbaqws.html

[U93] JS：模板字符串
来源：http://dali.jinqigufen.top/Article/details/gt2cahelwwt.html

`共 ${n} 条`
来源：http://dali.nanxinkj.top/Article/details/gt2edkwtjri.html

[U94] JS：箭头函数
来源：http://dali.mhx1999.top/Article/details/gt2dbjbgnve.html

const double = x => x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vlpnewvg.html

[U95] JS：Promise 包装
来源：http://dali.daria6918.cn/Article/details/gt2fxipxdjl.html

new Promise((resolve, reject) => {})
来源：http://dali.tanke756.top/Article/details/gt2mwjtjfhm.html

[U96] JS：async/await 与异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzklirrz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2tsknnqgg.html

[U97] JS：并发请求
来源：http://dali.jyoumei.cn/Article/details/gt2lbcdtaku.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2gubnsaki.html

[U98] JS：fetch 带 JSON
来源：http://dali.sweek.top/Article/details/gt2rfvilsqs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenzaomai.com/Article/details/gt2xbiuyqyz.html

[U99] JS：事件监听
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruyxtrob.html

el.addEventListener("click", e => {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnfehwbo.html

[U100] JS：DOM 查询
来源：http://dali.aibaodan.cn/Article/details/gt2btfyoitg.html

document.querySelector(".item")
来源：http://dali.smart0.xyz/Article/details/gt2bywxtice.html

[U101] JS：classList 操作
来源：http://dali.yj20258.top/Article/details/gt2chvzscxv.html

el.classList.toggle("active")
来源：http://dali.yueranfly.top/Article/details/gt2lgmligkc.html

[U102] JS：本地存储
来源：http://dali.yvedp.cn/Article/details/gt2tmniistt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.snrcjt.cn/Article/details/gt2fzkjtpob.html

[U103] JS：定时器
来源：http://dali.cdnleiting.top/Article/details/gt2clpcskqe.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgfzy.top/Article/details/gt2mptbaupg.html

[U104] JS：防抖
来源：http://dali.jqgufenzy.top/Article/details/gt2fzudjhfg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgtylpao.html

[U105] JS：节流
来源：http://dali.andypj.xyz/Article/details/gt2tjzbvzpy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xziqi.cn/Article/details/gt2cuzaplwc.html

[U106] JS：日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2ehvhehii.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.daria6918.cn/Article/details/gt2ydbaibbn.html

[U107] JS：数字千分位
来源：http://dali.zycfv.cn/Article/details/gt2rypfjuvm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okuazowo.html

[U108] JS：随机整数
来源：http://dali.zhixingplan.top/Article/details/gt2lvovbixl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hywenlv.cn/Article/details/gt2irglvyob.html

[U109] JS：数组分组
来源：http://dali.dianchejie.cn/Article/details/gt2gyqswrrj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gt2ppcyfosu.html

[U110] JS：数组分块
来源：http://dali.ppjwa.cn/Article/details/gt2yzhicuvx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj202588.top/Article/details/gt2perduldc.html

[U111] JS：对象转 Map
来源：http://dali.gaohongyu789.top/Article/details/gt2usvwkpzo.html

new Map(Object.entries(obj))
来源：http://dali.nanxinkj.top/Article/details/gt2uhamrfgo.html

[U112] JS：字符串补位
来源：http://dali.kuanghao11.cn/Article/details/gt2wmggauqq.html

"7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnhuyqnw.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gt2awiyvguu.html

s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2bdxhhvpw.html

[U114] JS：JSON 深比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2jeikeqgq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gt2dwykncxj.html

[U115] JS：生成 UUID
来源：http://dali.hnqzz.top/Article/details/gt2xvvwdois.html

crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gt2tgxrxenu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkrqgxpr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gzhubu.top/Article/details/gt2biyxoviz.html

[U117] JS：单元测试
来源：http://dali.zhoulong.xyz/Article/details/gt2gwhcerhk.html

npm i -D vitest;  npx vitest
来源：http://dali.sysykeji.top/Article/details/gt2ylfvbqoi.html

[U118] JS：开发服务器
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjkxwmnp.html

npm i -D vite;  npx vite
来源：http://dali.nwbrower.top/Article/details/gt2fethmfin.html

[U119] JS：生产构建
来源：http://dali.yangfankeji.com/Article/details/gt2ouopxjhr.html

npx vite build
来源：http://dali.jyoumei.cn/Article/details/gt2uzdphfsw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhengqikj.top/Article/details/gt2phdkujgy.html

import.meta.env.VITE_API_URL
来源：http://dali.guannengcc.top/Article/details/gt2tmxzyxik.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2tjucpjza.html

统计汇总
来源：http://dali.tian-w.cn/Article/details/gt2eleoqfru.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2bkisasqn.html

按语言统计（条）：
来源：http://dali.fzhhl.top/Article/details/gt2gheuvbef.html

Python ......... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzwvpnmz.html

PHP ............ 252
来源：http://dali.fzhhl.top/Article/details/gt2hctsuopj.html

JavaScript ..... 252
来源：http://dali.yongpay.top/Article/details/gt2rjmphtua.html

TypeScript ..... 212
来源：http://dali.guannengcc.top/Article/details/gt2iykvpfkk.html

Java ........... 212
来源：http://dali.guowangkeji.top/Article/details/gt2eoowmpjs.html

Go ............. 212
来源：http://dali.guowangkeji.top/Article/details/gt2didttfgb.html

Ruby ........... 212
来源：http://dali.meibo888.top/Article/details/gt2suothxhv.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gt2dwcjksgm.html

C .............. 30
来源：http://dali.xylfe.cn/Article/details/gt2xofgpfca.html

C++ ............ 30
来源：http://dali.zhoulong.xyz/Article/details/gt2mgleuthx.html

SQL ............ 90
来源：http://dali.sxryk.cn/Article/details/gt2mghumuyk.html

Bash ........... 80
来源：http://dali.cashguo.top/Article/details/gt2ncgectck.html

Kotlin ......... 15
来源：http://dali.meibo888.top/Article/details/gt2kkpptzvy.html

Swift .......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldleutir.html

Lua ............ 10
来源：http://dali.pycfn.com/Article/details/gt2zetoguck.html

Perl ........... 10
来源：http://dali.hywenlv.cn/Article/details/gt2jtzedzca.html

Scala .......... 10
来源：http://dali.jqgfzy.top/Article/details/gt2hpcctzwe.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gt2magxgeaz.html

合计 ........... 2106 条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxwggquj.html

按章节统计：
来源：http://dali.zhengqikj.top/Article/details/gt2udiodsxl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gt2nvwsqsjb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gt2ujqisfyv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gt2oosvijsc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gt2vvdwaedx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jyoumei.cn/Article/details/gt2xnjwkqyl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yvedp.cn/Article/details/gt2knvafehi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gt2xtximbup.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gt2vqooowcz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gt2tfjzpzyn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuanzx.com/Article/details/gt2ckerunqg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gt2msqawtbo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gt2omfglsuf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gt2lvawrtmd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gt2udpotqqv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.snrcjt.cn/Article/details/gt2hdozfelt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gt2azuvsecw.html

Q SQL 专题                              90
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdasnxak.html

R Bash 专题                             80
来源：http://dali.yj202588.top/Article/details/gt2nntflipf.html

S C / C++ 专题                          60
来源：http://dali.zhongyouzk.top/Article/details/gt2foueclxu.html

T 其他语言补充                          60
来源：http://dali.aibaodan.cn/Article/details/gt2naiugmke.html

U 高频实用片段                         120
来源：http://dali.cqqwz.cn/Article/details/gt2chebzfdc.html

------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2rrmpqsbj.html

合计                                  2106 条
来源：http://dali.andypj.xyz/Article/details/gt2qismijzy.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gt2iagwblpi.html

使用提醒
来源：http://dali.cucudq.cn/Article/details/gt2ujlkgehy.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2bwzzwcse.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xylfe.cn/Article/details/gt2crcrtebn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cheryme.top/Article/details/gt2zeagcwda.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ppjwa.cn/Article/details/gt2stzyjdha.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.quarkkingdee.top/Article/details/gt2heavafly.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cqqwz.cn/Article/details/gt2hmjaimeu.html

—— 文件结束 ——
来源：http://dali.smart0.xyz/Article/details/gt2areozjhi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2utdmlsum.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangdashe.top/Article/details/gt2uogajqmt.html

Common Programming Examples Cheat Book
来源：http://dali.vqdsnc.cn/Article/details/gt2qxousmju.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2rfweevha.html

【收录内容】
来源：http://dali.jyoumei.cn/Article/details/gt2whnecpbz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.guowangkeji.top/Article/details/gt2rgmnbjnc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shangyingyoupin.top/Article/details/gt2mekyjbzy.html

SQL · Bash · C · C++
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yufedykj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.fzhhl.top/Article/details/gt2zscsjsrk.html

【使用说明】
来源：http://dali.tanke756.top/Article/details/gt2tbvsxyah.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shzxlz.cn/Article/details/gt2rygbvarm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yangfankeji.com/Article/details/gt2fddeyloo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hnxiangtu.top/Article/details/gt2ajybihqb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gzhubu.top/Article/details/gt2kxpfmwas.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.andypj.xyz/Article/details/gt2noaweyki.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.316326.xyz/Article/details/gt2hffwvgpj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.vqdsnc.cn/Article/details/gt2qorwisrr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cqqwz.cn/Article/details/gt2ejuyewyq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvrknrem.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yuanzhike.top/Article/details/gt2fxgexawf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xziqi.cn/Article/details/gt2kcnfsnpj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hfpthk.cn/Article/details/gt2zpfwhafy.html

【文件统计】
来源：http://dali.c1oappe.top/Article/details/gt2xmrkfuql.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pycfn.com/Article/details/gt2pkjmblqr.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2ghpkkoua.html

目  录
来源：http://dali.birdmap.top/Article/details/gt2huxkjyxk.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2vzhgepnb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yongpay.top/Article/details/gt2kxwwkfof.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gt2wlksfjju.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gt2wujwcrhy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2aofaitop.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.bjfxy.top/Article/details/gt2jotcsjve.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gt2vxdktdzs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.redwolf501.top/Article/details/gt2qcgezvkg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gt2ufttcrqq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gt2vnclzcgw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2zbyznghy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2hplcofht.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gt2nmtsgulz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2msttssok.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwgbugad.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.snrcjt.cn/Article/details/gt2qesdmbbg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gt2cojubtea.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2uuqpzeiq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2eorwilkj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hfpthk.cn/Article/details/gt2sxcfhogk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gt2txdotiqm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258.top/Article/details/gt2chwgirtf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2lxfvhcfc.html

A. 基础语法与类型
来源：http://dali.yueranfly.top/Article/details/gt2mknnrqyb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ooksltto.html

[A01] Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2kfogpipo.html

Py:   print("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gt2phwenhml.html

PHP:  echo "Hello, World!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikgbwpvj.html

JS:   console.log("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gt2esohptft.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yueranfly.top/Article/details/gt2cmhyntyr.html

Java: System.out.println("Hello, World!");
来源：http://dali.shuidangran.top/Article/details/gt2qecfvlge.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yuxming.cn/Article/details/gt2sdhkhmjj.html

Ruby: puts "Hello, World!"
来源：http://dali.xuanzx.com/Article/details/gt2jgvgfvsm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gt2njjacwlr.html

[A02] 变量声明与赋值
来源：http://dali.jlsjyb.cn/Article/details/gt2gguflhfj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cashguo.top/Article/details/gt2wldnojcn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.birdmap.top/Article/details/gt2zosvgthm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.fzhhl.top/Article/details/gt2xlxbqpnp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jqgufenzy.top/Article/details/gt2yvcnwyyq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.dashuyun.cn/Article/details/gt2ybovfzat.html

Go:   name := "Alex"; age := 20
来源：http://dali.yvedp.cn/Article/details/gt2nzrfgisf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yangfankeji.com/Article/details/gt2hngkuaro.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gotoacloud.top/Article/details/gt2cihwxsgo.html

[A03] 常量定义
来源：http://dali.yuxming.cn/Article/details/gt2budvohaw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shzxlz.cn/Article/details/gt2pwgagmsi.html

PHP:  const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2mawkpbbk.html

JS:   const PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2jiahgygj.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cescnwxj.html

Java: static final double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2igdckqmq.html

Go:   const PI = 3.14159
来源：http://dali.jianghu66.top/Article/details/gt2tetlzjdj.html

Ruby: PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gt2lqcnhulp.html

C#:   const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2bthfgpwa.html

[A04] 判断变量类型
来源：http://dali.ydzc1.top/Article/details/gt2xnyjlcqu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gotoacloud.top/Article/details/gt2pdjtrgsy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zycfv.cn/Article/details/gt2npspxdve.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.9152youxi.cn/Article/details/gt2pmdsmsbu.html

TS:   typeof x; x instanceof Date
来源：http://dali.yangfankeji.com/Article/details/gt2tnsrrsbv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.iojbl.cn/Article/details/gt2jndqyqty.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.wangshuangyany.cn/Article/details/gt2htsuwado.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yanxiufei.cn/Article/details/gt2eoaipevl.html

C#:   x.GetType().Name; x is int
来源：http://dali.iojbl.cn/Article/details/gt2itoxpzzl.html

[A05] 整数除法与取模
来源：http://dali.bjfxy.top/Article/details/gt2uubecjhs.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgufenzy.top/Article/details/gt2jrkodmbl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.redwolf501.top/Article/details/gt2cscbwkde.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cucudq.cn/Article/details/gt2czyhkhpu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.guannengcc.top/Article/details/gt2zkvumylg.html

Java: 7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gt2oobupmqw.html

Go:   7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gt2qrtubtjl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gt2xufccfhu.html

C#:   7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gt2kfppvvfs.html

[A06] 字符串转数字
来源：http://dali.birdmap.top/Article/details/gt2xocacndw.html

Py:   int("42"); float("3.14")
来源：http://dali.quarkkingdee.top/Article/details/gt2xyjziopf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhixingplan.top/Article/details/gt2haifjfmo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yyiacnfv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybkkzplg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.fzhhl.top/Article/details/gt2mxrsyoix.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtqotzx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jqgfzy.top/Article/details/gt2snmqgrad.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.wangdashe.top/Article/details/gt2asmaxomi.html

[A07] 数字转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2cskvazjr.html

Py:   str(42)
来源：http://dali.tian-w.cn/Article/details/gt2olttfwdj.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2miajtykd.html

JS:   String(42); (42).toString()
来源：http://dali.yangfankeji.com/Article/details/gt2dgjoxotv.html

TS:   String(42)
来源：http://dali.jinqigfzy.top/Article/details/gt2hsvudjyl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.wangshuangyany.cn/Article/details/gt2owdumgzw.html

Go:   strconv.Itoa(42)
来源：http://dali.tian-w.cn/Article/details/gt2ezcchucz.html

Ruby: 42.to_s
来源：http://dali.jiagoushi.top/Article/details/gt2zvyvojlh.html

C#:   42.ToString()
来源：http://dali.hysaishi.cn/Article/details/gt2gdwfgbrq.html

[A08] 取整与四舍五入
来源：http://dali.yj202588.top/Article/details/gt2xcfmvbof.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gt2gdyfihfz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jqgfzy.top/Article/details/gt2mjcphezc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gt2pcypodvc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gaohongyu789.top/Article/details/gt2jzmmmezc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jilpqgpt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gt2hchlpwbf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.snrcjt.cn/Article/details/gt2dchbansb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gt2efztlodt.html

[A09] 绝对值与最大最小值
来源：http://dali.hnqzz.top/Article/details/gt2weqhcxvs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urzxciyw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gt2ntyxbefn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2cujydybk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2pthbetqd.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gt2ndstxyow.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.tianlin.xyz/Article/details/gt2wnwlduhj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpdmuuvv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2ldztyynk.html

[A10] 生成随机数
来源：http://dali.nanxuanxn.top/Article/details/gt2rklisriu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xinyue.icu/Article/details/gt2fbmsotjl.html

PHP:  random_int(1, 100);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvbylcxf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aibaodan.cn/Article/details/gt2xjpooqik.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sweek.top/Article/details/gt2flqhcpbo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xziqi.cn/Article/details/gt2pceijlmq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwcgdjvm.html

Ruby: rand(1..100)
来源：http://dali.haohaochexian.top/Article/details/gt2jqrljcyg.html

C#:   new Random().Next(1, 101)
来源：http://dali.shuidangran.top/Article/details/gt2bhdgyvye.html

[A11] 条件表达式（三元）
来源：http://dali.guannengcc.top/Article/details/gt2yekjyiyj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ppjwa.cn/Article/details/gt2jiaebcnj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gt2qrurbmsk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gt2xyxqgiar.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gt2kcqtzxfj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gt2eiobrjjv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhiwuduotai.top/Article/details/gt2mizrqxzd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywdkzlwl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gt2byvvemqf.html

[A12] 字符串插值 / 格式化
来源：http://dali.gogol.net.cn/Article/details/gt2ppnpnmxi.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfckerin.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sxryk.cn/Article/details/gt2wmekzajg.html

JS:   `Hello, ${name}!`
来源：http://dali.birdmap.top/Article/details/gt2gotijeeq.html

TS:   `Hello, ${name}!`
来源：http://dali.9152youxi.cn/Article/details/gt2dscwakgu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.guowangkeji.top/Article/details/gt2fzbcvzsk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrzpjkdd.html

Ruby: "Hello, #{name}!"
来源：http://dali.xinyue.icu/Article/details/gt2mmlonusw.html

C#:   $"Hello, {name}!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oskqermp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.dianchejie.cn/Article/details/gt2gandsjqg.html


<!-- 参考信息 -->