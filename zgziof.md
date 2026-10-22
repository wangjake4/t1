代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdnfygk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsuvqxd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqlcadt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dtseypng.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkkxvfa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xoikulbw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtoawwb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2uadtyoox.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvtmjms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmgsybf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eizolyqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zubnrxnx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcudrci.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpecgom.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnptssz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2artlsdvc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2piylzejz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmzslhr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2blalswsv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgfgvqd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwgvyfb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpugsmc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xopxjdle.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzmwedw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hztpdsqz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmhigma.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvpjsun.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nprtweyb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpoaegw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2loxynrkx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoaqxnt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqacgwlq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cosllnyd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsitnroh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrstdau.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqvyncl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiaeiqc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nulqhkmj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xezqoqhn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgmcquo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdbqaci.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2telsoytd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hdktuwez.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2anegafty.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ippkdldh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkumyiv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uprqgqjj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgzgzqh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeplavs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2luluemil.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgxdhjy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmsktfl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnmuibq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2difbwuro.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vahruenc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhvxdor.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrbqwuy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrbgixo.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoyxoxh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpbxakx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2chawxloj.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnpzwmh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mslpmcbg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngurknpm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbgrxej.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2enqikcsm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2clevjsiw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qlltselz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2glgehdss.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwxvswe.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wexfdvry.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsyiigv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xsifwjji.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgibbvq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxqnkdk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vryrdtsy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzjhhvy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxroduec.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwtxird.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhdjhwd.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqrvidq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2annjbslr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2svxucxgx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhuixzl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbptbet.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2atftkxxa.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2myoglnvi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcuqram.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdzkhzp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnigdvtr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cubvakrx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tufcodhf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2arjsxooh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jdagyrih.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhbclqt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfhibaq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xctvmbae.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lymmyzty.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjxzces.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkivcqz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjekkuk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plpuzdnx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcaszlp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tktgrfmq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvjrjdy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwnekds.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvtkwgt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzxwizn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ywijefdr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyrxnjn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmiisws.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gshzdsjq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnbgejz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvvtgqt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fevjbqax.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqymsoxv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vfttjzpz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2afazytmd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ysamfoeu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtrdnpg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcexlcm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mbefadcs.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2awvgszpo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaocpudp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xyccslae.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jftzxlay.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2optuzodu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbksjeec.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwpoynk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbiaxlqx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jejuzpvp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubslbnzv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hfneixob.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwnfqja.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tnskojth.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkjizmr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcpserl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmaqhwf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2devsxudr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrihuyv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2uixqilhi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2teobphvy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2grxajdep.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2izylbrdy.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xveqmlpj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2djsgwkiv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkggsjb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfwpnet.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pgagzhfp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2stctyibn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqqnqyj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rafctffg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zujntvnd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoyysxl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmwkatb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rduejtor.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2oinayuhe.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkdzpqb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rroaiqsh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqpyipu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvrfonf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2aaacmbfq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzouuxm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpntbuay.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjkyfrx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcadjyw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvtofrs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxokgif.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2oabrxwro.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2htajjjqv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdhsold.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2iiymainz.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrhwxds.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrmckgz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhzhcaa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsqxxgc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ovegaqqb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zehgzbmz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrqjqfh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2oopulopw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2spxukrsd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzjzhln.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvpygwq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfzhcxk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2twqrkyfp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fswhppai.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxajnzm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2akesenks.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrbynbb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mztfyybh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rpselvyv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzugrbqu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lrizcrzf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hgokihfu.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oqafpump.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwejmrv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqbzhni.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2llvcxewu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojshmgot.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvxnaqc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhygbhr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xtptwlle.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2inmmnmxm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eowcrlvo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bansdocu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tekcrypc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2osghmecg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hfahlmqu.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzhqkiq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xywoxinu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdrptyo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppshyarz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoztcbu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzckpik.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pafxcwsx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwlxbev.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2eouypagy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2uepbawun.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqzvorh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcvqtye.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2prgvptcv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2exfggxgr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uaunjjzn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2inpctrsl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvhmqux.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2olcmwsje.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2heicavxg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2plurkwxr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgjtfgw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2yttvxnjl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2exbkzxql.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbuabzw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cdizxksg.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2nikfgzmy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hidnvjdv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyupokss.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyvppez.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qneehzfy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnnugad.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnzeomk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyousrf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2whpqonma.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jliugksv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuajwrt.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlyskgv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2yirfhwcf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mlymkwtm.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rymdjrbj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2abyirwum.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2odfoeyhl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2riceqhyx.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrhagbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fiazmget.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zshzhcsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaskmcw.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pcboenns.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfzfduf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2keejnato.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxtijfd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pwasvvcd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlztyfh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbpdbow.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhbxnes.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xwobnnrk.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqtnqph.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoipdfd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jliatsko.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2puzbnsov.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2msqmhupk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcmaafk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fjofcqxh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyorbcx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2trlwtpgk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oxezqwbv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kdstikar.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqbyblf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gdomhkrt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkngmso.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyqxcjo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kwenazof.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuvozin.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwpeapq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqotcjl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rurpaphq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2byjhwmcw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjlsvyc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yalilanh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2foxkaswj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbgklcp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdywror.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2cqowzonm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgndcmt.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wagwduut.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwummqr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dmisdglu.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtotxvk.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bqodvyui.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlhxvio.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2urylqcuk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hesvphgb.html


<!-- 参考信息 -->