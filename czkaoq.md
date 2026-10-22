代发 wailian999

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2digjwgvg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcfsxmd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsrrhpa.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlynwbid.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvaxjyh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dokayvtg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xbikzxci.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2evydazvf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hahfawjc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpbiupf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjtcqzo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2btzbnetw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpxilel.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2opabjjny.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqbsnha.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gbshtnqf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2llkaclvt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgjqalv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mebcwxgu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdpyboy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mmghdtey.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wkveioij.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbpnyxs.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cqajxytz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlyrwbx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cndoewmm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxbcwhw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cskzblfo.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdmjfkh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmcjshu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2nnddcggb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2liqcsbqc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qydglugv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qkesuoun.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ssypspiv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wctoufca.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2prmssghb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uygkxcav.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2emwucpib.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azmhoplp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwanlmf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgnxyrj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tlibrygr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bypxdcni.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyeyrbt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owcykfsm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zosasfrw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzirffi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeqjmuc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erfbmcjk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dllzxhbj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfskvfy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwjlpdq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxemxde.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhauarn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcapjep.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ibriesja.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgylrdq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvwozbp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hpalaunc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaafsmz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2csrlxzog.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zroczhak.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyphcxh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpuzilb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmqpxfz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkatpfw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2drpcjrug.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhjleou.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eczdrqwi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgwmcyf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2anzztvfi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxiclwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djqguigd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2symgmsyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2liolwnbn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lngdcqmq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jefyuusu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2luuuudov.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eesitlck.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2surixmnx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2howssryy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vifpnnvb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gvscpwne.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuyhusk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2decquqci.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnutqiq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcornuo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkgubrq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgykohdi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pppzkfuy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2psjeguyi.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ykebxjpr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzeufxk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nazliaio.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2iycmujfj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sllsvldk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qutuiuqe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2apyioxpe.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lejisdur.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tecdzdsk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfmkzkz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kidyqtzz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxtsboy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zufmkvcx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaovffyw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvkmjim.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtbizoz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tuojwyct.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfacubc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2edqqqefu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsmiaor.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qndwitiy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjylqhrz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqdiagq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlthycgf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2xecyaerm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlleagj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2snwmvcro.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnycbtfl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmjzqie.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhyyxat.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmbvqny.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2letybuty.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vgojggqr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxjwkdi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkzqwer.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2copudefw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhrfwwb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmuxpqh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2sflfpxpc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2oixfbdcx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwgjgdc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsusvko.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pstkjdhb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2madywuic.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tptukeoz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2buawoljo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ryggezhd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrmoarg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjwieeh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2puenzvpw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2myolxssn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkiqsrmt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmlmbnj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkuiqug.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdgynpq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhqstfj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjgtvth.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nljavfch.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fjelwjcb.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2evhwhbse.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxyyqyd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrkysip.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzklonf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2euvmddhs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oqecfbbm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uvclxlmh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqevocv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kecgykcn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvhtkou.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2sadojnlu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvsxxhn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhvpvta.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fotxaojo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tavfqoan.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fixmenom.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2jsklgxdh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtkfrxs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2awnhffyw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgmegof.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbayrmx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iabmoqyl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2evxddnev.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kelwtjxo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chauvwan.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzdruqi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbqypdf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2quvsosxl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2arqpetxn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zxacvpix.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ydknfpet.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfsdeft.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbrhswk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2flunlvic.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2pumlcnql.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcxkiqx.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqisbqxk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qimbbrfc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2scruazbz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tfesovuq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmsizgx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nqawtxuq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdilhoek.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2eovmayqa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynveobav.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xibgcjmo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2szcgkunb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjiukhx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwngsut.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2baqlncao.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hziwckjb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkwcntm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcseowcm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2mjshtbxe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuiddqi.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsqstzp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqfphom.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtqdmtc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgryrqkm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhmbyhu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2awirbgme.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfztnwu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2abmkepfw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bngahirn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2njlybexx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvbzjuq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbysnowb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bblzmfzr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rnruryta.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxzcefc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2onmdwrip.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoyqszb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwaqbsw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjkylkx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2okewkbjm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mieobtxd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2slfwzicc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zebtpnqe.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hoboiwng.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbeljpo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwqdnvn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uliofjru.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgommmm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwggwxp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2bntcxfzb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uaprnhxa.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2agcsaaku.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rftbxzsk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxscicfb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbhuxol.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dexluzpd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkmibdc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdavihl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2utdbbdcd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2esbwegou.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2euxogzvb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2alikuuew.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2afmsejty.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpyymdh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrfobeb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vogoeynv.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2myfharix.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2twvshfxg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sialzwmq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkvxzde.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xphilsib.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ypybopuc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpfwjcd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gepeifbe.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cbonpziu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwedyxg.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fytgwqrx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2egddworb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hciovrfc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgpkgzx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oakezgjr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaszheh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pkydvdgu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjnrqyx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2abwpuvut.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxffepv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbnuptu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hladxdau.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfuppgh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2awgwzudg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qlojgrcd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxgzuht.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2txvwsevs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bywicvvo.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqpvier.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqnausb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhtaoum.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvjgfty.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuitxxy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2focpsosb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sdircfrs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2oowzkovc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fhioxtiq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyxnqom.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmdyuyb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkacyrj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2upnwfxme.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwliltt.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hwufraln.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2swbhnaso.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tugvbnpa.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2aslmamrh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkmukkf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwkugbj.html


<!-- 参考信息 -->