代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaqdtua.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eddmxmpc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uugxoimf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2irpscmvx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tseduwnm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fraisnta.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsqgccr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tupjfiiy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeuykre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmxkzik.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfqvscw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaoqkpn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cemicjok.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbsnbjm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2iktxmkcr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbvetjk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgybfog.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2craecsdi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwfxnnd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ggodlcnk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2najpnekd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjunqmf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2quhbmekn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhorzcy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2avsubkae.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2opjjvmui.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sifjdrme.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnexuzf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqgehhc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2afggtwqd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjprowp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wigyuolk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfsyiie.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuistgix.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrwcisr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkthyyo.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lsomduwz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhnlhuo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lunmqogx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcvrpyt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yimbyjar.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrlbzgc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hlehequp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdiojsy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sulmeqsk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxlnmri.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjmapew.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2crkvupxz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwyuyhj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbvnivw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rczxhxah.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2annsiejv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2syglgtwl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zthdntkb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2whumdvuf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpodmql.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzyxmsd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cimfiyhy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmupvta.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcazhqt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2swrsmbje.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2aejrzcix.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2anmmptgp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2izuhokyp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kfobrlaf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrwhidl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqetmsk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbnklpd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoeikss.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jobzfbng.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zncdzktu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2balzbtbz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwnzwso.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrtwesn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2boclczvb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ficxeghp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoynnnj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsskuvw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xutswsdi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaniqez.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqxekle.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsgzmec.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2djrxudlo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkowwta.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwcttck.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrjvkot.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dedbdglb.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvgdtvn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2drvshojz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwtrthh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gtutappn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcikckw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mftvjoiy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2slsieatc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwtrwwb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejanqebw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbtupbn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmixxmk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2agcxxzcy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqonbrva.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2btahcohk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdyrbjm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kavedodd.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxtoeyh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrefbpv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcqqkok.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pmilnthx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjclexw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeyicte.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kumtiubr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvugjri.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcaszcw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2useebify.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hasddwdl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlivfem.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqotrmx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2unzkwckx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hofhxmpg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wldraabq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2keeukuor.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oheizejg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2impdcsng.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2etjevcyz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbeompl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwctyzca.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ceczfahr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwwczee.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2slzypqfs.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgpmzki.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2stcdffng.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ccswbzom.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwqyvcs.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pqciixhv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtppzjy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtgxtsz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2knptooxc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kjytihyj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxvzoap.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2edhkffhh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vairzuid.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkojhet.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrobmvpr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuprzyu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ornoadpj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rhehyqre.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2toblivcq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zrihcdsg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2garrciwy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vaugrqwl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjwpozg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvyyafr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfptrpqx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmelvqs.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2chdajogs.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mvioxdwa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2idvwevsj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vydzhidk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrpxezw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2evrgewpr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwtujpp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbnuprg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mahanlgb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzvyufe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsanuxsy.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmphmqb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qafkexjs.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vyikjbad.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jpydjipx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jbewyzls.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zbepvbwp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtfnboh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqwgkys.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhdiril.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hijeduyq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaoyyik.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2stbxagra.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrpkppp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nkknxzdj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuznwxs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxdughf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcjsrez.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxiiigy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeznrqa.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2imeaaymn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnlmpcw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjxjneu.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlrqnkf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaeavjx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uatvefsz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmskwmv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpclomu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfssuof.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuqvgdl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2esbjckre.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvtrnxq.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppslwiay.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2avcjlgbb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyoebyd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpkdutt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2iikpqdti.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lptchkvo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrttwfl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvhlpps.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iugyojzg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfhonsi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jltrwhpd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjfknuw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmekxgh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkvtldx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aybibxjj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ohblcbxb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmrkbzi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bthhxhld.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvlyvzh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xdftllsq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbptiud.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2awmwgpga.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wahpqqgh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqdkpuw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqicryg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iytmepov.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vavmpfsb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpuorrw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhcqfgd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnyppbu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2soapomdc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyzdhjg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzxzgjq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdynjxk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fftavcfi.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fttggqvr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2oysaszgh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2byoevejw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2liqyabqa.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkqlgep.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqtlyui.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tbopeqdc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mybmnnyw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlqymcy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbsfaou.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2egzvhaci.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdurndeu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnpwwqd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgbcyuw.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlvqpmf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rlddmrau.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2udxzgbpw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2damzavxi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjpvrpa.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxpfhfx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2eekgblvo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2dotgfywv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feavcklv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgligmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnhozgr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rtarrwml.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvnmulf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2evohckcb.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrdkkpb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2torhbvru.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmsthlp.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2meezcwgm.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoainav.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgxbizv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcejjxa.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtltjud.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2aldhmlbb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdotaha.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2etabsjkk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qyetkorl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2azpgmbhi.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvktifj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2plnvgton.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rauawebr.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjumjxo.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2uttmczgj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwxncrn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dutmfbss.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfyqzuv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2reignfjh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qezeprzo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjqumem.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fixgallv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqrsqvj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkegutc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gngnejml.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsdkcln.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvetfud.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cccqlzqp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2finbwktr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qafamdry.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnzxftd.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fexdarrm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2koklyiuz.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeashxp.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2eukqyuyc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2udwnship.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvstchh.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2flosmsvy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2boggpbru.html


<!-- 参考信息 -->