代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.tianlin.xyz/Article/details/gt2ortmfwah.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gt2qhzdajhr.html

[U84] JS：CommonJS 写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iudlsmdm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.daxiang520.top/Article/details/gt2hsiwqxin.html

[U85] JS：可选链
来源：http://dali.yonumen.top/Article/details/gt2iwprwkpm.html

a?.b?.c
来源：http://dali.aizwys.cn/Article/details/gt2iqspgcwh.html

[U86] JS：空值合并
来源：http://dali.yangfankeji.com/Article/details/gt2vdoobakc.html

a ?? b
来源：http://dali.dianchejie.cn/Article/details/gt2dkjywrqv.html

[U87] JS：解构默认值
来源：http://dali.fengsongda.top/Article/details/gt2slbzsnag.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yangfankeji.com/Article/details/gt2mxxazwcq.html

[U88] JS：对象展开合并
来源：http://dali.jlsjyb.cn/Article/details/gt2gdjssyrx.html

{ ...a, ...b }
来源：http://dali.yj202588.top/Article/details/gt2vtwbzgfm.html

[U89] JS：数组去重
来源：http://dali.wangdashe.top/Article/details/gt2offusgvv.html

[...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gt2fxydemic.html

[U90] JS：数字数组排序
来源：http://dali.cucudq.cn/Article/details/gt2skiezrau.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gt2djtsjmru.html

[U91] JS：对象键值遍历
来源：http://dali.guannengcc.top/Article/details/gt2jnvfytum.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenjidiqi.icu/Article/details/gt2moxuasnb.html

[U92] JS：深拷贝
来源：http://dali.yj20258.top/Article/details/gt2wyhvuimq.html

structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2duspazfg.html

[U93] JS：模板字符串
来源：http://dali.yongpay.top/Article/details/gt2daxefooi.html

`共 ${n} 条`
来源：http://dali.cdnleiting.top/Article/details/gt2xbrvwbmn.html

[U94] JS：箭头函数
来源：http://dali.pycfn.com/Article/details/gt2iziyyjjr.html

const double = x => x * 2;
来源：http://dali.hnxiangtu.top/Article/details/gt2gmsnogfm.html

[U95] JS：Promise 包装
来源：http://dali.ydzc1.top/Article/details/gt2qzvuwvpc.html

new Promise((resolve, reject) => {})
来源：http://dali.9152youxi.cn/Article/details/gt2zvbjgpta.html

[U96] JS：async/await 与异常
来源：http://dali.jqgufenzy.top/Article/details/gt2bwjpalzw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2dujojpio.html

[U97] JS：并发请求
来源：http://dali.0kj1m.cn/Article/details/gt2yettmvto.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gt2vraqdutn.html

[U98] JS：fetch 带 JSON
来源：http://dali.hywenlv.cn/Article/details/gt2rgunjkwt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenlongwang.top/Article/details/gt2luemczko.html

[U99] JS：事件监听
来源：http://dali.yuanzhike.top/Article/details/gt2rxtujouq.html

el.addEventListener("click", e => {})
来源：http://dali.chenzaomai.com/Article/details/gt2cguvhpvo.html

[U100] JS：DOM 查询
来源：http://dali.cheryme.top/Article/details/gt2kkwuyxdx.html

document.querySelector(".item")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhexjjog.html

[U101] JS：classList 操作
来源：http://dali.yueranfly.top/Article/details/gt2imkqfimf.html

el.classList.toggle("active")
来源：http://dali.cqqwz.cn/Article/details/gt2joloznrf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrktwxs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yueranfly.top/Article/details/gt2duqlkyuk.html

[U103] JS：定时器
来源：http://dali.sysykeji.top/Article/details/gt2kmxscgis.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenlongwang.top/Article/details/gt2gsfkjris.html

[U104] JS：防抖
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezqkhmzb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2dipattzs.html

[U105] JS：节流
来源：http://dali.ivvv.top/Article/details/gt2zsrcjnng.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cashguo.top/Article/details/gt2oeovedpc.html

[U106] JS：日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2anctmtcu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ybcxt.top/Article/details/gt2zdxhibhy.html

[U107] JS：数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gt2palmjdsc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gt2lzijbfww.html

[U108] JS：随机整数
来源：http://dali.meibo888.top/Article/details/gt2dcniatyl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgfzy.top/Article/details/gt2pahohena.html

[U109] JS：数组分组
来源：http://dali.kuanghao11.cn/Article/details/gt2oqptvzwd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gt2pfnuiluw.html

[U110] JS：数组分块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngzallhb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xziqi.cn/Article/details/gt2vljzjciq.html

[U111] JS：对象转 Map
来源：http://dali.xylfe.cn/Article/details/gt2vogbdxyn.html

new Map(Object.entries(obj))
来源：http://dali.yueranfly.top/Article/details/gt2owcdapxv.html

[U112] JS：字符串补位
来源：http://dali.yj20258.top/Article/details/gt2dmizfxod.html

"7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2vslispaq.html

[U113] JS：正则替换全部
来源：http://dali.ehwqpu.com/Article/details/gt2voauxdef.html

s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2pnazncgp.html

[U114] JS：JSON 深比较
来源：http://dali.9152youxi.cn/Article/details/gt2yrrlhltw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yonumen.top/Article/details/gt2exsrsxsw.html

[U115] JS：生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gt2rzradevo.html

crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2qcyytatx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yongpay.top/Article/details/gt2ujyydcxs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gotoacloud.top/Article/details/gt2hbvhcfrr.html

[U117] JS：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cflclezk.html

npm i -D vitest;  npx vitest
来源：http://dali.jyoumei.cn/Article/details/gt2mhtwulkl.html

[U118] JS：开发服务器
来源：http://dali.sweek.top/Article/details/gt2juedawmb.html

npm i -D vite;  npx vite
来源：http://dali.yvedp.cn/Article/details/gt2vcflcnid.html

[U119] JS：生产构建
来源：http://dali.dashuyun.cn/Article/details/gt2cuwxpxsi.html

npx vite build
来源：http://dali.chenlongwang.top/Article/details/gt2wxkeoajk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gt2oqtuxvsy.html

import.meta.env.VITE_API_URL
来源：http://dali.ivvv.top/Article/details/gt2amrjxqsk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2vxpsrgml.html

统计汇总
来源：http://dali.hywenlv.cn/Article/details/gt2tsryqaca.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2fkypbcdl.html

按语言统计（条）：
来源：http://dali.zhongyouzk.top/Article/details/gt2tqpluxic.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gt2ohnklhfn.html

PHP ............ 252
来源：http://dali.nwbrower.top/Article/details/gt2efskhbpi.html

JavaScript ..... 252
来源：http://dali.nanxinkj.top/Article/details/gt2povknnnv.html

TypeScript ..... 212
来源：http://dali.hysaishi.cn/Article/details/gt2ynuggdyv.html

Java ........... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgwzxynx.html

Go ............. 212
来源：http://dali.redwolf501.top/Article/details/gt2cfauxuxd.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gt2cnlldfkg.html

C# ............. 212
来源：http://dali.xinyue.icu/Article/details/gt2mplgpelc.html

C .............. 30
来源：http://dali.zdqjudy.top/Article/details/gt2bryopdwl.html

C++ ............ 30
来源：http://dali.cqqwz.cn/Article/details/gt2gfbkayzd.html

SQL ............ 90
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wyelmivd.html

Bash ........... 80
来源：http://dali.zhixingplan.top/Article/details/gt2hvvbdtiw.html

Kotlin ......... 15
来源：http://dali.fengsongda.top/Article/details/gt2aeofejco.html

Swift .......... 15
来源：http://dali.shuidangran.top/Article/details/gt2qutlvuqx.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gt2txfnuovz.html

Perl ........... 10
来源：http://dali.yueranfly.top/Article/details/gt2meofbxbu.html

Scala .......... 10
来源：http://dali.gaohongyu789.top/Article/details/gt2ppzhldqq.html

------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2gsppqdat.html

合计 ........... 2106 条
来源：http://dali.bjfxy.top/Article/details/gt2cosdjqfs.html

按章节统计：
来源：http://dali.guannengcc.top/Article/details/gt2ngyxnvcj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gt2qomheunr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gt2syjrbtas.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gt2jzcbrbro.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jqgfzy.top/Article/details/gt2aylhdytx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shuidangran.top/Article/details/gt2pncbvwqj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gt2pymrjykd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gt2pxotoehz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gt2pnihdbda.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gt2jtrkfter.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yuanzhike.top/Article/details/gt2ajobmpfa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2xsefxbzl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2ysaihgde.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2pjgidjmz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gt2cgbhnqyl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hywenlv.cn/Article/details/gt2qksfskzo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2vpimktta.html

Q SQL 专题                              90
来源：http://dali.9152youxi.cn/Article/details/gt2jbjnxwug.html

R Bash 专题                             80
来源：http://dali.yj202588.top/Article/details/gt2sbuxpuqv.html

S C / C++ 专题                          60
来源：http://dali.sufxvd.cn/Article/details/gt2omsesupy.html

T 其他语言补充                          60
来源：http://dali.zhongyouzk.top/Article/details/gt2gotowjeg.html

U 高频实用片段                         120
来源：http://dali.hysaishi.cn/Article/details/gt2kbfcywqb.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2slxbqufn.html

合计                                  2106 条
来源：http://dali.sweek.top/Article/details/gt2ihlhbvtn.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gt2rsgkspzg.html

使用提醒
来源：http://dali.gaohongyu789.top/Article/details/gt2vtrvkeui.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gt2eoenxmah.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.fengsongda.top/Article/details/gt2bekpmsib.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sufxvd.cn/Article/details/gt2tccvjsdu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sxryk.cn/Article/details/gt2sucppfgf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ehwqpu.com/Article/details/gt2mnzyosln.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yangfankeji.com/Article/details/gt2sekqpbab.html

—— 文件结束 ——
来源：http://dali.sysykeji.top/Article/details/gt2qyhsehvq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2lkqrnhfp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.andypj.xyz/Article/details/gt2rnuswetz.html

Common Programming Examples Cheat Book
来源：http://dali.ybcxt.top/Article/details/gt2wxjavaei.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ugovhnme.html

【收录内容】
来源：http://dali.zhoulong.xyz/Article/details/gt2ciwbyqwy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yj20258.top/Article/details/gt2mipiyolo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hfpthk.cn/Article/details/gt2dcfurllv.html

SQL · Bash · C · C++
来源：http://dali.redwolf501.top/Article/details/gt2jtyeerxq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ehwqpu.com/Article/details/gt2rjlqsjgi.html

【使用说明】
来源：http://dali.cashguo.top/Article/details/gt2kkgacdja.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinqigufen.top/Article/details/gt2sfpyusez.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.316326.xyz/Article/details/gt2ycdrnkqp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hfpthk.cn/Article/details/gt2oidazdtx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cdnleiting.top/Article/details/gt2hirhytxd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.snrcjt.cn/Article/details/gt2pkyiknfc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.havefunace.top/Article/details/gt2hwavsmoc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yuxming.cn/Article/details/gt2baladyqd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.9152youxi.cn/Article/details/gt2ymsfsyna.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgfzy.top/Article/details/gt2bkxoewxk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.bjfxy.top/Article/details/gt2pjznjcff.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.pengpengdd.cyou/Article/details/gt2fpscvxbf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ppjwa.cn/Article/details/gt2ohgaywye.html

【文件统计】
来源：http://dali.sxryk.cn/Article/details/gt2eghigkzh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nanxinkj.top/Article/details/gt2xuadxifi.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gt2mnnwektj.html

目  录
来源：http://dali.zdqjudy.top/Article/details/gt2adqhgtvx.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2kffjxzyq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gt2pakjvcff.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gt2hgabozkd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2esovkjdr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jiagoushi.top/Article/details/gt2ubqoeoxd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2qwsudcpk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zavbewam.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2ooqacfyu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gt2rvspuqlq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsdbrcon.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqefdupg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2ektxhllk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2qaxxvcvc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2gfcimynr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2smhnycwo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sxryk.cn/Article/details/gt2hnmkrrsu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gt2igdaafnt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gsejzlzj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258888.top/Article/details/gt2krhmnurq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guannengcc.top/Article/details/gt2neoqekbi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gt2arxucdtw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gt2wdfnhptl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2dstcvtxc.html

A. 基础语法与类型
来源：http://dali.chenzaomai.com/Article/details/gt2idvjrcjf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2tusrzhik.html

[A01] Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2waxbfdti.html

Py:   print("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gt2jegmzcak.html

PHP:  echo "Hello, World!";
来源：http://dali.jinqigfzy.top/Article/details/gt2bhpheqcu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gt2lycrwoiz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xinyue.icu/Article/details/gt2jlehypqp.html

Java: System.out.println("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gt2fwaztkyy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tprljktc.html

Ruby: puts "Hello, World!"
来源：http://dali.sxryk.cn/Article/details/gt2xlnjkgil.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gotoacloud.top/Article/details/gt2icgzzgne.html

[A02] 变量声明与赋值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtxxlwep.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzxtqjly.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.meibo888.top/Article/details/gt2upoiurpc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shuidangran.top/Article/details/gt2vcethpsc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shuidangran.top/Article/details/gt2gzruddpa.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.smart0.xyz/Article/details/gt2oljzqery.html

Go:   name := "Alex"; age := 20
来源：http://dali.nwbrower.top/Article/details/gt2yidiuboe.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zdqjudy.top/Article/details/gt2qfshvwww.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kobjmyla.html

[A03] 常量定义
来源：http://dali.hfpthk.cn/Article/details/gt2ruzuyggl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cucudq.cn/Article/details/gt2nqcgdidp.html

PHP:  const PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mkheboiw.html

JS:   const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2ywmqcals.html

TS:   const PI: number = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gt2enpzzxpx.html

Java: static final double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdrfkbxy.html

Go:   const PI = 3.14159
来源：http://dali.yueranfly.top/Article/details/gt2mqxxbudt.html

Ruby: PI = 3.14159
来源：http://dali.ehwqpu.com/Article/details/gt2strdeloc.html

C#:   const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qerxyjdw.html

[A04] 判断变量类型
来源：http://dali.ivvv.top/Article/details/gt2ryjmcobe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hammf.cn/Article/details/gt2fhqkbuhb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxuanxn.top/Article/details/gt2dofbjduv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ehwqpu.com/Article/details/gt2ypqbdczw.html

TS:   typeof x; x instanceof Date
来源：http://dali.yuanzhike.top/Article/details/gt2orlppect.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ppjwa.cn/Article/details/gt2yzaiwnbq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cqqwz.cn/Article/details/gt2swbhlenj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.haohaochexian.top/Article/details/gt2gdtgvftf.html

C#:   x.GetType().Name; x is int
来源：http://dali.dashuyun.cn/Article/details/gt2clavogsg.html

[A05] 整数除法与取模
来源：http://dali.yonumen.top/Article/details/gt2sckcnpgq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivcyrqvy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gt2gltlgkge.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkxfspi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2canvfcyk.html

Java: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gt2wrlmuwuy.html

Go:   7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2teuyzmop.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2ugkmawud.html

C#:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gt2iuhajbfg.html

[A06] 字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gt2chctwbqs.html

Py:   int("42"); float("3.14")
来源：http://dali.yongpay.top/Article/details/gt2pbcuxxpk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.9152youxi.cn/Article/details/gt2zrewnshf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddresbsf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzffkimf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xinyue.icu/Article/details/gt2kewcvuje.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.haohaochexian.top/Article/details/gt2ilukwemh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zycfv.cn/Article/details/gt2mzsoevpr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxinkj.top/Article/details/gt2biisvqwy.html

[A07] 数字转字符串
来源：http://dali.andypj.xyz/Article/details/gt2xjbnebik.html

Py:   str(42)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ehgcqfeu.html

PHP:  (string) 42; strval(42)
来源：http://dali.ydzc1.top/Article/details/gt2nwlzizin.html

JS:   String(42); (42).toString()
来源：http://dali.redwolf501.top/Article/details/gt2zunzlxht.html

TS:   String(42)
来源：http://dali.zhixingplan.top/Article/details/gt2gibxfntp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.sufxvd.cn/Article/details/gt2unxfpjnp.html

Go:   strconv.Itoa(42)
来源：http://dali.yuxming.cn/Article/details/gt2wnqqohxq.html

Ruby: 42.to_s
来源：http://dali.zhengqikj.top/Article/details/gt2bxhkxdbp.html

C#:   42.ToString()
来源：http://dali.yueranfly.top/Article/details/gt2gyguikoo.html

[A08] 取整与四舍五入
来源：http://dali.cashguo.top/Article/details/gt2zjeityse.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gt2iytxmhey.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.iojbl.cn/Article/details/gt2fisspdso.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gt2hcnxdbbm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj20258.top/Article/details/gt2jacnldqu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gt2hdnimcdl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxhdwint.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tanke756.top/Article/details/gt2kldmfrye.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gt2psaswuwo.html

[A09] 绝对值与最大最小值
来源：http://dali.shzxlz.cn/Article/details/gt2dfxpwzha.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2frdpesxz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2syhpmvly.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xinyue.icu/Article/details/gt2upzsiqtx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cucudq.cn/Article/details/gt2ipgesfhn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2egkfygri.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.svipenyu.cn/Article/details/gt2wzakfxtt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.tianlin.xyz/Article/details/gt2qiarfohl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yj202588.top/Article/details/gt2wmoietnb.html

[A10] 生成随机数
来源：http://dali.gaohongyu789.top/Article/details/gt2hztdfdds.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yanxiufei.cn/Article/details/gt2wljqudnv.html

PHP:  random_int(1, 100);
来源：http://dali.shuidangran.top/Article/details/gt2pmevxiot.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258888.top/Article/details/gt2yegqbssm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldkidboi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2liyakzwq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sysykeji.top/Article/details/gt2xoonuxws.html

Ruby: rand(1..100)
来源：http://dali.shzxlz.cn/Article/details/gt2mhgqmfxd.html

C#:   new Random().Next(1, 101)
来源：http://dali.gotoacloud.top/Article/details/gt2yttzegbh.html

[A11] 条件表达式（三元）
来源：http://dali.zhoulong.xyz/Article/details/gt2ymemuegf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yj202588.top/Article/details/gt2mdbiwcue.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gt2ueeakeat.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gt2vpstpdhg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gt2mtnlcecz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gt2binzjgkg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.tian-w.cn/Article/details/gt2mrbaknlz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpynhblp.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghfloxfy.html

[A12] 字符串插值 / 格式化
来源：http://dali.hywenlv.cn/Article/details/gt2xngvgpwb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj20258.top/Article/details/gt2bekwlcxo.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmooywge.html

JS:   `Hello, ${name}!`
来源：http://dali.meibo888.top/Article/details/gt2sdanwqev.html

TS:   `Hello, ${name}!`
来源：http://dali.yuxming.cn/Article/details/gt2wdhdhvaa.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2meeehhsh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ehwqpu.com/Article/details/gt2pzechcwl.html

Ruby: "Hello, #{name}!"
来源：http://dali.wangdashe.top/Article/details/gt2qtloxltd.html

C#:   $"Hello, {name}!"
来源：http://dali.zhengqikj.top/Article/details/gt2axrhejdp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cqqwz.cn/Article/details/gt2rspfzlsd.html

Py:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gt2bxgwrqfl.html

PHP:  "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2eybifjme.html

JS:   "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gt2zocxlzbb.html

TS:   "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gt2fvmvjhhd.html

Java: "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gt2gnkoomxl.html

Go:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gt2aneqxjbt.html

Ruby: "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gt2oqqxaoyv.html

C#:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gt2frdzmzyg.html


<!-- 参考信息 -->