代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyxjdkq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2auwxkshs.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gfizysrj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvnpmdp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzvffbk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfkvrgb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgtmakb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2laxqvxng.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnaobtj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzioeih.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vohxszgi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaqdlam.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjpzcze.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcpzssn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rozkppds.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoigupw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xujjixii.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2efiqynoc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpgbntl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cipubcmo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiaekhk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqshzjkh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxyjwan.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lutmrwzs.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2phuhcsrx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2avhdfndh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrhsolw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuciylll.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dlprxtri.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aldmkkxk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwrcyhq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsehleo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2glduzmjs.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hjavotha.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwfxdca.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnpxhrb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edeepbwl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jinnqmxm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wddljqoq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yciuoosg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgvndea.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkoaeql.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdpggtx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mribcise.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2oargsecw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2uivjkejt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsaoysk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2byrgbcpt.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwtkbkw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2sslwrbpy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tutzczsa.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yajwpfxg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuhfmmv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwrzwgh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2duozfdss.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wogahvdu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tgemxnts.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zadkthac.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dggqsxex.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoewaag.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyaauzs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qriclbiz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsmznao.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzbpiih.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyimoyt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsdzgyx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpklogi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2sptxuszs.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2crajflgc.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjjkyhr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fklqvosw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsuoxfu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2plqlmmof.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmrbqcz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2brwcnjgu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2huigfgvp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fzphjmek.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsotgds.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpunxvv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iakjpefa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qytuosww.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daivqkxy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eijxyliw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbgomoa.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpzjsch.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgkxbck.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dokjgfmj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nehoavxz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqkkoxj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmxxiti.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2doashefa.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrnqsys.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpixkjj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qubnebgp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzmzzce.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzbpemd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdyebii.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2khyjqyev.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjamjbb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2odhycegl.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vttyznvd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwzaweg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpelity.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sifobdjp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eekfzxde.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2unnnhioi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2haupoemn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bokuasol.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2loeerqqe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxswjswa.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2cfofrdja.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnvbnuc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyzcqjy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjxeqrw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaozssq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggimpmng.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnqyrdc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnysrphq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2birmmrln.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsskous.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpxsdqq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgwriyn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2euthdomp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxicyqng.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmlyhjv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pktnlrqh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwlqgmo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwultgrq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mboerbwe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2domqbfdx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2blkktjcv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkonujw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtphwva.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjqbrdb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bpanxzba.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgjqoil.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2anytgqhm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dommtndz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jybbzcaf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fifxhaoi.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkyujhd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2usjzrlpv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2huyfjzww.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbibbupb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2udacimqg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzvekfm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoxqerd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgdksrk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyvytya.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2baencsxu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kicqwxjo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2utgzdwej.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcmvhtp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2tapovugi.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgyzlim.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2epzledrg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpmlghe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qrozwuwg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcqioxu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfizogmu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2uljgtivi.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeqczrq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrtxhhd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kfehkbpa.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsdggmz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2raflvugc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pplcxdqt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvopsppt.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2chinfrlb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhxgpqp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jxleoeqe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhgdzzk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hawhfwnu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wofhbgbe.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmrduek.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpkqits.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ituyzaqw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdeecnu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpksdbu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2obhniytk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqticad.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2grmfbvdo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpjvzri.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edulgxxy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdukvli.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqxqzxg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqhfcrv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yixceqrb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtyqqiq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrhumcj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2htdgsnef.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlqexsi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2unabawrz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ertonuew.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cptugerw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgdjvfd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeqejuf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgpcvuk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnnzqpl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkursjm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2grjhorug.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xbedkaut.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkythax.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrgtiri.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2waptqzmw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cejotnpq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsfxxqv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzlukcu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kugvkndy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvawvhxa.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fzulhgux.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmmmjwc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2okcddnsz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2sssdfccj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrtwpqz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqskldth.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vystljil.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2luugcjbo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zywbqcep.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtbukoj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2frvikuux.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2asrfilio.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgovsai.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dscsvawi.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrjxuxs.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuldetl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2usdejane.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cknvsvna.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2atpjqyzj.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2smhlckfz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuaszvt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2tljxtgpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlihjboj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2oryfzqfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqioswm.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2cperuwxs.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mglralak.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iypqrarn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmukhsg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2soabpifr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lywtooym.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2buditmvc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2baddrgzx.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcjpern.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2adqqudgg.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2egtwxekc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pveatldl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnjujxa.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrmewku.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2enciscuy.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sflfrzvd.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrrwmga.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzayfjs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lxippbac.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ovubkqug.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fxukfuqb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvdjifn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iqousrvm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sujdanai.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fuagukom.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lbczifok.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaqueog.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xwduuvvb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2idpdurbw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqanpww.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuzxica.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2phmrulii.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaxuhsq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2brxwfunx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhxhxnp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2korndhmo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkdodvv.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmdzbor.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvdevqd.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2aiapsnbf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhxtpwg.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zafyqvit.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xtybuush.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfxdcch.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lhplbyjz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gewpezoc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlgtihx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2urspchbg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkdyzvw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuatvud.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcpplvr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2teuchrxn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2edhhzmaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udufbvdk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2exdihizw.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2igynpgip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrloqha.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2siwtmuku.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwvqbdt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvroske.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgsfqgk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hauekthr.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xohdhkyc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wmunzlza.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzitonn.html


<!-- 参考信息 -->