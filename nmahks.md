代发 wailian999

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeqrbdq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2clixklfc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyymclf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tokvrmci.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmtajcc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqzwlfi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2emdkjtrx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmkstql.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rragwppe.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qeefidyz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgcdmip.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqmerrg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcrlrui.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfaxmfm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyxofti.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvskjlv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbhwoku.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsqgweb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kttbwyyv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqyzoqx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ydazctum.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpkdmeo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaxgbho.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngywlahr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjonvsm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wecgqfea.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwffkqw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzckjhfs.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbtzmip.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgskgskm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2abuucviz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzidzbat.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2balhsuxr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jksjirly.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjmnqcl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2clczrknr.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwfdurs.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaxypge.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuqznxe.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujngvrnq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2upqfbowe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2terluufu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgocnoc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgubpswy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2udabgmuj.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkrkysp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2joquohbn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnwwoxd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2efsupikl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfkdrih.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kyncjkak.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zphtleku.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxjmqgz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxecsso.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpmwnxk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrytfdp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2coqezaww.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjajfel.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hedhjmzb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vainghgv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2flchldfg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkejkedz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjskqll.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2saqzyfvl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhqmzbe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2paeuiuqu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ebogmbze.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyarlthh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zhleenxt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxztlgh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwzomqf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wwycfgff.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyqqszr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2spxvxtpj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sasepfkb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tclkuwps.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tzscalcj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjkjszd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqhppyz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjppcndb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nuayxnfk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bovzidxl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkdoxpn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoswnqy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xxneodvk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdehhnsn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fthwrzwi.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2whvwxlbg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuwisyi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlvtvrq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2evbrbfcy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaioabi.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlspmyz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2lsigucbf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jsujdjew.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqnszco.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvirdzs.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzynhyuo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2msycgstf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaguapt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfwqvdx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2drmkcpzi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtjizcj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtynaog.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nmybaduk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdpsend.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmgeqxk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfutjfbg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxutrjv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcilckd.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjkmfvy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcibbtpl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kijqllzn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjgnnun.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjvsvnh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsmbvce.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qdemgajx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnizdto.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xuumcvnx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqhxwod.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2aalmdfky.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnbtspc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfiyefn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcslxxd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2iickiotq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tetmdsaw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lnczshky.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqdqwdo.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzmwzxc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifytvklm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuvgclq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xokzwfex.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxcycwm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqyhntj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2abrrsral.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2oqehulas.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ardunknd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eihcayma.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cpravoai.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fudulcyr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2awocbopm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlatbwog.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2glyqtovn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2enhqkwtu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2exazkest.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ibijfocv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kahiedri.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmljihwu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2svrqizfa.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsmmezz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xkilecwg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2chyodltd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vildmtpo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2miqmxpqk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvvcbmq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jsictqwd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nqalmcpb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjfaxxa.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxnoohs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypymiuxp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzbnnrh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlcoqon.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqsquqg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjrksvd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzcmrha.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2udwgeyiv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2datpkcey.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhggytk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvtwkzn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoebnpzz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2smxtujpj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqsjfix.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qqreodws.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tliaboxu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfmqiql.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbgyypi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2omjqsnky.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zqstnryl.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zeztbzem.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkvqywr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnxqome.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2svynxqwf.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpyibnz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxxvcaz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjqqjjb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdvuvjl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbmlrhg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqnpovw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgdqbzg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2epqcufiv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bdslpluu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rurzclng.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2otxjbmfe.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsjjgwq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeegpti.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnirmfdw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rphtjrip.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vraelbnc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnbguaq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2merxsakk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2neqsusmf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhbzlft.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lntwcwap.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dllczaio.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vuokqsnb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyrttlz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2onftmajq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmnahur.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmdypaq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2stjhqtpp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnfpwrd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gdonzxtj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2glumrdrm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rchfwuay.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lifjcglf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jlztauzh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2htbymxsc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrnleya.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgwpden.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrxqtmb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbzcdma.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2imaylsoo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oowemovi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpepqmbz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tgycajld.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlkwqwm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpohbss.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fscmsfkx.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcxaens.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyztfcz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwbdpul.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfqiert.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbrelyj.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2iowogqxn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnfsyxb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2asryibzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjasibs.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqmehwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xveykwzn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gushslww.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dngzhzvu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpndhjn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmzgvua.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mnflapoo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbtwvup.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uaemxkqf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlbarrc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2onucezdk.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lslbeecr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2owyjlsaz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmhoinn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tvienqlj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdheqpi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbeiwhy.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvjtpkj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2esfgcvyw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2scnwlioa.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmqefpe.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlitvnx.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmyyktu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfvgwov.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2adpwhqga.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlbouur.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ajufraen.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ihojetjw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2azdssdxs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrpvpba.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnoapma.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2brsqjrjd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yqemewuc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2illszfnc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhdfzpv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoimpvh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzzzrqw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2momlbsgx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnpdlmy.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2eujyopti.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gknlikai.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2clgfazci.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjaltbc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2adndirud.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqumqyc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dizbnjss.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xagzxomd.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxsilxa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2upoenrou.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxpgtek.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2sexoyvmh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmglvak.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkqldfe.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxgvjto.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wetnsuxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeezgjn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2jueibynh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdeihmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcnmpho.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxafbus.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpjvtfz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2befflsdy.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2psosficl.html


<!-- 参考信息 -->