代发 wailian999

[U79] PHP：静态分析
来源：http://dali.0kj1m.cn/Article/details/gtgngxzofw.html

composer require --dev phpstan/phpstan
来源：http://dali.yj20258888.top/Article/details/gtniqwnjat.html

[U80] PHP：代码规范修复
来源：http://dali.hnqzz.top/Article/details/gtngmxkdyn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xylfe.cn/Article/details/gtczpbwzli.html

[U81] JS：初始化项目
来源：http://dali.gzhubu.top/Article/details/gtqlvhvujo.html

npm init -y;  npm i express
来源：http://dali.xziqi.cn/Article/details/gtrowsqjfk.html

[U82] JS：package.json 脚本
来源：http://dali.cheryme.top/Article/details/gtfroavolj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.svipenyu.cn/Article/details/gtokxexwxi.html

[U83] JS：ES Module 导入导出
来源：http://dali.zdqjudy.top/Article/details/gthxwessiw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.iojbl.cn/Article/details/gtgsfladqz.html

[U84] JS：CommonJS 写法
来源：http://dali.xuetiantiany.cn/Article/details/gtdielhycg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gotoacloud.top/Article/details/gteumruxec.html

[U85] JS：可选链
来源：http://dali.jinqigufen.top/Article/details/gtlaetseaa.html

a?.b?.c
来源：http://dali.jyoumei.cn/Article/details/gtrwmjmezo.html

[U86] JS：空值合并
来源：http://dali.0kj1m.cn/Article/details/gtectoircl.html

a ?? b
来源：http://dali.bjfxy.top/Article/details/gtroykjsvt.html

[U87] JS：解构默认值
来源：http://dali.gogol.net.cn/Article/details/gtpbkvokbe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fengsongda.top/Article/details/gtrtccacow.html

[U88] JS：对象展开合并
来源：http://dali.fengsongda.top/Article/details/gthgeaekhi.html

{ ...a, ...b }
来源：http://dali.yanxiufei.cn/Article/details/gtpaopjydd.html

[U89] JS：数组去重
来源：http://dali.c1oappe.top/Article/details/gtebxmtywj.html

[...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gthkjamafd.html

[U90] JS：数字数组排序
来源：http://dali.cashguo.top/Article/details/gthkrbhnof.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtwwhntnen.html

[U91] JS：对象键值遍历
来源：http://dali.vqdsnc.cn/Article/details/gtmllldrxx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.c1oappe.top/Article/details/gtlehkzdmd.html

[U92] JS：深拷贝
来源：http://dali.aizwys.cn/Article/details/gtowaipuor.html

structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtryclhvgx.html

[U93] JS：模板字符串
来源：http://dali.ppjwa.cn/Article/details/gtkqlzurlf.html

`共 ${n} 条`
来源：http://dali.chenjidiqi.icu/Article/details/gtrzrwaejw.html

[U94] JS：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gtmvnqzpcz.html

const double = x => x * 2;
来源：http://dali.aibaodan.cn/Article/details/gtglebcepg.html

[U95] JS：Promise 包装
来源：http://dali.gaohongyu789.top/Article/details/gtbvecqvrs.html

new Promise((resolve, reject) => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtnkvnqmzc.html

[U96] JS：async/await 与异常
来源：http://dali.jyoumei.cn/Article/details/gtzeltbwtp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtdskviqao.html

[U97] JS：并发请求
来源：http://dali.ivvv.top/Article/details/gtukzcxxks.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtzockltmr.html

[U98] JS：fetch 带 JSON
来源：http://dali.dianchejie.cn/Article/details/gtkpxwbhei.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.redwolf501.top/Article/details/gtkghgxogq.html

[U99] JS：事件监听
来源：http://dali.fengsongda.top/Article/details/gtryaefzlq.html

el.addEventListener("click", e => {})
来源：http://dali.jqgfzy.top/Article/details/gtjuqupiun.html

[U100] JS：DOM 查询
来源：http://dali.gzhubu.top/Article/details/gtvaklpigt.html

document.querySelector(".item")
来源：http://dali.chenlongwang.top/Article/details/gtnoywsvbv.html

[U101] JS：classList 操作
来源：http://dali.haohaochexian.top/Article/details/gtkiptivwe.html

el.classList.toggle("active")
来源：http://dali.xziqi.cn/Article/details/gtkklyxfmk.html

[U102] JS：本地存储
来源：http://dali.jinqigfzy.top/Article/details/gtpebnlbyi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinqigfzy.top/Article/details/gtgbsiqlwq.html

[U103] JS：定时器
来源：http://dali.hnqzz.top/Article/details/gtjaoomxwr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daria6918.cn/Article/details/gtnavqfunr.html

[U104] JS：防抖
来源：http://dali.aizwys.cn/Article/details/gtlspmddcg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtqcwdsigb.html

[U105] JS：节流
来源：http://dali.andypj.xyz/Article/details/gtncuarsyb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtaclbjhyq.html

[U106] JS：日期格式化
来源：http://dali.zycfv.cn/Article/details/gtouvfebsq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gtmghumecw.html

[U107] JS：数字千分位
来源：http://dali.cucudq.cn/Article/details/gtbozfccgu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtdxrigiea.html

[U108] JS：随机整数
来源：http://dali.redwolf501.top/Article/details/gtkuebxqoa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gogol.net.cn/Article/details/gtjeccdoed.html

[U109] JS：数组分组
来源：http://dali.daxiang520.top/Article/details/gtbwguvepq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtyfoloyuc.html

[U110] JS：数组分块
来源：http://dali.yj20258888.top/Article/details/gtwmvprrld.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pycfn.com/Article/details/gtrnrzrxjh.html

[U111] JS：对象转 Map
来源：http://dali.yj20258888.top/Article/details/gtimsmpntl.html

new Map(Object.entries(obj))
来源：http://dali.0kj1m.cn/Article/details/gtapppcibi.html

[U112] JS：字符串补位
来源：http://dali.zdqjudy.top/Article/details/gtwsufoxpo.html

"7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtxxspfubt.html

[U113] JS：正则替换全部
来源：http://dali.9152youxi.cn/Article/details/gtnjzaiznj.html

s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtuyrfoiea.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvazytzg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gttxqhlclk.html

[U115] JS：生成 UUID
来源：http://dali.316326.xyz/Article/details/gtaxheikqb.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtdvsiagui.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tian-w.cn/Article/details/gtahjbquwf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenzaomai.com/Article/details/gtfpdmecyy.html

[U117] JS：单元测试
来源：http://dali.hfpthk.cn/Article/details/gtptmzyzyh.html

npm i -D vitest;  npx vitest
来源：http://dali.ppjwa.cn/Article/details/gtumwrwqif.html

[U118] JS：开发服务器
来源：http://dali.316326.xyz/Article/details/gtqccewzui.html

npm i -D vite;  npx vite
来源：http://dali.shuidangran.top/Article/details/gtdioczwbw.html

[U119] JS：生产构建
来源：http://dali.jyoumei.cn/Article/details/gtkbgljxba.html

npx vite build
来源：http://dali.redwolf501.top/Article/details/gtwpxddwph.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dianchejie.cn/Article/details/gtouktscle.html

import.meta.env.VITE_API_URL
来源：http://dali.yonumen.top/Article/details/gtgiwcuxnz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gteuirwejw.html

统计汇总
来源：http://dali.snrcjt.cn/Article/details/gtxptsclbi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gteciaxdvr.html

按语言统计（条）：
来源：http://dali.gogol.net.cn/Article/details/gtbgluodmw.html

Python ......... 252
来源：http://dali.kuanghao11.cn/Article/details/gtjgaynhjg.html

PHP ............ 252
来源：http://dali.ydzc1.top/Article/details/gtxhfpmfxl.html

JavaScript ..... 252
来源：http://dali.gotoacloud.top/Article/details/gtjdoapwhn.html

TypeScript ..... 212
来源：http://dali.cheryme.top/Article/details/gtaogjztbn.html

Java ........... 212
来源：http://dali.ydzc1.top/Article/details/gtugennrst.html

Go ............. 212
来源：http://dali.nwbrower.top/Article/details/gtworzfsdx.html

Ruby ........... 212
来源：http://dali.tanke756.top/Article/details/gtagluawqy.html

C# ............. 212
来源：http://dali.tianlin.xyz/Article/details/gttykcnjwv.html

C .............. 30
来源：http://dali.cqqwz.cn/Article/details/gttjwtnevf.html

C++ ............ 30
来源：http://dali.fengsongda.top/Article/details/gtyagcfhms.html

SQL ............ 90
来源：http://dali.tian-w.cn/Article/details/gtzbbhpngb.html

Bash ........... 80
来源：http://dali.zhoulong.xyz/Article/details/gtuwhtcpfs.html

Kotlin ......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gtecbqrkpn.html

Swift .......... 15
来源：http://dali.bjfxy.top/Article/details/gtsfpiiikr.html

Lua ............ 10
来源：http://dali.gotoacloud.top/Article/details/gtnnnitfxj.html

Perl ........... 10
来源：http://dali.svipenyu.cn/Article/details/gtnijldrai.html

Scala .......... 10
来源：http://dali.chenzaomai.com/Article/details/gtrcjllrid.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtvlmgmmea.html

合计 ........... 2106 条
来源：http://dali.shzxlz.cn/Article/details/gtnpwkszkx.html

按章节统计：
来源：http://dali.zhengqikj.top/Article/details/gtkfvzimqg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gtmybkiuwj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtahoynijw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gthursztte.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gthpggeuyz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sysykeji.top/Article/details/gtssclserz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.snrcjt.cn/Article/details/gtakcencea.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtuwbekkxg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gtyhltearz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtxfzmhqsx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gttbjdkeor.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtbljiivtr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtafrzwllv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtvtitybqg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gtfhvpcdyj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxuanxn.top/Article/details/gtkjyurwqa.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gttyhkkzmz.html

Q SQL 专题                              90
来源：http://dali.zhiwuduotai.top/Article/details/gtegzbfamb.html

R Bash 专题                             80
来源：http://dali.yuanzhike.top/Article/details/gtmptxinjl.html

S C / C++ 专题                          60
来源：http://dali.smart0.xyz/Article/details/gtqvuzwrzw.html

T 其他语言补充                          60
来源：http://dali.9152youxi.cn/Article/details/gtqpnsgoej.html

U 高频实用片段                         120
来源：http://dali.tianlin.xyz/Article/details/gtkzwewpvg.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtyrbklsqo.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gtpcecqiia.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtlystyeev.html

使用提醒
来源：http://dali.daria6918.cn/Article/details/gteujztssz.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gturgbsqiu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yangfankeji.com/Article/details/gtyjplegso.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaaxkbvbw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jyoumei.cn/Article/details/gtamhnoyta.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tanke756.top/Article/details/gtythhnfym.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.mhx1999.top/Article/details/gtpylfnmnj.html

—— 文件结束 ——
来源：http://dali.ehwqpu.com/Article/details/gtcsnrvxqm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtsbjjylvw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ybcxt.top/Article/details/gtetyiqteg.html

Common Programming Examples Cheat Book
来源：http://dali.xziqi.cn/Article/details/gtuewbwtso.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtcsntzhnz.html

【收录内容】
来源：http://dali.smart0.xyz/Article/details/gtiehvujnn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhixingplan.top/Article/details/gtzvhhmwob.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gogol.net.cn/Article/details/gtbperyshg.html

SQL · Bash · C · C++
来源：http://dali.jlsjyb.cn/Article/details/gtkhmdzuyt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhengqikj.top/Article/details/gtogzupkra.html

【使用说明】
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvrybooq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ehwqpu.com/Article/details/gtgitkdsvu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.0kj1m.cn/Article/details/gtbssehofh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.redwolf501.top/Article/details/gtoeotpdsa.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yonumen.top/Article/details/gthidaqxxs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dianchejie.cn/Article/details/gtnlrztier.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenjidiqi.icu/Article/details/gtoufyruhp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hammf.cn/Article/details/gtvgievyze.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuanzx.com/Article/details/gtnsknxrmo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yanxiufei.cn/Article/details/gttvkyxztd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.bjfxy.top/Article/details/gtumjrcflg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cdnleiting.top/Article/details/gtkzrlftay.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.birdmap.top/Article/details/gtuiosadbm.html

【文件统计】
来源：http://dali.yuanzhike.top/Article/details/gtonotgqif.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xuetiantiany.cn/Article/details/gtzrazowib.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gtqxfjmqoc.html

目  录
来源：http://dali.guowangkeji.top/Article/details/gtwxkojuzl.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtdbrxtinm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.tian-w.cn/Article/details/gtcvkchexq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gtuqixtlqp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtnpoqsmvk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtpoogywel.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtaskricza.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gtgljtumcv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yangfankeji.com/Article/details/gtpugnsgsq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.pycfn.com/Article/details/gtokezaeri.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtrvhqdbhn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cdnleiting.top/Article/details/gtxfkefrni.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtsmgpkbtn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtmjdiblpn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtoedqsjgp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jianghu66.top/Article/details/gthvvqtqrv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinqigufen.top/Article/details/gtekqhjign.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtxwzvqkcl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258888.top/Article/details/gtmbzhxgsd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fengsongda.top/Article/details/gtgommllor.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.daxiang520.top/Article/details/gtirklxdls.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuoaxizhb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gtyenbpjkq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwvoabbam.html

A. 基础语法与类型
来源：http://dali.tianlin.xyz/Article/details/gtswythfev.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtnigmbyms.html

[A01] Hello World
来源：http://dali.cashguo.top/Article/details/gtuhyqxnka.html

Py:   print("Hello, World!")
来源：http://dali.meibo888.top/Article/details/gtvfzogkhk.html

PHP:  echo "Hello, World!";
来源：http://dali.guannengcc.top/Article/details/gttduzjfgm.html

JS:   console.log("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtdemtwsnl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ppjwa.cn/Article/details/gtzxtfpyrs.html

Java: System.out.println("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gtvashdfsb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nanxinkj.top/Article/details/gtaeskxbtw.html

Ruby: puts "Hello, World!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcispcski.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gtbmldprnz.html

[A02] 变量声明与赋值
来源：http://dali.shuidangran.top/Article/details/gtwonapwup.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ydzc1.top/Article/details/gtnbopnggk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtmzyryqaw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.guowangkeji.top/Article/details/gtbvcfajah.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttadxuoqe.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtoolxgrbc.html

Go:   name := "Alex"; age := 20
来源：http://dali.xuetiantiany.cn/Article/details/gtxlimsqqh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zdqjudy.top/Article/details/gtthudgdzt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteloerunl.html

[A03] 常量定义
来源：http://dali.kuanghao11.cn/Article/details/gtgjhlmkes.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenzaomai.com/Article/details/gtqdxacnyf.html

PHP:  const PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtcplxiwkh.html

JS:   const PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtmgsjhfbl.html

TS:   const PI: number = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtrrvnabqv.html

Java: static final double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtigocrxtv.html

Go:   const PI = 3.14159
来源：http://dali.zhongyouzk.top/Article/details/gtytqtfviw.html

Ruby: PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gtgwdgjuwg.html

C#:   const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtgajhgjrp.html

[A04] 判断变量类型
来源：http://dali.shuidangran.top/Article/details/gtkwigymoq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.dianchejie.cn/Article/details/gtvmaundmq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj20258888.top/Article/details/gtowayoyrz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gtokixiwkc.html

TS:   typeof x; x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gtqitiiasq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrtjelua.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sweek.top/Article/details/gtridqdioc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.aizwys.cn/Article/details/gteabrkias.html

C#:   x.GetType().Name; x is int
来源：http://dali.shuidangran.top/Article/details/gtmmlflcvr.html

[A05] 整数除法与取模
来源：http://dali.dashuyun.cn/Article/details/gtivpsixsm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daria6918.cn/Article/details/gtkfmnvvys.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtmduntrua.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtsublhrft.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtfiuezowr.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppuxouwz.html

Go:   7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtovwfaenz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibxszkcm.html

C#:   7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtssrltxvk.html

[A06] 字符串转数字
来源：http://dali.shuidangran.top/Article/details/gtcunxarxk.html

Py:   int("42"); float("3.14")
来源：http://dali.sysykeji.top/Article/details/gtkskufmhp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yj20258.top/Article/details/gtdiufrpdh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aizwys.cn/Article/details/gtkecwadhp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ydzc1.top/Article/details/gtfdmbtkpw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj202588.top/Article/details/gtshklhgzn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guannengcc.top/Article/details/gtzpvliwvi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hywenlv.cn/Article/details/gtaemqxqiu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprikfvrh.html

[A07] 数字转字符串
来源：http://dali.tian-w.cn/Article/details/gtdpilkncd.html

Py:   str(42)
来源：http://dali.xziqi.cn/Article/details/gtkuedhwwb.html

PHP:  (string) 42; strval(42)
来源：http://dali.aizwys.cn/Article/details/gtzcleabeq.html

JS:   String(42); (42).toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqetfldg.html

TS:   String(42)
来源：http://dali.zycfv.cn/Article/details/gtvixfkybs.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.sxryk.cn/Article/details/gthnzhxgch.html

Go:   strconv.Itoa(42)
来源：http://dali.dashuyun.cn/Article/details/gtkykhfnhs.html

Ruby: 42.to_s
来源：http://dali.yj20258888.top/Article/details/gtmogcktig.html

C#:   42.ToString()
来源：http://dali.chenlongwang.top/Article/details/gtazbbbaqy.html

[A08] 取整与四舍五入
来源：http://dali.tanke756.top/Article/details/gtdzirqday.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtqyxfotbp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinqigufen.top/Article/details/gtchklwrxd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtcgsjvgda.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.andypj.xyz/Article/details/gtgblllwbm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtngsnengy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpidxmccb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.redwolf501.top/Article/details/gtxodvddqy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtofszmwlc.html

[A09] 绝对值与最大最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpxnjnbi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtdafhfsdk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.316326.xyz/Article/details/gtsjmjtkjk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gthvsixtrk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yongpay.top/Article/details/gtrwwlnjfh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtwbrdeuuv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.chenlongwang.top/Article/details/gtxzfjfiot.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sysykeji.top/Article/details/gtvvzrlusu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtjwqnbqkr.html

[A10] 生成随机数
来源：http://dali.chenlongwang.top/Article/details/gtuljzsnwg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwriwkiay.html

PHP:  random_int(1, 100);
来源：http://dali.gotoacloud.top/Article/details/gtqbffhrcw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuanzx.com/Article/details/gtuftvxqci.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pycfn.com/Article/details/gtwfxahjaa.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jlsjyb.cn/Article/details/gthnhpufit.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.dianchejie.cn/Article/details/gthiayymrs.html

Ruby: rand(1..100)
来源：http://dali.guowangkeji.top/Article/details/gttkgejqne.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfuhfszq.html

[A11] 条件表达式（三元）
来源：http://dali.quarkkingdee.top/Article/details/gtdkhzjwrx.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.redwolf501.top/Article/details/gtpuwbysrh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtartbvntl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtumyyomjl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihhaysoh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gtgijcnmxv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jianghu66.top/Article/details/gthzupiztz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gtsgsfsdwb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtotawdqip.html

[A12] 字符串插值 / 格式化
来源：http://dali.yonumen.top/Article/details/gtzwpiugwe.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xuetiantiany.cn/Article/details/gttedrrnwp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hammf.cn/Article/details/gthldbggty.html

JS:   `Hello, ${name}!`
来源：http://dali.zhengqikj.top/Article/details/gtcggfbwsb.html

TS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangtech.top/Article/details/gtahmwbtdg.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.pycfn.com/Article/details/gtgkltrczi.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.tian-w.cn/Article/details/gtazwvkifb.html

Ruby: "Hello, #{name}!"
来源：http://dali.pycfn.com/Article/details/gtahaqbeiq.html

C#:   $"Hello, {name}!"
来源：http://dali.smart0.xyz/Article/details/gtjdgkgrqn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.birdmap.top/Article/details/gtlfyfjzqp.html


<!-- 参考信息 -->