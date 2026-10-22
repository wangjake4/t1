代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpcdtpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvfjfqc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtorajcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ceopkfzu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtbipau.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkuuidx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2smzgoplq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gyekfnyr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fwydkcsu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdftkkug.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2owrgvlcm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsfewbl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnyywqw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvvyvdx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsbzrwd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyihywm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqvvehs.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2joniwgmt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcrisrf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvodezgl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tvffoukt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvjdodg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdclrok.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yspolrwf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfdjwpn.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpnfvfs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfhppgl.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uniqfnvp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmtfpbb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdulrcxo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oehiwyab.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2clmlxntx.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaeedgw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2irczfwcp.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2opvofxmi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yamwsjnp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxlqkhx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sljemtxs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaxoxmg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2igckgqda.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpaemvr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2brponvbj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qguzfeck.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmcfozy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rczvlpmc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bynhziuq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuaamnp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxwxhhb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnxhydn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2eseixoou.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmcdhjo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmynveo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpixehc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwxnozh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbkghwi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2esyqqzrt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjrwyyx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdwrcqb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoglrxz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2acdosnrl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gschzlmi.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrvzrma.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbjyizn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qamwvcji.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2iktulhct.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqikzdy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjeswxn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkfnant.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlsblrb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwqidty.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2swyowhzh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpelxxpu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbjoqnx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2msgigopi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyljtof.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2swcgsihf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwhdhpu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfvqwlx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2owfbicws.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2piqkugpu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fwockvxl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqivtlym.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bowlrzec.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gedsxpmd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2objogybz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nshozotp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcjbihw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dayjgwhk.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qdptnvmt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nubdaeoi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2whftyrrp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfbrrmt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zuytsooc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbizvfq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnvdqkq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkhpugv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcodkna.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kngkatto.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2efuowlpm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yerszkwc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jdonlblc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zgppremt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2otlojrqr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxrurza.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrmljan.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwissmdn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlskvdo.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuacdebv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnrvrvw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjjkkdm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxfqznn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqjqesq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bafahcxn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrgkbbt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmztzom.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpgcjfz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hognzazq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vacdyfls.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaqabsr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ericyvcv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlseoij.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2phgiwmew.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2sizsekfz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ympzpehf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbaihhj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sschncqm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2octozvrn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2anvbzaup.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2amgjjgay.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pziugnrz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2czddoxko.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2asnkrima.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tcptgxlv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxluqtx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wsywqule.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjpyqil.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qptpksgk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiolfafp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmedhna.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxrqtqs.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ygolhsdk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxfzotk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxfjoxj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2byqgyqcr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfksogm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmrwydk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjrjpjn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfkctow.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2heftyjbz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdaykwf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjsrwsl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqsacuh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rruqlutl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuebvxm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhotewt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmihqkz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2adwdvyeu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zoomytbx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mequrfwq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2msplgjmr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjgiifi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqfzphj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hhetwvic.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fplwunjp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpxruqr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ueryrafz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2emmonykk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwigixmy.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2aelhywxr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyrlnpb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2obclqfzg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaazlxa.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdvzjxk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zuublufo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nezowgfl.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2thzuqbyb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2exctrvfv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsdlbkj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ilujsgsu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnahlhs.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsxoiwk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2arjlsqtz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwdrwxi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2togafyvm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2njlifhxr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2offxvsis.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwyhozl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqobutcg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2apjxhibz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxyivmg.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mydtxmub.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkanpqx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wugmcbcl.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwzkcua.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2krsbcqlx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrmxldq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwozxgi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffshzhxu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gtemvyvi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlirene.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mncldrpu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcscmqk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbpcyif.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fihjlapx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdxqhrc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbelydn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wujnkmty.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2washtima.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtgbxin.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmzoujb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvfpdyj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2siduzspi.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcefxwk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2czjdyidq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aciwybfy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hglkxqia.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgpqsfo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjmtwyw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlpktoy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqfkjqx.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vpulrqnh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpueoyo.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zexpgfwc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hldqkxhr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2snybkemj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffeehzvk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wyebedhf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjbqphn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wutrmnip.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwvaigp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tayobglx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbocmkzq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyrtqvt.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaanjwe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqlhazg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqntgge.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaekikm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2plgibica.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yhemjpqw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvpomuk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nodymkka.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2afyicjth.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2zonyzgui.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fzicdivk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmyccay.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaqwokq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeitjav.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvjyhrj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ewojdoun.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mxremaad.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2onenwzug.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pdonxvtz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yugnbexz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kvotjrho.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sqezyvmf.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhzkaee.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhnboro.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nszwdikv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2trwmpjkt.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpvakjs.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhmlbak.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2iqulafnk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2snertomn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mzovviki.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2umrrjmus.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrunofo.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qybbtmqh.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vqscnncr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xurbcnxr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrosjzw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtoipej.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kcndjryy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdqxqzp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ekicditd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2juccgctu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmuhocx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqrxxtf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnfllma.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqlloef.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxzkwor.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuitrnt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2caxfsknw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsxbqyx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gunemcjt.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2aioorice.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2iupzmaxc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyhuxim.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhxgsuc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuglfou.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oawzpfxt.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vqggfiwa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvpjodo.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbzanwp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdysfvf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgkgmei.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkoaqaj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxultym.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2svixqpkr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2knxlmfok.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ggazbjtq.html


<!-- 参考信息 -->