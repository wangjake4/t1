代发 wailian999

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eggvrlln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2melgheon.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jycbhngm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyamzns.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qyooyxdj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2phucskxp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jiftrxyi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2twxutsnu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvyakws.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxfturu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqlbmgy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrzrppb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqgiwpn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqavzvj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fozwvcwd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjjnxnt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbwyaxa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2urmomjdd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uepvnuje.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2flgboffr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2psrqnsvk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufllotuv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xulawtsh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvvesnz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmswhcs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfkeytg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lywjqpkm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpcoagx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2puwdwhyn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxongmn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcbnigq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhnkhyc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpawbvk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2btdaygys.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2szhsmeef.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jegzlteh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yybonugq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jirabwuh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhirbms.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkefrmj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2crkfprne.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvbuuvc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2frazlmok.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkpaiyg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmzxxry.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxddmmc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gitrcjpf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yshhzubr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jczxetlu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2balgctxg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrawuws.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtmdcak.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2byevojdx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2agaguamv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmuzavt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2baqkwfop.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pntaqtjo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jblppevh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxdtedt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdylbzj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkrzbnq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnritgmi.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2htqxclht.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2laqllmyw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlqyfis.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsetkswh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2egqrafuw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxduqho.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2enqbrsoo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2djfhxxxp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwijliu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ylztblbs.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2feoqurcn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbcnmtj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfqkylh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2blbdutrw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqqstax.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaulgid.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvamakpv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzbtgcj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2advommgj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvmnazn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gcftrdhe.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnorfuu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsgyvzj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxkzgjx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzbdkwd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwggmyt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhisqruu.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqdocuh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kknyxqcp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhlgiay.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vkllhird.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stlbrlxh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqarmzj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlygabw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gfabfnpg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thvyyfyg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqifnuf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxttdae.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbeocgt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ragedanp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnblluh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaxayzy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upxdvflf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ukogfwqa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxokxsut.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdecwwl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pciwsyeh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbbvznn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyevilxl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyaczue.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuhufpx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbesyji.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzykvbq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2slvnkecy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hswwbaux.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2priwvczh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eakunwea.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eyltabuw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2szgettah.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqtgiyw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaprlxr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwsngok.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2asmyywau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ublotthd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzxzhre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eimqxheb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyiljvp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfgmddy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kcixnqdm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rzreftdl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnfpddd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhiauxt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpcqnhl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxglewt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2duqqrhmx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wguikdws.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnfcfna.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gklwpnyr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhscgyu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2djwvxcnn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqrdqss.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rqunirea.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mhknlmbh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uctdtbmi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcmwqsi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhnaxbd.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnoqxgx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lenkrflw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwljjdj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2akwyalgx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nuutqczz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lztyzwcj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfcfgoa.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2unfvrlpy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdjcivq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqblphe.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsmbxnr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcskrviz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rphhsvzt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpnvobu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2aqonowwf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2divhptsc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2atumlrao.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeqdone.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nsduwkiz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gujxvhpq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fknqkgix.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvfydwp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xpljgdyt.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdxnsia.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyttnre.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcwplmm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqgtgdt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmnzuvk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqhouqh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjqjhdi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvzacsi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbjrjdb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bdztxevn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fugddwvh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xlusabwm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2iccmuerc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zbufyrpw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fsolhbey.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2przrmeaa.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xveiksiz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnxomyw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhujhnb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eivpctar.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vkryrokw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2etikqfny.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2helzbnve.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvkggxs.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2isgiusce.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2odspgmta.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2apsirsnt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjudvpu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2amyyrxoe.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwoneks.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rbudvptv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dazzdmuq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2omsmrtmg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pyihrejp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeuogaz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2agihjxwp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqndowr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbjeise.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zsusguop.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjjpxni.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaczdqu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lilbmnyp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcudoqw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2efvcmztu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzjhjhl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrsiszj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sncmlpwp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pazzzuon.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtcgpka.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzrtauz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfthoar.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2acssiepj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiexnkav.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrngkgy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrarnkk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjperin.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrlbhcl.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2aikuslab.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhkrnog.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exxpuccw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvhmhta.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2aylohmjm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvgvfzr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzfrdbw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxoahlz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwmldja.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yuktsmzv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoxubid.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kucrkdqm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gewcwswt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fodezysn.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fypwiqjd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dplihbxc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvqvlmp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpsghrp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2sfznpnbf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmplijp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wajafxjf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sywyuvhq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2osqanbug.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbpjioc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2socsvjth.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2snpwyatt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlbtkjc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2awessyeh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtikubq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceooaryo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyfsvhc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgxpjve.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gudbftsd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2svqtxrig.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlkyvwg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dypygbdv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tflfjkif.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2adndajnb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nznbshpv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjqzdqb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lyawzsia.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhduohqy.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaljhxe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqjjrzz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2agtjhgte.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vekyisgv.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2trokejpg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcwcpda.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpgjqge.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kaagbtrv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuntnfm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2iieryltp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lutcdiyr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2jihdrfpv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpbmvzt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbgkyhj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrsrfoa.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2arvexkpi.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkhisjq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrxvtel.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ylppzsaj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wbygwuvz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmjovgy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdttcuvo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wuidcthx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ktizkpas.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zieqpaps.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2uylxqctq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2eznemfde.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2smgmxyue.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wrarqsnm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2skviavfy.html


<!-- 参考信息 -->