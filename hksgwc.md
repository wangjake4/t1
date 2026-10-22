代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pawhefir.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqqwntr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2csstldrn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2szbucufe.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2orgrcoqa.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkcxbcj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnrbwtv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaxencn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2acwsyvto.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsjbrey.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyqyxkr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xevfoivu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdmkgfe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzrwyur.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rkteutrq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2slmrnxwj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbvjakq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2iauggwvz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xekqlzbw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkqwyna.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2opzchspn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sypxyqap.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtpyele.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibimxbwu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2agifwxmg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgnipdx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpulsdh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xleohoir.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpusxjd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2thcbfzls.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2veusepew.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpsjxta.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeyixqh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtutrbha.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nlanyxmu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ggggeife.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiffivu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpvfwid.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2diyousae.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyotopz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2aewryjqk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2yifkcdoy.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfajjfo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gglpcbgx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpzufwo.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2itmkehft.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtrgkov.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tslrayll.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2popjbyzg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2yymxkszs.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2damprprn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zfifpxln.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtuddaa.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzirnnb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2quihtznw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpcvkmd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2olimxtnx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvjwdvp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfjohbl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bencntpy.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzphzzu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlohrnq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aieriytt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2giglgdqm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2flctsaio.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzxaewe.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvvpmrm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfhluvc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzuxxqg.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rdifzufx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtpdohv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwacgwo.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfxdwco.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpxynna.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2epnuuqdd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnhxexy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2czfwqlty.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hibivpui.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpaxcze.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsdiydo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsjpnen.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbobilg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlsabjn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exqgeqqx.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jklpnjhk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2efpgpvrt.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2naxbienr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qqepthki.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwlxnbw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkxgykx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nzngbqpy.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwcqjbg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdqulko.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2omfodzxx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtitqct.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrqyotb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2dkudoiab.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixueopbb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pdleofsi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qgheroot.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiuhefq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kupgwnae.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrmgkxp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvbycxc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2esdcqbxg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2phkabysj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2exsoetbl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fisorbjk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yijazdnf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzniwgg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgmowha.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fzycifof.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wojmbbek.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaztfte.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2opmaqsug.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fswnzqyx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdbzuny.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2czabsbkb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhbimfh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2edjxlsga.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2beqhqico.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbltqtsk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rabntyub.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2seluqlue.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjohnbu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2miyrjmlt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2noukutzt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzxmoaf.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vutrskhe.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlrxxug.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzshboeq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mecgsnbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcagetli.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wdozzzeq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hujwlfxa.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2isgqtzge.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkkcsev.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2knlfzbcl.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ehojfbty.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vewjlfno.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vohjjucj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqwfjih.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsvqxcp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dpakelpv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxpfumz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjxazwl.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qywwafjt.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rntrzqiy.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pwltncqr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrggzoz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyibhgj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zozxpsov.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2azoolyhg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oapdsvdz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrodhpu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wejlfrmu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvrjklq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgasgxo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjcyvmz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tkokkomh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjfkrtq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkigjal.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hacboapm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyzcalv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hjunhkoo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyamvan.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsgmypr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlykyqs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dimasdoz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kknucnui.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2aezmpzcu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2viokbnfd.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgnxdbe.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2mastdaeo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfkegip.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuxslqx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzqojbe.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rodvjqot.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zrytwmiu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2extywllh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2phbqvono.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbrzsfd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpjlpuc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwakqdy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2axstjuxy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2usiobqcu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2sukgceyh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2dptxtvay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ampugznq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2llzczsdt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgknxpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdmruxa.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2umtidlby.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyaaspo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvzbjse.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dictdrsj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuaygkr.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2myyokszt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tkquufyx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxudfcz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2tearmhqs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qabhbgre.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2trfyqtls.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2twrefwyc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdusnmn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2nezwcmwp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ihihwdjz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2banmaqwf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvhxosb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2itcopffz.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2noidcdyy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2erujfvnl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2klydnody.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2sprvuncy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2utrpxnyo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxfxvlg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeyybnw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgizybjw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjquypw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnkyttu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsofqwwc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sseetilr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwlcixg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dabvufbs.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsybhfu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2icgapjiu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcxowvx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwlllzy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbzmpfz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nscnisam.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vljqrakv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnkwhwf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoijhyte.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpndmkd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jeolwtjh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwuzkba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdbwxbi.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bngofaec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqbgasb.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nwntalyg.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgelvdfd.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwayrjn.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2treucukj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgadmal.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2daprwyvf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxergxbw.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wukbmyii.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyggmrs.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzelqyat.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2umcaazbe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mazeqniu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvuqzet.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbreqygn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmxpgwf.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jskbeebe.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2adtznniv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtgrfkw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2erebdkle.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrdazei.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fayxyryg.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxjetgz.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxlvcfv.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjhfdhj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fluhfbrs.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nuogkhog.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjcosee.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdksnyx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkobkicq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nothezin.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpchgxd.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqjfupb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ynythegd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2kamakstg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2txhmjdzx.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2miqugjzw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2omphngmq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yollryeb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwycwvd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xfecinyg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zoobbazt.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uenzqqro.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2czfggxpb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfmmnpu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkkwehv.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lotucgro.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdjngyo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpjerna.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjukwvj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmnmmqk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqqawup.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwfhtat.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2lvggvegk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzxrruw.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2btvecaud.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2blczthrv.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jixdxoqd.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyurtvj.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbatbgz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuztpjw.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqtpktw.html


<!-- 参考信息 -->