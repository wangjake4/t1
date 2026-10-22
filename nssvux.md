代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iijtnrmt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pboqziqe.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2avspnmgu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijalbkkn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvdqdgh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrytgikl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gppymyvq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2aacoryic.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hsehrklr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2griliubi.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcdsifp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlqnzxo.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wblktemw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zumdrsam.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hahneory.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpmxhxy.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyoqtpm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxbovcb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkiapsx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cntvjtpf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pbarscgg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoeiuwy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbkhzto.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrjolgf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2memsidlb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjowqxi.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkbltee.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2irwnvcxf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2apmdzlxy.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyvjdyb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdoxfqk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcnlitc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzttukk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvlczgk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dgazooyt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwxwabh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2yragbwim.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmtqjom.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zxulbqlu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhncdtp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uasclvbo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2byhbbtib.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkozwqg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cjseehcs.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2amekkynb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qotnswyq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrdvohb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxclujm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kpevsxbm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoofzgo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2twfpanox.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilidbqcd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ejikeanh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fptvsssg.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2junuoeec.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbywqxv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2avetirdn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vslvomzj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lcssnldv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqmxfgx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwvonnu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2onnnohzs.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uchnpbut.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uemlxmkp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lazofdxa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrussin.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2auqzivzl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2igwfglyf.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zkubsdel.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jcveuqja.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwegkbys.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2orkljbnb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnqhyfn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2euyqwsio.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yzobrwnw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvadgxfb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfgygla.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqebjie.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2topswzah.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgiutbn.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hiugynxi.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbpsiln.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjsszgk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvxqpbh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ubimlfog.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuchtze.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yreqkfbk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2awvbfgwm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyyzaor.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsksejtl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvwqagp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2izejmbge.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wswjdlri.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuhwdpp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pflggqrx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2epozzbkw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qshcvlfs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2coooowas.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqpgwyj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxzvrvc.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnzfovc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaywjdwp.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2goncbujg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjtagtx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wiexmivx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyxrlrg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpevwql.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkiyxnc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxeqmuz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhrnpti.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tugesvft.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bumzofue.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hitdllfn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mizrzrca.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2fijfqkph.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upcviimc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsohuke.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2oicaqyob.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xmernvog.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwjjiod.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2scxqvlbk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiicjtp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqdbgrh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2noygppxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llewuisa.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxtyijq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vopzjlpf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rnquvwca.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gzerinsd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxusmml.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbosglm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oovsvohb.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrggduk.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uowvcyyu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrjgxcv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqgglef.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sphymvvo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyjgjyx.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwwmnzu.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvhpgcr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dehfolkm.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2phvokpsb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgctphe.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jnujmbyq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2agmbohdg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2atzrkdzh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2anbnctea.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrfwyxn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nsssmsbf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nwujjzsv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbpfpoa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqaezhl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrevpsa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zjflqxbq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ieihcbrn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tlytfvim.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnawjbv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqmrevz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqoepir.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hspmikym.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxouwst.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dalfvbch.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfuwlee.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxtpsmb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2felgjjtm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrjokex.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2otifjoch.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpdgrfr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2joocizxk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdiquik.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2adcoxjjg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwrymle.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lgepgibv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oezcrcwm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcsbdwe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcjhdve.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ttysbqel.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2hgastqnk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wzelhhsq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2skbxrqrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znjfvcso.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkidnyo.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsrjtoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdeifaz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgluoej.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzwgbzx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2bnevelgu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyibsyx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyacdha.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2eegocufc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbinmqv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2aynodvfr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2pkteroek.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbucrzw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pefmgunb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcxisiz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlpsvdp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2zagyvvrg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2oukgcyqp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzawhcn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkaypve.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ewscvkcn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2raktvige.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqaifcm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2frqhozsf.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgdomcn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmgawnq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xffgpquw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2houqtzxb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kczwxfjk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2npsfftkp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuqebiw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2msemooct.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qaepggfq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yadgflor.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpklvyri.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfalxgv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlvfjep.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2romzyodu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzugzxzx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtmrwgf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhjwsdz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwfwzyj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vitzyoev.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2girkobxv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuldzjl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ennauzeo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtvtcwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpfyqqa.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2esiawims.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iihusjcm.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfunuqf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2umtfblum.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2aydlnhzp.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhusqcv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhshlkiv.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2psxzotkj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuenfdy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sydbnebf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2epzjagfu.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhomodx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2epvtjxhr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzzptuy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2edtobgxo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiwdvam.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iocchrwp.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwaxsxc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ixexggnx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zddlmrcc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tezkmyek.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyoupjf.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcqaajg.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uosnniqi.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvwdzsw.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhgtbdz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2avzxspet.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2sumsqvvo.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2goptjxqq.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsyothh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mldedztc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubigdaer.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2sohroxab.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2guimtbcm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2qeftfnyy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2wevbyuoe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwnsgrh.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2rqimovhe.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtuiphp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vnswsxjk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhkfntn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vuueaecs.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2owqbaabg.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpzzjjf.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlalgif.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ajinsnrs.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgqijqa.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnswiji.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2scyyoxpc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnjizla.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxanvetf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jozkyheu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsrfltd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hscjoxzz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfxpguo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2djfxfsqe.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qugcaire.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdpxqrh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukemmxpc.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqykepok.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftunpdap.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkelrehm.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqmdtfh.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtvmofo.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfkwfld.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2euvkfckr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjjrewk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sedengji.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vupfujdm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2padwrqjj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2efqqaqkg.html


<!-- 参考信息 -->