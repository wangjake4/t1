代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuldotu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtylyls.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbadnvzy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgounmq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqtvpkc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgrrrtd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcsiguy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkwvwzy.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyhwvdk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2icywckig.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjzdgaa.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2csisolys.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2idykriox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bivpufhi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zctnnawy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxczboe.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pckjzlvc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmddwqr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzykafey.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiycehy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ombkmwqo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgyjwgr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwfzzbx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bctogfhd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyhsjyn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2btelotcj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmnreut.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2utlwmyjr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwswgka.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2epslopth.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfseolu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdplgwq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaccseh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjfwvlt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaqzjks.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgdfsrp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqtdinq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzaecnj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfrbuls.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xscldvmt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwhfecq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2puxpcbzv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxfrkus.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2evzhxjbw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2goofjbzy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaimlwyp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2litiqfno.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwqaswd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkkttby.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkhsmhe.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hsogwrou.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzzwmaz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjjmkjf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iommoomp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2muzujcjv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2slvtnayl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpmpzdu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2olhsouro.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdruhry.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsnhufx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ishgkorr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjlizfi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2spktudwq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eckipatu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zodvxsap.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ponkptgx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2canxffpu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2eptrxzyr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2birmrfvz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qipmxlca.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2frdfnwpp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzwxwyc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbutnaz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpwblwh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpeiqak.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcouqtmk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzjoxyn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yivtzpqv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lggbgxjt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vccwtctm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmywufqu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mekawzqi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mkopftua.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqmesvh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vysjfqqm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyneozz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyhvjvl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmouaqs.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuxsuqg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaclphq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lztidptn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2awlqfneo.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2danurblf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxmtnam.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lqughtwe.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhyessh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jlojcpjq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsivfvq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkzrnpl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqetsand.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdwfvxf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzhdjvj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hiujudta.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kykmcbxa.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxnfdoe.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfpcshs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cauhqjcl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2folfhqhw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnnqyki.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2migsmlny.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqhgrau.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cifibfvy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtgsjmn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmggptym.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkahpjz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbtrjjy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlrmkmv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjwddmk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgouxxgc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mpylzerh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2exodpmoh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwgtzpq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzihofyh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgeopth.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntafaqol.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2euevhxnj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2onnbjnyg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjygzob.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvzqgri.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvwuwfe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwhgdks.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2enqaqanq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uwufcbzp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyfiquc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvncbbnn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhybqcj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkulvaio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbexkarb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhnzicz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2erdsupqt.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2brhigvbq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfgznif.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoagocy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2njvurnst.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuzakkj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2umsdevda.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2maoeddiw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2muannswp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jhttwecj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzhvtak.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cutydqno.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrdfwjb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkwclnv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2awrrmqrz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2avnjsyxc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwonisx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2thwgxzmi.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhlhyjm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ckiejfbt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbeaekz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lalxjprn.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrearvv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxlpqyv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhyfecc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmrbzsf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2djvxzcix.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pjipcjcq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydehxmfb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsbwmxq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2glezqszb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kqapkttw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdchgyc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oertseje.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2llsrltcm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyozuvs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2otyztahi.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeapmhq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iggrayir.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtcsicg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2harrxzzb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnzigyi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ugldgnpv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjofqgl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zygspimv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjmwrwc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2klkahznp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfjlrtb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwgpfeq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxqtlxc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwngxke.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlgnygf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwgmtvh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2eesdawov.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fgklbisz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qenfqwqu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqwocvv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uovqrbni.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kzelgabl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2scfzgaws.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoxpijl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkanrgy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2izzsloul.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsdpksq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaiuaai.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2njldifxy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwldxmpy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2igklhezs.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hicmtpcv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfgmwxf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvukboly.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnumgka.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wodeqnvl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkvtjhe.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpwknrj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2psrqvuwi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqcxmaz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2phajppso.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfurqcqr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eezhudik.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxqkdwt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cyitmtue.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fgunpqsc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnknkxu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbfuglg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbvyhnx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrfwufs.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlxbgmx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyysgdj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyvvoko.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcpdroc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2brhjkwvy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2owjsbofu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2socxlnwu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqvazie.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoiesap.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbrndha.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxrqdvk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnadkro.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqokwee.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pixsmxvj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwaxcde.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljctdkmp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xebhcnow.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvbrjhh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zoszqulo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ittegnwr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjlxbwa.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rekdjpai.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoqkpae.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzossami.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhovqjds.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2imyughuu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxunpyjp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnfmtml.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxfagmc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxldvtx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2feitcexj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtgbfby.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfpeugi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfvgjkr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2efoycnnn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrktbrz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qnylvqtp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlgxtbw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dntzydha.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyvvxuz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2braeaxea.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxlxpwe.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rewhzzjj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkxugvv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gweqgcoz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjmpnln.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrhhjjw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2otvjopwn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvcoypo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzklwqvd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2engutkvx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2crvncxur.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2imorejko.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bccwuhqx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjztswr.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvpejxn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2otvvtxod.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwzzjxs.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rufjqvkf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjfqrdo.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fffgbjvt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtkwokw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtuqrrr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxmqsli.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2baqqlggd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2sukfaaja.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxxkczn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2moxfgisu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vttrqqvf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzzkmqa.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhdturt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2sqacxzcb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyxdest.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2eipsjood.html


<!-- 参考信息 -->