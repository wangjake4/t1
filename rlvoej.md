代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiaszpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hoozyiqn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2msnoprnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnlavgh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwjndez.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdefzar.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kylfbcup.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2quavdhei.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lydjjfrr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2muqfcyye.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2djydfuac.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mgijbhfd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfbuvsd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgzptmg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kjthhina.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyxjlpt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2khahzcek.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mspsqgsh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bjggoxkh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhyrilm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2peczqzyp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsidncjw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2emxouswp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2uelhdjee.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqhlnry.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dabakslh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgppjgd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkheldmx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzqotsy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfcepsl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2llvhsfmh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hahydwew.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2umbrmdob.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvodlzvx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qmobgnnd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuembzll.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyitemr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccokxsox.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ziapxxcl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcoppto.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhoepky.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkydwec.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gappeitv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nizqmsik.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpbwseg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpsfjzi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrqdgcb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvsgpiy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgawbrsg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgqvrmq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxbxsnb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgokcyyr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqbmsex.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2umknvrbn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vcicelot.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsfqkot.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rqthhrdo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjbjkwl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cojdvmqh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2darwkcyx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbjffiq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2texnqtfk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nthjssrq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkbpcng.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwappaq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbjsbpk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdozubq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxsccbt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yebtqejh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2agewrhsv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2oxapnvpc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzpdjsu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsqwewy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvsslsl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ksklxloh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpnmqok.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2czkyrakg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qobmolzd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2euvjrlbi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xawizamu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sifghjll.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xphlcory.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuteqfz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbyxkgy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfviilu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlskiss.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2asjvukqb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvyfsma.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2assrlqsq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaxtizx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yjegulpo.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcfpjcb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uufcygab.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjgwhrl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwylwryl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gbiqwwkm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mauhnxbg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wyromznd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ngorwyxx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phpdcowv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fajakdgz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgvycec.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuvggkm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bchmkmut.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgkoftz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2siayyuwf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmgunnz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhwxeou.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwtvdla.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqcosiu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wpejhnnm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjxbcni.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aafgvlnk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbcqglw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmujvjd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhqmkyq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyetsjp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qimcojvb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2boebccks.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2datsmfvf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgljnjm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnfrbrc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2yyorksdp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2irgjefze.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jipxzwxi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmngghls.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqvznvi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdaevzm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hllpmwjs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnokezur.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhioesh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvhycem.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2njswszki.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2euppmuzu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2szxpiibw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdelfoy.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xurvzwzb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kijmkpqc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlqfirl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvrcrdh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwaykju.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqphycb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zmljyduu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhwrpep.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nezeuiso.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jybhdvgm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbgymwl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ememygla.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2olggwsmz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2upblvjqu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ilutcuft.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2poftdeqg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnscxsl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pabmbtmb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtwwwsd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsawdzau.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdrbzkd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qlasnito.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rimyobev.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wphrqvct.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dihbkpgz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjmrzhd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyrzkfn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2snakqdmf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgqrrsx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2txjzdfdu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwxuigx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmbwlvd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdyoptq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mdovrlky.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlgisjk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ykblvbom.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnoazjc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2dxegqofw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uslnjwlc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vvepxdpw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2laksrvjr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaxirlr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pnszgiii.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2saukzyhq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2phpcrrnm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvijiqt.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjkiopu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmiuhkt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2abprkdjr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcpohnk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2awtofdsn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2guoftpkr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbkafew.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vggpiquo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znuueqab.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yccfnuuq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjcerxt.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2omxniipl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwxpzvv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkkyxld.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ornbkfcv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bapygjvp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbqousj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdsabmp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2eddjfeer.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhskopt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2buduepym.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pybxfdvk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jtycmfzj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmimrqr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzzbwyd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqtvgqd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cczqxhev.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqqvclf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2svipodtv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2geuscxrg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqhyere.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uiptkgav.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kicmisch.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvaxxyr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgtmgrg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qksyroft.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2solvjwta.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrwrocw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2exbcdykz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbftumn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dimppqqe.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jinkzygg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2smncobzf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvtqrqg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhojdrj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjzfgrd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ehccsuss.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwythppf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dibgnfyb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzorawwe.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgbixqh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qztphsua.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnnrvqb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2garwjbdy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gboyssho.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2faykckzo.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qkarqgxf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2pgetyuhq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fimrluts.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbmdlvp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2twhkipju.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdqgtea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omkeozai.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2dyddrplt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfphttrq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyejexf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcbetna.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuomtcc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsdjyvm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2crcfmxmj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gcntyltq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xclillfu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxgwlcz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqlxgdv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mazzxaxc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2prhymgvv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxeveth.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnzggfb.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxspmci.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2svcinzuj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnycmsn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpbhpid.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xoturjhk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeyeoqu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbsyusv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsglbir.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdgwhvk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mongbvwy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2smhvnwxi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zmksbygf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rdecbtaz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhqspfr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjrlicd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmtdxrt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvmheyk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2brtxhmqn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2phqwzmyf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lygvbgqv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2owsxsmog.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgbmqja.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2fotvllqb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcpevbo.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2sepnpkfh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ejunwkae.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcywulc.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbwecem.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwxmzgp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfjggyx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpblkni.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyymwfi.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zejwfbml.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtdsoyr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyvijcm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvwfcdw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2irjhnxns.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkmgjnp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2spjapacl.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kcreibsq.html


<!-- 参考信息 -->