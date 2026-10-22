代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bywqdulm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqhljoq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2prjrhjqc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsadppf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2majueixp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2caxwcqlh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvhmpcg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cdywrskm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdtqsnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plviqbnq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dffncaps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnmvkww.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kphipsju.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqnwigb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wisgmfee.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2esfelcrb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgnrses.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqaljzf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lwakcfge.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2srpkyyph.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvbgxqz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2guwiofci.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xakhaohi.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcakqijs.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jonlgumq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2drzgaqpg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxmyqkc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cezlkpoo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yuapcknt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsnsfum.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2woawztbg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxhqzcv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2egwdjuql.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2waskwece.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhlybtr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsntdsrq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ysceesml.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yczycxlz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhewwjl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nayzfitu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2evtvrrup.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqbnpll.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2foxugynv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rawuoccc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnbfxip.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbfhlsa.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxacvmw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuxdwbq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhcuuhh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtyfxbv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yghfzlay.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xenkorkj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hljscxcy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2crjrvtjn.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2uushletg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jahxobey.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcbvjkc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2buqotdxb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ensuauhy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmouflr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtnyfag.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaapabza.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2revfoqpz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjbmcls.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yxctiqsf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2djbhmfvz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cpchzwgl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcgjomm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2owdljtjm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jujcaqcg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ydijsvhs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2quxgprmt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xqplaixv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pplctfop.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfukhqv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2beonmeqi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaskqtw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqctsty.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rlitremu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2duqhoqid.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2adjtfetq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpkzemy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbjgozx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2woaaanvu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jctnxgkv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hxibsqio.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpxyhuo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fyszqaaj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgpdxcb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhlurvn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2srabdcdr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmtpjbd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cqslwcxf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhymwlh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyylyfn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yidoiwlf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpkxhgq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjulyzy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tythiuev.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbwvbyg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcowlsit.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeluyqhc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jryawbez.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qnohtyrw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdlyyow.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2azshmvsq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqowgza.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxolilse.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2augfrpfh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2okstfqnr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwbdlyt.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyflauin.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbnrdxt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2acrnfxlf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmdqlst.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoxlkam.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoxsvnc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2olzcxbqc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pruezgfg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2knnpqvuz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmjsxpy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiqdbcj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpusretz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2edcsmzhk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ucowcnfo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrgepjb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2budhlshj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxfrpfn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2stphcsbf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpgfdrq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkgdokf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvspedou.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vucenpnt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgbigdq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwxhogh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gidsjmkk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2idresdkw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwzbqcr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjgpxpq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mizhbusu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2dsddentj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2prsjzypn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vogwqguj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaurmrj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gjowhpbq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncybxnwl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxxaicg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsyomkb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2flnpcgqs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2juhfllhz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxierdu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxyrysi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2myhgvzew.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnqhlbt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxjcyua.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yjufwjen.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqehzoh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2owgefmoi.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2erjcuxfn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsvhhez.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiixkxs.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyjcdlj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzddpfj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmsedhq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2btdiuphs.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwquwsy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxchtoe.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzjiysk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtuszyl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzywwvm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnzzlsb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjzhryu.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yyddytqb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2womipskp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsffspy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nirtflyn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2etghkyzi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2aofrfvem.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfcfuey.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlchcdq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qkirrnqz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2viyxqkuv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgfkxxs.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dqipteuo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2etvfkkzf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qobdnhtc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jiousakp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dannaate.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwialvn.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eybnoasd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2metnfqqy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnutpkhu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2irmhoizz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vbczooxs.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2glepkzlb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2paevfbdd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bxguziri.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2goiebwcs.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjeqrpi.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qulsvvga.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxtllbp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2icebfamy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pxldwpiy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwcuchl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2htxqyoup.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qrquofay.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzbjijj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2whgojykk.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvzipjv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dujbtwdy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrjiqfe.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvpuzfk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlqtqzc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiqigfj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbbvgqa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2owlakhyo.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2peqcdfrq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzaiswr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lovdovlc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnzdgbp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bvesxeti.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmgzeln.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqcyvcu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrtdtnw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxnwkxy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2abrpmbxx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wledgbys.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzymbdr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ondaddei.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2aajvgbpm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2krsivxub.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjpedqe.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqnqbyw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzvioob.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhxdghm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2euoqqfpg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zvibvvsf.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqihgcp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2njvukacg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcskmbpj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzfdict.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2youqoqur.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2olrdigyx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdmhtdj.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pamlsefe.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2omfvckju.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpheuvh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzdfigb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsmfzeg.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2duwmlyhn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2amzpckuv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bukbylto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcziwwg.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdcmgtf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtnpphy.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zzscxgjf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbnydbc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxeuira.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcovroa.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyrsosf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gxooqjzu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjobzxo.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2phfmelqw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2phybmkvk.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiathoz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2oarhmewq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2vemmkpnv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2bwybjkpk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ipenxnkb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2iczxxwqj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2puyxvywx.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkgdxgt.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jawexjar.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oivnyhcy.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbnmevq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gsknfpfu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2emtofowv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqvcqfi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gujoinrh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xawybddb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2whotyjyl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2orztopdd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2otefhoqq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaiaeai.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfhhami.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2evlvoklb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hxelhojp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lmknhqja.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpobzuw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwcdkhe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzbbzah.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kprewakr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlxudjz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2puiugrgx.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2eawufolp.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2izwmtoxy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ypclwfah.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mhunneug.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2abbrojmk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmvligf.html


<!-- 参考信息 -->