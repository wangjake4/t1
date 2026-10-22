代发 wailian999

[U81] JS：初始化项目
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqymedmo.html

npm init -y;  npm i express
来源：http://dali.shzxlz.cn/Article/details/gt2fkeaauhp.html

[U82] JS：package.json 脚本
来源：http://dali.zhongyouzk.top/Article/details/gt2amcuiiaf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cucudq.cn/Article/details/gt2qyzyvufq.html

[U83] JS：ES Module 导入导出
来源：http://dali.daxiang520.top/Article/details/gt2kfklcday.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gt2epnvnfzu.html

[U84] JS：CommonJS 写法
来源：http://dali.yvedp.cn/Article/details/gt2bbkevclf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangdashe.top/Article/details/gt2cjibcurp.html

[U85] JS：可选链
来源：http://dali.hnqzz.top/Article/details/gt2lfwceyei.html

a?.b?.c
来源：http://dali.jyoumei.cn/Article/details/gt2avubujec.html

[U86] JS：空值合并
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvodmldh.html

a ?? b
来源：http://dali.andypj.xyz/Article/details/gt2vmuypwdn.html

[U87] JS：解构默认值
来源：http://dali.xinyue.icu/Article/details/gt2srcojkzc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ehwqpu.com/Article/details/gt2xnavegee.html

[U88] JS：对象展开合并
来源：http://dali.nanxinkj.top/Article/details/gt2wtfgmhqs.html

{ ...a, ...b }
来源：http://dali.cdnleiting.top/Article/details/gt2aqebkcix.html

[U89] JS：数组去重
来源：http://dali.tanke756.top/Article/details/gt2ibsxjcrd.html

[...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gt2yzdqyhel.html

[U90] JS：数字数组排序
来源：http://dali.chenzaomai.com/Article/details/gt2sypmvlsb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gt2poewrnuc.html

[U91] JS：对象键值遍历
来源：http://dali.yj202588.top/Article/details/gt2ttupbjlx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.0kj1m.cn/Article/details/gt2njddpjrl.html

[U92] JS：深拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2onlstoyc.html

structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2xxttqcrm.html

[U93] JS：模板字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2ynyqmtdj.html

`共 ${n} 条`
来源：http://dali.tanke756.top/Article/details/gt2oqfziqya.html

[U94] JS：箭头函数
来源：http://dali.ivvv.top/Article/details/gt2jojacepz.html

const double = x => x * 2;
来源：http://dali.fengsongda.top/Article/details/gt2ldktzxav.html

[U95] JS：Promise 包装
来源：http://dali.svipenyu.cn/Article/details/gt2dhqkzfhe.html

new Promise((resolve, reject) => {})
来源：http://dali.zdqjudy.top/Article/details/gt2qvpuntjf.html

[U96] JS：async/await 与异常
来源：http://dali.birdmap.top/Article/details/gt2kymspqxk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2wlyorycx.html

[U97] JS：并发请求
来源：http://dali.zhoulong.xyz/Article/details/gt2fujjnnmq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2wixdeqli.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangdashe.top/Article/details/gt2njyojadr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2lequpubp.html

[U99] JS：事件监听
来源：http://dali.sufxvd.cn/Article/details/gt2tflqbtsq.html

el.addEventListener("click", e => {})
来源：http://dali.cdnleiting.top/Article/details/gt2zlbtfopy.html

[U100] JS：DOM 查询
来源：http://dali.daria6918.cn/Article/details/gt2abwifsya.html

document.querySelector(".item")
来源：http://dali.gogol.net.cn/Article/details/gt2cbjludhz.html

[U101] JS：classList 操作
来源：http://dali.meibo888.top/Article/details/gt2bpfmtnyn.html

el.classList.toggle("active")
来源：http://dali.9152youxi.cn/Article/details/gt2qbwsztgv.html

[U102] JS：本地存储
来源：http://dali.tian-w.cn/Article/details/gt2przhskff.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xylfe.cn/Article/details/gt2jcibkhhl.html

[U103] JS：定时器
来源：http://dali.yonumen.top/Article/details/gt2rdwxibsr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cashguo.top/Article/details/gt2rymkgioo.html

[U104] JS：防抖
来源：http://dali.gotoacloud.top/Article/details/gt2elbsdkoi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gt2ycuseuhh.html

[U105] JS：节流
来源：http://dali.aizwys.cn/Article/details/gt2ecwtofiu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.kuanghao11.cn/Article/details/gt2jvuolctk.html

[U106] JS：日期格式化
来源：http://dali.iojbl.cn/Article/details/gt2ehtolpic.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xziqi.cn/Article/details/gt2evshsbdm.html

[U107] JS：数字千分位
来源：http://dali.andypj.xyz/Article/details/gt2uhipfubn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.birdmap.top/Article/details/gt2aekxqmaw.html

[U108] JS：随机整数
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbleqyfg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xylfe.cn/Article/details/gt2updvjcco.html

[U109] JS：数组分组
来源：http://dali.hysaishi.cn/Article/details/gt2olvahjsa.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdzxhrqk.html

[U110] JS：数组分块
来源：http://dali.chenlongwang.top/Article/details/gt2pzyqpadr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jyoumei.cn/Article/details/gt2llsfrnti.html

[U111] JS：对象转 Map
来源：http://dali.hnqzz.top/Article/details/gt2xtrlgbcp.html

new Map(Object.entries(obj))
来源：http://dali.daxiang520.top/Article/details/gt2jnjysmmm.html

[U112] JS：字符串补位
来源：http://dali.shuidangran.top/Article/details/gt2pkccptgi.html

"7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2vlzavwlx.html

[U113] JS：正则替换全部
来源：http://dali.tanke756.top/Article/details/gt2vmskatpj.html

s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2skqwfcob.html

[U114] JS：JSON 深比较
来源：http://dali.zhongyouzk.top/Article/details/gt2pskpfwep.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdhjkcra.html

[U115] JS：生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gt2nrmhojgh.html

crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pyzlsway.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cdnleiting.top/Article/details/gt2wvwblopb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dianchejie.cn/Article/details/gt2cwuacvhk.html

[U117] JS：单元测试
来源：http://dali.ybcxt.top/Article/details/gt2trachkkq.html

npm i -D vitest;  npx vitest
来源：http://dali.ppjwa.cn/Article/details/gt2wvleuryx.html

[U118] JS：开发服务器
来源：http://dali.bjfxy.top/Article/details/gt2sbafvhik.html

npm i -D vite;  npx vite
来源：http://dali.sxryk.cn/Article/details/gt2ucvejcwv.html

[U119] JS：生产构建
来源：http://dali.yuxming.cn/Article/details/gt2jexztgsy.html

npx vite build
来源：http://dali.yj20258.top/Article/details/gt2ixnfnosw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.meibo888.top/Article/details/gt2keeerljx.html

import.meta.env.VITE_API_URL
来源：http://dali.gotoacloud.top/Article/details/gt2rkjranel.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wlyfadvo.html

统计汇总
来源：http://dali.svipenyu.cn/Article/details/gt2zexrgfrh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2dsqqjpbn.html

按语言统计（条）：
来源：http://dali.zycfv.cn/Article/details/gt2wdqlkrtl.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udozpsyu.html

PHP ............ 252
来源：http://dali.aizwys.cn/Article/details/gt2wjpjkaqv.html

JavaScript ..... 252
来源：http://dali.guowangkeji.top/Article/details/gt2gelnilcp.html

TypeScript ..... 212
来源：http://dali.birdmap.top/Article/details/gt2tdhjmnxm.html

Java ........... 212
来源：http://dali.wangdashe.top/Article/details/gt2pqhchhqj.html

Go ............. 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzgkrjeg.html

Ruby ........... 212
来源：http://dali.gotoacloud.top/Article/details/gt2aorivvxl.html

C# ............. 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2zegjzpgg.html

C .............. 30
来源：http://dali.meibo888.top/Article/details/gt2xjeejwcn.html

C++ ............ 30
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvehhbvr.html

SQL ............ 90
来源：http://dali.cqqwz.cn/Article/details/gt2ztupakna.html

Bash ........... 80
来源：http://dali.jianghu66.top/Article/details/gt2gqsbxjrj.html

Kotlin ......... 15
来源：http://dali.yonumen.top/Article/details/gt2mhqeczsq.html

Swift .......... 15
来源：http://dali.smart0.xyz/Article/details/gt2zzmwaivu.html

Lua ............ 10
来源：http://dali.zycfv.cn/Article/details/gt2cialbdwl.html

Perl ........... 10
来源：http://dali.gogol.net.cn/Article/details/gt2irbodgmc.html

Scala .......... 10
来源：http://dali.nwbrower.top/Article/details/gt2wkzaprsm.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2sbnieaaj.html

合计 ........... 2106 条
来源：http://dali.ybcxt.top/Article/details/gt2pbwktnkg.html

按章节统计：
来源：http://dali.chenzaomai.com/Article/details/gt2ixqqihda.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gt2pcjyhgwu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2efzjkgcw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gt2vxobswmw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gt2xgywhqud.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xuanzx.com/Article/details/gt2inuiwpqw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqyezuoy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gt2lasbnenw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gt2sqtxepfi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gt2tgqfmhlg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.316326.xyz/Article/details/gt2xmqeglku.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gt2jsutqlbz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2fgjrrrha.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2ywzuqzij.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qggouahd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shuidangran.top/Article/details/gt2psyojqsc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gt2lnjizsfh.html

Q SQL 专题                              90
来源：http://dali.ppjwa.cn/Article/details/gt2nyniedfm.html

R Bash 专题                             80
来源：http://dali.zhongyouzk.top/Article/details/gt2herwekjc.html

S C / C++ 专题                          60
来源：http://dali.tanke756.top/Article/details/gt2jikjcrpb.html

T 其他语言补充                          60
来源：http://dali.yvedp.cn/Article/details/gt2eiomevfu.html

U 高频实用片段                         120
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlpstapw.html

------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2kjvsnlpb.html

合计                                  2106 条
来源：http://dali.hysaishi.cn/Article/details/gt2dwuqvoey.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2ubytvkrd.html

使用提醒
来源：http://dali.tanke756.top/Article/details/gt2keettgbq.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gt2jbeavwsp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ppjwa.cn/Article/details/gt2uqbuaoit.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yj20258888.top/Article/details/gt2idtyilcv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jqgufenzy.top/Article/details/gt2vswhjjlj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cqqwz.cn/Article/details/gt2dwwceqlz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.dashuyun.cn/Article/details/gt2rlayunyg.html

—— 文件结束 ——
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbtyvqfw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2yiqhhlhe.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.guowangkeji.top/Article/details/gt2uknqipkx.html

Common Programming Examples Cheat Book
来源：http://dali.snrcjt.cn/Article/details/gt2ospnzjwe.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2kglknmgy.html

【收录内容】
来源：http://dali.nanxuanxn.top/Article/details/gt2uogshsiq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jlsjyb.cn/Article/details/gt2xhincllj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cheryme.top/Article/details/gt2uvwajeoe.html

SQL · Bash · C · C++
来源：http://dali.fengsongda.top/Article/details/gt2orisobsl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yuanzhike.top/Article/details/gt2scncjvfl.html

【使用说明】
来源：http://dali.tanke756.top/Article/details/gt2evyxwcwd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jianghu66.top/Article/details/gt2rzqrxces.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jianghu66.top/Article/details/gt2xormdsze.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guannengcc.top/Article/details/gt2mcfjemeu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqsrhbs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuetiantiany.cn/Article/details/gt2kakexowc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xinyue.icu/Article/details/gt2bqcrcebz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.mhx1999.top/Article/details/gt2iikltfze.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kamhesny.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.0kj1m.cn/Article/details/gt2wxsbedww.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.kuanghao11.cn/Article/details/gt2drqhrwoj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.birdmap.top/Article/details/gt2lcfexpaz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.feifeiyinyue.top/Article/details/gt2flnrhmdb.html

【文件统计】
来源：http://dali.pengpengdd.cyou/Article/details/gt2axvgucio.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbtfxati.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gt2ngklwffx.html

目  录
来源：http://dali.yuanzhike.top/Article/details/gt2boasxfwi.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2hchuygxr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xziqi.cn/Article/details/gt2cdzfkact.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2fpydgqvg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2yypwaraz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.fengsongda.top/Article/details/gt2oofjxogx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.mhx1999.top/Article/details/gt2ydqprskh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yongpay.top/Article/details/gt2fdenbiym.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyslcfjt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.bjfxy.top/Article/details/gt2wucmimqf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gt2wcqrzwra.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.0kj1m.cn/Article/details/gt2mhjmrays.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gt2pbawpuui.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgjtxld.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxaptglk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gt2fqwoeayh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xziqi.cn/Article/details/gt2vpazwifg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gt2bevksfvb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tanke756.top/Article/details/gt2wyqzcfwh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.birdmap.top/Article/details/gt2ulrsfocg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2dahzwako.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xuztvbzw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pcqxuwwy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2qjspzjbv.html

A. 基础语法与类型
来源：http://dali.xuanzx.com/Article/details/gt2fuhcvykf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2lqztqlpw.html

[A01] Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2wiyzwiiq.html

Py:   print("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gt2jfxvjuwx.html

PHP:  echo "Hello, World!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxqyteki.html

JS:   console.log("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gt2notyzzgd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hywenlv.cn/Article/details/gt2bxgzubjs.html

Java: System.out.println("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gt2gbarhduh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenzaomai.com/Article/details/gt2umhdfogn.html

Ruby: puts "Hello, World!"
来源：http://dali.shuidangran.top/Article/details/gt2sixmutcz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gt2vpcafqiz.html

[A02] 变量声明与赋值
来源：http://dali.yuanzhike.top/Article/details/gt2hprcmmnv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shzxlz.cn/Article/details/gt2kxpknkyq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cucudq.cn/Article/details/gt2abyodcfg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinqigufen.top/Article/details/gt2atdnutmu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cashguo.top/Article/details/gt2fyawfnvx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.guowangkeji.top/Article/details/gt2dfxcxfms.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenlongwang.top/Article/details/gt2myznchjl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shzxlz.cn/Article/details/gt2zdnoayxu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.daxiang520.top/Article/details/gt2fengokae.html

[A03] 常量定义
来源：http://dali.jiagoushi.top/Article/details/gt2xocjphhs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jqgufenzy.top/Article/details/gt2kklxnrpj.html

PHP:  const PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2vujpymnz.html

JS:   const PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvpdmfsi.html

TS:   const PI: number = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2topoegyw.html

Java: static final double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2xtegbkmz.html

Go:   const PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gt2cbecamkn.html

Ruby: PI = 3.14159
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzwrklql.html

C#:   const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2gvxcgnfz.html

[A04] 判断变量类型
来源：http://dali.9152youxi.cn/Article/details/gt2zjldbfml.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.haohaochexian.top/Article/details/gt2kjpsmxbx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jianghu66.top/Article/details/gt2rwdqaqrg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbyjvyzk.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gt2rldbcwes.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sysykeji.top/Article/details/gt2asjdmdxl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xinyue.icu/Article/details/gt2tnxgeyes.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xinyue.icu/Article/details/gt2ctenvqvd.html

C#:   x.GetType().Name; x is int
来源：http://dali.havefunace.top/Article/details/gt2clveviwf.html

[A05] 整数除法与取模
来源：http://dali.fzhhl.top/Article/details/gt2dvpkkwet.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xziqi.cn/Article/details/gt2iyjydyfj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2wpijxvpb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gt2xjkhglxm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adlytrxo.html

Java: 7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gt2aeotnrbb.html

Go:   7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gt2tfoygfqc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rutldjru.html

C#:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2wythvxcp.html

[A06] 字符串转数字
来源：http://dali.bjfxy.top/Article/details/gt2vuqgkpbk.html

Py:   int("42"); float("3.14")
来源：http://dali.ppjwa.cn/Article/details/gt2zvjxnbic.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnqzz.top/Article/details/gt2nthzwzmc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.iojbl.cn/Article/details/gt2gohjtiab.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hfpthk.cn/Article/details/gt2pfxqjkwy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jianghu66.top/Article/details/gt2qrlduxag.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gzhubu.top/Article/details/gt2xlenybrv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhengqikj.top/Article/details/gt2qgbbtump.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.fzhhl.top/Article/details/gt2zywlwdee.html

[A07] 数字转字符串
来源：http://dali.cheryme.top/Article/details/gt2kxxuzdai.html

Py:   str(42)
来源：http://dali.yj20258.top/Article/details/gt2zdqsngem.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhixingplan.top/Article/details/gt2ojeacwnv.html

JS:   String(42); (42).toString()
来源：http://dali.shuidangran.top/Article/details/gt2qvxwjcsd.html

TS:   String(42)
来源：http://dali.mhx1999.top/Article/details/gt2zysfdxgr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dianchejie.cn/Article/details/gt2wvddtjuf.html

Go:   strconv.Itoa(42)
来源：http://dali.zdqjudy.top/Article/details/gt2mamiflzc.html

Ruby: 42.to_s
来源：http://dali.9152youxi.cn/Article/details/gt2fgxxyqal.html

C#:   42.ToString()
来源：http://dali.fzhhl.top/Article/details/gt2nytrocst.html

[A08] 取整与四舍五入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfihysxx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gt2byfmhioo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thjatkfn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gt2tkikhpkp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yongpay.top/Article/details/gt2vtmsyviq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gt2zttnuplo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gt2dyxspkkl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jqgfzy.top/Article/details/gt2sesqhhwm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gt2mzxdmemd.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ghohkqje.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbzbyzpk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2zqwhudwx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rauesfqx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2jtusiohi.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2ftgmioxd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sweek.top/Article/details/gt2nfuajttk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yanxiufei.cn/Article/details/gt2blgaqdjo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2odwsbnjm.html

[A10] 生成随机数
来源：http://dali.iojbl.cn/Article/details/gt2vfzqlloh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hywenlv.cn/Article/details/gt2hrdprbbw.html

PHP:  random_int(1, 100);
来源：http://dali.ydzc1.top/Article/details/gt2hzbsmggp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kypkoolf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guannengcc.top/Article/details/gt2ozhsclca.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gt2ahpledrx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.chenzaomai.com/Article/details/gt2qiigddob.html

Ruby: rand(1..100)
来源：http://dali.tian-w.cn/Article/details/gt2tmiwmgpu.html

C#:   new Random().Next(1, 101)
来源：http://dali.tian-w.cn/Article/details/gt2bspkspbs.html

[A11] 条件表达式（三元）
来源：http://dali.jqgufenzy.top/Article/details/gt2sudvilxf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cucudq.cn/Article/details/gt2ndtlhhza.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gt2bsfozdvn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gt2keeoztty.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gt2yocspgzu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gt2zudbboaw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.tianlin.xyz/Article/details/gt2kzayqasy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gt2kytnvabc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gt2lzjiboca.html

[A12] 字符串插值 / 格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2dvxzxmfo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cashguo.top/Article/details/gt2ihrfqrwu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.9152youxi.cn/Article/details/gt2yboxjihm.html

JS:   `Hello, ${name}!`
来源：http://dali.xinyue.icu/Article/details/gt2tdmsaoqj.html

TS:   `Hello, ${name}!`
来源：http://dali.hammf.cn/Article/details/gt2pzyeygps.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smyfibiy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqbqqanz.html

Ruby: "Hello, #{name}!"
来源：http://dali.jlsjyb.cn/Article/details/gt2tdiuijtv.html

C#:   $"Hello, {name}!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtsipxcm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2maegaekg.html

Py:   "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pozjdtaq.html

PHP:  "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gt2lzljcege.html

JS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gt2rqsupxio.html

TS:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gt2volhmywy.html


<!-- 参考信息 -->