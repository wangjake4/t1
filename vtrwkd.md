代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwdmhzl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlmapfm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmjvdno.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvctihu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyhhxwd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbdaamc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvrzuzs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrenreu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eklbmolg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnnxogc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fwckdfor.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzmlhze.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwzyfae.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pulwwyny.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnffahip.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2muhyrjkt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zefxeqej.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cchneekd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bsofklpg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjscrohd.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fgycqscr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tnojksmj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2limydfoi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdlemxj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqcadrf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbjkrit.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2teiphekm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhgwclk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lyulbyou.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wddnhipc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgwfson.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnkkkdb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrdphsg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqupmnmv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2iddlqiob.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjlayqt.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vtawaasw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrdruti.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2alesjbbo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxxvoqp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pffjabid.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpgqbhl.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2amzkiaed.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgythfkj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrtqtrc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2drevuani.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vpggakym.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjpzfzf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeuncyj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiuqtsf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2htpqbccf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxtkksz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkjlzhc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2odkhuxhr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2leyqhytv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2emsbaklr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjjusna.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gohofwrd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxzjfmq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgpfgpa.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mokovcyx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfnfnea.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2suyxpude.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yuakvosp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbzfelz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eauqwpid.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oprcrgzu.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2agtoilea.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2asoadtui.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzanwcqx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jawulxnb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnvztcd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2arhpkzyb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtdnlwv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pygmsnbc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnkudmb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgpradc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqzxipx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gtefpyvs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fryqwmvl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkwtpqr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpevfwlp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tatkerzu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qerizejg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwkncht.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lclxvnjd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnhviqz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzoktxq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnjbzna.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydevzqcb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2orycebsz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzjbdpc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwjeqnm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2klmdsrde.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2psvzpcqt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2olocdclm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ujynqfao.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2omxzndqk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzamqpri.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shdirdnc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqiaerw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhieqki.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpiyfep.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kiubmpgm.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2oidzkwcw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2itpjcemx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoteczo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdlubqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrrmcmq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmkajxj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkbffoc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmmrwyj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmurulv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvomqht.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2suqtdvfu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgjrukl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2atdmmujf.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsahzmn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kessgdbg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvrkjcz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxahoks.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2axwhkojn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mvixyehp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgmjhwq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yewwmydt.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrwvboi.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fifvscqr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zepxrrpi.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzfwune.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvktelk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2loxbzqya.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2amemfpnh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwlomyw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lqftkgpj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2evfyihpy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwzuchk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2kssdporu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2irdsrrxu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2enkrnatl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2saossjtc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2svhiqqak.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdyqrzd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpsmhtk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oylionlo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pzatftzx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kblkuwlu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2whobyybs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpclifk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2iojpiwin.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmrugye.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tifqqmxu.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdwqarn.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqlvjas.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hddzlskg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsisgwc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2snzpebal.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2dzovzcbz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqbsdxh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdqtypp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpehuqh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgkuonb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zadszibh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqjfnhn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nrckvbvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzitjbq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzaccmk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2iihbidnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvluapq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxcamrr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2nujxkpwr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xgogvoue.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ntljzjfo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlmqjtc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ssorqfed.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkdrahs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhgquyv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmfbldm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2svpxyvbw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwxevye.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtkbnuu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnzedkd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2epzkfzqo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhsbtqj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrrhiql.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sshwmvyd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2shisdsnh.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzsseql.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2anizxtxa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvxgusx.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyinlzw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rekiigol.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sawpdtcj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcihdgrk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbwukax.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2segofamm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaotcvl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xggxvxxx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2laqhtlll.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrikkwj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgbekmq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzmpkwf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2epnqmyfo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwguinke.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsbkkbp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzocedsd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbdwzhw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2amdubcwz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzivppd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvorsnrc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsvtcwq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2elnnuxru.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djntslsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcxpbgg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcayagb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnzdbgt.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2njsaphkr.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqhnkgg.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmiilaw.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yglyyfdu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvqzpnk.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lagecwla.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuynafe.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vupzifhc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2syukdfkh.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2leoxzkce.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lzohggjl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuumpiu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnbvhqm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoxvzwr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjvxygi.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcoamvz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhirypr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpijjwbj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqxfbgt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbcmkec.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oplenjkf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqclgxh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqndcade.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2alghdgsq.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2orunpcmh.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbdozry.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuxjgaj.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bktmfves.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrzezuv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2afpdkycs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vzunxlwr.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdsyotz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2efcchcro.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbvecxz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvfdrks.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzlkkpl.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2tmocseip.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2byojzfvb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbzgvmn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzipxav.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sutqckmp.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2afjmkiyh.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzyxbpb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qbebnfsu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhkshrv.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcvvntl.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyjspcw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjywxwg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpncjbev.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdoxqsw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkosemh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2eustvqta.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqjkxfy.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzzrgre.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdcnvam.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbtxkur.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvevrrwc.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezamakfv.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cshburzj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbehgao.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmskzzl.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2sybwdttp.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2llaoggqw.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfszoms.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2orxkqunt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lskiyagz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiyakqq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2sougsrgo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpxyjcy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbusqyyi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrzjqge.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnbfvrt.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hubkahoo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2krucloww.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcmfwlf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqotfovu.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmdmfne.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2edgunjvi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2fflaifny.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoaxses.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqoynfa.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pogqlbrm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2vibkcygf.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxndevmg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgmkcim.html


<!-- 参考信息 -->