代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.shuidangran.top/Article/details/gtxbqhyjyr.html

parse_ini_file("config.ini", true)
来源：http://dali.ybcxt.top/Article/details/gtulwtetki.html

[U74] PHP：读取环境变量
来源：http://dali.cheryme.top/Article/details/gtiasjzotb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hfpthk.cn/Article/details/gtswrmixvf.html

[U75] PHP：依赖注入
来源：http://dali.iojbl.cn/Article/details/gtiaakqhxt.html

composer require psr/container
来源：http://dali.yj202588.top/Article/details/gtszmdbtkp.html

[U76] PHP：简单路由
来源：http://dali.mhx1999.top/Article/details/gtosjakzvv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhengqikj.top/Article/details/gtrpqanivn.html

[U77] PHP：模板渲染
来源：http://dali.yueranfly.top/Article/details/gtjpdkdpmc.html

composer require twig/twig
来源：http://dali.guannengcc.top/Article/details/gtigdrwpwq.html

[U78] PHP：单元测试
来源：http://dali.jqgfzy.top/Article/details/gtgrxgtryg.html

composer require --dev phpunit/phpunit
来源：http://dali.meibo888.top/Article/details/gtlvwesjli.html

[U79] PHP：静态分析
来源：http://dali.guannengcc.top/Article/details/gteeavycep.html

composer require --dev phpstan/phpstan
来源：http://dali.chenjidiqi.icu/Article/details/gtqbochkfm.html

[U80] PHP：代码规范修复
来源：http://dali.wangshuangyany.cn/Article/details/gtfgncyyqy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jianghu66.top/Article/details/gtrgosrlay.html

[U81] JS：初始化项目
来源：http://dali.sweek.top/Article/details/gtqrhtsouc.html

npm init -y;  npm i express
来源：http://dali.zdqjudy.top/Article/details/gtdsrofsww.html

[U82] JS：package.json 脚本
来源：http://dali.quarkkingdee.top/Article/details/gtwlpuuhtb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nwbrower.top/Article/details/gtvkfqsmxc.html

[U83] JS：ES Module 导入导出
来源：http://dali.gzhubu.top/Article/details/gtjzubcoue.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gtxchcblct.html

[U84] JS：CommonJS 写法
来源：http://dali.ppjwa.cn/Article/details/gtvcpcycrg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.316326.xyz/Article/details/gtrkubynrl.html

[U85] JS：可选链
来源：http://dali.chenjidiqi.icu/Article/details/gtbfksmxja.html

a?.b?.c
来源：http://dali.nanxuanxn.top/Article/details/gtrpmxgrzj.html

[U86] JS：空值合并
来源：http://dali.hnxiangtu.top/Article/details/gtggzpidzy.html

a ?? b
来源：http://dali.aibaodan.cn/Article/details/gtzxvavtll.html

[U87] JS：解构默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwaguqgc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.birdmap.top/Article/details/gtdhnxgteo.html

[U88] JS：对象展开合并
来源：http://dali.sxryk.cn/Article/details/gtngptgdal.html

{ ...a, ...b }
来源：http://dali.daxiang520.top/Article/details/gtqeswljum.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnhxbtrt.html

[...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtivjautci.html

[U90] JS：数字数组排序
来源：http://dali.ppjwa.cn/Article/details/gtztjxwggc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtrbdyrzfv.html

[U91] JS：对象键值遍历
来源：http://dali.kuanghao11.cn/Article/details/gtiadvobhf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tanke756.top/Article/details/gteeiwqaay.html

[U92] JS：深拷贝
来源：http://dali.zhixingplan.top/Article/details/gtjtjpohyc.html

structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtjthagufc.html

[U93] JS：模板字符串
来源：http://dali.chenlongwang.top/Article/details/gtalevnoeh.html

`共 ${n} 条`
来源：http://dali.daxiang520.top/Article/details/gtduqckipb.html

[U94] JS：箭头函数
来源：http://dali.chenjidiqi.icu/Article/details/gtuzlwcltr.html

const double = x => x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtcihmvbsc.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrrezzqz.html

new Promise((resolve, reject) => {})
来源：http://dali.hnxiangtu.top/Article/details/gtptcelnnv.html

[U96] JS：async/await 与异常
来源：http://dali.zhixingplan.top/Article/details/gtwhykkuee.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtsqcixfck.html

[U97] JS：并发请求
来源：http://dali.havefunace.top/Article/details/gtuugshins.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtdoypibcn.html

[U98] JS：fetch 带 JSON
来源：http://dali.redwolf501.top/Article/details/gtyckeyjqg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.c1oappe.top/Article/details/gtznrkpakc.html

[U99] JS：事件监听
来源：http://dali.redwolf501.top/Article/details/gtvwkrpqsv.html

el.addEventListener("click", e => {})
来源：http://dali.nwbrower.top/Article/details/gtbxgmfpfc.html

[U100] JS：DOM 查询
来源：http://dali.tanke756.top/Article/details/gtcqliwdqt.html

document.querySelector(".item")
来源：http://dali.yonumen.top/Article/details/gtorgwhpva.html

[U101] JS：classList 操作
来源：http://dali.ehwqpu.com/Article/details/gtescdrotz.html

el.classList.toggle("active")
来源：http://dali.ppjwa.cn/Article/details/gtrupcqwhy.html

[U102] JS：本地存储
来源：http://dali.ybcxt.top/Article/details/gtdsmrpxce.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hongshengwenyu.top/Article/details/gtjhprkdzi.html

[U103] JS：定时器
来源：http://dali.jiagoushi.top/Article/details/gtrxpjxhyb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqucdzicw.html

[U104] JS：防抖
来源：http://dali.yuxming.cn/Article/details/gtnioeldgo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtzcoggiva.html

[U105] JS：节流
来源：http://dali.pycfn.com/Article/details/gtvtarzorh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtpckvabjz.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gtzigceqyz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dashuyun.cn/Article/details/gthplcadnj.html

[U107] JS：数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gtgyynopen.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtinifmhfq.html

[U108] JS：随机整数
来源：http://dali.cucudq.cn/Article/details/gtjolznnir.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gtdrdwonne.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gttvcyikpn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gtoocdxrsf.html

[U110] JS：数组分块
来源：http://dali.chenjidiqi.icu/Article/details/gtshnfyjga.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daxiang520.top/Article/details/gtnbrzgzcf.html

[U111] JS：对象转 Map
来源：http://dali.birdmap.top/Article/details/gtivvcpfhw.html

new Map(Object.entries(obj))
来源：http://dali.sxryk.cn/Article/details/gtvhjnvkju.html

[U112] JS：字符串补位
来源：http://dali.sxryk.cn/Article/details/gtmrxtlpzs.html

"7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtokqiwbvl.html

[U113] JS：正则替换全部
来源：http://dali.yj20258888.top/Article/details/gtoxspzdqv.html

s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtrkfobrtv.html

[U114] JS：JSON 深比较
来源：http://dali.haohaochexian.top/Article/details/gtzwggcquk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gttabkyfsg.html

[U115] JS：生成 UUID
来源：http://dali.316326.xyz/Article/details/gtwhhkvmyn.html

crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtfnzolcog.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yangfankeji.com/Article/details/gtmuidwsls.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfgqxsgvj.html

[U117] JS：单元测试
来源：http://dali.gzhubu.top/Article/details/gtmjlmrvny.html

npm i -D vitest;  npx vitest
来源：http://dali.jlsjyb.cn/Article/details/gtncvyghwj.html

[U118] JS：开发服务器
来源：http://dali.xinyue.icu/Article/details/gtxdizssjx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gtfalebitd.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangtech.top/Article/details/gtuufgsoxs.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gtobkpvfqi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258888.top/Article/details/gtxzlrmxme.html

import.meta.env.VITE_API_URL
来源：http://dali.shangyingyoupin.top/Article/details/gtmlvvmuff.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgzbbyls.html

统计汇总
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxishmym.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwudttqdy.html

按语言统计（条）：
来源：http://dali.gogol.net.cn/Article/details/gtfgcwmqjp.html

Python ......... 252
来源：http://dali.sxryk.cn/Article/details/gtaevgaytw.html

PHP ............ 252
来源：http://dali.shangyingyoupin.top/Article/details/gtapfqpivg.html

JavaScript ..... 252
来源：http://dali.ydzc1.top/Article/details/gtdlfhdkla.html

TypeScript ..... 212
来源：http://dali.vqdsnc.cn/Article/details/gtwhjoqtlg.html

Java ........... 212
来源：http://dali.yuxming.cn/Article/details/gtvfpdtfha.html

Go ............. 212
来源：http://dali.meibo888.top/Article/details/gtgpwrhkpz.html

Ruby ........... 212
来源：http://dali.jinqigfzy.top/Article/details/gtqxvsvayt.html

C# ............. 212
来源：http://dali.daxiang520.top/Article/details/gthkdoaiah.html

C .............. 30
来源：http://dali.iojbl.cn/Article/details/gtxytwfmxr.html

C++ ............ 30
来源：http://dali.316326.xyz/Article/details/gtcvwojpbe.html

SQL ............ 90
来源：http://dali.cashguo.top/Article/details/gtlrvhkmdd.html

Bash ........... 80
来源：http://dali.9152youxi.cn/Article/details/gtspyssdkc.html

Kotlin ......... 15
来源：http://dali.fzhhl.top/Article/details/gthdlatjgt.html

Swift .......... 15
来源：http://dali.haohaochexian.top/Article/details/gtwzvigakd.html

Lua ............ 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuyhbhba.html

Perl ........... 10
来源：http://dali.yj20258.top/Article/details/gtzutcvruw.html

Scala .......... 10
来源：http://dali.0kj1m.cn/Article/details/gtsngielqt.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtlshfxqcf.html

合计 ........... 2106 条
来源：http://dali.yuanzhike.top/Article/details/gtyqizutkq.html

按章节统计：
来源：http://dali.aizwys.cn/Article/details/gtmsadoyzt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gtfglufchj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbgauxcg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtnhdxapkv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gthmzkjenc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shangyingyoupin.top/Article/details/gtiljohdbq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvcqhhnw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gthndgzpti.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhhazmhg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtzzhimzsw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dashuyun.cn/Article/details/gtqxysospb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtzgkqxrsz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtqvipnayw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtgijpyels.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gtmbkvooac.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxinkj.top/Article/details/gtsopipavj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfqcfkgw.html

Q SQL 专题                              90
来源：http://dali.c1oappe.top/Article/details/gtghvgucyh.html

R Bash 专题                             80
来源：http://dali.cucudq.cn/Article/details/gtywimsaur.html

S C / C++ 专题                          60
来源：http://dali.pycfn.com/Article/details/gtbdgyljlb.html

T 其他语言补充                          60
来源：http://dali.birdmap.top/Article/details/gtykrsostv.html

U 高频实用片段                         120
来源：http://dali.ehwqpu.com/Article/details/gtmsusyvxp.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtwfbszbxm.html

合计                                  2106 条
来源：http://dali.jiagoushi.top/Article/details/gtwkwzzjwl.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtdlujskuy.html

使用提醒
来源：http://dali.chenzaomai.com/Article/details/gtehaxtebj.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnbaewvk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgqfvkye.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tian-w.cn/Article/details/gtrkoigpvp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhixingplan.top/Article/details/gtzlipccfx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.kuanghao11.cn/Article/details/gtmojfeoug.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuanzhike.top/Article/details/gtqsollpsn.html

—— 文件结束 ——
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamewedbu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtraqklzxo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.dashuyun.cn/Article/details/gtzbsgwniw.html

Common Programming Examples Cheat Book
来源：http://dali.yanxiufei.cn/Article/details/gtucsbtuql.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgydfcdir.html

【收录内容】
来源：http://dali.guowangkeji.top/Article/details/gtvhoecokr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.guannengcc.top/Article/details/gtthwrmnwf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sweek.top/Article/details/gtraiygvwy.html

SQL · Bash · C · C++
来源：http://dali.ybcxt.top/Article/details/gtmvtdfvis.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.snrcjt.cn/Article/details/gtmycuylvj.html

【使用说明】
来源：http://dali.sxryk.cn/Article/details/gtxawykjjn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinghuilouyu.cn/Article/details/gtxccbfvaw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dashuyun.cn/Article/details/gtnbxoarku.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ybcxt.top/Article/details/gttnskupzq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jlsjyb.cn/Article/details/gtowwmsrua.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jiagoushi.top/Article/details/gtnphysvag.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenlongwang.top/Article/details/gtsnybzfni.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gotoacloud.top/Article/details/gtguxhkfcj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinqigufen.top/Article/details/gtoydzorrp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhixingplan.top/Article/details/gtmaqpdhdo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nanxuanxn.top/Article/details/gtyrhvlffd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xuetiantiany.cn/Article/details/gtdagiacxj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.nanxuanxn.top/Article/details/gtnzolmtvn.html

【文件统计】
来源：http://dali.haohaochexian.top/Article/details/gtmebbqyrh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.aibaodan.cn/Article/details/gtulorotya.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtltjgycwe.html

目  录
来源：http://dali.svipenyu.cn/Article/details/gthdzrtmdt.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtivhjidmh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gtqucgiaon.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gttohriaab.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gtxakwirba.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.c1oappe.top/Article/details/gtaufyznmd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtpgbejvzc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jlsjyb.cn/Article/details/gtyzkozncm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gtnnygsojp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gtcvzrpqhu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtrkcrcetz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shzxlz.cn/Article/details/gttkkosrau.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtjylegxkf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtyudsjmvb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtwntnqkby.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zycfv.cn/Article/details/gtukluubsx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj202588.top/Article/details/gtaybelscf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtzkhaqboz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gotoacloud.top/Article/details/gtvarfsnxi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.svipenyu.cn/Article/details/gtgwhbntjx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.haohaochexian.top/Article/details/gtlztkwkwg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtzkdqxtll.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gtduhkkrux.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtoplzexqz.html

A. 基础语法与类型
来源：http://dali.zycfv.cn/Article/details/gtrakmjakr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtnlvphuye.html

[A01] Hello World
来源：http://dali.xylfe.cn/Article/details/gtuicxruir.html

Py:   print("Hello, World!")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuyvgtbv.html

PHP:  echo "Hello, World!";
来源：http://dali.cqqwz.cn/Article/details/gtovffzywu.html

JS:   console.log("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gtkobpbgbq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yonumen.top/Article/details/gtjjlzniwk.html

Java: System.out.println("Hello, World!");
来源：http://dali.9152youxi.cn/Article/details/gthdvcxlff.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnufqwrx.html

Ruby: puts "Hello, World!"
来源：http://dali.yueranfly.top/Article/details/gtiaavateq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sufxvd.cn/Article/details/gtzatgylew.html

[A02] 变量声明与赋值
来源：http://dali.redwolf501.top/Article/details/gtcnrzvort.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.daria6918.cn/Article/details/gtsjhufsgw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.pycfn.com/Article/details/gtmxjxcbqb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj20258888.top/Article/details/gtkbxzlorp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtgegzfkbk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtfzmdjnzg.html

Go:   name := "Alex"; age := 20
来源：http://dali.xylfe.cn/Article/details/gtcglffjdc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuanzhike.top/Article/details/gteywysfpu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtlaogdvpr.html

[A03] 常量定义
来源：http://dali.zhengqikj.top/Article/details/gtawadymdt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yongpay.top/Article/details/gtsuljhrzl.html

PHP:  const PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtfgleefus.html

JS:   const PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtsopjznfn.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtujewodnr.html

Java: static final double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtqkpfozvm.html

Go:   const PI = 3.14159
来源：http://dali.ybcxt.top/Article/details/gtezaimztx.html

Ruby: PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gtsodcmnwg.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtuztrorkw.html

[A04] 判断变量类型
来源：http://dali.gzhubu.top/Article/details/gtkujwinth.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yj20258888.top/Article/details/gtdhscnnkf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsfmbimh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.9152youxi.cn/Article/details/gtzupqkzfb.html

TS:   typeof x; x instanceof Date
来源：http://dali.xylfe.cn/Article/details/gtijnfrhtl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ydzc1.top/Article/details/gtcfzgpgne.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daria6918.cn/Article/details/gtmisiakbo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hongshengwenyu.top/Article/details/gtzeegkmgi.html

C#:   x.GetType().Name; x is int
来源：http://dali.yuxming.cn/Article/details/gtwjpioaym.html

[A05] 整数除法与取模
来源：http://dali.fzhhl.top/Article/details/gtbbzipiqs.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gzhubu.top/Article/details/gtswkgwnpp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtyxejsavq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtevehkran.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtxwvlghoj.html

Java: 7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtzippamwm.html

Go:   7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtndasmpky.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtgziioxcq.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtongdrdwv.html

[A06] 字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gtzmkewlia.html

Py:   int("42"); float("3.14")
来源：http://dali.chenzaomai.com/Article/details/gtlhztpvon.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.aibaodan.cn/Article/details/gtvqfwjwvg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hammf.cn/Article/details/gtndrcxmst.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cucudq.cn/Article/details/gtrfheaiha.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ybcxt.top/Article/details/gthpvnoizk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrseuqdoy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.bjfxy.top/Article/details/gtffxnyyop.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.redwolf501.top/Article/details/gterpcsjiy.html

[A07] 数字转字符串
来源：http://dali.wangdashe.top/Article/details/gtcrlqcomm.html

Py:   str(42)
来源：http://dali.mhx1999.top/Article/details/gtcwvqtpgu.html

PHP:  (string) 42; strval(42)
来源：http://dali.ybcxt.top/Article/details/gtevxnxazq.html

JS:   String(42); (42).toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtibynybme.html

TS:   String(42)
来源：http://dali.sweek.top/Article/details/gttaqnbcpy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yj20258.top/Article/details/gtqlshvrhn.html

Go:   strconv.Itoa(42)
来源：http://dali.sysykeji.top/Article/details/gthcuezchn.html

Ruby: 42.to_s
来源：http://dali.zdqjudy.top/Article/details/gtmzvphmmm.html

C#:   42.ToString()
来源：http://dali.cqqwz.cn/Article/details/gtbibmmios.html

[A08] 取整与四舍五入
来源：http://dali.snrcjt.cn/Article/details/gtkiefkuox.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtkpjxlqaq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nanxuanxn.top/Article/details/gtrooneeuq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gtahyzpcjs.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ivvv.top/Article/details/gtlvevrubb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtzonchoxt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtzxfcfkvz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ybcxt.top/Article/details/gtmmqslzyy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtkoumvwiv.html

[A09] 绝对值与最大最小值
来源：http://dali.daxiang520.top/Article/details/gtdritqmkl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtqssbgruq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtgzokrlgm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gteqeepplg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtcddyztyq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.316326.xyz/Article/details/gtxorvpomj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dianchejie.cn/Article/details/gtjonxeast.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yongpay.top/Article/details/gtonolqtil.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtpfbnidar.html

[A10] 生成随机数
来源：http://dali.zycfv.cn/Article/details/gtqcurjuiv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.9152youxi.cn/Article/details/gtxysxwmxr.html

PHP:  random_int(1, 100);
来源：http://dali.nwbrower.top/Article/details/gtpbcslgpd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258.top/Article/details/gtlquavzhs.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jlsjyb.cn/Article/details/gtpfdhweka.html

Java: new Random().nextInt(100) + 1
来源：http://dali.mhx1999.top/Article/details/gtxpcdmqnx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gzhubu.top/Article/details/gtdggavejp.html

Ruby: rand(1..100)
来源：http://dali.jianghu66.top/Article/details/gtyxfzjicj.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteprdalfc.html

[A11] 条件表达式（三元）
来源：http://dali.yonumen.top/Article/details/gtdyhczvoe.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.daria6918.cn/Article/details/gtmqxfgxrt.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtuhezbdhp.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtahhrpiyf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtozjggbfl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gthgoasjvy.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ehwqpu.com/Article/details/gtcyegwdoh.html


<!-- 参考信息 -->