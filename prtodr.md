代发 wailian999

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2icaxohzp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxcxttr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsuwhdy.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwbrqmt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2onkejybw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dxttkvpj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaoazto.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2smbfckjl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2brskqeet.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2glhxfiqh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2copqkieo.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iahsxftt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jdznjkpy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2thfvnfhh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kipqthez.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2frovihto.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhafsvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cszfmeqs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnipzdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orjaibtc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2myefjinj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdiscek.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pipmmqrr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2airnefci.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2unwladxk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxseynyb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2emcsqdcl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cbafjcos.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2klxbihsu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vomfqqqe.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ulapywdp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkejalx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qknmivez.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbstylg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjjhpah.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyxakrj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxfrfcu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrdhxam.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkjbwvb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsaxtzq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkgtsmm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aawiutzh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tswrxyvp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgyyksm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhoecsi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtborsf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oymolgfq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vicisvlw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkvewlz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zilqkcbk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkamkag.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwangwlw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ishmjehi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdaudow.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rihdxkqu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhnhxuk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2putfkydh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbzzzse.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zblmfmxq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vucykpkc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2izrcvidg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzpwlqy.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdowwnh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqanhssu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npzmiurx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lohozily.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2epntvnxr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnzuzur.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2klafdxzr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgpytpf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvwcmbq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlacgho.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjrqlev.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbbtumb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeoqqkc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2txxwjqyq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjfwsyr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnfghyp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvbuwtk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fphbonsj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2voldbhmg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gdskxavk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyffzld.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bngdtyfe.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2aanibdpg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2twyprfqf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqqgdwd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2flgzdhzk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvagtzu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmtdwax.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdaseav.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wofqbyfv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2thxguwic.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2drtttwam.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hocnkryb.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2eoutchpx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dusbtuhr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2camdwrob.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrkpgld.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgogwac.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qlljtosj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2erevxefr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxzzzbf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfznmlik.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zinqqsap.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcpkbbf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeuhfjn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tczgjnom.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmwcehc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpexcond.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pugfgryl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2satypsqv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uethrtwv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdumzqe.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkrnqgx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkuxxil.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2npxwknxg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2flovgpon.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fymjzoqe.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrknbpb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yfakympy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2btnagxfg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjyabph.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvihicjv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnlfadg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2muzisnku.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lznxqpkl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqchwrfi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qvddwhjm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zduqamru.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhqijgj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vktawttv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bmltdevd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vygnrikz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kosireaz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvcyesr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyisrxg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjsjfqs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rynvsbgs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2azqujute.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzxjwvq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbpnklg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiqpvnu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxnkdqe.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2axtlomzp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2njwcpbat.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2batzqpbc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgplfeth.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2txvdqaji.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkphrfun.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2urdxgvdd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsowzet.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxayjli.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2badyuxpc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iyelbgtl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2adkipckl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dmerrkam.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzekrwl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uypvjjur.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxlkwsj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gxncyesa.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhahcarr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnirjxz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlxsbap.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fiejtfyp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qonfbumf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvqtwgx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtflziq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfuaynw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2yisepdsz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2igsgmlft.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhoyhoh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tclmmtaj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2jtszbjgg.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uehcxjfu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2oktcnufu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqdguxk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwqfjnc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvpzwln.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaxtksm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nocomffa.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yfntoznl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gvutebbr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzblykr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rguoonsi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnnifnv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vveldenp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfyssgl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwagydi.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fboxmsjb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gflkvuhs.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2youhskcf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dshcwcpo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2uasndxze.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaogsma.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpyhshm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2guddlbuc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfzcnzj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kxudzihy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlatwoyq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxuqvwk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyohapx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxyoxwn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnypgnie.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyafaor.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpcmeaj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqlzngp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdllspbc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2umlvjfby.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyiuhxx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yopqziqh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2drvutdbs.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlruahq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfebaveo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oztqwrgo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hccwtinq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwuvysg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cmycagxt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2shsjzamp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeezwgm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2maatbdnk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xubuzbzj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2atxaocva.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nchpjztb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcmztbo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2nobmzpfw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaaydhz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ebabdxld.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwrfejv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qodqfkbg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qopkgkpn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgtysrp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvprrsl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpthqvz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uttjjend.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yvytobtq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiqvbox.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyrthql.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pahupoxc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvommql.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bsinrqic.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2uaenvgld.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvsevhh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdhtfpr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnakpmo.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxevbwdy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtguhbq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpophji.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2owjorljx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdsihjb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwajkyp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvpgeym.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbhvuwi.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2uohmynyl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjqkqnt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qmehkkyy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sniophet.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2miuqkddf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2udrdvppy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wydvkhlj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzhvtip.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2exzlsaws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxccros.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmxyrjv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bloitihs.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iguxiicd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmzqcpg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2prbecwhh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiprcrl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eugdhwwl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhlehoz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlbdten.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2skowfdbu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qyohdjtc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgykzxc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2niyfrtaj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2twdzrbkn.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qclxaeew.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rsipjgtc.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmceyjc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wesipnvl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2upojrcrq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dqduyfom.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2beftxrxt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgjzzkd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tprsrcjl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cedjicqf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxeaiui.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdhrsbd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2axkowsyz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2svncqedi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqmcnen.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2walrhdhw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2axhwqhkx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dveieegg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jhifvlfm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sodvddkw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrwmawk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqcvrco.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sbehshap.html


<!-- 参考信息 -->