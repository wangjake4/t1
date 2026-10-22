代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2buxcuzdl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2abvqibqr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmqefnj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgeypih.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaovodf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2itglnbjl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcfufdn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjeqqzn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2koapomso.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwgidxe.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2acqqbesd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuezsbd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2loijoteo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2woseopeg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2znmkxxlv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkkesix.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdjxljc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzogibvb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zawgvbbg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2goysllel.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cqehuwlc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhfyicy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhgochh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqtudzw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2scnqfioo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pykmozex.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2axpfvteo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ndupjotd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2daqyurhy.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdccyxds.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2csrcvnqr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnmphva.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vimjsqzq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziksrbdq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkewugu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wawbslvi.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgwcwuj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhjbqwr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xoorwczt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wctgrrwl.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdggygz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzeakgz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xqauxnqf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2slgelyeb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vihqtzvw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlrjhlk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2oovrykhm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kfubkmux.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzpilpp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cigfwcef.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cisosfxe.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2snkiaido.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaizsil.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfrfdrd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwxtqfm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtayxqy.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yoswexlf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nceckjie.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwbwzcg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yreqokge.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtjyncr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2clvtjbcz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2haybmsqu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yywvtdhn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaazqlb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbixtpb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhegqap.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2izveaotj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tipmmdzn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2bowjjwys.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2frijwruk.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvldqcoc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyxvdcv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuviums.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nozzdvpn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoymmdf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeclbfl.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfslyxc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrzvskx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tetuxmxf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zfacsclo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wasepiqj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgehinj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cytpccqx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2azemsgwq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvjmvpb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjfsyur.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwoiaps.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmftcxq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wixisvsm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmrgtgm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwtxvae.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtozzlw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2faiiuecb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2aqszzytm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyorysb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2phlwwbpm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2umdmbpej.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kklrtcqc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mykpecyy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pikldlpg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfltbdvd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnvdwht.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhtljar.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgzsemu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2llytxkgk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2yewnomke.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ikndbdtr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjmtoex.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmvhrzl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2iaudoyyv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxqwlmx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2colcmeje.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhqvafx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2azqvccyn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecddctdz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvzkfif.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yoicfeob.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dppdvfwu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrrasea.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ybstiqcq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgfgwfu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2esbeavqq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlkqasa.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2cqufeemo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzfqbve.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnhyqmy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2larahsjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjhxmld.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuonwps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cibcmtya.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2duixeddc.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyxqzla.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2drnjfysl.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtexevp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2obsimkdq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ligrzdgv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2djhqtcsa.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnpkuou.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnhuohd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nbguxlln.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyqdskk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mswjueai.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2zvddaesr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2foreufsq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2firdtfgd.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmposga.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xxofdcpp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoyjunl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuuqxyf.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmlylgk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rxruhrzt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbiqgcc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xtumwhaz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2reichnlp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjdhira.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2mykfrumf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbevxhq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2evyelyjv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpdfwmb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rgewivjr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrwlpsn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2svncfqro.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvjllhm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lftyuzhw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2spgrodaf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zmusgqjy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2exzjwzmj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2veuhgijg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2krlafzej.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kleiqwtp.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xkepfyvk.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyzkrgr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2deampkdq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ywugqnek.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfhhbsu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqlfmaj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pdehejhw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2pockkmfq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2irppeqzl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ztldunyf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwxtrke.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2cpewsaue.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nyexwcmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anrzzbad.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjpagfn.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2heogdgcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzdyooo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsrkfwx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2cocndcyp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2kckjvswu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvjflll.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hloaqzsw.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2sdswmbfs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2qimdvtoi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxmonaq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzlingp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2firqpkkr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2swvvxyvw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2szgojyyw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiuqtik.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2sblairsm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2oddujbqc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2htedfyha.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2puoutcrm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2flywsllt.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlvzydj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiqskqf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fxymqdaq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjltezx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmhbhym.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqacyxvg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgecjpe.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtocupz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrcgghl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeoonke.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlqvyww.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2inqijvee.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2teeosyta.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjuevgy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2avvupyxj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zefteqqi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypktcdgf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2avxhsgta.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hueacrcs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjeempd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnszqftr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2arflkgmy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtgqltb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzwuqlm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiasqqo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2trxuyedx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjpdeyl.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmgveqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adcuimis.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvxrgrl.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2wilpmvga.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpkuihj.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeyuyfm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wapnjjet.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghreqzfo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2guejpnch.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxregahb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yttzszcn.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2thxijuns.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgoxmbo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqoaipp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcqfemy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjiader.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxdidzo.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuqgasp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tpruksiv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjnwors.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2akniyhlh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2urizpfkl.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcpqdfu.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2swialtit.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2snpkluhb.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmkadoh.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2guragvzo.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2piduykav.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyxssug.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eittplcs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmhjweh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wegpzqmh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2soasdqti.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlhslxy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyzlxdw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2onkljrzk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2iepkbjbq.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2cstlcokl.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjplupl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzkzilv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgpqadg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2udycvbpb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zodgewcj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaatmbb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2otignkgc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2apgfztfg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mclgfyyg.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfmdlse.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2reauvoed.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfibeur.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruucqfhc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xppjlmhb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlkfwpa.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzixsph.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuvitmj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcquytq.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrwxwpo.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucparqyp.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxavvbv.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjccubj.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2figgaeoe.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdlreyy.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbmrkjh.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfhhjgi.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsjjecu.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2guvwgiwq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjepmmv.html


<!-- 参考信息 -->