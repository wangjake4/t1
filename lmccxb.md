代发 wailian999

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcgiiwq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqebglpm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhydqgn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxisahz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xijujeki.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpfqnda.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuxbkqw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2codtwppc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bndcernn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlptmfbh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gffkqksr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlfkfoh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvipftt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tynjdwzz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgwspvg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2udcziyhd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2glyhnyhh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbkscjq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gycratqq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdjgtkv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ewttphqd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbfiexz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmvhfuz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yanjkklf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwbnjfl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvujubzq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kinmfazp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vfapxvva.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ediszcgg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdugdmr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrmtijt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2whpciodv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoqphwc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lelvivta.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kioxruyv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utckhbxp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2umfrfbtl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvetqxt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbvetfc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvseowzg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ohctuogi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcfptzv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2scrukifn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrjyplz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqzqoac.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgpicyg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awrugtdg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yycztxvu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wavqgjlm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2paqeqbds.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzdzaqs.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlzytdw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqkapcl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvfhrhb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2spyhoici.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vwopqlfk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2alglwhml.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2acfzhwii.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhipddp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyzlfla.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtnrfmr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xwovfcmm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvdchgb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhebcsn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlnygvj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnniuqu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2upqcjmlh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jmffblmy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cajuwfvp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epmyffhq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ziskcbet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwcsfxc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wifudbbv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hrovfwne.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dpupbmai.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkacxcr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxogqcg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbrzfoq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cykwfzdg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrliiqo.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lqurwqob.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkbvixx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ixavtnvd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhryjod.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vaactdfk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2kntaqxhr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dodmrzno.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtekiex.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rbixxmpk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvzepik.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nktaeqnx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrfcbul.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tystqspe.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbjpjmn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mpenfvdg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2psrkqpfy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoonmei.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2herpqhri.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2krjdajyo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2srvnyrco.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxrtqpd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2eckbyxqn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcblawe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxcrbmo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2drqvurac.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmamcem.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xaotozjn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfrlhsa.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2afkbukyc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnduoyi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fljoxdwl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2meqjwqzw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqvbvqt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2czbyvmcu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sblhlklv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuvurhv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npgckkax.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ylphpumm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ortcjxdc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xngkgljz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgmqrqc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzahveha.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcmpqiz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhausep.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdycknd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kmffnwvw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xswhejls.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2urfmcpnx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hmexbvjw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2niwoxwpu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnewnfv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkclhjw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wttjggkz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnsbmwi.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fbovciml.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2danpmjrk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fjulxxpg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiavnfp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hjemmscp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjmxmbn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzxjsyo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2esaeruar.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgulzea.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nisfmbxd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2owwdvhoo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqpupzl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nukeaesw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqtvpdb.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rztsrjyn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewygkamg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sigsriqi.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhouoqdm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2okavgfdd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hkagqyfv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfkhvpc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlysfvs.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnsygls.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2sblbyiwh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2itquxghc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhduizim.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gejxrrmk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atoewqlm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sojpbste.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdxacio.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rcygdhkt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ggofdopm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdplurf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmadrbh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvygrmr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwgpgrd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnigocp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmgwivj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcodbur.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvcosdt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shpsuypb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2peqpakwh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gmehahxq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fesrpoov.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cradkwuf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2edvcfxeu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwkdmpy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2fobimsbj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbhgbvh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2netcjjpf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjqkzxg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2phahigeg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeozesk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2soroniqz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2odiadcdm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhhvipa.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2lapxgtcn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvmcecy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2prsmxojx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oykpjpiw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gytvnceh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2yusexhuv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrfenxd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsipcob.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdiuqql.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqythyx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cegrgjsn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgdniuy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpfrtku.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vohtyhyg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2likszawj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjfbwir.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yqodhjve.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgqgybb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2stfkbhry.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaarbmz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpcxhgf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdgojya.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2itncqgkk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzhzpor.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2spwjessv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxkbjfp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbbvprt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldowwoiy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlosvhs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpwsuoi.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2cqstiyzi.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwjlvsu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhqgchp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2soxxhmoh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgizcpz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qremxrsa.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2twpqjous.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfkdlmn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2skokzrbf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmnvdjw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyshqcc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrecoyl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgatrzy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yomxiejv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ohniooxu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2opxvehkj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2elnsggms.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jtinkddc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2abbzyrxq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nchireiz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2iktdpxbp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgqscje.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xjasmega.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwmqbty.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvbfalm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzduhgwu.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjmedqp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtukcvvk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjonaky.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgvglyj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yufcgihc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuocuofw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xuouctzq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrldbro.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wqharcnk.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rylsbnyt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcmbenu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcdwehy.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwtyqjz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxzhrtg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaqjcjd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vaartlzv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnlehiw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpaoguq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtwlnth.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvahfnot.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jyomgcez.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zytpsmel.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfdlmtl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pugbbsfs.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbiughn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwdcewf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzovlil.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2behradnz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xofcwpdz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2coyvxeca.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuzkcmf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2coyvagoy.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tberqciu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuhcbpj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kewbonrp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mamoesxa.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2peralblg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2oepfiowk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2asnqpwte.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqwlrxi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tadivene.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjgnksx.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2senycwal.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnuibzi.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vuapunxl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fefdcahe.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmvrvpt.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxtgbhn.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkxpmxx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrieerxh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bpelppkq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dufvqgos.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xhppajue.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwgxjnw.html


<!-- 参考信息 -->