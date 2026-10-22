代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsawves.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fknysrhq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2lzytbsmq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsidctfj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qhruzksf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwojikk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2guzjmepn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqjaacq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cxccbzgu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbebejxa.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcloppc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lttozoxi.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtdbyxd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fokajzar.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2eypvmjim.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuxzxde.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qvskndee.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2scmhkmgd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xcygcgjb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2srbhidjo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fiejezdz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mokukysl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsxhiuy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmflhbph.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2thwyvjix.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cleggrbt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhgizkn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2pamagohf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uuchdivq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jytcqfym.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzumodct.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwciomth.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2feifkzch.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxfwqib.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyghjta.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wakitrbo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzvwszp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuflpfa.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjkhmvp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qsidooku.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjrjmhe.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiiquns.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sokrajdj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpraqjk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqqjboa.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pooqnpsd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmvcoge.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hunoyrod.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzgjulz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zukfqlcc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dngtllrc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeedzip.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqwjblx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vapmvsic.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxychip.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2oozfvgov.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2losiumtv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqkbahq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vdovtqmh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvmgshr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpxdgxm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2htcuxblr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lucnumor.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bohwnfwz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2moubregg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jzinjywg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtwhprl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2edzheyde.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2brjdhepo.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hidjzqvl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pugoslih.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjawdgez.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzzlfsi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkcisbr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbjwacm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvampbb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjjocib.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqihrrdu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcxfbob.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mraacqtj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fndvmtms.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxwgjrn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2upubdnkk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrgesnl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fohliokg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lalztmfm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwjtzhm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gousisky.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ldragnfd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2sheactdg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2aqymjnhf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxjpuck.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjieadf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wegiapvl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvnpcax.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2erheigqp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfsldad.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbolexzs.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dehrpwju.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtditac.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfxavjw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2omqniqfm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmdujur.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ualkwpgf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkldpib.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpsefwn.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqaxowp.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nacrfmsc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fptnfvxr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mggysyio.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wnymlccu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zizltvkv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjjouco.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgzkevn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mufrqdma.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqclcwuu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fymfuphe.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjhkwtu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlaydhv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2iuaxkyrd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xiodygdw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2aipqinhj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbqlrdm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2iolgonlv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2byhdqrtt.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wenapuhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwizjlex.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvnoryd.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcaoqwv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rjumdxhv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmgpvrr.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzeiqiy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbjceiz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zalpxnhc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhhuwhl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgwidqp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nprjckty.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lulmvdgl.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzwjmxe.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdgzwxz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgjuofz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfibssn.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrmsxjn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdhhsfk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kahskoaa.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqizxhe.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zglphdqm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fztwtwtw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvljpjl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpzpvex.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgonxuv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwuudib.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2eloidcxj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtwnmue.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkecgan.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wobpmgzb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2acsqiicz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfmidue.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnkbyjt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2npajpisq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuctehg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkpdfgv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2pohidvkb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpammjz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ugekaicp.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhbcfca.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgstymy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tdniwxjo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsiymaj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qzknpbpn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zovxevey.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qixlacix.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjvkogu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eyybpasp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbnstim.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2commjjrd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2iybtlmwo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2egedprvy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2asxbrlno.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlmeitg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlvhyoo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2blzvbcqb.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxqxdkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiycsup.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrhqqvb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcaptbg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmhswzk.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2inxkamnx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tklxrpuo.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsbvvrw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2srxtrgyq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlqpcqy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdrtxyt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qsddkxgr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnkihgg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvhmxyl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuwstfs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiwsdvb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdhzgjc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vexniuqp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvybrrs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeumywq.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbiexew.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2uecnfmgk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dalybfqs.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvvgeuj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbybhsa.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnjoyqv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2obohimxv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqnthff.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuqibno.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtejhqpn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkbwaaw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaofvqr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rehcizlb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2itcllvpj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgxhtau.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dphqqgtt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoosqgdj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsuigve.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfxopam.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aneygesd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpddird.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxookqkw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgijhqi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2odpzhall.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvvmodn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tygfzuli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zllksyqi.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2irdoktrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzgjrhg.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oulyybay.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2quohvpdj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2znujykct.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpnmuls.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzfbpfj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tdooqsdm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaujsenb.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qamxgkzn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxbitrr.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoqkksv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvwchjb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfgwzvz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoeoatg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtyqkwq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnycotwj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmhokcx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xxguguph.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezteaxtj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeuurpq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2kroeplsn.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mubkblma.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfrvsfc.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdwvwib.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sknaockw.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkmfrrw.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2axdtuagx.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmppkqm.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwiajwg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfvfhtb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gswfuhvt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnqdtdg.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pcycglib.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2eabxprbr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2aydegbee.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2meoykzyf.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2hoajyawd.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2bviawsnb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rewoodjd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bswrrezm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbedfls.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sopcpbow.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tybjnrgb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdmtydt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fplvbbil.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoozajo.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vahsogft.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxkufhi.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoosjmu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtqveqc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnotwhy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2icwavfjj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkbsodc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnkudur.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfnmqie.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnyeksf.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsqhzgb.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjbpwvx.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvkqeqi.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxciuwi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2plfgszjo.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvzckgk.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ignkpgcc.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwucwsum.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbqeiah.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgynhjvi.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgrgjig.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pktrflcf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdusyqbs.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfqwulx.html


<!-- 参考信息 -->