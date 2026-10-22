代发 wailian999

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnhhvgt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbllgad.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nltopnsr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zchvavmh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sojvdldr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkclcrc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wthcosuq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeqsnpi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gvncoihr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2msdrpvpe.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdwuhaj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfnbwaa.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2iolscnft.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2smpwhdtv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxreucm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2meydurxw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2igtehpbe.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2texojmzh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhpkfss.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkvspgn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tmihhqtg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2acpxxglk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbuivih.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbvcrcy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqxiajz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpreopk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ajouacfm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2utltaypr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpauxsa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcvabwy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lquuobgn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtbzdoy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcbdknh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwkghws.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjnynxr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxeuxpz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgxpukp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2llzppgwh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2njatnppg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeokdhs.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azwqxflr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2irdrpzyr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrqagso.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfteyqvr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkwfjym.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2btlwqkkr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bhonhoti.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxktjja.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvvubml.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yemihrtd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiserye.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2aixerywj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwizokk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2omkgzxqk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfoqefr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2chbgouju.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2oiaghbuy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2sruyhdhk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wasvjvea.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjxuiwn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmyyisw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfmxier.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqwfzaf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fffuwtia.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2njmlmdhx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mholcrxo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hllxycut.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2swdeuydq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wiapmzej.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqiwhdm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qcczdegg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfliczs.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbhxnkk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnyzfcx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkchwlo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqhidic.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2htryawid.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2imchbepy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2oglmiefp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oweqgdqn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tgetkwlz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqtsukl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxkrcgt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2krqffxrv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvtkfvf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olivpekg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmnnulq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbduhzr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jlocxsfp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2utrkzglu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2scvozfof.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkwvrvg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2czyrnrxm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdzzbgd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hovixjfm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbhyzig.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gilnautt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlclgtx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnicvuu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsklnlh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwrgfsr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cbydaxad.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmvvokg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpetceky.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ywclzvem.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhlaxhg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqkhkcs.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuafuxxh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vimkcekf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2godpozvr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2sscdtisx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjzjdss.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vxahiwtm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zctmqkgq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyvsdzh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrtruxl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwrsagz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pekbokif.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fezzejug.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2sntfzyth.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2amxgiwhm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2walpwqiq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2frfjjuiz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaygrib.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvqghmp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbtmqoh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tujmdddw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2drbzmrex.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ytokgrxg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqidxaix.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmdckra.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyolfmi.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oolyoloq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2clnndten.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pornviai.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vishmtlg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlayhep.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkylewo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmqmxdb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2etuyduqy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xyntypqi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2oygvwows.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmpnnto.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndficxdm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbhsstu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwqqxdr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyluuyp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpnrgec.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjrualt.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2daewbhiy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvaruwq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2sgayrchn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jldmdjql.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2aftmvzhc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvjuqam.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvxirhz.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjfudmh.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rcknvonx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhohowm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvooito.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gjerkrwa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ethnzuvi.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2uryrpnte.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2reuabnyk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgqnkwd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bzakcrrq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcsybib.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsqbosj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2efungaky.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyufsrdq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkxxzxp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvteyqlj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2clhoikhk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbfqeiz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qamxzjms.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qucneerh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyhqvpw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2twxwtuoc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrspnar.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzbuxhh.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2seggireg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjvlwtu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2felupyva.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mryouvmr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2sognvkfy.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkfevvj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2khfpuoam.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2teysxqma.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbpmndl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrdpwal.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjmghfg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnyynil.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnpcjwu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2shpkahjq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lydasjoe.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaoahgg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wyahzbxr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyegwudi.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2capoasmr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrigfsvl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2accriwaw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmmkgjm.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jcptbwzw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gprhogqg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uxobunat.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2odkwwhtv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dmylmjyd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqnrizo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdthufd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yerrxgar.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvgyjaq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fufqzgas.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2filmkbjl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfmuced.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmophxp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqzopfp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvgvmim.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhgllsb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgoilgh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjshmtli.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwojhgy.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxbympg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hsufucdn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmpinqb.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuysgrd.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2avmdqsra.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbnigct.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaigioxg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dbveocvn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyborlo.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqolxgh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrpejrj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gggqvyvf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2saikkpym.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vasykgcw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zoftamiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2votkiyqv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmfeqbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdgrzcp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wucxcdto.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kkudgwqm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuotobm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ycydjkjf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2shwkzvty.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlidkmv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bacmagxd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xqorgvpe.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eahwnwuv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyjsqxv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlulggq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqlhlzk.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2aqslfyse.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhoorne.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpqpsgi.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzzvjgn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvxpcqv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkhijbx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyghaol.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbejvav.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnxlbjm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qteywfsv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsnskdh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbxqrkh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2drhxazfj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qagzxcvg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoyxked.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xphqmsog.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2aypfthwa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxunttb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2apqnpgbv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoocsqa.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2epcwiibe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qicihmue.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2imscdxqq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2maauxktc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fflqhipn.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2mmensdll.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnnevqj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyfmgqn.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsicqjh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyztfho.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2visobtic.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvaurfu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaemkeu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyzytkj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzzmtuw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdhicko.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkmtstg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrswwmi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrhmtgs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2rfppzmvi.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwauolp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmmdunk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zawzoolf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrwttsa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwcrfbd.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkbxzsb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2wcewdxkk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhsdwgt.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkiyfgc.html


<!-- 参考信息 -->