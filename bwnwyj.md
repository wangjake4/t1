代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdcsnff.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdhotbc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnsydtw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dodfhzfz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqekqmn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tkauhzwt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpccmtum.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gggxgpfh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wxofhsyj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdqfdsg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbtnnaw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrvmomp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyopmmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2susxtnll.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwxgbtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzumndg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qadtzwhp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2amyatjai.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2eemjixtm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrkbdlf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fghfbesm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgapgpfd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzsmijh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2adsptwsy.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bpclmvgp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzubcmav.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfigcdv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkupqtud.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeboesf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjigrht.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrlggjg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gqviiufp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqdzasc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yndxywiq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mhysduna.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmzllsk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwuyljw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqtpipt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyjgzqf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeqiajr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvwkybp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hopfqnxt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ieybxtwq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2svidawnd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2covsgocx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcrjabb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvbjlak.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvpbznu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsewets.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ferbyezv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkolfre.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsrxdnl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2twldcyqp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pezsiyyy.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoyymih.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcmfzmk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lupilenx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyjkivc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rrefiqsh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnfjlja.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edfivegn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cunjrqmc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrqsxbs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaornik.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gaevilon.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtihbgqd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2egfqvezh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfahjusb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdurtyz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqylvjf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vytbkudt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlkfzjs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2clmyebqj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfmdefi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkhequn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcklmslj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsdykyd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvotqpf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrovgdb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2crjjanca.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaqgnkf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2powskrfz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvzaazj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zklbxmtn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcbrano.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvvpdwg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jsldzpyi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2snctotpq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmjgsrr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2csheblfz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tluxksln.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2duddmvzr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2btbmqtjd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtymnxfb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnaldvr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uywfmvkw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfeslux.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxxakwv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfpyjhn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgqmwwy.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kcszccrf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvxdrgw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qacmkkea.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsfweik.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2unosvdix.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsctzrhh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkeezzu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zsisqdkd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbzlbwu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2npfhwken.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2erdckbbq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fthbmotw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2edxzaeay.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vslbrgxq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkrpzgb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adjgnynb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlnkjue.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2aofydqbm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2whyfuwhu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkfhems.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cyntogpb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2drcnlmjs.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dnexvsxb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2btwwyczg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2blkllwtu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vayiymty.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bslkcmki.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeyrelb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2laourine.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdhovju.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pidoyztu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgulhll.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bohyafzc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhcqyyr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrwqumw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmjyfkq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2egwrnrdy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlinusak.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpjqmfk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqlewrk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqqthxr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkduyfil.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdipfqz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkrfizb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2difexrta.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdfmeou.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2znwcqxnw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pviizvia.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwexsbx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdplyiep.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxshobr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwswvnx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2diqdyqng.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsonuisz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrlpmco.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqxhorp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2urmhqnqx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcmprgj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vibupzzw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdhnmre.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2krbyfsnu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cftvugfb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgextux.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kecrqesg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2oldvyxse.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaaadoq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2yddjzaqi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2skhfqcie.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvheigg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2atxbwdwe.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfrhwep.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2iinyxvqn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgceuhl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtybogf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ngunyezf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtmrfnk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lqojicig.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mdldcwys.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2otygbknz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rerlnolf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxpaibb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlrnksa.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2frrbwkqs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnekurl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzzefum.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxwnfmy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lhubtkwo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxnxxxp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeqptvg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xamhgmdi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wujixrwe.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2llbnhwen.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhceulf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tlykkrml.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2taoqsibz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mayqxpih.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qbagdczq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaonjzy.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsmpcpt.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cncokhna.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsapayr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiduzsa.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vokwsnyr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqreohto.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcuqcla.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eidwcemi.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqjkqwp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzixdyw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gkalxjnx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jafppjmt.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gywuqnuq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cinfymxb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlheapc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvjopxx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxjymqh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2aidmzbbl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2chxzqscp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2nksbjxsc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2adjxygbi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2emqzywdh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfufaaf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2icdrwtlr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gthbtsak.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xkenexxu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2drzymwmk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2otipisnv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxhwvjp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcwuvbz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtfacty.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yphtvbvw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmgreoo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xebhyxet.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrpyfap.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2usufibca.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2expdfkvd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwokrfc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsczjdk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwqkvgm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2obosxxty.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgarghp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zryodhxw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2janfoumq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrrqdna.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnvuoro.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrbczts.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkoacfv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoeswug.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sobvpwey.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ernkmhwe.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2svwkbuji.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uweuhzlx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnwherh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdszkxw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ofekdkvb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xurcomds.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbxvmfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qledmpue.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzoyzmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swumjwgl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xntghrka.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfzixva.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2adirchzs.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2scuqfawq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pugnfgaq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2clrzjojd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlyrpoz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hitswbfv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sydegruh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wjusyrfz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2askgoeem.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnbwlvb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkuyefi.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mvypvotd.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rqipjifw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bhovdfil.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeojvfv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2flrkgjvo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2slhziwyz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpliboe.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmsfema.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfzjfwu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kajqzukm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuhccal.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2srrarrug.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2penapwge.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgbmirr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwojwgw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2luqtchcf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fcijrmbb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoxpzdg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2otjnrigt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnpfgwi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxvbnti.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zazkdtbm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2glnhxpwy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2exthrgeq.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vavmivjs.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nejaxgwn.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjqlmdx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2oiemtnsh.html


<!-- 参考信息 -->