代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.andypj.xyz/Article/details/gt2rrowiuou.html

composer require psr/container
来源：http://dali.pycfn.com/Article/details/gt2dtpryrxw.html

[U76] PHP：简单路由
来源：http://dali.wangdashe.top/Article/details/gt2ygvbxpjn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.quarkkingdee.top/Article/details/gt2busovkqd.html

[U77] PHP：模板渲染
来源：http://dali.zdqjudy.top/Article/details/gt2iuytumlo.html

composer require twig/twig
来源：http://dali.dianchejie.cn/Article/details/gt2yyindoch.html

[U78] PHP：单元测试
来源：http://dali.dianchejie.cn/Article/details/gt2osmnhafc.html

composer require --dev phpunit/phpunit
来源：http://dali.316326.xyz/Article/details/gt2gzfsaold.html

[U79] PHP：静态分析
来源：http://dali.cheryme.top/Article/details/gt2bjqpjiay.html

composer require --dev phpstan/phpstan
来源：http://dali.ivvv.top/Article/details/gt2fywtmfjq.html

[U80] PHP：代码规范修复
来源：http://dali.zhoulong.xyz/Article/details/gt2suuvfiak.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sysykeji.top/Article/details/gt2tkteujzi.html

[U81] JS：初始化项目
来源：http://dali.yangfankeji.com/Article/details/gt2yljkcoka.html

npm init -y;  npm i express
来源：http://dali.guowangkeji.top/Article/details/gt2xtyszgsw.html

[U82] JS：package.json 脚本
来源：http://dali.redwolf501.top/Article/details/gt2thcpyxhf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.meibo888.top/Article/details/gt2cluutdfl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhixingplan.top/Article/details/gt2tccsxsar.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aeuxxyjo.html

[U84] JS：CommonJS 写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmknrcum.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edliejln.html

[U85] JS：可选链
来源：http://dali.jiagoushi.top/Article/details/gt2keibzidv.html

a?.b?.c
来源：http://dali.guowangkeji.top/Article/details/gt2lovphppw.html

[U86] JS：空值合并
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywkvmafn.html

a ?? b
来源：http://dali.ybcxt.top/Article/details/gt2cugldoox.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjotoqu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivephhqv.html

[U88] JS：对象展开合并
来源：http://dali.jqgfzy.top/Article/details/gt2tygaxpch.html

{ ...a, ...b }
来源：http://dali.zhoulong.xyz/Article/details/gt2kwqmhnoa.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdqxwbq.html

[...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gt2aiaverjg.html

[U90] JS：数字数组排序
来源：http://dali.shuidangran.top/Article/details/gt2sqfjfavc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2obfvqrjr.html

[U91] JS：对象键值遍历
来源：http://dali.sxryk.cn/Article/details/gt2whxtplru.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.316326.xyz/Article/details/gt2slxjohyl.html

[U92] JS：深拷贝
来源：http://dali.jqgufenzy.top/Article/details/gt2ymiuhreg.html

structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2ftrvlwop.html

[U93] JS：模板字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zahxsyte.html

`共 ${n} 条`
来源：http://dali.chenlongwang.top/Article/details/gt2zkpvqpua.html

[U94] JS：箭头函数
来源：http://dali.yvedp.cn/Article/details/gt2egaqsxuw.html

const double = x => x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvmmpfre.html

[U95] JS：Promise 包装
来源：http://dali.jiagoushi.top/Article/details/gt2demkyyep.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgufenzy.top/Article/details/gt2mmiwdift.html

[U96] JS：async/await 与异常
来源：http://dali.nanxuanxn.top/Article/details/gt2elppfgsm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gt2wbkewgpj.html

[U97] JS：并发请求
来源：http://dali.cucudq.cn/Article/details/gt2kqsgmmoo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gt2emgdnimi.html

[U98] JS：fetch 带 JSON
来源：http://dali.jyoumei.cn/Article/details/gt2zwsjaiqq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hysaishi.cn/Article/details/gt2temgipub.html

[U99] JS：事件监听
来源：http://dali.aibaodan.cn/Article/details/gt2qijxwbgl.html

el.addEventListener("click", e => {})
来源：http://dali.nwbrower.top/Article/details/gt2fndogezp.html

[U100] JS：DOM 查询
来源：http://dali.zhengqikj.top/Article/details/gt2nslebzyh.html

document.querySelector(".item")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yivvitci.html

[U101] JS：classList 操作
来源：http://dali.sweek.top/Article/details/gt2lyjoqpzs.html

el.classList.toggle("active")
来源：http://dali.zdqjudy.top/Article/details/gt2kaoyceqq.html

[U102] JS：本地存储
来源：http://dali.nanxuanxn.top/Article/details/gt2vjckskjs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgufenzy.top/Article/details/gt2qoswqtpb.html

[U103] JS：定时器
来源：http://dali.fengsongda.top/Article/details/gt2njxkqvam.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigufen.top/Article/details/gt2bajxzhml.html

[U104] JS：防抖
来源：http://dali.sysykeji.top/Article/details/gt2iiokrfgd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2zifcitpe.html

[U105] JS：节流
来源：http://dali.smart0.xyz/Article/details/gt2woxyjimk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.bjfxy.top/Article/details/gt2bofwhkgc.html

[U106] JS：日期格式化
来源：http://dali.aizwys.cn/Article/details/gt2mwwrkzcf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.svipenyu.cn/Article/details/gt2ukcqpijh.html

[U107] JS：数字千分位
来源：http://dali.0kj1m.cn/Article/details/gt2iskjscur.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yvedp.cn/Article/details/gt2gsknxejj.html

[U108] JS：随机整数
来源：http://dali.gogol.net.cn/Article/details/gt2korezfok.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ydzc1.top/Article/details/gt2cgakymfa.html

[U109] JS：数组分组
来源：http://dali.jinqigufen.top/Article/details/gt2ieyqgoqi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gt2pdhpqhcw.html

[U110] JS：数组分块
来源：http://dali.hnxiangtu.top/Article/details/gt2rcezacxw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmfcwcvs.html

[U111] JS：对象转 Map
来源：http://dali.sysykeji.top/Article/details/gt2ihfcoblk.html

new Map(Object.entries(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2jtvsrigk.html

[U112] JS：字符串补位
来源：http://dali.cashguo.top/Article/details/gt2oisqxqkt.html

"7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2svvmzeos.html

[U113] JS：正则替换全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwvuuaar.html

s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2ozzguwli.html

[U114] JS：JSON 深比较
来源：http://dali.ehwqpu.com/Article/details/gt2mlzwyhhi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2erpehzpz.html

[U115] JS：生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvevahey.html

crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljouhjdj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ybcxt.top/Article/details/gt2cjhdplyb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.birdmap.top/Article/details/gt2ewflvrxz.html

[U117] JS：单元测试
来源：http://dali.yuanzhike.top/Article/details/gt2alsrrvxa.html

npm i -D vitest;  npx vitest
来源：http://dali.jianghu66.top/Article/details/gt2hhbaorbr.html

[U118] JS：开发服务器
来源：http://dali.iojbl.cn/Article/details/gt2phqpvsfr.html

npm i -D vite;  npx vite
来源：http://dali.wangshuangyany.cn/Article/details/gt2eiwjkzbv.html

[U119] JS：生产构建
来源：http://dali.zdqjudy.top/Article/details/gt2lkhfnlbb.html

npx vite build
来源：http://dali.sufxvd.cn/Article/details/gt2fgkymdos.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhiwuduotai.top/Article/details/gt2xtspodud.html

import.meta.env.VITE_API_URL
来源：http://dali.dianchejie.cn/Article/details/gt2qmwyyode.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2tcxqkint.html

统计汇总
来源：http://dali.havefunace.top/Article/details/gt2uirvzmux.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2xnwfrhdn.html

按语言统计（条）：
来源：http://dali.tanke756.top/Article/details/gt2pdcfvgjo.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gt2lcsofgym.html

PHP ............ 252
来源：http://dali.tian-w.cn/Article/details/gt2htfzujdl.html

JavaScript ..... 252
来源：http://dali.yj202588.top/Article/details/gt2iotsxzws.html

TypeScript ..... 212
来源：http://dali.gogol.net.cn/Article/details/gt2ejnmagsj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2layjkapw.html

Go ............. 212
来源：http://dali.tanke756.top/Article/details/gt2izeygjoj.html

Ruby ........... 212
来源：http://dali.cashguo.top/Article/details/gt2oztzcplp.html

C# ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gt2drbmockl.html

C .............. 30
来源：http://dali.xuetiantiany.cn/Article/details/gt2cexhxqiv.html

C++ ............ 30
来源：http://dali.9152youxi.cn/Article/details/gt2tbozbipe.html

SQL ............ 90
来源：http://dali.aizwys.cn/Article/details/gt2fbzgjvhu.html

Bash ........... 80
来源：http://dali.sxryk.cn/Article/details/gt2hjcrsror.html

Kotlin ......... 15
来源：http://dali.sxryk.cn/Article/details/gt2cnfncqky.html

Swift .......... 15
来源：http://dali.pycfn.com/Article/details/gt2cejpjfzm.html

Lua ............ 10
来源：http://dali.cdnleiting.top/Article/details/gt2zwhofewd.html

Perl ........... 10
来源：http://dali.jianghu66.top/Article/details/gt2aslrljev.html

Scala .......... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2reqkuldo.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gt2azntgdzw.html

合计 ........... 2106 条
来源：http://dali.chenzaomai.com/Article/details/gt2qaptlpex.html

按章节统计：
来源：http://dali.chenlongwang.top/Article/details/gt2hxqnfozk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gt2jzgkzmjb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gt2pqocdlvm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gt2kmeojgmc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfmlbqdm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinqigufen.top/Article/details/gt2cpttoyff.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cwmehtgp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gt2oeoucrii.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gt2rnddpjni.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2fcmmfaqo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sufxvd.cn/Article/details/gt2feylpbpe.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djobvbja.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gt2izhwkhne.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gt2sueyiomo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkwgytyg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tanke756.top/Article/details/gt2robpkejr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2inbfkjda.html

Q SQL 专题                              90
来源：http://dali.sweek.top/Article/details/gt2ptambrre.html

R Bash 专题                             80
来源：http://dali.jqgufenzy.top/Article/details/gt2sclndkaw.html

S C / C++ 专题                          60
来源：http://dali.bjfxy.top/Article/details/gt2xrgbspug.html

T 其他语言补充                          60
来源：http://dali.aibaodan.cn/Article/details/gt2jauivcjb.html

U 高频实用片段                         120
来源：http://dali.ppjwa.cn/Article/details/gt2swshylik.html

------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gt2seuoqeuj.html

合计                                  2106 条
来源：http://dali.chenjidiqi.icu/Article/details/gt2yarudyku.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gt2xejbvzkc.html

使用提醒
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqfxynzf.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2dtzciqyx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxibuvaw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhiwuduotai.top/Article/details/gt2gikmekcl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daria6918.cn/Article/details/gt2zlzsdqjt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.andypj.xyz/Article/details/gt2ghgcrvak.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gzhubu.top/Article/details/gt2amribylz.html

—— 文件结束 ——
来源：http://dali.gotoacloud.top/Article/details/gt2ugnywlco.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2zdtuahnb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258888.top/Article/details/gt2qansskay.html

Common Programming Examples Cheat Book
来源：http://dali.hysaishi.cn/Article/details/gt2fthwxcso.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2fjxlwxxg.html

【收录内容】
来源：http://dali.zhengqikj.top/Article/details/gt2dtixcznh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ydzc1.top/Article/details/gt2uizlugtm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ppjwa.cn/Article/details/gt2itfequvl.html

SQL · Bash · C · C++
来源：http://dali.chenlongwang.top/Article/details/gt2kppipkyy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj20258.top/Article/details/gt2zzlzpohm.html

【使用说明】
来源：http://dali.jinqigufen.top/Article/details/gt2kyibyjrc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zycfv.cn/Article/details/gt2uucmmivt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenzaomai.com/Article/details/gt2fgukdrbu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zycfv.cn/Article/details/gt2zbjfeewp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.pycfn.com/Article/details/gt2gsghjjwh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.quarkkingdee.top/Article/details/gt2ensorapu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.svipenyu.cn/Article/details/gt2gcdypjdz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ydzc1.top/Article/details/gt2ylfpcbcn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvkdjcvh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zdqjudy.top/Article/details/gt2ffmtukez.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gt2moobxlio.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.wangdashe.top/Article/details/gt2zwljydnx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shzxlz.cn/Article/details/gt2aqdgyeux.html

【文件统计】
来源：http://dali.jqgfzy.top/Article/details/gt2nwkjrbup.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yongpay.top/Article/details/gt2jrlwflxg.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2wgsktuik.html

目  录
来源：http://dali.yanxiufei.cn/Article/details/gt2blvmmclj.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gt2qvkixkos.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtenense.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gt2vetpzoja.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhixingplan.top/Article/details/gt2idjrqwpv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2eokvyump.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnqzz.top/Article/details/gt2jpdkttyz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojqblavj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gt2dhktqdwx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2bggqhmfc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2pbvejwaz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gt2jfxvboff.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gt2zluknfdl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gt2gvojwteg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gt2mknvujak.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzlygfaj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.smart0.xyz/Article/details/gt2jjdftecj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gt2grabyudg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.dashuyun.cn/Article/details/gt2icrlcaub.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cheryme.top/Article/details/gt2unzqihgk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xuanzx.com/Article/details/gt2zjgbmrdz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gt2esjcvrsw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gt2mjauyjpd.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2hatrbmqr.html

A. 基础语法与类型
来源：http://dali.sysykeji.top/Article/details/gt2enpzufsg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptnzmeou.html

[A01] Hello World
来源：http://dali.yj20258.top/Article/details/gt2bxneytnv.html

Py:   print("Hello, World!")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hczucngb.html

PHP:  echo "Hello, World!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkpoyyho.html

JS:   console.log("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gt2nsdrtsne.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cheryme.top/Article/details/gt2mfhodkwt.html

Java: System.out.println("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gt2gvmvtyqf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.kuanghao11.cn/Article/details/gt2nwnrwrae.html

Ruby: puts "Hello, World!"
来源：http://dali.fzhhl.top/Article/details/gt2cwjcmduv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gt2sqimjjms.html

[A02] 变量声明与赋值
来源：http://dali.cucudq.cn/Article/details/gt2jqjnpumf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yvedp.cn/Article/details/gt2sjfnqzrb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gotoacloud.top/Article/details/gt2rpuaaino.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pncudmnb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2heihjrml.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.aibaodan.cn/Article/details/gt2xkcdybxb.html

Go:   name := "Alex"; age := 20
来源：http://dali.gzhubu.top/Article/details/gt2plugkzqx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cashguo.top/Article/details/gt2qpjhgfph.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yongpay.top/Article/details/gt2yrchvpqo.html

[A03] 常量定义
来源：http://dali.hywenlv.cn/Article/details/gt2mgrkufxp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuanzhike.top/Article/details/gt2tttenjri.html

PHP:  const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2nkcmbyzs.html

JS:   const PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2qydudhok.html

TS:   const PI: number = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2akhwplse.html

Java: static final double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2jfrveqhb.html

Go:   const PI = 3.14159
来源：http://dali.bjfxy.top/Article/details/gt2bbbshrck.html

Ruby: PI = 3.14159
来源：http://dali.jlsjyb.cn/Article/details/gt2brizdgyl.html

C#:   const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gt2sgjxlpdp.html

[A04] 判断变量类型
来源：http://dali.jianghu66.top/Article/details/gt2bjsbdtqp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenjidiqi.icu/Article/details/gt2snvyuvyj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.aizwys.cn/Article/details/gt2zjnhsobl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.havefunace.top/Article/details/gt2htdpcxnf.html

TS:   typeof x; x instanceof Date
来源：http://dali.chenlongwang.top/Article/details/gt2duakyhou.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangdashe.top/Article/details/gt2zsddargv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sweek.top/Article/details/gt2rnddkplh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.tian-w.cn/Article/details/gt2gvtyfinr.html

C#:   x.GetType().Name; x is int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxsfuzsh.html

[A05] 整数除法与取模
来源：http://dali.9152youxi.cn/Article/details/gt2wzmciscu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hnxiangtu.top/Article/details/gt2tomxldyd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2xtyzzman.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2ukkfoigs.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gt2mbzllukq.html

Java: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2pfcaplic.html

Go:   7 / 2; 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gt2umibkkdd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gt2ygkjygqr.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gt2sdkqjacq.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfdznvhr.html

Py:   int("42"); float("3.14")
来源：http://dali.yuxming.cn/Article/details/gt2funondni.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xinyue.icu/Article/details/gt2fyxszewm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbjkzkre.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nwbrower.top/Article/details/gt2mrruprbd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yangfankeji.com/Article/details/gt2unoajjuw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.meibo888.top/Article/details/gt2xphizzsq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj20258888.top/Article/details/gt2jeanggfu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yangfankeji.com/Article/details/gt2ksrbfiag.html

[A07] 数字转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvikilxx.html

Py:   str(42)
来源：http://dali.nanxinkj.top/Article/details/gt2tvbkvofc.html

PHP:  (string) 42; strval(42)
来源：http://dali.bjfxy.top/Article/details/gt2thcezjfa.html

JS:   String(42); (42).toString()
来源：http://dali.xinyue.icu/Article/details/gt2deacxnzp.html

TS:   String(42)
来源：http://dali.yonumen.top/Article/details/gt2xjngdale.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hammf.cn/Article/details/gt2ljgwqbht.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuxcbms.html

Ruby: 42.to_s
来源：http://dali.9152youxi.cn/Article/details/gt2nylczvio.html

C#:   42.ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlxwdpkx.html

[A08] 取整与四舍五入
来源：http://dali.jqgufenzy.top/Article/details/gt2vkvqconf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gt2tyjbhlhw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gytmwwxn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yangfankeji.com/Article/details/gt2mwlpnfwf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.nanxinkj.top/Article/details/gt2gxtdnmyc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdmpccr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gt2xvjnjoru.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jiagoushi.top/Article/details/gt2rymffyis.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gt2eiffgwlw.html

[A09] 绝对值与最大最小值
来源：http://dali.guowangkeji.top/Article/details/gt2bfmamirr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzifrxgu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gt2tbobipxt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2znoyjhps.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2mfttqenw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2clztcqin.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydqarsva.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sxryk.cn/Article/details/gt2yyjfwnxw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2ztefdlfo.html

[A10] 生成随机数
来源：http://dali.ybcxt.top/Article/details/gt2jjtobvwa.html

Py:   import random; random.randint(1, 100)
来源：http://dali.daxiang520.top/Article/details/gt2whiepuym.html

PHP:  random_int(1, 100);
来源：http://dali.9152youxi.cn/Article/details/gt2sgrppeup.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zdqjudy.top/Article/details/gt2woepsuot.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zycfv.cn/Article/details/gt2hhuzoarh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xuanzx.com/Article/details/gt2dzafsiqh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.fengsongda.top/Article/details/gt2byexklvs.html

Ruby: rand(1..100)
来源：http://dali.gotoacloud.top/Article/details/gt2rgafypgn.html

C#:   new Random().Next(1, 101)
来源：http://dali.cdnleiting.top/Article/details/gt2gxhkwkfv.html

[A11] 条件表达式（三元）
来源：http://dali.sweek.top/Article/details/gt2fwuenpdw.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jqgfzy.top/Article/details/gt2ukqegfro.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gt2kmpdpovq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gt2lmunvvbd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gt2bviacgzc.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gt2qrqjluyy.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2liqsldxp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gt2hvstzrxl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gt2lnzxkitt.html

[A12] 字符串插值 / 格式化
来源：http://dali.cucudq.cn/Article/details/gt2ijvuzenh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.snrcjt.cn/Article/details/gt2imaftdck.html


<!-- 参考信息 -->