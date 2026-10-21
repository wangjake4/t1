代发 wailian999

[U79] PHP：静态分析
来源：http://dali.jqgfzy.top/Article/details/gthehuanfa.html

composer require --dev phpstan/phpstan
来源：http://dali.sufxvd.cn/Article/details/gtcsnnfzxk.html

[U80] PHP：代码规范修复
来源：http://dali.dianchejie.cn/Article/details/gtnxkguphr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ivvv.top/Article/details/gtrzerfftj.html

[U81] JS：初始化项目
来源：http://dali.dianchejie.cn/Article/details/gtmzsyyllh.html

npm init -y;  npm i express
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrrcsitp.html

[U82] JS：package.json 脚本
来源：http://dali.ivvv.top/Article/details/gtfgzankfd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zycfv.cn/Article/details/gtzqguxutt.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenlongwang.top/Article/details/gtluwamqph.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gtbwssyfel.html

[U84] JS：CommonJS 写法
来源：http://dali.chenjidiqi.icu/Article/details/gtthkelpmg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpezshov.html

[U85] JS：可选链
来源：http://dali.sysykeji.top/Article/details/gtjovhzdee.html

a?.b?.c
来源：http://dali.0kj1m.cn/Article/details/gtosgmvsxm.html

[U86] JS：空值合并
来源：http://dali.fzhhl.top/Article/details/gtnmnpfxia.html

a ?? b
来源：http://dali.sxryk.cn/Article/details/gtlfmgysau.html

[U87] JS：解构默认值
来源：http://dali.ydzc1.top/Article/details/gtobcwumqt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yuanzhike.top/Article/details/gtydgbdymt.html

[U88] JS：对象展开合并
来源：http://dali.zhengqikj.top/Article/details/gtirqpoegw.html

{ ...a, ...b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdingkaea.html

[U89] JS：数组去重
来源：http://dali.kuanghao11.cn/Article/details/gtiiwqoxwh.html

[...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtvflkltjp.html

[U90] JS：数字数组排序
来源：http://dali.wangdashe.top/Article/details/gtlbacsewj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtyrvmyhwg.html

[U91] JS：对象键值遍历
来源：http://dali.zycfv.cn/Article/details/gtgpaqmrii.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.9152youxi.cn/Article/details/gtzdoiwgxh.html

[U92] JS：深拷贝
来源：http://dali.chenlongwang.top/Article/details/gtgfiwckvj.html

structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtqrlqsrjh.html

[U93] JS：模板字符串
来源：http://dali.bjfxy.top/Article/details/gtesdaygqi.html

`共 ${n} 条`
来源：http://dali.yonumen.top/Article/details/gtuqwkyyxx.html

[U94] JS：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gtxodemeol.html

const double = x => x * 2;
来源：http://dali.xuanzx.com/Article/details/gtekezksjj.html

[U95] JS：Promise 包装
来源：http://dali.shzxlz.cn/Article/details/gtuuxjayeb.html

new Promise((resolve, reject) => {})
来源：http://dali.hysaishi.cn/Article/details/gtiwicmzhj.html

[U96] JS：async/await 与异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiukxqztw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtzlzyarob.html

[U97] JS：并发请求
来源：http://dali.yvedp.cn/Article/details/gtzqiicznz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtgzxtaiyf.html

[U98] JS：fetch 带 JSON
来源：http://dali.meibo888.top/Article/details/gtntopyrav.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.snrcjt.cn/Article/details/gtmdalhdmr.html

[U99] JS：事件监听
来源：http://dali.svipenyu.cn/Article/details/gtqoitndrc.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigfzy.top/Article/details/gtjbekczwv.html

[U100] JS：DOM 查询
来源：http://dali.guowangkeji.top/Article/details/gtxktjovee.html

document.querySelector(".item")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadeskcos.html

[U101] JS：classList 操作
来源：http://dali.chenjidiqi.icu/Article/details/gtaoyyevdz.html

el.classList.toggle("active")
来源：http://dali.bjfxy.top/Article/details/gtnlxhrkpi.html

[U102] JS：本地存储
来源：http://dali.havefunace.top/Article/details/gthogicyhp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.haohaochexian.top/Article/details/gtdfzzajsz.html

[U103] JS：定时器
来源：http://dali.vqdsnc.cn/Article/details/gtzecazyhx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhixingplan.top/Article/details/gtmeqsyiln.html

[U104] JS：防抖
来源：http://dali.yj20258888.top/Article/details/gtxkykfuep.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtzyrosxtr.html

[U105] JS：节流
来源：http://dali.yj202588.top/Article/details/gtufmrdkbz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gtiqgjonnq.html

[U106] JS：日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtcmgmkpro.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.0kj1m.cn/Article/details/gthnddiqmw.html

[U107] JS：数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gtvzotozte.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtmjykrkgl.html

[U108] JS：随机整数
来源：http://dali.yj202588.top/Article/details/gtsgutkmzv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigufen.top/Article/details/gtjggwxdhb.html

[U109] JS：数组分组
来源：http://dali.svipenyu.cn/Article/details/gtjciwtcgh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtpchhgymy.html

[U110] JS：数组分块
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvjxeqyk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tian-w.cn/Article/details/gtsdolpilx.html

[U111] JS：对象转 Map
来源：http://dali.hongshengwenyu.top/Article/details/gteornoktl.html

new Map(Object.entries(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtplrwaglc.html

[U112] JS：字符串补位
来源：http://dali.pengpengdd.cyou/Article/details/gtgiszxwlc.html

"7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtdnrllbdq.html

[U113] JS：正则替换全部
来源：http://dali.hysaishi.cn/Article/details/gtcucewpvg.html

s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtzqjlltrr.html

[U114] JS：JSON 深比较
来源：http://dali.zdqjudy.top/Article/details/gtwppztxzt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gtcnvotvvy.html

[U115] JS：生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtfvmdmdst.html

crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gthvzxajab.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sweek.top/Article/details/gtvrjdssyr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.0kj1m.cn/Article/details/gtscazmkuj.html

[U117] JS：单元测试
来源：http://dali.hywenlv.cn/Article/details/gtxhzsgeon.html

npm i -D vitest;  npx vitest
来源：http://dali.cqqwz.cn/Article/details/gtoqjjyuah.html

[U118] JS：开发服务器
来源：http://dali.shuidangran.top/Article/details/gtbxoroddh.html

npm i -D vite;  npx vite
来源：http://dali.yuanzhike.top/Article/details/gtsdexgnac.html

[U119] JS：生产构建
来源：http://dali.ivvv.top/Article/details/gtkavdswko.html

npx vite build
来源：http://dali.sufxvd.cn/Article/details/gtthfhvlzy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yangfankeji.com/Article/details/gtabedmfqi.html

import.meta.env.VITE_API_URL
来源：http://dali.xuetiantiany.cn/Article/details/gtrafxtkpt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtporlfioz.html

统计汇总
来源：http://dali.gogol.net.cn/Article/details/gtqmfggelg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwgdkfoco.html

按语言统计（条）：
来源：http://dali.jianghu66.top/Article/details/gtxulqubtg.html

Python ......... 252
来源：http://dali.shangyingyoupin.top/Article/details/gtslaeqctf.html

PHP ............ 252
来源：http://dali.pycfn.com/Article/details/gtkmnckcfz.html

JavaScript ..... 252
来源：http://dali.gzhubu.top/Article/details/gtrpnjuuec.html

TypeScript ..... 212
来源：http://dali.guowangkeji.top/Article/details/gtlhinbxjx.html

Java ........... 212
来源：http://dali.tian-w.cn/Article/details/gtankjqfbm.html

Go ............. 212
来源：http://dali.yongpay.top/Article/details/gtydctdqgi.html

Ruby ........... 212
来源：http://dali.zhengqikj.top/Article/details/gtqarinhxu.html

C# ............. 212
来源：http://dali.snrcjt.cn/Article/details/gthrzclkng.html

C .............. 30
来源：http://dali.jyoumei.cn/Article/details/gtlqspmriv.html

C++ ............ 30
来源：http://dali.nanxuanxn.top/Article/details/gtswozojwz.html

SQL ............ 90
来源：http://dali.sysykeji.top/Article/details/gtkkzoenyi.html

Bash ........... 80
来源：http://dali.wangdashe.top/Article/details/gtjkdjlrlz.html

Kotlin ......... 15
来源：http://dali.jyoumei.cn/Article/details/gtgoktqeyd.html

Swift .......... 15
来源：http://dali.yangfankeji.com/Article/details/gtcnvfvugq.html

Lua ............ 10
来源：http://dali.birdmap.top/Article/details/gtmyjdeevm.html

Perl ........... 10
来源：http://dali.feifeiyinyue.top/Article/details/gtrifbtpuz.html

Scala .......... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzadoccs.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtcsgqndfj.html

合计 ........... 2106 条
来源：http://dali.hnxiangtu.top/Article/details/gttyaiveai.html

按章节统计：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyysqasz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnqzz.top/Article/details/gtwbmjelly.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gteewkmotj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqujnzpk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gtwkezmgdz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fzhhl.top/Article/details/gtmnxilgkt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gtlkmhjcbx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtygxoqyeo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtjvblybha.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gttrxxvsup.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltghmtjk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvrnvynx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtuomobthx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtmhcibtlq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gtdyercbet.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pengpengdd.cyou/Article/details/gtbyiyihux.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtxatynxgi.html

Q SQL 专题                              90
来源：http://dali.snrcjt.cn/Article/details/gtbxfheljc.html

R Bash 专题                             80
来源：http://dali.yj20258888.top/Article/details/gthbuxobfu.html

S C / C++ 专题                          60
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsuikmry.html

T 其他语言补充                          60
来源：http://dali.jinqigfzy.top/Article/details/gtjjnszohw.html

U 高频实用片段                         120
来源：http://dali.zdqjudy.top/Article/details/gtotpzoiwl.html

------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtsclykjlq.html

合计                                  2106 条
来源：http://dali.vqdsnc.cn/Article/details/gtkdmycfsb.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtypqdtjuk.html

使用提醒
来源：http://dali.shangyingyoupin.top/Article/details/gtjmbzweyh.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtjkkxckch.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj20258888.top/Article/details/gtmccsyvqv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nanxuanxn.top/Article/details/gtflwpasfm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jiagoushi.top/Article/details/gtrjbsavpt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hfpthk.cn/Article/details/gtxvfbvmna.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.smart0.xyz/Article/details/gtrtoylwls.html

—— 文件结束 ——
来源：http://dali.yuxming.cn/Article/details/gtkhvpihfg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtuktledjv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yongpay.top/Article/details/gtwssofbsi.html

Common Programming Examples Cheat Book
来源：http://dali.daxiang520.top/Article/details/gtkaqcdevw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtpcnbkoyu.html

【收录内容】
来源：http://dali.xinyue.icu/Article/details/gtadscydzm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.birdmap.top/Article/details/gtiewmnkwc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.feifeiyinyue.top/Article/details/gtzulfycmu.html

SQL · Bash · C · C++
来源：http://dali.316326.xyz/Article/details/gtfeocbuje.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.c1oappe.top/Article/details/gtcwjuelse.html

【使用说明】
来源：http://dali.sysykeji.top/Article/details/gtvpvvwwwd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinghuilouyu.cn/Article/details/gttaahpjny.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yongpay.top/Article/details/gtfkwhppsy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.birdmap.top/Article/details/gtmicyuuxx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gtvtkkkkpg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyyugpch.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daria6918.cn/Article/details/gtqblmrllm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jianghu66.top/Article/details/gtkmkbjlxz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cqqwz.cn/Article/details/gtmuhtfgqu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenlongwang.top/Article/details/gtnejesqan.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.iojbl.cn/Article/details/gtmgoyrmij.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cucudq.cn/Article/details/gtntoolriu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.mhx1999.top/Article/details/gtmddyoclr.html

【文件统计】
来源：http://dali.aizwys.cn/Article/details/gtupqgwqct.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.feifeiyinyue.top/Article/details/gtvfejcugq.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gttibxxeob.html

目  录
来源：http://dali.yj20258888.top/Article/details/gteznjezik.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtpacpomdn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gtxhcloelz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gtbdsjypsv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gtszphyasv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.fengsongda.top/Article/details/gtbeqisafs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlnosozl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gtrdfixlsr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gtfqtqlhoz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtskxzwgmz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtexdmqeyw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.dianchejie.cn/Article/details/gtsrfmytqh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gttrordvqn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gtnvoedsie.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtrcmlaiug.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shuidangran.top/Article/details/gtlichsrdh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgufenzy.top/Article/details/gtlhjhhsze.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtkrdriswn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.andypj.xyz/Article/details/gtndxqpepx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.smart0.xyz/Article/details/gtsrghwnyv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aibaodan.cn/Article/details/gtjxtdvlrq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtkyztdwmd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gtlcxyzvic.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfktxkdvi.html

A. 基础语法与类型
来源：http://dali.shzxlz.cn/Article/details/gtvkejfagz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbehrdzgb.html

[A01] Hello World
来源：http://dali.tianlin.xyz/Article/details/gtflqiawuo.html

Py:   print("Hello, World!")
来源：http://dali.jiagoushi.top/Article/details/gtmvsxcpqk.html

PHP:  echo "Hello, World!";
来源：http://dali.sysykeji.top/Article/details/gtikokrgtq.html

JS:   console.log("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtoaahlbbj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cdnleiting.top/Article/details/gtslbteojk.html

Java: System.out.println("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gtuaawvnkw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhiwuduotai.top/Article/details/gtlcsfxptv.html

Ruby: puts "Hello, World!"
来源：http://dali.shangyingyoupin.top/Article/details/gtgbekfgtg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtateylujv.html

[A02] 变量声明与赋值
来源：http://dali.jqgfzy.top/Article/details/gtmodiiwbq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.mhx1999.top/Article/details/gtaecbvflk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtvpufusta.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtjzlgvzas.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.fengsongda.top/Article/details/gttcfarmze.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xinyue.icu/Article/details/gtlazxbszt.html

Go:   name := "Alex"; age := 20
来源：http://dali.bjfxy.top/Article/details/gtrrhlqege.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gtluhscexh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtpanwrznr.html

[A03] 常量定义
来源：http://dali.kuanghao11.cn/Article/details/gtsvkpancz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daxiang520.top/Article/details/gtquirfljp.html

PHP:  const PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtkvrctqvp.html

JS:   const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtjrecpoaf.html

TS:   const PI: number = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtefnyuitv.html

Java: static final double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtmbisqzxm.html

Go:   const PI = 3.14159
来源：http://dali.iojbl.cn/Article/details/gtgsjvlnat.html

Ruby: PI = 3.14159
来源：http://dali.jqgfzy.top/Article/details/gtaamswvgy.html

C#:   const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtqszjgfky.html

[A04] 判断变量类型
来源：http://dali.0kj1m.cn/Article/details/gtjjdgiyfi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gtkottnmre.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenzaomai.com/Article/details/gtwzmlwmvh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gtupwpkoau.html

TS:   typeof x; x instanceof Date
来源：http://dali.shangyingyoupin.top/Article/details/gtvuirfpmk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hywenlv.cn/Article/details/gtomugsber.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hammf.cn/Article/details/gtqajbsfub.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.dianchejie.cn/Article/details/gtbonbgeow.html

C#:   x.GetType().Name; x is int
来源：http://dali.cdnleiting.top/Article/details/gttejmqhsm.html

[A05] 整数除法与取模
来源：http://dali.daria6918.cn/Article/details/gtffwncttp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.fengsongda.top/Article/details/gtabrtghrb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtacieilob.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtazusmgzl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ivvv.top/Article/details/gtusorqoru.html

Java: 7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtwbprhobu.html

Go:   7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtktwsildx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtzjifogqj.html

C#:   7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gtxykbhioz.html

[A06] 字符串转数字
来源：http://dali.yongpay.top/Article/details/gtqpqwopfm.html

Py:   int("42"); float("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gtsbzksqaa.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xuanzx.com/Article/details/gtnppiunor.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yuanzhike.top/Article/details/gtzgvszaaj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jianghu66.top/Article/details/gtvebaywwb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zycfv.cn/Article/details/gtcbcaasud.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gogol.net.cn/Article/details/gtibpdxwrw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ybcxt.top/Article/details/gtpaiitjdb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jianghu66.top/Article/details/gtpnafjomw.html

[A07] 数字转字符串
来源：http://dali.guannengcc.top/Article/details/gtvbgfqtdo.html

Py:   str(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtelihsqux.html

PHP:  (string) 42; strval(42)
来源：http://dali.yuanzhike.top/Article/details/gtooykwqhd.html

JS:   String(42); (42).toString()
来源：http://dali.andypj.xyz/Article/details/gtnngpsosg.html

TS:   String(42)
来源：http://dali.svipenyu.cn/Article/details/gtzkwejuhh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hammf.cn/Article/details/gthvgtlexo.html

Go:   strconv.Itoa(42)
来源：http://dali.xuanzx.com/Article/details/gtxmvtnkgo.html

Ruby: 42.to_s
来源：http://dali.jianghu66.top/Article/details/gtvvhdmals.html

C#:   42.ToString()
来源：http://dali.snrcjt.cn/Article/details/gtqqgdzjug.html

[A08] 取整与四舍五入
来源：http://dali.jqgufenzy.top/Article/details/gtwkgxaqqv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtxnrjpdkm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tianlin.xyz/Article/details/gttievhcdx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtutadiyxg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonypfojc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtnpydtjeu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtncevspgk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.wangdashe.top/Article/details/gtiwqodxrq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tanke756.top/Article/details/gtgrnarrqs.html

[A09] 绝对值与最大最小值
来源：http://dali.cqqwz.cn/Article/details/gtaoskigha.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtfvimzrsj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtuqgeskhi.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtgwtfsalk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.havefunace.top/Article/details/gtjhndrfna.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtdoealrdz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.feifeiyinyue.top/Article/details/gtzjnjyrsl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ehwqpu.com/Article/details/gtemammyld.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrjknvmq.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gtusyavldh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hnqzz.top/Article/details/gtnxpvgpwl.html

PHP:  random_int(1, 100);
来源：http://dali.xziqi.cn/Article/details/gtayzhgiwl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gtnujjajzl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aizwys.cn/Article/details/gtznjyxplf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.nanxinkj.top/Article/details/gtduvylmrr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.wangdashe.top/Article/details/gtjcadnybu.html

Ruby: rand(1..100)
来源：http://dali.c1oappe.top/Article/details/gtnlmmvdrh.html

C#:   new Random().Next(1, 101)
来源：http://dali.chenzaomai.com/Article/details/gtlcfhguos.html

[A11] 条件表达式（三元）
来源：http://dali.feifeiyinyue.top/Article/details/gtxovbjpab.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tian-w.cn/Article/details/gtfwautbrg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gtcvqebgbg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtczdxzlbx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gtshnblkhh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtdoradxse.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhixingplan.top/Article/details/gtagnsymhh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtpjoijqsr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtikiufkgb.html

[A12] 字符串插值 / 格式化
来源：http://dali.ppjwa.cn/Article/details/gthozyaegw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhoulong.xyz/Article/details/gtatkrlmvw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.bjfxy.top/Article/details/gtgsfdhtgz.html

JS:   `Hello, ${name}!`
来源：http://dali.yj202588.top/Article/details/gtbktmdnxj.html

TS:   `Hello, ${name}!`
来源：http://dali.guannengcc.top/Article/details/gtemyyypwn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shzxlz.cn/Article/details/gtohftprhz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtnbvmxtpi.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcvxqpro.html

C#:   $"Hello, {name}!"
来源：http://dali.cucudq.cn/Article/details/gtiaywsspm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nanxinkj.top/Article/details/gtlipzijrr.html


<!-- 参考信息 -->