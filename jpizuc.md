代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2quioxuas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuspgbb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtszpja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfciykkh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdmarno.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2whyabple.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2psqddbhm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwixgyd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvypqow.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptglhtjf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kavektzm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnemiul.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwklkwr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbcohbf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdadrtu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ietvxwcp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gjchpmtz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxywkgfb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxnsssd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ykskfztq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vjetgrru.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcttnoww.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2umsgkpdx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxavkke.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ktisftog.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrawksw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzhmjzc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwqehzc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfdmcnn.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkczvij.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cqofooaw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqesfqe.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqjzwtw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xginhkgp.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwizndd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ziucmqjc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnybbgp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2azxbtlff.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgizenk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2niqonfqj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fngcoeuq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qekdhnka.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpapxvg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rewzzjpw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfzutss.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2afiksopv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvmcrou.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2deysqndy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbdmowl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnxlvoh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xpaeyhjx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzhwrqj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rsixggqa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfckbkw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpccdvs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuvjsrr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrgmzbl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwjqajv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqboqdm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ojihunll.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2syqnsels.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaagzur.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpzigqo.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqakuzxh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fvukdheg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhgcfmc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2liuruckx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvnzfrx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtywlwm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoqzmhe.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbgzsnm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnrnbpt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeaphud.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2phgiugea.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pchshydt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nccpmrre.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvemnuv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nccuohgz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuchlmz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hglgvgsa.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iqydqcmq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxduvfek.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2izxemtap.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjxtxay.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbmceba.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvnpcuh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2okjybzxi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihleshec.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2agsdbvwz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzckwza.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2afxqlcrk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuicyoc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsrschm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwtfsnk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2srnsdyae.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fikqiean.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhvvpam.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wkldkqrz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2musqgdwf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opzvokay.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhnvgeu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2lehszcrj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2elxvywuq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtizpwf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjrrtzc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lngnzabw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmhisdl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfatnhfo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2urqetivi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vaekysxm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lwietctq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2xetntnxp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tovoqska.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiosztq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqipxln.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rncdkcpn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2infsbkfu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuequse.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2czriycjf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uakeggoc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuggmjs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqutpvt.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzazpip.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2anbrawru.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuzspiy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2efnalcao.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkwblcq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdcihbb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2juhcyzai.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckefurrb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyvtqzq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnisqre.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrdrutf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhftpijz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2grrucnnb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnplerzz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsyksvj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2oefgurxi.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aticyrmz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxikegkp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmirvva.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2repsziko.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrmiqij.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhzcowk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vnenzpag.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wctganlj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgtsjeg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqlkdsb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rurrlhuk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2upmcifab.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzhzcpr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgsykyz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2obsqhedx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bpouhkhq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfnwasm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2oduobags.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2myqrbrag.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxgjral.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ctertkxn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bjasnsdv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2unvjaozp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkhcpzb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qedombka.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gqriufjt.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2aghpmtsk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbwjuwk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmlhjie.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrjvujr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfymuny.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rchqlqua.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxxhmpm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2usuwpupk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lybnarrh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtfcipm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnlcqrx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2edyzyhgr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2npyrjubu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbelsov.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgtimtu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocepbdro.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcnzcet.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2uilutebg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvjlaiq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2unigkzbn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnualox.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbyrqga.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2txxmlkcr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmjkckb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfwijmw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ramuhjuj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gifexwre.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtusice.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgrszkz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwcusvz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlqzyet.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmfskjg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yrokwluy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfkaaqf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuqshst.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2sonpwbib.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuvxbln.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgawxfs.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zzatsjho.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2glioeips.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2phtjkjqk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoghxifj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2uxupwray.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgsudnr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaarguc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2coveotim.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uoodajez.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2svtmviiw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fektsnyt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbfhidh.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxkzywx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqmcuty.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2medxirve.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibonyalx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkowziuz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrbhman.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjraomb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkddyyu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2umbrmrkk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2sbskyqzt.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrwxsnf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2frsebsag.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jippdvux.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxcczfi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwbbveo.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiqtwkq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqphddh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvajdpb.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsctpkc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuoumwl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2idvwimzv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxruelkm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2prmtabmx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2esrtzgrh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2grbiblnt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jvohsdzw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2grvpqbtg.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2reklfwub.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzwltdh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2aesiywiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yptulmch.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bccnzrlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmanrzca.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2cmohyqlq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2amzswrhl.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2frhsbdmx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyytdnq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vukplgkn.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2krzojvcs.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlnamlx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxymjgz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fksqoxiv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2oppqgoeu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rqidoymm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mevyxply.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tjecqsod.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrbhzcf.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2odajgmtn.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdhgiut.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2izsjztnv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cofqqxdz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvalwtb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwwrkjq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2shkrkvsu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cewhahrk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hylqziue.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyugjcs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxxfvpy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtkpzaj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkefded.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2opgavpuv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoirxwa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2njofzsvj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lagitjzz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzfhhki.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2khhzhitk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2umpjohep.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeaeaca.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2umvrgbjv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2chldqkap.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2pazsspsw.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2eyafhqzj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rsksszjy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqksrdq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhyjpng.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zwabiulw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pzelbzki.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgaavor.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2czwnjfkq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wagpxlne.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xyziwdnf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2lfocuazg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2aabeexac.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfvdgem.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2pevllaal.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2srkvtgqa.html


<!-- 参考信息 -->