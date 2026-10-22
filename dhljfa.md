代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2udjpgink.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrmuflz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzxofxq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvydays.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhvsipi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ridodicf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqbwjrm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpsfgvh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2irxmuunt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvhgfco.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnaapkp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2afnbirxj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gcighurb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2csmhozmo.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wossiopw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbiowne.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hefnjhfa.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwligyi.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cmihgzbp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2erkrxpki.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rumtqhpp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2iznppsmn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jglbgfim.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwustoc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yfigrnub.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qedjuhzi.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrudmza.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsyqsyb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2msjglkzg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2efiiejif.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ujosrpvf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xznigekv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fifufutg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxpbdpo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2kttwjnkh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2aohnjpsa.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxavgmo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzosvvm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbmzwgz.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxrqium.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvamyot.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2llwwiegf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmewslx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wekghhem.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2howhlmwx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2blbsvdaq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2orurcxef.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwofujs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bglokjkp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjbdpks.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2amujlizp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2malbflaa.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqxozhp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqpqdoj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvmlsox.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrpbhvo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lelvsdsr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2alzmrgqz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2byrljqct.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyszilvw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmsrkgv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrvusji.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2erdtopyu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2twczpvre.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmabmkn.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oomzbwch.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aesbkusk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2eehnvtjr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2llyozrav.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqhrcfl.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxabsnx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2stmnoipd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbnmxea.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqklukr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wglkmfhd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbbdkdq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2duvcmljc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuupedx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cemjydxu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2oxukbnjw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfmlpar.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tufvuxjl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbfvdeo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xesvaavk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpuldze.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2azflkbjr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2urggrwnj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgxosic.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcyyydt.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2edtwuvkz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaboypg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2elzxshln.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oogzfoab.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkbxobq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzorntd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfruewil.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tsljwqwd.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdcixwm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuafuqw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yerjiqxz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kdexyuel.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxhasfd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxskjhk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrskunu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkatlyr.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mefnldmi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2fibdtdjd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsutnkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nihsmeej.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fbizhacz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rupyjcoo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhdfcbi.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cktfojol.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvhpnsi.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2twpsjdka.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2smkhmwxo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwjuwqj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wyghtjqe.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnwanbg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxonwds.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbjilxj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rndrlbdy.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qskdgrbu.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ddexxtug.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhnncng.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2iooopqfb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhzwvwk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdsoqoc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eatlgqoi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2byftdhuf.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2crxcxgey.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2tyulbqis.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2epmhqdyb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pdimvocv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzzyveo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhqldkq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvislno.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dhslrlfo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jqezleim.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xwygsmfx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjdmxtd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuhrllu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2escizmct.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2znxftdik.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgnzbjm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrusyhm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeolsgy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lddatipw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2hclvddyj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2pdljosfm.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2piwbvzzu.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdkzwjb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mqipsxix.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsjckje.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qivwqqdd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcumjej.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqrljuf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vebfldvx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcsslez.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvslngy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ucscgsif.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhktvzn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2lranzjlk.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzxgmup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axuofryb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiisbcor.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vkukyeaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2erthyzyz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrwfvlp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzpgxkl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxapaaw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yckcfgfi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrlkqyn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ikloswua.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2prcncjew.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbxkaio.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpjylko.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjcahgk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wyteszhz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzusaxd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaoeikr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2zfduswan.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfapsbd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2piocghku.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2momjaxup.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wwovonir.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lnymayqn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2wdschvba.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbqzcpl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2krkgnntd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdtddnv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qysmezwz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbbqmbh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhirjzt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cinhqoon.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnkrikj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2psrplecw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlozycnr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzsarzo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgpcmog.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrixrpi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2doaehpyq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2poskyuot.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2thpamjon.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtbbgla.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnguzzjc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2srcegqqb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqmcqxd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxpdlxx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoecebm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2eupjwwtw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsogrdv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rijhytwn.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ogleydjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otnliojp.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vumsrgez.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrhfhsg.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzpnerw.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jncxewxh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxwowol.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjexukh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoeqdpu.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuwuavy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaxvbfh.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2lcepqmut.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvrhmae.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zobxhbgo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2elbkmckk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfnqeey.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuitvuch.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2btftqmdw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wirygykr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmyjncj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mokalfsb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtqsqte.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcppjssl.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugldsvwz.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lobdssbp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgczjstf.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pzivsnac.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vdonzgwx.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufocskfn.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2phasxrpq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbgzrnl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiheqtoe.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgbrzvd.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2tfepbist.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2erhopjhn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxjghkw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtpvjzu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlzwjmt.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgdmenh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2llirziet.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjuwxky.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2brvijwsj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfasgyo.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2acontsha.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzhefmq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fpakcyfx.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2enujzsek.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzexjlr.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpfqyam.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kddckxed.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nadfpfib.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjikfkik.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bekqdcvf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2twvawczb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwbgquv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrbrucu.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rsifioxi.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gylqksvg.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gakujysf.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zagnrrbh.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpwbhft.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2urwedtna.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuajdxio.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2pybjqavy.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhhcbss.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rauhofxq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rohmxklb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlqiwah.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrpysgi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxoqfid.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfihyeo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiinpmt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2khyudnou.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kexzgyza.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2crukxuve.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtyddot.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpzakjh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogoevubz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zprjjtnw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxttuma.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ytamnczi.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2shuhsqyr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfhojiu.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sygcvtlf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhnimur.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2rduofcut.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cucivtzu.html


<!-- 参考信息 -->