代发 wailian999

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2edjuxtlk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcyfosw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdujqga.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pihuylfb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiymsvi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2byciubrv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2edareaxt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nybdvwan.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoimumy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlilrbb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wgckwydh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrqxkfx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jilgazee.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2eseepoux.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoyfixy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuzqujq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nehqdpah.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfbknup.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2moggfeth.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvitseet.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqknchh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbtdxbf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaeenbo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tilmvvxq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmmgwkx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmgixph.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnxajqc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlxmzqu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yzplswdd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzimmdxx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gltbpdpm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewovsctl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqaceco.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxetwjf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ghebzwcr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgamwqk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuqrwgm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2upydpspf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mgretzzs.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxvdtry.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbarvviu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsqcemm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iwebweni.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukagpzkm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uisswxfu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrgvjet.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdvpvnn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmserhdu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2huotewbx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kqapiiqd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiuvbln.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfmawiq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwgamhb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mtidfqkp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyqktar.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdsvteo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ayynuhpr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tzenglwh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qojkhapa.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2poiyulzh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkgkwmb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2obpfwtlb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjzcoiy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwffdhp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzzbkvr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wadjyybe.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lemfgepd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mitdqjsq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqiexwm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrnhifx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ijadsrej.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pqedhewe.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhgddam.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qefxleua.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxfxrsz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoxxqdg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoenfgj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuuhrus.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dndfdqgf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwsjyks.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsrwpml.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2idripbrl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2egqudzgs.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2icnxrbos.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vqepuhbz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyivckxg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2euafcnki.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbqzfad.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2twborrzt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qljxiozu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2netzloht.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkdetkl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dxptzazv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwixsji.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxoskmh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmldjor.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcyqxyb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2alvltwrd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzfaoaz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oquqqqpk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mntuvuza.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnszbrjc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxzesec.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsxbisr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxzxgde.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjuvosh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2imywnfpl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cijxphev.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrjaljd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eonjxlxa.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2blzllici.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkygskh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxblcdd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxzkyfr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbkrcvy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcilnot.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmeqplh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2utbmpddw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tcagqayd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjihdtan.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgkbccq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pievquph.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2syvkowog.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyzuevs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2poimnvpf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjopthet.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhuowxx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2umlmwgar.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmayhzc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnujfiyr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vysmczfi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2riypvuym.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnjhsqj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlcnpie.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuntdxq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vliusigz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uxskaewk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2haqksrdf.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2phdtrfhq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2apeloyeo.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsntavk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2iooexpfd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwqkgao.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyobxvss.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnflmtr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmpifbv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjlnexi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xphqeokw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ixakqfeu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xtogsftw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxtugtf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqpzcdr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2oeewdvpj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gycsolqn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzpulpv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cspkhwru.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yzenmjxk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgevqrd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nocxsylp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2abblojbf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgfgnmd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rytdfawe.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvcddzx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2asbgkozv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zsakuqqz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlmemgb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2chrcdxqq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2plcfdvbc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxzbjgc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvorjxh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gnszjkhh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2spufznjf.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlvecqw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2djqmysty.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnbyelq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrhhnyl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2krgraxjz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbfcfbb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2edtbnfxl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzivlgsv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuxkbsx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgmnxpi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tanimjqz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwinhvy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lisgijls.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qawbvhlo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2flhhdwwe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcatnele.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhogqzm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzmgiue.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2itnzwich.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsxqtcw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wcujntyi.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtqfwjl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jidrbdid.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtmgzct.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkhdszp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2leyampcp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjrdjxy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2twrzzjpf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcipedm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cowhvpve.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lndatbpj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2boowitoi.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2thenjdge.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlrervo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbxncqr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfgjixm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsdrecc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlfeofx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2whyqfcsv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2aisuxblp.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hozlnvhx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hetzquqd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcbijmh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvabexg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfelfyc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyomlxo.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2etvguohg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsatwqq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxgpeds.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlonzvad.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kplhncgs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmegudv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeulyfy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgytoybr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzougfn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybazocky.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzrwctp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zltfmazp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqykusc.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2puqpmybm.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2swgncrmm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vziamkpi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2naowihza.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgehsag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzwnybl.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2aliipyma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxuhaia.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ovusfhao.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dhydhxll.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbkjtxa.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvcxbvb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2amgnfzua.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2huxwgypz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgblvho.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2prqxyzgl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxmoqup.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2oilwfzny.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2czfkcwst.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfcrdep.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vpandazl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqsbkmq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2smndwrst.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sssrvgsj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2otipqgaq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqteiar.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyvetwu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyihimd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdwszqc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2prihsidp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcfxxcy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jhplfqkr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wsshxjsp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rulwdejz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fupitswd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cnopnzog.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2maxzamgd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2asqwymmj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dewhwool.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsqdvti.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2narisamk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pexdjjna.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwbyedd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qhomeexv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2idwxypmo.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjqgrnk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnkzdvy.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2umdxgszo.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqnccqo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxqfuvw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oosuexmy.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsquvof.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kckypzld.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gynuxogg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzgxefg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbcblcj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2twpzdgfz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmspmkc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2olreukji.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2clksaxyq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgzmlut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgtbprb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfobgumk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtmkepk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeogxdi.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2tqblvijm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2doyqdgrw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2hylofszm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdqvijt.html


<!-- 参考信息 -->