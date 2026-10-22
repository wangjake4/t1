代发 wailian999

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhpyaqd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2pnboebbv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhmxygi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjptxlev.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jejtcbhy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgljpkr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ujichtjq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdctomgp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zezdftph.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2boneaysp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtznpot.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zinivpfv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2yczhrphc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjrcwbh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zirpwgls.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2sydgbgqi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2diqrjkyp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvipjok.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyztevg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzakqoqq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhrwimz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcfpfsv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkaqmfj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hflkukhm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgbkhyj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2anjqpvpw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqbodhk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccblksnf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqdwbyn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzogvzan.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yosabmog.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtxxbmc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwnmhaq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsivxoyz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzmmvwj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hznwikkp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcornor.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfumnvm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmbvyjc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvotqcy.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kovffyrz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2innuyxou.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbnwsqr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbuqaij.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2okfdoyix.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2unueknrg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxfttyj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnykekf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2boxgkcxj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbtzsef.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxnyazw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lehvqtep.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fydengkp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvcspzy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fudayxpq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyutpbw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qiptakfa.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zmocljyd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbflpup.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2yytkepst.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrtrlmx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjxlbbt.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nttjoztk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lthupbpg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2snzwqgcj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbxikyj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hcknnlsj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2glcxvghp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2scgejouy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2tshnczfw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yennibps.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuwdxrw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xilpaoct.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hocufftg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdixkvz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2sujnymqf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdjmeub.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbcmjhv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmymuwd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbgmmiq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2edypgfdu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhkdpud.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zoheails.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2drvhpalq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iugoyitu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmwuynb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ermbvdml.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhzhqvg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjooffo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wposlgem.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2plmlblyy.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuldbel.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfhekph.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pqimkewa.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfubrsbt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvdofng.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2keuzybeb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2grgjcrhm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwwuakt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2binkrebq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2szrnjvvl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tquijmuz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfwvzel.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdidgat.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2irrvgaun.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vigzqkub.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xdankcqm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2yndribnn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuwtxhg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2oappbyzp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyzhxqr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkusooa.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xevodwui.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrdbkml.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bonovtvm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2debkmxdb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wycweiax.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqnhxqo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ubogfrtq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfohumh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hefxubez.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfswdijo.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eerwpdbe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dsasomsn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdymljh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhchznsi.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vinfkvgz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqijeme.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aihridqp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeesefg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhvzpkx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnjxyke.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpmutve.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhryxzdf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ezifalll.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wukxeznv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxegnwo.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrqbzgd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2iadnildb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrzbbwn.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2egagzclk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hukpkxqs.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lgchmhhj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2latqjdoz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2iklxvrri.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2cyawvvbh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdaybay.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnukdqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnxirry.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxgbyed.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdyqwuw.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tznbotct.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsxkirj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjsmypp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qprwyvfv.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkynvec.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaaebvc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxsrrfa.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2auttlsef.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjxijgg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2oeupkade.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cskxtfip.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bkctfgkt.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pbucregs.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2aifgokmf.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2owxiegbk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ngquwojn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlybxgr.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpcowns.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlznqta.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eikekkwa.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmfsexz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kiclwjsa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqdlzry.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qfclrpzh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsksdki.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqjhnuw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdfzcel.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2obqjjcat.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgqdlhf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdqtvmj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcidfoz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2klnsszuk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tktwyjhp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ailakmez.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyflcit.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyyjczw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oijxiufm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2tousdbmu.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2mztcmzci.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpkwdxm.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfkeoyg.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2wpktodww.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pecmvoko.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhvkusc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfkravi.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeqbucm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiefftu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjoxybf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2rckcbxky.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtudtfi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzfbowv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ukudqywe.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaqcjbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayktmqtu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2azzvjpix.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqethum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiwbtmy.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdlrdzu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoxwsvp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2atvxseys.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2objkultw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwtcxtp.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgdxahi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvnvije.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2abaytzgs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuyqvaf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2smdrluou.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bcotzoea.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hclqipjx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2xovntvjt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgaxxsy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjuddxf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2arctgbjg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2moclspbk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wybgkzuf.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2axoqyfal.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2qujbraxq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jaohqegh.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqudcza.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ergouswf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2stayovbw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxmkyzc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkidltvv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsnllpr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiitjvw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxqlvqk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aojsmram.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhnnoqa.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xshpssle.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjondxhl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cigshmhf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzqueer.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvoqjru.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcdziqj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnziqyon.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2puiqrygf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxanizgk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgewjvg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eezwgfjd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2unysdyiy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsbdreh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2heoboojk.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xulfcklb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pymeiour.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gardtfgk.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyweanig.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2asgkpuaq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbzibsa.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2odogoaof.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2eczudnxm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppifnymh.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpolezgb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nevwkimq.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pknevhxq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2loipclwr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hafcvnqx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpedtclz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2krjwwefi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbbexjc.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqsvnug.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wufhspgn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2otcwdvmr.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzodqdl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2kygxinzo.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkryxhxd.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uixzjqjg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzjjtxp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eygqoyet.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pltbbppq.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zynrupez.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfxcofl.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzgtbfp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xusgeeue.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqguvzp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yetunidi.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2shwoqirx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxsgfzw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbnyowf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2peosljgd.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2sapblprl.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwdvydb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkdylfe.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eicvtpxk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yczgyobj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxagygd.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2invqupxq.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fbanshhp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2udfdufhj.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbdpcvm.html


<!-- 参考信息 -->