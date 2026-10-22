代发 wailian999

[U81] JS：初始化项目
来源：http://dali.yuanzhike.top/Article/details/gt2zgdadmwj.html

npm init -y;  npm i express
来源：http://dali.yuxming.cn/Article/details/gt2ueypsxfl.html

[U82] JS：package.json 脚本
来源：http://dali.xinyue.icu/Article/details/gt2szcezesx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dashuyun.cn/Article/details/gt2vnubieta.html

[U83] JS：ES Module 导入导出
来源：http://dali.sysykeji.top/Article/details/gt2mfqkuebp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yongpay.top/Article/details/gt2azrilueh.html

[U84] JS：CommonJS 写法
来源：http://dali.yonumen.top/Article/details/gt2hkmskptv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.9152youxi.cn/Article/details/gt2blkwvubp.html

[U85] JS：可选链
来源：http://dali.mhx1999.top/Article/details/gt2pduqkfhk.html

a?.b?.c
来源：http://dali.zhongyouzk.top/Article/details/gt2tnprrkyq.html

[U86] JS：空值合并
来源：http://dali.aizwys.cn/Article/details/gt2dcegnkwd.html

a ?? b
来源：http://dali.jinqigfzy.top/Article/details/gt2emgrztci.html

[U87] JS：解构默认值
来源：http://dali.havefunace.top/Article/details/gt2stqwuzlm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bsmxdsgb.html

[U88] JS：对象展开合并
来源：http://dali.9152youxi.cn/Article/details/gt2exzbbtxr.html

{ ...a, ...b }
来源：http://dali.nanxinkj.top/Article/details/gt2qvtdjqro.html

[U89] JS：数组去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2vudcqryd.html

[...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2aihfmokp.html

[U90] JS：数字数组排序
来源：http://dali.snrcjt.cn/Article/details/gt2oaevlhka.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gt2hkpyabtl.html

[U91] JS：对象键值遍历
来源：http://dali.ivvv.top/Article/details/gt2aaqskagi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guannengcc.top/Article/details/gt2hxbhbzeh.html

[U92] JS：深拷贝
来源：http://dali.smart0.xyz/Article/details/gt2pbmhipps.html

structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2qcsbldjg.html

[U93] JS：模板字符串
来源：http://dali.jianghu66.top/Article/details/gt2wjrngjlw.html

`共 ${n} 条`
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmcqetja.html

[U94] JS：箭头函数
来源：http://dali.9152youxi.cn/Article/details/gt2daveqpuv.html

const double = x => x * 2;
来源：http://dali.andypj.xyz/Article/details/gt2ntzuoyym.html

[U95] JS：Promise 包装
来源：http://dali.gogol.net.cn/Article/details/gt2hiydcxpx.html

new Promise((resolve, reject) => {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfbjeiwi.html

[U96] JS：async/await 与异常
来源：http://dali.hysaishi.cn/Article/details/gt2lxjgruwk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2kobqexcw.html

[U97] JS：并发请求
来源：http://dali.yanxiufei.cn/Article/details/gt2tikzwyea.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2lnguwttf.html

[U98] JS：fetch 带 JSON
来源：http://dali.tianlin.xyz/Article/details/gt2sygmpwnx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cdnleiting.top/Article/details/gt2zciahozv.html

[U99] JS：事件监听
来源：http://dali.gzhubu.top/Article/details/gt2nwxzcdza.html

el.addEventListener("click", e => {})
来源：http://dali.gogol.net.cn/Article/details/gt2lcnkxunz.html

[U100] JS：DOM 查询
来源：http://dali.hnxiangtu.top/Article/details/gt2mrdvxafg.html

document.querySelector(".item")
来源：http://dali.jyoumei.cn/Article/details/gt2gxoewivd.html

[U101] JS：classList 操作
来源：http://dali.jqgufenzy.top/Article/details/gt2ffztafvg.html

el.classList.toggle("active")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ledqwnas.html

[U102] JS：本地存储
来源：http://dali.meibo888.top/Article/details/gt2hptczeyr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfnwssey.html

[U103] JS：定时器
来源：http://dali.andypj.xyz/Article/details/gt2rmirtdsq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgufenzy.top/Article/details/gt2wagvgane.html

[U104] JS：防抖
来源：http://dali.nanxinkj.top/Article/details/gt2pczolemh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2gxlbipfn.html

[U105] JS：节流
来源：http://dali.hnqzz.top/Article/details/gt2alfjgkrv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.meibo888.top/Article/details/gt2uwdwjjaj.html

[U106] JS：日期格式化
来源：http://dali.tanke756.top/Article/details/gt2vnrqubey.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fengsongda.top/Article/details/gt2oiqmfgvf.html

[U107] JS：数字千分位
来源：http://dali.0kj1m.cn/Article/details/gt2wjbtehzo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gt2nfgctaww.html

[U108] JS：随机整数
来源：http://dali.yj202588.top/Article/details/gt2finnimnk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.meibo888.top/Article/details/gt2weszcito.html

[U109] JS：数组分组
来源：http://dali.nanxuanxn.top/Article/details/gt2saeythlp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gt2ytkulamu.html

[U110] JS：数组分块
来源：http://dali.jqgufenzy.top/Article/details/gt2evecacge.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ybcxt.top/Article/details/gt2kaqgpdsq.html

[U111] JS：对象转 Map
来源：http://dali.cashguo.top/Article/details/gt2usdjkiki.html

new Map(Object.entries(obj))
来源：http://dali.zhongyouzk.top/Article/details/gt2hqscoyaa.html

[U112] JS：字符串补位
来源：http://dali.hnqzz.top/Article/details/gt2rdubwnld.html

"7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2nvtnqbus.html

[U113] JS：正则替换全部
来源：http://dali.yvedp.cn/Article/details/gt2tnuajben.html

s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bquaeewg.html

[U114] JS：JSON 深比较
来源：http://dali.daxiang520.top/Article/details/gt2bovtbnsf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258888.top/Article/details/gt2vaqqysbl.html

[U115] JS：生成 UUID
来源：http://dali.pycfn.com/Article/details/gt2ysvhlzkr.html

crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gt2sfdmpexq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yueranfly.top/Article/details/gt2yqrixncz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.redwolf501.top/Article/details/gt2aokeaspo.html

[U117] JS：单元测试
来源：http://dali.sxryk.cn/Article/details/gt2yyooqmrz.html

npm i -D vitest;  npx vitest
来源：http://dali.hnqzz.top/Article/details/gt2agdispfl.html

[U118] JS：开发服务器
来源：http://dali.zhongyouzk.top/Article/details/gt2yglmuyoi.html

npm i -D vite;  npx vite
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzpnstzc.html

[U119] JS：生产构建
来源：http://dali.havefunace.top/Article/details/gt2bfuhfrru.html

npx vite build
来源：http://dali.guowangkeji.top/Article/details/gt2vedmiqeb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mupekcss.html

import.meta.env.VITE_API_URL
来源：http://dali.andypj.xyz/Article/details/gt2towoowvo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2qwwdpjgk.html

统计汇总
来源：http://dali.yuanzhike.top/Article/details/gt2uzvjelxw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ubbtmmaj.html

按语言统计（条）：
来源：http://dali.nanxinkj.top/Article/details/gt2kgxfdrrl.html

Python ......... 252
来源：http://dali.sufxvd.cn/Article/details/gt2nqcbqewu.html

PHP ............ 252
来源：http://dali.hysaishi.cn/Article/details/gt2ttefgrwy.html

JavaScript ..... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ooswcnca.html

TypeScript ..... 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqqrxlwm.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gt2zcdffgxa.html

Go ............. 212
来源：http://dali.gotoacloud.top/Article/details/gt2rdmaeuac.html

Ruby ........... 212
来源：http://dali.ydzc1.top/Article/details/gt2elfrzpkr.html

C# ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gt2oqbbhffj.html

C .............. 30
来源：http://dali.jlsjyb.cn/Article/details/gt2rguygbto.html

C++ ............ 30
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktqvtlbc.html

SQL ............ 90
来源：http://dali.mhx1999.top/Article/details/gt2jlhioboc.html

Bash ........... 80
来源：http://dali.tian-w.cn/Article/details/gt2ufdjjtbq.html

Kotlin ......... 15
来源：http://dali.vqdsnc.cn/Article/details/gt2ftujtqoy.html

Swift .......... 15
来源：http://dali.aibaodan.cn/Article/details/gt2wqjelxjh.html

Lua ............ 10
来源：http://dali.zhiwuduotai.top/Article/details/gt2lnbxkfgo.html

Perl ........... 10
来源：http://dali.jqgfzy.top/Article/details/gt2vgnmtcis.html

Scala .......... 10
来源：http://dali.feifeiyinyue.top/Article/details/gt2lovljgzc.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2byetkcyg.html

合计 ........... 2106 条
来源：http://dali.cheryme.top/Article/details/gt2wnmffkvb.html

按章节统计：
来源：http://dali.gogol.net.cn/Article/details/gt2lyqrtlev.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gt2wicurtxb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gt2iizbrlkg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gt2dcsjstpg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jqgfzy.top/Article/details/gt2rjwmhhhs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.birdmap.top/Article/details/gt2qetxesao.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hfpthk.cn/Article/details/gt2scybhwbl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gt2fsfabmkd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mofzzenw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gt2lrnobtac.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gt2viuoqdaa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gt2wcnvjtba.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gt2eeoxaidt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2souuvfcy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gt2lmiwxepz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pycfn.com/Article/details/gt2anjufdzg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2ljrhepho.html

Q SQL 专题                              90
来源：http://dali.cucudq.cn/Article/details/gt2csxzeyjm.html

R Bash 专题                             80
来源：http://dali.haohaochexian.top/Article/details/gt2gmelmhdb.html

S C / C++ 专题                          60
来源：http://dali.hnqzz.top/Article/details/gt2zndqlfxj.html

T 其他语言补充                          60
来源：http://dali.fengsongda.top/Article/details/gt2iszgzsfu.html

U 高频实用片段                         120
来源：http://dali.xziqi.cn/Article/details/gt2hxubkyoz.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2icanldai.html

合计                                  2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjhrtteo.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2milrbxxo.html

使用提醒
来源：http://dali.redwolf501.top/Article/details/gt2vuuewqen.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gt2ivrophfl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinqigfzy.top/Article/details/gt2dabapfeo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hnqzz.top/Article/details/gt2efkldjdq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sweek.top/Article/details/gt2jiqlofuu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ehwqpu.com/Article/details/gt2qtwgstjt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nwbrower.top/Article/details/gt2zpwhcbkq.html

—— 文件结束 ——
来源：http://dali.guannengcc.top/Article/details/gt2vfpujlyj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2fdunimlq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekhznvfs.html

Common Programming Examples Cheat Book
来源：http://dali.andypj.xyz/Article/details/gt2zwpbyzsl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ykrlpcel.html

【收录内容】
来源：http://dali.sxryk.cn/Article/details/gt2skykluga.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ybcxt.top/Article/details/gt2bexfgdzw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shuidangran.top/Article/details/gt2fqszqbzb.html

SQL · Bash · C · C++
来源：http://dali.jianghu66.top/Article/details/gt2vzmclsee.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.havefunace.top/Article/details/gt2mejblbjg.html

【使用说明】
来源：http://dali.daria6918.cn/Article/details/gt2vwyqadbn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenlongwang.top/Article/details/gt2oiltspge.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yonumen.top/Article/details/gt2cdlseczp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dpflyyst.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkgtzlw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.svipenyu.cn/Article/details/gt2nuqubbgj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfrsbgzr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.kuanghao11.cn/Article/details/gt2eersrqpl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hnxiangtu.top/Article/details/gt2lihjrrey.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xuanzx.com/Article/details/gt2fokvzasw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yonumen.top/Article/details/gt2rsteruur.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yangfankeji.com/Article/details/gt2vrtdicyf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cucudq.cn/Article/details/gt2txskznhr.html

【文件统计】
来源：http://dali.yj20258.top/Article/details/gt2hmvmrchc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhoulong.xyz/Article/details/gt2nmptqufg.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2ismxdmpg.html

目  录
来源：http://dali.pycfn.com/Article/details/gt2qawzputd.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gt2czdneejo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cdnleiting.top/Article/details/gt2nzfytvda.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2ujjiaysk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfquvivs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gt2matxzikw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2uugkhmcj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cijinwgx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2rawiaqzp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gt2nrmrzfrc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gt2eobdjxot.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2iubozvse.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2ftlpcutx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gt2rrceousd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2wglxwktz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxmzlzdr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhpknuyr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gt2mdedidyp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hnqzz.top/Article/details/gt2vhaliupk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkeicjmu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jiagoushi.top/Article/details/gt2pmvzaqzy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gt2qgeepbee.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2ynkkkugk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ettrzeyb.html

A. 基础语法与类型
来源：http://dali.jinqigfzy.top/Article/details/gt2yzdhblgk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2njkcvhue.html

[A01] Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2lwazjqsa.html

Py:   print("Hello, World!")
来源：http://dali.jiagoushi.top/Article/details/gt2kbflnegw.html

PHP:  echo "Hello, World!";
来源：http://dali.tanke756.top/Article/details/gt2blghsaqw.html

JS:   console.log("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gt2nprvduuj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhoulong.xyz/Article/details/gt2owtxatlx.html

Java: System.out.println("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gt2dwwjdkjz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yangfankeji.com/Article/details/gt2ooesqkvi.html

Ruby: puts "Hello, World!"
来源：http://dali.9152youxi.cn/Article/details/gt2rejolhed.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gt2jiadjrtj.html

[A02] 变量声明与赋值
来源：http://dali.yj20258.top/Article/details/gt2kfyiwhvc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhixingplan.top/Article/details/gt2qextstqb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.fengsongda.top/Article/details/gt2zfqpthbu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gzhubu.top/Article/details/gt2zvyyyzsq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2ncoyybei.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsgcasre.html

Go:   name := "Alex"; age := 20
来源：http://dali.tanke756.top/Article/details/gt2cvimdlef.html

Ruby: name = "Alex"; age = 20
来源：http://dali.smart0.xyz/Article/details/gt2ikvxcjpb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yonumen.top/Article/details/gt2psbogkfp.html

[A03] 常量定义
来源：http://dali.9152youxi.cn/Article/details/gt2yhkfbxsw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinqigfzy.top/Article/details/gt2npytnidg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2tvrglxni.html

JS:   const PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2pwcqroiv.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2bzmddlst.html

Java: static final double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2dxdjmlso.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnvyzds.html

Ruby: PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gt2sevzddue.html

C#:   const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2obunxizs.html

[A04] 判断变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdlklguc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cashguo.top/Article/details/gt2gpxphwum.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gzhubu.top/Article/details/gt2alvsnwho.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gotoacloud.top/Article/details/gt2pgavvthj.html

TS:   typeof x; x instanceof Date
来源：http://dali.ydzc1.top/Article/details/gt2lnfqzdod.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpenfuds.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.tanke756.top/Article/details/gt2vtodspnu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gaohongyu789.top/Article/details/gt2uditzfou.html

C#:   x.GetType().Name; x is int
来源：http://dali.ivvv.top/Article/details/gt2dgtxflvt.html

[A05] 整数除法与取模
来源：http://dali.jiagoushi.top/Article/details/gt2eqcfgkif.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.guannengcc.top/Article/details/gt2rtvfvxlj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2ybehaujs.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2kolfjfeh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gt2slaqyukg.html

Java: 7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gt2nqqdmiac.html

Go:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gt2dljuutlm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gt2fvpttpgz.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2ctpwozwt.html

[A06] 字符串转数字
来源：http://dali.cheryme.top/Article/details/gt2xgyxoqme.html

Py:   int("42"); float("3.14")
来源：http://dali.cqqwz.cn/Article/details/gt2bhoeumfb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jyoumei.cn/Article/details/gt2atxkdpsn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.bjfxy.top/Article/details/gt2lsippssn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hysaishi.cn/Article/details/gt2hwfeaapi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jahyjkex.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ielnfqcw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlcoefoj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hysaishi.cn/Article/details/gt2yoodpxcd.html

[A07] 数字转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2epobgixa.html

Py:   str(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2gfgldfqi.html

PHP:  (string) 42; strval(42)
来源：http://dali.dianchejie.cn/Article/details/gt2jplcihbr.html

JS:   String(42); (42).toString()
来源：http://dali.zhixingplan.top/Article/details/gt2sblctobf.html

TS:   String(42)
来源：http://dali.gotoacloud.top/Article/details/gt2nzbaezjb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfqdadav.html

Go:   strconv.Itoa(42)
来源：http://dali.jlsjyb.cn/Article/details/gt2lgpfnmvv.html

Ruby: 42.to_s
来源：http://dali.gaohongyu789.top/Article/details/gt2dbgkvcca.html

C#:   42.ToString()
来源：http://dali.sxryk.cn/Article/details/gt2nkhydgnr.html

[A08] 取整与四舍五入
来源：http://dali.iojbl.cn/Article/details/gt2endvnbim.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gt2supxcjgf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cheryme.top/Article/details/gt2cakqdjdm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gt2noesezkv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.redwolf501.top/Article/details/gt2bhvnvxbj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gt2ztirqmjf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gt2linkmcvk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ydzc1.top/Article/details/gt2uldjennu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gt2gfgezbuj.html

[A09] 绝对值与最大最小值
来源：http://dali.hfpthk.cn/Article/details/gt2khytbnxp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gt2kgagmhcw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihvmjhsc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2erpikhso.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj202588.top/Article/details/gt2vupjcxqk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.guannengcc.top/Article/details/gt2fbvekvcf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.pycfn.com/Article/details/gt2jlzghbyn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xylfe.cn/Article/details/gt2nkcdejkh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqdnknpq.html

[A10] 生成随机数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zozlurkf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xuanzx.com/Article/details/gt2bqwayvto.html

PHP:  random_int(1, 100);
来源：http://dali.jinqigfzy.top/Article/details/gt2bdvjjcmm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwksfdbd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tianlin.xyz/Article/details/gt2hpikxede.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jiagoushi.top/Article/details/gt2zakujast.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.fengsongda.top/Article/details/gt2ugsqbhip.html

Ruby: rand(1..100)
来源：http://dali.xinyue.icu/Article/details/gt2vkxtxhpf.html

C#:   new Random().Next(1, 101)
来源：http://dali.yangfankeji.com/Article/details/gt2lwybqtmd.html

[A11] 条件表达式（三元）
来源：http://dali.dianchejie.cn/Article/details/gt2ngiefuyu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hnqzz.top/Article/details/gt2naefcvlm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gt2ekslnhdo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gt2uvpbiday.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gt2cililooa.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.ppjwa.cn/Article/details/gt2nevopjua.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.0kj1m.cn/Article/details/gt2kezvgrdd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gt2ebmtdjfg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gt2hclhqhso.html

[A12] 字符串插值 / 格式化
来源：http://dali.dianchejie.cn/Article/details/gt2jxjywoun.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2igmmscmy.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gaohongyu789.top/Article/details/gt2zfmgbgxp.html

JS:   `Hello, ${name}!`
来源：http://dali.hongshengwenyu.top/Article/details/gt2rphdvkra.html

TS:   `Hello, ${name}!`
来源：http://dali.yangfankeji.com/Article/details/gt2uurighii.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xziqi.cn/Article/details/gt2tkqgfqtb.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.andypj.xyz/Article/details/gt2kwjylsws.html

Ruby: "Hello, #{name}!"
来源：http://dali.yangfankeji.com/Article/details/gt2whlaloqy.html

C#:   $"Hello, {name}!"
来源：http://dali.jianghu66.top/Article/details/gt2leebtswd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nanxinkj.top/Article/details/gt2apvrqndw.html

Py:   "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gt2nnjhrndn.html

PHP:  "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gt2eyhvomrp.html

JS:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gt2wiwwuyhz.html

TS:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gt2glahgzbu.html


<!-- 参考信息 -->