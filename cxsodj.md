代发 wailian999

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tplhjtai.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxjdtkd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyskdqj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdbesmq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkznnyv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjsrabq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwexksz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmywgah.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsswprr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnsxwfl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjkfepu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tishjyxn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfeywgf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbdnwcs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2angbmxyo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwnwchb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoukvqe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzwtqei.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxrdqal.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxtdppm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzxuimr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwdgnsz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpabeuz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kuroemhd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnkiqxj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzweztx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kewvekqk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2resxjykq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwmgxux.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfknzasw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2obzmjmvp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kmllxxla.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2juvxwbcg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhppjeq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfynoif.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxudeqwu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwteufs.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvadhdvj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cncfroms.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnhhhtk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nijahxbz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zywyzxwn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsnkitv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbyahxf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnuzdpq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkyukpq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxtejnb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2emylyzny.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuyiuxd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpgamcg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drbwtvog.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2saneexue.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgvzxei.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2axawjrxv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2izippxkl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2msslzigj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqeowik.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgjxjks.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tokmlbfz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2chijizys.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2irgkcvnp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dkogsqop.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuprvko.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbblnll.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuvodus.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwuhlut.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xntxewfl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtoonzy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfimcrv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgggece.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qudgtpwk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmtjssf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2avkjraip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqncyksq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwepfist.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxijjfh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oddhixkq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2msrmxatv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gobwlkxm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eojecieq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rwubvfyf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoezqie.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2amvlvbkn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ivolwarw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxjbywq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxfxggd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2apjjaljj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbbjmph.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2htmgxrpp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxmepzn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2apnbiqek.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2drflrprf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkwypbp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgwjvyu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jpybasmq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbekvnl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2enwrqpnz.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qawiyddl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xznfuhqz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzejmpdt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzofuwl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2broeliks.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2blgmrsvx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvlehxh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dajkhaxc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zoblxpbz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qivtrcmi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdqnrnm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gsblxivr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiozjkw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqzrehd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxpqyhk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vifnersk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzuynel.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwuwlyg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyjqmvg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2xnghmtta.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2iksvielu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hazcpgoz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtabblk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaovats.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2okodjhto.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbojdsn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mihuidrc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yeetxpyf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxwxhzt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkjjywq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2iobpbzsn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjyjuxk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pmegdgqg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrjxwre.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fonvucdb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyyuyyy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfgzmxa.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyvxpeh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyekbxto.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvagpqo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiqzwjf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xhemdycg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhqqqve.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfgohka.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyjlnjj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsmxhnx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2djhvugju.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2igdeyvqt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gingweiz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaotjpi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtwpajp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvganxb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmyrkpb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2piwmuagt.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkskvwr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dhamwbzy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkbwvvv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zijfedzx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwrvbez.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2joenjmmm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sjckdehq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2oflpnaje.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqkbclv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2icyiqxsm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwarprw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmbkpvg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2edtenskf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2krakfhcg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjqiysp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vehlkaco.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gfemxtcm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ublgkekq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxvsrhf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vaclukmk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvkirxc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyurosf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvssxvp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2upvizfny.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmtctxj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2urgxmzsl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiskhtd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyxubie.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaekzyn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmpabdb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2unxmygzn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhgkxdt.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrygevz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2itaympsm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2plgkrxjr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymobncgs.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lokmvsku.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rffgmrxw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpstsmyz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2znlhjfem.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2coxocthm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kefdrhxt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmjlotl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dsislyyz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tidebwjg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiiofwo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnvgfem.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2heutbvix.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfejome.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhiawca.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ateyohtl.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2osconuon.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgniyqsw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjkyzyt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtcwpov.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuqgsqp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwogeod.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2svhtbrta.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbefmuh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmwilda.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvstgrp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2myhgnjln.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2byuwpxzz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzobroaj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdziqgf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eqietmvu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2atlznqve.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoesxuk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mgolqier.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2milqalrl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hywbgdqz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2susxmtrc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmdqcgd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgddzgt.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvhzsvq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wozbmjdx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvvtlrk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2iueokdzx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvvpumd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2savyadla.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vsudtdtp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdxvnzb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoaoyyn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yscjjogw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jecqvuwt.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nwscdmvg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpexexb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqyjqim.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2anbrhwvk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2emlmclus.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vssgsbkg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgylxwa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfgxxwq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwvgxdy.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtwqyuo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwiqkhk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2reuegaxw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eoovbjjh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2unxtebzh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hczxacfn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbihcja.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2atnatpbf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsuikuu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yweknmzo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkrpojd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdinprq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmrofsx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjlykjw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xssudpze.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2itqxcvho.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlnbviu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tegccskg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkzeyqx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2iucboajz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyjscnd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2docghame.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iujxcloh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcctoae.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yzalwbzm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhuydap.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bovcuofn.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwauiyv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkfhcpu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmzyfnd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2opdsjdux.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgnwbpe.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhivkke.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoeeaum.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kagppauz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2dickqbcs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2stblqxjg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkrrdqg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbcokmy.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hubocdef.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xwckjacv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ggymddfq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqctbnw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdtauha.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tumdlxaj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yncrzaxc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2woznnpot.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqylkbt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2yioqwsje.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vruqikxf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qszsdhnm.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2baiefpkq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoljminn.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcdodzd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbozrwin.html


<!-- 参考信息 -->