代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzqknxj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vxisjwss.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2adxhvopq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnjqwly.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqtlxuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbbushp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nizekxai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhdccwy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nalwsdlm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpnmebe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kperhzzo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jngwyrxf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdvackk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvfbniw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hctgojwv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ouucqhpj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gyieihli.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhejopmo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rrykxmmg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2digepmoz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vcybgvha.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qarcyetr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mujasqyi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjxiemk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnmenes.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2utowufsj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdrfftp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsehdik.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jamyrbad.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2josedkac.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkqhuhg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaceehvj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2krowohrv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkluswzj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nocihrod.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbzlzok.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzsoylx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiuiojo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsbngva.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbwyysz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uisyekbb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzicxctr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vuojvhii.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikksdnfv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jaetghjh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wekbkhzc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2afyypxhq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxzcylj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2eixpirny.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsfgqid.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wedjgfra.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2abldrpmg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdldftu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2euvziuzn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaujtsd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtybxlg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2frloebbm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jysblaus.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2dpacdmlt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaeesqph.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2snjipeah.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2facezjhx.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tvprsbdz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjenpqh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wzntalti.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dtisxmww.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkqjnxg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwzhiwd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2lavgzngu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2czvlcfzx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oovehpye.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnustjk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mtehwxix.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hspcthgg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kinfxehw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlntgxvo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2msmzzqlf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2etljfsoh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhelklf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2echtvqyz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmrffsl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyfelcm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eonjorqm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qthfbkqc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpvyvgo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbfwiqb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wiagvgtk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktksmsrd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxqyrwk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2skzhvnco.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnrjqhs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuesuvh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2longecvf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcabhaky.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgxthpl.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmkkmha.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jexqusvg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpausgit.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxphgep.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zalfyxqp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2crpjvlsr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqlljhr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qurtheel.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqercxjo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfawics.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2oktpiuiq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkdsmle.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovifegmy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2odzeoztg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hryzerhu.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txwytyfz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dahyohys.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpquskr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjbinyk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dghcugcu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjblawea.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxjavlk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2esvuaiqp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pacddkif.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfmbkij.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqneucws.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvqoeiu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsgfeyl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnkepnm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2igimkhfu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ephzcbju.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpgdjzw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnqcavb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhczmwo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrljghq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdojsvi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrzdcos.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xxidzlyl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrfctpw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrbqfsn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxmclpn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvggbvu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnyjpkc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2snjiaqgx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifggdoyl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgfuuym.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzhoqce.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvmqnkw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbnpwnd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqgxfpi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwmbygw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xieptzjs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2buwvanre.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rsguwqmy.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2okrrxctv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ryocwcaa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtdxlbs.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdqltbg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2eogdgxvc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zklhpsxr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipycexzz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbfsqje.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyjqrqg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2aealtuel.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsvzdal.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2auwccypr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvvtchj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfrycfs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhmlbxj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cphywakk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgnyrxe.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvfcqyw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkcqzoh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyzhdma.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzrwgue.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdmqefy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyfrbsf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hswbfmik.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mesnpwjg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2naufmjsj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nocawnym.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvqgjsu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2higsjxbi.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2taroxndv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ppljzdam.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vngazztq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2iikivktg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeekqtl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwjkrhf.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2injdznig.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgocgmx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtvxsru.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jayioqsz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxjbimx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2yglnbpna.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jydtzdwn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkootbcu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fiszxtmw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2upwpumnp.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqfzibn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kocbngwa.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2agaotaqq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfuryva.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iijtyvtn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zixdnmqk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2waqgsycq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmpctlp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvuhlup.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vchchryt.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwxdste.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2njnpcloy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dyljxkhc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtpjnaw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhvtplq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2elhmmivi.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2njlawalb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpifkphe.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2elbejcjm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvtnfqo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2arhwjukb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqitixz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaswopb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tafbbblr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2olfqdydf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2expjjhzc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxgtfme.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfgfqnj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2palfwvyv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoluqad.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2llgymcay.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2aggwvzpv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jjybfmmd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yvboolml.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lvldjbvo.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wldcxpax.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2umbibodv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvarllub.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxmuhup.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzymewis.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbjlfjn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrqsdee.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kitdepej.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqzwwlz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwcmuog.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjljwzim.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2joxyxgll.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fuefrabf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmdjtnb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2frpfqyoq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2oerljrht.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2veonfaee.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzsvgpk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jpymghyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jylwivbh.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrzfiko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoioftp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmrhuwn.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jblstjhu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkffifo.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qluicfec.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tywojacw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ezihfnip.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2greixzsm.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pqthznum.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fvutbdck.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbjlzgs.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxelzvm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxwmcki.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wmztlfcr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdzibrb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwhhrgo.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2omgeotnb.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kaveaftj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wovrfeyg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjqmbba.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwimbna.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ukojjjbt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2osmoxtby.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ebludsxu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2avtgasac.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rpofttao.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2kejyrsoe.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmelwls.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2psyuwsgv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zizghzlc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nquggfba.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkigqlf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtnufbg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ailnpqtc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cimseufe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqktbnf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjtkcjo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqowvan.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkdhzqh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrvehhp.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2iatlqjfm.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2oakefgmb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2erlpkuej.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yxovnmor.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvgzynp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2btemycyn.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgrbfvk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpyeqiv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjuphox.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2izzodfnd.html


<!-- 参考信息 -->