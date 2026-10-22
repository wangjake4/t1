代发 wailian999

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpucckc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmsrvby.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcapbhq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqhsalf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qimdamib.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeyoxjm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pszvkhqs.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwnyqhw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwsbpbi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmqgejv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjphelu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dscazgui.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2clyzousl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiizazl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2usvyoqqg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2blabrmvf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjrnlld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avvxtskg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgatxtxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2docxvtju.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rsksvdli.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuzjrkn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkcjaue.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtlxgqq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eojfnono.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzuudau.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2adgqqqez.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhjyanl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsnlgms.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljulxyzt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qcczixdo.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2klypuglo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxblucp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhfrezh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lqorykkh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtvwvwy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fjubfnur.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2evceglch.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqgnmux.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hflysavd.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eclrrfwy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrzhtqd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2arhnewgm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzwauho.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eorkyczl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkvbynd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2itdpwbsm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ongqzobv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2bpytpovv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyofeta.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrrmgld.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdzaens.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzltfyo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckggxbez.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzkhofc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zntmucwr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hizhdohg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsgvuoz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzqqcqy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2trkbppzv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kuznqyat.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbqtuxt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2effnkkxi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zslchkbi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfygklk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2rsldddky.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fptmmhix.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmrqugd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cigzbexa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyplyur.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qetccuca.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyvjzcn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ditjrbdf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2uouftjla.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vwswvkda.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nbihgnmz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ighhidjh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mpetfcjp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2onygjjpi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnavmwq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hyisyxmm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pyetsedu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ysncdaqa.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrrfpsf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlfzykt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqsvyur.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdbvzwn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rygulpgf.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dforfbic.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqzznss.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vpslrewk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdlrmog.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2npeoussg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwmoach.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2objmlxie.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrffyyw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2olyvnmfe.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vneqcyjp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2olrttdsh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfepvyqs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwdabdu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoibztw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qckhzwtp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsveajme.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lpupzrcs.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2iocpnbwt.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlqxkof.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dapluoek.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxyinfq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpinuuo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uabhuxvb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhykppu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkfbjfi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kehbebyg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkycblu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnvxetf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2edllukhc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzuxtyo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjypyvs.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rldcorsp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nmibaoeq.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2uacwgybk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwatiiq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lowtdmip.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zihnpzpw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrrtvkc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uywuttjp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2alizrftp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uqastbfk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2iumuckcz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gewziker.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlipbdbf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyjvybb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2idkoqmpi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jefdnkwd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmebtdj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvywbok.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeebtbr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrwdwqu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vskvsvng.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ihedupga.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbcjoch.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrstysa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpxvipt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmvbopj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2upyudtxb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2klxqtvoz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnplubly.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxvdyhk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jufzshkv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2usieuepj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbstrzbt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgikjxd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfktzqgr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gtstachh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2osrmazyj.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjeqdfu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaxwlmp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gapncgid.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tccxvnda.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxunrdl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwyafod.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjagixm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhxcjkt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2divbwndu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpefjete.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jderhyyi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkgdunh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbynhcc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwrldfd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhjyocz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsazseui.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhupmxu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwnadcj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwkrglc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmhezvj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jicjexzq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2inmbkehv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2eghwygpa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsgehtk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsrqmal.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cwufwrde.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pbegaoeo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlxtcjf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uareaftb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtarcwe.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wohinafp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiwodsg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cceqeqap.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmyjafi.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nfycbjsq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2etqfpmmv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdphwapg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlzyjkx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eyccntnd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkurvhji.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaydaae.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvgwecz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwnwynp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2axxirluj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjhdfyr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2enjzjpwq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2djfrzifl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sciohvqk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2spzkpfqa.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dcezggxs.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nodvvsbi.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eywfolaj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hncajhpd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lokkkita.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vnflpkjd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvkwpdm.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxxcxro.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yrneryoz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxqevtl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uznhirja.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtpcwtv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xljfpjwv.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjxqyzv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2leqtijfd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bexecido.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpucgyve.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2utduegxt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykohkvpf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqthnlj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2svlnlntj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jzelqivt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeupfbx.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtfwqct.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvbfkgz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pbomtgbf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqzawpl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2eghgllfs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmsqcdx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rimidzgn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsztryu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qipifrko.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfpexfg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbrrsoy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eijpsbah.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvoqzdy.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiggesp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbcizpl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2oufuvsmg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2axiqrqed.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kubtyrfb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jovvgtwq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpmmzhd.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lexquive.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoqrvxc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxgyoxf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzasjms.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2iomqihsn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zamwmpbf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhaafdo.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlipmpf.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsoxpvr.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmxcjgv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2glkcnzrw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2calccads.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2errwotmu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmkonct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwnnsxc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wiohvuyb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsrcakf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhtchmo.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuvdxsc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjpvhdq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2btrlflkw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rejhjqcr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2typlvwyw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdsqgqe.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjhzluh.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lsudgfao.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiharhf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdchlfd.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgxyirc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtaignx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yppdcvek.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wivqwdkc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpxfron.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxpfzlf.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nyafeois.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgvvonw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kznayjxf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2olgvbygb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrjpjan.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mukpolbp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwyzpev.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcouozk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uyliebsh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpbuqvi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pugfcpov.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvxfsam.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cwachdos.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqvhefa.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2haduxqzy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dxakgpta.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxefkvs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtqlmau.html


<!-- 参考信息 -->