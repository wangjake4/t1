代发 wailian999

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qtescpwz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwwhtpo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbslbiy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnhvlxf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvutijd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2crhhectk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdztamx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mkonlsaq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zatgyqer.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mchnnqmm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxdbima.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2liqfevmi.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fravqwkb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vegostsa.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuejusf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeieaif.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nustqbrh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnjzckh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xowrzxpr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgttdzee.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrzgapk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhtemoc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjbhfvb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ervlctka.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fjabfyhy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2psmcnnkf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmmvsrh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvqkklf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lswnpagm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xstxdiyc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrffmgw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgispqi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2brrndvrs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxjhmqn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cttnsjqg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwcxsbh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ktderjnf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2anclqiau.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oexkyvmq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oahkxywf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2slbrcufq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vazhfpna.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jfibuskm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2jvduhtcs.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhjneri.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wdraptcj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2snniuqsb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmxfwyn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2agfdotgw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hopqdlsu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2imjzmdgj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjkjutr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sffklzyj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsooklqr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smqfllnt.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvfekkp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnvylqs.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2disctamj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwscyxc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mffvfpmj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bqobyzgm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfervfw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dclszgbr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zygaciop.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmrnoeg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2seintbfq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2khrficnf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqwugxr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zgevfhkc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyudpsdn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaqbpnk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaddgui.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzgqphy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tubxdmqm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdyamnu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuhabzy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxsfoej.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbzqgzs.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2flubakdw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnmqmtk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlzwkua.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfncqhhk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ohilfhfi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hutneozc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2eytjljgd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwfcmxa.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlqnhqd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2blchjxig.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbngbwr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2whhkjlbn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvhgrcs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeaxmyj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nidkacml.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlqvjyp.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhqbjxn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzqkcww.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgevhql.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqlhnqu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjatftl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuxkoms.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gapvmwaw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bztpqhda.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bysfrniy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nulwuemx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2unobhmts.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xnytkpis.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfqpnle.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdwwhos.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2osncjcrh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2udzopgin.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2owlhxrcd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsyujwa.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rxadadhu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gslcyfgz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pifnxpjx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaencigl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjtcbcm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkxfzou.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqkdcfa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2uusldsvj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrvnvlm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jcormqas.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2omcckzsq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvkuxbe.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2duwlbepx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vovvopxl.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaxwjsg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdammflx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mqklccgy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mcetuugq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsvtbmz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqydactr.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbesqin.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbdlsop.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rztgqxvg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsillgv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsmeasi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgfcimr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhskyaf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxxkbds.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhkqjps.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvelwdo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqvcyvg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxifhdx.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgestou.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxycsgka.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xiotguxv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cbagntmj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2miapigml.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yeecvaxh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qivxktyr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcxqyrq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaiphqt.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtvimdf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzlkcpv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2uveyybvh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdqhtym.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2blmxuytz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbfanpm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2goqwcnpj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ifetvbpq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsgohgx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sutmpdnc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2iduutxul.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2oankvpan.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmdmvgs.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2djssqzku.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcfcpsv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaknprg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyfyoyz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzoedfr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ntytpggx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdytyjj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlzydhw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2adfqlqjw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuppewi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfopcob.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfowpgy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkwowul.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohedvmzt.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtnqlfe.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbiysww.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2quogtigj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cydzinqr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2staoiotb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zylxewhv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlubfpw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzpxncx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqcgrjq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xesqjtcn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xutpbttg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2thiwyzjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2seiqrcqt.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjuabdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfldcey.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dptcjwrd.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oonjmaxs.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2angsybtr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmnxuhj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrrorsf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2giytnkqn.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmrollv.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ympnouzb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mjudwpmq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwumvvw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pixriyua.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2lujhwdve.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpihchf.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdqzlns.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrehsxd.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjxeopq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzexdpq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqcxrpm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tiatxncb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqtbjnd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2knkliwfb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhvazov.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ngezlizu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2aazmpbfo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lmajzgfi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2iqytwfyb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ymosbfjo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2maiuaopg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pwukkcya.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtbgnvf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gnispsyn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jecuhgrz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aiksgipw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2myywmjuc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmpheia.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2prkrcgpn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bswsbrfr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ygswmnzb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nxonepbm.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2usrofvio.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pquxzufg.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2piszujmy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrslams.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkgnfrv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uohignee.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2xtakudas.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvnksdx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2zallyhkp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2renqbxdv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhewuop.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcsksyb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kfejppev.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfiqmtx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmipuatq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2moabnxiy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2aypofwxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkxkrar.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxbgwny.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2prdegqqx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlgugci.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmodogk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhvwysb.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvqmwst.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcfxrxt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyyykkc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdfwqyn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiffghi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoghdpx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvqtgwe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rptygibo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2psxnwwnk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoyudbr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ekimkrvm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dwppwpsf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lakzsiho.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2wjodnvrc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiztrly.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tljlzlyc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2stvhlson.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tltoqnst.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpslezlb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kantfrua.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dabzqsha.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkqthhu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhcdfjb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbipkbji.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwccpjht.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdipuyg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfpbqvt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzhiutw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgclzqf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpgdvmp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuaiktw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxqstoo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bokeixta.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2meaeyvsp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2izdooexg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyttjkd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fskqklvr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhbatde.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tniyhtvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psmafbrh.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqmortg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaognmp.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvncqgt.html


<!-- 参考信息 -->