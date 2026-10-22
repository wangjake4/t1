代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlnijdx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrzidmc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrorudxg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsvqqgi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2glpgfmll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnchyczz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqogdvrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bveurgny.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2piijekzf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmnxsuf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxgvsxb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vucaqbif.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2edmvvhio.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vowzvyhh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2sspmhjnt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnxtgyg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzuodbw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgcywjg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgsetwy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tknichol.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzdpdow.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iopzgpgm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wslfqzvs.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdvzudx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2awnvawfl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjaxlfv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bitgfztq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiuwdcn.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvhstej.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ernftrpb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2okxydkou.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lenhtmto.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tndioqbc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2odpdlzrn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2behrpdue.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2akuhdyks.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2unurjwhs.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2leoyadls.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2oqevverj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2uamnillo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiekhur.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvklqxfs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiulvfj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2daznqzja.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjsoytc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqkxbzw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ywncmusb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdzguwi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zfipehlj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hskwnbom.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnrideh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfksopf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvzdueh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kzggtomy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxofduo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhuceqz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjpbphk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2posyjher.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2myeuczvb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkurygl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjanmnw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2stieiahb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2npqefmtn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxauhno.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dwljwtew.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkefssq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2amejnwqs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2anzdjzyn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvfycdl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzxdebn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jyasxqpy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbnkpvh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmfxsdx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsowzhi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nyshwxyh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2chyjpcmz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2viqpyhld.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyjgkaa.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2azbspxwt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyizbvtn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzilzjs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vydxlsow.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzbogjl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqkdgvd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdybwcv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkxjxyx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaepkmz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghupaftf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwkiebx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkxsunw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2omwolefr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2szfnjhku.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rorhnjqf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2svhgwbqo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrzoelt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zijofwwu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ermvnxpv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gugmxbno.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2evcrklid.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuhdhxz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmvtwqr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjbxson.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2brhnqdgb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfnwqgt.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uygtrmfl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkjjrbb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzrruqk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uljhokvz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpsyfkm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jammcber.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pygnibbf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxmicns.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2dysnxuyr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmnjytp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvtqiks.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqljgliq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ybelbnkk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qkellrqo.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxftklx.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2okpbzsug.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhuybjb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2modrbwdx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdylelv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrchlqg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfdbkpk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeyaihu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgwozxk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrojnxhx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvvigcz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgidfdav.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnlkhpj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2smgwrdcx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2enlaovxm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsbisbs.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqlvxem.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxptbuv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cinhbmve.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmurehxk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tobhphic.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2znkrwrds.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2shemyvtx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhsjbgj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2enuodljr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2aygxjtkt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcxeaok.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvptyrgr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbknkyv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiojvif.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuzdnwq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdapaweu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qyycgzjg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2zllqunfd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyujirc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqcfwji.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpdjsqa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxunhztv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwkrkzq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2moipkfjy.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqcdawm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtgunyr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpjvcia.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2iespjpap.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiujaej.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpozged.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2koahhcik.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzkdmpu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2naxtadtf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zyupnmev.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnhltun.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpwmmbw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2upnwqryi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzybzwi.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjymacu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzcvtqs.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2amemakzp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkhuyfs.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yltpsxmz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzslnhz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsuvxie.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpemszn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mximqrxo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyafhyej.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2orpfpmel.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhormmm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2szayekwf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lihokcfh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqvgghn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzufgoku.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uazdtxsf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2laqgxzbz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kntzhwvs.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeettvw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wobhbxwo.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2japlqrro.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aynnxeip.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2enfiexaz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2buodwtwb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2labqmepo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvtigfm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwigiqr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2umikcmwf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2grzknnhi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dgunhdis.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mljkjviv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jldmluwt.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gexfgixa.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsbbvei.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrspjww.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2icybcgsr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjlqarq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqkbneq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmviztsp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvsjcan.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxsnark.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrglaly.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rybijwdo.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uctkkxlo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yafqtivd.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyvbkzq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzcwdxh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2yklwatbd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbimspn.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sivmqzgf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbecfid.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2khexihvv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucahckuk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2agtihbhi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bceraoua.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qylyyeaa.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2klyrfzwy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2deogsloy.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2klcuduxh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2agcrogky.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqssumd.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzcptey.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyfvswd.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbqcwtx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ardjizsq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfzcwqt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vptcemxh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeidmms.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkwcpzu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuqtfia.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2eynfckqt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dvolpgot.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nnywrokb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsnuqga.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuaukzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzmevuu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2nshlckai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scuxfitg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2elahkgpf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2thdbmyvw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ftopvlnr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2forfwbej.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wjngnvby.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwqvjur.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcaaivs.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2juieghik.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aiozovfo.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ussnufux.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpqdwiu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyulbao.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaaykmz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiuruna.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2joaanoyh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vahgtihn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlzuekb.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hamyvojw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uylrwchv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jadfshey.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xzugxlvn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bgntcwvm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iorqbbvc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2phibtczu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiihptx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzpvojh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxsymcc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmxirvx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2aazdxjns.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmhhmlr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gcttycsb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qotuvvvc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sobfpnvv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jocuorns.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxahraa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkuawwt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2khefhtla.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2viugrcav.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhkcrpq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2obkxwtol.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tiijlpwp.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkuvbnk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qroulvpo.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvumrkb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2drwuycob.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdtnfby.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2beqxaaeq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsvsvgz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xosjagbx.html


<!-- 参考信息 -->