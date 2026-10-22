代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxsrcci.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fubkfaum.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyzwwgq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlkjciu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2azodlozg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2twwebfoh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhtuivc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltywilia.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2nduoskya.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2eplenhfm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hydttfpa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeefgrw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zzquzbyt.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2svfyhpcg.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2czgeyoti.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrixoge.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ousksgha.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkzyimg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lefoqwvf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxywmml.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjjiteb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbugfiy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuurocb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyctgsz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dviyldag.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2etqpirsq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnilxst.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbtljcx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2srpfzovv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlltknr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2znpfhhzg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdsvuev.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2egvslava.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2luxwfxij.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpwalzp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjnrkvc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gijotmiv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfxemtk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyomoze.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkitiynl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sdohvdub.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mprdoefu.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fplhnrup.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbianyuz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wqktdynh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoytiuv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cixskpro.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vifwulhk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dbomqwzu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2thrukxuz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjhvskk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmkmmnr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2atwkupuu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bphqebrt.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fueabkfx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtefaej.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaxywno.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kowmwwwc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzsktwb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2blwuuruu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfvxyyj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvhfvkz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pezgxvdb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyymqys.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2steskatq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzsuugo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoqjvfi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2feqibvep.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gphhobwo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nubpthol.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fztedbdg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsgeqpb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjduiwk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnoxzvw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zueablar.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jfozulqu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhkbhvo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2glypmmyn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkmyefm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dleyefem.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtjnoeb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmgcgfb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxxyfga.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2omjivjgf.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gagiajoj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2buxqcmjl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yagrmxum.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqetnqiw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kexgwhot.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bygntten.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjwfwst.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nozezvhr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2swxeokhj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlebgtj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcseidm.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvdseud.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fguoelfn.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2loemkkgy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2btpdmgfv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2crkdgokc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wczxlers.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2thhgtkpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxsfvxk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcxzdpg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cytzjkae.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cblvbxsu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqcnifd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnldhlu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxlblzg.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2osyzktvr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ijndjuww.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bodnkayl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgpywnr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ozinfmeo.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2khkejbbq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgidlnr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ccirvteu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzgxmjl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqtniwo.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqoawft.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kssdzqks.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ahamklhy.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfrnlef.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gfskbeme.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvyameq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nomnuyte.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xbomzulh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yeupblkq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpnwqvt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xvegxcym.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2klyfklfo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2napnppry.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ctonfzdh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2efntlpea.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xczotdju.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hljqeihj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxchnxt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmvocmw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2muxffarf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkbgqwb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ybodvsme.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hazcrtuc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2iafqvuuj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwqizwt.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zaitbkfy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2llakexoa.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtabmiz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbqefju.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgtxuxk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmjwfln.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2zefaqhqk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nypgewfb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2suvfsjvg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzwnqnw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2npulxadt.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtalmza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oandpdcs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2alvpmsid.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhcrokh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsuohdr.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zexmbdis.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2exbysnnp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwwepov.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mamilqgp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2krehzakm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdnuncp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhxwprm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrroyjk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdufxyc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrzflqa.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2joxjbhtp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyjcabj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2scnsahgm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kiockylg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzzybos.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xifdlzqe.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbeyjqf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nqamvpjp.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ouekycjd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2adfblvat.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zhegzrvt.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpljvqu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeptimb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcljwaw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkgpbyz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scytrpvd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kckvkvhq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lofmvqsv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgbqgqv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rldtrgnb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2juzgadte.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxpcemq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnhwirw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvqwgvy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdlnbvq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtikpkd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewigsqde.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fneelzgq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcgycbn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2glxnsgni.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmvpwpi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2inxiiary.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2prbdzhce.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oadikwyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zheozfmd.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmthtnj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlyncwn.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nrstoatl.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyckanl.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nweaqylc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmjdkih.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2btlyyjrr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxtvzbu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdszjuo.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzxeith.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeevttu.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2iinrtbik.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cixefsbw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpsntvp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzqwupv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2umaatbza.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmdtyhw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2czpxnsaw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2owunvebh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2etobrzvo.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnqytbx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkehcqk.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcueeqoh.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2recodued.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnddpjw.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuhzpvg.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxlrjnn.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bipajafg.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hevcdaay.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxlgcho.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdksugfd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eofwftga.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdlhois.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkmtmly.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2oukcwogr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceymxvuv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2xegniwgd.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyxydxw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2dkauqsem.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuiiumg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tetchgck.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2peldecyv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfuuiyw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zsesotqu.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2clhtwluc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrefken.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnjvoyx.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmaajmk.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fffcbeqw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcnjzuk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dijyyuym.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubugjltu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdliwva.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvnbfkp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2swpfcvrv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2masulivj.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2swwfazhp.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lktwmzri.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqkecmt.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nutltqgy.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoyalge.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyesqmtl.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxavcvtp.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhajryo.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdnbrid.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcykmiz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmstlmcn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vewkyejt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdxgsae.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnzmkby.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uezucooo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrocnoz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgqikwv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnpibom.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2syihzdfs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkzddvp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfmyzhk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmaholp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cldwlyob.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtchvofn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2daabulti.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnsqpnq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2clekwmpq.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaiqqef.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqzislm.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrhgdxm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wzklvpmb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ixipzjgf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aumvknwy.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ahineijj.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsigqoms.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwrifao.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhkwzwr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfrirgn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozygotpu.html


<!-- 参考信息 -->