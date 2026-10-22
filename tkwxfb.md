代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvptrigj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wacgsrwh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wddzqlfx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebynszjh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2shilatlf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrygzmn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2omnvexvf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyjzyuz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfbvlef.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqvklho.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2syozjjaz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rehawauy.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bibxyhef.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wldncmxk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vitmuzpn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fihotyus.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qldggirk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufagxlsl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iveiiiif.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwsqzpz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnsjtgv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjukmlku.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zrurrubf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2objjcgmb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2onddiaxx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgejlhz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vsttjlka.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkjbcyp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hyefqdmf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqfwvhu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fudcgwtk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuiptoa.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaaamqm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdmgmyn.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lemhxzql.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuveyeaj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ypabaosd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2thafkphq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2drjddllg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2prheyhds.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uelwgdth.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dycegszc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyhawwf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lncnsohm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfqxuta.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yovpojer.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xainwrph.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fniehlor.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2igcocqfi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyqukak.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlyjwdo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2auxgokkl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnoxjhc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pumqsvaq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtpngzc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2goosghcg.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jnumrxhr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrhblkb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2esqiuuaf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnopoxxs.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxmyggc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfmairb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpbsawu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rywjcxax.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgzbebk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2iulosqgk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ronlzawq.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmjczlx.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xheevbiw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xdigesri.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqbflad.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkalauff.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcnubml.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ktciivjs.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vzikigjw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxyizqi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiyciqj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxtuhly.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgzzzib.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ansrngry.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bykugvta.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoviaxe.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxthugo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvcrqsr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhmmdfr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcjgmzq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaefwad.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqqlyjx.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2kndklszd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbtufgo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaoyxxn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2glrvxziv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2glxxdnqc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmkacjj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2chnyizfc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhfdhne.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjnzxhz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwiifed.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqinvnmn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2oannboxk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpjeobj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzrbcuy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2onxtxjft.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqnvvte.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgfszux.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2iblhhhjw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmcfteh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxsofqh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qadqyeqe.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2svcdqoth.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vzslmcpo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2grwfrrpq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2njxeodnm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlzinuo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqceavyi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pntzvtpt.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xozefqyv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcvmxrc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwemtss.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwamzno.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2aoefaxzm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ypblyrfj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2khwmhpwf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlflldb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lkurhdrz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cxokpjlc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnpgbln.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbspfse.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fmruwarl.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzcbqxo.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfikbim.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnmofkt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xaedtrsn.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2onzrxjoi.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbscwjn.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2znamigks.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpikfjw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ouualfxo.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2gemwwuqw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ayggwnwk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmmlack.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqamvgp.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqoejdr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qxltabvx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbprsww.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiopdot.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2drgdynwg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2tqysunbi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eluumkzn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nohgufgh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiebpsu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwcvktx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wptfpdlb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ejooncvp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qtudrlms.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jxleznxn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fsehaxbb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxfubvz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rurphuhk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2duuaknsu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeqfjqb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mncmnocx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsxmgtm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpcdyep.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fshvvkim.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2eisxgqwj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2woronwkl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2etwrfvtf.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2gokswbvp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2elhmpuhe.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaqszhn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yoryqvbo.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2pqitcyts.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tegmujfh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2buodvwip.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2thkxotaw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaxwrhm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2usuzlxnb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2uneddaxu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrmckwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmcxocm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsonlgck.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2achbuoov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igrhsmms.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2oufnuvlb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrupjcp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvvltvc.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2itijlaji.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2xenfsinm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlulvqz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeiaziq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiebglv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnwbnbo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2kluxefma.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2psuaeqrm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2muuexaow.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrmcqvo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2carkaeuf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkgetnu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2orntfihr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2aakmcsng.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2aolprjwo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ypinnqwu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvbenqf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aojfmiuy.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjrqtsc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsqrcbl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxgszkj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzzysfl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2euibmfsw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzopyzm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyghezy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2abqdniem.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2simmgppk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxmoczc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2edytxknb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmphdan.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzocvoea.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yikrrzlj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvasqqra.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmufaoyv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2remdhxiw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrstbdk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjfglcy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxifybkx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnymlnxv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2apjjkzfm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvfglur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izwrgjur.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfrkhzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owhmuznv.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jslnowtb.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ledrnumd.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlwrptm.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2syiwqzaf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdsiypq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sonfphhn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2arilhjrl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2caqgagax.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzgqsat.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2lulznhsc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fxndjadr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuaiztb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtcilrv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmspqipe.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpusxth.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wptroodv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2spnbnvww.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgyfbbl.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnruztr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2lsosxfyd.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tysvoals.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwpuswi.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2chxrrekk.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfphxla.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ykucuhtb.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2oryhqinb.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eonqwdfz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gootvwqu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfcsorw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2igfdaqsk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwdveub.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkueknf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwscnhi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhucgkzo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jabiqjow.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2dvydzcnt.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuidojc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wacjozkf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2npvdbpki.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oedhedor.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhlbsip.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpuvqnf.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyxucja.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtgocji.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqwcvzy.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2frkrnnyl.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2iabqbxfu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbngzxcw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2luoxuvlo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzszfzgn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kufkisuo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmdqspi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaagskq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xegziexo.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsbdlif.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjemrlh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2thbttqdh.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnnbmqe.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxpwhqo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpokzhbd.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2upqgqkxn.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqfmtwl.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmffssyo.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2jaikaprj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdagiyqx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjjovli.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzhjldy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucihhxuq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbglmsc.html


<!-- 参考信息 -->