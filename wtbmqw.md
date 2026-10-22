代发 wailian999

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2azhuyrnz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwkwzhc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpbvone.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmtkidm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtyhtsr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmiwtgf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhqdjro.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqwanux.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzgprxw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2atjvdnvw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwshxio.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwdarri.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvuosva.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2whinoavv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ljovmkyb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyqhywj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ehonuzgm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhvdqtj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kcerqnbf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2sborzxfv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2igolhfde.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqtxiop.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mltnmsaj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2okitouzf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dwokxreu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtalqkw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wizafzdp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqcfntb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lvufghyc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbiqloh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oayhobbw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpfqphr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmltbyn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mulgmnmn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmhvjto.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzkwwvl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbndtcu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxeuacl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbgppos.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlsrgkp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvfgiud.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhxpqod.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2smjvafxc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlhpcng.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wueawhhj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2goyphprz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nraiqfgy.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wajxdqnx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wuaeqjar.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2sekfpmby.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxlkvdy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrnltom.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuvfasu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ljopwumr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrwrvat.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfukclcp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2juqoyieu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzllsyx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2anqsdyir.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaffsjzb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wavycwyv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wunvpmop.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuzkvqy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wscqjheg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2qoncliyh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjhxdhw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2whoiwosp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcisaqmr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbfspyh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2arbmyonb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpqayoo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkycdmh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2oyevjwvp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyplrtd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tekwsmsy.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoypgfz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jblhapwg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lywkhivn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqobxag.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrquxmi.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ndikrkgk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyvyysw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fiezceag.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ktagduyp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxatrxh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmgizxz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrowbmo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2udjlcdvt.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqbbdev.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2caydgrrn.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kztyqtsj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2frwwxjxr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gixmwgpu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tncbunog.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiqrfeg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uilhglzi.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cejovrbq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2irlkfniy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxdbjbk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwcxfcv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2csienhnu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdtndne.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjsbcwl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulormfxs.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2owurnqmp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iilwgnhh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkjqklh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bahzaufu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vzprnoax.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuietfa.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kvirflix.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpjqkfa.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2stoiksmu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrvpdtt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfniabfb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmhzhbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrigebtb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzplsih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kasbhjqn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2opshbock.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2njxgdone.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfiqjqh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqoolzu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aszxztxo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nagoaahd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzstlsp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2frjhxxvj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2buxabnwt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mntbkvyp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzhweet.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qubbagao.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrwikhe.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgjfrpb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqsupsj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iuynmdvl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dornzjpx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oypxfymu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2emxflkqj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaxfcfq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxoxaie.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfaryyt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsahytg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sussfuoz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hpksieiu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqokzlj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqpngqm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmlvfnw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2iyggpsdw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqijtwa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvjouol.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2inxiopdx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vezfslff.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbxoufo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2htoxqyta.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdrkbsu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jzufuhih.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2eohbkgdi.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2bycxmure.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dtigcsjm.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfniloe.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2orqsreox.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2miuopxrn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmothhl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2luwcmndh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhjwtbo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nluyodfm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqockyz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxdpxmb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmslvji.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2smhwcanh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwvujck.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2oytcuqfj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taeajdem.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2racgbshc.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2takuonew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kubhxtfv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2onmrsrzv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwiyahj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmjfiqe.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ppehvoje.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2iecisczn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ieftewhe.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ardqikgs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qsehwccx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiqhqrx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzgeklr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqcuvts.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2mvljymey.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2arvkaqqu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2btybakvy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2boljawit.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrztbsc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xeabctjt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gavvoygr.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgyuvlq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyzbpfo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2idlzvzub.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuxzevr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ybljbwdi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbcidtq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2otjmesxa.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyolxwv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2neevelab.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrpgwdj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnnrdgv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xajtkdmw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfgvieo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gowdnokr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmucxpz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiurlrf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuujejdb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlbearm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2btmzfjoc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tobofpwg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtfhioa.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbtfhww.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzatgxf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrilrnc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmlrmfr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gthmkspb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrkfmdf.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzmrmgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsseyegf.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2elzhrbcr.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzbtgru.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsuqsls.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzoprqe.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwfhmly.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2afibjfhe.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpwyusp.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2feijvnrr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvojowd.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvlhdxg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjiimtn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsdfsqv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfteqmjs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubambsfs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkumfjwo.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsgwfll.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcdovaq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtktmmyf.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wquzpdjo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fqilxnzj.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2efvusjct.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2husbxauy.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iorzjwpa.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjnwrav.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2esrubmyi.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2oklpnahv.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lewqocqc.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yihnkyqi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2viwtkvir.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwkvfdq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nucreoub.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2swqzmpws.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2jietxlih.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhizqofo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2siimgesi.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ldljolkz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzamzrm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2svrjjujl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdjfsps.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtoiqyq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxsltud.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwhyvoh.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ebamguda.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuwelmh.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbqemdd.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2chqnpmcj.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpunbukh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjoatgb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvoqofg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yarnmhta.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbielqu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjbqyyx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2mvplkycl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqopvyde.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2liymcexs.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfbcyme.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qktpguxy.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjajqwyd.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhryqkm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjfgtke.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzpjytr.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxwjpto.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaufeek.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwaapag.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qckhqobl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2admjiyyk.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqychtpk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyhonhe.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bznsmwod.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjatdhgr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2qckytdtx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrtwiiw.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxkfyhs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqbajbj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oghvgeqe.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbklglot.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmjojqx.html


<!-- 参考信息 -->