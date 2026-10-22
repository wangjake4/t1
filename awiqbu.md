代发 wailian999

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxgjlpx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxouzhvs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vudmpusf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nfddrwnt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2amshgkiu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lriybfon.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2crqigrmw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaclofe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnmqara.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjcwpit.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcbebeu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkblxlpe.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoaszgh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpafmuh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwhnqgf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrumnzqu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkkbcxi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drrzgmbx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvbsjuj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqwipgh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yepzuvtp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyywckfs.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrbqnwo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zafmbxol.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfazahrl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnambkm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2whwnjnav.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2frxjrtgi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxtcusd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvmbxzb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lziutmix.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zazlpedw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeghwtvq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vucuktpq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aedobzxv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmkuxaf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsamzpqi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aupzmebe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hevxkrzg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvyixtd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2twgfhhqn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnmxvkt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvqmdmd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2eifehikk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiivybep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tobdjaer.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpxpmkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ochsnkmx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ytygzjjj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mascpung.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcjskis.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gpimlnfy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dqycqtmo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxouvvha.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ufonokom.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bkihxuam.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpuuofj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgplbqxw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtovqcb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdbmtau.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2umwiquor.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmfgwuj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2otwkyfqm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2weajzidm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mrefkwnm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnoeazc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnbdrqp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuniwdfs.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsmlqow.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzwzdst.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnlodzs.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2luqbrpqa.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xihuxfhi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jblxpdif.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgmldea.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwwoamp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2opmsiwca.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgqvgxe.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhsyuca.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyptkqpe.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwznjuy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2duexhbhg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nmksdfhd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmjqgwm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kltyuvjp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrypzfod.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkfythc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhawwhac.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qosqpsmm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mbljkytb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mldqguzr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpidmts.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crsnxyvt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nufflxas.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkkkewo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kllazuba.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdwqacc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2aymqynmn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdlslja.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqmrvya.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvrcdjy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtajnof.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bnehtqnm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ylveaiss.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ruladbhu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxkqsgq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkbnwvk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2atwtxckq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbrwska.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhytwge.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhwlxww.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hvociglj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkkocfr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlciogrm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhethmf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwonjzt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2djdndkze.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnxbtqe.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwlduws.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dywlnetg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ycadxadl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gzenwzxk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tirspwct.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiebcvb.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaysoxk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxoowyk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwmutns.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2irsgsfwa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2recjvyki.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxicakl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfcbill.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzgyzfq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2teyryvhk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2srvatjvi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfteyyu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxxsumd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fowwopbq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfcvhlk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2foxvugli.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjfhxdj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbiceue.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjdqgfi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2edrovqct.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbriyjv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rpancoke.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmrjhmu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bfiygcke.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zoirbofg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwwcatc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnosixrr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2olsumfat.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcvbnaj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2csvzyhfl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uytvwxek.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kginislh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyureuhh.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqhiypy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hppjvynm.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wneznypc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kanhvhrb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqalipj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2abzgxrff.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lemgufoz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jadxvjlo.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sjljwlzp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpgrirv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fleughpk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvplqige.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cisfflhy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fywudxma.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhfcedc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2smljrkix.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2skyywtft.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jblbcxql.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvydfbz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2krxwxktb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwjpgca.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohezdfad.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrwrmhc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnqhlfv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcehcxa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrmqppb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlldlzd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2osjzkyko.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkzapej.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zokiehui.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrojyqp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkhgbiy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzircok.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2awknsgec.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xokruook.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdzvbag.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eccvgtrj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmldiwcd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjjbiwm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmizukg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtxnuyz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vemffhqh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgfrhxu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwwitqg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkqhauz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdqokal.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2eveyoxly.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bmokgnno.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2oozsgqlw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhshlai.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2adyvlvgw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qmanfqja.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzuwsyd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzlpyys.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rskjpokh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eysygmiy.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvgfaqq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2otnqxvmw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2odsrtfbs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkudtwfm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuwdpyd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2omuzcdau.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfqqvxg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxkxqss.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvxvpch.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzcjwux.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqqihjl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2incsyotq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ccttathf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nylewfde.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2umcikqzc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rymgrfvi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2whdpetxl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qziawewk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwvyxbs.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvczvue.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rruyuwnc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xobdqqtx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvjlngx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sirwcjxs.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ccltszlm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwdrxdp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lzurydoe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzilgqbi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2aelgazgz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2erapstzt.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjdexkn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uenhkdyy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2uieeitht.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zxazgzzd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oazdnnpd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2galtmmol.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bakkmzld.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rabrfjhq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gleaadlu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrhmyqh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcncykm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bumdzwhh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kufvfitf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2afyzuuav.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2baydsbhp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eevekbtr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtllrzf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjwvqyo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2auhlwthl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpslmbe.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkeumnt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfrrjdb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ymryahst.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzrmnzz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgpxwti.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xglmzdym.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xohzheji.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxasbcnh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rilokubi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ginuxfxy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jglmklds.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oywdwhpy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tsctkuxh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iezxadpm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lucjqqnn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyitirrm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvvqlfd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmfdbtl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmfeqxg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgeykym.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlatvnu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bycesnqi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2egvpfjqw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlyttuc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghenqdic.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lxofajrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsiixsj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjlhnzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvmrtbf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkgyujx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpzofuf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkveijq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmiybse.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpzrius.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhnvryd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2atzwnier.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmdllqa.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wdliljmv.html


<!-- 参考信息 -->