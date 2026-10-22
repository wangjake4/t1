代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vboclomx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pponxunz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmvgkey.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhuuxbc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwbzzyv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsltosuo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yszjgslh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crubwtki.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2inttgejd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpghvkl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgpfvln.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2frdjdmwj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqvadda.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqglxco.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgxiodm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nscqndks.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2onfjndhc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2alxmxzcr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjdvbgw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cyolgvzn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kizxhtfr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxedhpi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2beaqmhdr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2agssrmgm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqqikvk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsmfnrl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtexouf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2savxemvf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjpzujt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sizotkdx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfwdzyv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ednegahq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2krfxhgmo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cottmnbx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoqaztu.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzhoefd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ewohzzbx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyrgcfv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbzhiih.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2eiugsmya.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2brhkiplr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jznfmswg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2apejkkcn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqazlqvg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ayotolil.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwouwrvc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkdjwhr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzoxikl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zoapfjwd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2exlophzg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hevtmqnx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mggbmhpq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2okrkgsoc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwpofii.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbxpecw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhczcdka.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpakrbp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nepjfhlg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxvbhov.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsqkoac.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2laaccktq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkyvwpm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vsatjbku.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnidkwm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uhapczmi.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtxvsrm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fruwpqwf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2awmnlfcj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bfazmzpb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbqrrxp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2toppoiur.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zemncrry.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xaewmtpf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2icefwyne.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dghvaetk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgcfhok.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpfdweb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwccisc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xighjxbp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jodvtwxd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nldajksx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpgvjjz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmbdpvp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2iegbhbtu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mscosuoc.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjfhvfb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vlviffqo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbzvrgu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2valilzjj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pqeshflx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2eskakilg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dndnnnny.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmkehxd.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxxevsr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oujhlybr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2csehfrph.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oibeadji.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axsxhzst.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pprotnqh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbfquwt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmagmpgo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsgjehw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2enxxxftw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fursxbjx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmfkxpt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2prlqprib.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuxkpfe.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqarjppa.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2egycksoh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvjajfm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjjwpiu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdmvzqq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvqbdgk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyylkmd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rxetrtrw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2izgnvsdt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjcioea.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2klalectd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2igjaoswf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtcaeto.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdbvjgi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yycqeoki.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtlngvv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzocils.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yhugsixr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcckvfjc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ucetfulw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2briaopsz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bucfbzih.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvtmmjr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uzubfwce.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwvxbxq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dydvgrjj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cogcgecc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsijxne.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2kthxcuhm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2jckkrnqf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwsotmo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmwmtcg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghstbugu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxicrji.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpotxhw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jbakhxxc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfjpvkm.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvaprwr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqmfesm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2llgombqs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdehjxy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzaopdm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyergujo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uiobvjax.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hrerwdpm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcgutyz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pglikznl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmjvuqv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxziejb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwvsfss.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzfheln.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2uajgpnpz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnalnfz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeieabg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdtfhke.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jaewdkrr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfldukb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqnbipi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2altkevxt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2euaxnqvd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2msbsvcmw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yduhdzwi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zueysabf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwsaprb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyinqpy.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lgslvbyw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xychzthm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gaixylsg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqijkrv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2aisbqqnb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzudzkr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbxrqhh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqjbrbv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpupkkf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2krqrsiah.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpcldry.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndktiqom.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhjmwyk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwwgmxc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2czuiowrh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdfblup.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kxplbaqt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2iojyqyev.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mldvhlej.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2efggqetg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyjgrmn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkuixfw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehehyngl.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pveoyhet.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dfggjvqu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwpkjyy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2urspeecx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abhtdkfg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2skzvgyes.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sitsloni.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pfluanjl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhfugff.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuuqxfq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zyexscqj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmyyjyv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsvigrs.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkuvrmz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfllyend.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkxlqgt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2podrmovx.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwlmqer.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2limtular.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnnweca.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqwvupz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnldexn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjtnefy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2quvmiyun.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2echqufdd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtupfnq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvoielf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcnwxsl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeoolvo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdkxdtv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2coyxgzsa.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnkrltn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsrtnsr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bniqayxj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2skcylboo.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2azofhjzn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvmycqm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tocplpme.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yndjqfzb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgijbxl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhqawvb.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhlgzls.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrrianw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wypjcnjc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiierern.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pccojtlu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wsljyqrh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlujfoc.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2czdtohad.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2cyksgpsx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxpxywt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2eovpjdcs.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdyooqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaakubk.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2nkubhiik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hphoxxlm.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mhffvxlf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyufdfu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oqokczuf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgrmxvx.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qimofrxr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjxzteu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2guefthyg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hvehuvej.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zidbejvd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fgniqbbv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pdncmqqe.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgicfrc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2esfvmerg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiexglm.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhxxgop.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2quzgztwo.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjqisgs.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lzogdltz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xucwluvq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkodirj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmivnva.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwgvsyr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nczjrbuv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2whymabrz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vrronsnd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hguuovrh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xowhgzrl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uunqfnuo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2joqygcqp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2shalkgqc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2btyuxlgy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuedszo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2akktpfyh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nostlhir.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yknrjymc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcbwlse.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvdgdxb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtcffgg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwovbic.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfcecml.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2blutcvyu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vglwrsjc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yfclhqxg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsgasio.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rckuebnc.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vbekcgtc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrckjlp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnmnjaz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnuigrj.html


<!-- 参考信息 -->