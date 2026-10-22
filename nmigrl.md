代发 wailian999

[U81] JS：初始化项目
来源：http://dali.haohaochexian.top/Article/details/gtmznhsxdn.html

npm init -y;  npm i express
来源：http://dali.gzhubu.top/Article/details/gtrcenjnvt.html

[U82] JS：package.json 脚本
来源：http://dali.jinqigfzy.top/Article/details/gtzrltsskl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dashuyun.cn/Article/details/gtdqacdgxx.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgfzy.top/Article/details/gtltqbaino.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gtntzebohj.html

[U84] JS：CommonJS 写法
来源：http://dali.hywenlv.cn/Article/details/gtiwbytvhz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shuidangran.top/Article/details/gtdrwwzhwt.html

[U85] JS：可选链
来源：http://dali.iojbl.cn/Article/details/gtfnrfdqhc.html

a?.b?.c
来源：http://dali.jlsjyb.cn/Article/details/gtisubbssa.html

[U86] JS：空值合并
来源：http://dali.guannengcc.top/Article/details/gtksnaondm.html

a ?? b
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzakyhjv.html

[U87] JS：解构默认值
来源：http://dali.jiagoushi.top/Article/details/gtedkqemqz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gtvjhxjrqw.html

[U88] JS：对象展开合并
来源：http://dali.havefunace.top/Article/details/gtzgrtlidd.html

{ ...a, ...b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgfvpfgg.html

[U89] JS：数组去重
来源：http://dali.yvedp.cn/Article/details/gthcbhfqru.html

[...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gtllquihvg.html

[U90] JS：数字数组排序
来源：http://dali.yongpay.top/Article/details/gtlxypgwmn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunwlefnc.html

[U91] JS：对象键值遍历
来源：http://dali.yuanzhike.top/Article/details/gtnexugmez.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ehwqpu.com/Article/details/gtrtjxqkpg.html

[U92] JS：深拷贝
来源：http://dali.havefunace.top/Article/details/gtzqhxpxwj.html

structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzgmgqza.html

[U93] JS：模板字符串
来源：http://dali.dianchejie.cn/Article/details/gtqsfxxruz.html

`共 ${n} 条`
来源：http://dali.ydzc1.top/Article/details/gtyocqywld.html

[U94] JS：箭头函数
来源：http://dali.fengsongda.top/Article/details/gthnaosksi.html

const double = x => x * 2;
来源：http://dali.tianlin.xyz/Article/details/gtulhnlgjm.html

[U95] JS：Promise 包装
来源：http://dali.yvedp.cn/Article/details/gtyvyynnme.html

new Promise((resolve, reject) => {})
来源：http://dali.sufxvd.cn/Article/details/gtapruxwmi.html

[U96] JS：async/await 与异常
来源：http://dali.ivvv.top/Article/details/gtwqruuzgx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtosfltgli.html

[U97] JS：并发请求
来源：http://dali.yonumen.top/Article/details/gtvxfmebdo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gttyhsgwin.html

[U98] JS：fetch 带 JSON
来源：http://dali.zdqjudy.top/Article/details/gtdpxrflso.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.aizwys.cn/Article/details/gtuglhmazr.html

[U99] JS：事件监听
来源：http://dali.tian-w.cn/Article/details/gtymfasybx.html

el.addEventListener("click", e => {})
来源：http://dali.yueranfly.top/Article/details/gtgxyxgsyw.html

[U100] JS：DOM 查询
来源：http://dali.pycfn.com/Article/details/gtojbuucni.html

document.querySelector(".item")
来源：http://dali.shangyingyoupin.top/Article/details/gtdcdwkxvb.html

[U101] JS：classList 操作
来源：http://dali.dianchejie.cn/Article/details/gtkybuazta.html

el.classList.toggle("active")
来源：http://dali.cheryme.top/Article/details/gthhcegrvw.html

[U102] JS：本地存储
来源：http://dali.chenjidiqi.icu/Article/details/gtdmkdpbhu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sufxvd.cn/Article/details/gtwgomecwr.html

[U103] JS：定时器
来源：http://dali.zhiwuduotai.top/Article/details/gtbcektgay.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ydzc1.top/Article/details/gtsiwupyth.html

[U104] JS：防抖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnwnrqqb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtgovszaaa.html

[U105] JS：节流
来源：http://dali.nanxuanxn.top/Article/details/gtbhkxezjz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxuanxn.top/Article/details/gtglftutyc.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlasosgmv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gotoacloud.top/Article/details/gtepccrmla.html

[U107] JS：数字千分位
来源：http://dali.guannengcc.top/Article/details/gtnlqtmzea.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaajcepv.html

[U108] JS：随机整数
来源：http://dali.zhixingplan.top/Article/details/gtbtbnovuo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daria6918.cn/Article/details/gtwwwedljl.html

[U109] JS：数组分组
来源：http://dali.svipenyu.cn/Article/details/gtrmwvfcft.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gtnxurgqvk.html

[U110] JS：数组分块
来源：http://dali.tianlin.xyz/Article/details/gtjkvsihty.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jlsjyb.cn/Article/details/gtlfesrpeg.html

[U111] JS：对象转 Map
来源：http://dali.iojbl.cn/Article/details/gtcomslbmm.html

new Map(Object.entries(obj))
来源：http://dali.aibaodan.cn/Article/details/gtyxgfzkae.html

[U112] JS：字符串补位
来源：http://dali.nwbrower.top/Article/details/gtsnijygko.html

"7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtuvxwnznh.html

[U113] JS：正则替换全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnttycdcq.html

s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtnyfkvhrz.html

[U114] JS：JSON 深比较
来源：http://dali.meibo888.top/Article/details/gthvruezjb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gthshzgrau.html

[U115] JS：生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyltgrrdm.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtofzukmof.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yonumen.top/Article/details/gtdqxlhtrb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dianchejie.cn/Article/details/gtxjppqzpv.html

[U117] JS：单元测试
来源：http://dali.hnqzz.top/Article/details/gturqlsoxz.html

npm i -D vitest;  npx vitest
来源：http://dali.sysykeji.top/Article/details/gtgaopfapo.html

[U118] JS：开发服务器
来源：http://dali.yanxiufei.cn/Article/details/gtxjajmjxw.html

npm i -D vite;  npx vite
来源：http://dali.meibo888.top/Article/details/gtoemdvtzi.html

[U119] JS：生产构建
来源：http://dali.yuanzhike.top/Article/details/gtbhfzilvp.html

npx vite build
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngmkponb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fengsongda.top/Article/details/gtwqgmlmlo.html

import.meta.env.VITE_API_URL
来源：http://dali.cashguo.top/Article/details/gtehgycimz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcwnqqgdx.html

统计汇总
来源：http://dali.chenjidiqi.icu/Article/details/gtrwlhsjja.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtocdoknvd.html

按语言统计（条）：
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyiifyzn.html

Python ......... 252
来源：http://dali.andypj.xyz/Article/details/gtbqnheqwc.html

PHP ............ 252
来源：http://dali.pycfn.com/Article/details/gthdyfmohy.html

JavaScript ..... 252
来源：http://dali.yj20258888.top/Article/details/gtwgrswsgi.html

TypeScript ..... 212
来源：http://dali.yongpay.top/Article/details/gtwxhgyzwy.html

Java ........... 212
来源：http://dali.sufxvd.cn/Article/details/gtqftlueub.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gtlortdwak.html

Ruby ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtojrlxohg.html

C# ............. 212
来源：http://dali.cashguo.top/Article/details/gtevikuouo.html

C .............. 30
来源：http://dali.dianchejie.cn/Article/details/gtcluxluxt.html

C++ ............ 30
来源：http://dali.cqqwz.cn/Article/details/gtwuykjqed.html

SQL ............ 90
来源：http://dali.zhongyouzk.top/Article/details/gtvgmznhjk.html

Bash ........... 80
来源：http://dali.dashuyun.cn/Article/details/gtyqfvqolx.html

Kotlin ......... 15
来源：http://dali.ivvv.top/Article/details/gtqyftommb.html

Swift .......... 15
来源：http://dali.wangdashe.top/Article/details/gtnidcxunb.html

Lua ............ 10
来源：http://dali.gogol.net.cn/Article/details/gtsrhaigjh.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtmylihaxm.html

Scala .......... 10
来源：http://dali.cdnleiting.top/Article/details/gtfpgfqrvm.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtmozmieet.html

合计 ........... 2106 条
来源：http://dali.ydzc1.top/Article/details/gtfglsdsuj.html

按章节统计：
来源：http://dali.chenzaomai.com/Article/details/gtdudknjmp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gtfagismnc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtgwhciwrs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtpaapzmqa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gtlunwghhx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.svipenyu.cn/Article/details/gtbfyffhiz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gtwkbxxskn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gtkyzrgciu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.haohaochexian.top/Article/details/gtgnvqywgb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtjikbxikv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gtrxsjjeao.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtzxojqnms.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtokmknywl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtzxbnpppo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gtbzvguoub.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.feifeiyinyue.top/Article/details/gtvqberqvc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtvrijjyiy.html

Q SQL 专题                              90
来源：http://dali.shangyingyoupin.top/Article/details/gtzdahaphu.html

R Bash 专题                             80
来源：http://dali.yuxming.cn/Article/details/gtgprfyvcj.html

S C / C++ 专题                          60
来源：http://dali.jinqigfzy.top/Article/details/gtlfpolmjk.html

T 其他语言补充                          60
来源：http://dali.yj20258888.top/Article/details/gtwwpomiug.html

U 高频实用片段                         120
来源：http://dali.jqgufenzy.top/Article/details/gtewaewhkl.html

------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtbuvrbzxw.html

合计                                  2106 条
来源：http://dali.sxryk.cn/Article/details/gtpkakyqhk.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtvhtstfwe.html

使用提醒
来源：http://dali.zhixingplan.top/Article/details/gtpwzjnatc.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtlmgftuub.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.316326.xyz/Article/details/gtfrotuqho.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ivvv.top/Article/details/gtsltmbkas.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.guowangkeji.top/Article/details/gtseeensbj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.havefunace.top/Article/details/gtqcytwbyw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shangyingyoupin.top/Article/details/gtxqjbclky.html

—— 文件结束 ——
来源：http://dali.hongshengwenyu.top/Article/details/gtawtjawsv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlgdwiidu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xziqi.cn/Article/details/gtofkawceg.html

Common Programming Examples Cheat Book
来源：http://dali.shanyushiyangtech.top/Article/details/gttgzmyqsb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtomamcxig.html

【收录内容】
来源：http://dali.sxryk.cn/Article/details/gtxozwckim.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ehwqpu.com/Article/details/gtbqwtpfxz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhoulong.xyz/Article/details/gtzmqyfmkg.html

SQL · Bash · C · C++
来源：http://dali.hongshengwenyu.top/Article/details/gtabpvrzzu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zdqjudy.top/Article/details/gtqwnykgap.html

【使用说明】
来源：http://dali.shanyushiyangtech.top/Article/details/gtcelunwae.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jiagoushi.top/Article/details/gtcrslmydg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhiwuduotai.top/Article/details/gtbcjnfipa.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nwbrower.top/Article/details/gtxprnssil.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ivvv.top/Article/details/gthbhpsgan.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenjidiqi.icu/Article/details/gtpuszsche.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj202588.top/Article/details/gtackuyxao.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gotoacloud.top/Article/details/gthgsxpjpg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hongshengwenyu.top/Article/details/gtmeefvght.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkdckopd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yangfankeji.com/Article/details/gtuiabnmsn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xylfe.cn/Article/details/gtzeqimrqb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.9152youxi.cn/Article/details/gtcrwxcldp.html

【文件统计】
来源：http://dali.guowangkeji.top/Article/details/gtejmsouzt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cqqwz.cn/Article/details/gtxctvpkpy.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtlgwsatqy.html

目  录
来源：http://dali.cdnleiting.top/Article/details/gtoafsjgjv.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtxqqdkoag.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yanxiufei.cn/Article/details/gtrdjaahkg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.c1oappe.top/Article/details/gtxynwguxq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gttqlaqqaq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gtynmsfxrg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.smart0.xyz/Article/details/gtjtkxufsl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbsunyok.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtuasknjna.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.meibo888.top/Article/details/gtkhkhnyll.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtrixuclxs.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yuxming.cn/Article/details/gtuyzvbmgn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtftneliwf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtryurugxb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtieauwgfc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.redwolf501.top/Article/details/gtmahykoct.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinqigfzy.top/Article/details/gtbabdwogf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtetzcxtwb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ivvv.top/Article/details/gtxsdlmlkl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtkvfebtuj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gotoacloud.top/Article/details/gthnldeluk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gtgszeyhzq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gtpavvdgsr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gteynnhjsk.html

A. 基础语法与类型
来源：http://dali.haohaochexian.top/Article/details/gtyjrzcoby.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfhizbnud.html

[A01] Hello World
来源：http://dali.aibaodan.cn/Article/details/gtareavlto.html

Py:   print("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gtwnxgqocz.html

PHP:  echo "Hello, World!";
来源：http://dali.hysaishi.cn/Article/details/gteazoyhjp.html

JS:   console.log("Hello, World!");
来源：http://dali.9152youxi.cn/Article/details/gtifovfdju.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zdqjudy.top/Article/details/gtkwpfojks.html

Java: System.out.println("Hello, World!");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthroivmqo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.wangshuangyany.cn/Article/details/gtzghmtypb.html

Ruby: puts "Hello, World!"
来源：http://dali.zdqjudy.top/Article/details/gtnjravqia.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shuidangran.top/Article/details/gtmxliipsc.html

[A02] 变量声明与赋值
来源：http://dali.zycfv.cn/Article/details/gtfatfqaqh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yangfankeji.com/Article/details/gtamtaujbx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaepwwnig.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.bjfxy.top/Article/details/gtrdtqyyog.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ivvv.top/Article/details/gtuvzqfyij.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcwxxsfh.html

Go:   name := "Alex"; age := 20
来源：http://dali.havefunace.top/Article/details/gtcazysfjf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuanzx.com/Article/details/gtjbxlshzg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtqhwllnsm.html

[A03] 常量定义
来源：http://dali.zhiwuduotai.top/Article/details/gtwupkahtu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nwbrower.top/Article/details/gtcsndrkhf.html

PHP:  const PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtxwztuqqv.html

JS:   const PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtqsbiqbmk.html

TS:   const PI: number = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtqdbbtaks.html

Java: static final double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtnbwbwpnb.html

Go:   const PI = 3.14159
来源：http://dali.pycfn.com/Article/details/gtckuxqqjl.html

Ruby: PI = 3.14159
来源：http://dali.chenjidiqi.icu/Article/details/gttufrjxtq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gthbdswyey.html

[A04] 判断变量类型
来源：http://dali.dashuyun.cn/Article/details/gtdeqdruea.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cdnleiting.top/Article/details/gtihussofz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.haohaochexian.top/Article/details/gtuqcttvvw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.9152youxi.cn/Article/details/gtutkbljhb.html

TS:   typeof x; x instanceof Date
来源：http://dali.yongpay.top/Article/details/gtxjrmbgbs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangshuangyany.cn/Article/details/gtfsyveblg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shzxlz.cn/Article/details/gtckjsnlss.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xuetiantiany.cn/Article/details/gtbzbpgkut.html

C#:   x.GetType().Name; x is int
来源：http://dali.gaohongyu789.top/Article/details/gtvqlzeegv.html

[A05] 整数除法与取模
来源：http://dali.yvedp.cn/Article/details/gtfpkgtjxu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gzhubu.top/Article/details/gttjwlwhkg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtfqimlfnt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtnxgreeqi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtvbijsjdr.html

Java: 7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtcdzfblhx.html

Go:   7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtnlbynorr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtzugumasr.html

C#:   7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtjubbnuic.html

[A06] 字符串转数字
来源：http://dali.hammf.cn/Article/details/gtyzvzalfn.html

Py:   int("42"); float("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gtyozundmb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shangyingyoupin.top/Article/details/gtwrijhcxr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangdashe.top/Article/details/gtfbsvlplu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xuetiantiany.cn/Article/details/gtyajlpzhn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.havefunace.top/Article/details/gtchbqmvie.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.0kj1m.cn/Article/details/gtnleqsyob.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvozwvoc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hfpthk.cn/Article/details/gtufrtcgdn.html

[A07] 数字转字符串
来源：http://dali.gogol.net.cn/Article/details/gtvuwcmtxp.html

Py:   str(42)
来源：http://dali.yongpay.top/Article/details/gtxczhznak.html

PHP:  (string) 42; strval(42)
来源：http://dali.smart0.xyz/Article/details/gtmcgrfusz.html

JS:   String(42); (42).toString()
来源：http://dali.sxryk.cn/Article/details/gtveumbidj.html

TS:   String(42)
来源：http://dali.yonumen.top/Article/details/gtszabujjc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cheryme.top/Article/details/gtiwbimzvs.html

Go:   strconv.Itoa(42)
来源：http://dali.tian-w.cn/Article/details/gtvibqyrau.html

Ruby: 42.to_s
来源：http://dali.jlsjyb.cn/Article/details/gtbwvparpk.html

C#:   42.ToString()
来源：http://dali.yongpay.top/Article/details/gtuaphihab.html

[A08] 取整与四舍五入
来源：http://dali.jqgfzy.top/Article/details/gtizusczmo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtbogdcggn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nanxuanxn.top/Article/details/gtyzanzdqy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtremevsqd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.vqdsnc.cn/Article/details/gtfevprhik.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gtyghsmham.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtkgwwjtfa.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cqqwz.cn/Article/details/gtuwwooehc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gtwvupvabz.html

[A09] 绝对值与最大最小值
来源：http://dali.chenlongwang.top/Article/details/gtkeghirku.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtyxjscdoz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtzpoktqxz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtyqrcvqfk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gteegsmfya.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtrvxngvfn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yangfankeji.com/Article/details/gtpzeqzxik.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.wangdashe.top/Article/details/gtkttutlcr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtacqnyfeh.html

[A10] 生成随机数
来源：http://dali.hysaishi.cn/Article/details/gtpgftcsdt.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhixingplan.top/Article/details/gtspqvrqxj.html

PHP:  random_int(1, 100);
来源：http://dali.cdnleiting.top/Article/details/gtajutvpra.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aibaodan.cn/Article/details/gtxrgalcxg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yongpay.top/Article/details/gtnhpubhsv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.gogol.net.cn/Article/details/gtntmnmukc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.iojbl.cn/Article/details/gtradjeerm.html

Ruby: rand(1..100)
来源：http://dali.zhoulong.xyz/Article/details/gtrguiojxu.html

C#:   new Random().Next(1, 101)
来源：http://dali.9152youxi.cn/Article/details/gtaugihgrx.html

[A11] 条件表达式（三元）
来源：http://dali.jinqigfzy.top/Article/details/gtolhzoask.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tanke756.top/Article/details/gtwvoqyyts.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtvbbxhb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gtyvkdyghw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gtwroobunu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gtptrwktwv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.svipenyu.cn/Article/details/gtrorzibky.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gtygvbsuwy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtveoqzovn.html

[A12] 字符串插值 / 格式化
来源：http://dali.birdmap.top/Article/details/gtwqgnbehi.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.nwbrower.top/Article/details/gtvayvcevc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.316326.xyz/Article/details/gterulfdtz.html

JS:   `Hello, ${name}!`
来源：http://dali.pycfn.com/Article/details/gtvqbchtvk.html

TS:   `Hello, ${name}!`
来源：http://dali.316326.xyz/Article/details/gtsglwuuck.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yuanzhike.top/Article/details/gtifyyxoly.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxwguhhm.html

Ruby: "Hello, #{name}!"
来源：http://dali.jqgfzy.top/Article/details/gttusuflep.html

C#:   $"Hello, {name}!"
来源：http://dali.xziqi.cn/Article/details/gtzvzlndbn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yanxiufei.cn/Article/details/gtmylncxwj.html

Py:   "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtdnjohfis.html

PHP:  "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtlhizwfms.html

JS:   "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtwebhqwuk.html

TS:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtzclayzid.html


<!-- 参考信息 -->