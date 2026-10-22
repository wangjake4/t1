代发 wailian999

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2lypatipz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrljtpv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zekzpukc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyhluep.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhiyycs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzriztg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoutcwu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdznuwy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2crzwawom.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mueydajc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bcclzvjt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwjpikx.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwnbefr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2alxaeamn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2genjsgne.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdipwmm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mksppakz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsvtykd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsqcwww.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kejlygyt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dghybaym.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2eyypcras.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mejcopho.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2heriwyov.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yemylhxj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzppcjqf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjagkji.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ityoassi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbdenjx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbjkehe.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnvmwwi.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2igrgmjxb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pshnccfc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2alpdprga.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqyzdrv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlddvqsv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2henogdov.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpkzedf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxssldm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwmpqzs.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hzahujcg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnfczao.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoyrpmx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pumfhzzd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbqloer.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxhjzga.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjpcbam.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilknzacg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2poedljjm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xslgkqve.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uygqhwse.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2plcutkoi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eexbrouy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qedxxdmw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2cphzgoza.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuunmup.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwzpfjq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gajzmvht.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdesrvb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkawqxsv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxpwgsi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uklprkze.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jwputlmi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2uatenlyz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ucruobgq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2skqopozj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2umlhvlct.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqutvxi.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2csthbkzi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrhgajt.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2atemuycx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aettmirr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuwsdol.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgujwgi.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsltaui.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yedutofv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kozybnmr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2crmqzedh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2liodzlis.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhgtkcu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jksmitrt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgmcgym.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aosbyzuu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2biiuzfvi.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxefylc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmyihne.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ksajxfyc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2drxwmrri.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjwgxso.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwyryrw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bdljnmgy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2okefjzbm.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzsakqh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tpauvjgk.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qxejgmpc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2izwjnpuy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrsofzz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2tptrybwv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jftzbiig.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2yktckfyj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvajyqy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vpprjvla.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeikglv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2muzefgcs.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uiastcdv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dstqiijb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2almjbpos.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2inorcxug.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkxswli.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xafigtpr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xufjqgrv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2utxfhzbp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpfjqvu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qklaalik.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yqevcgyq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2knqekxuf.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzzzcwr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xezbsnfz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxqqnjl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dotwvvne.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmpldxp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mwanrsta.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbcexnl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyieaciw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hewvayzf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfolkcu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jncecuvy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekroglnb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ooajelcp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaywygm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwbkcmr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxigbxex.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwrcgmn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzcrejo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkdapww.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xvufdikf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvhibeo.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2klevcieg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvuiyeo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2uekmhbwm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzsrmuk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2upxvydid.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jejtebnr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfarjof.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2azqsiuqg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qofetgay.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgvaycd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rjarnlrd.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpwlktn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeerscj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yluezmez.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyiaoxb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fckslhtr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2raxvdkvl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojecsfrp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lsamdkqo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzzlfrq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsegmas.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nymeotld.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnkbpoo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cfktmcuf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2osvmceql.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfkznyq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kademhsb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnvdvjt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmexhufc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwhxwdi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzsbwou.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lijnrdjg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sopwrxpt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2olmbcsgx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfllkiq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmhxeer.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyifpvf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuwtdfe.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrzgtoe.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkzjnlh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkbdmjr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmyklxc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fibnpbtt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdkqcyn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2olfdjvlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjglrjr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pmllgfmg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvbkeqc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uremhngl.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnpixmw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wilndyal.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2njpgykgt.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfxvnus.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cfechzul.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyuoytl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hltlmacq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2annybsjc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2uscnsliw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2yukuofkj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bweeqexw.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xrplzuby.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgmasri.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ipghqlrw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2txdjmwku.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnbktjc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pchevrkv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2iuycclny.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ersuyluf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfajgaq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2daaaqves.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlmyamg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgphger.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbrxntu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhsmjnt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyqhaei.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqbbrlt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pliakkes.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fzumzibj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ohepudap.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkidtai.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ptziykad.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlukkfb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwdnwfk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuvchhd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmizdyx.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gefxzfgg.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgkzqhn.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2anwltujj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pagzvvob.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fivizykf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2takvpqmo.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2tosuopze.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmvvljm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyittxq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qiprsplu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcswgrl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2edmdsfqs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wdulwbqr.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nubegmpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bchaflga.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysucfufb.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzklexf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzopqiu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbojncx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2lutnwrrj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2imeaatov.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nammhong.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfnljpf.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2osddsqen.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfgxigi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyulsri.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2iiydwike.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbackgz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeaxbgv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2limsalel.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjqqkie.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2luyilheq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2gffrvfec.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbrylpy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqmabyk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxdtbgn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2taujwxnu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2tyatocop.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlhozoe.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ncswpkrk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kaearhbb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfrfyin.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eurdthnn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sddcriie.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjkvfdk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aahcqzor.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2czddnkwm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nacsjerh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmiabno.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoccwpfe.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqzauxb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2etkpagyt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpjgces.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsxrjky.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2liddoiyk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjezsusi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrupnxh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqejhgb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jntxdtto.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdfkmqv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgpuomj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tufsghzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vskcphux.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2taghlxrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khqpfwgf.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yfofdprf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnavjhw.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjgsknq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2brykseze.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkxnnzn.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxepvuzn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzxehuo.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2townthtx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2brxcodzv.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zotjkubk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2thlmoxop.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2esuiiujs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjotija.html


<!-- 参考信息 -->