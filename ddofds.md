代发 wailian999

[U79] PHP：静态分析
来源：http://dali.shuidangran.top/Article/details/gtdgbqlihd.html

composer require --dev phpstan/phpstan
来源：http://dali.tanke756.top/Article/details/gtkkzdufdg.html

[U80] PHP：代码规范修复
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjiyohps.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.snrcjt.cn/Article/details/gtjjdjucev.html

[U81] JS：初始化项目
来源：http://dali.ybcxt.top/Article/details/gtihtzbeii.html

npm init -y;  npm i express
来源：http://dali.cdnleiting.top/Article/details/gttufdxjae.html

[U82] JS：package.json 脚本
来源：http://dali.svipenyu.cn/Article/details/gtubceueto.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.havefunace.top/Article/details/gtekmdhzvw.html

[U83] JS：ES Module 导入导出
来源：http://dali.tian-w.cn/Article/details/gtirxaults.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gttshsitmn.html

[U84] JS：CommonJS 写法
来源：http://dali.shzxlz.cn/Article/details/gteyfmwyvl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yuxming.cn/Article/details/gtcdjbkeew.html

[U85] JS：可选链
来源：http://dali.smart0.xyz/Article/details/gtqpfqzzyj.html

a?.b?.c
来源：http://dali.sysykeji.top/Article/details/gtjmcylwtg.html

[U86] JS：空值合并
来源：http://dali.nanxuanxn.top/Article/details/gtyqraermz.html

a ?? b
来源：http://dali.ivvv.top/Article/details/gthzgxopbj.html

[U87] JS：解构默认值
来源：http://dali.jianghu66.top/Article/details/gthpujmmbb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.9152youxi.cn/Article/details/gtivcrjezl.html

[U88] JS：对象展开合并
来源：http://dali.xylfe.cn/Article/details/gtzurnhgln.html

{ ...a, ...b }
来源：http://dali.jiagoushi.top/Article/details/gtmsybnplh.html

[U89] JS：数组去重
来源：http://dali.nanxuanxn.top/Article/details/gtrntdkgnw.html

[...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtbgynnarh.html

[U90] JS：数字数组排序
来源：http://dali.fzhhl.top/Article/details/gtiblsfapk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtefohkuaf.html

[U91] JS：对象键值遍历
来源：http://dali.chenlongwang.top/Article/details/gtqcmhjriz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hysaishi.cn/Article/details/gtyrusngyj.html

[U92] JS：深拷贝
来源：http://dali.xuanzx.com/Article/details/gtsopdynwt.html

structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtliqcypch.html

[U93] JS：模板字符串
来源：http://dali.jlsjyb.cn/Article/details/gtbpxtedxi.html

`共 ${n} 条`
来源：http://dali.havefunace.top/Article/details/gtwrwvfzbw.html

[U94] JS：箭头函数
来源：http://dali.hammf.cn/Article/details/gteqbusozb.html

const double = x => x * 2;
来源：http://dali.jinqigufen.top/Article/details/gtjqnauhqk.html

[U95] JS：Promise 包装
来源：http://dali.cucudq.cn/Article/details/gttjrkhatp.html

new Promise((resolve, reject) => {})
来源：http://dali.tian-w.cn/Article/details/gtsivxgute.html

[U96] JS：async/await 与异常
来源：http://dali.dianchejie.cn/Article/details/gtyuzajhjf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtdwxhfkvn.html

[U97] JS：并发请求
来源：http://dali.dashuyun.cn/Article/details/gtjfjmedct.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtxmycpdrf.html

[U98] JS：fetch 带 JSON
来源：http://dali.tian-w.cn/Article/details/gtmdpjopzo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinqigufen.top/Article/details/gthqeixwne.html

[U99] JS：事件监听
来源：http://dali.gogol.net.cn/Article/details/gtmtqdliio.html

el.addEventListener("click", e => {})
来源：http://dali.nanxuanxn.top/Article/details/gtquouqlpr.html

[U100] JS：DOM 查询
来源：http://dali.jinqigufen.top/Article/details/gtzrcqbeks.html

document.querySelector(".item")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvltfojh.html

[U101] JS：classList 操作
来源：http://dali.gogol.net.cn/Article/details/gtkmeyjnzd.html

el.classList.toggle("active")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdobjmfe.html

[U102] JS：本地存储
来源：http://dali.iojbl.cn/Article/details/gtqkykoujg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinqigfzy.top/Article/details/gtqctnkybn.html

[U103] JS：定时器
来源：http://dali.cashguo.top/Article/details/gtvyaqkhwv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sysykeji.top/Article/details/gtnoxmipqm.html

[U104] JS：防抖
来源：http://dali.shangyingyoupin.top/Article/details/gtjqjbujvg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtdqxrrpnd.html

[U105] JS：节流
来源：http://dali.gotoacloud.top/Article/details/gtaepftdcu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shzxlz.cn/Article/details/gtmpqakwpi.html

[U106] JS：日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtvtcdidic.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.vqdsnc.cn/Article/details/gtoosbdfip.html

[U107] JS：数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtnhihuegz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthufetwit.html

[U108] JS：随机整数
来源：http://dali.yuxming.cn/Article/details/gtmzlbogau.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhixingplan.top/Article/details/gtdrwdtylw.html

[U109] JS：数组分组
来源：http://dali.dianchejie.cn/Article/details/gtmyrzbziw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtvkcybibl.html

[U110] JS：数组分块
来源：http://dali.sysykeji.top/Article/details/gtcmtupcqi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.guowangkeji.top/Article/details/gtjhuafigq.html

[U111] JS：对象转 Map
来源：http://dali.xinyue.icu/Article/details/gtcwkggfmi.html

new Map(Object.entries(obj))
来源：http://dali.jyoumei.cn/Article/details/gtcckhpdws.html

[U112] JS：字符串补位
来源：http://dali.wangshuangyany.cn/Article/details/gtulbrnjnq.html

"7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtinuihfxh.html

[U113] JS：正则替换全部
来源：http://dali.dashuyun.cn/Article/details/gtjautypja.html

s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtwalrllwq.html

[U114] JS：JSON 深比较
来源：http://dali.gotoacloud.top/Article/details/gtldkpajhx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtunsewumt.html

[U115] JS：生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtgjvbpekb.html

crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtboemsjpg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ybcxt.top/Article/details/gthkuxsapr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.9152youxi.cn/Article/details/gttgevftba.html

[U117] JS：单元测试
来源：http://dali.redwolf501.top/Article/details/gtazwhtdix.html

npm i -D vitest;  npx vitest
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzyekqyk.html

[U118] JS：开发服务器
来源：http://dali.hywenlv.cn/Article/details/gtmdxpehxr.html

npm i -D vite;  npx vite
来源：http://dali.aibaodan.cn/Article/details/gteehatydg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gtmsgnvknd.html

npx vite build
来源：http://dali.hnqzz.top/Article/details/gtyyketreq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrmpjczx.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gtazfzmkea.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvnnprzva.html

统计汇总
来源：http://dali.shzxlz.cn/Article/details/gtaogcxdrd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtontdbdvt.html

按语言统计（条）：
来源：http://dali.yongpay.top/Article/details/gtxveshded.html

Python ......... 252
来源：http://dali.meibo888.top/Article/details/gtacrrovbq.html

PHP ............ 252
来源：http://dali.hnxiangtu.top/Article/details/gtzticvhju.html

JavaScript ..... 252
来源：http://dali.xuanzx.com/Article/details/gtgtjxpzsp.html

TypeScript ..... 212
来源：http://dali.cucudq.cn/Article/details/gtqmbiivip.html

Java ........... 212
来源：http://dali.hammf.cn/Article/details/gtnfqgiecx.html

Go ............. 212
来源：http://dali.yangfankeji.com/Article/details/gtdshdpuyn.html

Ruby ........... 212
来源：http://dali.tanke756.top/Article/details/gtntnernbw.html

C# ............. 212
来源：http://dali.zhengqikj.top/Article/details/gtqektkkyk.html

C .............. 30
来源：http://dali.yj202588.top/Article/details/gtirgwyzff.html

C++ ............ 30
来源：http://dali.dianchejie.cn/Article/details/gtpdjkkfgl.html

SQL ............ 90
来源：http://dali.shangyingyoupin.top/Article/details/gtwbjbtgfu.html

Bash ........... 80
来源：http://dali.cucudq.cn/Article/details/gtlczmymnw.html

Kotlin ......... 15
来源：http://dali.jinqigfzy.top/Article/details/gtrstdjfxx.html

Swift .......... 15
来源：http://dali.ppjwa.cn/Article/details/gtmbnuzmwv.html

Lua ............ 10
来源：http://dali.wangshuangyany.cn/Article/details/gtredmabis.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gtckumthjs.html

Scala .......... 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprmvjudi.html

------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtshvqezud.html

合计 ........... 2106 条
来源：http://dali.jyoumei.cn/Article/details/gtydiodnfi.html

按章节统计：
来源：http://dali.feifeiyinyue.top/Article/details/gtudnsijvh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gtcplgbjvd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtgqbmivop.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtjuuvcajz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gtxvnmygnn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sufxvd.cn/Article/details/gtzbriagju.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gtgakhsxdd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtanqjifoh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtxcrnbaas.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtcujnajdn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.vqdsnc.cn/Article/details/gtznhttrfm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtdtepxpwl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtgmqwfjst.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtwtjegibx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoavlbbdf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yongpay.top/Article/details/gtoxsxnglk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtrixsrliy.html

Q SQL 专题                              90
来源：http://dali.jinqigufen.top/Article/details/gtidmuhggm.html

R Bash 专题                             80
来源：http://dali.wangshuangyany.cn/Article/details/gtdoypxxet.html

S C / C++ 专题                          60
来源：http://dali.zhongyouzk.top/Article/details/gtmsruyjru.html

T 其他语言补充                          60
来源：http://dali.xinyue.icu/Article/details/gtbuifwbro.html

U 高频实用片段                         120
来源：http://dali.andypj.xyz/Article/details/gtdoiibnor.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtfonmuvgt.html

合计                                  2106 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkssnzsf.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtfhrrdhtu.html

使用提醒
来源：http://dali.ybcxt.top/Article/details/gtbbakuzal.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtrhcfohdh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj202588.top/Article/details/gtaadvgxpd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhiwuduotai.top/Article/details/gtbinsnooq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigfzy.top/Article/details/gtmupgpmpf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.meibo888.top/Article/details/gtmbigpyha.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cdnleiting.top/Article/details/gtgafqbzxh.html

—— 文件结束 ——
来源：http://dali.jiagoushi.top/Article/details/gtptizpuaa.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtuwagrscy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.bjfxy.top/Article/details/gtpgtmephe.html

Common Programming Examples Cheat Book
来源：http://dali.redwolf501.top/Article/details/gtlkerqiym.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtrkskwegc.html

【收录内容】
来源：http://dali.ydzc1.top/Article/details/gtryagulgo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daria6918.cn/Article/details/gtgpwjzzgj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangdashe.top/Article/details/gtopffaevg.html

SQL · Bash · C · C++
来源：http://dali.hfpthk.cn/Article/details/gthcdrxxui.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.vqdsnc.cn/Article/details/gtpouiwbef.html

【使用说明】
来源：http://dali.ehwqpu.com/Article/details/gtycpobafz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.fengsongda.top/Article/details/gtfnkhcskd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gzhubu.top/Article/details/gtkgiqcmmw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guowangkeji.top/Article/details/gtkxwtxrif.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhongyouzk.top/Article/details/gtdbmpfcuw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sufxvd.cn/Article/details/gtlxdylqow.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmauxgor.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pengpengdd.cyou/Article/details/gtktqglsto.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jyoumei.cn/Article/details/gtmmswhcgd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.9152youxi.cn/Article/details/gtxvxrlimw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gtfihffmzj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnqzz.top/Article/details/gtyspyfekt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.havefunace.top/Article/details/gtmxitgvuv.html

【文件统计】
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqdvmgqq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfzkqwjr.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtvfzienvc.html

目  录
来源：http://dali.guowangkeji.top/Article/details/gtipebgvwd.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtqbdrbtby.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpvvvnvj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yanxiufei.cn/Article/details/gtwtevbvxn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtcecvknfr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinqigfzy.top/Article/details/gtulazohgf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xuanzx.com/Article/details/gtwsxwsoqv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotyujnod.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yangfankeji.com/Article/details/gtskdxgout.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yangfankeji.com/Article/details/gtctgevlmm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtfzhivtyi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fzhhl.top/Article/details/gtdqlkskiu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtbwjmbynt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtipjigsnt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtmszrsikg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gtmkxhdppz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ehwqpu.com/Article/details/gtcelenzqz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtopvbbcze.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shuidangran.top/Article/details/gtkozzyamf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jqgfzy.top/Article/details/gtyapucilx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yongpay.top/Article/details/gtusdgseoc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtekrxhsfs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfvnetxs.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkqtqgfnw.html

A. 基础语法与类型
来源：http://dali.ppjwa.cn/Article/details/gtofpqdcjs.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gteetkgvln.html

[A01] Hello World
来源：http://dali.hammf.cn/Article/details/gtjjfglgio.html

Py:   print("Hello, World!")
来源：http://dali.tianlin.xyz/Article/details/gtyffoodyq.html

PHP:  echo "Hello, World!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnobszfja.html

JS:   console.log("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gtkvswtict.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.redwolf501.top/Article/details/gtpelzixma.html

Java: System.out.println("Hello, World!");
来源：http://dali.yuxming.cn/Article/details/gtazyasglt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gtvrmfxxkp.html

Ruby: puts "Hello, World!"
来源：http://dali.hnqzz.top/Article/details/gtmrccncqk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gtsgrutayn.html

[A02] 变量声明与赋值
来源：http://dali.mhx1999.top/Article/details/gtxscvincc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj202588.top/Article/details/gtgzmidbjg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yongpay.top/Article/details/gtmwcgeqdo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.meibo888.top/Article/details/gtjjcaxxrk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.aizwys.cn/Article/details/gtudtsjfmr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtvqjqphkp.html

Go:   name := "Alex"; age := 20
来源：http://dali.hnqzz.top/Article/details/gtatuxvxng.html

Ruby: name = "Alex"; age = 20
来源：http://dali.c1oappe.top/Article/details/gtwzyphrpt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nwbrower.top/Article/details/gtqixxmdpt.html

[A03] 常量定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticcnywag.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zdqjudy.top/Article/details/gthamdbwmg.html

PHP:  const PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtwmglsufq.html

JS:   const PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtdlmxrltq.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtvpqirnxb.html

Java: static final double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtuciebzmf.html

Go:   const PI = 3.14159
来源：http://dali.zycfv.cn/Article/details/gtcqkxnmza.html

Ruby: PI = 3.14159
来源：http://dali.guannengcc.top/Article/details/gtystlsanl.html

C#:   const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebmveqzn.html

[A04] 判断变量类型
来源：http://dali.shuidangran.top/Article/details/gtckadeggw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guowangkeji.top/Article/details/gtghpjwjol.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ybcxt.top/Article/details/gtvchlanyh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhixingplan.top/Article/details/gtlycnhnrg.html

TS:   typeof x; x instanceof Date
来源：http://dali.yangfankeji.com/Article/details/gtjagjilcc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.meibo888.top/Article/details/gtvlogeigt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dashuyun.cn/Article/details/gtfamnxfgt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj20258888.top/Article/details/gtxevvvhgq.html

C#:   x.GetType().Name; x is int
来源：http://dali.quarkkingdee.top/Article/details/gticqistls.html

[A05] 整数除法与取模
来源：http://dali.havefunace.top/Article/details/gtdriwdszj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptvokmry.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtnqdewkwk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.316326.xyz/Article/details/gtjknxderw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gtcgfzmxll.html

Java: 7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtvtemlojp.html

Go:   7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtrirybsyr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtmkltaywb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtgadvtegj.html

[A06] 字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gturqxspyy.html

Py:   int("42"); float("3.14")
来源：http://dali.ydzc1.top/Article/details/gtiskwqoza.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.9152youxi.cn/Article/details/gteivsudzl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.fzhhl.top/Article/details/gtnniotbkd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.gotoacloud.top/Article/details/gtwvsrftwx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xuanzx.com/Article/details/gtqfbjjlyj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ivvv.top/Article/details/gtwmamzeju.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shuidangran.top/Article/details/gtbaumnszr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxinkj.top/Article/details/gtyjdnydut.html

[A07] 数字转字符串
来源：http://dali.hnqzz.top/Article/details/gtwaywffoh.html

Py:   str(42)
来源：http://dali.cashguo.top/Article/details/gtjprfsoyv.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhongyouzk.top/Article/details/gtkbvhluzu.html

JS:   String(42); (42).toString()
来源：http://dali.cdnleiting.top/Article/details/gtdvgrgriv.html

TS:   String(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrdadfwy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hnxiangtu.top/Article/details/gtxwnjvnxc.html

Go:   strconv.Itoa(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtzxleaeft.html

Ruby: 42.to_s
来源：http://dali.vqdsnc.cn/Article/details/gttpthrnlu.html

C#:   42.ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkjhnrfa.html

[A08] 取整与四舍五入
来源：http://dali.xziqi.cn/Article/details/gtrtsegjol.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtucigyxef.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.snrcjt.cn/Article/details/gtyoboixfl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtcolyvlnn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xuetiantiany.cn/Article/details/gtjqsyjktd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yonumen.top/Article/details/gtnisaqtiy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmrorzsi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.dianchejie.cn/Article/details/gtesqpxfoo.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofylfbsm.html

[A09] 绝对值与最大最小值
来源：http://dali.9152youxi.cn/Article/details/gtnfnktzqh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gthqqjomgl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtixwasigy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtbbimavbw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yongpay.top/Article/details/gtclkkfync.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtmtvygldn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zycfv.cn/Article/details/gtfrjkmeyj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gogol.net.cn/Article/details/gtukquknqk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gttchthwyo.html

[A10] 生成随机数
来源：http://dali.cucudq.cn/Article/details/gthyspocfv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.fzhhl.top/Article/details/gtfsyivrpb.html

PHP:  random_int(1, 100);
来源：http://dali.yongpay.top/Article/details/gttyjefvdf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jyoumei.cn/Article/details/gtprpyfoko.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shzxlz.cn/Article/details/gtmoqnxhkx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yuxming.cn/Article/details/gtovodpujz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gogol.net.cn/Article/details/gtdaspbail.html

Ruby: rand(1..100)
来源：http://dali.daxiang520.top/Article/details/gtyqilfzxu.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoolvotvm.html

[A11] 条件表达式（三元）
来源：http://dali.zycfv.cn/Article/details/gtffsrjnaf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ppjwa.cn/Article/details/gtrsjicizx.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gtwombofsn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gtscwfxhux.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gtqrcewjzx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gtxhzaeosc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.vqdsnc.cn/Article/details/gtdkfqrgqg.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtxnrgfcyr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtuyabcvkm.html

[A12] 字符串插值 / 格式化
来源：http://dali.jlsjyb.cn/Article/details/gtusfcurfj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.birdmap.top/Article/details/gtqpavmvpd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zycfv.cn/Article/details/gtevfcxdmf.html

JS:   `Hello, ${name}!`
来源：http://dali.hywenlv.cn/Article/details/gtgiacicpj.html

TS:   `Hello, ${name}!`
来源：http://dali.fengsongda.top/Article/details/gtnjqjkiaj.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhixingplan.top/Article/details/gtilkcmvfh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yvedp.cn/Article/details/gtmqoskbyb.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenzaomai.com/Article/details/gtteidsvkk.html

C#:   $"Hello, {name}!"
来源：http://dali.sysykeji.top/Article/details/gtxwpkslks.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yangfankeji.com/Article/details/gtvxqxmttu.html


<!-- 参考信息 -->