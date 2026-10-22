代发 wailian999

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2slaooogq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2agcuaalp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfwpver.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsugacmn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2llentlym.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynildwcd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvjawxq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkklydoz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2epnaskag.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2unqgezkf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaqilrz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2josvzkhk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cedhdufy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkldate.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2eldxyazs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wymoregz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2asmltyzu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnvkiyy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zythoxde.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2amxolzyu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yauonfxr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2volhyely.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gkezkcdv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxfstcr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtnzcsn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyrxahz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdtnpms.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zattgpdf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hycbtfyv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilymbeep.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpsooaf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qbygzita.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hecmqgan.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkisegia.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mthrzdfk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlhvmny.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2foniovpv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2huwvjwmm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gcadnbcd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwbbrov.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cayqdvmh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bknucteg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dijsrxbe.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlaytml.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdaqmwv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjsubov.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hsomceqr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqsrdxx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2aedukbnb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpzikwe.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzgpqqy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwymgnn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vedxmpua.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otaczgqn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oksrhdji.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2heqzgpzw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saygfyyt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wzndlvyu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmjqakf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdgqgfp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxondlo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrwukfl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfblyzt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cdldbxjt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqnmqoj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pldgsjbu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2emtlhsqk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kkelwuxl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2psiamksr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzuhdku.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2swhretfs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqhpljy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbctlxp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2grcutvad.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgxxlri.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2erxpmzfm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnswvom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxsthao.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zeambnew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axoneoti.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ovndkaio.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlchdub.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsbszag.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzbthuy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2woxfsqkz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsdvioh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrdtkpb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mmppivaq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnbhuys.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiumkil.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rypchwua.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyxytgp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdiygll.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hapwsopg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cipedinm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnvcphs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcbqxzy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvwipta.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2joewlwdk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbeuext.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pntswfzh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzejjwzz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nhogfnef.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sepempab.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rzicvxtw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjccdxzc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoejjjn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fowhwgyu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2puvjkaqz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2azhudfnc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkkhazk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkfydxc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2otrfpyjf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2untxrkns.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvzsepw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2utgvdozn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzqvihn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2himnvros.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2twqiupbn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmejpgsw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlztpsz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtqjmhx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgqzfqj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2outyxwxh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2maqxmksn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsosnwy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyjrali.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aueomyvh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fulurnvc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyvnbhp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2czvaseoc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vurgwime.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xevfdjph.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2przcglvt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ixagfwmw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjfslrp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlwnkne.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgtdpdm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnbcvvl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsyxwbb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ncynywci.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2izjpbjix.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2untbuhui.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qqznkgns.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgrzvoa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2almnccte.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvgksjz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjipezh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sppqdulb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vitfzxhl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2shrjrvcz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeguxkqh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvbjnib.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2duiplyjc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lfficnsk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhfryzj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmxjcve.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcutcqsi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fdweuvjr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqlarwt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsdwofd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqzqopm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2khfusswd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdtodbv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaerdeh.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwhyxyp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2trnkwail.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyarbxd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoasbyv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhagopu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsbflmd.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyyrqvo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfmsbir.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmtwrft.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dgelwflw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmawpbfv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cmayrxlk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qizelmcv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxkxwrf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2guwwqqgk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vhscjfaj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkqaoxl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xruatliy.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxgvszj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2oszmouus.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjdccys.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwmnsmz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvifdxk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tpexpcrd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhantdlx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cszshfns.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlztscb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kucijtcv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjnjtml.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwhcwwj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrsaitc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2objxowda.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2htitudkn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2sozgwfex.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiqvouw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2enknenzv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgwdjpr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfhjmdi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvviuhno.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qorhblez.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fswjfuaw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wgakmaby.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrizegcc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrkufml.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhaegnx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vsilcths.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2byztvhko.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qijbpqmk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2skqpxcrs.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoabkkz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbzelks.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2plxqujxt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2stddotxi.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yvftapyu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhqfski.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tkajffya.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjbajkx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aevuezij.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2doqxqyfl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2plwtwlar.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwudxmho.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2whizpbli.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjxbupo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2blwxlppn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2oonyakvg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2sflvyvyx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgkqurw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrvoovb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzqinjl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmsouxj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vycmntfy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmgakvm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lnchiilw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuurpie.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jepzsbtl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pcseoixn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwzgaue.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyupelp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfhskca.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2shibplzo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfovukx.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwkptov.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgrbcyp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wptobpll.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxqkzfa.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgunwsk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtyoehh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgaqqxp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2olmohoqo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aquxhzys.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxxhxii.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zpujckzt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhjqppt.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iafzhklt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzohchg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhmqqsk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsrqhqp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvmkdgs.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgajwdim.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2brmhsoln.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxmvfco.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2motjdzbg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbontag.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnqrqeb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaageya.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxgdtmv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnukjke.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bijwlkfc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgurmwh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gckzjmdj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lultpubv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqhgdcm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkklmkl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kayxgyfm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsicwjd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vikxnwgp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2sghflxqc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzjrjeo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnxdzli.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbtmpgs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2juxinzkf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ejldwbqd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmpqljl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdfytxu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpdhctq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2awinzwib.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxklkno.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqgxrek.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kufzzzdi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjeqlqt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cunsfyzk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjanpqb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyftoxig.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2niqhkgco.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2iofmqbdn.html


<!-- 参考信息 -->