代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbhttlx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyyewas.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbvfwdm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2reomilll.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvovobd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjlfqpj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcfnfps.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrlaenu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kflrwknt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2puihfzbf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcquzno.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dmofirxc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nezbhnwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmyoobk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2npwfpbsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iupyhjfy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxbaudx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhozpgn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wekibwku.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wlijlcdp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyvpfwx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipysoqex.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkxrhfx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsjpknl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2quhlznez.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhxrxrs.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpklbvf.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuurqjd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2akujvhla.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgwoqkj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jizccpfl.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiwfwjl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwmbowc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2amnmumdp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoifrnd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2umexzwla.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmwmoia.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdpqaoj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nbperkxo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqbcgzl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wddlnevs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwffysh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqungiy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2plkxpukk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wexsnxvn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2feusspdd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yavshkvu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vijjrbku.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bsimlzrs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2prowwcqq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uynmgeve.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjkeriq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnmivtl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiwsypz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2idzglzvo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kavgaqyn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2iabmogtl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2slbcusbw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2avgmeotx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbswtzt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnighydq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2idehluzp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jumitcdo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsnlxfa.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zuakolft.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2anigzhat.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ertiwdlg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ratejrta.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2usbxyszr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dijivifz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvoimvb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ewltvldx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxokvhz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lwakzhzd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtywjwk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uihueasz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ioduwdfu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtzlwuv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xlothphf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkqflyd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsnbqeb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2htvvifrj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpvynne.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmufchq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiirxbv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnhgwwl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wiopaydj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2aghigfsb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxpezje.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfouvuh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2coyqrajl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfbkizz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqmdgje.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2awbnqxvy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjjjazv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uairebvn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pmctlxgt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsqobcy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jiiitygh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cghwoyrm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnwujsl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzrbdlp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2beeubkzt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wridwrpd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoipjgb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jstfticu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpbxkgd.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwlbymu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xytsjfnx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hichlope.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjdnwnr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaunmnc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjyowmh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jhstcksx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrgfjmn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orlafsfg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2heydmwnw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxurhmr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsjycif.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gznlhhrb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qdeijfvc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2asxkjlev.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjrhrvx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2abquihjm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmzyuun.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfwtksq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpzumwk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyxxxhn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdqxngf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgugawgi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgjlrzp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuyhrpm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zqienrdj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2imxivtri.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyjhbds.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2holfxuoa.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2upkbtkut.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kalywyza.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eppnzhwu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2njojxfmi.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cpujpggf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2uixtjoyx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rakjwunl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwlwtnb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvcobhc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eztuctuv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbprhdj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2durermol.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2duwciuiq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxbzybx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlcmphj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbtnmbd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqqjlck.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bddvrsyd.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zwocwwxy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hwutcxcq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvvoxct.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2spyrfwyp.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ewonqxmz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ruajmpik.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2oygwbrfg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugapvkqf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hraudjnm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqjalvc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxltnyh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuojqyf.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyluqgz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvhmkdj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrwkdss.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvmkbah.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdsrjbg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gegzrnfy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxrbcbc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbhodts.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2utsohmdp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2krrutxzc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2grdkdyhg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cgysjwgq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2keytqfrq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lglhyite.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhhxqzp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2yngrdyff.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfzyfnd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsuuwoa.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwltnsp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xphylfet.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeaxund.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsdrgwm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nzflhbot.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2lffyucdq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2plvyoecr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnnooiv.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oofmftyp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2btwllkij.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxhixyy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyfnqlg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cohjejoa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqcfgyj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2awmnpzxe.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2naykcmki.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hcezjsvi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvtbpmb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyqusej.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrachzn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsddwii.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wssnhvay.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2glvtiotz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtomnvp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkswjte.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaohhis.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vstxthab.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzbwfww.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvrybco.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gadgzyam.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bneobhta.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvpxuzn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kptaipbl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgthevsg.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2trmkbomm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyipsjj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hfffigyh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2onjhhtdy.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcicjlz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mukmvfjn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2snmdwzvw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhtlklb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2slysedtb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2woxturvd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxfjwyy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnptpfbz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nipjvzdi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2itzzmtjr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrucegc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vphzlbuo.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2cppoyody.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpakkzh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2erfxumuw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofelmtet.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2uysbflbh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuobxfq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpjmwxi.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lltwrdya.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2frfuzwfk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rawepugy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvghiop.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgpanvm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2usvkffez.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqaviok.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nqogvizw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhyxeyz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhdsrnz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2iupdhjhn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ortmxayr.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zwndakdk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoseoutx.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcbjemz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idwdqnxy.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rofrvqzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plflsqtz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jppwrdvh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdfvpai.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aramzzts.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzznpmf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrqtuqx.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzszxks.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmqhqpv.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrrcigw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpbppmt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yheqpvki.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2blfiyvxi.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjslvmj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pbccnscu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2etcqvoib.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxiwdpi.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqzirmr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsfjlut.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nggiuwfx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gzahtkmu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2brzirpwk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcjgftj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2annkajva.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2asplskzj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hftbahkt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsepduj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwexiqu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdpyrzf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2valedioy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2iktdgvyx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gjagujfb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqxfeyl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2smmwlofy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvasjcg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfglpxf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqiodjr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzrbgcc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2twavvfsc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2njiepydo.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdiowqh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrwmkwh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nqirpaby.html


<!-- 参考信息 -->