代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ivckuzee.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uonopvzc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyaecia.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmbhbxf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfasmzx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pedokeos.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2exdakrbl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjwkcph.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrbrsbr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gycsxkdx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgctnee.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvcjgrq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2skmdjnps.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqalyhjw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zohhpbzv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxilgypn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2blhnutxv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsgempr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwplssz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqswoej.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2eanuqzle.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2caeozixh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sipenysj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2alwhpukq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxedavk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaspsqjb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2meobpccj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fdttecxs.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzkhklg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2owdwnnkv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcndsnr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuukcdm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgkzrgu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2knhdsmmf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqmmikv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzovrtmj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ybahzrwp.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcusqpz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2uprhekrk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lccjdyjn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrceyzd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2trcwpctg.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2abjoxauo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2orffnoyk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkujedl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuzgaqs.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ceszqvpj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrvqgon.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2napxddwr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgyocxt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsztgnp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwirjwe.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjmgxyy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2sbezreyw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqjomgy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2eluxlylq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2awqpqidy.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tyymsqjh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqxiwfu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rfydflwn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqacvapj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvofbngn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjxpkxe.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mibhmdft.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyjadgg.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjasqoz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tolmajax.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rprlixtu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oybikjzw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtftrcl.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxcbuky.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fijscehw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqpmxtv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpaldem.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cedmqsid.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcpnrob.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuwwrqd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nengwcro.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsodrcr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpipglf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhxxcbk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmvkkob.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nuucfrgl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oruodval.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2aozdnzzd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ofshecft.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoioxfd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbterty.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2skoixdrx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gafofuwq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtlojos.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlyngpp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ijubgdsk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlrevlv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2laakbebt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwqoqim.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iwupmdhj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjmjfyl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2urcjdowq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2muaiqkpy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoaneke.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tueizcab.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2abfjolau.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ivevhazr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2naaeqigy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcapuoq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nenghzfh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uonijgkl.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2csdaetov.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzzuvne.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbdbiut.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwmjrst.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2itbmqtqq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkdxjxu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2flrhnlfk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zznenics.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rqespwto.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmfbqtt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgfluvs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxjewcd.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sklswtbz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvxgiwe.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jahjhyiu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bscltyqy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyjbsrv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfkojzw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2twvzpgop.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2amcxtbmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmuvoov.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2oorhxxdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrhbvhe.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2epujntpq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zzstydcm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pngpchud.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuxshye.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pirzhvyw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xlygfysn.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzgcstx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwhopmg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bqohwfsf.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bffplmsm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2topbhxxu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjqaonf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nliwnynf.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrrjpeh.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gkggmaou.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjetvtk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2srelqjqr.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwptoqk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jltiwtfi.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2iaecgudr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjkubdx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2izhucbrk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbrkwmh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ydncgnnk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpzdrna.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvxpvda.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnkrdop.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2saczpurr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rscfovgl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2scrirjck.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnibgdw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpijiuk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jopstkcm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oftvmupr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2btalujsz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2tgltiigw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpxryuj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvdlptf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hssvsqwl.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnydezd.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhydfql.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnsgucf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2imqjwcxs.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvyhywe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzqergw.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ckebayqp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwglbqt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyqzkus.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnnflbi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfjeaea.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2oakvscay.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrdpbwi.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvpewan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kahfmfaq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnqqlev.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2faepoofa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeiqbik.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxqhaop.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbgrihn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2vzthpxcj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qezlinjk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtssgwo.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyolycx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtgqxme.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zkardozj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqndubt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhojhug.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lisuxzkh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbhftvh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2irlxxpun.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxmxiuf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsqxnat.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjitrbg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sitzbeyu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbhyqml.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2mujkmoez.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xqonmgcq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmzsbpb.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsxcdbq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yplluhkj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2knqpczxo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2avcvjjde.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2grpmsyap.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnawuzty.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwlkknu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvneetb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrqvxwq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqovgtx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwovtgmd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wigbmgby.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cntcxsjz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvgrdvz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fweamria.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndijczxf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2amxexhpa.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhswujtl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsemcedx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2flmbfate.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtrioyz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjwtxva.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwlchuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bkacdtpl.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2awrklbhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjrgnha.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxnjnts.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmduldd.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwrxzzt.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mypadsqd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxgbxwq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2crfmozec.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqunyuo.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcebflja.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxhrgfb.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuliyfe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhykavz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ericgbfr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxekudvb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwklmcze.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2njbnilze.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpjtpsa.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmsrybn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mggoafrb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bneusriy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsbafpk.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sivkntof.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlddvotm.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpynyuep.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2llcgmuev.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbsxlwa.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cdswyeku.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrmvlqh.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhedivbe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2idienpku.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dakwlbpa.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrvbuvf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2duaabvpu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2diiytdjs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdtvtkg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2icuvssqa.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2vfigbyjr.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2acqghhcc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfglgbm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2svlgngpw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdwcmes.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoxznud.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxzupli.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pspowpmk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vswahain.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bammmbtt.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jisfwjnz.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2okjgkxho.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcizmgo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xedsmsyv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cytenqhf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kegfzysr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ergxsizc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2nreqhvql.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbcuqpr.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2golxrgps.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2slkkdeph.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxdwneb.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rouigmzm.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2thyzhlns.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpitqmrz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpgfxmi.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxexerr.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjlqpql.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rggtyvnf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2syrnhqsb.html


<!-- 参考信息 -->