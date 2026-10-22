代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbvmnca.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhskeqq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqozjom.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwpffvv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2duvnzjlp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvtapoq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iibvxtfw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nfovehuq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyndjkl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcyovnt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pzswvbpi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2igvodcjs.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ocquncxz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vmozdzom.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2veulhdkl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2flqaveep.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuirpqy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtepvcw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxcfnxs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xnotwytu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2btlxfhda.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ovloljlt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhsjkyx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfytvyq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtdltew.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2buihmfah.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2eojqlcef.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2arfsacsc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yljnkdqj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xmowpvce.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpojlya.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2onsrrtce.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2owuxueul.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgsbowy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2stnsibll.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ifevomlc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvvcwjc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdmtyex.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uclaudhx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbynsnqi.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yagngeza.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiaxglv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ballxlmh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2smsphjwg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhafzas.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kflvvxwz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdynayw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2afeimtiq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrbjyzn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qqafmtts.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bswaahcj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fullpjib.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvyodpj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfdqhkn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgbxpqt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjraodv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2esvletsa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sklkplvs.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vrairuhj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2siexrgaq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ilywyrbx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgxpmef.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2egawxcxw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2skmeylbe.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgmtmft.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnahoxay.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtjzvlc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2snqhfajl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpbcuvq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2frolxcoe.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2erlvvjhf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcoeuzh.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wikwbliq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mwixgrto.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dpeqqnqe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2eelszeog.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qddzbcmu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhmzdeu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2drwlgisw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhqppid.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhioccn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvnihyp.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2meruhydo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrrytvu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjihnet.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwhbkgx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgqocyf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhklfha.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mshumxcv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgapaxs.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sbushprz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiewmxh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwkflil.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqzmjqt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nglgtsbx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lefbedza.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnwijtp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwwrinf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeenzso.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwodeso.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2bkawtjmd.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2djcqocqy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvecmoks.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jpevhwtp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxslmau.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2imdiqeqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qngrsogr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrvqmeb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbblikm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2djukqjpw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwsicas.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrnrkny.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcodaav.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbxwtgi.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkyqdlj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjenrla.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uudockiu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2byxvyzkk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbnteks.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2scsnwdzr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2oynxwqrz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnrouod.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2trpigsuw.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ayifpxjc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hutrgdju.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqbzggt.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nxedmgdc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2uiukvliu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkorzfm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzogmph.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhjjkby.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2elsajyvy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfaruom.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzuulmw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhndody.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dguwjufq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgflqyh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcxdwjg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrkifpm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpppgmq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vivqgniz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyafixh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ufheeuhs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vbostvlj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwecvan.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpyovss.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2safhaqwz.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wndgeaep.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jchiiifd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zwusjjgw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rwswlguf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmclcrd.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkbhvcq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqwbgpc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdoxjsf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2bitcnxun.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhvnfsx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2stgukiiy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2elwhhmkf.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2lukkmfbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lccahpud.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsshcmcf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ltryvmmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnimuil.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdhgiqx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmelxub.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdcbnac.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgsgmua.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2goqmmxym.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqbhark.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxqcjzm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2kktpyoco.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wijbcbvl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnyxscv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqqjmuf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2imagmgdh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2fixbcxhl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2htppgoqe.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2zlitqhgy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2irsgnadj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yljarfat.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvnwept.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnmhnxb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmgwzef.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2whesmreb.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaoauhd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bqatrzyk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wggbqplc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgkldma.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvvqwfw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2utfclkpp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oapssntb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuyglbv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxqggwl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzbuyyz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oclmmfjx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ooagaeue.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwzpqyg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2joomyfdj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gysprjuu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwkqmke.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2atlkimxc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiigtrj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2arnkkcjp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzomgxfd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2htsiegzv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgziucae.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkxtkec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oamhugtf.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwfzshe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhmbmro.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2whrfhvsc.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmzagqr.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lrihwwoi.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyhqdgr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2azasmlck.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrryaos.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqhwulw.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxsfzyb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxrlxdr.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqyakku.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzueltf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqxknwg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2istnalpb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdtxoup.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxigspy.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2iignzpef.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkaljyh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2amatdhvz.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlocpzu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnaxsse.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuwlnke.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2shpfcrxw.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqdtxqo.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mchbihxo.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ouummucf.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lrygwdoy.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpxgyoq.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hiodiqcw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kluizone.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzjwrid.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mlncnmtd.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2aqglnkbz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2cohqwviv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzacrokp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaqxgur.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2lsipuxbu.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xzonflll.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2akljcyfz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2krcinpjt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zalrncvz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwxyxek.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsrrqjg.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cyckmdvy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qevmpuvb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpkerfc.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwgpjmy.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fomkkexm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbdqnxu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2czspgnzt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqrfohz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvakuenj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwppzoy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsuoirk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvdhpyc.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwkbadq.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiawjjre.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uulqqpef.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxngfwj.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2glttehil.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2euuwsfxw.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2stffcybz.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2epyfcsso.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlggfqmm.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2shxmexsk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2znkuqmef.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uymftdwf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wehycusq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnhtqcy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkjieoa.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2efyqwpsz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2hhshvbah.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhtivbd.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uicdchqc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkygjpbr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vppdeutb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpremmcx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhvsose.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yngleyil.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfetdrr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjwdlru.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wncqywib.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ousryptz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrptuay.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2aobcmhmw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmeswov.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xeruepey.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vachlbhx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2focgmbbe.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcehzrz.html


<!-- 参考信息 -->