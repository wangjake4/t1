代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.pengpengdd.cyou/Article/details/gtnebplmez.html

composer require psr/container
来源：http://dali.shzxlz.cn/Article/details/gtiuyiykgs.html

[U76] PHP：简单路由
来源：http://dali.svipenyu.cn/Article/details/gttarxtqnq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fengsongda.top/Article/details/gtvnwrgcyl.html

[U77] PHP：模板渲染
来源：http://dali.xziqi.cn/Article/details/gtjcjafxfe.html

composer require twig/twig
来源：http://dali.tianlin.xyz/Article/details/gtodyjdupz.html

[U78] PHP：单元测试
来源：http://dali.bjfxy.top/Article/details/gtueistjwj.html

composer require --dev phpunit/phpunit
来源：http://dali.xylfe.cn/Article/details/gtmvgknqah.html

[U79] PHP：静态分析
来源：http://dali.ppjwa.cn/Article/details/gtavkomwsm.html

composer require --dev phpstan/phpstan
来源：http://dali.wangshuangyany.cn/Article/details/gthukefpvw.html

[U80] PHP：代码规范修复
来源：http://dali.hammf.cn/Article/details/gtgbxotekl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shzxlz.cn/Article/details/gtatuixhmj.html

[U81] JS：初始化项目
来源：http://dali.jianghu66.top/Article/details/gtydnepfrk.html

npm init -y;  npm i express
来源：http://dali.gzhubu.top/Article/details/gtrfhmrefu.html

[U82] JS：package.json 脚本
来源：http://dali.cashguo.top/Article/details/gtjazthtao.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhongyouzk.top/Article/details/gterxgmmng.html

[U83] JS：ES Module 导入导出
来源：http://dali.ivvv.top/Article/details/gtwldnijmz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gtshmdagxi.html

[U84] JS：CommonJS 写法
来源：http://dali.tanke756.top/Article/details/gttbyzgfky.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.kuanghao11.cn/Article/details/gtuckwsgox.html

[U85] JS：可选链
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrieiscvd.html

a?.b?.c
来源：http://dali.redwolf501.top/Article/details/gtvvvkurgc.html

[U86] JS：空值合并
来源：http://dali.vqdsnc.cn/Article/details/gtxkphueao.html

a ?? b
来源：http://dali.zhengqikj.top/Article/details/gtsptigqvi.html

[U87] JS：解构默认值
来源：http://dali.shzxlz.cn/Article/details/gtblwqxzuh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.guannengcc.top/Article/details/gtjyrdpcas.html

[U88] JS：对象展开合并
来源：http://dali.jlsjyb.cn/Article/details/gtzieensfw.html

{ ...a, ...b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhhjpfmn.html

[U89] JS：数组去重
来源：http://dali.mhx1999.top/Article/details/gtkskfwvmy.html

[...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtcrtrrwct.html

[U90] JS：数字数组排序
来源：http://dali.redwolf501.top/Article/details/gtemknyowm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtjxkwbnoz.html

[U91] JS：对象键值遍历
来源：http://dali.fzhhl.top/Article/details/gtfpdklgdv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cdnleiting.top/Article/details/gthaggpgcm.html

[U92] JS：深拷贝
来源：http://dali.svipenyu.cn/Article/details/gtuqbkyvgm.html

structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gttcnkckin.html

[U93] JS：模板字符串
来源：http://dali.cheryme.top/Article/details/gtknsbqtiv.html

`共 ${n} 条`
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrjcrzzl.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdoylcoy.html

const double = x => x * 2;
来源：http://dali.ybcxt.top/Article/details/gtorkstnhr.html

[U95] JS：Promise 包装
来源：http://dali.yangfankeji.com/Article/details/gtrrzrwsnt.html

new Promise((resolve, reject) => {})
来源：http://dali.cheryme.top/Article/details/gtdhbizddo.html

[U96] JS：async/await 与异常
来源：http://dali.shzxlz.cn/Article/details/gtzikdfyfq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtfypvgoll.html

[U97] JS：并发请求
来源：http://dali.hammf.cn/Article/details/gthiahdmzb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxvblbem.html

[U98] JS：fetch 带 JSON
来源：http://dali.ydzc1.top/Article/details/gtswtymibf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sxryk.cn/Article/details/gtcnwplzhn.html

[U99] JS：事件监听
来源：http://dali.yuanzhike.top/Article/details/gtnrubyagy.html

el.addEventListener("click", e => {})
来源：http://dali.9152youxi.cn/Article/details/gtjfioodww.html

[U100] JS：DOM 查询
来源：http://dali.yuxming.cn/Article/details/gtjenrotir.html

document.querySelector(".item")
来源：http://dali.hongshengwenyu.top/Article/details/gtomqjyouc.html

[U101] JS：classList 操作
来源：http://dali.ppjwa.cn/Article/details/gtsksznbcu.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivglzgfc.html

[U102] JS：本地存储
来源：http://dali.daxiang520.top/Article/details/gtfbebsach.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.snrcjt.cn/Article/details/gtizmamuvr.html

[U103] JS：定时器
来源：http://dali.shuidangran.top/Article/details/gtulomluaq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tian-w.cn/Article/details/gtctfdouvn.html

[U104] JS：防抖
来源：http://dali.fzhhl.top/Article/details/gtptuzniuq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtdnxavikk.html

[U105] JS：节流
来源：http://dali.yuanzhike.top/Article/details/gtaptrdtlc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.c1oappe.top/Article/details/gtimgkaxdv.html

[U106] JS：日期格式化
来源：http://dali.xinyue.icu/Article/details/gtlkmfihwd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dianchejie.cn/Article/details/gtgogytdms.html

[U107] JS：数字千分位
来源：http://dali.redwolf501.top/Article/details/gtkqmpnfbh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj202588.top/Article/details/gtowrqgruz.html

[U108] JS：随机整数
来源：http://dali.xuetiantiany.cn/Article/details/gtgrcykucv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cucudq.cn/Article/details/gtisuzmkxd.html

[U109] JS：数组分组
来源：http://dali.birdmap.top/Article/details/gtyqipksws.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtelyoupwz.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfonkrgp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxuanxn.top/Article/details/gtpudwbebr.html

[U111] JS：对象转 Map
来源：http://dali.c1oappe.top/Article/details/gtvzzwhzrg.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtrfutfxqg.html

[U112] JS：字符串补位
来源：http://dali.ehwqpu.com/Article/details/gtfsucoltw.html

"7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtxkargvlc.html

[U113] JS：正则替换全部
来源：http://dali.hammf.cn/Article/details/gtoqxxcksb.html

s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtfpxzmaax.html

[U114] JS：JSON 深比较
来源：http://dali.aibaodan.cn/Article/details/gtiemquvex.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gteosqxllm.html

[U115] JS：生成 UUID
来源：http://dali.yj20258.top/Article/details/gtwbgeauqb.html

crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtmojuozju.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hongshengwenyu.top/Article/details/gtcriiiitf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtulppgfjc.html

[U117] JS：单元测试
来源：http://dali.birdmap.top/Article/details/gtpmdlglxn.html

npm i -D vitest;  npx vitest
来源：http://dali.havefunace.top/Article/details/gtvxyncdom.html

[U118] JS：开发服务器
来源：http://dali.yj20258.top/Article/details/gtzfympyki.html

npm i -D vite;  npx vite
来源：http://dali.dashuyun.cn/Article/details/gtkccwgxdz.html

[U119] JS：生产构建
来源：http://dali.jiagoushi.top/Article/details/gtyrvpgnza.html

npx vite build
来源：http://dali.tanke756.top/Article/details/gtsayefynm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xylfe.cn/Article/details/gtdubsgbkj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhixingplan.top/Article/details/gtxmtpwnqv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwdyqqmur.html

统计汇总
来源：http://dali.jianghu66.top/Article/details/gtnjokolmj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtzhdfrcey.html

按语言统计（条）：
来源：http://dali.yuxming.cn/Article/details/gtfgwachpk.html

Python ......... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gtixsuxfqp.html

PHP ............ 252
来源：http://dali.meibo888.top/Article/details/gtcaxkgxzb.html

JavaScript ..... 252
来源：http://dali.c1oappe.top/Article/details/gtiwsugzaz.html

TypeScript ..... 212
来源：http://dali.nwbrower.top/Article/details/gtkxctwbuz.html

Java ........... 212
来源：http://dali.pycfn.com/Article/details/gtrpfckbxc.html

Go ............. 212
来源：http://dali.zhixingplan.top/Article/details/gtdkmlaqyx.html

Ruby ........... 212
来源：http://dali.hammf.cn/Article/details/gtminnmfol.html

C# ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqkurraf.html

C .............. 30
来源：http://dali.yongpay.top/Article/details/gtukkceixg.html

C++ ............ 30
来源：http://dali.havefunace.top/Article/details/gtlmofeoww.html

SQL ............ 90
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvvetauy.html

Bash ........... 80
来源：http://dali.yj20258888.top/Article/details/gtiyfxyxol.html

Kotlin ......... 15
来源：http://dali.jinqigufen.top/Article/details/gtmtohfqem.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gttbfxbhar.html

Lua ............ 10
来源：http://dali.xuetiantiany.cn/Article/details/gtpcuypill.html

Perl ........... 10
来源：http://dali.nanxuanxn.top/Article/details/gtkawlipaf.html

Scala .......... 10
来源：http://dali.jiagoushi.top/Article/details/gtfxmmtdcs.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gtsdajjnok.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gtpxsjhllp.html

按章节统计：
来源：http://dali.smart0.xyz/Article/details/gtoxetozqx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgiqxsbqi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gtkclmbhpo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtdjrrlwwu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtrameosuw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gtwqonqquz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gtnfdgirom.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gtjttjdgzr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbctnhmdq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtxqsfksbt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yanxiufei.cn/Article/details/gtvuwkapet.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtidctghfj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gttowvopta.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtxbtobczt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.haohaochexian.top/Article/details/gtifmdfnbw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gtsrreftfp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtlgewvzqv.html

Q SQL 专题                              90
来源：http://dali.iojbl.cn/Article/details/gttlwgeksb.html

R Bash 专题                             80
来源：http://dali.smart0.xyz/Article/details/gtflfzmloi.html

S C / C++ 专题                          60
来源：http://dali.jinqigufen.top/Article/details/gttnigtpef.html

T 其他语言补充                          60
来源：http://dali.hnqzz.top/Article/details/gtkfqrihaa.html

U 高频实用片段                         120
来源：http://dali.cashguo.top/Article/details/gtuoxbcxeh.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gttreocmuz.html

合计                                  2106 条
来源：http://dali.316326.xyz/Article/details/gtchxecwky.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtxchbceme.html

使用提醒
来源：http://dali.quarkkingdee.top/Article/details/gtixtanvkb.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjseaknb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hysaishi.cn/Article/details/gtxscorpye.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tian-w.cn/Article/details/gtzncgxqrh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cucudq.cn/Article/details/gtsdwmwids.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenzaomai.com/Article/details/gtdaxebnvf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yueranfly.top/Article/details/gtawxfpolx.html

—— 文件结束 ——
来源：http://dali.yj20258.top/Article/details/gtgrzdcbtv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmpxldstp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ivvv.top/Article/details/gtaiiholjv.html

Common Programming Examples Cheat Book
来源：http://dali.guannengcc.top/Article/details/gtctvrhwdh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtbkpgwkue.html

【收录内容】
来源：http://dali.xinyue.icu/Article/details/gtgsfyjomf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sufxvd.cn/Article/details/gtpgfpfiyo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.svipenyu.cn/Article/details/gtvrplfxvs.html

SQL · Bash · C · C++
来源：http://dali.guannengcc.top/Article/details/gtgddvrxkz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.feifeiyinyue.top/Article/details/gtxmzduwro.html

【使用说明】
来源：http://dali.zhixingplan.top/Article/details/gtlpqjtxeh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shzxlz.cn/Article/details/gthoclcsvf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yueranfly.top/Article/details/gtdhyakrgf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ybcxt.top/Article/details/gtejeasdhe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.daria6918.cn/Article/details/gtozdedcul.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuetiantiany.cn/Article/details/gtkknjunsb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.fzhhl.top/Article/details/gtanzebtyd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj202588.top/Article/details/gtwmuuuwql.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yangfankeji.com/Article/details/gtiyijpukn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shanyushiyangtech.top/Article/details/gtqneubmwt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shzxlz.cn/Article/details/gtphhhvdsc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.birdmap.top/Article/details/gttbpvmnjv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.quarkkingdee.top/Article/details/gtbhfmopcg.html

【文件统计】
来源：http://dali.jqgfzy.top/Article/details/gtrgrxdmbo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.wangshuangyany.cn/Article/details/gtbedpqzbb.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtnstpivuo.html

目  录
来源：http://dali.cdnleiting.top/Article/details/gtfwyslycs.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtryywzban.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.dashuyun.cn/Article/details/gtifreqjvf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtnswdzahk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gtkqhiauzr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tian-w.cn/Article/details/gtrftvdmgx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sweek.top/Article/details/gtglgisexp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.mhx1999.top/Article/details/gtltzpbftv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtrcislzta.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gtrtvgaddc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtcssrvmgc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtwtbcuxsm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtgjpvlcnc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtnggcksbe.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtsmiskupq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gtdempfnjy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yuanzhike.top/Article/details/gtutjphksx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtzrmnhrpq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuanzhike.top/Article/details/gtxiiutcmd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ydzc1.top/Article/details/gtxzotujay.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.fzhhl.top/Article/details/gtwtezirjh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gtunqsowio.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.c1oappe.top/Article/details/gtajsejctl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtuoafhbqc.html

A. 基础语法与类型
来源：http://dali.mhx1999.top/Article/details/gtoefllnea.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtxsucpdml.html

[A01] Hello World
来源：http://dali.yj20258888.top/Article/details/gtycmekgqk.html

Py:   print("Hello, World!")
来源：http://dali.jlsjyb.cn/Article/details/gtkpqlsjlw.html

PHP:  echo "Hello, World!";
来源：http://dali.dianchejie.cn/Article/details/gtisiridbf.html

JS:   console.log("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtyzfgwvqu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yonumen.top/Article/details/gtohnlsgkd.html

Java: System.out.println("Hello, World!");
来源：http://dali.yuxming.cn/Article/details/gtuixvpmjt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.birdmap.top/Article/details/gtpmkzwgke.html

Ruby: puts "Hello, World!"
来源：http://dali.xinyue.icu/Article/details/gtsrlphczf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gtjkpqbcti.html

[A02] 变量声明与赋值
来源：http://dali.yuanzhike.top/Article/details/gtqgmfnioh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yangfankeji.com/Article/details/gtykcmkdqz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258888.top/Article/details/gtfurwnmxm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfircqmtv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxsxrhjq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ivvv.top/Article/details/gtzmfmjvge.html

Go:   name := "Alex"; age := 20
来源：http://dali.xuanzx.com/Article/details/gtpncgaaoz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ydzc1.top/Article/details/gtrzjksbep.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gtxthxddtr.html

[A03] 常量定义
来源：http://dali.meibo888.top/Article/details/gtxoaeaxnw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.svipenyu.cn/Article/details/gtnmjebkuo.html

PHP:  const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtwscztfat.html

JS:   const PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtuiqknxjf.html

TS:   const PI: number = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtygegljom.html

Java: static final double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtnhpnimpr.html

Go:   const PI = 3.14159
来源：http://dali.zhiwuduotai.top/Article/details/gtlfotstjh.html

Ruby: PI = 3.14159
来源：http://dali.yanxiufei.cn/Article/details/gtpfvwarlr.html

C#:   const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtzlhausze.html

[A04] 判断变量类型
来源：http://dali.ivvv.top/Article/details/gtxnfgvsov.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gtercvsykm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ivvv.top/Article/details/gtodifcbtw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shangyingyoupin.top/Article/details/gtiqmabqjh.html

TS:   typeof x; x instanceof Date
来源：http://dali.ivvv.top/Article/details/gtxhfblhak.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gotoacloud.top/Article/details/gtunvobxul.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hongshengwenyu.top/Article/details/gtoayazdil.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.iojbl.cn/Article/details/gtgxtpiuvz.html

C#:   x.GetType().Name; x is int
来源：http://dali.cdnleiting.top/Article/details/gtaznlpmdd.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gtesmnzyec.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jianghu66.top/Article/details/gtealenaky.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtxntnvdhl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtagbgpmuz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtohgfctpj.html

Java: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtfuuoxlvp.html

Go:   7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtwvzgndow.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtbetqrybn.html

C#:   7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtoeaxxqur.html

[A06] 字符串转数字
来源：http://dali.fengsongda.top/Article/details/gtfepdyyee.html

Py:   int("42"); float("3.14")
来源：http://dali.yj20258.top/Article/details/gtrourizpq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.birdmap.top/Article/details/gtxzdpavwh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.tian-w.cn/Article/details/gttbmveiba.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gtfxngutgk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ybcxt.top/Article/details/gtczljpupb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.svipenyu.cn/Article/details/gtrukdcezx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.snrcjt.cn/Article/details/gtvytqkjbn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jyoumei.cn/Article/details/gtssxiiuvi.html

[A07] 数字转字符串
来源：http://dali.cdnleiting.top/Article/details/gtwswwstvb.html

Py:   str(42)
来源：http://dali.jqgufenzy.top/Article/details/gtfnjskcgn.html

PHP:  (string) 42; strval(42)
来源：http://dali.gaohongyu789.top/Article/details/gtnojtfowa.html

JS:   String(42); (42).toString()
来源：http://dali.gogol.net.cn/Article/details/gtnktmkxwm.html

TS:   String(42)
来源：http://dali.cqqwz.cn/Article/details/gtejzrbscs.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.nwbrower.top/Article/details/gtfwbkflnk.html

Go:   strconv.Itoa(42)
来源：http://dali.aibaodan.cn/Article/details/gtafodozmm.html

Ruby: 42.to_s
来源：http://dali.snrcjt.cn/Article/details/gtunundpbm.html

C#:   42.ToString()
来源：http://dali.birdmap.top/Article/details/gtuzqiuvor.html

[A08] 取整与四舍五入
来源：http://dali.daria6918.cn/Article/details/gtoijnvrid.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gtbbcbfpag.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.pycfn.com/Article/details/gtzzrronvx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtzadymsaa.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zdqjudy.top/Article/details/gtxuqmcrug.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtksmsskqn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtrbxvqdyj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.vqdsnc.cn/Article/details/gtjvmlmvoi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gteuxbkvhz.html

[A09] 绝对值与最大最小值
来源：http://dali.snrcjt.cn/Article/details/gtuhetrgtt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtgfppbduc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gthzifqolx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtvffvpzbb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtermchgky.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtiufnjchi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.fengsongda.top/Article/details/gtgdichlcg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.nanxuanxn.top/Article/details/gtfynvwris.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtqfhcxufv.html

[A10] 生成随机数
来源：http://dali.yuxming.cn/Article/details/gtohhbrlca.html

Py:   import random; random.randint(1, 100)
来源：http://dali.pycfn.com/Article/details/gtxjvmwues.html

PHP:  random_int(1, 100);
来源：http://dali.haohaochexian.top/Article/details/gtfzzbgabb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ivvv.top/Article/details/gtktgdxaly.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.quarkkingdee.top/Article/details/gtizynjpfd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.shangyingyoupin.top/Article/details/gtcomcfjon.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.9152youxi.cn/Article/details/gtltkfxzjv.html

Ruby: rand(1..100)
来源：http://dali.hnqzz.top/Article/details/gtsspsmtmb.html

C#:   new Random().Next(1, 101)
来源：http://dali.sufxvd.cn/Article/details/gtmkcszcqg.html

[A11] 条件表达式（三元）
来源：http://dali.chenzaomai.com/Article/details/gtundhixyk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtyjindeuu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtsdqtnflu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokshdumy.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gtpiqhyyff.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtcmpvolgf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xziqi.cn/Article/details/gtmzvigrlj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gtnpiwwsan.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtjlogctwi.html

[A12] 字符串插值 / 格式化
来源：http://dali.0kj1m.cn/Article/details/gtvzkdhdiz.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhoulong.xyz/Article/details/gtejgnidek.html


<!-- 参考信息 -->