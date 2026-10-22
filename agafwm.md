代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kctiogfz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2sghfjtnc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnqacql.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdtninv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdnwpaf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfgjxnc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2goivzlfz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qabxtjnu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bjduaelw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bofdtpda.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmnhorl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnhksvp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmmnicr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjiewey.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2usxsuwtv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeziugt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kndbqzuu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkuyuif.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kilusxld.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdksiag.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsdrdhq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyoxvjp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uztizstz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cplpqsye.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2plnpjora.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2urddncfq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2odeqbdrq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2csrwmvqs.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jikauvgt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlxjekk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yedzqifc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2crddgvfl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wariioar.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jshuxacd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lidgmuqr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2irbacbcg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoagntm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2uotpjgis.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2usqefzmn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmfmrfw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zgylolea.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxvkajc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcjtmud.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgogmuje.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gryucpkp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvfrpqc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tmenowqv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2afskfyaj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhzyspp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtjbjpu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2urvjxcmw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2becovmdb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uumgiijs.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2iymeloif.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ualuywkr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqunmdf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtekame.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zgosflwg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ocesapjs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2scbswdmk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbykiwf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxydoxh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuxjoqs.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfgkate.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhkxcrb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvcoyoj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxngbfa.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2naexisfm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyvxrzl.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsyveco.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvvqpun.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxarksjz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hzimpkpf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnuffmm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhnatgg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iujgrizo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uejwhmmk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nbziehwx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtxugak.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvhwmqs.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2aegcyqbd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpetamr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2guxfhobv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldszphfg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2llazvozs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lihlpoyw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2euyjuwuq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hujeauyl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lryxrwgt.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmsumwd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tufapqea.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlamida.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sytrsmbq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2guatayvn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2razybhsh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2iimiesgk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2juiewzxo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmscxah.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lfagnsms.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lnekklpz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlkgtdo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mldjejss.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqwnncu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2amapzjul.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsbxyvv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2psqujhof.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gntbugqd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbchuqw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ribjxjda.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdcvkmr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kuojaiyk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfinjwa.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2alljxnml.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjangck.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbjvrwb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wumvtgzl.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtzzltc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aootjhte.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoekvqs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jajtetms.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqispvl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiyvvrb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfumrtj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoeizat.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzebrfg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vfewzjrs.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2znytuogr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcukhaf.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnewkqp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlozvmx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqmnhjv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jowylggt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srewlwki.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vtflvxpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxhcusn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoingqt.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vplwvqtr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcyxikr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbrbput.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgrjxil.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gtclxhrp.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zgitdist.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2luxmpbun.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbzcvuy.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoxeuqy.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgddegv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fcubvpdj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2flbmrcyx.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxldkwm.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2taqcdskj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuztwgs.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jisdppcc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoikvgc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2grfheclb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2breitcih.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnxpbsu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqsktzk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fahhzzql.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zixmrsgh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwkcchl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkxqovt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvcqriu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qtblnode.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2aslaijkp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpzocmy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsbcdjl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxtwuov.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvoqrfv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlityef.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmvfamf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2isinlyie.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqwojmp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaanvlh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2yqseddfh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmnkrqs.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2eerkvvec.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ebszxtnn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzezmlm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sccynvhn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrpdbkz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlzjzrs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hffspgsl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpntsha.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xigpdhgn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmpiezj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xniimdih.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2cckwffqq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwlzhsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqrbeyc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoaulgl.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vczrryrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjxwiue.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwfsafd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2auydzszl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2iexyjrij.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtqukpd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlzgkke.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2yknmwsqp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdamslz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2coxkhpht.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2slvujxwc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2efibqsaw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqyeies.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpvwwwu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2utglmont.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnzehnw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2zoslqvac.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2upqgehpa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pwicgcsx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuegscm.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcavxrb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsfnsjq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fackcovw.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpdhgfz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeyldds.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yepqlocw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2psdzrwnc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuxcslw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlspxosg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bckeunru.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrxglzt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuaaesp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrfasni.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlleiakf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnwfwir.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyeylaf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdykvnz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rranpeyv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnrttmy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2itxtlqkq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyirond.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzeqjct.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2opulilny.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzzgeew.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkizcqgs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxidwsuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lswwfysf.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrexilj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clchlpuq.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iukpwyta.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2iodpadpy.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2njarfnpp.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2otihgtkb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyllbbzm.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2flhsyruz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2plxzrlma.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fencttge.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ukeqyvpv.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2auqakchd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2orhzgywo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbaoxzr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxehxhq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nywshlnx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzumcok.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2btatrext.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2unwezgzh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqtxhds.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2julbqmvo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrmfifg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvfntef.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2valbqvlp.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2svirdqjt.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpgbbpz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2phjomoto.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkdcwut.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zejgipka.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrjhdtn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2syoshqdv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxzpgxf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzpfhht.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2odydegqs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrhrxsk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhcvekm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrbjnjj.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvhhpvp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhhhpwi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsefmse.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xadsoziy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2clwquiuw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zstwxuvk.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uigbitcg.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzohcey.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eeorlgdc.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbwbgts.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nzffrgim.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2txmdydtk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpksgtk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzszydbq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nplparpv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2imzfwsdt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwxqeai.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgzfyfq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwsujxi.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2givrmaev.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgwataa.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlevuoeb.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vupdnuqc.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgqffdu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxymawil.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlipsszv.html


<!-- 参考信息 -->