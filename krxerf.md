代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xbevjwsl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2skxixvat.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rtftibdl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2etxviwfn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpxmqlo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxkezvu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjkkmug.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2htygtxkm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkiyrrf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2oefidetv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jkayyiop.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwyeddw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2twpmcuhh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxpukmp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wixprfvx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wqedjpts.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvglxeq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaakrbb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xewximzv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2emifqvqv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcijjuy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwgegkp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfvyyuk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2miavzcqf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdkobbu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2regedxlo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2eijacsmt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2usxwikln.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzudsgv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2opvyllzx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkuixtr.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzurhtc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ccebawor.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrnqaei.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhpqamc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2glichejh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyiifwh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oezfyvcx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtbycdd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrgpdsu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmrsdbx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qwycdsir.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aaktwxaz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqeilss.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgznpcn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnmempz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2comcxhaf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnlzqun.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bucncfmj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwarqxv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfbsqyn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkklvckq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2poxedlaf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfizlwpc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrbzzkz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pzofvoey.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvcqogk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfryvib.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxqtlin.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqlsrzk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2skoixcas.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhkzfqj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2crmhwiok.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wserbptn.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzfxidl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vukqqgef.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hblrlkiz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bovzsoaq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhwbyqh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pmskdskc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2etkprwid.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoxckxh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2flbkszbj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2eozfssbm.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbwkxoh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2amhhylmo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqgxmys.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbabsidc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ueozcopy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjzypgb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2blbrjxnz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzirkhy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2idpxvjbf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgibgsxy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxnrpbc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyytcbx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrqirka.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkixkyoo.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlupzru.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxjnsac.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2madhiryy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2totyodhh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyzfxxc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zfchglqh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mggzjoyx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqbutrh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2weloexzt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuqwwib.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2argqjiud.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nxziwqvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcrgcry.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpdrumu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iovjjmni.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnhoaen.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vauyeplc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2outextdo.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzjwxep.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpganuu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvqqbsp.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nprievbk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuhaguy.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wulbygoe.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxlweha.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2maikyrql.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2iniizdab.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2whgxkumz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gshjzjuo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqgwxog.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxzgowk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nfabkuhz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2elhcfscp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wymikohe.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrjtvkg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2iccsapql.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2miwfdwpp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rornlhsf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwzeggl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2oibnzjha.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vriwjgjl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxbgrdf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzemaio.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2huyrevdh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vqftxsjn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcuxgwd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2awsiqmfc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxnuvfq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hjytrwjs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqnqfgu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2juyqcaya.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkoztar.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wghmzmed.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2dydrlojz.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjnrbzt.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ceelnjpv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2caycowhf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzwmkbh.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvjmlvb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cynoowqf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqtkqhv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpshpwa.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdbbvuu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2tpchjlwl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2efoyvjhx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxhctnu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpmabla.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxmciax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsjidqv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiezuzf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpzcysn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfctqmnc.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsxkpxs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2nidrxlbq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2hqisjequ.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdusfrq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuibxkv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xljnvyro.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzitprx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjnjcsg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2gohxgijy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjizqaf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xotxzlaz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkjrwkq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2fujnmcvb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2iamncwdx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxrrmxr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxrqhqs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkpzktf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ornudort.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgbenxk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2waqxkwsn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvuzknm.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuqqlwj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2agfiymju.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhiwkzw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwliouob.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zatmtrju.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsuolue.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2epthkaua.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnzthqw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrpstoa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnlmgro.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwcqerl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtinhnp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvlxszv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2syvvjmsp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2akbrodkh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqetntp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgpylig.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvijbwv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2umsmcmtz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrnqidz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqantje.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fswpgvbt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qolcwtyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzrfjex.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsshzzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoykzog.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2knjbzvlp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2izsciwnb.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dipwmwmr.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pigpyenj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtphsxo.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtpizoz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2olwjktpp.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2niclaino.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzdkvpl.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wagoentf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pknfzqxo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfytfvum.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgsldlr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhwpqqu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbadrywo.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxxndzh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpugyxz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmpqktg.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdyfisa.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2pynpbwpm.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbsqbqb.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojznbbej.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyrmfxf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnewxpkz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kcakuyzj.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqdjdww.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqvxklu.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfonscm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpagppz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaehpzd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvyyoro.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkcobsk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2opdkxltn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqcvndj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2noptgeao.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2klwyildm.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbqqvlc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbvebnz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dxihcyuv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2seapqnxh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfhucjw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2usjxgeat.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2blcbjkkz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmqtnbt.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2idricvsn.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wphvfcim.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxrifzl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxytjtog.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsyuxsj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2inhfjglw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbekxye.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2cipyehxa.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqhxizm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2drvjenhq.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsjtven.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2prrumliw.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2buzqedch.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbnjefr.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpkhqsv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bomuubuu.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfynabzm.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqbuedw.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgafknxb.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrqfzas.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2oycffpob.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bskhnqza.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtajbwww.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2silszqbj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuecfxt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsflujz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2dluscxhl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhuabll.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qzondrcd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnrnvyg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2molzkhef.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2npndekxw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uokmrnza.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2varhwqtx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2qgicbjit.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2vawdhodc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfszkkmc.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2brgtzmnm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifynndlb.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2hejrdgfd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zrktoghf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsvgtdf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmdmvib.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcqhzsj.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmlxxky.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2erxywhky.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfllvxtn.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2otrmyllk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mirnaaee.html


<!-- 参考信息 -->