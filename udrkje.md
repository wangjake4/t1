代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxtyxzt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2llhrxjch.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uskwhqgg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjgotvp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2idlawapy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbglqfvj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xejyniec.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyvzrrs.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeoqail.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uztdfhti.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxcvyye.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmactes.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqwnhtv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulozxvms.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnadqld.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoaajrp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrdeyuz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbkkxdi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxvzamz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zolgdkcv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mfchwmvv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrttkwdu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mecckheq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyinpnn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2klbcejzp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzdnlpf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvhwsav.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zthhkyyg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xndrvoii.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwjisep.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zajweevl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkuptwe.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ygozmwme.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2itkcwsuh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyojops.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbelhiu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkqabuh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2icpnxxpu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnohkpk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ercgyiav.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2efprditj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2idydnvvp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwptuqw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzjgovq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imfozyta.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxdwqfu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkkvnel.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzkyttk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhokyot.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmphyyim.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwqxxcx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxejpasm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2egqmzbiy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeyzxpo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzcujsf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsjtzhx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qjygonmn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdqteki.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eicgxylo.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pffcykxw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qapxvexo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2youtoede.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ltduhquw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeurwnp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xorzossa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbbkdwy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jevpuqku.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdgfnqs.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2cevffghy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbxfayx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zarqrflg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dutpwurq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nzskfqiv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwhtdee.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhsxzhu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cprtslzk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2stbbbdhr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpoxzrlh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxusfuj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2piwnlmgv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jikpiout.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dltqmwvs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoyckfg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eglpuloo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgrcgtp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfmnmjp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hssdqgwn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqudhlrl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbnyixr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbjrhpt.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlmhvxg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoqrmxo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2whxkveun.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlbdjxy.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qgllavmb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkumifq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlbhumu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rtltoyzj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nobyqnqw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbspgdwv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmebfeu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rawswypg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pemaifiq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhbheoa.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbisjud.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2pssjhjqk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdnhgnc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhtsekb.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2suneerki.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tozdwznv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeyllkd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcflhtvx.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2edidydja.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpiwuow.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2foxaakfa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ausgpdib.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfcgxoc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuurdlcq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqiaegm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2avfbkrci.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2robdbkqm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2owonknds.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ppinyugt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xszhqrqz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjehxzd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2htauhqps.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2daukcaij.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2uorexhfx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2svplbvyy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxtiqrp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2oinhalnv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrftxka.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfpexlu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nllhhipe.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmznhjb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkryifl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rczapbno.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2saknzszv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2irsgfhro.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ucorqhbm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgemqaj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfelljxh.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrtotlx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2prffaxfi.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfnwrbf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxrudyo.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2okhwupss.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2prtpzghq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xopuvfwd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtktdtw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwzzydd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2quskxvmi.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hxetxytx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2buooeruh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kliqjjrs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfyodgy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xofiauvq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlhnjhf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzxbsym.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2aagehgdt.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwhdnwv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2dnykwewb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdrstre.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rezgqizn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rujjqmnd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2egjcnbsk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfirdfv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2naydmjih.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaldjil.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wykgrfkg.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtwzucd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2cyylmbii.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ewncyvgd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlzzraf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgiojdb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjoflol.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqcmshc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqucrtt.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mulcsioz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqovesf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgahidj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2pgohtkoa.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wpppcikq.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2suxhvwju.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ntemomaw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhqqnpt.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxyjoll.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oygifzzl.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2styqjsrc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2irhkkjpm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkwzkcp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okypndre.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfeaqzp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbriibop.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oyewyhwk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoosmik.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2orraqezd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gkguxwjt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxintjs.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2upldoieb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdhrzwj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdukeicb.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ispxionf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2btuzklud.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdtocuo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdbgkag.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2whbyoyhn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlpwcxr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjlgozq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zijzkejw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eouvsxab.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hwylmahy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlviimm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqvzgpt.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuutnihk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhijjol.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pvghslvw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnzbqgb.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kueozqhr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2upxowril.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdmirwp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdyjxwo.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rcajipmf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoexckp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlwoksw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzhfkzc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xffcemis.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxyvzpy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyadszv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrvnvus.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jibpvtmp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npzzmqys.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrxkrgh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2epqxxyfn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnkeqef.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2uiawufzz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbwcboe.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvxstdw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvobmsah.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmtvbmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blkyczmn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cooountf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxwugsu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdltxoz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgnnvkt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjhqbwt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sdncxktd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrfehip.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2buxxxynw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tgudczzz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtyzmgg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqwnekl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2izbfwgrb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2raefynls.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnfuufy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkwwtmq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nswaegul.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpkncpw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzfpolf.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2puirliox.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jxktpnlg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uujgreli.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzuijhy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbbixms.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sylgnlln.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tlotnjwc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yznufbdm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbudbdv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yvazkidf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2udzwvcjh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxomylc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfvyewu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkittul.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zsewuass.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bathxllv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpkyduu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dshhkldl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2znotycjh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2npycmnud.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rujuesgm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvoihls.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiqtnzt.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbtalsx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmoodeu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2geqczbhm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fpenaywp.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ycogkgvq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmfuxlz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2yigvoejz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nphgakiy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hufmppep.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2iggpeabn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2urczkbrg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvtfgfe.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2rvilyujk.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmecqlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcwsbud.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhqbykg.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfthmis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzlebzp.html


<!-- 参考信息 -->