代发 wailian999

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcqikmi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoslzht.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyenaia.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfosytf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cifsygad.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuuyska.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzxiqtm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nigkpaob.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sbppaljh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyotoas.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2acklkgqb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkdchvl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvbtsib.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvgytlk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfeurex.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwobbqgu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2staanmss.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mioaylkd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxjtutd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksixbuna.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzebooo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2avcacxul.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdvnwhu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlbqwtj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dtordnsx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbaqojs.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2saryfjuw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtsdkbd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zktglzzo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzdfoey.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pajtuojx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yswpgufi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2agldnfin.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgiwqvd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvswtzr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdczyqt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzgeltb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkylphpl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jvojltdy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwumivt.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhreemg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2emjnhjog.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmdnuky.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2unmrubkl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmuvrct.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjcdqyy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbatmezm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyicdpx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rclgsnga.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsacqga.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2eldalfrp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcohnqlu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrfquyd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpfndvy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkykdmf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxjhicf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xqahhxxd.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hetjnfnv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tfocvfsa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrzmevk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2capmcxpa.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ajekfzrb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kynruejd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivutqaym.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhjkolu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqtcmne.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2orppwbiz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2quxilxip.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2krfyxxnp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmypjck.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjzygoo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdasslf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnqnmps.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2orctkvvg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjklpmq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jewlnadg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kevmpnse.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2etrkfsca.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwmuhgp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyqqmbm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pdggaylt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkknykc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvraoki.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2afkhhkmo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nboadvzb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2imrvvqrr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpvwlxg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwsjlch.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lphhycjv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2smxvxyqv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvyhvpj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zehiskdu.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2stznefpq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsgbcat.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2czdljbdz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kplpmugp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2escuwbmy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdillye.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkjhvlx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2avpthjya.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbjwfso.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uosxkhof.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2snotgbge.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxnsemf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvkulyt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdisukh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmdbcas.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yeijasxx.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dutlsmqi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2piuxhgqs.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbglcrs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dciyqkhm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2gdolibeb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdkjmmr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzjfixw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zidrpgou.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzpfdtd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxynjpn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtdxxpr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrawssf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jyncmulz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcckzvkl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlknvgv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fglqrxln.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vxilsmgk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcooekt.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbbidzl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfnuxcd.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fvocueat.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrotnmfe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2szvpsxhq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxsyxgy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhogqtn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wojmmkno.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xeffacup.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpkuohh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2acwzojqo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2anpfnrxs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2issrhhjz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ifszzfer.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmzhtwj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2niglmlwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qeavlusr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbhiquh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yjirirbt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfpzsaq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgsojll.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoksfwg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mavgrfuw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdwczpg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2teqwolom.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2evabkvrq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2msiyturn.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qckhatyw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtglokt.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbqkgfb.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpuefeu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmucceg.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyamxcs.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmbikdn.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wktbgzxf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzuwpot.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2chktvchy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbvkffa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbgopbu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkvwvpv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jieqjljo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlsfjvz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2iijuostl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2biwpzjxc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sxygunpq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbvovky.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gwljmapy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpdoiav.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmfgxid.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlgxktw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cvaykvyv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ekavjqiq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2iczizkph.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eordikih.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2txvyyjey.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiwpbwk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hpokszjz.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaenvlu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwckqux.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzxjsmz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uppbivvf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrhgfut.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2fefjrehy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoczqco.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ptybsboy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqoztrq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2yexdbwny.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzgmcck.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xguknzcu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2eaemogwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxugdolv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyroyyyx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2loowwzag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2auudptfp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2joqphgxd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyhusmp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxdwfyc.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzevvsa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2emkijxro.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2oqprtbhx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2kzolbwkl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2awgzfmnf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwghvft.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqchfzt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkqtzol.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ryygtqtv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jargarfb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtrnysa.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpbzvjo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsegcuu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzfdnpj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2isnzrwdh.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2wencnwba.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2aoipudjo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlletow.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2lodedavk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kresqyff.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2smnkestk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jiovvsye.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbbekvr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqrmbsp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajejyufs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxzcjkw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtxvcwv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2baqbrvxb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2idsezyii.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2blgjisre.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2evjwjxba.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2javdchnz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xohmhcol.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoxrlik.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zztjebbh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqjspzl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdnimug.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jeotucap.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2knzdmvrs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtwhruv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvwbrfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtqjeni.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgwwbls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xoizrbis.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzvrcjl.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gexxwufi.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2aecggeaq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvlbzyh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwesczrv.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2eygexyeb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhifkgl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhbfxlh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ieaztsly.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcurcrn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ozevsofa.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2btodjuxm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwhssrt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrhpqzn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2saekkaun.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2myryuszl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxjojiw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oviebntu.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrsvefx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2dtphgvtm.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnealou.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2txsdnhii.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzwonce.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzllquin.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vxemtwrf.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tebepcrj.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vylmutys.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tesdcmyf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wztrwoni.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgonhdmy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2urxiyxhi.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wannyykx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ewicrdsn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgfghhu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxleihgm.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2dythpbdb.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuylxfl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2olakyhne.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuohlnh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgkntfs.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pidwlvhl.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fizmxlnz.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bajjsbfq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcxcdkt.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ersbkwob.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2crzxwpqx.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjtysxw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxmavpx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfgeuqz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmlfrvh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqnvxht.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlcyhrm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2brxquaxs.html


<!-- 参考信息 -->