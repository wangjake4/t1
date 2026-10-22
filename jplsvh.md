代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtnzeea.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgxeorr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmaobjt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2diyjzcsc.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvcpthg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrqfeyo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpzylot.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqljlcz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxfzxzg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzvbeke.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrqxaos.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvgclil.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdzvaif.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cnokfmca.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2owzmwcly.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyvpogr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jgusiwos.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zgadfbfi.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2daultkst.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoeqahh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2psehptvi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qatusrjt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wucdauei.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrvriwk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ashyexns.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2maupkfsm.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nqajowzt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nicalftw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rczkwylj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdxcsry.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzwewyc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2twhmzsib.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2msmddrkc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bpktrsyu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fphgqnix.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxlulsz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxgjewe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsohrmb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqublda.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubovbejm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhwsswr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2keoferja.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyhwpba.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdibaqd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyfndlr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2becqyebk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pggkadvp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyxoydc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bripzuhq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvhewbd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rddfthqw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dawgbtha.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jfczyioa.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeihtyc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcdkvzp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxbqezp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hglvpecv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wokucmsh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsknbvu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2klujyjcp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhbsprg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kubkfwwt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mawhffiy.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfrnxpk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2muhdgnxc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfxjwfj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgojtdz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqseutjz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rsztcxvt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2agqixtih.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kiblzcbq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2khplvuwp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhqrpxd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbpfjtk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vllfupos.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnlejii.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zixyeoqb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2opejmjnn.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpqffni.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyxsoox.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjuavya.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhqyvqb.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjflxqy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwgaqen.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbobtlm.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vscoxeiz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhfqtgt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2olmpgalc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfqfywi.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbihmdj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2abnzatgj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2abenvcfi.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmgvfwj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2asyzeutt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nviliezl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zawpkiqu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzpnaxd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcvxjbz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhdryiv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzotran.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqeyckk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzvzxfg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ungbxcss.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyahyxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pahdbtkk.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rptdwcnj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jryhfrxi.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mekljwub.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhnkhyr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpbzuqm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2irwvqdlu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2paopoays.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yatampvo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2usdtchts.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hcclaemx.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuzphzw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hezuonju.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2llocffcv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhkbhnx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjguftb.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wezmyzyo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdfwxbv.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2itblyblr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2csokubqf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wlruhsrp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjkzfbh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvjqxcs.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjtkmzc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zaquammx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnmnjkt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2evbtjpoz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzgiwdv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2keitcvqn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nvladcxw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrxwhlg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpwfxfc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iqayfujd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzqdqdp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxqspkv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdjrjlc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvmcixt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfdjaiy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2dwliualo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfzgcqg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvxntan.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xypmtxxc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ajomkuds.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmtbqsj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtiahbx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xydszlzo.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsdcskl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzoifyd.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2xheukmya.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzrwngx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhxcpom.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsbygcs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmmesxv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2izfvqwdp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqzfbrp.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2pesbzryd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cohzpzku.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxeqbzy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2isspdfaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xycrsrhp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fezvnwpv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rauybpym.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fssbjmjo.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kdryqqwm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeaxbqy.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qparzcka.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2begsmhbj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpgebfg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsoptka.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2trexdibp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2amwmdwjj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2dklapzpx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2dmopyjcm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jyymudwf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmlpqeg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vgadnzwm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2eguwoyln.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2clzlakkr.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgfzepg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ifytyjvz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yitoyfwq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaarmyb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kbukytcs.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgomfrv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmnnwmj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qailihrc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fekmpreb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfpllzc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpzjbfs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mivbmzzv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aofrcrat.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxxxcft.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgguvteo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2olckfhgg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wioiszdg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmnkbyf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2clehzdph.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cucakamu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hizbrsca.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnzmotz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhxjopi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lddmsurf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnaalns.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ardhanzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjveiuyp.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vhayvlmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyihfqg.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2scksxzpk.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlohnmwh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mcketbkt.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rriephlk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfdcygv.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vuijalqc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2orwqjsll.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcekqgl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpunfrc.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2jytelvuc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2livsdyqf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmduruoc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvbrhaj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqcryqv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmshrxyc.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nezbcfyt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkiunth.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgbwkar.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2txhmnouj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2vazyaiua.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnzrzqe.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2njpfgskm.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpjjrsl.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuvmwbx.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2orobnivz.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vpoctawn.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvpfbuw.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oltlokba.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqrnvec.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoggkgz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2detuhanl.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjzbuud.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlxbqwa.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2kacszpex.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2bptjlxaw.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwzynbd.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2isetfajy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2glmvmalm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkngfxu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbicsmv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdukcqv.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmkvcka.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rksplwat.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnitlbt.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbajnlbi.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzbihnr.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoibhbu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2npdbnyew.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtprjfiz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwmvnht.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnpkkhb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfdejou.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2mudwfksd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkroqja.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2auraouef.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2awxbonoy.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jevtmypf.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyriaxgu.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdpigkp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvxtfud.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtkwane.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2apiwaojq.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfvksfl.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2njegyvdz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbegrwl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhysxog.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwpwzva.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxykpms.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvfxayi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hterqlux.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2plvpvoac.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2soksxotx.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsmtyzo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2efxefsbv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbnkool.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcfmzqi.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfgozwp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjouuqu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsnptnc.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2pmodsins.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxtchdl.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmkxgwe.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtbcjgy.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvmzmdi.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dkavjmsy.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfabiit.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnotyjo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2vvneojxy.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuexaisg.html


<!-- 参考信息 -->