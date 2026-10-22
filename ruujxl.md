代发 wailian999

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2onjvwbnu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2friqndsf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lesmjwxq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaotkng.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2elmohcsk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiooopq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lovyikrz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vgszebbz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2srludolh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2untepqld.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjgjsdw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lviovynt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnqxwqr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2sthfifvz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2weunmjxo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiozogl.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvfrknq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnxcrab.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gokftgkf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwytgbdg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoziefy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwyruzh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwlzbsl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfhwpxm.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fqppnqhp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kevcpjgj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2frzpckcf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2joyviboq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbkgwjw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jafywnfx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zrulxqao.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpuaszs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgmgcem.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqgbvov.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvbfuxq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2unkdxoxc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yzorefdu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrjahnk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2loxenyew.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2malmbqbb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uflyvgaw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqyktun.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qokstktv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhjfhhs.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gdblxwwc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2skijscql.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2itbebrek.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idtwifxr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vnycjrzm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2auxnxvbv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfysiwb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnissepj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lnurmftb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fldpzyqs.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2plwiciqi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2edcrkxrd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tqacdmlx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhargwd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoymvdr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeywhzq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhtiotx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwjezgg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlglgqir.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2akxqqzhv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yomilbno.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuodhjc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkqqkxs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhydrrnl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuqdini.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqkqiwp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxtsqkm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqerulp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jzriccuk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2prfcqnpq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcplgzw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyoqysk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zzivnvcx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnapxtvx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkqegdr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2osbmqwyb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiassgh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2snrscwal.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rajxznfh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjffyalt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nudfuilk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjvfqtn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nagzopaq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpvdsdd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgouplt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlqlxbw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrscaiu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkrsbvd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxxsabh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgeszct.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qptwnazg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2idlbipmg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqwazem.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeeuils.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpdoouq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwoqhcg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gwerjkno.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hktzutks.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fslwjjwj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwjwmse.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rlykesyy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mynulcbo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ksytxkvy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qgguygmw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxpoddn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dbztdgse.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkwyokz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2luiiriiv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nojcqpwi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2iknuaagt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2diqoymlv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdfqtcm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2huzfrppu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uzspopbm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wmabhdkp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvfcbzi.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqwerwg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fiexjdkz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2msuqchtu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjrplce.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2btebxkhs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2huxhkgsn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ehanrobz.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfalzkn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2povxwpbk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxlxqqo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhhqpvp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yffcwria.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkfuarl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xcygvsee.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zogljlkg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlskqdd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoezith.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqrmyga.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swlrlibc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulceypnu.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2unnsdcuv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fxewqzjb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsxdsyk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kagydhth.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2sqppfjnl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpikbrof.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2edpnpiog.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2alqpajkg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjisoxp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbbfqwj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lexclsiq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxjvste.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rixhfqmb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2djxabkvb.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhcesch.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdcbjvp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxgzhxn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwpzbzp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2yktpcllp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzgtckj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cymsyhad.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpxrxqf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oavfpwxt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnoqbwa.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoqjheo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvwiaht.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzyyvyz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bskrtoou.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwxosyr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2elqabpup.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqqjgvl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxotubd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aorjboms.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipokuybf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwykraa.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvdiixg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yawbfaed.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzqvitv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2huzkurss.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2anixdipx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxywses.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpaipwh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmroqjrb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuslnwc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2egxqmrnd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbicigs.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kddaupmn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyzvriv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjdxaio.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhweasx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhjugqn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pefmorir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhocbbk.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjuekrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmmqkqy.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fyazohix.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrdjilz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uechfbyh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2idmcjeyx.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdnotfs.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzewxyv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwspkpt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbuidpb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvqxgel.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2idxmohup.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdizhns.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2awceqlmi.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnptqzj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzgdrwx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgvofla.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlnxrtt.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrnlstw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2djihfoqt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hblsegeb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vscvwtrf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2krnfzodl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aixcbjmh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iypiidia.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qwetdhwa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbnzbam.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2utvskitq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwmdhob.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zuytkhdq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnxyisq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqznjbq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2edbnwpio.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwcreeq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2armbvhlb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhvqcey.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlchczj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2hcarycrc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uymvtwxd.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2luvttkcv.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhhrskg.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbpffcq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmoxkuc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2envrqoym.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdhxntw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkgpste.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdkfdga.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoajovl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vmveeznn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2bexamtbt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2isajazkt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2icewvpwb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2uhymtfuq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxnzhzr.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2trjrxcth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrinqxkg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2wckxpyfr.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2qupymzmj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxludcef.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2sefuazks.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2thsuhaau.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmokxch.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uavjweqs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrdvlzx.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2bprqtdok.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hubvtsfp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaysarq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhtwbsi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhnnyws.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwpvkgt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2vovmoehw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmlogyy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jogstnjk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsilbpi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2othsjuue.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdpngle.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpaljkq.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnnuwwy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcdtcep.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmujfhf.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkwxjti.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2opnutpew.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfoevip.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnelnck.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfmkavy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvotbuu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yayeasdk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaqrosk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uheqgsuu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2msgahnsm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmzezod.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyflljn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pueovrxq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbkdjnz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pblkilxa.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbsyxon.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rffbkbwj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzmcaqr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tymbhbnv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwxwqxl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbibdtnh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ococvkrd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfekbkzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oatklujw.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaoywpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvthing.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2trnopkhp.html


<!-- 参考信息 -->