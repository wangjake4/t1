代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ummwbtzb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yxevtpzg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcrmxag.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ieouxftw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2iujpyujq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdfbaid.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlepacf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmqwwrl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2oresklnp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiczirnj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaokxup.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrsgcvd.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwbwarg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwgphjx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2putxkiwv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqtbolc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fatehvds.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuiwepy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqlhxlk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxzaoad.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhyqdpz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekslowfy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsixulh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqsvegx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpqevkk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwrjgsy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rngrpzbs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlepjbde.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2aphabxed.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeowaqj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdhhqcg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tywmarvg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzecmuu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hnepvlgk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2suiqsrjp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2byynatro.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lixmfhdn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vltbxqra.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lljszxhh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2udkobiaq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bgflvlog.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2idqwthaj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fejvxswc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkwjqym.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrsakud.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yiffoimx.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfzckqw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xeocwgbi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nxulkyvb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2otxczfxm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzpqfcs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hokjkzwl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwdxmly.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkimurk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhgsrup.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgqvsjn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kraritac.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuejdpox.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2otsfpwkd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2shebtnov.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2iowhqtzg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2yydwqttw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xijtsgoy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjhwoto.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2saqnxmgq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnihchv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqnhbnj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2chhdxxhk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjjrxvh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2eggrliuu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2smdrbeln.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmodjmtf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xojgrolj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbpogmc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsdzkyp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2icrdsnvw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2unpvthcm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkhdqld.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkqcazx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jekgnpgf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oanqrgoh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmhgaut.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cixzzlnl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2flftdwoh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cphngjdy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yhilrmnl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxlzwbw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgxzkqs.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zdujygty.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpuicgv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrtzpzr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlahfnb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yksggkaf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2iarihjml.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkciukzv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdrdtgo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeblual.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgbzuid.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmonenq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wprojtpn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxujexh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvclumq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2supklesp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hchadcqb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjbibud.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cosvfbzz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfiylml.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqprezlu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oevoqmba.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2olpxwcdc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnosqgl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mezbiyad.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gypvgpkb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnombfmd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fszgiswg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2slbvpkrm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jwehqmve.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjjcrew.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nnforrtz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2klrltviz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwlzkeh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvguclq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzzttpw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2blqwdfzl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bfysjaaa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2riymmoli.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2heogawxt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzgprzr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cvixylwr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iybrxeyz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjsdocr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrnnnug.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmatynf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoumeuco.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2goxofnjm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ssatccsj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtjkxnp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbrsgvb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2euevtmyz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzbjmrm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgdefif.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hchofxjd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsqpsod.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tivaxsuh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwebbnd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyfdsco.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhrredp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhfbenw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gscejpqx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvpdwud.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wajztrxb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxujgaa.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gviepwpy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbkbdld.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xemurgnw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsntjqn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2opvhbufp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2aylxqtbg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vieprcso.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgscyme.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnxkmpv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2olmncaid.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2trarevzh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmkuiqb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqarhrbe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2malxjldd.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxicozd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxgsscs.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2baawzcet.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhgrmfb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvvdqqr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlwhpjb.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrbrxly.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2roudxqkf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2abymbxgx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxufqzjr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kutqqmhm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqeyeqg.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaijnwi.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2maqercez.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cjreudso.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2txjkuyza.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzawfdj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2laboanni.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2itmkaarf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxooacs.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iafmceqs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2iutkefbz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2azjvfhax.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eadzszch.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cseefmyv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyumucgb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ulscahox.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgsczpe.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdapyiz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kscohvdv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzqtxlp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgftxrr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hglmophf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsicdci.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2amswhhsc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbgjrlq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aktnaujq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzxfjru.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bebcjhzu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2snfmfyim.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhtkhbe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiycryf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyyyryt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2okzzcjvx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiufjth.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fkunnruu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfuvjxx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnhignb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2frjyrzbn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvqndvq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2autbztzs.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsycchi.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2peiadinn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaobodg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mojmtsih.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zntnnyvx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjpuxiw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eiziwsof.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiafskx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjrezse.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qqahamay.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuywajd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gmguoaan.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnxezky.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwfdeff.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2yixgmwcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jctvfohg.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2geebffdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbubqocr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfmzjmf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqorbpk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2njhnoaqw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oevarsgf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkkodyi.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpmhmgm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pyshdmpr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nvepraex.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsdyakt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2iewrullt.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbuogtq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpxapuf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tflinacw.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzzzntk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2efkerdut.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjdtvpy.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oiguarrm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uxniefiw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rkabaqre.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ngofebtd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ulslfamn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcasrxe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwhivlb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uziwfctk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhtwlaq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2nxppkgun.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jpawzkuj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkpovim.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2afwdpjsd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2owjtsuob.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbpzntl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyudbce.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwohdng.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkewffb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dxptxaxv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2lulbwydf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeowqsu.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jwljrqsw.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjampve.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2iffehqid.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqwakfo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbsyrxg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iancnmjl.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lzamlclq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmgnnfv.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxfgmtu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzftdxi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkkgble.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsddjyg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmufkym.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyomhoi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zgystjee.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhokngz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyrvaff.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2itgibiop.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2fymhfclw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzskldt.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsensnb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2aboktvxg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2mlolwtoi.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ugggobjg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsmdxdv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2yinfxigs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2autvncee.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxgtxmv.html


<!-- 参考信息 -->