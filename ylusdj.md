代发 wailian999

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wzprpmvu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmefwta.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2huzkzmaw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjxsqci.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mefvpnrx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwmugzb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyhzqfs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqgmuvl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rytmqjbx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2swrwrfmi.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyautio.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtilmwxf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qeonybcy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgbofxg.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zdefddsf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsrqbru.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyqnxpy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfzbirr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xwipcjvr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kandaoyq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoelslj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2strpoudh.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oplcbxwa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2clsanboz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwuhckt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbczlmeu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xqplydzo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2siwntlgd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2biuxtxjc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mffajblv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ndonneyk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzhhtep.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiarrnn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2utfkrgpq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2emyxnxne.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmgucax.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcfzpxf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fcndoeib.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaslbtf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2coaxdgoq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaupesf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdszakw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2udmjitcn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrksnbm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbbglye.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uomlgpky.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2khxzseno.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqavbznm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbvxjao.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnaajfy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrrthbu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqtgfkl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsnndxl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuyclto.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnpmmqm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlmmkle.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jdugzjfr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuqbxmp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vmchfmza.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qshnodlq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2weelmlir.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2eguaasgd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaesemy.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2shiywhom.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcoztxe.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2eubozrbn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssscmyyn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaqugkc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pifvtcre.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pazxtcfu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xceecjiv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2niqjgkhq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxvmypv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkyhyja.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuhearq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2aobgqaak.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvorbod.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvbjkty.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2funbvnkr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmowtyvp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjeokib.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2kslnhuyn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhlmnma.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vylzfusk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2iobjhsip.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvukruj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpulufm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2psbuyvno.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gofktsac.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdjanbp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2drozduik.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyafvpa.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsvldtn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbicqgju.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xztttekg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfrfxlh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mefycrqu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwvlfio.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2oipbbonb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zonqprba.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyakwqw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhdzfea.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2stqjuysb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlgbahz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2whqqvxtb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcouhvlw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nypquaad.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzsacjx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdkzyco.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctespjds.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2elonpfbh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ualqvvrs.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmmqrzl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2quloqfwv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2juvhlfuv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bypmrwro.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xoooedqy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjfpvyk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoxqzev.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrsfikh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djtlmjkf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gffkzflj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyocrwa.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvbyhau.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2adwjqcbb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2exyfdpaf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xmovfcsa.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvnvqot.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2woqhugly.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvfnpnp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jialiwdg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2udtcxkzr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bisbbpxt.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2axmbalgt.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mjacrevw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xshvknhw.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qyubbiah.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjjhpsw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2aaibxnxl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqhxagp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hiatufbv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjrtxml.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vihvbuef.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvntzus.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2llsxslth.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2seaxmznh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnbhulm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2swggfpet.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lduwwzca.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiigrjc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyhczkb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2plvnghdp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaklsua.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhubztr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2waechymq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2osvtaziu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eayocqfe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bbframus.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zzafxygb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ayslplrz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaxdozj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2roghndfh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2urzkbwpr.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcalseo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkklxfh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzlmlrr.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqulzfr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fqciwscz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2iufsseut.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2osygzknf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgmctav.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfjstgs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ufflbqyh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvqcwnj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgytqhd.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfgxapo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2felftiyg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuavsos.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2uftebgsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyalwkk.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2byebmmmp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2olbeoggg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2oikhgibe.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lebyxspx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2vpczttte.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzovfrg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqbcvrb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qfttgwmi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpvudho.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfdkytq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmvvfqz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2emgvzqtd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzatxpx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ohimwatg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2picxhbmc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqfjcub.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2aqotgwds.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2unxhvyma.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpnuryw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcpwydt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsosreh.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2qaminshl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kphnfhml.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsvzqab.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qplunowd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2laexksau.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwuopnn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dguotzbk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyupnjdh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrrbryq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvsfqix.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tszlydwf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgezsku.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqijmpet.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwkmpkl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofusjeka.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbrwfve.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgboolrw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjoedlc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtgngae.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvzqull.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfcytij.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2miujccjc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwibkpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isvpsyyg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uzacunco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyteqgs.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ciniupyo.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cspyqxwp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqinnjzs.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsktboc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdbzipy.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2csidjwrg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqztmkt.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlizwyux.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoxwsps.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwtzbnj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2slditgoy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtzjbjw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2swrzcodd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwgfubs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqourspt.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xwypgvvn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ywowzylh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeacvpq.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkhqosg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xinkfojo.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2swssepkg.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfxicsx.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcafowez.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoouwtmv.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzrzqfy.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2anjezrtv.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2squwmvph.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xokwfyof.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtejfie.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pruznked.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiqvrfi.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fajzgbzw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxivkez.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2dllyesad.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2akatjmhq.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2taeybnfu.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjlfjtp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfonoqm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qyicdefu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqhzhxd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2evmdiymo.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vwslucjk.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeugelz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2widccqgh.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpnmsvx.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxrozek.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjufpnab.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgykmlii.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucduyrfs.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dckjirqy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuwlyzq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjatmln.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2bxloycfz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmgkvod.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyquiog.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sryzwmin.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeeaoxr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdnozrn.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpnfrpb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebivycvz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsnvumo.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2urbrhemv.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvfkrgl.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkkxmud.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hupaeyvj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnhdldt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxskmoo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiyhnlb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwsmzmt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iudylhcw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyrpgdi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ritdmwjl.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zodamoyu.html


<!-- 参考信息 -->