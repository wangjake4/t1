代发 wailian999

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2grxpgcak.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqexadcs.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2stazvjgi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjzmpnw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eocrdbrq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpvhimj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfgjkch.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvvxwje.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbnmqsp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhxhnuo.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2twthwgqk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tujidpeb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gqldafwz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzuplhw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdhzygx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvpxsxn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2adsazwoy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fohjxkgn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaqdqqe.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdkcioy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpbcyat.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nryrfvvr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2agsonthl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtiqibj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fewtyhat.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nysjrmuq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2akwmpncb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yabujnel.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eviiqywe.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqpstya.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhqfijy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omfdjnoc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2olboaajf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2svjshrmn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsgfcxk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnxfzyi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzvauwr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2soviwfaz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlzlvxt.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wifojxuc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvldcrc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zaijjrht.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fseuvvmo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhxlhzf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dodpskvo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyznwns.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ebexqjek.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxouanh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2svzgtzok.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnfvgoi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bluimqpr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhfuloy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwjnwww.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqgewnm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlgygxd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqwpztg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvnjvsf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2twcndgvx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpwukky.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuvyykx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fogqoqha.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjczgfc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bypxntpj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaewttmw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zunnjgxk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxhgbjt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjlnlth.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnzlkqa.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjupvyt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmkvwzb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwqwilh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvautxv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsjmdcb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzpahti.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ixveqpvc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqrdzcw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sxanqumo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2idtjrhsv.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcujoljo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjdccbw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2oizuhior.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fafnihlr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vioyulgc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xldqhjvk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2icyjfohi.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyiaijp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzgipan.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2efhmxcmu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbamuam.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzzwcnk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjkhqkh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2feuazulr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uaebklnz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fseivawy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxhyfxh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wquwumpj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdobxio.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nzehwaaa.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2iijqrbmh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwiojch.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2psfdguok.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jisoxeli.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiswbih.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2igeqfmen.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfqndig.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnfitww.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfjjite.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeiuzet.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2daktdpuu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdvkmbt.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oldzmyqc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sejnfgpg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrenmxk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2klojhsxb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jypdvhwt.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkeczrq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgawbto.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyfhmqx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpmtbcz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrztqaf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2okqhdxfn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2srxcgxhj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eljrpczh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eesqhrzt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzbkfno.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwepaoe.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2asiwnskg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmqffnt.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2iznrcicy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2easqrtor.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uzipigvn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiivalss.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaepvzx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2iespforn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2eokqoilm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwecmlqv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxboeao.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mphgcdaq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2luvljgdx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cftekwie.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2acbjcrap.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxhodsv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wppzewqb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxbhwbw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfontcc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjijswmv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcubhfqt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjvbzsy.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hqldkgwi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjprvyo.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wnippdtx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eelglcib.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmtgnrt.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbiohql.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrfeepe.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpgnxwo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2arbqzkfi.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaekltvs.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cixuukak.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2azkjbbyr.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgzklpx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzrupqe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoiereb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smemlglz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2buyrijds.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2buyqwgke.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgbhehj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2revcqwng.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlfutkx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgwexmj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlhpxba.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kncoesjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrxfqyw.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2chigtsvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrxclif.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxgcmgz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sczpgirv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwtfkcn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jpovjkeu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdlknad.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqsbrol.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrcjkqz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bnatvirj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2skdfrqlt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvxeduu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvmtbkp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiribdp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsauois.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgpamme.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2izdwqkgj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpgjjpe.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vovyuuto.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvdhyaf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2calxjogf.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjjkyxy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzfstxk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qydrgfwr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsjsgqb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjqqhje.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2renzbmmc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmfysqh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzruyqb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnwwhdo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2txsazfjg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjctnoo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yfodgqtz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvqvznr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmvhjlo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rupskjqq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kemhalvv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqmtomp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wswvhjqd.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtluwac.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2knfxjgds.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vujoejnt.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyvxhgt.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvbumuh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrfdbko.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pinykeqw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmkdxcd.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wwveaihv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqtslst.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2gezfvvtt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2azjibzqh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsznccg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzfubcc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxcgxob.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ebresrce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvycmgdl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2umxhckil.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrqxcxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pglskikf.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwfolrw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2figedtdd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtyscdo.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyspimy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfoiyiz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2butsaucz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2eizjkvdj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcgwozg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2tdggpzpe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2plarczsd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cepcdizm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzofoms.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaultvj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2setzbfkn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2tbevfuuc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrgsfjj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwscqag.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfmpccb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2nxywdojl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2hebvhcde.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbxlvic.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxrqejx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwpqtds.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqmkhbv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2phwuytoz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xskjbnqg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxeaxgs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfqeafe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlvjsmy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lepjgluz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuzeqmv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urvlxpsz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2madbiywd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhlevxb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rytholms.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jenwxynf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nijrzcdv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnggngd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmhrrzd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2stqjavvn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlkpcqu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkuxqaa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjjmfgg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2snjrmvwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xswvisfm.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2trcshigb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pklgodpr.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vieaajfb.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sllqwexn.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2czltarab.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2slwxrqxq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyxqjcf.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2eftjsgfu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtxvqtd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2deoxxxtz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwonagu.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgjvnyh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2toernfuf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nscqvsrx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bykiynei.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mptaiwbc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkiowck.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2afclnpeu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcnttmp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdnfgzd.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qprrpwgq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzslqjj.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qygciaop.html


<!-- 参考信息 -->