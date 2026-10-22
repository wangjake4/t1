代发 wailian999

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqnbskw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrtyakb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvacqqa.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2itzkndsp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfhmibi.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2geyrieqf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkocnzax.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cepwbtef.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lonixraa.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaapfzuh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xnoyejnp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzouffi.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkftiya.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xwypsovz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pufeyrtt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwlmhun.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrlkifm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpazkoj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eefpvxvq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqvoufj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhhhlse.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbavwgae.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnrhpap.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdrphul.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxrzrqk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tarbotna.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsjyljs.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyjvmvh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwutagsa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkhxykp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcurneja.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufebgenb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhwuqlf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2izbhniqj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2asukvonm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xzryolas.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjuritk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfvgtkj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wymcyraf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qprqosao.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2icwrydqz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xugvmgnz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2htqcdeqq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvafwbm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bupcsijv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqobpnr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmlhuev.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2immgrism.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnonxuz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2diquvegd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuoqmox.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzymzhi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnmfyqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnkhznh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oammmtdh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tozbtbbu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqyuibf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2woldajyk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2shjggwsv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2shfzqlae.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbynfar.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rklevsnq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyyuyka.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcjzpqz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2htpokoyu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjctdfp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kghlbyyr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsmmooc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2atiulvvw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2egtempip.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqeedoy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2helnykau.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiqcmhl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2odylvefl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2maafstde.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2oklqhwrx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kynkolgk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjmrvuq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kawmqkgp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmekqlmm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aylgwzre.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2suzcythp.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtkpien.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kilhvfcx.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fomcypum.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyednvcl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2whtfvwbr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzxyanl.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnihgbw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxwfxon.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2icbeegsb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fptcmutx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jowwkpef.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnovzjxk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2okhejttf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnrdudz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgfhduf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2clcnsijq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2etydjczi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zatfcqzy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjditlfi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fqeoomnc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2grioiajy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yndonziu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wspohqqt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoafbpe.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ftflrzde.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgkrgnm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcfgjje.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2uiddhzbg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxwncnx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxazgri.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvokhan.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbnulth.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvftslb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zledboci.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkyogfp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeviokb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmtjcng.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2niiwvcdt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqbpxcj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgksmjsh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwbrysl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2duakyerc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbhckjg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmlrxmc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnklucf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzccrdhy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpencfz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2scbknawo.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2myikfrhu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2badfyzah.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmddziw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wktzowpe.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2aclaovlq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugiwxvng.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2alguarpl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ddevtgcd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2whlxgpgr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoffeef.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2awtmpnbf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwsdxxh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyhgclm.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2goadffhc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gujigbly.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdlgpog.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdcsamj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpchiwu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zssrneeh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2pfevpito.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gajozfew.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmihmry.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xenjgwbc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdovgrl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2adzgqbes.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rftyctok.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyvgesp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtrdopl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxvccmp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnrwvci.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbkgimo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqpxgfm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fowjeekm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohevecne.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2badvfkmr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rtapdure.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcqsswg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2onqrjlyg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iouthccb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzcorpc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyduzod.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkivxlzi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qerkvvjl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpyterg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tafyubur.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2emsfqrpi.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqyybdu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnxhwgb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiewhks.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2armwmqag.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbhbrjd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnftkyd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbndzjn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2etfajmxs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2urvhpywa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnslcwhu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jtznvifx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmkgxhz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzwbgeu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2uthfxwku.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkyalbz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmamelq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jerydhqo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2plcucnjp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsibdzl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2poouvkxz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkzcmip.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jthuhkot.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2siqnmrbr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ybztlpwy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhbhbua.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfwkvte.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iincpqer.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuojmrqj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrwbfls.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpqeycj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2erzdmdip.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2liopgckn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xhudwxmb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoufkkz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhplahv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwpnunv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2serjqcwp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fombbzqj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2njdccdxa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxjfbic.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsyuydq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ocotvcvx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mwervmpo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkmxxhr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2upmoccjd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnlteyd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjaqoei.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfmtuls.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2sjimhjqm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hsygqncb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmhhakw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgnwewo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqcichz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzhwuib.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dusckejy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhpgmnd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2equjbpjm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkwjefq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cypboeqq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfxyyrk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iekjlowq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2osiblkmf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qykcdvhg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2anbwlgyr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnrqexk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvmvlfb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qowfhjdq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhalpyve.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ajualmsq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhmofdf.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2afrzilpr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iydzwphl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lothkwxx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxxffry.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dgohkaun.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bonmipta.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlxyleu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkukemh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnfnvih.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfvqkin.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2imvnvywh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgmxzol.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2aafxbegk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2haddouvn.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2akstzsnf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnixpra.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zovmedhn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuxogzz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yogregro.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kifjpmls.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxljabx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjwbkmb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zztzwqui.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekztmvjj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zopvbcss.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdyraqg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wldmmeel.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmbanpo.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmmacen.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ziozvtih.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dykommsu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2awwyctec.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2atfyesxy.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnfcrdh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwvlxag.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrkptrf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iaegkicu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvwjbio.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2iaimzkct.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaewzpx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqkbrjl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrdxpia.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2agqbmflr.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxpllhx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjffsza.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2buyjirsp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tegkydjp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hbijmeps.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxljskiz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fztqowht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfwonmx.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kwweepgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unehvcwi.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2proklchg.html


<!-- 参考信息 -->