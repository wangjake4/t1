代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtbyrckqyd.html

throw new RuntimeException("失败", 500);
来源：http://dali.hnxiangtu.top/Article/details/gtynmmfedi.html

[U72] PHP：写错误日志
来源：http://dali.sweek.top/Article/details/gtmlnxryee.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjfwyhed.html

[U73] PHP：读取 ini 配置
来源：http://dali.quarkkingdee.top/Article/details/gtjzsnumgh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhixingplan.top/Article/details/gtgyfvezdt.html

[U74] PHP：读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtlgvokoqe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.iojbl.cn/Article/details/gtwuptxrac.html

[U75] PHP：依赖注入
来源：http://dali.dashuyun.cn/Article/details/gtlftqnokg.html

composer require psr/container
来源：http://dali.sysykeji.top/Article/details/gtgenwnppa.html

[U76] PHP：简单路由
来源：http://dali.cqqwz.cn/Article/details/gtaqjaczhm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcheavkqv.html

[U77] PHP：模板渲染
来源：http://dali.snrcjt.cn/Article/details/gtigaarthv.html

composer require twig/twig
来源：http://dali.ppjwa.cn/Article/details/gtmtlsrgql.html

[U78] PHP：单元测试
来源：http://dali.sweek.top/Article/details/gtxrbhhbrd.html

composer require --dev phpunit/phpunit
来源：http://dali.redwolf501.top/Article/details/gttkroeqgv.html

[U79] PHP：静态分析
来源：http://dali.guannengcc.top/Article/details/gtlpdqonyj.html

composer require --dev phpstan/phpstan
来源：http://dali.hammf.cn/Article/details/gtrtrcfeqv.html

[U80] PHP：代码规范修复
来源：http://dali.xuetiantiany.cn/Article/details/gtbvkcfnei.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigufen.top/Article/details/gthxjzxmnn.html

[U81] JS：初始化项目
来源：http://dali.zhixingplan.top/Article/details/gtwewdlhvc.html

npm init -y;  npm i express
来源：http://dali.sufxvd.cn/Article/details/gtfhgmvbjw.html

[U82] JS：package.json 脚本
来源：http://dali.cqqwz.cn/Article/details/gtkarktiiu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nanxuanxn.top/Article/details/gtdofiywxu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvonparj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cheryme.top/Article/details/gthbmjismw.html

[U84] JS：CommonJS 写法
来源：http://dali.bjfxy.top/Article/details/gtyapbqjyz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hammf.cn/Article/details/gtaardazsd.html

[U85] JS：可选链
来源：http://dali.zycfv.cn/Article/details/gtnxinrxsg.html

a?.b?.c
来源：http://dali.vqdsnc.cn/Article/details/gtaquqomjw.html

[U86] JS：空值合并
来源：http://dali.hywenlv.cn/Article/details/gtmwylulfu.html

a ?? b
来源：http://dali.ivvv.top/Article/details/gthmwotbqg.html

[U87] JS：解构默认值
来源：http://dali.c1oappe.top/Article/details/gtguxwshpu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xuanzx.com/Article/details/gtgtqxbitk.html

[U88] JS：对象展开合并
来源：http://dali.smart0.xyz/Article/details/gtvxrvhnyt.html

{ ...a, ...b }
来源：http://dali.ybcxt.top/Article/details/gtlsztbrap.html

[U89] JS：数组去重
来源：http://dali.shuidangran.top/Article/details/gtwnmsgdxx.html

[...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtbqqzgpsk.html

[U90] JS：数字数组排序
来源：http://dali.zdqjudy.top/Article/details/gtnzvjsrdu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtvnlhhbqt.html

[U91] JS：对象键值遍历
来源：http://dali.ehwqpu.com/Article/details/gtyncufmez.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xuanzx.com/Article/details/gthxdvhgxb.html

[U92] JS：深拷贝
来源：http://dali.guannengcc.top/Article/details/gtbzfstoce.html

structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gthzqazmxq.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtirfcpqcz.html

`共 ${n} 条`
来源：http://dali.sysykeji.top/Article/details/gteqhkrhng.html

[U94] JS：箭头函数
来源：http://dali.sxryk.cn/Article/details/gtvycwdrlf.html

const double = x => x * 2;
来源：http://dali.tianlin.xyz/Article/details/gtlrvcurpu.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gtplgjnefw.html

new Promise((resolve, reject) => {})
来源：http://dali.yueranfly.top/Article/details/gtdpacbftn.html

[U96] JS：async/await 与异常
来源：http://dali.gzhubu.top/Article/details/gtlbzqwyhn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtoeaakyik.html

[U97] JS：并发请求
来源：http://dali.hywenlv.cn/Article/details/gtqfuimcfq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtnsjzlert.html

[U98] JS：fetch 带 JSON
来源：http://dali.gzhubu.top/Article/details/gtgznvtobs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhtlfwha.html

[U99] JS：事件监听
来源：http://dali.jianghu66.top/Article/details/gtjhbqaljd.html

el.addEventListener("click", e => {})
来源：http://dali.chenjidiqi.icu/Article/details/gttikxlett.html

[U100] JS：DOM 查询
来源：http://dali.gaohongyu789.top/Article/details/gtgwiodlxc.html

document.querySelector(".item")
来源：http://dali.yonumen.top/Article/details/gthxrtloqb.html

[U101] JS：classList 操作
来源：http://dali.redwolf501.top/Article/details/gtlbwxmzlq.html

el.classList.toggle("active")
来源：http://dali.gotoacloud.top/Article/details/gtppusyhwf.html

[U102] JS：本地存储
来源：http://dali.hnxiangtu.top/Article/details/gtitfiymqk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gtxsdoptgs.html

[U103] JS：定时器
来源：http://dali.svipenyu.cn/Article/details/gtfruhoonw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.kuanghao11.cn/Article/details/gthtkchqgq.html

[U104] JS：防抖
来源：http://dali.bjfxy.top/Article/details/gtwrywjunf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtctxyeubw.html

[U105] JS：节流
来源：http://dali.yonumen.top/Article/details/gtaqxjziem.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenlongwang.top/Article/details/gtzjewskuy.html

[U106] JS：日期格式化
来源：http://dali.jianghu66.top/Article/details/gtyamryafx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aibaodan.cn/Article/details/gtzhkrxnhx.html

[U107] JS：数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gteifaiwpz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gtqylclmcs.html

[U108] JS：随机整数
来源：http://dali.hammf.cn/Article/details/gtclrdqhos.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhixingplan.top/Article/details/gtqjxuswvi.html

[U109] JS：数组分组
来源：http://dali.sxryk.cn/Article/details/gttcfkzgkx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnransgh.html

[U110] JS：数组分块
来源：http://dali.zhengqikj.top/Article/details/gtygeyhjii.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnlkgmpt.html

[U111] JS：对象转 Map
来源：http://dali.ydzc1.top/Article/details/gtvsfiajft.html

new Map(Object.entries(obj))
来源：http://dali.gzhubu.top/Article/details/gtwyupenvz.html

[U112] JS：字符串补位
来源：http://dali.yonumen.top/Article/details/gtnqgzhzkv.html

"7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtdqkaqigc.html

[U113] JS：正则替换全部
来源：http://dali.hnxiangtu.top/Article/details/gtjqcjhxim.html

s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtfdoazunj.html

[U114] JS：JSON 深比较
来源：http://dali.fengsongda.top/Article/details/gthvaggqnx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gtcroaewcu.html

[U115] JS：生成 UUID
来源：http://dali.316326.xyz/Article/details/gtdnxlcpww.html

crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtpalqaujf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ydzc1.top/Article/details/gtxcsgszpf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.iojbl.cn/Article/details/gtatkmbmoq.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gtaitdpyny.html

npm i -D vitest;  npx vitest
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucmmcgfk.html

[U118] JS：开发服务器
来源：http://dali.guannengcc.top/Article/details/gtvuyrxgou.html

npm i -D vite;  npx vite
来源：http://dali.cheryme.top/Article/details/gtyufoppqv.html

[U119] JS：生产构建
来源：http://dali.cucudq.cn/Article/details/gtugknxsip.html

npx vite build
来源：http://dali.wangshuangyany.cn/Article/details/gtcvdyqlju.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.svipenyu.cn/Article/details/gtidsgbhdh.html

import.meta.env.VITE_API_URL
来源：http://dali.chenlongwang.top/Article/details/gtfpoktpes.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzyrmgkuc.html

统计汇总
来源：http://dali.iojbl.cn/Article/details/gtjyzkkobq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxtanrkku.html

按语言统计（条）：
来源：http://dali.ppjwa.cn/Article/details/gtmcbejlum.html

Python ......... 252
来源：http://dali.yj202588.top/Article/details/gtzpoqlcna.html

PHP ............ 252
来源：http://dali.yueranfly.top/Article/details/gtzykdpoos.html

JavaScript ..... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqnrqbkf.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gtxfptjgul.html

Java ........... 212
来源：http://dali.yueranfly.top/Article/details/gtverimsei.html

Go ............. 212
来源：http://dali.sufxvd.cn/Article/details/gtxbffvqhs.html

Ruby ........... 212
来源：http://dali.yangfankeji.com/Article/details/gtnzntynsf.html

C# ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gtbaloswug.html

C .............. 30
来源：http://dali.feifeiyinyue.top/Article/details/gtfadefgng.html

C++ ............ 30
来源：http://dali.wangdashe.top/Article/details/gtopzjlxnr.html

SQL ............ 90
来源：http://dali.jinqigufen.top/Article/details/gtsykjoeud.html

Bash ........... 80
来源：http://dali.sxryk.cn/Article/details/gtthpfktgi.html

Kotlin ......... 15
来源：http://dali.shuidangran.top/Article/details/gtlcsmowis.html

Swift .......... 15
来源：http://dali.yueranfly.top/Article/details/gtknwtspis.html

Lua ............ 10
来源：http://dali.meibo888.top/Article/details/gtpobxzkvz.html

Perl ........... 10
来源：http://dali.yj202588.top/Article/details/gtpznghtjw.html

Scala .......... 10
来源：http://dali.yonumen.top/Article/details/gtsgtluhuz.html

------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtuuhbvpeq.html

合计 ........... 2106 条
来源：http://dali.xziqi.cn/Article/details/gtbcptrynq.html

按章节统计：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvevolben.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gtjehrzros.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gtopeklzms.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gtiheonggs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xinyue.icu/Article/details/gtyiadtqbh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jyoumei.cn/Article/details/gtfchgixup.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gteisfymzm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gtnblslqke.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yongpay.top/Article/details/gtzeuhsgvj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtgwzfkzpe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gtxgipftoz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gthgeqwmqo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtcapmtsbr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtskzxvuwx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gtgffklnlo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzawaqgex.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gthgjcgmle.html

Q SQL 专题                              90
来源：http://dali.jinqigfzy.top/Article/details/gtssgywape.html

R Bash 专题                             80
来源：http://dali.sufxvd.cn/Article/details/gtuceqeoba.html

S C / C++ 专题                          60
来源：http://dali.sweek.top/Article/details/gtjesxjges.html

T 其他语言补充                          60
来源：http://dali.xuanzx.com/Article/details/gtxhfounev.html

U 高频实用片段                         120
来源：http://dali.hysaishi.cn/Article/details/gtajljsara.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtinrjcaey.html

合计                                  2106 条
来源：http://dali.316326.xyz/Article/details/gtbvunaipl.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhvwftmt.html

使用提醒
来源：http://dali.jinqigfzy.top/Article/details/gttjabkfst.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtijvxbday.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gaohongyu789.top/Article/details/gtytfupkez.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gzhubu.top/Article/details/gtotxqzrir.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cashguo.top/Article/details/gtllbfeupy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yongpay.top/Article/details/gtwhvqptmk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xylfe.cn/Article/details/gtygcnpton.html

—— 文件结束 ——
来源：http://dali.jqgufenzy.top/Article/details/gtjkysgxot.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtdhjbxmnt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tian-w.cn/Article/details/gtwimyaahh.html

Common Programming Examples Cheat Book
来源：http://dali.ehwqpu.com/Article/details/gtzzirfuwl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtgaxvuvlt.html

【收录内容】
来源：http://dali.shuidangran.top/Article/details/gtpdazbulx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shuidangran.top/Article/details/gtxvxzykfr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ivvv.top/Article/details/gtjobcfkzj.html

SQL · Bash · C · C++
来源：http://dali.haohaochexian.top/Article/details/gtptvjfmhw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenjidiqi.icu/Article/details/gtzvmjugyp.html

【使用说明】
来源：http://dali.sxryk.cn/Article/details/gtocdbhogx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jianghu66.top/Article/details/gtglvtcklh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxeialmyo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ppjwa.cn/Article/details/gtztxymwoc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zycfv.cn/Article/details/gtxboqoofl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.pycfn.com/Article/details/gtvckmtuui.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yuxming.cn/Article/details/gtgomcpczu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hysaishi.cn/Article/details/gtvvvqxita.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nanxuanxn.top/Article/details/gtgqsphvpn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.birdmap.top/Article/details/gtceykpxvt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.svipenyu.cn/Article/details/gtqwxkwdvc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.guannengcc.top/Article/details/gtspnogxlt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jianghu66.top/Article/details/gteqkeetyr.html

【文件统计】
来源：http://dali.jinghuilouyu.cn/Article/details/gtjemvhhaz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gaohongyu789.top/Article/details/gtekaaxiqr.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtmiqlstzr.html

目  录
来源：http://dali.jinqigfzy.top/Article/details/gtbaptddeo.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtjwdqiyco.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.dashuyun.cn/Article/details/gtcxnbkoya.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtmnfzrhda.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gtxjlxbdjw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtofobtu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.wangdashe.top/Article/details/gtbnunbpbr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvaoshjk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhixingplan.top/Article/details/gthzlzvgif.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtoqepvylq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtydosvsht.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.birdmap.top/Article/details/gtamzbrooo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtxmdnsjmt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtneyoosik.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtixsumbvp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hnqzz.top/Article/details/gtcacppltf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.guannengcc.top/Article/details/gtnfqybibx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtmtycxbpw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tian-w.cn/Article/details/gtzgqmbhhi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cheryme.top/Article/details/gtaimxzzlt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ivvv.top/Article/details/gtmvjvrzvp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtmmwnocur.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gtzasnhjld.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtaxrkeuoe.html

A. 基础语法与类型
来源：http://dali.quarkkingdee.top/Article/details/gtbiulzfnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtgerwebru.html

[A01] Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtqaknohil.html

Py:   print("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gtalimymuo.html

PHP:  echo "Hello, World!";
来源：http://dali.ehwqpu.com/Article/details/gtvcafhege.html

JS:   console.log("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtowlfxexl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258888.top/Article/details/gticdcckcy.html

Java: System.out.println("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gtdzjjrfqv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gogol.net.cn/Article/details/gtrnahhnwc.html

Ruby: puts "Hello, World!"
来源：http://dali.jinqigfzy.top/Article/details/gtdwyqxkgm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.316326.xyz/Article/details/gtxgwvwlfc.html

[A02] 变量声明与赋值
来源：http://dali.smart0.xyz/Article/details/gtlukdpskk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuanzx.com/Article/details/gtijjvgnzu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258.top/Article/details/gtbmdswvaa.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yuanzhike.top/Article/details/gtfzwykyuc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtlftachjs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtmrehbhos.html

Go:   name := "Alex"; age := 20
来源：http://dali.gzhubu.top/Article/details/gtmoadnmeq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.daxiang520.top/Article/details/gtrjjcpifw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.c1oappe.top/Article/details/gtrdzltgjp.html

[A03] 常量定义
来源：http://dali.shangyingyoupin.top/Article/details/gtsuqppksg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hfpthk.cn/Article/details/gtukaucyrh.html

PHP:  const PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtggufwxvg.html

JS:   const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtetjcfwlp.html

TS:   const PI: number = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtnggzvzpm.html

Java: static final double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtbotohekf.html

Go:   const PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gtzycmyfjx.html

Ruby: PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gtcoprvrej.html

C#:   const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtfdvvllbe.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gtrkawgday.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.kuanghao11.cn/Article/details/gtepfqehbl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gotoacloud.top/Article/details/gtpgdcmyvw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gtxodiztzy.html

TS:   typeof x; x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gtezexhflt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ehwqpu.com/Article/details/gtblkpoamu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hysaishi.cn/Article/details/gtfhmfwnpy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigfzy.top/Article/details/gtvwtpzdmn.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj202588.top/Article/details/gtzshgiatr.html

[A05] 整数除法与取模
来源：http://dali.sysykeji.top/Article/details/gtopzqkxsh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlppnfpkg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtdddljkpc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtgvcwicid.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtudjbkeft.html

Java: 7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtxvodwdvw.html

Go:   7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtdrljlsee.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtmtceceqz.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtsznwgtog.html

[A06] 字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gtosffnhlb.html

Py:   int("42"); float("3.14")
来源：http://dali.hfpthk.cn/Article/details/gturdpqazw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yj20258.top/Article/details/gtnlshtpyt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.mhx1999.top/Article/details/gtvtuolmgd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatkzkxej.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.316326.xyz/Article/details/gtcphgjttx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.andypj.xyz/Article/details/gtdenmsjge.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hywenlv.cn/Article/details/gticfgfcxu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gtuhmvzxfp.html

[A07] 数字转字符串
来源：http://dali.dianchejie.cn/Article/details/gtxztmimgu.html

Py:   str(42)
来源：http://dali.xziqi.cn/Article/details/gtehqrqtkz.html

PHP:  (string) 42; strval(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtwuvdsmbj.html

JS:   String(42); (42).toString()
来源：http://dali.gzhubu.top/Article/details/gtdrqxpqno.html

TS:   String(42)
来源：http://dali.tian-w.cn/Article/details/gtrseinuww.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jlsjyb.cn/Article/details/gthegukosz.html

Go:   strconv.Itoa(42)
来源：http://dali.dashuyun.cn/Article/details/gtodosnpqy.html

Ruby: 42.to_s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhewwzmn.html

C#:   42.ToString()
来源：http://dali.chenzaomai.com/Article/details/gtwxlngpld.html

[A08] 取整与四舍五入
来源：http://dali.hnxiangtu.top/Article/details/gtupgesagz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gtjslsjouw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.svipenyu.cn/Article/details/gtqhdyfkhr.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gtpmoqvopz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jqgfzy.top/Article/details/gtsclkqxsj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gtxtlrtvvi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.birdmap.top/Article/details/gtjrbhjjwo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.kuanghao11.cn/Article/details/gtclbiuuxl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gtjdespnvv.html

[A09] 绝对值与最大最小值
来源：http://dali.gotoacloud.top/Article/details/gtzgzmzzcd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gttmtycbwn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtpquowwmy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzafjlsjv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtkfjimptg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtkssbnqbj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.0kj1m.cn/Article/details/gtzbwavfrf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sufxvd.cn/Article/details/gtknsjpmzq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gttgqthisd.html

[A10] 生成随机数
来源：http://dali.cqqwz.cn/Article/details/gtmrbycbnt.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yj202588.top/Article/details/gttavgwbpg.html

PHP:  random_int(1, 100);
来源：http://dali.zhiwuduotai.top/Article/details/gtfkzryddj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jyoumei.cn/Article/details/gthbvslhnl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.316326.xyz/Article/details/gtlotifqem.html

Java: new Random().nextInt(100) + 1
来源：http://dali.kuanghao11.cn/Article/details/gtcjaealzj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.fzhhl.top/Article/details/gtdtnjqsuf.html

Ruby: rand(1..100)
来源：http://dali.hfpthk.cn/Article/details/gtxukhbruo.html

C#:   new Random().Next(1, 101)
来源：http://dali.sxryk.cn/Article/details/gtmzcwedzw.html

[A11] 条件表达式（三元）
来源：http://dali.wangdashe.top/Article/details/gtvtpuayck.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nanxinkj.top/Article/details/gtyvtzvuap.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gtjjndfmig.html


<!-- 参考信息 -->