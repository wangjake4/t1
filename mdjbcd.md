代发 wailian999

[U81] JS：初始化项目
来源：http://dali.wangdashe.top/Article/details/gthpuxxnpi.html

npm init -y;  npm i express
来源：http://dali.yonumen.top/Article/details/gtnwruwgig.html

[U82] JS：package.json 脚本
来源：http://dali.gaohongyu789.top/Article/details/gtekfvozmw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guannengcc.top/Article/details/gtestjgrvo.html

[U83] JS：ES Module 导入导出
来源：http://dali.gogol.net.cn/Article/details/gtwkrconhp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtvrvtbazg.html

[U84] JS：CommonJS 写法
来源：http://dali.hnxiangtu.top/Article/details/gthyjatoxm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hywenlv.cn/Article/details/gtyixwebpu.html

[U85] JS：可选链
来源：http://dali.hfpthk.cn/Article/details/gtycqqgtyq.html

a?.b?.c
来源：http://dali.nanxinkj.top/Article/details/gtqfzoblqx.html

[U86] JS：空值合并
来源：http://dali.wangdashe.top/Article/details/gtiruaesla.html

a ?? b
来源：http://dali.smart0.xyz/Article/details/gtxewasked.html

[U87] JS：解构默认值
来源：http://dali.cashguo.top/Article/details/gtoeypufzk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnxiangtu.top/Article/details/gtvzljxlzp.html

[U88] JS：对象展开合并
来源：http://dali.hysaishi.cn/Article/details/gtmonrpuon.html

{ ...a, ...b }
来源：http://dali.andypj.xyz/Article/details/gtndboqufu.html

[U89] JS：数组去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplmhplli.html

[...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gthnamjgap.html

[U90] JS：数字数组排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtkiblvpiw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtpdvaqcut.html

[U91] JS：对象键值遍历
来源：http://dali.yueranfly.top/Article/details/gtmryrbzdp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhixingplan.top/Article/details/gtrwrpzaor.html

[U92] JS：深拷贝
来源：http://dali.ppjwa.cn/Article/details/gtclyeguhq.html

structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtcksftvmd.html

[U93] JS：模板字符串
来源：http://dali.yj20258888.top/Article/details/gtptumjwin.html

`共 ${n} 条`
来源：http://dali.yuxming.cn/Article/details/gtbreiwmqq.html

[U94] JS：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gtfxhtxmcc.html

const double = x => x * 2;
来源：http://dali.chenlongwang.top/Article/details/gtnermtlgc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gtbcxlxpey.html

new Promise((resolve, reject) => {})
来源：http://dali.yanxiufei.cn/Article/details/gtwbekztsn.html

[U96] JS：async/await 与异常
来源：http://dali.xziqi.cn/Article/details/gtwxsfrmhx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtklicqqmc.html

[U97] JS：并发请求
来源：http://dali.tian-w.cn/Article/details/gtnttbqytf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtprsodajg.html

[U98] JS：fetch 带 JSON
来源：http://dali.cashguo.top/Article/details/gteqhyhnjr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fzhhl.top/Article/details/gtogpfabho.html

[U99] JS：事件监听
来源：http://dali.smart0.xyz/Article/details/gtpvcgprte.html

el.addEventListener("click", e => {})
来源：http://dali.haohaochexian.top/Article/details/gtusajyxsa.html

[U100] JS：DOM 查询
来源：http://dali.yonumen.top/Article/details/gtaydnyqgq.html

document.querySelector(".item")
来源：http://dali.feifeiyinyue.top/Article/details/gtvffyxyrg.html

[U101] JS：classList 操作
来源：http://dali.chenjidiqi.icu/Article/details/gtklnnabkn.html

el.classList.toggle("active")
来源：http://dali.sxryk.cn/Article/details/gtsadhyqsy.html

[U102] JS：本地存储
来源：http://dali.shangyingyoupin.top/Article/details/gtrndudcjg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj20258.top/Article/details/gtcafhxtxe.html

[U103] JS：定时器
来源：http://dali.birdmap.top/Article/details/gtgrjkoqtp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xinyue.icu/Article/details/gtugojrdpc.html

[U104] JS：防抖
来源：http://dali.ppjwa.cn/Article/details/gtkmmylkei.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtgwhvclus.html

[U105] JS：节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfvehwht.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhengqikj.top/Article/details/gtgmfrlanx.html

[U106] JS：日期格式化
来源：http://dali.tanke756.top/Article/details/gtwbizungo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sxryk.cn/Article/details/gtjlrdhmvq.html

[U107] JS：数字千分位
来源：http://dali.andypj.xyz/Article/details/gtegphyfjn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpstgnzb.html

[U108] JS：随机整数
来源：http://dali.xinyue.icu/Article/details/gtkrywrkdb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj20258888.top/Article/details/gtzxxmmqmm.html

[U109] JS：数组分组
来源：http://dali.snrcjt.cn/Article/details/gtjhkcbctc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybtfglax.html

[U110] JS：数组分块
来源：http://dali.feifeiyinyue.top/Article/details/gtqngjhdtg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvagumfe.html

[U111] JS：对象转 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwaadmtw.html

new Map(Object.entries(obj))
来源：http://dali.c1oappe.top/Article/details/gtxozipvwc.html

[U112] JS：字符串补位
来源：http://dali.cdnleiting.top/Article/details/gtmpexjxop.html

"7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtsjfxrbrm.html

[U113] JS：正则替换全部
来源：http://dali.tianlin.xyz/Article/details/gtczyxvbsb.html

s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtcwaxweqs.html

[U114] JS：JSON 深比较
来源：http://dali.c1oappe.top/Article/details/gtbktzwnzj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtipykzzcb.html

[U115] JS：生成 UUID
来源：http://dali.bjfxy.top/Article/details/gtsmwnoxhe.html

crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnrlqqtn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yangfankeji.com/Article/details/gtytgxssny.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqekoeoo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtbdifrxjt.html

npm i -D vitest;  npx vitest
来源：http://dali.xziqi.cn/Article/details/gtqgfzjunh.html

[U118] JS：开发服务器
来源：http://dali.hnxiangtu.top/Article/details/gtdgmruocd.html

npm i -D vite;  npx vite
来源：http://dali.andypj.xyz/Article/details/gtewsgrcbm.html

[U119] JS：生产构建
来源：http://dali.chenlongwang.top/Article/details/gtysbmexqz.html

npx vite build
来源：http://dali.yj202588.top/Article/details/gtxklamfxg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258888.top/Article/details/gtosdbvgln.html

import.meta.env.VITE_API_URL
来源：http://dali.dianchejie.cn/Article/details/gtrqsgysna.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttbjsjctv.html

统计汇总
来源：http://dali.yangfankeji.com/Article/details/gtpsciyjqq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gteeqhtqyi.html

按语言统计（条）：
来源：http://dali.havefunace.top/Article/details/gtzlnadhej.html

Python ......... 252
来源：http://dali.yongpay.top/Article/details/gtagsgzngc.html

PHP ............ 252
来源：http://dali.jlsjyb.cn/Article/details/gtlyegrgmy.html

JavaScript ..... 252
来源：http://dali.hammf.cn/Article/details/gthygixjzl.html

TypeScript ..... 212
来源：http://dali.zhixingplan.top/Article/details/gtjtfaehuk.html

Java ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gtulpiubjz.html

Go ............. 212
来源：http://dali.fengsongda.top/Article/details/gtgbpdozxy.html

Ruby ........... 212
来源：http://dali.tianlin.xyz/Article/details/gttsmmxeis.html

C# ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gtsrmzhgoq.html

C .............. 30
来源：http://dali.xinyue.icu/Article/details/gtnnyzyexz.html

C++ ............ 30
来源：http://dali.hywenlv.cn/Article/details/gtnvqfqzle.html

SQL ............ 90
来源：http://dali.zhiwuduotai.top/Article/details/gtwpxybyof.html

Bash ........... 80
来源：http://dali.snrcjt.cn/Article/details/gtbxfehvzi.html

Kotlin ......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gtzojrsxnl.html

Swift .......... 15
来源：http://dali.yj202588.top/Article/details/gtwmjgizmm.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gtnhrvbgbk.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtfdvobeur.html

Scala .......... 10
来源：http://dali.andypj.xyz/Article/details/gtevioyksc.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gtptsgmhzm.html

合计 ........... 2106 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemcrxefy.html

按章节统计：
来源：http://dali.sysykeji.top/Article/details/gtlvntrzvx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gtzjjaggvz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtiqgzndiq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtupxdboox.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gtbdilxgza.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.iojbl.cn/Article/details/gtqwkcufxw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangtech.top/Article/details/gtndauuxfn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtqtiywhbs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gtamedvazq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtpbbddfxu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gaohongyu789.top/Article/details/gtnzxpbkrq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtznhcpmyy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarjcxelp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtwqugawes.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gtrykvrdif.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sweek.top/Article/details/gtyvvvmveq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfjdeosm.html

Q SQL 专题                              90
来源：http://dali.havefunace.top/Article/details/gttuidbyrr.html

R Bash 专题                             80
来源：http://dali.jlsjyb.cn/Article/details/gtikwfbxug.html

S C / C++ 专题                          60
来源：http://dali.birdmap.top/Article/details/gtepslekxp.html

T 其他语言补充                          60
来源：http://dali.tian-w.cn/Article/details/gtbaokvkzt.html

U 高频实用片段                         120
来源：http://dali.fzhhl.top/Article/details/gtbclscint.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtlfxgaxmc.html

合计                                  2106 条
来源：http://dali.ybcxt.top/Article/details/gtfpxzorvu.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtfmyahowe.html

使用提醒
来源：http://dali.tian-w.cn/Article/details/gtplqiyvgz.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypmzflnw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuanzx.com/Article/details/gtjkizockc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gogol.net.cn/Article/details/gtfrvysvaz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.aibaodan.cn/Article/details/gtbirsyjvr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj20258888.top/Article/details/gtbdshncda.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.meibo888.top/Article/details/gtofiwaexu.html

—— 文件结束 ——
来源：http://dali.nanxinkj.top/Article/details/gtiglrcsrg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtbpdbvikh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.dianchejie.cn/Article/details/gtwcyqdpre.html

Common Programming Examples Cheat Book
来源：http://dali.ybcxt.top/Article/details/gtpjdtwuls.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtktqsjspj.html

【收录内容】
来源：http://dali.feifeiyinyue.top/Article/details/gtgwxgrwpq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ydzc1.top/Article/details/gttqergkwa.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlkpyxgh.html

SQL · Bash · C · C++
来源：http://dali.sweek.top/Article/details/gturfcaxph.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aizwys.cn/Article/details/gtvuyyefrp.html

【使用说明】
来源：http://dali.sysykeji.top/Article/details/gtjtuhsuxq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sweek.top/Article/details/gtsigezycv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hnqzz.top/Article/details/gtsnqklwwg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhoulong.xyz/Article/details/gtcxujcxxv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gzhubu.top/Article/details/gtdkyfktxe.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuetiantiany.cn/Article/details/gtmbxjjhvy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenzaomai.com/Article/details/gtpghlbhgi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.vqdsnc.cn/Article/details/gtowbfcpfn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenlongwang.top/Article/details/gtnslzqfbr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.9152youxi.cn/Article/details/gtozvtdvki.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cucudq.cn/Article/details/gtqmzyscqk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.c1oappe.top/Article/details/gttympmgps.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cqqwz.cn/Article/details/gtmdljtrxo.html

【文件统计】
来源：http://dali.yanxiufei.cn/Article/details/gtjisqbony.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yuanzhike.top/Article/details/gtecfdvlfm.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtotvhshso.html

目  录
来源：http://dali.haohaochexian.top/Article/details/gtgyubmzru.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfufdjfxt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gtxckpydwx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gtsgxmmslw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gtoasugclh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jqgufenzy.top/Article/details/gtqlktcjte.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zdqjudy.top/Article/details/gtoehzltkc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinqigfzy.top/Article/details/gtbexndzcm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtpprykjmd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.iojbl.cn/Article/details/gtghrwphyy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gtmpqegvqh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zdqjudy.top/Article/details/gthyxkhbwm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtwvtnpasy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpacpyqob.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtqmlpfmpm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gtftapdoir.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj20258888.top/Article/details/gtoombspgy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtktjjbzyb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtpyyfdltw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zycfv.cn/Article/details/gtvwksxrfe.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtaislwlod.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtoomdjiav.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtutthisfd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjsynemqe.html

A. 基础语法与类型
来源：http://dali.xuetiantiany.cn/Article/details/gtfjiyanha.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtupjmbcka.html

[A01] Hello World
来源：http://dali.ivvv.top/Article/details/gtsfhrkmhx.html

Py:   print("Hello, World!")
来源：http://dali.zhixingplan.top/Article/details/gtuduxprrw.html

PHP:  echo "Hello, World!";
来源：http://dali.zhongyouzk.top/Article/details/gtwnxmvexb.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtzcckiiiu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yueranfly.top/Article/details/gtevrtbtub.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gtlhrkyjuw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gtxtkurgkl.html

Ruby: puts "Hello, World!"
来源：http://dali.gotoacloud.top/Article/details/gtiuzxdahf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymwblraw.html

[A02] 变量声明与赋值
来源：http://dali.dashuyun.cn/Article/details/gtcomzjute.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.snrcjt.cn/Article/details/gtxxlfkvci.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtxmboegwq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cheryme.top/Article/details/gthafmzuxr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenzaomai.com/Article/details/gtnygkmrjf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtlqopgbhw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhongyouzk.top/Article/details/gtfachcytd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aizwys.cn/Article/details/gtndwpuegc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gthtgbgcbo.html

[A03] 常量定义
来源：http://dali.shzxlz.cn/Article/details/gtbabwrrby.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.andypj.xyz/Article/details/gtcuzjtbdh.html

PHP:  const PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gttshitisx.html

JS:   const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsxpafxm.html

TS:   const PI: number = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gttuguwerm.html

Java: static final double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtkkyfqstr.html

Go:   const PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gtambrxilj.html

Ruby: PI = 3.14159
来源：http://dali.hnqzz.top/Article/details/gtpqbqrbbx.html

C#:   const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtsqlhryrm.html

[A04] 判断变量类型
来源：http://dali.yuanzhike.top/Article/details/gtjaqmeedk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jlsjyb.cn/Article/details/gtjrhiuygq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yangfankeji.com/Article/details/gtuumfjxav.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.iojbl.cn/Article/details/gtwccxphax.html

TS:   typeof x; x instanceof Date
来源：http://dali.tian-w.cn/Article/details/gtvgpuvckn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.daria6918.cn/Article/details/gtvvuqvqzl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shangyingyoupin.top/Article/details/gtcvfkzddu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hammf.cn/Article/details/gtfhwkcpjg.html

C#:   x.GetType().Name; x is int
来源：http://dali.tianlin.xyz/Article/details/gtbkffaqip.html

[A05] 整数除法与取模
来源：http://dali.daria6918.cn/Article/details/gtyrdqjamd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hnqzz.top/Article/details/gtciazkhfe.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtrxdqospu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtnfadgqoq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtixsidvkh.html

Java: 7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtgrziflgb.html

Go:   7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtklbbcbkd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtmbjhkxrg.html

C#:   7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtuuqiucuy.html

[A06] 字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gticxurkzi.html

Py:   int("42"); float("3.14")
来源：http://dali.ydzc1.top/Article/details/gtediddhsp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpscvoozn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zycfv.cn/Article/details/gtkavxibel.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.bjfxy.top/Article/details/gtqzicdhvq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gtaisblfnt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sxryk.cn/Article/details/gtcqrylwtm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shuidangran.top/Article/details/gtffbqygkt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yuanzhike.top/Article/details/gtasmwacwp.html

[A07] 数字转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtlerutgnp.html

Py:   str(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtcogpwfxp.html

PHP:  (string) 42; strval(42)
来源：http://dali.tianlin.xyz/Article/details/gtwocjvdlo.html

JS:   String(42); (42).toString()
来源：http://dali.dashuyun.cn/Article/details/gtuhuoucek.html

TS:   String(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtuyisxjyz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jqgufenzy.top/Article/details/gtjbmvjdba.html

Go:   strconv.Itoa(42)
来源：http://dali.hysaishi.cn/Article/details/gttxpykvwv.html

Ruby: 42.to_s
来源：http://dali.gotoacloud.top/Article/details/gtdhwunfgw.html

C#:   42.ToString()
来源：http://dali.haohaochexian.top/Article/details/gtxubvrkih.html

[A08] 取整与四舍五入
来源：http://dali.meibo888.top/Article/details/gtilufgiam.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtclktywey.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.chenjidiqi.icu/Article/details/gtosshyngg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gtlwigkfqn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yuxming.cn/Article/details/gtqhkvvynh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gtnpzfyppv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cheryme.top/Article/details/gtxaswpltz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigufen.top/Article/details/gtgjlxlznt.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtqaddtvxe.html

[A09] 绝对值与最大最小值
来源：http://dali.yj202588.top/Article/details/gtkvznpxmc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gteqkmanzk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cashguo.top/Article/details/gtwuxdhcoa.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtdbkiioft.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtfuualmba.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtmvgtuuxy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gzhubu.top/Article/details/gtqgqrqsgw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yj202588.top/Article/details/gtrsotswsp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtkjkotyos.html

[A10] 生成随机数
来源：http://dali.tanke756.top/Article/details/gtxgflkvnq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.quarkkingdee.top/Article/details/gtvelbnjss.html

PHP:  random_int(1, 100);
来源：http://dali.snrcjt.cn/Article/details/gtshatkvop.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hnqzz.top/Article/details/gtydekalkt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.316326.xyz/Article/details/gtjlgajrkw.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jiagoushi.top/Article/details/gtlvtjkqbs.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cucudq.cn/Article/details/gteutpwxja.html

Ruby: rand(1..100)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkzvpejy.html

C#:   new Random().Next(1, 101)
来源：http://dali.sufxvd.cn/Article/details/gtsafryqis.html

[A11] 条件表达式（三元）
来源：http://dali.chenjidiqi.icu/Article/details/gtvrgxeeeh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gaohongyu789.top/Article/details/gtxjappntk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gtekmcljhp.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gtzqyjrtpr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gtfarbptzg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gtjuytgcjh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.mhx1999.top/Article/details/gtlrpqlyjs.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gtbpvitthq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtfcuumrtl.html

[A12] 字符串插值 / 格式化
来源：http://dali.cashguo.top/Article/details/gtkourfmza.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinqigufen.top/Article/details/gtzwkrhxna.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jianghu66.top/Article/details/gtgtunpnry.html

JS:   `Hello, ${name}!`
来源：http://dali.gogol.net.cn/Article/details/gtnotmqpbh.html

TS:   `Hello, ${name}!`
来源：http://dali.tianlin.xyz/Article/details/gtufvaroav.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cheryme.top/Article/details/gtwuklyuio.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.fzhhl.top/Article/details/gtcqyztqbo.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenlongwang.top/Article/details/gtebpahzwx.html

C#:   $"Hello, {name}!"
来源：http://dali.ivvv.top/Article/details/gtohafohlo.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.fengsongda.top/Article/details/gtqujjtoie.html

Py:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtmdhfwpbe.html

PHP:  "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gttiuvwptf.html

JS:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtljuujaeg.html

TS:   "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchqrskji.html


<!-- 参考信息 -->