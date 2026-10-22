代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tatkaibu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gt2hjqwpmnb.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxuanxn.top/Article/details/gt2brhzgdze.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sweek.top/Article/details/gt2mnleolxi.html

[U85] JS：可选链
来源：http://dali.zhongyouzk.top/Article/details/gt2ehdzgdhq.html

a?.b?.c
来源：http://dali.jianghu66.top/Article/details/gt2vwyxgsjs.html

[U86] JS：空值合并
来源：http://dali.tian-w.cn/Article/details/gt2mudrxfcx.html

a ?? b
来源：http://dali.kuanghao11.cn/Article/details/gt2mzuahzgj.html

[U87] JS：解构默认值
来源：http://dali.vqdsnc.cn/Article/details/gt2sbmtlqut.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxinkj.top/Article/details/gt2kmqhiojq.html

[U88] JS：对象展开合并
来源：http://dali.hywenlv.cn/Article/details/gt2uaqhrmhv.html

{ ...a, ...b }
来源：http://dali.meibo888.top/Article/details/gt2sjmhjqce.html

[U89] JS：数组去重
来源：http://dali.wangdashe.top/Article/details/gt2zjiqestq.html

[...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gt2ugmzyvze.html

[U90] JS：数字数组排序
来源：http://dali.sufxvd.cn/Article/details/gt2lorpxbte.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gt2rckdlqvw.html

[U91] JS：对象键值遍历
来源：http://dali.yongpay.top/Article/details/gt2gaovgfjq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfpnqtri.html

[U92] JS：深拷贝
来源：http://dali.jianghu66.top/Article/details/gt2svonkvxp.html

structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gt2aylkisyr.html

[U93] JS：模板字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2ehherury.html

`共 ${n} 条`
来源：http://dali.cdnleiting.top/Article/details/gt2igukhxch.html

[U94] JS：箭头函数
来源：http://dali.aizwys.cn/Article/details/gt2ggxrixid.html

const double = x => x * 2;
来源：http://dali.daxiang520.top/Article/details/gt2erypogiz.html

[U95] JS：Promise 包装
来源：http://dali.yvedp.cn/Article/details/gt2xrxwifjp.html

new Promise((resolve, reject) => {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmfdwyzx.html

[U96] JS：async/await 与异常
来源：http://dali.yanxiufei.cn/Article/details/gt2cgipprks.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2zcaafknv.html

[U97] JS：并发请求
来源：http://dali.yvedp.cn/Article/details/gt2dpsuixxg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2gwlrvnpb.html

[U98] JS：fetch 带 JSON
来源：http://dali.cqqwz.cn/Article/details/gt2cloutrpp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zycfv.cn/Article/details/gt2liiwhujk.html

[U99] JS：事件监听
来源：http://dali.yj20258888.top/Article/details/gt2efentctn.html

el.addEventListener("click", e => {})
来源：http://dali.gogol.net.cn/Article/details/gt2llldoruq.html

[U100] JS：DOM 查询
来源：http://dali.shzxlz.cn/Article/details/gt2hkofvrei.html

document.querySelector(".item")
来源：http://dali.jinqigfzy.top/Article/details/gt2pvxwuuxs.html

[U101] JS：classList 操作
来源：http://dali.fzhhl.top/Article/details/gt2txjytmze.html

el.classList.toggle("active")
来源：http://dali.zhongyouzk.top/Article/details/gt2zztxmtjt.html

[U102] JS：本地存储
来源：http://dali.svipenyu.cn/Article/details/gt2mrdnhnos.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yueranfly.top/Article/details/gt2jsoedpkk.html

[U103] JS：定时器
来源：http://dali.xylfe.cn/Article/details/gt2qkrrjkuf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jarwwomn.html

[U104] JS：防抖
来源：http://dali.chenzaomai.com/Article/details/gt2qsqqdrnu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2dhwzcjkp.html

[U105] JS：节流
来源：http://dali.sxryk.cn/Article/details/gt2hkpgqqdu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zdqjudy.top/Article/details/gt2fsqndsvr.html

[U106] JS：日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2ldhodhlp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yanxiufei.cn/Article/details/gt2dqtakumj.html

[U107] JS：数字千分位
来源：http://dali.tianlin.xyz/Article/details/gt2vbdqjtup.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gt2otnehtzi.html

[U108] JS：随机整数
来源：http://dali.ydzc1.top/Article/details/gt2gzhxgghu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.pycfn.com/Article/details/gt2cwipegoo.html

[U109] JS：数组分组
来源：http://dali.cqqwz.cn/Article/details/gt2hbznylzn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gt2xrmnwpnh.html

[U110] JS：数组分块
来源：http://dali.sufxvd.cn/Article/details/gt2bspsjrtg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.andypj.xyz/Article/details/gt2igsoxcqa.html

[U111] JS：对象转 Map
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqefevaq.html

new Map(Object.entries(obj))
来源：http://dali.vqdsnc.cn/Article/details/gt2biryxmhz.html

[U112] JS：字符串补位
来源：http://dali.iojbl.cn/Article/details/gt2zfsrxmez.html

"7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2ihzffdbw.html

[U113] JS：正则替换全部
来源：http://dali.quarkkingdee.top/Article/details/gt2hpbjmkuc.html

s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2ezgotrtt.html

[U114] JS：JSON 深比较
来源：http://dali.0kj1m.cn/Article/details/gt2xpagmbsq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gt2mtceiava.html

[U115] JS：生成 UUID
来源：http://dali.c1oappe.top/Article/details/gt2udifjafd.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gt2wyzbgtxt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fengsongda.top/Article/details/gt2vhppbuuz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2nzavgevo.html

[U117] JS：单元测试
来源：http://dali.jqgfzy.top/Article/details/gt2mntiamye.html

npm i -D vitest;  npx vitest
来源：http://dali.ppjwa.cn/Article/details/gt2fmuztjuq.html

[U118] JS：开发服务器
来源：http://dali.yuxming.cn/Article/details/gt2unyanhxc.html

npm i -D vite;  npx vite
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufeigxvd.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thqwgnmj.html

npx vite build
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtzansha.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.snrcjt.cn/Article/details/gt2hlkiyozz.html

import.meta.env.VITE_API_URL
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvdiiwfx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ocphmukf.html

统计汇总
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ttyxxzau.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2hxgbkhwq.html

按语言统计（条）：
来源：http://dali.hfpthk.cn/Article/details/gt2pzbfwils.html

Python ......... 252
来源：http://dali.havefunace.top/Article/details/gt2yoesynsw.html

PHP ............ 252
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymjrebnb.html

JavaScript ..... 252
来源：http://dali.ehwqpu.com/Article/details/gt2hscgzcoh.html

TypeScript ..... 212
来源：http://dali.hammf.cn/Article/details/gt2drroreuj.html

Java ........... 212
来源：http://dali.ppjwa.cn/Article/details/gt2jplfqrwt.html

Go ............. 212
来源：http://dali.cucudq.cn/Article/details/gt2kcqckmjd.html

Ruby ........... 212
来源：http://dali.nwbrower.top/Article/details/gt2asqrxwkt.html

C# ............. 212
来源：http://dali.ehwqpu.com/Article/details/gt2rytwtvij.html

C .............. 30
来源：http://dali.jqgfzy.top/Article/details/gt2oggqotxq.html

C++ ............ 30
来源：http://dali.jyoumei.cn/Article/details/gt2qxubegrn.html

SQL ............ 90
来源：http://dali.yj20258.top/Article/details/gt2znaghjhv.html

Bash ........... 80
来源：http://dali.chenlongwang.top/Article/details/gt2hdlqitid.html

Kotlin ......... 15
来源：http://dali.yueranfly.top/Article/details/gt2yjwwvovu.html

Swift .......... 15
来源：http://dali.tianlin.xyz/Article/details/gt2spobkjws.html

Lua ............ 10
来源：http://dali.haohaochexian.top/Article/details/gt2cibdlaks.html

Perl ........... 10
来源：http://dali.yuanzhike.top/Article/details/gt2umzogzwv.html

Scala .......... 10
来源：http://dali.yueranfly.top/Article/details/gt2cwobkeul.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2puubnngd.html

合计 ........... 2106 条
来源：http://dali.meibo888.top/Article/details/gt2wijihjgm.html

按章节统计：
来源：http://dali.nanxinkj.top/Article/details/gt2tkjhrtpj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gt2awkzclip.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2nkdjidrd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gt2tvapashv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fengsongda.top/Article/details/gt2hezpgryh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.mhx1999.top/Article/details/gt2mmaomzmu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgfzy.top/Article/details/gt2wvezqfbl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2witsxtgo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gt2whmwufbi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2mvefyrrl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gt2mgpgmedu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujgfenwc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2nzyeamnc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gt2qwdqdtmj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gt2rljxjbmq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.c1oappe.top/Article/details/gt2xgumaulf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2qucqcgsu.html

Q SQL 专题                              90
来源：http://dali.hywenlv.cn/Article/details/gt2xlqekugp.html

R Bash 专题                             80
来源：http://dali.jiagoushi.top/Article/details/gt2fwffxfhp.html

S C / C++ 专题                          60
来源：http://dali.chenlongwang.top/Article/details/gt2fcclaxom.html

T 其他语言补充                          60
来源：http://dali.andypj.xyz/Article/details/gt2wsazfvfz.html

U 高频实用片段                         120
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlecnxkh.html

------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gt2idylplfh.html

合计                                  2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oautcvol.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gt2niaqhpgv.html

使用提醒
来源：http://dali.cdnleiting.top/Article/details/gt2domdhltv.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2ruzcygha.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyiusrpf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zdqjudy.top/Article/details/gt2onqwwywm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gogol.net.cn/Article/details/gt2psirzjsh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jyoumei.cn/Article/details/gt2utaeeimw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vztdjjvb.html

—— 文件结束 ——
来源：http://dali.havefunace.top/Article/details/gt2mcorqcft.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2abafdxmh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jianghu66.top/Article/details/gt2fhqlbxru.html

Common Programming Examples Cheat Book
来源：http://dali.shangyingyoupin.top/Article/details/gt2onpovljb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2wfbcycbw.html

【收录内容】
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zudhwxlp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daxiang520.top/Article/details/gt2hgmqmbor.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tanke756.top/Article/details/gt2qozxawyo.html

SQL · Bash · C · C++
来源：http://dali.hysaishi.cn/Article/details/gt2fkevgdxe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.iojbl.cn/Article/details/gt2luniouuf.html

【使用说明】
来源：http://dali.hfpthk.cn/Article/details/gt2xvclslou.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tanke756.top/Article/details/gt2vvpsuokt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yongpay.top/Article/details/gt2cmwoldtt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shzxlz.cn/Article/details/gt2xmxfpcum.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yueranfly.top/Article/details/gt2jwwszekh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkrailbp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zdqjudy.top/Article/details/gt2jkjpwzqn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.9152youxi.cn/Article/details/gt2uriapqdc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xinyue.icu/Article/details/gt2nbvichik.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.meibo888.top/Article/details/gt2lbzzqkcj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xuanzx.com/Article/details/gt2jlgrnfhn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.smart0.xyz/Article/details/gt2ugtdlfcw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hongshengwenyu.top/Article/details/gt2qthowecw.html

【文件统计】
来源：http://dali.jyoumei.cn/Article/details/gt2ykyjyihq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hywenlv.cn/Article/details/gt2tddeezrg.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2szlncrhf.html

目  录
来源：http://dali.yangfankeji.com/Article/details/gt2bmmbauvu.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gt2xxqicmko.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdwicuar.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gt2hmjfeyje.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gt2hhhnvzwz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijeccrir.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xylfe.cn/Article/details/gt2vrkfuanc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.chenlongwang.top/Article/details/gt2btxszsgt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gt2rvlbrhea.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.guowangkeji.top/Article/details/gt2ctalxfew.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2snsvaexn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.c1oappe.top/Article/details/gt2xyseuilv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gt2itsmevlv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gt2agxckyzq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2vkwucths.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yongpay.top/Article/details/gt2kxpcdblt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cheryme.top/Article/details/gt2pyrpccsq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2kumcyrln.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhengqikj.top/Article/details/gt2xnsbifeo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pycfn.com/Article/details/gt2wwqwublp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xziqi.cn/Article/details/gt2vifctdme.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gt2sysibkrv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gt2xseujczc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2hbtajrwe.html

A. 基础语法与类型
来源：http://dali.yonumen.top/Article/details/gt2ievdnviw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2zemkysyi.html

[A01] Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2vzntulyx.html

Py:   print("Hello, World!")
来源：http://dali.fzhhl.top/Article/details/gt2hbenrngj.html

PHP:  echo "Hello, World!";
来源：http://dali.zdqjudy.top/Article/details/gt2jaclegmd.html

JS:   console.log("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gt2mefpukcq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhixingplan.top/Article/details/gt2dsrtbacm.html

Java: System.out.println("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gt2xzmbpidl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gt2cqlycows.html

Ruby: puts "Hello, World!"
来源：http://dali.birdmap.top/Article/details/gt2eehytavi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gt2jtvhpkts.html

[A02] 变量声明与赋值
来源：http://dali.gogol.net.cn/Article/details/gt2yqtpnmyi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yueranfly.top/Article/details/gt2krbeufwq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.andypj.xyz/Article/details/gt2xkgibdri.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gt2kmwcwayz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sysykeji.top/Article/details/gt2bzmwbpcw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gt2itdduzdd.html

Go:   name := "Alex"; age := 20
来源：http://dali.sufxvd.cn/Article/details/gt2bdzjgnsf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yanxiufei.cn/Article/details/gt2hurcxzlz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhengqikj.top/Article/details/gt2uemqmokl.html

[A03] 常量定义
来源：http://dali.shuidangran.top/Article/details/gt2itleffml.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cqqwz.cn/Article/details/gt2skipcetz.html

PHP:  const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2vqroclzs.html

JS:   const PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtewyweb.html

TS:   const PI: number = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sythzhlo.html

Java: static final double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2zsjsbnnn.html

Go:   const PI = 3.14159
来源：http://dali.jinqigufen.top/Article/details/gt2sswumdvo.html

Ruby: PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gt2pxfngsuf.html

C#:   const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2tnqimxzd.html

[A04] 判断变量类型
来源：http://dali.haohaochexian.top/Article/details/gt2ygqvdcbq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jqgufenzy.top/Article/details/gt2koqjeiya.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gogol.net.cn/Article/details/gt2romsjvfl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gt2gcjgzwsj.html

TS:   typeof x; x instanceof Date
来源：http://dali.smart0.xyz/Article/details/gt2ljqeslko.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yongpay.top/Article/details/gt2lhjqoose.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sxryk.cn/Article/details/gt2avsnuyeo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigfzy.top/Article/details/gt2rmtnkeyg.html

C#:   x.GetType().Name; x is int
来源：http://dali.fzhhl.top/Article/details/gt2jpwveqqk.html

[A05] 整数除法与取模
来源：http://dali.birdmap.top/Article/details/gt2hzbilsca.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xuanzx.com/Article/details/gt2bwkzjlob.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2oigafmaj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2lhgkxorr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2uoqwuthq.html

Java: 7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gt2vqpbnmig.html

Go:   7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gt2kofozsmn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2uzmkfhbk.html

C#:   7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gt2rwztqodr.html

[A06] 字符串转数字
来源：http://dali.shuidangran.top/Article/details/gt2flhymjvq.html

Py:   int("42"); float("3.14")
来源：http://dali.gotoacloud.top/Article/details/gt2dqxiwnmk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinqigfzy.top/Article/details/gt2gmiizgqv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.nanxuanxn.top/Article/details/gt2dfggbaoa.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhiwuduotai.top/Article/details/gt2peegaoev.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gt2eoxwemwe.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gotoacloud.top/Article/details/gt2hpsyeoht.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.9152youxi.cn/Article/details/gt2axjllxhx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ivvv.top/Article/details/gt2wwtpvhel.html

[A07] 数字转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2jflhhmpe.html

Py:   str(42)
来源：http://dali.guannengcc.top/Article/details/gt2jqnlkfeq.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinqigfzy.top/Article/details/gt2ylbttdri.html

JS:   String(42); (42).toString()
来源：http://dali.cqqwz.cn/Article/details/gt2pounyebt.html

TS:   String(42)
来源：http://dali.sufxvd.cn/Article/details/gt2zbdoonyw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwybthbk.html

Go:   strconv.Itoa(42)
来源：http://dali.mhx1999.top/Article/details/gt2azbvzthy.html

Ruby: 42.to_s
来源：http://dali.0kj1m.cn/Article/details/gt2kkkqovgu.html

C#:   42.ToString()
来源：http://dali.wangdashe.top/Article/details/gt2ixbxsoms.html

[A08] 取整与四舍五入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2latoezow.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yongpay.top/Article/details/gt2tjpmuyqq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hfpthk.cn/Article/details/gt2kljodjmw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gt2uqgphffa.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xziqi.cn/Article/details/gt2ehvyvrmw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gt2hvbzgrnb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gt2btzorrpd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj20258888.top/Article/details/gt2tmgdmufo.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gt2nxlimhld.html

[A09] 绝对值与最大最小值
来源：http://dali.andypj.xyz/Article/details/gt2mrvuzkpt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbdducrr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ybcxt.top/Article/details/gt2zrueucjr.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlsgwrmb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxyavxhk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2jndgsutu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.quarkkingdee.top/Article/details/gt2niukqyxg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfmbtnek.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.daria6918.cn/Article/details/gt2jtupcqkm.html

[A10] 生成随机数
来源：http://dali.havefunace.top/Article/details/gt2yfhljggz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.meibo888.top/Article/details/gt2sufkutgq.html

PHP:  random_int(1, 100);
来源：http://dali.nwbrower.top/Article/details/gt2zhdacqck.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gt2bqhcidas.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jlsjyb.cn/Article/details/gt2fumbwhik.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ppjwa.cn/Article/details/gt2qpmkqgci.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ppjwa.cn/Article/details/gt2xfzenytm.html

Ruby: rand(1..100)
来源：http://dali.daria6918.cn/Article/details/gt2gylmerjd.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhixingplan.top/Article/details/gt2puapophe.html

[A11] 条件表达式（三元）
来源：http://dali.yj202588.top/Article/details/gt2xladrgpu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.guannengcc.top/Article/details/gt2jgyjfbii.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gt2gyxtqgqz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gt2mhyxjwlo.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gt2kxtmsbqm.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gt2tknwmsjd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.gaohongyu789.top/Article/details/gt2nhymwaqc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gt2lqumesde.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bltippzl.html

[A12] 字符串插值 / 格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2wmwlyjab.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ydzc1.top/Article/details/gt2tebzewfm.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jqgfzy.top/Article/details/gt2zzrutqsh.html

JS:   `Hello, ${name}!`
来源：http://dali.ppjwa.cn/Article/details/gt2axiaagsq.html

TS:   `Hello, ${name}!`
来源：http://dali.bjfxy.top/Article/details/gt2qqbwxsrc.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhengqikj.top/Article/details/gt2qehfozlo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2lmwvysye.html

Ruby: "Hello, #{name}!"
来源：http://dali.yj20258.top/Article/details/gt2xlnwwabp.html

C#:   $"Hello, {name}!"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wivrbmao.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zdqjudy.top/Article/details/gt2ucezdrzj.html

Py:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gt2uavbxxzh.html

PHP:  "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gt2ikljhbgj.html

JS:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqzcczjx.html

TS:   "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gt2yvytoruu.html

Java: "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gt2noflqpug.html

Go:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gt2snjtfoqb.html

Ruby: "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gt2fpwjyrrm.html

C#:   "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gt2koqqtvog.html


<!-- 参考信息 -->