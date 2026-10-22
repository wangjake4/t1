代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxwzloh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmwdfxg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbzptoc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkhcqtl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqgypjw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wekbuece.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjoocar.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2sniokocn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjawwieb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsrlneo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlyleem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjaycdg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnisssz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2iiojmpui.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxrmtwx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fohylqat.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2asvpcpmi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tczxqzkc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqecdmz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2owljfyyj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bttlbqku.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuxxefi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2enywpdfc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2oombpfbv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhvmoyl.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnjiwbc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsvlhfe.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgdfwyg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdobxgz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wblbmeau.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yybvehxa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnvvljk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qpigmzyk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyheihl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2blmcgnku.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlagrjp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2safwerjz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfgapuu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqfmwbl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2unbwhggh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpsvjrg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnrimmj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2sucfjeev.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxayixa.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fytfkwth.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqiryuw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgyvrzt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyqdivl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qeojhebs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtbdukl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wioizbwt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nulywnkg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvqkmai.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaeuqku.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2chapkeuu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfuxixh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdqqmnf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzwoben.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrhmmmm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bursaeje.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dssrqcck.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2podvtdks.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2efbwzvla.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhkvmhh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlqeivt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzzpzms.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2flxrnizx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gsasqudn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbmxvfi.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zlncppci.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2texgywiw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iukswmdg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdauyer.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhyqqzk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2toirbeic.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kyejolvk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mntopigi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2avrttoql.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2goxnwbnf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2npesibqg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzogfheo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngedjnnz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxymgcy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2btoqezyk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbqyksh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhuciyj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gaocgcem.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qbueywbg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhkydjf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2eydxjjns.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yntpbkng.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzxhlpp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cyawrbnd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpkgmqe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqeowkq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqthcgqs.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2teuhyrzg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mujaryxc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pftjcoio.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2adipzvuh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfidegn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibezsdlw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pyenhiht.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ceihlvod.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdxtcol.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaaovba.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsqqygj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkgnjrk.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ncghsgoc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2swniamvi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2selgoxxz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkwhivy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwgjsfx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvldses.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbejgskh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxjjqlw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiljkow.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2iyixiwbn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2snxhejdy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdsgyfb.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvtnrhp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqhtkbz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsqlxpp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eddevzzg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwaukoa.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iajnufwg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xdagzoqq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhzerto.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmpkudl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxknsec.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2greigedx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkctadkk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2djvrwgnz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecosufgg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqnhnlm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkkngxm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hudghlrm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmedrgyu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pkopbsic.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2iuphbskc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2adfsfepl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2znzjswul.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgvdnnl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iecjjstc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vskucaze.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsqsxav.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2acfkiofk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmahuifl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrqqidv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgmpugk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjpyweq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2akkweupy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2omxtiuov.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbbhnky.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ykptaewj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2euianbxm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgrqtwu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuejeuqy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjtdzdy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2eevntpfb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2myojhsmx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pulqmqxt.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbhpywp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeqetpo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyphort.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xxejqizr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hstrwvzy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiybmcf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2eshuabnw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpntpiu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kvewohyb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqyyaiq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ynazymch.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoaddui.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjidure.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2enghhkwy.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vknxalmo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwonnqm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qnubaaab.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wteuiuni.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jivfevhp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyrzrle.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2stpntuxq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nuniiwix.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zkppclil.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlvzyzj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrvaudc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxprhugd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2icpsjngp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfrlnge.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxoeejq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfulnuz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2laftjuqt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zoissrrk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwkyxyf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgzygvc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yrujidkj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xoebypcr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwdtdty.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgotwua.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2djtbcavo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vevvysok.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnzixoe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kybkjboh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pawsgvof.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mypkjgij.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kuowwoqk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vocpbnwb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyturrl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfybevh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxodbvn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiicptzw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqxunuv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmzkqly.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pygqftbd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhsktmr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2raeqhfjd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrltcga.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nepdllil.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iqifuaaa.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfrsgyz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uegvlitk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoekrbe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jcowwofl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xjywytjg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rezdlhff.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxmnvbe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ljimufuk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnnfvbm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2glrpwssh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2texwoqge.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2odxnmklz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cckjiuea.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2klsyyuou.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwvsfym.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsoyzqm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrptfdw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxvddlm.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyuaqlr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpcrutp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlfvswf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2frfslgue.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufffetxl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpsyfiv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2brvtmvtx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2otdzlypo.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zbckgeof.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bgedlqct.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2icbajuor.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmvzjif.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbwsadp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnjicha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxsgwkz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2iokcptxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wullrivw.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxlotoa.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvbmncq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxneqeg.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2osmduiok.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2unvcvgjy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kccjplys.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aurvswzr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lhitlnci.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpwjdil.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jvssnxpa.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfofkqd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxotkpg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2panjhatk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtxjsds.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkfwmsf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2syvybnek.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sksqpixc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdeyags.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkkqxxs.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bpatqzrb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnukorj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uupqonfu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqifvjz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kptoliyz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhwnnkv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xajzeoja.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lawxamsy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yphiedrv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwfedxh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjqlzaa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fcocdxhq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaasxcv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ephqhgyn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyiekkl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mkendjze.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yfscbgfr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2swiihadh.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2swdjdcss.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbqqrxa.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kcludogk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dqefjcuz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2adkklyjm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2utdjcqzm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmjhiit.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zecljrik.html


<!-- 参考信息 -->