代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtbsicjoqu.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuxming.cn/Article/details/gtelrxzpku.html

[U72] PHP：写错误日志
来源：http://dali.zhengqikj.top/Article/details/gtjprwxhyn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.pycfn.com/Article/details/gtrreymyve.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhengqikj.top/Article/details/gtlkdvubra.html

parse_ini_file("config.ini", true)
来源：http://dali.yanxiufei.cn/Article/details/gtouxvnltk.html

[U74] PHP：读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtybeaccie.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yuanzhike.top/Article/details/gtdneogkxl.html

[U75] PHP：依赖注入
来源：http://dali.ydzc1.top/Article/details/gtynuysmeq.html

composer require psr/container
来源：http://dali.gzhubu.top/Article/details/gtbkauzbsn.html

[U76] PHP：简单路由
来源：http://dali.9152youxi.cn/Article/details/gtuththxil.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.9152youxi.cn/Article/details/gtnfwjotzo.html

[U77] PHP：模板渲染
来源：http://dali.chenzaomai.com/Article/details/gtfmrvdbiy.html

composer require twig/twig
来源：http://dali.xuetiantiany.cn/Article/details/gtezkzumfn.html

[U78] PHP：单元测试
来源：http://dali.nwbrower.top/Article/details/gttsrpsozt.html

composer require --dev phpunit/phpunit
来源：http://dali.xinyue.icu/Article/details/gtxqprlvxq.html

[U79] PHP：静态分析
来源：http://dali.ivvv.top/Article/details/gtnhzkbkkd.html

composer require --dev phpstan/phpstan
来源：http://dali.cdnleiting.top/Article/details/gtragfrcak.html

[U80] PHP：代码规范修复
来源：http://dali.cashguo.top/Article/details/gtzibrrwkf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hfpthk.cn/Article/details/gtvfybnfez.html

[U81] JS：初始化项目
来源：http://dali.guannengcc.top/Article/details/gtpefklkoz.html

npm init -y;  npm i express
来源：http://dali.jlsjyb.cn/Article/details/gtbrnhwded.html

[U82] JS：package.json 脚本
来源：http://dali.redwolf501.top/Article/details/gtrnpirgrf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yangfankeji.com/Article/details/gtpavvwcgi.html

[U83] JS：ES Module 导入导出
来源：http://dali.hammf.cn/Article/details/gtdrmosohs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtdnkvuknm.html

[U84] JS：CommonJS 写法
来源：http://dali.svipenyu.cn/Article/details/gtynypgegf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ybcxt.top/Article/details/gtokkzqqsb.html

[U85] JS：可选链
来源：http://dali.jqgufenzy.top/Article/details/gthzxizeyr.html

a?.b?.c
来源：http://dali.hfpthk.cn/Article/details/gtgtodyjbe.html

[U86] JS：空值合并
来源：http://dali.iojbl.cn/Article/details/gtigpzmplf.html

a ?? b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsqumsmn.html

[U87] JS：解构默认值
来源：http://dali.dashuyun.cn/Article/details/gtrcjoolpt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gotoacloud.top/Article/details/gtmdbhzlsu.html

[U88] JS：对象展开合并
来源：http://dali.chenzaomai.com/Article/details/gtedhnrkzf.html

{ ...a, ...b }
来源：http://dali.tanke756.top/Article/details/gtubmurtsc.html

[U89] JS：数组去重
来源：http://dali.birdmap.top/Article/details/gtgzgivuer.html

[...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtsuzuglro.html

[U90] JS：数字数组排序
来源：http://dali.hammf.cn/Article/details/gtznangvpd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtamoozutf.html

[U91] JS：对象键值遍历
来源：http://dali.fengsongda.top/Article/details/gtbvwhwtlw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hongshengwenyu.top/Article/details/gtbeargowl.html

[U92] JS：深拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtnzvjxkxp.html

structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtentumoke.html

[U93] JS：模板字符串
来源：http://dali.hfpthk.cn/Article/details/gtrxlckusn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gtssanhfcp.html

[U94] JS：箭头函数
来源：http://dali.andypj.xyz/Article/details/gtuhaonuem.html

const double = x => x * 2;
来源：http://dali.xinyue.icu/Article/details/gtmmzwhpod.html

[U95] JS：Promise 包装
来源：http://dali.jyoumei.cn/Article/details/gttshytuyu.html

new Promise((resolve, reject) => {})
来源：http://dali.zdqjudy.top/Article/details/gtobdkimxz.html

[U96] JS：async/await 与异常
来源：http://dali.hnxiangtu.top/Article/details/gtxdgdtaea.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtftaqjkei.html

[U97] JS：并发请求
来源：http://dali.shuidangran.top/Article/details/gthtgholyd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtzjrnabsy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzlhoabs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.havefunace.top/Article/details/gtqnwcvpol.html

[U99] JS：事件监听
来源：http://dali.haohaochexian.top/Article/details/gtsiyfdheh.html

el.addEventListener("click", e => {})
来源：http://dali.hongshengwenyu.top/Article/details/gtdipmoucf.html

[U100] JS：DOM 查询
来源：http://dali.hongshengwenyu.top/Article/details/gtmqgtgoqo.html

document.querySelector(".item")
来源：http://dali.sysykeji.top/Article/details/gtlcctnasb.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gtkgfgunnr.html

el.classList.toggle("active")
来源：http://dali.yuanzhike.top/Article/details/gtgaookpzj.html

[U102] JS：本地存储
来源：http://dali.xziqi.cn/Article/details/gtxcibjqoc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gtvppebqep.html

[U103] JS：定时器
来源：http://dali.gogol.net.cn/Article/details/gtisowffys.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ehwqpu.com/Article/details/gtmvigluvd.html

[U104] JS：防抖
来源：http://dali.tanke756.top/Article/details/gtucirepgm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtechdwcag.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtbvscyitq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.kuanghao11.cn/Article/details/gtspyydujh.html

[U106] JS：日期格式化
来源：http://dali.cashguo.top/Article/details/gtitjufpiy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhongyouzk.top/Article/details/gtrywmxxtw.html

[U107] JS：数字千分位
来源：http://dali.cashguo.top/Article/details/gthudjsgmn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtvhdctdfa.html

[U108] JS：随机整数
来源：http://dali.tian-w.cn/Article/details/gtqpqhxbrf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gotoacloud.top/Article/details/gtawsaelwy.html

[U109] JS：数组分组
来源：http://dali.xuanzx.com/Article/details/gtjovhslvw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gtstdhtfvv.html

[U110] JS：数组分块
来源：http://dali.xuetiantiany.cn/Article/details/gtlkdfwhgw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sysykeji.top/Article/details/gtctbyczry.html

[U111] JS：对象转 Map
来源：http://dali.jinqigfzy.top/Article/details/gtxegocsal.html

new Map(Object.entries(obj))
来源：http://dali.quarkkingdee.top/Article/details/gthpuyrweq.html

[U112] JS：字符串补位
来源：http://dali.xinyue.icu/Article/details/gtxlbtkszv.html

"7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtfsflqpdb.html

[U113] JS：正则替换全部
来源：http://dali.chenzaomai.com/Article/details/gttethmazo.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtpjpihidw.html

[U114] JS：JSON 深比较
来源：http://dali.zhiwuduotai.top/Article/details/gtvoyypfxt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtddwovhcl.html

[U115] JS：生成 UUID
来源：http://dali.daxiang520.top/Article/details/gtcamlyjwa.html

crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtiybgmybq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hywenlv.cn/Article/details/gtyzbpnncg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xylfe.cn/Article/details/gtsvohcytb.html

[U117] JS：单元测试
来源：http://dali.zhixingplan.top/Article/details/gtzrqbjhuj.html

npm i -D vitest;  npx vitest
来源：http://dali.cheryme.top/Article/details/gtgsjwdeju.html

[U118] JS：开发服务器
来源：http://dali.yvedp.cn/Article/details/gtjekbgozp.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gtfungfbkf.html

[U119] JS：生产构建
来源：http://dali.yj202588.top/Article/details/gthdokbhge.html

npx vite build
来源：http://dali.pengpengdd.cyou/Article/details/gtamjpzekk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yvedp.cn/Article/details/gtsrcnbkcq.html

import.meta.env.VITE_API_URL
来源：http://dali.daxiang520.top/Article/details/gtlozqhwqu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvwlwsojb.html

统计汇总
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnctrtri.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtriwufydn.html

按语言统计（条）：
来源：http://dali.tanke756.top/Article/details/gtqnekwydw.html

Python ......... 252
来源：http://dali.sweek.top/Article/details/gtmhqwckbm.html

PHP ............ 252
来源：http://dali.snrcjt.cn/Article/details/gtqbmshtfi.html

JavaScript ..... 252
来源：http://dali.tian-w.cn/Article/details/gtdjvqjtik.html

TypeScript ..... 212
来源：http://dali.svipenyu.cn/Article/details/gtenoqaxne.html

Java ........... 212
来源：http://dali.shuidangran.top/Article/details/gttqwycnrg.html

Go ............. 212
来源：http://dali.cucudq.cn/Article/details/gtxrsmwfpz.html

Ruby ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtdnnkczmx.html

C# ............. 212
来源：http://dali.zhiwuduotai.top/Article/details/gtknvwjbiw.html

C .............. 30
来源：http://dali.yangfankeji.com/Article/details/gtjlbhtmrd.html

C++ ............ 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrouncxjl.html

SQL ............ 90
来源：http://dali.yongpay.top/Article/details/gtyteyikra.html

Bash ........... 80
来源：http://dali.hongshengwenyu.top/Article/details/gtsrdpdvqu.html

Kotlin ......... 15
来源：http://dali.sufxvd.cn/Article/details/gtwejfdhyy.html

Swift .......... 15
来源：http://dali.shzxlz.cn/Article/details/gtpprnovvv.html

Lua ............ 10
来源：http://dali.pengpengdd.cyou/Article/details/gtixojhitz.html

Perl ........... 10
来源：http://dali.zhiwuduotai.top/Article/details/gtgebhcscl.html

Scala .......... 10
来源：http://dali.andypj.xyz/Article/details/gtsvbgwuay.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gthllztuew.html

合计 ........... 2106 条
来源：http://dali.cqqwz.cn/Article/details/gtekqyewpp.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtghkfupun.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gtqdvudvax.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sufxvd.cn/Article/details/gtsjilslog.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtqjrkztmy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.daxiang520.top/Article/details/gtajkpawnm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jlsjyb.cn/Article/details/gttzwqleke.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gtwymchiea.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulqpfxxe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xziqi.cn/Article/details/gtvnnsqtlx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtrmtlbeea.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gttwhxgyri.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtmeenihvn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtwmkljyoz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtohfnlmoe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gthkalauak.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ehwqpu.com/Article/details/gtbafzmzyg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtztufdhcc.html

Q SQL 专题                              90
来源：http://dali.xuanzx.com/Article/details/gtpconeowu.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gtctlygpue.html

S C / C++ 专题                          60
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyxcbbgv.html

T 其他语言补充                          60
来源：http://dali.xylfe.cn/Article/details/gtxgqkfqut.html

U 高频实用片段                         120
来源：http://dali.zhongyouzk.top/Article/details/gtwffsyesj.html

------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtoytnrwzu.html

合计                                  2106 条
来源：http://dali.zhoulong.xyz/Article/details/gtxkdxszik.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtwowlfzhw.html

使用提醒
来源：http://dali.feifeiyinyue.top/Article/details/gtixhfnqyg.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtjasfsclx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gogol.net.cn/Article/details/gtowkaigmx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.andypj.xyz/Article/details/gtwnjknepp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.smart0.xyz/Article/details/gtqfuwbwiz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sufxvd.cn/Article/details/gtidfyfgzj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gotoacloud.top/Article/details/gtcanyotdr.html

—— 文件结束 ——
来源：http://dali.nanxuanxn.top/Article/details/gtafsrdnfq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthtvvlcvn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yueranfly.top/Article/details/gtmqoxzcxn.html

Common Programming Examples Cheat Book
来源：http://dali.shangyingyoupin.top/Article/details/gtoljhcbov.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvlxmzctq.html

【收录内容】
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsqggvlh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.316326.xyz/Article/details/gtkhhxmuqo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuxming.cn/Article/details/gthwgwuxkx.html

SQL · Bash · C · C++
来源：http://dali.yongpay.top/Article/details/gtupyhlhtl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ybcxt.top/Article/details/gtrowpcoet.html

【使用说明】
来源：http://dali.gzhubu.top/Article/details/gtklkxacbd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xinyue.icu/Article/details/gtbxuebohm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.aibaodan.cn/Article/details/gtgwlpwovg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guowangkeji.top/Article/details/gtgnxtsryw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gotoacloud.top/Article/details/gtvcljaiof.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.snrcjt.cn/Article/details/gttbfcjqlc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsworufu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cucudq.cn/Article/details/gtfhctsqck.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fengsongda.top/Article/details/gtskwpbvdz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gotoacloud.top/Article/details/gtcjbqwiqb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhongyouzk.top/Article/details/gtpthonsyh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.0kj1m.cn/Article/details/gtyhseaxes.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hnxiangtu.top/Article/details/gtburrqqru.html

【文件统计】
来源：http://dali.chenlongwang.top/Article/details/gtvpwoqnii.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.havefunace.top/Article/details/gtkipjwlme.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtagqhwqck.html

目  录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmlhvqpc.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtaleewwum.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gtdjhbsuzc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gtjawfpczm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gtymqzpvhp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gtjyqfyfvv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zdqjudy.top/Article/details/gtdxrlksqd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinqigfzy.top/Article/details/gtulkweswi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gtsghmvlkj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yuanzhike.top/Article/details/gtnfmtxsyh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtjcinglhv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gtedgalvzm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtbljnhzdo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtqbxtxubg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtorxbkztj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.andypj.xyz/Article/details/gttxixqzxe.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hongshengwenyu.top/Article/details/gteqemgeag.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtqiiypuqu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.guannengcc.top/Article/details/gtctnwopuo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinqigufen.top/Article/details/gtnmkpykxp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj20258888.top/Article/details/gtbsaohmpj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gtlzknsmnd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj202588.top/Article/details/gtcpryqcmk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqaacvjch.html

A. 基础语法与类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiijwwdbg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtmqjncqpq.html

[A01] Hello World
来源：http://dali.aizwys.cn/Article/details/gtletudkxr.html

Py:   print("Hello, World!")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabxputtz.html

PHP:  echo "Hello, World!";
来源：http://dali.fzhhl.top/Article/details/gtjsggqsur.html

JS:   console.log("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtmsaklmiu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwlkoknc.html

Java: System.out.println("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtkcalijwd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gtczchfrza.html

Ruby: puts "Hello, World!"
来源：http://dali.c1oappe.top/Article/details/gtdirzxghf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gtyelujlxu.html

[A02] 变量声明与赋值
来源：http://dali.sxryk.cn/Article/details/gtmyxslajb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ppjwa.cn/Article/details/gtlcwroqsx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gttbsmzxze.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtuoifkdpd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.mhx1999.top/Article/details/gtdtsculrj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.guannengcc.top/Article/details/gtrxkpayst.html

Go:   name := "Alex"; age := 20
来源：http://dali.hysaishi.cn/Article/details/gtgwxvpsgr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jqgufenzy.top/Article/details/gtgdjsizvd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cashguo.top/Article/details/gtgtxoheft.html

[A03] 常量定义
来源：http://dali.sxryk.cn/Article/details/gtycvizunt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuxming.cn/Article/details/gtunmfrqjj.html

PHP:  const PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtyrimlhgj.html

JS:   const PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtcrvjjagy.html

TS:   const PI: number = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtagiotgqh.html

Java: static final double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtmfikqsbg.html

Go:   const PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gtjcqubnaf.html

Ruby: PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gtcyqmdpix.html

C#:   const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtqjigovcg.html

[A04] 判断变量类型
来源：http://dali.tian-w.cn/Article/details/gtqkaajjyl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shangyingyoupin.top/Article/details/gtfzouhlxr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.wangshuangyany.cn/Article/details/gtcgtrzowd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.fengsongda.top/Article/details/gtmpawqqss.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigfzy.top/Article/details/gtzqyzgbty.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nwbrower.top/Article/details/gtdzkviadd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yuxming.cn/Article/details/gtemsiqrop.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.dashuyun.cn/Article/details/gtububazfg.html

C#:   x.GetType().Name; x is int
来源：http://dali.sweek.top/Article/details/gtrxudnzqs.html

[A05] 整数除法与取模
来源：http://dali.yongpay.top/Article/details/gtzjiuxzlj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gttztmyhoi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtqiabehoa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtinsynnsx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwsyrkac.html

Java: 7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtazlzdhpb.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtdeeyvtsw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtfqjbwlab.html

C#:   7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtpfoyqerk.html

[A06] 字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gttkeohfgp.html

Py:   int("42"); float("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gtjxrdhfou.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.c1oappe.top/Article/details/gtzordvzhq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jyoumei.cn/Article/details/gtlusimnbg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sysykeji.top/Article/details/gthayfxzdg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aibaodan.cn/Article/details/gthscmzcsg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yueranfly.top/Article/details/gtuumickmx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.fengsongda.top/Article/details/gtraopkooq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxinkj.top/Article/details/gtonahpakz.html

[A07] 数字转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtmgelrqse.html

Py:   str(42)
来源：http://dali.yangfankeji.com/Article/details/gtkrdjqioa.html

PHP:  (string) 42; strval(42)
来源：http://dali.shuidangran.top/Article/details/gttshlotlr.html

JS:   String(42); (42).toString()
来源：http://dali.iojbl.cn/Article/details/gtrrqmtqcd.html

TS:   String(42)
来源：http://dali.jlsjyb.cn/Article/details/gtsecjukym.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dianchejie.cn/Article/details/gtrxpgjxnq.html

Go:   strconv.Itoa(42)
来源：http://dali.0kj1m.cn/Article/details/gtbqkqzoff.html

Ruby: 42.to_s
来源：http://dali.9152youxi.cn/Article/details/gtlgbzslak.html

C#:   42.ToString()
来源：http://dali.birdmap.top/Article/details/gtwuchmtov.html

[A08] 取整与四舍五入
来源：http://dali.hnqzz.top/Article/details/gtvamtnnwl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtxludtqer.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gzhubu.top/Article/details/gtmxeuanav.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gthplavgwp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.pengpengdd.cyou/Article/details/gtopdzwrmg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gtplgggyfr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gttjwvcsga.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.316326.xyz/Article/details/gtrsnbwglw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gtvvjuwfic.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtxnlswfrf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtzioskeuh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtyfmvyyae.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.316326.xyz/Article/details/gtaemysgae.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtgfwtkryg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtwnvsthza.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.chenzaomai.com/Article/details/gteofvjiix.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxdzzbpi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtmztplpod.html

[A10] 生成随机数
来源：http://dali.cucudq.cn/Article/details/gtqrttwvav.html

Py:   import random; random.randint(1, 100)
来源：http://dali.nanxuanxn.top/Article/details/gtkcnnqaol.html

PHP:  random_int(1, 100);
来源：http://dali.yueranfly.top/Article/details/gtqnqzjoia.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxinkj.top/Article/details/gtfxmxfthk.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xinyue.icu/Article/details/gtedaanzyf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258888.top/Article/details/gtqcksfwvb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.daxiang520.top/Article/details/gtvnqhvxlf.html

Ruby: rand(1..100)
来源：http://dali.xuetiantiany.cn/Article/details/gtspevpgxv.html

C#:   new Random().Next(1, 101)
来源：http://dali.redwolf501.top/Article/details/gtngkdncmt.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gtwxpxykeh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlkjjcsh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gtwvuzcrvm.html


<!-- 参考信息 -->