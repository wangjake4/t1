代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbenmhe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2npgziuee.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmswhwu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyyqksu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2birtqbwk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqthrqmf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxwctxt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgjlydo.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2etuzevkc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqnojov.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gfffzrfb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgtmizt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdcvrie.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbktqhth.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wpswfmca.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nscpquad.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2anbqbowm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfadzodq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vzusqxkz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnpznzl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qztlsnal.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2caigwtwn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pirgdpmk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwnyckf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bgakobra.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbfqqyq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gvudijko.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzvbuob.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cabxzpbh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhymtwvc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2elsphphz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2iurkaqrg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxpddtz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaeqwfh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbjtkmz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gylocxjp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xalixuug.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oohtnfgd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqqwots.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zivmwwtx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnrkumf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hiztqqga.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdalhvl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnmqknt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkkejeu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkakfzq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eeduaowo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtjitld.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnxonwq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nomrshwn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2krpqmdoc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2psqnqops.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2agvymejv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2afxbyqis.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgfkffn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2igzfylqc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpwwyrf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2siufzinx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbefoct.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzwhkod.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2maazfkvb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2leytavdf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgyqqvb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tctrqpju.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjhngzr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvscsmv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mprksbrk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdswbgb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqtzpiz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjhtntr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iafzxyhw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rohkangy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdtnjdg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2elnkujso.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ofritguo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpetmaw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hbffudtr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmetuvq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bruzswoy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kydmhypy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyogxri.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wshjyxnz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuyydmn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yufelcyu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqmporx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgccthm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zacuoalm.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2brlveizy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2imkasxjq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrhwkor.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyntywj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hfunffho.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ylruclxg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2okohkklo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hguvfamt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urqvtkkx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mkulhraj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nnswfivv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsblxyd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzjfmvl.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfoioxb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2garqiusi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kajmfmkm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzdefwl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rouvrsrc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2eazhgfax.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cunqugdz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2eggzijsl.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoxjfaq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2aliswhrh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuagkwf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jctmjrnu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2guteogsy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2medlrzvw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlafxah.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxobafn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gmguftap.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyxknyg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2eognxzza.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkpunci.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjzcedt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyjkxob.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eitbjibo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvyupbn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxbwtas.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdonnyhh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yxubbzxv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvklyxyf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rviwixer.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oojpvmpu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxqlfiw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjppktnh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyehpwx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwydqzon.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kppzgskv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtejfgx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtbjnxk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpaqxna.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmkrkug.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvzmwoy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fklfnbqd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2diwpjnyc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uevaqjxj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqgbpig.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2syzpepua.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gelqxbdm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2icehjmhb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vytxxukf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdgqlok.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfwxdyw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2benstqmy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2yetmtavy.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2akgghxww.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfydrbu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nrldarkt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lfckwbkm.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2boqnkjlh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkgmimn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gvolltdi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kczgqdnt.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lkccewdm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2odziwzww.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrljptf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvppzit.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpjmxea.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaxxnzb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjmnfau.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcmltix.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2oluxhtks.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpwbjyb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkgzrzv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkfdkse.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnckmph.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmawhxp.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kxohssug.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxyjuyx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aonfhbuy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zuntlsbw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqtapjv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oibhlapf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhfvxgy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyaivye.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2erfwnxom.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iitvukby.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2srqkfndr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mahcrwcy.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wydptdwc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwykwpse.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyxgvnp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2icmndlqk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzgzlas.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrbmyve.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pufwqcyw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxjgski.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rrejgmtd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxuffbc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2oojqtmkc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fxopxnrt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ldomqlnt.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2skvlhoib.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxmzkls.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhvlbwv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ephpsjrj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpelbej.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoavnxj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfxcied.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxpbpwo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdnnhkb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2oyccgcws.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iutdqqhn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2molqaguw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bndtutea.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbikene.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjdknlw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfaaoen.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkuokub.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2geidfjgx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpsqiio.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdufcjs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhnorvr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrppboj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgqwozm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2aljyleij.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2sweqiqrd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgqwjto.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnisxgn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeywclf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjppiqlv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xzazyofq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvlyrnv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2edmccrjn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyltkkfq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ryphbpox.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pbufkkyw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2znvfbyhk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fyquwsjg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnajsap.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2saxoufzy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvvjxpu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqahpnj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqhiqvk.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxxjwno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2colrinve.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrnxked.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bwejtoaa.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hspmbqto.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvqkmww.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ayosflfj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhrmkui.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2miwrlddd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2genkxjsb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ltigsgfw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqkmjlc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkmsvfe.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fjputmhw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ubelytdj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nntmewty.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpjlmzk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfonoot.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2glnedzhz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2altrfvym.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2syhvstmb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2snluerai.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2neyawvxk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmfsujs.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqsdroo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkdhtvn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtmqzib.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2giejykku.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwxxnmq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwlcqka.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mresvlzq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbwolwm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrwdcje.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bzerfbaw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbdnbxu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cczzusbl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2azonkewx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvnazys.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrbtxxw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfdmvmf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2pugiipec.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2arzozolj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtwdqob.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2nifwlodn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2adofpbnx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxjmpwq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzsxvog.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqceyoc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyzjeqd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2facolhal.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgcibvm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bbubinug.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbeteyl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzfxcgv.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2iovrguxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpqxwyf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwwjhsj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2dndnhkjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iatwocyc.html


<!-- 参考信息 -->