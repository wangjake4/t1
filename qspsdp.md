代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbleccz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sehhxenb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2szhfgphs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzprhdwa.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrsaukd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjvensu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsdngjo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2crcpeixx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrgafou.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dovztbbx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ljapmwny.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrprqlg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2etvlrzvz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2teuneiot.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxombzh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwsyhxd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcdvrhu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbruortq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2cjowrtcy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrlxoaa.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2glgcjpes.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2decrenhw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cirlgymz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrznycs.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2exlvmvgl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2otuwblip.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2infdlcav.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdzfnxf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dnatflqe.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbipmrqv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyzjyue.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vdodqoyr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2shbkwjhm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpegofm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzyrvwx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbyeboz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wjozqtmu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ytohxxgy.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtvcoxq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwdrlyb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjbltjx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ntamkzta.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2anczznzo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2otpdtwoc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkrghon.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2glgiquza.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2auioztxt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfoicke.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyngkse.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lsimathd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgrydzp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnztaas.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vpowcgyz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2taniemqj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2guvkhbfi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2adpqsctw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyzxrfy.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xuonkveu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xatolqfs.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fntsawyr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmratbf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqsrwqt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2luomyiuy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnjyaby.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhwpgiq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdbhasp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dxitkpql.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhdmzdm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoxaivc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sxegzbfj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lburhjfx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzgoqti.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zflajxep.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmlssvi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfekqen.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpmjpwc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xznqchow.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2twitroiu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpyfqgp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2updscusk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyofoey.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2scmlagyu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cvixwynt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvaccad.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bteudteg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nugdtlzy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxubmhhj.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtqyljt.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzankgb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjcvvwi.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvrntxr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2obqympme.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2efpirgrt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2prymsidz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2psedzura.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aergyfbx.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlvjtqm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfkxzfh.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzdgqcj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbqzfzb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2legediup.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzheuqhk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lataqaau.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nytmyzkr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ngclnsho.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpafrrqv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2oljflwjd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kauswzhx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2quebsvts.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljazuswz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxxhmdb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwvgott.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cnocgeoa.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rddscfbx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mkydxhfv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2swdbogjp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvgkrua.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqenjmt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nprjsmxs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcgfmip.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfuplze.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmorwvl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2islscfwa.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nghpnakl.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbycota.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vleorjna.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhtrhgu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xzljbzzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzanxhge.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bawnheim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjhelnv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2sssgdhui.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xapygczs.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvukeee.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmosraw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdwjvqp.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eixbgksm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpcxogn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiyiuvr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzmolsi.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmpadpl.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhjqjiw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2tfubuinc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wpewhtlc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlrpzwl.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pttcoccm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zshfpyoc.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpsyspj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yunzobtd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nhathigi.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhcmpws.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wcounjfb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuyhoye.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jucptlnr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuchnbg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sfljxqdl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdhrbel.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2broxhraj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tqucsqrp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyareag.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfrjwrr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhnjvgn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2trqpzuxf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vdadjpak.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmxsvyv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xcifxbjp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgaosrz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2audrwwnn.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vxamlztb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcooypd.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuwgtaa.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xworwnut.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnbvjuc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bffeiadu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jfewbult.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gplwzrin.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2diqdomhq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zdulgrpa.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2znjohqqv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmlknul.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgctsmp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjbpjkx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkajlwz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2icwxuprw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgkdvwo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbtngkc.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2myeamtht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udyjlisb.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2yttcbkds.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiwkfuk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2kiclvbdv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2euwtmvjb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gubghzzo.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqpsnur.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2anbtdmpe.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlvwrje.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiurxnr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmqqcvn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xetvylhp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qyownehj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2spbwybsz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2sspspkot.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmmcemz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgwfrek.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvwxgka.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2whovwunc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2agmmouwz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2noyokshi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvexzeg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2oewjdcog.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ecymjghi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjuuojy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzovsgs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzvtblt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eacywibl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cducfark.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouigugvm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2flnrjafp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwvdfoo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kejgotrw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgpbhex.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfzubsq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssirihig.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxudqbxv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnfislg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhdxtav.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkphpal.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gszdonme.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2atjsoaxy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2befpxhuk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwegbxb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiyevot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoftkqm.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pbluqdqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pirwpcqv.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2etanvuww.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2audpxmup.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxscpswh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssikflmu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nktmxolr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gljjtfov.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdjqxcl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kapjjfru.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bibadacv.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2uqonttjc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkajxsr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jchfxrfs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aljpgods.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcesfxr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2foxrwgnr.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzsdeva.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzngtwi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2exetftfe.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gyifkoos.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyjlkpm.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilknzwdl.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2faiwevxu.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jygafqmg.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsnxdys.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2poyigdbd.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbwlnpp.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsrupzy.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xxinhojb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwovtfig.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkvfdtj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2odhfwdhw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkteuzx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2huhmjiiv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaeatsk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2garnmrbw.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2goqmueez.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnsmasi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kyosoqvt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrhieqq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdmybny.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2klyznxnd.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2laeeouia.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbtetgv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gluvxbih.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzanyzg.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uecdmyww.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsoxnlz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2plpqvttp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cconawhc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsaudgi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2atxzoixc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2mijgplde.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqydhhe.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjezpvg.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnvhlwr.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rodkyxvx.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2peawwhdq.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckozenrj.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcnckqb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzggungy.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgggqusw.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2somnftmu.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wedmpwmj.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2yopbcbmg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzafeaft.html


<!-- 参考信息 -->