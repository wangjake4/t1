代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.fengsongda.top/Article/details/gt2ztfvyaqy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gt2vepkpxuj.html

[U84] JS：CommonJS 写法
来源：http://dali.hnqzz.top/Article/details/gt2fmrlrldx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.mhx1999.top/Article/details/gt2izclhcfe.html

[U85] JS：可选链
来源：http://dali.nanxinkj.top/Article/details/gt2wnpiwcal.html

a?.b?.c
来源：http://dali.zhixingplan.top/Article/details/gt2fxgalitm.html

[U86] JS：空值合并
来源：http://dali.yj202588.top/Article/details/gt2regjpjaf.html

a ?? b
来源：http://dali.dashuyun.cn/Article/details/gt2voynwzpe.html

[U87] JS：解构默认值
来源：http://dali.daria6918.cn/Article/details/gt2gxpqrjil.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ybcxt.top/Article/details/gt2ednxpior.html

[U88] JS：对象展开合并
来源：http://dali.chenlongwang.top/Article/details/gt2zeemzmcn.html

{ ...a, ...b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obupqsqv.html

[U89] JS：数组去重
来源：http://dali.chenlongwang.top/Article/details/gt2whdfluqe.html

[...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2wmytzdxn.html

[U90] JS：数字数组排序
来源：http://dali.cucudq.cn/Article/details/gt2fvimzxet.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2djhmglhj.html

[U91] JS：对象键值遍历
来源：http://dali.zdqjudy.top/Article/details/gt2uwzkgehq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymrcugif.html

[U92] JS：深拷贝
来源：http://dali.yanxiufei.cn/Article/details/gt2wsskjqzj.html

structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2rqkhcfjt.html

[U93] JS：模板字符串
来源：http://dali.birdmap.top/Article/details/gt2vnbmbkck.html

`共 ${n} 条`
来源：http://dali.ehwqpu.com/Article/details/gt2rbemsooe.html

[U94] JS：箭头函数
来源：http://dali.fzhhl.top/Article/details/gt2edisdmhh.html

const double = x => x * 2;
来源：http://dali.bjfxy.top/Article/details/gt2fbpvvesn.html

[U95] JS：Promise 包装
来源：http://dali.tianlin.xyz/Article/details/gt2iuolkksh.html

new Promise((resolve, reject) => {})
来源：http://dali.hywenlv.cn/Article/details/gt2iaxaucat.html

[U96] JS：async/await 与异常
来源：http://dali.zhoulong.xyz/Article/details/gt2wbztwcma.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gt2fvrbrtmv.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gt2dqwohfmd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2jeradrli.html

[U98] JS：fetch 带 JSON
来源：http://dali.316326.xyz/Article/details/gt2hzjznbmr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jianghu66.top/Article/details/gt2dqawhutv.html

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gt2zttrqguk.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258888.top/Article/details/gt2xqunbhwz.html

[U100] JS：DOM 查询
来源：http://dali.havefunace.top/Article/details/gt2nuapxymd.html

document.querySelector(".item")
来源：http://dali.shzxlz.cn/Article/details/gt2adhcxvmu.html

[U101] JS：classList 操作
来源：http://dali.cdnleiting.top/Article/details/gt2cjfufsqx.html

el.classList.toggle("active")
来源：http://dali.gogol.net.cn/Article/details/gt2xudgmmzq.html

[U102] JS：本地存储
来源：http://dali.nanxinkj.top/Article/details/gt2eirgqyjb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ppjwa.cn/Article/details/gt2cfykxqsl.html

[U103] JS：定时器
来源：http://dali.ppjwa.cn/Article/details/gt2uwpputdb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhixingplan.top/Article/details/gt2anpfwwnp.html

[U104] JS：防抖
来源：http://dali.quarkkingdee.top/Article/details/gt2pyhcyuxv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gt2uizdisav.html

[U105] JS：节流
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ctwdffgg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cucudq.cn/Article/details/gt2vhvvcbsn.html

[U106] JS：日期格式化
来源：http://dali.ppjwa.cn/Article/details/gt2nwmdojbv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhiwuduotai.top/Article/details/gt2htiwtemb.html

[U107] JS：数字千分位
来源：http://dali.wangdashe.top/Article/details/gt2tjhkeccq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gt2zfperfib.html

[U108] JS：随机整数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzlczeih.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.wangdashe.top/Article/details/gt2nnkiskpz.html

[U109] JS：数组分组
来源：http://dali.cheryme.top/Article/details/gt2mycyhuag.html

Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gt2zdtvaoln.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gt2emayrncq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpliksgs.html

[U111] JS：对象转 Map
来源：http://dali.yvedp.cn/Article/details/gt2gduszqox.html

new Map(Object.entries(obj))
来源：http://dali.yongpay.top/Article/details/gt2wbrbshtn.html

[U112] JS：字符串补位
来源：http://dali.aizwys.cn/Article/details/gt2uzhtvwcq.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmeimpjq.html

[U113] JS：正则替换全部
来源：http://dali.hywenlv.cn/Article/details/gt2rzrxbenz.html

s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2egnqmwjk.html

[U114] JS：JSON 深比较
来源：http://dali.yvedp.cn/Article/details/gt2acdboqem.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gt2vmwodvcr.html

[U115] JS：生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gt2eopeelzz.html

crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2opibikzk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guannengcc.top/Article/details/gt2hivstyfh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzdadipb.html

[U117] JS：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxojohku.html

npm i -D vitest;  npx vitest
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgadidlx.html

[U118] JS：开发服务器
来源：http://dali.yangfankeji.com/Article/details/gt2mxzqmvpb.html

npm i -D vite;  npx vite
来源：http://dali.zhixingplan.top/Article/details/gt2wnpwpeip.html

[U119] JS：生产构建
来源：http://dali.gzhubu.top/Article/details/gt2fycrrtjw.html

npx vite build
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfqmfwgz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.havefunace.top/Article/details/gt2uogsepuk.html

import.meta.env.VITE_API_URL
来源：http://dali.dashuyun.cn/Article/details/gt2raoioqsv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2kpwylqgs.html

统计汇总
来源：http://dali.gogol.net.cn/Article/details/gt2cgqgppoq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2gjorfdzr.html

按语言统计（条）：
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpndccdj.html

Python ......... 252
来源：http://dali.smart0.xyz/Article/details/gt2jabsnott.html

PHP ............ 252
来源：http://dali.iojbl.cn/Article/details/gt2nxfspbne.html

JavaScript ..... 252
来源：http://dali.zycfv.cn/Article/details/gt2nhwbthxb.html

TypeScript ..... 212
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukyxusoc.html

Java ........... 212
来源：http://dali.0kj1m.cn/Article/details/gt2rhmyluzx.html

Go ............. 212
来源：http://dali.sxryk.cn/Article/details/gt2salywwyb.html

Ruby ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gt2nmujttku.html

C# ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zusgydve.html

C .............. 30
来源：http://dali.wangdashe.top/Article/details/gt2jvpsjnbd.html

C++ ............ 30
来源：http://dali.daria6918.cn/Article/details/gt2wcnaimze.html

SQL ............ 90
来源：http://dali.guannengcc.top/Article/details/gt2lytpuqiw.html

Bash ........... 80
来源：http://dali.zhiwuduotai.top/Article/details/gt2uaddpbzx.html

Kotlin ......... 15
来源：http://dali.jiagoushi.top/Article/details/gt2vpwrnmbl.html

Swift .......... 15
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ryfvgpey.html

Lua ............ 10
来源：http://dali.fengsongda.top/Article/details/gt2fhugnfzl.html

Perl ........... 10
来源：http://dali.chenzaomai.com/Article/details/gt2ypccfkws.html

Scala .......... 10
来源：http://dali.cqqwz.cn/Article/details/gt2ubfqkozz.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gt2vfymxszx.html

合计 ........... 2106 条
来源：http://dali.cdnleiting.top/Article/details/gt2thgpbmzk.html

按章节统计：
来源：http://dali.0kj1m.cn/Article/details/gt2wczrzrcd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gt2fqkzflls.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gt2uaptsxno.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qenhfeil.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gt2fsrbpgze.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gaohongyu789.top/Article/details/gt2vimqxelk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gt2mnitijhu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gt2sxqskhmd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gt2npfcvbsn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gt2hxeixkkf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.c1oappe.top/Article/details/gt2qmdbhqkr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2zmcbuylw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gt2gjbduwyy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2vgtlfixv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrvpzszz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.redwolf501.top/Article/details/gt2waxzhybm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gt2vnrrgujq.html

Q SQL 专题                              90
来源：http://dali.pycfn.com/Article/details/gt2qsrqfnfd.html

R Bash 专题                             80
来源：http://dali.nwbrower.top/Article/details/gt2olemiuym.html

S C / C++ 专题                          60
来源：http://dali.feifeiyinyue.top/Article/details/gt2jdswgqfa.html

T 其他语言补充                          60
来源：http://dali.gogol.net.cn/Article/details/gt2dmzfarzz.html

U 高频实用片段                         120
来源：http://dali.hnqzz.top/Article/details/gt2tszilpvt.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gt2fdesyezy.html

合计                                  2106 条
来源：http://dali.yuanzhike.top/Article/details/gt2jydwwgob.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2pnnocvgg.html

使用提醒
来源：http://dali.kuanghao11.cn/Article/details/gt2yagmrylc.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gt2zgvztnvd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sufxvd.cn/Article/details/gt2zrrufwqz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sysykeji.top/Article/details/gt2ugnipjlw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.aizwys.cn/Article/details/gt2zhgbcmxj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aibaodan.cn/Article/details/gt2shzqlbkh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jianghu66.top/Article/details/gt2jkrxoegv.html

—— 文件结束 ——
来源：http://dali.nanxuanxn.top/Article/details/gt2lfwtvejs.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2rhklobjl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yueranfly.top/Article/details/gt2mrmxpymh.html

Common Programming Examples Cheat Book
来源：http://dali.nanxinkj.top/Article/details/gt2yarmcgvx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2aknvigqf.html

【收录内容】
来源：http://dali.jinqigfzy.top/Article/details/gt2nevqipvt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yonumen.top/Article/details/gt2fgjmwuyi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pengpengdd.cyou/Article/details/gt2klpyqfqv.html

SQL · Bash · C · C++
来源：http://dali.0kj1m.cn/Article/details/gt2wvkzblui.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.havefunace.top/Article/details/gt2bqoixhkl.html

【使用说明】
来源：http://dali.jqgufenzy.top/Article/details/gt2nvyfdfrz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.redwolf501.top/Article/details/gt2kpruvfah.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.quarkkingdee.top/Article/details/gt2beoypsqk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hfpthk.cn/Article/details/gt2rhpybtyv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.guannengcc.top/Article/details/gt2sepiwmej.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuxming.cn/Article/details/gt2yazbpovr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhiwuduotai.top/Article/details/gt2ochserpj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sufxvd.cn/Article/details/gt2gurxvsnn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenzaomai.com/Article/details/gt2yrysdfxq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhixingplan.top/Article/details/gt2yfpyyyeb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yueranfly.top/Article/details/gt2daufotvl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ppjwa.cn/Article/details/gt2hrjndeqs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.feifeiyinyue.top/Article/details/gt2scotclrg.html

【文件统计】
来源：http://dali.xylfe.cn/Article/details/gt2ivhhddvy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guowangkeji.top/Article/details/gt2uvzapnyf.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gt2tuquekun.html

目  录
来源：http://dali.jinqigufen.top/Article/details/gt2ndpaeezt.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2okxohbys.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2gpfnwntg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.0kj1m.cn/Article/details/gt2vqogegni.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gt2upspkjyx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2xyikyfly.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2lalqhpjw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2bqryqajp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gt2ygkkriaj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdcboncp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gt2pnvrdbye.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.aibaodan.cn/Article/details/gt2mslilevj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2krideujz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2lyasobkh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gt2ngbydnaj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ivvv.top/Article/details/gt2ezdsyhtp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.smart0.xyz/Article/details/gt2iboslllk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qtiamdyx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hfpthk.cn/Article/details/gt2gaivtitp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cucudq.cn/Article/details/gt2faqsvywt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvmjxiwp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jtvbiojo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gt2lucbkxlb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2vicpygyh.html

A. 基础语法与类型
来源：http://dali.xylfe.cn/Article/details/gt2nfdjljdp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ixkwxrmb.html

[A01] Hello World
来源：http://dali.fengsongda.top/Article/details/gt2akerwxuc.html

Py:   print("Hello, World!")
来源：http://dali.aizwys.cn/Article/details/gt2hbaryfmi.html

PHP:  echo "Hello, World!";
来源：http://dali.ivvv.top/Article/details/gt2kptoxspb.html

JS:   console.log("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gt2dfniccju.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangdashe.top/Article/details/gt2itodzxfd.html

Java: System.out.println("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gt2nqvoihds.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.snrcjt.cn/Article/details/gt2yvemvnlc.html

Ruby: puts "Hello, World!"
来源：http://dali.quarkkingdee.top/Article/details/gt2iwrklctp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gt2cvyxagsz.html

[A02] 变量声明与赋值
来源：http://dali.sxryk.cn/Article/details/gt2bpxbcgtn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aizwys.cn/Article/details/gt2ubmvvsvo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tian-w.cn/Article/details/gt2nopfbtld.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pycfn.com/Article/details/gt2knxdmsag.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.fengsongda.top/Article/details/gt2xvktpkry.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ydzc1.top/Article/details/gt2jihfhlwa.html

Go:   name := "Alex"; age := 20
来源：http://dali.svipenyu.cn/Article/details/gt2bmqmdcul.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jiagoushi.top/Article/details/gt2kcccbhgx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gt2qommnuss.html

[A03] 常量定义
来源：http://dali.ehwqpu.com/Article/details/gt2xxyksmwy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhoulong.xyz/Article/details/gt2khwmezmv.html

PHP:  const PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2gtlimwhx.html

JS:   const PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2mjtqilkd.html

TS:   const PI: number = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2spbvqftp.html

Java: static final double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gt2boqybdtj.html

Go:   const PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgzujhxt.html

Ruby: PI = 3.14159
来源：http://dali.sufxvd.cn/Article/details/gt2bmkzjxbl.html

C#:   const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2gpjtahbm.html

[A04] 判断变量类型
来源：http://dali.sufxvd.cn/Article/details/gt2jbreekqo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yj202588.top/Article/details/gt2jxnsgxdj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shuidangran.top/Article/details/gt2sxzijfau.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnqgtcol.html

TS:   typeof x; x instanceof Date
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xojnfxoc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.quarkkingdee.top/Article/details/gt2qrgyekmq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhongyouzk.top/Article/details/gt2wgasnqph.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.fzhhl.top/Article/details/gt2yziyemil.html

C#:   x.GetType().Name; x is int
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbdjgmqh.html

[A05] 整数除法与取模
来源：http://dali.sweek.top/Article/details/gt2gaxaamcy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.smart0.xyz/Article/details/gt2brafewsd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gt2ymwlszop.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gt2pqxudyog.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hizbenod.html

Java: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gt2ljxbnghk.html

Go:   7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gt2mcfdehgk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gt2dluomshx.html

C#:   7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2vcpucedo.html

[A06] 字符串转数字
来源：http://dali.daxiang520.top/Article/details/gt2znrdmagz.html

Py:   int("42"); float("3.14")
来源：http://dali.yangfankeji.com/Article/details/gt2qftapbqc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sxryk.cn/Article/details/gt2gnztugbf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gt2ktoskdas.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yongpay.top/Article/details/gt2etysywbp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gt2krbchmtl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.daria6918.cn/Article/details/gt2eqvcwjxx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hnqzz.top/Article/details/gt2bzacxqiw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.wangdashe.top/Article/details/gt2gqpiolun.html

[A07] 数字转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2kmoqcdop.html

Py:   str(42)
来源：http://dali.svipenyu.cn/Article/details/gt2ngbiviyz.html

PHP:  (string) 42; strval(42)
来源：http://dali.shzxlz.cn/Article/details/gt2jgzlasyn.html

JS:   String(42); (42).toString()
来源：http://dali.havefunace.top/Article/details/gt2dqvntuqg.html

TS:   String(42)
来源：http://dali.yj202588.top/Article/details/gt2ekogenme.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.wangdashe.top/Article/details/gt2bhupkanh.html

Go:   strconv.Itoa(42)
来源：http://dali.ehwqpu.com/Article/details/gt2cbwgxila.html

Ruby: 42.to_s
来源：http://dali.guowangkeji.top/Article/details/gt2sajbjqxh.html

C#:   42.ToString()
来源：http://dali.zdqjudy.top/Article/details/gt2myxohyds.html

[A08] 取整与四舍五入
来源：http://dali.zdqjudy.top/Article/details/gt2ztbmzplh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gt2jwnqjslv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnqzz.top/Article/details/gt2ahiuiuis.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gt2syotymgc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinqigfzy.top/Article/details/gt2wiscenmn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gt2xzrvdnui.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gt2gktxteqj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.aibaodan.cn/Article/details/gt2xlyqosqs.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gogol.net.cn/Article/details/gt2kbxxlydl.html

[A09] 绝对值与最大最小值
来源：http://dali.9152youxi.cn/Article/details/gt2clthsupa.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kduaqmwc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2eidczbre.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2sbbgiugh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2oziwbfvj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlyatmsd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ybcxt.top/Article/details/gt2elduyzml.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywqyhvfj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydxjkdoe.html

[A10] 生成随机数
来源：http://dali.hywenlv.cn/Article/details/gt2rzjmzjtr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhengqikj.top/Article/details/gt2qopdbcbb.html

PHP:  random_int(1, 100);
来源：http://dali.jianghu66.top/Article/details/gt2jmtgielz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.bjfxy.top/Article/details/gt2guukncyu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gt2elmubtna.html

Java: new Random().nextInt(100) + 1
来源：http://dali.fengsongda.top/Article/details/gt2palvhkuh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hywenlv.cn/Article/details/gt2lfmsyfmi.html

Ruby: rand(1..100)
来源：http://dali.pycfn.com/Article/details/gt2vqabdilp.html

C#:   new Random().Next(1, 101)
来源：http://dali.ybcxt.top/Article/details/gt2ptrplzry.html

[A11] 条件表达式（三元）
来源：http://dali.yangfankeji.com/Article/details/gt2phspvtey.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.bjfxy.top/Article/details/gt2qrsjupqo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gt2flxkglya.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gt2oxoazlzp.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gt2zmlrnxxy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gt2jtmcgmuc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinqigfzy.top/Article/details/gt2mpttivoq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gt2dvlxmrvs.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gt2bupoldtn.html

[A12] 字符串插值 / 格式化
来源：http://dali.xziqi.cn/Article/details/gt2psflapjs.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.tanke756.top/Article/details/gt2foiwsbls.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zycfv.cn/Article/details/gt2zqbhrucj.html

JS:   `Hello, ${name}!`
来源：http://dali.xuetiantiany.cn/Article/details/gt2owgnlwrv.html

TS:   `Hello, ${name}!`
来源：http://dali.sxryk.cn/Article/details/gt2xirqwtyu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cdnleiting.top/Article/details/gt2mbekqjzy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.fengsongda.top/Article/details/gt2jqsrnpcq.html

Ruby: "Hello, #{name}!"
来源：http://dali.hnqzz.top/Article/details/gt2jqpnhbfp.html

C#:   $"Hello, {name}!"
来源：http://dali.cqqwz.cn/Article/details/gt2jxnjdakn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.snrcjt.cn/Article/details/gt2wyebzkjr.html

Py:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gt2hogegbvs.html

PHP:  "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjkyprey.html

JS:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gt2chqztyov.html

TS:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gt2zixqgbkt.html

Java: "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gt2rerudyjk.html

Go:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gt2ikndqcvz.html

Ruby: "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gt2nnsakxvg.html

C#:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gt2pjjqqswv.html


<!-- 参考信息 -->