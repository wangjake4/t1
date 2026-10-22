代发 wailian999

[U81] JS：初始化项目
来源：http://dali.yj20258.top/Article/details/gt2wqutghgx.html

npm init -y;  npm i express
来源：http://dali.wangdashe.top/Article/details/gt2heuttudo.html

[U82] JS：package.json 脚本
来源：http://dali.xinyue.icu/Article/details/gt2lywuxrnj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssklacsr.html

[U83] JS：ES Module 导入导出
来源：http://dali.yj202588.top/Article/details/gt2nevocead.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gt2etrkhzoq.html

[U84] JS：CommonJS 写法
来源：http://dali.shangyingyoupin.top/Article/details/gt2mpbvaxsw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zdqjudy.top/Article/details/gt2fohhfmas.html

[U85] JS：可选链
来源：http://dali.sufxvd.cn/Article/details/gt2aekcyeyi.html

a?.b?.c
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqjnnkly.html

[U86] JS：空值合并
来源：http://dali.shzxlz.cn/Article/details/gt2qhaqvhzo.html

a ?? b
来源：http://dali.cheryme.top/Article/details/gt2gwgesmeq.html

[U87] JS：解构默认值
来源：http://dali.yj20258.top/Article/details/gt2dipugknz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hysaishi.cn/Article/details/gt2ytbetewg.html

[U88] JS：对象展开合并
来源：http://dali.ydzc1.top/Article/details/gt2hjgmrhpi.html

{ ...a, ...b }
来源：http://dali.nwbrower.top/Article/details/gt2wqthhovm.html

[U89] JS：数组去重
来源：http://dali.gogol.net.cn/Article/details/gt2feasshdt.html

[...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gt2nqibkxrs.html

[U90] JS：数字数组排序
来源：http://dali.jlsjyb.cn/Article/details/gt2htihdcyc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gt2qjdquqmg.html

[U91] JS：对象键值遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgqqjvtj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhongyouzk.top/Article/details/gt2smgcvrel.html

[U92] JS：深拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2niponnsz.html

structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2mvxoyrge.html

[U93] JS：模板字符串
来源：http://dali.bjfxy.top/Article/details/gt2gfnycjpn.html

`共 ${n} 条`
来源：http://dali.jqgfzy.top/Article/details/gt2kdpubimj.html

[U94] JS：箭头函数
来源：http://dali.ivvv.top/Article/details/gt2nevnwjgp.html

const double = x => x * 2;
来源：http://dali.hywenlv.cn/Article/details/gt2mgvxrpwt.html

[U95] JS：Promise 包装
来源：http://dali.quarkkingdee.top/Article/details/gt2qloerafy.html

new Promise((resolve, reject) => {})
来源：http://dali.yongpay.top/Article/details/gt2wscadhrk.html

[U96] JS：async/await 与异常
来源：http://dali.yangfankeji.com/Article/details/gt2vtieuvng.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjxgyvai.html

[U97] JS：并发请求
来源：http://dali.fzhhl.top/Article/details/gt2unibmjln.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2uszdytxi.html

[U98] JS：fetch 带 JSON
来源：http://dali.jianghu66.top/Article/details/gt2vqdijogx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2plrnjlqv.html

[U99] JS：事件监听
来源：http://dali.hfpthk.cn/Article/details/gt2ucgzyvrp.html

el.addEventListener("click", e => {})
来源：http://dali.wangdashe.top/Article/details/gt2cebttrni.html

[U100] JS：DOM 查询
来源：http://dali.haohaochexian.top/Article/details/gt2zdatzqyg.html

document.querySelector(".item")
来源：http://dali.kuanghao11.cn/Article/details/gt2qvtzsgps.html

[U101] JS：classList 操作
来源：http://dali.tianlin.xyz/Article/details/gt2jybnvlyy.html

el.classList.toggle("active")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqwisclo.html

[U102] JS：本地存储
来源：http://dali.cheryme.top/Article/details/gt2zgqsjpah.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tanke756.top/Article/details/gt2etibbxdk.html

[U103] JS：定时器
来源：http://dali.jianghu66.top/Article/details/gt2cgbfddfw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.mhx1999.top/Article/details/gt2lwibrrbo.html

[U104] JS：防抖
来源：http://dali.shzxlz.cn/Article/details/gt2funmrxdy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2fnkmszzp.html

[U105] JS：节流
来源：http://dali.tian-w.cn/Article/details/gt2mzdcfpfl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xziqi.cn/Article/details/gt2rxtmvohp.html

[U106] JS：日期格式化
来源：http://dali.jinqigufen.top/Article/details/gt2kxhkufiy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cashguo.top/Article/details/gt2igpgtebh.html

[U107] JS：数字千分位
来源：http://dali.guowangkeji.top/Article/details/gt2pliqaxvh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.smart0.xyz/Article/details/gt2pinzalit.html

[U108] JS：随机整数
来源：http://dali.vqdsnc.cn/Article/details/gt2ovbptrch.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.smart0.xyz/Article/details/gt2xbocfsms.html

[U109] JS：数组分组
来源：http://dali.pycfn.com/Article/details/gt2gnxctlit.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gt2lhyrpsdx.html

[U110] JS：数组分块
来源：http://dali.daxiang520.top/Article/details/gt2grkwixeq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cqqwz.cn/Article/details/gt2tazsfkwe.html

[U111] JS：对象转 Map
来源：http://dali.zhixingplan.top/Article/details/gt2ovrewjle.html

new Map(Object.entries(obj))
来源：http://dali.zdqjudy.top/Article/details/gt2yiaikudv.html

[U112] JS：字符串补位
来源：http://dali.ehwqpu.com/Article/details/gt2tdydeixm.html

"7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2inyjarex.html

[U113] JS：正则替换全部
来源：http://dali.zhoulong.xyz/Article/details/gt2lapiotvv.html

s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgstwodf.html

[U114] JS：JSON 深比较
来源：http://dali.mhx1999.top/Article/details/gt2lkiafpcn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gt2djvcfvyj.html

[U115] JS：生成 UUID
来源：http://dali.gzhubu.top/Article/details/gt2upemhnxz.html

crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2xnfhtbvw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hammf.cn/Article/details/gt2filgwkoc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.meibo888.top/Article/details/gt2gmquyyyk.html

[U117] JS：单元测试
来源：http://dali.daxiang520.top/Article/details/gt2kjhmggnw.html

npm i -D vitest;  npx vitest
来源：http://dali.daxiang520.top/Article/details/gt2vejsvqiv.html

[U118] JS：开发服务器
来源：http://dali.aizwys.cn/Article/details/gt2fzsnkjre.html

npm i -D vite;  npx vite
来源：http://dali.hfpthk.cn/Article/details/gt2oyyhrdbl.html

[U119] JS：生产构建
来源：http://dali.zhengqikj.top/Article/details/gt2djriazvi.html

npx vite build
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsadjbcw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sxryk.cn/Article/details/gt2psuwikvm.html

import.meta.env.VITE_API_URL
来源：http://dali.yuanzhike.top/Article/details/gt2hvbqwhai.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2rvitxwpa.html

统计汇总
来源：http://dali.svipenyu.cn/Article/details/gt2ouhfxfjg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkiakgfo.html

按语言统计（条）：
来源：http://dali.andypj.xyz/Article/details/gt2iggjxcaw.html

Python ......... 252
来源：http://dali.jinqigfzy.top/Article/details/gt2dgtwsvyz.html

PHP ............ 252
来源：http://dali.yuxming.cn/Article/details/gt2ghqmvfep.html

JavaScript ..... 252
来源：http://dali.daria6918.cn/Article/details/gt2rnbbncaw.html

TypeScript ..... 212
来源：http://dali.yvedp.cn/Article/details/gt2nkiiizmh.html

Java ........... 212
来源：http://dali.pycfn.com/Article/details/gt2ndblmfgw.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gt2unwptbec.html

Ruby ........... 212
来源：http://dali.jinqigfzy.top/Article/details/gt2vyqphgbx.html

C# ............. 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adynahmw.html

C .............. 30
来源：http://dali.snrcjt.cn/Article/details/gt2wayfzwwl.html

C++ ............ 30
来源：http://dali.yuanzhike.top/Article/details/gt2eaoiwxev.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gt2wpubecnx.html

Bash ........... 80
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzkgkeyk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcsofhl.html

Swift .......... 15
来源：http://dali.xziqi.cn/Article/details/gt2rdccxekj.html

Lua ............ 10
来源：http://dali.gotoacloud.top/Article/details/gt2hvcserlv.html

Perl ........... 10
来源：http://dali.jinqigfzy.top/Article/details/gt2pjdfqgod.html

Scala .......... 10
来源：http://dali.cdnleiting.top/Article/details/gt2toygvyko.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2eerzyxka.html

合计 ........... 2106 条
来源：http://dali.ivvv.top/Article/details/gt2qkfelofl.html

按章节统计：
来源：http://dali.yj202588.top/Article/details/gt2ggdhgtjq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gt2fsgjmmjw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2wwywmjbn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gt2uoauvqwy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gt2zxwvymcx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daria6918.cn/Article/details/gt2bbwdwcaq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daria6918.cn/Article/details/gt2lkszhljr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gt2irepvsjn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daria6918.cn/Article/details/gt2vodraaez.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gt2edoznfpf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gt2yblwsimk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gt2orgrsylx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gt2pxnwsylf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gt2iltyoblg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ueipznub.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vsrijugn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkwwqqwj.html

Q SQL 专题                              90
来源：http://dali.meibo888.top/Article/details/gt2iroteser.html

R Bash 专题                             80
来源：http://dali.tian-w.cn/Article/details/gt2jzorwawp.html

S C / C++ 专题                          60
来源：http://dali.guowangkeji.top/Article/details/gt2yyzrivbk.html

T 其他语言补充                          60
来源：http://dali.yonumen.top/Article/details/gt2ollzzlld.html

U 高频实用片段                         120
来源：http://dali.mhx1999.top/Article/details/gt2mezzgbhz.html

------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2selessad.html

合计                                  2106 条
来源：http://dali.sxryk.cn/Article/details/gt2nknplwzi.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2jgunekid.html

使用提醒
来源：http://dali.zhoulong.xyz/Article/details/gt2trbgoxho.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2apqgyyiz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.iojbl.cn/Article/details/gt2tfgsbywj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aibaodan.cn/Article/details/gt2cxsbtfav.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuetiantiany.cn/Article/details/gt2entyxxqu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltfrrqvm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tanke756.top/Article/details/gt2rzhjtsix.html

—— 文件结束 ——
来源：http://dali.0kj1m.cn/Article/details/gt2glmcwgbz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ydwpsleq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.dianchejie.cn/Article/details/gt2paqmgsxn.html

Common Programming Examples Cheat Book
来源：http://dali.ybcxt.top/Article/details/gt2xxjqeaar.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxnwqthj.html

【收录内容】
来源：http://dali.hammf.cn/Article/details/gt2abtodokj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ivvv.top/Article/details/gt2evsxdzqk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhongyouzk.top/Article/details/gt2kvwtswny.html

SQL · Bash · C · C++
来源：http://dali.svipenyu.cn/Article/details/gt2fehfogey.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jyoumei.cn/Article/details/gt2ytrogxwm.html

【使用说明】
来源：http://dali.mhx1999.top/Article/details/gt2eyfkphzs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cucudq.cn/Article/details/gt2axuqfapy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cdnleiting.top/Article/details/gt2gjiaawzm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ydzc1.top/Article/details/gt2fongvsee.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sufxvd.cn/Article/details/gt2wtsksciz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.wangdashe.top/Article/details/gt2ieihnobo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hammf.cn/Article/details/gt2zdftalan.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cashguo.top/Article/details/gt2zbhvorid.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xinyue.icu/Article/details/gt2aalbaqnv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.havefunace.top/Article/details/gt2dwhmcvug.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jyoumei.cn/Article/details/gt2nmoufnbh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.meibo888.top/Article/details/gt2glvznrox.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sufxvd.cn/Article/details/gt2kmapmbvt.html

【文件统计】
来源：http://dali.c1oappe.top/Article/details/gt2gdcchluf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinqigufen.top/Article/details/gt2auxqpyoj.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2bzruyaom.html

目  录
来源：http://dali.yongpay.top/Article/details/gt2osiqzgvw.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gt2vatykhzz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gt2zipzujur.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gt2zcfiyrgc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gt2ilrcbqby.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jiagoushi.top/Article/details/gt2dhahxfjc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2bkfxcbtk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gt2ofrebhtn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gt2hhfvcogr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2tchhgbka.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gt2ykdfejwo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tianlin.xyz/Article/details/gt2paeuwlvj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gt2ubhmjoji.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gt2yuwryikd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2jeaxsqjl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.snrcjt.cn/Article/details/gt2tygwhvkw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ybcxt.top/Article/details/gt2ortpirri.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gt2smrmeenk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hysaishi.cn/Article/details/gt2heltvwhb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2jkcafhbd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.dianchejie.cn/Article/details/gt2bqdppcze.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gt2qwmndmfu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gt2sdomenul.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ctnzzxcr.html

A. 基础语法与类型
来源：http://dali.jiagoushi.top/Article/details/gt2cioeyonz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2umhcdgib.html

[A01] Hello World
来源：http://dali.316326.xyz/Article/details/gt2fapyikpl.html

Py:   print("Hello, World!")
来源：http://dali.cheryme.top/Article/details/gt2xyqksxqk.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxinkj.top/Article/details/gt2bilixcbm.html

JS:   console.log("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gt2wdsrslde.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shuidangran.top/Article/details/gt2buskvqdj.html

Java: System.out.println("Hello, World!");
来源：http://dali.shuidangran.top/Article/details/gt2wolapxug.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj202588.top/Article/details/gt2xcakaajw.html

Ruby: puts "Hello, World!"
来源：http://dali.aizwys.cn/Article/details/gt2qjwxvhvc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubboyozl.html

[A02] 变量声明与赋值
来源：http://dali.hnqzz.top/Article/details/gt2llsyuenj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hammf.cn/Article/details/gt2uauyxmfw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gt2rhpxynea.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hfpthk.cn/Article/details/gt2slaxveti.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vluptars.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gt2ctlcggue.html

Go:   name := "Alex"; age := 20
来源：http://dali.cdnleiting.top/Article/details/gt2cnyxobxh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.quarkkingdee.top/Article/details/gt2asghgbjk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jqgfzy.top/Article/details/gt2gctgelox.html

[A03] 常量定义
来源：http://dali.meibo888.top/Article/details/gt2taedjghs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.dianchejie.cn/Article/details/gt2cymmsbmw.html

PHP:  const PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbazquog.html

JS:   const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2lyhfklcp.html

TS:   const PI: number = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2vqcyoeij.html

Java: static final double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbmzdhzn.html

Go:   const PI = 3.14159
来源：http://dali.meibo888.top/Article/details/gt2asfxwfdo.html

Ruby: PI = 3.14159
来源：http://dali.zhixingplan.top/Article/details/gt2wmdctpui.html

C#:   const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2xmthddsi.html

[A04] 判断变量类型
来源：http://dali.jqgfzy.top/Article/details/gt2iztnuvns.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uytkjnmk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nwbrower.top/Article/details/gt2aaccvxdy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gt2zzncowif.html

TS:   typeof x; x instanceof Date
来源：http://dali.svipenyu.cn/Article/details/gt2zwqdtuzk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jlsjyb.cn/Article/details/gt2lptpcbqi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jyoumei.cn/Article/details/gt2xgtbpdan.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.quarkkingdee.top/Article/details/gt2kroiqehr.html

C#:   x.GetType().Name; x is int
来源：http://dali.sufxvd.cn/Article/details/gt2fgpjefdp.html

[A05] 整数除法与取模
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyluusdw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhengqikj.top/Article/details/gt2zltejyfn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gt2donawhnh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gt2kgshmlmk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gt2newrugoo.html

Java: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znxcgrre.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ethcizmx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxgnrgfn.html

C#:   7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gt2gbuqrgrj.html

[A06] 字符串转数字
来源：http://dali.zycfv.cn/Article/details/gt2fcxodfle.html

Py:   int("42"); float("3.14")
来源：http://dali.shuidangran.top/Article/details/gt2ontxqgno.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yongpay.top/Article/details/gt2ocmpjzeo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yueranfly.top/Article/details/gt2yivfauem.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sufxvd.cn/Article/details/gt2vvfibdhz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jianghu66.top/Article/details/gt2fwfulerb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuxming.cn/Article/details/gt2uvkqrwlu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.pengpengdd.cyou/Article/details/gt2wsfrqnhf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jlsjyb.cn/Article/details/gt2jsbvgmzv.html

[A07] 数字转字符串
来源：http://dali.zycfv.cn/Article/details/gt2fcmzmdje.html

Py:   str(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uowxdoyy.html

PHP:  (string) 42; strval(42)
来源：http://dali.ehwqpu.com/Article/details/gt2udosmufl.html

JS:   String(42); (42).toString()
来源：http://dali.guannengcc.top/Article/details/gt2fvkdhsyk.html

TS:   String(42)
来源：http://dali.yj202588.top/Article/details/gt2jznlidoh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgeopmrg.html

Go:   strconv.Itoa(42)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbypumgl.html

Ruby: 42.to_s
来源：http://dali.ydzc1.top/Article/details/gt2pepfekko.html

C#:   42.ToString()
来源：http://dali.tanke756.top/Article/details/gt2ymbrbhqa.html

[A08] 取整与四舍五入
来源：http://dali.kuanghao11.cn/Article/details/gt2qksjjsyj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gt2vfinlhds.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cqqwz.cn/Article/details/gt2ocpbmsmx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gt2qowbqhal.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shuidangran.top/Article/details/gt2dugxbflp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gt2ofmtapqz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gt2zmjewamc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrybgqef.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gt2vpbdfedj.html

[A09] 绝对值与最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2eivegoak.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2dqsnntyg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj202588.top/Article/details/gt2myqwwabn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2bjohdyzx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.c1oappe.top/Article/details/gt2jphoafpy.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2tgqlbaou.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jianghu66.top/Article/details/gt2gossjqgt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jiagoushi.top/Article/details/gt2srtbksyz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2joxinwjv.html

[A10] 生成随机数
来源：http://dali.yuanzhike.top/Article/details/gt2erpafnca.html

Py:   import random; random.randint(1, 100)
来源：http://dali.fzhhl.top/Article/details/gt2qsklzezv.html

PHP:  random_int(1, 100);
来源：http://dali.ydzc1.top/Article/details/gt2qbdhqxmo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkwiileb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sxryk.cn/Article/details/gt2jvyxxlmh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.daxiang520.top/Article/details/gt2fvtrlxaa.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.mhx1999.top/Article/details/gt2wmrvudlg.html

Ruby: rand(1..100)
来源：http://dali.havefunace.top/Article/details/gt2bzgpbxya.html

C#:   new Random().Next(1, 101)
来源：http://dali.yanxiufei.cn/Article/details/gt2ukwqkstq.html

[A11] 条件表达式（三元）
来源：http://dali.fengsongda.top/Article/details/gt2edznzowj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jqgufenzy.top/Article/details/gt2rvphwoea.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gt2ustdjwpp.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gt2lpgumswi.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gt2eaqgafku.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gt2nscnzmym.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gilevdya.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gt2rsukuuyr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gt2debjemwp.html

[A12] 字符串插值 / 格式化
来源：http://dali.hnqzz.top/Article/details/gt2rrsoiphl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jqgfzy.top/Article/details/gt2cpmmbkds.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yj202588.top/Article/details/gt2owlzeyqd.html

JS:   `Hello, ${name}!`
来源：http://dali.fzhhl.top/Article/details/gt2ianjfohs.html

TS:   `Hello, ${name}!`
来源：http://dali.xuanzx.com/Article/details/gt2vztbvgid.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhengqikj.top/Article/details/gt2xgdoveyh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.9152youxi.cn/Article/details/gt2dwhvixxz.html

Ruby: "Hello, #{name}!"
来源：http://dali.sufxvd.cn/Article/details/gt2hcpbjdzm.html

C#:   $"Hello, {name}!"
来源：http://dali.cheryme.top/Article/details/gt2nqplfjvm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.tianlin.xyz/Article/details/gt2tlzeaski.html

Py:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gt2hqosmaca.html

PHP:  "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gt2qcauhlak.html

JS:   "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gt2sduworta.html

TS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2ucvlvawj.html


<!-- 参考信息 -->