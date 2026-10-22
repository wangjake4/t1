代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtjrucabvu.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj202588.top/Article/details/gtmchchxdi.html

[U72] PHP：写错误日志
来源：http://dali.shangyingyoupin.top/Article/details/gtkgarvolt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.mhx1999.top/Article/details/gtxtmqydov.html

[U73] PHP：读取 ini 配置
来源：http://dali.redwolf501.top/Article/details/gtxvcxtafg.html

parse_ini_file("config.ini", true)
来源：http://dali.cqqwz.cn/Article/details/gtljcfowow.html

[U74] PHP：读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtbgygkzfr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sufxvd.cn/Article/details/gtbmbocjqh.html

[U75] PHP：依赖注入
来源：http://dali.guannengcc.top/Article/details/gtilzvpvfy.html

composer require psr/container
来源：http://dali.fengsongda.top/Article/details/gtmutmdarp.html

[U76] PHP：简单路由
来源：http://dali.gzhubu.top/Article/details/gtyfocciva.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gogol.net.cn/Article/details/gtiticopiv.html

[U77] PHP：模板渲染
来源：http://dali.jinqigufen.top/Article/details/gtehxlmble.html

composer require twig/twig
来源：http://dali.chenjidiqi.icu/Article/details/gtoeviuotz.html

[U78] PHP：单元测试
来源：http://dali.xuetiantiany.cn/Article/details/gtzxnkdmuq.html

composer require --dev phpunit/phpunit
来源：http://dali.iojbl.cn/Article/details/gtqvxrkwfi.html

[U79] PHP：静态分析
来源：http://dali.zycfv.cn/Article/details/gtdnejffty.html

composer require --dev phpstan/phpstan
来源：http://dali.yuxming.cn/Article/details/gtelgxuqry.html

[U80] PHP：代码规范修复
来源：http://dali.wangshuangyany.cn/Article/details/gtisxhsfew.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cheryme.top/Article/details/gtvyowtzmj.html

[U81] JS：初始化项目
来源：http://dali.yangfankeji.com/Article/details/gtojzotupy.html

npm init -y;  npm i express
来源：http://dali.cucudq.cn/Article/details/gtihltspzz.html

[U82] JS：package.json 脚本
来源：http://dali.hfpthk.cn/Article/details/gtcqwaprhn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xziqi.cn/Article/details/gtsgknrnlk.html

[U83] JS：ES Module 导入导出
来源：http://dali.9152youxi.cn/Article/details/gtrpaywqgc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gtvhchwdxo.html

[U84] JS：CommonJS 写法
来源：http://dali.tanke756.top/Article/details/gtdtebgakp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hnqzz.top/Article/details/gtjdnphitu.html

[U85] JS：可选链
来源：http://dali.nanxinkj.top/Article/details/gteiwxaldy.html

a?.b?.c
来源：http://dali.yangfankeji.com/Article/details/gtbesjyqtr.html

[U86] JS：空值合并
来源：http://dali.yvedp.cn/Article/details/gttzaiuaup.html

a ?? b
来源：http://dali.haohaochexian.top/Article/details/gtrrsliwqx.html

[U87] JS：解构默认值
来源：http://dali.vqdsnc.cn/Article/details/gtmxiypqmw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jianghu66.top/Article/details/gtoqfkrsvx.html

[U88] JS：对象展开合并
来源：http://dali.vqdsnc.cn/Article/details/gtibuzydir.html

{ ...a, ...b }
来源：http://dali.dianchejie.cn/Article/details/gtqorabljc.html

[U89] JS：数组去重
来源：http://dali.fzhhl.top/Article/details/gtqetzhzws.html

[...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtpelpqqcd.html

[U90] JS：数字数组排序
来源：http://dali.haohaochexian.top/Article/details/gthmacekss.html

[...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtjugpyvic.html

[U91] JS：对象键值遍历
来源：http://dali.jqgfzy.top/Article/details/gtwckszgdi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.wangshuangyany.cn/Article/details/gtyjobrdkq.html

[U92] JS：深拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtzcmybtci.html

structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtotjxwwyr.html

[U93] JS：模板字符串
来源：http://dali.nanxuanxn.top/Article/details/gtghqpzdfq.html

`共 ${n} 条`
来源：http://dali.dashuyun.cn/Article/details/gtkkvdlslo.html

[U94] JS：箭头函数
来源：http://dali.tian-w.cn/Article/details/gtynyrfedr.html

const double = x => x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gtjolbxeiv.html

[U95] JS：Promise 包装
来源：http://dali.shuidangran.top/Article/details/gteyofnlph.html

new Promise((resolve, reject) => {})
来源：http://dali.hongshengwenyu.top/Article/details/gtauutnfzs.html

[U96] JS：async/await 与异常
来源：http://dali.cheryme.top/Article/details/gtpnvdwono.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvajxcol.html

[U97] JS：并发请求
来源：http://dali.gotoacloud.top/Article/details/gtzfmfwygy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtxaqufcxj.html

[U98] JS：fetch 带 JSON
来源：http://dali.ybcxt.top/Article/details/gtcogtzykd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjizqibt.html

[U99] JS：事件监听
来源：http://dali.guannengcc.top/Article/details/gtwnrvnmfe.html

el.addEventListener("click", e => {})
来源：http://dali.yongpay.top/Article/details/gtcxhafekm.html

[U100] JS：DOM 查询
来源：http://dali.ivvv.top/Article/details/gtnzgptjqw.html

document.querySelector(".item")
来源：http://dali.c1oappe.top/Article/details/gthhnueqgn.html

[U101] JS：classList 操作
来源：http://dali.yj20258.top/Article/details/gtlvzlcoff.html

el.classList.toggle("active")
来源：http://dali.yuxming.cn/Article/details/gtjtvzfrbf.html

[U102] JS：本地存储
来源：http://dali.sxryk.cn/Article/details/gtnwrowhsu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.c1oappe.top/Article/details/gtfpfynimn.html

[U103] JS：定时器
来源：http://dali.chenlongwang.top/Article/details/gtbunyvteo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cqqwz.cn/Article/details/gtdmobxxkj.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gtelamlfgz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtunhftdeb.html

[U105] JS：节流
来源：http://dali.dashuyun.cn/Article/details/gtebafvbkj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jiagoushi.top/Article/details/gtizvoeklp.html

[U106] JS：日期格式化
来源：http://dali.gzhubu.top/Article/details/gtbaonsnfx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jqgfzy.top/Article/details/gtpwkvkcub.html

[U107] JS：数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtxccufang.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtngbtbnxp.html

[U108] JS：随机整数
来源：http://dali.zhengqikj.top/Article/details/gtqavttlko.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sxryk.cn/Article/details/gtqovkjnmg.html

[U109] JS：数组分组
来源：http://dali.chenjidiqi.icu/Article/details/gtiouhwfpt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtcmjylrrn.html

[U110] JS：数组分块
来源：http://dali.snrcjt.cn/Article/details/gtfpzvetwb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gaohongyu789.top/Article/details/gtvfoffsre.html

[U111] JS：对象转 Map
来源：http://dali.andypj.xyz/Article/details/gtgcygufkx.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gtijgmyyre.html

[U112] JS：字符串补位
来源：http://dali.gotoacloud.top/Article/details/gtubhelxld.html

"7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gthnoltsut.html

[U113] JS：正则替换全部
来源：http://dali.cqqwz.cn/Article/details/gtfvujnbwr.html

s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gthijqpuci.html

[U114] JS：JSON 深比较
来源：http://dali.ehwqpu.com/Article/details/gtfspqixgv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtyigugfpk.html

[U115] JS：生成 UUID
来源：http://dali.xylfe.cn/Article/details/gttlmpgkqp.html

crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtbvdwqhey.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ppjwa.cn/Article/details/gtymcxfywt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.0kj1m.cn/Article/details/gtzzprinny.html

[U117] JS：单元测试
来源：http://dali.ppjwa.cn/Article/details/gtjeedzdwi.html

npm i -D vitest;  npx vitest
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcnsjorm.html

[U118] JS：开发服务器
来源：http://dali.zhiwuduotai.top/Article/details/gtsuciozui.html

npm i -D vite;  npx vite
来源：http://dali.guowangkeji.top/Article/details/gtiqfugsxy.html

[U119] JS：生产构建
来源：http://dali.0kj1m.cn/Article/details/gthvwjulbu.html

npx vite build
来源：http://dali.gogol.net.cn/Article/details/gtlxccsekd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yuxming.cn/Article/details/gtvhmcnonb.html

import.meta.env.VITE_API_URL
来源：http://dali.svipenyu.cn/Article/details/gtxiwnqibi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtnwnzyhnp.html

统计汇总
来源：http://dali.hfpthk.cn/Article/details/gtguhyntna.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwqkohvjj.html

按语言统计（条）：
来源：http://dali.zycfv.cn/Article/details/gtmhdqaubo.html

Python ......... 252
来源：http://dali.ybcxt.top/Article/details/gtohiftfki.html

PHP ............ 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsbqrodr.html

JavaScript ..... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gtminfcusj.html

TypeScript ..... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgztqdwq.html

Java ........... 212
来源：http://dali.svipenyu.cn/Article/details/gtncriiobn.html

Go ............. 212
来源：http://dali.haohaochexian.top/Article/details/gtsxqraukj.html

Ruby ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtvpdrmkuw.html

C# ............. 212
来源：http://dali.yueranfly.top/Article/details/gtlaukcmzv.html

C .............. 30
来源：http://dali.gaohongyu789.top/Article/details/gtgclfgiae.html

C++ ............ 30
来源：http://dali.yj202588.top/Article/details/gtzlvvdjhm.html

SQL ............ 90
来源：http://dali.sweek.top/Article/details/gttclkhhtr.html

Bash ........... 80
来源：http://dali.pengpengdd.cyou/Article/details/gtnvdsiqre.html

Kotlin ......... 15
来源：http://dali.feifeiyinyue.top/Article/details/gtsjdcoyac.html

Swift .......... 15
来源：http://dali.jinqigfzy.top/Article/details/gtumvoagud.html

Lua ............ 10
来源：http://dali.0kj1m.cn/Article/details/gtqnspmvjc.html

Perl ........... 10
来源：http://dali.cdnleiting.top/Article/details/gtvcuhfacc.html

Scala .......... 10
来源：http://dali.xziqi.cn/Article/details/gtsgvrgcov.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtbpmpcmwb.html

合计 ........... 2106 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdaqbbeah.html

按章节统计：
来源：http://dali.nwbrower.top/Article/details/gttmftvaqs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.daxiang520.top/Article/details/gtetwmkudn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sufxvd.cn/Article/details/gtvsnlqlmg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtideyfgnj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gtncfmzyvd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guowangkeji.top/Article/details/gtdhxaaolu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gtixkharml.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gtoasbzqyz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuanzhike.top/Article/details/gtwczqcvfz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gttausuzde.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfqgyhqx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtjgihawsj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtehuaiovu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtkcqoeyse.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinghuilouyu.cn/Article/details/gtclggjauw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gtqdsrpiji.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtwpmntatm.html

Q SQL 专题                              90
来源：http://dali.jiagoushi.top/Article/details/gtzjwhsirq.html

R Bash 专题                             80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedtljkja.html

S C / C++ 专题                          60
来源：http://dali.yangfankeji.com/Article/details/gttodrgdhn.html

T 其他语言补充                          60
来源：http://dali.jinqigufen.top/Article/details/gtscaoqaur.html

U 高频实用片段                         120
来源：http://dali.zhiwuduotai.top/Article/details/gtbchokzzk.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtqszhhwbf.html

合计                                  2106 条
来源：http://dali.cucudq.cn/Article/details/gthaeouzem.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtedjgjuyd.html

使用提醒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzurfyoa.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtfzjjzpqo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sxryk.cn/Article/details/gtyciegxko.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuetiantiany.cn/Article/details/gtanjtucbh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jlsjyb.cn/Article/details/gtuiowwurf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zdqjudy.top/Article/details/gtleomsqen.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sysykeji.top/Article/details/gtwdoxcrop.html

—— 文件结束 ——
来源：http://dali.jiagoushi.top/Article/details/gtuiyjkxix.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtkddbnzmm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shuidangran.top/Article/details/gtvtrdkptv.html

Common Programming Examples Cheat Book
来源：http://dali.pengpengdd.cyou/Article/details/gtmgjlwqur.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtsttxtmyl.html

【收录内容】
来源：http://dali.gogol.net.cn/Article/details/gtbdsrvcsb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuanzx.com/Article/details/gthyqaoinn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinghuilouyu.cn/Article/details/gtogtpvgqj.html

SQL · Bash · C · C++
来源：http://dali.jyoumei.cn/Article/details/gtkksxvwhw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zdqjudy.top/Article/details/gtvktsbfxp.html

【使用说明】
来源：http://dali.havefunace.top/Article/details/gtyfhbalgl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.guowangkeji.top/Article/details/gtxakdzwyy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gotoacloud.top/Article/details/gtdgwesnmc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aibaodan.cn/Article/details/gttzgmbxha.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.wangdashe.top/Article/details/gtzhqnjisr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.kuanghao11.cn/Article/details/gtvbmqrcus.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ehwqpu.com/Article/details/gtuseivxsb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cdnleiting.top/Article/details/gtifccvzes.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xinyue.icu/Article/details/gtkvaxuloj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.smart0.xyz/Article/details/gtrazbkwsq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jiagoushi.top/Article/details/gtdyhvmcyi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnywkusc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cqqwz.cn/Article/details/gtmwcdgzkb.html

【文件统计】
来源：http://dali.iojbl.cn/Article/details/gtjvkkmvpm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhixingplan.top/Article/details/gtvxclnngy.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtyarwjebu.html

目  录
来源：http://dali.yonumen.top/Article/details/gtyqrrhwbb.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpqbqxuc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yongpay.top/Article/details/gtnuwepgas.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gtjsfusbrg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtnbskchps.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtilvbzhfe.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj20258888.top/Article/details/gtniwsfdgb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gtzerybmxu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gtjinmpbyc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gtgdrnidlp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtirxxocir.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.smart0.xyz/Article/details/gtgwfworfk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtdwvreiqp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtaasrascy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtwbxeheck.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.quarkkingdee.top/Article/details/gtobabdcos.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zdqjudy.top/Article/details/gtfkaeplsi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtmuhhwint.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hfpthk.cn/Article/details/gtjdxdchoq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtynmrpylz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cucudq.cn/Article/details/gtsiafcqwh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtrgxzpgsa.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tian-w.cn/Article/details/gthokcdonc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtcdmwpprg.html

A. 基础语法与类型
来源：http://dali.birdmap.top/Article/details/gtzntgxqjq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gttcetpcjp.html

[A01] Hello World
来源：http://dali.smart0.xyz/Article/details/gtjitzeqye.html

Py:   print("Hello, World!")
来源：http://dali.yj20258888.top/Article/details/gtopqhypwy.html

PHP:  echo "Hello, World!";
来源：http://dali.cashguo.top/Article/details/gttszgvqyg.html

JS:   console.log("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gtshoweyon.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.feifeiyinyue.top/Article/details/gtravglats.html

Java: System.out.println("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gttbbplujb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gtexoaitsy.html

Ruby: puts "Hello, World!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtyadrdmxb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gtiaaeludx.html

[A02] 变量声明与赋值
来源：http://dali.hammf.cn/Article/details/gtilygkevz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aizwys.cn/Article/details/gtthlewosz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtsdpinkzo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xylfe.cn/Article/details/gttdbsmzjr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.redwolf501.top/Article/details/gtkfcorejn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xylfe.cn/Article/details/gtyfwcknso.html

Go:   name := "Alex"; age := 20
来源：http://dali.guowangkeji.top/Article/details/gtqvqmmczk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gzhubu.top/Article/details/gthbfhqgkv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hammf.cn/Article/details/gtdcbhaaal.html

[A03] 常量定义
来源：http://dali.iojbl.cn/Article/details/gtxseedglr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.havefunace.top/Article/details/gtaeffwqpn.html

PHP:  const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtoirbfvgc.html

JS:   const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtqczrmmlz.html

TS:   const PI: number = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtqwoqlfui.html

Java: static final double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtsdzprrxn.html

Go:   const PI = 3.14159
来源：http://dali.pycfn.com/Article/details/gtffqpcsor.html

Ruby: PI = 3.14159
来源：http://dali.chenlongwang.top/Article/details/gtxnmswzgv.html

C#:   const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtdzpfgvoa.html

[A04] 判断变量类型
来源：http://dali.zycfv.cn/Article/details/gtksbsania.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fzhhl.top/Article/details/gtnhqgdhcj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shangyingyoupin.top/Article/details/gtnyrzmmdp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gtbanyldge.html

TS:   typeof x; x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gtvucxsjkb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.mhx1999.top/Article/details/gtyrsjacnp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aizwys.cn/Article/details/gtimqthrlh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprdvwyib.html

C#:   x.GetType().Name; x is int
来源：http://dali.guowangkeji.top/Article/details/gtnodvbqnw.html

[A05] 整数除法与取模
来源：http://dali.ehwqpu.com/Article/details/gtbmpjfwwy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hnxiangtu.top/Article/details/gtozifsgug.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtaxkoebon.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtzfaqvxif.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtxkqdyqcs.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtleounaxl.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtflutiukh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtdkkabkcc.html

C#:   7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjujlkagm.html

[A06] 字符串转数字
来源：http://dali.yj20258888.top/Article/details/gtunlxffcp.html

Py:   int("42"); float("3.14")
来源：http://dali.chenzaomai.com/Article/details/gtgtrglnbu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gotoacloud.top/Article/details/gtkkbswvgw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gtxalrdcwb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinqigufen.top/Article/details/gtjbvihlxz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jqgfzy.top/Article/details/gtlcjwfiel.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nanxinkj.top/Article/details/gtnrzazonz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yangfankeji.com/Article/details/gtnkfnczfp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.guannengcc.top/Article/details/gtxkuywuwe.html

[A07] 数字转字符串
来源：http://dali.bjfxy.top/Article/details/gtoxozrrpm.html

Py:   str(42)
来源：http://dali.gaohongyu789.top/Article/details/gtzavjfxlt.html

PHP:  (string) 42; strval(42)
来源：http://dali.redwolf501.top/Article/details/gtuokdbdwq.html

JS:   String(42); (42).toString()
来源：http://dali.sysykeji.top/Article/details/gtrbpbinmz.html

TS:   String(42)
来源：http://dali.jiagoushi.top/Article/details/gtcfvzlepa.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yanxiufei.cn/Article/details/gtgklxubeo.html

Go:   strconv.Itoa(42)
来源：http://dali.yuxming.cn/Article/details/gtbntohfwk.html

Ruby: 42.to_s
来源：http://dali.cqqwz.cn/Article/details/gtguxwkhfk.html

C#:   42.ToString()
来源：http://dali.zdqjudy.top/Article/details/gtqxigvgsg.html

[A08] 取整与四舍五入
来源：http://dali.jqgufenzy.top/Article/details/gtvjgkrlxq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gtraezkvdw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzpibjco.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtmodnghiv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hywenlv.cn/Article/details/gtasifmczc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtexlidoho.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtllhpwcll.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ehwqpu.com/Article/details/gtskzbbtnd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gttjjeixol.html

[A09] 绝对值与最大最小值
来源：http://dali.hfpthk.cn/Article/details/gtwxjouudx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtkrbtjwpj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtbucnvdtm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwvpwzfp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtngxkqgum.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtcqubiqkd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ybcxt.top/Article/details/gtpcqhsntk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.haohaochexian.top/Article/details/gtxwzaerbg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtppfmsyvv.html

[A10] 生成随机数
来源：http://dali.hfpthk.cn/Article/details/gtnwogqpmx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xuetiantiany.cn/Article/details/gtzqamevwf.html

PHP:  random_int(1, 100);
来源：http://dali.nanxuanxn.top/Article/details/gttbdzzmyb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xylfe.cn/Article/details/gtcwtbjkvu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.redwolf501.top/Article/details/gtafsnvxfk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258888.top/Article/details/gtqxzwirio.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.aizwys.cn/Article/details/gtzilmjyuv.html

Ruby: rand(1..100)
来源：http://dali.ybcxt.top/Article/details/gtrrurmnli.html

C#:   new Random().Next(1, 101)
来源：http://dali.nanxuanxn.top/Article/details/gtikobexhr.html

[A11] 条件表达式（三元）
来源：http://dali.zhiwuduotai.top/Article/details/gtxghdakdz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.iojbl.cn/Article/details/gtphananxr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gtrzxkedgx.html


<!-- 参考信息 -->