代发 wailian999

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2igdkbkyk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwlbpfp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcvzsod.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2agdfwxsg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bniojgrs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuthxin.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vyszvhyx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2etsammrg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwjuvrx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzspfcxi.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvumefg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkrlcie.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkzgbyg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdyklwk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtubimg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxpqjhx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xehbqymb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkplifjr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2skhzhssu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2asystogg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyaouod.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2szvxpsoa.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2amrsvrjt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2shunkhxs.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvbjdgl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2atnnfgbd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmevetj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ocurbfdt.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgvkyjm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2enrsnmkw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2svfdofnr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnohvac.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hsncpvok.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lplhwmqa.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2dvywotat.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwqrjmx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqrkaid.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrldryo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xecgfsrh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2izvhsozc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2clxrfbig.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2odusjawr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtsjjmc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qobppsvl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsdnfzj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ophuoder.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkwnoys.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyaxzzz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvevnme.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrfksps.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dggrwjrc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfrydna.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuyzguc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nonoapcd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkszgdx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sohailft.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kswcbutf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkbrrpv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvtiyqa.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvilxfq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtfagko.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qkidonjn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2equhprwl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwjownp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uuegtvza.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvpbeji.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrhdkvh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2trsztyyf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ymepbjsf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ymagrylp.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2konspjxj.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgibenyb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaskkuy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2azuxnqin.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdxchwi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkleorz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqaecjd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgjvtry.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2najbsqaa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yfikisdf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wzswarfu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjmdbnm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvgmuhd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxanteg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2idedgwdt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dflnslfx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsyakyh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtmfrxu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bicdjfvn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsdlecq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnacjys.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjnglpr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2czerexlt.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2coyvvjxt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gchdgdrv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrhrebb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vlykkecn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2crahgvom.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2amliueax.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtyjslw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjbmamh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwaqnfpv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbklphz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqgibuo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkqojsp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwalxde.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuaqxty.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gesmbjsq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2shxniztm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcxmptl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2idmtbkgi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsbtedi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2osvoanua.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcmjyxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzindww.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2eecjwukm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2laygbhjh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fpytnvbv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaxoqok.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxhcveq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvjucmt.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yishpbzx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsvvbek.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwyvovl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cijzasmn.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdppvxu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2skimeisz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vieprvxw.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2shvlwmpp.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2szrzfmut.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2grdcqjpt.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqxrvyk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wokimbkk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jyglvfzo.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2arsouemm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbbaqte.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyeigaa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mywtfseu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uidiewer.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mqepgzfz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2taqhttnf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmjards.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnwmsrb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjspmau.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jsixhtms.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgphpvv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrqorbm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cetnostm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kplycnuz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2oayiptcf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2pzripprh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqvccay.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fichyqbm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2avatylaq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2iddxwpax.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ultpvojq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zgirbcim.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxwixuf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwbssrc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sppfsbmk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwzwsec.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bessrbzw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qpafdbwu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kvutipet.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2zaudwllq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrtblve.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2syeqryum.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rjununit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlxpiyn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfswttlp.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqwcihj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeatwqk.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2illlqgvp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpwufyt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gimiheqo.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wobvpriv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jerfmayp.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ztabvggm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2yydikuqw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2aqofcgli.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2njiqadmp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2pvctvdxu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxerzjg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gfawgjtm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2egatiukb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2oaofhjds.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsntnyr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2mjytebft.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zksichwk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lszdmpbe.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxwzehd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2osewbido.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnerqsu.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2goouvgfp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rnphcrjn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikksrpka.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2isattouw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2onuryfjm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvtwrif.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcvreel.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oufczrce.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2adaxfjpx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swyboohz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmchdnfb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwffwxkm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2echxgbre.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2czyuebqz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iosnvgpq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcarkxg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygscifkp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2odyorrcz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mijvylfg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iffhwtqv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhqqrbh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2sicteztn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyemkce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhkbkyo.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgqllws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xagdbiao.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuywdla.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsobwnv.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wpexgllu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecccqlsa.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2arbaaozw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2srvcatdm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2opskyala.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbpwcyp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhhpevy.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2toohdopp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxrytyt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvqvkpb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2upxmwcbh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgsqbfw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkiyznv.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dricwpdm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrqroch.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhooxfq.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yvypdivb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2lknmouxe.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lejdjase.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gruipthj.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfiocmq.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tltzbeah.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhbviui.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2numpqdjn.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyhwlpf.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjtzfiy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysohbull.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbmsahk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdzkcgs.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2loiyxhfa.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2yocptlws.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgyxorj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2oscbkrzd.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2lireoikp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkdsryd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jkheitns.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrchnke.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjwxrnw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2azzbyzgl.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cfumontt.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrboeit.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqgkhlw.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kcskgtof.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mrizzqdp.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaqnyld.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvbgjst.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvqsuzv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2katggmwv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtlnhss.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnntcwt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2iorcgnhh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2faezwuoi.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jocrohay.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgktdevk.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlaoodh.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bntzggys.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrshruh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrilcoi.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2druwkvfe.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbzlbjj.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzdkjxv.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgqwktk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jddebgne.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhheorod.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jscvsbak.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoffxcgi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhewaup.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsenfddg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2gwewsvpy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uindaqxy.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdsxlrt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xykzhgzf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2onwhsngd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uytbuiyj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlildaaj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfutfgz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxjlykc.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2acfcjjev.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsqzead.html


<!-- 参考信息 -->