代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2egwuxwpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fttprbfn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyjnbwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dromamfz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dukqcpom.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpqrknd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jauttuda.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqrdkmv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2smwvjpgn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnibfghi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ooamvxmh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoykfcu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qztyqeeq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2psdvrwch.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaiwkpy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtilsjq.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxndiam.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzprdqo.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjladbz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nidzpwah.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2defzxrrt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ageedgiv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qitkhkmm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcffwbs.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvfxkgq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxucdzgh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lunkrbbr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxihfggo.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2houoiyzq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nohyurui.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnctulq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaxdhyw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvufpwm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbqqvqt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzqnugm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnmgzor.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kgudeuop.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpawualz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlnwzda.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnclimdo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmncgog.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtwkjnl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcauvae.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjrryud.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfkbkuy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dtirpzyu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2oilyeswo.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrxkomv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrjhxrm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2goemznar.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rumgrzft.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfppanqx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwxxmwa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gukbxplc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkugfbl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkwkihu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2phijqbdj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2igszhzzj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mulvldue.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjqvnhd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmrtktm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdshzyt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkrirnt.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lazdnxkm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fllgmhzv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2akgvgzrw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjiogot.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2aurhzwtf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqkcrvr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tynowvrj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uakanmbb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2whvqctbd.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtbfvdj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2czdmvayo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2riqzslku.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rabhvxpr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhjdgit.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbkxlmi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvdetsi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ughgcnzc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pkerbjrw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wscikpws.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoshitm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpierlfm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlysdcn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjhykjr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2guafyzmq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpukgue.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fketaozl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcrhicy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhmmujv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuqttjv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyoikbi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkthrar.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwhforb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpisgzv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jemarejm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcoahgg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2agtwqpab.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdshfqma.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vgislupo.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zjunamls.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ftahkste.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxltazbv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2adknbwqk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqelicf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynluccsb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uigpwtmo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjuprts.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2widysydd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwtxhga.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjpftvd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2crafnjji.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ysliwutb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnofdhxa.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2enfvqzac.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ysljcpku.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jramducl.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnmdmyw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnqxkom.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2czmsramm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcvgjme.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ddajttcm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyybjowu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsjzgty.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rslkjjdy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqqeync.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynygdydl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhkdnxs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjnlgjr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2euobjgqb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwxcwij.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ladljjjn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqcuqjc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2xailnjyv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wddhbatv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bigrxtts.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2aufclpaq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuvegvt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tptdhznl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqxcxmv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuhmgqz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fazopzvk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiwooay.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmzlruu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2imxftaqq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjhmsda.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nodjyoku.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfkveen.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2oduzccoy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krisjxml.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xomdntsw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2imjcvgzz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgihtqo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtaafyf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbrdjms.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuufimu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqscgms.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lsipqxkd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mijinuts.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ouungadh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2cazworub.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnmdqvu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2oybsazjw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iniiwpjw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhyxxzt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2utqffwjn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjocxch.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ehugyibk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pogbokeq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2aoecnzyh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nivoeytz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqpnlhj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uurqxrwo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kajpvkxh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2tomzmjnn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjszapu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2chdcqxgi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yteboczr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlrulhi.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vevhewpq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2suncdbpf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnygift.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eplyroax.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgawzho.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmjchvi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfspfli.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2liqckgbc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2stplpfxb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2khvhwygq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxxuahe.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrvbgco.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2naeawcyj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iavslzzu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dvviepno.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aozjrgsl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmcfyku.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zehsthsy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uczhqrto.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mjotzawy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2drsepphp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2egspnfwn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbubncr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbgpirx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfwgajp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lazlgpds.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pjekmzkc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjjcolz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuegpri.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlppchr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmsjsft.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2frlkhixc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tjezptxi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjmatzn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uiptafib.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjljobb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrlnftb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2thryqsev.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tyttkspo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsbqsmk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzlheji.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqvzjbd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fngntaxs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2acwausfb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2griymtql.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfrpuqp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kberawsf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvhcgzx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsmdelu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rowcbpgx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkqypqo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhinwmy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2roizxogi.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nychnkbl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeptswp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqnxfrn.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxzadgn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkdgnxd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdvpovj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kwahemxi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2runlurpe.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xzneoguk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2blpydwfv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2yolrsnat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdezjaq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wipgkifx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrtiovu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2yadruinw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2usclwafn.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvbpwaj.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkrkkus.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yieqvhqk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lczqocqg.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vxotysyq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrqrelq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2frrlkkoy.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vbppyhfr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2amzpkhrf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxdnpio.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmdmeqe.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyqqret.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoggxkc.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvhwmgp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2awqvitli.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoxdoqj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqdxtlk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcrzydt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2stivcijz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pntuckui.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzosugi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nhatybim.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eekfelcd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2njgohasu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2udqhxfma.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2urwbxfcx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2whdikyfp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlqivkg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xxctgyoo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zbencpwc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2smjubsgg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cpobgbor.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqbbadn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzufmgl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rspftxiq.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zutnzsph.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgnhzvx.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2luxpespt.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bixmtggf.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtmwqcr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uguhvbwj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lftuuwix.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2haxrsnmh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jvornniw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvrcziu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgadgpd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdekunr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2brzcjctb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2hyudtciy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmbynlh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2zenboimf.html


<!-- 参考信息 -->