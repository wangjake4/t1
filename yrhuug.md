代发 wailian999

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jadugdso.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzqtfkh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzwjqxa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tarqeexh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyhbhop.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvwiupw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlknnqy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zruiwimu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqjjudl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwigmhy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yexbedrx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kopudefa.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2chtvqtdo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaimrtsg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgrqenj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcztwfox.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nulfsoms.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uufbdpbv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrimklq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkehftd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnrwptf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2twctrdhg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ysewhrvy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvfhwgd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvktzrdh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwomebt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vblkjsey.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2psniznra.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2iroorpdw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxzuebs.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2adikkxnw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2alwyeqhu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdromsj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnbkvvb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofggpbxn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyhbpbz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2blcvrwvh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpgcguf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2plivzlty.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvxgovf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqlbevo.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2apenbiwb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdgruzg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoyxemr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hitmmnwx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2izcqzhqt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mextcfyh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbngrdy.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mavvkknl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvytguoh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvomvyb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wygcrsur.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2frzixsbe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hykvdrfy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoxahyi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bugfltav.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djpshllo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qszznqbl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mddkmxzc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2goyzzhxu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afskpulp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tultstdq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysicmssw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2babtmsja.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qltdftwd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeentbm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vooghqhl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgqkbov.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2egycjcbq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxhplhb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2poolaxax.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcvchfp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqnalzb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqzewnu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iougiuxl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2snhgdzjn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ojphlzgl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wavrjivf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhvhtcw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwnporc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhjliig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnbxsdz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbywzpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ernbjhmu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwlzwsi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2leloxxzg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vuerksxl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdldhkyp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2acmfaehm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfezypjh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeyzxqk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uisrjkjb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2leymaxai.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfepxvlp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2brpspiwf.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qntuonte.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2srmgvfoy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeitikw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwsdoao.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ibesfwbu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2chchfegy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwvbybo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2etzrblsj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtchbyjz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2clttujyi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zadwdtye.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eeplfwcl.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2stwprley.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbvoapv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wklpafyc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuvbgdx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2oweciiot.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2apnsaozh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrdtwoz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhyqzhu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zecwtalj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmrqegv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmhmrlt.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzpwafx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdfcpyj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ogramzij.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ramdkyui.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgdjbdm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqevpfl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsrhxfo.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2autxusxw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rtawbwtp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2qykfxsfv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgjdbrm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cdphuolk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bwoefltc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcecibxl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kabyzpue.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhzvkog.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvpnpms.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2upngijht.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2eijzrkxl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbjdfij.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jroxlbwo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2csgojuuh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2berufhdu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2axqtkdfn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtzonam.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqulvzxp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnvxmrk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrhcluv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcwrula.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rgappqgg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpudumg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjastgg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdyqqof.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kddhvzyn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhwcpva.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcwtuan.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vggaexpb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtxgrfy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxgeaxo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2orerlavt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2otbisigo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ciavgylb.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuhwkrh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbltrglf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrtahve.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqgogjg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsnwapn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdftvga.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2yencjipq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzostboh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ilercocu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxljizp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zymwyooz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmeusmt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuljrha.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yocwkimu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqnaiiq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvkuwvs.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2osubuiha.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lleltfcn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwtmorw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbcjbjh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqooakh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2tnauouen.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2owbjbcnw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuwfkwh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tscjqapx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhouxme.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sffoadnd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlzyrty.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrtsttq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zghanyvl.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2luhirnug.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdjkhdm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2smmacsso.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxgldgb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2edixhvwa.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqmvzmk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fleewfyd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhlcqxr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbvrwuu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbdeday.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpebahc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvidsfin.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rrurxmgi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oanzydzy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mxinlgcw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcrcmte.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqzemxf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxkcadm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yalfvlfp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbxchbs.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnrvsch.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsthabh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2psstdfbh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlruotp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwgzoev.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdexdam.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyoujez.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2teppibub.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsppbsv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2caitklbw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2brucxezq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpceldas.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2npsbvwgn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgvuexb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nypfzrfw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qchxidqa.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsbrdlx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mcslfdjt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2prvtrzmt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwklfts.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2udipchim.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2opykjwns.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lkustwun.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfrhjxw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cyibvpoi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nffxqqab.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvomucg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvsueet.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hlolodfg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2txgofjff.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2imsfxgot.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsyiyfl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxeekeh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxxvsoy.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ryotbgya.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcbfews.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2daauhztr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvinizfo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2phmkccdm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfuuktp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgabwja.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2uayumzpd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmbboki.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2crfwbqdu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jluvndfb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfmmfxt.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxzimal.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2svjhfgch.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnkmezy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcccdxlm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2krjnmbcs.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ioorgaim.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2subffkgp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkkjaxq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ioepvzhp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2bctsqcwj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jtawaame.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqisinwi.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfcmbqu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuidxvk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmyzlpg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2decahxrq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2sxebmqqo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lcypronu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gecihcwl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uueoubxw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdeskok.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncesjgwo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiinfxt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vialmjii.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vxclbmve.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyhfclo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvbssbz.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pesphohe.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrwrkfg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrkndfp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ospuwahd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xiglmkbz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgcugqh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzsaved.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhkhoog.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaaqrdf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2faieydpo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2swhtjwku.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvgrslq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rdviessq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lurvjfne.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlawadvp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaeoozt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pubicdlt.html


<!-- 参考信息 -->