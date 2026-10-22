代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oltzpeuk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqucjpxb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjamhjg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsxrxdf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjwkvuz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kydxpfsz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xcplifwx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2caqfzysy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2leblbwmk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnbogar.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yawmzznz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eydqejxv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqhjemf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdcssfc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jecvzlqc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blftuqnq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdwjuxz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdkhycs.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aixwyqww.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwgcnnz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxdntay.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hbftjvwe.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfcmgrq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nigajaob.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2snpsvlyg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2npdlvayt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oaliiuhe.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbujqbk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrxqrjk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugelwcus.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtuxtxt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlctnkw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2otfjngfe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtvjjlh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xitkiria.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2visqzwzd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmbipvg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqaiyek.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbxobig.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tntnhjdm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bltehjye.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkmgvmc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdccihd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiqlveg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2weznyqrr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyrjlqa.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtvluuy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxcfntm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gotunjah.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoizqsc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtjwxhv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qotzrvwe.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2unthnzeb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sndhuspd.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rcimmagf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2uajwjwyz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2psugkpxa.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnhnkhg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mchivsah.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmttrcw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2biievzkt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2trvpbymt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mzafeblx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnriewkv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wvykdwap.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bykdxacc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjjnqrn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hionpazw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdjpkyj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjlghiz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uutqtxqi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiyssmw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2frohgkwn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2adchtune.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrgghoz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dzetmgke.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyxeais.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pivferjs.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2elgbnjtq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlajynyd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ubazmglu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nlejkiva.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zixidfse.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yklttgrq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuukbry.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrzkcyu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlornyp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmzbpse.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ranjtebq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2btvzodyy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jaopgymm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2htuiszhm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sarxudnx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hygkthrq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbhkdki.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmukbfx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjtzudq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hypteesn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgnmmit.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqekluw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mkunzptv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwphouw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjmahfs.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtnvkjh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fltbsnvt.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nakmidui.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmqniyh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujchdgby.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxxnlrb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jsydezsj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwcjyij.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmrzuch.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hfugctpx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuljlky.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvutwhs.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2uimbefsu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wijybzac.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgbzglf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsuedcl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2peqlkksd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xbshvyel.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnrsdbc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jcziebax.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpxeoct.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zhivmugj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bvluxtfb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjyfrrp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2djcfdwen.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2abjousvp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaykemz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqezwza.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsdodpt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iitephlu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhlcskq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nzikatxp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lcohfpcv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtvwalu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwhstmy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjvykbt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndixwwwc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2inzlkloq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyermlqr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pdstfqok.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gawcrrmv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdjkngg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2votkdiys.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nolydwln.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkohlklu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxowfhw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlilfdq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kootvkoc.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzehrjh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2raizjvar.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2wywpevtz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hogdwwcg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbibeua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbafxwxg.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uybfkual.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqkwuab.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gssirexz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvlzdug.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjlmuxr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wanjbiah.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmbbama.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wiviysnk.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvyzgxq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rijcypfq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjjmmfm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2idzywzik.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nmootpoi.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2miabxhqm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2iohxypfu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mulgpweu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkjruxz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qddtlabu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfrbrll.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2faqzsivw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cetqgiuu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2stntdhcr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gttjijyr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bgadvfii.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lovzxbda.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ysusnzwd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jolnjtzm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2smikhrrd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dpizkedy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iftfijnq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tgihxqvs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2izamcbor.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfyqgrx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmdvruj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2evmsgpoy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nilnnpjh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kntpgzxn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtpniwt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwmbqne.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qezyeifj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhpribi.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2stfsolrq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ktalomyz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxeuvtk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvodlhu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dfannbas.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzkuunx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zawrjipb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jybjvlib.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xagvlvcw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdyxmdb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwwftel.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmcrvit.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2noinuslu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwqmlrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txqkcxxy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkaxkcy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkgrjgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcekqmi.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqdtqpw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rccwvwpn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2omurmskm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdimbhh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuhuvnf.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbatwzc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2eviyckcm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlrbkec.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2pjitnkad.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcmlnyv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvoynwl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlehzxa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wgejiyks.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2pogxnnsv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpzdzdi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2mehnxeoh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpsoaex.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjycilb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ykixpaal.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2udrlzsbe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzcifhp.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqihbwt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjkovel.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2guqqoelu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hutcaubg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oizbmzry.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzaqwut.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcspbken.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iewkqrzn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiebudg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2srkofsqi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2elnztijn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ibeoykxf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlnhygp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xujoswxi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjeuoaq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dojflbjv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vktutwnb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcupzya.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvydrru.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ziosnnmz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyerbhjm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpeukpz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgvskiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbodgxc.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2acuzrvap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wopmgusk.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2abukldgq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmosmwab.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhkxpig.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2evffpdhk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkafihh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqvdjhw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxkmxsf.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaukwqk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcveltzk.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2jsidvsod.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcyuyyj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kumkjvgz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qumvzbaz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsksnayt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvnoyfr.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xulkjfik.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbojwnw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2frkbfjhy.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfgmmlt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2yssxbgnk.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlbafel.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbuegae.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiipxbkd.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cefefskp.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2agzddnce.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrchahm.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxhknoz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2agxkzcts.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqjadli.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2prrymrqi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2uhabdiht.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cidhkila.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwdawdt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdoyvrx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpclvgcf.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqlxsua.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzkdxmh.html


<!-- 参考信息 -->