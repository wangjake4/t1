代发 wailian999

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zojeaptn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuifcfwj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kheslluq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnkrawt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlpcskq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsmtzpk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nycwgnml.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbvsoxt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zewjjrtl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvvguao.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyrhqqi.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhyubhv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2twgfucda.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdxixyz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvnqobw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2efdndyyp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dupeqtjz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojttybvv.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfcuiei.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbebbhbq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xudoynlj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kavoehmg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuhldgj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhmrvgc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkpimkz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxdzjyk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xnknhgto.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txugydvn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmtyjty.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vslsuymx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdxghej.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmsjzlv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2udhqtcsc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbhvodl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtvnynq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrfsvgo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgceihi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2oneksxbz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcajzzq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcxnspq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyrakcc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkxpicp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxktpnp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsomljk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sfymuhst.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2egbvdtgr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qlywpioj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2czhwidpq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rwapmzpo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2omffnjfh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2aolileoi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieodiard.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzycyfs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vulsrdtk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyodqdt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjdppbc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnertkb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2yekjbjxk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xefbntgi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqcdelj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kybaljzg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfltvibx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2iixzjpqb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfrgdpf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2djecmucc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkryizad.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjouqzg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2simszyzt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqixyaw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnavbsh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xzegoyjm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yowqeryg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2impbtsxd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhynqrf.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2airalyul.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxkyfcw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbztbaj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjiowlf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dziltvbo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2akfzvgcf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcztbqx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wexfkjdq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2csjlpbiw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2trmvuyhf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rguggjvn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2myrpnzcb.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kopnjjhf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xgegtvjp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gzurhaub.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2npbeditt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ghadhtpj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrquwyx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiwrvcc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wynxwhgt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvwmhkz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2semikldk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvrmgln.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rpojojuv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcatnvy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ledtvsgl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2npglpiwx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbzmaee.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wgymefzn.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbgitee.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtubzae.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpswmnm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyaejyp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjjwneq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lohxdial.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2apajhsvo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfigche.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdttwbc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgnfqye.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2omcjfptk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gcddgamk.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdvdkth.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ittztxsg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2eqacekva.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qortcvrj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwspmmc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bghbqfym.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjlvenr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkdlvtf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrfymhv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gamqbqus.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbztskve.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxyhmjm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbzpbzq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbexcss.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtctssj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zitfyqjk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlwdrzq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkumesn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmiuxga.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeilsdi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwjmwcb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pojiekdh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnfgynx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ibparbbb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuigaon.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2drfspcmz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2duudttxo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wckszlfs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuzyaiq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2smrcjidi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2aktwfdhx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtbckvr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jcanafeo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fjduszym.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmapdnxw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gontkrvs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2aewqallc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbemtzu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsqyoqm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcbgmbp.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeolsxl.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uytsqaoq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuyxqwp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwjxybf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjduekk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nymnlnnr.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yovfegqo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrxqxev.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bejabgou.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tffqzcui.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2itumjges.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2khumzgzt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nhftuktk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xtspcvnh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2guwtrsql.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2naxdsdwk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2txebezir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjhhgiw.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qeamyriy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epidvvgq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2weeovykz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfmbeqo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzvjktx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2flsslakq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hclhpyod.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2stooxlfb.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbmrryx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2myroivik.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dxummzgy.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hacgwjhd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tblekqls.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kytpykod.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzincud.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2icvzipgj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wejqndif.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqdtbfi.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2guqulkoq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhwuwso.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fuglojmo.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnfwgtl.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbwxtga.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lzufozjb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nartrohb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmuprnq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfjqemi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdycdya.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwqixxi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rdojrqow.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pfiufzxl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqsmsyj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwcpfqq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmjtpqw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ryompcia.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtulxac.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhkwimd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnvnujo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2whpisryr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgsjdtp.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xamleetj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pslekphb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjuyglg.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrxwfrz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmtzxiy.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bhymbaev.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvbsqhg.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2rupjuveb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yzieylqw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwoedtj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2trfnjmyd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzudlwl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2larewpei.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfmuhjr.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2elthrvdh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkhieiu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyfhxfd.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2atjqoekc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpwjknz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2leapeyes.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvbugas.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2mdscxhvj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xniffydo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzfkevs.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2wltaakpp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtpvecs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2btrryjkb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpjyfxh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2pgunolxx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdlsbux.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqrhluj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxgvxkl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvrphpv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2bslqrsbm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2dymbkrob.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2iajfbvbr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsykwil.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzpevhe.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2slrrjxzw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfmlbxk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmxunvs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqzdqtj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqkreuo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxruluwa.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvsnaqq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2juluxsdd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzxblja.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2znlcauen.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzofwtlb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnfnxxx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaoqemj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqniwlib.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rllrbotx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdibbsz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdpilxo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrfdzik.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urxcgcep.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cashafee.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpxdmmc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugglgjgm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpizsqh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjotzvzd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiqwqei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duhefkid.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcatqst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wudszeke.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aswzaggj.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nukqmfbh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rwknwxke.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2csjqeuuy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcarnjzc.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iostzpxk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwztdzu.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmagvqsk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsgplux.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyffrbt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bgntdtvg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2duqhurtg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwidoig.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2otjjwiog.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyconzu.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qrporqcd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcjqmqy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2smggfgko.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2irqlkluf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxfmolo.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nasbvdnb.html


<!-- 参考信息 -->