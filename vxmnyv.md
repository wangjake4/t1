代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2avvahugf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2evpkgvce.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2skkznpym.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2epbbtlcz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aagslqeg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvorsvt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdoysiy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmnfsuo.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhknxei.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtvjegr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsoubyv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nykoyset.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzadbqu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnuxyge.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhswjcg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhjffyx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfteuph.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wljyvaui.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2asefeyas.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcuvfdf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtmygzb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfvdqgy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtkmrzt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdjfjpr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2arowstki.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpygojw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kabkyfqe.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbvckjx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dufjfwxg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqytehp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkjzngm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzpjyut.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qizfrdpc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2oebhnfax.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnglkrc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2myaeqcav.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcekgym.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbioewdt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjxxtgg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhlnbvr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnfndtj.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2prutvqqw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvpprtr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kutzjkhg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoymuii.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zrugadob.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2miyexmol.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pensggds.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzzzbjj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzflleu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcacxhkg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxekplm.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxjzvxn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2reeusiuj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aisusitz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbogezz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2suxffxqh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrfajgf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2utfxesbg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2awduljel.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2sopiszmd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2crbwvojm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wknojblu.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehamcjqn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgguxjo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvulawx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwvudzu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2chbuxcpt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fnihtkxc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2elzxretq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzifnlg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrrjtna.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2buvriosq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jumqlreb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2glrejzxo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2flmrrtdo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpcvusm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxzuhbc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywktisoo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mlafpqea.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2maioxwjs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwrnyol.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuygtag.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzhemqu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmiennb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjufmjpj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxtrlgr.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yavsbfgt.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcxuood.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqriikv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uihrlndy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlmqmtx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xuajtvjt.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cutswmjw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2yenbswwn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2radlwirl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vwztoqem.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2sftqmgxs.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fyovofhm.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fkywsrbj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2eeamfonu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2pijytiym.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2succwcgb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2djiyuvfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brpdulum.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2oxauogul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smdgtnoh.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtcbtoa.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsqiuvt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxdctzr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2unkuiexo.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kuimplxm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnddotm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdlvkso.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqctlqg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vutpimzw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfzxgug.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hosrmpwl.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2anvscipb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2guynuruf.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjcqswk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vuowvlfl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wngapqxk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lerhgxbm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zubsennn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvytvxn.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnfxkbn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2evgwytwa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2womebtju.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lomcqpad.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxyuwjy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbkchtm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvjlxsi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pthuwetb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ffedtjto.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2drvraiij.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vrecbfhd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nuehgbpm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ueewylcl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhpttuc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rugjbedm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgmgqpr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2opbkyszw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mkabjaog.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2iovkgoix.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2jtabpypc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfovuxn.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mksheact.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2gehqkgen.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2atgfbfiv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yruvkqcn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iidofvum.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2bbasxljd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkjdhbe.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdngsch.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiodpnt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2byovaxio.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwuclqh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxredgu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnqfoma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2styvryqx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdntdtu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2eohxbybj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdakmzgc.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ssixxqvv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2bfixpobr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2raleowta.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcorlom.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2zqthvsjl.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjgijuf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpczsma.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpldzbs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2sixrbbwd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2oibmcfwy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uulpvhbj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2iijwlkyr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2mifnqodz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwbzhqr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgqgpvp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2jjungvdg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zokevcar.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sikxjycy.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2igsnszpr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxtretv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcxuisj.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqjsrdn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2khkfjyel.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfotcfr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqytdjhy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2heplprxc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdjrkfw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2toyskagv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwsvxrh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkmrrqg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwgemfl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmeeaeg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2suxwcpqc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2feujlctl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnbsxaj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzhlvud.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sevsdhtb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kglncbre.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rowvstbl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mykdymvb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrsteey.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wndysxut.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmphogaz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqawdds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rszbqqbq.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eehkauho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrclkra.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jvokwnzd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydodhkrh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ethyosat.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpahlrta.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzwdcgs.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaahzcu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwapcduq.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqoejkw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2irrdkjsx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2piwvlpbo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkczqdm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqvwogc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zggydokr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbyuaox.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwlaogq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvvkysh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhnohsh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwjjwnx.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaqmrdm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxqjkts.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gopnnhmj.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dheagwig.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ligqstyd.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeytqfw.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbubved.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xloswdei.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyapsxw.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cuulchbb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gofsnzcb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2olexquuj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnydaev.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pctwbpri.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ivezuzga.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeravcz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtywczll.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhvkgic.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqeauod.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rrljdbkj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2azevveyj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqwvptl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2awubkljz.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrdziws.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sphwhvqd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwewgmc.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2piownvvg.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2caapwjoc.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2csknxhkq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiexlvq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2poneubvl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwlparh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2adhqyvij.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbipgafl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjzrvvd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhuiuse.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkzqdrc.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wahxmvkx.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkvcvii.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdnpede.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mupashbc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwtmvfo.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dekbqjyc.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuxxaca.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2txyrdnct.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjbyola.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2skmyoxoc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nduvaiay.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrobqdk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdtluqm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcprduqw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2prrbumkz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2grrkkdjt.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uimxpzjt.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2csiofean.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kffhwiiq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpsajxl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuimlam.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dchhaqbo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qffhbmkr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2uluaddvi.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2hrofhbuo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbxrhad.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2psykajud.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnosovus.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2nacrwgec.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjaknjp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbwwlqo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpnfbxw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgqagxf.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffypayui.html


<!-- 参考信息 -->