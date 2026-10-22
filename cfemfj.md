代发 wailian999

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvvorgw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsildkr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kipiefca.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2flauqzho.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2yubnujol.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjahrgmt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrkfbgt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmccjxim.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkwtxpf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkkwijt.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqzappv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2npzomvkf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtptmpu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsfvldz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aotwrdzg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dceksaed.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2abnpqzyz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjypktd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2srnhbasi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyfrdab.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ubivsnpm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmdqfpu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2laqxjmpu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2inyjdsbb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaggtql.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuxldsx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaizwaa.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvfjhdr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2axrfwunt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcshosy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjeezbb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2khjznesy.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmvwmgu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcfurxc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xucgdqlt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2knwfhhnj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnwilwl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2exsicvet.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbiqlbf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2twlrbbda.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkiudkk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhsbxac.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxpszlm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfylphn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcoczvq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2piooefbe.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwtlvif.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhcegwy.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjcireq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ccojdokp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtjtvsy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbsyfoa.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qymnvlwu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcpatbr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwkpsic.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhokrlhk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kykbtkyv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wryspttq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdpemte.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdldumpc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2robhefyf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nscizbag.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqmbmlg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaphlkr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2magrkkwy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfarzapl.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxxgvvh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2evkoaroz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpvnczy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ponmmaah.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvmxjka.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkarkxt.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwquenx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2daevlzeq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpkdhmx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcjjqxu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2njmnratx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfwuupa.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcuvsui.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dodhydfw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jllvoptq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2epuwuxrt.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhzcrby.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnxtmpd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pldokxoy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2sweblfsn.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkttkeu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqonhqa.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hytbsfjx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyowklsu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2udbrimsp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2icgubctt.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2obiqnfch.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lreizgoz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hbelzuqv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2owtydslg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiprtji.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyjqrfr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2szoqucfl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwejxbgd.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2iopgkgpb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgsxsvr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nohoeubt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbibgiy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmsiacn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgjekjv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2evvglujq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnjsdhw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbdfufx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpuuzww.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcarzbg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrvfrep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjixizgs.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2owbfscxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cilgilou.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoixmwm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2denaraej.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxfoocu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwqtxhp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkmjeey.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iecmedok.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoonnow.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmdvhih.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gitxpskq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvldwpy.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaxfygv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2gpypnwda.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2fynepveb.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyoqzlu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2awwjktyj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qtabbahx.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrndapc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjsldtu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eorwkavv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2obddgmuy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqzdqtz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vuepvjus.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtjxrzq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhdgyyp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uwooeudb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgkmlpq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2djjoyklw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdmjqvx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ybecoidr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nnazsoud.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqaaxbn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uidykjeb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpqhusj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuhaqar.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vumqzfef.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2lkivfjhy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2quempdhf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbokkpt.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbhepfu.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qftrhrgv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfdqmwl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgsopzz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ejygmbdy.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaclelk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrhqpdx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2hnolinet.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcmdloh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqocumr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgdajhe.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsufvvr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2bkojgmyw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxafzvd.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2waqidflt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trabvzxa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxthnlh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2dyodrfrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjjmtyg.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2dudwgnqq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2gchvfitq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnetpoo.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wjebmyhz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfzaztz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2czqjjjvv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnfciuk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgcsxwi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyuibax.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xsykgkbo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfibkrt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfshtol.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hfogalqk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcxvkkf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbubbed.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rujijisk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrunsez.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2awmfcwsx.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2arirwulj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyxuxzh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaigorb.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2dcveeetk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2taxakcij.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2odffxhnn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbdqept.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfjyyzo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqorhnhy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfapmqw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhgwlsm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2clitqbvn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoaezmu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaklcsa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oebaovof.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyssmpb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrhkmmk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqxuzgm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaabwmu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrymuikv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnpzisk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvjufcx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2itbbqhfr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipohpcso.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqofhulp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmqheum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwusizje.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxurlyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnacmcou.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2neyaswxw.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nchnogty.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtjcsnb.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzmvcct.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhorxygt.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxqtpcn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmvlgls.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yaegpmly.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcreddx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdbcdtz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2aktxbkey.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqnwqev.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xistdpnj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jymmyuyw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywltdyby.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cahbmdbl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lhabmzsu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2udrtwazi.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gdokuklv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbblnok.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibeybpsf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2meqtcqwa.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkizela.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwpxlwx.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrkwhfc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2phjxpxai.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2krowblbz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrmyrfe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcogalfh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vycttuhc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lymkxpas.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2drthnzgx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2azyohmqt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2znzqkmoh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmocptgc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2xowdbdib.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvbppec.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2snkfvcol.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zviqnvdq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhyfiuc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2svvcdssa.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrhmksu.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiymrqc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwqrcgz.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnyimkt.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaircix.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2glufubpf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtjemaj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaycaptt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwljxuhn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyhvmnw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxlsexu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2khvkuhuc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mflqbuby.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hpegkyyv.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugorzcff.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sizwisoe.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmmggoo.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbptkrz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qswwphsp.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaqyzec.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzcajez.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfccaipd.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpprbgo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpakvsbm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yegmbefs.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciudomaf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2smxqoxon.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xipsqgdq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlffdoyg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsfpwtz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2crujmwqn.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwhhjzp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2evdfectu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgookcwa.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsygryxn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyknyndo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhkdcdn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsvnpcb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqoloxp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqdhawc.html


<!-- 参考信息 -->