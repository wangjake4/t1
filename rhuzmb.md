代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.vqdsnc.cn/Article/details/gt2zbnvcurz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gt2uvyvcfnf.html

[U84] JS：CommonJS 写法
来源：http://dali.hysaishi.cn/Article/details/gt2fmgtlawu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinqigfzy.top/Article/details/gt2mkluctfn.html

[U85] JS：可选链
来源：http://dali.yangfankeji.com/Article/details/gt2jnjwqmhu.html

a?.b?.c
来源：http://dali.zycfv.cn/Article/details/gt2pywkzkpt.html

[U86] JS：空值合并
来源：http://dali.svipenyu.cn/Article/details/gt2qlpwhfqm.html

a ?? b
来源：http://dali.hnxiangtu.top/Article/details/gt2jroklrkf.html

[U87] JS：解构默认值
来源：http://dali.xinyue.icu/Article/details/gt2tumuusus.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nwbrower.top/Article/details/gt2mxeaqbte.html

[U88] JS：对象展开合并
来源：http://dali.yonumen.top/Article/details/gt2wdgbosmx.html

{ ...a, ...b }
来源：http://dali.bjfxy.top/Article/details/gt2vsqkznrq.html

[U89] JS：数组去重
来源：http://dali.zhixingplan.top/Article/details/gt2zragiyul.html

[...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gt2hmjdhgdw.html

[U90] JS：数字数组排序
来源：http://dali.sxryk.cn/Article/details/gt2nwxqdhjv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gt2qzmsflod.html

[U91] JS：对象键值遍历
来源：http://dali.guannengcc.top/Article/details/gt2qfcktqzy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.nanxuanxn.top/Article/details/gt2evxsfifj.html

[U92] JS：深拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gt2wglklniy.html

structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2jsjihtoa.html

[U93] JS：模板字符串
来源：http://dali.hammf.cn/Article/details/gt2dkftisih.html

`共 ${n} 条`
来源：http://dali.gogol.net.cn/Article/details/gt2fiifraam.html

[U94] JS：箭头函数
来源：http://dali.cheryme.top/Article/details/gt2hoimkscy.html

const double = x => x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gt2skwaooah.html

[U95] JS：Promise 包装
来源：http://dali.havefunace.top/Article/details/gt2qsdwggmq.html

new Promise((resolve, reject) => {})
来源：http://dali.xinyue.icu/Article/details/gt2ohescjfr.html

[U96] JS：async/await 与异常
来源：http://dali.zhengqikj.top/Article/details/gt2xajxewxj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2kyqeotna.html

[U97] JS：并发请求
来源：http://dali.pengpengdd.cyou/Article/details/gt2xaowswjq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2cztjnwyu.html

[U98] JS：fetch 带 JSON
来源：http://dali.tanke756.top/Article/details/gt2hbumbsdn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangdashe.top/Article/details/gt2gsrayksd.html

[U99] JS：事件监听
来源：http://dali.hnqzz.top/Article/details/gt2uinvvkjt.html

el.addEventListener("click", e => {})
来源：http://dali.gotoacloud.top/Article/details/gt2jihlqtbg.html

[U100] JS：DOM 查询
来源：http://dali.birdmap.top/Article/details/gt2sfiwsdrp.html

document.querySelector(".item")
来源：http://dali.fzhhl.top/Article/details/gt2zniyidbe.html

[U101] JS：classList 操作
来源：http://dali.cashguo.top/Article/details/gt2wxzhnvgu.html

el.classList.toggle("active")
来源：http://dali.snrcjt.cn/Article/details/gt2ekmfjfzf.html

[U102] JS：本地存储
来源：http://dali.meibo888.top/Article/details/gt2ddxvppwk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daria6918.cn/Article/details/gt2lqemlcxs.html

[U103] JS：定时器
来源：http://dali.yj20258.top/Article/details/gt2gqwcetog.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sufxvd.cn/Article/details/gt2usgpxhat.html

[U104] JS：防抖
来源：http://dali.zdqjudy.top/Article/details/gt2utwrlxiy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2zrkydpvb.html

[U105] JS：节流
来源：http://dali.xziqi.cn/Article/details/gt2oybhzgra.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2ghccdovy.html

[U106] JS：日期格式化
来源：http://dali.ivvv.top/Article/details/gt2fikxpaud.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gt2nnhabjxr.html

[U107] JS：数字千分位
来源：http://dali.tian-w.cn/Article/details/gt2qirhszid.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gt2qytgcviq.html

[U108] JS：随机整数
来源：http://dali.meibo888.top/Article/details/gt2pqvzhhkt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zycfv.cn/Article/details/gt2wgofhbhu.html

[U109] JS：数组分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntkxmdlk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gt2lomgbfcj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2awfajboq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.smart0.xyz/Article/details/gt2umyukjzp.html

[U111] JS：对象转 Map
来源：http://dali.ybcxt.top/Article/details/gt2yaskqeai.html

new Map(Object.entries(obj))
来源：http://dali.cucudq.cn/Article/details/gt2uuxbuowl.html

[U112] JS：字符串补位
来源：http://dali.hysaishi.cn/Article/details/gt2vjspmgmn.html

"7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2yuveuita.html

[U113] JS：正则替换全部
来源：http://dali.havefunace.top/Article/details/gt2ngukrirj.html

s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2gwtdzicx.html

[U114] JS：JSON 深比较
来源：http://dali.sysykeji.top/Article/details/gt2xijjkoef.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yonumen.top/Article/details/gt2dauomtfy.html

[U115] JS：生成 UUID
来源：http://dali.zycfv.cn/Article/details/gt2jcjltsnr.html

crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gt2spzqvwze.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tuqkckcy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epnaaqhg.html

[U117] JS：单元测试
来源：http://dali.jqgfzy.top/Article/details/gt2foeiumyw.html

npm i -D vitest;  npx vitest
来源：http://dali.tanke756.top/Article/details/gt2xxzleybk.html

[U118] JS：开发服务器
来源：http://dali.shuidangran.top/Article/details/gt2pvabiltj.html

npm i -D vite;  npx vite
来源：http://dali.0kj1m.cn/Article/details/gt2mfssktuj.html

[U119] JS：生产构建
来源：http://dali.sysykeji.top/Article/details/gt2haketcjs.html

npx vite build
来源：http://dali.zycfv.cn/Article/details/gt2lktqhyuj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.bjfxy.top/Article/details/gt2qgaisenu.html

import.meta.env.VITE_API_URL
来源：http://dali.shuidangran.top/Article/details/gt2goieupzd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2mjflddsr.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gt2qcwbzsqh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2aikcfmia.html

按语言统计（条）：
来源：http://dali.ydzc1.top/Article/details/gt2lxbcdgcr.html

Python ......... 252
来源：http://dali.jianghu66.top/Article/details/gt2emqjqjmf.html

PHP ............ 252
来源：http://dali.yuanzhike.top/Article/details/gt2wjcnoqaf.html

JavaScript ..... 252
来源：http://dali.redwolf501.top/Article/details/gt2rulytdeh.html

TypeScript ..... 212
来源：http://dali.316326.xyz/Article/details/gt2hpwkcibf.html

Java ........... 212
来源：http://dali.jianghu66.top/Article/details/gt2ktunmkxt.html

Go ............. 212
来源：http://dali.shanyushiyangtech.top/Article/details/gt2selibfav.html

Ruby ........... 212
来源：http://dali.yj202588.top/Article/details/gt2jtgbwddp.html

C# ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gt2eldiucww.html

C .............. 30
来源：http://dali.vqdsnc.cn/Article/details/gt2ouxgewyt.html

C++ ............ 30
来源：http://dali.birdmap.top/Article/details/gt2cdzoomag.html

SQL ............ 90
来源：http://dali.andypj.xyz/Article/details/gt2zcajywha.html

Bash ........... 80
来源：http://dali.wangdashe.top/Article/details/gt2mdufhlnd.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gt2etoizdif.html

Swift .......... 15
来源：http://dali.hfpthk.cn/Article/details/gt2sgtkjbnj.html

Lua ............ 10
来源：http://dali.aizwys.cn/Article/details/gt2rrtrbtyu.html

Perl ........... 10
来源：http://dali.hammf.cn/Article/details/gt2uojoaoli.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gt2aidhuufp.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2ykghkjxt.html

合计 ........... 2106 条
来源：http://dali.cdnleiting.top/Article/details/gt2zdgyqsvw.html

按章节统计：
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwoqokmh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gt2fppycakl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gt2bsoymomc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hfpthk.cn/Article/details/gt2umqpqipr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xziqi.cn/Article/details/gt2fceuxjlk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhengqikj.top/Article/details/gt2okfbooha.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gt2sodvcyqo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2hcbcglce.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gt2hnfskkmu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gt2sxdltbjl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gt2wtelhlkd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gt2rivvpdys.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2ynzsqwyx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezwtbhpb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gt2hqoanswy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yongpay.top/Article/details/gt2usasrcdo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gt2bkycudio.html

Q SQL 专题                              90
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2agjdegay.html

R Bash 专题                             80
来源：http://dali.shzxlz.cn/Article/details/gt2hpojdcjv.html

S C / C++ 专题                          60
来源：http://dali.hnqzz.top/Article/details/gt2hyvjtasy.html

T 其他语言补充                          60
来源：http://dali.dianchejie.cn/Article/details/gt2xgedpmzm.html

U 高频实用片段                         120
来源：http://dali.svipenyu.cn/Article/details/gt2vjogxnna.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gt2oxqsuqdc.html

合计                                  2106 条
来源：http://dali.gaohongyu789.top/Article/details/gt2wzmglmsf.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gt2pmdlnkst.html

使用提醒
来源：http://dali.meibo888.top/Article/details/gt2cuidskyx.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpnjdzgq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hammf.cn/Article/details/gt2oibecspt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbtpfekp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xylfe.cn/Article/details/gt2eqtnhady.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aibaodan.cn/Article/details/gt2lsjoqpsx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aizwys.cn/Article/details/gt2cofdiajd.html

—— 文件结束 ——
来源：http://dali.gaohongyu789.top/Article/details/gt2qhfbmrzj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2gheshmps.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.vqdsnc.cn/Article/details/gt2vutyfnii.html

Common Programming Examples Cheat Book
来源：http://dali.wangdashe.top/Article/details/gt2djcckvzh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsvapbwa.html

【收录内容】
来源：http://dali.chenjidiqi.icu/Article/details/gt2igpdqybs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yongpay.top/Article/details/gt2tipomrto.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj20258888.top/Article/details/gt2qkxthiij.html

SQL · Bash · C · C++
来源：http://dali.sweek.top/Article/details/gt2iwgvktis.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gt2lkgvfkko.html

【使用说明】
来源：http://dali.redwolf501.top/Article/details/gt2akffpabd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkqumwfi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2jspcuyux.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jlsjyb.cn/Article/details/gt2gmacddha.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ivvv.top/Article/details/gt2uqdxrxpq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.mhx1999.top/Article/details/gt2avhhwxpk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.haohaochexian.top/Article/details/gt2uoxrczmc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aizwys.cn/Article/details/gt2omwiowqm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daxiang520.top/Article/details/gt2zksaupxg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xklzqkmu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tbpniqfg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yuxming.cn/Article/details/gt2ncmbrqdo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.pengpengdd.cyou/Article/details/gt2hndplacf.html

【文件统计】
来源：http://dali.yuxming.cn/Article/details/gt2olhfboiq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hysaishi.cn/Article/details/gt2jqhnkbwf.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2ttharpqp.html

目  录
来源：http://dali.hammf.cn/Article/details/gt2dupphzsp.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gt2txmbvoxk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gt2nemfwxyq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinqigufen.top/Article/details/gt2nhmrbncg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gt2pknvgvyo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yuanzhike.top/Article/details/gt2sdbfanqo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.316326.xyz/Article/details/gt2ytlyhyhb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gt2neltrgvn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cdnleiting.top/Article/details/gt2otldtwhu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouytjepp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gt2jumvrxlr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gt2uoubushu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gt2tojadtga.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gt2rchdltna.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gt2ajeyjaov.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hammf.cn/Article/details/gt2akafalwb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jyoumei.cn/Article/details/gt2zniagnus.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gt2taxpwwga.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2fobadvdm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ppjwa.cn/Article/details/gt2bsayaout.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shuidangran.top/Article/details/gt2jnxhuvpo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gt2lgssdgou.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gt2snlhgwyb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2vjnscrgj.html

A. 基础语法与类型
来源：http://dali.hnxiangtu.top/Article/details/gt2ocflqkkq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2xfkxscho.html

[A01] Hello World
来源：http://dali.gzhubu.top/Article/details/gt2rcpporpg.html

Py:   print("Hello, World!")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tltorcaj.html

PHP:  echo "Hello, World!";
来源：http://dali.redwolf501.top/Article/details/gt2uhxwmbzq.html

JS:   console.log("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqfypuzf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258888.top/Article/details/gt2utxazmlq.html

Java: System.out.println("Hello, World!");
来源：http://dali.aibaodan.cn/Article/details/gt2ygnewqyw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gt2pthvpaps.html

Ruby: puts "Hello, World!"
来源：http://dali.yanxiufei.cn/Article/details/gt2cfpvzkyf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gt2xytfbmlo.html

[A02] 变量声明与赋值
来源：http://dali.fengsongda.top/Article/details/gt2zulnvzro.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yvedp.cn/Article/details/gt2fogehkbm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.fengsongda.top/Article/details/gt2hnndllwb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ppjwa.cn/Article/details/gt2qborlxng.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hnqzz.top/Article/details/gt2zgkrqxrp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tianlin.xyz/Article/details/gt2qnoffkmw.html

Go:   name := "Alex"; age := 20
来源：http://dali.snrcjt.cn/Article/details/gt2kwhrsirs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.fzhhl.top/Article/details/gt2oqgqafoe.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gt2cijxxglc.html

[A03] 常量定义
来源：http://dali.0kj1m.cn/Article/details/gt2rbfvweci.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.meibo888.top/Article/details/gt2poluqsql.html

PHP:  const PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2vliwowco.html

JS:   const PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2ismrkkiy.html

TS:   const PI: number = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2uqyrlvem.html

Java: static final double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2vzjbcugk.html

Go:   const PI = 3.14159
来源：http://dali.9152youxi.cn/Article/details/gt2eraygfiz.html

Ruby: PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gt2ocdsfyeu.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2gsjwbqxj.html

[A04] 判断变量类型
来源：http://dali.sweek.top/Article/details/gt2vksbfemo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yj20258888.top/Article/details/gt2rsmuznlb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shzxlz.cn/Article/details/gt2edljkyyh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.vqdsnc.cn/Article/details/gt2dhpmmyut.html

TS:   typeof x; x instanceof Date
来源：http://dali.bjfxy.top/Article/details/gt2ftttooio.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlwmymac.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xylfe.cn/Article/details/gt2kdxcblqu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zycfv.cn/Article/details/gt2tkneosqe.html

C#:   x.GetType().Name; x is int
来源：http://dali.yangfankeji.com/Article/details/gt2tzibxven.html

[A05] 整数除法与取模
来源：http://dali.cqqwz.cn/Article/details/gt2ddlhssvc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcvfwmjo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gt2uegmujov.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gt2hzeykzhn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gt2zdksdumi.html

Java: 7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2whwhjmig.html

Go:   7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gt2shptghxm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gt2eeojesax.html

C#:   7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2dxgomsch.html

[A06] 字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gt2iyqxxcva.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuixqhz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.kuanghao11.cn/Article/details/gt2emytowyv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xuanzx.com/Article/details/gt2sykelwls.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.316326.xyz/Article/details/gt2hpskorhy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xuanzx.com/Article/details/gt2edepfqmx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.tanke756.top/Article/details/gt2luiktuhx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xuanzx.com/Article/details/gt2axqvkbzz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sweek.top/Article/details/gt2nlpuwbrp.html

[A07] 数字转字符串
来源：http://dali.yj202588.top/Article/details/gt2zicgyvok.html

Py:   str(42)
来源：http://dali.ehwqpu.com/Article/details/gt2tgrxgojg.html

PHP:  (string) 42; strval(42)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cleopvdl.html

JS:   String(42); (42).toString()
来源：http://dali.daxiang520.top/Article/details/gt2mrnikceg.html

TS:   String(42)
来源：http://dali.jyoumei.cn/Article/details/gt2joxzajop.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ehwqpu.com/Article/details/gt2oapukqkq.html

Go:   strconv.Itoa(42)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lovrkywf.html

Ruby: 42.to_s
来源：http://dali.vqdsnc.cn/Article/details/gt2lglastik.html

C#:   42.ToString()
来源：http://dali.yongpay.top/Article/details/gt2ewmrimrp.html

[A08] 取整与四舍五入
来源：http://dali.9152youxi.cn/Article/details/gt2hqvrsmlf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gt2xwsqquws.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xziqi.cn/Article/details/gt2pqkokmoy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdxgqvtq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinqigufen.top/Article/details/gt2klqybdru.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gogol.net.cn/Article/details/gt2kvpuyxya.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gt2nsugyyhk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vuzhypxw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gt2kznxgtoj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gt2ecxdswgx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj202588.top/Article/details/gt2odtysfcl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2yteypefu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2gurctmah.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ivvv.top/Article/details/gt2elwgsplf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqomicbu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zdqjudy.top/Article/details/gt2hiakhtpa.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xinyue.icu/Article/details/gt2kgguqhuw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2oghspvyu.html

[A10] 生成随机数
来源：http://dali.fengsongda.top/Article/details/gt2nfkibqdd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.0kj1m.cn/Article/details/gt2hajwbfix.html

PHP:  random_int(1, 100);
来源：http://dali.jiagoushi.top/Article/details/gt2kfovhmdx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guannengcc.top/Article/details/gt2paqufwjx.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jyoumei.cn/Article/details/gt2vssgitfo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yanxiufei.cn/Article/details/gt2lnbdlnmm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwbzmqiy.html

Ruby: rand(1..100)
来源：http://dali.yuanzhike.top/Article/details/gt2njgtkawk.html

C#:   new Random().Next(1, 101)
来源：http://dali.fengsongda.top/Article/details/gt2fnsfnqtf.html

[A11] 条件表达式（三元）
来源：http://dali.gotoacloud.top/Article/details/gt2ewynwiqg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.sweek.top/Article/details/gt2utcvcfmb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gt2ervavunx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gt2hajoxmmt.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gt2xfsagnuu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gt2fqcmpxmy.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jqgufenzy.top/Article/details/gt2lkzdksgi.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwzghydx.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gt2stffugxd.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgfyshdg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.meibo888.top/Article/details/gt2rxzsnowq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xuanzx.com/Article/details/gt2znylsnyj.html

JS:   `Hello, ${name}!`
来源：http://dali.cqqwz.cn/Article/details/gt2moghlstq.html

TS:   `Hello, ${name}!`
来源：http://dali.xziqi.cn/Article/details/gt2zxqvhfem.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hnxiangtu.top/Article/details/gt2mkxsworj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.sysykeji.top/Article/details/gt2zqfzgcmw.html

Ruby: "Hello, #{name}!"
来源：http://dali.yueranfly.top/Article/details/gt2uyirsjjb.html

C#:   $"Hello, {name}!"
来源：http://dali.svipenyu.cn/Article/details/gt2szhpkqlm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkmkpgs.html

Py:   "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gt2ujihissk.html

PHP:  "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nkadudqq.html

JS:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gt2ygijcota.html

TS:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gt2wmmnlvbb.html

Java: "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gt2oxxozhcz.html

Go:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gt2avrenwla.html

Ruby: "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gt2jrdkgxuc.html

C#:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gt2zburjlyl.html


<!-- 参考信息 -->