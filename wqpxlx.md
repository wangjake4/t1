代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxmyuol.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeuygcl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtwbthl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdgftdj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyxqnvx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2viaqomzv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfxooky.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sbilfnts.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpxxwyl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yduntali.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvgqiwm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wadpyrgh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvasifua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uudqyxfr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovovrzlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2koukkjzh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjjfhxr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkssbnf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2udgyzqvt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsxklxx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvvpfim.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykosykcg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhfueig.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgpyqaz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2avvkfjpk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcmxugf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxncpkn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmidjtr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fckqaakb.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnosgif.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqncupe.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmxqyzo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qeygequx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlelkrt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdzqbxc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zefgghfb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wddxodxk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkxhgbx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zfybdtkq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qidhjnxn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwxvypa.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpodpbrm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2azhqiept.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxkjyrc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ouowhisy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ichratpb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkrhesb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgjzzkj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfxynkr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2idtkwcmv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vylaomne.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbadrzsr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2aqptubuo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bolgegbv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxclvsi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdayram.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lytewggr.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvxdmuo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxeqqnr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqhqqji.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwtxbvk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wiowbipc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbftglq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uudodbbk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2drpgayaz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fctwfjmi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kaolpmze.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmqnxqj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsebhhl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaumzmm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ifokllat.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2baupfuxa.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtxukxn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dataxgeg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2urotebvf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaillwcy.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlpdmlh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lsroebgq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jhghytcj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2depljdan.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gybypfya.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzuhboy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjapyob.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2phsuucaa.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlupevj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiatklk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2orfwwsos.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoshjhn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2stcelcgy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrylhxb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qarldbib.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pyorkynt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzsspgi.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhnrwrz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbzfwli.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqdrhpd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrgncoh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2evukbwic.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjfppkq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfatvmfm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcblsfp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2adejbquz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xuguqzjh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrutfoxn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqyodjg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnsrzgd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrmfufp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcujwmn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2puwjofdd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzutfyl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfhfiuw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smkmtmhy.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsauzou.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmadnwl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dgudaghn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbchtyqw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2skvdlnin.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2imtaxdqu.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwtaeyr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdxnmbu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cncilnvk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxrghog.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaddmju.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbsupoq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cahrysvx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hemecaxg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzurqka.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqmltiy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2frzbyhok.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrplgfq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsirxtn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlrwhdq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oootlozl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nejjyong.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjozalq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqghkwsg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oslrdoor.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdajswlh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vulshwss.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2suuomvda.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrcrcbu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2judfnmvz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2drraheel.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvjwwkc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fmukjcgt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhxutwc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qmejeoiy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iejmbght.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pikpitsz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpezunc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnfjpzd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvmhxif.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2liccffty.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayldmgws.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlgtkfw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiwrizf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xxecszey.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcmrcnm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfhydbu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2trnifmmg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuigjej.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhcrrpu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdivyvb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwghqrnz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ehszmwul.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wquybrhh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bebctfmy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdckpuw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rueyaquf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyapzlu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbksgnc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bifwhumm.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mgycxszu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2udijnusv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjwryky.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbfoyzr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kaunyfvp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2suwxeuix.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2blxbmoiq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbuethr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2guxccbls.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2exyejjca.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2unhvcubg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2amwtzwgm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsqgpik.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2elznqrne.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdwnghw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2aufvgzsq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcxuphk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkmjkbp.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lwddaspp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tupxmicv.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2puqothtt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2naaovepi.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vspffkys.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnieibe.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iijpyyzh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkildrs.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnktncn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwhtxcd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wegclzxi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ierahbuv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaytafx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbprrvu.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2timuxfxr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gumxxyrm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jusfednp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxsysdh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2txufeocy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wsneuvbr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2solzpibo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpnqmdw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxcijpm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpouxmb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfphjae.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xggzwldd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jlaoablc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2teoajfym.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqjtqut.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfouueh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2egmutuov.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2roabibpt.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2sttejjqv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tavwrgsq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qtllleke.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nayxvhmv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2izizuxmb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvfrolm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kztfsmwr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwrwheo.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhlgblm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2airnvopr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jxljrmes.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwmfedi.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vioxppht.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpqsxac.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqhizfs.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqoccoo.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vaabezsf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2avojdxao.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uxemzwwf.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxccznsu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2awzdeowp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyajfib.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bhicikxz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2argicsne.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dilaccax.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vinhpdqw.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqlrlib.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2arewmljp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2albxdxlr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jyamwzni.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rijfzsvx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnppyyg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzzolte.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwaadrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpoojtge.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrgvcvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucezfcob.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdceait.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkdaika.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjhimli.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnjijmf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqsvsen.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vejlxjfd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pegvflgb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsjazim.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gflfqhtc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vokwgoex.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqinvhx.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qytewhdr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcjcxuq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkasuiz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsdvqln.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zkttfwhx.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyfryvv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2duhavfla.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2twumqcum.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbvchqq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyzvueh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyiunpg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcxlpqx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2crjkqjdf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2astdxckh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qupjccen.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hvccaftw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2krvpnjkn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzqnkmk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrzxfpy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fifzmotc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jtchsvyx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtvocao.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyuaxrz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtcbddv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwlwxqv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqyxlpp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbrtche.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtjpknt.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrjbkzy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrtrgjk.html


<!-- 参考信息 -->