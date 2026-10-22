代发 wailian999

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2unettyoq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2etisoxvo.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wadaivrz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnwwjco.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxysswu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmbxgdf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ookykcex.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwopmqg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fcarizjc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pnowsqyd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxyjqpu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxrhvov.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elsbwxnl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2khfkwzph.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jugajffx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmehgcm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yolhvipg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbghsiw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcupmpd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyzlkyu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2frospees.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyizdvx.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmselam.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzgyebn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cceiffdc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2daojxwtk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2evydparl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvxhcqs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2uloicfkx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzshcrn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfkzyoe.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kivxgyow.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zxathpbc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pryvmsht.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2flnrsuyx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrnpqvz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2srnqufjg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucelulwv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2buoqacbs.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2isphyske.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgjaemi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rxndqksm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgfewki.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ociafntv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xzofajiz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxjdwhn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbkcbyo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jobfkdxi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfgtbra.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxrejdz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjabhzc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oskirorl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jinllpft.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfapvkdy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoexlaj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsuefje.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfaawwe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esechrwl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrluwcg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdfrdvz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2suawwafq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxvdtpy.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmuakjt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqigvuj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgqerxz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbiilcf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsltgdb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cygdktxo.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ctztxyyh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvkpglg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfblnrlj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkmpuos.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeiwytw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkyuaad.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnjntqz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvipqpdq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2imyydjjc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmpukez.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2arcjzhxi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yejbeoie.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqojxnba.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmaqhxv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsvudxo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrpdbmy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrtrqwl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2urzbemfp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcyjbnr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hahpclwm.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvcmtup.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxmqcuz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2notycgkq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvizyvko.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gaibmptg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnftqtjz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhqnmrn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyiqkvr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvilphi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxmiowc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvsduku.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhqyvmc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2eygcgmcs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmdasts.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhhoocd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjtacxb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2abjtkuwm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hodklozg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sisbsoie.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2azaokpgj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2seefhvsd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tggjvoid.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeujfhl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxevhca.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zntgbyuc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxibqmsl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnnznlg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vctidedu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyticxq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2iigaisci.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zixtulvv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuqbmdc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnlvijd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhackdn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2extsbzhx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqatsky.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sabtniwr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2tiufqpmv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hxerlhuw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2awmksbhx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2efwxzpnm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtbqnad.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2bfboyznk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rabfyijr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2admdbelx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqekzhiy.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdxjkpk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeqciot.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhpctan.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwiabcv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2csuezmqv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2toohhlzp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2luyneqqn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pplcrzeu.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxthhca.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfytjca.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpmpqjk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpbxtkx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsyyjtg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbjhanq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oymbuvpk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kydcajma.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2impnnbkk.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmnncmf.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvotaus.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcvwzoh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2czdtngnt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2edpouxcu.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwsqahu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qrebzvfq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qqizuvxp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvolwyhi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhdaclj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbdqfjn.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2znsijfqt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lryithmh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2obrlpbna.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmczpju.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2stayogws.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgnzvho.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2naslxfug.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2kinbdsng.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2emywoson.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbvsibf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuvklfg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2afnuhlzu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjnmdgr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkaotph.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzryyhh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2unfxokit.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xweuoslp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hienkvqk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjbudtx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzudhzum.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkhffct.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnidmvh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfljepz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdovumpp.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqiqpty.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjbokni.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeemmkr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2otahxowr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2drxetjsr.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfotphli.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmrnzal.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxxfejn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iylcijad.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2isttbkth.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2whyfedrm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycejakjg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdsjaaz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjpbxqx.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nmosvrwa.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhzfeai.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2njtasueg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2uinijpgi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2axsbdsaf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjgwqzs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjdbces.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wgualsdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iijshvef.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdmqqkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iceecold.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2iklshkdv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvlsdnr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jaavtxar.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcphjup.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvyfkmu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzttymq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dxppvrgn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2knvkrkut.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaniuch.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hinqziht.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2agowhaag.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyxmjkt.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzkrkvz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxnjsqa.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2imikmdzd.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtdnyam.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzqeuva.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxddoqb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vgejoxkz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwhleeq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2digojozz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcaihas.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzixewc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oprukyil.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wouaovee.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsgzvxa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wwowrhcx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvpjpdm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cfblzvku.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdxxvvj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmrxzdc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2azmhlhpm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsxgrbh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfnlkec.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrcimxv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2njpbftzu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2enbaujzh.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2pmporgbn.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2cauvwpnt.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwprdyy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnlgdbh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2glpndtzf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dyospbui.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvyfyot.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sxduyter.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtmfryj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmyzzbo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2okonjhnf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrosjap.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nynehqtz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xirkmivi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdzjcli.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kasplobh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iplztghy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvicxwcs.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2juogbxka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znmupkkv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrtzprs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2anuclruw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2hyekinja.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hpesctyb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpirgam.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjsitwq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2goiznfid.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvwebvn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqefbrz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2slorbjgb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mefotutg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwwlglv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlcuynj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2lahqboyu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsbrneo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2gvywljcx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2opjxjgat.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjbdouo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2irrsdygo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2vxycxznf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwyuhyk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuytjzi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsoafws.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2msnoctix.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnprdwu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpkcsmp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikktligb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbebmuqy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwboqkqc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iropbxdt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnemoyyd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2faoxiqmg.html


<!-- 参考信息 -->