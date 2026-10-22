代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2oujluqnl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fojjrbtb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgfyacv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwrdefw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wcclaboa.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jknyfnoc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2goachlhw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2caivqyxk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bywjoalc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgqkmjp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiiazbz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nccghsrm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2etubyswi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeubiwd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhxcdgs.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgxdlyn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aldferyy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2inyykurl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2taoqmxzp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2iibwpyfw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2scmejtcr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tviuhlyg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzzjtgc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbynfyy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2swttnjqf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcxgkuf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bumzfeay.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2czeqidva.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdcsjdg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjetaarb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmxogeb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2whhxndqu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qzczezou.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jjawxcuo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjuuddj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2iexbruev.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrtgtwc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeayjut.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2weixfutz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bosqtjwt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2npaxniip.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfdeotn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrshofx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsvkbee.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvgivbn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cgewbxbw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qphunaon.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnpobed.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrtmiit.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuujbqp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nusrfzij.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjktgxh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gjweptwn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdzcifj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2chdyrjvw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vufupulo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2esgvlwto.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgfzbhh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsbbdxa.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2iogictnz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fduklejt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2yidwnhug.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtxfyru.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2idmcexpi.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2smaudcrj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2arzwguja.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jenmzqbz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fjthpftf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjdkeki.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmskbpzi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xbltnece.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcelqcz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiyhicb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvhmbfh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvewaug.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiarooq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2adqxsjoj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tetufyfi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wugunqsm.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2njnfvwpa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfwgcbp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpygplhk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yxykdrkj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdnpgox.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mewnyjio.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeapqhn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcpxvjv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrhwjhm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rorgawke.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjsmvpd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjwunjc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyjhqil.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyueyam.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuiegkl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfdnndb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ethaaelq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoypxyn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2abkpqcsv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ehylxapa.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qewtkolc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2beidurvc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yluydxhe.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xegwxrkk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgqwgoc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hqumltdq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cekhfgdt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vvurbssr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iighcldf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgusefv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqpbihj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2apqqyowh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlgqmkj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zemibpsr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eprjwamg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2crmnfnqu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwktsrpl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bmduldfi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dndstnwi.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqubzov.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxbcxiq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nojbelqm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsratstd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2llttrpvi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqxxcxt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2blhfgeff.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bputjkdy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyykezy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxpympc.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvducpo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxihsyz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2haayydag.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjrunas.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrxooaa.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeaghua.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjjdyde.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwdifmb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnjtiyc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2onnsxoiv.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzxdifd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kutrxvgm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdkaglq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hmztuqqr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrndvhb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvdkleu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoeqhzn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxwrjov.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ewntcrrj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gypjwglh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2okbnuowk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcodqyp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fueofzvc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qduholgn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dptecbkp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmpvniq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hgismpne.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzzrbep.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdfhoqq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgwzzyt.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2suanzktp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtofixu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2namowgwl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2iftyidsj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnnrqbm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2blqjnuts.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzdsenc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrqnpyw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkxjztl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsrsbjb.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyaujgr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvegkvy.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2svchrvgp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtnpnny.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yssdatht.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcabcel.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qequsaqe.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvcfkpb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpayixn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2brohdmmx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwbfkav.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oonizgaw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2sanhvhew.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eaytbrsz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcyspms.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfnpzme.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtdyojv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhlsiqp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oblapfpv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxkcxhp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaewqap.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dghrfjse.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfmvnnr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpeidqa.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2voothqdo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgczfyer.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kvclmzyz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyurota.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxckrai.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpohijwj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mffysuhh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hiycymhj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dohrpcey.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dccxfguc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvvrlke.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaigczz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2eiazbsog.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbzdxyx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sewvhwpq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nkivwyng.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdkuhka.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqtxtbn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfkukvk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rczcbfsa.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dkghlwch.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ollpfakk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2sbopcejj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnnkijx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ezihxxdt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrthjmh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oifuobqn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmwmsnl.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmfiycp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlqxvib.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xeidbixx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvqlioz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdwvzei.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnyyzqj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ogljrxpm.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2blzepvba.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxiwkao.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2kowhzvgh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qoadzltu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2evoojhjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xswaquxl.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcfxbop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wivgndrn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuayoec.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlbnwgp.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyjrecc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uoikmbgz.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fvquvsxc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ksudqauw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eruueljn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oluhjgcw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmtfdwi.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbaasid.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdkjkdk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkrtjzp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uzszhjjd.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlzeyml.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nixmxrif.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbucrgf.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcewuff.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnwnbkq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2woeahzln.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eculcwvz.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2qudwajmk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcbcpbp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yodjlszg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmwifth.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2syqdkgqg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zqslpmyl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvlvbvg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hunflzgv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyisoxd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtkrift.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlaelvg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qssubfhd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yiazctlj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2seyaqkjw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nksupylb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjzckuw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnwpkui.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnqwcvb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvmacic.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkdnomh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhnsqjl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxrgbqj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lqegeeyz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkkxnyu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jbufbxng.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzdzqgp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxnxjnc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ofydfttr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ycksbfsh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2qslzzops.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2uplomnxt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkavkqp.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqkjgwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2losypahk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuagnxgj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhnsoqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2woepnilj.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzrhilb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiffuzm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtyuhup.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2meqojtmk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhmxsxy.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2faaxybeg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkithxh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2lajesjaz.html


<!-- 参考信息 -->