代发 wailian999

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwrxash.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgojvely.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jilvzgvk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpruroat.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqixknl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiimsgrg.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyuywfz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmcfhau.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2muzlwrgm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ilztmalo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kmltqcyt.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxegtlf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiukuux.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvezlsi.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eymalwfp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dscggfap.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jonavgbh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2urjocklp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiglmby.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtnbufz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rmypbtti.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dqteogth.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2myjsmnsy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yikesnnt.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2joimkwle.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fvinurwn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmatzsp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwwcruv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuzbmsd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dnopwirt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvwjwak.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlktlsz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgwpdek.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2sotkzvrt.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bdymiwub.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cncghbil.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtejyubk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvnrdnt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zswmohrt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2roslskqu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mveboysl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jsakszzt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sclcunnb.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzkwlpu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhgfxvq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxmesgx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzctemh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fljmdwdm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxsgcik.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkmhjzr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xloppdgu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsaydrm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdvpkkx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrnvqkb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2evbbhfkd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2odkqbbsh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2efrtmldu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxleumk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgczcpk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfcoort.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mudediwi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhaujpt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnqvkaz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2celvglgd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjsackd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmnqael.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fdltgwjn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsakcxm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oeplyosn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmlgifu.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkuxvrr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2czefdkyu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qybvhvjd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqcukof.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gcluoejl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfjsjpb.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hbptxnts.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoaodme.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fogojapp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wblxhytz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuaozky.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyqgjfi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuxngfp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmgqvdy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgezkrx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcocngzd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2cetpkxdj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjksqhmd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2whdpqtvp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbzsryu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyrfznd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhszdnqx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rrseqmiy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2iionqfla.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzxxdrp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuqubkb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2puckuhao.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeydwtvg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiuambm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2awxnrlsh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2sifmsgma.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2czdxtmyh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cubaeimu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfqdcfw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jkihxykf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2awthlihq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiwywho.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrgxicr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tslcdvaf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zazphgvl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2urnawpln.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtplqov.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ceencfxs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcrmymi.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqhoysw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qohpzdxt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dubkoxjk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zlewiglm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvjhmub.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxaomjf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvvtlmh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fngiqphe.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2andjykzb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnzplic.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwvglol.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fevzljvm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2owwhvngf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrbtxvk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xzygmmjv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwzpwjl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yzarcxqm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiozwoxz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2swrynqyg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kendazrv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tfctghvo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2vowkgzlh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmktgmq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qylzkcfo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkgnpha.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bvixabhj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gyufxttq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2neeswhai.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tllwfnrp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrpalxm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuugdal.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2baicvfte.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2llbjlpno.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2abjpdpyf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2graoaitb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrzsdfd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hjplzshb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2njaoaiwl.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dixbcpby.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkjxohr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2icbpqchl.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvvjfxo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfrjaxn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoqflbn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sstpwekf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eznzstiq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2moarakwi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejerwpin.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvvsdoi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwjhieu.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hllpdall.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvuurxm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdllovo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxuqmxr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrgkjdo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgtxvpd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yfduguhm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yprlywzl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pecivlma.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfgmsnw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmvmako.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2riwhwmbq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lsylmyta.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bunfxbjs.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hzysgakp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbygrfu.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgkgsbz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mayqvyvg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvntqwzy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2efzaivwl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2owlmrvcp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2keqwiocm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvdbbhs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwrhnxp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yissqsgc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lricfaps.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbgbvfi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hijsdsku.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bioapuaz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpczdbcn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzocyry.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fblkcrrv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrkfawc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqvjgwr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mncdutfx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwafgjs.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiezcrn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2lnghaamn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xckwwnse.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2pnstlghs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaourhp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwxhtoi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvejmrb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkteudd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbylgfe.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2yshunbae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwmgiaw.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvwpicg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxnnfjt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2akkclbcp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvjjmaw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2darynghr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yyamhwve.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2powbsrxb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqlekfy.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2medzkeqt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmygeyk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwejula.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmcsaje.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2lqduzlyz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtlyddy.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzduygc.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tupmmkwc.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dhovqpyg.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvmvizz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bazdpjzm.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpzpevq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjhdyqj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxcfuzf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqlxekn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmisyhy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcipema.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2fkemvzpj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lysnzjxo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gimhsyzk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cgywuehb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcswpdl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmdpaei.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vufwmvui.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzjxahm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvwkvkh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lluasymq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhiffvj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fturwrej.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzpaeza.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2iluxcxrk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmiwlis.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fbphplfv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2llhsnokz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fihnqibt.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nivafmkd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdnkcbn.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfbhokr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjgddre.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2yixongtb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlponwe.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfuafws.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2mumheeqy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ejanhomh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrdtyjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbeqmpn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2oddkikyl.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsguvhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvdzmfo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2nalanzno.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xacpahbv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfzbejk.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yidanofj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyishxg.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwgofwn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgdhkmv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2znxgqwxq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2npjvakys.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wihaljji.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2oaugdcmx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2anygtatj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2lltburgl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrmivna.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmqidnz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xfigbcdk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nkouohit.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2txeenzxl.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcydqyh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqafdes.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yovhbewi.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2muqnykop.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lngvnqik.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mirsyqeu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoetzro.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yksfkuyv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cppzijma.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxbpvsv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvffudxj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lamcntgd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2veuhpkxf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2glcmztpi.html


<!-- 参考信息 -->