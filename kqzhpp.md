代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeevjtj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhtpcmy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kzynyxqt.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrttwmjx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rmosddij.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnmatlu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nefouezn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxwsowa.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ectgjigt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uffanovw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqqjlmp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqaumtw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlienah.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ricewndz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uecfkmta.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfececx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdjzruu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2heekszmj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lcolatsp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbhxvcw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2znokryrq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2aorbcmmc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ipahvbfx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2glwxhrgx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnubimu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2omccqhfb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvtjomt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwrycoh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2auwzmxcb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvjpcnj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zylsddur.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2oveeysza.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnpuqtu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyojegp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcdnoes.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwugzuy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcoantk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fchvhsck.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2djcyfoxx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2irxlbtni.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zahmqgvj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrlhxlf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jgovfhzs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwdyfhp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmkcgok.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyczcva.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdczofm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkioqhhb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vefrtuhn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2kanjkrdp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxxnsft.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pebdflls.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2evcbwfrx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ncljgles.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2masowqoy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuvcyax.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfmydce.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mydffvdi.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjahpkf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzggpef.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvdymxi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmwmhgv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qddtbkfp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pglwszvt.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmmxswc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tupuljxb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2amfcpwss.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeehqef.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ccumqlib.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rscdzrux.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kochkwup.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ainikkhc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vdclciok.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wqagrfki.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyixzfv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnsxqcu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvuwlep.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjqkpzy.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mcspraby.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cneqlslu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjmbejr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyoldvk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnizglz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaanrqqo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwgpjeo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjlvued.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kgedompg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfitnul.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zlexdetv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iharypyf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvsjuqn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ndimeilq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gayxlndl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrafhci.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iauzsyiq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkhqzgj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqzgfwe.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvucopuu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvwgllv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqifdavi.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuuauww.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcbgkir.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ceaaktpx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pdndlimb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmmnwhk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aarvhwjj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyvihuh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mylagbzl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2eseiekvn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvzsgzw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2azuzmctm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zsukixlg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqqwcpm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaevulam.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwsixph.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlkhoqu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oaehyxpk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeqtodv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2udjfsdrm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjswccr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwievmb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxjdrvw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vecspyjv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbeslnj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2aiokjdjz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2emyzzeac.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyizflvi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjplacnn.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyeedkt.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbcojwh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2eskkohzx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfaotwm.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gidzsjxp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2litkmzit.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbjhhrm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqcibij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nepfjczx.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmfzvcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2piunrvco.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2yopvmvin.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jddljwhu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qnahldgy.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aahndapn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ytytkosh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2caaqtnko.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lryhmpkr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cebiznsw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xduqqcls.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ivelynyf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkrpoxm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjukvwf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xaolzlzt.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2weyrloam.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2beyfoyff.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2aladrojz.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtxjuxb.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyuyrwu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfudhdn.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkdjidx.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2msuzfcwd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pabwfqkv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmulrcs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkytaqt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gozyqzjf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzuplbs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtpzgnb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyfifpv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtuppts.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbzwpxf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2drspozyl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dibsayvk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fittnbnv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rlztaxra.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uojejfvn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbfeqwt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2alenddmj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbtzyav.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2aelswbsp.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jchukjbe.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2weordvwc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxgjvbo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fybqlfbq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2utozqfcy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pimxmsgm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2racrutel.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmpspgy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2locviysk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2drzfedxh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsvvzvk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdqwfmc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2aeywyzxb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuqiaif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnxnrir.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmhltce.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnhgaog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btzbxenh.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hemcxxsy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2tknhllwe.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkncuux.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2izvnecas.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbmllul.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzwtaux.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tswjphli.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2coupqnfl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrlqvuw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbqdple.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfhjpyu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2pedmguwv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsgnuiu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2sztldous.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhvppht.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcvcuyb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rglgwkqp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkspgdz.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2buwzrmpt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtmwqaj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bbynbwyn.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2juwfiuys.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uwulpvtd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbcujpy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmjlati.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgxirrq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2alwwvjmf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2erayifah.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxitkghn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbruxazg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2voxdrdyp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jruiiprz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqxjqam.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2marigyki.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpkcmul.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sckorcnn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2domsrxcl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cujeygvd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2augfjurw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxgazgk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2riupynca.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoftsije.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bupqoejr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxclfvsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hliptycy.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2puatwbth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwnmjhl.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2krpqsqxu.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2apphonwb.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuxvhrh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnvlfhq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwulohl.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxitamz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpqozsp.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxazjylt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpweqqa.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgscgfy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2shrnmugj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xazujbli.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqxdjpy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2atipbgvb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2otwfopuf.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yrolfnxg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2svqkhcam.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylneehgk.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2irxmgvst.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2aifmgkex.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wblsuptf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzlgbqw.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2csmrybzn.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnspfdwo.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuvogdo.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lprgjpnq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlsqnno.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hibnnfwk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhncyuom.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojckcexo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmeybgo.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrwjrda.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2thxgvtlv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2okzjjyem.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoxtvjz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2jxruuxof.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcwtghy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2txpbuobd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrdxcnu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbgjlhj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvtvpqf.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdxddyb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zkolzuly.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lckntczf.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvuqina.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsyeglt.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ablousry.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2adlsebhe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvaazws.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mboumxxd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuegfjzr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jobsqjpn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiqatvp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlhknqk.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2khiiyxhx.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsdwopo.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2frhlyrpf.html


<!-- 参考信息 -->