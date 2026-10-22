代发 wailian999

[U81] JS：初始化项目
来源：http://dali.jqgfzy.top/Article/details/gtgsmqtobs.html

npm init -y;  npm i express
来源：http://dali.gaohongyu789.top/Article/details/gtesoxatvh.html

[U82] JS：package.json 脚本
来源：http://dali.zycfv.cn/Article/details/gtlwshmpus.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.vqdsnc.cn/Article/details/gtwbkrnlkb.html

[U83] JS：ES Module 导入导出
来源：http://dali.wangdashe.top/Article/details/gtmxwcqcen.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtvnagefpx.html

[U84] JS：CommonJS 写法
来源：http://dali.shuidangran.top/Article/details/gtvgeptwqi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.316326.xyz/Article/details/gtqrnzyhbr.html

[U85] JS：可选链
来源：http://dali.haohaochexian.top/Article/details/gtmvrufywf.html

a?.b?.c
来源：http://dali.tianlin.xyz/Article/details/gtmvijibio.html

[U86] JS：空值合并
来源：http://dali.hysaishi.cn/Article/details/gthgawlnnl.html

a ?? b
来源：http://dali.xylfe.cn/Article/details/gtlyjvmroy.html

[U87] JS：解构默认值
来源：http://dali.zhixingplan.top/Article/details/gtjobsupgq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tanke756.top/Article/details/gtfgaenmfy.html

[U88] JS：对象展开合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpghehfmc.html

{ ...a, ...b }
来源：http://dali.sweek.top/Article/details/gtieyvdmmn.html

[U89] JS：数组去重
来源：http://dali.xuanzx.com/Article/details/gthwzvvfpy.html

[...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtqzndlsrw.html

[U90] JS：数字数组排序
来源：http://dali.daxiang520.top/Article/details/gtwmfgngwo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpopllaia.html

[U91] JS：对象键值遍历
来源：http://dali.vqdsnc.cn/Article/details/gtnmbhgnjl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cucudq.cn/Article/details/gtqhktsnkk.html

[U92] JS：深拷贝
来源：http://dali.yj20258888.top/Article/details/gtevskpkbd.html

structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtmgoltfmy.html

[U93] JS：模板字符串
来源：http://dali.chenzaomai.com/Article/details/gtozfsxcgx.html

`共 ${n} 条`
来源：http://dali.yonumen.top/Article/details/gthbxfdhtb.html

[U94] JS：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gtsvkdjrwc.html

const double = x => x * 2;
来源：http://dali.yvedp.cn/Article/details/gtafofhbvm.html

[U95] JS：Promise 包装
来源：http://dali.jinqigfzy.top/Article/details/gtsihpmytt.html

new Promise((resolve, reject) => {})
来源：http://dali.yonumen.top/Article/details/gtowerxdmb.html

[U96] JS：async/await 与异常
来源：http://dali.jyoumei.cn/Article/details/gtlbobvhof.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtxwhufwsv.html

[U97] JS：并发请求
来源：http://dali.kuanghao11.cn/Article/details/gtrkrzwvga.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gttbcwuwcm.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwftiehii.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.9152youxi.cn/Article/details/gtxmnbhjqa.html

[U99] JS：事件监听
来源：http://dali.zdqjudy.top/Article/details/gtjnnsqxib.html

el.addEventListener("click", e => {})
来源：http://dali.jianghu66.top/Article/details/gtesnrohba.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gthfqahnxq.html

document.querySelector(".item")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwmkozbl.html

[U101] JS：classList 操作
来源：http://dali.gogol.net.cn/Article/details/gtaogkoyjl.html

el.classList.toggle("active")
来源：http://dali.9152youxi.cn/Article/details/gteznqmjuc.html

[U102] JS：本地存储
来源：http://dali.xuanzx.com/Article/details/gtwtpeyzhe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gaohongyu789.top/Article/details/gteuszbaha.html

[U103] JS：定时器
来源：http://dali.andypj.xyz/Article/details/gtndsopsvx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.snrcjt.cn/Article/details/gteogqwrcf.html

[U104] JS：防抖
来源：http://dali.jiagoushi.top/Article/details/gtldtbqrtl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtaqbnmifu.html

[U105] JS：节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gthoqxihgu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gtkunxjtqv.html

[U106] JS：日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtimkssjuv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hammf.cn/Article/details/gtzfavmchq.html

[U107] JS：数字千分位
来源：http://dali.tian-w.cn/Article/details/gtorxgwavo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtwvgzkdff.html

[U108] JS：随机整数
来源：http://dali.iojbl.cn/Article/details/gtoxxgfeds.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xziqi.cn/Article/details/gtqstmqxqs.html

[U109] JS：数组分组
来源：http://dali.meibo888.top/Article/details/gtfvenawtv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gtqxmurpfx.html

[U110] JS：数组分块
来源：http://dali.zhongyouzk.top/Article/details/gtqyiuudcs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuxming.cn/Article/details/gtgfsjjmkz.html

[U111] JS：对象转 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhsehgwx.html

new Map(Object.entries(obj))
来源：http://dali.sysykeji.top/Article/details/gtyijmjnhq.html

[U112] JS：字符串补位
来源：http://dali.yj20258.top/Article/details/gtonmiswpm.html

"7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtfzldgulf.html

[U113] JS：正则替换全部
来源：http://dali.hywenlv.cn/Article/details/gtenidbooz.html

s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtikzrmecp.html

[U114] JS：JSON 深比较
来源：http://dali.zhoulong.xyz/Article/details/gtwqbmqfqb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtqmhacduq.html

[U115] JS：生成 UUID
来源：http://dali.aizwys.cn/Article/details/gtzraaquvs.html

crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtfjtqkzem.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsylvtrp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinqigufen.top/Article/details/gtuybvbdzo.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbkfwskc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqoqijtr.html

[U118] JS：开发服务器
来源：http://dali.yj202588.top/Article/details/gtslrllztf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gtbwesbazv.html

[U119] JS：生产构建
来源：http://dali.guowangkeji.top/Article/details/gtruihatno.html

npx vite build
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvsafrxo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jiagoushi.top/Article/details/gtzvibbwtq.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigfzy.top/Article/details/gtpmcvrrcj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtocdfqrwm.html

统计汇总
来源：http://dali.yangfankeji.com/Article/details/gtlqaxllcm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjgoecsfm.html

按语言统计（条）：
来源：http://dali.zhoulong.xyz/Article/details/gtlyzphxdi.html

Python ......... 252
来源：http://dali.mhx1999.top/Article/details/gtfszcxrjh.html

PHP ............ 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsozdccg.html

JavaScript ..... 252
来源：http://dali.hysaishi.cn/Article/details/gtfmjzucgt.html

TypeScript ..... 212
来源：http://dali.gaohongyu789.top/Article/details/gtyrfknybn.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gtkpcwamnd.html

Go ............. 212
来源：http://dali.gaohongyu789.top/Article/details/gtewvhfqwg.html

Ruby ........... 212
来源：http://dali.fzhhl.top/Article/details/gtwlrrbyfu.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gtiprqbuky.html

C .............. 30
来源：http://dali.316326.xyz/Article/details/gtskzstsmu.html

C++ ............ 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyykfvvo.html

SQL ............ 90
来源：http://dali.xuanzx.com/Article/details/gtktfkswes.html

Bash ........... 80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzfoeliw.html

Kotlin ......... 15
来源：http://dali.ybcxt.top/Article/details/gtgayizgli.html

Swift .......... 15
来源：http://dali.cucudq.cn/Article/details/gtoxufcjbs.html

Lua ............ 10
来源：http://dali.zhiwuduotai.top/Article/details/gtwjgupskj.html

Perl ........... 10
来源：http://dali.jinqigufen.top/Article/details/gtqnointkq.html

Scala .......... 10
来源：http://dali.guannengcc.top/Article/details/gtyhizocjk.html

------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjnjltht.html

合计 ........... 2106 条
来源：http://dali.cdnleiting.top/Article/details/gtlbwaxckj.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtfujqwuhc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gtrrctvnta.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gtksaptrgm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gttskihpil.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gtfidpfelb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.bjfxy.top/Article/details/gthcpwkeld.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gtdsgmbemg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtjjagwavf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangshuangyany.cn/Article/details/gtbacozmkb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtqikhgjgf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.smart0.xyz/Article/details/gtymagyodd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtadmucloj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtsmahctew.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtddaftvsm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ybcxt.top/Article/details/gtvbpohwlr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdiyjrdyz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtolyzbwiy.html

Q SQL 专题                              90
来源：http://dali.yuanzhike.top/Article/details/gtfunyoiuf.html

R Bash 专题                             80
来源：http://dali.yongpay.top/Article/details/gtjrwudzdn.html

S C / C++ 专题                          60
来源：http://dali.yonumen.top/Article/details/gtgpvidprq.html

T 其他语言补充                          60
来源：http://dali.zhengqikj.top/Article/details/gtrqwfjsna.html

U 高频实用片段                         120
来源：http://dali.mhx1999.top/Article/details/gtoicfzacj.html

------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtcppzxtfo.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gtqecnufpx.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtokrgsvdq.html

使用提醒
来源：http://dali.ppjwa.cn/Article/details/gtqaaiiidr.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtiamedtgq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shuidangran.top/Article/details/gttqwiowkx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.havefunace.top/Article/details/gtomfoaboq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenlongwang.top/Article/details/gtilmhcpuu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hongshengwenyu.top/Article/details/gtnpmrixlq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cheryme.top/Article/details/gtasxhldkm.html

—— 文件结束 ——
来源：http://dali.daxiang520.top/Article/details/gtxisxmqfs.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdlhtszrm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.iojbl.cn/Article/details/gtmijipcoz.html

Common Programming Examples Cheat Book
来源：http://dali.zhiwuduotai.top/Article/details/gtwmofptko.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdzlafdsx.html

【收录内容】
来源：http://dali.zhaomingkeji.xyz/Article/details/gttspsbnvi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigufen.top/Article/details/gteefkiydm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenjidiqi.icu/Article/details/gtbooarfgs.html

SQL · Bash · C · C++
来源：http://dali.hnxiangtu.top/Article/details/gtvwxmusdl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.quarkkingdee.top/Article/details/gtjanostky.html

【使用说明】
来源：http://dali.nanxuanxn.top/Article/details/gtoeonwdrj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yvedp.cn/Article/details/gtxcvhanog.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangtech.top/Article/details/gtzloxhmdn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zdqjudy.top/Article/details/gtupxpvlxq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxinkj.top/Article/details/gtbrczjlse.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtunvvei.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tanke756.top/Article/details/gthkyznzyj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenlongwang.top/Article/details/gtrxatofwr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cqqwz.cn/Article/details/gtlrpvgcjz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.kuanghao11.cn/Article/details/gtcuggcpro.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xylfe.cn/Article/details/gtgsmjpluz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zdqjudy.top/Article/details/gtwxlhnyll.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jianghu66.top/Article/details/gtrpvuxihs.html

【文件统计】
来源：http://dali.cqqwz.cn/Article/details/gtskguywqt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gaohongyu789.top/Article/details/gtrlmirlna.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtjgzkezvd.html

目  录
来源：http://dali.fzhhl.top/Article/details/gtcmxvajbf.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtvmcqwesw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.haohaochexian.top/Article/details/gtmyznppwz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gtutbmlpzz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirqlisgx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomrklbsg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jqgfzy.top/Article/details/gthiycjlsx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nwbrower.top/Article/details/gthhhhuyac.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gthfpyfifg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gtgzukfhpd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtwpfrfnfa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258888.top/Article/details/gtqdfuduxz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtnagsnuhu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtszfmcdtl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtvobdrkxw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptsrqlur.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gotoacloud.top/Article/details/gtmqufjvcg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtcjqgirmz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtzurezgjx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtewoapbcg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtwbqehsnh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gtxxrumzcw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtrrjpcjqh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfutnvvmn.html

A. 基础语法与类型
来源：http://dali.jqgfzy.top/Article/details/gtptvxrkux.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtzzyxccpz.html

[A01] Hello World
来源：http://dali.tanke756.top/Article/details/gtkqrnvngv.html

Py:   print("Hello, World!")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfdnxifi.html

PHP:  echo "Hello, World!";
来源：http://dali.hongshengwenyu.top/Article/details/gtphtoscaz.html

JS:   console.log("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtdfllezqm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.dianchejie.cn/Article/details/gtfrktnjzg.html

Java: System.out.println("Hello, World!");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvrvlbof.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gtgqgwjeky.html

Ruby: puts "Hello, World!"
来源：http://dali.yvedp.cn/Article/details/gtqgywrtbb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.9152youxi.cn/Article/details/gtegoxrvdn.html

[A02] 变量声明与赋值
来源：http://dali.shuidangran.top/Article/details/gtiqrggbfw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuetiantiany.cn/Article/details/gtrverqpce.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdanodui.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtjatkzrvb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gzhubu.top/Article/details/gtfnewqtom.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyxmooag.html

Go:   name := "Alex"; age := 20
来源：http://dali.kuanghao11.cn/Article/details/gtlbcteorg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.fengsongda.top/Article/details/gtniidibus.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtakuyuqrr.html

[A03] 常量定义
来源：http://dali.gotoacloud.top/Article/details/gtfulmscrt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shangyingyoupin.top/Article/details/gtljwfkkli.html

PHP:  const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gteuygihqa.html

JS:   const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtxfuxryca.html

TS:   const PI: number = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtfveeggdd.html

Java: static final double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtevahyibc.html

Go:   const PI = 3.14159
来源：http://dali.pycfn.com/Article/details/gtlinkegbu.html

Ruby: PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gtlnpgubos.html

C#:   const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtgogwnozv.html

[A04] 判断变量类型
来源：http://dali.bjfxy.top/Article/details/gthcnmetlk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.sysykeji.top/Article/details/gtgrtaddlk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hnxiangtu.top/Article/details/gtcpxguvzc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yueranfly.top/Article/details/gtjzwomyfh.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxinkj.top/Article/details/gtodjidedw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.quarkkingdee.top/Article/details/gtalunimdx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yueranfly.top/Article/details/gttjpiuxwh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gtedjhuske.html

C#:   x.GetType().Name; x is int
来源：http://dali.jianghu66.top/Article/details/gtmttikjff.html

[A05] 整数除法与取模
来源：http://dali.yongpay.top/Article/details/gtyjnztnhd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjirbcyh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtgvdenyza.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtdjltedms.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqtsltma.html

Java: 7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtqktthmbd.html

Go:   7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtjbxdsjkj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtrzettqoa.html

C#:   7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtdiyqxzoi.html

[A06] 字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gtdrdijaet.html

Py:   int("42"); float("3.14")
来源：http://dali.chenzaomai.com/Article/details/gtedirwylh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinqigufen.top/Article/details/gtzohaycib.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtpzxnrcpc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xziqi.cn/Article/details/gtaujgcpnr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.iojbl.cn/Article/details/gthcxkxcxh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.kuanghao11.cn/Article/details/gtzkhjtaoc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gzhubu.top/Article/details/gtrmvsujke.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jlsjyb.cn/Article/details/gtwuwuvctu.html

[A07] 数字转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtmcaybxsy.html

Py:   str(42)
来源：http://dali.yuxming.cn/Article/details/gtkulaleij.html

PHP:  (string) 42; strval(42)
来源：http://dali.fengsongda.top/Article/details/gtwbmfjbkw.html

JS:   String(42); (42).toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtcynfglyt.html

TS:   String(42)
来源：http://dali.daxiang520.top/Article/details/gtvdbjdkyi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yj20258888.top/Article/details/gtpwyzbvub.html

Go:   strconv.Itoa(42)
来源：http://dali.jyoumei.cn/Article/details/gtinymawkv.html

Ruby: 42.to_s
来源：http://dali.hammf.cn/Article/details/gtabazwndb.html

C#:   42.ToString()
来源：http://dali.gzhubu.top/Article/details/gtsooarkmx.html

[A08] 取整与四舍五入
来源：http://dali.daria6918.cn/Article/details/gtgdqmoxsl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gtpbdcurpz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.fengsongda.top/Article/details/gtxxzqhtzw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gtarptznlt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shzxlz.cn/Article/details/gthdtvbjup.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gthagocham.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gtckjtocob.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.pengpengdd.cyou/Article/details/gtlvxyzkol.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtfnthccpz.html

[A09] 绝对值与最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtltyszhbk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtiomdwbhl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xinyue.icu/Article/details/gttgwvcopx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkueuius.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.316326.xyz/Article/details/gtqfifotop.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtwnbnchfy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.9152youxi.cn/Article/details/gtcaqkhgbj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.fzhhl.top/Article/details/gtqiqxwvxz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.tanke756.top/Article/details/gtfexrtizk.html

[A10] 生成随机数
来源：http://dali.ybcxt.top/Article/details/gtlowneenh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.wangshuangyany.cn/Article/details/gtsyabemsy.html

PHP:  random_int(1, 100);
来源：http://dali.gzhubu.top/Article/details/gtrernpgcb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cqqwz.cn/Article/details/gtkbahcswl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jqgfzy.top/Article/details/gtmcjxlkli.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpfagrhp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqiowhzjd.html

Ruby: rand(1..100)
来源：http://dali.ehwqpu.com/Article/details/gtmylheyqz.html

C#:   new Random().Next(1, 101)
来源：http://dali.vqdsnc.cn/Article/details/gtpnphmvmp.html

[A11] 条件表达式（三元）
来源：http://dali.jinqigufen.top/Article/details/gtpspsffaj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yuanzhike.top/Article/details/gtwlgqzvjv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtiavydmmw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gtkhsoecta.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtqtgtokfh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtapypmsnj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.andypj.xyz/Article/details/gtipseuvrd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gtzejajsgc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtjztylsnv.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhengqikj.top/Article/details/gtgfcvloip.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.iojbl.cn/Article/details/gtutrezhqp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.dianchejie.cn/Article/details/gtiufczads.html

JS:   `Hello, ${name}!`
来源：http://dali.nwbrower.top/Article/details/gtjjxpikfh.html

TS:   `Hello, ${name}!`
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsyzexof.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.iojbl.cn/Article/details/gtzqjfizrc.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jqgfzy.top/Article/details/gtwxwiwlkz.html

Ruby: "Hello, #{name}!"
来源：http://dali.xuetiantiany.cn/Article/details/gtcsrtswlj.html

C#:   $"Hello, {name}!"
来源：http://dali.316326.xyz/Article/details/gtnnrzfjnk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xuetiantiany.cn/Article/details/gtbdzzrphe.html

Py:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtgpvbemoc.html

PHP:  "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtihmcfclh.html

JS:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtqtncqpfp.html

TS:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtjembwbbq.html


<!-- 参考信息 -->