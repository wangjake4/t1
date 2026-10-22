代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.yuanzhike.top/Article/details/gt2ftigifku.html

throw new RuntimeException("失败", 500);
来源：http://dali.hywenlv.cn/Article/details/gt2qnlsiuuw.html

[U72] PHP：写错误日志
来源：http://dali.zdqjudy.top/Article/details/gt2txorwmtj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuxming.cn/Article/details/gt2iakjrzpp.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkzbmnrz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhongyouzk.top/Article/details/gt2bupvikvx.html

[U74] PHP：读取环境变量
来源：http://dali.yongpay.top/Article/details/gt2btlvntze.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jlsjyb.cn/Article/details/gt2ladutajt.html

[U75] PHP：依赖注入
来源：http://dali.zhongyouzk.top/Article/details/gt2qaeouqes.html

composer require psr/container
来源：http://dali.jqgfzy.top/Article/details/gt2idvfkrun.html

[U76] PHP：简单路由
来源：http://dali.dianchejie.cn/Article/details/gt2qudbhtnj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nchturmu.html

[U77] PHP：模板渲染
来源：http://dali.sxryk.cn/Article/details/gt2zdqjspbj.html

composer require twig/twig
来源：http://dali.zhoulong.xyz/Article/details/gt2hkshchen.html

[U78] PHP：单元测试
来源：http://dali.sysykeji.top/Article/details/gt2ynqqrghz.html

composer require --dev phpunit/phpunit
来源：http://dali.andypj.xyz/Article/details/gt2spnmnqiz.html

[U79] PHP：静态分析
来源：http://dali.daxiang520.top/Article/details/gt2aodzxzgf.html

composer require --dev phpstan/phpstan
来源：http://dali.daxiang520.top/Article/details/gt2nfzmmkak.html

[U80] PHP：代码规范修复
来源：http://dali.redwolf501.top/Article/details/gt2lpgdyqtt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgfbetyt.html

[U81] JS：初始化项目
来源：http://dali.nanxinkj.top/Article/details/gt2hfmjrjkk.html

npm init -y;  npm i express
来源：http://dali.xylfe.cn/Article/details/gt2qfdqeson.html

[U82] JS：package.json 脚本
来源：http://dali.zdqjudy.top/Article/details/gt2rafczcqy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfybeaar.html

[U83] JS：ES Module 导入导出
来源：http://dali.c1oappe.top/Article/details/gt2yceuryea.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gt2pbervovp.html

[U84] JS：CommonJS 写法
来源：http://dali.zdqjudy.top/Article/details/gt2jcdsbszz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xuetiantiany.cn/Article/details/gt2epqddmxn.html

[U85] JS：可选链
来源：http://dali.pycfn.com/Article/details/gt2tpodgilm.html

a?.b?.c
来源：http://dali.yangfankeji.com/Article/details/gt2ngjrbciz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdetvtp.html

a ?? b
来源：http://dali.jlsjyb.cn/Article/details/gt2sspiffih.html

[U87] JS：解构默认值
来源：http://dali.cucudq.cn/Article/details/gt2xkrlcjux.html

const { a = 1, b = 2 } = obj;
来源：http://dali.316326.xyz/Article/details/gt2juyihixt.html

[U88] JS：对象展开合并
来源：http://dali.aizwys.cn/Article/details/gt2bbhdtjjn.html

{ ...a, ...b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvrbscah.html

[U89] JS：数组去重
来源：http://dali.zdqjudy.top/Article/details/gt2pxrhzivu.html

[...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofxgsfiq.html

[U90] JS：数字数组排序
来源：http://dali.shuidangran.top/Article/details/gt2wgucwmyz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utjmoguk.html

[U91] JS：对象键值遍历
来源：http://dali.andypj.xyz/Article/details/gt2nkraspli.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.havefunace.top/Article/details/gt2dvbcqhdn.html

[U92] JS：深拷贝
来源：http://dali.hnxiangtu.top/Article/details/gt2bhyqaqbc.html

structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gt2ahvsanql.html

[U93] JS：模板字符串
来源：http://dali.xinyue.icu/Article/details/gt2ceoazrzn.html

`共 ${n} 条`
来源：http://dali.cqqwz.cn/Article/details/gt2xghsfube.html

[U94] JS：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gt2rmpyhdgo.html

const double = x => x * 2;
来源：http://dali.yj202588.top/Article/details/gt2ccivlplr.html

[U95] JS：Promise 包装
来源：http://dali.feifeiyinyue.top/Article/details/gt2prlfmzkc.html

new Promise((resolve, reject) => {})
来源：http://dali.jlsjyb.cn/Article/details/gt2ogwnhsrd.html

[U96] JS：async/await 与异常
来源：http://dali.dianchejie.cn/Article/details/gt2htinkwmb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2mpkecbbs.html

[U97] JS：并发请求
来源：http://dali.jyoumei.cn/Article/details/gt2swxilvsz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2jntaepwp.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2javroxya.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhixingplan.top/Article/details/gt2syilprth.html

[U99] JS：事件监听
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfsvnhiq.html

el.addEventListener("click", e => {})
来源：http://dali.dianchejie.cn/Article/details/gt2zlfidlwi.html

[U100] JS：DOM 查询
来源：http://dali.cheryme.top/Article/details/gt2cumioswi.html

document.querySelector(".item")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldalkirw.html

[U101] JS：classList 操作
来源：http://dali.cdnleiting.top/Article/details/gt2vjlqsknz.html

el.classList.toggle("active")
来源：http://dali.yueranfly.top/Article/details/gt2ohoiqqwx.html

[U102] JS：本地存储
来源：http://dali.yangfankeji.com/Article/details/gt2datymvot.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yongpay.top/Article/details/gt2zwmzxbuz.html

[U103] JS：定时器
来源：http://dali.vqdsnc.cn/Article/details/gt2huyagaua.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwfaqurk.html

[U104] JS：防抖
来源：http://dali.guowangkeji.top/Article/details/gt2epwghqac.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2ntrvzjey.html

[U105] JS：节流
来源：http://dali.dianchejie.cn/Article/details/gt2zhcfoekb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gt2hbmufftk.html

[U106] JS：日期格式化
来源：http://dali.bjfxy.top/Article/details/gt2gkwdsvip.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sysykeji.top/Article/details/gt2hfcwiyyv.html

[U107] JS：数字千分位
来源：http://dali.yuanzhike.top/Article/details/gt2tolbdyqf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gt2niccskpo.html

[U108] JS：随机整数
来源：http://dali.birdmap.top/Article/details/gt2oowqiogt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.316326.xyz/Article/details/gt2kabdxhez.html

[U109] JS：数组分组
来源：http://dali.shuidangran.top/Article/details/gt2whvxmihg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gt2nbusqkat.html

[U110] JS：数组分块
来源：http://dali.c1oappe.top/Article/details/gt2clvofyjp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hfpthk.cn/Article/details/gt2qojvgfkc.html

[U111] JS：对象转 Map
来源：http://dali.sufxvd.cn/Article/details/gt2etipqlss.html

new Map(Object.entries(obj))
来源：http://dali.hammf.cn/Article/details/gt2cjrdqyjd.html

[U112] JS：字符串补位
来源：http://dali.hammf.cn/Article/details/gt2jgpsgyqm.html

"7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2jmysmrsu.html

[U113] JS：正则替换全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmdqnosn.html

s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2znzromsm.html

[U114] JS：JSON 深比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfympmja.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqckcmbk.html

[U115] JS：生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gt2ukzdlmsf.html

crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2tayxrokn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tianlin.xyz/Article/details/gt2pkqaqzig.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ybcxt.top/Article/details/gt2uanbunou.html

[U117] JS：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifxovvut.html

npm i -D vitest;  npx vitest
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plalepjf.html

[U118] JS：开发服务器
来源：http://dali.aizwys.cn/Article/details/gt2ywihkkhr.html

npm i -D vite;  npx vite
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdqbbbfw.html

[U119] JS：生产构建
来源：http://dali.jinqigfzy.top/Article/details/gt2bssthsgi.html

npx vite build
来源：http://dali.yangfankeji.com/Article/details/gt2aakuogsh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jyoumei.cn/Article/details/gt2sihzjbny.html

import.meta.env.VITE_API_URL
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smaalyju.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2jmyulzme.html

统计汇总
来源：http://dali.zhiwuduotai.top/Article/details/gt2vnkrpmyb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2tplkfloe.html

按语言统计（条）：
来源：http://dali.jianghu66.top/Article/details/gt2kkhfevna.html

Python ......... 252
来源：http://dali.xuanzx.com/Article/details/gt2anrpwpyx.html

PHP ............ 252
来源：http://dali.bjfxy.top/Article/details/gt2wincoahw.html

JavaScript ..... 252
来源：http://dali.xinyue.icu/Article/details/gt2obihtprp.html

TypeScript ..... 212
来源：http://dali.gotoacloud.top/Article/details/gt2pixnzdeu.html

Java ........... 212
来源：http://dali.dianchejie.cn/Article/details/gt2kasnnvvu.html

Go ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjamjgld.html

Ruby ........... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gixrsmsr.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gt2vijptizo.html

C .............. 30
来源：http://dali.yuxming.cn/Article/details/gt2zjjissak.html

C++ ............ 30
来源：http://dali.yvedp.cn/Article/details/gt2xirfpcus.html

SQL ............ 90
来源：http://dali.meibo888.top/Article/details/gt2dumonqhd.html

Bash ........... 80
来源：http://dali.smart0.xyz/Article/details/gt2fatmpnuf.html

Kotlin ......... 15
来源：http://dali.meibo888.top/Article/details/gt2yhludhsh.html

Swift .......... 15
来源：http://dali.gaohongyu789.top/Article/details/gt2eotvqzxx.html

Lua ............ 10
来源：http://dali.zhixingplan.top/Article/details/gt2yxvdapto.html

Perl ........... 10
来源：http://dali.0kj1m.cn/Article/details/gt2lpkfffep.html

Scala .......... 10
来源：http://dali.yj20258888.top/Article/details/gt2pltgoywf.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gt2hvtkjwgf.html

合计 ........... 2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcedknmf.html

按章节统计：
来源：http://dali.aibaodan.cn/Article/details/gt2hwnbuxix.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.dianchejie.cn/Article/details/gt2gklcefzr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gt2wsbzvzbw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gt2jkulpdsx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gt2qbgglmdo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xuanzx.com/Article/details/gt2idbtuqif.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenzaomai.com/Article/details/gt2bpbardaj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2ebhpghmc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuanzhike.top/Article/details/gt2dsrcfpas.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gt2zvwlqebx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owjtnuzh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gt2dchjgxjl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gt2qvmpkoiv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2lpivevcj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cashguo.top/Article/details/gt2enpumjnm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenlongwang.top/Article/details/gt2thopmdbc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gt2lyizszck.html

Q SQL 专题                              90
来源：http://dali.svipenyu.cn/Article/details/gt2djvxqckg.html

R Bash 专题                             80
来源：http://dali.cdnleiting.top/Article/details/gt2warbbrwk.html

S C / C++ 专题                          60
来源：http://dali.tianlin.xyz/Article/details/gt2zpibjxoa.html

T 其他语言补充                          60
来源：http://dali.gzhubu.top/Article/details/gt2zxjxwryy.html

U 高频实用片段                         120
来源：http://dali.meibo888.top/Article/details/gt2orpkboty.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gt2jubcrldj.html

合计                                  2106 条
来源：http://dali.yj20258888.top/Article/details/gt2iwkaehkz.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2nbrzwbaa.html

使用提醒
来源：http://dali.zhiwuduotai.top/Article/details/gt2wohuvnqp.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2bjfqynly.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvgdgzbp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yvedp.cn/Article/details/gt2zeynnfke.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ivvv.top/Article/details/gt2izkpjnvg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxuanxn.top/Article/details/gt2wdufyvnp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shuidangran.top/Article/details/gt2mxpzcadh.html

—— 文件结束 ——
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpwuccnq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2rtpoiyuv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xuanzx.com/Article/details/gt2vluqmyni.html

Common Programming Examples Cheat Book
来源：http://dali.hysaishi.cn/Article/details/gt2yetxwajl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2rejeywcg.html

【收录内容】
来源：http://dali.yanxiufei.cn/Article/details/gt2malztfvr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtyozbvd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwuedlev.html

SQL · Bash · C · C++
来源：http://dali.shzxlz.cn/Article/details/gt2jfgygqhw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yvedp.cn/Article/details/gt2vqxdgwrd.html

【使用说明】
来源：http://dali.smart0.xyz/Article/details/gt2rlekabrl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.mhx1999.top/Article/details/gt2tvvksoml.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hfpthk.cn/Article/details/gt2ksnqufac.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.haohaochexian.top/Article/details/gt2xbgqafum.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuanzhike.top/Article/details/gt2jpqzacua.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenzaomai.com/Article/details/gt2feqodhki.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cucudq.cn/Article/details/gt2radnxolm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yanxiufei.cn/Article/details/gt2ovljwohq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yonumen.top/Article/details/gt2qduqizsy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xinyue.icu/Article/details/gt2xpdthvlr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.feifeiyinyue.top/Article/details/gt2viubosfw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yj202588.top/Article/details/gt2yvlfsoyc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cheryme.top/Article/details/gt2olpfvrfy.html

【文件统计】
来源：http://dali.yj20258888.top/Article/details/gt2kgfjlylm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.316326.xyz/Article/details/gt2wlkscbzp.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfmxibmc.html

目  录
来源：http://dali.sysykeji.top/Article/details/gt2tqwzomka.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gt2nciyonmk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.daria6918.cn/Article/details/gt2hbqezfrb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gt2mycrddae.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gt2brlhhmko.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hammf.cn/Article/details/gt2clhqmaqs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.wangdashe.top/Article/details/gt2smdbwvmv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2gzvvukxt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gt2nwrufznb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinqigufen.top/Article/details/gt2afvpaexx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2jjbaaynq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2ozvpfmro.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gt2jmsdcriv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gt2dqlkgdye.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gt2wuorbiwr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbhspjyr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cdnleiting.top/Article/details/gt2fvfafxue.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gt2clnijens.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sweek.top/Article/details/gt2cjmzewwe.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zycfv.cn/Article/details/gt2leeynsng.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqmjutco.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gt2borohhbh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gt2zskzgopy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2aqdkshaq.html

A. 基础语法与类型
来源：http://dali.yuanzhike.top/Article/details/gt2iglswqns.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2dlvdlkgo.html

[A01] Hello World
来源：http://dali.aizwys.cn/Article/details/gt2cdugigzy.html

Py:   print("Hello, World!")
来源：http://dali.quarkkingdee.top/Article/details/gt2ktfhhiwm.html

PHP:  echo "Hello, World!";
来源：http://dali.cdnleiting.top/Article/details/gt2ismymaga.html

JS:   console.log("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrrsecoh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.aibaodan.cn/Article/details/gt2uxhbkwfc.html

Java: System.out.println("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gt2ynlggzur.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gt2kzyqqmvd.html

Ruby: puts "Hello, World!"
来源：http://dali.wangdashe.top/Article/details/gt2lfataryb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sweek.top/Article/details/gt2elumqyai.html

[A02] 变量声明与赋值
来源：http://dali.ehwqpu.com/Article/details/gt2xuszfmzf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tanke756.top/Article/details/gt2bqtjmxxk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zycfv.cn/Article/details/gt2mmqsbxnt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yongpay.top/Article/details/gt2lxxbjxqz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hfpthk.cn/Article/details/gt2trkkvyjo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shzxlz.cn/Article/details/gt2izorkubo.html

Go:   name := "Alex"; age := 20
来源：http://dali.ybcxt.top/Article/details/gt2wjczzqbx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.svipenyu.cn/Article/details/gt2idtlqshp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gt2aamhilgy.html

[A03] 常量定义
来源：http://dali.tianlin.xyz/Article/details/gt2hfizdbui.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.aibaodan.cn/Article/details/gt2auxljjnp.html

PHP:  const PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvgsauyp.html

JS:   const PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2qnnlpjek.html

TS:   const PI: number = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2myacqgdv.html

Java: static final double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2knxghglg.html

Go:   const PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gt2ujvoljrg.html

Ruby: PI = 3.14159
来源：http://dali.gaohongyu789.top/Article/details/gt2fzjgwxkr.html

C#:   const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2mwposqbm.html

[A04] 判断变量类型
来源：http://dali.yvedp.cn/Article/details/gt2fdvsuecb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dyojtrgc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.fengsongda.top/Article/details/gt2geynwgfo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yonumen.top/Article/details/gt2yrklfpbf.html

TS:   typeof x; x instanceof Date
来源：http://dali.gzhubu.top/Article/details/gt2udruuoug.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangdashe.top/Article/details/gt2oxauffvu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.havefunace.top/Article/details/gt2hdqjcaou.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.guowangkeji.top/Article/details/gt2lxnzsknx.html

C#:   x.GetType().Name; x is int
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldlljkrw.html

[A05] 整数除法与取模
来源：http://dali.yangfankeji.com/Article/details/gt2sklhqguy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hnqzz.top/Article/details/gt2wvmwrjts.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2rqscixqb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gt2hrjprimh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sweek.top/Article/details/gt2vwedarng.html

Java: 7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2mhllzsie.html

Go:   7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gt2twtcufmv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2hjxuovcj.html

C#:   7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gt2ihvrzimo.html

[A06] 字符串转数字
来源：http://dali.cashguo.top/Article/details/gt2vwcnpqyk.html

Py:   int("42"); float("3.14")
来源：http://dali.hysaishi.cn/Article/details/gt2lqoulozz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jqgfzy.top/Article/details/gt2pxsavhpt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.iojbl.cn/Article/details/gt2vejugtfv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.316326.xyz/Article/details/gt2blndlvys.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gzhubu.top/Article/details/gt2gqqfirvh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cashguo.top/Article/details/gt2mlpqpiko.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jqgfzy.top/Article/details/gt2prfaxszf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjuijozh.html

[A07] 数字转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpduwsog.html

Py:   str(42)
来源：http://dali.hammf.cn/Article/details/gt2fihrfczt.html

PHP:  (string) 42; strval(42)
来源：http://dali.smart0.xyz/Article/details/gt2swrbypau.html

JS:   String(42); (42).toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2ngzxigvy.html

TS:   String(42)
来源：http://dali.cucudq.cn/Article/details/gt2vgknlznv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.fzhhl.top/Article/details/gt2gljzdtyq.html

Go:   strconv.Itoa(42)
来源：http://dali.yangfankeji.com/Article/details/gt2ffkpfhka.html

Ruby: 42.to_s
来源：http://dali.fengsongda.top/Article/details/gt2lehcovms.html

C#:   42.ToString()
来源：http://dali.nwbrower.top/Article/details/gt2phsjmdfo.html

[A08] 取整与四舍五入
来源：http://dali.smart0.xyz/Article/details/gt2xcfnduxz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gt2ajtwdmxz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.chenlongwang.top/Article/details/gt2msymlzbs.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gt2gqsewafx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.aizwys.cn/Article/details/gt2bcvapvtl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gt2znqjjamq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj20258.top/Article/details/gt2sooypfvs.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yanxiufei.cn/Article/details/gt2vtjjdqnx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gt2vlxpftsl.html

[A09] 绝对值与最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2wslbtmkd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gt2ewvhbhhl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmeolxma.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gt2elyxcoln.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2cxpykone.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2azpyiery.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ivvv.top/Article/details/gt2wdekbwob.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cucudq.cn/Article/details/gt2dfzryuyw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2usnqhzww.html

[A10] 生成随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnbgojba.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yuxming.cn/Article/details/gt2xsqkzysc.html

PHP:  random_int(1, 100);
来源：http://dali.sweek.top/Article/details/gt2gamjqddb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tian-w.cn/Article/details/gt2lypewzmw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hnqzz.top/Article/details/gt2vejgirok.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hnqzz.top/Article/details/gt2rmgllmyg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gzhubu.top/Article/details/gt2fmvnssaq.html

Ruby: rand(1..100)
来源：http://dali.bjfxy.top/Article/details/gt2lbyhbpct.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhixingplan.top/Article/details/gt2ngdbtndz.html

[A11] 条件表达式（三元）
来源：http://dali.haohaochexian.top/Article/details/gt2akddzhmw.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.smart0.xyz/Article/details/gt2lxxlijsh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gt2athwogqd.html


<!-- 参考信息 -->