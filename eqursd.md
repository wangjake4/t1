代发 wailian999

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqmqwvg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjojkpng.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tddaoirp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiwsvfp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjitzzp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mjekvdxo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybveiydv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2chydgwpj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiygmact.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmljnbe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vioijmmy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxtfjcv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kjczzlut.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqjhbit.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2efootkxz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtsmkea.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxwzxch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwpgjcw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjqqqye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeerigj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2blqfpqrn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtnhjbq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwxgnwg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnyzevi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjqpnsc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2htznpriz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfrfohe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxpmrit.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjyjztb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjslvtyt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eltfgujw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wletyzzu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlkudww.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdoxloz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lonvcurl.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2aixsnpwe.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lctsohws.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhqhciq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xncjined.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nibkejpb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbfkvfj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yizbvoju.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkpxjdx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqozofey.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2csmokzqh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bracrnpt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2syexatnv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2latckuar.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wklshaew.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cekqqrmd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkogqdi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wycdjdhg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrgnxmz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxlttvx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtcjmcc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgjltol.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ycehesxr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2blcpyjsl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyigrgn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2eupcmyhv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnqmkds.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjeazha.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqptikm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwodalz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vosdiuph.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2rybbkfhs.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cufxkblv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqfnngo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qumhhfhf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwwicfr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnipxzr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2prymuhtk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2oshpvirp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2sezhxrko.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiuupep.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2giagnxqj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxbetyx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2naoxgwts.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnuwjii.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfabpjzs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zivvmntt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lmslymam.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2giktgssh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vbscepxa.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fzllcjyv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjtdlrq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nrevctrc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jexfxksh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mphlpxpu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufulzufo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqkuwhb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2duqvzpvd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xteogclu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpkgvtk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpbuipo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pyukexuk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnohidt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2eydyzjtl.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uvljkzox.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfvwjno.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fezyqrud.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyqwkve.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwshnvj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qukrhtkq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgkzkvb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgyqalt.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnmjpqa.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxpiqwl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoptvkj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ockqpfng.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkgkygc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkukwtu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qawulqkc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wupnrupo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxlgwbv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrtdqnd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2buwjsbhp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fefvlmqz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2piwqwocw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixipjdmo.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vorfcjjd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2surcdcbo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yiprccmr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nieegqli.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2muhcxilq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mttscnct.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmpdutk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2guhufqac.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdfjjfb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlosbvf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbjjgkk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmytfji.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fntlkntv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2scerqtkt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlvomld.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsqrmji.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvxtqrh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrtvymf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2arzhcton.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcqsife.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzhlakb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbtxtix.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvmbdta.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2twstturb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jybpdjaz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkxeben.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzgduoh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtdeqjd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnqodnc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwopxidy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvxiwmo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzfuxds.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ogamvptg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlkfgyb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ruitehfc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrocskvn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aqekhcuq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xssnezkn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlylipi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zgucvhgf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqbaygv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qapfnxmm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qekjqjzd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkcgwic.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xjegzukm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzggmjy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqpzqyj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2iikjvkqy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvedbfu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xfweoyie.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mswhblnx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpgqybu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcqusvd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcfrcjk.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzyaagu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzhqsrj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2czscnmex.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uktxabnt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2moxxsaxq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cpajkihb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaerqrz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2txosgbxr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoxdean.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqpuwov.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jkygmssj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrjggpg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsuwrzz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mshimcod.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbqmxeh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgdxvvr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gyepkgtf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2estjjcds.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cscmybxk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwryhipr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ltppqars.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lznvoxbx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nvonaovc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaqxfaj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2trcgusru.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kldkhtnt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xevcwgkm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rhikwcpx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmkniln.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdkzdmj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqjhrjh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2duebxwvs.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpmndpb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnleird.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfewnez.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2adqujtnu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrpzkas.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeoaksp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2eywovmem.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cebslcoy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zrugwhtc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2daxffoti.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmtrers.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkaxkxt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2adxggtue.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqugztzl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2klmktxez.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxppzdfa.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyzufxu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqhiiec.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pvegjvdr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2naicfrjc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zuaykdjs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdqnyjb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrupojk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dokednqb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iarabpzu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2anmdqppa.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2idbvrbik.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmbpaem.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2abzdyvry.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nhogokbu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxsihpx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcpehmj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhdxaci.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2izishoti.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2khmurbuq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbriume.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kpinekrs.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhnuqem.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlbsxau.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jizgyspw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfkyddg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zymheelk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2biycbxih.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2spcwrksb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwfgfef.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxjshcd.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhhydml.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gctjofhp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fyusxgvr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jiguicpd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2covjewju.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqmfdhy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkiepjvo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyghqwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxjqdhr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlrrqkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiuuedx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrtbdqm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvwlbuz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoifzrr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqzvxls.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2omhykuwt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2noiowxbh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2erskefyb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xveywjnx.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwxzvfw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wipqmeae.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2phfozjbv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxbntwv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2asowsulv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqjhqnt.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqudqls.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2trpildpl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrwudma.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnimrqf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2puwuwrci.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhjkqjo.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2buexdwlj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxmjwwo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nodswxvi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yokxgupt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xaikuyxm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xfidnebb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhgonyl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgcssds.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2udckrnwb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrdczwy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qlioxagl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqvfack.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgwnqkn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2akqullgp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2akpzmorj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2aumvgaze.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmzgnwa.html


<!-- 参考信息 -->