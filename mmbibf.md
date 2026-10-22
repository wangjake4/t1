代发 wailian999

[U79] PHP：静态分析
来源：http://dali.hongshengwenyu.top/Article/details/gtzziznqbk.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdymwuaj.html

[U80] PHP：代码规范修复
来源：http://dali.pycfn.com/Article/details/gtagddadoc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sufxvd.cn/Article/details/gtcjckpemu.html

[U81] JS：初始化项目
来源：http://dali.tian-w.cn/Article/details/gtfgkwtcog.html

npm init -y;  npm i express
来源：http://dali.nanxuanxn.top/Article/details/gtlmlseglk.html

[U82] JS：package.json 脚本
来源：http://dali.c1oappe.top/Article/details/gtvspkoely.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zycfv.cn/Article/details/gtsskegbsw.html

[U83] JS：ES Module 导入导出
来源：http://dali.fengsongda.top/Article/details/gtvxekoqxh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtfuaphfnm.html

[U84] JS：CommonJS 写法
来源：http://dali.guannengcc.top/Article/details/gtsvlibcer.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ppjwa.cn/Article/details/gtobzsbwnd.html

[U85] JS：可选链
来源：http://dali.hnxiangtu.top/Article/details/gtmgdiwlij.html

a?.b?.c
来源：http://dali.ehwqpu.com/Article/details/gtukvoxcdk.html

[U86] JS：空值合并
来源：http://dali.guannengcc.top/Article/details/gtwhzkwivc.html

a ?? b
来源：http://dali.jqgfzy.top/Article/details/gtkpkgjety.html

[U87] JS：解构默认值
来源：http://dali.gaohongyu789.top/Article/details/gtucfyrnrv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.c1oappe.top/Article/details/gtlmbqmbgl.html

[U88] JS：对象展开合并
来源：http://dali.yj20258.top/Article/details/gtxjfhcrpx.html

{ ...a, ...b }
来源：http://dali.nwbrower.top/Article/details/gtdwjpqhky.html

[U89] JS：数组去重
来源：http://dali.guowangkeji.top/Article/details/gtyxdypmmp.html

[...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtdscfqszv.html

[U90] JS：数字数组排序
来源：http://dali.nwbrower.top/Article/details/gtlkhfqesa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtewzqgiri.html

[U91] JS：对象键值遍历
来源：http://dali.iojbl.cn/Article/details/gtlqcmpfcc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhongyouzk.top/Article/details/gtmcrptmyi.html

[U92] JS：深拷贝
来源：http://dali.gzhubu.top/Article/details/gtnytxcgpq.html

structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtyjoxhzrh.html

[U93] JS：模板字符串
来源：http://dali.havefunace.top/Article/details/gtinzppqgn.html

`共 ${n} 条`
来源：http://dali.ppjwa.cn/Article/details/gtjclkwjif.html

[U94] JS：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gtivektuhu.html

const double = x => x * 2;
来源：http://dali.ppjwa.cn/Article/details/gtgujwafru.html

[U95] JS：Promise 包装
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihsytaah.html

new Promise((resolve, reject) => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtivzviqfv.html

[U96] JS：async/await 与异常
来源：http://dali.cashguo.top/Article/details/gtdxggbktr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtffoequjy.html

[U97] JS：并发请求
来源：http://dali.yuxming.cn/Article/details/gtwyihkclg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtptsbgbar.html

[U98] JS：fetch 带 JSON
来源：http://dali.mhx1999.top/Article/details/gtrlwmkkoz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangdashe.top/Article/details/gtrsafblef.html

[U99] JS：事件监听
来源：http://dali.jqgfzy.top/Article/details/gtnluopvcv.html

el.addEventListener("click", e => {})
来源：http://dali.gogol.net.cn/Article/details/gtysclpiuq.html

[U100] JS：DOM 查询
来源：http://dali.sysykeji.top/Article/details/gtdhioknlo.html

document.querySelector(".item")
来源：http://dali.0kj1m.cn/Article/details/gtkfmeajuj.html

[U101] JS：classList 操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwozwsjnf.html

el.classList.toggle("active")
来源：http://dali.zhiwuduotai.top/Article/details/gtzknzyuxv.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gtcicsvzjl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.birdmap.top/Article/details/gtnmouugku.html

[U103] JS：定时器
来源：http://dali.tian-w.cn/Article/details/gtualctffn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinghuilouyu.cn/Article/details/gtedhhlpzk.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gtwsjyiywr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtwpfkzude.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtenyedcmr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.quarkkingdee.top/Article/details/gtgsccrzvy.html

[U106] JS：日期格式化
来源：http://dali.aizwys.cn/Article/details/gtoksjeyly.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aizwys.cn/Article/details/gtztuwwejd.html

[U107] JS：数字千分位
来源：http://dali.sweek.top/Article/details/gtkqtibshr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtubmzwayc.html

[U108] JS：随机整数
来源：http://dali.hongshengwenyu.top/Article/details/gtklzshumf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhoulong.xyz/Article/details/gtuwdnsxwh.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzelswmy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gtdcjdbqei.html

[U110] JS：数组分块
来源：http://dali.shuidangran.top/Article/details/gtwioxfxwb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hongshengwenyu.top/Article/details/gteesxhfdp.html

[U111] JS：对象转 Map
来源：http://dali.svipenyu.cn/Article/details/gtvsivqzir.html

new Map(Object.entries(obj))
来源：http://dali.yonumen.top/Article/details/gtuinrscwe.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gtgjjykqjg.html

"7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtdnhtqkai.html

[U113] JS：正则替换全部
来源：http://dali.hywenlv.cn/Article/details/gtvayiubma.html

s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtigahfrrt.html

[U114] JS：JSON 深比较
来源：http://dali.gotoacloud.top/Article/details/gtlkliyrby.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtywsehlnd.html

[U115] JS：生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gtcicocgng.html

crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtpoakjbec.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangshuangyany.cn/Article/details/gtqymtgpro.html

/** @param {string} name */ function f(name) {}
来源：http://dali.snrcjt.cn/Article/details/gtaqbjpskm.html

[U117] JS：单元测试
来源：http://dali.pycfn.com/Article/details/gtyreqcjoa.html

npm i -D vitest;  npx vitest
来源：http://dali.yangfankeji.com/Article/details/gtgkroespq.html

[U118] JS：开发服务器
来源：http://dali.fzhhl.top/Article/details/gttkjsujfh.html

npm i -D vite;  npx vite
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlckrhgsw.html

[U119] JS：生产构建
来源：http://dali.chenjidiqi.icu/Article/details/gtljwffyvu.html

npx vite build
来源：http://dali.hywenlv.cn/Article/details/gtcidjyzmx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuanzx.com/Article/details/gthqbpugjo.html

import.meta.env.VITE_API_URL
来源：http://dali.hysaishi.cn/Article/details/gtppvtahwe.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttlricjml.html

统计汇总
来源：http://dali.316326.xyz/Article/details/gtlfkbwfvq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbhwvuser.html

按语言统计（条）：
来源：http://dali.gotoacloud.top/Article/details/gtelhmtxjr.html

Python ......... 252
来源：http://dali.aizwys.cn/Article/details/gtrcleksll.html

PHP ............ 252
来源：http://dali.hysaishi.cn/Article/details/gtykmawsvi.html

JavaScript ..... 252
来源：http://dali.hongshengwenyu.top/Article/details/gtdvvxfvjp.html

TypeScript ..... 212
来源：http://dali.guowangkeji.top/Article/details/gtsrmgjbrr.html

Java ........... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppqjnboq.html

Go ............. 212
来源：http://dali.birdmap.top/Article/details/gtngyfhcpt.html

Ruby ........... 212
来源：http://dali.yj20258.top/Article/details/gtglyygpdq.html

C# ............. 212
来源：http://dali.sufxvd.cn/Article/details/gtoizwpidd.html

C .............. 30
来源：http://dali.gotoacloud.top/Article/details/gtlbgdiopp.html

C++ ............ 30
来源：http://dali.havefunace.top/Article/details/gtmyenmxsr.html

SQL ............ 90
来源：http://dali.quarkkingdee.top/Article/details/gtdsubnikl.html

Bash ........... 80
来源：http://dali.cdnleiting.top/Article/details/gtafxvjmnk.html

Kotlin ......... 15
来源：http://dali.andypj.xyz/Article/details/gttahohsnk.html

Swift .......... 15
来源：http://dali.snrcjt.cn/Article/details/gthyrcrpgw.html

Lua ............ 10
来源：http://dali.jlsjyb.cn/Article/details/gtdemxrqem.html

Perl ........... 10
来源：http://dali.jlsjyb.cn/Article/details/gtjrkflmvi.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gteepeojbp.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gthdnehlth.html

合计 ........... 2106 条
来源：http://dali.guowangkeji.top/Article/details/gtteurpnyw.html

按章节统计：
来源：http://dali.jinghuilouyu.cn/Article/details/gthpohctrw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gtdwjalaff.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gthmvihtut.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gthjfkceje.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtdmvdyusk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhoulong.xyz/Article/details/gtynvcqxju.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gtwikjfazo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtpsplyvve.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gtrajummfy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtwswiusvu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.iojbl.cn/Article/details/gtxrdlhcbs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtjwefeesu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtwnftrawi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtqrrpbeyb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.svipenyu.cn/Article/details/gthmpbcrqg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guowangkeji.top/Article/details/gtnpeeubpn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtorqpdgny.html

Q SQL 专题                              90
来源：http://dali.dianchejie.cn/Article/details/gtmatoczqk.html

R Bash 专题                             80
来源：http://dali.vqdsnc.cn/Article/details/gtqbunpfbk.html

S C / C++ 专题                          60
来源：http://dali.zycfv.cn/Article/details/gtdopobqdc.html

T 其他语言补充                          60
来源：http://dali.haohaochexian.top/Article/details/gtwxvaqptw.html

U 高频实用片段                         120
来源：http://dali.jiagoushi.top/Article/details/gtwyduntwi.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtfgqssqok.html

合计                                  2106 条
来源：http://dali.yanxiufei.cn/Article/details/gtniegslvi.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtttagmhvu.html

使用提醒
来源：http://dali.kuanghao11.cn/Article/details/gtzyvxdyqu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtdstoscoj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.vqdsnc.cn/Article/details/gtvnrvwjjc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinghuilouyu.cn/Article/details/gtrckwkzcm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigfzy.top/Article/details/gtvyufssyk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.andypj.xyz/Article/details/gtvtzprjbt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewesyefi.html

—— 文件结束 ——
来源：http://dali.sysykeji.top/Article/details/gtedxomhbh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtsphymrtn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.kuanghao11.cn/Article/details/gtcxsouyig.html

Common Programming Examples Cheat Book
来源：http://dali.zhixingplan.top/Article/details/gtcwmqwxsj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtscwzydde.html

【收录内容】
来源：http://dali.meibo888.top/Article/details/gtyiahaopo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aibaodan.cn/Article/details/gtaiuiszov.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hongshengwenyu.top/Article/details/gtivqkdcer.html

SQL · Bash · C · C++
来源：http://dali.ivvv.top/Article/details/gtaxfdithl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cashguo.top/Article/details/gtafodufyn.html

【使用说明】
来源：http://dali.yuanzhike.top/Article/details/gtxwippyyj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xinyue.icu/Article/details/gthmnrpivs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.daxiang520.top/Article/details/gtxxpcnanj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hnxiangtu.top/Article/details/gtzibgufkn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zdqjudy.top/Article/details/gtlrsyfjtl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shzxlz.cn/Article/details/gtbkkoxxcu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.feifeiyinyue.top/Article/details/gtdqpoicni.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.fengsongda.top/Article/details/gtghgokggg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xylfe.cn/Article/details/gtlfngfulf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.316326.xyz/Article/details/gtqzexqfbn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yuanzhike.top/Article/details/gtxhhvqwdv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.9152youxi.cn/Article/details/gtdrpwpxtv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jlsjyb.cn/Article/details/gtazwdljbq.html

【文件统计】
来源：http://dali.jqgfzy.top/Article/details/gttuqifagu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shuidangran.top/Article/details/gtxndpwvvi.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtlazhkknm.html

目  录
来源：http://dali.zhoulong.xyz/Article/details/gtvvjnfxiz.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtayaljfnd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ydzc1.top/Article/details/gtiyehwbfb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gthrtlbwor.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gteusamyzy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhengqikj.top/Article/details/gtbbgrxibp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jqgfzy.top/Article/details/gtyyvgushu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jyoumei.cn/Article/details/gtstybthlq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gtstouoamz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnqzz.top/Article/details/gtnpxsqyap.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtizjfifwz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtblgbwbpf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtpzacgrpo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtoihiauvf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gturbincsy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gtlyutdgiu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sweek.top/Article/details/gtmyvygxdv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gttxbkqavu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yangfankeji.com/Article/details/gtgsukuwdv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.daxiang520.top/Article/details/gtocoflzjc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guannengcc.top/Article/details/gtwgwoxidm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtblvcdbmz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sxryk.cn/Article/details/gtkutqtxaa.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtetdlwlob.html

A. 基础语法与类型
来源：http://dali.dashuyun.cn/Article/details/gtopmibvzi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqpiojhii.html

[A01] Hello World
来源：http://dali.ydzc1.top/Article/details/gtekwtbimw.html

Py:   print("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtumgwjrzy.html

PHP:  echo "Hello, World!";
来源：http://dali.jqgufenzy.top/Article/details/gtaemnslbr.html

JS:   console.log("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtzvbuvuza.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinqigufen.top/Article/details/gtfbrswjad.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtggqpdlov.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zycfv.cn/Article/details/gtjruxfnic.html

Ruby: puts "Hello, World!"
来源：http://dali.gogol.net.cn/Article/details/gtdpmrvmak.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gtvdlxefrt.html

[A02] 变量声明与赋值
来源：http://dali.mhx1999.top/Article/details/gtefikpiav.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcwwxxlp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zycfv.cn/Article/details/gtjrnxlnna.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gtivcajffz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiszkbetg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.daxiang520.top/Article/details/gtrngczzms.html

Go:   name := "Alex"; age := 20
来源：http://dali.haohaochexian.top/Article/details/gthothdqko.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvfoauni.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.daxiang520.top/Article/details/gtzagtunlk.html

[A03] 常量定义
来源：http://dali.yonumen.top/Article/details/gtvuleqfny.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cqqwz.cn/Article/details/gtdbsykjay.html

PHP:  const PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtsuhfcdjn.html

JS:   const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gttztagteb.html

TS:   const PI: number = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtrtrsrxpa.html

Java: static final double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtblgggqdw.html

Go:   const PI = 3.14159
来源：http://dali.guannengcc.top/Article/details/gtwewsfsgb.html

Ruby: PI = 3.14159
来源：http://dali.hammf.cn/Article/details/gtfqfqnrps.html

C#:   const double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphyvdhhc.html

[A04] 判断变量类型
来源：http://dali.yueranfly.top/Article/details/gtxstpzycl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jqgfzy.top/Article/details/gtntgeziiq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jyoumei.cn/Article/details/gtyzlbjche.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shuidangran.top/Article/details/gtbdecsilm.html

TS:   typeof x; x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gtbxzyxxjk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jyoumei.cn/Article/details/gtikjyidkt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpcnbllc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvjffqxu.html

C#:   x.GetType().Name; x is int
来源：http://dali.hongshengwenyu.top/Article/details/gtresxhxon.html

[A05] 整数除法与取模
来源：http://dali.wangshuangyany.cn/Article/details/gteavspndx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dianchejie.cn/Article/details/gtihmczwfa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtbvbxthcr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtqywpsmtt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gthzjxmnbf.html

Java: 7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtircfipnc.html

Go:   7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gtavphohmd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gtvwhmkihw.html

C#:   7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtmsefkdfw.html

[A06] 字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gtjwenxlbp.html

Py:   int("42"); float("3.14")
来源：http://dali.jiagoushi.top/Article/details/gtsvnwaafx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gaohongyu789.top/Article/details/gtedspwxzx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.andypj.xyz/Article/details/gtccnhyokq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhiwuduotai.top/Article/details/gtysimscnw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nwbrower.top/Article/details/gtudjwnitq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hnxiangtu.top/Article/details/gthickkqog.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwpmvqpz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xziqi.cn/Article/details/gtlmluzupi.html

[A07] 数字转字符串
来源：http://dali.yvedp.cn/Article/details/gtzesxueeo.html

Py:   str(42)
来源：http://dali.yvedp.cn/Article/details/gtyhtivyjy.html

PHP:  (string) 42; strval(42)
来源：http://dali.ppjwa.cn/Article/details/gtoflmdlox.html

JS:   String(42); (42).toString()
来源：http://dali.cucudq.cn/Article/details/gtajlxojif.html

TS:   String(42)
来源：http://dali.pycfn.com/Article/details/gtwrhwudqz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.smart0.xyz/Article/details/gtzlgnrwbx.html

Go:   strconv.Itoa(42)
来源：http://dali.tian-w.cn/Article/details/gtaubwbfek.html

Ruby: 42.to_s
来源：http://dali.yj20258.top/Article/details/gtvnlskdph.html

C#:   42.ToString()
来源：http://dali.tianlin.xyz/Article/details/gtjbhmscuy.html

[A08] 取整与四舍五入
来源：http://dali.fengsongda.top/Article/details/gtkppmipew.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtzkpeeayb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.daria6918.cn/Article/details/gtfvzrxosp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gtgekahsyv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinghuilouyu.cn/Article/details/gttlafsmtb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtoepvitsv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtzndelahp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecnegrfe.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtarcfbreb.html

[A09] 绝对值与最大最小值
来源：http://dali.hysaishi.cn/Article/details/gtmoshgwnc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pycfn.com/Article/details/gtcbcbizrd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtxezftwts.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthejreacl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtpdcrwunc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtdkgusrqi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xuanzx.com/Article/details/gttxhmbmxi.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yongpay.top/Article/details/gtmtxfcaea.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtateeugty.html

[A10] 生成随机数
来源：http://dali.hysaishi.cn/Article/details/gtzrmxslav.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sweek.top/Article/details/gtmjzypenv.html

PHP:  random_int(1, 100);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfqelkkl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xinyue.icu/Article/details/gtiuxrrhjs.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cheryme.top/Article/details/gtqgaucdfq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwvidghn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.birdmap.top/Article/details/gtfizscdrc.html

Ruby: rand(1..100)
来源：http://dali.feifeiyinyue.top/Article/details/gtlymujcxa.html

C#:   new Random().Next(1, 101)
来源：http://dali.gzhubu.top/Article/details/gtpmguhjrd.html

[A11] 条件表达式（三元）
来源：http://dali.ivvv.top/Article/details/gtaycrgcmm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.bjfxy.top/Article/details/gtpjqcnnrw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtusthvioj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtwydvzpqq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gtsaqyiltu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gtydmlevkz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryobucqs.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gtenzuyivr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gtunuapvrl.html

[A12] 字符串插值 / 格式化
来源：http://dali.jqgufenzy.top/Article/details/gtinyjojro.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hongshengwenyu.top/Article/details/gtdtpeddxq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yongpay.top/Article/details/gtbpedlhwv.html

JS:   `Hello, ${name}!`
来源：http://dali.yanxiufei.cn/Article/details/gtfsxbxjar.html

TS:   `Hello, ${name}!`
来源：http://dali.hammf.cn/Article/details/gtpscbhhzm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhoulong.xyz/Article/details/gtbdfdpbcy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xziqi.cn/Article/details/gtbxngqwbv.html

Ruby: "Hello, #{name}!"
来源：http://dali.pengpengdd.cyou/Article/details/gtejprolky.html

C#:   $"Hello, {name}!"
来源：http://dali.yj202588.top/Article/details/gtvtkjepem.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shuidangran.top/Article/details/gtgakeewfa.html


<!-- 参考信息 -->