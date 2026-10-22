代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.ehwqpu.com/Article/details/gt2jzdfzfox.html

composer require psr/container
来源：http://dali.aibaodan.cn/Article/details/gt2svqjfihe.html

[U76] PHP：简单路由
来源：http://dali.yanxiufei.cn/Article/details/gt2pnmbvgox.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigfzy.top/Article/details/gt2cytqtkdx.html

[U77] PHP：模板渲染
来源：http://dali.redwolf501.top/Article/details/gt2howjbnwz.html

composer require twig/twig
来源：http://dali.fengsongda.top/Article/details/gt2glbdbanu.html

[U78] PHP：单元测试
来源：http://dali.haohaochexian.top/Article/details/gt2jxfshgyp.html

composer require --dev phpunit/phpunit
来源：http://dali.vqdsnc.cn/Article/details/gt2pjkpvmkb.html

[U79] PHP：静态分析
来源：http://dali.tianlin.xyz/Article/details/gt2klafktmq.html

composer require --dev phpstan/phpstan
来源：http://dali.xinyue.icu/Article/details/gt2xpcfctll.html

[U80] PHP：代码规范修复
来源：http://dali.hnqzz.top/Article/details/gt2wwvisywz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yongpay.top/Article/details/gt2erssbiqq.html

[U81] JS：初始化项目
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmaqfeup.html

npm init -y;  npm i express
来源：http://dali.0kj1m.cn/Article/details/gt2igcvxkak.html

[U82] JS：package.json 脚本
来源：http://dali.shangyingyoupin.top/Article/details/gt2auvtsgzy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cdnleiting.top/Article/details/gt2emqiggms.html

[U83] JS：ES Module 导入导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jansrvha.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gt2fogahgpo.html

[U84] JS：CommonJS 写法
来源：http://dali.pycfn.com/Article/details/gt2twwrftoz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenlongwang.top/Article/details/gt2xaqknaor.html

[U85] JS：可选链
来源：http://dali.smart0.xyz/Article/details/gt2yybzvbhs.html

a?.b?.c
来源：http://dali.snrcjt.cn/Article/details/gt2vdsndxyl.html

[U86] JS：空值合并
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufallvyp.html

a ?? b
来源：http://dali.0kj1m.cn/Article/details/gt2zucqriay.html

[U87] JS：解构默认值
来源：http://dali.sysykeji.top/Article/details/gt2zkmtirxq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigfzy.top/Article/details/gt2ffkbdpeq.html

[U88] JS：对象展开合并
来源：http://dali.aizwys.cn/Article/details/gt2frjwxmjp.html

{ ...a, ...b }
来源：http://dali.jlsjyb.cn/Article/details/gt2wwicjeoc.html

[U89] JS：数组去重
来源：http://dali.sufxvd.cn/Article/details/gt2mslzthai.html

[...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gt2dcnljfel.html

[U90] JS：数字数组排序
来源：http://dali.kuanghao11.cn/Article/details/gt2qywljadv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2icwkgbob.html

[U91] JS：对象键值遍历
来源：http://dali.yueranfly.top/Article/details/gt2kpnjjhjh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jqgfzy.top/Article/details/gt2jhhstjrp.html

[U92] JS：深拷贝
来源：http://dali.fzhhl.top/Article/details/gt2wltgtxhz.html

structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2synnmbfl.html

[U93] JS：模板字符串
来源：http://dali.xylfe.cn/Article/details/gt2wointurq.html

`共 ${n} 条`
来源：http://dali.wangdashe.top/Article/details/gt2ttrlgmwd.html

[U94] JS：箭头函数
来源：http://dali.daria6918.cn/Article/details/gt2wgkvpkjl.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wptjmqkc.html

[U95] JS：Promise 包装
来源：http://dali.ehwqpu.com/Article/details/gt2iqkbjcqo.html

new Promise((resolve, reject) => {})
来源：http://dali.hysaishi.cn/Article/details/gt2lydrjxcl.html

[U96] JS：async/await 与异常
来源：http://dali.yvedp.cn/Article/details/gt2cyejoads.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2ezitauvz.html

[U97] JS：并发请求
来源：http://dali.aibaodan.cn/Article/details/gt2mqitxxam.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2rkzgokor.html

[U98] JS：fetch 带 JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2qqifefmw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgufenzy.top/Article/details/gt2lehswjst.html

[U99] JS：事件监听
来源：http://dali.yonumen.top/Article/details/gt2cqbcomhf.html

el.addEventListener("click", e => {})
来源：http://dali.chenzaomai.com/Article/details/gt2zjjafsoc.html

[U100] JS：DOM 查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fqhwxvxh.html

document.querySelector(".item")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kaeykiav.html

[U101] JS：classList 操作
来源：http://dali.jlsjyb.cn/Article/details/gt2ggsgfvlc.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gt2xxhqnqts.html

[U102] JS：本地存储
来源：http://dali.hywenlv.cn/Article/details/gt2oifkvkis.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.snrcjt.cn/Article/details/gt2ymewttne.html

[U103] JS：定时器
来源：http://dali.tianlin.xyz/Article/details/gt2dmvvbjyq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgufenzy.top/Article/details/gt2wuyoqkkq.html

[U104] JS：防抖
来源：http://dali.zhoulong.xyz/Article/details/gt2wmgdfzdp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2ftuqirvm.html

[U105] JS：节流
来源：http://dali.yongpay.top/Article/details/gt2skbvrsug.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fzhhl.top/Article/details/gt2ftpkbinp.html

[U106] JS：日期格式化
来源：http://dali.aibaodan.cn/Article/details/gt2nyikfriv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hammf.cn/Article/details/gt2oricihem.html

[U107] JS：数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvwpehdq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fachojxt.html

[U108] JS：随机整数
来源：http://dali.xinyue.icu/Article/details/gt2wqkvblqn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuanzx.com/Article/details/gt2otqlwdip.html

[U109] JS：数组分组
来源：http://dali.fzhhl.top/Article/details/gt2qzoxvcmw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gt2ulvndtko.html

[U110] JS：数组分块
来源：http://dali.zhiwuduotai.top/Article/details/gt2woqigalc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sysykeji.top/Article/details/gt2ckqvdfdx.html

[U111] JS：对象转 Map
来源：http://dali.yanxiufei.cn/Article/details/gt2anlydjdr.html

new Map(Object.entries(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gt2cyaqjffs.html

[U112] JS：字符串补位
来源：http://dali.sweek.top/Article/details/gt2sdkjupzg.html

"7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gt2fvkqfhbb.html

[U113] JS：正则替换全部
来源：http://dali.svipenyu.cn/Article/details/gt2erryoefw.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbnmexqt.html

[U114] JS：JSON 深比较
来源：http://dali.yonumen.top/Article/details/gt2eeccbgca.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gt2rsnnksxj.html

[U115] JS：生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gt2dxnxehfo.html

crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2aysrxxle.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daxiang520.top/Article/details/gt2mcxysmpr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dashuyun.cn/Article/details/gt2dpmalsha.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gt2aqbifaow.html

npm i -D vitest;  npx vitest
来源：http://dali.cheryme.top/Article/details/gt2ifqatdeo.html

[U118] JS：开发服务器
来源：http://dali.hysaishi.cn/Article/details/gt2gknvcsxg.html

npm i -D vite;  npx vite
来源：http://dali.yuxming.cn/Article/details/gt2qazjbqhi.html

[U119] JS：生产构建
来源：http://dali.tanke756.top/Article/details/gt2qpzsclhd.html

npx vite build
来源：http://dali.haohaochexian.top/Article/details/gt2oanshlxw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.andypj.xyz/Article/details/gt2edocpyld.html

import.meta.env.VITE_API_URL
来源：http://dali.fzhhl.top/Article/details/gt2uzwxasdm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2yvochhbe.html

统计汇总
来源：http://dali.fzhhl.top/Article/details/gt2rabkxcek.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2tedcquux.html

按语言统计（条）：
来源：http://dali.gaohongyu789.top/Article/details/gt2ylzruwdi.html

Python ......... 252
来源：http://dali.hnqzz.top/Article/details/gt2gjjeayiq.html

PHP ............ 252
来源：http://dali.ybcxt.top/Article/details/gt2pkoprdfi.html

JavaScript ..... 252
来源：http://dali.redwolf501.top/Article/details/gt2gupokasz.html

TypeScript ..... 212
来源：http://dali.cdnleiting.top/Article/details/gt2utsdykpp.html

Java ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fymjsbqp.html

Go ............. 212
来源：http://dali.cashguo.top/Article/details/gt2xdleriix.html

Ruby ........... 212
来源：http://dali.svipenyu.cn/Article/details/gt2bxtcdrit.html

C# ............. 212
来源：http://dali.jianghu66.top/Article/details/gt2hzwrlxyc.html

C .............. 30
来源：http://dali.guowangkeji.top/Article/details/gt2kmvrstoy.html

C++ ............ 30
来源：http://dali.xuanzx.com/Article/details/gt2rdmhaola.html

SQL ............ 90
来源：http://dali.c1oappe.top/Article/details/gt2qzjdcrcg.html

Bash ........... 80
来源：http://dali.hnqzz.top/Article/details/gt2igtoxukw.html

Kotlin ......... 15
来源：http://dali.hysaishi.cn/Article/details/gt2hstjtqcb.html

Swift .......... 15
来源：http://dali.dashuyun.cn/Article/details/gt2cftdlfme.html

Lua ............ 10
来源：http://dali.ydzc1.top/Article/details/gt2lnlppmoc.html

Perl ........... 10
来源：http://dali.ivvv.top/Article/details/gt2faqxpdvq.html

Scala .......... 10
来源：http://dali.shangyingyoupin.top/Article/details/gt2ueokemnm.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gt2toqdqxsy.html

合计 ........... 2106 条
来源：http://dali.bjfxy.top/Article/details/gt2sopzosfe.html

按章节统计：
来源：http://dali.wangdashe.top/Article/details/gt2aqsnxufr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gt2nzpzfoik.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gt2bqebdkdj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gt2mgtdszyu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gt2gytpnlgn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nwbrower.top/Article/details/gt2rytzrrmz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gt2uofxdjfj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gt2gpjnyfwg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.c1oappe.top/Article/details/gt2shqwjiqx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2bariydfh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwgxatfp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2gqyhxbqr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gt2bectkaoq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gt2hcnpzsmk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.smart0.xyz/Article/details/gt2cwnkurjt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.dianchejie.cn/Article/details/gt2qybbymyg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gt2xnsvoxco.html

Q SQL 专题                              90
来源：http://dali.zdqjudy.top/Article/details/gt2gjdhcasx.html

R Bash 专题                             80
来源：http://dali.aibaodan.cn/Article/details/gt2paiqfevh.html

S C / C++ 专题                          60
来源：http://dali.xziqi.cn/Article/details/gt2ymbatdxv.html

T 其他语言补充                          60
来源：http://dali.yuxming.cn/Article/details/gt2nnhzmkwl.html

U 高频实用片段                         120
来源：http://dali.fzhhl.top/Article/details/gt2ukexxdoc.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gt2llpuajvy.html

合计                                  2106 条
来源：http://dali.nanxinkj.top/Article/details/gt2virdqmmf.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gt2quoxkihv.html

使用提醒
来源：http://dali.daria6918.cn/Article/details/gt2hkiyfchl.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gt2rraqxrwz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenzaomai.com/Article/details/gt2gavliajr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shzxlz.cn/Article/details/gt2fezbikjr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.316326.xyz/Article/details/gt2bwvixzel.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xziqi.cn/Article/details/gt2sfglmsdc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangdashe.top/Article/details/gt2hcjavpoq.html

—— 文件结束 ——
来源：http://dali.chenlongwang.top/Article/details/gt2jfgrzebp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2bqyfrhke.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.dianchejie.cn/Article/details/gt2roqomvil.html

Common Programming Examples Cheat Book
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tfrjaerp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2hawottlq.html

【收录内容】
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aggktbby.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aibaodan.cn/Article/details/gt2cuokduxw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guowangkeji.top/Article/details/gt2oghorgjk.html

SQL · Bash · C · C++
来源：http://dali.xuanzx.com/Article/details/gt2uroibfdc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.bjfxy.top/Article/details/gt2tzylnirc.html

【使用说明】
来源：http://dali.yj20258.top/Article/details/gt2ruyvoejt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.kuanghao11.cn/Article/details/gt2wykbmrla.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.wangdashe.top/Article/details/gt2dxlsxtob.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgufenzy.top/Article/details/gt2itccagyr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.redwolf501.top/Article/details/gt2efpidykk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.snrcjt.cn/Article/details/gt2xpeemoli.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenlongwang.top/Article/details/gt2uviqmdfl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.c1oappe.top/Article/details/gt2omopldkj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuanzx.com/Article/details/gt2xdzofjoy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guowangkeji.top/Article/details/gt2iptaqhpk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.svipenyu.cn/Article/details/gt2hnskmatl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sysykeji.top/Article/details/gt2mvkclhqb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xinyue.icu/Article/details/gt2xphxmful.html

【文件统计】
来源：http://dali.shzxlz.cn/Article/details/gt2dghamjln.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinqigufen.top/Article/details/gt2kxxqtgjv.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gt2rnagnzyp.html

目  录
来源：http://dali.yueranfly.top/Article/details/gt2ldfydrhy.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gt2tgyxokjs.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gt2doopptsy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gt2enngxijt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2hjeuohki.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.fzhhl.top/Article/details/gt2ejwlfasv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sxryk.cn/Article/details/gt2mtxrhyig.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.andypj.xyz/Article/details/gt2rmhmddgq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xziqi.cn/Article/details/gt2wricqbbo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.havefunace.top/Article/details/gt2ihpzxoxq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gt2ocoteknz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yongpay.top/Article/details/gt2fieksafp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2oeeppabz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2sjlgtlws.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gt2xutnafrf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.316326.xyz/Article/details/gt2fcnorgej.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yongpay.top/Article/details/gt2zjfanlzb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2fihyrhjx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxzgvtdc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sxryk.cn/Article/details/gt2cxnhqvqz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hywenlv.cn/Article/details/gt2cdmmwxjq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gt2ltfaaceg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gt2qvhqwmlf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2dsyohkfs.html

A. 基础语法与类型
来源：http://dali.aibaodan.cn/Article/details/gt2crksmcyv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2uuhfhpjy.html

[A01] Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gydikwpi.html

Py:   print("Hello, World!")
来源：http://dali.xuanzx.com/Article/details/gt2kydzdfkm.html

PHP:  echo "Hello, World!";
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlkfytxx.html

JS:   console.log("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ssexcsux.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.kuanghao11.cn/Article/details/gt2qxatdryl.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzddhjtc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.birdmap.top/Article/details/gt2fwobgncp.html

Ruby: puts "Hello, World!"
来源：http://dali.c1oappe.top/Article/details/gt2rpkzglki.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gt2uuuvwfnt.html

[A02] 变量声明与赋值
来源：http://dali.jyoumei.cn/Article/details/gt2bciplrsm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2htiqutjr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gt2kjqnputy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.chenlongwang.top/Article/details/gt2wwqghzrf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.haohaochexian.top/Article/details/gt2xdlcnzyp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gt2wbkvhjwm.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iypqfbtq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenlongwang.top/Article/details/gt2ttuuusat.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shuidangran.top/Article/details/gt2zxphtply.html

[A03] 常量定义
来源：http://dali.snrcjt.cn/Article/details/gt2fzqzgzym.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtjudyjh.html

PHP:  const PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahhfqofa.html

JS:   const PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vqyhjesg.html

TS:   const PI: number = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2ennopdmt.html

Java: static final double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flcwttmb.html

Go:   const PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gt2nxuwwhas.html

Ruby: PI = 3.14159
来源：http://dali.guowangkeji.top/Article/details/gt2kssmcsju.html

C#:   const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2heaqjjrg.html

[A04] 判断变量类型
来源：http://dali.guannengcc.top/Article/details/gt2bsmmhzxd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhixingplan.top/Article/details/gt2qaezpuvx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnfpfpia.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gejylrfs.html

TS:   typeof x; x instanceof Date
来源：http://dali.gzhubu.top/Article/details/gt2ytjjkmzk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhongyouzk.top/Article/details/gt2nuyxuzwp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.pycfn.com/Article/details/gt2jvizmjii.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhcphjel.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdzgcvym.html

[A05] 整数除法与取模
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qixgtxhv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.fengsongda.top/Article/details/gt2muwfmsus.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gt2onylfpyt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gt2dlrepvks.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gt2ctusnjlj.html

Java: 7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gt2urhvvaij.html

Go:   7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2pafghkfl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2ecmuiini.html

C#:   7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2nrjzjufl.html

[A06] 字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gt2hincfdqq.html

Py:   int("42"); float("3.14")
来源：http://dali.yvedp.cn/Article/details/gt2hmbzyolg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tupkbrod.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj20258888.top/Article/details/gt2mvnshocp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.iojbl.cn/Article/details/gt2apclvgtr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cucudq.cn/Article/details/gt2mcatcwkx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.meibo888.top/Article/details/gt2xbwkmlwb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.mhx1999.top/Article/details/gt2tmurljmj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yvedp.cn/Article/details/gt2bwvrvuxb.html

[A07] 数字转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2mvtqbstk.html

Py:   str(42)
来源：http://dali.guannengcc.top/Article/details/gt2fccxzkmc.html

PHP:  (string) 42; strval(42)
来源：http://dali.quarkkingdee.top/Article/details/gt2yckqunjw.html

JS:   String(42); (42).toString()
来源：http://dali.bjfxy.top/Article/details/gt2afglsilt.html

TS:   String(42)
来源：http://dali.fengsongda.top/Article/details/gt2vskxcado.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhoulong.xyz/Article/details/gt2duonvjds.html

Go:   strconv.Itoa(42)
来源：http://dali.yuxming.cn/Article/details/gt2sujflbxg.html

Ruby: 42.to_s
来源：http://dali.daxiang520.top/Article/details/gt2uyljkfkk.html

C#:   42.ToString()
来源：http://dali.gzhubu.top/Article/details/gt2lrdvqpwg.html

[A08] 取整与四舍五入
来源：http://dali.guowangkeji.top/Article/details/gt2krrfjqxz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ivvv.top/Article/details/gt2wlgmuobl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klpiffpp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gt2vmeujmsy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.daria6918.cn/Article/details/gt2rpfsdnfo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gt2hoiszegd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xujmrjbt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgurlsqa.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gt2fqmcvhqq.html

[A09] 绝对值与最大最小值
来源：http://dali.aizwys.cn/Article/details/gt2mmojvydr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2ifiqjoxu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixkprqbl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2epvwlzry.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sweek.top/Article/details/gt2gnwaovke.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2kgaqmvhm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.haohaochexian.top/Article/details/gt2fgumflkw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.meibo888.top/Article/details/gt2travywvo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2dwdixgfs.html

[A10] 生成随机数
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfzbusgf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cashguo.top/Article/details/gt2mdssaiof.html

PHP:  random_int(1, 100);
来源：http://dali.andypj.xyz/Article/details/gt2hnqvymkr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.c1oappe.top/Article/details/gt2gwqikyvs.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlcotcbt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guowangkeji.top/Article/details/gt2tsbbpnrf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdxbarua.html

Ruby: rand(1..100)
来源：http://dali.snrcjt.cn/Article/details/gt2ihqupyqo.html

C#:   new Random().Next(1, 101)
来源：http://dali.jianghu66.top/Article/details/gt2albeinko.html

[A11] 条件表达式（三元）
来源：http://dali.havefunace.top/Article/details/gt2awgnpwej.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.aizwys.cn/Article/details/gt2hokeglnp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gt2tadpyugs.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gt2jtclkdye.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gt2kqmwkqif.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gt2dudjjcyp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yonumen.top/Article/details/gt2igsvmqhw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gt2tjybotgl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gt2kkgjikir.html

[A12] 字符串插值 / 格式化
来源：http://dali.c1oappe.top/Article/details/gt2dtstforp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.0kj1m.cn/Article/details/gt2qjijtwkt.html


<!-- 参考信息 -->