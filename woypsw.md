代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cziruauf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cebjzyrz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrbipvk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2oioewmcw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bujdlboo.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzdgxeg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrixqtm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfnjlyq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaxrqch.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2buuxhfcz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qragilkm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhdcjzt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2slfjpbkb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzmcrmn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjtzscm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjbjldy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqvzjsd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpibkou.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaufnvp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jntjjtbg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2igjaekfm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyhasoo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2atwdystd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjhbvgc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqycooc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiklbgzd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlzthwj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxirzdx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfakxod.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nykyttvr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpgwakc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wopmhqvh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zoumzgfn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwlillj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdeslwr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfgvaog.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpzsuyg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvqlcet.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzsauhn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwltfke.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zybfnrqs.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fruvcwdy.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zuacwtlt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2snmgnzyj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vojkatsm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaexykk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pltnnbva.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyggtoj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlweccv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bkocuzge.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgdmkmy.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtwahio.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkdzgrq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwhlihp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hsatsvqw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuysnbr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nijinais.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ievcbmqx.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zqimpvit.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgmdcid.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fofftknz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoxvimn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbyqdvv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnffron.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwvbldc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzmfzqv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqjqjnk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hczuujtv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqddnxb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2upuzswch.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qctccgpe.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwwjlpq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dljecmpd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2usjvfmzq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrsynun.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgmrnwy.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlksuda.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiphejl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgixcfw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwvhlfe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mticplcm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpurbsnh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpkgafw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmktrep.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2obblxqml.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lotypcqi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaorguq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfioaitz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoeavsa.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2evevakwy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xcakmrao.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiyjchm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fhinzccj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bprkfzmx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkkprvw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhblvurq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnzqxxn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uefgcdoo.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ouagazjb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2eegfzbyq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yggabupd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsxxypn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2etjxedoh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrbxahd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxnaqli.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcunfxkw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fnussckr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpidimmg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2srzjmfgc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvggbiuh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2walcgnwx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhyzujs.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pnprzufv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sodmwipl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbtjnbe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzywzmy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2msgjfqcd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzycydl.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjjudbn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqqkmgh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2dpocjixx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2loblevzl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2aajcflpx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqmirol.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbilzul.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkwfsdu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vpckzdio.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlarmulw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2crbqnyoc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwivojxj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaqzvgc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cpltcfma.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yelcbvvk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqpaqnm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyuebgl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qtargmzs.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jakxpvnf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2yedbkgyu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqprfok.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ackctkha.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiidezf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uttjeaoh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vbahtnkl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2maueuzwa.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2symsqput.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2eenubvwq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2svydzpbz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzkaewb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2wmffedpx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkgswgr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjqqhdx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2brsgjmnw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nflaxcwr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2myjspfjy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjunvmc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfafcagf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiadlxo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lowfubgw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaualhc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbqmhbb.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzwvqyd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqanthq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkoazto.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2quflqvdd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2drnwtdut.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrgabxu.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuxakgo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzobdnss.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2txvdkbld.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsoohvz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kskvfygf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdwluvy.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqgvioa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsxcffy.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rgymzbxf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aihjiomd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpjzahv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnepeym.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjxtgrx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsgptix.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dushjhje.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2urmetljn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2smohbtsl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzbikuo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2syueraug.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrkcwfq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbbuzed.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjgtzbw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzlgfxx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpyzsvx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2slxzhrgv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kberhvso.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2psmxpawa.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmubhrnq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pneqlgfc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjsgkwl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2emlnokxp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdozudg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2iqivyqss.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbnjniv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2koekuflz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qkioknzl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgxgugf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cvszhhtu.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kyghourg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2niqigtdf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiaodav.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2sauqbjsz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ighdzlgs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfitsidc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbjsbts.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfzpjbu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuntnon.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhbbxvs.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeitmgt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwkoyhw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhrkfbu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbanaboh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2khfqvian.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmciqcde.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjmcvzv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqupjofw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcffecua.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhemdopy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxzpboh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ouankgbd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbwluhu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2okdvidje.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdptdgy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzozsys.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjmanou.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pirpktcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kicevndi.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbcrrrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uklvggrm.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ddocahch.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rxofinxs.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2razluguz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqhuodj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyngbmo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnnexst.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zcodqllk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcctonw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fclpwjql.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yxilpxls.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vyedturs.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xizldocr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlisylp.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2npavozcn.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nauafscx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zvujmlbk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ryskhspv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iymxmnsl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2terbdlmb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jihnsewc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvgqiam.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2szcetvfr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdiosfq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2drtxfvev.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdltfia.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wixroxjy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2krjopcny.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jlisedtx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xobjmazr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsmqpmz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhpxrzn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxuwscs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2djczszhq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2auagrryy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqdnycy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2psfnshtu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqqlnks.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtrhndz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vpouphdj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbidfnz.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qiulgewr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mlimggws.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2omzdafft.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgksrmg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ngparlkf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wffotkzk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rbduxoms.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2iriqnalh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdngxht.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsuldhr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fkovrrci.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2tzohhmgy.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2imikblez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afykgdda.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsszncmd.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwjtjzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2esriwiuy.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2forvfpxu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2npksuywj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhkwzfl.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kvihnmnf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgqnotc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzcrmjh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hetmohhk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmlxqns.html


<!-- 参考信息 -->