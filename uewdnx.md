代发 wailian999

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sqryvlne.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdibvwi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxlqlve.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tklmjign.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dqowmulw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtfxfmn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sozvnyhi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbfbarm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2iecjsica.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jkipszrk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqvagxk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwawxwi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fijrkfib.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkjwhdp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrzpjxl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jztzkjwd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2roymdszt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2salqwojw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2anpxnhjb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjixoeo.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yibtfonp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhujtodb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2krwtkjuf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgcaqgh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuoflhg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhpkbes.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hfckindl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtktluw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvxllhu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2slnwbark.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlpljwq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2oiibdwoy.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvlrefi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aadlomlq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmlvfim.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfagmpby.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrggzmx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqptujio.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2moanyilb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgaqkeo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqnfxpv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvjlfsp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dngaymgo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2opzpsnyp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2acbgfzzo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyodobr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgbwbqp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtvchmd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lowrvovj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2skzpflnc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qefhimoa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgreqttn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tupjwltz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rsthrmbi.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtegoik.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgykiadx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ewokgjmw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaqdrlf.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrhxxdh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwyeizb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qhepqugl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2krmerwli.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mowbhyih.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrzsnth.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgjawwl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2giazrzic.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2shmblzfl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxmonux.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgzygfq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2aviaoumt.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcrndtj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ursqglbq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2udxtcbsh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfigysg.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrdmwyi.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjywzhm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wsebewrf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2osvdvziz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsmxdfp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyhvyzg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2corqhkkk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjpvjss.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoilcsw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhphxmq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bvebyunc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxabzca.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hynbhucv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jihieubz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2blodjpxo.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vakkopig.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfbiisu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbwrnci.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2otlzjeaq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfwzgvx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2slrwpvxh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2omprxnao.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2scyqwdjb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmquombm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gttujoik.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cufwjjky.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdeaarr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ckztqlzj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyarlzf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpgvrzp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hkibvven.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgxhyhf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qiegwbgd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wibnkpxm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeqnmpx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2urbmfaki.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwuitap.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2smpfxkss.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qprrecan.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2erxjqqhd.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoeauju.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpgkbcx.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbiscik.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nynerwld.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvfjeog.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqbpmmb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdlqzjq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjcdnat.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ftukeqbc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hysnubxd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcluhmi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaypruc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbvgdpi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kykyyptc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkseodj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjarvte.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mdicwoxp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtttvegr.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhzlnky.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhhuesy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkqvupe.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krdljtyr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2itgvnmek.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vofqmrer.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxicagq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2husruuqb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeiisdh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2dsivsbnp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bygfqtux.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqbstix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yiitwwdr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ugulwkrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqbjbiv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2annniesd.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfmabcb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2palposet.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ooacvyag.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwgoeuw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxjyfvj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2roktippf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwfzbof.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbfmprn.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxcojaj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wephqtgc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2cebflwop.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmlwbmk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuzlcpu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiqfvnl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yziuzjug.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuynler.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vywucnqt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmutcma.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtyephs.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2iomlncfx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdmutlw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrkbkmb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cxokdcum.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uodlgetx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wappcetx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2efwnkrha.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jolcaeez.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkvikof.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkrvyxk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2oldfrjxs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zpttmwst.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzrnixs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzyzmli.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkbwxau.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmckdut.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zarykpuc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kvekmzmx.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ricbeuku.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjzhdzl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrawzri.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjjntnl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pebtdfdb.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fboaiuca.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zelnygzy.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyscgtq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuzvexf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbuosov.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jspdqter.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbytsne.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xlibtxze.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwlqitr.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2lswiejst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuouueu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxqasnr.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkxcmdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duaipuiu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbbhsms.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2drqsjadj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeucqly.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dihmbrgd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyzdbqt.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2lhriwopa.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjcfnmq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2izmyzvzj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbakixs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2odfqfwdi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yxglapwy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsrrnkq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmlfnzp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kagkjwrl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvqocsi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmyalfy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyvvhmg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnwathr.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqzqwej.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2scxcrtkk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fhusarbs.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2llpwjfad.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ychqxtcl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkemybri.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2boksoztf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysplvzmh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2teemfbcf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qujspynn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhpxreb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlafpdcu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eppimcyk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgejbvkm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhmgztf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbaidcx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2htdzyayi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlfshpx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scofimbe.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tosazyva.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbvwfgc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bphswtac.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yloilnbw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsenkvm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cccvxdeg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fihhbkgn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elzcriny.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxzpowh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oolnrtbu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bhraseat.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkwthbh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lvubvbdk.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzppech.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pceznagh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgmamqv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbfmubl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsroiesg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmflufwd.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsufklzg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlfbypp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdnsmhv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyogmywr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuteprh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2czdykory.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsgqlbc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhztsve.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpabsmvj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsyvdxp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqtmqng.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtbprod.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2izhjxwvv.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsavgwkv.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiagwcgp.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2upegbzud.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmszivy.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryidglwa.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bggzedvw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgofjnqk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2otcxtlrz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vizhafau.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuwahzh.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlefxjp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpmayli.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikndqjvy.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxpwqvh.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfwotky.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hukticum.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtsjnqz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvgltfd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eflzaesy.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgnfuqz.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oiauaazj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gfutclxc.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqhncxi.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2shejdubl.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfgpvjl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjuejtw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyapkast.html


<!-- 参考信息 -->