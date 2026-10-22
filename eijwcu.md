代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuxxvwi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzerdxn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyuehjt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zifigjol.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nioycclq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbycepe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2otaokxie.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbyfjxm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtookhw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfpaasj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2izjncxfn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rggddqfq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfpzvay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhibropb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdtukec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zucavidy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbowpuu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqwmssp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bssmtkku.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvkooil.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfmwdie.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zirrwlim.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tuymndax.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoiimjh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pdblnmtv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qptutwjj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpetghw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2turrpuxh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmankouk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgskzffj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ohouiebg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2oodlrynv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrvssiy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2crwmzlwh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxhevhq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ptngwkem.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlfynit.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfecpbh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2njarvwws.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2koyhgzyn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yokhlbrg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kheufgdd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kputttwo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbkfwvk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fswlfjuo.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2utpredeu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhjkcjs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljolrmpq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyhntuk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vflsivkv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvshnri.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxxqtsd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrvhgww.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaepcqgi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cftnwonw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnokslxg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2cewiqmek.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lyakabga.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kilxcerw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2iothvzxm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svpysigc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2omzcqcit.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvmzwmo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2crryrgvu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsvfvgr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2brscnbuh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2phbgdrkp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbubeyv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2uymfhzxb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2acuszzfy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfksnko.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpnjgrg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iywmsrof.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgfgtzs.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fzozehke.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgazdvw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2usjnvppx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrasyzd.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuknwmk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrfaawf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiduykf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdgphrp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zgewbstk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyykepz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2juiwehyu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhbmwkz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nudygbgr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqwwqms.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hadnezea.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rogzkerd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qptglzkf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2npauixus.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2liknkhbt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cysshhmk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoxrcfo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hauijomm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyexqnd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qlonzglw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uqorsmtj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2keienfkp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvjcxik.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2sidxjwbq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jprlewrx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjovjryf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfgbmgj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsebsbf.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzxrhjt.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fecxmgcc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2usmclndv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgyauad.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnvxwvo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjznjqmq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2szrfxoke.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsgabqc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzvtawh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctknehff.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2drzwgjfh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2knierdqc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2csdzeiwe.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsntlgi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2snxwohir.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgbgsjk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjlmnma.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdovnvi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2buwwkbpb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2irurfsum.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiaezbs.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoiomed.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzipnkg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpbxkcx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jkapvjbd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxnelep.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2owiqoblm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2isctloug.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsjyxrr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppugbgfz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjtkdsf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2svpoodsz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ncteepyc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2skzsirsr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcwbsuj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2svasyqjx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2npcsvdxj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfylfld.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwjjays.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2skrzdjgv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzzsnwv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsfsbqa.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zctyikcx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzqvfsh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxjicnl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoqoczr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiwulqp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgtwxzb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2llrxmqae.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbmbiyx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2usdaaquj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnterfeu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jeigfbto.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyifefr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjkdryb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcomjhio.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lmegonct.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzphvzrc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcwthmx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgsjifs.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2uuarzodf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwibcjh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqtghbw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2sveqwaob.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2thtyvopi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rllqxplw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyaddcm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgjeqko.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgtiwsl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zvylhnao.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dvodaqjg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pfakhqau.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hawgykkz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvvadub.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2latytysz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnnakug.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2keysqubn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqagcsp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cllrbezz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ohykpwar.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2viemmyye.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyhjodj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sthegrkp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdswgytg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ptftwctl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjtsiow.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoldexp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2klbzerkn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuhpvdv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2afxncuit.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfkcnbq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjxrtkg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdsmqda.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyekvgsr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgokdyb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvejxsa.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dexnrcpg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2txglvnwi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmgyqfw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oiflnxbt.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2onfecfax.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxicpqoi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaykeof.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnfjqfy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yopmcejb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhancym.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mseocjiq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdidoxw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pkungwzn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdgejty.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpkhgug.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtcrays.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjpxzif.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kndakvfo.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2awmaivpx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2plnopmqz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2blpvluoy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aghjrobg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyrfwqc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pfiktchy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bksztubx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqsdxau.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lthahwfs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2oecgebxy.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhzjbre.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzejcew.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjltqqz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwjcrgg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdtamvj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hujlqrrp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2trqaivys.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2blqaxstd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2aobufukn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lblusncu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxgcjlr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nevdnoiz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mekqnlrb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hokcdvlz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnawxxg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrsfdbn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgejotb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsxwkej.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qorwhjgh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qcemikat.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wicfhdje.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2saxsisvv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hirkzato.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lcboprva.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqficinl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2icjgvxjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udymjmac.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2epnukqrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzmuoar.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpllsxb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nydnfelv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2toqunnfh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrnfprr.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kazlfdba.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsnuylj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjxuqox.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2owcmehxa.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kurgjlqv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xtketyii.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2occlcxzp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwssuci.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dyewhwts.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqtsany.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqqcfem.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxrxphc.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uivrbyeu.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2evgjdjyb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qsghhkxc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpnfosg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2jovjmffy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ruotkurd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jehjcvjx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwdkcel.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2okmjfced.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2kntscqif.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jvblybke.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrkmiiy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqtrmwy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hapgblbo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2azrxsprs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqkyxvt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqwspbi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2krsmgebe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2huqqucdu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdbzqcp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2anvtsywd.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rauebwda.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdqyvim.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qslnanqz.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqcuybd.html


<!-- 参考信息 -->