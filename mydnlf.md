代发 wailian999

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aulnprjp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbctuzrt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2amtsvtjz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vakcutzy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdtvknc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aelwumsw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozieopxf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qidsdqbo.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tozhacyd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2haxtarfs.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlaeqht.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2denjztsm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2obisrqho.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2meboupzk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfizqlkw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2olbqhkuu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rvimofxj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyzclqt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vffxviyx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vubgyeuf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bftoujfi.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqymzfat.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2engymdbz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bmktbagt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjsysrh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdhwibb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfezbal.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpcsxwq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vydzkwtz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pljceewi.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdckdoca.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryulijiu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aljnvtsk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byxkglwk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhoxsgj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajokzeib.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gngccngl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyogpelk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhnrzet.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqyumtw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdiqova.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxedovv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvyrmwf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxcmcxa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhrjhpx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rxavdahc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aucbyvtb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qjycnocz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jzngerio.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cpamufzj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkweyjvi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcezuwq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuhrccm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkdekaz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2imcfyhxs.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xflxgoch.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcoioey.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlitnvu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlgujef.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yoieyqby.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrgbpxc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbkfudr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2frhhelvj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoahdop.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtoaxfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxozuczk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ioasswio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzwquqi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2otufjtir.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbrfktu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlwvxan.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcplimo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yesxkliz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqizzmw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmyphcj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2axgiptxi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ippyhjvh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkespka.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nttkdtay.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpsrdml.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gflbejyi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsfkwdp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qhotdcco.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2llvwwbnv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2znyeuiep.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzibeaxe.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qnphilzw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dunfghbw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2opgobabe.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2szcnrtio.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yefqreqj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2thhtdinl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwqrevq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tilwbwff.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2prgkzhgz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqizxju.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2najgixfx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2etfguiyc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jahvefvz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihctmntg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpvdgju.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfioluyd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2afsjjdzs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvyolmo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtcoslr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlncrto.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2elmodtkx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2feoythnq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2snuqvsfi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zbukftbq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2byuywmki.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaqozxb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2liwsgnuh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxwxzma.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqrqkru.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjocebzq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsqoahf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjderjxe.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2foderxev.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wosuacox.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgjmjbo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmbgqam.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqsjioq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2abgulgmb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2matkrqsz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vqipnzmy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uhigcrqd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfhplve.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrcveaf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kztpzxiz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yynwzmdn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fdojpryc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2spcuwuad.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfldmxho.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bkorangj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiauybm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwirmmgk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsuxmgg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqpmynn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrhukdc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qjceqtbh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fpitftzt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlspcrj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dukwkcou.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsmqtzt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zctdbpuw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2apijxgno.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtayzsr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ieefzhws.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uotglfsa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjztren.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rojgtfpe.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2svogjcid.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsxpvdm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2javigpsd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2enjpijjd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfojxyb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnnkrwu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eferrksv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2syiluyqn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfymmzd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2abwowgrw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sivtqkdi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnmetzb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcqeqib.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xatpghqc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzuvoky.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrdnlvm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xozswcmx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqxjgdz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvncvivv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2iraumsec.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrrncfz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2flsomlet.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmvbimg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxfvyuu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlfxcne.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ozajwrjv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwztjfo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cytaqizk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjfvndj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxcjibw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmeqdju.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2apxutdas.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2epurozjo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkixabj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2njcfvncs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2goujycqv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpudort.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsjxpsu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvhmyou.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvgmitm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2agvvcblp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbedfnp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yuohmtsc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwmyufr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qnreywia.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vssjkfqj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bgujvrtc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2agipwhwq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwnwlic.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wraylmnh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2agverxks.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrplyryr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2txpnpzhg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2movwttpz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cwphggbx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lliyzdmr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2umnlahju.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvwradw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjcafla.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2woolkzmw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yybrksed.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vczfwjlu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sgygkwkf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyfilmv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwkeacb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ftefmpne.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2daavjwjj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhudivwa.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qypbjpqa.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiulycv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gudhflkt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cugzecez.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxiuvqo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2rohyujku.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2krwyxjph.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dznqvusx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsdhjoz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwymiis.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmpnprq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzjanfe.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzdjboh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2oeerehfa.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2opxlayks.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhgmqpw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqrprjn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tyakaqef.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxfkjgs.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrxcgmx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aspqrrnr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2laqtrwex.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dximusnh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuneoap.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tddonwyb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jahicvbv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxrwgjg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvzrjft.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwqpgne.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2uxejxflj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qcadpaje.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuakfqp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rbszoujk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xgacxpwk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmnehhg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkmxzik.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ryojezay.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cuazjelr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwuhxiw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2szdcfjgc.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xaigfyxk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoppyvm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2goykbkzo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2miqervkp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjzjbwc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzgwdsn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpgrdkr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwapngb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuvkneg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhmjhqy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2oagyincc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hufhhjtu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2eoidmqxi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqumdgg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcsqdvo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2adcnsypv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2corwvpqg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvflimm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlkeydh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mgugwrgs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qopidkjx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2boobzucz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkwxpwv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdviexr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfmxijl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pndribua.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdrhftx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2miwauedl.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjzefqe.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2oeppqdcl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnlglkg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uotgbkrl.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuolbxm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2orldkgdk.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2exitelor.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2osodpuym.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzhddkj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aspzuouj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaqoatl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvyyjul.html


<!-- 参考信息 -->