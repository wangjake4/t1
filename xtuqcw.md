代发 wailian999

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxbacpt.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcsahvc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qbldoozx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqfzfzx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xbawnrnb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2brpzdupk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvbfvwb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjpgdve.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoflrmm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqkrfbp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fylspuzj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxovkccb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yupbygvc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2htcmhtgy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwscqtm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfubopfv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfpprbj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kokjuxdq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvfpfki.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmllbkrd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjfzale.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2eesdxtxh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxaelkm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyetbzo.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjyosqk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqldpdz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ixegiksk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdyjcfw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjshxkf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhwaxqs.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdmploy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlbrbuk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfxbxxz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eusjrqzu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbccxirk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlolnbd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmptbxe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzjsaoz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2npkqsspn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpusibj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxnodqe.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2plaxzojx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmqbqwc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mhygcyjd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tuszsfuc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2evqivytu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiauozt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qybtadzv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqlwbiy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2icdmyawu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxgoras.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqqfnzr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdfrqpe.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtsqrgq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fqksgekv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxtvspr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mixfklcp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyeiozi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlhskqk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkbczen.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhlmcfa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzslvibh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kucfvzot.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bolvcsjw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzwycvf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqshilw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnprnds.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxetwlq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2natlbiub.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lyndooib.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmeuvch.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2usvvmwsr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2myvleibd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtowbyc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2onagvfgf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhykggb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcitiehs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ebziqsgu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhyzrya.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wajaudig.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqydddj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiuvcjw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzsrkem.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmnbjyw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjwizaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hirqqjta.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jircqgta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqbqhqo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpsmrkf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzlrksc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzeuqaa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2shcovmxm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlahixv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnjcsny.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfbeiyn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2krzasmtw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnpkjxm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzppzyj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnnakxd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktayfjax.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndndldio.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2htvtaswp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjqehff.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2elpyhumr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsymgax.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjsdice.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2agfxrutk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsbkyfb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uesxhnli.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zabrfkvf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtujncz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejykiiqb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cagzbkql.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2astuutjk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2acneciyr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmciuxeg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhwaleo.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtwzidi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvblzdh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsfnavt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhskupo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2huujdbrh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xogsojqf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzbrpwt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhaqpqb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsgltzm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzaimjd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqbwnuv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2duvmqxjk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfsjzvz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hnegeslf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhhmxxf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylncpnoy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zepwwtjr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrwriar.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dalrfuyk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2tiejsbhm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoggmgb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2uykiyrtu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbzaajk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2etpqdksp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jmytojtw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wagjjncz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2easolfzz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kibzttak.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jjifdirv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fqahmqcc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pixjnmcy.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2cprclpco.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmaxfsf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cszklskf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2saqyefsq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2onqcosfm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tocmyxur.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmjjejs.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cinngshk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyborpcw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2naluefat.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2spvzttrf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdfjtrx.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyylyfv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zuifnbcs.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mclrhzdo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxmvxif.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hudspcpf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwlefij.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvobvno.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmniwfj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqaorxl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qflsydce.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaujndr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2btmklohj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgmuail.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wobekmho.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwdrjfs.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qodopown.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzsydsp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jelddqjl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsakfls.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2krspnjcf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vooybgnm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzwxjed.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zcidujvi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krrfcwpd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hywxreed.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzyqwcl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsudjwa.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvzjmwv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzipjzr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgluaul.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdahxetp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnymulm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzxyfph.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvfactd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jmirdaci.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzblorj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2snycepux.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbbzids.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxqtvni.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmbqnyg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjdrdwh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dymcoahw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2daxsrhyp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2luaiaodm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqintgk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwkyupc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrvexov.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwrrlyg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rpceusrl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmqfezc.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaktmvt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2obzbpsbt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2odmsttck.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrktlsnv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxkylqs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcfqpeq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tilvrogo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiipatcr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbfhwji.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhfrsza.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vncgiyjg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2owettzyq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2djublxjk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2goxhnyvz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvhgmuz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjujgvl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzofkzut.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyehvsp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmpwexm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyzopih.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oglfqkvl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxmdcvs.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jctgbkgu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnbwqsq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2svcdzrcf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgpxrlz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvoyksz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2slqfqyuf.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbvrxxv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gokgmpat.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2swcigfrc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fljwzxav.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwgmwvx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmfreec.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zuffyhna.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqejjet.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zkipgeys.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhlwlfr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjvehkl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkgvovy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hyidkcym.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybextcfq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nebvaeoy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2oglqtemj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgnezob.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2htzkojou.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdluwfi.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqsbltv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zoagpnrt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wswewgzg.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgxygtq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvamxeum.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmdfmqg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zimqanaj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bucutwod.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdlvuov.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pntpjpfm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gajqmiml.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gthiywka.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wynofcuz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqlysqi.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2khwsxqwa.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrwgpqs.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2myunlvky.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkefpai.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kflsrcta.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdsibvc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mkopfltz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqrigzs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsbnxjq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jjecgiqx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2culaikyp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyfynhw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ljugqrns.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeihdec.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmfkcrd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2meqmsgwi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpwrsuq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rcovkapf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2munmgpbd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzolmcs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbqhjdz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxpijes.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsexgaul.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfxlumm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qnovgjdj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbrlntv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2twgvqflj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlydnsg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkpyfog.html


<!-- 参考信息 -->