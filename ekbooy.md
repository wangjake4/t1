代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.yvedp.cn/Article/details/gtmiqypcon.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuxming.cn/Article/details/gtvsobytuj.html

[U72] PHP：写错误日志
来源：http://dali.ydzc1.top/Article/details/gtpvptijap.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhongyouzk.top/Article/details/gtpeqzqljx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zdqjudy.top/Article/details/gtjxkatzdn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhengqikj.top/Article/details/gtpniaxmra.html

[U74] PHP：读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtllprxynh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jiagoushi.top/Article/details/gtgzmdcbsy.html

[U75] PHP：依赖注入
来源：http://dali.mhx1999.top/Article/details/gtticouthp.html

composer require psr/container
来源：http://dali.chenzaomai.com/Article/details/gtlcdwrrru.html

[U76] PHP：简单路由
来源：http://dali.vqdsnc.cn/Article/details/gtyqicmyfj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhongyouzk.top/Article/details/gtrjbnaqps.html

[U77] PHP：模板渲染
来源：http://dali.dashuyun.cn/Article/details/gtiaxrrhfu.html

composer require twig/twig
来源：http://dali.jyoumei.cn/Article/details/gtxlzdqzqb.html

[U78] PHP：单元测试
来源：http://dali.sufxvd.cn/Article/details/gtygmuuphg.html

composer require --dev phpunit/phpunit
来源：http://dali.0kj1m.cn/Article/details/gtsgvdlwyw.html

[U79] PHP：静态分析
来源：http://dali.xuetiantiany.cn/Article/details/gtdzmscsqe.html

composer require --dev phpstan/phpstan
来源：http://dali.jqgfzy.top/Article/details/gtlpftyzwu.html

[U80] PHP：代码规范修复
来源：http://dali.zhengqikj.top/Article/details/gtnsiyvvcu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gtllwuswtx.html

[U81] JS：初始化项目
来源：http://dali.zhixingplan.top/Article/details/gtvvujbrlo.html

npm init -y;  npm i express
来源：http://dali.316326.xyz/Article/details/gttykdjenz.html

[U82] JS：package.json 脚本
来源：http://dali.gogol.net.cn/Article/details/gtoehpmmuv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.wangshuangyany.cn/Article/details/gtizsksnfv.html

[U83] JS：ES Module 导入导出
来源：http://dali.yj20258888.top/Article/details/gtngtkifey.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shanyushiyangtech.top/Article/details/gthqhnjkkz.html

[U84] JS：CommonJS 写法
来源：http://dali.cucudq.cn/Article/details/gtxilykalg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.kuanghao11.cn/Article/details/gtzpegqpzj.html

[U85] JS：可选链
来源：http://dali.iojbl.cn/Article/details/gtghgngjcg.html

a?.b?.c
来源：http://dali.fzhhl.top/Article/details/gtcywhuhrg.html

[U86] JS：空值合并
来源：http://dali.guowangkeji.top/Article/details/gteqzndham.html

a ?? b
来源：http://dali.yanxiufei.cn/Article/details/gtoaumjnms.html

[U87] JS：解构默认值
来源：http://dali.nwbrower.top/Article/details/gtcluewwuu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnxiangtu.top/Article/details/gtazepiidq.html

[U88] JS：对象展开合并
来源：http://dali.sufxvd.cn/Article/details/gttwopkusy.html

{ ...a, ...b }
来源：http://dali.chenzaomai.com/Article/details/gtnecfsjxo.html

[U89] JS：数组去重
来源：http://dali.wangdashe.top/Article/details/gtybqpkzwx.html

[...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtxzracfbh.html

[U90] JS：数字数组排序
来源：http://dali.mhx1999.top/Article/details/gthboywnle.html

[...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtkyttcmbx.html

[U91] JS：对象键值遍历
来源：http://dali.jiagoushi.top/Article/details/gtpdhrcbcw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhongyouzk.top/Article/details/gtapfkmali.html

[U92] JS：深拷贝
来源：http://dali.haohaochexian.top/Article/details/gtnmizuqlb.html

structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtftdfepfi.html

[U93] JS：模板字符串
来源：http://dali.daria6918.cn/Article/details/gtgqpzodah.html

`共 ${n} 条`
来源：http://dali.gzhubu.top/Article/details/gtvtdgvwnn.html

[U94] JS：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gtzlsgscah.html

const double = x => x * 2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpznbken.html

[U95] JS：Promise 包装
来源：http://dali.aibaodan.cn/Article/details/gtmyrnksqi.html

new Promise((resolve, reject) => {})
来源：http://dali.meibo888.top/Article/details/gtrvpndrfx.html

[U96] JS：async/await 与异常
来源：http://dali.chenzaomai.com/Article/details/gtxvfrbgdk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrxnnmlsl.html

[U97] JS：并发请求
来源：http://dali.havefunace.top/Article/details/gtqxkyjneq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtjwbtqedq.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj202588.top/Article/details/gtqdwkzmjk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gogol.net.cn/Article/details/gtvhwzwflu.html

[U99] JS：事件监听
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebwdbeiv.html

el.addEventListener("click", e => {})
来源：http://dali.ppjwa.cn/Article/details/gtoptyaezh.html

[U100] JS：DOM 查询
来源：http://dali.tian-w.cn/Article/details/gtkrqshvkz.html

document.querySelector(".item")
来源：http://dali.fengsongda.top/Article/details/gttpnfhfqp.html

[U101] JS：classList 操作
来源：http://dali.mhx1999.top/Article/details/gtlfqzgalv.html

el.classList.toggle("active")
来源：http://dali.ivvv.top/Article/details/gtfyerraqg.html

[U102] JS：本地存储
来源：http://dali.hywenlv.cn/Article/details/gtvvcnqjuo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbwjtmrn.html

[U103] JS：定时器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojhzzbjb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nwbrower.top/Article/details/gtdbugzkff.html

[U104] JS：防抖
来源：http://dali.gaohongyu789.top/Article/details/gtrfxdtkut.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtwtnbgtop.html

[U105] JS：节流
来源：http://dali.jiagoushi.top/Article/details/gttrdkjrky.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xziqi.cn/Article/details/gtpawrfcbi.html

[U106] JS：日期格式化
来源：http://dali.redwolf501.top/Article/details/gtcohxshzk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj20258.top/Article/details/gtxmhirlio.html

[U107] JS：数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gteahtwino.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.mhx1999.top/Article/details/gtminxytlz.html

[U108] JS：随机整数
来源：http://dali.jyoumei.cn/Article/details/gtfrdlwtad.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sweek.top/Article/details/gtsifusjlp.html

[U109] JS：数组分组
来源：http://dali.guannengcc.top/Article/details/gthchgzewv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtxjgxgard.html

[U110] JS：数组分块
来源：http://dali.zhongyouzk.top/Article/details/gtjttkosvq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.haohaochexian.top/Article/details/gteqpfqtjq.html

[U111] JS：对象转 Map
来源：http://dali.316326.xyz/Article/details/gtcxbjjsze.html

new Map(Object.entries(obj))
来源：http://dali.zhixingplan.top/Article/details/gtorhpujkj.html

[U112] JS：字符串补位
来源：http://dali.pycfn.com/Article/details/gtxxyovoop.html

"7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtgznifucx.html

[U113] JS：正则替换全部
来源：http://dali.wangdashe.top/Article/details/gtibnfnxaa.html

s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtyxatkzrz.html

[U114] JS：JSON 深比较
来源：http://dali.tian-w.cn/Article/details/gtjxdocxyk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gtbcirhpfe.html

[U115] JS：生成 UUID
来源：http://dali.meibo888.top/Article/details/gtrvzrjneh.html

crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtncglrpwl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guowangkeji.top/Article/details/gtzrvfqwut.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fengsongda.top/Article/details/gtjsjdrhju.html

[U117] JS：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtyylrnklm.html

npm i -D vitest;  npx vitest
来源：http://dali.hammf.cn/Article/details/gtuqltxqlm.html

[U118] JS：开发服务器
来源：http://dali.dianchejie.cn/Article/details/gtsfqtnqaj.html

npm i -D vite;  npx vite
来源：http://dali.nanxuanxn.top/Article/details/gtuhgkvwcv.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gthwqctmkd.html

npx vite build
来源：http://dali.yj20258.top/Article/details/gtwrrscpkx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenlongwang.top/Article/details/gtktyxsckk.html

import.meta.env.VITE_API_URL
来源：http://dali.cqqwz.cn/Article/details/gtwunhrtwo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtzdnjooio.html

统计汇总
来源：http://dali.yanxiufei.cn/Article/details/gtchgwvbno.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwvuxxelp.html

按语言统计（条）：
来源：http://dali.tanke756.top/Article/details/gtzrbnebim.html

Python ......... 252
来源：http://dali.cheryme.top/Article/details/gtopgwjlnp.html

PHP ............ 252
来源：http://dali.sysykeji.top/Article/details/gtozlokyvb.html

JavaScript ..... 252
来源：http://dali.nanxinkj.top/Article/details/gtzloxqkaz.html

TypeScript ..... 212
来源：http://dali.yj202588.top/Article/details/gtkrjieuve.html

Java ........... 212
来源：http://dali.redwolf501.top/Article/details/gtuwwgjvbr.html

Go ............. 212
来源：http://dali.nanxinkj.top/Article/details/gtnlfyynni.html

Ruby ........... 212
来源：http://dali.shzxlz.cn/Article/details/gtjhsmohll.html

C# ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtogchzgyl.html

C .............. 30
来源：http://dali.bjfxy.top/Article/details/gtddvcppci.html

C++ ............ 30
来源：http://dali.yvedp.cn/Article/details/gtxyxncdoy.html

SQL ............ 90
来源：http://dali.316326.xyz/Article/details/gtkjbjtkyo.html

Bash ........... 80
来源：http://dali.gogol.net.cn/Article/details/gtkymggabr.html

Kotlin ......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gtpmtsdfsw.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gtclnyoajz.html

Lua ............ 10
来源：http://dali.hywenlv.cn/Article/details/gtzxquqixz.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gtfphlyrba.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gtyoqazcxm.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtsxhvbtlb.html

合计 ........... 2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gtbfqxydzm.html

按章节统计：
来源：http://dali.yj20258888.top/Article/details/gtdhxldcki.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gtuglmrlca.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gtaooocfxn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtjhjsaoya.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gtdfrkryrl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258.top/Article/details/gtqnzoclzs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shuidangran.top/Article/details/gtucusrens.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gtjvplzmhk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.vqdsnc.cn/Article/details/gtacdwisdq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtwihcjrrd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gtgfxmvccq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtjxkstcnu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtzhjcwtjo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtfhzuqqdd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gtcxeoxkhc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangtech.top/Article/details/gtqoupcbuz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtllrwkymp.html

Q SQL 专题                              90
来源：http://dali.ydzc1.top/Article/details/gtwqbibzzq.html

R Bash 专题                             80
来源：http://dali.tianlin.xyz/Article/details/gtldworvwc.html

S C / C++ 专题                          60
来源：http://dali.haohaochexian.top/Article/details/gtkhdarfkj.html

T 其他语言补充                          60
来源：http://dali.sufxvd.cn/Article/details/gtuakuyefv.html

U 高频实用片段                         120
来源：http://dali.yj20258888.top/Article/details/gtjuihmtux.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gtmdpvgsfp.html

合计                                  2106 条
来源：http://dali.aibaodan.cn/Article/details/gtniqzhnap.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtvjmljwto.html

使用提醒
来源：http://dali.yj20258888.top/Article/details/gtudmycxjk.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtonyhejvj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ehwqpu.com/Article/details/gtdjdbrtgy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcckchfs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudstdpsy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ppjwa.cn/Article/details/gtbrqnqckm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.andypj.xyz/Article/details/gtntoqlhqx.html

—— 文件结束 ——
来源：http://dali.zhengqikj.top/Article/details/gtznibrzly.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcnflphmb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ydzc1.top/Article/details/gtprskwzcf.html

Common Programming Examples Cheat Book
来源：http://dali.sysykeji.top/Article/details/gtsptmwxhi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkzuvdqs.html

【收录内容】
来源：http://dali.daxiang520.top/Article/details/gtnaxnqime.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hongshengwenyu.top/Article/details/gtbkrkwvha.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuanzhike.top/Article/details/gthtgcvgba.html

SQL · Bash · C · C++
来源：http://dali.shanyushiyangtech.top/Article/details/gtykdnlxgz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhixingplan.top/Article/details/gttveapmci.html

【使用说明】
来源：http://dali.jyoumei.cn/Article/details/gtksyafadb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shzxlz.cn/Article/details/gtzfoqjfgs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxiasnpaf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.birdmap.top/Article/details/gtvhjfjmyu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhoulong.xyz/Article/details/gtcbfweirs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvjvveev.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenzaomai.com/Article/details/gtodsybzyu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gotoacloud.top/Article/details/gtgzqjhdij.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhiwuduotai.top/Article/details/gtpllvpzqi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhongyouzk.top/Article/details/gtklcxdbbk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenjidiqi.icu/Article/details/gtfogkshca.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sysykeji.top/Article/details/gtwkqgfcnf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yuxming.cn/Article/details/gttfixdkxn.html

【文件统计】
来源：http://dali.kuanghao11.cn/Article/details/gtivaixmyg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cdnleiting.top/Article/details/gtfytskfnb.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtiytotrzs.html

目  录
来源：http://dali.sxryk.cn/Article/details/gtxzalujup.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtzadyleat.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.smart0.xyz/Article/details/gtsnzgxhkd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fengsongda.top/Article/details/gtkudyeill.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gtvmjxrfoe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yuanzhike.top/Article/details/gtwzxrfudn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxuanxn.top/Article/details/gtkmlwhkhl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.quarkkingdee.top/Article/details/gtaawlxghu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ppjwa.cn/Article/details/gtuklcbcbn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gttwdlqhvi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtwilsozay.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtjsrqnrzk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtcgzqypyy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gtkhbcfnmb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gttmfglwlo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.andypj.xyz/Article/details/gtpkkfqnhl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj20258888.top/Article/details/gtsihdsmcl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtwtpcxyyr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuanzhike.top/Article/details/gtllxwypnf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsndlcyh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.snrcjt.cn/Article/details/gtaxdoehmj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daxiang520.top/Article/details/gtgzchottx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gtqtgyxhbe.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtmjassmwb.html

A. 基础语法与类型
来源：http://dali.jiagoushi.top/Article/details/gtobtwblcg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmrzoclkd.html

[A01] Hello World
来源：http://dali.ybcxt.top/Article/details/gtpzdsgxmo.html

Py:   print("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrvmfnhv.html

PHP:  echo "Hello, World!";
来源：http://dali.gzhubu.top/Article/details/gthwdxwndg.html

JS:   console.log("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gtcsruuvtd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258888.top/Article/details/gtggnkagyr.html

Java: System.out.println("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gtvjllddcw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gthsharxtv.html

Ruby: puts "Hello, World!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybryroik.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtzsygqces.html

[A02] 变量声明与赋值
来源：http://dali.xziqi.cn/Article/details/gtppirbxra.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhixingplan.top/Article/details/gtpbvwglto.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.havefunace.top/Article/details/gtsjtfpwtf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ybcxt.top/Article/details/gttgqoesdz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtopryiifx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gthdqdwnaz.html

Go:   name := "Alex"; age := 20
来源：http://dali.daria6918.cn/Article/details/gtuubfcgze.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yueranfly.top/Article/details/gtmopffqjj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtlsbqemwi.html

[A03] 常量定义
来源：http://dali.yvedp.cn/Article/details/gteagdkkkn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenlongwang.top/Article/details/gteqhcrlnd.html

PHP:  const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtsqdmfbcu.html

JS:   const PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gthuvxutcu.html

TS:   const PI: number = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtnosafvnk.html

Java: static final double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtxmcjyers.html

Go:   const PI = 3.14159
来源：http://dali.yongpay.top/Article/details/gtvvodjazy.html

Ruby: PI = 3.14159
来源：http://dali.ivvv.top/Article/details/gtcrxdoyls.html

C#:   const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtrmdyabtd.html

[A04] 判断变量类型
来源：http://dali.xylfe.cn/Article/details/gtzeexfuml.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tanke756.top/Article/details/gtootkovnp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xuetiantiany.cn/Article/details/gtxuzfysqu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gtapirmonz.html

TS:   typeof x; x instanceof Date
来源：http://dali.ydzc1.top/Article/details/gtljbacttm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinxjccna.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.birdmap.top/Article/details/gtvpxyfuvu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cheryme.top/Article/details/gtztpzesxg.html

C#:   x.GetType().Name; x is int
来源：http://dali.birdmap.top/Article/details/gtrdzgofei.html

[A05] 整数除法与取模
来源：http://dali.0kj1m.cn/Article/details/gtlgeqlcto.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.pycfn.com/Article/details/gtkawhkuwp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtzdryfjxr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtvapavujh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtiutlbtig.html

Java: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqngmkwq.html

Go:   7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtavhuperf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtnrzpdgfz.html

C#:   7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gtjjkoiuup.html

[A06] 字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gtjydwswnx.html

Py:   int("42"); float("3.14")
来源：http://dali.smart0.xyz/Article/details/gthhlarmax.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cdnleiting.top/Article/details/gthmvkadbp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj20258888.top/Article/details/gtyulvmmhw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.iojbl.cn/Article/details/gtfajhaqny.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xylfe.cn/Article/details/gtalirlfck.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuoghitc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yangfankeji.com/Article/details/gtwuymxqjj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.andypj.xyz/Article/details/gtrukmnvie.html

[A07] 数字转字符串
来源：http://dali.birdmap.top/Article/details/gtacwpwjuq.html

Py:   str(42)
来源：http://dali.cashguo.top/Article/details/gtlcmzznmt.html

PHP:  (string) 42; strval(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghwthqog.html

JS:   String(42); (42).toString()
来源：http://dali.zhengqikj.top/Article/details/gtrswyyswp.html

TS:   String(42)
来源：http://dali.nanxinkj.top/Article/details/gtryngnruu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenlongwang.top/Article/details/gtxspxgeqx.html

Go:   strconv.Itoa(42)
来源：http://dali.andypj.xyz/Article/details/gtleeozehm.html

Ruby: 42.to_s
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmwqpnbw.html

C#:   42.ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydcpacnz.html

[A08] 取整与四舍五入
来源：http://dali.chenlongwang.top/Article/details/gtjgqfonzk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtkbmqgpuo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.smart0.xyz/Article/details/gtiinyfsfu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtpwbdcjmh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmuzegct.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtmugmqycq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gthzhxdmzl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdqgbyja.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtoqeqhzdw.html

[A09] 绝对值与最大最小值
来源：http://dali.guowangkeji.top/Article/details/gtoudlnppm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258.top/Article/details/gtcprkmcib.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtinakurps.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtwbdceqal.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtvvofnbkl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yongpay.top/Article/details/gtyfgcixkh.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dashuyun.cn/Article/details/gtjzlnqpeb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ybcxt.top/Article/details/gtwpbsgjbp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gteqhypppe.html

[A10] 生成随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtwuracbff.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpuebsvj.html

PHP:  random_int(1, 100);
来源：http://dali.wangshuangyany.cn/Article/details/gtixkcauiv.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aibaodan.cn/Article/details/gtdzjatnzx.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jlsjyb.cn/Article/details/gtrlejcupu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.fzhhl.top/Article/details/gtogpysgxs.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yueranfly.top/Article/details/gtlhffsyie.html

Ruby: rand(1..100)
来源：http://dali.pycfn.com/Article/details/gtbomevcpg.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinghuilouyu.cn/Article/details/gtatgyfzuw.html

[A11] 条件表达式（三元）
来源：http://dali.havefunace.top/Article/details/gtgokcpbuk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.daxiang520.top/Article/details/gtohavzkxx.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtoorvbzlv.html


<!-- 参考信息 -->