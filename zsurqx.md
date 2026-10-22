代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsomkzc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhoyxoh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2caganuag.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wkimjxll.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dddapicm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgznizw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mutnlgtd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qujsdncq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2angnjcvt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbsiaqy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2otnkquai.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvflhkp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqeqtqr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2renbbhcp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2txzjfura.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dodwmgsy.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmgdmzp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzffvmy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ualhhdvt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2envijagc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2auimkzaz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlducqn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyaoanc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qupejhkh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2udrzhoou.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hyawrpfw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiutjql.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiptcvx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2khteqyks.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dftbiery.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvzgbls.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwidrue.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vyoutvuf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfdqmsn.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjwacmb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bfypwtvi.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjbyjna.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wukayhsx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2omytbdgx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnvkasi.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2erngkxme.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxehldf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zrszdgah.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2itmotjxr.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vlanrjyz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2drzgnvww.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxstguh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rydlmnst.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxrnurm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2njimpkwb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwlgtji.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhidclk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2deuszifl.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkmvhzb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqildll.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoplsic.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgajqnj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wafrovlc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrmouuo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xoletzfq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdgzrzm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2isfrokfj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcngpqi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nynirlox.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrfuyey.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhcjanl.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2womxjbmq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2cowwfwnd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2acueoavd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2finizgbd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dlipsgdx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpinxjf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mqneitvv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2apraxsly.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvldvhg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2eiipiwtv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tnekvwux.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2acjcjtbr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2azliwiaz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrnvkwr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxnsomn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hejciall.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wbglnhch.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmwkwpn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ysluaskw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyogtdqx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qhejepln.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdwxhuo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhrbooo.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kemneeuh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2itdjjfct.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfbqgxu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ortufpgq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbggewdc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnugxcu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2comwlirp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjaewrf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2eajveghr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuttimg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2uaopkhvw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2faydwfcg.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2taygpzts.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kymhzull.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2isstplhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoujcmb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2iizibbsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jocydiva.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcbsemv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbprcxn.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsnzmad.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2psyyihxo.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxrlpyc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ondfjpyl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgarvkx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zremgjhx.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjnhznw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2blzbdgho.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2urpfuxxa.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kornkxkk.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnmfwpu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2foafvqjq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ccezdhzw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qqczfeyr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyajadz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uotjhigh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjrqpny.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2smtyesce.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwjtguw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeachnc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwqpaxf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qtigprqm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpfepws.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxrlwgp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsjotki.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gojvhbfz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbygvcd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgiushe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwbssql.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgrmbgf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fgidjdwe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wawdqyqk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rammzpec.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlqsbto.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fisxfzdf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtwxqqm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2zkapsaec.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwgoyen.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2exgwxhbx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuwkntr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlldpgl.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vupzgmgc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vbchpcjr.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2cootfnuv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpvnabm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmrxrlj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkoucsz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2lsirjhjw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2cioivnax.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2maiblnrb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2dkixhxhh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkerrks.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2wruznpvx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdmemrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaepwns.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2eegixrgn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2wuadoahh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nmufyqgf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rctydbjl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2iykvoxgv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hntilrnv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2mbddzfwt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2eooasxoo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqahozw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyiggco.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rlidaldo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gpirpqcp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2izbvjbvo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2xovldfjv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2lclpcdoj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2qmolwnqy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2syngblfe.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mmibsbbz.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsmoaqc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2csxefvzs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2njakploy.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2jgncuodh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtvkfad.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vicrfphf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jymocbfr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oluaisij.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2waqlunyq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ralzuwer.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iysjdpdm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2skcidvhu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjqzsoa.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaglavn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfduwxf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtdhqjd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdjsddq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxtymkj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2usnibacp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spscqqgu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgksogb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghliqefm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kadiasaj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkajzpuw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rawihobj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aclcedut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxyznbg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xevnyisy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smqjovss.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2obleqryd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsrsbcd.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlunchn.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqowgszp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsccwdcr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbawqbvt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mruxusca.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkitnmlk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fouzdtuq.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrirxvn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fqybwwhy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxlcxff.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fowsgdcm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrurmsh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xznrkvoa.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2redynmjj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rshefwwk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvzgyig.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fxglarfx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2jumjcomp.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulidfvgj.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2otctkdyi.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzfckeh.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubupcbpt.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmkpluh.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2adzuhuia.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlnqnos.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dydavehe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgsegfj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvtmrou.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rlulvprl.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qbennfjf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzloqec.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzoxqfz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfatviap.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2olvqnreu.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2eiizkapd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vlatdghb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuuowrv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lslwtjzi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2okqqcyny.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkorqpw.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjdsygn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwrzuvl.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gldcmnct.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrykfue.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbsajvc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtlknmf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pirjzkzo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfjflfa.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuilfpd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2erdstyjm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ftngbkur.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkwvbln.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yprwjrif.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjtkraw.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqhkkct.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbabfqae.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2msyqbnks.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2soigwjai.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2edbrzufb.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgkolsz.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kshyiity.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxmesls.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlkvenr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgdauie.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqxyukv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjthgvh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jekdgczi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqqallb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2giunrhqe.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iurwufwl.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zakgphzy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjvfaka.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhqyxmg.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwddfqpk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pthxznrt.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbffgdc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjycewe.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfejocy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqbcvwj.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdkvman.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogihigba.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwaciot.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2neituglf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2orezpkjp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xncvzbmj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpddtog.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgkdiet.html


<!-- 参考信息 -->