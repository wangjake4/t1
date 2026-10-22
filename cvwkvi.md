代发 wailian999

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdylmdb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffynzqpz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2skgjlhga.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdrzzrm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vnavvmbo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbxgubb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwgnhbt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvrfqma.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2amvfoung.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjmqlgu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tttspkkf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjhesnu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxufzvr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zddlmgss.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xenxoihw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwsgouy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fbopklom.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uizpaskt.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnfnarl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnokfxl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kptwzora.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvzocwu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwyxcsi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhoxiyl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrprmrc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dodqdzel.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzygovq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2skvinzxe.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wdggfrfz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2yadamoup.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwhbbtf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoejqij.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2drhckgso.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hijhqxfp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvpemnc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgsshhk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaaqkqu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwapyey.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bipxopvo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmorpzg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2moypgssv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbumisz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzklils.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcsovvd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrzenpj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmwvjms.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2czyptdwe.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlakewn.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xaasveom.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgoceno.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wukiirqd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2msvjmzfu.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dslevqre.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjafhdib.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vpadhcec.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfolewp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtaasui.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaltuun.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jigsbqrw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipckxdnb.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mfezfsqe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ywagenqn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2enbjmyhy.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvawzado.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cylwpynz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaqldob.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smpommao.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwdzygr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqyebxd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjzrorr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpivfov.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrockra.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2diasafvm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlboadr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtddmlu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxnkabp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2newvabvi.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnmxcoq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdifykk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2higdaybz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfaxmhk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuodrui.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcdljtc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2odqaswfa.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsqdnoc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfxpugw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmaseyr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uujwjkau.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmfyebb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qsptbfkm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtocush.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgzooor.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nryqqotm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqujdgyb.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yezoaexk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2txsgnvex.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2auayohgs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmhudvp.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbkfwdq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kawpeszp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2frltmswu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbesjmec.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mswahlct.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsddndg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2eagpppgr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mriuugfn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvkrisq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxokjhi.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2izfetzan.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuktlwsl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgyyhvv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgcxkal.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dvizijom.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyctvmi.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wfreiigj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2awleactk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmkulta.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkechzl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfbkwur.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwecakd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuazuiq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2feavklzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkuafus.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2uftdbxqj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmproxd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ahanhbku.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2moqrrchd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dxorgpxc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2svnyrdik.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfdqpsl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqsncqq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhfvtlr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nlksogxp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ktabdjoq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kodeulps.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ysduiikl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xgylrpcn.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvddwio.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmbxkou.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtaeptk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rdznoosr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmhkjvj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhrambn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ckybubpf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdluafm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rujnodxr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zavttakh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkedshw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhogxjf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2munmaydh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvodkiq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpqbbny.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jlufeoch.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dswnaodb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zbauuaqw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2byacnhdq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgdlomx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhlttws.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2sisbnrhg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwwdcry.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2mynhmpyq.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2wophmsum.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjxkqgo.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdshvvs.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjogsoc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aslouyvv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvvgdnm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2szoifggz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkgxoxf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvzflql.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sdccixiy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2sdawqosa.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tklernwx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvfrcfg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdqfvmo.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2slspfzpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhltcnv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbjrjdv.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2prrkcpvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vutoxpog.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2igkayaeh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtekwkz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoqtonh.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2boufijst.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2baamiagj.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2bgekqztl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ehulswqa.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsgjrku.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjzrncc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnkuvuj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2twyydokm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqamwwa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ktviwyyq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2snihyqqk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbwzagg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2oslufzwt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpdxudj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mastnjhb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkwjdwp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzkgyjo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dckygdxy.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2eaifojue.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tffdiwej.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2foneievp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcjjzci.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2obqinevp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vybkzktp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqjxsdm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2shvqsbja.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbajwive.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eicceyoy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsufopj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2adaendjc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxaanlj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaolhdw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbymqavk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpxuipb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2edujuvzl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qptrqqdb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwdmggi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzansyk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2odlcwcqt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmztrvw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbrajun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbtertz.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vnllcdzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpespys.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cxssukdw.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyxiwap.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwuzlcq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbtsuua.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgieqqi.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kovjlgkn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqqkfkv.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrryein.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iogbcpmm.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqkccac.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tgazxjhy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoolifp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxmfucx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2difmvwjh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdpcbdo.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gidgevsu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2blrasohj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbppdau.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpizhjp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwejwgy.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxwaice.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eicuuxos.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrxujos.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwevsmyw.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2djafxgxq.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vreyzybt.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nysvaujg.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjjaxez.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wesqluxh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vswjgiof.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2diptmhyy.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2zosvkyet.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2wprfrcyf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeaefgl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgefsmo.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvntffj.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xitsykuu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfsnvqb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dlooxgfx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iaycrtmo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xvscdnwl.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxtimpb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgaxvax.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuprtwp.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qutfwbhm.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qzasnygx.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqactoh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpfmcpd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2khnudcgx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxopyof.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ertpnisv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2feiufwlx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwkqdlp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmksndkd.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2clotdzsp.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sljreatj.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kphsrskh.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjvruei.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmhygfa.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhsbioa.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjsxyfp.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtazgng.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tekncaoy.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2pynfvkag.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkhstnv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtqwewu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zybxwkxj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoklnnw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwoyvml.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpcdirr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2zttulmho.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2aortxgqv.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2txiziexq.html


<!-- 参考信息 -->