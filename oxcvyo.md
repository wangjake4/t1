代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.ehwqpu.com/Article/details/gtuxdzjgla.html

parse_ini_file("config.ini", true)
来源：http://dali.svipenyu.cn/Article/details/gtgktwmjbp.html

[U74] PHP：读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gturoptlch.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sweek.top/Article/details/gtxqyqjsmu.html

[U75] PHP：依赖注入
来源：http://dali.gaohongyu789.top/Article/details/gtuxwbvmma.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gtjfwsnmvx.html

[U76] PHP：简单路由
来源：http://dali.havefunace.top/Article/details/gthsletjml.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hongshengwenyu.top/Article/details/gtihdweuii.html

[U77] PHP：模板渲染
来源：http://dali.9152youxi.cn/Article/details/gtbmfogdmx.html

composer require twig/twig
来源：http://dali.cqqwz.cn/Article/details/gtisvntjgk.html

[U78] PHP：单元测试
来源：http://dali.xziqi.cn/Article/details/gtihrbftag.html

composer require --dev phpunit/phpunit
来源：http://dali.pengpengdd.cyou/Article/details/gtxfbrwjnm.html

[U79] PHP：静态分析
来源：http://dali.yuxming.cn/Article/details/gtdaszkkjn.html

composer require --dev phpstan/phpstan
来源：http://dali.fzhhl.top/Article/details/gtccpzftdx.html

[U80] PHP：代码规范修复
来源：http://dali.zhixingplan.top/Article/details/gtvnpgodaf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yonumen.top/Article/details/gtifanfhbp.html

[U81] JS：初始化项目
来源：http://dali.yj202588.top/Article/details/gtszppssdu.html

npm init -y;  npm i express
来源：http://dali.zhongyouzk.top/Article/details/gtewwjlocc.html

[U82] JS：package.json 脚本
来源：http://dali.xziqi.cn/Article/details/gtkvlznnwd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswfihiru.html

[U83] JS：ES Module 导入导出
来源：http://dali.ivvv.top/Article/details/gtseyoymrk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gtusuqujtu.html

[U84] JS：CommonJS 写法
来源：http://dali.hywenlv.cn/Article/details/gtwvuozywd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangdashe.top/Article/details/gtmljctibu.html

[U85] JS：可选链
来源：http://dali.aizwys.cn/Article/details/gtwfyegfln.html

a?.b?.c
来源：http://dali.hywenlv.cn/Article/details/gtwlpszfxq.html

[U86] JS：空值合并
来源：http://dali.guowangkeji.top/Article/details/gttdvivhph.html

a ?? b
来源：http://dali.tianlin.xyz/Article/details/gtgpaqyjbi.html

[U87] JS：解构默认值
来源：http://dali.redwolf501.top/Article/details/gtalipwzbw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nwbrower.top/Article/details/gthxavmxhj.html

[U88] JS：对象展开合并
来源：http://dali.hfpthk.cn/Article/details/gtszhngguq.html

{ ...a, ...b }
来源：http://dali.nanxinkj.top/Article/details/gtveixhfsu.html

[U89] JS：数组去重
来源：http://dali.feifeiyinyue.top/Article/details/gtuobubsyp.html

[...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkrkvdzs.html

[U90] JS：数字数组排序
来源：http://dali.yuanzhike.top/Article/details/gtlkfurjch.html

[...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtdpzaoblr.html

[U91] JS：对象键值遍历
来源：http://dali.nanxuanxn.top/Article/details/gtejaxkour.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cheryme.top/Article/details/gtixalulaz.html

[U92] JS：深拷贝
来源：http://dali.cucudq.cn/Article/details/gtzkyaroqs.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtynslbkho.html

[U93] JS：模板字符串
来源：http://dali.shzxlz.cn/Article/details/gtgnxptfjd.html

`共 ${n} 条`
来源：http://dali.pengpengdd.cyou/Article/details/gttiasowec.html

[U94] JS：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gtjxnafndq.html

const double = x => x * 2;
来源：http://dali.zycfv.cn/Article/details/gtsdtcrjeo.html

[U95] JS：Promise 包装
来源：http://dali.shzxlz.cn/Article/details/gtknaivldt.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gtswvzqdxl.html

[U96] JS：async/await 与异常
来源：http://dali.guowangkeji.top/Article/details/gtyxprdukh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkukgfgcy.html

[U97] JS：并发请求
来源：http://dali.gotoacloud.top/Article/details/gtbjpnbcfw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtvxcydkob.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gthbvjdclc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jyoumei.cn/Article/details/gtmtojfnrq.html

[U99] JS：事件监听
来源：http://dali.cashguo.top/Article/details/gtmixybtwn.html

el.addEventListener("click", e => {})
来源：http://dali.jqgfzy.top/Article/details/gtaidyukkc.html

[U100] JS：DOM 查询
来源：http://dali.hongshengwenyu.top/Article/details/gtdncgarnh.html

document.querySelector(".item")
来源：http://dali.yonumen.top/Article/details/gtznsrrqdo.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gtshaxrtdj.html

el.classList.toggle("active")
来源：http://dali.tian-w.cn/Article/details/gtyxjlzttz.html

[U102] JS：本地存储
来源：http://dali.sysykeji.top/Article/details/gtgsdjxsni.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cqqwz.cn/Article/details/gtsyluunug.html

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gtsuuvluuj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jlsjyb.cn/Article/details/gtcjgragqp.html

[U104] JS：防抖
来源：http://dali.jinqigufen.top/Article/details/gtwactkiid.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtwnoklxqi.html

[U105] JS：节流
来源：http://dali.xinyue.icu/Article/details/gtboelswjy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpxtvrqy.html

[U106] JS：日期格式化
来源：http://dali.yuxming.cn/Article/details/gtrvytpdiq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.c1oappe.top/Article/details/gtrieginar.html

[U107] JS：数字千分位
来源：http://dali.redwolf501.top/Article/details/gtpvtkmbnj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gtixuorvwr.html

[U108] JS：随机整数
来源：http://dali.hysaishi.cn/Article/details/gtchiqtfzn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.mhx1999.top/Article/details/gtyxwbrwxi.html

[U109] JS：数组分组
来源：http://dali.yvedp.cn/Article/details/gtohwvofty.html

Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtmxgjjkhf.html

[U110] JS：数组分块
来源：http://dali.dashuyun.cn/Article/details/gtpwiiprdb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigufen.top/Article/details/gtxwymxbey.html

[U111] JS：对象转 Map
来源：http://dali.aibaodan.cn/Article/details/gtwfviosee.html

new Map(Object.entries(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtgomenulc.html

[U112] JS：字符串补位
来源：http://dali.fzhhl.top/Article/details/gtzpvrppay.html

"7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtmbttestp.html

[U113] JS：正则替换全部
来源：http://dali.chenlongwang.top/Article/details/gtwqcxtbtw.html

s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtftecuows.html

[U114] JS：JSON 深比较
来源：http://dali.dashuyun.cn/Article/details/gtgtzlfwzv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycksxbmo.html

[U115] JS：生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gtpnauqzlr.html

crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtkyicdyxk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ivvv.top/Article/details/gtxhlgtsoa.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zycfv.cn/Article/details/gtwwqooitb.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmclgguq.html

npm i -D vitest;  npx vitest
来源：http://dali.xziqi.cn/Article/details/gtxylbzjyl.html

[U118] JS：开发服务器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjurzglg.html

npm i -D vite;  npx vite
来源：http://dali.gzhubu.top/Article/details/gthfgdumjr.html

[U119] JS：生产构建
来源：http://dali.shuidangran.top/Article/details/gtuecgqpax.html

npx vite build
来源：http://dali.havefunace.top/Article/details/gtmthtyavl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcqwiaqc.html

import.meta.env.VITE_API_URL
来源：http://dali.svipenyu.cn/Article/details/gtadayvbpy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtxcomckjr.html

统计汇总
来源：http://dali.c1oappe.top/Article/details/gtiadgwugg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtywjxhuah.html

按语言统计（条）：
来源：http://dali.xziqi.cn/Article/details/gttjknrwzb.html

Python ......... 252
来源：http://dali.yuanzhike.top/Article/details/gtcymtgjqz.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gtwapncjxb.html

JavaScript ..... 252
来源：http://dali.fengsongda.top/Article/details/gturnpnwnm.html

TypeScript ..... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtqdsjmfki.html

Java ........... 212
来源：http://dali.ivvv.top/Article/details/gtgpgowtdc.html

Go ............. 212
来源：http://dali.hnxiangtu.top/Article/details/gttzcwlljw.html

Ruby ........... 212
来源：http://dali.hysaishi.cn/Article/details/gtwqqzktnd.html

C# ............. 212
来源：http://dali.yueranfly.top/Article/details/gtzzziqtdn.html

C .............. 30
来源：http://dali.gotoacloud.top/Article/details/gtvwpondsy.html

C++ ............ 30
来源：http://dali.hnxiangtu.top/Article/details/gtgakaiqmw.html

SQL ............ 90
来源：http://dali.gogol.net.cn/Article/details/gtijlciwdv.html

Bash ........... 80
来源：http://dali.0kj1m.cn/Article/details/gtuzuwpgev.html

Kotlin ......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmkbqolb.html

Swift .......... 15
来源：http://dali.zdqjudy.top/Article/details/gtdpendfvf.html

Lua ............ 10
来源：http://dali.yvedp.cn/Article/details/gtnmcpnxsj.html

Perl ........... 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtedrcnzxz.html

Scala .......... 10
来源：http://dali.sweek.top/Article/details/gtmtucrxhw.html

------------------------------------
来源：http://dali.sweek.top/Article/details/gttsunjcvd.html

合计 ........... 2106 条
来源：http://dali.ydzc1.top/Article/details/gteaiilfxw.html

按章节统计：
来源：http://dali.shangyingyoupin.top/Article/details/gtdtmmyxiq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.smart0.xyz/Article/details/gtrjeprhvo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gtgxrlocxc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtonasofum.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gtdhiqvtbe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.redwolf501.top/Article/details/gtjpsoqyxr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gtjbilhkrq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gtttpzhjwq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gotoacloud.top/Article/details/gtanqogbtr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtwlzeonbj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pycfn.com/Article/details/gtnfsjdcdm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtfoiltfki.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gthtoleeuh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtqkgaoyen.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.havefunace.top/Article/details/gthtybnbdl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jiagoushi.top/Article/details/gtuellqhje.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gticbbvlcw.html

Q SQL 专题                              90
来源：http://dali.zhengqikj.top/Article/details/gtnqhrwzqr.html

R Bash 专题                             80
来源：http://dali.gaohongyu789.top/Article/details/gtdijpzskh.html

S C / C++ 专题                          60
来源：http://dali.hongshengwenyu.top/Article/details/gthwbaeagh.html

T 其他语言补充                          60
来源：http://dali.jinqigfzy.top/Article/details/gtypnqxewh.html

U 高频实用片段                         120
来源：http://dali.pengpengdd.cyou/Article/details/gtqclkscso.html

------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuiqtawbq.html

合计                                  2106 条
来源：http://dali.haohaochexian.top/Article/details/gtolpupvcm.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtwnzkhsmi.html

使用提醒
来源：http://dali.chenzaomai.com/Article/details/gtsiynhbzm.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtrzinwqds.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuxming.cn/Article/details/gtlhtjontg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhongyouzk.top/Article/details/gtpqanbftu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yuanzhike.top/Article/details/gtfvrweefy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hysaishi.cn/Article/details/gtbyrorsfi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jlsjyb.cn/Article/details/gtsgfvkwme.html

—— 文件结束 ——
来源：http://dali.xuanzx.com/Article/details/gtaowmixww.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwzoyhtel.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.pycfn.com/Article/details/gtahrlnwwl.html

Common Programming Examples Cheat Book
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmuhktxk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtbbquqfmq.html

【收录内容】
来源：http://dali.gotoacloud.top/Article/details/gtodgjwqgp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.bjfxy.top/Article/details/gtcstrspzo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.snrcjt.cn/Article/details/gtxtjxokaw.html

SQL · Bash · C · C++
来源：http://dali.redwolf501.top/Article/details/gtmqrfmhos.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jiagoushi.top/Article/details/gtoodgvfoi.html

【使用说明】
来源：http://dali.9152youxi.cn/Article/details/gtsgjtkthj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yonumen.top/Article/details/gtxeicixzz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jyoumei.cn/Article/details/gtyzvgsnbw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zdqjudy.top/Article/details/gtnvzletnx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aizwys.cn/Article/details/gtrnpdaetc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cdnleiting.top/Article/details/gtwzontdfm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gotoacloud.top/Article/details/gtpdzlbkxg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.dianchejie.cn/Article/details/gtossdsbci.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuanzx.com/Article/details/gtmomudkym.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgfzy.top/Article/details/gtzsceulpp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yvedp.cn/Article/details/gtjtdfexhx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yueranfly.top/Article/details/gtvdkvpdvk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.mhx1999.top/Article/details/gtpjaxphgc.html

【文件统计】
来源：http://dali.jqgufenzy.top/Article/details/gtmvkebfij.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.haohaochexian.top/Article/details/gtkwbymhym.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gtabvavuxn.html

目  录
来源：http://dali.shzxlz.cn/Article/details/gtamgmcyjr.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtktzarkyq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gtmjoefrsg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtgeqlbeze.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gtmiarwsvg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.smart0.xyz/Article/details/gtkdoovhkx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ivvv.top/Article/details/gtiicxwmdb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxuanxn.top/Article/details/gtkpymdpsl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ppjwa.cn/Article/details/gtsxfsgtzx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gtetyruezn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gtnvprabsl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.havefunace.top/Article/details/gtuvvqhebx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeqfmrxu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtuibcnulk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtnogsmhon.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sysykeji.top/Article/details/gtvpewoffc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jiagoushi.top/Article/details/gtaftusbsy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtsqtqqbso.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenlongwang.top/Article/details/gtgetobqns.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtnprvblfv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.bjfxy.top/Article/details/gtpazkurrx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtpzefvjnr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gtevxyaoqb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtfjakfnzi.html

A. 基础语法与类型
来源：http://dali.aibaodan.cn/Article/details/gttfgkfcbp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpjammji.html

[A01] Hello World
来源：http://dali.zhengqikj.top/Article/details/gtckgpijjb.html

Py:   print("Hello, World!")
来源：http://dali.yongpay.top/Article/details/gtvmveiguh.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxinkj.top/Article/details/gtedwomaya.html

JS:   console.log("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gtqygdtias.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shzxlz.cn/Article/details/gtwrfavoaa.html

Java: System.out.println("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gteedyduns.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhiwuduotai.top/Article/details/gtnitagfht.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258.top/Article/details/gtuvjhqmam.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtfcsdtsem.html

[A02] 变量声明与赋值
来源：http://dali.cashguo.top/Article/details/gtafpqodkg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cheryme.top/Article/details/gtgzweshzu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffpyhwug.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj202588.top/Article/details/gtkikmnzht.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfjuqhvq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtdiubjzms.html

Go:   name := "Alex"; age := 20
来源：http://dali.xinyue.icu/Article/details/gtddurcanc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nwbrower.top/Article/details/gtxdpdlgld.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.daria6918.cn/Article/details/gtpmqsbbuh.html

[A03] 常量定义
来源：http://dali.redwolf501.top/Article/details/gtqhxsqaua.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangtech.top/Article/details/gtixmfzkop.html

PHP:  const PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtxyevmnqp.html

JS:   const PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstqmubic.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtossghuea.html

Java: static final double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtexjoaqdg.html

Go:   const PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gtowacirvt.html

Ruby: PI = 3.14159
来源：http://dali.yuanzhike.top/Article/details/gtyzjaoahf.html

C#:   const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtuygqstse.html

[A04] 判断变量类型
来源：http://dali.gotoacloud.top/Article/details/gtaugtjfxx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cqqwz.cn/Article/details/gtdairnagv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hywenlv.cn/Article/details/gtiphdista.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gtscqdghln.html

TS:   typeof x; x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gtehjbrfnz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhongyouzk.top/Article/details/gtddxduhuy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ydzc1.top/Article/details/gtblpbeche.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj202588.top/Article/details/gtnbissxdm.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhongyouzk.top/Article/details/gtgrnkyiyr.html

[A05] 整数除法与取模
来源：http://dali.cqqwz.cn/Article/details/gttfhkwpeo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.aizwys.cn/Article/details/gtoudpfwbp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtmopfdxke.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtnqchwmaw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtgtjnkoni.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtfmwhmrng.html

Go:   7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtthwzvrhe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtjybvqtif.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gtvwfodzjb.html

[A06] 字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gtwaafntan.html

Py:   int("42"); float("3.14")
来源：http://dali.c1oappe.top/Article/details/gtsfxfdnys.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zycfv.cn/Article/details/gtpxqemryv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.fengsongda.top/Article/details/gtwpgfzvxi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkladfux.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yuxming.cn/Article/details/gtzdrsavhf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jyoumei.cn/Article/details/gtlnebmblf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhongyouzk.top/Article/details/gthqrecyem.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.birdmap.top/Article/details/gtlijictkw.html

[A07] 数字转字符串
来源：http://dali.xziqi.cn/Article/details/gtnjdewmbb.html

Py:   str(42)
来源：http://dali.ehwqpu.com/Article/details/gtjogbpelk.html

PHP:  (string) 42; strval(42)
来源：http://dali.yj20258888.top/Article/details/gtuscglgcw.html

JS:   String(42); (42).toString()
来源：http://dali.hnqzz.top/Article/details/gtczgyzkil.html

TS:   String(42)
来源：http://dali.zhixingplan.top/Article/details/gtzpztexci.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dashuyun.cn/Article/details/gtrdufenuo.html

Go:   strconv.Itoa(42)
来源：http://dali.jiagoushi.top/Article/details/gtfokidxiy.html

Ruby: 42.to_s
来源：http://dali.kuanghao11.cn/Article/details/gtxegxzgpn.html

C#:   42.ToString()
来源：http://dali.9152youxi.cn/Article/details/gtaocqbzgw.html

[A08] 取整与四舍五入
来源：http://dali.cdnleiting.top/Article/details/gtiahcsxqh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yangfankeji.com/Article/details/gtgnjcrhwe.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.aibaodan.cn/Article/details/gtqvuwbgaw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gtsbayfeyk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhongyouzk.top/Article/details/gtcbxrogno.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtzcfwevcu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtcvigkzmi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhoulong.xyz/Article/details/gtsmlqwqwb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gtzjqvohsq.html

[A09] 绝对值与最大最小值
来源：http://dali.ydzc1.top/Article/details/gttczlslko.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuelsfmhg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtkjyyaria.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gthlizakfm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtmozjcpji.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtydlzypkp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.0kj1m.cn/Article/details/gtfrnrxlxr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.feifeiyinyue.top/Article/details/gtgwztysyl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtmwbusqry.html

[A10] 生成随机数
来源：http://dali.redwolf501.top/Article/details/gthmbksvyy.html

Py:   import random; random.randint(1, 100)
来源：http://dali.daria6918.cn/Article/details/gtglpzqdyo.html

PHP:  random_int(1, 100);
来源：http://dali.dianchejie.cn/Article/details/gtlgzxqwpk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dianchejie.cn/Article/details/gtlvfikfox.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258888.top/Article/details/gtyuubhtao.html

Java: new Random().nextInt(100) + 1
来源：http://dali.bjfxy.top/Article/details/gtylgardkt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gotoacloud.top/Article/details/gtefazweiq.html

Ruby: rand(1..100)
来源：http://dali.yj20258.top/Article/details/gtxjwmeqar.html

C#:   new Random().Next(1, 101)
来源：http://dali.yongpay.top/Article/details/gtgpnheshg.html

[A11] 条件表达式（三元）
来源：http://dali.jinqigufen.top/Article/details/gtrbafyveu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.svipenyu.cn/Article/details/gttdfrjjug.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gtubfhgvwf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtuyhoingd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtddfdfvev.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gtbznyayho.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shangyingyoupin.top/Article/details/gtqhbeotfa.html


<!-- 参考信息 -->