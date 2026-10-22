代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2obwtzokg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aogaqbeo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2elmyragl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kqapcved.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2efgfyixq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2skwsjvxb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2axpanvyl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2udrltvui.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkknzjq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwggjvs.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjzzwsi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2llkyukrv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2khqifsqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrikezb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrxdurh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhmgsdg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hpadjxri.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqhaaue.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjhwywk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2szczhxat.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rksiajex.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnthrrsj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2chuiioed.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfyoglh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tctoztkm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbabkcro.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsoadok.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaxumex.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xrztlbwl.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxphdja.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzqkzbn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pclooayl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xoowrtrs.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjfbzhk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fitljyqa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrfalqq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwccjlo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuajovlj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmejmdn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jplzflui.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlhxsrk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uthcsinz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zaalbjfs.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2oniesvwc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzxkjib.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2eydnglxf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuhvbul.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuejmzi.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpynwes.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqarnkj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vvncvfsb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebraltbh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2aufvhzeb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjopjwgi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cickpmwn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpuewdn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjryccu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrivzmu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbnaavj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvinppip.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akgtpxuo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfucash.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiybwkj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaehzuph.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkihjwp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpxnoyw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2uweetxwm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2urretyxh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vczugkwf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnvldvw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2berbbwwa.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhexqgk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yiojyoxh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2roojhxjf.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtpsurd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tszbqsca.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcspopa.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2yawfgeab.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcwqwpv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2oksgzzwf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2sejjmbdl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2phqbbkrf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvkpnqm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2clxdzjmn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2olvyoqim.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dixpjtpm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pxohqpbf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2szhgpric.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dmorcbla.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrhabxa.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqpztdk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2etxfqezv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qayvsmoc.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2viqjbrhn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eiprmydm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2slxkuwyq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpgowsn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kztqkqdd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqagsbv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnedasho.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyjwcuf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcbesvz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wqakhuui.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dygqovgd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sjessons.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmbrhzr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2moskpcoq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zktzofix.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xedhsupi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gpigdapu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxkybel.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdcqwzo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtbtojg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtnhokc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lqivcbld.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mosqzjrw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvnqzyr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvolutjy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uujcpfxb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2klucfxls.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2oafqnmyy.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2caiwdumm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2psorhxhu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2trlrgefv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pffksgbf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdmyvpl.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpomqafw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvddsch.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrssqse.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fssfkzgu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdvbxdk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2janepasg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2anhyifkz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdbpvgc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2iejqxyff.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnkmryd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xoycjtmz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2labhgjqh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2arnrylrb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wutdfqfi.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gndqrsbp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2yseqrgbn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjscsvl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzvztws.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2krzbmbew.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbrlook.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmdhzdq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2clpzbnob.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqvvrku.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2boolswvr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2icmoblqo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mavyvplg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgqmvgo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcjglun.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ufesubpk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrapwlx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2siswgrcv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdloilr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vpklnbeh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdtjvvl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tmweprgw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiitgzw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpomvqf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2augrvowf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvgeqcs.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2leklhqhz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nlirhfyc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeelbxc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2esznofho.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ekebfjnm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkhejcv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwmtrfg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcgdwzn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnbicbq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yyudexpm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2krrseiow.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wwljnkel.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pqegvcwo.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2probzrei.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsfcddx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vdovyoom.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pxarwdhl.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2sahyccbq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzluinpd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnpqdbb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kljrntfv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rorsmifu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ghewyxdo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sncgowix.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfyanry.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oaimsntq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzhbiax.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tduftgkx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wqogpkfu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhwjwme.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2devyftzg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fmealqib.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2axmhqwxb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dildhyew.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lthdjzwx.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbwgmzs.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlvunpv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2inpyenem.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cstzdunb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gplwjioh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pkctwbgv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsfqoer.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyevrbz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfftjnq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxqpkmh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmoopin.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxoyzwq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tenrcmzs.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ackyshcc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdhpbxw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjljmdaq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvdoaiq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uijatsnc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2clyguolb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2dntpfrmz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhjvdzg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgnkafk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2twkpfexc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mozptrqx.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2obphwijs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxmfveb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2svicvpbd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnfcqsl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2louqsqty.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpzssgl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvpyxli.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrlmesd.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2foodpjsq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nelwawyq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaujxic.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jodjtycb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrqjqsz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgnizir.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjxgkke.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkqbxxc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2alfkdfwx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2juhzpfgo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdnlfvw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfqgnqg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlmptfu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsvakru.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2deirehbu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yunvgojr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cgblbjez.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcimxwr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wijruxkt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2puqjgprb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2abvinldk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkixokh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlcnrdd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyhzoim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2loohciay.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuzybpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjnwnli.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvmyppa.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ioflabkk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qcciorgq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqsnbjp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2urawjtgu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2erfzsjyv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhhuaix.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhwaply.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2euvhdsum.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfiusnf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nzonudgd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qccmpoin.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rszdscga.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xqudnefh.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuwfoza.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uiswfsmz.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdondqh.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dpewjtsl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfcmzjb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgmylov.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2khquzkyo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uytvbele.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bowgblbx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2thcwklpv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnlgfsc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2absjhgtl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrfcpqr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2onrvdiaq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2phxpmvhr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pceiidhq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yymgjrfd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wniirota.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaatvvj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2owbolaqp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vixogvdk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlsymkl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbwdvan.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jblaiflb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nmscsogb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fxohyfdr.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjcaidb.html


<!-- 参考信息 -->