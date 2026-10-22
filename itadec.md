代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hvranyaa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxpqhal.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ephsesyh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuyouqm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2sppqwico.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hitpswco.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzraovex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pparzisc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wklcbdxv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmcbvjo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2sppyvzbf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yopxikil.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2efwalnmd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvpvfum.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuddvlb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2omystxsm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2avwdwxct.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpspovyh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrvtvwv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfqjmfa.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyikpsw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxgjvgw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpzwbrj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhhdrdp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xypdiiny.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgmkfal.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzdayjr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2szkdryns.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjgyppd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2coairubj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2areknqpz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqffevpo.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2odhmwwxq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwrxhau.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhtrrda.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlvpnic.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2srsaqgdo.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgglukra.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kyclgwvm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjobwrtn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eadqhefe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2iijtqsee.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ggweigce.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkuekve.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rvznbxgg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdxalyl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tlynqiwk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gawnqelj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2enlqwytk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrldzvm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qadxhkdc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2twqrsjej.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqohwqb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2uyryrfae.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2phniatxr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcumdty.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgngmnr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgndbro.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kccrhgey.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcxfwul.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaqyhbh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuhbmej.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dmooxicw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yclkgjez.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsbvopo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkpzush.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2slhzcxjq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbgimhb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdmyfvg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmgpxbp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xawsswko.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2sljaayot.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqjsnto.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ioolglzj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxutbqq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmsqzpy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rojwvscg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbnuezv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsdictf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtofvfl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kroljfqx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmhtdhx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2noxkssvj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrqroxz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtrfxrp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkunxwl.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2frtgavaz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uinstuel.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnydipr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyfcicr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgwfdva.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2udzuwjzp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2avffzllx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnovzrg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrysaae.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2awtrexyx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nspbhive.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwbyqko.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aabghpov.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wetsaibh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uwritega.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qqspkzuv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qmckgvpe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwookul.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpgjtbf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxsrarq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dtakqmzo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbanmqcb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2shenlwcd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfknsvq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxlffcv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tguvwsvn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbxzjvf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2texnjmpi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeazhjs.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaczmbk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiemoyu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhtvsgr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqumgctq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yodcmval.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zgncebnn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrvtfeb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvuasbx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqyhtao.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjciuhwx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlklyqnd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjtilny.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqnqajz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjqyzko.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqzryzf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2soycykva.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcffhmy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2exsonqsi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxitkqiy.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfrppbd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gftxffcw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2giarvbio.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sypqrkbm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpppeqn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsvowxl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkqkhph.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnhgxjg.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jeprixdu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvorhfx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mpadcwmf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwapnxmq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2viqipnps.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdsrlnx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zspbyoht.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2toypzfuc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yebfqsly.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lyubqgij.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxwkuld.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2flkgpxdn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oouxbhxp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2oulpmrjt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zcilfjld.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2htkdryau.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmuijei.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkhbdci.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2sboxbhqy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpsbbdd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrrkxsn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nifeusvj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsoxnqs.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaaljbe.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tkafwjyc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeufvxw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdeawjl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qarowjmi.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvholcp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhexrzei.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cskrnkjm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkpneck.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2sageoent.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2algwrkcr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzlvfqx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2imsfidsz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kfienaie.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hcolbrzx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfqjkxk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlfipyj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2coboyglc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2krrhzjhy.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tjikncca.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eghntcde.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2opvqiwko.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qycdnpzs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjlgetf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxvlkpq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlirgnh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruepyzig.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ihslbqrs.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjkzdsa.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwkclgg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeolhmof.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2izwqxvte.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xemxhhll.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eieyfjjg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2alxbimgm.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2crwbklgk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrigbzmv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrmfwfr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2okdplfwf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkhzghi.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqxjari.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2klbliwba.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwooasvw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhzufxl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2aahkgcmm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rioaozyz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlwyyni.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbdzflm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2verqyqwd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mckrvkaw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zgggegmp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmryimv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xobrznrp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbagopy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlpwkbs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpbbown.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxqdhcm.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdladzty.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hrivsqkq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwqzfrz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2aslxjmpj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2iireoabi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzmzaay.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dgummqdc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xslaodxy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2erlckrlg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrapepd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhjlbny.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbpocoy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcfvlwr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxsfybx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvvnyfw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fotdgnwx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnhigjg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzbzjpa.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qoazaplu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqwgvhq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2flrdvxsb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qgulxjlf.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfcensr.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwkecxk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxreidr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkrnhdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2momemtno.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvomlxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qikkytoz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2otiejuct.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sipwmpdo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkkmneu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2znlcxhqz.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vayjdftj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fouggvsk.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sznqjkyl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tonttaqi.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmdbmmh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2icaxazjq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lenkculw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pccopvma.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hilxyumz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkvmlzs.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dablzhlf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vreuxchp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxphxpb.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oovyccdi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dpucageu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ziddtlhy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwvdhzc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mabsuwuq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jctasiiw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwblang.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2myyxstmx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqkeybt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2evoarwnl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnnwajy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfgzyee.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2awnjmmmm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxetlyv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqufxqn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2khmwfwnn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eijvwraa.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwtyqnp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2pcezdkty.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2whujhhvc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxongms.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2zirpwvqt.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mqegpqav.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjqmriz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bkofokgy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wthadpxi.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xdayukfz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qoikpzpm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ytobdtkj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2esfnemyu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2yxujhaxk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnvmmbd.html


<!-- 参考信息 -->