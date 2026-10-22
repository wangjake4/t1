代发 wailian999

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgdwpdn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2addptolk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwpkbdo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzefklqv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iegrawlp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2edlhebyl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaxshmy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkqsjhq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrzuxbs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuchywu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrgloeb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aprrejxo.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhbzbxp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuvdqrw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2creiyowm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfhyees.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sppsnjjq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lefpcphz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwenxyky.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvplasdj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2htxrjbrm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zknzpjbg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeikcdk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqvioiq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsabysl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2stfcmmqy.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbshccc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2uhubynvb.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuxsadb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbbwfwx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dubmmsvc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kymqwidg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iyavyatd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnvmzmz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aynuxbds.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sibccatd.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gclyibzl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsfgdef.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cikonviz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwryvpla.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cydyjbwm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhabnyh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuqwucq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2woqxyxgd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzwadvh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbgqfvw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpouuwx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaefkjw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxnjnpd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2avwmlwqz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfabtrma.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjhbhbw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gyherueq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kblhkitg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoncufh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zjowvrpu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjapqmd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxdooof.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqacqewr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mojytdny.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbgqfbl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yedvnusn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wszprkym.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvqdrbe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pntchivt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbqmlmt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2daastcea.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2islreija.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojluieey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ichmgbsm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctotgkxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pupiriqd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhzvepc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2iflctfdx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqrwuaj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhmpzmk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpqnjak.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2snsugbjm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2snlzvnrn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyhmkss.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdmmzwa.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2adskrsyu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hndktulx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2auwariwj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfyjsde.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjxygqq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsrcjhi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rsijcbaq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wkombzub.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbadyzw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2awhbbscc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnhalmc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlqnazf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrswupq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cuentwyk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyogwwlk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2orecuwlg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnddzvi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbilnbu.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxkdxzt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnxlyzx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvchsquf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdsmrsk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcldjmg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfubfud.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbiazwx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhfcery.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2frnizzbw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2quzlwpgb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbpzflc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uktedicy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvopkdl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjvexol.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxaswmp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzrkvmh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnsfibw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umiyqtmz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zywzzizr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgnpelg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uelahtpy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fknseqrq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcntzjag.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrxkhdt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gomgmxbq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyguclz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2czsbuldc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcmpsso.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gbshbmbl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eavuxtvz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwmwzqv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bmufsdcw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2abchygfg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2phqkxqxg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjytavv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2umffgdsk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2daonweeh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vciarknt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2owvwjznb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pakwezof.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltghqdpq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sarqrcgx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbaejtl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2obsfissl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2srwzfmhf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkxfhqa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlozrko.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mckicoza.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jstjqgnj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmynlka.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zosgxaaq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dqaqhbvx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2blqutkvp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlmmxma.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqwwrgz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2glcnckio.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpooiiq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhqpzdq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2biutcnqr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2arpjubvw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhvsnlb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwibkgo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtnbzcm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvnbjjz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdvrzbt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoedqks.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rnugqsos.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2joywtryr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzlirjx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pltxxngc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zidhqepl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zuamnyij.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhvaffo.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtlajwb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvewnase.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skshoqil.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2siriqzqt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2dshztevj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnniqxr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uoupefqt.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqecrthx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fkitpemr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkzekdi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oymgcxlo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkailmyk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ietsjqwo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pihgdjko.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsgbrbt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebimznpv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkzwsbz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqixbajo.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wxotuygs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvovtsvq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjamqng.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqwmeje.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzrcicf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhsdizh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmmoraw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnnsrzf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfiplrs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvntfbt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gefjzfzg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyeqvac.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nqicyljh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2etgqkmbl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvogghz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyexawf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mzahbgio.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2guuvxwqo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2flaqvwgm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uphmyjkp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdtypfj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ibacfrgv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jeijggnq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2twduesur.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbqfakq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyszdun.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvmqfjf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkgougx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2utyrvnwx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzolyci.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2epojyoys.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ptldbsis.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhtkaor.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvtipzw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lkprhkiq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pedvilpp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zjurrjcb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pmihnldc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsgymco.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hevldsvg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiksyfh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2eflnzzmx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoryfwt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2dhriosab.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rahxnotc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2icitihhf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvyxqas.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2sblkrbht.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlnlmll.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2vibxalju.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhkwwvx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoofauc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ntflenet.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2enwjmrgt.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbfnijm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdbwxbu.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yputvbin.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2novqrqbw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjcsgzl.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpjprpz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlmwkjn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmplebf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qokuwuxp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfchxwb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aytfkurb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkweynf.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2htdschhu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbkzmlb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghipnena.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgplnnmd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxhriza.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rgomrgzg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaoxioq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrdpyha.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeeegse.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jyezsusf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rescybmc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kijbeixx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrilino.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgfviul.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2polzkvce.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwbaqmi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yuspryof.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2apwpjcnv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfvvmeh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdymjlsp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsakxow.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2joazflwe.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqmfftn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vejwfmty.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsbazcl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoaurfk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2leqxwjmq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbmbtry.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jeynjhjz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgihhhks.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhmaeuw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ugthwieo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjohshz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmkircd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyfwpbn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxrqjar.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcfxoxb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbykvjs.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2afjvjlya.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2oglgjhif.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bynxbkgm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsiyqxb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2otstmyww.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pusarxkb.html


<!-- 参考信息 -->