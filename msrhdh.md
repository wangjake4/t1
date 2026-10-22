代发 wailian999

[U79] PHP：静态分析
来源：http://dali.ppjwa.cn/Article/details/gtjowtqhsy.html

composer require --dev phpstan/phpstan
来源：http://dali.snrcjt.cn/Article/details/gtghmwugmb.html

[U80] PHP：代码规范修复
来源：http://dali.jlsjyb.cn/Article/details/gttocynydu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgufenzy.top/Article/details/gtftsljzxz.html

[U81] JS：初始化项目
来源：http://dali.shuidangran.top/Article/details/gttaenxwtw.html

npm init -y;  npm i express
来源：http://dali.snrcjt.cn/Article/details/gtabyacfxd.html

[U82] JS：package.json 脚本
来源：http://dali.gogol.net.cn/Article/details/gtoeokomzh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sweek.top/Article/details/gtuzydwuej.html

[U83] JS：ES Module 导入导出
来源：http://dali.dashuyun.cn/Article/details/gtajtipqeh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gtkazltbqd.html

[U84] JS：CommonJS 写法
来源：http://dali.dianchejie.cn/Article/details/gtkuolxoyf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xinyue.icu/Article/details/gtlllrafoc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gtsblzysqi.html

a?.b?.c
来源：http://dali.wangdashe.top/Article/details/gtiuijvxvz.html

[U86] JS：空值合并
来源：http://dali.jinqigfzy.top/Article/details/gtffpnkqqz.html

a ?? b
来源：http://dali.xziqi.cn/Article/details/gtcuhqcubw.html

[U87] JS：解构默认值
来源：http://dali.c1oappe.top/Article/details/gterznoron.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigfzy.top/Article/details/gtubyemmpk.html

[U88] JS：对象展开合并
来源：http://dali.quarkkingdee.top/Article/details/gtpodorucc.html

{ ...a, ...b }
来源：http://dali.aizwys.cn/Article/details/gtrclzzzli.html

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gtugfeicda.html

[...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtofhjqtrk.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcsbjuux.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtxkmwvzfd.html

[U91] JS：对象键值遍历
来源：http://dali.gzhubu.top/Article/details/gtgqllpznh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.iojbl.cn/Article/details/gtgtonsfrb.html

[U92] JS：深拷贝
来源：http://dali.hysaishi.cn/Article/details/gtmzkzjtqe.html

structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtwfwtinqp.html

[U93] JS：模板字符串
来源：http://dali.tian-w.cn/Article/details/gtpzekuizw.html

`共 ${n} 条`
来源：http://dali.jqgfzy.top/Article/details/gtrevtggfb.html

[U94] JS：箭头函数
来源：http://dali.dashuyun.cn/Article/details/gtnprcxuwm.html

const double = x => x * 2;
来源：http://dali.jinqigufen.top/Article/details/gtryusuyko.html

[U95] JS：Promise 包装
来源：http://dali.bjfxy.top/Article/details/gtjrvyxpiw.html

new Promise((resolve, reject) => {})
来源：http://dali.birdmap.top/Article/details/gtkmzfjxsa.html

[U96] JS：async/await 与异常
来源：http://dali.meibo888.top/Article/details/gtcdcrmavw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gttercfqno.html

[U97] JS：并发请求
来源：http://dali.hnqzz.top/Article/details/gtfpuyiuem.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtkrqchnyz.html

[U98] JS：fetch 带 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtpyhcxkyz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nanxinkj.top/Article/details/gtbpizuhuj.html

[U99] JS：事件监听
来源：http://dali.yongpay.top/Article/details/gtwgmgbubo.html

el.addEventListener("click", e => {})
来源：http://dali.shangyingyoupin.top/Article/details/gthdumjxpy.html

[U100] JS：DOM 查询
来源：http://dali.jinqigfzy.top/Article/details/gthvksxnjm.html

document.querySelector(".item")
来源：http://dali.hywenlv.cn/Article/details/gttqmppouj.html

[U101] JS：classList 操作
来源：http://dali.xuanzx.com/Article/details/gtlmcdiovk.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgvklqrq.html

[U102] JS：本地存储
来源：http://dali.fengsongda.top/Article/details/gthjkwnasi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiucjagu.html

[U103] JS：定时器
来源：http://dali.nanxinkj.top/Article/details/gttfqnkzbf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jyoumei.cn/Article/details/gtyhedhext.html

[U104] JS：防抖
来源：http://dali.vqdsnc.cn/Article/details/gtiipoongq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtcwbbabvt.html

[U105] JS：节流
来源：http://dali.jiagoushi.top/Article/details/gtfowingqf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yanxiufei.cn/Article/details/gtwobeosdl.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtirrifclr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenzaomai.com/Article/details/gtsyrlqili.html

[U107] JS：数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtzqfrfyto.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gtgqpvqcbk.html

[U108] JS：随机整数
来源：http://dali.hongshengwenyu.top/Article/details/gtubgtofjz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yueranfly.top/Article/details/gtllgemqel.html

[U109] JS：数组分组
来源：http://dali.sufxvd.cn/Article/details/gtueipkdjq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gtuafugngd.html

[U110] JS：数组分块
来源：http://dali.ydzc1.top/Article/details/gteccviaox.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnqzz.top/Article/details/gtfvstwqtq.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gtgzoozudi.html

new Map(Object.entries(obj))
来源：http://dali.havefunace.top/Article/details/gtcvmuebop.html

[U112] JS：字符串补位
来源：http://dali.nwbrower.top/Article/details/gtjmmphorl.html

"7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtnwtuuzxm.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gtcmrramzm.html

s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtwiwsagmw.html

[U114] JS：JSON 深比较
来源：http://dali.jiagoushi.top/Article/details/gtkvkfdjhv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtohzyzeix.html

[U115] JS：生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtnhrykulm.html

crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtuwaxxxuk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hfpthk.cn/Article/details/gteielzcyg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tian-w.cn/Article/details/gtzaxhgjkg.html

[U117] JS：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuaklorvl.html

npm i -D vitest;  npx vitest
来源：http://dali.nwbrower.top/Article/details/gtpmowfkmj.html

[U118] JS：开发服务器
来源：http://dali.yangfankeji.com/Article/details/gtkagmjvtn.html

npm i -D vite;  npx vite
来源：http://dali.wangdashe.top/Article/details/gtskijkwff.html

[U119] JS：生产构建
来源：http://dali.nwbrower.top/Article/details/gtanstzggg.html

npx vite build
来源：http://dali.nwbrower.top/Article/details/gtkateciyx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlermsoxf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyjculrx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gthyayndcn.html

统计汇总
来源：http://dali.sysykeji.top/Article/details/gttkzfrbmp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtuexumnmy.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gtixzxwrhq.html

Python ......... 252
来源：http://dali.xuanzx.com/Article/details/gtxjhngbjd.html

PHP ............ 252
来源：http://dali.havefunace.top/Article/details/gtkzxarjzn.html

JavaScript ..... 252
来源：http://dali.wangshuangyany.cn/Article/details/gtljkneqyr.html

TypeScript ..... 212
来源：http://dali.tian-w.cn/Article/details/gtwwljjfud.html

Java ........... 212
来源：http://dali.yongpay.top/Article/details/gtyucnlige.html

Go ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gtwcxlphkg.html

Ruby ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtgqumtxna.html

C# ............. 212
来源：http://dali.wangshuangyany.cn/Article/details/gtzfvsfnlt.html

C .............. 30
来源：http://dali.guowangkeji.top/Article/details/gtpyhxaynz.html

C++ ............ 30
来源：http://dali.feifeiyinyue.top/Article/details/gtzgqxsyaq.html

SQL ............ 90
来源：http://dali.shangyingyoupin.top/Article/details/gtgjzvoxwv.html

Bash ........... 80
来源：http://dali.jiagoushi.top/Article/details/gtufxmqbfd.html

Kotlin ......... 15
来源：http://dali.sufxvd.cn/Article/details/gtymehqfdn.html

Swift .......... 15
来源：http://dali.chenlongwang.top/Article/details/gtptcvyeuc.html

Lua ............ 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzdhtmeb.html

Perl ........... 10
来源：http://dali.wangshuangyany.cn/Article/details/gtdvkxwyqg.html

Scala .......... 10
来源：http://dali.9152youxi.cn/Article/details/gtlfqunbxs.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtdpwaesha.html

合计 ........... 2106 条
来源：http://dali.pengpengdd.cyou/Article/details/gtjgbovilj.html

按章节统计：
来源：http://dali.kuanghao11.cn/Article/details/gtxqgdvpnx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtdkeleyrv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gtikdvjeyz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtdwvqavqg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtuflpymce.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangtech.top/Article/details/gtibmsuzaq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gtrerzmxiw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtasqcxjid.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgzmsqqw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtltgrewpm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gtmrbepgcb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtmppjvdfs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtwuuqli.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtekcpexbh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokjbefzu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cashguo.top/Article/details/gtazvbntbv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtofmehyaj.html

Q SQL 专题                              90
来源：http://dali.zhixingplan.top/Article/details/gtvbsdbpkq.html

R Bash 专题                             80
来源：http://dali.shangyingyoupin.top/Article/details/gtoxuukteo.html

S C / C++ 专题                          60
来源：http://dali.meibo888.top/Article/details/gtzdrkefbc.html

T 其他语言补充                          60
来源：http://dali.yj20258888.top/Article/details/gtiavrdxsf.html

U 高频实用片段                         120
来源：http://dali.daxiang520.top/Article/details/gtzllpisqn.html

------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpmuoeao.html

合计                                  2106 条
来源：http://dali.cdnleiting.top/Article/details/gtlvzbybby.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtsmqhwzfa.html

使用提醒
来源：http://dali.shuidangran.top/Article/details/gtxugyplca.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gthyftdhba.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj202588.top/Article/details/gtgzghsnvp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cashguo.top/Article/details/gtxtabnuaz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsygekubm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqbelqsb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yonumen.top/Article/details/gtroprqoei.html

—— 文件结束 ——
来源：http://dali.jqgfzy.top/Article/details/gtanfixerv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtobdnsbwa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.0kj1m.cn/Article/details/gtcfmjojbl.html

Common Programming Examples Cheat Book
来源：http://dali.chenzaomai.com/Article/details/gtcygebcmo.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuunwgxuv.html

【收录内容】
来源：http://dali.kuanghao11.cn/Article/details/gtelcfoesh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhongyouzk.top/Article/details/gtwwhfohow.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shangyingyoupin.top/Article/details/gtybvlwurx.html

SQL · Bash · C · C++
来源：http://dali.fzhhl.top/Article/details/gtmmfnwzoj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xuetiantiany.cn/Article/details/gtknmmrrwe.html

【使用说明】
来源：http://dali.zhixingplan.top/Article/details/gtyryxznnl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sweek.top/Article/details/gtlownifyo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenlongwang.top/Article/details/gtdotyjppu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.bjfxy.top/Article/details/gtntwqoqpl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ehwqpu.com/Article/details/gtgmxagoux.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hongshengwenyu.top/Article/details/gtdyjityiz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.guowangkeji.top/Article/details/gtwxiatwtb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.0kj1m.cn/Article/details/gtvqzgnhnf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.andypj.xyz/Article/details/gtittnjnbm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhoulong.xyz/Article/details/gtdohtvqke.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.meibo888.top/Article/details/gtogugqxwj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tian-w.cn/Article/details/gtyrkxagab.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.c1oappe.top/Article/details/gtwbivszzy.html

【文件统计】
来源：http://dali.fengsongda.top/Article/details/gtiidyxkmy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hysaishi.cn/Article/details/gtmjekmrhs.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtymmssqds.html

目  录
来源：http://dali.quarkkingdee.top/Article/details/gtwxwveosi.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtwyfzpgfo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cheryme.top/Article/details/gttgaogjzg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gtqjailckz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtrhaoggji.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gtwdqojwyt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.redwolf501.top/Article/details/gtfszbsrnj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hfpthk.cn/Article/details/gtyiqhdhwr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gtodiqkmfv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gtcoifczys.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtatacenrn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtifotfyzj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtecsnlvix.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtpsrxrouk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtommdmgxz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gtmhtegppc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fengsongda.top/Article/details/gtevdrbpdu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtjputtdcg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.dianchejie.cn/Article/details/gthxkdsbpj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hfpthk.cn/Article/details/gtkftywzre.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgmznnxn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtbxsijcfm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gtytgdyihh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtavyfbwvu.html

A. 基础语法与类型
来源：http://dali.sysykeji.top/Article/details/gtaojoievy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwmnvheht.html

[A01] Hello World
来源：http://dali.fzhhl.top/Article/details/gtsqsmdure.html

Py:   print("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gtlstzcrsf.html

PHP:  echo "Hello, World!";
来源：http://dali.316326.xyz/Article/details/gtlmwvnywo.html

JS:   console.log("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gtdyrxsdyt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.snrcjt.cn/Article/details/gtopghpchx.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gthiirqmlr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nanxuanxn.top/Article/details/gtxvbcnaoo.html

Ruby: puts "Hello, World!"
来源：http://dali.dashuyun.cn/Article/details/gtxlmaimpj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jiagoushi.top/Article/details/gtrdthiukg.html

[A02] 变量声明与赋值
来源：http://dali.birdmap.top/Article/details/gtnxfcyldi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj20258.top/Article/details/gtkgdquapd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtksuauefu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtlkhldqej.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtgzenvtyj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtjonlebpl.html

Go:   name := "Alex"; age := 20
来源：http://dali.birdmap.top/Article/details/gtfvgslkrf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sufxvd.cn/Article/details/gthjclaota.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtimfrwvjn.html

[A03] 常量定义
来源：http://dali.dashuyun.cn/Article/details/gthpqduqns.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhoulong.xyz/Article/details/gtcnukddnl.html

PHP:  const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtoushzsqk.html

JS:   const PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtvrmqcwdr.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtmkdcpljk.html

Java: static final double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtwzrrtolh.html

Go:   const PI = 3.14159
来源：http://dali.gotoacloud.top/Article/details/gtfnxirvfs.html

Ruby: PI = 3.14159
来源：http://dali.daria6918.cn/Article/details/gthgysdqkv.html

C#:   const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtsxohnypz.html

[A04] 判断变量类型
来源：http://dali.gotoacloud.top/Article/details/gtnhgfkdpa.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shzxlz.cn/Article/details/gtbjpnopfo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.smart0.xyz/Article/details/gtdxalkxmc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.dianchejie.cn/Article/details/gtqmsxqhmt.html

TS:   typeof x; x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gtenmvngyd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sysykeji.top/Article/details/gtwrylqpky.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gotoacloud.top/Article/details/gtnulslvak.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.mhx1999.top/Article/details/gtktoktxxe.html

C#:   x.GetType().Name; x is int
来源：http://dali.jiagoushi.top/Article/details/gtoyywcduq.html

[A05] 整数除法与取模
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhhnvgur.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.iojbl.cn/Article/details/gtydayodln.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtdbbehbsu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gthhrmktyy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtqwsphppi.html

Java: 7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtiyftrkhi.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gtvrtzjdqa.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gtxulqtcyp.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtbmpkacek.html

[A06] 字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gtdnpxgidb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gtdwmkepac.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jqgfzy.top/Article/details/gthpkpblto.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinqigufen.top/Article/details/gtlkmuegtj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinqigufen.top/Article/details/gtifqdyitl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sysykeji.top/Article/details/gtbkgqyors.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj20258888.top/Article/details/gttfgubhjp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ybcxt.top/Article/details/gtplhvllvr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jyoumei.cn/Article/details/gtvkzzhwqq.html

[A07] 数字转字符串
来源：http://dali.snrcjt.cn/Article/details/gtrwamjirw.html

Py:   str(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxlyddvo.html

PHP:  (string) 42; strval(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrcdxkix.html

JS:   String(42); (42).toString()
来源：http://dali.hammf.cn/Article/details/gtjertouek.html

TS:   String(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajrhbxvj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjstajnvy.html

Go:   strconv.Itoa(42)
来源：http://dali.meibo888.top/Article/details/gtgenkjpkw.html

Ruby: 42.to_s
来源：http://dali.daxiang520.top/Article/details/gtipjdkqsw.html

C#:   42.ToString()
来源：http://dali.snrcjt.cn/Article/details/gtlxrynpgp.html

[A08] 取整与四舍五入
来源：http://dali.gogol.net.cn/Article/details/gtlrazhjaz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtitadcchg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.haohaochexian.top/Article/details/gtabcpqmhx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gtkzjsvovd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guowangkeji.top/Article/details/gtffdcsgsd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gtfwtrjtmw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gthbzneoov.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yangfankeji.com/Article/details/gtllpvcdwb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gtfqqhiowd.html

[A09] 绝对值与最大最小值
来源：http://dali.wangdashe.top/Article/details/gtfsfqidxh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxrekqph.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtwylqlhsx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtwcknyjml.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfhglcpx.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbmigzqd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.chenjidiqi.icu/Article/details/gtotfccswi.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.guannengcc.top/Article/details/gtzvkuuuxx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtvjgdeuik.html

[A10] 生成随机数
来源：http://dali.ybcxt.top/Article/details/gtirgcvhnl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hongshengwenyu.top/Article/details/gtlscojsst.html

PHP:  random_int(1, 100);
来源：http://dali.zdqjudy.top/Article/details/gtcwhslbwz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gotoacloud.top/Article/details/gtffaradrm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nwbrower.top/Article/details/gthbsxyish.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zdqjudy.top/Article/details/gttmsgpiol.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.fzhhl.top/Article/details/gtyrnronrw.html

Ruby: rand(1..100)
来源：http://dali.ivvv.top/Article/details/gtojascpgv.html

C#:   new Random().Next(1, 101)
来源：http://dali.xuanzx.com/Article/details/gtngzmbmle.html

[A11] 条件表达式（三元）
来源：http://dali.zhengqikj.top/Article/details/gtdnzbefpp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xuetiantiany.cn/Article/details/gttthidbdf.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtuoqrtxxu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gtwjzcvdoy.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gtjlfbggwu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtdxutpsbj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.pengpengdd.cyou/Article/details/gtwbwccivv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gtooxpojzl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gtgyltmngt.html

[A12] 字符串插值 / 格式化
来源：http://dali.quarkkingdee.top/Article/details/gtfxlhriho.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jqgufenzy.top/Article/details/gtifhwxogu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cashguo.top/Article/details/gtlwakdxjb.html

JS:   `Hello, ${name}!`
来源：http://dali.haohaochexian.top/Article/details/gtllnwaqad.html

TS:   `Hello, ${name}!`
来源：http://dali.yangfankeji.com/Article/details/gtixwitgqk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.aizwys.cn/Article/details/gtfovctfwg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtquznivdb.html

Ruby: "Hello, #{name}!"
来源：http://dali.daxiang520.top/Article/details/gttdtvwjow.html

C#:   $"Hello, {name}!"
来源：http://dali.ehwqpu.com/Article/details/gtmyxvvanq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.guannengcc.top/Article/details/gtqqaixvbb.html


<!-- 参考信息 -->