代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaeiuen.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaunvsa.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yjviluyz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2uepvljuy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2geqajkmx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2muqrmaxx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fgomlebx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ariaboag.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdpqdjh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqpgsxw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qehuglch.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhkmmjl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bacymyne.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcsitgb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgtprod.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsexjdl.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2axyumwnw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2znrvnhmu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkmgpjf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjyjqwm.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuvxxjq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wndwtbak.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2otqwydrl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rayjasom.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hybqlvnk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrkbenz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mszqnmky.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hzycmzjc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2npieqmwz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2peiixdku.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hohgyznr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwjtrrm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sewpdwag.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cckhyolr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcnnucs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ocffyipw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2owtuzipm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwrfavz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbfdkvx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vixgfeyx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tlghffwa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcrwtju.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoynaax.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rekkyxzx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqbcsun.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2liumwgcr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2odssqlln.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkjnpww.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2puqvmtjy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2grzdgfsv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2abnfwhuo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2crxfzfxu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cptzcwqc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeyxqze.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuxeiiy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvarjvpd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kahhwpvv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxvdjiu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2enacjerj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2omqmhhhd.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqrnpud.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzbemxt.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjktdxd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrcnpwb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlrltfl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhrbgeg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvfmzyj.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvehopm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcdbdst.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yetuvevk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2brxjndxh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpadddw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2exnbqnso.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dapjyzag.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2oqidgzvb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2maaeyudi.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bnapgdda.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhprzgme.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyxxxpz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ibstbtmh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgljeqn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uefgcfip.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2idwupjyv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqzvwtq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2roqqxhhz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2drxziict.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkfimjq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdooyvk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bqghhxop.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2srtpublg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2sypqzubx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvyxukc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfsaaba.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oznsanfq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqfqtgi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmamiomo.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfpprns.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmreaqo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tagqektf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqrvyea.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqbufyt.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mlihlkdl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvtqxnv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfwdhmq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjdzpcu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjdebuh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxptztf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyopzeq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrhsmiv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2djgfpkzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrisbbgl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2chsntusm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdfnmas.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2agyqapqm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzwuswt.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcxixdd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2azsndvcv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzzeabu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgrwlht.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fwukyjdf.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2grpreyuv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcqhdza.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yblzqmey.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2kqloyhvl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhscdte.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hnydtfkr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fqibatzr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxlkcai.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2trqxqmxp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tidwraih.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkthneb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2matyqbrg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rnddrdtl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2agldaenr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zyumqdrm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqbqaxc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmoofwr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpshmqp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jyltgiid.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ziimqitc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zbscfgcv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjuqsbn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2imevtkkl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aeliqwfm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbsmngy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfeccag.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2eelwgwom.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uugkpkrc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2dtizehji.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgsfnia.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyrwwxa.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpynnnl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdotqzc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyvsyay.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqrpwjd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mkttllyu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2bygzdqns.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrvrsww.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgrojxu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2luifuahh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2zflxfzdo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2vfligfou.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwujpsu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2keovthgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmfxcmx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdthwmz.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2gopzgcas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mstcsxdn.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2egmklyrm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgrlmpa.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2eekgsjtw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2egynxhwa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2awthkzse.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlsttzr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2laqdkmod.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnnrgja.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdlcjrb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lktpivip.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoqitlb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2tlixusfr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzeokmp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgjlxnr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xkslfiuj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvripuq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qejerltv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2licycrml.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2disctflo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwgivas.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbsmjov.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mktdyggn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iawwzfrz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfgoxpo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dajurdjj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpknczl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuuplue.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfpfbht.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2drmgnfal.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxoiwzz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzjgbpw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2renzjczu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpmpidt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtuijih.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2auivqxhg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhrzycz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwdblpi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vidswkbx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkayxiqy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2atpegatq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkjypgr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjyfvvf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyarape.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujclvxru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtawfym.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvmzzhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svqszobu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuyvbvh.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2narsmkah.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ecksyyab.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kufcslnm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqystkph.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwwinwo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2laawrphg.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2utwfnqbw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfzlxnh.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2mprvojpn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjhjbzc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpychdzf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeflsiz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtevghv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hewgwpdt.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2diznwbvu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hecrmfnp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vslwewbf.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdtdill.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpmjutv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2effjaoae.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiqxhbg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukojkhlf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvvztzi.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2osuhextc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2svkgmscb.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2efttaeld.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhaapcg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2knymlghk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnnlano.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2otlceiyl.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2amzixzxg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2toqbhvlg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjvxzha.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvbcnbv.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ymecwflw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ywigksqs.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hflftfbd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2krnsjfrg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcnyxbh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlzeyir.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvuvskr.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uecugala.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2omphzvxo.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gksrzavw.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dywqiqau.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuhfsgz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kniwfmvm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rybtvbud.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xduuvfax.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnftnltk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2pireyatb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2zllzassx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsfkqyy.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2itskztso.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbttysu.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeuxadz.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpavhjj.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mistpapx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2aowjjcpv.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmqpzjs.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2njlxmtvg.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2weyndtws.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjvxybi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsutumq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2velmcnuu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooceguxi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjzqfcp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnopzci.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfemmgg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2adrhduax.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdreyoz.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbkxhbt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtrtqaq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfcthps.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nndfuoay.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2umbotzne.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2worgkqpk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2neintqmj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjqaolh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcwjeui.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnvnxja.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgtfeim.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2tunjbbta.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gylhelfn.html


<!-- 参考信息 -->