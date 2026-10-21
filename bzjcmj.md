代发 wailian999

[U81] JS：初始化项目
来源：http://dali.jianghu66.top/Article/details/gtkgmajtsz.html

npm init -y;  npm i express
来源：http://dali.vqdsnc.cn/Article/details/gttfpvnzpu.html

[U82] JS：package.json 脚本
来源：http://dali.ivvv.top/Article/details/gtdkwsidys.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.bjfxy.top/Article/details/gtstfifkdz.html

[U83] JS：ES Module 导入导出
来源：http://dali.birdmap.top/Article/details/gtrrfmmoez.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtqhmlolie.html

[U84] JS：CommonJS 写法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubyqihlt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cdnleiting.top/Article/details/gtpdghazdu.html

[U85] JS：可选链
来源：http://dali.tian-w.cn/Article/details/gtwugcfflk.html

a?.b?.c
来源：http://dali.vqdsnc.cn/Article/details/gtxorsktjm.html

[U86] JS：空值合并
来源：http://dali.shuidangran.top/Article/details/gtylhafijl.html

a ?? b
来源：http://dali.yj20258.top/Article/details/gtqoxibuhp.html

[U87] JS：解构默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqkazjfb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hammf.cn/Article/details/gtfxpipikw.html

[U88] JS：对象展开合并
来源：http://dali.nanxinkj.top/Article/details/gtfznqihnx.html

{ ...a, ...b }
来源：http://dali.yj202588.top/Article/details/gtufnlhcbf.html

[U89] JS：数组去重
来源：http://dali.aizwys.cn/Article/details/gttkuyermh.html

[...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtvpkddxza.html

[U90] JS：数字数组排序
来源：http://dali.iojbl.cn/Article/details/gtxinuxwch.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtacphwkza.html

[U91] JS：对象键值遍历
来源：http://dali.yonumen.top/Article/details/gtwtzrlfkl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.kuanghao11.cn/Article/details/gtciyavkeo.html

[U92] JS：深拷贝
来源：http://dali.jyoumei.cn/Article/details/gtvfjirepz.html

structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtysmjepdw.html

[U93] JS：模板字符串
来源：http://dali.nwbrower.top/Article/details/gtmkvnwkpk.html

`共 ${n} 条`
来源：http://dali.9152youxi.cn/Article/details/gtivxlaiml.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhcybbtd.html

const double = x => x * 2;
来源：http://dali.ivvv.top/Article/details/gtsnjlxzzv.html

[U95] JS：Promise 包装
来源：http://dali.xinyue.icu/Article/details/gtgqtupwdp.html

new Promise((resolve, reject) => {})
来源：http://dali.nwbrower.top/Article/details/gtmqurtlet.html

[U96] JS：async/await 与异常
来源：http://dali.wangdashe.top/Article/details/gttmzvvayc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtpaqgafys.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtlwowiipj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtmxwrljkq.html

[U98] JS：fetch 带 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtowyugbsf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258888.top/Article/details/gtdfroitks.html

[U99] JS：事件监听
来源：http://dali.yongpay.top/Article/details/gtcwbdvjpi.html

el.addEventListener("click", e => {})
来源：http://dali.jiagoushi.top/Article/details/gthmackzxv.html

[U100] JS：DOM 查询
来源：http://dali.hysaishi.cn/Article/details/gttdpevmhf.html

document.querySelector(".item")
来源：http://dali.wangshuangyany.cn/Article/details/gtjllbkufr.html

[U101] JS：classList 操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcswbbgby.html

el.classList.toggle("active")
来源：http://dali.nwbrower.top/Article/details/gthztuaram.html

[U102] JS：本地存储
来源：http://dali.dianchejie.cn/Article/details/gtdntmzcyt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkieguxm.html

[U103] JS：定时器
来源：http://dali.zhiwuduotai.top/Article/details/gtrubjbjrz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.iojbl.cn/Article/details/gthopkyqdg.html

[U104] JS：防抖
来源：http://dali.dianchejie.cn/Article/details/gtxadmomeh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtoxghqgtv.html

[U105] JS：节流
来源：http://dali.meibo888.top/Article/details/gtbmptftpm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgufenzy.top/Article/details/gtwiwrfaeh.html

[U106] JS：日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtnptwgsvs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jqgufenzy.top/Article/details/gtzvdemcgy.html

[U107] JS：数字千分位
来源：http://dali.hammf.cn/Article/details/gtwyacyqzw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtxriyawan.html

[U108] JS：随机整数
来源：http://dali.jqgfzy.top/Article/details/gtlyganetp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cheryme.top/Article/details/gtussiiioj.html

[U109] JS：数组分组
来源：http://dali.andypj.xyz/Article/details/gtqzlteeaa.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtuxkacemi.html

[U110] JS：数组分块
来源：http://dali.dianchejie.cn/Article/details/gttvyusuvf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhiwuduotai.top/Article/details/gtsqpwlmiy.html

[U111] JS：对象转 Map
来源：http://dali.hywenlv.cn/Article/details/gttrsahisr.html

new Map(Object.entries(obj))
来源：http://dali.yangfankeji.com/Article/details/gtlracxlgr.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gtvmsfqkau.html

"7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtoawkcgmo.html

[U113] JS：正则替换全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiktseldn.html

s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtlxzkmfjo.html

[U114] JS：JSON 深比较
来源：http://dali.yonumen.top/Article/details/gtldchzaay.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtxhbxvihs.html

[U115] JS：生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtfqgotofx.html

crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtwthlkqzf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sufxvd.cn/Article/details/gtxopriicv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.snrcjt.cn/Article/details/gtuknxhkoq.html

[U117] JS：单元测试
来源：http://dali.fzhhl.top/Article/details/gtbebjfncs.html

npm i -D vitest;  npx vitest
来源：http://dali.cdnleiting.top/Article/details/gtxrkokoai.html

[U118] JS：开发服务器
来源：http://dali.guannengcc.top/Article/details/gtfrmqrgzu.html

npm i -D vite;  npx vite
来源：http://dali.shangyingyoupin.top/Article/details/gtgserknis.html

[U119] JS：生产构建
来源：http://dali.andypj.xyz/Article/details/gtpqkzhubm.html

npx vite build
来源：http://dali.hongshengwenyu.top/Article/details/gtwdrlehon.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgfzy.top/Article/details/gtnivtvxrm.html

import.meta.env.VITE_API_URL
来源：http://dali.hnqzz.top/Article/details/gtgosxpzok.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtuskoaqew.html

统计汇总
来源：http://dali.bjfxy.top/Article/details/gtwxkozhzf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmumgqxpd.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gtkakztafr.html

Python ......... 252
来源：http://dali.yanxiufei.cn/Article/details/gtfriozmzz.html

PHP ............ 252
来源：http://dali.zhoulong.xyz/Article/details/gtklkftqvo.html

JavaScript ..... 252
来源：http://dali.gaohongyu789.top/Article/details/gtzwrdcgsg.html

TypeScript ..... 212
来源：http://dali.sufxvd.cn/Article/details/gtubbacdty.html

Java ........... 212
来源：http://dali.yonumen.top/Article/details/gtcmwepwip.html

Go ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gtcitubvfj.html

Ruby ........... 212
来源：http://dali.shzxlz.cn/Article/details/gtrwgrzmls.html

C# ............. 212
来源：http://dali.yvedp.cn/Article/details/gtddbrwewq.html

C .............. 30
来源：http://dali.shzxlz.cn/Article/details/gtzenbgzwv.html

C++ ............ 30
来源：http://dali.redwolf501.top/Article/details/gtckbmrtsq.html

SQL ............ 90
来源：http://dali.pengpengdd.cyou/Article/details/gttksvgroy.html

Bash ........... 80
来源：http://dali.yueranfly.top/Article/details/gtmgexzhre.html

Kotlin ......... 15
来源：http://dali.0kj1m.cn/Article/details/gtjyecaqbt.html

Swift .......... 15
来源：http://dali.xylfe.cn/Article/details/gtsedrsado.html

Lua ............ 10
来源：http://dali.tian-w.cn/Article/details/gtkfujckvg.html

Perl ........... 10
来源：http://dali.sweek.top/Article/details/gtgwopvvqk.html

Scala .......... 10
来源：http://dali.cqqwz.cn/Article/details/gtejpyjzyk.html

------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtslddsvsv.html

合计 ........... 2106 条
来源：http://dali.jqgfzy.top/Article/details/gtocuyqizy.html

按章节统计：
来源：http://dali.xuetiantiany.cn/Article/details/gtrosdkanq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gtprvfxwzw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gtkxlvlosg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gtswgwzksi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.0kj1m.cn/Article/details/gtyymydqxh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cdnleiting.top/Article/details/gtutazkvbw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xinyue.icu/Article/details/gtbxbdxdpt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexoogbub.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.dashuyun.cn/Article/details/gtscsnyxrt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtjgtzkapy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gtdzmirzec.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtfcbpzolr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtvlmzshdt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtppvebhsg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gtwrkpktjf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pengpengdd.cyou/Article/details/gtyljjoimf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtrbjyhnsh.html

Q SQL 专题                              90
来源：http://dali.sxryk.cn/Article/details/gtkxvqtope.html

R Bash 专题                             80
来源：http://dali.aibaodan.cn/Article/details/gtwppqxvyr.html

S C / C++ 专题                          60
来源：http://dali.0kj1m.cn/Article/details/gtzkmjmzxp.html

T 其他语言补充                          60
来源：http://dali.ydzc1.top/Article/details/gtosxywshh.html

U 高频实用片段                         120
来源：http://dali.zdqjudy.top/Article/details/gtpxgwcxsj.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtzowvwvjp.html

合计                                  2106 条
来源：http://dali.yuxming.cn/Article/details/gtybkkthuo.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtkfxzplko.html

使用提醒
来源：http://dali.jianghu66.top/Article/details/gtzxywhdoi.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtziflspyg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.birdmap.top/Article/details/gtgaucwvvg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gogol.net.cn/Article/details/gtadprkyml.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jqgufenzy.top/Article/details/gtahrikuul.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.haohaochexian.top/Article/details/gtrezokgzf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tanke756.top/Article/details/gtflrfmylj.html

—— 文件结束 ——
来源：http://dali.gotoacloud.top/Article/details/gtqtfpcrsb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcwacaenq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shuidangran.top/Article/details/gtwkogyxvu.html

Common Programming Examples Cheat Book
来源：http://dali.ivvv.top/Article/details/gtqeqaenob.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqzmrhtfw.html

【收录内容】
来源：http://dali.jinghuilouyu.cn/Article/details/gthqtsuwpu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.chenjidiqi.icu/Article/details/gtublngrju.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.dianchejie.cn/Article/details/gtqtlgvqdw.html

SQL · Bash · C · C++
来源：http://dali.ppjwa.cn/Article/details/gtkvaijxsj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.kuanghao11.cn/Article/details/gttltkxzso.html

【使用说明】
来源：http://dali.snrcjt.cn/Article/details/gtzuwydwqc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.bjfxy.top/Article/details/gtvendgsnm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigufen.top/Article/details/gteuvwhzhe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yanxiufei.cn/Article/details/gtrkqynirc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj202588.top/Article/details/gtrcgvnmxj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dashuyun.cn/Article/details/gtdrzcbgrn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgummljpe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj202588.top/Article/details/gtaiyzcpcy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hnqzz.top/Article/details/gtblvjvvzw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gogol.net.cn/Article/details/gtlsxiudwy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.vqdsnc.cn/Article/details/gtqcwykdzi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xinyue.icu/Article/details/gtgjnvmyzw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.dianchejie.cn/Article/details/gtsisbxaow.html

【文件统计】
来源：http://dali.cqqwz.cn/Article/details/gtgrqgxabr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zycfv.cn/Article/details/gtmmpuptzn.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtygfprycp.html

目  录
来源：http://dali.pycfn.com/Article/details/gttwwoymdx.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnljwklzh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jyoumei.cn/Article/details/gttrvaxhpm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gtttwgqvac.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtwizosq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hysaishi.cn/Article/details/gtnnianfno.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenzaomai.com/Article/details/gteryqfhgf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cashguo.top/Article/details/gtezcelbka.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtgwnpvsxs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtlojsfrjd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtzxagqnzo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtjvdszzey.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtwdrglmwv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtvzmrdsdj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtdhuuurib.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jianghu66.top/Article/details/gtwbsessrn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.vqdsnc.cn/Article/details/gtgdpdeezg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtnfaoctoo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hnxiangtu.top/Article/details/gtxkzjndsc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.andypj.xyz/Article/details/gtmhdfdilv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.birdmap.top/Article/details/gtzutoedns.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtplkfwrhw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtvlgljbuo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlytgyhgr.html

A. 基础语法与类型
来源：http://dali.316326.xyz/Article/details/gtkugdtlgl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtehozlzmx.html

[A01] Hello World
来源：http://dali.smart0.xyz/Article/details/gtrzdozszs.html

Py:   print("Hello, World!")
来源：http://dali.ydzc1.top/Article/details/gtphoudksz.html

PHP:  echo "Hello, World!";
来源：http://dali.shuidangran.top/Article/details/gteqmqvkbg.html

JS:   console.log("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gtikdcekqe.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shuidangran.top/Article/details/gtthfnwrus.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtxpytlwne.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.fzhhl.top/Article/details/gtnhkgkncb.html

Ruby: puts "Hello, World!"
来源：http://dali.meibo888.top/Article/details/gtipxqawsv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gteugfejke.html

[A02] 变量声明与赋值
来源：http://dali.nanxinkj.top/Article/details/gtehgctplo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinqigfzy.top/Article/details/gtnarchgwm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yuanzhike.top/Article/details/gtdeikacjq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pycfn.com/Article/details/gtahkojhqp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenlongwang.top/Article/details/gtzlmjcmzo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtudkxotnq.html

Go:   name := "Alex"; age := 20
来源：http://dali.dianchejie.cn/Article/details/gttcfxwnft.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnxiangtu.top/Article/details/gtjmeehbcg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gtoykqgqtt.html

[A03] 常量定义
来源：http://dali.daxiang520.top/Article/details/gtmxgrgken.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudfpbqfz.html

PHP:  const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtouqiwlhr.html

JS:   const PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtyovmqali.html

TS:   const PI: number = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtlcegcxvh.html

Java: static final double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtqnlxmnqa.html

Go:   const PI = 3.14159
来源：http://dali.hammf.cn/Article/details/gtcxyorswh.html

Ruby: PI = 3.14159
来源：http://dali.cucudq.cn/Article/details/gtrjtiehap.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtgarkawoi.html

[A04] 判断变量类型
来源：http://dali.birdmap.top/Article/details/gtwiqitylj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guannengcc.top/Article/details/gthjmeouso.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yonumen.top/Article/details/gttlipsfam.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daxiang520.top/Article/details/gtjofbvnfc.html

TS:   typeof x; x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gtvktmzlhg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.9152youxi.cn/Article/details/gthbtpgybj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shuidangran.top/Article/details/gtupshnckl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.aibaodan.cn/Article/details/gtueindtby.html

C#:   x.GetType().Name; x is int
来源：http://dali.jianghu66.top/Article/details/gtkszlypzp.html

[A05] 整数除法与取模
来源：http://dali.shuidangran.top/Article/details/gtatymrzet.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ydzc1.top/Article/details/gtxfutpkpp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtihtaqgaf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtzqodiatx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtcxjxocir.html

Java: 7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtgaceinym.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtbansikuv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtouhceecx.html

C#:   7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtognaunvf.html

[A06] 字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtndssotph.html

Py:   int("42"); float("3.14")
来源：http://dali.fengsongda.top/Article/details/gthiqyxyrr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jlsjyb.cn/Article/details/gtmroqmhru.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gtqsjgjeva.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yj20258.top/Article/details/gtiymenoyt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj202588.top/Article/details/gtommhbogt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yueranfly.top/Article/details/gtodybzgnl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jlsjyb.cn/Article/details/gtqcftuxbp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ydzc1.top/Article/details/gtkdkfgjqn.html

[A07] 数字转字符串
来源：http://dali.yuanzhike.top/Article/details/gtkjsiqyda.html

Py:   str(42)
来源：http://dali.jinqigufen.top/Article/details/gtcmynurgd.html

PHP:  (string) 42; strval(42)
来源：http://dali.gotoacloud.top/Article/details/gtmexclmuz.html

JS:   String(42); (42).toString()
来源：http://dali.aibaodan.cn/Article/details/gthtwfxdih.html

TS:   String(42)
来源：http://dali.chenlongwang.top/Article/details/gtbwfdllos.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jqgfzy.top/Article/details/gtgyuoykqv.html

Go:   strconv.Itoa(42)
来源：http://dali.tianlin.xyz/Article/details/gtfdplofqz.html

Ruby: 42.to_s
来源：http://dali.yuxming.cn/Article/details/gtbmpybrjb.html

C#:   42.ToString()
来源：http://dali.hfpthk.cn/Article/details/gthnkpgcwy.html

[A08] 取整与四舍五入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqfugudi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtvvigxakf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.aibaodan.cn/Article/details/gtksgkqlbw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttronfzci.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhiwuduotai.top/Article/details/gtebowruev.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtzjncpfkb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqvoqlpz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yongpay.top/Article/details/gtgaykfmbc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtmqplnaus.html

[A09] 绝对值与最大最小值
来源：http://dali.hammf.cn/Article/details/gtvieqjuvw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yvedp.cn/Article/details/gthxljyjze.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtrnthmnwf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtkbumrarp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtdfvuucmb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtscrvqhvj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.aibaodan.cn/Article/details/gtfcwbskta.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hfpthk.cn/Article/details/gtkrbogazt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtjumevvzk.html

[A10] 生成随机数
来源：http://dali.wangdashe.top/Article/details/gtrpuazfys.html

Py:   import random; random.randint(1, 100)
来源：http://dali.aizwys.cn/Article/details/gtdqbhyqgk.html

PHP:  random_int(1, 100);
来源：http://dali.zycfv.cn/Article/details/gtxslfhjjk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gtvxcjssky.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gtxhsmyvpa.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gtrwioamje.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.shzxlz.cn/Article/details/gtjipnfdhh.html

Ruby: rand(1..100)
来源：http://dali.yanxiufei.cn/Article/details/gtwbpbfeow.html

C#:   new Random().Next(1, 101)
来源：http://dali.sxryk.cn/Article/details/gttdfmospu.html

[A11] 条件表达式（三元）
来源：http://dali.yj20258888.top/Article/details/gtcyfxpjbn.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hywenlv.cn/Article/details/gtqgcifhms.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtvasrlhcb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtadgptpty.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gtbrtnyszl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gtduatbthd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.bjfxy.top/Article/details/gthvcancor.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gtvxtbthnm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gtgemmjtot.html

[A12] 字符串插值 / 格式化
来源：http://dali.zycfv.cn/Article/details/gtfxowgrcz.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hysaishi.cn/Article/details/gtutcxuhzl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.nanxinkj.top/Article/details/gthxxwetpq.html

JS:   `Hello, ${name}!`
来源：http://dali.gotoacloud.top/Article/details/gtmtptybac.html

TS:   `Hello, ${name}!`
来源：http://dali.havefunace.top/Article/details/gtsptgczov.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.ppjwa.cn/Article/details/gtiulrrncp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xziqi.cn/Article/details/gtnnlamorg.html

Ruby: "Hello, #{name}!"
来源：http://dali.jqgufenzy.top/Article/details/gtobrqalvr.html

C#:   $"Hello, {name}!"
来源：http://dali.yvedp.cn/Article/details/gtabscvpww.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.dianchejie.cn/Article/details/gtvahtupzr.html

Py:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtfazjrphz.html

PHP:  "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtakdrsatq.html

JS:   "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gthulrdytz.html

TS:   "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtkzjvgaxq.html


<!-- 参考信息 -->