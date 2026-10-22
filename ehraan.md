代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.hnqzz.top/Article/details/gt2imjbwcsi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2qeehrxqt.html

[U72] PHP：写错误日志
来源：http://dali.xylfe.cn/Article/details/gt2hmbeqxrv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hfpthk.cn/Article/details/gt2hfpkzyon.html

[U73] PHP：读取 ini 配置
来源：http://dali.bjfxy.top/Article/details/gt2ipackgar.html

parse_ini_file("config.ini", true)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzualqnz.html

[U74] PHP：读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gt2eihueblb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sysykeji.top/Article/details/gt2gjmuahmh.html

[U75] PHP：依赖注入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhnulyvv.html

composer require psr/container
来源：http://dali.yvedp.cn/Article/details/gt2fdnxzshj.html

[U76] PHP：简单路由
来源：http://dali.smart0.xyz/Article/details/gt2sbqzmilt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.0kj1m.cn/Article/details/gt2ipzzoftd.html

[U77] PHP：模板渲染
来源：http://dali.chenjidiqi.icu/Article/details/gt2whkjooiv.html

composer require twig/twig
来源：http://dali.sweek.top/Article/details/gt2qnbktruh.html

[U78] PHP：单元测试
来源：http://dali.mhx1999.top/Article/details/gt2iiegeiqf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhongyouzk.top/Article/details/gt2jchhrdch.html

[U79] PHP：静态分析
来源：http://dali.guannengcc.top/Article/details/gt2zvytkelt.html

composer require --dev phpstan/phpstan
来源：http://dali.yvedp.cn/Article/details/gt2amozdwyp.html

[U80] PHP：代码规范修复
来源：http://dali.fzhhl.top/Article/details/gt2rtylqwux.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.iojbl.cn/Article/details/gt2wbecrfre.html

[U81] JS：初始化项目
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvrlivyo.html

npm init -y;  npm i express
来源：http://dali.jqgufenzy.top/Article/details/gt2educdqwj.html

[U82] JS：package.json 脚本
来源：http://dali.daria6918.cn/Article/details/gt2ijwkipbp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nwbrower.top/Article/details/gt2igjbfulh.html

[U83] JS：ES Module 导入导出
来源：http://dali.wangdashe.top/Article/details/gt2rximmbdj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gt2srxejgrk.html

[U84] JS：CommonJS 写法
来源：http://dali.316326.xyz/Article/details/gt2vamrebul.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.birdmap.top/Article/details/gt2xuhcfmvv.html

[U85] JS：可选链
来源：http://dali.jyoumei.cn/Article/details/gt2gtfdjvoe.html

a?.b?.c
来源：http://dali.tianlin.xyz/Article/details/gt2lvigsijh.html

[U86] JS：空值合并
来源：http://dali.zhixingplan.top/Article/details/gt2dmciodfx.html

a ?? b
来源：http://dali.vqdsnc.cn/Article/details/gt2gcwcbahn.html

[U87] JS：解构默认值
来源：http://dali.yanxiufei.cn/Article/details/gt2aexxohnf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2glssipzi.html

[U88] JS：对象展开合并
来源：http://dali.yueranfly.top/Article/details/gt2rdzwofrb.html

{ ...a, ...b }
来源：http://dali.ppjwa.cn/Article/details/gt2ukklxsgj.html

[U89] JS：数组去重
来源：http://dali.sxryk.cn/Article/details/gt2iiljxrnu.html

[...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gt2uvvzlpqu.html

[U90] JS：数字数组排序
来源：http://dali.bjfxy.top/Article/details/gt2ughhcqjo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gt2ogxlbmfw.html

[U91] JS：对象键值遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhaqgsko.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sweek.top/Article/details/gt2fxcupkie.html

[U92] JS：深拷贝
来源：http://dali.hnqzz.top/Article/details/gt2yzqihgpy.html

structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2ewiosemw.html

[U93] JS：模板字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2wklimxof.html

`共 ${n} 条`
来源：http://dali.shuidangran.top/Article/details/gt2xlgcvwsa.html

[U94] JS：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gt2yhdpthqk.html

const double = x => x * 2;
来源：http://dali.xinyue.icu/Article/details/gt2jspgubrq.html

[U95] JS：Promise 包装
来源：http://dali.jqgufenzy.top/Article/details/gt2ivypvmoe.html

new Promise((resolve, reject) => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpxoztgo.html

[U96] JS：async/await 与异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2dktillyw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjgrtnrp.html

[U97] JS：并发请求
来源：http://dali.xinyue.icu/Article/details/gt2oxbnqhri.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2hnbvrqxs.html

[U98] JS：fetch 带 JSON
来源：http://dali.cqqwz.cn/Article/details/gt2vdcafwof.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ydzc1.top/Article/details/gt2uwiyqmjj.html

[U99] JS：事件监听
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbyclfoe.html

el.addEventListener("click", e => {})
来源：http://dali.yanxiufei.cn/Article/details/gt2baurdrxk.html

[U100] JS：DOM 查询
来源：http://dali.yonumen.top/Article/details/gt2cxuckvqz.html

document.querySelector(".item")
来源：http://dali.yj20258888.top/Article/details/gt2yajdtqbg.html

[U101] JS：classList 操作
来源：http://dali.andypj.xyz/Article/details/gt2uqvuhhxr.html

el.classList.toggle("active")
来源：http://dali.ehwqpu.com/Article/details/gt2wwieakto.html

[U102] JS：本地存储
来源：http://dali.tianlin.xyz/Article/details/gt2anixouxk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ehwqpu.com/Article/details/gt2gctttbln.html

[U103] JS：定时器
来源：http://dali.ydzc1.top/Article/details/gt2lxcedvvo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ivvv.top/Article/details/gt2djvxdhoy.html

[U104] JS：防抖
来源：http://dali.yj202588.top/Article/details/gt2laomplmm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2xwbpxqui.html

[U105] JS：节流
来源：http://dali.shangyingyoupin.top/Article/details/gt2urzouprm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zdqjudy.top/Article/details/gt2pnvgimjh.html

[U106] JS：日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2gbeelgxl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dianchejie.cn/Article/details/gt2eyiossnk.html

[U107] JS：数字千分位
来源：http://dali.xylfe.cn/Article/details/gt2ccflkkey.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj202588.top/Article/details/gt2osqmbknd.html

[U108] JS：随机整数
来源：http://dali.svipenyu.cn/Article/details/gt2skagchsx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.birdmap.top/Article/details/gt2ohguqpej.html

[U109] JS：数组分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypxiwukn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gt2wjhbewbe.html

[U110] JS：数组分块
来源：http://dali.shangyingyoupin.top/Article/details/gt2tqcdmbyq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shzxlz.cn/Article/details/gt2kvevzywq.html

[U111] JS：对象转 Map
来源：http://dali.fengsongda.top/Article/details/gt2lykopfkw.html

new Map(Object.entries(obj))
来源：http://dali.yj202588.top/Article/details/gt2bpbjnbfh.html

[U112] JS：字符串补位
来源：http://dali.aibaodan.cn/Article/details/gt2buyzanzy.html

"7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2botahccl.html

[U113] JS：正则替换全部
来源：http://dali.hongshengwenyu.top/Article/details/gt2xisqrtmo.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qffqtlcm.html

[U114] JS：JSON 深比较
来源：http://dali.yanxiufei.cn/Article/details/gt2qzrgbmni.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2vwmylapd.html

[U115] JS：生成 UUID
来源：http://dali.hnqzz.top/Article/details/gt2fgcemurf.html

crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gt2ijhwzhsm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fzhhl.top/Article/details/gt2grgshvgv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2idnrdpfg.html

[U117] JS：单元测试
来源：http://dali.zhoulong.xyz/Article/details/gt2xxgkiyie.html

npm i -D vitest;  npx vitest
来源：http://dali.zhongyouzk.top/Article/details/gt2tihpigre.html

[U118] JS：开发服务器
来源：http://dali.cdnleiting.top/Article/details/gt2bsfqvfgn.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gt2ykrgoged.html

[U119] JS：生产构建
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkopqzby.html

npx vite build
来源：http://dali.zhongyouzk.top/Article/details/gt2voxwccnl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shzxlz.cn/Article/details/gt2oaonsntp.html

import.meta.env.VITE_API_URL
来源：http://dali.hnqzz.top/Article/details/gt2qtxxgocn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2rkeljimn.html

统计汇总
来源：http://dali.hnxiangtu.top/Article/details/gt2wbudpkbj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2kvhbzbij.html

按语言统计（条）：
来源：http://dali.yueranfly.top/Article/details/gt2fqikwnca.html

Python ......... 252
来源：http://dali.shuidangran.top/Article/details/gt2nchuyzfb.html

PHP ............ 252
来源：http://dali.kuanghao11.cn/Article/details/gt2tfswlicr.html

JavaScript ..... 252
来源：http://dali.daxiang520.top/Article/details/gt2awufwldx.html

TypeScript ..... 212
来源：http://dali.fengsongda.top/Article/details/gt2jwlsozsj.html

Java ........... 212
来源：http://dali.fzhhl.top/Article/details/gt2golssesg.html

Go ............. 212
来源：http://dali.havefunace.top/Article/details/gt2mczotjei.html

Ruby ........... 212
来源：http://dali.hfpthk.cn/Article/details/gt2sskffxsv.html

C# ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gt2ijbkddjh.html

C .............. 30
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwpzbcgm.html

C++ ............ 30
来源：http://dali.jianghu66.top/Article/details/gt2knhlkedl.html

SQL ............ 90
来源：http://dali.hysaishi.cn/Article/details/gt2tecvasxo.html

Bash ........... 80
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vndbbivn.html

Kotlin ......... 15
来源：http://dali.ybcxt.top/Article/details/gt2jvnbsyey.html

Swift .......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdcghwhk.html

Lua ............ 10
来源：http://dali.yueranfly.top/Article/details/gt2qfsaanry.html

Perl ........... 10
来源：http://dali.ehwqpu.com/Article/details/gt2rftqjwqy.html

Scala .......... 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dsmkzbgm.html

------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftcbjajv.html

合计 ........... 2106 条
来源：http://dali.redwolf501.top/Article/details/gt2kcehqcib.html

按章节统计：
来源：http://dali.9152youxi.cn/Article/details/gt2ukhsqpxt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gt2wmunmxcx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gt2dkahfmym.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gt2assqwyme.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gt2uaopuler.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzyqwpj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pycfn.com/Article/details/gt2qnkclmil.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hysaishi.cn/Article/details/gt2xuufjvrb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gt2lazntdwn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdvxzsfe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gt2dyrvulmy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gt2pepfhkyv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gt2qnwcffav.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gt2nlnhgkoc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gt2uvmqljna.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zdqjudy.top/Article/details/gt2gtmqybby.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gt2kfeidfcb.html

Q SQL 专题                              90
来源：http://dali.tanke756.top/Article/details/gt2hrcvzqjn.html

R Bash 专题                             80
来源：http://dali.xziqi.cn/Article/details/gt2kjooqwam.html

S C / C++ 专题                          60
来源：http://dali.svipenyu.cn/Article/details/gt2zpqftzyk.html

T 其他语言补充                          60
来源：http://dali.kuanghao11.cn/Article/details/gt2focfylpo.html

U 高频实用片段                         120
来源：http://dali.ydzc1.top/Article/details/gt2nsnmbnho.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2uyemfqrx.html

合计                                  2106 条
来源：http://dali.hnxiangtu.top/Article/details/gt2muzunxgi.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2syidhvol.html

使用提醒
来源：http://dali.shzxlz.cn/Article/details/gt2zbtkhgpf.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2psgstsfy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.bjfxy.top/Article/details/gt2pztqlwky.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tianlin.xyz/Article/details/gt2cmpxjacp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cucudq.cn/Article/details/gt2hkjquwco.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.iojbl.cn/Article/details/gt2bvxjdcgq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.bjfxy.top/Article/details/gt2ptovwnag.html

—— 文件结束 ——
来源：http://dali.chenzaomai.com/Article/details/gt2nqpwluhn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ewexnwxd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhiwuduotai.top/Article/details/gt2arazcmny.html

Common Programming Examples Cheat Book
来源：http://dali.dianchejie.cn/Article/details/gt2hxgbaoja.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2enpfqixu.html

【收录内容】
来源：http://dali.zhongyouzk.top/Article/details/gt2rjyemehe.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.bjfxy.top/Article/details/gt2wbgumcle.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yaznwcbu.html

SQL · Bash · C · C++
来源：http://dali.cucudq.cn/Article/details/gt2teuowkka.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.9152youxi.cn/Article/details/gt2qvdredll.html

【使用说明】
来源：http://dali.nanxuanxn.top/Article/details/gt2irfnutrg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ppjwa.cn/Article/details/gt2gyehqvhs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigufen.top/Article/details/gt2ugizxygu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj20258.top/Article/details/gt2glxjplrz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tianlin.xyz/Article/details/gt2apyvsyfq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.mhx1999.top/Article/details/gt2qzudlxcd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cdnleiting.top/Article/details/gt2yoqbvfyb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.iojbl.cn/Article/details/gt2sllzwwcv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yanxiufei.cn/Article/details/gt2yiymfnry.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ybcxt.top/Article/details/gt2tiwzkxhz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.mhx1999.top/Article/details/gt2jvzahxjp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.snrcjt.cn/Article/details/gt2wjlmwxdw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.dashuyun.cn/Article/details/gt2dyevkdxg.html

【文件统计】
来源：http://dali.redwolf501.top/Article/details/gt2bqcitsbp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drzlmqua.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gt2vgewyzhi.html

目  录
来源：http://dali.andypj.xyz/Article/details/gt2qljrxxel.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gt2zflcoojk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xziqi.cn/Article/details/gt2bpstzphu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gt2leyajoyi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gt2pkokbfup.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ydzc1.top/Article/details/gt2hhcblojl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gzhubu.top/Article/details/gt2bwzvhxxa.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ppjwa.cn/Article/details/gt2pgovlopi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2tomovtjv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinqigufen.top/Article/details/gt2fqpdjxhm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gt2qdioasux.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gt2yfloewoz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gt2khvxyieb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gt2eaijmhrq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gt2ubqrrdgm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhengqikj.top/Article/details/gt2bhxelgho.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ehwqpu.com/Article/details/gt2hjvjhwdf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2ygerhodo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenzaomai.com/Article/details/gt2ztgweiyu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.haohaochexian.top/Article/details/gt2rmjsbvji.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hammf.cn/Article/details/gt2jvpttdfh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gt2ftetjvwm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gt2hwakiimv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2jdrqxglv.html

A. 基础语法与类型
来源：http://dali.hnqzz.top/Article/details/gt2fmhcnuzs.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2halxaeqm.html

[A01] Hello World
来源：http://dali.ivvv.top/Article/details/gt2cuidrzoh.html

Py:   print("Hello, World!")
来源：http://dali.yangfankeji.com/Article/details/gt2jrcwqory.html

PHP:  echo "Hello, World!";
来源：http://dali.chenlongwang.top/Article/details/gt2zttpxsel.html

JS:   console.log("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gt2hzjrlqor.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.nanxinkj.top/Article/details/gt2ulbtwogy.html

Java: System.out.println("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gt2bcqnfctw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhongyouzk.top/Article/details/gt2ltgmpkni.html

Ruby: puts "Hello, World!"
来源：http://dali.nanxuanxn.top/Article/details/gt2cqxevtas.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jyoumei.cn/Article/details/gt2kpycfeih.html

[A02] 变量声明与赋值
来源：http://dali.cqqwz.cn/Article/details/gt2kmvorcwy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yueranfly.top/Article/details/gt2vzdlwtsm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.guowangkeji.top/Article/details/gt2vqdmntlz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jyoumei.cn/Article/details/gt2duaqqgxs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.snrcjt.cn/Article/details/gt2pnsgefnu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gt2gmnrhhec.html

Go:   name := "Alex"; age := 20
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcepwmpl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.svipenyu.cn/Article/details/gt2gnazttbe.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gt2qnknhuhu.html

[A03] 常量定义
来源：http://dali.zhengqikj.top/Article/details/gt2tiuocbqo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ydzc1.top/Article/details/gt2zakcjvbv.html

PHP:  const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2fkobqysi.html

JS:   const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2jfojbtlg.html

TS:   const PI: number = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2mozwgnvp.html

Java: static final double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2gpfvtcig.html

Go:   const PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gt2viguicxw.html

Ruby: PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gt2vfkxazwk.html

C#:   const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2fsamjzds.html

[A04] 判断变量类型
来源：http://dali.dashuyun.cn/Article/details/gt2dhllntuh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jyoumei.cn/Article/details/gt2tpbgdkmk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ppjwa.cn/Article/details/gt2rdymiriv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gt2sfnjomlm.html

TS:   typeof x; x instanceof Date
来源：http://dali.andypj.xyz/Article/details/gt2pqwogtat.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xziqi.cn/Article/details/gt2estoohri.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.smart0.xyz/Article/details/gt2qkcbswnj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yknckmba.html

C#:   x.GetType().Name; x is int
来源：http://dali.hammf.cn/Article/details/gt2gbtqwsnp.html

[A05] 整数除法与取模
来源：http://dali.quarkkingdee.top/Article/details/gt2dnqgtwjk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2npxysbel.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxwgqvkv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2sutvagic.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.guannengcc.top/Article/details/gt2ylwmgmcz.html

Java: 7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gt2dxodpmhp.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgxfxub.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gsazfmkc.html

C#:   7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gt2bylfhknf.html

[A06] 字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gt2ppdnrzxw.html

Py:   int("42"); float("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkedbnnx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yonumen.top/Article/details/gt2yvicjdmy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sxryk.cn/Article/details/gt2pdtrsvnd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.aizwys.cn/Article/details/gt2jncmphjf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cquwppqn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jyoumei.cn/Article/details/gt2yiwpyqxr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.fzhhl.top/Article/details/gt2kixgonmr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.fengsongda.top/Article/details/gt2zfqqunbd.html

[A07] 数字转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2zfiqpnlf.html

Py:   str(42)
来源：http://dali.jlsjyb.cn/Article/details/gt2ptxonczk.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinqigfzy.top/Article/details/gt2smypvctb.html

JS:   String(42); (42).toString()
来源：http://dali.smart0.xyz/Article/details/gt2kjlleyjs.html

TS:   String(42)
来源：http://dali.sufxvd.cn/Article/details/gt2zvcggbyj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqqvjrza.html

Go:   strconv.Itoa(42)
来源：http://dali.svipenyu.cn/Article/details/gt2kchalvfu.html

Ruby: 42.to_s
来源：http://dali.shzxlz.cn/Article/details/gt2fldgkxiy.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2msrjepfg.html

[A08] 取整与四舍五入
来源：http://dali.guowangkeji.top/Article/details/gt2itcvizwl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpsyqqye.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.svipenyu.cn/Article/details/gt2sojlolww.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gt2gmgmiyro.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibxbqzez.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gt2okpydxww.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gt2lmbihfuz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.feifeiyinyue.top/Article/details/gt2qayqpcyw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gt2vfkqjndc.html

[A09] 绝对值与最大最小值
来源：http://dali.iojbl.cn/Article/details/gt2mokqingy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2qzhaoaqk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2vmjhxovo.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2acnaavhd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258888.top/Article/details/gt2sknjpsfl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2hzdvwwct.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcjbrdhc.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shuidangran.top/Article/details/gt2ukmkklpw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2pmtzpuks.html

[A10] 生成随机数
来源：http://dali.redwolf501.top/Article/details/gt2bwiguflu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yangfankeji.com/Article/details/gt2pgbmmbcs.html

PHP:  random_int(1, 100);
来源：http://dali.birdmap.top/Article/details/gt2jahaprgj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.vqdsnc.cn/Article/details/gt2lcgzzhhq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.316326.xyz/Article/details/gt2dxedotjj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sysykeji.top/Article/details/gt2pnktlyru.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xylfe.cn/Article/details/gt2udzdcoys.html

Ruby: rand(1..100)
来源：http://dali.svipenyu.cn/Article/details/gt2eppgoxag.html

C#:   new Random().Next(1, 101)
来源：http://dali.guowangkeji.top/Article/details/gt2reikfiyj.html

[A11] 条件表达式（三元）
来源：http://dali.gaohongyu789.top/Article/details/gt2gpktqguv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cucudq.cn/Article/details/gt2fsludpja.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gt2qwlvywvm.html


<!-- 参考信息 -->