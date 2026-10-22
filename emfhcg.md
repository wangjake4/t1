代发 wailian999

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mksnpsnw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjhdhxs.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2irdlfjxz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpvrjbw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhimock.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vfylglqo.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jseuoucw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zooavxqc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2depmguus.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2eicehmsw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2plguwbre.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2htbzzyvx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtbtiwm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnttxqr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2czzlqohh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cfudtdtx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2avkdrfnd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuplvbq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbuqgcy.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uokzaquk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwoblkk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjlnqxq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnszqsl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgtacgb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2govgynbx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdhcfjb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbqrgey.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qimtvbeu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2adundgdz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2umbzkroy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwyrgvl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pemhfpat.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdjcrzd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbkxmfm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhftypd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tqulgucj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfrmuco.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfdvvzv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpnfbea.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2euomompa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2khaawibq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ysifzsry.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzhtwqm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2srycydpi.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zkchuxax.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeobtji.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mjknpejb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pztdinxq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2detulthz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhxtgar.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dcinvzlm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpqmqhp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2opajuhof.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rvotipbn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uojjqnpr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drhemqao.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zgadfuzh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zneyqmig.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrgivos.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfohxxv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2awofonva.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhxdfrn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yunaqzpd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2godsgtll.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2acdkhlyo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuqswqw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeucoqm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2eubzbsgj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcgwchz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqpvobu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzharhks.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2umkbteef.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jinsmkma.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jatnephh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxcgueu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyruwcci.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbostiy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzcmgjs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtzojgf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqmgnsf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlcmzrk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocawkjln.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsvjnpb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvhvqqc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kopkfjtm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zenpfaht.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2meategfx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwczrlnd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2calswrdp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qundrelx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2iwddwkip.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbiyeuv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2oozttnol.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqvffip.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqfbfqm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxjdlsf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jcupbpsp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2spsivyal.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zxunhyif.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pihmfmrp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdkpfpu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nflxuaee.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2apulbsge.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaairjh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmihzzr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkpzjss.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dejndiry.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpiptnp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzigafz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kajhkkmn.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2yywewbee.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzddysp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2arvdcsms.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mfukbuui.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2drpzboro.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdrzsrb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiavjix.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zuphfjee.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxmejxs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeqtawk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnwqkwm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpfbadq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwyasmi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvezjaw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xedflwym.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwrcjie.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmfeeos.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mernnpkm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jhklyuwc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2eveuvkch.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhpaakp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsxxtou.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuowulh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuqbjlc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qizatots.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnqmwlu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxfnddm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ldclgqir.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyqvehn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsumrbzw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2izynplmz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kopdziwh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2snytkhft.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2buliluht.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ahefobim.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjdxetx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmgzuyx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsdgpgj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyxqyll.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrbhind.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwdbokr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sttkgjxt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uyghqijl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvgaiat.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2csmcahrf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bphqvkje.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqbcqun.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfzgyvu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sdptfvwy.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2liajnqtq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuvohxy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2bicuapwd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzlnmwb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2grsxdric.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2klqggpvg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2lahoxsfz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpbhuec.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuhelqw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2shfibkzz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cccjptxu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zdulbomp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2swcazgkd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvetyxa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xktpzeom.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2smeuwlin.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yquymwha.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hngrxgff.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvubbkf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrpkafg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kocgmtpv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kyohlizz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpwhcco.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2euxaxcrc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kevdkjvy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qyapcfeb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gozosbgy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqfbvyc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zksryjzn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2axycjpjs.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiboocf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcosctvt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elpuonsc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2abolvvoo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2opoeheqb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ukecuhkk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yylnvurw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzsvjcq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2reyauqlm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvvqzvu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xscgieyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnyebau.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpzmbii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yazyqfpx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnatlix.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uorvngeg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mggdvxlt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fquxrkzc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhijvtp.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkmdpoh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhznsbi.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lynfzjgb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqsgjcd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cpecuygm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2exwrzlge.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkivfxs.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ribrijiu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgrmlmo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmestes.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2saumfuvd.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqcrsfl.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zstitcpe.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcagvil.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hlivvtvr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kouwvfwi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2chdllzcq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xqngouyx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiikfbz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2htwgbnkp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jifyyggr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmvnedf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhnjngz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ipebkvhs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yptqwjxh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvebwwd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoegnrt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhsncdg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsmunxe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2msikcabz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2monvmjdg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdejjeo.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2catrsidr.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfxgosf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mkggvqzh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkecrra.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzorcrx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbmogoh.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xzypaigx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnbnqfj.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhnejnh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tzplvkqv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlonywo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2eeggnvhb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2meohvdqk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgwrqzk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2adizmiyc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaxbgfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2araisbnr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpgcggc.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmimfdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zoovwyhd.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2epwpylir.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhdwvtx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2hvifoszq.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqgvhzs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqalxhb.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwoemex.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvflfxd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbnhani.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxigtyp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqcgdeq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrduixz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvqvlxe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2johmhhta.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxmpncq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2eucxbljc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2kizgrpkd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhexjpw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoglocg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrvzutf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2poulahhp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmpjuhc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhxfgyt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rorovlcr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2avxvjgno.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2secytzpw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pplmtxki.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjzbkiy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuglnqit.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkdsxgd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uueiciec.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wphnlxnx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwilsaj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqertkot.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2thshwprq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lubxezit.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfxctcd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvirqyav.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmlcxyc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyasdkuu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lidkfivh.html


<!-- 参考信息 -->