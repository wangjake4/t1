代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjhqnqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrgckxr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttukssiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfvmvfz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ynstnkjc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfomngg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjsfazt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrouywg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yphftozf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkuhqdt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mylpycya.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkwcvnz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2paaaakgj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2baykymyz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xuldwjau.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyubskot.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2akvxrtxr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2loiwkewo.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2honbnewo.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jerqcmin.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyvithl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbyuzmz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vaeurxxg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzyaynu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2njnzuiwr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdchnvhk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtfruqo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2krdqweoj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vonrrikv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2prmectci.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyvpwwh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxmpyvn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gnckmvon.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqisfku.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmpcxio.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzavhfv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbkasjf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gllwchcd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvcdyew.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2amvckcva.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwmnfqb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnyhahh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qgootgfh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2grvfazgz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpurhgx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqkmtsd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qisihklb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2eorokjzb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvbeqnm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2usteyjin.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wstjccfi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvmyihk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcgqacg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgmvtxf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdedbfa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcrrfkt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbhcbtq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fonmzxdn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdqznli.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqmxuwz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuuknrk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrteqbd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sdulzzri.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2khrvdene.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzmwvff.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2agguherk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzdzlop.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2cwynxfmi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2guewhcnu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2aausrfie.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lckaddxp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uggszndl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfklskb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2twlrqqeu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgpwpfk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnwcgwv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fdocidmu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdoktui.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgczasj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kmflcoko.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdqnvnu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrcgelm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiuicbz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkdmeql.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bxflbigt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2byvegzxr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbfeiui.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiibghxa.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmegcts.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhzdmoi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwaqhif.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnhlekc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2besjbtwq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjokasn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsltxqar.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcyyblu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vdushvqe.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kajcejiu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dhizhnvz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qukcpfpx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dplibpby.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2tteomxxj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiwrepz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fikrzjyg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vilwwyxf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqhmosq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsdtksg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbgmign.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjekoak.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbvfyml.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ugivfwkh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjzaauj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzbuyjr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtjaphc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmwivkc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqvqgbi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcouzfh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2leeqekre.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hzttyllc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvqbqji.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvxhvrs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiizezmi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmmzmdk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgyepbj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jeppjzke.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aktbwowu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gisevlkn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxamtkpv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2obnhtqpc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2urukndyq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dccfixhx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkxnjqq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ipifztlv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2skmwxutl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmmxddp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkbwaof.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzabapg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldomsmam.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jesoawnr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgzidgd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2slyunmfv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkxnkkc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2txkjievr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbemrclr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kewwpceb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhkopex.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tcendozk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2wivvqkpx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfhdcyh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrndopks.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zurdjuhn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmtnngi.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiubbhy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2usgxvbbu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuiufrs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgcbqck.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfzhekt.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsxgfbq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzwlpqo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwbetbg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdyrfnx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xscipsfz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeiopwb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hjchsrtr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2amseqrie.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhvzjaw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2imziivzj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsvioxo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxjeppu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtxtqvi.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2efhcxoha.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuymeqb.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vjokxjmp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqlxppo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjxcyjr.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2chveqkrb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2srbisjnm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2igxocxzo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oammizdo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfwtcrp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nmovkejo.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzwacap.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkqgibp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoxerof.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2epacrmpk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2akgicrde.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbjuabq.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yffwkfdq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nsapathj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxocivm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzzcbbt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hclpjwgr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkqmaif.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2afzxbfso.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oyagavro.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wphsigmc.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lqopvpjz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmciwft.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lomaxlls.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yusujboc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2baqfbfmo.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hkummkdo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bniuazbw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnokvxqw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcpmtcx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuphaon.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cssncwna.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaznigh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcrgbcu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqetdua.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyssfsf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnjxspl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ccletaqj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxbesdm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeikxfg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdsoczp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zcatjcaf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcelbvuw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjkzfys.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2czduguid.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lumzahsy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2eilfhsmk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ecleygjh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmkinnq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rnynlpag.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfwlpyn.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2omydbsbk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gewjjcuj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxveucx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfodvjkq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qegetsup.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kasfsyko.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaatkkh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2envdevdp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xghmvjlg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzkiuvb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ycliohvc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zewsgrsv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uzadnffx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2twdpftvs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tywbeejj.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmfbovd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2baroqhfp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2quibecdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exyhtpgs.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kctuytzt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltokknhr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kldmebco.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpbmfah.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uelmqdtw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2chmrhbdr.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuftziu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjhucxw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuufcoa.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wycanpke.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyqqfrb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2teqnqxbe.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2viitrzoc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhiquev.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgodnpz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lpamcchw.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdxjigf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2otaazvvb.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzblbxl.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2unzabyoc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqzcijv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jicoqpsc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vidcmlec.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kleelrym.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2skcoccfl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tisgotrn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bceazuvq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbkhavt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hluacyqd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2merpzrsl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwroicv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsqxnwr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqqztfu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzgtemk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxpqzkq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwbwbtw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sohtuqng.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtixgzm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2krjevnpg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lngysvkn.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2esshqsjt.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjmjfse.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jywzgehx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjmsoap.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpjtxwq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ejatahyj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ipstomkm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhlkdlf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2azwmhilt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsiycna.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2caxpjwui.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2twvmftmn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zubmcucg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuynyqq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2uymcudrp.html


<!-- 参考信息 -->