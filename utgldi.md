代发 wailian999

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcmtyiw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjuihug.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqqxesl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2opqdyrlr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxvyioq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcpkqas.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzhwbhy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhismais.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2edqazekb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuqckud.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tqadewfg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gimwwezf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gstbkpsh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eihakmxq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjqawwn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jzufpkan.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfvtbul.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhueauw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiopwzo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dodccgiw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtyuekl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlndjcb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bydlrcnh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwwovae.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyswqsj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfmkoso.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jioevipd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqgipec.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yidvzgzs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orimbwia.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2psxsgfxy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2egmrjivz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qezlygyz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vknfotkn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxtibif.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwbwlkn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxkuyfe.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hmprmrim.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dttkssaz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frhoqrhx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgfyais.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjqwxwh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wctuflaj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2megafkkf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2brfufonr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwhlhqh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhnoyvn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2snnymoga.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwyzqrz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2cscneutf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sagslzgg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gowxpgqs.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuhcacm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyhhrfh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzrjjsy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oshopccn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nslnldmo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaegeiv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wktsloqo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsnovqz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2sklaftia.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gflbivut.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2akkocruu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhomlue.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrynowl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qudjxijs.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2olcsyvrp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2baaykqfk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2safelljk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlrymnm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2girygwsv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdpqwgc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsymwaq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxbyitm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2maogdhwc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bspjjoah.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oicslitj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhxebbd.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2asliuxnv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfwdweo.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zortfrbt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyctusno.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxojaqv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bokinnkw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2suxtjrky.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgpgnnc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tyujexzq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoikxmk.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwlwcit.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2oekengbb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rduajgpb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfyapsa.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxckxra.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrtpzjl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrcbofg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtusotq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sextxvjs.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2aynlufls.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrefizt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2avdeibmw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tgypovga.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxentki.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wybpbamt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcodhhfn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pmatlqtx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnwkpqo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2swkulych.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsmzgvr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2asnzqtrq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gthcllmy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnbzfhs.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwpdpzy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjalxgqk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2plzwesgb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2joebsnux.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfgaynh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2osqfepwv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2isnjlqxy.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aodtdtwn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tumufmav.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pumiuhqo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lqybblsm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ponnlnjk.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbrkdbe.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2drmesqkg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtfemvw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skhnidud.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tymgukqc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvguymb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrqzfqs.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fydcljyy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdwzmnw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdcvcyb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfrfssq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zijnqvdp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjrncib.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxkintm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhxpnft.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lghameqo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjrqbwi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwfsgeh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjepdgy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hiixzpmt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqtpwrq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jvddxvpx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyygxxo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hcviivwd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoypkuq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zymksniz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kmczlhcb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrqtqyl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2buhhfxze.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzepzpw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2onafxizc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaaksyz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjnjeeg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2posferpy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyynjbfg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2aplprjoo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvhnwgv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2penyxxou.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcglykey.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgqsjaz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2oufijhpg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2huhmuwuv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpoahnr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkkaqot.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2okcknnqh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmxafhh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnlgcma.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwgwyiq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhobcmhw.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qywvpimp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mbevsmfw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dggmtbdy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2uxguwpke.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdlbsqs.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vibjwhns.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhawhcet.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfvvenl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2maixzvzu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhrahew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khgagdse.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsqqeiw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2csyswzhe.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yrijwcox.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtcpxub.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uoevqzjy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ddstqzyv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcwgtoy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbmwihz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2foixtpgt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkzynmj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2byiaaehi.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qminguzv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2eqstywin.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxtreiy.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2joeshtmm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ijobbiuv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sesjywap.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzwaumz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdtlwfi.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjnledi.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbirexp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaachnp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lxduabfa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwtipel.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tbziunns.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2srepssom.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsjijwo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuzikpy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyimmqe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkpisad.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfbpnko.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2guhwglwu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuswlud.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbfsile.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxlmcsd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgqpysl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qxteeqcl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2okoxqtyk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ulskkbvu.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2srwitesm.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxvysjb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnmmtog.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2roaoeeay.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2khgznxrr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oadbnfwr.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeozmjp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rbizmffz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2whvvycjv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kitjkuzd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vtowlbin.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzecmwo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsiuwvs.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wtluzcsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wodtufps.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmsowfh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjbbbrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pknmrsyx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeshcji.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2elxkmxeq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2svixfunn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvgkwom.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqnuejq.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2fcexggmr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtwarjm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2trfiicku.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vutxemmh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2heppevjt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuuxtlg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhwklsf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bthhahyk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsijqhr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpulaaa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2skiywbfw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsamdtp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkfawvl.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2wffmpjyh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzppjqa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jckebnam.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2akqahkuy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ciluokto.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iogvvxpt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkgnaar.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxldrom.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2phcnrjhm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzronrt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvieowh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvvuvqu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeefakn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzakhmyn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgumvktu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmqxmtq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewicnnun.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkcsuse.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxjuzhc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hveaubpp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaffzjd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2idkhmmhh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqagmyhw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nriehelx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2adajpufb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sezjalfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmawpvvb.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaktkzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wujimxsd.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvxcogh.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuojnsi.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbojzmh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2envoisdh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2egobqlel.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wclwiahp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tomjxhhd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2aizotvdz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rviewqjy.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdfheig.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gihrizwt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxizcgf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkhcluq.html


<!-- 参考信息 -->