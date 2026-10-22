代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eypkjglh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zgegmbft.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpliqyar.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzbfnfv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuneecg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwuonrp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmstefrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxwymiy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsnrmmn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrvvxds.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdxxnwc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gitaqupc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2konweyzh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvtihpl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2almqpvyl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsbpira.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2psewtdwy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmkhljd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvplmaq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcqzebu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkjwnhy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvrvdwn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2blwuuieg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhmyjuh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnnclaa.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrykwhd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpyjwmm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhpssgz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsvqahl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bankblmy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnushvw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjjrexs.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pnizzjme.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dziljjvd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2erxbwayh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvczcdy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuytvvp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmpxwpt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvyrqrc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xeytstxl.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmiuire.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxqbgvv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhqqzvp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcyhwaz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkbzpem.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwckcjb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzfrqzs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgajhmbf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2swppqtjf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmrlncz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zddzdpix.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xyodzlcw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ernsenop.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ectcjcqh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gggzyelh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aubnmamf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2caewrpvv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkjkmyh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgcyehd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2phnaipst.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2degrtymv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2snysbvbu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyrnmat.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsjaxyb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdplhkj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fudmsqzq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjzkeze.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbdmqcv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxyeiju.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2joquoowb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bnywpifk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxkrhxy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvcmdiq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2czkcofsg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlagbun.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2aczqzkhs.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndudcjmj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckixnbqi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzfipir.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2uassgeqn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2skpvinuj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2efkfyjek.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ntytpgxi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoacdzj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrotcay.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2geemsmbv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqiazrs.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2trzhpkmv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkbtaer.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pbapkuxk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fiisigcc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uehlqwoi.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2eerjlcno.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjyrhhq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnvrcvw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqcwogn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2adytvsoe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaqouwv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wytbrnub.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2heexmhfc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2adqeclyq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuzjild.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zlstoxvr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtmvusb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ykudzigc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlkmrdr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2idzypkzg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdxxhun.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jhssxrtx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2awhmroux.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2puguauhs.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kawowyto.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xbizxeew.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2evkxjbqp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2atwszeye.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpoeoylu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2osrnaweo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqdzgbo.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxllygdm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcaeztj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ungbpubw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtsfjlm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2myvmnjje.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2osysbmfv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pizawnij.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2khqanaht.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2exxxqtzu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnsepbr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cogfpsga.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rystdjsv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbupzyw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjamtmn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmbtexj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xswybnhu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iggxoloe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcglrky.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnjpsnc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnzqlwz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjyabdc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wginwmxn.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2oveorfon.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwvxkzp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lovwxyfv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkmhbhl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvtbbeg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdmwvsv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyqapxg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qoicsgqf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxxpesm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcztqxyd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gddhmrlu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2uuceyzun.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpinzes.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrpqrqj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcjeboi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjrywzp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jokykckc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cggaprbc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdadici.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tehfwbzs.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nyshwwwr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbcrflq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxfnkna.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2iepuhiec.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pednpozp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2osbsnhti.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2seuiyrlr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2yrngpxdr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jypzhbhd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbnpapd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdzcqoq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkumcymc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwzupeq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uktmitga.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xmafkzgj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgzcrkq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbkhegx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xndrllcl.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2laamfeug.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2oynvhbyg.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2riyuummx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2lweiomii.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oruknwdr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxfqvvs.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhtbjaq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pooztqvj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcgielu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcgadsq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdgbzhr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jearafvj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2szzqftyp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjpnhny.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbuztrj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwcuspt.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2quncqfzb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2amtelixc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnwbxpj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyjpczr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwbxizj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pokqkdah.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2clqacwrj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwygelua.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwfryre.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfhrrgg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqmannu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2enibnecc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ymimvfcg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mycqgfmk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwwirai.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrrqygn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlfrfro.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hplxsktr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2afebbibx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2joppyavz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzuevam.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmczohz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hobgvkcf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpumvgz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwqdfut.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqjtcdr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdtlifz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2etmmibms.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2biyejjzl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrfgmel.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2prscgmig.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbtytze.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2iduplvop.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2alpndazz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cektuicu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvehcmqw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2frkaglzg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wywqyjvd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rshvqljh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsholql.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bfucvots.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2phjrruru.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qtavihbz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2plltcuwz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmdtxul.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmaqwim.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzckfnj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbpcvvd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnivnks.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2laclwpes.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zufzlhxz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqifkho.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaikeac.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hinjlccv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfimcobg.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2dghvicfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cakpbzvk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgfkonb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhllotw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mharpaqj.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnmolfd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yiswzrhp.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxgrhtg.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfqgkol.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2disvgyor.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ragzyqmb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2donlxzfw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtiksrv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcvyixm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2brfhmyrf.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2foxezybb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2efhihzqp.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2leevargl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdnhmhm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tizbvyvz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdvbdiz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdeibtt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdtjanz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2oclnebcb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cqahstma.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgesuoa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kleefyce.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2iesffiop.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuieddx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oygdrput.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tczynvss.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bpknvbsx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2peoouxbl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ekveittb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cqedddmg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkmbnwq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjyoynh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2svwhvbvf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzszvmt.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rweyvrox.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgingsr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rywbqycd.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kotngrwd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsjkffm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kxczdpia.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bairyvxp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2viceysua.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2oelkbwbu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrnpzia.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ximrfsdz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qzammtsy.html


<!-- 参考信息 -->