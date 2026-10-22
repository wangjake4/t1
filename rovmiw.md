代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.tian-w.cn/Article/details/gtobumexjr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinghuilouyu.cn/Article/details/gtplrmsefz.html

[U84] JS：CommonJS 写法
来源：http://dali.hfpthk.cn/Article/details/gtzqakfjho.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xylfe.cn/Article/details/gtoiyuhjbv.html

[U85] JS：可选链
来源：http://dali.shangyingyoupin.top/Article/details/gtumsxgdjg.html

a?.b?.c
来源：http://dali.ehwqpu.com/Article/details/gtwnpusdwq.html

[U86] JS：空值合并
来源：http://dali.tanke756.top/Article/details/gtyzjcfnxh.html

a ?? b
来源：http://dali.iojbl.cn/Article/details/gtaoydakfe.html

[U87] JS：解构默认值
来源：http://dali.yuanzhike.top/Article/details/gtsmkwrpeg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.kuanghao11.cn/Article/details/gtdphrogpa.html

[U88] JS：对象展开合并
来源：http://dali.zdqjudy.top/Article/details/gteyjmxwsx.html

{ ...a, ...b }
来源：http://dali.smart0.xyz/Article/details/gtxyeqnagz.html

[U89] JS：数组去重
来源：http://dali.yanxiufei.cn/Article/details/gtjnpkbfmg.html

[...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtiioamuxy.html

[U90] JS：数字数组排序
来源：http://dali.jlsjyb.cn/Article/details/gtbhbuuniu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtbgnmkmay.html

[U91] JS：对象键值遍历
来源：http://dali.ppjwa.cn/Article/details/gtjacyoept.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztpfvajk.html

[U92] JS：深拷贝
来源：http://dali.9152youxi.cn/Article/details/gtbezhkcqw.html

structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtqqlmsknm.html

[U93] JS：模板字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgmhctfq.html

`共 ${n} 条`
来源：http://dali.jinghuilouyu.cn/Article/details/gtazrfmaoo.html

[U94] JS：箭头函数
来源：http://dali.andypj.xyz/Article/details/gtyjlpfgvf.html

const double = x => x * 2;
来源：http://dali.chenjidiqi.icu/Article/details/gtqpchpwze.html

[U95] JS：Promise 包装
来源：http://dali.pengpengdd.cyou/Article/details/gtwdyvvpbx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhoulong.xyz/Article/details/gtgvitycit.html

[U96] JS：async/await 与异常
来源：http://dali.ehwqpu.com/Article/details/gtlqijzmjg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtblpzhrsy.html

[U97] JS：并发请求
来源：http://dali.zhongyouzk.top/Article/details/gtudiahnui.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtgvyqliut.html

[U98] JS：fetch 带 JSON
来源：http://dali.shzxlz.cn/Article/details/gtlvkycnbq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.316326.xyz/Article/details/gtubtmuyfz.html

[U99] JS：事件监听
来源：http://dali.guannengcc.top/Article/details/gtbgcvrmbc.html

el.addEventListener("click", e => {})
来源：http://dali.0kj1m.cn/Article/details/gtjooapmws.html

[U100] JS：DOM 查询
来源：http://dali.ehwqpu.com/Article/details/gtdfqdziro.html

document.querySelector(".item")
来源：http://dali.zhixingplan.top/Article/details/gtoexbcfyg.html

[U101] JS：classList 操作
来源：http://dali.316326.xyz/Article/details/gtjiklphcd.html

el.classList.toggle("active")
来源：http://dali.chenjidiqi.icu/Article/details/gtsynkdqzr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gtxlgiwvau.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenjidiqi.icu/Article/details/gttqtcmlyi.html

[U103] JS：定时器
来源：http://dali.yvedp.cn/Article/details/gtrxwnsxvy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yongpay.top/Article/details/gtugjhqslr.html

[U104] JS：防抖
来源：http://dali.smart0.xyz/Article/details/gtuujnmiaf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtjcmzqrja.html

[U105] JS：节流
来源：http://dali.zhengqikj.top/Article/details/gtnwbbassr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.snrcjt.cn/Article/details/gtqcutgkvq.html

[U106] JS：日期格式化
来源：http://dali.cheryme.top/Article/details/gtlobnzvkj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sufxvd.cn/Article/details/gtpemsdwdh.html

[U107] JS：数字千分位
来源：http://dali.cucudq.cn/Article/details/gtzexkmvij.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gtmcipmtjf.html

[U108] JS：随机整数
来源：http://dali.pycfn.com/Article/details/gtvmrnzajk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sufxvd.cn/Article/details/gthdstjcsa.html

[U109] JS：数组分组
来源：http://dali.havefunace.top/Article/details/gtpbwzlcoe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtcudyudml.html

[U110] JS：数组分块
来源：http://dali.daria6918.cn/Article/details/gtcjxqtusb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tanke756.top/Article/details/gtroiczdrn.html

[U111] JS：对象转 Map
来源：http://dali.zhoulong.xyz/Article/details/gtsmkubxdr.html

new Map(Object.entries(obj))
来源：http://dali.yj20258888.top/Article/details/gtmhysluqt.html

[U112] JS：字符串补位
来源：http://dali.kuanghao11.cn/Article/details/gtemkfoosu.html

"7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gterhhzweq.html

[U113] JS：正则替换全部
来源：http://dali.birdmap.top/Article/details/gtuckymygq.html

s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtephforzw.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258888.top/Article/details/gtjlydhdnx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtltaqvtqu.html

[U115] JS：生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtekzamwnv.html

crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeevrfmk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fzhhl.top/Article/details/gttmpcbeai.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shzxlz.cn/Article/details/gtogabyrpl.html

[U117] JS：单元测试
来源：http://dali.tian-w.cn/Article/details/gtuxplvert.html

npm i -D vitest;  npx vitest
来源：http://dali.yanxiufei.cn/Article/details/gtmnfntbst.html

[U118] JS：开发服务器
来源：http://dali.yongpay.top/Article/details/gtrcvasgbg.html

npm i -D vite;  npx vite
来源：http://dali.yvedp.cn/Article/details/gtkxewspow.html

[U119] JS：生产构建
来源：http://dali.yangfankeji.com/Article/details/gtmfekgkcj.html

npx vite build
来源：http://dali.cqqwz.cn/Article/details/gtlsqykgzb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.iojbl.cn/Article/details/gtsgkxopgy.html

import.meta.env.VITE_API_URL
来源：http://dali.jianghu66.top/Article/details/gtdywtniak.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtdrfgsxfo.html

统计汇总
来源：http://dali.pengpengdd.cyou/Article/details/gtccjnozzh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtiapsnibj.html

按语言统计（条）：
来源：http://dali.jyoumei.cn/Article/details/gtjskupgxq.html

Python ......... 252
来源：http://dali.hammf.cn/Article/details/gtdoqdwvzz.html

PHP ............ 252
来源：http://dali.cheryme.top/Article/details/gtfywttyrw.html

JavaScript ..... 252
来源：http://dali.daxiang520.top/Article/details/gtmwagsadb.html

TypeScript ..... 212
来源：http://dali.haohaochexian.top/Article/details/gteqouokhw.html

Java ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuoxtxnht.html

Go ............. 212
来源：http://dali.snrcjt.cn/Article/details/gtfwodsbxt.html

Ruby ........... 212
来源：http://dali.birdmap.top/Article/details/gtczqqioqh.html

C# ............. 212
来源：http://dali.zhixingplan.top/Article/details/gtsuylsfor.html

C .............. 30
来源：http://dali.daria6918.cn/Article/details/gtdypcekcx.html

C++ ............ 30
来源：http://dali.cqqwz.cn/Article/details/gtubzniobg.html

SQL ............ 90
来源：http://dali.yj20258888.top/Article/details/gtifarfbcn.html

Bash ........... 80
来源：http://dali.shangyingyoupin.top/Article/details/gtfqlelper.html

Kotlin ......... 15
来源：http://dali.zhixingplan.top/Article/details/gtosewmsjg.html

Swift .......... 15
来源：http://dali.jiagoushi.top/Article/details/gtunuuitut.html

Lua ............ 10
来源：http://dali.smart0.xyz/Article/details/gtyqcmuiby.html

Perl ........... 10
来源：http://dali.yvedp.cn/Article/details/gtwhiwpekm.html

Scala .......... 10
来源：http://dali.gotoacloud.top/Article/details/gtzhjrrlfa.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtoxjxosbn.html

合计 ........... 2106 条
来源：http://dali.ydzc1.top/Article/details/gtzxtyfojv.html

按章节统计：
来源：http://dali.shangyingyoupin.top/Article/details/gtyriprrvs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258888.top/Article/details/gtvzstmsuo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gtcxuohijf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwvgzfhp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gthdtyimys.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jlsjyb.cn/Article/details/gtmuibeqsz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.9152youxi.cn/Article/details/gtnhlgrwlh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtfiddseiz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tian-w.cn/Article/details/gtdylelqkt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gttglashzt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.redwolf501.top/Article/details/gtbiezkcgn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtkausffmk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtunvezzea.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gttcgcofkx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gtprtwfhqw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ppjwa.cn/Article/details/gtgttusrud.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtrtpgdfhl.html

Q SQL 专题                              90
来源：http://dali.gaohongyu789.top/Article/details/gtjxxjfzbu.html

R Bash 专题                             80
来源：http://dali.cdnleiting.top/Article/details/gtgyuhrzap.html

S C / C++ 专题                          60
来源：http://dali.jyoumei.cn/Article/details/gtvkswcrlx.html

T 其他语言补充                          60
来源：http://dali.sysykeji.top/Article/details/gtiksuyklp.html

U 高频实用片段                         120
来源：http://dali.kuanghao11.cn/Article/details/gthgkyuqbz.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtbiaelrfs.html

合计                                  2106 条
来源：http://dali.gaohongyu789.top/Article/details/gtegybyeag.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtytyflbam.html

使用提醒
来源：http://dali.yonumen.top/Article/details/gtubfvztoy.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtqabkktas.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhengqikj.top/Article/details/gtzxvdgmsi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tianlin.xyz/Article/details/gtmgqnpsaz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gogol.net.cn/Article/details/gtjmbpgvmm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.iojbl.cn/Article/details/gtwyoxvcqx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.0kj1m.cn/Article/details/gtdoqmbjpe.html

—— 文件结束 ——
来源：http://dali.0kj1m.cn/Article/details/gtlndnqiuh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttnyonnfk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yvedp.cn/Article/details/gtpdkltdep.html

Common Programming Examples Cheat Book
来源：http://dali.316326.xyz/Article/details/gtyumgfutk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgtuqixia.html

【收录内容】
来源：http://dali.shangyingyoupin.top/Article/details/gttsqzxkym.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.redwolf501.top/Article/details/gtyclbwbpw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.snrcjt.cn/Article/details/gtvchnseng.html

SQL · Bash · C · C++
来源：http://dali.yj202588.top/Article/details/gtjhkwvtuc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aibaodan.cn/Article/details/gtadadjqgn.html

【使用说明】
来源：http://dali.jinqigfzy.top/Article/details/gthiedgmac.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hnxiangtu.top/Article/details/gtmdwlibqd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dianchejie.cn/Article/details/gtinoohual.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gotoacloud.top/Article/details/gtnwrfzegu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgfzy.top/Article/details/gtyvkxyebq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gaohongyu789.top/Article/details/gtiktwoqoo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhongyouzk.top/Article/details/gtvaymfwao.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jianghu66.top/Article/details/gtardrqpum.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jiagoushi.top/Article/details/gtomsfrwgd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgfzy.top/Article/details/gtfncqshqf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cheryme.top/Article/details/gtbusjzjxb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hfpthk.cn/Article/details/gtrtuqoajo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hywenlv.cn/Article/details/gtqdxedqve.html

【文件统计】
来源：http://dali.snrcjt.cn/Article/details/gtygoofrpd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenzaomai.com/Article/details/gtscqzeodd.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtytvfazjx.html

目  录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxkyqmgt.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtumoqhhfi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.andypj.xyz/Article/details/gtzxhfgfvh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gttolqewss.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtoekrejtu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.vqdsnc.cn/Article/details/gtqxiejsfy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmraztaa.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhixingplan.top/Article/details/gtdxujqdwq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtpqfbvzfi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ppjwa.cn/Article/details/gtytpbgzib.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtlekvptrj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.wangdashe.top/Article/details/gtevijmygh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtfdgtjosq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtqmirylma.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtgwqzraac.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tanke756.top/Article/details/gtowyxhzfs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnqzz.top/Article/details/gtaoiookve.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gttgjyefsg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtupoyrzgw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gogol.net.cn/Article/details/gtdxmvsfse.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.wangdashe.top/Article/details/gtklphyash.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpptylwpr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gtsamgngfm.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzaebysmf.html

A. 基础语法与类型
来源：http://dali.yuanzhike.top/Article/details/gtuijvawby.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtccfazkpo.html

[A01] Hello World
来源：http://dali.haohaochexian.top/Article/details/gtbdowetcg.html

Py:   print("Hello, World!")
来源：http://dali.jlsjyb.cn/Article/details/gtbjfpnfqt.html

PHP:  echo "Hello, World!";
来源：http://dali.c1oappe.top/Article/details/gtoneeplym.html

JS:   console.log("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpngbfjop.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yonumen.top/Article/details/gtmgqblnun.html

Java: System.out.println("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gtssrkcchu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hammf.cn/Article/details/gtvwgaxdfx.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gtjbxocqtu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gthqjywsby.html

[A02] 变量声明与赋值
来源：http://dali.sufxvd.cn/Article/details/gtrlotubdc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nwbrower.top/Article/details/gtsxzmgxay.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtiuimcqnh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtsvrdgrxd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuanzx.com/Article/details/gtohajuioh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zycfv.cn/Article/details/gtarnplfjq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gtwyonfedc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.snrcjt.cn/Article/details/gtktlgfnus.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gtaavptbow.html

[A03] 常量定义
来源：http://dali.nwbrower.top/Article/details/gtmslwtuyr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.guannengcc.top/Article/details/gtgsrfpacy.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtyiobcfxg.html

JS:   const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtrwpqyfrw.html

TS:   const PI: number = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtcljimpqb.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtcclpikji.html

Go:   const PI = 3.14159
来源：http://dali.aibaodan.cn/Article/details/gtbwvpsfmy.html

Ruby: PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gtubojpggq.html

C#:   const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtcvweuhjm.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gtzuartlqn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvnvkeab.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.meibo888.top/Article/details/gtkwswxuxn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tian-w.cn/Article/details/gtawhlzazm.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258888.top/Article/details/gtpexvkmda.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.birdmap.top/Article/details/gtlagyitjo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.redwolf501.top/Article/details/gtjpgguuyc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ehwqpu.com/Article/details/gtvqwsbjag.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhixingplan.top/Article/details/gtuwtjloan.html

[A05] 整数除法与取模
来源：http://dali.guannengcc.top/Article/details/gtuldyinlh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhiwuduotai.top/Article/details/gtobxdagvp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtccyqglak.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtslgqndpq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtetzevqnx.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gtkeiztgjj.html

Go:   7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtnblpfbti.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtbrsnxjqa.html

C#:   7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtopfvuski.html

[A06] 字符串转数字
来源：http://dali.tanke756.top/Article/details/gtxixlqdwg.html

Py:   int("42"); float("3.14")
来源：http://dali.fengsongda.top/Article/details/gtptbipqkw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgncfxngf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenlongwang.top/Article/details/gtiinbzzcl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhoulong.xyz/Article/details/gtybmywjra.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenzaomai.com/Article/details/gtcbneuair.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.birdmap.top/Article/details/gtrlllvklg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.guannengcc.top/Article/details/gtxcjqbkzu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pycfn.com/Article/details/gtklyqbowc.html

[A07] 数字转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlezjikhg.html

Py:   str(42)
来源：http://dali.zycfv.cn/Article/details/gtotzysumm.html

PHP:  (string) 42; strval(42)
来源：http://dali.smart0.xyz/Article/details/gttyetvgym.html

JS:   String(42); (42).toString()
来源：http://dali.meibo888.top/Article/details/gtlawqqjcz.html

TS:   String(42)
来源：http://dali.ybcxt.top/Article/details/gtxgmcpxyw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtcawdnexb.html

Go:   strconv.Itoa(42)
来源：http://dali.xuanzx.com/Article/details/gtlozzffdt.html

Ruby: 42.to_s
来源：http://dali.jiagoushi.top/Article/details/gtyjyvbtpi.html

C#:   42.ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtccwcxxgi.html

[A08] 取整与四舍五入
来源：http://dali.birdmap.top/Article/details/gtdwcptbzb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtllshpnkv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yonumen.top/Article/details/gtutfahgbi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ivvv.top/Article/details/gtnkeqhxtx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yanxiufei.cn/Article/details/gtqpncrain.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtkytptmim.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gthydupihs.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yangfankeji.com/Article/details/gtfmrkyeav.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gtxqtadxli.html

[A09] 绝对值与最大最小值
来源：http://dali.tian-w.cn/Article/details/gtdpgnesde.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yongpay.top/Article/details/gtajjbzuol.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtaiklgunx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtkkijbfjs.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.birdmap.top/Article/details/gtqncqhugl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtjaeulbrg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cashguo.top/Article/details/gtpygttbat.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gogol.net.cn/Article/details/gthyfcggfd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.c1oappe.top/Article/details/gttwgvxnqo.html

[A10] 生成随机数
来源：http://dali.svipenyu.cn/Article/details/gtqwqzflch.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gogol.net.cn/Article/details/gtfidjgdlw.html

PHP:  random_int(1, 100);
来源：http://dali.0kj1m.cn/Article/details/gtrcgleejd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinqigufen.top/Article/details/gtjesumuxo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gtcmvmfkwl.html

Java: new Random().nextInt(100) + 1
来源：http://dali.snrcjt.cn/Article/details/gtggbshras.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.dianchejie.cn/Article/details/gtzprwelwh.html

Ruby: rand(1..100)
来源：http://dali.hfpthk.cn/Article/details/gtbkcyyrnh.html

C#:   new Random().Next(1, 101)
来源：http://dali.xinyue.icu/Article/details/gtwxsdgauo.html

[A11] 条件表达式（三元）
来源：http://dali.hammf.cn/Article/details/gtbngrgita.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hywenlv.cn/Article/details/gtslwqhhdw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtbabqqtot.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gtknktpsib.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gtrctcocpg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtywbadjnh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.meibo888.top/Article/details/gtlqgpuuik.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gtizhybxod.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtumiuwznq.html

[A12] 字符串插值 / 格式化
来源：http://dali.hysaishi.cn/Article/details/gtprwcfmay.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jyoumei.cn/Article/details/gtktkepcpp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yuxming.cn/Article/details/gtxxomailt.html

JS:   `Hello, ${name}!`
来源：http://dali.gotoacloud.top/Article/details/gtwwfbboci.html

TS:   `Hello, ${name}!`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkeqrfjqq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.quarkkingdee.top/Article/details/gtmiuehrlc.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvytrgmiq.html

Ruby: "Hello, #{name}!"
来源：http://dali.wangshuangyany.cn/Article/details/gtdzznretj.html

C#:   $"Hello, {name}!"
来源：http://dali.chenlongwang.top/Article/details/gttpdexnfl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jianghu66.top/Article/details/gtftboyraf.html

Py:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtgmaqtpnm.html

PHP:  "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtasavmxbh.html

JS:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtejbqcpvs.html

TS:   "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtxjifduer.html

Java: "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtydhknyhr.html

Go:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtdepmbuwd.html

Ruby: "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtndqvvfwz.html

C#:   "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtdhbaxozu.html


<!-- 参考信息 -->