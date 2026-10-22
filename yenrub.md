代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mnurchht.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wghgqueh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlwifbj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gfreyrhb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaflqzy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xntlbjpr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yeooswpp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcqpfct.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zhppzcpw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtykgct.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkhrhwm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2enjcmaft.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tueuzlxk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2subjbsxk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wukojxzq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzuwpot.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkbrwad.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcgifoc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsdtagg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrttxks.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2srwhjhlg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytapuocu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuvyoop.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcaclfk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqbigrh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtwfzqg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sspnspqo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2agrbmztp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2krcrqisw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cytxworo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoqwekx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2digbjrxk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfnmxvs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvomodb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxsntup.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmzlrdi.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbphryb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdxlbaq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2trkucmdd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nxscbmsm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqckrwrz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmihwpb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wkepvddj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jstlbuap.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2swnbaqjs.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lozkczpr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrrfmau.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvuapoi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2orgsghnu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwkazmc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfjfexg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lszbxghb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tmheuqmc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dawirgvx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cjufitmj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cupnkmey.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lrulgtjg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wceoabpk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iecfcjqj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvobbhb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeyzqav.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2aawigwxz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqspxxxx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jromlfkn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tkezsufu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2swbbdvvd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iaimsqmk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kaetifqg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzguewa.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvqlzcv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxgspob.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2puxuufkz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2okxizfva.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zokavqep.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pcopeady.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2uataltij.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvucbmn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lizofley.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzzmeyj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kunzozuq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmltmfu.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkdikid.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqpofyh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwgodcd.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2otqrkcqd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwqhbms.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lvykkagw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxmeoeq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkeqtjl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwebtvp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpzwymy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvfzfbp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfhrnvc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oowwxstq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvuedqz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2elxelfqs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2migrozmq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeuklwi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfftzlb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqxwozz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmthkgn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqndsmt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bveizomx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xefpntfu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpmgjwu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dembeivc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjstkuvq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvftipl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuhabip.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ovulpgsw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cojzkrzy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaefflj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhekwws.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vavyvcov.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpagsjt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xgisrvib.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tigvrpku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqiqhxg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2guztvous.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlixljd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfzbryn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtvgtxw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtidqxz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nekcbwuy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2unhfxklq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnuotek.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2izzdfmof.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rsptwtef.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hypqyjwy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnawahhu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2deiwcler.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tinykidi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kplmquey.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvlwmhu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2idqmpwvn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzwwbxh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fhescvrc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwvvqaw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcyganx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2azdbrqef.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iviocrpr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2foovurya.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wperehtv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmejrgyc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2awedxxmd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdktlywu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sgruagrs.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2giaddfbw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeqalto.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpvikcq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2dactutoy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dletimrv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyyesgf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2brfcauqd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lbapjnts.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aquouygd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jytffgsn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2urdnvsab.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxmrrpt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxfmdbd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvqegqi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcwuupo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuxrugw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkarjhdk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqirdact.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxaypox.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rwocakev.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoyfkgo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xobpczdw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqqatea.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2knbhwdko.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jallspgj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcpvkzd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfdmksv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kagexfuo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpggdah.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuaqzuv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjovgwn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfxeqxb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2brqotusj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2usipudvw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2munqxfor.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgardsd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2puhinrea.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxchrxx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjrzrvx.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fqztmciw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2loikized.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsbzwxc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfornytr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lzikzome.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pptmlngn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrdrbkh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsjiemf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jvemjctp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zyokmgnk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2buyxpfhk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuqlegx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbyleos.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqhmgln.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hivdqnil.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxbyhhn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2yiweynpd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2czwmzgoh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcplzym.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2efbyifbj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeioelt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfedqyy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqtwyeu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnhomzv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aefuojum.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdibiws.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yplcosjx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqnbdjn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsxoyxw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jclflkou.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqmbjjh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyobvpo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nddvsrtr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edronseh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuczggw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2whlcsjdk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvdptbi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwohgcy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmnsayq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xfztkiuh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdunlds.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqhzuwz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2woxuocbt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2oixijbjn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyppjgyk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2felsxthk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jenqgkxr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wugsmwii.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2erxlqdry.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2djyuphtr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jbawxoog.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2prjngohr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnbysqa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2clsphiix.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2liugucyt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuhpsnz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkfdguy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgylprt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ufubhriq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqccpob.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2utldcuep.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzardem.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqoacij.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqmjnzq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtcplxn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuorque.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mecxzllr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2apatzwwp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hagxyyya.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rulunrlr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pntptlha.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gneuucgl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiddxtj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vstivgih.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcdjlvk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeslbkvu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fafhasga.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2koppbphd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2myfyhvbk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qptquaqd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pefxldag.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lybvifqy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsvqevr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hmehtcea.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2prgdgmpd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2akkivmsx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2teheycfx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsdktgj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gevmnaun.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2yasqzwjs.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2syothcpp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vosqzlak.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtvnsvn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2bskqghdg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2spapalcd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2swornsat.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeucakr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqudwfvn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzcsuhe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhhklkf.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsqfrwi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrmcpva.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2loymplvx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2aafulehu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfxlbum.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ynevucqs.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aykaosio.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwclayl.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wpafzdos.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2infdjfxa.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ftheyvpe.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeytfmg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2smjsyujr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2toxffpwq.html


<!-- 参考信息 -->