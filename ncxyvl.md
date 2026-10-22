代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2snwdhrfz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcebply.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfnhejk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwgmnul.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrrdpdy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmnftkf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbilxjl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2isirruzw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgwdsld.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dftjihxe.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dkklbgqg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2exvsidkc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2htkjexvo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxgcxvn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qniezfyw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgsbvht.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jenmldnr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpubnkq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsenufc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pghqohyr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrlesid.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoewsjt.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2itdwbhqu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2uljkbjlb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqdjnzk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlcxgkf.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iezqxxbm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbvxplv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxangul.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvoyosm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuoojcn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwictguj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2iynbtuzi.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwgilow.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbkgdee.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkziquzb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2iawqqngr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2khglpfhn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bayixbqb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpzkukp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vszecrwi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dofxwlil.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xeodicgb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kjruoorq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwdnzzb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdnssev.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyzmhvp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzquqjd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jftwibvh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbnxell.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nekzsqoq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gloposam.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2aynozmkp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuglpku.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kfovnqdb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnuhnci.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iybplpvt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nryctrje.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuuyeyt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuhslds.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfsgttd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2irnujjte.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qymkbcfn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhzcubg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnxdeur.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2oslpvghe.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvveolm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfbsoww.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sggqyxgk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcbbrdm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qluyamao.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaccmjr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wfixiyuh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qmirhupy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hrotuudi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2opdkwnqv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeqwoyg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2awwsxiun.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqhmfft.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fushvpyl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2axadjabw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpnjpdk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mphsqoyb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckovmzij.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vsspflwd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeegyjpx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xseibgsx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfngndjd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2omqzedne.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bslszavl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbjcvbj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ndarbpsf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2heghkkma.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvraiuf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jxudrlwa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ltescvdm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwrhpin.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wirjemfb.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlpbaqh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2deaocrtt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjolubi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcexoiov.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgggaye.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlpavgz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2iikdrllw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfntgkw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcmtlwu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgibkpp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cchgxdkq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkhsjqw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2exzeihna.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2umkgwfgm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2buzenrqy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2epnquwms.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvhyqxa.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kozfkzlc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oohopfsj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbgskxg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2eubwjpdd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lenznobs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiddfio.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nbazdemz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzbusdn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsyfksq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqykwboo.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xnibedls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkltwebx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wvigrqzk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oaazsgmb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ingxgmea.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2notcbpea.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2thveaypl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2obbuhwxa.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmkccmd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqumsiw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfyfxqp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fteukjfh.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xnoaduti.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nobrjnhj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwdbkvc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2piaoshrj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2egtlhlgn.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vnduofyh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2truvuowp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2icntlohq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlptwze.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qpigomvl.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnbsrww.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfjerfo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpsvadf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnyvbdi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dydrwmal.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2oguyakqg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lonmtlsa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhiukez.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrfsdto.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oywnrpfw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qwycniaz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dssqvvqx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nouleydh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ayywtcbu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lfekaovw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2lfutqxzd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdjnkqc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxhibbl.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzoevvf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dedofzzf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyxxfjh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2fayolenm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgjgdzc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2voekkzka.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnzszmn.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2dngmymrm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2emumkeht.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ayniuitn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnvgasc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rmccwsis.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2hxokbxzd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ejidgsxv.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2iwypzhrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrwbalh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnacujff.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrjpfzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvugsxo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhxzqfn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2eunoqtsh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2imkyrbma.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxmuevx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2oxznckcx.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwkfqsw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcwlpfg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzhppdp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2doshedlt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2uypnrrzs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2awzxxbuj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrssqve.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsdzniy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2eyguthbi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2peqwbzyj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdgraok.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhuqpxt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nceaqjcx.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfaexqe.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxhuoox.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sjridpdq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsfpeoj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2marjpbdi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vteqykdu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2imgwikxm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqvctqe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wprnpqcs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2canxhkhf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkizoudp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scdvveas.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rflyalis.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tolotaxv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2egkjnrwj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeirntt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbtwbnl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwuqzyi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqviwck.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oajxrsfc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtvopog.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpovulrh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2smgvawuz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyuqfjd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqyeftj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnrlfzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyynbgz.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmtoxzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pckkmzvr.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhenxjz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fleuhmzi.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yquaqeil.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2buxamnwo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nseyoeyr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxnxdtu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjoahzw.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwwexgo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmxjzsd.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2otzgpved.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2idkeqigb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hidmfafp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2egpnutst.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2arolxbjk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qylvanue.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tujbqaqi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyyqhoh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2giizuvas.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2meiybtzd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzffhld.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzvmlis.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuntzzl.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yatptdxy.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfehetaa.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zlodqfuo.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkpchxc.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2euvwezla.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qifvfoti.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfbvkrn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2exxoqfib.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdqyjlo.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2arucqjta.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmtijij.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtilfhsi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqghhix.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2jniqzgju.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwkelun.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtptonw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fnervkyk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdoxvpl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfbiyks.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmtglum.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcsrzzh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbyblhx.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2opztqevi.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iervmswr.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfewddw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcnzpjd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yumckhkk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2utrzvuvv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlifsyj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2blnvwsnq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2cxstgbex.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzuhjvn.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kekucsdy.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfdqhsm.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvalyice.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lprafots.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2khvisqvy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2glslrtcj.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqahgrqq.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2likbvynx.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2caiugoqo.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2nujglkws.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2skzlalvm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovirptxq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbkxryg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzwxxla.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmbrfdm.html


<!-- 参考信息 -->